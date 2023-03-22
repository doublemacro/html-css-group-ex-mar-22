
We will be reusing project files from last time.

Start by editing the **index.html** and **style.css** files in this repo. Add the style code at the end of the style.css file.

We will be refactoring our code, to build a better layout.

Inside of body, add a div with id "body-container";
 - move the header tag in it;
 - add a div with class "main-container" inside the body-container div
 - create an aside tag with class "sidebar" inside the main-container div, with 5 p tags, with text "Item 1" - "Item 5" in it

 - move the main tag and its contents inside the div main-container, after the aside tag.

 - style the aside tag with display flex, direction column, align-items: center;
- move the footer tag inside the "body-container div.


Style the "body-container" div:
 - add a min-width: 100%; to it
 - make it display flex, direction column;
 - make the header align to center, by using align-self: center;
 - make the footer align to the left side of the screen, by using align-self: start;

Style the "main-container" div:
 - make it display flex
 - justify content space-between
  - style the main tag inside this div with:
   -   display flex, and flex: 1;


Style the sidebar with:
 - flex: 0.3;
 - display flex, direction column, align items center

Style the main tag with:
 - flex: 1;
 
 


