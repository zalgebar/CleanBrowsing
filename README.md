# CleanBrowsing
Utilizes [uBlock Origin Filter Syntax](https://github.com/gorhill/uBlock/wiki/Static-filter-syntax).

## CleanAmazon
Removes various elements related to Rufus (Amazon's AI).

## CleanAtlassian
Removes various elements that enable Rovo AI (Atlassian's AI).

## CleanFandom
Fandom has taken over just about every Wiki for gaming and other types of fandoms, resulting in a corporate, bloated, ad-heavy experience. This filter list intends to clean up the Fandom website of annoying ads and excess content.

While this filter list is quite helpful, there are other resources out there that could use your support for their initiatives.

* https://www.wiki.gg/
* https://breezewiki.com/

### Disabled Elements
* Slide Down Top Navigation bar
* Left Navigation Panel
* Pre-content Ad Bar
* Right Ad bar
* In-Content Video Ads
* Bottom Ad Bar
* Floating Notification pop-up (lower left)
* Floating Navigation bar (lower right)
* Footer suggesting other Wikis
* Comments Section

## CleanGoogle
Removes Gemini elements, buttons, and panels.

## How to Use
These filter lists were developed for use with [Brave Browser](https://brave.com/). Other suggested settings to enable within Brave:
* "Shields Up" (required to use filter lists)
* Advanced Controls:
  * Aggressively block trackers & ads
  * Block fingerprinting
  * Block third-party cookies

To install in Brave:
1. Click on the `*.txt` file in this repository for whichever site you want to clean up.
2. Click on the **raw** button on the far right.
3. Copy the address from from this new plain text GitHub page.
4. Enter `brave://settings/shields/filters` into your address bar.
5. Scroll down to **Add custom filter lists**.
6. Paste the address from step 3 into the **Enter filter list URL** text field and click **Add**.

To install in Firefox (tested), Edge (untested), or Chrome (untested):
1. Install the uBlock Origin Extension.
2. Follow the instructions to install custom filter lists on the [uBlock GitHub page](https://github.com/gorhill/ublock/wiki/Dashboard:-Filter-lists#3rd-party-filter-lists).

It appears that Safari does not support Custom Filter Lists either natively nor with the uBlock Origin Extension.

## Other Suggestions
1. Please don't use MS Edge or Google Chrome, use Brave or some other Privacy respecting Browser instead.
2. Click the "Expand" button in the upper-left to get more real estate for reading actual content.

# FAQ
Q: For Fandom, There's still a big empty panel on the left side. What's up with that?

A: Unfortunately, this is not an element in an of itself, it is a margin from the main content, so it can't be fixed with a simple filter list. However, you can make it smaller. Simply click the "Expand" button in the upper-left and then refresh the page. It will usually go away.

# Donate
Help support the project.


lightning: zalgebar@rizful.com
