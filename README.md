this script requires sudo password and homebrew on high sierra or apt on linux installed

for each device, generate a gmail app password like this

https://myaccount.google.com/

2 factor authentication needs to be set up

Click "Signing into Google"

Click "App passwords"

Select "Mail" and "other", maybe name it "msmtp"

Generate the msmtp password and save it somewhere

run like this:

chmod 755 msmtp_setup.sh

EMAIL_="your@mail.com" USERNAME_="your-screen-name" PASSWORD_="your-generated-google-app-password" ./msmtp_setup.sh
