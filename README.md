 <!DOCTYPE html>
<html lang="en">
<head>
<tittle>MY PROFILE<tittle/>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML</title>
    <style>
        * {
            margin: 0;
        }
    .body {
        width: 100%;
        height: 100vh;
        background-image: url("cse_043.JPG");
        background-position: center;
        background-repeat: no-repeat;
        background-size: 100% 100%;
    }
    @media screen and (min-width: 800px){
        .body {
        width: 100%;
        height: 100vh;
        background-image: url("has14.jpeg");
        background-position: center;
        background-repeat: no-repeat;
        background-size: 100% 100%;
        }
        
    }
    ul {
        list-style-type: none;
        background: #333;
        overflow: hidden;
        padding: 0;

    }
    li {
        float: left;
    }
    a {
        display: inline-block;
        text-decoration: none;
        color: white;
        padding: 12px 16px;
    }
    a:hover {
        background: black;
    }
    .drop {
        position: absolute;
        background: rgba(51, 51, 51, 0.555);
        display: none;
        box-shadow: 2px 2px 10px black;

    }
    .drop a {
        display: block;
    }
    .act:hover{
        background: red;
    }

    .act:hover .drop{
        display: block;
        
    }
    
    

    </style>
</head>
<body>
    <div class="body">
    <ul>
        <li><a href="https://www.justdial.com/Muzaffarpur/Waseem-Diagnostic-Center-Near-Dr-M-Nizamuddin-Pakki-Sarai/9999PX621-X621-170929142727-A8I2_BZDET/photos">HASEEB RAZA BLOGS</a></li>
</style>
</head>
<body>
    <div class="body">
    <ul>
        <li class="act"><a href="#">Contact</a>
            <div class="drop">
            <a href="details.html">Details</a>
            </div>
            </li>

        <li class="act"><a href="#">College</a>
            <div class="drop">
            <a href="osLab.html">Practical</a>
            <a href="exam.html">Notes</a>
            <a href="#">Books</a>
            <a href="#">Syllabus</a>
            </div>
        </li>
        <li class="act"><a href="#">About</a> 
            <div class="drop">
            <a href="Owner.html">About Owner</a>
            
            </div>
            </li>
<li class="act"><a href="#">Gallery</a>
            <div class="drop">
            <a href="pic.html">My pics</a>
            <a href="#">Friends pic</a>
            </div>
        </li>
 <li class="act"><a href="#">Video's</a>
            <div class="drop">
            <a href="videoaddin.html">About clip</a>
            <a href="funny.html">Funny clips</a>
            <a href="#">Memorised clips</a>
            <a href="#">Family clips</a>
            </div>
        </li>


    </ul>
</div>
</body>
</html>
