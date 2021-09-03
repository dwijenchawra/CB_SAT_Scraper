# CB_SAT_Scraper

NOTE: THIS MAY NEED SOME EDITS DEPENDING ON YOUR PORTAL. THIS IS NOT GUARANTEED TO WORK OUT OF THE BOX!

A Selenium tool to check automatically whether there are open SAT testing locations, then email and text you a list so you don't miss the date like I did!

This script uses chromedriver, so get youself one that matches your installed chrome version from https://chromedriver.chromium.org/downloads.

I ran this on a Raspberry Pi as a cron job, every 30 minutes just to be safe. The SMS option will not work with TMobile, because they do not support MMS (Mail Messaging Service). You can always use Twilio or another messaging service of your choice.

Hopefully this script lands you a SAT date!
