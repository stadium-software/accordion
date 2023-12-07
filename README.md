# Accordion



## Sample applications
This repo contains one Stadium 6.7 application
[Accordion.sapz](Stadium6/Accordion.sapz?raw=true)

## Version 
1.0 initial

# Setup

## Application Setup
1. Check the *Enable Style Sheet* checkbox in the application properties

## Global Script Setup
1. Create a Global Script called "EditableRow"
2. Add five input parameters to the Global Script
   1. DataGridClass
   2. EditColumnHeader
   3. FormFields
   4. IdentityColumnHeader
   5. IdentityValue
   6. CallbackScript
3. Drag a *JavaScript* action into the script
4. Add the Javascript below into the JavaScript code property (ignore the validation error message "Invalid script was detected")
```javascript

```

# Styling
Various elements in this module can be styled using the two CSS files in this repo

## Applying the CSS

**Stadium 6.6 or higher**
1. Create a folder called "CSS" inside of your Embedded Files in your application
2. Drag the two CSS files from this repo [*accordion-variables.css*](accordion-variables.css) and [*accordion.css*](accordion.css) into that folder
3. Paste the link tags below into the *head* property of your application
```html
<link rel="stylesheet" href="{EmbeddedFiles}/CSS/accordion.css">
<link rel="stylesheet" href="{EmbeddedFiles}/CSS/accordion-variables.css">
``` 

![](images/ApplicationHeadProp.png)

**Versions lower than 6.6**
1. Copy the CSS from the two css files into the Stylesheet in your application

## Customising CSS
1. Open the CSS file called [*accordion-variables.css*](accordion-variables.css) from this repo
2. Adjust the variables in the *:root* element as you see fit
3. Overwrite the file in the CSS folder of your application with the customised file

## CSS Upgrading
To upgrade the CSS in this module, follow the [steps outlined in this repo](https://github.com/stadium-software/samples-upgrading)
