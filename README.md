## Cassandra Zara 
T1A3 - Portfolio 
url: https://cassandra-zara.netlify.com/
GitHub repository: https://github.com/czara804/website_portfolio
Wireframes: https://www.figma.com/file/gtbDvN1qBY0XfNWnVDpDH8/Portfolio-wireframes?node-id=0%3A1
Moodboard: https://www.figma.com/file/f4F8NXraeTlY5MiGyNAxGx/Portfolio-moodboard?node-id=0%3A1

## Purpose & Target audience

This website serves as a digital resume and portfolio for prospective employers seeking developers. The website construction demonstrates proficiency with client software HTML and CSS, vital as a front-end developer. The website also showcases projects in Ruby to demonstrate skill and proficiency with back-end languages. The website is designed to look professional yet personal to help prospective employers gauge personality and skills with media links demonstrating an engaged approach and online presence as a developer. 

## Tech Stack 
- HTML
- CSS
- Git version control & GitHub
- Neflify for deployment
- Subresource Integrity (SRI)


## Sitemap

![](docs/sitemap.png)

Each page on the website is linked via navigation bar at the top of each page. The initial page is the Portfolio Home (Introduction) or index. From this page the user can navigate to and between 'About', 'Portfolio', 'Blog' and 'Contact'. 

A PDF of the Curriculm Vitae (mock-up) can be downloaded from the 'About' page. 
The 'Portfolio' page contains links to projects posted on GitHub. 
The 'Contact' page sends an e-mail to the owner using netlify-data. 
The 'Blog' contains a gallery, and individual posts each with a link to the original author. 

## Wireframes

Homepage 
![wireframes](docs/screenshots/wf_home.png)

About
![wireframes](docs/screenshots/wf_about.png)

Portfolio
![wireframes](docs/screenshots/wf_portfolio.png)

Blog
![wireframes](docs/screenshots/wf_blog.png)

Contact 
![wireframes](docs/screenshots/wf_contact.png)



## Functionality

The overall aesthetic and design of the website is to allow the user to explore as well as being able to identify the components clearly.

### Text Components

**Navigation Bar**
The navigation bar is located the top of each page for ease of access, with a skew to the right of large screens. The link's standard colours for 'visited' and underline have been removed as they disrupted the back and forth flow of the user. The links in the navigation bar highlight when there is a hover and the cursor has been made a pointer. The navigation bar switches to a column layout for mobile view for easier access. 

![nav bar](docs/screenshots/nav.png)
![header mobile](docs/screenshots/footer_mobile.png)

**Footer**
The footer is at the bottom of each page and contains icons as anchors for professional links such as Linkedin and GitHub, and social links (Instagram). The icons are shaped as hexagons to fit with the Art deco theme and coloured to quickly identify between them. The footer also contains copyright information. 

![footer](docs/screenshots/footer.png)

**'About'**
This component contains the text involving education history and also contains a button for downloading resume/CV. The box position is sticky and remains fixed on the page while the background images scroll, creating a parallax effect. The design intent behind this component is to create a 'journey' effect as the text content corresponds to the personal images - the mallee where I grew up, Gembrook forest and recent travels to Lisbon, Portugal. This effect was created via a negative margin for the first image. 

 **Homepage animation**

 The text components on the landing page (index) align with the background image and have a keyframes animation that moves down from the top of the page upon opening. This text element guides the reader to scroll down and engage in the website blurb and to create visual interest. This animation also contains the author's full name, as each of the other pages contains a logo with a shortened first name. 

 **Blog post**

 This component is replicated for each blog post to allow the styling to remain consistent. Each post contains a title, date with background image and hidden text. The collapsible text is designed via a hidden checkbox that when clicked ('Read more'), expands with a smooth transition. This component stayed true from the initial design stage to minimize the overall height of the page upon opening and for a neater, more minimalist style. 

![blog post collapsed](docs/screenshots/blog_collapsed.png)
![blog post expanded](docs/screenshots/blog-expanded.png)
### Graphic Components 

**Portfolio cards**

