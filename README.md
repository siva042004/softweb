# Ex.07 Software Product Company Website
## Date:13-05-2024

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
## home.html
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Web Development Company </title>
        <style type="text/css"> 
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image:url(bg.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(81, 32, 93);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(135, 123, 14, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(144, 163, 22);
            } 
            ::placeholder {
                color: rgb(87, 18, 47);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(27, 114, 130);
                border-radius: 10px;
                background: #6fa1f8;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(144, 161, 59);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(255, 255, 255);
                background-color: #6fa1f8;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: rgb(42, 135, 34);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: rgb(28, 11, 85);
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(46, 14, 106);
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: rgb(32, 120, 50);
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid #6fa1f8;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: white;
                border-radius: 30px;
                background-color: #6fa1f8;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid #6fa1f8;
                color: #6fa1f8;
                background-color: rgb(141, 136, 46);
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color: #76127b;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>zoho</span>S<span></span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2> Web Development Company </h2>
                <br>
                <p> Welcome to zoho, the forefront of digital innovation and specialized in crafting tailored web solutions to elevate businesses to new heights in the digital sphere. </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center> Designed and Developed by SIVARAGUL.M 212221040155 </center>
    </footer>
</body>
</html>
```
## contact.html
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Page </title>
        <style type="text/css">
            * {
                margin: 0;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid rgb(23, 57, 123);
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: rgb(58, 34, 54);
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: rgb(255, 255, 255);
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid rgb(113, 104, 24);
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: rgb(64, 135, 53);
                border-radius: 30px;
                background: #6fa1f8;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: rgb(44, 28, 135);
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: rgb(83, 33, 90);
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color: #6fa1f8;
                font-size: 20px;
            }
            footer {
                background-color: #30635d;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>ZOHO</span><span></span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="person.html"> People </a></li>
                <li><a href="contact.html" class="bg-contact"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Info </h2>
                <p> <span>Address</span> :173, Avvai Salai, Gopalapuram, Chennai, Tamil Nadu-600086</p>
                <p> <span>Email</span> : vijay082005@gmail.com </p>
                <p> <span>Phone</span> : 8248040448</p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by SIVARAGUL.M 212221040155</center>
    </footer>
</body>
</html>
```
## person.html
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> people page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image:url(bg.jpg);
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-people {
                border: 1px;
                padding: 10px;
                color: rgb(115, 12, 118);
                background-color: #6fa1f8;
                border-radius: 30px;
            }
            .logo {
                color: #6fa1f8;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(50, 122, 73);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(32, 33, 104);
            } 
            ::placeholder {
                color: rgb(116, 57, 138);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(136, 125, 59);
                border-radius: 10px;
                background: #57162b;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(96, 137, 26);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(18, 49, 102);
                background-color: #1e742f;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: rgb(134, 54, 112);
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid rgb(32, 118, 132);
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: #6fa1f8;
            }
            footer {
                background-color: #2a2062;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>ZOHO</span><span></span></h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="product.html"> Products </a></li>
                <li><a href="person.html" class="bg-people"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="ragul.jpg"> </td>
                    <td> <img src="virat.jpeg"></td>
                    <td> <img src="sanji.webp"></td>
                    <td> <img src="lewis.jpg"></td>
                    <td> <img src="ronaldo.jpeg"></td>
                </tr>
                <tr align="center">
                    <th> SIVARAGUL.M</th>
                    <th> VIRAT KOHLI </th>
                    <th> SANJI </th>
                    <th> LEWIS HAMILTON </th>
                    <th> CRISTIANO RONALDO</th>                    
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                    <td> Secretary </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by SIVARAGUL.M 212221040155</center>
    </footer>
</body>
</html>
```
## product.html
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title> Product Page </title>
<style type="text/css">
    * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
    }
    .banner {
        width: 100%;
        height: 100vh;
        background-image:url(bg.jpg);
        background-size: cover;
        background-position: center;
    }
    .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    .bg-product {
        border: 1px;
        padding: 10px;
        color: rgb(127, 33, 88);
        background-color: #3f0842;
        border-radius: 30px;
    }
    .logo {
        color: #6fa1f8;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
    }
    span {
        color: white;
    }
    form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
    }
    form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: rgb(97, 15, 46);
    } 
    ::placeholder {
        color: rgb(18, 148, 47);
    }
    form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: rgb(5, 5, 104);
        border-radius: 10px;
        background: #753070;
        cursor: pointer;
    }
    .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
    }
    .navbar li a {
        text-decoration: none;
        color: rgb(255, 255, 255);
        text-transform: uppercase;
    }
    .navbar li:hover {
        border: 1px;
        padding: 10px;
        color: rgb(114, 43, 98);
        background-color: #649b86;
        transition: 0.5s; 
        cursor: pointer;
        border-radius: 30px;
    }
    .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
    }
    .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 20px;
    }
    .container .box-container .box {
        color: rgb(54, 14, 65);
        box-shadow: 0 5px 10px rgba(0,0,0,.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid rgb(150, 161, 66);
        padding: 30px 20px;
    }
    .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
    }
    .container .box-container .box h2 {
        color: #411033;
        font-size: large;
        padding: 10px 0;
    }
    .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
    }
    footer {
        background-color: #156b58;
        margin-top: auto;
    }
</style>
</head>
<body>
<div class="banner">
<br>
<div class="navbar">
    <h1 class="logo"><span>ZOHO</span><span></span></h1>
    <ul>
        <li><a href=home.html> Home </a></li>
        <li><a href="product.html" class="bg-product"> Products </a></li>
        <li><a href="person.html"> person </a></li>
        <li><a href="contact.html"> Contact </a></li>
    </ul>
    <form action="" method="get">
        <input type="text" placeholder="Enter to Search">
        <button type="submit"> Search </button>
    </form>
</div>
<center>
    <h1 > <font color = "lightgreen"> OUR PROJECTS </font> </h1>
<img src="images.png" height="500" width="800">
</center>
</div>
<footer>
<center> Designed and Developed by SIVARAGUL.M 212221040155 </center>
</footer>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2024-05-13 230239.png>)
![alt text](<Screenshot 2024-05-13 230249.png>)
![alt text](<Screenshot 2024-05-13 230254.png>)
![alt text](<Screenshot 2024-05-13 230304.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
