# Step4-Popular Foods Section 😊

### Popular foods section has 4 parts (h2 element, div has 6 buttons, div has 3 catalogue and button).

![step4-01]()
![step4-02]()
### Create a new section with class="popular-foods" and id="menu", inside it create h2 element with text "Popular Food / 人気" and give it class="popular-foods__title".
### Below h2 element, Create a div with class="popular-foods__filters" and class="sushi__hide-scrollbar", Within that div, Add a set of 6 different buttons for meals.

![step4-03]()

### Below the div that contining the buttons, Create a new div with class="popular-foods__catalogue".

### finally Below catalog div, create a button , that button has a class="popular-foods__button" 
![step4-04]()
### Create css/sections/popular.css. First style the sections that is wrapping everything that has a class="popular-foods". Give it  padding: 64px to give it some space then give it a display: flex andflex-direction: column, Let's give it a background-color: var(--primary-color) ,background-image: url(../../images/popular_bg.png), background-position: center,background-repeat: no-repeat, background-size: contain and finally set overflow: hidden.

![step4-05]()
![step4-06]()
![step4-07]()
![step4-08]()

### Let's change the popular-foods__title. Give it a big font-size of 56px, font-family: var(--playfair-display), font-weight: 600, line-height: 78px, color: #fff which is white and text-align: center.

![step4-09]()
![step4-10]()

### Let's modify the .popular-foods__filters. Give it margin-top: 48px to divide these buttons a bit from the top.Give it a max-width: 100% so they can span all the way till the end , overflow-x: auto which means that may be on smaller devices we will need to scroll over them . Give it  display: flex,  justify-content: center and a gap: 24px to give it a bit of space.

![step4-11]()
### Modify the buttons. they have a class="popular-foods__filter-btn", Give it padding: 10px 28px. display: flex, flex-direction: row, align-items: center ,gap: 10px, background: rgba(255,255,255,0.05) which is white color with 0.05 opacity, border: 1px solid rgba(255,255,255,0.2), border-radius: 46px, font-size: 16px, font-weight: 300px, line-height: 25px, font-family: var(--plus-jakarta-sans), color: #fff, cursor: pointer.
![step4-12]()


### Let's style the images by targeting .popular-foods__filter-btn img. Give each individual image a width: 36px, a height: 36px and object-fit: contain.
![step4-13]()

### finally we want to make a difference between the active and non-active classes. So let's style the .popular-foods__filter-btn.active, Give it a background: #fff and color: var(--primary-color).
![step4-14]()

### Add an hover effect to the buttons by targeting .popular-foods__filter-btn:hover . on hover we want to apply the same properties as when active .
![step4-15]()
![step4-16]()
![step4-17]()



### Let's style .popular-foods__catalogue. Give it  margin-top: 64px to divide it from the top, display: flex, justify-content: center, align-items: flex-end to appear at the bottom , flex-wrap: wrap and a gap: 56px to provide a lot of space between its elements.

![step4-18]()

### finally, Let's style the .popular-foods__button button , Give it a width: fit-content , this is an interesting one so you don't have to provide a fixed width. Give it also a padding: 20px 30px, a margin: 80px auto 0. Let's change the text within the button by giving it a font-weight: 500, a font-size: 18px, line-height: 23px, font-family: var(--plus-jakarta-sans), color: #fff,  border: none, outline: none, background: var(--secondary-color), border-radius: 64px ,cursor: pointer.
### finally let's style the arrow icon by targeting .popular-foods__button img . give it a width: 14px, a height: 14px, an object-fit: contain and a margin-left: 21px.


![step4-19]()
![step4-20]()
![step4-21]()


### Let's focus on the catalogue or the menu in index.html file , Let's create HTML5 semantic tag called article. Article is simply a card , it is an element that is a complete self-contained composition, so let's create the first article with a class="popular-foods__card". within the article, Add an image with class="popular-foods__card-image" ,src="images/sushi-12.png" and alt="sushi-12". Below the image, Add h4 with class="popular-foods__card-title" and text "Chezu Sushi". Below the h4, Add div that will be  for rating, stars and the price. so let's give it a class="popular-foods__card-details" and use one of the utility classes called flex-between. This will automatically apply the flex property as well as the flex-between inside of that div . Create another div, this one will be rating so give it a class="popular-foods__card-rating".it can have an image for the star. it has a src="assets/star.svg" and alt="star". below it Add a score within a p element.finally below popular-foods__card-rating div add a p element for the price and give it a class="popular-foods__card-price"

![step4-22]()
![step4-23]()

### copy the article two times and paste it below the first aricle and change images and text. the second article add a class="active-card:.


![step4-24]()
![step4-25]()


![step4-26]()
![step4-27]()

### Let's style the .popular-foods__card article, Give it padding: 38px, min-width: 260px, height: fit-content, display: flex, align-items: center, flex-direction: column to make the information is below the image, border-radius: 36px, background: rgba(255, 255, 255, 0.05) to give it a glassy effect, border: 1px solid rgba(255, 255, 255, 0.2).

![step4-28]()


### Let's change the images of these cards by targeting .popular-foods__card-image. Give it  width: 110px, height: 84px and object-fit: contain.

![step4-29]()


### Let's change the title of a specific meal by targeting the .popular-foods__card-title. Give it  margin-top: 47px to divide it a bit from the top, font-weight: 600, font-size: 24px, line-height: 32px, font-family: var(--playfair-display), color: #fff, text-align: center. 
![step4-30]()

### Edit the datails by targeting the .popular-foods__card-details. Give it width: 100% and margin-top: 32px. 
![step4-31]()

### Edit the rating by targeting .popular-foods__card-rating . Give it a display: flex so the star appears on the left side of the rating, align-items: center and gap: 8px.
![step4-32]()

### Let's modify the rating image by targeting .popular-foods__card-rating img. Give it a  width: 24px , height: 24px and object-fit: contain.

![step4-33]()

### Change the p element of the same card rating by targeting the .popular-foods__card-rating p. Give it font-size: 20px, font-weight: 300, font-family: var(--plus-jakarta-sans) and color: #fff. The price is similar to the p tag.
![step4-34]()
![step4-35]()
![step4-36]()

### The active element is the middle one. It is bigger than other. so target the .popular-foods__card.active-card. Give it background: #fff, min-width: 340px. 
### Target the .popular-foods__card.active-card .popular-foods__card-image. Give it width: 214px and height: 160px.

### Then target  .popular-foods__card.active-card .popular-foods__card-title. Give it color: var(--black-500) and font-size: 32px.

### Then target .popular-foods__card.active-card .popular-foods__card-rating img . Give it width: 32px and  height: 32px.

### Then target .popular-foods__card.active-card .popular-foods__card-rating p . Give it font-size: 24px and color: var(--gray-100).

### Then target .popular-foods__card.active-card .popular-foods__card-price . Give it font-size: 24px and color: var(--secondary-color).
![step4-37]()
![step4-38]()
![step4-39]()



