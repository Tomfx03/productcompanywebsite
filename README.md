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
Home.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="./home.html">Home</a></div>
        <div class="menuitem"><a href="./products.html">Products</a></div>
        <div class="menuitem"><a href = "./people.html">People</a></div>
        <div class="menuitem"><a href = "./contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            At Edusoft, we take pride in being a leading provider of high-quality
            tally books that cater to a diverse range of industries and professionals.
            Our commitment to excellence, innovation, and customer satisfaction 
            sets us apart in the market, making us your go-to destination for all 
            your tally book needs.
            <br />
            Why Choose Edusoft?
            <ul>
              <li>Quality Assurance: Our tally books undergo rigorous quality checks to ensure accuracy and durability.</li>
              <li>Innovation: We embrace new technologies and offer customizable solutions to streamline your work.</li>
              <li>Customer-Centric: Your satisfaction is our priority.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Meyyappan.
      </div>
    </div>
  </body>
</html>
```
product.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="./home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="./products.html">Products</a>
        </div>
        <div class="menuitem"><a href="./people.html">People</a></div>
        <div class="menuitem"><a href="./contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_gold.png" alt="product image">
                  </div>
                  <div class="itemname">Tally Gold</div>
                  <div class="itemprice">Price: Rs.40,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/tally_silver.png"  alt="product image">
                  </div>
                  <div class="itemname">Tally Silver</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="./img/platinum_pic.jpeg"  alt="product image">
                </div>
                <div class="itemname">Tally Platinum</div>
                <div class="itemprice">Price: Rs.70,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="./img/diamond.jpeg"  alt="product image">
                </div>
                <div class="itemname">Tally diamond</div>
                <div class="itemprice">Price: Rs.100,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="./img/red_diamond.png"  alt="product image">
                </div>
                <div class="itemname">Tally red diamond</div>
                <div class="itemprice">Price: Rs.200,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="./img/emerald.jpeg"  alt="product image">
                </div>
                <div class="itemname">Emerald</div>
                <div class="itemprice">Price: Rs.50,000.00 </div>
              </div>
          </div>
          </div>
      
        <h1>Our Other Items</h1>  
        <div class="productitem"> 
          <div class="itemimage">
          <img src="./img/cement.jpeg"  alt="product image">
          </div>
          <div class="itemname">Cement</div>
          <div class="itemprice">Price: Rs.1000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="./img/diamond.jpeg"  alt="product image">
          </div>
          <div class="itemname">Tally diamond</div>
          <div class="itemprice">Price: Rs.5000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="./img/tile1.jpeg"  alt="product image">
          </div>
          <div class="itemname">Ceramic tile</div>
          <div class="itemprice">Price: Rs.5000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="./img/tile2.jpeg"  alt="product image">
          </div>
          <div class="itemname">Tally tile</div>
          <div class="itemprice">Price: Rs.4000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="./img/tile3.jpeg"  alt="product image">
          </div>
          <div class="itemname">Rich tile</div>
          <div class="itemprice">Price: Rs.8000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="./img/tile5.jpeg"  alt="product image">
          </div>
          <div class="itemname">Plain as day tile</div>
          <div class="itemprice">Price: Rs.2000.00 </div>
        </div>     
      </div>
      <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Meyyappan.
      </div>
    </div>
  </body>
</html>
```
people.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="./home.html">Home</a></div>
        <div class="menuitem"><a href="./products.html">Products</a></div>
        <div class="menuitemselected"><a href = "./people.html">People</a></div>
        <div class="menuitem"><a href = "./contactus.html">Contact Us</a></div>
      </div>
    <div class="content">
      <div class="productcontent">    
        <h1>Our Staff !!</h1>
        <div class="productitems">
            <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/modi_pic.jpeg.crdownload"  alt="product image">
              </div>
              <div class="itemname">Modi - CEO</div> 
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/andrew_tate_pic.png"  alt="product image">
              </div>
              <div class="itemname">Tate-2 - Infulencer</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/trump_pic.png"  alt="product image">
              </div>
              <div class="itemname">Trump - HR</div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/priyanka_pic.png"  alt="product image">
              </div>
              <div class="itemname">Priyanka Mohan - Mascot</div>  
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/maran_pic.png"  alt="product image">
              </div>
              <div class="itemname">Blue Sattai Marran - Advertizer</div>  
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="./img/mona_pipc.png"  alt="product image">
              </div>
              <div class="itemname">Mona Lisa - Useless</div>
            </div>
        </div>
      </div>        
    </div>
    <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Meyyappan .
    </div>
    </div>
  </body>
</html>
```
contactus.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>EduSoft Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">EduSoft Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="./home.html">Home</a></div>
        <div class="menuitem"><a href="./products.html">Products</a></div>
        <div class="menuitem"><a href = "./people.html">People</a></div>
        <div class="menuitemselected"><a href = "./contactus.html">Contact Us</a></div>
      </div>
    <div class="content">
        <div class="contactcontent">
          <h1>Contact Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contcontenttext">
                      We value your interest in Edusoft. If you want any kind of assistance regarding our services, reach out to us !!
            <br>
            <br>
            <b><u>Contact Information:</u></b>
            <br>
            <b><u>Email --></u></b> edusoft.help@gmail.com<br><br>

            Feel free to reach out to us via email at the address provided above, Or Just Call <b>044-4050-4000</b><br><br>

            <b><u>Office Address:</u></b><br>

            <b><i>*****Edusoft Private Limited*****</i></b><br>

                                                                         <pre>                                                             42 Wallaby Way, Sydney, Australia<br></pre>

                                                                         <b><u>Customer Support</u></b><br><br>

                                                                         For technical support or assistance with our products and services, please contact our support team at <u>edusoft.help@gmail.com</u>.<br><br>

                                                                         <b><u>Feedback and Suggestions:</u></b><br><br>

                                                                         We appreciate your feedback and suggestions. Feel free to share your thoughts by emailing us at edusoft.help@gmail.com.<br><br>

                                                                        <b> Thank you for choosing Edusoft Private Limited. We look forward to hearing from you and assisting you on your educational journey!</b>
          </div>
        </div>
      </div>
    <div class="footer">
        Copyright &#169; 2021 EduSoft Private Limited, Developed by Meyyappan .
    </div>
    </div>
  </body>
</html>
    
```

## OUTPUT:

### Home Page:

q

### Products page:
q

### People page:

q
### Contact_us page:

q

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
