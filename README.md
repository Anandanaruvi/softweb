### Ex.07 Software Product Company Website

### AIM:

To develop a static company website to display the softwares and services provided by the company.

### DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 7:

Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Home Page
        </title>
        <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
        color:pink;
        font-family:'Gill sans MT';
        font-size: 40px;
        text-align:center;
    }
    img{
        
        height:250px;
        width:250;
        position:center;
    }
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
				<a href="home.html" title="Home" style="color: teal; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color:teal; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:teal; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:teal; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>ARUVI SOFTWARE DEVELOPING CENTER</h1> 
                </div><br>
                <div class="content">
                    <div class="text">
                    <marquee><b>Make your future bright by developing your skills. </b></marquee>
                    <p style="color:blue; font-family:'Tahoma'; font-size:26px;"> This is the Official Website of our Teaching center.</p>
                    </div> 
			
		     <div class="content1">Software developers are the creative force behind computer programs of all kinds.<br>They design and write the code used to build everything from operating systems to apps to video games.<br>A Software Developer designs and builds computer programs that power mobile devices, desktop computers, and even cars.<br>Software developers need to stay up-to-date on the latest advancements regarding the tools, frameworks, programming languages, and apps to achieve success.<br>You can learn from<span style="background-color:lime">ARUVI SOFTWARE DEVELOPING CENTER</span>
                         for Rs.1600 | Get free certificate. | Intenship programs. | Workshops | Hackathons | And much more...
                        <img src="/""></div> 
                    
                    <br>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by A.ARUVI</footer></div>
            </div>
        </div>
    </body>
