# 0x01. AirBnB clone - Web static

## Learning Objectives:bulb:
What you should learn from this project:

* What is HTML
* How to create an HTML page
* What is a markup language
* What is the DOM
* What is an element / tag
* What is an attribute
* How does the browser load a webpage
* What is CSS
* How to add style to an element
* What is a class
* What is a selector
* How to compute CSS Specificity Value
* What are Box properties in CSS

---

### [0. Inline styling](./0-index.html)
* Write an HTML page that displays a header and a footer.
Layout:

    - Body:
      - no margin
      - no padding
    - Header:
      - color #FF0000 (red)
      - height: 70px
      - width: 100%
    - Footer:
      - color #00FF00 (green)
      - height: 60px
      - width: 100%
      - text Best School center vertically and horizontally
      - always at the bottom at the page

Requirements:
- You must use the header and footer tags
- You are not allowed to import any files
- You are not allowed to use the style tag in the head tag
- Use inline styling for all your tags
![image](https://user-images.githubusercontent.com/105589308/220024560-f1b29c39-d4ec-4835-ab86-d029cf52b069.png)



### [1. Head styling](./1-index.html)
* Write an HTML page that displays a header and a footer by using the style tag in the head tag (same as 0-index.html)

  - Requirements:
     - You must use the header and footer tags
     - You are not allowed to import any files
     - No inline styling
     - You must use the style tag in the head tag   
  - The layout must be exactly the same as 0-index.html

### [2. CSS files](./2-index.html)
* Write an HTML page that displays a header and a footer by using CSS files (same as 1-index.html)
  - Requirements:

      - You must use the header and footer tags
      - No inline styling
      - You must have 3 CSS files:
      - styles/2-common.css: for global style (i.e. the body style)
      - styles/2-header.css: for header style
      - styles/2-footer.css: for footer style
  - The layout must be exactly the same as 1-index.html


### [3. Zoning done!](./3-index.html)
* Write an HTML page that displays a header and footer by using CSS files (same as 2-index.html)
Layout:

  - Common:
     - no margin
     - no padding
     - font color: #484848
     - font size: 14px
     - font family: Circular,"Helvetica Neue",Helvetica,Arial,sans-serif;
     - icon in the browser tab
  - Header:
    - color: white
    - height: 70px
    - width: 100%
    - border bottom 1px #CCCCCC
    - logo align on left and center vertically (20px space at the left)
  - Footer:
    - color white
    - height: 60px
    - width: 100%
    - border top 1px #CCCCCC
    - text Best School center vertically and horizontally
    - always at the bottom at the page
  
  - Requirements:
    - No inline style
    - You are not allowed to use the img tag
    - You are not allowed to use the style tag in the head tag
    - All images must be stored in the images folder
    - You must have 3 CSS files:
      * styles/3-common.css: for the global style (i.e body style)
      * styles/3-header.css: for the header style
      * styles/3-footer.css: for the footer style
![image](https://user-images.githubusercontent.com/105589308/220024369-c3504caf-eaab-4ac8-bfae-82d751ed7c14.png)


### [4. Search!](./4-index.html)
* Write an HTML page that displays a header, footer and a filters box with a search button.

- Layout: (based on 3-index.html)
  - Container:
    - between header and footer tags, add a div:
      - classname: container
      - max width 1000px
      - margin top and bottom 30px - it should be 30px under the bottom of the header (screenshot)
      - center horizontally
   
   - Filter section:
      - tag section
      - classname filters
      - inside the .container
      - color white
      - height: 70px
      - width: 100% of the container
      - border 1px #DDDDDD with radius 4px

  - Button search:
     - tag button
     - text Search
     - font size: 18px
     - inside the section filters
     - background color #FF5A5F
     - text color #FFFFFF
     - height: 48px
     - width: 20% of the section filters
     - no borders
     - border radius: 4px
     - center vertically and at 30px of the right border
     - change opacity to 90% when the mouse is on the button

- Requirements:
  - You must use: header, footer, section, button tags
  - No inline style
  - You are not allowed to use the img tag
  - You are not allowed to use the style tag in the head tag
  - All images must be stored in the images folder
  - You must have 4 CSS files:
    - styles/4-common.css: for the global style (body and .container styles)
    - styles/3-header.css: for the header style
    - styles/3-footer.css: for the footer style
    - styles/4-filters.css: for the filters style
  - 4-index.html won’t be W3C valid, don’t worry, it’s temporary
![image](https://user-images.githubusercontent.com/105589308/220024137-a611d9b1-f8d3-4f4c-a3c0-a0b14699a914.png)


### [5. More filters](./5-index.html)
* Write an HTML page that displays a header, footer and a filters box.

- Layout: (based on 4-index.html)

  - Locations and Amenities filters:
      - tag: div
      - classname: locations for location tag and amenities for the other
      - inside the section filters (same level as the button Search)
      - height: 100% of the section filters
      - width: 25% of the section filters
      - border right #DDDDDD 1px only for the first left filter
      - contains a title:
          - tag: h3
          - font weight: 600
          - text States or Amenities
     - contains a subtitle:
          - tag: h4
          - font weight: 400
          - font size: 14px
          - text with fake contents
          
- Requirements:
    - You must use: header, footer, section, button, h3, h4 tags
    - No inline style
    - You are not allowed to use the img tag
    - You are not allowed to use the style tag in the head tag
    - All images must be stored in the images folder
    - You must have 4 CSS files:
      - styles/4-common.css: for the global style (body and .container styles)
      - styles/3-header.css: for the header style
      - styles/3-footer.css: for the footer style
      - styles/5-filters.css: for the filters style
![image](https://user-images.githubusercontent.com/105589308/220025869-8e2092bd-1a9d-4eab-9413-02ee069234db.png)


### [6. It's (h)over](./6-index.html)
* Write an HTML page that displays a header, footer and a filters box with dropdown.

#### Layout: (based on 5-index.html)

- Update Locations and Amenities filters to display a contextual dropdown when the mouse is on the filter div:
    - tag ul
    - classname popover
    - text should be fake now
    - inside each div
    - not displayed by default
    - color #FAFAFA
    - width same as the div filter
    - border #DDDDDD 1px with border radius 4px
    - no list display
    - Location filter has 2 levels of ul/li:
      - state -> cities
      - state name must be display in a h2 tag (font size 16px)

- Requirements:
  - You must use: header, footer, section, button, h3, h4, ul, li tags
  - No inline style
  - You are not allowed to use the img tag
  - You are not allowed to use the style tag in the head tag
  - All images must be stored in the images folder
  - You must have 4 CSS files:
    - styles/4-common.css: for the global style (body and .container styles)
    - styles/3-header.css: for the header style
    - styles/3-footer.css: for the footer style
    - styles/6-filters.css: for the filters style
![image](https://user-images.githubusercontent.com/105589308/220027036-40ded4b6-3f55-4769-8b1a-66584f76ae75.png)
![image](https://user-images.githubusercontent.com/105589308/220027147-a0ba4476-ee51-44e3-a880-c0e5348c9563.png)


### [7. Display results](./7-index.html)
* Write an HTML page that displays a header, footer, a filters box with dropdown and results.

#### Layout: (based on 6-index.html)

- Add Places section:
    - tag: section
    - classname: places
    - same level as the filters section, inside .container
    - contains a title:
      - tag: h1
      - text: Places
      - align in the top left
      - font size: 30px
   - contains multiple “Places” as listing (horizontal or vertical) describe by:
      - tag: article
      - width: 390px
      - padding and margin 20px
      - border #FF5A5F 1px with radius 4px
      - contains the place name:
      - tag: h2
      - font size: 30px
      - center horizontally
      
- Requirements:
  - You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
  - No inline style
  - You are not allowed to use the img tag
  - You are not allowed to use the style tag in the head tag
  - All images must be stored in the images folder
  - You must have 5 CSS files:
    - styles/4-common.css: for the global style (i.e. body and .container styles)
    - styles/3-header.css: for the header style
    - styles/3-footer.css: for footer style
    - styles/6-filters.css: for the filters style
    - styles/7-places.css: for the places style
![image](https://user-images.githubusercontent.com/105589308/220028492-b7e8860c-8950-4793-8535-611149379648.png)


### [8. More details](./8-index.html)
* Write an HTML page that displays a header, a footer, a filter box (dropdown list) and the result of the search.
####Layout: (based on 7-index.html)

###### Add more information to a Place article:

- Price by night:
    - tag: div
    - classname: price_by_night
    - same level as the place name
    - font color: #FF5A5F
    - border: #FF5A5F 4px rounded
    - min width: 60px
    - height: 60px
    - font size: 30px
    - align: the top right (with space)
- Information section:
    - tag: div
    - classname: information
    - height: 80px
    - border: top and bottom #DDDDDD 1px
    - contains (align vertically):
        - Number of guests:
              - tag: div
              - classname: max_guest
              - width: 100px
              - fake text
              - icon
        - Number of bedrooms:
              - tag: div
              - classname: number_rooms
              - width: 100px
              - fake text
              - icon
        - Number of bathrooms:
              - tag: div
              - classname: number_bathrooms
              - width: 100px
              - fake text
              - icon
- User section:
    - tag: div
    - classname: user
    - text Owner: <fake text>
    - Owner text should be in bold
- Description section:
    - tag: div
    - classname: description
    
##### Requirements:
   - You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
   - No inline style
   - You are not allowed to use the img tag
   - You are not allowed to use the style tag in the head tag
   - All images must be stored in the images folder
   - You must have 5 CSS files:
        - styles/4-common.css: for the global style (i.e. body and .container styles)
        - styles/3-header.css: for the header style
        - styles/3-footer.css: for the footer style
        - styles/6-filters.css: for the filters style
        - styles/8-places.css: for the places style
![image](https://user-images.githubusercontent.com/105589308/220031771-24e082fe-03fc-4134-84d0-263acc779de3.png)

### [9. Full details](./100-index.html)
* Write an HTML page that displays a header, footer, a filters box with dropdown and results.
##### Layout: (based on 8-index.html)
##### Add more information to a Place article:

- List of Amenities:
    - tag div
    - classname amenities
    - margin top 40px
    - contains:
        - title:
            - tag h2
            - text Amenities
            - font size 16px
            - border bottom #DDDDDD 1px
        - list of amenities:
            - tag ul / li
            - no list style
            - icons on the left: Pet friendly, TV, Wifi, etc… feel free to add more
- List of Reviews:
    - tag div
    - classname reviews
    - margin top 40px
    - contains:
        - title:
            - tag h2
            - text Reviews
            - font size 16px
            - border bottom #DDDDDD 1px
        - list of review:
            - tag ul / li
            - no list style
            - a review is described by:
                - h3 tag for the user/date description (font size 14px). Ex: “From Bob Dylan the 27th January 2017”
                - p tag for the text (font size 12px)
##### Requirements:
- You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
- No inline style
- You are not allowed to use the img tag
- You are not allowed to use the style tag in the head tag
- All images must be stored in the images folder
- You must have 5 CSS files:
    - styles/4-common.css: for the global style (body and .container styles)
    - styles/3-header.css: for the header style
    - styles/3-footer.css: for the footer style
    - styles/6-filters.css: for the filters style
    - styles/100-places.css: for the places style
![image](https://user-images.githubusercontent.com/105589308/220033016-aca88c68-07e5-4f0a-b2cf-5632886924a7.png)


### [10. Flex](./101-index.html)
##### Improve the Places section by using Flexible boxes for all Place articles
- [Flexbox Froggy](http://flexboxfroggy.com/)


### [11. Responsive design](./102-index.html)
* Improve the page by adding responsive design to display correctly in mobile or small screens.
##### Examples:
- no horizontal scrolling
- redesign search bar depending of the width
- etc.

### [12. Accessibility](./103-index.html)
* Improve the page by adding Accessibility support
##### Examples:
- Colors contrast
- Header tags
- etc.
---

## Author
* **Charles Obimnaeto Egesionu** - [IamNaeto](https://github.com/IamNaeto)
