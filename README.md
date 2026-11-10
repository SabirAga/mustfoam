# MustFoam — Premium Website (revised)

## Open locally
Open `index.html` in Chrome or Safari. The standalone file `MustFoam-Premium-Final-Preview.html` supplied separately includes all images, CSS and JavaScript inside one file. Google Fonts are used if an internet connection is available; system font fallbacks are available offline.

## Design
Premium warm stone and ivory palette, integrated foam artwork in the hero, and the approved embossed MF relief artwork in the contact section. The earlier flat MF letters and poorly integrated hero card have been replaced.

## Product scope
Only two product lines: foam sheets and **unbranded** dishwashing sponges. No foam blocks are offered for sale. No unregistered consumer brand is referenced or pictured.

## Languages
English, Azerbaijani and Russian, selectable in the header.

## Before launch
- Product imagery is conceptual / illustrative, not verified photographs of the company's inventory.
- Inquiry form submits to Formspree; confirm the receiving address and test after deployment.
- Add a confirmed domain, verified business email, privacy policy and other legal/contact details before publishing.
- Confirm product specifications and descriptions.

## Test results
Confirmed locally at 1440px, 768px and 390px: no horizontal overflow, product images load, language switcher works and the inquiry form prepares a message. Browser preview test used a rendered inline HTML document due local file navigation restrictions in the test environment.


Default language: Azerbaijani (AZ). Language menu order: AZ / EN / RU. All translations remain available.

## Contact form connected to Formspree
The inquiry form in `script.js` is configured to submit to `https://formspree.io/f/mvkapknq`.

1. In Formspree, confirm the form's notification email is `sabir@mustfoam.az` and complete any verification requested.
2. Deploy the complete website folder through Vercel Drop.
3. Submit a test inquiry on the live site. Check your Zoho inbox and spam folder, as well as the submissions in Formspree.
4. Add a privacy policy and anti-spam protection as appropriate before public promotion.
