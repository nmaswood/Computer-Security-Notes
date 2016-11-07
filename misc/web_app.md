# Web Application Security

## Cross-Site Scripting
* XSS enables attackers to inject client side scripts into webpages viewed by other users. Can bypass acess controls such as same origin policy
* Same origin policy
    * If content from one site is granted permission to access reousrces on a system then any contnt from that shit will share tehse perismissions while other sites will have to granted permission seprately.
* Websites need to sanitize input.
* Basically Mallory will write malicious code somewhere in onot a webpage and an unsuspecting user will have that code run with their own permissions set.


## Cross-Site Fogery Request

* Unauthorized commands are transmitted from a user that the website trusts
    * Exploits the trust a site has in the user's browser
* Can be triggered through image elements and other no descript stuff
* Confused deputy attack
* The attacker must target that doesn't check the refererheader or a victim with a browser or plugin that allows referrer spoofing
