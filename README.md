# 2-Player Growth Game

Small browser game I made with HTML/CSS/JS. Two players move around, collect orbs to grow, and when they collide the bigger player wins.

## Controls

* **Player 1 (Red):** `W A S D`
* **Player 2 (Green):** `↑ ↓ ← →`

## How it works

* Pick up the colored circles to increase score + size.
* Orbs respawn at a random position after being collected.
* If the two players touch, the larger one wins.
* A restart button appears after someone wins.

## Run it

Just open the HTML file in your browser.
(If you use VS Code, Live Server makes it easier.)

## Built with

* HTML
* CSS (animations)
* JavaScript (DOM + collision detection)
* Bootstrap (CDN)

## TODO (maybe later)

* Keep players inside the game area
* Split the code into separate HTML/CSS/JS files
* More items / power-ups

________________________________________________________________________________________________________________

# Kiddy Website (Bootstrap)

A multi-page website layout I built to practice Bootstrap + CSS. It has a home page, sections for packages/pricing, and a testimonial carousel.

## Pages

Home / About / Packages / Gallery / Pricing / Contact

## What’s inside

* Bootstrap layout + components
* Custom CSS for styling/hover effects
* Carousel for testimonials
* Navigation bar + hero section

## Run it

Open `home.html` (or your main page) in a browser.

## Important note about images

If your image links look like:
`/Users/emilimperator/...`
they won’t work once you upload to GitHub.

Fix: put images in an `images/` folder inside the project and update the paths.

## Built with

* HTML
* CSS
* Bootstrap 5 (CDN + bundle)
