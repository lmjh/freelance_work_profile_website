# Freelance Work Profile Website

The purpose of the site is to provide information about my freelance services to prospective clients and provide contact details to both new and returning customers.

I primarily cater to local businesses, freelancers and charities. My clients are usually looking for a locally-based developer to work with and aren't usually interested in many technical details.

The site is designed to provide easily accessible, relevant information to my target audience. I have used a responsive, mobile-first design to ensure the site is effective and well laid out across a range of devices.

***

## User Experience

Most users of the site will be either prospective new clients or returning clients. 

### New Client User Stories

* As a prospective new client, I want to quickly and easily understand the services on offer so I can decide if they might meet my needs.
* As a prospective new client, I want to learn about the experiences of previous clients so I can determine if the service is reliable.
* As a prospective new client, I want to know how to request more information or hire the freelancer.
* As a prospective new client, I want to quickly be able to understand how to navigate the site to find the information I need.
* As a prospective new client, I want to learn more about the freelancer so I know who I might be working with.

### Returning Client User Stories

* As a returning client, I want to quickly find information on services offered.
* As a returning client, I want to be able to contact the freelancer through my preferred communication method. 

### Design

The overall design of the site is clean and minimalist, to highlight the content and prioritise ease of use.

#### Colour Scheme

* The site employs a limited colour palette, striking a balance between cooler, professional colours and warmer, friendly colours. 
* A colour is associated with each section of the site and used to visually link the navigation bar and the content through coloured underlines of links and section headers. This helps to orient users, establish a feeling of consistency, and provide visual feedback that an action (clicking a coloured link) has had an intended effect (taking the user to the section with the matching colour).
* Colours are used sparingly so as to maintain the clean look of the site and prevent the page from becoming too visually ‘busy’.

#### Typography

* The site uses clean-looking, attractive fonts that are very easily legible.
* The main font used for the body of the website is Montserrat, a clean, modern-looking sans-serif font that is frequently used in web design because of its attractive appearance and legibility.
* Section headers use Josefin Sans, another popular web font that has clean geometric lines and a few subtle visual flourishes on some characters (such as the capital W), while maintaining high legibility. 
* Uppercase letters with a little extra letter spacing are used for most section headings to provide visual contrast with the body text and subheadings. The exception to this is the home section, which has an informal greeting as a header rather than a standard section title. To maintain the casual, informal feel and contrast with the other sections, lowercase letters are used here.
* Both fonts have a fallback set to sans serif, in case the external Google Font fails to load.

#### Imagery

* The home section is intended to serve as a friendly and welcoming introduction, so it is illustrated by a simple vector drawing of myself, to accompany the informal greeting header and the introduction text. To help establish visual consistency, the drawing uses the same limited colour palette as the website for the clothing, eye colour and background.
* Font Awesome icons are used to illustrate the Services section. The icons are set against simple coloured backgrounds, using the website’s colour palette. 
* The testimonial section currently uses fictitious people and quotes, so stock images of people are used to illustrate these and help to establish trust with potential clients. The images selected are intended to represent a range of potential clients: a teacher in front of a whiteboard, a business person in a suit, and a person in front of a colourful, graffitied background, intended to imply creativity. These images would be replaced with real images of actual clients in a final live version of the site.
* An image of a mountain lake in my part of the country is used to illustrate the About section, to reinforce the idea that I’m a rurally-based developer who works with local businesses.

### Wireframes

The site is responsively designed to adapt to the viewing device.

![An illustration of the landing page on different devices](documentation/wireframes/responsive-layouts.png)

Full layout wireframes for different sized devices can be viewed here:
* Mobile Full Layout Wireframe - [View](documentation/wireframes/mobile-layout.png)
* Tablet Full Layout Wireframe - [View](documentation/wireframes/tablet-layout.png)
* Desktop Full Layout Wireframe - [View](documentation/wireframes/desktop-layout.png)

***

## Features

* A simple navigation bar to allow users to easily find content.
* Clear and concise information on services.
* Testimonials from previous clients.
* Clear and readily accessible contact details and a simple contact form.
* Responsive design.

