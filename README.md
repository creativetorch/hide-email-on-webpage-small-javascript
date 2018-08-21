# hide-email-on-webpage-small-javascript

Hide an email address on your webpage from spam bots, crawlers, and website scrapers with a small javascript.


Change "updateuser" (1 reference) and "updatehost.com" (in 2 places) for your desired user and email-domain address.
The script will add "@" and put everything together and print your full email address on a webpage. Place the script where you want the email address displayed.


var userid = "updateuser";

var hostid = "updatehost.com";

...remaining code removed for security reasons; see file...

Do not rename 'userid' or 'hostid'

NOSCRIPT option:
Update the line with any information you want the user to see if they do not have javascript enabled:
<noscript> [Javascript needs to be enabled to view the email address] </noscript>
Do not put the full email address here with an "@" symbol... that will defeat the whole purpose of using this script. Leave the current text or try: Email us at username ..![at]!.. domain.com.

DISCLAIMER: This script is not perfect, protecting from bot crawlers is a constant battle. As "they" get better, so must our protections. If you start to get more email junk than normal, check where your email address may be displayed without any "protection" online. You may also think about changing the script and text to adapt it to obfuscate the text more so crawlers can not read it – hire a web designer or developer.
