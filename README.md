# LemonTree - The Clean lemonade company.  

In a marketplace saturated with soft drinks & energy drinks full of artificial ingredients,  
we wanted to cut through the noise and provide the consumer with the simplest/ tastiest/ 
most pure water alternative out there. Using healthier drinks to make healthier people.

The idea of this project was to provide our users both consumer and business, with an 
easy access platform to purchase our product as well as discover all the benefits lemonTree has to offer them. 


# UX

### Site owner's goal: 

To set up a web platform that showcases the unique features of the product and allows customers or vendors to order from 
and make enquiries directly with the company. 

### External User's Goal :

The sites users are health conscious people or highend restaurants/cafe's who are looking to purchase a
cheaper, healthy, 100% green re-usable product as an alternative to mainstream soft-drinks.

### User stories :

**Clancy** is the owner of a busy highstreet-side cafe in Richmond he is known for his home made pasteries
and his cafe food is celebrated by local retail and office workers as a delicious healthy reasonably 
priced lunch option that keeps them from going to the fast food chain restaurants in the area. 
His clients love his coffee but he finds that many of them would be more inclined to visit frequently
if he had a larger variety of fresh drinks to go with his tasty sandwiches. He is presently loosing 
business to local pharmacies and offlicences which provide a range of main brand high in sugar soft drinks.

**Nancy** is a young mother of 4 she lives in a very busy area in southeast london with her husband Ralph and
their two cats Thor and loki. Running a household is a full time job and its made more difficult as she also
works part time as assitant manager of a local brewery. Her kids are all very active, take part in sport and 
often drink energy drinks to replenish after a game/session. As any mother who cares for her children's health 
she wants to make sure her kids aren't taking in energy drinks with too much caffeine or substances that could
be harmful to their development and is unsure about all the ingredients she sees when looking at the labels on
some of the drinks she finds in her local supermarket. She wants something that she can smart her kids into taking
that is both tasty and good for them.

### Typography

The font Inter was chosen from the google fonts catalog for its flexibility/simplicity and modernity. It is extremely versatile and appears distinctive in both bold and regular formats.
As a derivitive of open sans it instantly recognisable and went well with the playful colour-scheme of the site. 

### images

The images were all sourced from unsplash.com and all artists can be found credited below. Opaque overlays were used to bring out the contrast between the Typography and the image. You may notice that the colours dont deviate far from the green white and grey colorscheme
and in the case of the about me and ingredients section all images picked feature hands, picked purposefully to mirror the handmade image of the product and thus taking the customer away from the mass produced imagery of other brands.

### Wireframe

![Image of wireframe](assets/images/wireframe.jpg)


 # features

  ### index.html

 * Navigation section - Responsive navbar design which keeps its uniformity on both mobile and desktop devices.
                        featuring a collapsible hamburger menu designed with bootstrap, Company logo (centered)
                        and a sign up icon which leads the user to the newsletter portion of the site.
 * Callout section - Full viewport background image wih centered callout text as well as call to action **Buy Now!** button.
 * About us section - Featuring mini company Bio as well as Health focused Company Ethos
 * Ingredients section - Showcasing lemontree's ingredients and unique value proposition done for transparency 
                        between company and comsumer. 
 * Testimonial section - Featuring horizontal/side scrollable range of positive feedback from past consumers which flips to a carousel design for mobile devices. The latter being sourced from bootstraps documentation.
 * Social link footer section - Providing ways to get in touch with the company through various forms of social media.
                                aswell as a newsletter sections where customers can sign up to receive information on the
                                doings and initiatives. 

 ### purcahse.html

* pricing plan section - This section features 3 seperate subscription plans with added value incementally with the increase of price on both premium and family options.
                        there are also selectors for different options of flavour. This section is also fully responsive on all screen sizes



 * Buy for business section - the company is taking more of a hands on approach and is looking to cultivate long term 
 relationships with new businesses, which is why the form section comprises of email and phone inputs as well as a text area.
 for companies to express their interest in the product.


 * try section - As the brand is still relatively new the site is currently exhibiting a try section for consumers
 to get familiar with the product. This section features a simple address form and a call out section.

### blog.html

* Blog section with three different entries speaking about the company ethos as well as the company's pledge to charity
there is also a third option which appears on reduced screens.

 ## Future Features to implement:

### major
 
 * Possible future articles for blog page.
 * fully realised transaction page with js.

 
 ### minor

* all features implemented.

# Technologies used
 
### Bootstrap
Specificially its grid system to create a responsive mobile first design, simplify the positioning of certain elements of the website as well as the navbar and pre-made classes for the forms on purchase.html and cards on blog.html

### HTML  
Was used to write all the front end code on the website.

### CSS 
Used throughout and provides styling to all sections of the website.

# Testing

The HTML was tested using https://validator.w3.org/ 
The CSS was tested using https://jigsaw.w3.org/ (validator can't parse root variables)

The site renders as expected on all pages and after testing there was a correction made to the file paths to the images
in the testimonials section and the cards featured in blog.html.

The site was tested on: 
13" Macbook pro display, 
15"Macbook pro display, 
iPhone X/11/11Pro/11pro max
iPhone 6/7/8 and plus models
iphone 5s/SE
Galaxy s11
Pixel 2
iPad Air
iPad Pro

And renders on both chrome and safari.
but does break when using microsoft edge.

The site was tested by two users one was a 27 year old male with a background in Frontend/Backend development
The second a 24 year old female Who identifies as preferring to make purchases online. 

The users where tasked to:

* Identify the main Elements in the first section - both users identified, The navbar, Dropdown menu, and Buy button successfully.

* **Addendum after testing**  The sign up button was changed to read subscribe in order to make it easier to understand that it points to the newsletter in the footer section of website.

* Using the navbar to navigate to the ingredients and about me section - both users performed the task with ease.

* users where then tasked to read through the about me section - the text was darkened in the mobile version to increase visibility as well as a light overlay was applied to the background.

* testimonial section - Both users navigated the section successfully

* navigate to the buy page - perfomed successfully with both links found in callout section and navbar.

* **Addendum after testing**  there was an issue reading the forms on the buy page so a semi-transparent dark overlay was added to the background images. 

* the blog page was easy to use - links were reported as not fully functional, which is fine as the extensions to the blog pages full articles are yet to be implemented.

* **Addendum after testing** Both links to the buy.html and blog.html pages were originally set to **target="_blank** however  this was changed as it was founf to be bothersome to users to have multiple pages open and both users reported that it broke the sites feeling of continuity.

# Deployment

I've deployed the site using GitHub Pages, and is available here: https://pipicallu.github.io/LemonTree/

For this project, local deployment was not required.

# Credits

### Content
All content written was original but wikipedia was used to research The health benefits of ingredients mention on the site.
particularly this article : https://en.wikipedia.org/wiki/Coconut_sugar

Font awesome - was used to to diplay icons on the website.

Google fonts was also used to provide the styling and typography. 

### media
The photos used on the site were obtained exclusively from unsplash.com 
with special thanks to photographers:
* Alexander Krivitskiy
* Andy falconer
* Aston Graham
* Ben Sweet
* Emmanuel Ben Paul
* Jenny pace 
* Louis Hansel
* Milad Shams
* Nathan Dumlao
* Reka Biro Horvath
* Seth Doyle
* Tata Zaremba
* Zahra Owji

### Acknowledgements

The whiskey drop landing page as seen in the user centric development module, as well as the coca-cola uk website were definitely the two main inspirations for the desgin of this website.
