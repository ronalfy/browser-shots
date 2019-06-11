# Browser Shots

<a href="https://wordpress.org/plugins/browser-shots/">Browser Shots is a WordPress plugin</a> to automate the process of taking website screenshots.

## Shortcode Arguments

```
// basic shot 600px wide
[browser-shot url="http://link-to-website" width="600"]

// shot with link to other website
[browser-shot url="http://link-to-website" width="700" link="http://www.binarymoon.co.uk/"]

// shot with caption (uses default WordPress caption styles)
[browser-shot url="http://link-to-website" width="700"]Add Caption[/browser-shot]
```

## Gutenberg

As of 1.7, there is a Gutenblock for embedded your screenshots.

## Gutenberg Devs

1. Clone the repository
2. Run ```npm install```
3. Edit the block in ```src/edit.js```
4. To develop run: ```npm start```
5. To build for deployment run: ```npm run build && wp i18n make-pot . languages/browser-shots.pot --exclude="/src/js,src/block"```
