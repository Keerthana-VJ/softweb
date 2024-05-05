# Ex.07 Software Product Company Website
## Date:05.04.2024

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
```
home.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>NexGen</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(237, 214, 9);
            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(240, 35, 7);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(64, 11, 210);
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
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgb(222, 33, 134);
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
                color:rgb(55, 9, 237);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:rgba(180, 16, 134, 0.49);
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
                color: rgb(140, 6, 86);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
	    .text h3 {
                color: rgb(16, 65, 225);
                font-weight: 800;
                font-size: 22px;
                letter-spacing: 3px;
            }
	
            .text p {
                color: rgb(244, 10, 119);
                text-transform: capitalize;
                font-size: 17px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
	
            }
                footer {
                background-color: rgb(9, 237, 108);
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>NexGen Software Tech</span></h1>
            <ul>
                <li><a href="Home.html"> Home </a></li>
                <li><a href="Product.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2><span> SOFTWARE DEVELOPMENT </span></h2>
                <br>
		<h3></h3>
		<br>
                <p>"NextGen Software Company is a dynamic leader in the tech industry, dedicated to pushing the boundaries of innovation and delivering cutting-edge solutions to meet the evolving needs of businesses worldwide. With a focus on customer-centricity and a commitment to excellence, NextGen specializes in developing bespoke software solutions tailored to optimize efficiency, drive growth, and empower digital transformation. Leveraging a talented team of experts and state-of-the-art technologies, NextGen is poised to shape the future of technology and revolutionize industries across the globe."</p>
                <br>
                
            </div>
        </div>  
    </div>                                                          
    <footer>
        <center> Copyright@2024 Developed by KEERTHANA V(212223220045)</center>
    </footer>
</body>
</html>

product.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>NexGen</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(115, 54, 171);
            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(116, 101, 13);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(41, 153, 168);
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
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgba(255, 217, 0, 0.823);
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
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:rgb(160, 124, 127);
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
                color: white;
                box-shadow: 0 5px 10px rgba(0,0,0,.2);
                border-radius: 10px;
                background: transparent;
                border: 1px solid white;
                padding: 10px 5px;
            }
            .container .box-container .box img {
                height: 50px;
                border-radius: 20px;
            }
            .container .box-container .box h3 {
                color: gold;
                font-size: larger;
                padding: 10px 0;
            }
            .container .box-container .box p {
                color: white;
                font-size: larger;
                line-height: 1.5;
            }
            footer {
                background-color: rgb(240, 198, 11);
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>  NexGen Software Tech</span></h1>
            <ul>
                <li><a href="Home.html"> Home </a></li>
                <li><a href="Product.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="container">
            <div class="box-container">
                <div class="box">
                    <img src="python.png" alt="">
                    <h3>PYTHON</h3>
                    <p> Expected to continue its dominance due to its simplicity, versatility, and extensive library ecosystem. Python's applications in AI, data science, and web development will likely see sustained growth.</p>
                </div>

                <div class="box">
                    <img src="c.png" alt="">
                    <h3>C</h3>
                    <p> C programming is a powerful and versatile language known for its efficiency, flexibility, and close-to-hardware capabilities. It is widely used in system programming, embedded systems, and low-level development. </p>
                </div>

                <div class="box">
                    <img src="c++.png"alt="">
                    <h3>C++</h3>
                    <p> Expected to maintain their significance in performance-critical applications like gaming, system programming, and embedded systems, where low-level control and efficiency are paramount.</p>
                </div>
               
                <div class="box">
                    <img src="java.png" alt="">
                    <h3>JAVA</h3>
                    <p> Despite its age, Java remains a staple in enterprise applications, especially in large-scale systems and Android app development. The language's robustness and cross-platform compatibility contribute to its enduring relevance.</p>
                </div>
                <div class="box">
                    <img src="sql.jpg" alt="">
                    <h3>SQL</h3>
                    <p> SQL (Structured Query Language) is a powerful domain-specific language used for managing relational databases. It allows users to perform various operations such as querying data, inserting, updating, and deleting records, creating and modifying database structures (tables, indexes, views), and defining permissions.</p>
                </div>
 
            </div>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by KEERTHANA V(212223220045) </center>
    </footer>
</body>
</html>

persons.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>NexGen</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(67, 6, 249);
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
                color:gold;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: yellow;
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
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:gold;
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
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:gold;
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
                color: white;
                position: relative;
                left: 200px;
            }
            .image table img {
                height: 250px;
                width: 250px;
                border: 2px solid yellow;
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color: yellow;
            }
            footer {
                background-color: gold;
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span>NexGen Software Tech</h1>
            <ul>
                <li><a href="home.html"> Home </a></li>
                <li><a href="Product.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div> 
        <div class="image">
            <table cellspacing="20"> 
                <tr align="center">
                    <td> <img src="person.jpeg"> </td>
                    <td> <img src="venkatesh.jpeg"> </td>
                    <td> <img src="thamarai.jpeg"> </td>
                    <td> <img src="jayanthi.jpeg"> </td>
                    
                </tr>
                <tr align="center">
                    <th> Keerthana</th>
                    <th>Venkateswaran</th>
                    <th>Thamarai</th>
                    <th>Jayanthi</th>
                   
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> Co-Founder </td>
                    <td> CTO </td>
                    <td> Director </td>
                    
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by KEERTHANA V(212223220045)  </center>
    </footer>
</body>
</html>

contact.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>NexGen</title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: 'Courier New', Courier, monospace;
                        }
            .banner {
                width: 100%;
                height: 100vh;
                background-size: cover;
                background-position: center;
		background-color:rgb(62, 3, 69);
            }
            .navbar {
                width: 100%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:rgb(201, 162, 23);
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(104, 104, 25);
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
                color: white;
            } 
            ::placeholder {
                color: white;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color:black;
                border-radius: 10px;
                background:rgba(255, 217, 0, 0.764);
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
                color: white;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: white;
                background-color:rgba(255, 217, 0, 0.523);
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid white;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid rgb(183, 162, 47);
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: white;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid white;
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: white;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: white;
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 15px;
                border: 1px solid white;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: white;
                border-radius: 30px;
                background: rgb(169, 150, 48);
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: white;
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: white;
                position: relative;
                top: 50px;
                
                padding: 10px 80px;
            }
            .box-2 span {
                color: gold;
                font-size: 30px;
            }
            footer {
                background-color: rgb(207, 233, 38);
                margin-top: auto;
            }
        </style>
    </head>
<body background="image.webp">
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo"><span> NexGen Software Tech </span></h1>
            <ul>
                <li><a href="Home.html"> Home </a></li>
                <li><a href="Product.html"> Products </a></li>
                <li><a href="persons.html"> People </a></li>
                <li><a href="contact.html"> Contact </a></li>
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
                        <h1> <span>Contact Us </span></h1>
                        <input type="text" placeholder="Your Name">
                        <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="30" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information</h2>
                <p><span> Address</span>: 35,Gandhi street,Tirupathur Dist 635601 </p>
                <p> <span>Email</span> : NexGen@gmail.com</p>
                <p> <span>Phone</span>: 9874536241 </p>
            </div>
        </div>
    </div>
    <footer>
        <center> Copyright@2024 Developed by KEERTHANA V(212223220045)  </center>
    </footer>
</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot (44).png>)

![alt text](<Screenshot (43).png>)

![alt text](<Screenshot (45).png>)

![alt text](<Screenshot (46).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
