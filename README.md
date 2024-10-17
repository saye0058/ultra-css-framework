# custom-css-framework

# how to make changes to our framework

```bash
sass --watch src/ultra-css-template.scss dist/ultra-css-framework.css
```


# UltraCSS: Your Web Friendly Framework

Hey there! Welcome to UltraCSS, the CSS framework that makes your websites look awesome without the headache.

## What's UltraCSS?

UltrCSS is like a toolbox for your website. It's packed with ready-to-use styles that make your site look great and work smoothly on any device.

## How to Get Started

1. Downlad the 'ultra-css-framework.css' file from our 'dist' folder.
2. Pop it into your project folder.
3. Link it in your HTML like this:
   ```html
   <link rel="stylesheet" href="path/ultra-css-framework.css">
   ```

That's it! You're ready to roll.

## How to Use UltraCSS

Here are some cool things you can do:

1. Make a primary button:
   ```html
   <button class="btn btn-primary">Click me!</button>
   ```

2. Add some margin:
   ```html
   <div class="m-1">I have some breathing room</div>
   ```

3. Change text color:
   ```html
   <p class="text-primary">I'm in the primary color!</p>
   ```

4. Create a responsive grid:
   ```html
   <div class="row">
     <div class="col-6">Half width</div>
     <div class="col-6">Other half</div>
   </div>
   ```

## Make It Your Own

Want to change things up? No problem!

1. Find the '_variables.scss' file in the 'src' folder.
2. Change the values to match your style. For example:
   ```scss
   $primary-color: #FF5733;  // Change primary color to a cool orange
   $font-size-base: 18px;    // Make base font size a bit larger
   ```
3. Save your changes and recompile the SCSS to CSS.

And yay! You've got a customized version of UltraCSS.

Need more help? Just send us a message in the issues section. Happy styling!
