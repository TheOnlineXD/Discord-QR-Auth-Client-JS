# Discord-QR-Auth-Client-JS
A Discord Bot to communicate with Discord's QR Code login auth server
to easily retrieve useful information about your account
(including token.)

## Thanks to github.com/DismissedGuy for original python source code

## And Thanks to github.com/MrAugu for starter commands

## How to use
Prerequisites:
* Have Node.JS 14+ installed
* A Discord client that can scan QR codes (your phone)

Optional:
* Enable debug mode by modifying `debug=false` in index.js

### Steps
1. `npm i`
2. `node index.js`
3. Use command "$gettoken" with the bot
3. A QR code wil pop up. Scan it using your phone
(either using discord or a generic QR code scanner)
4. Bot will send a DM to account that scanned the QR Code.
