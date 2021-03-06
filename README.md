![Logo](/docs/logo.png)
# Kooky -- Secure Browsing made easy
------------------

### Why Kooky?
In a time when many companies are gathering more and more data everyday, Kooky puts you back in control of your online privacy. By using smarter techniques to make it impossible to track your browsing habits, Kooky always has your back.

### What we do
Kooky is a powerful browser extension, designed to provide real time data on the sites following you. We turn the tables on the websites tracking you by allowing you to view their information. By using our browser extension, you can choose which cookies you keep to allow websites to function as normal, or you can use our 'Ultimate Protection Mode' to maximise your anonymity.

### How we built it
Kooky uses the power of Avast's Secure Browser and CCleaner, as well as some Javascript libraries in order to link these and extend their functionality.

### Accomplishments that we're proud of
Our 'Aggressive Caching' allows regular scheduled cookie deletion, whilst the 'Ultimate Protection Mode' allows you to anonymise your browser user agent at regular intervals.

### What's next for Kooky 

An implementation of an 'IP-scrambler' in order to alter your IP address through a VPN extension when using the Ultimate Protection Mode will follow. We have already discussed the best way to do this with the Avast team.

---------------

### Screenshots
![Dashboard](/docs/dashboard.jpg)
![Options Page](/docs/options_page.jpg)
--------------------------
### How to Install:
Dependencies: 
- Avast Secure Browser ([here](https://dev-download.avastbrowser.com/ccleaner/avast_secure_browser_setup.exe))
- CCleaner Application (requires a custom build of the application) *To do: remove CCleaner dependency so that the app can work without having to depend on the custom built CCleaner.

Extensions can be loaded in unpacked mode by following these steps in the Avast Secure Browser:
- Visit secure://extensions (via: Menu -> More Tools -> Extensions).
- Enable Developer mode by ticking the checkbox in the upper-right corner.
- Click on the "Load unpacked extension..." button.
- Select the directory containing the unpacked extension (e.g. src)

