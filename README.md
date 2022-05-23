# SOFING Responsive Website
![Website Mock Up](assets/images/mockup.png)
# Purpose
This project is a static website aimed at popularizing a new sporting activity called [Sofing](https://oks-erm.github.io/sofing/index.html), which involves you and your couch. It hopes to give a chance to belong to everyone who wants to be a part of a community and have a trendy hobby with little commitment. 

The core purposes of the website:
- introduce Sofing to a broad audience, spread **"philosofy"**.
- advertise related projects.
- create a community and help people connect via networking and local practices. 
- make visitors smile. 

The website is built using HTML and CSS as a Milestone Project#1 for the Code Institute's Full Stack Developer course.  

[The live website is available here](https://oks-erm.github.io/sofing/index.html)
___
# UX Design
## User stories
### As a **first time user**

- I want to easily understand the main purpose of the site and learn more about the topic.
- I want to be able to easily navigate and find content.
- I want to find ways to join the community and follow the movement on different social media.
- I want to be amused.

### As a **returning** and **frequent user**

- I want to find up-to-date information about events and meetings.
- I want to contact the organisation to request additional information.
- I want to join the community.
- I want to find information about training programms and self-development in the field.

### All users want to be able to access and comfortably view the website on mobile devices.
___
## Structure
### Home Page
- Introduces the movement and its "selling points" on the first screen.
- Provides a full overview of the topic: each page of the website is represented by it's own block.
- Catches user's attention and grips it with bold design and entertaining content.
    #### User Goal:
    >   - Understand the main purpose of the website.
    >   - Preview all the sections of the website.
    >   - Easily navigate and interact with the website.
    >   - Be amused.
    #### Website Goal:
    >   - Convey selling points and ethos.
    >   - Interest and engage the user.
    >   - Present the user a preview of all content sections.
    >   - Entertain the user.
    >   - Initiate future engagement, such as following on social media, joining the club, attending meetups etc.

### Philosofy Page
- Delivers the movement ethos and purpose in detail.
- Justifies and redeems doing nothing.
- Includes an easter egg for entertainment.
    #### User Goal:
    >   - Obtain information about the movement philosophy and ethos.
    >   - Be amused.
    #### Website Goal:
    >   - Convey the movement ethos.
    >   - Gain the users trust and sympathy.
    >   - Convince the user to join.
    >   - Entertain the user and make them smile.

### Meetups Page
- Provides up-to-date information about local meetups and practice sessions.
- Allows the user to contact local representatives.
    #### User Goal:
    >   - Find local meetups and regular practice sessions.
    >   - Check the schedule.
    >   - Be able to contact local representatives.
    #### Website Goal:
    >   - Provide information about local meetups and practice sessions.
    >   - Make it easy for the user to find one and contact local representatives.

### Signup Page
- Allows the user to join the club and get access to special programms and discounts.
    #### User Goal:
    >   - Join the club to access unique content and special offers.
    #### Website Goal:
    >   - Provide simple and accesible way to join the club.

### Meetups 
It was decided to take this section to the separate web-site (supposedly existing), because it is intended as a commercial project and contains plenty of information, which deserves a separate platform. However it was considered reasonable including it in the menu to inform about it, because the movement in new and users can not assume what features it includes. So it takes the user to the website of **Sofing Bootcamp** where the user may obtain all the relevant information about training. 
___
## Design

As Sofing is a completely new thing, the design shapes future brand recognition. The project's design springs from the ethos and values of Sofing: it is cheerful, bold and calm at the same time. It seems to be contrasting purposes, but it is a conscious intention to make it a little contradictory for comical effect, as a part of mocking existing cliches. It is somewhat a combination of a stereotypical small business, gym and furniture store website, as I see it. 


### Colour Scheme

A seemingly unconventional colour palette choice serves to embody a maverick component, mock existing cliches and challenge the rules (such as colour combination), just as Sofing does by turning doing nothing into a sport. 

#### **Shades of Whitesmoke** 
represent calm, air and light; two shades are used for volume effect.  
> #efefef (Background Colour, Text Colour on dark background).

> #f8f8f8 (Background Colour, Borders). 

#### **Shades of Charcoal Grey** 
are cool, neutral and balanced, just like Sofing wants its practitioners be. It is also known as a sophisicated colour. It is used to bring some contrast and draw attention to the ethos block on the home page. Several shades are used in order to avoid excessive contrast and heavy headings but provide accessibility. 
#333333 (Background Colour)
#515151 (Default Text Colour)
#6a6a6a (Headings, Borders)

#### **Coral** 
represents friendliness, cheerfullness and boldness. Moreover, it seems to be one of the typical sofa colours and it refers to the [famous couch from Friends tv series](https://www.texomashomepage.com/wp-content/uploads/sites/41/2019/09/friends-orange-couch.jpg).
#e06666 (Background Colour)

#### **Reef**  
represents trust and tranquility. In fact, [57% of men and 35% of women say blue is their favorite color](https://ceblog.s3.amazonaws.com/wp-content/uploads/2018/03/24214633/website-color-palettes-35.png), it’s the most common “favourite” color among the majority of the population. So, as I want to appeal to a broad audience, I decided to implement it.
#a6ceef (Background Colour, Buttons, Hover effects, Gradient for Logo and Headings)

### Typography

[Koulen](https://fonts.google.com/specimen/Koulen) was intended to be used for logo and headings, however it turned out to be too loud and intense if used for all headings, also it compromised legibility of many headings. Therefore, it was decided to limit its implementation and prefer softer and more neutral font for most of the headings throughout the website.

[Montserrat](https://fonts.google.com/specimen/Montserrat) was chosen for this purpose, as it is neutral and easy to read. 

[Lato](https://fonts.google.com/specimen/Lato) was chosen for body text, as it is light and easy to read.

### Images

The images in this project were sourced from [Unsplash](https://unsplash.com/), [Pexels](https://www.pexels.com/) and [iStock](https://www.istockphoto.com). They were specifically selected to correlate with the main website colour palette and increase aesthetic impact of the design.

### Visual Effects

#### Shadows
As the Home Page consists of multiple colourful overlaping blocks, it was important to add volume and make the content easier to percieve as the viewer's eye doesn't have to focus on understanding spatial relationships between elements, which might be quite daunting. However, to provide better performance on mobile devices it was implemented only for screens bigger than 992px.


#### Logo and Page Headings Gradient
Sofing movement does not have a logo at the moment, for this reason the text logo was established. Although the font provided the style, it still looked rather bland, flat and intensively dull in default text colours and illegible or inappropriate when executed in colours. Thus, it was decided to implement a gradient based on [Charcoal](#shades-of-charcoal-grey) and [Reef](#reef). The similar gradient was later applied to the Philosofy Page Heading and the Meetups Page Heading, but based of [Coral](#coral), in order maintain the website colour pallete.   

#### Blocks with CTA
Each block of the Home Page that we want users to interact with and that contains a Call To Action, such as join the club or follow the link, slightly grows (3%) whilst hovered over with a mouse. It provides stimulating visual effect and draws users attention even if hovered over by accident whilst scrolling. To provide better performance on mobile devices it was implemented only for screens bigger than 992px.   

#### Buttons
Each button offers a similar growing effect described above combined with change of its background colour: by default it is blue and it turns subtle green hovered over with a mouse. The green colour was opted for because it is known to be the [best colour for effective CTA buttons](https://www.wordstream.com/blog/ws/2015/02/20/call-to-action-buttons). To provide better performance on mobile devices it was implemented only for screens bigger than 992px.

#### Links
Due to the bold design and abundance of various content on the Home Page, it seemed to be necessary to draw additional attention to the links. When being hovered over with a mouse links change the text colour and the background colour (depending on the parent block design), the change is implemented with animated effect - "running" from left to right. To provide better performance on mobile devices it was implemented only for screens bigger than 992px.

#### Navbar Hover effect
The navbar includes a hover over effect to make experience more interactive and navigation more intuitive. When the user engages with the link or hovers over the link, its background colour changes to light blue to subtly highlight the item without compromosing legibility.
___
## Features
