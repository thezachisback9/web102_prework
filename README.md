# WEB102 Prework - Crowdfunding Stats

Submitted by: Zachary Amanuel

Crowdfunding Stats is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 6 hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] List anything else that you can get done to improve the app functionality!
* [X] When pressing the most funded game button or runner up button, that game card will light up

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://imgur.com/a/IMFA6YB.gif' title='Video Walkthrough' width='50' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with LiceCap
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.

I had some difficulties when I mixed up games_json with gamesContainer because they both seemed similar to me but once I realized the difference, it wasn't really a problem for any future steps

Another problem was when I wanted the default order of the games to be the same as when you click the "show all games"  button, but the button would sort them in order of money raised so I had to call the sort method on a copy of games_json so that games_json wouldnt be altered

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
