# semester-project-1

This is my repository for 1. semester project.

                    <p>Mon-fri: 09.00-19.00</p>
                    <p>sat-sun: 10.00-1700</p>

/_ GLOBAL _/

:root{
--light-txt_bg: #d9d9d9;
--dark-txt_bg: #2e2e2e;
--red: #C34D4D;
--blue: #006466;
--yellow: #C8B724;
--green: #5D8B52;
--amatic: amatic SC, cursive;
--poppins: poppins, sans-serif;
}

body{
display: flex;
flex-direction: column;
margin: 0 auto;
padding: 0;
box-sizing: border-box;
background: var(--light-txt_bg);
}

body h1, h2, h3{
font-family: var(--amatic)
}

body h1{
font-size: 4rem;
}

body p{
font-family: var(--poppins)
}

body a{
text-decoration: none;
}

/_ HEADER _/

header {
background: #2e2e2e;
display: flex;
flex-wrap: wrap;
align-items: center;
justify-content: space-between;
}

nav a{
color: var(--light-txt_bg);
text-decoration: none;
font-family: var(--amatic);
font-size: 2rem;
font-weight: 700;
padding: 30px;
}

nav a:hover{
text-decoration: underline;
}

nav a.active{
text-decoration: underline;
}

.logo img{
max-width: 85%;
padding: 10px 0;
}

/_ HOME _/

.hero{
display: flex;
flex-direction: column;
position: relative;
}

.mini-container-hero{
font-size: 1.1rem;
position: absolute;
display: block;
right: 0px;
top: 0px;
color: var(--light-txt_bg);
}

.red{
background-color: var(--red);
padding: 1px 30px 20px;
}

.red a{
display: block;
color: var(--light-txt_bg);
font-family: var(--poppins);
}

.red p,.green p{
font-family: var(--amatic);
font-weight: 700;
font-size: 2rem;
margin: 5px 0;
color: var(--light-txt_bg);
}

.green{
background-color: var(--green);
padding: 1px 30px 20px;
text-decoration: none;
}

.green li{
list-style-type: none;
font-family: var(--poppins)
}

.hero h1,.hero h2{
text-align: center;
color: var(--dark-txt_bg);
font-family: var(--amatic);
font-weight: 700;
padding: 10px;
margin: 10px;
}

.hero h2{
font-size: 2.5rem;
}

.info-board{
display: flex;
flex-direction: column;
align-items: center;
}

.news, .site-cards{
display: flex;
flex-wrap: wrap;
flex-direction: row;

}

.news{
color: var(--light-txt_bg);
display: flex;
justify-content: space-around;
gap: 90px;
}

.energetica-home{
background: linear-gradient( rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url(../images/home-energetica.jpg);
}

.nighttime-home{
background: linear-gradient( rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url(../images/home-nightevent.jpg);
}

.nighttime-home, .energetica-home{
background-repeat: no-repeat;
background-size: cover;
width: 590px;
height: 560px;
border-radius: 10px;
}

.random{
margin-top: 40%;
margin-left: 40%;
padding: 10px;
}

.nighttime-info{
margin-bottom: 40%;
margin-left: 40%;
padding: 10px;
}

.site-cards{
display: flex;
flex-wrap: wrap;
padding: 10px;
margin: 20px;
gap: 90px;
justify-content: space-around;
}

.simple-container{
display: flex;
width: 250px;
height: 250px;
border-radius: 10px;
}
.about-home{
background: linear-gradient( rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url(../images/home-explore.jpg);
}

.about-home a{
margin-top: 75%;
margin-left: 10%;
color: var(--yellow);
font-family: var(--amatic);
font-size: 2.3rem;
font-weight: 700;
}

.exhibitions-home{
background: linear-gradient( rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url(../images/home-exhibitions.jpg);
}

.exhibitions-home a{
margin-top: 15%;
margin-left: 40%;
color: var(--light-txt_bg);
font-family: var(--amatic);
font-size: 2.3rem;
font-weight: 700;
}

.events-home{
background: linear-gradient( rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url(../images/home-events.jpg);
}

.events-home a{
margin-top: 7%;
margin-left: 60%;
color: var(--red);
font-family: var(--amatic);
font-size: 2.3rem;
font-weight: 700;
}

.visit-home{
background: linear-gradient( rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url(../images/home-visit.jpg);
}

.visit-home a{
margin-top: 15%;
margin-left: 40%;
color: var(--light-txt_bg);
font-family: var(--amatic);
font-size: 2.3rem;
font-weight: 700;
}

.icon-chain{
display: flex;
align-items: center;
justify-content: center;
padding: 10px;
}

.rising-stars{
display: flex;
flex-wrap: wrap;
justify-content: center;
text-align: end;
background: url(../images/home-star-club.jpg);
background-repeat: no-repeat;
background-size: cover;
}

.rising-stars a h2{
color: var(--yellow);
font-family: var(--amatic);
font-size: 3rem;
font-weight: 700;  
}

.rising-stars a p{
color: var(--light-txt_bg);
}
