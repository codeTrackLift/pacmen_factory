<head>
    <link rel="stylesheet" href="./style.css">
    <style>
        html {
            background: transparent !important;
            text-shadow: 2px 2px black;
        }
        h2 {
            color: cornflowerblue;
        }
        .listNoBullets {
            list-style-type: none;
            margin-left: -1.5rem;
        }
        li>span {
            color: cadetblue;
            font-size: 1.25rem;
        }
        a:link,
        a:visited {
            color: lime;
            text-decoration: none;
        }
    </style>
</head>

# <img src='https://www.codebypete.com/pics/about/mitxPro_logoStacked.jpg' alt='MIT xPro logo' style='width:2.5rem;margin-bottom:-0.5rem;'> Portfolio Project: Pac-Men Factory

## About
We were supplied with starter code and PacMan images. Assignment objectives:
<ul>
    <li>Make a PacMan at a random position on the screen</li>
    <li>Move PacMan along the x and y-axis at random velocities</li>
    <li>PacMan should use alternating images to simulate 'chomping' movement</li>
    <li>PacMan should change direction of movement upon hitting a screen edge</li>
    <li>PacMan images should change based on direction of horizontal movement</li>
    <li>Project should operate with buttons</li>
</ul>

Just for fun, I added some additional features:
<ul>
    <li>'Aquarium Theme' with animated background</li>
    <li>Matching 'Aqua-Suit' with random colors</li>
    <li>PacMan spawns within 'Aquarium' boundaries</li>
    <li>Random spawn sizes</li>
    <li>Button to make PacMan move, now toggles movement</li>
    <li>Button to ZAP! PacMan, which removes the first PacMan element from the array and DOM</li>
    <li>Project is responsive, but reload may be necessary if screen size changes while moving</li>
</ul>

## How to Run
This project has three buttons, and they operate as follows: 
<ul>
    <li class='listNoBullets'><span>Add PacMan</span> - Creates a PacMan within aquarium boundaries with random: position, velocity, size, and 'Aqua-Suit' color.</li>
    <li class='listNoBullets'><span>Start Stop</span> - Starts PacMen moving on their designated trajectory; or Stops them in place.</li>
    <li class='listNoBullets'><span>ZAP! PacMan</span> - Gives the first PacMan in the array a quick, but fatal ZAP! They are removed from the array, as well as the DOM.</li>
</ul>

## Future Roadmap
I may incorporate what I learned about handling an array of DOM elements into my <a href='https://codetracklift.github.io/pacman' target='_blank'>Pac-Man Mini-Game</a> project.

## MIT License

Copyright (c) 2022 Pete Chu

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
