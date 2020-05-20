## *Notes from Reading 04*
*Duckett book HTML&CSS*
## Process to Make a New Site

Important questions to consider re the audience and their needs:

1. Who are your visitors? 
2. Why people visit your website
3. What your visitors are trying to achieve
4. What information your visitors need
5. How often people will visit your site
    - How often you need to update it (maybe different for different parts of site)

### Site Map
*Diagram of the pages that will be used to structure a site*

- Can use **card sorting** to help decide what info should go on each page
- Site map usually begins with homepage at top
- It's possible each page will have its own section homepage as well, if its a large site


### Wireframe
*Simple sketch of key information that needs to go on each page*

- Shows the hierarchy of information and how much space it might require
- Don't worry yet about CSS stuff (color, font, etc) in wireframe phase

**The primary aim of any kind of visual design is to communicate.**

## Design

- Content
- Prioritizing 
    - *Visual hierarchy*
- Organizing 
    - *Grouping* related content into *blocks* or *chunks*
    - Present certain types of info in *similar* visual style

## Structure 

*HTML describes the structure of pages*

'''<p>words</p>'''

- Start with **doctype html**
- Don't need to, but you should still use **html opening and closing tags**
- Can use ! for code comments (pg 182)
- **Head** above body, that says what shows on tab. Head**ers** within body.
- **Met** element lives inside head element, contains info about web page
    - Not visible to users
    - Doesnt have closing tag, **empty element**
- description, keywords, robots
- Opening and closing **tags**
- **Element** is what lives inside tags
    - **Attributes** tell more about elements
        - attributes have **name** and **value**
        - name is what kind of extra information you're supplying about the element's content
        - value is info or setting for that attribute
        - pg 25 for example
- Every HTML element can carry **id attribute**
    - Giving an element uniqueness allows CSS to style it differently from other instances of same element
    - Can also be used to allow script in JavaScript to work with that particular element
- **Class attributes** way to identify several elements as being different than other elements on the page
    - Class attribute on any element can share same value (can use same class attribute on headings and links, for ex)
- **Block elements** always appear to start on new line in browser
    - h1, p, ul, li
- **Inline elements** always appear to continue on same line
    - a, b, em, img


## HTML5 Layout

- **Article** element acts as container for any section of a page that could stand alone
- **Aside** element has two uses
    - if inside article element, should have info related to article
    - if outside article element, acts as container for content related to whole page
- **Section** element groups related content together, each section should have own heading
- **Div** element is good containing element for whole page
    - Can use when there is no other suitable element to group a set of elements
- **Hgroup** element is to group together sets of headers so they are treated as one single heading
    - *Is it best practices to use this? Personal preference?*
- **Figure** element used to contain content referenced from main flow of article (images, graphs, videos, etc)
    - Should also contain **figcaption** element

#### **Since older browsers may not know newer HTML elements, need to include line of CSS which states which new elements should be rendered as block-level elements**

    







[Back to home](README.md)


