# Ex.07 Restaurant Website
## Date:06/10/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

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

~~~

home.html

<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="home.css"> 
    </head>
    <body>
        <nav>
            <a  href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <div class="name">
            <h1>ELEVEN MADISON PARK RESTAURANT</h1>
            <b>"From Field To Fork - Fresh Foods On Every Day"</b>
            
        </div>
        <div class="offer">
            <h2>Limited Offers</h2>
            <h3>50% off for all Food</h3>
        </div>
        <footer>
            <h6 class="bottom">GOKULRAJ K(25017714)</h6>

        </footer>
    </body>
</html>



home.css

*{
    margin: 0;
    border: 0;
}

body{
    background-image:url("home image.jpeg");
    background-position: center;
    background-size:cover;
    width: 100%;
    background-color: rgb(252, 93, 24);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: rgb(11, 11, 11);
}

a{
    padding: 15px;
    color:rgb(20, 195, 14);
}
a:hover{
    background-color: rgb(15, 14, 14);
    color:rgb(237, 67, 15);
}
.name{
    text-align: center;
    position: relative;
    left: 290px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
    color: rgba(251, 9, 9, 0.855);
    font-size: 30px;
    width: 1000px;
    background-color: rgba(251, 246, 246, 0.94);
}
.offer{
    text-align: right;
    font-size: 40px;
    color: rgb(18, 18, 17);
    position: relative;
    right: 100px;
    top:200px;

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 462px;
    background-color: rgb(232, 248, 11);
}



menu.html

<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="menu.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Menu Lists</h1>
        <div class="main">
            
            <div class="food1">
                <img src="chocolate cake.jpeg"alt="pic">
                <b>CHOCOLATE CAKE-$20</b>
            </div>
            <div class="food2">
                <img src="falooda.jpeg" alt="pic">
                <b>FALOODA-$15</b>
            </div>
            <div class="food3">
                <img src="Momos.jpeg" alt="pic">
                <b>MOMOS-$50</b>
            </div>
            <div class="food4">
                <img src="mutton.jpeg" alt="pic">
                <b>MUTTON-$60</b>
            </div>
            <div class="food5">
                <img src="omlette.jpeg" alt="pic">
                <b>OMLETTE-$30</b>
            </div>
            <div class="food6">
                <img src="Samosa.jpeg" alt="pic">
                <b>SAMOSA-$40</b>
            </div>
            <div class="food7">
                <img src="pizza.jpeg" alt="pic">
                <b>CHEESE PIZZA-$30</b>
            </div>
            <div class="food8">
                <img src="chips.jpeg" alt="pic">
                <b>CHIPS-$40</b>
        </div>
        <footer>
            <h6 class="bottom">GOKULRAJ K(25017714)</h6>

        </footer>
    </body>
</html>



menu.css

body{
    
    background:url("menu image.jpeg");
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
a{
    color:rgb(17, 17, 16);
    position: relative;
    left: 1200px;
}
.food1{
    padding: 10px;
    background-color: rgba(245, 45, 14, 0.993);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
}
.food2{
    padding: 10px;
    background-color: rgba(243, 9, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
    
}
.food3{
    padding: 10px;
    background-color: rgba(246, 28, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
}
.food4{
    padding: 10px;
    background-color: rgba(245, 16, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
    
}
.food5{
    padding: 10px;
    background-color: rgba(255, 37, 8, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    bottom: 20px;
    
}
.food6{
    padding: 10px;
    background-color: rgba(244, 4, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food7{
    padding: 10px;
    background-color: rgba(247, 57, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food8{
    padding: 10px;
    background-color: rgba(239, 39, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}



img{
    width: 150px;
    height: 100px;
    border: solid rgb(4, 4, 4) 6px;
}
h1{
    text-align: center;
    position: relative;
    bottom: 10px;
   
    color: rgb(46, 36, 220);

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 50px;
    background-color: rgb(237, 212, 212);
}




admin.html

<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="admin.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contanct</a>
        </nav>
        <h1>Administration</h1>
        <div class="admin">
            <div class="a1">
                <img src="vivek.jpeg">
                <b>VIVEK</b>
                <b>CEO</b>
            </div>
            <div class="a2">
                <img src="yogi babu.jpeg">
                <b>YOGI BABU</b>
                <b>Manager</b>
            </div>
            <div class="a3">
                <img src="santhanam.jpeg">
                <b>SANTHANAM</b>
                <b>Service Manager</b>
            </div>
            <div class="a4">
                <img src="senthil.jpeg">
                <b>SENTHIL</b>
                <b>Reception</b>
            </div>
            <div class="a5">
                <img src="vadivelu.jpeg">
                <b>VADIVELU</b>
                <b>Accounts Manager</b>
            </div>
            <div class="a6">
                <img src="vijay.jpeg">
                <b>VIJAY</b>
                <b>Maintenance Manager</b>
            </div>
        </div>
        <footer>
            <h6 class="bottom">GOKULRAJ K(25017714)</h6>

        </footer>
    </body>
</html>



admin.css

body{
    background-image:url("admin background.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
a{
    padding: 15px;
    color:rgb(251, 9, 9);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
    font-size: x-large;
}
.admin{
    display: grid;
    grid-template-columns: repeat(6,1fr);
    font-size: 20px;
    gap:10px;
}
img{
    width: 210px;
    height: 300px;
    border:solid 5px rgb(240, 235, 235);
}
.a1,.a2,.a3,.a4,.a5,.a6{
    padding: 5px;
    background-color: rgb(16, 16, 16);
    text-align: center;
    font-size: 24px;
    
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color:white;
    position: relative;
    top: 60px;
    color:white;
}
h1{
    text-align: center;
    color:rgb(250, 21, 21);
    font-size: 40px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 125px;
    background-color: brown;
    width: 1550px;
}

~~~

## OUTPUT:

![alt text](<home output.png>)
![alt text](<menu output.png>)
![alt text](<admin output.png>)
![alt text](<contact output.jpeg>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
