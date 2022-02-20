# Semantic Markdown of Horiseon Social Media Marketing Website


## Description

The task is to modify the Horiseon Social Media Marketing Website follow accessibility standards and consolidate the CSS code, but produce a website that is visually the same as the original.


Original Website Display

![Original Horiseon Social Media Marketing Website](/assets/images/Original_Wesite_Display.png)

Accessible Website Display

![Modified Horiseon Social Media Marketing Website](/assets/images/Accessible_Wesite_Display.png)


## Process

After creating a GitHub repository for this project, I modified the existing index.html and style.css files for the Horiseon Social Media Marketing Website given to me by my instructor from the UW Coding Bootcamp to follow accessibility standards and consolidate the CSS code. The task was to produce a website that is visually the same as the original, but follows accessibility standards. See the links to my repository and the accessible website below.

- [Git Hub Repository](https://github.com/areitan/SemanticMarkup)
- [Accessible Website](https://www.example.com)

### index.html

1. Added a more descriptive title in ```<title>``` element.
2. Changed all ```<div>``` elements to semantic elements, including ```<header>```, ```<nav>```, ```<main>```, ```<section>```, ```<aside>```, and ```<footer>```.
3. Added comments to identify sections of content.
4. Changed original heart symbol in the footer to a ```<figure>``` element with heart unicode for accessibility. Note: ```<i>``` tag only italicized the text, so I used the ```<figure>``` element.
5. Added a class to heart ```<figure>``` in footer to match the color and size in the original website.
6. Changed class selectors to match consolidated CSS class selectors.
7. Fixed broken *Search Engine Optimization* link in navigation links.
8. Added alt attributes to all images.


### style.css

1. Updated CSS selectors to match index.html semantic elements.
2. Added comments to identify what CSS selectors do.
3. Changed some class selector naming to consolidate CSS code.
4. Removed redundant CSS selectors and their attributes.


## How To Contribute

Complying with accessibility is important for those with disabilities. You may update or add semantic HTML tags to index.html or improve the CSS styling in style.css.


## Credits

- [MDN Web Docs HTML: A good basis for accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML)
- [W3 School HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [W3 School CSS Selectors](https://www.w3schools.com/css/css_selectors.asp)
- [Injosoft HTML Symbols - Unicode symbols, entities and codes](https://www.htmlsymbols.xyz/heart-symbols)
- Trilogy Education Services, LLC for the original code





