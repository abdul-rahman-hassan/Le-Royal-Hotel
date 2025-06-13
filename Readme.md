# Le Royal Hotel Website

Welcome to the Le Royal Hotel website project! This is a responsive and interactive website designed to showcase a luxury hotel, providing visitors with information about rooms, services, location, and a seamless Browse experience.

## Table of Contents

- [Le Royal Hotel Website](#le-royal-hotel-website)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Setup and Installation](#setup-and-installation)
  - [Usage](#usage)
  - [Folder Structure (Anticipated)](#folder-structure-anticipated)

## Project Overview

Le Royal Hotel is a modern website for a luxury hotel chain. It aims to provide an elegant and user-friendly interface for potential guests to explore the hotel's offerings. The website is built with a focus on responsiveness, ensuring a great experience across various devices, from desktops to mobile phones.

## Features

This project incorporates several interactive and design elements to enhance the user experience:

* **Responsive Design:** Adapts seamlessly to different screen sizes, providing an optimal viewing experience on mobile, tablet, and desktop devices.
* **Dynamic Image Sliders:**
    * A prominent hero image slider on the homepage (using Slick Carousel).
    * Image sliders for rooms and guest reviews.
* **Interactive Navigation Bar:**
    * A clean, intuitive navigation menu for easy Browse.
    * A responsive "hamburger" menu icon on mobile devices that toggles open/close with a smooth 'X' transformation animation.
* **Animated Call-to-Action (CTA) Section:** A compelling section to encourage users to explore rooms, featuring a subtle fade-in and slide-up animation that triggers each time it enters the viewport.
* **Service Showcase:** Highlights key services offered by the hotel (e.g., Free Parking, Free Spa).
* **Room Details Section:** Dedicated page (`rooms.html`) to display various room types.
* **Date Picker:** Integrated for easy date selection (e.g., for booking forms).
* **Spinner Buttons:** Interactive quantity selector buttons (e.g., for number of guests or rooms).
* **Google Maps Integration:** Displays the hotel's location with an embedded Google Map.
* **Scroll-to-Top Button:** A convenient button to quickly navigate back to the top of the page.
* **Modern CSS Effects:** Utilizes CSS transitions and transforms for smooth animations and interactive elements.

## Technologies Used

The project leverages a combination of standard web technologies and popular JavaScript libraries:

* **HTML5:** For the core structure and content of the web pages.
* **CSS3:** For styling, layout, responsiveness, and animations.
    * `main.css` (custom styles)
    * `slick.css` (Slick Carousel styles)
    * `pickmeup.css` (Datepicker styles)
    * `handle-counter.min.css` (Spinner button styles)
* **JavaScript:** For interactive elements and dynamic behavior.
    * **jQuery:** A fast, small, and feature-rich JavaScript library.
    * **Slick Carousel:** A powerful and responsive carousel/slider library.
    * **pickmeup.js:** A minimalist date picker library.
    * **jQuery ScrollUp:** A plugin to add a scroll-to-top button.
    * **Google Maps API:** For embedding interactive maps.
* **Google Fonts:** `Lora` (for headings) and `Open Sans` (for body text) for elegant typography.

## Setup and Installation

To get a local copy up and running, follow these simple steps:

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository_url>
    ```
    (If this is a local project without a Git repo, you can skip this step.)

2.  **Download/Copy the project files:**
    Ensure you have all the HTML, CSS, JavaScript, and image files in a structured folder.

3.  **Open in a Web Browser:**
    Navigate to the project directory and simply open `index.html` in your preferred web browser (e.g., Chrome, Firefox, Edge). All assets are linked relatively.

    *Note: Some features like Google Maps might require an internet connection to load properly.*

## Usage

* **Homepage (`index.html`):** Explore the main features, services, and the animated call-to-action section.
* **Rooms Page (`rooms.html`):** View details about different room types.
* **Navigation:** Use the top navigation bar to move between pages. On mobile, click the hamburger icon to reveal the navigation menu.
* **Interactive Elements:** Interact with the date picker, spinner buttons, and image sliders.
* **Scroll:** Scroll down to see the "Check Our Rooms" section animate into view, and click the scroll-to-top button to return to the top.

## Folder Structure (Anticipated)

A typical structure for this project would look like this:
```
project-root/
├── index.html
├── rooms.html
├── css/
│   ├── main.css
│   ├── slick.css
│   ├── slick-theme.css
│   ├── pickmeup.css
│   └── handle-counter.min.css
├── dist/
│   ├── demo.js
│   ├── demo2.js
│   ├── handle-counter.js
│   ├── pickmeup.min.js
│   ├── jquery.scrollUp.min.js
│   └── slick.js
└── images 