# Fake Captcha
Realistic reCAPTCHA lookalike widget for any web project
## Demo
https://75a.github.io/fake-captcha/

<img src="https://raw.githubusercontent.com/m-brz/fake-captcha/main/gif-demo.gif" alt="Fake captcha demo">

## Installation/Usage
1. Copy the `images` and `src` directories to your project
2. Put `<link href="src/fakerecaptcha.css" rel="stylesheet">` inside the `<head>` tag
3. Put `<script src="src/fakerecaptcha.js"></script>` right before the `</body>` closing tag
4. At the location where you'd like the fake captcha to be, put the HTML code from [fakecaptcha.html](https://github.com/m-brz/fake-captcha/blob/main/fakecaptcha.html)
## Customization
### Verifying window
Contents of the verifying window is to be set inside the `<main>` tag
### Verification process
Clicking at the "Verify" button triggers the `verifyCaptcha()` function in the [src/fakerecaptcha.js](https://github.com/m-brz/fake-captcha/blob/main/src/fakerecaptcha.js).
You can define the function however you want. If you wish to close the verification window upon that action, just call 
`closeVerifyWindow()`, which will cause the widget to refresh itself and close the window.
