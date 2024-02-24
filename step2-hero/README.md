# Step2-heroSection 😊
### 1.Below the header, create HTML5 semantic section tag with class="hero".start with sushi image, So create a div and that div will have a class="hero-image", within it create a self-closing image tag with src="images/sushi-1.png" and alt="sushi".

![step2-01]()

### 2.Below image, we  want to display some japanese characters. Put them within h2. and add a break line tag after each character.

![step2-02]()

### 3.Below the h2, add a div , it will have a class="hero-image__overlay"

![step2-03]()

### 4.Create css/sections/hero.css file.
![step2-04]()
### 5.Import css/sections/hero.css file in css/style.css.
![step2-05]()

### 6.In css/sections/hero.css file. Start with .hero div section by giving it a display:flex; .
### Then, Change the min height of the hero section to be equal to calc(100vh-74px). (100vh-74px) means 100 vertical height of the page minus the height of the navigation bar which is 74 pixels. So that means if you look at the finished site, the hero section will always take the full height of the screen but will subtract it by the height of the navigation bar. 
### Set overflow:hidden; to ensure that content is clipped and no scrolling mechanisms should be provided to scroll outside of the clipping region.
![step2-06]()

### 7.Let's deal with the huge image. Start with the div that containing the image and the h2 and the overlay. it has a class .hero-image, give it a flex:1, display:flex, flex-direction:column, position:relative, and z-index:5 to appear on top of the other elements. 
![step2-07]()

![step2-08]()

![step2-09]()

### 8.let's deal with the image itself by saying .hero-image img to target the image. give it a width:120%, height:100%, object-fit:contain.

### 9.let's deal with the overlay by saying .hero-image__overlay, this will be shown on top of the other elements so we can give it a position:absolute, it will not be related to the other elements.it will just be there,give it inset proprty of zero and width:100%, background-color:var(--primary-color) and z-index:-1 .
![step2-10]()

![step2-11]()

![step2-12]()

### To focus on the right side of our screen , comment the huge image.
![step2-13]()

### 10.In hero section, Below our hero-image div, Create a new div with class="hero-content", within it , Create a new div with a class="hero-content-info", within it, Create h1 . it is a primary heading on our page. it will say feel the taste of japanese food. and a p tag . it will say feel the taste of the most popular Japanese food from anywhere and any time .
![step2-14]()

### 11.Below the p tag, Create a div with class="hero-content__buttons. Let's add two buttons inside it ,Order Now and How to Order . Give the first button a class="hero-content__order-button" and it will say Order Now. Give the second button a class="hero-content__play-button". Inside the second button , Create a self-closing image with src="images/play-circle.svg" and alt="play". The button itself after the image will say How to Order.
![step2-15]()
![step2-16]()

### 12.Below the hero-content-info div, Create a new div with class="hero-content__testimonial". Inside it , Create another div with class="hero-content__customer" and another class=" flex-center". Ii will contain the 24000 happy customers. you can do it by crating <h4>24<span>k+</span></h4>, below it in a p tag <p>Happy Customers</p>.


### 13.Below hero-content__testimonial div, Create a new div with a class="hero-content__review", Inside it add an image with src="images/user.png" alt="user" and below it add a p tag  <p>"This is the best Japanese food delivery service that ever existed."</p>.

![step2-17]()

![step2-20]()

### Uncoment the huge image.
![step2-21]()

![step2-22]()
### 14.Add style to Japanese chatacters. You can select it by .hero-image h2. Give it position:absolute because it does not have to worry about the other elements on the page. It will appear at the full bottom so bottom:0. Give it padding:20px, font-family: var(--playfair-display),font-weight: 700,font-size: 120px,line-height: 138px and color: #fff which is a white color.  

![step2-23]()

![step2-24]()

### 15.Add style to the hero content which has a class .hero-content. It is a block. Give it flex: 1.22, display: flex,justify-content: space-between , flex-direction: column which will make the elements appear one below another. 

![step2-25]()

![step2-26]()
### 16.Add style to hero-content-info div by giving it padding:64px to give it some space. Give it display:flex, justify-content: center and flex-direction: column.

