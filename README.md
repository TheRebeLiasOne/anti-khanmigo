# anti-khanmigo

> [!IMPORTANT]
> Khan Academy "Reimagined" broke this filter. It will no longer be updated. An Anti-Khanmigo Reimagined will be released in the hopefully not to distant future. 

uBlock Origin/AdBlock Plus filter to block Khanmigo crap on school accounts. Normally impossible to disable, as the settings page says that it can't be managed by people under 18. 

This only blocks Khanmigo! If you want to block other things, I'd recommend checking out [Fanboy's Anti-AI Suggestion List](https://github.com/easylist/easylist/blob/master/fanboy-addon/fanboy_ai_suggestions.txt). To add it, follow the same instructions listed below, but add https://raw.githubusercontent.com/easylist/easylist/refs/heads/master/fanboy-addon/fanboy_ai_suggestions.txt in addition to my link. 

## Disclaimers
**USE AT YOUR OWN RISK!** If you're modifying settings on a school device, I assume no responsibility for it or any trouble you might get into as a result. This is primarily intended as a resource for home computers accessing school accounts (if so allowed), or schools that don't have issues with custom AdBlock filters. 

I'm still working on these filters, so not everything may be blocked yet. This is my first time making a filter, so apologies if it looks duct taped together.

## What it Blocks
* Khanmigo sidebar in lessons, videos, and 
* Khanmigo link in nav bar
* Khanmigo section in Learner Home sidebar
* The entire Khanmigo activities page
* Khanmigo courses under "Life Skills" and "Khan for Educators"
* The "Tutor Me" button when incorrectly answering a question

### Not blocked
* Khanmigo tab in user settings (in case they do enable the ability to configure it)
* Some less "in your face" entrypoints may not be filtered yet.

## Installation
**I always recommend using uBO and Firefox or the AdGuard extension on Chrome**. I've included instructions for AdBlock Plus as well, as it's installed by default on my school's computers and therefore most convenient, and uBO isn't usable on Chrome (thanks, Google) while most schools have it. I don't recommend uBO Lite for custom filters; it has partial support but can't update them automatically.  

For details on why AdBlock Plus is *not* recommended, see [Why not AdBlock Plus?](https://github.com/TheRebeLiasOne/anti-khanmigo/blob/main/Why%20not%20ABP.md)

### uBlock Origin
*These instructions won't work on uBO Lite*
1. Click on the extension in your toolbar, and from the popout, click the cogwheels.
2. Navigate to "filter lists" (not "my filters") tab.
3. Scroll to the bottom and click "Import".
4. Paste the link: https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo/refs/heads/main/anti-khanmigo-filter.txt
6. Click "Apply Changes".
7. You're done! It should show up in the "Custom" section on the filters page.
8. You don't need to add Fanboy's list manually as it's already included under "EasyList - Annoyances". Just enable it from there. You'll manually add this to the other extensions though. 

**To update:** Should update automatically. If you ever wish to check, navigate to the filters page and find the filter in your list then click the clock icon. (If there's a loading icon, it's already in the process of updating). 

### AdGuard
1. Open AdGuard. From the extension popout, click the cogwheel.
2. On the left, click "Filters".
3. Scroll to the bottom and enable "Custom".
   *If prompted to allow user scripts*: Click the link to your browser's extension settings and toggle "Allow User Scripts".
5. Now click on "Custom", and choose "Add Custom Filter".
6. Paste https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo/refs/heads/main/anti-khanmigo-filter.txt and click "Next".
7. Check the "Trusted" box if desired, then click "Add".
8. You're Done! The filter should appear in the custom list.

**To update:** open the extension popout then click the clockwise arrows at the top to check (it'll check for all enabled filters). If it's already checked, it may show as a green up arrow instead. AdGuard might not automatically install updates so it's important to check every once in a while.

### AdBlock Plus
1. Click on the extension and click the cogwheel (settings) icon in the popout.
2. On the left of the page, choose "Advanced".
3. Scroll down and click "Add Filter List by URL".
4. Paste the link: https://raw.githubusercontent.com/TheRebeLiasOne/anti-khanmigo/refs/heads/main/anti-khanmigo-filter.txt, then choose "Add a Filter List". 
6. You're done! It should be in the list alongside the default filters.

**To update:** Revisit the "Advanced" page and find the filter, then click the cogwheel (settings) icon next to the filter and choose "Update Now". 

