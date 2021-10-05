<template>
  <div id ="utama">
    <div id="appbar">
          <div id="bg">
                <div id ="h2"> <img alt="background" src="@/assets/bg-appbar.png"></div>
            </div>
            <div id = "akun">
                <div id="icon">
                    <div id ="user"> <img alt="iconuser" src="@/assets/icon-account.png"></div>
                </div>
                <div id = "name">
                    <div id="tech">Technical Writers </div>
                    <div id= "p1">Qomariyatul Hasanah</div> 
                </div>
            </div>
          
        <div id ="nav">
            <div id="menu">
                <div id="menuk">
                    <div id="isimenu">IOC SKK Migas</div>
                    <div id ="vectorr"> <img alt="iconuser" src="@/assets/ic-rec-tracking.png"></div>
                </div>
            </div>
        </div>
  </div>
    <div id="group">
        <div id="card1">
            <div id="table1">
            <div id="chart1"></div>
                <div id="tittle1">
                    <div id="tittle11">
                        <div id="isi11">Work Performance Order by Category</div>
                    </div>
                </div>
            </div>
           
        </div>
        <div id="card2">
             <div id="isi1">SCE</div>
        </div>
        <div id="card4">
            <div id="table4">
                <div id="chart4"></div>
                <div id="tittle4">
                    <div id="vector4"></div>
                    <div id="isi4">SCE</div>
                </div>
            </div>
        </div>
        <div id="card3">
            <div id="table3"> 
                <div id="chart3"></div>
                <div id="tittle3">
                    <div id="isi3">Gas Compressor Performance by Area</div>
                </div>
            </div>
        </div>
        <div id="card5">
            <div id="table5">
                <div id="tittle5">
                    <div id="isi5">MP SYSTEM CONDITION</div>
                </div>
            </div>
        </div>
    </div>
    <div id="kaki">
        <div id="foot">
            <div id="frame"> 
                <div id="font"> &copy; 2021 ICT PHI Region3 Policy</div> 
            </div>
        </div>
    </div>

  </div>
</template>

<script>
export default {
name : "Navbar"
}
</script>

<style>
#vectorr{
    position: static;
width: 24px;
height: 24px;
left: 38.5px;
top: 0px;

background: #FFFFFF;

/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 2px 0px;
}
#isimenu{
    position: static;
left: 0%;
right: 0%;
top: 56.52%;
bottom: 0%;

font-family: Open Sans;
font-style: normal;
font-weight: normal;
font-size: 15px;
line-height: 20px;
text-align: center;

/* Dark Gray 100 */
color: #52637D;


/* Inside Auto Layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 2px 0px;
}
#menuk{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 0px;

position: static;
width: 101px;
height: 46px;
left: 0px;
top: 0px;


/* Inside Auto Layout */
flex: none;
order: 6;
flex-grow: 0;
margin: 0px 26px;
}
#menu{
    display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;

position: absolute;
width: 101px;
height: 46px;
left: 32px;
top: 6px;
}
#isi3{
    position: static;
left: 0%;
right: 15.92%;
top: 4.17%;
bottom: 4.17%;

font-family: Open Sans;
font-style: normal;
font-weight: 600;
font-size: 16px;
line-height: 22px;

/* identical to box height */

color: #52637D;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 61px;
}
#tittle3{
    display: flex;
flex-direction: row;
justify-content: left;
align-items: center;
padding: 0px;

position: relative;
width: 534px;
height: 24px;
left: -70px;
top: 0px;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 24px 0px;
}
#chart3{
    position: static;
width: 501px;
height: 214px;
left: 16.5px;
top: 48px;


/* Inside Auto Layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 24px 0px;
}
#table3{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 0px;

position: static;
width: 534px;
height: 262px;
left: 16px;
top: 16px;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 10px 0px;
}
#chart1{
    position: static;
width: 501px;
height: 194px;
left: 16.5px;
top: 68px;


/* Inside Auto Layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 24px 0px;
}
#isi11{
    position: static;
left: 0%;
right: 15.92%;
top: 4.17%;
bottom: 4.17%;

font-family: Open Sans;
font-style: normal;
font-weight: 600;
font-size: 16px;
line-height: 22px;

/* identical to box height */

color: #52637D;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 61px;
}
#tittle11{
    display: flex;
flex-direction: row;
align-items: center;
padding: 0px;

position: relative;
width: 534px;
height: 24px;
left: -70px;
top: -20px;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 4px 0px;
}
#tittle1{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: flex-start;
padding: 0px;

position: static;
width: 534px;
height: 44px;
left: 0px;
top: 0px;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 24px 0px;
}
#table1{
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 0px;

position: static;
width: 534px;
height: 262px;
left: 16px;
top: 16px;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 10px 0px;
}
#vector4{
    position: static;
width: 24px;
height: 24px;
left: 510px;
top: 0px;


/* Inside Auto Layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 0px 61px;
}
#chart4{
    position: static;
width: 486px;
height: 361.38px;
left: 24px;
top: 48px;


/* Inside Auto Layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 24px 0px;
}
#tittle5{
display: flex;
flex-direction: row;
align-items: center;
padding: 0px 0px 0px 4px;

position: static;
width: 197px;
height: 22px;
left: 0px;
top: 0px;

/* white */
background: #FFFFFF;

