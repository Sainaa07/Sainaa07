- 👋 Hi, I’m @Sainaa07
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Sainaa07/Sainaa07 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css" integrity="sha512-YWzhKL2whUzgiheMoBFwW8CKV4qpHQAEuvilg9FAn5VJUDwKZZxkJNuGM4XkWuk94WCrrwslk8yWNGmY1EduTA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
        <title>Webjunto</title>
    <body>
       <header > <nav id="logo"><img src="logo-webjunto (1).png"alt="WebJunto" height="50px" 
          width="200px"> </nav>
             <nav id="navbar">
                 <div class="container">
             <h1 class="hello"> Hello , world</h1>
             <p> Welcome to Bootstrap v3.3.7. check out this awesome jumbotron</p>
             <button class="read-btn">Learn more</button>
            </div> </nav>
       </header>
       <section>
           <div class="contain">
               <div id="left">
        <h1 >Heading goes here</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <iframe width="1000" height="600" src="https://www.youtube.com/embed/jCU5C4SrIlI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        <div class="alert">
            <span class="fas fa-exclamation-circle"></span>
            <span class="msg">Whoa! This is a super important alert!</span>
        </div>
     </div>
       <div id="right">
        <button class="read-btn2">Messages</button>
        <div class="alert2">
            <span class="msg">Welcome Candidate!</span>     </div>
            <p>You are a Starfleet Academy candidate. Greet the Captain in a respectful/fashion. </p>
            <input type="text" class="form-control" placeholder="Input your greeting...">
   
       

    </div>
     </section>
     <div class="clr"></div>
     <footer id="main-footer">
         <p>2017 All Rights Reversed, SomeCompany.</p>
         </footer>
     
    </body>
    </head>
</html>
* {margin:0; padding:0; box-sizing:border-box;}
@import url('https://fonts.googleapis.com/css2?family=Lato&display=swap');
   body{font-family: 'lato'sans-serif; }
#navbar{ background:#13124F; color:white;
    padding:40px 20px 60px 50px; }
    .container {
       
        max-width:1100px;
        
    }
    #logo{ background:#1B1B6C; z-index:1;
    padding-left:30px;}
 h1{font-size:3em; }
 p{margin:10px 0;padding-bottom:15px; font-family:'lato',sans-serif}
.read-btn{ background-color: #f61067;
padding:5px 14px;  color:white; font-size: 18px; cursor:pointer; border:none;}
#left {float:left; width:67%;}
#left h1 {padding-top:15px; padding-left: 40px; 
 border-bottom:#e4e4e6 solid 1.5px;
overflow: hidden;}
#left p {text-align:left;
padding-left:40px ;padding-top:10px;padding-bottom:20px;}
#right {float:right; width:30%}
#left iframe {padding-left:300px;}

    .clr {clear:both;}
    #main-footer{background:#352BA5; 
     padding:20px 0 10px 20px; color:white}
     .alert{display:block;
    background:#9090A5;margin:30px 0 20px 40px;
    padding-top:20px;padding-left:20px;padding-bottom:20px;border-radius:4px;}
     .read-btn2 { background-color: #f61067;
        padding:8px 150px; margin:20px 5px 10px 10px;
        color:white; font-size: 18px; cursor:pointer; border:none;}
       .msg
        { background-color: #9090a5;
        
            font-size: 20px;
            padding:20px; margin:20px 70px 10px 10px;
              border-radius:4px;
            }
           .alert2 {background:}
        
        
        .can2
        {
            background-color: #13124F;
            height: 24%;
            color:white;
            width: 21.3%;
            padding:10px;
        }
        
        .form-control
        {
            position: absolute;
            background-color: #352ba5;
            color: gray;
            height: 25px;
            width: 19.3%;
            font-size: 18px;
        }
        .send
        {
            position: absolute;
            background-color: #f61067;
            text-decoration: none;
            color:white;
            width: 19.5%;
            height: 30px;
            font-size: 20px;
        
        }
        .send:hover
        {
            background-color: #2AD392
        }
        .id
        {
            position: absolute;
            top: 77%;
            left: 65%;
            color: white;
            background-color: #352ba5;
            width: 21.3%;
            height: 4%;
           padding-top: 5px;
            font-size: 14px;
             text-align:center;}
            
