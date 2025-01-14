# WEB102 Prework - *Sea Monster Site*

Submitted by: **Amanda Stone**

**Sea Monster Site** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **3.5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x]  The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding.
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.
<br>

The following **optional** features are implemented:

* [x] **Enhanced Button Interactivity:** Added hover states to the filter buttons to visually emphasize their interactivity, improving user experience by providing clear feedback on actions.
* [x] **Custom Design Styling:** Refined the overall page design for a more professional appearance. This includes:
* * [x] Importing a custom font for headers to establish a unique brand identity.
* * [x] Designing a logo and color scheme that complements the theme and branding of the page.
* [x] **Search Functionality:**
* * [x] Implemented a collapsible search bar to improve usability and maintain a clean layout.
* * [x] Users can click a search icon (styled to match the filter buttons) to expand the search bar, where they can type and search for specific game titles.



## Video Walkthrough

Here's a walkthrough of some updates to the website.

Updated Stats and Top Games
<img src='https://i.imgur.com/It8LSHs.gif'>

Improved Visual and Hierarchical Design
<img src='https://i.imgur.com/Yyk0s4b.gif' title='Improved Design' width='' alt='Improved Page Design' />

Working Header Menu Navigation
<img src='https://i.imgur.com/hxt5DRi.gif' title='Menu Design' width='' alt='Menu Design' />

Filterable Games Section<br>
<img src='https://i.imgur.com/UTpQGfL.gif' />

Search Game Titles Functionality - CSS Slide Down Effect<br>
<img src='https://i.imgur.com/FtKynne.gif' />

Added Footer
<img src='https://i.imgur.com/RqUSY3o.gif' />

GIFs created with [Kap](https://getkap.co/) for macOS

## Notes

This JavaScript code dynamically imports JSON data into the website to display relevant game information. The data is loaded using standard JavaScript methods and manipulated with functions like `reduce` to calculate specific values, such as the number of unfunded games. The script then updates the DOM by appending these calculated results to designated HTML elements, ensuring that the website's content remains accurate and up-to-date based on the provided JSON data. This approach allows for easy integration and real-time updates of game statistics on the webpage.

Throughout the development of this project, there were a few key challenges that required careful consideration and problem-solving:

### Search Icon and Input Positioning
One of the challenges was deciding on the best placement for the search icon and input field to ensure a user-friendly interface. Initially, it was tricky to position the elements in a way that felt intuitive while maintaining a clean design. After experimenting with various layouts, I decided to place the search icon inside a button next to the other filters, and the input field was placed within a collapsible container that only appeared when the button was clicked. This approach balanced both functionality and aesthetic appeal.

### Implementing the CSS Drop-Down Feature
Another challenge was implementing the CSS-based drop-down effect for the search bar. The goal was to create a smooth, animated transition when the search bar appeared and disappeared. Initially, getting the animation to work correctly was difficult, especially with ensuring the search container's height adjusted dynamically based on content. After some trial and error with max-height and overflow properties, I was able to achieve a clean, smooth drop-down effect that was both functional and visually appealing.

These challenges, while tricky at times, provided an opportunity to learn more about CSS animations and the importance of user-centered design.


## License

    Copyright 2025 Amanda Stone

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
