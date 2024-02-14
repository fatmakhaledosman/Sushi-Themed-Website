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


### 7.In css/sections/header.css file,
![step1-10]()
#### Notice that the elements appear in a row , first the title , then ul element , then menu.

![step1-11]()
#### class of flex:1; means that it will expand however long it needs to. the sushiman is on the left side and the menu is on the right side.

![step1-12]()
#### position:absolute; means that it will not be bound to other elements on the page it will be absolutely positioned.
```
background-color: rgb(121,45,45);
```
#### Every time that you use the same instance of the color you would have to manually type rgb(121,45,45).
#### Instead, we can use CSS variables.
