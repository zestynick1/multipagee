
<!DOCTYPE html>
 
<html>
 
<head>
    <title>Simple web Development Template</title>
 
    <style>
        * {
            margin: 0;
            padding: 0;
        }
 
        .navbar {
            display: flex;
            align-items: center;
            justify-content: center;
            position: sticky;
            top: 0;
            cursor: pointer;
        }
 
        .background {
            background: black;
            background-blend-mode: darken;
            background-size: cover;
        }
 
        .nav-list {
            width: 70%;
            display: flex;
            align-items: center;
        }
 
        .logo {
            display: flex;
            justify-content: center;
            align-items: center;
        }
 
        .logo img {
            width: 180px;
            border-radius: 50px;
        }
 
        .nav-list li {
            list-style: none;
            padding: 26px 30px;
        }
 
        .nav-list li a {
            text-decoration: none;
            color: white;
        }
 
        .nav-list li a:hover {
            color: grey;
        }
 
        .rightnav {
            width: 30%;
            text-align: right;
        }
 
        #search {
            padding: 5px;
            font-size: 17px;
            border: 2px solid grey;
            border-radius: 9px;
        }
 
        .firstsection {
            background-color: green;
            height: 400px;
        }
 
        .secondsection {
            background-color: blue;
            height: 400px;
        }
 
        .box-main {
            display: flex;
            justify-content: center;
            align-items: center;
            color: black;
            max-width: 80%;
            margin: auto;
            height: 80%;
        }
 
        .firsthalf {
            width: 100%;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
 
        .secondhalf {
            width: 30%;
        }
 
        .secondhalf img {
            width: 70%;
            border: 4px solid white;
            border-radius: 150px;
            display: block;
            margin: auto;
        }
 
        .text-big {
            font-family: 'Piazzolla', serif;
            font-weight: bold;
            font-size: 35px;
        }
 
        .text-small {
            font-size: 18px;
        }
 
        .btn {
            padding: 8px 20px;
            margin: 7px 0;
            border: 2px solid white;
            border-radius: 8px;
            background: none;
            color: white;
            cursor: pointer;
        }
 
        .btn-sm {
            padding: 6px 10px;
            vertical-align: middle;
        }
 
        .section {
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            max-width: 90%;
            margin: auto;
        }
 
        .section-Left {
            flex-direction: row-reverse;
        }
 
        .paras {
            padding: 0px 65px;
        }
 
        .thumbnail img {
            width: 250px;
            border: 2px solid black;
            border-radius: 26px;
            margin-top: 19px;
        }
 
        .center {
            text-align: center;
        }
 
        .text-footer {
            text-align: center;
            padding: 30px 0;
            font-family: 'Ubuntu', sans-serif;
            display: flex;
            justify-content: center;
            color: white;
        }
    </style>
</head>
 
<body>
    <nav class="navbar background">
        <ul class="nav-list">
            <div class="logo">
                <img src= "logo.png">
            </div>
            <li><a href="#web">voluptate</a></li>
            <li><a href="#program">occaecat</a></li>
            <li><a href="#course">Excepteur</a></li>
        </ul>
 
        <div class="rightNav">
            <input type="text" name="search" id="search">
            <button class="btn btn-sm">Search</button>
        </div>
    </nav>
 
    <section class="firstsection">
        <div class="box-main">
            <div class="firstHalf">
                <h1 class="text-big" id="web">Lorem Ipsum</h1>
                <p class="text-small">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Gravida quis blandit turpis cursus in hac habitasse platea. Consequat interdum varius sit amet mattis vulputate enim nulla. Nunc mi ipsum faucibus vitae aliquet nec ullamcorper sit amet.
                    content to display it in the required format.
                </p>
 
 
            </div>
        </div>
    </section>
 
    <section class="secondsection">
        <div class="box-main">
            <div class="firstHalf">
                <h1 class="text-big" id="program">
                    Deserunt mollit
                </h1>
                <p class="text-small">
                   Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                </p>
 
 
            </div>
        </div>
    </section>
 
    <section class="section">
        <div class="paras">
            <h1 class="sectionTag text-big">Fortag</h1>
 
            <p class="sectionSubTag text-small">
              Arcu dui vivamus arcu felis bibendum ut. Nullam non nisi est sit amet. Sagittis purus sit amet volutpat consequat mauris nunc congue. Consectetur adipiscing elit ut aliquam. Lectus sit amet est placerat in. Laoreet suspendisse interdum consectetur libero. Dolor sit amet consectetur adipiscing elit duis tristique sollicitudin. Venenatis a condimentum vitae sapien pellentesque habitant morbi. Nisl suscipit adipiscing bibendum est. 
            </p>
 
 
        </div>
 
        <div class="thumbnail">
            <img src= "img.png" alt="laptop image">
        </div>
    </section>
 
    <footer class="background">
        <p class="text-footer">
        <p>Click <a href="https://zestynick1.github.io/Nickm/">here</a>
        </p>
 
 
    </footer>
</body>
 
</html>
