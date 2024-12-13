* {
    box-sizing: border-box;
  }
  
  :root{
  --bg-first-color:grey;
  --bg-second-color: white; 

  }
h1{
    color: #463F3A;
}
  
  h1{
    text-align: center;
    text-shadow: 4px 2px 5px #F7934C;
    text-shadow: -3px -3px -10px blue;
    font-family:RacingSansOne-Regular.ttf;
    font-size: 2.5rem
  }
  #rosh a{
    text-decoration: none;
    color: #47370a;
    display: contents;
  
  }
  h3{
  text-align: center;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  }
  p{
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;
  color: #463F3A;
  }
  .navbar ul{
    list-style-type: none;
    background-color: #1F1300;
    padding: 1px;
    margin: 0;
    overflow: hidden;
    font-size: larger;
    display: flex;
    flex-direction:row;
    justify-content: space-around;
    
    
  }
  .navbar a{
    color: #81d2dd;
    text-decoration: none;
    padding: 15px;
    display: block;
    text-align: center;
    font-size: 1.25rem;
  }
  .navbar a:hover{
    background-color: #fafafa;
    margin: 0;
  }
  .navbar li{
    float: left;
  }
  aside {
    width: 30%;
    float: left;
    padding: 10px;
  }
  section {
    width: 30%;
    float: left;
    padding: 10px;
  }
  article {
    width: 40%;
    float: left;
    padding: 10px;
  }
  footer {
    clear: both;
    display: block;
    padding: 15px;
    background-color: #bb924f;
    margin: 0;
  }
  small {
    font-size: 1rem;
  }
  .icon {
    background-color: #bb924f;
    text-align: center;
    margin: 0;
    animation-name: shrink;
    animation-duration: 2s;
  }
  .fa-solid.fa-filter.fa-2x {
    color: #eeb823;
  }
  .fa-solid.fa-filter.fa-2x:hover{
    color: #f7d988;
  }
  #header {
    width: 100%;
    height: 100px;
    font-size: 5em;
    animation-name: glow;
    animation-duration: 3s;
    padding: 3px;
    background-color: #bb924f;
    text-align: center;
  }
  #header:hover {
    animation-name:glow;
    animation-duration: 2s;
    animation-iteration-count: infinite;
  
  }
  @keyframes glow {
    50%{box-shadow:0 0 50px rgb(233, 191, 4)}
  }
  @keyframes shrink {
    50%{transform: scale(1.5,1.5)}
  }
  @font-face {
    src: url(fonts/RacingSansOne-Regular.ttf);
  }
  







'
  
  