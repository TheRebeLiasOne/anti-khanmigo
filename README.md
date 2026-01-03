# anti-khanmigo
uBlock Origin/AdBlock Plus filter to block Khanmigo crap on school accounts. Normally impossible to disable, as the settings page says that it can't be managed by people under 18. 

## Disclaimers
**USE AT YOUR OWN RISK!** If you're modifying settings on a school device, I assume no responsibility for it or any trouble you might get into as a result. This is primarily intended as a resource for home computers accessing school accounts (if so allowed), or schools that don't have issues with custom AdBlock filters. 

I'm still working on these filters, so not everything may be blocked yet. This is my first time making a filter, so apologies if it looks duct taped together.

## What it Blocks
* Khanmigo sidebar in lessons
* Khanmigo link in nav bar
* Khanmigo section in Learner Home sidebar
* The entire Khanmigo activities page (slightly broken; won't work on AdBlock Plus)

### Not blocked
* Khanmigo tab in user settings (in case they do enable the ability to configure it)
* Some less "in your face" entrypoints may not be filtered yet.

## Optional: Fanboy's Anti-AI Suggestions List

To also hide AI suggestions in search engines, you can use [Fanboy's Anti-AI Suggestion List](https://github.com/easylist/easylist/blob/master/fanboy-addon/fanboy_ai_suggestions.txt) from the EasyList Repo. Note that this filter is licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/), and not public domain like my Khanmigo filter is. To add it, follow the same instructions listed below, but add https://raw.githubusercontent.com/easylist/easylist/refs/heads/master/fanboy-addon/fanboy_ai_suggestions.txt in addition to my link.

(I don't know Fanboy in any capacity, I'm just happy this exists. Not forking it because I can't be trusted to keep it up to date.)

## Installation
**I always recommend using uBO and Firefox**. I've included instructions for AdBlock Plus as well, as it's installed by default on school computers and therefore most convenient, and uBO isn't usable on Chrome (thanks, Google). AdGuard instructions coming soon. 

### uBlock Origin
*uBlock Origin Lite isn't supported right now. You can add it manually, but YMMV.* 
1. Click on the extension in your toolbar, and from the popout, click the cogwheels.
2. Navigate to "filter lists" (not "my filters") tab.
3. Scroll to the bottom and click "Import".
4. Paste the link: https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo/refs/heads/main/anti-khanmigo-filter.txt
6. Click "Apply Changes".
7. You're done! It should show up in the "Custom" section on the filters page.

### AdBlock Plus
1. Click on the extension and click the cogwheel in the popout.
2. On the left of the page, choose "Advanced".
3. Scroll down and click "Add Filter List by URL".
4. Paste the link: https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo/refs/heads/main/anti-khanmigo-filter.txt, then choose "Add a Filter List". 
6. You're done! It should be in the list alongside the default filters.

## AdGuard
A nice, FOSS alternative to uBlock Origin that still works on Chrome. Seemingly more customizable than uBO Lite. 
1. Open AdGuard. From the extension popout, click the cogwheel.
2. On the left, click "Filters"
3. Enable "Custom"
4. *If prompted to allow user scripts*: Click the link to your browser's extension settings and toggle "Allow User Scripts"
5. Now click on "Custom", and choose "Add Custom Filter".
6. Paste https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo/refs/heads/main/anti-khanmigo-filter.txt and click "Next".
7. Check the "Trusted" box if desired.
8. You're Done! The filter should appear in the custom list. 
