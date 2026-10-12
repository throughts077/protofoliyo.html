<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <link rel="stylesheet" href="styles/style.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
  <style>
            body {
            margin:0px;
            min-height:100vh;
            overflow: visible;
            height: auto;
            width:100%;
          }
            main{
            flex: 1;
          }
           .navbar{
            display:flex;
            
            position: sticky;
            z-index:1000vh;
            top:0;
            justify-content:space-between;
            align-items:center;
            padding:1rem 1.5rem;
            margin:0;
            height:20px;
            background-color:black;
            color:white;
          }
  
           .logo {
            display:flex;
            font-size:20px;
            font-weight:bold;
            font-family:times new roman;
            align-items:center;
            white-space:nowrap;
          }
           .logo i {
            font-size:30px;
            margin-right:10px;
            padding:0;
          }
         
            .nav-links {
             display:flex;
             padding:0; 
             margin:0;
             list-style:none;
             white-space:nowrap;
             gap:20px;
           }
  
            .nav-links a{
             text-decoration:none;
             color:inherit;
             font-weight:bold;
           }
            .nav-links i {
             font-weight:bold;
             font-size:18px;
           }
            #mode {
             display:none;
           }
            body:has( #mode:checked ) {
             background-color:black;
             color:white;
           }
             .navbar:has( #mode:checked ) {
             background-color:white;
             color:black;
             }
            label{
               color:darkorange;
                font-weight:bold;
            }
            .footer{
              bottom:0;
              left:0;
              height:7px;
              background-color:black;
              align-items: center;
              color:white;
              padding:1rem 1.5rem;
              margin-top:40px;
            }
             .footer-content {
               display:flex;
               justify-content:center;
               align-items:center;
               white-space: none;
               margin-top: 0px;
               margin-bottom: 5px;
               flex-wrap:wrap;
               gap:20px;
            }
             .footer-content p {
               display:block;
               margin:0px;
               margin-bottom: 15px;
            }
             .social-links {
               display:flex;
               gap:15px;
               margin-bottom:15px;
            }
              .social-links a {
               color:inherit;
               font-size:15px;
               text-decoration:none;
            }
              body:has(#mode:checked) 
             .footer {
              background-color: white;
              color: black;
            }

            .profile img{
              width:200px;
              height:250px;
              margin-left: 60%;
              margin-top: 5%;
              border:2px solid darkcyan;
              border-radius: 50%;
              position: relative;
              box-shadow: 0 3px 15px #aaa;
            }
            .text {
              position: absolute;
              top:20%;
              left:5%;
            }
            .text h1 {
              margin:4px;
            }
            .text h2 {
              margin:4px;
            }

            .text p {
              margin:4px;
            }
            .text a {
              margin-right:10px;
              color: black;
            }
            .text span {
              color:darkcyan;
            }
            .btn {
              display:flex;
              gap:5px;
            }

            .btn a {
                text-decoration: none;
              }

            .btn1  {
             padding: 7px 15px;
             background-color:powderblue;
             border: 1px solid darkcyan;
             border-radius: 15px;
             width: fit-content;
             color: inherit;         
            }

            .btn2  {
             padding: 7px 15px;
             background-color:powderblue;
             border: 1px solid darkcyan;
             border-radius: 15px;
             width: fit-content;
             color: inherit;         
            }

            body:has( #mode:checked)
            .btn{
              color:inherit;
            }
            .contact {
              margin-left:10px;
            }

  </style>
  <title>Hello, World!</title>
</head>
<body>
  
  <nav class="navbar">
    
    <div class="logo"> <i class="bi bi-code-slash"></i><p> RAJU PRAJAPATI </p>
    </div>
    
    <ul class="nav-links">
      <li> <a href=""> Home </a> </li>
      <li> <a href=""> Service </a> </li>
      <li> <a href=""> Result </a> </li>
      <li> <a href=""> About </a> </li>
      <li> <label for="mode"> <i class="bi bi-brightness-high"> </i> </label>
      <input type="checkbox" id="mode"></li>
    </ul>
  </nav>
  <main>
        <div class="profile">
      <img src="F:\C2434\OL2602\image OL2602\WhatsApp Image 2026-10-11 at 11.17.45 PM.jpeg">
    </div>

      <div class="text">

      <h1> Hi,I'm <span> Raju Prajapati </span> </h1>
      <h2> Frontend Devloper </h2>
      <p> I build exceptional digital experiences that are fast,<br>
        accessible, and visually appealing.Let's create something <br>
      amazing togeher.</p>
      <br>
      <div class="btn">
      <a href="#" class="btn1"> Hire Me </a>
      <a href="#" class="btn2"> View Work </a>
    </div>
    <br>
      <div class="contact">
      <a href="#" class="icon"><i class="bi bi-github"></i></a>
      <a href="#" class="icon"><i class="bi bi-linkedin"></i></a>
      <a href="#" class="icon"><i class="bi bi-twitter"></i></a>
      <a href="#" class="icon"><i class="bi bi-envelope-at"></i></a>
    </div>
    </div>

    
  </main>
  
  <footer class="footer">
    
    <div class="footer-content"> 
    
      <p> &copy; 2026 Raju Prajapati. All rights reserved. </p>
    
      <div class="social-links">
      
      <a href="https://www.instagram.com/info.rajuprajapati?stkn=MXJxZDgxamdjM2Y5eg=="><i class="bi bi-instagram"></i></a>
      <a href="#"><i class="bi bi-github"></i></a>
      <a href="#"><i class="bi bi-linkedin"></i></a>
      
    </div>
    </div>
  </footer>
</body>
</html>