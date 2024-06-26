# TIA2 - Lina Ngo  

## GitHub repo

[Lina Ngo Portfolio 2024](https://github.com/nlina-0/portfolio-2024)

<br></br>

## Purpose

The purpose of this online portfolio is to provide information about myself as an aspiring web developer. It will contain content about my education and career history, skills and interests, as well as professional knowledge and a showcase of work. The website itself will also act as a demonstration of my skills as a web developer.

## Target Audience

The target audience for this online portfolio would be potential employers that include:

- Senior developers
- Chief technical officers
- IT recruitment agencies

## Site Map

- A navigation bar sits at the top of the website which allows users to navigate to the home, about, work and blog index page. This navigation bar remains consistent across all pages when in tablet and desktop display mode.
- When in mobile display, the navigation is displayed as an icon that links to a separate menu page that displays options to navigate to the home, about, work and blog index page. 
- The blog index has a list of links that leads to separate blog posts. 
- The work page has a resume button linking to a PDF file that opens in a new tab. 

<img src="docs/sitemap_2.png" alt="site map">

<br></br>

## Functionality / Features

### Navigation

The navigation bar allows users to move to the four main sections of the website which include the home, about, work and blog index page.

#### Navigation bar - Tablet and Desktop (mockup)

![navigation bar mockup](docs/navigation.png)

- The navigation bar remains static at the top of the page. It contains a logo to the left and the options to navigate to different pages on the right.  
- The navigation bar remains consistent throughout all pages, except when in mobile display.

#### Navigation bar - Mobile (mockup)

![navigation bar for mobile display mockup](docs/navigation_mobile.png)

- When the user is in mobile display, the navigation bar will collapse into a hamburger icon (created in css) that is situated to the left. Once clicked, the user will be directed to a separate page that clearly displays the four main pages to navigate to. Only the page title remains to the right. By doing this, the navigation bar will look less condensed and cluttered during mobile display, thereby keeping a clean and minimal aesthetics, consequently improving user experience.

- When the user enters the menu page the **X** button at the top left of the page (created using css) will return user to the previous page.


#### Menu page - Mobile (mockup)

<img src="docs/mobile_menu.png" alt="menu mobile mockup" width="200px">

#### Menu page - Mobile (screenshot)

<img src="docs/mobile_menu_ss.png" alt="menu mobile screenshot" width="200px">


<br></br>


### Home Page

The purpose of the home page is to introduce the web developer in a professional and clean manner. All sections in the home page are combined to take up 100% of viewport height as a way to remove vertical scrolling and keep the focus on the introduction. The footer contains the job titles and social media links. The social media links open in a new tab to LinkedIn and Ghithub profiles. 

The home page consist of 2 sections:

1. Main element - contains the introduction
2. The footer - contains job title and social media links.

#### Home - Social Media Links

<img src="docs/home_social.png" alt="home social media links" width="150px">


#### Home - Mobile (mockup)

<img src="docs/home_mobile.png" alt="home mobile mockup" width="200px">

#### Home - Mobile (screenshot)

<img src="docs/home_mobile_ss.png" alt="home mobile screenshot" width="200px">


#### Home - Tablet (mockup)

<img src="docs/home_tablet.png" alt="home tablet mockup" width="300px">

- Initially the home tablet display was to have the same navigation design as the mobile display. However, when implementing the design, the size of the tablet display created a lot of empty space, throwing off the visual balance of the elements. So, the navigation feature used for the desktop display is also used for the tablet display.

#### Home - Tablet (screenshot)

<img src="docs/home_tablet_ss.png" alt="home tablet screenshot" width="300px">

#### Home page - Desktop (mockup)

<img src="docs/home_desktop.png" alt="home desktop mockup" width="600px">

#### Home - Desktop (screenshot)

<img src="docs/home_desktop_ss.png" alt="home desktop screenshot" width="600px">


<br></br>


### About Page

The purpose of the about page is to provide information about myself as an aspiring web developer and also my hobbies and interests. This is separated into two sections:

1. About me 
2. Hobbies and interests that has 2 sub sections. 

Originally, the design of the website was to use inverted colours for every second section in order to create a clear distinction between content. However, when it was being developed the black blockouts became too visually jarring on the page and was not aesthetically pleasing. This led to a decision to maintain a minimal aesthetic seen in the home page, using only borders to separate sections. 

The hobbies & interests sections use the same component, it icludes an image with a caption, a title, sub-title and paragraph. 

### Section Line breaks

<img src="docs/section_line_break.png" alt="section line break" width="600px">

- The section line break was created using CSS code is used throughout the website to separate different sections. It expands across the entire width of the page.
- Originally it was only used for the home page, but was implemented to all other pages to maintain consistency. It became an ideal solution to separating content. 

#### About - Mobile (mockup)

<img src="docs/about_mobile.png" alt="about mobile mockup" width="200px">

#### About - Mobile (screenshot)

<img src="docs/about_mobile_ss.png" alt="about mobile screenshot" width="200px">

#### About - Tablet (mockup)

<img src="docs/about_tablet.png" alt="about tablet mockup" width="300px">

- When the screen size increased, the sections split into two columns to fit more content horizontally on the page. This was done to avoid excessive vertical scrolling.

- The images were made to maintain the same width as the column, creating uniformity throughout the page.

#### About - Tablet (screenshot)

<img src="docs/about_tablet_ss.png" alt="about tablet screenshot" width="400px">

#### About - Desktop (mockup)

<img src="docs/about_desktop.png" alt="about page desktop display mockup" width="400px">

- Originally, the desktop display was designed using a four column grid. This was done to use the extra horizontal space in desktop display. By doing this, the **about text** was justified to the left of the page, while splitting into two columns. The same thing applied to the hobbies and interests sections which allowed the images to take up more space (3 columns), emphasising its visual importance. However, when the design was implemented, it was found that when the screen size decreased, even a little, the columns would become drastically slim thus creating an ugly display of text. This was mitgated by keeping the layout consistent with the tablet display. 

#### About - Desktop (screenshot)

<img src="docs/about_desktop_ss.png" alt="about desktop screenshot" width="800px">


<br></br>

### Work Page

The purpose of the work page is to display education and work history, as well as having a link to a resume. This page is displayed in a list view. It consists of 3 sections:

- Information about self
- Education history
- Work history

After redesigning the **about page** that uses borders rather than colour blocks, the other pages were revisited and redesigned to maintain consistency.

#### Resume button

<img src="docs/work_resume_button.png" alt="work resume button" width="400px">

<img src="docs/work_resume_button_hover.png" alt="work resume button hover" width="400px">

- The resume link is created as a button.
- It resizes when the width of the section changes. 
- Colours invert when mouse is hovered over. 


#### Work - Mobile (mockup 1)

<img src="docs/work_mobile_1.png" alt="work mobile mockup 1" width="200px">

#### Work - Mobile (mockup 2)

<img src="docs/work_mobile_2.png" alt="work mobile mockup 2" width="200px">

- The first section containing the name and current job titles were added later in the design process to link the page back to who the website is about. 

#### Work - Mobile (screenshot)

<img src="docs/work_mobile_ss.png" alt="work mobile screenshot" width="200px">

- The resume link was moved to the top section for easier accesibility. 

#### Work - Tablet (mockup 1)

<img src="docs/work_tablet_1.png" alt="work tablet mockup 1" width="300px">

#### Work - Tablet (mockup 2)

<img src="docs/work_tablet_2.png" alt="work tablet mockup 2" width="300px">

#### Work - Tablet (screenshot)

<img src="docs/work_tablet_ss.png" alt="work tablet screenshot" width="400px">

#### Work - Desktop (mockup 1)

- To remove excessive vertical scrolling, the desktop display was designed to use the horizontal space provided with the size of the screen. This was achieved using flexbox. 

<img src="docs/work_desktop_1.png" alt="about page mobile display mockup" width="800px">

#### Work - Desktop (mockup 2)

<img src="docs/work_desktop_2.png" alt="about page mobile display mockup" width="800px">

#### Work - Desktop (screenshot)

<img src="docs/work_desktop_ss.png" alt="work mobile screenshot" width="800px">


<br></br>

### Blog Index

The purpose of the **blog index** is to display a list of blog posts that display the publish date and title. It consists of 2 sections:

- The header
- The list of blog posts

The blog index uses css grids for the list of blog posts in order to create columns depending on screen size. This reduces excessive empty space and allows users to easily view all listed blog posts.

- Mobile - 1 column
- Tablet - 2 columns
- Desktop - 3 columns

#### Blog Index - Mobile (mockup)

<img src="docs/blogIndex_mobile.png" alt="blog mobile mockup" width="200px">

#### Blog Index - Mobile (screenshot)

<img src="docs/blogIndex_mobile_ss.png" alt="blog mobile screenshot" width="200px">

#### Blog Index - Tablet (mockup)

<img src="docs/blogIndex_tablet.png" alt="blog tablet mockup" width="400px">

#### Blog Index - Tablet (screenshot)

<img src="docs/blogIndex_tablet_ss.png" alt="blog tablet screenshot" width="400px">

#### Blog Index - Desktop (mockup)

<img src="docs/blogIndex_desktop.png" alt="blog desktop mockup" width="800px">

#### Blog Index - Desktop (screenshot)

<img src="docs/blogIndex_desktop_ss.png" alt="blog desktop screenshot" width="800px">


<br></br>

### Blog Post

All five blog posts maintain the same code but images and text can be rearranged in html according to content.

The **blog posts** consists of 2 sections:

- The header
- The main content that contains the body of text and images. 

The image blocks will stretch to fill the width of the text in order to maintain a sense of flow throughout the page. Images are given a maximum height as to not over fill vertical space.

#### Blog Post - Mobile (mockup)

<img src="docs/blogPost_mobile.png" alt="blog mobile mockup" width="200px">

#### Blog Post - Mobile (screenshot)

<img src="docs/blogPost_mobile_ss.png" alt="blog mobile mockup" width="200px">

#### Blog Post - Tablet (mockup)

<img src="docs/blogPost_tablet.png" alt="blog tablet mockup" width="300px">

- The original design of this page was inspired by newspaper layouts. The idea was to restrict the amount of words to each line for easier legibility.
- After revising, it was decided to maintain the uniformity of one column for each display, as the break points for two columns would be unknown and inconsistent to each new post added.

#### Blog Post - Tablet (screenshot)

<img src="docs/blogPost_tablet_ss.png" alt="blog tablet mockup" width="400px">

#### Blog Post - Desktop (mockup)

<img src="docs/blogPost_desktop.png" alt="blog desktop mockup" width="800px">

- As the screen widens, the body of content will reach a maximum width to avoid the stretching of content. Ensuring that the page is easy to read. 

#### Blog Post - Desktop (screenshot)

<img src="docs/blogPost_desktop_ss.png" alt="blog post desktop screenshot" width="800px">

<br></br>

## Fonts

- Fonts chosen during the mockup stage allowed for creative freedom in Figma, which led to the use of interesting fonts. However, after researching the accesibiility for web, I decided to choose a font that was accessible to all in order to maintain consistency to all users.

## Tech Stack

- HTML
- CSS