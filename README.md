@import 'utilities.css';
:root{
--primary: rgb(29, 221, 189);
--bgDark: rgb(12, 12, 12);
--white: rgb(250, 250, 250);
--secondary: rgb(0, 59, 50);
--bgLight: rgb(190, 181, 181);
}
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    -webkit-font-smoothing: antialiased;
}
header{
background-color: var(--bgDark);
clip-path: polygon(0 0, 100% 0, 100% 100%, 73% 94%, 0 100%);
}
header nav .left a{
color: var(--white);
text-decoration: none;
margin-right: 2rem;
text-transform: uppercase;
transition: all .2s ease;
}
header nav .left a:hover{
color: var(--primary);
}
header nav {
padding: 2rem 0;
}
header nav .logo{
margin-right: 3rem;
}
body{
font-family: 'Poppins', sans-serif;
}
.container{
max-width: 1152px;
padding: 0 15px;
margin: 0 auto;
}
.hero{
padding-top: 2rem;
padding-bottom: 3rem;
}
.hero .left img{
width: 400px;
}
.hero .right {
color: var(--white);
margin-top: -7rem;
}
.hero .right h6{
font-size: 1.6rem;
color: var(--primary);
margin-bottom: 0.5rem;
}
.hero .right h1{
font-size: 4rem;
font-weight: 100;
line-height: 1.2;
margin-bottom: 2rem;
}
.hero .right h1 span{
color: var(--primary);
}
.hero .right p{
line-height: 1.9;
margin-bottom: 2rem;
}
.flex{
display: flex;
}
.items-centre{
align-items: center;
}
.justify-between{
justify-content: space-between;
}
.justify-center{
justify-content: center;
}
.justify-right{
justify-content: right;
}
.btn{
padding: 0.6rem 2rem;
font-size: 1rem;
font-weight: 600;
border: 2px solid transparent;
outline: none;
cursor: pointer;
text-transform: uppercase;
transition: all .2s ease;
}
.btn-primary{
background-color: var(--primary);
color: var(--secondary);
margin-top: -15rem;
}
.btn-primary:hover{
background: transparent;
border-color: var(--primary);
color: var(--primary);
}
.flex-1{
flex: 1;
}
.btn-secondary{
background: transparent;
color: var(--primary);
border-color: var(--primary);
}
.btn-secondary:hover{
background: var(--primary);
color: var(--secondary);
}
section{
padding: 6rem;
}
section.about h1{
margin-bottom: 1rem;
font-size: 1.6rem;
font-weight: 600;
}
section.about h1 span{
color: var(--primary);
}
section.about h3{
font-size: 1rem;
margin-bottom: 1rem;
font-weight: 600;
}
section.about p{
font-family: 'Lato', sans-serif;
color: var(--secondary);
line-height: 1.9rem;
margin-bottom: 2rem;
}
section.about .socials{
display: flex;
}
section.about .socials a{
display: flex;
align-items: center;
justify-content: center;
width: 35px;
margin-right: 0.8rem;
border-radius: 50%;
}
section.about .socials a:hover{
background: var(--primary);
}
section.services{
background: rgb(17, 17, 17)
}
.services-head{
color: rgb(10, 9, 9);
text-align: center;
margin-bottom: 1rem;
line-height: 0.5rem;
color: var(--primary);
}
.services-head + p{
color: var(--white);
font-family: 'Lato', sans-serif;
margin-bottom: 1rem;
text-align: center;
margin-bottom: 6rem;
font-weight: 400;
}
.card img{
width: 50px;
background:white;
}
section.services .card-grid{
display: grid;
grid-template-columns: repeat(3,1fr);
column-gap: 2rem;
}
section.services .card-grid .card{
background: var(--white);
padding: 3rem 2rem;
position: relative;
text-align: center;
transition: all .2s ease;
}
section.services .card-grid .card img{
position: absolute;
top: -1.5rem;
left: 50%;
transform: translateX(-50%);
color: var();
}
section.services .card-grid .card h2{
font-weight: 600;
font-size: 1.2rem;
margin-bottom: 0.5rem;
}
section.services .card-grid .card p{
font-family: 'Lato', sans-serif;
color: var(--seconday);
line-height: 1.6;
}
section.services .card-grid .card:hover{
background: var(--primary);
}
section.services .card-grid .card:hover h2{
color: var(--white);
}
section.services .card-grid .card:hover p{
color: var(--white);
}
