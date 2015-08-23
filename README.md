# IranAddressJS
IranAddressJS is a jQuery plugin that provides selection for city and province fields (of Iran) in a form. You can simply add two select input in your html page. one for selecting province and the other for selecting the city from the selected province.

## Demo
You can access to live Demo from here : [Demo](http://jsfiddle.net/hosseinRashno/8z8Lo5oL/10/)

## Requirements

IranAddressJS works with jQuery 1.3+ . If you have no Idea what is about, Just add the following line to header of your code:

```html
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
```

## Installation

Add a reference to Iran-Address-JS.js :

  You can add IranAddressJS to your page from jsdeliver CDN, Just add following line to header of you page:
```html
<script src="//cdn.jsdelivr.net/jquery.iranaddressjs/0.5.0/jquery.iranaddressjs.js"></script>
```  
  Or you can download it from this project and add reference like below:

```html
<script src="Iran-Address-JS.js"></script>
```

## How to use?

In your html code you must have two select input. one for province and one for city. Province inputs must have ```"province"``` class and city inputs must have ```"city"``` class.
  
Each serie of city and province selects must be inside a unique ```"div"``` tag.
  
Example:
  
  ```html
        <div>
            <!-- استان  -->
            <select class="province">
            </select>
            <!-- شهر -->
            <select class="city">
            </select>
        </div>
```

You can use how many of these series you want, just keep this in mind that use each serie in a diffirent ```"div"``` tag. That's all you need to do. Good lock.

## Copyright and license

Licensed under the GNU GENERAL PUBLIC LICENSE Version 2, June 1991 licensing.
