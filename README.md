# floativ
floativ is a responsive floating scroll-box at the bottom of the screen of your site that contains text, among other things, which can be displayed while browsing a web page. This floating scroll-box disappears when the user reaches an element with a specific id.

**See a working demo [here](http://gbratsos.github.io/floativ).**

## Installation
1. Download and install [NodeJS](https://nodejs.org/)
2. Clone or Download project straight from [GitHub](https://github.com/GBratsos/floativ).
3. Extract the zip file and start working.

## Directions
* cd into the directory and run `npm install` in order to install all the project dependencies.
* Open index.html to see and start working with this project.

## NPM Package
You can find and install floativ from npm [here](https://www.npmjs.com/package/floativ).

## Usage
Put this `$("#floativ").floativ();` inside __script tags__ at the bottom of your HTML file.
You can also specify parameters, such as:
```html
<div class="floativ" id="floativ">
    <div class="floativ-container">
        <div class="floativ-head">
            <span>
                <i class="fa fa-plus-circle floativ-expand" aria-hidden="true" aria-label="Expand"></i>
            </span>
            <span>
                <i class="fa fa-minus-circle floativ-collapse" aria-hidden="true" aria-label="Collapse"></i>
            </span>
        </div>
        <div class="floativ-wrapper">
            <div class="floativ-body">
                ... YOUR CONTENT HERE ...
            </div>
        </div>
    </div>
</div>
```

## Dependencies
* [jQuery](https://github.com/jquery/jquery)
* [mCustomScrollbar](https://github.com/malihu/malihu-custom-scrollbar-plugin)
* [FontAwesome](https://github.com/FortAwesome/Font-Awesome)

## Library compatibility
This library works for IE8+, Mozilla Firefox 4+, Google Chrome 11+, Opera 10+, Safari 4+.

## Collaborators
* [George Bratsos](https://github.com/gbratsos)
* [Panagiotis Papadatis](https://github.com/hennett)
* [Vivi Zygoura]()

## Contributors
* [George Raptis](https://github.com/georapbox)

## Projects using floativ
* [Sprix](http://sprix.com/Home.aspx)
* [OXAYDO](http://www.oxaydo.com/)

## License
[GPL-3.0](LICENSE)
