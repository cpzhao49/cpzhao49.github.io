<!DOCTYPE html>
<html lang="en">    
    <head>
        <meta charset="UTF-8" />
        <title>WEB222 FINAL ASSESSMENT</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <link rel="stylesheet" href="https://raw.githubusercontent.com/cpzhao49/web222/main/style.css?token=GHSAT0AAAAAABQS7WRFX4IGKWW42YIVP2YCYSXA3VQ">
    </head>
    <script src="https://raw.githubusercontent.com/cpzhao49/web222/main/script.html?token=GHSAT0AAAAAABQS7WRFEILN75XSSBFLSKWOYSXA3FQ">
    </script>
    <body>
    <nav class="navbar">            
        <ul class="bar">            
            <li class = "navbar_left"><a href="https://ict.senecacollege.ca/course/web222?q=course/web222">WEB222</a></li>        
            <div class="navbar_right">               
                <li><a href="#Title">Top</a></li>
                <li><a href="#Contact">Contact</a></li>
            </div>           
        </ul>    
    </nav>
    <br><br><br><br><br>

    <header class="Header">
        <Center>
            <h1 id="Title" class="Title">WEB222 Final Assessment</h1>
        </Center>            
    </header><br><br><br><br><br>

    <section class = "PersonalInformation" id ="PersonalInformation">
    <div>
        <img src="https://raw.githubusercontent.com/cpzhao49/web222/main/Cat.jpeg?token=GHSAT0AAAAAABQS7WRF7HCRK6CF4MXI62YEYSXA2XQ"><br>
        <div class = "text">
            <h1 class = >Chongpu Zhao</h1><br>
            <h3 class = >A Programmer</h3><br><br>         
        </div>
        <div class="buttons">
            <button class="button1" ahref="" download></a>Resume</button>
            <button class="button2" onclick="toContact();">Contact Me</button>
        </div>
    </div>   
    </section>

    <div class="AboutMe" id="AboutMe">
        <div class ="left" >
            <p class="title"><b>Honesty Statement</b></p><br>
            <i class="Statement">I declare that my assessment is wholly my own work in accordance with Seneca Academic Policy. No part of this assessment has been copied manually or electronically from any other source (including web sites) except for the information supplied by the WEB222 instructors and / or made available in this assessment for my use. I also declare that no part of this assignment has been distributed to other students.</i>
            <br><br>
            <b>Date:</b><p id="current_date" >date</p>
            
        </div>
        <div class="right"><br>
            <p class="title"><b>Basic Information</b></p><br>
            <p><b>Name:</b>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Chongpu Zhao</p><br>
            <p><b>Course code:</b>&emsp;&emsp;&emsp;&emsp;&emsp;WEB222</p><br>
            <p><b>Instructor:</b>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Alireza Moghaddam</p><br>
            <p><b>Course section:</b>&emsp;&emsp;NFF</p><br>
        </div>
    </div><br><br><br>

    <section class="Education" >
        <div>
            <p id="title"> <b>Education</b></p>
        </div>
        <div class="left">
            <p><b>2021 - 2023(expected)</b></p>
            <p>College Diploma</p>
        </div>
        <div class="right">
            <p><b>Diploma</b></p>
            <p>At Seneca College</p>
        </div>
      
    </section>
    

    <section class="ContactMe" id="Contact" >
        <br><br>
        <div class="Title">Contact ME</div>
        <br>
         <form>  
                <div class="input">
                    <label for="input">Name</label>
                    <input type="text" class="forminput" id="name" placeholder="Enter Name" size="10">
                <br>                
                    <label for="input">Title</label>
                    <input type="text" class="forminput" id="title" placeholder="Enter title" size="10">
                 <br>                  
                    <label for="input">Email</label>
                    <input type="text" class="forminput" id="email" placeholder="Enter Email" size="10">
                <br>
                <label for="input">Address</label>
                <input type="text" class="forminput" id="address" placeholder="Enter Address" size="10">
                <br>
                <br> 
             
                    <label for="input">City</label>
                    <input type="text"class="forminput"  id="city" placeholder="Enter City" size="10">
                 <br>              
                    <label for="input">Postal Code</label>
                    <input type="text" class="forminput" id="postal" placeholder="Postal Code" size="10">              
                </div> <br>  
                <label for="input">Question</label>
                <input type="radio"class="forminput"  id="radio1"  size="10">
                 <br>  <br> 
                 <label for="input">Comment</label>
                 <input type="radio" class="forminput" id="radio2"  size="10">
                  <br>   <br> 
                  <label for="input">Hiring</label>
                  <input type="radio" class="forminput"  id="radio3"  size="10">
                   <br>  <br> 
                <textarea id="comment" class="forminput"  rows="10" cols="30" placeholder="Leave some informations that you want me to know"></textarea><br><br>                                  
            </form>
            <div class="submit">
                <button  onclick="validate()">Submit</button>  
            </div>            
    </section><br><br>   
    </body>
    
    <footer class="footer">
            <p> 2022 Chongpu Zhao</p>     
    </footer>
</html>
