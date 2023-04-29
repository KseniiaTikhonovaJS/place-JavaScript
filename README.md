# study project "PLACE-JAVASCRIPT"

by Kseniia Tikhonova

*place-javascript is an interactive webpage. Responsive web design. (italic)*
*Place-javascript features include: adding, deleting (only created by you) and liking photos, opening a popup with a picture, editing a profile (avatar and personal information). (italic)*

## Installation

1. To use "place-javascript", you will need to install Node.js on your computer. Once you have installed Node.js, you can clone the repository to your local machine using the following command:

```
git clone https://github.com/KseniiaTikhonovaJS/place-javascript.git
```
2. After cloning the repository, navigate to the project directory and install the necessary dependencies using the following command:

```
npm install
```

## Usage

To run "place-javascript" on your local machine, navigate to the project directory and use the following command:

```
npm run build
```
This will start the development server and open "place-javascript" in your default browser. You can then interact with the page by adding, deleting, and liking photos, as well as editing your profile.
If the page does not open automatically in the browser, you can open it manually: /dist/index.html

## Description

### Webpack set up:
* installed webpack , webpack-cli and webpack-dev-server ;
* configured build and dev builds;
* scripts are created in package.json ;
* configured minification and transpilation with JS babel. Webpack bundles all JavaScript into one file and
* automatically adds a script tag to HTML with a link to it;

### Styles included in a separate file.

### Complied with BEM methodology and file structure.

### Functionality:
* 6 cards are created using JS;
* the form for adding a card is laid out, opens, adds a card;
* click on the like button works;
* deleting the card is implemented correctly;
* modal windows close at any screen resolution;
* a modal window with a picture opens, the image does not lose its proportions;
* Implemented smooth opening and closing of the modal window with CSS styles;
* for all input fields in forms, live validation is enabled;
* the form submit button is inactive if at least one of the fields does not pass validation;
* the modal window is closed by clicking anywhere outside this window and by pressing Esc .

### Data checking:
* the data of any input field is checked by one unified function;
* HTML5 attributes and the ValidityState JS property are used to validate the data in the field;
* a separate function is responsible for the state of the submit button;
* the enableValidation function is responsible for enabling form validation;

### The code is object-oriented.
* Used ES6 classes.
* Each class is described in a separate JS file and imported into index.js .
* Each class performs strictly one task. Everything related to the solution of this problem is in
class.
* Weak coupling is used to describe the interaction between classes, that is, within classes
instances of other classes are not directly instantiated.

### The code is not repeated. If a line is needed in several places, it is moved to a separate function.

### Interface accessibility
* All links and clickable elements have a hover state of :hover .
* Content images have an alt with a correct description corresponding to the language of the page.

