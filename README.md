<p align="center">
<img width="100" height="100" alt="logo quila" src="https://dibodev-files.s3.eu-west-3.amazonaws.com/flags-logo.png">
</p>

<h2 align="center">Scss Flag Generator</h2>

<p align="center">
 Quila is a Chat / messaging application made with react js
</p>


![Language](https://img.shields.io/badge/language-json-green.svg?style=flat)
![Language](https://img.shields.io/badge/language-scss-ce679a.svg?style=flat)

<img alt="hero" src="https://dibodev-files.s3.eu-west-3.amazonaws.com/scss-country-generator.png">



> Source code for the demo page can be found on the [quila repo](https://github.com/Leoglme/flag-scss-spritesheet)

### Contents

- [Documentation](#documentation)

## Install

   ```sh
    $ git clone https://github.com/Leoglme/flag-scss-spritesheet
   ```

1. Download the sprite sheet **flags.png** and place it in your directory.
2. At the beginning of the **scss file** replace the value of the **$spriteSheetUrl** variable with the **path** of the **image**
    ```scss
        $spriteSheetUrl: '/path/to/images/flags.png';
   ```  
4. Compile SCSS file and linking **CSS to HTML**.

   ```html
       <html lang="en">
          <head>
            <title>Example</title>
            <link href="/examples/countries.css" rel="stylesheet">
          </head>
       </html>
   ```
5. Example of use

   ```html
       <html lang="en">
          <body>
            <span class="flag flag-fr" data-v-2f2b3a59=""></span>
            <span class="flag flag-it" data-v-2f2b3a59=""></span>
            <span class="flag flag-de" data-v-2f2b3a59=""></span>
            <span class="flag flag-en-uk" data-v-2f2b3a59=""></span>
            <span class="flag flag-en" data-v-2f2b3a59=""></span>
          </body>
       </html>
   ```

## License

Copyright (c) 2021 [Dibodev](https://github.com/leoglme)
