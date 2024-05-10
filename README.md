# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

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
## HOME.html
'''
    <html>
    
    <title>ADOBE</title>
    <style>
        body{
            background:url(bg.jpg);
            background-size: cover;
            
        }
    
        h1{
            color: blue;
        }
        h2{
            color: red;
        }
        h3{
            color:blue;
            align:center;
        }
    
    /* the main window options*/
    .styled form {
        margin-top: 20px;
                display: flex;
                justify-content: space-between;
            }
            .styled [type="button"] {
                padding: 10px 20px; /* button size */
                background-color:blue; /* initial background color */
                color: #ffffff; /*initial text color */
                border: none;
                transition: background-color 0.3s, color 0.3s; /*smooth transition */
            }
            .styled [type="button"]:hover {
                background-color:purple; /*background color on hover */
                color:aliceblue; /*text color on hover */
            }
            .styled [type="submit"] {
                border-radius: 10px;
                padding: 5px 10px; /* button size */
                background-color:aqua; /* initial background color */
                color: #ffffff; /*initial text color */
                border: none;
                transition: background-color 0.3s, color 0.3s; /*smooth transition */
            }
            .styled [type="submit"]:hover {
                background-color:purple; /*background color on hover */
                color:#ffffff; /*text color on hover */
            }
            .styled [type="text"] {
                margin-left: 500px;
                transition: background-color 0.3s; 
                background-color:paleturquoise;
            }
            .styled input[type="text"]:focus {
        /* Change background color when input is focused */
        background-color:rgb(224, 127, 224); /* Adjust the color as needed */
    }
    
    .login{
        margin-top: -100;
        margin-left: 1100;
        margin-right: 100;    
        background:url(123.jpg);
    
        scroll-padding-left: 5px;
        border:2px solid white;
    }
    .login input[type="button"] {
        padding: 10px 20px; /*  button size */
        background-color:violet;
        color: #ffffff;
        border: none;
        cursor: pointer;
        transition: background-color 0.3s, color 0.3s;
    }
    .login input[type="button"]:hover {
        color:#000;
        background-color:rgb(204, 32, 204);
    }
    .login input[type="submit"]{
        padding: 10px 15px; /*  button size */
        background-color:#4234db;
        color: #ffffff;
        border-radius: 10px;
        cursor: pointer;
        transition: background-color 0.3s, color 0.3s;
    }
    .login input[type="submit"]:hover {
        color:#000;
        background-color:chocolate;
    }
    .login input[type="text"] { 
        padding: 10px; /* Add padding for better appearance */
        transition: background-color 0.3s; /* Add transition for a smooth effect */
            /* Set initial background color */
            background-color: #ffffff;
    }
    .login input[type="text"]:focus {
        /* Change background color when input is focused */
        background-color:blue; /* Adjust the color as needed */
    }
    .join{
        padding: 10px 20px; /*  button size */
        background-color: violet;
        color: #ffffff;
        border: none;
        cursor: pointer;
        transition: background-color 0.3s;
    }
    .join:hover {
        color: blue;
        background-color: red;
    }
    </style>
    <body >
        <form class="styled ">
            <div class=>
                <a href="ex 1.html">
                    <input type="button" value="HOME">
                </a>
                <a href="ex 2.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
    
                <a href="ex 3.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="ex 4.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="ex 5.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
    
        <h1>WELCOME TO ADOBE</h1>
        <h2>Empowering Creativity, Enabling Innovation</h2>
        <h2>PRODUCTS</h2>
        <a href="sign.html">
            <input type="button" value="JOIN US" class="join">
        </a>  
        
        <h3>"Innovation Beyond Imagery, Powered by Adobe"</h3>
    
             <center>
            <div class="login">
                <div class="login-box">
                <p style="color: rgb(204, 32, 204);">DONT HAVE AN ACCOUNT</p>
        <a href="sign.html">
                        <input type="button" value="SIGN IN"><br><br>
                    </a>  
                    <p style="color: blueviolet;">LOGIN</p>
                    <input type="text" value="Username or email" ><br><br>
                    <input type="text" value="Password"><br><br>
                    <a href="products.html">
                        <input type="submit" value="SUBMIT"><br><br>
                    </a>  
                </div>
                </div>
            </center>
        
        </body>
        </html>

'''
## Products.hml
    '''
    <html>
        <title>our products</title>
        <style>  
        body{
            background:url(bg.jpg);
            background-size:contain;
        } 
        h1{
            color:purple;
        }  
        .styled form {
                margin-top: 20px;
                display: flex;
                justify-content: space-between;
            }
            .styled [type="button"] {
                padding: 10px 20px; /* button size */
                background-color:cyan; /* initial background color */
                color: #ffffff; /*initial text color */
                border: none;
                transition: background-color 0.3s, color 0.3s; /*smooth transition */
            }
            .styled [type="button"]:hover {
                background-color:pink; /*background color on hover */
                color:pink; /*text color on hover */
            }
            .styled [type="submit"] {
                border-radius: 10px;
                padding: 5px 10px; /* button size */
                background-color:green; /* initial background color */
                color: #ffffff; /*initial text color */
                border: none;
                transition: background-color 0.3s, color 0.3s; /*smooth transition */
            }
            .styled [type="submit"]:hover {
                background-color:darkorange; /*background color on hover */
                color:#ffffff; /*text color on hover */
            }
            .styled [type="text"] {
                margin-left: 500px;
                transition: background-color 0.3s; 
                background-color:palevioletred;
            }
            .styled input[type="text"]:focus {
        /* Change background color when input is focused */
        background-color:rgb(224, 127, 224); /* Adjust the color as needed */
    }
    </style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="ex 1.html">
                    <input type="button" value="HOME">
                </a>
                <a href="ex 2.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
    
                <a href="ex 3.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="ex 4.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="ex 5.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PRESTIGEOUS PROJECTS</h1>
        <img src="products.jpg" height="500" width="800">
     </center>
        </body>
        
    </html>
'''
## ABOUT.html
'''

        <html>
        <title>about us</title>
        <style>
            p{
                color: whitesmoke;
            }
            body{
                background:url(bg.jpg);
                background-size: cover;
            }
            .styled form {
                    margin-top: 20px;
                    display: flex;
                    justify-content: space-between;
                }
                .styled [type="button"] {
                    padding: 10px 20px; /* button size */
                    background-color: #3498db; /* initial background color */
                    color: #ffffff; /*initial text color */
                    border: none;
                    transition: background-color 0.3s, color 0.3s; /*smooth transition */
                }
                .styled [type="button"]:hover {
                    background-color:purple; /*background color on hover */
                    color:aliceblue; /*text color on hover */
                }
                .styled [type="submit"] {
                    border-radius: 10px;
                    padding: 5px 10px; /* button size */
                    background-color: black; /* initial background color */
                    color: #ffffff; /*initial text color */
                    border: none;
                    transition: background-color 0.3s, color 0.3s; /*smooth transition */
                }
                .styled [type="submit"]:hover {
                    background-color:purple; /*background color on hover */
                    color:#ffffff; /*text color on hover */
                }
                .styled [type="text"] {
                    margin-left: 500px;
                    transition: background-color 0.3s; 
                    background-color:cyan;
                }
                .styled input[type="text"]:focus {
            /* Change background color when input is focused */
            background-color:rgb(224, 127, 224); /* Adjust the color as needed */
        }
        .photos{
            display:flex;
            justify-content: space-around;
            margin-top: 200px;
        }
        .names{
            display:flex;
            justify-content: space-around;
        
        }
        .position {
            display: flex;
            justify-content: space-around;
            margin-left: 10px;
            border-image:5px;
            border-image: peach;
        }
        
        </style>
        <body>
            <form class="styled ">
                <div class=>
                    <a href="ex 1.html">
                        <input type="button" value="HOME">
                    </a>
                    <a href="ex 2.html">
                        <input type="button" value="OUR PRODUCTS">
                    </a>
        
                    <a href="ex 3.html">
                        <input type="button" value="ABOUT US">
                    </a>
                    <a href="ex 4.html">
                        <input type="button" value="SIGN IN">
                    </a>
                    <a href="ex 5.html">
                        <input type="button" value="CONTACT">
                    </a>  
                    <input type="text">
                    <input type="submit"value="SEARCH">  
                </div>
            </form>
            <div class="photos">
            <img src="kamalesh2.jpeg" height="200" width="180">
            <img src="rakc2.jpg" height="200" width="200">
            <img src="kiran.jpg" height="200" width="200">
            <img src="Daisy .jpg" height="200" width="200">
            <img src="kavs.jpg" height="200" width="200">
            <img src="PRADEEP.jpg" height="200" width="200">
        </div>
        <div CLASS="names">
            <P>KAMALESH</P>    
            <P style="margin-left:-20;">RAKSHITHA</P>    
            <P>KIRAN</P>    
            <P>DAISY</P>    
            <P>KAVIYA</P>    
            <P>PRADEEP</P>       
        </div>
        <DIV class="position">
            <p>[Founder] </p>
            <p style="margin-left:40;">[CEO]</p>
            <p style="margin-left:60;">[Founder] </p>
            <p>[Co-CEO] </p>
            <p>[Director]</p>
            <p>[Co-Director]</p>
        
        </DIV>
        0</body>
        </html>

'''
## SIIGN.HTML
'''

    <!DOCTYPE html>
    <html>
    <head>
        <title>Sign up</title>
        <style>
            body {
                background:url(bg.jpg);
                background-size: cover;
                color: purple;
                font-family: Arial, sans-serif;
            }
    
            .form {
            margin: 0 auto;
            width: 300px;
            padding: 20px;
        }

        label {
            color: brown;
        }

        .purpose {
            color: green;
        }

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #3498db;
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: blue;
            background-color: #4234db;
        }
        .styled form {
            margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:aliceblue; /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #ffffff; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#ffffff; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:plum;
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(224, 127, 224); /* Adjust the color as needed */
    }
    .text{
        transition: background-color 0.3s, color 0.3s;
    
    }
    .text :focus{
        background-color:purple;  
    }
    .full{
        background:url(BGI.png);
        padding: 10px;
        border:4px double white;
    }
        </style>
    </head>
    <body>
        <form class="styled ">
            <div class=>
                <a href="ex 1.html">
                    <input type="button" value="HOME">
                </a>
                <a href="ex 2.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>

            <a href="ex 3.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="ex 4.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="ex 5.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="form">
        <p align="center">JOIN THE GROUP OF ADOBE</p>
        <p align="center">DON'T HAVE AN ACCOUNT YET?</p>
        <div class="full">
        <div class="text">
           
        <label>Unique Username</label>
        <input type="text" value="username"><br><br>
        <label>Email</label>
        <input type="email" value="email"><br><br>
        </div>
        <label>DOB</label>
        <input type="date"><br><br>
        <label>Gender</label><br>
        <div class="purpose">
            <input type="radio" name="gender">Male<br>
            <input type="radio" name="gender">Female<br><br>
        </div>
        <label>Purpose</label><br>
        <div class="purpose">
            <input type="radio" name="purpose">Study<br>
            <input type="radio" name="purpose">Work<br>
            <input type="radio" name="purpose">Partnership<br><br>
        </div>
        <label>Click the checkbox to prove you are human</label>
        <input type="checkbox"><br><br>
        <input type="submit" value="CREATE ACCOUNT" class="buttons">
        <input type="submit" value="DOWNLOAD SOFTWARE"class="buttons">
    
    </div>
    </div>
    </body>
    </html>
'''
## CONTACT.html:
'''

    <!DOCTYPE html>
    <html>
    <head>
    <title>Contact us</title>
    <style>
        b{
            color:cyan
        }
        p {
            color: cyan;
        }
    
        body {
            background:url(bg.jpg);
        }
    
        .yourinfo {
            background:url(bg.jpg);
                border:5px solid green;
                margin-right: 800px ;
                
                margin-top: 200px; /* Adjusted margin-top */
                padding: 10px; /* Added padding for better spacing */
            }
            .yourinfo input[type="text"] {
                width: 500px;
                transition: background-color 0.3s; 
            }
            .yourinfo input[type="text"]:focus {
        /* Change background color when input is focused */
        background-color: #2278c3; /* Adjust the color as needed */
    }
    
            .buttons {
                margin-top: 20px;
                padding: 10px 20px;
                background-color: #3498db;
                color: #ffffff;
                border: none;
                cursor: pointer;
                transition: background-color 0.3s, color 0.3s;
            }
    
            .buttons:hover {
                color: red;
                background-color: #4234db;
            }
            .styled form {
                display: flex;
                justify-content: space-evenly;
            }
            .styled form {
                margin-top: 20px;
                display: flex;
                justify-content: space-between;
            }
            .styled [type="button"] {
                padding: 10px 20px; /* button size */
                background-color: blueviolet; /* initial background color */
                color: #ffffff; /*initial text color */
                border: none;
                transition: background-color 0.3s, color 0.3s; /*smooth transition */
            }
            .styled [type="button"]:hover {
                background-color:purple; /*background color on hover */
                color:aliceblue; /*text color on hover */
            }
            .styled [type="submit"] {
                border-radius: 10px;
                padding: 5px 10px; /* button size */
                background-color: palevioletred; /* initial background color */
                color: #ffffff; /*initial text color */
                border: none;
                transition: background-color 0.3s, color 0.3s; /*smooth transition */
            }
            .styled [type="submit"]:hover {
                background-color:purple; /*background color on hover */
                color:#ffffff; /*text color on hover */
            }
            .styled [type="text"] {
                margin-left: 500px;
                transition: background-color 0.3s; 
                background-color:blue;
            }
            .styled input[type="text"]:focus {
        /* Change background color when input is focused */
        background-color:rgb(224, 127, 224); /* Adjust the color as needed */
    }
        
    .company{
    
    margin-left: 900px;
    margin-top: -330px;
    background:url(BGI.png);
    
    scroll-padding-left: 5px;
    border:2px solid white;
    }
    .message textarea {
            background-color: white; /* Set the default background color */
            color:plum; /* Set the default text color */
        }
    
        /* Styles for the text area when it is in focus */
    .message    textarea:focus {
            background-color: blue; /* Set the background color when in focus */
            color: white; /* Set the text color when in focus */
        }
        </style>
    </head>
    <body>
        <form class="styled">
            <div class=>
                <a href="ex 1.html">
                    <input type="button" value="HOME">
                </a>
                <a href="ex 2.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>

            <a href="ex 3.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="ex 4.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="ex 5.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="yourinfo">
        <center>
        <p>Contact Information</p>
        <div>            
            <input type="text" maxlength="100" placeholder="Your Name"><br><br>
            <input type="text" maxlength="100" placeholder="Your Email"><br><br>
            <div class="message">
            <textarea rows="5" cols="65" placeholder="Your Message"></textarea><br><br>
        </div>
            <input type="button" value="SUBMIT" class="buttons">
        
        </center>
        </div>
    </div>
    <div class="company">
        <center>
        <h3 style="color:plum;">COMPANY CONTACT INFORMATION</h3>
       <p> <b >Address</b></p>
        <p >13 ANNA STREET</p>
        <p >, ANNA NAGAR</p>
        <p >TAMIL NADU-600001</p>
        <b >Email:</b>
        <p >kdsis@gmail.com</p>
        <b >Phone</b>
        <p >9600141495</p>
    </center>
    </div>
    </body>
    
    </html>
'''


## OUTPUT:
![Screenshot 2024-05-10 132104](https://github.com/sakamalesh/softweb/assets/149148235/73e2a6f8-5dbf-4cb5-9821-e8ad49f2bd75)
![Screenshot 2024-05-10 132122](https://github.com/sakamalesh/softweb/assets/149148235/8937fe60-222c-423b-b86b-11b8d96e2d0f)
![Screenshot 2024-05-10 132147](https://github.com/sakamalesh/softweb/assets/149148235/36a1c1c6-c65d-4a40-8ba2-9ceb1ea21eec)
![Screenshot 2024-05-10 132158](https://github.com/sakamalesh/softweb/assets/149148235/3b6a5923-7bf5-4ed5-b6b9-05fcb950e903)
![Screenshot 2024-05-10 132217](https://github.com/sakamalesh/softweb/assets/149148235/dc86a339-165e-40d8-a23c-97e8a37a3040)
![Screenshot 2024-05-10 132050](https://github.com/sakamalesh/softweb/assets/149148235/2f375ed5-da08-475d-a631-cb61f2935bbb)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