</html>
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            People
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 2540px;
            width: 85%;
            border: 12px solid lawngreen;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
        color:black;
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
        
        }
        .content{
            border:2px solid blue;
            background-color:white;
            width:98%;
            height:2240px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
 }
        .ceoph{
            background-image: url("/static/images/w9.jpg");   
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:3px solid red;
            height:200px;
            width:200px;
            position:relative;
            left: 0px;
            margin-left:auto;
            margin-right: auto;
        }
        .ceo{
            color:black;
            position:relative;
            text-align:center;
            
            
        }
        .manph1{
            background-image: url("/static/images/w1.jpg");
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;            
        }
  .man1{
            color:PINK;
            position:relative;
            text-align:center;
            
        }
        .manph2{
            background-image: url("/static/images/w2.jpg"); 
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

            
        }
        .man2{
            color:black;
            position:center;
            text-align:center;
        }
        
  
        .amph1{
            background-image: url("/static/images/w3.jpg");  
            background-size: 250px;
            background-position-x:center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

            
        }
        .am1{
            color:black;
            position:center;
            text-align:center;
        }

        
        .amph2{
            background-image: url("/static/images/u4.png"); 
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:200px;
            width:200px;
            position:center;
            margin-left:auto;
            margin-right:auto;

}
        .am2{
            color:black;
            position:relative;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: blue; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: blue; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:blue; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:blue; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>People</h1>
                </div><br>
                <div class="content">
                    <div class="text">
<p>Board Members</p>
                    <h4><u>Chairman</u></h4>
                    </div>
                    <div class="ceoph"></div>
                    <div class="ceo"><p align="center"><b><h2> A.ARUVI </h2></b></div>
                    <br>
                    <div class="text">
                        <p><b><u>Head executives</u></b></p><br>
                    </div>
                    <div class="manph1"></div> 
                    <div class="man1"><p align="right"><b><h2>PRIYA</h2></b></p></div>
                    <div class="manph2"></div>
                    <div class="man2"><p align="left"><b><h2>MAHA</h2></b></p></div>
                    <br>
                    <div class="text"><p><b><u>Managers</u></b></p></div><br>
                    <div class="amph1"></div>
                    <div class="am1"><p align="right"><b><h2>REVATHI</h2>
                    
                   
support!<br>Hope our teaching had made you more to create a new world with TECHNOLOGY.<br> We hope that, we are helping you to develop your programming skills.</div>
                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by ARUVI</footer></div>
            </div>
        </div>
    </body>
</html>
products.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Products
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
        <style>
        .home{
            height: 1260px;
            width: 70%;
            border: 12px solid lawngreen;
            padding-left:10px;
            padding-right:10px;
            margin-left: auto;
            margin-right:auto;
            background-color:cyan;
        }
        .text{
            color:blueviolet;
            font-family:'Lucida Sans';
            font-size: 30px;
            text-align:center;
        
        }
        .content{
            border:3px solid darkblue;
            background-color: white;
            width:90%;
            height:900px;
            padding:10px;
            margin-left:auto;
            margin-right:auto;
        }
        .ph1{
            background-image: url(/static/images/p1.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
        }
        .l1{
            color: crimson;
            position:relative;
            right:320px;
            
            
        }
        .ph2{
            background-image: url(/static/images/p2.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l2{
            color: crimson;
            position:relative;
            right:320px;
        }
        .ph3{
            background-image: url(/static/images/t2.png);
            background-size: 250px;
            background-position-x: center;
            background-repeat: no-repeat;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 50px;
            
        }
        .l3{
            color:crimson;
            position:relative;
            right:330px;
        }
        .ph4{
            background-image: url(/static/images/r1.png);
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom: 796px;
            background-size: 310px;
            background-repeat: no-repeat;
            
            
        }
        .l4{
            color: crimson;
            position:relative;
            left:250px;
            bottom: 796px;
        }
    
        .ph5{
            background-image: url(/static/images/t1.png);  
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom:796px;
            background-size: 280px;
            background-repeat: no-repeat;
            
            
        }
        .l5{
            color: crimson;
            position:relative;
            left:250px;
            bottom: 796px;
        }

        .ph6{
            background-image: url(/static/images/r2.png); 
            background-position-x: center;
            border:1px solid black;
            height:150px;
            width:30%;
            position:relative;
            left: 600px;
            bottom:796px;
            background-size: 280px;
            background-repeat: no-repeat;
            
            
        }
        .l6{
            color: crimson  ;
            position:relative;
            left:250px;
            bottom: 796px;
        }
        .bot{
            text-align:center;
            font-size:larger;
            

        }

        </style>
    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color:blue; text-decoration: none;"><b>Home</a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: blue; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:blue; text-decoration: none;"><b>People</b></a>
                    </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:blue; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Products</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p>These are the programming languages that are available now</p>
                    </div>
                    <div class="ph1"></div>
                    <div class="l1"><p align="center"><b>Python program<br> Price: 2500.00</b><br><br><br><br></p></div>
                    <div class="ph2"></div>
                    <div class="l2"><p align="center"><b>Carbon<br> Price: 3000.00</b><br><br><br><br></p></div>
                    <div class="ph3"></div>
                    <div class="l3"><p align="center"><b>HTML<br> Price: 1999.00</b><br<br><br><br></p></div>
                    <div class="ph4"></div>
                    <div class="l4"><p align="center"><b>Blochchain<br> Price: 6999.00</b><br><br><br><br></p></div>
                    <div class="ph5"></div>
                    <div class="l5"><p align="center"><b>Kotlin<br> Price: 7999.00</b><br><br><br><br></p></div>
                    <div class="ph6"></div>
                    <div class="l6"><p align="center"><b>PHP<br> Price: 5999.00</b><br><br><br><br></p></div>
         
                </div>
                <div class="bot"><p>To Order Online: Call 80 60 40 2004</p></div>

                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by A.ARUVI </footer></div>
            </div>
        </div>
    </body>
</html>
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>
            Contact Us
        </title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="/static/css/styles.css">
    <style>
    .text{
    
        font-family:'Lucida Sans';
        font-size: 30px;
        text-align:center;
    }
    
    </style>

    </head>
    <body>
        <div class="home">
            <div class="header">
                <header>
                    <div class=logo></div>
                    <div class=h>
                    <a href="home.html" title="Home" style="color: blue; text-decoration: none;"><b>Home</b></a></div>
                    <div class="prod">
                        <a href="products.html" title="Products" style="color: blue; text-decoration: none;"><b>Products</b></a>
                    </div>
                    <div class="people">
                        <a href="people.html" title="People" style="color:blue; text-decoration: none;"><b>People</b></a>
 </div>
                    <div class="contact">
                        <a href="contact.html" title="Contact Us" style="color:blue; text-decoration: none;"><b>Contact Us</b></a>
                    </div>
                </header>
                <div class="title">
                    <h1>Contact Us</h1>
                </div><br>
                <div class="content">
                    <div class="text">
                    <p><b>Here are the details about us
                    <h5>Do contact us for any need</h5></b></p>
                    
                    </div>
                    <b><h2>Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                        ARAKKONAM,TamilNadu, India. 
                    </p>
                    <ul>
                        <li><b>Landline:</b> 9843127204</li>
                        <li><b>Mobile</b>: 9940262541</li>
                        <li><b>Facebook</b>: fb/ Aruvi developing</li>  
                        <li><b>Email Id:</b> Aruvi@gmail.com</li> 
                    </ul>
                    <div style="text-align: center;color:red;font-size:20px;"><b>Use our services and Make your bright Future!</b></div>

                </div>
                <div class="footer">
                <footer style="color:white">
                Copyright &copy;2023 Developed by ARUVI </footer></div> 
            </div>
        </div>
    </body>
</html>
```

### OUTPUT: 

![image](https://github.com/Anandanaruvi/softweb/assets/120443233/67f0290d-5584-4e36-8f33-3fd19a9d3356)

![image](https://github.com/Anandanaruvi/softweb/assets/120443233/b8057e7b-a6cf-4bdb-b614-20a3f391dfff)

![image](https://github.com/Anandanaruvi/softweb/assets/120443233/f3bc2047-5012-4855-9538-ae87dd5b97d7)

![image](https://github.com/Anandanaruvi/softweb/assets/120443233/6b306d3b-f826-4ba9-8d95-30e14b22c264)

### HTML VALIDATOR:

![image](https://github.com/Anandanaruvi/softweb/assets/120443233/00611ed6-501c-46c8-8160-54939a7a978a)

### RESULT:

The program for designing software company website using HTML and CSS is completed successfully.
