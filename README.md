# TIA2 - Lina Ngo  

<br></br>

## Purpose

The purpose of this portfolio website is (use as a contact point…) that can be shared with potential employers. It contains content about myself as a growing web development professional, my education and career history, and my contact information. Displays my skills through the build of the website itself.

The purpose of this online portfolio is to provide information about myself as an aspiring web developer. It will contain information about my skills, interests, professional knowledge and a showcase of work. 

## Target Audience

- Potential Employers 
- IT recruitment

## Site Map

<img src="docs/sitemap.png" alt="site map">

<br></br>

## Functionality / Features

### Navigation

#### Navigation bar - Tablet and Desktop (mockup)
![navigation bar mockup](docs/navigation.png)

- The navigation bar remains static at the top of the page. It contains a logo to the left and the options to navigate to on the right.  
- The navigation bar remains consistent throughout all pages, except when in mobile display.

#### Navigation bar - Mobile (mockup)
![navigation bar for mobile display mockup](docs/navigation_mobile.png)

- When the user is in mobile display, the navigation bar will collapse into a hamburger icon (created in css) to the left and only the page title will remain to the right. By doing this, the navigation bar will look less condensed and cluttered, thereby keeping a clean and minimal aesthetics when in mobile display mode, consequently improving user experience. 


#### Menu page - Mobile (mockup)
<img src="docs/mobile_menu.png" alt="menu mobile mockup" width="200px">

#### Menu page - Mobile (screenshot)
<img src="docs/mobile_menu_ss.png" alt="menu mobile screenshot" width="200px">

- During mobile display mode, when the hamburger icon is clicked, the user will be directed to a new page clearly displaying all options to navigate to. 
- The **X** button at the top left of the page (created using css) will return user to the previous page.


<br></br>


### Home Page

The home page consist of 2 sections:

1. Main element - contains the introduction
2. The footer - contains job title and social media links.

All sections in the home page are combined to take up 100% of viewport height. Since the main purpose of this page is to display the introduction and not much else, it takes up majority of the screen space. The footer contains job titles and social media links represented as its respective logos. Intentionally there is no vertical scrolling to maintain simplicity of the page.

#### Home - Social Media Links
<img src="docs/home_social.png" alt="home social media links" width="150px">


#### Home - Mobile (mockup)

<img src="docs/home_mobile.png" alt="home mobile mockup" width="200px">

#### Home - Mobile (screenshot)

<img src="docs/home_mobile_ss.png" alt="home mobile screenshot" width="200px">

<br></br>

#### Home - Tablet (mockup)

<img src="docs/home_tablet.png" alt="home page tablet display mockup" width="300px">

- Initially during the mockup stages of the website in tablet display, the nagivation bar was designed to remain collapsed as a hamburger icon as it does during mobile display. However, when implementing the design, the top of the page looked too empty, throwing off the visual balance of all the elements. So, the tablet display has the same navigation features as the desktop display.

#### Home - Tablet (screenshot)

<img src="docs/home_tablet_ss.png" alt="home tablet screenshot" width="300px">

<br></br>

#### Home page - Desktop (mockup)

<img src="docs/home_desktop.png" alt="home page desktop display mockup" width="600px">

#### Home - Desktop (screenshot)

<img src="docs/home_desktop_ss.png" alt="home desktop screenshot" width="600px">


<br></br>


### About Page

The about page consist of 2 sections:

1. About me 
2. Hobbies and interests that has 2 sub sections. 

Originally, the design of the website was to use inverted colours for every second section in order to create a clear distinction between content. However, when it was developed and interacted with the black blockouts became too visually heavy on the page and was not aesthetically pleasing. This led to a decision to maintain a minimal consistency seen in the home page, using only borders to separate sections. 

#### About - Mobile (mockup)

<img src="docs/about_mobile.png" alt="about mobile mockup" width="200px">

#### About - Mobile (screenshot)

<img src="docs/about_mobile_ss.png" alt="about mobile screenshot" width="200px">

#### About - Tablet (mockup)

