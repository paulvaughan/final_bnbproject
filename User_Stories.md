# Final Project Overview: Code MD201-4

## Bites'N Bethesda 

### User Stories

Maslow's Hierachy of Needs lists **food** as one of the basic physiological needs. When the call of nature beckons and hunger strikes, no one wants to be faced with the undaunting task of figuring out _where to eat_. Working through the logistics of satisfying one's hunger is difficult. As modern day _Hunter Gatherers_ this can be further complicated when you have a various palettes to satisfy; i.e. a **family**.

This is where Bites'N Bethesda comes in... let's be honest; sometimes deciding where to eat can be hard. We won't promise to eliminate all the uncertainties, but our solutions are designed to make your _"Hunt"_ a little bit simplier.

**Bites'n Bethesda** provides nutritious and delectable dining options in the Bethesda area; we allow our users to search our database by providing key _"cuisine options"_ (i.e. Italian, Asian, Spanish, etc) to fine-tune your dining experience. To top it off, we will even throw in **recommended parking location(s)** for your selected dining location... because, yeah we thought of that too!!

## Problem Domain

To create this _"dine-out selection"_ application we enlisted a team of talented development experts. The project stakeholders are as follows:

- `Market researchers`: researches were engaged to conduct market analysis on restaurants within the Bethesda area. Their findings would then highlight the ***twelve (12) marquee restaurants** in Bethesda; the names of which would be submitted to our development team. _N.B. The analysis is re-initiated every month to provide an updated database for the application_.

- `Videographers/Photographers`: a team of _visionaires_ visited all five locations to shoot eye-catching images and video of the restaurants.

- `UX/UI Designers`: a team of designers will _wireframe_ the layout and user experience components of the project.

- `Developers`: a development team was tasked with the challenge of bringing **Bites'N Bethesda** to life. They are the _brains_ behind the `technical requirements` and innovations of the application.

~~Once the `marketing team` submits the results from their analysis the `videographers` will go out and capture the _"best views"_ of each restaurant.~~

`UX/UI Designers` will generate wireframmed sketches and details which will guide the development team's formulation of `technical requirements` for the project (_see attached sketches and notes in the project assets folder_).

The application will consist of three (3) HTML pages with accompanying CSS and JavaScript code to style and drive the interactivity of the application. A master repository `final_bnbproject` will be created with accompanying branches: `html-content`; `css-content`; `js-content`. _User Stories_ will be held on the master branch.

The two primary HTML pages are as follows: `index.html` `select.html` and `results.html`. Each HTML page will be styled by its respective CSS page: `main.css` `select.css`. The entire project will be driven by the JavaScript code created in a `select.js` file.

The application will launch on a main page `index.html`. It includes an `about` section and a *tag-line*. A button titled `continue` will be included which sends the user to the selection page `select.html`.

The selection page will utilize a `div` with radial selections or `field sets` of cuisine options.~~It will then have a second `div` of *features*.~~ The users selections will be held in local storage by collecting each click with an `eventListener`. The even listener initiates a pull from an array of restaurants to display *three (3) logo* `images` (_based on the user's cuisine selection_) on the `select.html` page. A user selection of any one of the three image options will `display a result` of the restaurant image on the `result.html` page.

An embedded`video banner` will also be displayed on the `select.html` using *HTML code*` to give the user an area overview of the Bethesda area. The Video will be _load and run automatically_ *on loop*. Finally, the application will reference the *nearest parking location(s)* ~~by `name` and `address`~~. A `link tag` snippet from _Google maps_ will be embedded for visual illustration - activated by a `hover feature` (_Should be coded using HTML_).

## Project Timeline

- **Tuessday, April 2nd**: Initial HTML + CSS Demo to be submited for review and assessment

- **Wednesda, April 3rd**: JavaScript included to project and demo conducted for review and assessment

- **Thursday, April 4th**: Beta test for project

- **Saturday, April 6th**: Full demo for final project with presentation elements.

N.B. To `reload` or return the application to home a `Home` or `Return to Home` button will be included. **Additionally, the `asset` folder will also house all restaurant images/video and google map snippets relevant to the project.**

* Update - April 4, 2019: A navbar was included to each page and a `contact.html` page will be added to the project. The team is exploring the possibility of including a clever _easter egg_; details will be provided in future updates to the _User Stories_ file.