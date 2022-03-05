![DigitalZ logo](/images/blue-logo.png)

Welcome!


The idea is to develop a digital solution for SME or non-profits where they can, without any investment into development or licenses, equip themselves with crowdfunding, crowdsourcing and e-commerce tools to run and grow their business. It has been my experience from the last 7 years that such solution would be very relevant and in demand (one of the potential cleints would be "DKIRU", starting field operation in Mexico). This thought is supported by 2021-2027 EU initiative #AStrongerigitalEurope where the aim is to dramatically increase the use of digital tools and data usage for the growth of Small & Medium Enterprises (SMEs).

Typically, a start-up, a small company or an association have a great idea, publish a facebook or business website and even connect to the e-commerce solution. However, the engagement from the business partners remain very low, because many tools are passive and you have to use several of them (WhatsApp, Facebook, Kickstarter, Shopify and a few more) to achieve the business impact. DigitaZ should be a unifying platform with several unique features that satisfy most of the business engagement needs in one platform.

The initial sceleton of the platform (static several pages, made with html & css) can be found [here](https://zilvaro.github.io/my-digitalz/index.html).

![website preview](/readme-assets/#)


This project is the HTML and CSS based functional core structure of the solution working as a teaser and allowing interested people to request more information. By adding more elements in JavaScript and Python later it will become more functional, easier-to-use and beneficial for different users.

##Table of Contents

#1. User Experience (UX) & Interface (UI)

##1.1 General Rules
[Go to the top](#table-of-contents)

While designing the functionality & user experience there were applied some guiding principles:
*5 seconds rule: it has to be clear what the page is for in 5s (is it just for information, to perform an activity or leave a comment) and where to go next
*2 clicks rule: user shall get to any core functionality (perform a task, order product, check the points balance, leave a message, etc.) in max-2 click from any page within the application.
*call-to-action: at every page or stage there is an invitation "to do something" (contact, order, donate, perform a task or follow to instruction section).
*consistency: every page has the same color scheme, similar structure, button design and follows a common practice of app design (OK buttons - green, main page - home, settings - in profile, etc.)


##1.2 Personas

Alex : 25 years old sustainable business owner. He is promoting reusability and sharing, so he provides refillable containers for food products, supplies quality produce from different parts of the world and organizes communal workshops about circular economy. In addition to his facebook and Instagram accounts he would like to have an application where he can check the display and stock level in partner stores, activate on-line store and run continuous crowdfunding activities to support the business.  

Marion : 42 years old grocery store manager that is looking how to improve the sales and make extra revenues for additional services. She is busy at the store, so is not in favour with visiting salesmen and merchandizers so for her the contractual tasks and communication with suppliers would be ideal if they happen at her own schedule. And posibility to have a personalized discount on supplies or extra revenue from performing some merchandising services would be very appreciated.



##1.3 Color Scheme

The idea of the solution is that ad-banners, product pictures or story-images will be very colorful, therefore core color scheme was chosen to be calm, cool, but not cold.

With the help of https://www.color-hex.com/color-palettes/ DigitalZ has the color combination that guaranties sufficient contrast, readibility and enough supporting colors to be engaging:

![color scheme](./readme-assets/digitalz-color-scheme.jpg)



##1.4 Structure (Flow)

###Wireframes
To visualize the ideas and define the prioriies for the development BALSAMIQ tool was used. At first, larger (not full) site architecture was created, then prioritized what would be possible to do just with html and css, but already be a functional site and give a solid structure for the next upgrades.

It was designed with both personas' interests in mind:
*on the home-page: advertizing banners & money making actions - tasking & e-store (currently replaced by Contact link)
*within advertizing/info pages: promo or instructional materials with a link to action
*contact page: it is a form for giving the posibility to contact the solution operator and collecting info about the user (before proper log-in/sign-up form is developed)

Then, the concept pages for mobile and wide-screen were designed:

####Site-map
![Site Map](./readme-assets/DigitalZ-wire-flow-v2%20.jpg)

####Home-page
![Home Page-mobile](./readme-assets/Digi_home_v1%20mobile.png)
![Home Page-widescreen](./readme-assets/Digi_home_v1%20wide-screen.png)

####Info-blog
![Info-mobile](./readme-assets/Digi_info_articles_v1%20mobile.png)
![Info-widescreen](./readme-assets/Digi_info_articles%20v1%20wide-screen.png)

####Contact-registration
![Contact](./readme-assets/Digi_contact_v1%20wide-screen.png)



#2.Features

#2.1 Navigation

#2.2 Banners/Images

#2.3 Info/Blog

#2.4 Contact/Registration

#2.5 Features-to-come



















------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