/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 16px 0px;
}
#table5{
    display: flex;
flex-direction: column;
align-items: flex-start;
padding: 0px;

position: static;
width: 1132px;
height: 650px;
left: 0px;
top: 0px;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 24px 0px;
}
#isi5{
    position: static;
left: 2.03%;
right: 100%;
top: 0%;
bottom: 0%;

font-family: Open Sans;
font-style: normal;
font-weight: 600;
font-size: 16px;
line-height: 22px;

/* identical to box height */

color: #52637D;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 10px;
}
#font{
    position: static;
left: 15.38%;
right: 0%;
top: 15.63%;
bottom: 15.63%;

font-family: Roboto;
font-style: normal;
font-weight: 500;
font-size: 12px;
line-height: 14px;

/* identical to box height */

/* neutral/black 60 */
color: #747474;


/* Inside Auto Layout */
flex: none;
order: 1;
flex-grow: 0;
margin: 0px 8px;
}
#frame{
    display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 0px;

position: absolute;
width: 182px;
height: 20px;
left: 32px;
top: 20.8px;
}
#utama{
position: relative;
width: 1440px;
height: 1700px;

background: #F4F5F7;
}
#bg{
    position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;


}
#card5{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 16px 8px;

position: absolute;
width: 1148px;
height: 638px;
left: 0px;
top: 820px;

/* white */
background: #FFFFFF;
border-radius: 8px;
}
#card2{
    position: absolute;
left: 0.14%;
right: 52.56%;
top: 8.71%;
bottom: 78.65%;

background: #FFFFFF;
border-radius: 8px;
}
#card3{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 16px;

position: absolute;
width: 566px;
height: 294px;
left: 568px;
top: 458px;

/* white */
background: #FFFFFF;
border-radius: 8px;
}
#card4{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 16px;

position: absolute;
width: 515px;
height: 441.38px;
left: 0px;
top: 311px;

/* white */
background: #FFFFFF;
border-radius: 8px;
}
#card1{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 16px;

position: absolute;
width: 566px;
height: 294px;
left: 568px;
top: 118px;

/* white */
background: #FFFFFF;
border-radius: 8px;
}
#h2{
position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;
}
#group{
    
position: absolute;
width: 1148px;
height: 1370px;
left: 146px;
top: 40px;
}
#nav{
position: relative;
width: 1148px;
height: 58px;
left: 146px;
top: 58px;

background: #FFFFFF;

/* menu */
box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
border-radius: 8px;
}
#p1{
    position: static;
left: 0%;
right: 0%;
top: 0%;
bottom: 47.37%;

font-family: Open Sans;
font-style: normal;
font-weight: normal;
font-size: 15px;
line-height: 20px;
text-align: right;

color: white;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 2px 0px;
}

#user{
    position: absolute;
left: 0.69%;
right: -0.69%;
top: 0%;
bottom: 0%;
}

#appbar{
    position: absolute;
width: 1440px;
height: 82px;
left: 0px;
top: 0px;
}
#akun{
    position: absolute;
left: 82.15%;
right: 3.61%;
top: 10.73%;
bottom: 32.93%;

}
#name{
    
display: flex;
flex-direction: column;
justify-content: center;
align-items: flex-end;
padding: 0px;

position: absolute;
width: 153px;
height: 38px;
left: 3px;
top: 4px;


}

#tech{
    position: static;
left: 40.52%;
right: 0%;
top: 57.89%;
bottom: 0%;

font-family: Open Sans;
font-style: normal;
font-weight: normal;
font-size: 12px;
line-height: 16px;
text-align: right;

color: white;

flex: none;
order: 1;
flex-grow: 0;
margin: 2px 0px;
}
#icon{
position: absolute;
width: 36px;
height: 36px;
left: 175px;
top: 5px;

}

#kaki{
    position: absolute;
left: 0%;
right: 0%;
top: 96.24%;
bottom: 0%;
}

#foot{
    position: absolute;
left: 0%;
right: 0%;
top: 0%;
bottom: 0%;

/* neutral/white 100 */
background: #FFFFFF;
}

#table4{
    display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
padding: 0px;

position: static;
width: 534px;
height: 409.38px;
left: 16px;
top: 16px;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 10px 0px;
}
#isi1{
    position: absolute;
left: 7.01%;
right: 85.56%;
top: 9.88%;
bottom: 88.53%;

font-family: Open Sans;
font-style: normal;
font-weight: 600;
font-size: 20px;
line-height: 27px;

color: #52637D;
}
#tittle4{
    display: flex;
flex-direction: row;
justify-content: left;
align-items: left;
padding: 0px;

position: relative;
width: 534px;
height: 24px;
left: -30px;
top: 0px;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 24px 0px;
}
#isi4{
    position: static;
left: 0%;
right: 15.92%;
top: 4.17%;
bottom: 4.17%;

font-family: Open Sans;
font-style: normal;
font-weight: 600;
font-size: 16px;
line-height: 22px;

/* identical to box height */

color: #52637D;


/* Inside Auto Layout */
flex: none;
order: 0;
flex-grow: 0;
margin: 0px 61px;
}

</style>