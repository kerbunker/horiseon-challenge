# Week 1 Challenge

## Horiseon Social Services Refactor

This week I helped Horiseon Social Services to clean up the code for their website and make it more in line with accessibility standards.

### Changes made to pre-existing code

The title of the site was previously "website"
* Title has now been updated to reflect the content of the site.

Previously everything was in a div tag
* Added the header and footer into header and footer tags
* Within the header, the navigation elements were added to a nav tag
* Added section and article tags

Every item had its own class even when the item used the same style as other items
* A single class was used for each set of items that used the same CSS styling. This allowed me to cut down on a lot of repetitive code.
* These items include each benefit that each had their own class as well as each of the main content items that also each had their own class despite their shared styles

The navigation links were not all set up correctly to direct the user to the appropriate section
* The nav links in the nav section of the header should now all send the user to the appropriate section of the page.

Some accessibility issues were found in the site originally
* alt tags were added to images to assist with screen readers and those with slower internet that may not be able to load the page as easily.

The code for the website was not very reader friendly
* Comments were added to help organize and explain the different sections in the index.html file as well as the CSS stylesheet.
* Some heading tags were changed to better align with the contents of the page. The benefit section all had h3 tags despite not being a child of an element with an h2 tag. These h3 tags were changed to better align with the content and flow of the page.

### Links
* Github repository: [kerbunker/horiseon-challenge](https://github.com/kerbunker/horiseon-challenge)
* Deployed website: [kerbunker.github.io/horiseon-challenge/](https://kerbunker.github.io/horiseon-challenge/)

![screenshot](/assets/images/page-screenshot.png)
