# projectupdatepart2
GwG Project Update 2 - lesson 14
<! -- Trying to get this to work. will paste responsive.css code here -->
@media screen and (max-width: 400px){
body{
  display:flex;
  flex-wrap:wrap;
}
  .hero {
    order: 0;
    background-image: url("./images/dog.jpg");
    background-size: cover;
    height: auto;
  }
  .news top-news a{
    order:1;
    padding: 1.5em;
  }
  .scores {
    order:2;

  }
  .weather{
    order:3;
  }
  .recent-news{
    order:4;
  }
  .footer{
    order: 5;
  }
}


media screen and (min-width: 550px){

}

media screen and (min-width: 950px){

body {
  width: 900px;
  margin-right: auto;
  margin-left: auto;
}
}
