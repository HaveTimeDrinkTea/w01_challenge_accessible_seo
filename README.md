# w01_challenge_accessible_seo


## Description

This project is part of the Frontend Dev Bootcamp course challenge for week 1. It simulates a on-the-job ticket where a starter code is provided and my role as a developer is to make changes, correct errors or otherwise improve on the code to satisfy client's requirements. 

Through this project, I have an opportunity to demonstrate my understanding of HTML/CSS, the git workflow, github, terminal commands, VSCode, editing a markdown document and debuging using browser developer mode. 

I have also read up and get a (very) brief understanding of web accessiblity and SEO.

The main user story for this project is to refactor an exisiting site to make it more accessible and optimised for search engines.


### Methodology

* Inspect the various elements in the starter index.html on mainly safari browser.
* Identify areas to be improved or corrected and divide the issues into three main areas. See [Features](#features). 
* Make the changes and follow a git workflow as if I am working in a team of developers.


### Further Issues Requiring Attention

* It is recommended that the webpage should be made to be responsive as the next step. E.g. The header and slider area will not work if a user reduces the browser window. (I am looking forward to learning more about responsive design later in the course!)
* Will need to connect the request a demo form to a CRM application like mailchimp to collect leads.
* Will need to update all social media account icons with the correct URL.
* Will need to relink the main nav in header to the relevant pages for this website.
* Implement cookie consent and check compliance with GDPR.


## User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

[Deployment link](https://havetimedrinktea.github.io/w01_challenge_accessible_seo/)



## Acceptance Criteria

The website must meet accessibility standards by having the following:

* Semantic HTML elements can be found throughout the source code
* HTML elements follow a logical structure independent of styling and positioning
* Image and icon elements contain accessible ''alt` attributes
* Heading attributes fall in sequential order
* Title elements contain a concise, descriptive title


## Table of Contents (Optional)

* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Features](#features)
* [Testing](#testing)


## Installation

N.A.


## Usage 

A screen shot of the mock up and of the submitted webpage:

### Mock up provided by the client:

![alt text](assets/images/01-html-css-git-challenge-demo.png)

### Webpage submitted for review:

![alt text](assets/images/01-html-css-git-challenge-final.png)



## Credits

Used Font Awesome v4.7. [Link to Font Awesome](https://fontawesome.com)


## License

MIT License



## Features

* Semantic HTML
	* divided the body into header, main and footer.
	* converted all div into the relevant section within main.
	* regroup the relevant tags and classes into readable sections
	* heading attributes fall in sequential order
	* clean up the stylesheet by grouping repeating styles for different sections into one.
	
	
* Accessibilty 
	* all img elements have alt and title attributes
	* all img elements are accompanied by figcaption where necessary
	* added address tag in footer for contact information.
	* added aria-hidden= true for purely decorative elements.
	
* SEO
	* Added title
	* Added SEO keywords in the meta description tag instead of meta keywords tag
	* Reduce image sizes for faster loading without losing too much resolution
	
* Extra features
	* the header logo and navigation bar is now fixed to the top of the webpage and floats on top as a user scrolls down. This helps in navigation.
	
	
## Testing

The new webpage has been assessed against 

* Download speed 
	* tested by [test engine Pingdom.com](https://tools.pingdom.com/#6141af4982400000) 
	* Overall grade B. 
	* Total page size 600kb with a latency of 325ms.
	
* Accessibility
	* tested by [test engine Wave.webaim.org](https://wave.webaim.org) 
	* identified a few issues such as colour contrast between the white font and the blue background and the three images in the benefits section. To check with client regarding choice of colour or change the images for better contrast.
	* Tool tips for the header navigation is not descriptive enough. Changes have been made.
	* Form email input does not have a label and the form submit button colour contrast is not good.  Both have been corrected.
	* Text content on top of the top slider image has contrast issue. 

---

## Badges

![bathmath](https://img.shields.io/badge/Memo%20League-Golden-yellow)
![bathmath](https://img.shields.io/badge/SoloLearn%20League-Mars-red)
