---
layout: page

title: SGTrains
subtitle: Web Design and Development

image: /assets/images/sgtrains/sgtrains-thumb.jpg
color: 111

year: 2015-04

sidebar: 
    - title: Type
      content: |-
        Web Design and Dev.
        Brand Identity
    - title: Date
      content: |- 
        Launched 2015
    - title: Technology Stack
      content: |-
        Bootstrap + PHP (site)
        Python (data processing)
    - title: URL
      content: |-
        <a href="https://sgtrains.com/">SGTrains.com</a>

description: SGTrains.com is a website that documents and shares information about Singapore's rail network. 
---

SGTrains is a community of railway enthusiasts formed in 2011. Apart from being active in the local transport scene through participation and feedback, SGTrains also maintains a website documenting and sharing information about Singapore's rail network. 

I designed and developed [SGTrains' new website](https://sgtrains.com/), and helped craft the group's new brand identity. 

The new website, apart from being more comprehensive and visually appealing, also reduced technical complexity compared to the previous forum-based website. The new brand identity also gave the group a more professional image.

![Screenshot of the SGTrains homepage](/assets/images/sgtrains/sgtrains-hero.png)


## Tech

The previous SGTrains website was written as webpages that extend from the forum software. This meant the website was dependent on the forum, and any forum downtime would bring down the website too. 

The new website is a static website, with the exception of the homepage which uses PHP. The website styles build upon a modified, lightweight build of Bootstrap. 

The choice to go with a static HTML website and Bootstrap was made to simplify the website, and to make it easier to maintain with basic tools and with less dependencies.

A later addition to the website was the Travel Guide section, which included [First & Last Train Timings](https://www.sgtrains.com/guide-traintiming.html). As an open API for train network information was not available from LTA, a tool was written in Python to scrape and transform data from LTA's MyTransport website into a JSON file used by the page.

For collaboration with others on the project, Git was used as the source control system with a central repository set up. 

## Design

![Snippet of the style guide](/assets/images/sgtrains/sgtrains-design.png)

To complement the launch of a new website, a new logo was designed. 

A style guide was also created to aid the team in creating content with a consistent style, covering elements from colours, logo guidelines and font types, to the  editorial tone to use in writing. 

## Gallery

### Home page
![Screenshot of the SGTrains homepage](/assets/images/sgtrains/sgtrains-home.png)

-----

### Content pages
![Screenshot of the rolling stock page](/assets/images/sgtrains/sgtrains-rollingstock.png)
![Screenshot of the last train page](/assets/images/sgtrains/sgtrains-lasttrain.png)
