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

### Examples website update
#### Add a new lab member
Below are the steps to add a new lab member
1. Add the member's profile picture to folder `assets/img/{member_name}.jpg`
2. Modify the file `people.md` to add the new member's biography and link to the uploaded profile image

Example commit: https://github.com/chung-neuroai-lab/chung-neuroai-lab.github.io/commit/164e65df0eddc92564b58d463de2fe82a9a80378

#### Add a new publication
Below are the steps to add a new publication
1. Add the bibliography of the new publication: Go to Google Scholar, download the `BibTeX` file, add the `BibTeX` file to `assets/bib/{publication_name}.html`
2. Add an illustration image of the new publication: Go to the publication `pdf` file, screenshot an illustrative image, add the illustration image to `assets/bib/pub_imgs/{publication_name}.png`. Examples can be found at `assets/bib/pub_imgs`
3. Modify the `publications.md` file to include the publication's title, authors, short description, and links to the bibliography and illustration image

Example commit: https://github.com/chung-neuroai-lab/chung-neuroai-lab.github.io/commit/a2f3d042c6f73949139eac5b250240f5f068af47