![step2-27]()

![step2-28]()

### 17.Target <h1>Feel the taste of Japanese food</h1> by type .hero-content-info h1 because target the h1 element within it. Give it a font-size: 80px, font-weight: 600px, font-family: var(--playfair-display),color: var(--secondary-color).

![step2-29]()

![step2-30]()

### 18.Target <p>Feel the taste of the most popular Japanese food from anywhere and anytime. </p> by type .hero-content-info p. Give it some margin to divide it a bit bit from the rest of the content , 32px on the top, zero on the right, zero on the bottom and then 32px on the left side as well, Give it  font-family: var(--plus-jakarta-sans), color: var(--secondary-color), font-size: 18px, font-weight: 400;

![step2-31]()

![step2-32]()

### 19.Target the buttons that have a class .hero-content__buttons, give it margin: 41px 0 0 41px; 41px on the top and left side, display: flex; for the items to appear in a row as well as flex-wrap: wrap; because if we do not have enough width on the screen, they are going to wrap one below another and then give it gap: 36px; to give it some space.

### then target the first button that has a class .hero-content__order-button. Give it padding: 20px, border-radius: 36px, min-width: 212px, outline: none to remove the ugly outline as well as border: none ,change the  background-color: var(--secondary-color),change cursor: pointer to make it clickable, give it color: #fff , increase the font-weight: 500 to make it bolder, change font-size: 18px ,as weel as line-height: 23px;

### Target the second button that has a class .hero-content__play-button. Give it border: none, outline: none, background: transparent, display: flex, align-items: center, font-size: 16px, line-height: 19px, color: var(--black-200), font-family: var(--plus-jakarta-sans), cursor: pointer.

### Target the image inside the button , you can select it by write .hero-content__play-button img , Give it a margin-right: 12px to move it a bit from the text, give it  width: 46px, height: 46px and object-fit: contain to ensure that it always keep the same aspect ratio.

![step2-33]()
![step2-34]()
![step2-35]()
![step2-36]()
![step2-37]()


### 20.Target the hero-content__testimonial div and give it  padding: 32px on top and bottom and  64px on left and right to give it some space. give it a display of  flex for the elements to appear in a row. give it a flex-wrap propertyset to  wrap so on smaller devices they can still appear normally and gap of 20px. and change the background to var(--color-white).

![step2-38]()

### 21.Change the customer div by saying .hero-content__customer , Give it a flex of 1 which will make it take the majority of space and then a gap of 10 pixels. 
![step2-39]()

### 22. Edit the h4 and p tag ,Select .hero-content__customer h4 to target h4 tag within hero-content__customer div. we can give it a font-size of 62px, font-weight of 400, and a font-family of var(--playfair-display) .and for a p tag within hero-content__customer div. select .hero-content__customer p e can give it a font-size of 16px, font-weight of 400, and a font-family of var(--plus-jakarta-sans),color of var(--secondary-color) and opacity of 0.5 .
![step2-40]()

![step2-41]()

### 23. Modify the .hero-content__review by giving it flex: 1 to take all the remaining space . we have a flex:1 on the customer and a flex:1 of review which means that they are gonna both take 50% of the space. give it display: flex, align-items: center so they are vertically aligned. give it gap: 10px , and padding-left: 20px to divide it from the content on the left. and give it  border: 1px solid rgba(2, 2, 2, 0.1). This will make it barely visible of course we do not want to turn this into an entire box we just want to make it a border of left there ,and give it min-width:200px.
![step2-42]()

### 24. Let's style the image to make it a bit smaller . Target hero-content__review and then target the image, giving it a width of 42px,a height of 42px as well an object-fit of contain for it to manage its aspect ratio.
![step2-43]()

### 25. Style the p tag by targeting hero-content__review then p tag, giving it a font-size of 12px, font-weight of 400,line-height: 32px,font-family: var(--plus-jakarta-sans),a color: var(--secondary-color) and opacity of 0.8.

![step2-44]()

![step2-45]()


### 26. There is a bit of a gap here between our navigation bar and the overlay. Let's fix that by going back to header__menu , give it flex:1.236 in header.css file.  

![step2-46]()