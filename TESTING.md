# Testing
Return back to the [README.md](README.md) file.

## Code Validation

### HTML
I have used the recommended [HTML W3C Validator](https://validator.w3.org/nu/) to validate all of my HTML files.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Falansmythdeaf.github.io%2Froversfanclub%2Findex.html) | ![screenshot](documentation/validation/html-validator-index.png) | Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed. |

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Roll of honour | [W3C](https://alansmythdeaf.github.io/roversfanclub/rollofhonour.html) | ![screenshot](documentation/validation/html-validator-roh.png) | Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed. |

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Gallery | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Falansmythdeaf.github.io%2Froversfanclub%2Fgallery.html) | ![screenshot](documentation/validation/hmtl-validator-gallery.png) | Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed. |

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Falansmythdeaf.github.io%2Froversfanclub%2Fcontact.html) | ![screenshot](documentation/validation/css-validation-style.png) | Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed. |


### CSS
I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.


 File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator) | ![screenshot](documentation/validation/css-validation-style.png) | Pass: No Errors |
|

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

- [Chrome](https://www.google.com/chrome)

| Index - Home | Roll of Honour | Gallery | Contact | Notes |

![screenshot](documentation/browser/browser-chrome-index.png) | ![screenshot](documentation/browser/browser-chrome-roh.png) | ![screenshot](documentation/browser/browser-chrome-gallery.png) | ![screenshot](documentation/browser/browser-chrome-contact.png) | Works as expected |

- [Firefox (Developer Edition)](https://www.mozilla.org/firefox/developer)

| Index - Home | Roll of Honour | Gallery | Contact | Notes |
| ![screenshot](documentation/browser/browser-firefox-index.png) | ![screenshot](documentation/browser/browser-firefox-roh.png) | ![screenshot](documentation/browser/browser-firefox-gallery.png) | ![screenshot](documentation/browser/browser-firefox-contact.png) | Works as expected |

- [Edge](https://www.microsoft.com/edge)

| Index - Home | Roll of Honour | Gallery | Contact | Notes |
![screenshot](documentation/browser/browser-edge-index.png) | ![screenshot](documentation/browser/browser-edge-roh.png) | ![screenshot](documentation/browser/browser-edge-gallery.png) | ![screenshot](documentation/browser/browser-edge-contact.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

- Mobile Phone

| Index - Home | Roll of Honour  | Gallery | Contact |
| --- | --- | --- | --- |
| ![screenshot](documentation/responsiveness/responsive-mobile-index.jpg) | ![screenshot](documentation/responsiveness/responsive-mobile-roh.jpg) | ![screenshot](documentation/responsiveness/responsive-mobile-gallery.jpg) | ![screenshot](documentation/responsiveness/responsive-mobile-contact.jpg) | works as expected

- Tablet (Ipad Mini)

| Index - Home | Roll of Honour  | Gallery | Contact |
| --- | --- | --- | --- |
| ![screenshot](documentation/responsiveness/responsive-ipad-index.png) | ![screenshot](documentation/responsiveness/responsive-ipad-roh.png) | ![screenshot](documentation/responsiveness/responsive-ipad-gallery.png) | ![screenshot](documentation/responsiveness/responsive-ipad-gallery.png) | 

- Laptop / Desktop

| Index - Home | Roll of Honour  | Gallery | Contact |
| --- | --- | --- | --- |
| ![screenshot](documentation/responsiveness/responsive-desktop-index.jpg) | ![screenshot](documentation/responsiveness/responsive-desktop-roh.jpg) | ![screenshot](documentation/responsiveness/responsive-desktop-gallery.jpg) | ![screenshot](documentation/responsiveness/responsive-desktop-contact.jpg) |


## Lighthouse Audit
I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

 - DESKTOP

| Index - Home | ![screenshot](documentation/lighthouse/lighthouse-index.png) | Recommended hero banner to be WebP than png |

| ROH -Roll of honour | ![screenshot](documentation/lighthouse/lighthouse-roh.png) | Recommended image to be WebP rather than png |

| Index - Gallery | ![screenshot](documentation/lighthouse/lighthouse-gallery.png) | Recommend images that are appropriately-sized to save data and improve load time |

| Contact | ![screenshot](documentation/lighthouse/lighthouse-contact.png) | Recommened not to use br after li |

- MOBILE

| Index - Home | ![screenshot](documentation/lighthouse/lighthouse-mobile-index.png) | Recommended hero banner to be WebP than png |

| ROH -Roll of honour | ![screenshot](documentation/lighthouse/lighthouse-mobile-roh.png) | Recommended avoid large layout shifts & Recommended image to be WebP rather than png |

| Index - Gallery | ![screenshot](documentation/lighthouse/lighthouse-mobile-gallery.png) | Recommended avoid large layout shifts & proplerly size images |

| Contact | ![screenshot](documentation/lighthouse/lighthouse-mobile-contact.png) | 


## User Story Testing

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to easily understand the main purpose of the site and learn more about the organisation. | ![screenshot](documentation/features/index-fanclub.png) |
| As a new site user, I would like to easily navigate throughout the site to find content. | ![screenshot](documentation/browser/browser-chrome-contact.png) |
| As a new site user, I would like view the website and content clearly on my mobile device. | ![screenshot](documentation/responsive-mobile-index.jpg) |
| As a new site user, I would like to find ways to follow the Shamrock Rovers Fan Club on different social media platforms.| ![screenshot](documentation/browser/browser-chrome-contact.png) |

| User Story | Screenshot |
| --- | --- |
| As a Returning user, I want to see the gallery section | ![screenshot](documentation/responsiveness/responsive-desktop-gallery.jpg) |
| As a Returning user,  I want to see the opening hours and days| ![screenshot](documentation/browser/browser-chrome-contact.png) |

## Bugs

- When validating HTML, theSection lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed.

    ![screenshot](documentation/validation/html-validator-roh.png)
## Unfixed Bugs
