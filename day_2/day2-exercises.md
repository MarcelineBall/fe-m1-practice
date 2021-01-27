
First Reading
    1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?
      1. Ordered lists are have each item with a number preceding them <ol><li><li/><ol/>
      * Unordered lists begin with a bullet point and do not imply hierarchy <ul><li><li/><ul/>
      Definition lists: A set of terms paired with the definitions of the terms <dl><dt><dd><dd/><dt/><dl/>
    2. What is the basic structure of an element used to link to another website?
    <a href="http://www.theurl.com">Text that describes the link</a>
    3. What attribute should you include in a link to open a new tab when the link is clicked?
    after the url you use ` target="_blank"`
    4. How do you link to a specific part of the same page?
You need to use an id attribute to the part of the page that you are trying to link to and then use `<a href="#atrribute_id">`

Second Reading

  1. What is the purpose of CSS?
CSS allows you to specify how the content of the elements will appear
  2. What does CSS stand for? What does cascading mean in this case
Cascading style sheets. Rules that come later in the style sheet will override rules that appeared earlier
  3. What is the basic structure of a CSS rule?
  ```
  selector {
    property: value;}
  p {
    font-family: Arial;}
  }
  ```
  4. How do you link a CSS stylesheet to your HTML document?
in the head of the html `<link href="css/styles.css" type="text/css" rel="stylesheet" />`
  5. When is it useful to use external stylesheets as opposed to using interal CSS?
When making a site with more than 1 page, having a single external stylesheet allows for styling to be consistent, and you can make changes to the entire site by editing one file.
  6. Describe what a color hex code is.
hex code is a 6 character code used to represent the amount of red green and blue in a color
  7. What are the three parts of an HSL color property?
Hue: the coloquial color, Saturation: the amount of gray in a color, and Lightness: the amount of black or white in a color
  8. In the world of typeface, what are the three main categories of fonts? What are the differences between them?
Serif: Have extra detail on the ends of letters, Sans serif: straight ends to letters, monospace: letters are all equal in width
  9. When specifiying font-size, what are the main three units used?
  Pixels, percentages and ems
