# Ex-06-Book-Cover-Design
NAME: CHANDRU.p

DEPT: CSE(IOT)
# AIM
To Design a book cover page using HTML and CSS.

# DESIGN PROCEDURE
## Step 1:
Create a html file .
## Step 2:
Choose background image and photo to be used and save it to the repository.
position the elements appropriately
## Step 3:
Use html and css code to design the book cover.
# CODE
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
    </head>
    <style>
        body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    background-color:rgb(0, 0, 0);
    margin:auto;
    position: relative;
    background-image: url('web technology.jpg');
    background-repeat: no-repeat;
    background-size:606px;
    background-position: bottom 150px center;
}
h1{
    font-size:70px; 
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: x-large;
    color: #f47027;
}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 0px;
    border-top:2px solid #f47027;
    padding-top:10px;
    width:726px;
}
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
    </style>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>First Edition</h3>
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>CHANDRU P</span>
                    <span id="end"><u>Packt></u></span>
                </div>
            </footer>
    </section>
    </body>
</html>
```
OUTPUT:
![Screenshot 2023-12-20 101431](https://github.com/Karthi-Govindharaju/Ex-06-Book-Cover-Design/assets/139841798/827ada84-9b29-425c-8bbe-fca1bcc4fd48)