<img src="docs/about_tablet.png" alt="about tablet mockup" width="300px">

- When the screen size increased, the sections split into two columns to fit more content horizontally on the page. This was done to avoid excessive vertical scrolling.
- The images were made to maintain the same width as the column, creating uniformity throughout the page.

#### About - Tablet (screenshot)

<img src="docs/about_tablet_ss.png" alt="about tablet screenshot" width="300px">

#### About - Desktop (mockup)

<img src="docs/about_desktop.png" alt="about page desktop display mockup" width="400px">

- Originally, the desktop display was designed using a four column structure. This was done to use the horizontal space given. By doing this, the **about text** was justified to the left of the page, while splitting into two columns. This is also done to the hobbies and interests sections to allow the image to take up more space (3 columns), emphasising its visual appeal. However, when the design was implemented, it was found that when the screen size decreased, even a little, the columns would become drastically slim thus creating an ugly display of text. This was mitgated by keeping the layout consistent with the tablet display. 

#### About - Desktop (screenshot)

<img src="docs/about_desktop_ss.png" alt="about desktop screenshot" width="800px">


<br></br>

### Work Page

After redesigning the **about page** that uses borders rather than colour blocks, the other pages were revisited and redesigned in that manner for consistency.

The **work page** consists of 3 sections:

- Information about self, contains a resume link (This section was added later in the design process)
- Education history
- Work history


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

- To remove excessive vertical scrolling, the desktop display was designed to use the horizontal space. This was achieved using flexbox. 

<img src="docs/work_desktop_1.png" alt="about page mobile display mockup" width="800px">

#### Work - Desktop (mockup 2)

<img src="docs/work_desktop_2.png" alt="about page mobile display mockup" width="800px">

#### Work - Desktop (screenshot)

<img src="docs/work_desktop_ss.png" alt="work mobile screenshot" width="800px">


<br></br>

### Blog Index

The **blog index** consists of 2 sections:

- The header
- The main content being the list of blog posts

The blog index uses css grids for the main content in order to create columns depending on screen size. This reduces excessive empty space and allows users to easily view all listed blog posts.

- Mobile - 1 column
- Tablet - 2 columns
- Desktop - 3 columns

#### Blog Index - Mobile (mockup)

<img src="docs/blogIndex_mobile.png" alt="blog mobile mockup" width="200px">

#### Blog Index - Mobile (screenshot)

<img src="docs/blogIndex_mobile_ss.png" alt="blog mobile mockup" width="200px">

#### Blog Index - Tablet (mockup)

<img src="docs/blogIndex_tablet.png" alt="blog tablet mockup" width="400px">

#### Blog Index - Tablet (screenshot)

<img src="docs/blogIndex_tablet_ss.png" alt="blog tablet mockup" width="400px">

#### Blog Index - Desktop (mockup)

<img src="docs/blogIndex_desktop.png" alt="blog desktop mockup" width="800px">

#### Blog Index - Desktop (screenshot)

<img src="docs/blogIndex_desktop_ss.png" alt="blog desktop mockup" width="800px">


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
- After revising, it was decided to maintain the uniformity of one column for each display, as the break points for two columns would be unknown and inconsistent to each new post.

#### Blog Post - Tablet (screenshot)

<img src="docs/blogPost_tablet_ss.png" alt="blog tablet mockup" width="400px">

#### Blog Post - Desktop (mockup)

<img src="docs/blogPost_desktop.png" alt="blog desktop mockup" width="800px">

- As the screen widens, the body of content will reach a maximum width to avoid the stretching of content. Ensuring that the page is easy to read. 

#### Blog Post - Desktop (screenshot)

<img src="docs/blogPost_desktop_ss.png" alt="blog post desktop screenshot" width="800px">

<br></br>

## Fonts

- Fonts chosen during the mockup stage allowed for creative freedom in Figma, which led to the use of interesting fonts. However, after researching the accesibiility of web, I decided to choose a font that was accessible to all in order to maintain consistency to all users.

## Tech Stack

- HTML
- CSS