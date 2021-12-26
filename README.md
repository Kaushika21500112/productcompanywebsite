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
## CSS StyleSheet
~~~
* {
  box-sizing: border-box;
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif ;
}
body{
    background-color: black;
    color: white;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: hidden;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/adobe.png");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: white;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #2B2B2B;
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
  color:rgb(180, 180, 179);
}

.menuitem a {
  text-decoration: dotted;
  color: rgb(180, 180, 179);
}

.content {
  display: block;
  width: 100%;
  min-height: 550px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-style:hidden;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align:justify;
  font-size: x-large;
}
.heading2{
  text-align:center;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 450px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  font-size:large;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #2B2B2B;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: rgb(180, 180, 179);
}
.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
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
}
.productitem .itemprice {
  display: block;
}

.peoplecontent{
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.peoplecontent h1{
  text-align: left;
}

.peoplepics{
  display: block;
}

.peoplepic{
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.peoplepic img{
  width: 100px;
  height: 100px;
  display: block;
}

.peoplepic .peopleimage{
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.peoplepic .peoplename{
  display: block;
}

.peoplepic .peopledes{
  display: block;
}

.contactcontent{
  min-height: 500px;
  margin: 10px 10px 10px 10px;  
}

.contactitems{
  display: block;
}

.contactitem{
  display:block;
  text-align: left;
}

.contactitem .address{
  display: block;
  text-align: left;
}

.contactitem .number{
  display: block;
  text-align: left;
}

.conatctitem .email{
  display: block;
  text-align: left; 
}

.conatctitem .socials{
  display: block;
  text-align: left; 
}
~~~
## Home Page html
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Thedigitrove.org</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactpg.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1><u>About</u></h1>
          <img src="./img/image.jpg" alt="digi" />
          <div class="contenttext">
            Digitrove is a global leader in next-generation digital services in the digital art industry.We empower
            the business with our intricate tools that are generally time comsuming to customize, easily available
            and compatable to multiple softwares to deliver unprecedented levels of performance and customer delight. 
            Our always-improving agenda drives the continuous development and creation of newer tools with hyper-realistic 
            details and unimaginable colours using the user preference and modification data, for better expirience.
            <br/>
            <h1>Every digital artist's Heaven </h1>
            In the past 6 years, Digitrove has stayed as a vital resourse platform for budding beginners and 
            even professionals worldwide. 
            <br/>
            Our mission is to provide high end digital devices and compatable
            software tools for digital artists to create precise and detailed artworks with ease.
            <h1>Features</h1>
            <ul>
              <li>Best available digipad and stylus</li>
              <li>Downloadable and customizable Brush styles</li>
              <li>Unique individual colors and color palettes</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Thedigitrove.Ubisoft.org, Developed by Kaushika Anandharaman.
      </div>
    </div>
  </body>
</html>
~~~
## Products Page html
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Thedigitrove/products</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactpg.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">
          <h2 class="heading2">OUR PREMIUM PRODUCTS</h2>
          <h3 class="heading2"><u>DRAWING-PADS AND STYLUS</u></h3>
          <div class="productitems">
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod1.jpg" alt="product 1">
              </div>
              <div class="itemname">Office Art Digital Graphics Drawing Tablet Board</div>
              <div class="itemprice">Price: Rs.19,446.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod2.jpg" alt="product 2">
              </div>
              <div class="itemname">Multi-function Handwriting Digital Stylus</div>
              <div class="itemprice">Price: Rs.10,550</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod3.jpeg" alt="product 3">
              </div>
              <div class="itemname">Digital graphics touchpad for PC/Laptop</div>
              <div class="itemprice">Price: Rs.8,000</div>
            </div>
            <br/>
            <h2 class="heading2"><u>Brush Collections</u></h2>
            <br/>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod4.jpg" alt="product 4">
              </div>
              <div class="itemname">Glitz-Pink</div>
              <div class="itemprice">Price: Rs.1500.00</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
            <img src="./img/prod5.jpg" alt="product 5">
            </div>
            <div class="itemname">Glitz-Black</div>
            <div class="itemprice">Price:Rs.1500.00</div>
          </div>
          <div class="productitem">
            <div class="itemimage">
            <img src="./img/prod6.jpg" alt="product 6">
            </div>
            <div class="itemname">Glitz-Rose gold</div>
            <div class="itemprice">Price: Rs.1500.00</div>
          </div>
          <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod7.jpg" alt="product 7">
              </div>
              <div class="itemname">Monochrome B&W</div>
              <div class="itemprice">Price: Rs.999.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod8.jpg" alt="product 8">
              </div>
              <div class="itemname">Natural Curls</div>
              <div class="itemprice">Price: Rs.2300.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod9.jpg" alt="product 9">
              </div>
              <div class="itemname">Classic Locks</div>
              <div class="itemprice">Price: Rs.895.00</div>
            </div>
            <br/>
            <h2 class="heading2"><u>Color Palettes</u></h2>
            <br/>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod10.jpg" alt="product 10">
              </div>
              <div class="itemname">Fall Series</div>
              <div class="itemprice">Price: Rs.975.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod11.jpg" alt="product 11">
              </div>
              <div class="itemname">Winter Series</div>
              <div class="itemprice">Price: Rs.975.00</div>
            </div>
            <div class="productitem">
              <div class="itemimage">
              <img src="./img/prod12.jpg" alt="product 12">
              </div>
              <div class="itemname">Dark Academia</div>
              <div class="itemprice">Price: Rs.975.00</div>
            </div>
          </div>
        </div>
      </div>      
      <div class="footer">
        Copyright &#169;2021 Thedigitrove.Ubisoft.org, Developed by Kaushika Anandharaman.
      </div>
    </div>
  </body>
</html>

~~~
## People Page html
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Thedigitrove/people</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/logo.png" type="image/x-icon" />    
    </head>

    <body>
        <div class="container">
            <div class="banner"></div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>    
                <div class="menuitem"><a href="/static/products.html">Products</a></div>   
                <div class="menuitemselected"><a href="/static/people.html">People</a></div>  
                <div class="menuitem"><a href="/static/contactpg.html">Contact Us</a></div>           
            </div>
            <div class="content">
                <div class="peoplecontent">
                    <h2 class="heading2"><u>Foundation Team</u></h2>
                    <div class="peoplepics">
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/people1.jpg" alt="peo1">
                            </div>
                            <div class="peoplename">Ms.Sara Ludy</div>
                            <div class="peopledes">Chairperson</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/people2.jpg" alt="peo2">
                            </div>
                            <div class="peoplename">Mr.Lev Manovich</div>
                            <div class="peopledes">President</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/people3.jpg" alt="peo3">
                            </div>
                            <div class="peoplename">Ms.Mehda Srinivastava</div>
                            <div class="peopledes">Head of HR Department</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/people4.jpg" alt="peo4">
                            </div>
                            <div class="peoplename">Ms.Seo DalMi</div>
                            <div class="peopledes">Chief Executive Officer</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/people5.jpg" alt="peo5">
                            </div>
                            <div class="peoplename">Mr.Nam DoSan</div>
                            <div class="peopledes">Chief Technology Officer</div>
                        </div>
                        <div class="peoplepic">
                            <div class="peopleimage">
                                <img src="./img/people6.jpg" alt="peo6">
                            </div>
                            <div class="peoplename">Mr.Ganesh S</div>
                            <div class="peopledes">Head of Management and Finances Department</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169;2021 Thedigitrove.Ubisoft.org, Developed by Kaushika Anandharaman.
              </div>
            </div>
    </body>
</html>
~~~
## Contact Us Page html
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Thedigitrove/Contact Us</title>
        <link rel="stylesheet" href="./css/layout.css" />
        <link rel="icon" href="./img/logo.png" type="image/x-icon" />    
    </head>

    <body>
        <div class="container">
            <div class="banner">
            </div>
            <div class="menu">
                <div class="menuitem"><a href="/static/home.html">Home</a></div>    
                <div class="menuitem"><a href="/static/products.html">Products</a></div>   
                <div class="menuitem"><a href="/static/people.html">People</a></div>  
                <div class="menuitemselected"><a href="/static/contactpg.html">Contact Us</a></div>           
            </div>
            <div class="content">
                <div class="contactcontent">
                    <div class="contactitems">
                        <div class="contactitem">
                            <h2><u>Contact Us</u></h2>
                            <h3>Head Quarters- Global</h3>
                            <div class="address">1 Hacker Way,<br/>
                                 Menlo Park,<br/>
                                 CA 94025,<br/>
                                 United States</div>
                            <div class="number">phone: +1 650-543-4834 </div>
                            <div class="email">E-mail: Thedigitrove@Ubisoft.com</div>
                            <div class="socials">Instagram/Twitter/Facebook: @The_Digitrove_USA</div>

                            <h3>Regional Head Quarters-London,UK</h3>
                            <div class="address">42 Earlham St,<br/>
                                London WC2H 9LA,<br/>
                                 CA 94025,<br/>
                                 United Kingdom</div>
                            <div class="number">phone: +44 (0) 20 7234 3456 </div>
                            <div class="email">E-mail: ThedigitroveUK@Ubisoft.com</div>
                            <div class="socials">Instagram/Twitter/Facebook: @The_Digitrove_UK</div>

                            <h3>Regional Head Quarters-Seoul,South Korea</h3>
                            <div class="address">42 Teheran-ro 108-gil,  <br/>
                                Daechi-dong,<br/>
                                Gangnam-gu,Seoul,<br/>
                                South Korea</div>
                            <div class="number">phone: +82 2 312 3456 </div>
                            <div class="email">E-mail: ThedigitroveKor@Ubisoft.com</div>
                            <div class="socials">Instagram/Twitter/Facebook: @The_Digitrove_Kor</div>

                            <h3>Regional Head Quarters-Chennai,India</h3>
                            <div class="address"> 60,Krishna Block Rajaji Salai,<br/>
                                Opp.Dist.Collectorate,<br/>
                                Chennai,<br/>
                                Tamil Nadu 600001</div>
                            <div class="number">phone: +91 57853 22746 </div>
                            <div class="email">E-mail: ThedigitroveIndia@Ubisoft.com</div>
                            <div class="socials">Instagram/Twitter/Facebook: @The_Digitrove_India</div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 Thedigitrove.Ubisoft.org, Developed by Kaushika Anandharaman.
            </div>
        </div>
    </body>

</html>
~~~
## OUTPUT:

## Home Page:
![Output](./images/output.png)
## Products Page:
![output2](./images/output2.png)
## People Page:
![GitHub Logo](./images/output3.png)
## Contact Us Page:
![output4](./images/output4.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
