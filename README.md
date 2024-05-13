# Project Responsive Web Design using Bootstrap
## Date:13-05-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
products.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            color: rgb(0, 0, 0);
            font-size: 45px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            position: absolute;
            top: 35%;
        }

        body {
            background-color: rgb(0, 0, 0);
            margin: 0;
        }

        .navbar ul {
            list-style-type: none;
            background-color: darkblue;

        }

        .navbar a {
            color: white;
            text-decoration: none;
            padding: 25px;
            display: flex;
            text-align: left;
            position: relative;
            font-size: 20px;
            top: -95px;

        }

        .navbar a:hover {
            background-color: lightblue;
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: white;
            font-family: monospace;
            font-size: 60px;
            background-color: rgb(0, 0, 0);
        }

        footer {
            background-color: black;
            height: 30px;
            text-align: center;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color: rgb(0, 0, 0);
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: white;
            margin-top: 10px;
            margin-left: 10px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button {
            color: white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }

        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: silver;
        }

        .contain {
            position: absolute;
            top: 12%;
            width: 1210px;
            height: 700px;
            margin-left: 10px;
            background-color: rgb(0, 0, 0);
        }

        .contain p b {
            font-size: 30px;
            padding-left: 45px;
        }

        .contain p {
            font-size: 20px;
            color: white;
            padding-left: 15px;
            padding: 5px 20px 0px 15px;
        }

        .contain img {
            margin-top: 0%;
            padding-left: 10px;
            padding: 20px 20px 0px 20px;
        }
    </style>
</head>

<body>
    <header>
        <h2>PAGANI</Code></h2>
    </header>
    <hr>
    <nav class="navbar">

        <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="investors.html">Products</a></li>
            <li><a href="directors.html">People</a></li>
            <li><a href="home.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <div class="contain">
        <table>
            <tr>
                <td><img src="zonda f.webp" height="200px" width="200px">
                    <p><b>ZONDA F</b><br>
                        &nbsp;&nbsp;&nbsp;Game Development<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Platform
                    </p>
                </td>
                <td><img src="trach huyra.jpeg" height="200px" width="200px"><br>
                    <p><b>HUYARA TRACK</b><br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloud-based<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;CRM
                    </p>
                </td>
                <td><img src="huyara.jpeg" height="200px" width="200px"><br>
                    <p><b>HUYARA</b><br>
                        &nbsp;&nbsp;&nbsp;Content Management <br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; System
                    </p>
                </td>
                <td><img src="utopia.jpeg" height="200px" width="200px"><br>
                    <p><b>UTOPIA</b><br>
                        &nbsp;&nbsp;&nbsp;&nbsp;Project Management<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Tool
                    </p>
                </td>
                <td><img src="zomnda hf.jpeg" height="200px" width="200px"><br>
                    <p><b>ZONDA HF</b><br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Cloud Storage<br>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Device
                    </p>
                </td>
            </tr>
        </table>
    </div>
    <footer>
        <hr>
        Designed and Developed by HARIPRASHAAD S&copy; 2024
    </footer>

</body>

</html>


```

## OUTPUT:
![image](https://github.com/HARIPRASHAAD-RA/Pharma/assets/164654451/f5059c4f-9301-486c-9172-4d2d02b3158b)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
