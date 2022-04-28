# CES UDM
This site is intended to show the benefits of the lock CES UDM. It will show some unique features it has. The site also have a contact form so it will be easy to contact us and get more information about prices and other information. The site will also have an about section that will build trust towards the customers.

The target for this site is other companies such as real estate owners, schools, hospitals and other companies that have a lot of doors and on need of big and complex locking system.

Welcome to [CES UDM](https://spangen87.github.io/rikard-spangmyr/).

![Image with different screen sizes of the page.](assets/readme-images/responsive.jpg)

## User Experience (UX)
### Wireframes
Wireframing was done before the project started. Some changes has been made on the way because it looked better on different screen sizes. And it is now following the same proportions through the site.

![Wireframe 1](assets/readme-images/wireframe-1.jpg) ![Wireframe 2](assets/readme-images/wireframe-2.jpg)
![Wireframe 3](assets/readme-images/wireframe-3.jpg) ![Wireframe 4](assets/readme-images/wireframe-4.jpg)
### Site Structure
The CES UDM page have one scrollable page with three sections: [Why CES?](https://spangen87.github.io/rikard-spangmyr/#why-ces), [About](https://spangen87.github.io/rikard-spangmyr/#about) and [Contact](https://spangen87.github.io/rikard-spangmyr/#about). Each section is linked in the header navigation meny. There is also one more page that confirms that you have filled out the form, [Contact Confirmation](https://spangen87.github.io/rikard-spangmyr/contact-confirmation.html).
The sections order i thought of. The Why CES should build an interest of the products, the About section should build some trust and finally the Contact section where the visitor can take the step to make contact is it's interesting to them.
### Design Choices
#### Typography
I choosed to use Roboto on the whole site. I wanted a clean look to the text and thought that Roboto was a good choice. To give the headings some additional styling I made them all uppercase and gave them some spacing between letters.
#### Colors
Since CES already have a color on the logo I used that in the color scheme of the site. Then I wanted to complement with some subtile colors and choosed a very light grey and also a dark grey color.

![Image of the color scheme](assets/readme-images/color-scheme.jpg)
## Features

### Existing features
#### Navigation Bar
- A navigation bar with links to the diffrent sections on the page. Home, Why CES?, About and Contact Us.
- This will make it easier to navigate to preffered part of the page.

![Image of navigation bar](assets/readme-images/navigation-bar.jpg)

#### Hero image
- An image that covers the full width of the site and that is fully responsive. 
- This section gives the user a feel for the quality of the locks and what high end finishes that are available.

![Image of hero image](assets/readme-images/hero-image.jpg)

#### Why CES?
- Three sections with a picture to each section. Shows what is unique with this lock and what safety functions there is.
- Gives the user a quick overview with short text and descriptive images.

![Image of why ces section](assets/readme-images/why-ces.jpg)

#### About
- Here the history av the company is presented with text and three pictures of the present and today. A video from the comapny shows some refereces for buildings using the locks today and some stories from the company.
- The section aims to build trust towards the visitor by showing that they are developing all the time and have been around for nearly 200 years.
- One of the pictures shows the Swedish team working with CES.

![Image of about section](assets/readme-images/about.jpg)

#### Contact Us
- This section gives the user an easy way to contact the company and see where it's located.
- There is a form to fill out with a message to the company to show that they are interested and want to know more. The form is for educational purpuse and no mail will be sent when submitting. The form has four fields to fill out which are required
- There is also a map helping the visitor find the company if they want to visit in person. This address is real, but it's for educational reason, and no sales are made at this address.

![Image us contact section](assets/readme-images/contact.jpg)

#### Footer
- The footer section shows the address, mail and phone number to the company.
- Below there is icons with links to social media pages. Those are for educational purpuse and will only link to the starting page for each social media.
- There is also an icon to send an direct email to the company. This link will open the deafult email program for the visitor. This email is real and is working.

![Image of footer section](assets/readme-images/footer.jpg)

#### Form confirmation page
- This page validates the form input. There is no function for collectiong the data entered at this point. 
- There is a link back to the index page so you don't need to use the back button in the browser. If you click the logo in the top it will also bring you back to index page.

![Image of the form confirmation page](assets/readme-images/confirmation-page.jpg)

### Future Features
- A working form that collects the data and sends an email to the company.
- A shop page where you can buy simple single lockings directly from the page. This would need an e-commerce platform.

## Technoligies Used
- [HTML](https://html.spec.whatwg.org/) - is setting the structure and the content of the website.
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html) - providing the style for the pages.
- [Gitpod](https://www.gitpod.io/#get-started) - used to develop and deploy the site.
- [GitHub](https://github.com/)  - is used to host the site.
- [Balsamiq](https://balsamiq.com/wireframes/) - was used to make the wireframes.

## Testing
### Browser Testing
- Tests on Safari for MacOS was made through [Browserstack](https://live.browserstack.com/) because I had no computer with MacOS available in the process.
- Google Chrome was used during the develpment and there is no known issues in that browser.
- The compability with Mozilla Firefox is tested through the development. No known issues in that browser.
- Microsoft Edge is also tested with no known issues.

### Responsiveness Test
The responsive design for mobile devices is tested with [Googles Mobile Friendly Test](https://search.google.com/test/mobile-friendly).
Manual testing is also made with [Google Chrome DevTools](https://developers.google.com/web/tools). In DevTools I have checked that screens with width from 2560px down to 375px looks good and working properly.

### Accessibility Testing
The accessibility was tested using [Lighthouse](https://developers.google.com/web/tools/lighthouse).
- Performance shows how the page perform in terms of loading speed.
- Acessibility shows how accessible the page are for all users.
- Best Practices shows that the site uses industry standard practices.
- SEO shows Search Engine Optimisation.

Results for [CES UDM](https://spangen87.github.io/rikard-spangmyr/index.html) page:

![Picture of results från Lighthouse](assets/readme-images/lighthouse-result.jpg)

### Validator Testing
The site is tested with [W3C HTML Validator](https://validator.w3.org/) for the HTML and for the CSS with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/).
At first there were a couple of minor errors, mostly typos that were easy to fix. 

Here is the results:

![Image validating the HTML of Index](assets/readme-images/html-validation.jpg)

![Image validating the CSS](assets/readme-images/css-validation.jpg)

![Image validating the HTML of Confiramtion page](assets/readme-images/html-validation-confirmation-page.jpg)

## Bugs
### Solved
- Found a bug that made ul in nav not completely in the center on smaller screens. I used dev tools to found that there was a padding to the left of the ul that made the distortion. Solved the problem by just adding padding 0 to the ul.
- When doing the validation i realized i had put the script for [Font Awesome](https://fontawesome.com/) below the body. The issued was fixed by moving it inside the body at the bottom instead.
- In the validating of the CSS file I found out that I had forgot to add size for the font at one place. The fix was simply to add the size in correct format.


## Deployment

## Credits
### Content
- The font is picked from [Google Fonts](https://fonts.google.com/).
- The icons came from [Font Awesome](https://fontawesome.com/).
- The video is embedded from [Youtube](https://www.youtube.com/).
- The map is embedded from [Google Maps](https://www.google.com/maps).
- Some text pieces is from the original site for [CES](https://www.ces.eu/).
- Insipration to the form validating page was given from my mentor [Precious Ijege](https://www.linkedin.com/in/precious-ijege-908a00168/) and from this repository on [GitHub](https://github.com/EwanColquhoun/wawaswoods).

### Media
- Photos are all from [CES](https://www.ces.eu/) exept from the picture of the team in the about section. That foto is taken an edited by the developer [Rikard Spångmyr](https://www.linkedin.com/in/rikard-sp%C3%A5ngmyr-126ab436/).
- Photos were compressed using [TinyPNG](https://tinypng.com/).
- The photos that needed editing is edited in [Adobe Photoshop](https://www.adobe.com/se/products/photoshop.html).

## Acknowledgements

