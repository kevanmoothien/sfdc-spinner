# Spinner

Sfdc-spinner is just a salesforce component using [tobiasahlin/SpinKit].

## Demo
A live demo of the different spinners available.
http://tobiasahlin.com/spinkit/

### Installation

To install the component, just copy the spinner.component found in the folder "src/components".

### Usage

##### Basic Usage
```html
<apex:page >
    <c:spinner />
</apex:page>
```
##### Javascript
```javascript
km_spin(true); // to show the spinner
km_spin(false); //to hide the spinner
````
##### Customizing the spinner
```html
<apex:page >
    <c:spinner spinner_name=""  spinner_color="" />
</apex:page>
```
Possible value for "spinner_name" are:
- rotating-plane
- wave
- wandering-cubes
- spinner-pulse
- double-bounce
- chasing-dots
- three-bounce
- circle
- cube-grid
- fading-circle
- folding-cube

Value for "spinner_color" is a hex or html color name

[tobiasahlin/SpinKit]: <https://github.com/tobiasahlin/SpinKit>



