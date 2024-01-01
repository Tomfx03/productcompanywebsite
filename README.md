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

1) Banner was changed.
2) 12 products (tally books) were added.
3) 6 users were added to the staff page.
4) Contact address, email were added in the contact us section.

### Step 4:

Choose the appropriate style and color scheme.

--> The Color scheme used in this website was a combination of yellow and light blue for content area, and a dark blue colour for menu text and footer text.

### Step 5:

Validate the layout in various browsers.
@@ -36,11 +43,479 @@ Publish the website in the given URL.

## PROGRAM :

  ### CSS LAYOUT CODE :

    {
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }
    body {
      background-color: whitesmoke;
      color: #000000;
    }
    .container {
      width: 1080px;
      margin-left: auto;
      margin-right: auto;
      border-width: 1px 1px 1px 1px;
      border-style: solid;
      box-shadow: 15px 15px 8px rgb(0, 0, 0);
    }

    .banner {
      display: block;
      width: 100%;
      height: 250px;
      text-align: center;
      font-size: 60px;
      background-image: url("/static/img/banner.jpg");
      background-size: 100% 100%;
      margin: 0px 0px 0px 0px;
      padding-top: 150px;
      color: #0f0f0f;
    }

    .menu {
      display: block;
      width: 100%;
      height: 50px;
      font-size: larger;
      background-color:#07eeff;
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
      color:rgb(236, 221, 88);
    }

    .menuitem a {
      text-decoration: none;
      color: #00225d;
    }

    .content {
      display: block;
      width: 100%;
      background-color: #f2dd69;
      min-height: 500px;
      margin: 0px 0px 0px 0px;
      border-width: 1px;
      border-color: white;
      border-style: solid;
    }
    .homecontent {
      min-height: 500px;
      margin: 10px 10px 10px 10px;
      background-color:#f2dd69;
    }
    .homecontent h1 {
      text-align: left;
    }
    .homecontent img {
      float: right;
      width: 400px;
      height: 300px;
      margin-left: 10px;
    }

    .contenttext {
      text-align: justify;
      font-size:x-large;
    }

    .contactcontent {
      min-height: 500px;
      margin: 10px 10px 10px 10px;
    }
    .contactcontent h1 {
      text-align: center;
    }
    .contactcontent img {
      float: left;
      width: 400px;
      height: 300px;
      margin-left: 10px;
    }

    .contcontenttext {
      text-align: justify;
      font-size:x-large;
    }

    .productcontent {
      min-height: 500px;
      margin: 10px 10px 10px 10px;
    }

    .productcontent h1 {
      text-align: left;
    }

    .productitems {
      display:block;
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

    .footer {
      display: block;
      width: 100%;
      height: 40px;
      background-color: #07eeff;
      text-align: center;
      padding-top: 10px;
      margin: 0px 0px 0px 0px;
      color: #00225d;
    }


## HTML CODE:

   ### 1) home.html

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
                <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
                <div class="menuitem"><a href="/static/products.html">Products</a></div>
                <div class="menuitem"><a href = "/static/people.html">People</a></div>
                <div class="menuitem"><a href = "/static/contactus.html">Contact Us</a></div>
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
                Copyright &#169; 2021 EduSoft Private Limited, Developed by Shri Sai Aravind.R.
              </div>
            </div>
          </body>
        </html>

   ### 2) products.html

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
                <div class="menuitem"><a href="/static/home.html">Home</a></div>
                <div class="menuitemselected">
                  <a href="/static/products.html">Products</a>
                </div>
                <div class="menuitem"><a href = "/static/people.html">People</a></div>
                <div class="menuitem"><a href = "/static/contactus.html">Contact Us</a></div>
              </div>
              <div class="content">
                <div class="productcontent">    
                  <h1>Our Premium Products</h1>
                  <div class="productitems">
                      <div class="productitem"> 
                          <div class="itemimage">
                          <img src="/static/img/tally_gold.png" alt="product image" >
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
                        <img src="/static/img/Tallyprime.png"  alt="product image">
                        </div>
                        <div class="itemname">Tally Prime</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/tally-erp9.png"  alt="product image">
                        </div>
                        <div class="itemname">Tally erp 9</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/book-03.jpg"  alt="product image">
                        </div>
                        <div class="itemname">Tally Essential</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/payroll.png"  alt="product image">
                        </div>
                        <div class="itemname">Payroll Using Tally Prime</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/accounting.png"  alt="product image">
                        </div>
                        <div class="itemname">Accounting Using Tally Prime</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/comdex.png"  alt="product image">
                        </div>
                        <div class="itemname">Comdex - Tally erp 9</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/comdex1.png"  alt="product image">
                        </div>
                        <div class="itemname">Comdex - Computer and Financial accounting using Tally 9</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/comdex2.png"  alt="product image">
                        </div>
                        <div class="itemname">Comdex - Business accounting using MS Excel and Tally 9</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/inventory.png"  alt="product image">
                        </div>
                        <div class="itemname">Basic accounting And Inventory using Tally 9</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                      <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/tallynew.png"  alt="product image">
                        </div>
                        <div class="itemname">Tally Prime - With all new features</div>
                        <div class="itemprice">Price: Rs.15,000.00 </div>  
                      </div>
                  </div>
                  </div>        
              <div class="footer">
                Copyright &#169; 2021 EduSoft Private Limited, Developed by Shri Sai Aravind.R.
              </div>
            </div>
            </div>
          </body>
        </html>

   ### 3) people.html

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
                <div class="menuitem"><a href="/static/home.html">Home</a></div>
                <div class="menuitem"><a href="/static/products.html">Products</a></div>
                <div class="menuitemselected"><a href = "/static/people.html">People</a></div>
                <div class="menuitem"><a href = "/static/contactus.html">Contact Us</a></div>
              </div>
            <div class="content">
              <div class="productcontent">    
                <h1>Our Staff !!</h1>
                <div class="productitems">
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="/static/img/person1.jpeg"  alt="product image">
                      </div>
                      <div class="itemname">Aravind - CEO</div> 
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="/static/img/person2.jpeg"  alt="product image">
                      </div>
                      <div class="itemname">person-2 - Head developer</div>
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="/static/img/person3.jpeg"  alt="product image">
                      </div>
                      <div class="itemname">person-3 - HR</div>
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="/static/img/person4.jpeg"  alt="product image">
                      </div>
                      <div class="itemname">person-4 - Project manager</div>  
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="/static/img/person5.jpeg"  alt="product image">
                      </div>
                      <div class="itemname">person-5 - Receptionist</div>  
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                      <img src="/static/img/person6.jpeg"  alt="product image">
                      </div>
                      <div class="itemname">person-6 - Salesman</div>
                    </div>
                </div>
              </div>        
            </div>
            <div class="footer">
                Copyright &#169; 2021 EduSoft Private Limited, Developed by Shri Sai Aravind.R .
            </div>
            </div>
            </body>
            </html>

   ### 4) contactus.html

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
                  <div class="menuitem"><a href="/static/home.html">Home</a></div>
                  <div class="menuitem"><a href="/static/products.html">Products</a></div>
                  <div class="menuitem"><a href = "/static/people.html">People</a></div>
                  <div class="menuitemselected"><a href = "/static/contactus.html">Contact Us</a></div>
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

                      Feel free to reach out to us via email at the address provided above.<br><br>

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
                  Copyright &#169; 2021 EduSoft Private Limited, Developed by Shri Sai Aravind.R .
              </div>
              </div>
            </body>
          </html>


## OUTPUT:

### Home Page:
![image](https://github.com/gowriganeshns/productcompanywebsite/assets/101335832/97acf714-eec5-4930-ac3a-eebefa4bbff4)

### Products Page:

![image](https://github.com/gowriganeshns/productcompanywebsite/assets/101335832/101dc78f-4bef-4618-b9fa-63bd92e684c0)


### Staff Page

![image](https://github.com/gowriganeshns/productcompanywebsite/assets/101335832/8ae2802a-937e-438d-8c8d-70a5c53db543)

### Contact Us Page

![image](https://github.com/gowriganeshns/productcompanywebsite/assets/101335832/1d6fc37a-2b62-4cb6-bfa8-fff31b5ac818)

## Result:
Thus a website is designed for the software product company and the HTML,CSS code are validated.
