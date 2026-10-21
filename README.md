# corevyn-sms

Public website for the Corevyn text message (SMS) program. It describes how people opt in to appointment notifications from Corevyn, the clinic management software, and links to the privacy policy and terms that SMS program registration requires.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Opt-in page: text **START** to (754) 260-2413, with the consent disclosure |
| `privacy.html` | Privacy Policy for the SMS program |
| `terms.html` | SMS Terms & Conditions (program description, frequency, costs, STOP/HELP) |
| `style.css` | Shared styles, with light and dark mode |

## Running locally

The site is plain static HTML with no build step or dependencies. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploying

Upload the files to any static host, such as GitHub Pages. Keep the three pages at stable public URLs, because the SMS program registration links to them.

## Updating the policies

When you change `privacy.html` or `terms.html`, update the "Effective" date at the top of the page.

## Contact

hectechsys@gmail.com
