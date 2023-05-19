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
##home.html:
```python
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content">
        <h1 id="home-h" >THINK DIFFERENT.</h1>
        <p id="home-p">Everything is designed. Few things are designed well. And those are designed by us.</p>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by Chandru.
      </div>
    </div>
  </body>
</html>
```
##about.html:
```python
{% load static %}

<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Apple</title>
    <link rel="stylesheet" href="{% static 'css/layout.css' %}" />
    <link rel="icon" href="https://alchemyimmersive.com/wp-content/uploads/sites/4/2020/04/apple-logo-transparent.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"></div>
      <div class="menu">
        <div class="menuitem fill"><a href="/home">Home</a></div>
        <div class="menuitem fill"><a href="/about">About</a></div>
        <div class="menuitem fill"><a href="/products">Products</a></div>
        <div class="menuitem fill"><a href="/people">People</a></div>
        <div class="menuitem fill"><a href="/contact">Contact Us</a></div>
      </div>
      <div class="content p-con">
        <h1 style="margin:auto;margin-top:50px;font-size:50px;">About Us</h1><br><br>
        <p id="about-p">Apple is an American technology company founded by Steve Jobs, Steve Wozniak, and Ronald Wayne in April 1976. Incorporated in 1977, the company was one of the early manufacturers of personal computing devices with graphical user interface. Over the years, the company also forayed into other consumer electronics segments like mobile communication devices, digital music players, notebooks, and wearables. The company also develops and markets a range of related software and services, accessories, and networking solutions. Currently, the company’s chief executive officer (CEO) is Timothy Donald Cook, commonly known as Tim Cook.
            <br><br>
            From smart wearables to digital content streaming platforms, Apple offers a wide range of products and services within a closed ecosystem. Its products include iMac desktops, MacBook notebooks, iPhone mobile devices, iPad tablets, iPod digital multimedia devices, Apple Watch and Apple TV. The services include iOS operating system for mobile devices, macOS operating system for notebooks and desktops, iCloud online storage, tvOS operating system for Apple TV, watchOS operating system for Apple Watch, iTunes for digital content services, Apple Pay digital payment service, Apple Music for online multimedia streaming, and Apple News.
            <br><br>
            Apple has been known to be on the forefront of innovation. The company was among the first to develop an app-based ecosystem for smartphones. It was the first smartphone maker to introduce touchID — a fingerprint scanner module to unlock a device — and use 64-bit processors, both of which were later also adopted by most other smartphone manufacturers.
            <br><br>
            Apple’s services have so far been exclusive to its own products. However, in March 2019, the company announced that its subscription-based TV Plus service will be available as an app on televisions from other brands, too. This is for the first time that Apple has enabled its ecosystem service to work on products from other brands, and more announcements of similar nature are expected in future.
            <br><br>
            In 2019, Apple also settled its long-pending legal battle with American chipmaker Qualcomm. The move came after the company found itself in a tight spot securing 5G chips to power its future devices. With Qualcomm on board, the company is expected to bring its first 5G-ready smartphone by 2020.</p>
            <br><br>
      </div>
      <div class="footer">
        &#169; 2021 Apple Lt., Developed by Chandru.
      </div>
    </div>
  </body>
</html>
```
##people.html:
```python
                <div class="profile-info">
                    <h3 class="profile-name">Jonny Sins</h3>
                    <p class="profile-desc">All Rounder</p>
                </div>
            </div>
            <div class="profile-card-body">
                <ul class="status">
                    <li>
                        <span class="status-value">751</span>
                        <span class="status-text">Posts</span>
                    </li>
        
                    <li>
                        <span class="status-value">1.8m</span>
                        <span class="status-text">Followers</span>
                    </li>
        
                    <li>
                        <span class="status-value">4</span>
                        <span class="status-text">Following</span>
                    </li>
                </ul>
        
                <div class="action">
                    <button class="btn btn-pink">Follow</button>
                    <button class="btn btn-gray-outline">Message</button>
                </div>
            </div>
        </div>
        <div class="profile-card">
            <div class="profile-card-header">
                <div class="profile-image" ></div>
                <div class="profile-info">
                    <h3 class="profile-name">Powervel</h3>
                    <p class="profile-desc">Developer/Conent Creator</p>
                </div>
            </div>
            <div class="profile-card-body">
                <ul class="status">
                    <li>
                        <span class="status-value">532</span>
                        <span class="status-text">Posts</span>
                    </li>
        
                    <li>
                        <span class="status-value">1.5m</span>
                        <span class="status-text">Followers</span>
                    </li>
        
                    <li>
                        <span class="status-value">423</span>
                        <span class="status-text">Following</span>
                    </li>
                </ul>
        
                <div class="action">
                    <button class="btn btn-pink">Follow</button>
                    <button class="btn btn-gray-outline">Message</button>
                </div>
            </div>
        </div>
        <div class="profile-card">
            <div class="profile-card-header">
                <div class="profile-image" style="background-image: url('https://m.media-amazon.com/images/M/MV5BNzg1MTUyNDYxOF5BMl5BanBnXkFtZTgwNTQ4MTE2MjE@._V1_.jpg');"></div>
        
                <div class="profile-info">
                    <h3 class="profile-name">RDJ</h3>
                    <p class="profile-desc">Genius, billionaire,philanthropist.</p>
                </div>
            </div>
            <div class="profile-card-body">
                <ul class="status">
                    <li>
                        <span class="status-value">532</span>
                        <span class="status-text">Posts</span>
                    </li>
        
                    <li>
                        <span class="status-value">1.5m</span>
                        <span class="status-text">Followers</span>
                    </li>
        
                    <li>
                        <span class="status-value">423</span>
                        <span class="status-text">Following</span>
                    </li>
                </ul>
        
                <div class="action">
                    <button class="btn btn-pink">Follow</button>
                    <button class="btn btn-gray-outline">Message</button>
                </div>
            </div>
        </div>
        <div class="profile-card">
            <div class="profile-card-header">
                <div class="profile-image" style="background-image: url('https://file1.telestar.fr/var/telestar/storage/images/3/3/2/3/3323904/chris-evans-comment-failli-refuser-role-vie.jpg?alias=exact1024x768_l');"></div>
        
                <div class="profile-info">
                    <h3 class="profile-name">Cris Evans</h3>
                    <p class="profile-desc">Conent Creator</p>
                </div>
            </div>
            <div class="profile-card-body">
                <ul class="status">
                    <li>
                        <span class="status-value">532</span>
                        <span class="status-text">Posts</span>
                    </li>
        
                    <li>
                        <span class="status-value">1.5m</span>
                        <span class="status-text">Followers</span>
                    </li>
        
                    <li>
                        <span class="status-value">423</span>
                        <span class="status-text">Following</span>
                    </li>
                </ul>
        
                <div class="action">
                    <button class="btn btn-pink">Follow</button>
                    <button class="btn btn-gray-outline">Message</button>
                </div>
            </div>
        </div>
        <div class="profile-card">
            <div class="profile-card-header">
                <div class="profile-image" style="background-image: url('https://image.gala.de/21743318/t/N_/v12/w960/r0.6667/-/elizabeth-olsen.jpg');"></div>
        
                <div class="profile-info">
                    <h3 class="profile-name">Elizabeth Olsen</h3>
                    <p class="profile-desc">Developer</p>
                </div>
            </div>
            <div class="profile-card-body">
                <ul class="status">
                    <li>
                        <span class="status-value">532</span>
                        <span class="status-text">Posts</span>
                    </li>
        
                    <li>
                        <span class="status-value">1.5m</span>
                        <span class="status-text">Followers</span>
                    </li>
        
                    <li>
                        <span class="status-value">423</span>
                        <span class="status-text">Following</span>
                    </li>
                </ul>
        
                <div class="action">
                    <button class="btn btn-pink">Follow</button>
                    <button class="btn btn-gray-outline">Message</button>
                </div>
            </div>
        </div>
        <div class="profile-card">
            <div class="profile-card-header">
                <div class="profile-image" style="background-image: url('https://a1cf74336522e87f135f-2f21ace9a6cf0052456644b80fa06d4f.ssl.cf2.rackcdn.com/images/characters/large/800/Bruce-Banner.The-Incredible-Hulk.webp');"></div>
                <div class="profile-info">
                    <h3 class="profile-name">Bruce Banner</h3>
                    <p class="profile-desc">Scientist</p>
                </div>
            </div>
            <div class="profile-card-body">
                <ul class="status">
                    <li>
                        <span class="status-value">532</span>
                        <span class="status-text">Posts</span>
                    </li>
        
                    <li>
                        <span class="status-value">1.5m</span>
                        <span class="status-text">Followers</span>
                    </li>
        
                    <li>
                        <span class="status-value">423</span>
                        <span class="status-text">Following</span>
                    </li>
                </ul>
        
                <div class="action">
                    <button class="btn btn-pink">Follow</button>
                    <button class="btn btn-gray-outline">Message</button>
                </div>
            </div>
        </div>
    </div>
  </div>
  <div class="footer">
    &#169; 2021 Apple Lt., Developed by Chandru.
  </div>
</div>
```
##products.html
```python
      </div>
      <div class="product-card">
        <div class="badge new">New</div>
        <div class="product-tumb">
          <img src="{% static 'img/pro/airpods.jpg' %}" alt="">
        </div>
        <div class="product-details">
          <span class="product-catagory">Airpods</span>
          <h4><a href="">Apple Airpods Pro</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
          <div class="product-bottom-details">
            <div class="product-price"><small>$96.00</small>$230.99</div>
            <div class="product-links">
              <a href=""><i class="fa fa-heart"></i></a>
              <a href=""><i class="fa fa-shopping-cart"></i></a>
            </div>
          </div>
        </div>
      </div>
      <div class="product-card">
        <div class="badge">Hot</div>
        <div class="product-tumb">
          <img src="{% static 'img/pro/macair.jpg' %}" alt="">
        </div>
        <div class="product-details">
          <span class="product-catagory">Laptop</span>
          <h4><a href="">Macbook Air</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
          <div class="product-bottom-details">
            <div class="product-price"><small>$96.00</small>$230.99</div>
            <div class="product-links">
              <a href=""><i class="fa fa-heart"></i></a>
              <a href=""><i class="fa fa-shopping-cart"></i></a>
            </div>
          </div>
        </div>
      </div>
      <div class="product-card">
        <div class="badge">Hot</div>
        <div class="product-tumb">
          <img src="{% static 'img/pro/watch.jpg' %}" alt="">
        </div>
        <div class="product-details">
          <span class="product-catagory">IWatch</span>
          <h4><a href="">Apple Watch</a></h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
          <div class="product-bottom-details">
            <div class="product-price"><small>$96.00</small>$230.99</div>
            <div class="product-links">
              <a href=""><i class="fa fa-heart"></i></a>
              <a href=""><i class="fa fa-shopping-cart"></i></a>
            </div>
          </div>
        </div>
    </div>
    <div class="product-card">
      <div class="badge">Hot</div>
      <div class="product-tumb">
        <img src="{% static 'img/pro/tv.png' %}" alt="">
      </div>
      <div class="product-details">
        <span class="product-catagory">Monitor</span>
        <h4><a href="">Apple Monitor</a></h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
        <div class="product-bottom-details">
          <div class="product-price"><small>$96.00</small>$230.99</div>
          <div class="product-links">
            <a href=""><i class="fa fa-heart"></i></a>
            <a href=""><i class="fa fa-shopping-cart"></i></a>
          </div>
        </div>
      </div>
    </div>
    <div class="product-card">
      <div class="badge">Hot</div>
      <div class="product-tumb">
        <img src="{% static 'img/pro/tab.jpg' %}" alt="">
      </div>
      <div class="product-details">
        <span class="product-catagory">Tab</span>
        <h4><a href="">Apple Tablet</a></h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
        <div class="product-bottom-details">
          <div class="product-price"><small>$96.00</small>$230.99</div>
          <div class="product-links">
            <a href=""><i class="fa fa-heart"></i></a>
            <a href=""><i class="fa fa-shopping-cart"></i></a>
          </div>
        </div>
      </div>
    </div>
    <div class="product-card">
      <div class="badge">Hot</div>
      <div class="product-tumb">
        <img src="{% static 'img/pro/14pro.jpg' %}" alt="">
      </div>
      <div class="product-details">
        <span class="product-catagory">Mobile</span>
        <h4><a href="">IPhone 14 Pro</a></h4>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
        <div class="product-bottom-details">
          <div class="product-price"><small>$96.00</small>$230.99</div>
          <div class="product-links">
            <a href=""><i class="fa fa-heart"></i></a>
            <a href=""><i class="fa fa-shopping-cart"></i></a>
          </div>
        </div>
      </div>

  </div>
  <div class="product-card">
    <div class="badge">Hot</div>
    <div class="product-tumb">
      <img src="{% static 'img/pro/13.jpg' %}" alt="">
    </div>
    <div class="product-details">
      <span class="product-catagory">Mobile</span>
      <h4><a href="">IPhone 14</a></h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
      <div class="product-bottom-details">
        <div class="product-price"><small>$96.00</small>$230.99</div>
        <div class="product-links">
          <a href=""><i class="fa fa-heart"></i></a>
          <a href=""><i class="fa fa-shopping-cart"></i></a>
        </div>
      </div>
    </div>
  </div>
  <div class="product-card">
    <div class="badge">Hot</div>
    <div class="product-tumb">
      <img src="{% static 'img/pro/11.jpg' %}" alt="">
    </div>
    <div class="product-details">
      <span class="product-catagory">Mobile</span>
      <h4><a href="">IPhone 11</a></h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
      <div class="product-bottom-details">
        <div class="product-price"><small>$96.00</small>$230.99</div>
        <div class="product-links">
          <a href=""><i class="fa fa-heart"></i></a>
          <a href=""><i class="fa fa-shopping-cart"></i></a>
        </div>
      </div>
    </div>
  </div>
  <div class="product-card">
    <div class="badge">Hot</div>
    <div class="product-tumb">
      <img src="{% static 'img/pro/7.jpg' %}" alt="">
    </div>
    <div class="product-details">
      <span class="product-catagory">Mobile</span>
      <h4><a href="">IPhone 7</a></h4>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
      <div class="product-bottom-details">
        <div class="product-price"><small>$96.00</small>$230.99</div>
        <div class="product-links">
          <a href=""><i class="fa fa-heart"></i></a>
          <a href=""><i class="fa fa-shopping-cart"></i></a>
        </div>
      </div>
    </div>

</div>
<div class="product-card">
  <div class="badge">Hot</div>
  <div class="product-tumb">
    <img src="{% static 'img/pro/12mini.jpg' %}" alt="">
  </div>
  <div class="product-details">
    <span class="product-catagory">Mobile</span>
    <h4><a href="">IPhone 12 Mini</a></h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
    <div class="product-bottom-details">
      <div class="product-price"><small>$96.00</small>$230.99</div>
      <div class="product-links">
        <a href=""><i class="fa fa-heart"></i></a>
        <a href=""><i class="fa fa-shopping-cart"></i></a>
      </div>
    </div>
  </div>
</div>
<div class="product-card">
  <div class="badge">Hot</div>
  <div class="product-tumb">
    <img src="{% static 'img/pro/se.png' %}" alt="">
  </div>
  <div class="product-details">
    <span class="product-catagory">Mobile</span>
    <h4><a href="">IPhone SE</a></h4>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vero, possimus nostrum!</p>
    <div class="product-bottom-details">
      <div class="product-price"><small>$96.00</small>$230.99</div>
      <div class="product-links">
        <a href=""><i class="fa fa-heart"></i></a>
        <a href=""><i class="fa fa-shopping-cart"></i></a>
      </div>
    </div>
  </div>
</div>
  </div>
  <div class="footer">
    &#169; 2021 Apple Lt., Developed by Chandru.
  </div>
</div>
```
## OUTPUT:
![image](https://github.com/prithviraj5703/productcompanywebsite/assets/121418418/ccb3b79d-8319-48ee-85fa-fb622b268e6c)
![image](https://github.com/prithviraj5703/productcompanywebsite/assets/121418418/1cde10d3-7ac1-490b-a28b-46c06149611d)
![image](https://github.com/prithviraj5703/productcompanywebsite/assets/121418418/75c7378f-f0ce-4b2c-b500-4f7b39a05216)
![image](https://github.com/prithviraj5703/productcompanywebsite/assets/121418418/fb5ca958-27be-4edb-8aa8-e08e45da5036)


### Home Page:

![output](./images/homepage.jpg)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
