# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### home page:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>DRIFTER</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ico.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">DRIFTER</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/icn.jpg" alt="Building" />
          <div class="contenttext">
            DRIFTER is a world leader in gaming, content creation, business & productivity and AIoT solutions. Bolstered by its cutting-edge R&D capabilities and customer-driven innovation, DRIFTER has a wide-ranging global presence spanning over 120 countries. Its comprehensive lineup of laptops, graphics cards, monitors, motherboards, desktops, peripherals, servers, IPCs, robotic appliances, and vehicle infotainment and telematics systems are globally acclaimed. Committed to advancing user experiences through the finest product quality, intuitive user interface and design aesthetics, DRIFTER is a leading brand that shapes the future of technology.
            <ul>
              <li>Rise above everyone.</li>
              <li>Gaming is about the performance and talent.</li>
              <li>Gaming is NOT a crime being not able to game is ONE.  </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2004 DRIFTER, Developed by M Gautham.
      </div>
    </div>
  </body>
</html>
###product.html:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>DRIFTER</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ico.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">DRIFTER</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">contact us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/head.png" alt="product image">
                  </div>
                  <div class="itemname">Drag X200</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/int.png"  alt="product image">
                  </div>
                  <div class="itemname">DRX 5000</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/g300.png"  alt="product image">
                </div>
                <div class="itemname">G3000</div>
                <div class="itemprice">Price: Rs.16,000.00 </div>
             </div>
             <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/mother.png"  alt="product image">
              </div>
              <div class="itemname">Krypt 6000 </div>
              <div class="itemprice">Price: Rs.45,000.00 </div>
             </div>
           <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/mot.png"  alt="product image">
            </div>
            <div class="itemname">BS7000 bison gear </div>
            <div class="itemprice">Price: Rs.60,000.00 </div>
           </div>
           <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/graphic.png"  alt="product image">
            </div>
            <div class="itemname">Syren GTX1700</div>
            <div class="itemprice">Price: Rs.70,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/head.png" alt="product image">
          </div>
          <div class="itemname">Drag X250</div>
          <div class="itemprice">Price: Rs.43,000.00 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/MAG.png" alt="product image">
        </div>
        <div class="itemname">Drag X2500</div>
        <div class="itemprice">Price: Rs.70,000.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/car.png" alt="product image">
      </div>
      <div class="itemname">HYPER 4300</div>
      <div class="itemprice">Price: Rs.50,999.00 </div>
   </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/coo.png" alt="product image">
    </div>
    <div class="itemname">TA47GH</div>
    <div class="itemprice">Price: Rs.19,999.00 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="/static/img/3040.png" alt="product image">
    </div>
    <div class="itemname">SPERO RT7000</div>
    <div class="itemprice">Price: Rs.80,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="/static/img/MSI.png" alt="product image">
  </div>
  <div class="itemname">SPERO GT6888</div>
  <div class="itemprice">Price: Rs.30,000.00 </div>
</div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2004 DRIFTER, Developed by M GAUTHAM.
      </div>
    </div>
  </body>
</html>
### people page :
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>DRIFTER</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ico.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">DRIFTER</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/People.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">contact us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Founders</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/father.jpg" alt="product image">
                  </div>
                  <div class="itemname">Ralph baer</div>
                  <div class="itemprice">Ralph baer was the father and also know as the father of modern video games. </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/jeff.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">JEFF BEZOS</div>
                  <div class="itemprice">He was the co-founder of the DRIFTER along with ralph and he is also the former ceo of the amazon.</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/elon.jpg"  alt="product image">
                </div>
                <div class="itemname">ELON MUSK</div>
                <div class="itemprice">He was the co-founder of the DRIFTER and his also the owner of spacex,tesla. </div>
                </div>
                <div class="productitem"> 
                    <div class="itemimage">
                    <img src="/static/img/sun.png"  alt="product image">
                    </div>
                    <div class="itemname">SUNDAR PICHAI</div>
                    <div class="itemprice">Chief Architect </div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/jo.jpg"  alt="product image">
                        </div>
                        <div class="itemname">Joseph Hyung</div>
                        <div class="itemprice">CTO </div>
                        </div>
                        <div class="productitem"> 
                            <div class="itemimage">
                            <img src="/static/img/John.jpeg"  alt="product image">
                            </div>
                            <div class="itemname">JOHN HENRY</div>
                            <div class="itemprice">CIO </div>
                            </div>
                <h2>MISSION</h2>
                <p class=par >We at the DRIFTER try to bring the best of the best to the world class gamers and we strive to do it every moment and we have the best motherboards,graphic cards,headphones,mouse etc which are essential for gamer,and we try do this every time without any fail and we want to create a world where gaming is not thing but a future for aspiring young people who like to play,and for aspiring young people who want to create their own . </p>
                <br>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2004 DRIFTER, Developed by M GAUTHAM.
      </div>
    </div>
  </body>
</html>
### contact us :
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>DRIFTER</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/ico.jpeg" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">DRIFTER</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/People.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact us.html">contact us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>CONTACT US</h1>
          <img src="./img/icn.jpg" alt="Building" />
          <div class="contenttext">
           
            <ul>
              <li>You can contact us online, visit or give us a call.</li>
              <li>you can contact us through online by using our gmail id-DRIFTERtechnical@gmail.com for technical support.</li>
              <li>You can contact us by call to the number +1468634823 </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2004 DRIFTER, Developed by M Gautham.
      </div>
    </div>
  </body>
</html>
### layout css:
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: rgb(15, 7, 7);
  color: #09140b;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px rgb(10, 8, 8);
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 50px;
  background-image: url("/static/img/drag.jpeg");
  font-family: 'Eczar', serif;
  background-size: 97% 97%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: white ;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: rgb(14, 9, 9);
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #e0e6e4;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: black;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
  color: #e0e6e4;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color: #e0e6e4;
  font-family: 'Roboto Slab', serif;
  font-size: x-large;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: #e0e6e4;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  color: #e0e6e4;
}
.productitem .itemprice {
  display: block;
  color: #e0e6e4;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #faf2f2;
}
.par {
  font-size: 90%;
}

## OUTPUT:

### Home Page:

![image](https://user-images.githubusercontent.com/94810884/146704109-e4b15c12-b1b3-4c62-ae26-4aa537a5ea51.png)
 
 ### product page:
 ![image](https://user-images.githubusercontent.com/94810884/146704146-d8e46596-26c6-47d7-9739-24c0aeeb6a5b.png)

### people page:
![image](https://user-images.githubusercontent.com/94810884/146704185-60d043c4-cd3d-4668-8011-dbe503f822a0.png)

### contact us :
![image](https://user-images.githubusercontent.com/94810884/146704229-6160a739-dc27-4eff-8e6b-e39df7e1a0bc.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
