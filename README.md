# anti-khanmigo
uBlock Origin/AdBlock Plus filter to block Khanmigo crap on school accounts. Normally impossible to disable, as the settings page says that it can't be managed by people under 18. 

# Disclaimers
**USE AT YOUR OWN RISK!** If you're modifying settings on a school device, I assume no responsibility for it or any trouble you might get into as a result. This is primarily intended as a resource for home computers accessing school accounts (if so allowed), or schools that don't have issues with custom AdBlock filters. 

I'm still working on these filters, so not everything may be blocked yet. This is my first time making a filter, so apologies if it looks duct taped together.

# What it Blocks
* Khanmigo sidebar in lessons
* Khanmigo link in nav bar
* Khanmigo section in Learner Home sidebar
* Khanmigo activities page (slightly broken; uBO only)

## Not blocked
* Khanmigo tab in user settings (in case they do enable the ability to configure it)
* Some less "in your face" entrypoints may not be filtered yet.

# Installation
**I always recommend using uBO and Firefox**. I've included instructions for AdBlock Plus as well, as it's installed by default on school computers and therefore most convenient, and uBO isn't usable on Chrome (thanks, Google). AdGuard instructions coming soon. 

## uBlock Origin
*uBO Lite instructions coming soon*. 
1. Click on the extension in your toolbar, and from the popout, click the cogwheels.
2. Navigate to "filter lists" (not "my filters") tab
3. Scroll to the bottom and click "Import"
4. Paste the link: https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo/refs/heads/main/anti-khanmigo-filter.txt
5. Click "Apply Changes"
6. You're done! It should show up in the "Custom" section on the filters page.

## AdBlock Plus
1. Click on the extension and click the cogwheel in the popout.
2. On the left of the page, choose "Advanced".
3. Scroll down and click "Add Filter List by URL"
4. Paste the link: https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo/refs/heads/main/anti-khanmigo-filter.txt
5. You're done! It should be in the list alongside the default filters.
