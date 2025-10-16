This project is a simple client-side Captcha Solver demo.

## Features:
- Load a default captcha image (`sample.png`).
- Load a custom captcha image by providing a URL.
- Input text to solve the captcha.
- Basic client-side verification for the `sample.png` captcha.

## How to Use:
1. Open `index.html` in your web browser.
2. The `sample.png` captcha will be displayed by default.
3. Enter "ADUR3" into the text field and click "Verify Captcha" to see a "Correct!" message.
4. Optionally, enter an image URL into the "Image URL" field and click "Load Image" to display a custom captcha.
    - *Note*: Client-side verification is only implemented for `sample.png`. For custom images, it will only acknowledge input.
