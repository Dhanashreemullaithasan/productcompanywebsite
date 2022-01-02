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
HOME PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GOOGLE PRODUCTS</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">GOOGLE PRODUCTS</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/ICONE.jpg" alt="Building" />
          <div class="contenttext">
            At Tally, we believe in the power of technology to make business
            owners efficient, empowered and happier, so they can focus on what
            matters most for their business. We design our products to focus on
            just that to make our products work for you, and not the other way
            around.
            <br />
            Our google product takes this to new level, making your job to easy.
             Our products  G mail is help to most widely used free email service 
             in the world, YouTube has become the second most-used search engine
             in the world and the first online video service, Google Maps is another
             of the most used products of Google that allows us to see the maps
             of any part of the world, even also the streets in some of the major
             cities through the Option of  Streetview. We are now  discover  the
             products much more useful and easy for you ,without doing hard work .
             There is greater flexibility as the product adapts to your business
             and your way  of working. The products also use your day to day life also.
             And this  products are only makes for you love the products and use it even more. 
             We want to satisfy your needs so we make the products and update it in the day to day . 
             So, kindly use it .
            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 GOOGLE PRODUCTS, Developed by DHANASHREE
      </div>
    </div>
  </body>
</html>
PRODUCT PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GOOGLE PRODUCTS</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">GOOGLE PRODUCTS</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/M1.png" alt="product image">
                  </div>
                  <div class="itemname">G MAIL</div>
                  <div class="itemprice">Price:Rs. 10,000</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/M2.png"  alt="product image">
                  </div>
                  <div class="itemname">GOOGLE MAP</div>
                  <div class="itemprice">Price:Rs.80,000</div>
              </div>

              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/M3.png"  alt="product image">
                  </div>
                  <div class="itemname">GOOGLE DRIVE</div>
                  <div class="itemprice">Price: Rs.70,000 </div>
              </div>

              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/M4.png"  alt="product image">
                </div>
                <div class="itemname">GOOGLE CALENDER</div>
                <div class="itemprice">Price: 50,000 </div>
            </div>

            <div class="productitem"> 
              <div class="itemimage">
              <img src="/static/img/M5.png"  alt="product image">
              </div>
              <div class="itemname">GOOGLE LENS</div>
              <div class="itemprice">Price: Rs.70,000 </div>
          </div>

          <div class="productitem"> 
            <div class="itemimage">
            <img src="/static/img/M6.png"  alt="product image">
            </div>
            <div class="itemname">GOOGLE MEET</div>
            <div class="itemprice">Price: Rs.80,000</div>
        </div>

        <div class="productitem"> 
          <div class="itemimage">
          <img src="/static/img/M7.png"  alt="product image">
          </div>
          <div class="itemname">YOUTUBE</div>
          <div class="itemprice">Price: Rs.50,000 </div>
      </div>

      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/M8.png"  alt="product image">
        </div>
        <div class="itemname">YOUTUBE MUSIC</div>
        <div class="itemprice">Price: Rs.60,000 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/M9.png"  alt="product image">
      </div>
      <div class="itemname">YOUTUBE TV</div>
      <div class="itemprice">Price: Rs.90,000 </div>
    </div>

    <div class="productitem"> 
       <div class="itemimage">
       <img src="/static/img/M10.png"  alt="product image">
       </div>
       <div class="itemname">GOOGLE CLASSROOM</div>
       <div class="itemprice">Price: Rs.20,000 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/M11.png"  alt="product image">
    </div>
       <div class="itemname">GOOGLE VOICE </div>
       <div class="itemprice">Price: Rs.70,000 </div>
    </div>

    <div class="productitem"> 
      <div class="itemimage">
      <img src="/static/img/M12.jpg"  alt="product image">
     </div>
        <div class="itemname">GOOGLE TASKS</div>
        <div class="itemprice">Price: Rs.20,000 </div>
      </div>
    </div>
  </div>        
  </div>
    <div class="footer">
      Copyright &#169; 2021 GOOGLE PRODUCTS, Developed by DHANASHREE
    </div>
  </div>
 </body>
</html>
CONTACT PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GOOGLE PRODUCTS</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">GOOGLE PRODUCTS</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      
        <div class="contact content">
           <h1>Our Contact Address</h1>  
        
          <div class="contacttext">
           Phone:6592001799
           <br>Eamail-address:e-martlimited@eemail.com
          </div>
        </div>

     
<div class="footer">
  Copyright &#169; 2021 GOOGLE PRODUCTS, Developed by DHANASHREE
</div>
</div>
</body>
</html>
PEOPLE PAGE:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GOOGLE PRODUCTS</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon2.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">GOOGLE PRODUCTS</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>  
        <div class="menuitemselected"><a href ="/static/people.html"></a>People</a></div>
        <div class="menuitem"><a href="/static/contact us.html">Contact Us</a></div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/P1.jpg"  alt="product image">
      </div>
         <div class="itemname">HEAD of the company
           <br>
           (Ram)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/P2.jpg"  alt="product image">
      </div>
         <div class="itemname">Manager
           <br>
           (Selvi)
         </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/P3.webp"  alt="product image">
      </div>
         <div class="itemname">Assistant class <br>(Berry)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/P4.jpg"  alt="product image">
      </div>
         <div class="itemname">Product Department Head <br> (Jhon)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/P5.jpg"  alt="product image">
      </div>
         <div class="itemname">Deliver Department Head <br> (Lakshmi)</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="/static/img/P6.jpg"  alt="product image">
      </div>
         <div class="itemname">Chennai Branch Head <br> (Dev)</div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 GOOGLE PRODUCTS, Developed by DHANASHREE
      </div>
    </div>
  </body>
</html>

## OUTPUT:

### Home Page:

![GitHub Logo](./image1.png)
### PRODUCT PAGE :

![GitHub Logo](./image2.png)

### PEOPLE PAGE :

![output](./image3.png)
### CONTACT PAGE :

![output](./image4.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
