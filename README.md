# WEB102 Prework - *Game Site*

Submitted by: **Amanda Stone**

**Game Site** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **3.5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] Disabled shadow hover for stats- bad ux design to make hoverable effect if not clickable (assumed games hover leads to donation link)
* [ ] Added hover states for filter buttons- emphasize clickability and let user know where they are
* [ ] Stylized the page for stronger design, including importing a custom font for header


## Video Walkthrough

Here's a walkthrough of implemented features:

Button Hover States
<img src='https://i.imgur.com/T9YDKjv.gif' title='Buttons Walkthrough' width='' alt='Buttons Walkthrough' />

Game Card Hovers
<img src='https://i.imgur.com/6XxvtGa.gif' title='Card Walkthrough' width='' alt='Card Walkthrough' />


<!-- Replace this with whatever GIF tool you used! -->
GIF created with ...  
[Kap](https://getkap.co/) for macOS

## Notes

This JavaScript code dynamically imports JSON data into the website to display relevant game information. The data is loaded using standard JavaScript methods and manipulated with functions like `reduce` to calculate specific values, such as the number of unfunded games. The script then updates the DOM by appending these calculated results to designated HTML elements, ensuring that the website's content remains accurate and up-to-date based on the provided JSON data. This approach allows for easy integration and real-time updates of game statistics on the webpage.

## License

    Copyright 2024 AStone

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
