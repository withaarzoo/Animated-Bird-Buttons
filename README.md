# Animated Bird Buttons
This repository contains HTML and CSS code for creating animated bird buttons. There are three types of buttons available, each with different color combinations.

## Usage
To use these buttons, simply copy the HTML and CSS code from this repository into your project. Then, modify the code as necessary to match your project requirements.

There are three different types of buttons available, each with its own CSS class:

* `button--piyo`
* `button--hoo`
* `button--pen`

To use a particular type of button, add the corresponding class to your HTML code.

```HTML
        <a href="#" class="button button--piyo">
            <!-- button content goes here -->
        </a>
```

## Customization
These buttons can be customized by modifying the CSS variables in the code. Each button type has its own set of variables, which can be changed to alter the appearance of the button.

```CSS 
.button--piyo {
    --main_color: #f4cf47;
    --sub_color1: #f4e19c;
    --sub_color2: #ff8108;
    --base_color: #000;
    --border_radius1: 60px 60px 40px 40px / 48px 48px 30px 30px;
    --border_radius2: 70px 70px 40px 40px / 48px 48px 30px 30px;
    --border_radius3: 40px 40px 40px 40px / 48px 48px 30px 30px;
}
```

To customize the button colors, simply change the values of the CSS variables to the desired colors.

## Preview
<img width="960" alt="Screenshot_20230226_185159" src="https://user-images.githubusercontent.com/59678435/221413311-4cfad695-3d41-4768-90b4-9316829ab956.png">

