# phone

A simple webpage that automatically triggers a phone dialer with a preset USSD code (`*8378#`).

## How it works

Opening `index.html` redirects the browser to a `tel:` URL, prompting the device to dial the number. A fallback button is shown in case the automatic redirect is blocked.

## Usage

Host `index.html` and open the link on a mobile device. The dialer will launch with `*8378#` pre-filled.
