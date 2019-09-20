# ArtShack – Art Gallery Website
## Stream One Project: User-Centric Frontend Development - Code Institute
<a href="https://gph.is/g/4gBXGGX"><img src="https://media.giphy.com/media/QZ84AEYaGHtxDUTtRc/giphy.gif"/></a>

This is a website for a local contemporary art gallery, ArtShack to promote its artists to potential art collectors. The website contains various visual elements that highlights the activities of the art gallery - information on the gallery’s upcoming exhibition, a summarized biography of its house artists, interactive images, a contact form as well as a newsletter subscription form.
## UX
My goal in the design was to ensure that viewers are seamlessly able to access information about the gallery on the site while striving for a minimalistic colour-blocking design to suit its branding. A vintage colour palette was achieved using a triadic colour scheme – containing both warm and cool primary colours. This adds neutral, calming, yet eye-popping look which adds a playful aspect to it.

With a user-friendly design, viewers would be able to catch a glimpse of the gallery’s upcoming exhibition, featured collection and even communicate with us via the contact form, all in the homepage. And if they are interested in receiving prompt updates about future events, they can have the option to subscribe to the gallery’s newsletter via the ‘Subscribe’ button on the navigation bar. The gallery’s registered company name, address and contact details are also placed at the footer of all pages for their ease of access. 

To maintain the minimalistic aspect of the design and prevent overcrowding of information, I included external PDF attachments of documents with complete information. Once they seek more information on the exhibition details, they can click on the hyperlink that links them to a downloadable PDF version of the exhibition catalogue and full biographies of the artist. 
## Technologies
1. HTML
2. CSS
3. Bootstrap (4.3)
4. Javascript
## Features
- Navigation bar is mobile responsive and collapses upon viewing the page via mobile devices
- Modal pop-up subscription form upon toggling the ‘Subscribe’ button at the Navigation Bar and page footer
- Logo redirects to Homepage (index.html) upon clicking
- Page footer has additional call to actions that will place a phone call (tel:), launch the user’s mail client ready to send email to the page’s email address (mailto:) and follow the page’s socials
- Responsive to all iOS and Android devices as well as browsers Chrome, Firefox and Safari
- In the ‘Collection’ section, image text captions appear on hover using CSS and on the Artists page (artists.html), image collage appear on hover using Javascript
- Form validator activated on Contact Form
## Features Left to Implement
For design, I would like to add more animations to the website that animate on hover, animate on scroll, fix the positioning of the collapsed navbar to the right side of the page, and adjust the positioning of the ‘Close’ button to the top right-hand corner of the pop-up modal subscription form. For functionality, I would add a form validator to the subscription form.
## Testing
Users are able to view the activities of the gallery as the homepage has a Hero Image that consists of an interactive carousel featuring some artwork from the exhibition. If the user is keen to browse the collection, they can click on the carousel and be redirected to the ‘Collection’ section of the Homepage (index.html). Along with the ‘Collection’ section, the ‘Exhibition’ and ‘Contact’ section of the Homepage can be accessed through the navigation bar.

All links have been manually tested to ensure that they redirect the user to the correct destination.

A form validator is included in the ‘name’, ‘email’, and ‘message’ fields of the contact form. This is to prevent users from submitting the form with invalid details or incomplete information. If the user tries to submit the contact form with an invalid email address, there will be an error noting the invalid email address. And the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all fields are valid, the page will reload.

Upon clicking on the ‘Subscribe’ button at the Navigation Bar and footer, the pop-up modal form will appear at the top of page. However, for small and medium devices, this aspect made the ‘Subscribe’ button at the footer unusable. to appear out of the user’s screen mobile devices.

To ensure compatibility and responsiveness, the site was tested across multiple browsers such as Chrome, Safari and Internet Explorer and on multiple android devices - Galaxy S5, Pixel 2, Pixel 2 XL and iOS devices - iPhone 5-X, iPad and iPad Pro.

Upon testing, the text alignment of the Home page and About page was not compatible with Internet Explorer.

## Deployment
This site can be viewed (here)[https://lynette-lyf.github.io/artshack/]. This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/lynette-lyf/artshack into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.
## Credits
### Content
Only the content in the homepage (index.html) and ‘Mission & Vision’ section of the About page (about.html) were written by me.

Content in the ‘Our Story’ section of the ‘About’ page is taken from https://www.artporters.com/about-us/

Content in the ‘The Team’ section of the ‘About’ page is taken from https://theartling.com/en/info/team/

Content in the ‘Doãn Tú Ly’ section of the ‘Artists’ page is taken from https://www.dawn-ng.com/bio

Content in the ‘Song Ye-Jun’ section of the ‘Artists’ page is taken from https://theartling.com/en/artists/benny-teo/
### Media
All photos were taken from [Pexels](https://www.pexels.com/), a stock image library, with the exception of the gallery’s logo which I created.
### Acknowledgements
Font converted to CSS using [font-converter.net](https://font-converter.net/en)

Customized BootStrap4 CSS Styling credits to [Saranya Rajendran](https://stackoverflow.com/questions/49400853/how-to-change-navbar-hover-color-on-bootstrap-4/49405726)

Image appear on hover credits to [dedman](https://stackoverflow.com/questions/51232278/image-appear-when-hover-the-text-html-bootstrap)

**This is for educational use.**
