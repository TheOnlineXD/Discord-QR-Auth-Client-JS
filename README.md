# Discord-QR-Auth-Client-JS
A Discord Bot to communicate with Discord's QR Code login auth server
to easily retrieve useful information about your account
(including token.)

## How to use
Prerequisites:
* Have Node.JS 12+ installed
* A Discord client that can scan QR codes (your phone)

Optional:
* Enable debug mode by modifying `debug=False` in server.py

### Steps
1. `npm i`
2. `node index.js`
3. Use command "$gettoken" with the bot
3. A QR code wil pop up. Scan it using your phone
(either using discord or a generic QR code scanner)
4. Bot will send a DM message to account that scanned the QR Code.
and it prevents confusion when using the script multiple times.
