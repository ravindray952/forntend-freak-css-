# forntend-freak-css-
css 1 video
<html part/>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS tutorial</title>

    <!-- /* internal css */ -->
    <style>
        p {
            color:blueviolet
        }
    </style>

       <!-- external css -->
       <link rel="stylesheet" href="style.css">

</head>
<body>

    <!-- inline css -->
    <p class="para">ALorem, ipsum dolor sit amet consectetur bm'bmdfophmhmfdhbfd/.,mhrg'hmthpemtrmherghrefmhgfopmhbdfoimbniofdmniogfgnnm , mollitia voluptatibus, molestiae saepe optio iure. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vitae assumenda ad maiores similique tempora laborum at ea, rerum, illum aliquam nisi, officiis placeat expedita id impedit saepe. Ex nihil mollitia minend</p>
   <p id="third">BLorem ipsum dolor sit amet consectetur adipisicing elit. Iste, quibusdam!</p>
   <!-- <p id="triangle"></p>
   <p id="circle"></p> -->

    <a href="https:google.com">Go to google</a>
    <p>Go to google</p>
</body>
</html>

<h1>css part</h1>
/* universal selector // select all the html element*/
* {
  padding: 0;
  margin: 0;
}
/* with the  help of pading and marzing all paragraph are gone */

/* selector{
    property:  value;
    property2:   value2;
} */

/* Element selector  */
p {
  color: rgb(49, 141, 27);
}

/* id selector */
#third {
  color: blueviolet;
  
}

/* class selector */
.para {
    /* for all side */
   margin: 30px; 
  /*margin  top/bottom    left/right */
  margin: 30px 0px; 
  /*margin: top right bottom  left */
   margin: 30px 10px 20px 5px; 
   padding: 60px; 
  /* color: rgb(25, 236, 236);
  background-image: url("https://picsum.photos/id/237/200/300");
  background-repeat: no-repeat; */
  background-color: black;
  background-size: cover;
  background-position: center;
  background-origin: content-box;

  /* border */
  border-width: 5px;
  border-color: brown;
  border-style: solid;
  border-top: 5px solid green;                           /*width,style-solid,color-black */
     /* text */
  /* text-align:right;
  word-spacing: 10px;  //  space between two words
  letter-spacing: 2px;    // space between letters
 */
}

/*  Gropuing selector */
h1,
p {
  color: black;
}

/* Font Property */
p {
  /* font-family:Arial, Helvetica, sans-serif;

   font-size: large;                                20px,100%,medium 
   font-weight: 500;
   font-style: italic;
   font-variant:small-caps;
   line-height: 40px;  */

  font: italic small-caps 20px/50px  bold large Arial, Helvetica, sans-serif;

  /* colors */
  /* coloer by name */
  color:black;
   
  /* color by rgb value */
  color:rgb(236, 11, 11)
}

#triangle{
  width: 0px;                                 /*33% */
  height: 0px;                         /*40%*/
  
  border-top: 50px solid transparent;
  border-bottom: 50px solid blueviolet;
  border-left: 50px solid transparent;
  border-right: 50px solid transparent;
}


#circle{
  width: 300px;
  height: 300px;
  background-color: black;
  border-radius: 50%;
}

p{
  background-color: black;
}
/* pseudo selector */
a{
  text-decoration: none;
  color: brown;
  font-size: 24px;
  background-color: red;
}

/* mouse is over link   (hover) */
  a:hover{
    color: blueviolet;
  }
  /* the moment when link is clicked */
  a:active{
     color: yellow;
  }
  /* once you visit the link after that */
   a:visited{
      color: green;
   }

   /* Display property */
