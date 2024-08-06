# [Experience Valencia](https://desireealexia.github.io/Experience-Valencia/index.html)

![Am I Responsive](/assets/design/ev_responsive.png)

Experience Valencia is a comprehensive, user-friendly online guide for tourists visiting Valencia, Spain, providing information on attractions, cuisine and practical tips. This guide can also be used by nomads, expats, and residents of Spain.

## Table of Contents

- [UX](#ux)
  - [Project Goals](#project-goals)
  - [User Stories](#user-stories)
  - [Design](#design)
  - [Wireframes](#wireframes)
- [Features](#features)
  - [All Pages](#all-pages)
  - [Home Paege](#home-page)
  - [Explore Valencia Page](#explore-valencia-page)
  - [Contact Us Page](#contact-us-page)
- [Accessibility](#accessibility)
- [Technologies Used](#technologies-used)
  - [Languages](#languages)
  - [Frameworks, Libraries & Programmes Used](#frameworks-libraries--programmes-used)
- [Testing](#testing)
- [Deployment](#deployment--local-deployment)
  - [Deployment](#deployment)
  - [Local Deployment](#local-deployment)
- [Credits](#credits)
  - [Code](#code)
  - [Media](#media)
  - [Content](#content)

# UX

## Project Goals

- **Provide a comprehensive guide to Valencia, Spain:** Focusing on top attractions and local cuisine to offer valuable information to tourists.
- **Ensure ease of navigation:** Design the website to be user-friendly, visually appealing and informative.
- **Offer practical tips and contact form:** Include sections that provide useful information and an easy way for users to get in touch.

## User Stories

### Client Goals

- **Increase awareness of Valencia:** Promote Valencia as a premier travel destination to attract more tourists.
- **Easy navigation:** Ensure users can navigate the website effortlessly.
- **SEO optimisation:** Optimise website for SEO to rank high in search engines and attract more visitors.
- **Responsive and accessible design:** Make the website responsive and accessible to users on different devices and with different abilities.

### Visitor Goals

As a first-time visitor, I want:

- To learn about the top attractions in Valencia so that I can plan my sightseeing itinerary.
- The website is easy to navigate and visually appealing.
- The website loads quickly on my mobile so I can access it on the go.

As a returning visitor, I want:

- To discover the best local cuisine so I can experience authentic Valencian flavours.
- Easy access to practical tips and local insights.

As a frequent visitor, I want:

- To be able to share my own experiences and tips with others.
- To get personalised recommendations.

## Design

### Colour Palette

The colour palette reflects the Flag of the [Valencian Community](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHDltCMJWOwD_TXM0lBRmdTQM0RO9Ol97DFQ&s) and was created using [Coolors](https://coolors.co/?home).

The following colours were used in the project:

- **Background:** Off-white (#FAFAFA)
- **Text:** Black (#000) and White (#FFF)
- **Primary colour:** Blue (#1C5B97)
- **Secondary colour:** Yellow (#FFCB47)
- **Accent colour:** Red (#DC332E)

![Experience Valencia Colour Palette](/assets/design/ev_colour-palette.png)

### Typography

Google Fonts was used for the typography on the website:

- **Headings:** League Spartan (sans-serif)
- **Body text:** Quicksand (sans-serif)

### Imagery

The website consists of high-quality images showing Valencia's attractions, food and culture. The Experience Valencia logo and favicon were created using [Canva](https://www.canva.com/en_gb/).

<img src="/assets/images/experience_valencia_logo.png" width="200" height="200"> <img src="/assets/images/experience_valencia_icon.png" width="200" height="200">

## Wireframes

Wireframes were created using [Figma](www.figma.com) to plan the layout and structure of each page. They show how the site will look on three device sizes: mobile (width: 576px), tablet (width: 768px), and desktop (width: 1200px).

- Home Page Wireframe:

![Home Page Wireframe](/assets/design/wireframes/wireframe_home.png)

- Explore Valencia Page Wireframe:

![Explore Valencia Page Wireframe](/assets/design/wireframes/wireframe_explore.png)

- Contact Us Page Wireframe:

![Contact Us Page Wireframe]()

# Features

The website contains five pages, three main pages which can be accessed using the navigation menu, Home page (index.html), Explore Valencia page (explore.html) and Contact Us page (contact.html). The other two pages are a Thank You page (thank-you.html) and a 404 page (404.html). The Thank You page opens when a user submits the form on the Contact Us page while the 404 page opens when a user requests a page that does not exist.

## All Pages

The website features a responsive design ensuring it looks great on all devices, from mobile to desktop computers. The logo is consistently displayed across all pages to maintain brand identity.

## Main Pages

The main pages include the Home page, Explore Valencia page and Contact page. These pages:

- Display the Experience Valencia logo as a banner above the navigation menu.
- Include a responsive navigation menu for easy access to other parts of the site. On a mobile device, the navigation menu collapses so each navigation links sit under the other.
- Have a hero section that features an engaging image of L'Umbracle Terraza in the City of Arts and Sciences and introductory text.
- Include a footer containing the Experience Valencia favicon, text thanking users for visiting the website, social media icon links and copyright text.

## Home Page

- There is an introduction text that provides an overview of Valencia.
- An essential tips section offers useful information for visitors.

## Explore Valencia Page

- The hero section includes a captivating image and introductory text.
- Buttons are provided to quickly scroll to the attractions and cuisine sections.
- Detailed information on popular tourist attractions is presented to inform visitors.
- A showcase of local cuisine highlights the unique flavours of Valencia.

## Contact Us Page

- The hero section has an inviting image and introductory text.
- A contact form is provided for visitors to get in touch with the site administrators.

## 404 Page

- A message indicates that the page was not found.
- There is a button that allows users to go back to the Home page.
- Another button is available to direct users to the Contact Us page.

## Thank You Page

- A message thanking the visitor for their submission.
- A button is provided to take users back to the Home page.

## Future Features

- **Reviews:** Allow users to leave and read reviews of attractions and cuisine.
- **Separate pages for each attraction and cuisine:** Provide detailed information on individual attractions and dishes.
- **Events/festivals:** Include a section for upcoming events and festivals in Valencia.

# Accessibility

- **Semantic HTML:** used semantic HTML elements to improve the structure and readability for screen readers.
- **Clear and consistent Headings and Labels:** designed with clear and consistent headings and labels to aid in navigation.
- **Alt Text for Images:** included `alt` text for all images to describe the content for screen readers.
- **Hover States on Buttons:** implemented hover states on buttons to provide visual feedback for user interactions.
- **Aria-Labels on Links:** used `aria-label` attributes on links to provide additional context for screen readers.
- **Keyboard Navigation:** implemented keyboard navigation to ensure all interactive elements can be accessed and used without a mouse.
- **Text Contrast:** ensured text contrast meets accessibility standards using the [Accessible Colour Palette Builder](https://toolness.github.io/accessible-color-matrix/?n=Off-White&n=Black&n=White&n=Yellow&n=Blue&n=Red&v=FAFAFA&v=000000&v=FFFFFF&v=FFCB47&v=1C5B97&v=DC332E)

![Accessibile Colour Palette](/assets/design/ev_colour-accessibility.png)

# Technologies Used

## Languages

- **HTML5:** used for the structure of the website
- **CSS3:** used for styling the website

## Frameworks, Libraries & Programmes Used

- **Figma:** used to create wireframes
- **Canva:** used to create the logo and favicon
- **Visual Studio Code:** used as an Integrated Development Environment (IDE)
- **Google Fonts:** used to import fonts into `style.css` file to be used throughout the project
- **Font Awesome:** used to add social media icons in the footer
- **Flaticon:** used to download the icons for the Home page
- **Git:** used for version control
- **GitHub:** used to store the project code
- **GitHub Pages:** used to deploy the website

# Testing

# Deployment & Local Deployment

## Deployment

This website was deployed using GitHub pages. Here are the steps of deployment:

1. Log in to GitHub and locate the [Experience-Valencia](https://github.com/desireealexia/Experience-Valencia) repository
2. Under the repository name, click **Settings**
3. In the "Code and automation" section on the left sidebar, click **Pages**
4. Under "Build and deployment", in the "Source" section, select _Deploy from a branch_
5. Use the branch dropdown menu to select _main_, ensuring that the _root_ folder is also selected
6. Save these settings
7. Under the repository name, click **Code**
8. Wait a few minutes and refresh the page
9. A "Deployments" section will appear on the right sidebar. Click the GitHub Pages link, which will open the deployed site
10. Click on the link to be taken to the live site

## Local Deployment

1. Log in to GitHub and locate the [Experience-Valencia](https://github.com/desireealexia/Experience-Valencia) repository
2. Click the green button that says **Code** and click **Local**
3. To clone the repository using HTTPS, copy the provided link
4. In your terminal, type `git clone` and then paste the link
5. Press Enter, and your local clone will be created

# Credits

## Code

- Columns and Cards:
  - Adapted from my [Portfolio Project](https://gitshub.com/desireealexia/my-portfolio/blob/main/home.html). This was used in the essential tips section on the Home page, the attractions and cuisine sections on the Explore Valencia page, and the footer.
- 404 and Thank You Pages:
  - Adpated code from [GeeksforGeeks](https://www.geeksforgeeks.org/create-a-404-page-using-html-and-css) and [Akash Rajendra's Codepen](https://codepen.io/akashrajendra/pen/JKKRvQ). Maintained consistency throughout the website by using the same structure and styling for both pages.
- Three Columns Styling:
  - Adapted from [W3Schools](https://www.w3schools.com/howto/howto_css_three_columns.asp).
- Cards Styling:
  - Adapted from [W3Schools](https://www.w3schools.com/howto/howto_css_cards.asp).
- Responsive Top Navigation:
  - Adapted from [W3Schools](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp).
- Copyright Symbol:
  - Used from [HubSpot](https://blog.hubspot.com/website/html-code-copyright#:~:text=To%20add%20a%20copyright%20symbol,it%20appear%20on%20a%20page).

## Research and Resources

- Responsive Design Breakpoints:
  - Used [DEV.to](https://dev.to/linusmwiti21/best-practises-for-building-responsive-design-in-2024-48c4) for common breakpoints in media queries.
- CSS Declaration Order:
  - Followed conventions from Kraken Technologies' [public-conventions repository](https://github.com/octoenergy/public-conventions/blob/main/conventions/css.md#declaration-order) on GitHub to ensure consistency in the `style.css` file.

## Media

### Images

- Hero Section:
  - Image of L'Umbracle Terraza (City of Arts and Sciences) sourced from [Pixabay](https://pixabay.com/).
- Explore Valencia Page:
  - Images sourced from:
    - [Pixabay](https://pixabay.com/): City of Arts and Sciences, The Silk Exchange, and Paella.
    - [24/7 Valencia](https://247valencia.com/): Valencia Cathedral
    - [Visit Valencia](https://www.visitvalencia.com/): Bioparc Valencia
    - [Wikipedia](https://en.wikipedia.org/wiki): Horchata
    - [Tripadvisor](https://www.tripadvisor.co.uk/): Churros and Chocolate
    - [Tom Press](https://www.tompress.co.uk/): Fideua

### Icons

- Social Media Icons:
  - From Font Awesome
- Home Page and Explore Valencia Page Icons:
  - From Flaticon

## Content

- Written Content:
  - Created by the developer with assistance from ChatGPT.
