
# Mars Colony One
## **Site Overview**

This site is a demonstration of my front end design skills in pure HTML and CSS.

The site is designed for a fictional company called StarSeed industries, who are a market leader in space exploration.
The company is starting recruitment for civilian colonists to be part of StarSeeds Mars colony "Mars Colony One"
The objective of the site is to capture the attention of possible colonists, provide details about the mission, and collect contact information from visitors that wish to apply.
​
![Intro Page](./docs/images/intro-page-amir-trans.webp)
![Main Page](./docs/images/Main-page-amir-trans.webp)


#### [The live website is here](https://will-griffiths-ireland.github.io/Mars-Colony-One/)​

## Table of contents:
1. [**Site Overview**](#site-overview)
1. [**Planning stage**](#planning-stage)
    * [***Planning Overview***](#planning-overview)
    * [***Target Audiences***](#target-audiences)
    * [***User Stories***](#user-stories)
    * [***Site Aims***](#site-aims)
    * [***Wireframes***](#wireframes)
    * [***Color Scheme***](#color-scheme)
    * [***Typography***](#typography)
1. [**Site-Wide Features**](#site-wide-features)
    * [***Site Logo***](#site-logo)
    * [***Navigation Bar***](#navigation-bar)
    * [***Page Background***](#page-background)
    * [***Footer***](#footer)
    * [***Navigation Flow***](#navigation-flow)
1. [**Individual Page Content features**](#individual-page-content-features)
    * [***Intro Page Content***](#intro-page-content)
    * [***Mission Page Content***](#mission-page-content)
    * [***Mars Page Content***](#mars-page-content)
    * [***Ship Page Content***](#ship-page-content)
    * [***Trip Page Content***](#trip-page-content)
    * [***FAQ Page Content***](#faq-page-content)
    * [***Sign-up Page Content***](#sign-up-page-content)
1. [**Future-Enhancements**](#future-enhancements)
1. [**Testing Phase**](#testing-phase)
1. [**Deployment**](#deployment)
1. [**Technology**](#technology)
1. [**Credits**](#credits)
    * [**Honorable mentions**](#honorable-mentions)
    * [**General reference**](#general-reference)
    * [**Content**](#content)
    * [**Media**](#media)

---


## **Planning Stage**

### **Planning Overview:**

I gave a lot of thought to producing a site that was an example of something a large company/corp would produce.

* The site aims to be a sleek promotion of their project/mission
* My focus is to captivate the user and keep them wanting more
* My design is bold and minimalist

### **Target Audiences:**

* Users interested in space travel 
* Users interested in new work opportunities
* Users interested in a new life challenge
* Users not sure what to do with their life (adolescents)
* Users previously involved in work within challanging environments
* Users formally involved in space industry

### **User Stories:**

* As a user, I want to quickly understand the purpose of the site and its core message
* As a user, I want to navigate through content easily
* As a user, I want to learn more about what opportunities there are for me on Mars
* As a user, I want to learn about the technology the company uses
* As a user, I want to easily submit my details so I can be contacted
* As a user, I want to easily view the site with whatever device and browser I am using 

### **Site Aims:**

* Core aim is to generate as much interest as possible in the mission and for users to provide their contact details for recruitment followup
* To help the user understand the mission to colonize mars
* To provide key details about what they can do on mars
* To provide key details about the living conditions
* To get contact information from the user for future recruitment

### **Wireframes:**

Wireframes were built in Balsamiq as a foundation and there has been an organic evolution of the design during construction of the site and testing across the different devices I had available.

Original wireframes in PDF [here](./docs/mco-wireframe.pdf)
​
### **Color Scheme:**

My aims for the color scheme​.

* High contrast
* Complimentary colors
* Dark/space theme

I leveraged https://coolors.co/ during the process.

I took inspiration for the core color from Mars itself and built out from that.
I used a colour picker on the image of mars to pull out the hex of a color I like to start with.

![Core Mars Color](./docs/images/orange.png)

In contrast to the rich orange of mars I have used pure black to match with the void of space.

![Space Black Color](./docs/images/black.png)

I've also used a light blue which I see as introducing a link to planets atmospheres and a connection to life, water, and hope. I feel the use brings balance to the overall feel of the site. Used in a graduated form across the header to keep that atmospheeric theme across all pages.

![Dark Blue Color](./docs/images/light-blue.png)

Used sparingly and with opacity, I have a plum colour. This was to add a little varation where it felt right.

![Plum Color](./docs/images/plum.png)

Finally the core font color is pure white. This is not only for contract but also represents the pure white light of the sun.

![White Color](./docs/images/white.png)


### **Typography**
​
I was aiming for a sci-fi look and feel without going overboard and alianting users.

After much searching I chose https://fonts.google.com/specimen/Exo+2

I feel it strikes the right balance between readability and a modern futuristic look.

It's used with a bold weight of 800, which is unusual but it was a conscious design choice to have a chunky industry look across the entire site.

Sans-serif is used as a fallback.


## **Site-Wide Features**
​
### **Site Logo**

![MCO Logo](./docs/images/mco-logo.png)

* The page logo embraces a simple sci-fi astectic.
* Using Exo 2 font to look modern/futurist while still highly readable.
* The white text has a black drop shadow to add some depth.
* Globe Icon is used in place of the 'O' in One
* Simple 3d rotate on globe to be memorable but not anoyingly frequent
* Size scales down for lower res screens

### **Navigation Bar**

Across both mobile and desktop the header has at graduation from blue to transparent. This is to signify the transition from the surface of a planet to the atmosphere and allow a blend from the header into the body.

#### *Desktop*

The desktop navigation is done via simple hyperlinks across the top right of the page.

* Exo 2 Font
* Font size increase for higher width screens
* Small drop shadow to add depth
* Double dash indicates active page

![Navigation bar](./docs/images/nav1.png)

When a user mouses over the links they change orange and have a white glow

![Navigation bar2](./docs/images/nav2.png)

#### *Mobile/Tablet*

On lower resolution screens the menu is hidden and replaced with a "burger" menu. I had played with other types of icons but felt they led to a confusing experience for the user.

![Navigation mobile](./docs/images/nav-mobile1.png)

Once clicked there is dropdown list

![Navigation expand](./docs/images/nav-mobil21.png)


### **Page Background**

At first I used pure black as the background for all pages but it didn't have the right feel/depth

I tried different solid colors and images but they were either too flat or far too busy for my astetic.

Finally I created a small image and and added random pixels, this image is repeated across x/y for a starfield background.

![Star Maps](./docs/images/stars.png)

### **Footer**

The absence of a footer is a deliberate design choice as I felt this type of site would not benefit from one

### **Navigation Flow**

The journey for the user should be a linear trip through each page on the site bar the FAQ.

The text within the page has links that lead the user towards the next page in the flow towards the sign-up.

An example from the mars page.

![nav flow example](./docs/images/nav-flow-ex.JPG)

---
​
## **Individual Page Content features**

### **Intro Page Content**

I used index.html as an intro page to capture the users attention and generate a "wow" factor about Mars

* Animations fade in and out thought provoking text
* Animation simulate approaching Mars from afar
* Core site logo is introduced on a grand scale
* Link to skip to mission page for return visitors

#### *Desktop @1080p Example*

![MCO intro page](./docs/images/intro-page.webp)

#### *Mobile Example*

![MCO intro page mobile](./docs/images/intro-page-mobile.webp)

### **Mission Page Content**

The mission page gets right to the point and explains to the user what this site is about and how they can play a part

* Animations bring content in from off screen left/right
* Colonist image was edited with circular transparency to allow a drop shadow filter. This is the blend the imagery of plant mars and its outer halo with the concept of exploration,
* The StarSeed logo relates to the company that is running this mission and brings the credibility of a well known brand. Again circular framing of the logo continues the theme
* The founder Stranto Marlini is a household name so his image and quote bring further credibility to the importance of the mission
* The founders image is also cut circular to allow a transparent background, a drop shadow filter is applied to the image to give it more impact.
* At lower mobile resolutions the layout is changed and font sizes are reduced

#### *Desktop @1080p Example*

![Mission page desktop](./docs/images/main-page.webp)

#### *Mobile Example*

![Mission page desktop](./docs/images/main-page-mobile.webp)


### **Mars Page Content**

* This is the info about the mars page

#### *Desktop @1080p Example*

![Mission page desktop](./docs/images/mars-page.webp)

#### *Mobile Example*

![Mission page desktop](./docs/images/mars-page-mobile.webp)

### **Ship Page Content**

* This is the info about the ship page

#### *Desktop @1080p Example*

![Mission page desktop](./docs/images/ship-page.webp)

#### *Mobile Example*

![Mission page desktop](./docs/images/ship-page-mobile.webp)

### **Trip Page Content**

* This is the info about the trip page

#### *Desktop @1080p Example*

![Mission page desktop](./docs/images/trip-page.webp)

#### *Mobile Example*

![Mission page desktop](./docs/images/trip-page-mobile.webp)

### **FAQ Page Content**

* This is the info about the faq page

#### *Desktop @1080p Example*

![Mission page desktop](./docs/images/faq-page.webp)

#### *Mobile Example*

![Mission page desktop](./docs/images/faq-page-mobile.webp)

### **Sign-up Page Content**

* This is the info about the sign-up page

#### *Desktop @1080p Example*

![Mission page desktop](./docs/images/sign-up-page.webp)

#### *Mobile Example*

![Mission page desktop](./docs/images/sign-up-page-mobile.webp)

---
​
## **Future-Enhancements**
​
* user account creation
* user application tracking
* interactive 3d model of Jagger I Ship

​
​
## **Testing Phase**

Testing was performed throughout development of the site and led to design evolution as I gained deeper understanding of what was possible.

* Images displaying correctly
* Text displaying correctly
* Animations displaying correctly

### **Validators**

#### *HTML Validator*

| File | Result | Comments |
| ----------- | ----------- | ---- |
| index.html | Pass | N\A|
| Paragraph | Text |

#### *CSS Validator*

| File | Result | Comments |
| ----------- | ----------- | ---- |
| index.html | Pass | N\A |
| Paragraph | Text | N\A |

​
* Responsiveness - How do you test this, dev tools? checking on multiple devices?
​
* Functionality - Each feature needs to be tested before something is complete, talk about the process, click each link check each image, does form validation work, if your using javascript or anything else, does it always behave as the user expects
​
* Validators - Here include images from w3c html validator and css jigsaw (jshint for js and pep8 for python) and the results that came from it
​
​
## **Bugs**
​
We always have bugs in development, a few bullet points here to talk about bugs you found and how you fixed them, in later projects this will be more detailed
​
* Issue - When on mobile the user had horizontal scroll with items overflowing
* Cause - The images had absolute positioning and caused them to go off screen
* Resolution - Changed the width of the image to stay within the confines of the screen.
​
***
## **Deployment**
I deployed the page on GitHub pages via the following procedure: -
​
1. From the project's [repository](pageurl), go to the **Settings** tab.
2. From the left-hand menu, select the **Pages** tab.
3. Under the **Source** section, select the **Main** branch from the drop-down menu and click **Save**.
4. A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.
​
You  can find the live site via the following URL - [live webpage](https://yoururlhere)
***
​
## **Technology**
​
These are the technoligies used for this project.

​
- HTML5
- CSS3
- Javascript (Only for fontawesome)
- Powerpoint (Initial Logo Creation) 
- Paint.net (Image editing/sizing/compression)

My approach was to start from a blank canvas really try to build out my vision without using a lot of content​

----

## **Credits**
### **Honorable mentions**
​
Thanks to my mentor Richard
​
### **Content:**
​
I used code from https://alvarotrigo.com/blog/hamburger-menu-css/ example 1
This was used as a starting point for the advanced animations but I made extensive changes to make the menu fit my sites style
  
### **Media:**
​
Links to the locations of images if you've used them from an online source!
