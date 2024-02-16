# Step1-header 😊
### 1.Create Sushi website structure
![step1-01](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-01.png)

### 2.Import css/sections/header.css in css/style.css

![step1-02](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-02.png)

### 3.Add the HTML5 base structure in index.html file
![step1-03](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-03.png)

### 4.Add title and icon that shows in your tab on the browser
```
<link rel="icon" type="image/png" href="sushi.png">
```
![step1-04](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-04.png)

### 5.Create HTML5 semantic header element and inside it, Create nav element with class="header__nav".
![step1-05](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-05.png)

### 6.Inside nav element
#### First, Create div with class="header__logo" that will contain the logo, so inside it we can add the h4 element that is going to say sushiman, and below it , we can create a div with class="header__logo-overlay"
#### Second, Create unordered list with class="header__menu", inside it create a couple of list items
#### The first list item has an anchor element inside it so it is actually a clickable link, and that anchor element has href="#menu" and says menu.
#### The second list item has anchor element with href="food" and says food.
#### The third list item has anchor element with href="services" and says services.
#### The fourth list item has anchor element with href="about-us" and says about us.
#### The last list item has an image element with src="images/search.svg and alt="search".
![step1-06](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-06.png)

![step1-07](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-07.png)

#### If we are on mobile devices then we will not be able to see all these elements on the screen. so below this ul element we need to create another ul element with class="header__menu-mobile" it will be for mobile devices, and it will render just one li element that will render an image with src="images/menu.svg" and alt="menu".

![step1-08](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-08.png)
#### White menu appears here, but later on they're going to be divided depending on which device size.

![step1-09](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-09.png)

---------------------------------------------
### 7.In css/style.css file,
![step1-10](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-10.png)

#### - The CSS margin properties are used to create space around elements, outside of any defined borders.
#### - An element's padding is the space between its content and its border.
#### - box-sizing: border-box; on an element ---> padding and border are included in the width and height.
#### - Adding a smooth scrolling effect to the document.

### 7.In css/sections/header.css file,
![step1-11](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-11.png)

#### Notice that with display:flex; the elements appear in a row , first the title (flex:1) , then the ul menu element(flex:1.235) ,then the menu-mobile (flex:1.235).
### The CSS overflow property controls what happens to content that is too big to fit into an area.
##### The overflow property specifies whether to clip the content or to add scrollbars when the content of an element is too big to fit in the specified area.
##### The overflow property has the following values:

   ##### visible - Default. The overflow is not clipped. The content renders outside the element's box
   ##### hidden - The overflow is clipped, and the rest of the content will be invisible
   ##### scroll - The overflow is clipped, and a scrollbar is added to see the rest of the content
   ##### auto - Similar to scroll, but it adds scrollbars only when necessary

##### Note: The overflow property only works for block elements with a specified height.



### left-side part 
![step1-12](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-12.png)

![step1-13](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-13.png)

### position: absolute; inside position: relative;
### outer div .header__logo has display:flex; and overlay has width:100%.

![step1-14](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-14.png)
```
background-color: rgb(121,45,45);
```
#### Every time that you use the same instance of the color you would have to manually type rgb(121,45,45).
#### Instead, we can use CSS variables.
#### to create css variable 
```
--name:"specify-the-color";

--primary-color: #b1454a;
--secondary-color: #121212;
```
![step1-15](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-15.png)

![step1-16](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-16.png)


![step1-17](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-17.png)

### Right side part
![step1-18](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-18.png)

![step1-19](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-19.png)

![step1-20](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-20.png)

![step1-21](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-21.png)

![step1-22](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-22.png)

![step1-23](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-23.png)

![step1-24](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-24.png)

![step1-25](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/Step1-header/images-readme-file/img1-25.png)

