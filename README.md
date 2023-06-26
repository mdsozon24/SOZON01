<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My CV</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@300&display=swap" rel="stylesheet">
    <style>
        body{

            background-color: rgb(177, 184, 156);

            font-family: 'Roboto Condensed', sans-serif;
        }
        .con{
            max-width: 1000px;
            margin: 0 auto;
            background-color: rgb(171, 224, 207);
            padding: 20px;
            object-fit: cover;
        }
        .p{
            float: left;
            padding: 10px;
        }
        .img{
            height: 100px;
            width: 100px;
            border: 2px solid gray;
           border-radius: 50%;
           margin-top: 21px;
           float: left;
           object-fit: cover;
        }
        h1,h2,h3,h4,h5,h6{
            color: rgb(107, 74, 94);
            
        }
        .cont{
            float: right;
            font-weight: bold;
            color: rgb(213, 27, 27);
        }
        .cont a{
            text-decoration: none;
            color: blue;
        }
       .cont a:hover{
             text-decoration: underline;
             color: tomato;
        }
        .clear{
            clear: both;
        }
        .h{
            border: 3px black solid;
            border-bottom: none;
        }
        .laft{
            float: left;
            width: 30%;
            margin-top: 20px;
        }
        .right{
            float: left;
            width: 70%;
            color: rgb(174, 77, 114);
            font-weight: bold;
        }
        .eright{
            float: left;
            width: 20%;
            color: rgb(174, 77, 114);
            font-weight: bold;
            margin-right: 5% ;
        }
        .elaft{
            float: left;
            width: 20%;
            color: rgb(174, 77, 114);
            font-weight: bold;
            margin-right: 5% ;
            
        }
        .ed{
            float: left;
            width: 20%;
            color: rgb(174, 77, 114);
            font-weight: bold;
        }
        .chr{
            border: 2px solid black;
            margin: 0 auto;
            margin-top: 10px;
            border-bottom: none;
        }
        .end{
            color: white;
            background-color: black;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .end a{
            color: white;
            text-decoration: none;
            margin: 15px;
        }
        .end a:hover{
            text-decoration: underline;
             color: tomato;
        }
        </style>
</head>
<body>
    <div class="con">
        <header>
            <img class="img" src="image/my_presentation.jpg" alt="Erorr loding">
            <div class="p">
                <h1>MD Sozon</h1>
               <h3>Web developer</h3>
               </div>
               <div class="cont">
                <p>Email :<a href="mailto:mdsozon24@gmail.com" target="_blank"> mdsozon24@gmail.com</a></p>
                <p>facebook :<a href="https://www.facebook.com/mdsozon24" target="_blank"> https://www.facebook.com/mdsozon24 </a></p>
                <p>Phone :<a href="tel:+8801907033716" target="_blank"> 01907033716</a></p>
               </div>
        </header>
        <div class="clear"></div>
        <hr class="h">
        <main>
            <div>
                <div class="laft">
            <h2>Parsonal info :</h2>
                </div>
                <div class="right">
                        <p>Address : Satarkul , Badda , Dhaka-1212</p> 
                        <p>Sex : Male</p>
                        <p>Religion : Islam</p>
                        <p>Date of birth : 07/03/2004</p>
                        <p>Nationality : Bangladeshi</p> 
                </div>
            </div>
            <div class="clear"></div>
            <hr class="chr">
            <div>
                <div class="laft">
                  <h2>Educational skill :</h2>
                </div>
                <div class="eright">
                <h3>SSC</h3>
                <h4>2018-2019</h4>
                <P>I have completed my SSC from Sharsha Govt. Pilot Model Secondary School (EIIN - 116328). I completed SSC in science background. I got GPA 4.72 in SSC exam.</P>
                <p class="cont">School website : <a href="https://sarsapilothighschool.jessoreboard.gov.bd/" target="_blank">Sharsha Govt. Pilot Model Secondary School</a></p>
           </div>

           <div class="elaft">
            <h3>HSC</h3>
                    <h4>2019-2021</h4>
                    <P>I have completed my HSC from B. A. F. Shaheen College, Jashore (EIIN - 116115). I completed HSC in science background. I got GPA 4.75 in SSC exam.</P>
                    <p class="cont">College website : <a href="https://bafshaheencollegejashore.jessoreboard.gov.bd/" target="_blank">B. A. F. Shaheen College, Jashore</a></p>    
           </div>
                
           <div class="ed">
            <h3>BSc. in CSE</h3>
            <p>2023-2027</p>
            <p>Dhaka International University</p>
            Computer Science and Engineering
            <p class="cont">Versity website : <a href="https://diu.ac/" target="_blank">Dhaka International University</a></p> 
           </div>
            </div>
            <div class="clear"></div>
            <hr class="chr">
            <div>
                <div class="laft">
                 <h2>About :</h2>
                </div>
                <div class="right">
                    <p>
                         I have two years of student teaching experience. 
                         I can teach all subjects from class 1 to class 8 to all students. 
                         Can teach all subjects of science to 9-10 & 11-12 students (Without Biology).
                        </p>
                
        </div>
        
        </main>
        <div class="clear"></div>
        <hr class="chr">
        <footer class="end">
          <a href="https://www.facebook.com/mdsozon24" target="_blank">Facebook</a>
          <a href="mailto:mdsozon24@gmail.com" target="_blank">Mail</a>
          <a href="tel:+8801907033716" target="_blank">WhatsApp</a>
            <p>Copyright &copy; MD Sozon 2023</p>
        </footer>
    </div>
</body>
</html>
