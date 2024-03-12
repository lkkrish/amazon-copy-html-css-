![hero_image](https://github.com/lkkrish/amazon-copy-html-css-/assets/163138410/9fe39cd0-0643-495c-bbb9-e451b02c4424)
![box1_image](https://github.com/lkkrish/amazon-copy-html-css-/assets/163138410/9a5d68d7-7045-407d-aa26-d22b873ca3f3)
![box2_image](https://github.com/lkkrish/amazon-copy-html-css-/assets/163138410/54bc29fd-7127-4c95-9299-22a98532024a)
![box3_image](https://github.com/lkkrish/amazon-copy-html-css-/assets/163138410/47b65857-766f-400d-ad19-7af4218e0239)
![box4_image](https://github.com/lkkrish/amazon-copy-html-css-/assets/163138410/b20387ae-27b2-4908-9aa0-b37880d67818)


////////////////////////////////////////////////////////////////////////////////HTML CODE//////////////////////////////////////////////////////////////////////////////////////////////////////////////
<html lang="en">
<head>
<link rel="stylesheet"href="amazon.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body >
    <header id="m"; >
    <div id="box";   >
        <div id="nav-logo"; >
         <div id="logo";>
         </div>   
        </div>
        <div style="margin-top: 4px;">
            <p >  Diliver to <br><i class="fa-solid fa-location-dot"></i>
                    Nepal 
                </p>
        </div>
        <div >
            <select id="option" >
                <option >All</option>
            </select>
            <input  id="s"  placeholder="search amazon ">
            <button id="sh">
            <i class="fa-solid fa-magnifying-glass"></i>
            </button>

        </div>
        <div>
            <p id = "upper-text"><span>Hello, sign in</span></p>
            <p id="lower-text" style="font-size: 0.87rem;">Accounts & Lists</p>

        </div>
        <div>
            <p id = "upper-text"><span>Returns</span></p>
            <p id="lower-text" > &Orders</p>

        </div>  
        <div id="Cart">
            <i style="font-size: 35px;" class="fa-solid fa-cart-shopping"></i>
            Cart
        </div>
    </div>
    <div id="nd">
        <div id="menu">
            <i class="fa-solid fa-bars"></i>
            All
        </div>
        <div id="optio"> 
            <P>Todays deal</P>
            <P>Customer service</P>
            <P>Registry</P>
            <P>Gift cards</P>
            <P>Sells</P>
        </div>
        <div id="ex-deal">
            Shop deals in elcotronic 
        </div>
    </div>
    </header>
    <div id="middle-section">
        <div id="middle-meassge">
            <p>
                You are on amazon.com You can also shop on Amazon nepal for millions of products with fact local deliver. <a href="https://www.amazon.com/">Click here to go on amazon</a>
            </p>
        </div>

        
    </div>
    
    <div id="shop">
        <div id="area" itemid="area1"><h2>Healt & persnoal</h2>
        <p>see more</p>
        <img src="box1_image.jpg" style="width: 95%; margin-left: 8px;"></div>
        <div id="area"> hello
        <img src="box2_image.jpg" style="width: 95%; margin-left: 8px;">
         
        </div>
        <div id="area">bhai
        <img src="box3_image.jpg" style="width: 95%; margin-left: 8px;">
        </div>
        <div id="area">how are You         <img src="box4_image.jpg" style="width: 95%; margin-left: 8px;"></div>

    </div>

    <script src="p.js"></script>
</body>
</html>


/////////////////////////////////////////////////////////////////////////////////////////////////////////////////CSS CODE//////////////////////////////////////////////////////////////////////////

* {
    margin: 0;
    font-family: Arial;
     /* Ensure consistent box model */
  }
  
  #box {
    height: 60px;
    width: 100%; /* Use `%` for responsive width */
    background-color: black;
    color: white;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
  }
  #option{

    height: 1cm;

  }

  
  #logo {
    background-image: url(amazon_logo.png); /* Replace with your image path */
    height: 50px;
    background-size: cover;
    width: 100%;
    border: 2px solid transparent; /* Default border */
  }
  
  #logo:hover {
    border: 2px solid white; /* Hover effect */
  }
  
  #nav-logo {
    height: 50px;
    width: 100px;
    /* Consider adding class for styling to avoid potential conflicts */
  }
  
  #Cart {
    margin-top: 4px;
  }
  
  #s {
    width: 15cm; /* Use `px` for consistency */
    height: 1cm;
    font-size: 1rem;
    
  }
  
  #srollbar {
    width: 400px; /* Use `px` for consistency */
  }
  
  #upper-text {
    font-size: 0.7rem;
  }
  
  #lower-text {
    font-size: 0.87rem;
    font-weight: 700;
  }
  #sh{
    height: 1cm;
    width: 1cm;
    background-color:white;
    border-right: 25%;
  }
  
#all{
    height: 1cm;
    width: 500px;
    display: flex;
    border-radius: 25%;
    
    
}


/*fiffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffffff*/
#nd{
    display: flex;
    background-color: 222f3d;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}

#menu{
    height: 40px;
    align-items: center;
    


}
#optio p {
    display: inline;
    margin-left: 10px;
    
}
#optio{
    width: 70%;
    font-size: 0.85rem;

}

#ex-deal{

    font-size: 0.9rem;
    font-weight: 700;
}



/*ggggggggggggggggggggggggggggggggggggggggggggggffggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggggg
*/

#middle-section{

  background-image: url(hero_image.jpg);
  height: 350px;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: flex-end;
  
}

#middle-meassge{
  background-color: white;
  color: black;
  height: 40px;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 0.85rem;
  margin-bottom: 25px;

}
#middle-meassge a {
  color: 007185;
  border: none;
  
}
#area{
  border: 2px solid black;
  height: 500px;
  width: 23%;

}
#shop{
  display: flex

}
#shop{
  justify-content: space-evenly;
}
#area {
  padding: 20px 0px 15px;
}

#shop{
  padding: 20px 0px 15px;
}





