***

## Organisation of Content

The site contains relatively few features and doesn't have a large amount of content to accommodate, so a single page with clearly delineated sections and a simple and always-visible navigation bar would be a good solution. Although the content could be spread across multiple pages, this would add an unnecessary  burden on the user to click between pages to load and view content. Some of the pages would also be quite sparsely populated with content. From an SEO perspective, it's generally considered better to have a single content-rich page than multiple thin pages.

Because the main purpose of the website is to describe and promote my services to prospective clients, content sections will be prioritised in the following order:

1. A home screen / hero area with a clear and concise description of the purpose of the site and the services available.
2. A section with further details on the services on offer. This will be more detailed than the hero area, but still concisely written.
3. A section featuring testimonials from previous clients.
4. A section with further details on myself, my experience and my work.
5. A section with contact details and a contact form.

N.B. Although providing contact details is a priority for both the business and the users, the contact details section has been placed at the bottom of the page for the following reasons:

* Providing useful information to new users is a higher priority than providing contact details. Most new prospective clients won't want to contact a freelancer until they have an understanding of the services on offer.
* There is a convention that contact forms are usually placed at the bottom of single-page websites. Many users will expect the form to be positioned there and can quickly scroll to the bottom of the page to find it. I don't see a good reason to break this convention here.
* The low positioning of the form / details will be mitigated by frequently placing buttons linking to the form throughout the other sections. This acts as a call to action and ensures the contact section is always readily accessible.

***

## Technologies

### Languages Used

* HTML5
* CSS3

### Frameworks, Libraries & Programs Used

1. [GitHub](https://github.com/) - Used for version control and deployment through GitHub Pages.
2. [GitPod](https://gitpod.io/) - Used to write all code and test before deploying to GitHub.
3. [Balsamiq](https://balsamiq.com/) - Used to produce design wireframes.
4. [Bootstrap](https://getbootstrap.com/) - Version 4.6 used extensively throughout the project, including the responsive grid, navigation bar, services section cards, testimonial carousel, and the form and button styles, and the contact button modal. [Official documentation for Bootstrap 4.6](https://getbootstrap.com/docs/4.6/getting-started/introduction/) was also used extensively for reference.
5. [Affinity Designer](https://affinity.serif.com/en-gb/designer/) - Used to put combine wireframes for documentation and to crop and edit site images.
6. [Fontawesome](https://fontawesome.com/) - Used for services section and contact section icons. Installed via [cdnjs](https://cdnjs.com/libraries/font-awesome).
7. [Google Fonts](https://fonts.google.com/) - Used for heading font ([Josefin Sans](https://fonts.google.com/specimen/Josefin+Sans)) and body font ([Montserrat](https://fonts.google.com/specimen/Montserrat)).
8. [coolors](https://coolors.co/) - Used to help design colour scheme. 
9. [Pexels](https://www.pexels.com) - Used to source images for Testimonials and About sections.
    - About section image: [Lake Surrounded by Mountain, by Lukas Hartman](https://www.pexels.com/photo/lake-surrounded-by-mountain-1462012/)
    - Testimonial image 1: [Woman Standing Near Whiteboard, by Christina Morillo.](https://www.pexels.com/photo/woman-standing-near-whiteboard-1181519/)
    - Testimonial image 2: [Men's Wearing Black Suit Jacket and Pants, by mentatdgt](https://www.pexels.com/photo/men-s-wearing-black-suit-jacket-and-pants-937481/)
    - Testimonial image 3: [Woman Leaning on Teal and Red Wall, by Luis Quintero.](https://www.pexels.com/photo/woman-leaning-on-teal-and-red-wall-1575996/)
10. [uifaces.co](https://uifaces.co/) - Used to help find appropriate images for testimonial section.
11. [NameFake](https://en.namefake.com/) - Used to generate fake names for testimonial section.
12. [Inkscape](https://inkscape.org/) - Used to draw vector portrait for homepage.

***

## Testing

Please see [TESTING.md](TESTING.md) for full details of tests performed and bugs fixed.

***

## Deployment

***

## Other Credits and Acknowledgements
