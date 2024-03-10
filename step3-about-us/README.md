# Step3-About Us Section 😊

![step3-01]()
![step3-02]()

### About Us section has two images, learn more button  and text about their service.
### Create a new section with a class="about-us" and an id="about-us". That section has two parts.
### Part one- the Left side:
### Inside about-us section, Create a div with a class="about-us__image" and inside it:

### First: Create a div with a class="about-us__image-sushi3" and inside it, Add the image element with src="images/sushi-3.png" and alt="sushi".
![step3-03](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/step3-about-us/images-readme-file/img3-03.png)

### Second: Below the about-us__image-sushi3 div that contining the image, Create a button with a class="about-us__button" and add an image with a src="images/arrow-up-right.svg" and alt="learn more".

![step3-04](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/step3-about-us/images-readme-file/img3-04.png)

### Third: Create a div with a class="about-us__image-sushi2" and inside it, Add the image element with src="images/sushi-2.png" and alt="sushi".
![step3-05](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/step3-about-us/images-readme-file/img3-05.png)

### Part Two- the right side:
### Below the about-us__image div, create a div with a class="about-us__content", inside it, 
### First: Create a p element with class="sushi__subtitle"
### <p class="sushi__subtitle">About Us / 私たちに関しては</p>.
### Second: Below p element, Create an h3 element with a class="sushi__title"
### <h3 class="sushi__title"> Our mission is to bring true Japanese flavours to you.</h3>
### Third: Below h3 element, Create an p element with a class="sushi__description"
### <p class="sushi__description"> We will continue to provide the experience of Omotenashi, the Japanese mindset of hospitality, with our shopping and dining for our customers. </p>

![step3-06](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/step3-about-us/images-readme-file/img3-06.png)

### Create css/sections/about.css file to start adding style.
![step3-07](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/step3-about-us/images-readme-file/img3-07.png)
### Import that file in css/style.css file.
![step3-08](https://github.com/fatmakhaledosman/Sushi-Themed-Website-step-by-step/blob/main/step3-about-us/images-readme-file/img3-08.png)
### Add style to primary div that is wrapping the entire content. That has a class="about-us" . Give it display: flex,as well as a min-height: 720px, and overflow: hidden.
![step3-09]()

### Add style to image div that has a class="about-us__image". Give it a flex: 1 so now it takes the majority of the space, display: flex , you see one next to another but we still want to see them one below another so we can change the flex-direction: column, justify-content: center to center them vertically then change the background: var(--color-white) and finally give it position: relative.
![step3-10]()

### Add style to the div itself by targeting the about-us__image and then the div, Give it a padding: 32px on top and bottom and  64px on left and right then give it flex: 1, display: flex, align-items: center, background-position: center,background-repeat: no-repeat, background-size: contain.
![step3-11]()

### we can update those two background images by saying that .about-us__image-sushi3. Give it a border-bottom: 8px solid var(--color-creamson) and background-image: url("../../images/about__bg1.png"). and for .about-us__image-sushi2.Give it background-image: url("../../images/about__bg2.png").
![step3-12]()

### Let's modify the images by targeting these same classes .about-us__image-sushi3 and then target the image itself img. Give it width: 225px and height: 200px.and for .about-us__image-sushi2 img .Give it width: 240px and height: 160px.
![step3-13]()

### Let's focus on the learn more button that is in between those two images that has a class="about-us__button". Give it position: absolute if you do this it will not care about the rest of the items next to it and Give it a right: 0 to go to the end of it's container, also give it some space like padding: 12px 32px, min-height: 64px ,background: var(--secondary-color),and  border-radius: 32px on top ,0 on right, 0 on bottom and 32px on the left.Set border: 0,outline: 0 color to text to #fff,font-family: var(--plus-jakarta-sans), font-weight: 500,font-size: 18px, line-height: 23px and cursor: pointer to make it appear clickable.
![step3-14]()

### Let's modify the icon within the button by targeting the .about-us__button and then the img within it. Give it object-fit: contain as well as margin-left: 32px.
![step3-15]()

### Add style to our content by targeting .about-us__content. Give it a padding: 64px,flex: 1 meaning that since this is one and the above left side we also set to one. they takes 50% of the space each. Give it a display: flex, justify-content: center to center it horizontally and change flex-direction: column for the elements to appear one below another. 

![step3-16]()


###  .flex-center, .flex-between, .sushi__subtitle, .sushi__title, .sushi__description , These are known as utility classes when you are using a specific class often you can extract the specific set of styles and then apply it with one class same thing will happen for the subtitle and the description. we will have to reuse these pieces of the text often across the website.

![step3-17]()
![step3-18]()
![step3-19]()

