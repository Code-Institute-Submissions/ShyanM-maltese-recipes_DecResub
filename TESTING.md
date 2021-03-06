# Testing

[Main Readme.md](./README.md)

## User Stories Testing

- to be able view recipes:
    - The landing page shows all recipes created by all users.
- to be able to create an account where I can add recipes.
    - Users are able to register their account by pressing on the register link in the menu that takes them to the register website.
- to be able to log into my account.
    - users can login by clicking on the login link in the menu which takes them to the login page.
- to be able to add new recipes.
    - Once logged in, users can click on add recipes and a page with a form for them to fill will show up.
- to have my recipes all in one place.
    - users can click on my recipes link which will take them to all the recipes they have created.

 ## Validation testing

 [PEP8 Compliance](assets/pep8_validator.png)
 Had a few indentation issues which were solved.

[CSS Validator](assets/Css_validator.png)

No issues in the CSS validator.

[Html Validator](assets/html_validator.png)

There was an error in the html where the url of the image was showing an extra inverted comma at the end. This was amended and cleared most of the issues. The HTML validator showed some issues with regards to the image and missing alt, but since the images are links submitted by viewers it makes sense that an alt is not present.

[JS Validator](assets/jshint_validator.png)

Had an issue with a comment that didn't have the appropriate comment signs (/*), which was causing issues with the rest of the script. Changed that and solved it.

 ### Lighthouse

 Lighthouse shows good accessibility for both website and mobile version.

 [Lighthouse Webpage](assets/lighthouse-website.png)
 [Lighthouse Mobile](assets/lighthouse-mobile.png)

### PEP8

 [PEP8](assets/pep8.png)

 The only issues shown are under-indentation which are necessary for better code visibility.

### JSHINT

JShint showed no issues with the javascript and jquery code.