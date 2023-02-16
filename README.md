# Read Me

## General
- The **layouts** directory contains **default.html** which defines the layout of the website i.e. navigation bar, footnote.
- The **css** directory contains **main.css** which defines the style of various elements such as textboxes, photos, font, and margin.
- All bibs and images are added to the **assets** directory.
- Each page of a website corresponds to one of the **.md** files. This allows you to edit the text of the page using the markdown language. Markdown files also allow html. As such, in each markdown file you will often find elements of this type 
  ``` 
  <div class='classname'>
  text
  </div>
  ```
  The div tag allows one to manipulate the object (text/image) stylistically separate from the rest of the page. You are able to change, for example, the font size of the text inside this div tag by locating '.classname' in **main.css**
- If you wish to create a new page, go to **config.yml**. Add Name and Link where Name will be the name of the page on the navigation bar. Link should be the name of the markdown flie corresponding to that page. 
  
### Changing Margin and Fonts
- Changes to style should be made in the main.css file 
- For overall font and margin, go to the '.body' element in main.css
- For other specific element, go to the corresponding element indicated by "class" or "id" in the div tag 



## Notable Formating


