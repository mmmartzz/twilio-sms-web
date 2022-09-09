Twilio SMS App
==============
A minimalist web application to send and receive SMS with Twilio.

Twilio Account
==============
You will need a Twilio account to read and send SMS messages.

Sign-in to Twilio SMS Web
-------------------------
1. Sign-in to Twilio and get your `ACCOUNT SID` and `AUTH TOKEN` on the [Twilio's Console Page][TwilioConsole].
2. Use your `ACCOUNT SID` and `AUTH TOKEN` to sign-in to [Twilio SMS Web][HostedDemo].

Environment Variables
---------------------
This project uses [dotenv](https://github.com/motdotla/dotenv) to manage environment variables.
Developers can change these values according to their needs via environment variables or editing the `.env` file.

Sample `.env` file:
```
# When this value is populated, then Google Tag Manager is going to be enabled with this publicId, i.e: GTM-0000000
REACT_APP_GOOGLE_TAG_MANAGER_ID=GTM-0000000
```

`.env` files should be managed independently and they should not be pushed to the codebase repository.


[TwilioConsole]: https://www.twilio.com/console?