This component is a combination of image and text that is designed to group information relating to one portfolio item. The card is designed to be reusable in terms of HTML and CSS block, so that the portfolio can be expanded upon. The items are aligned within a grid with 4 columns in laptop viewport width and realign to 1 column in mobile view. 
The card component contains an image of fixed size for uniform design, a header, arrow, short blurb and external link for extra information or source code. 

![portfolio card component](docs/screenshots/portfolio_card.png)

**Contact form**

This form allows the user to contact the author by entering their details, a subject and message. The form utilizes netlify (the deployment platform), to send the message and show a confirmation message. The form is designed with flexbox to be responsive in mobile view and the button has hover elements with border outset and inset to demonstrate functionality. The form background is transparent to allow the background image to be viewed and link back to the homepage aesthetic. 

![contact form](docs/screenshots/contact.png)

**CV button**

The resume/CV can be downloaded as a PDF from the 'About' text section on the 'About' page. It is styled with CSS to look like a button with an underline and pointer upon hover to demonstrate functionality. The CV (currently a mock-up) would contain a more detailed work and education history, along with contact details. 

**Blog gallery**

The blog page contains a list of blog posts that are linked (anchored via id) straight to a post. The gallery images have been filtered with saturate to minimize colour distraction and increase brightness with hover to increase interactivity. Each list item contains an image, date published and brief title. More list items could be added as the blog grows. The list is responsive to mobile view and realigns to a column. 

![galley](docs/screenshots/blog_gallery.png)



## Responsiveness 

Flex, grid and media querys were used in an effort to make the website reponsive at mobile, tablet and laptop viewport widths. 

See screenshots below at mobile viewport width. 

![home](docs/screenshots/responsiveness/rhome.png) 
![about](docs/screenshots/responsiveness/rabout.png)
![portfolio](docs/screenshots/responsiveness/rpf.png)
![blog](docs/screenshots/responsiveness/rblog.png)
![contact](docs/screenshots/responsiveness/rcontact.png)


## Accessibility

- Accessibility for people with colour-blind vision was checked using 'Colorblind - Dalton for Google Chrome'
- Semantic HTML was used throughout the code for better use with screenreaders. 
- aXe 
- HTML validation via 'https://validator.w3.org/'


## Style Aesthetic & Design Variations

The website's aesthetic follows an Art Deco color theme of dark and mid blues with yellow/gold, black and white elements. 
The header banner with name logo was styled in yellow and dark blue as the contrast means they are easy to read from far away as a combination and the text colour was modified to a dark blue to fit the aesthetic. There is also low saturation in the colours used. The font family used wwas Ivymode from Adobe fonts which is commonly used in fashion magazines and is clear and has high readability.  

![logo](docs/screenshots/logo.png)

**Main Design**
Master Branch:

![master theme](docs/screenshots/artdeco.png)

**Pink Aesthetic**
Pinkblue Branch:

![Branch Pink Aesthetic](docs/screenshots/pink.png)

## Mood boards

![Moodboard](docs/screenshots/mood_board.png)
![Moodboard](docs/screenshots/pink_mood.png)

## Design Process

- Mood Board using Pinterest and Figma
- Wireframes using Figma
- Started with Navigation and Footer as bookends for page (see pflayout.css) and linked to each HTML page. 
- Layout for portfolio using grid and flex component with placeholder text. 

![Process](docs/screenshots/process_about.png)
![Process](docs/screenshots/process_blog.png)
![Process](docs/screenshots/process_contact.png)
![Process](docs/screenshots/process_home.png)

- Layout for blog with collapsible text and gallery 
- Contact via netlify form (attempted to use php but this did not work effectively once deployed on netlify.)
- About page created using parallax for personal images to have ‘journey feel’ for the user. 
- Homepage with central image to tie together aesthetic and then styled whole website with colour swatches to link toegther in a theme. 

## Branches 

Multiple branches were made using Git and GitHub. The current master design was initially on an 'artdeco' branch but was then merged back into the master branch. There are currently 5 branches, with the intention of also fleshing out a 'greentheme' design based around nature with a sticky side navigation. 

Master branch: current design with 'art deco' theme 
Branch pinkblue: Earthy/pinks aesthetic
Branch minpink: More basic layout with variations on colour and background, used as a back-up of initial layout. 