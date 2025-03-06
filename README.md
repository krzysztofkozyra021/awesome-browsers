# Awesome Browsers
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

**Welcome to the Awesome Browsers! This list covers a wide range of web browser-related topics, including features, privacy aspects, and helpful links. Whether you're seeking information on mainstream browsers, privacy-focused alternatives, or specific browser extensions, this list helps you navigate the web with confidence.**

# Contribution

**Contributions are highly encouraged — let's expand this list together and make it the go-to resource for everything related to web browsers and grow an awesome community! <br><br> <a href="contributing.md">Contribution guidelines</a>**

# Contents

- **[Browsers](#browsers)**
- **[Browser Comparison](#browser-comparison)**
- **[Special Browsers](#special-browsers)**
- **[Browser for Developers](#browser-for-developers)**
- **Search Engines**
    - **[Standard](#standard-search-engines)**
    - **[Privacy-Focused](#privacy-focused-search-engines)**
- **Privacy & Security**
    - **[Privacy Testing Tools](#privacy-testing-tools)**
    - **[AdBlock Testers](#adblock-testers)**
    - **[Browser Security Best Practices](#browser-security-best-practices)**
- **Extensions**
    - **[Chrome Web Store](#chrome-web-store)**
    - **[Mozilla Add-ons](#addons-mozilla)**
    - **[Extension Categories](#extension-categories)**
- **[Browser Customization](#browser-customization)**
- **[Browser Testing](#browser-testing)**
- **[Choosing the Right Browser](#choosing-the-right-browser)**
- **[Awesome Browser Resources](#awesome-browser-resources)**

# Browsers

🛡️ **Privacy-focused** <br>
💻 **Cross-platform** <br>
🌐 **Open-Source** <br>


- ## Desktop browsers
    - [Chromium](#chromium) - **(and browsers based on)**
        - [Arc](#arc) 💻
        - [Brave](#brave) 🌐 💻 🛡️
        - [Chrome](#google-chrome) 💻
        - [Falkon](#falkon) - 🌐
        - [Microsoft Edge](#microsoft-edge) 💻
        - [Opera](#opera) 💻
        - [Opera GX](#opera-gx) 💻
        - [Vivaldi](#vivaldi) 🌐 💻 🛡️
        - [Yandex Browser](#yandex-browser) 💻 **(controversial)**
        - [Sidekick Browser](#sidekick-browser) 💻
        - [Thorium](#thorium) 🌐 💻
        - [Zen Browser](#zen-browser) 🌐 🛡️

    - [Mozilla Firefox](#mozilla-firefox) 💻 - **(and browsers based on)** 
        - [Floorp](#floorp) 🌐 🛡️ 
        - [Libre Wolf](#libre-wolf) 🌐 🛡️ 
        - [Tor Browser](#tor-browser) 🌐 💻 🛡️  
        - [Mullvad Browser](#mullvad-browser) - **( based on Tor )** 🌐 🛡️
        - [Waterfox](#waterfox) 🌐 🛡️
        - [Firefox Developer Edition](#firefox-developer-edition) 🌐 💻
        - [Firefox Nightly](#firefox-nightly) 🌐 💻
        
    - [Pale Moon](#pale-moon) 🌐
    - [Min Browser](#min-browser) 🌐 🛡️
    - [Orion](#orion) 🛡️
    
- ## Mobile Browsers
    - [Arc](#arc) 💻
    - [Brave](#brave) 🌐 💻 🛡️
    - [Chrome](#google-chrome) 💻
    - [Kiwi Browser](#kiwi-browser) 🌐 💻
    - [Microsoft Edge](#microsoft-edge) 💻
    - [Mozilla Firefox](#mozilla-firefox) 💻
    - [Opera](#opera) 💻
    - [Opera GX](#opera-gx) 💻
    - [Safari](#safari) 💻
    - [Vivaldi](#vivaldi) 🌐 💻 🛡️
    - [Yandex Browser](#yandex-browser) 💻
    - [DuckDuckGo Browser](#duckduckgo-browser) 🛡️
    - [Bromite](#bromite) 🌐 🛡️
    - [Mull](#mull) 🌐 🛡️
    - [Firefox Focus](#firefox-focus) 🌐 🛡️
    - [Onion Browser](#onion-browser) 🌐 🛡️

# Browser Comparison

## Rendering Engines
Modern browsers use different rendering engines that determine how webpages are processed and displayed:

- **Blink**: Used by Chromium and derivatives (Chrome, Edge, Brave, Opera, Vivaldi)
- **Gecko**: Used by Firefox and its derivatives
- **WebKit**: Used by Safari
- **Goanna**: Used by Pale Moon (fork of older Gecko)

## Key Feature Comparison

| Feature | Chrome | Firefox | Safari | Edge | Brave | Opera | Vivaldi | Tor |
|---------|--------|---------|--------|------|-------|-------|---------|-----|
| **Rendering Engine** | Blink | Gecko | WebKit | Blink | Blink | Blink | Blink | Gecko |
| **Open Source** | Partially | Yes | Partially | Partially | Yes | No | Partially | Yes |
| **Password Manager** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Limited |
| **Ad Blocking** | No | Limited | Yes | Limited | Yes | Yes | Yes | Yes |
| **Tracker Blocking** | Limited | Yes | Yes | Limited | Yes | Yes | Yes | Yes |
| **Sync** | Yes | Yes | Apple Only | Yes | Yes | Yes | Yes | No |
| **Extensions** | Many | Many | Limited | Many | Many | Many | Many | Limited |
| **Resource Usage** | High | Medium | Low | Medium | Medium | Medium | Medium-High | Medium |
| **Privacy** | Low | Medium* | High | Low | High | Low | Medium | Very High |
| **Developer Tools** | Excellent | Excellent | Good | Excellent | Good | Good | Good | Basic |

*Note: Recent Firefox updates have raised some privacy concerns regarding data collection practices

# Special Browsers
**[Nyxt](https://github.com/atlas-engineer/nyxt)** - Keyboard-driven web browser inspired by Emacs and Vim with familiar keybindings <br>
**[Qutebrowser](https://github.com/qutebrowser/qutebrowser)** - Keyboard-driven web browser based on Python and Qt, popular among users who prefer minimalism <br>
**[Min Browser](https://minbrowser.org/)** - Minimalist browser with a clean and distraction-free interface <br>
**[Sidekick Browser](https://www.meetsidekick.com/)** - Productivity-focused browser with workspaces and app integration <br>
**[Thorium](https://thorium.rocks/)** - Chromium fork focused on performance and removing Google services <br>
**[Orion](https://kagi.com/orion/)** - WebKit-based browser for macOS with Chrome/Firefox extension support <br>
**[Lynx](https://lynx.invisible-island.net/)** - Text-based browser for terminals, useful for accessibility and low-bandwidth connections <br>
**[Zen Browser](https://www.zen-browser.com/)** - Privacy-focused, customizable browser with built-in productivity tools and zero-data collection policy

# Browser for Developers

Browsers offer specialized tools for web developers to test, debug, and optimize websites and applications.

## Developer-Specific Browser Versions
- **[Firefox Developer Edition](https://www.mozilla.org/firefox/developer/)** - Pre-release version with cutting-edge developer tools and features
- **[Chrome Canary](https://www.google.com/chrome/canary/)** - Bleeding-edge version of Chrome for developers and early adopters
- **[Safari Technology Preview](https://developer.apple.com/safari/technology-preview/)** - Preview of upcoming Safari features

## Key Developer Features
- **DevTools** - Inspect DOM, debug JavaScript, analyze network activity, audit performance
- **Responsive Design Mode** - Test websites across different screen sizes
- **Source Maps** - Debug minified code
- **Console** - JavaScript execution environment
- **Network Monitor** - Analyze requests, timing, and headers
- **Performance Profiling** - Identify bottlenecks and optimize code
- **Accessibility Tools** - Check compliance with accessibility standards

## DevTools Extensions
- **[React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)** - Debug React components
- **[Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd)** - Debug Redux applications
- **[Axe DevTools](https://chrome.google.com/webstore/detail/axe-devtools-web-accessib/lhdoppojpmngadmnindnejefpokejbdd)** - Accessibility testing
- **[Vue.js DevTools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)** - Debug Vue.js applications

# Search Engines

- ## Standard Search Engines
    - **[Google](https://www.google.com/)** - The most popular and widely used search engine, known for its fast, comprehensive, and accurate search results, along with a range of integrated tools and services, altough, not really secure

    - **[Microsoft Bing](https://www.bing.com/)** - A robust alternative to Google, Bing offers visually rich search results, image searches, and rewards users with Microsoft Points

    - **[Yahoo!](https://www.yahoo.com/)** - A search engine that integrates news, mail, and entertainment content with its search capabilities, though its search results are powered by Bing.

    - **[Ecosia](https://www.ecosia.org/)** - An "eco-friendly" search engine that uses ad revenue to plant trees, with the goal of making a positive environmental impact with each search
    
    - **[Kagi](https://kagi.com/)** - A premium, ad-free search engine with advanced customization and high-quality results

    - **[You.com](https://you.com/)** - A search engine focusing on customization and AI-assisted search experiences
    
    - **[Neeva](https://neeva.com/)** - Ad-free, subscription-based search engine with a focus on privacy (now acquired by Snowflake)

- ## Privacy-Focused Search Engines
    - **[Brave Search](https://search.brave.com/)** - Privacy-first search engine developed by Brave, offering ad-free search results without tracking users or collecting personal data

    - **[Startpage](https://www.startpage.com/)** - Privacy-focused search engine that delivers Google's search results without tracking or storing user data

    - **[Qwant](https://www.qwant.com/)** - European search engine that prioritizes privacy and delivers search results without tracking or targeted ads

    - **[SearXNG](https://github.com/searxng/searxng)** - Community-driven fork of Searx that enhances user privacy while offering highly customizable and non-tracking search results

    - **[Swisscows](https://swisscows.com/)** - Family-friendly, privacy-respecting search engine based in Switzerland, focusing on security and data protection

    - **[DuckDuckGo](https://duckduckgo.com/)** - Popular privacy-focused search engine that doesn't track user activity and offers straightforward search results without personalized ads

    - **[Presearch](https://presearch.com/)** - Decentralized search engine that rewards users with cryptocurrency tokens for searching while maintaining privacy and security
    
    - **[Mojeek](https://www.mojeek.com/)** - Independent search engine with its own index that doesn't track users
    
    - **[MetaGer](https://metager.org/)** - Privacy-focused meta search engine from Germany with its own web crawler

# Privacy & Security

- ## Privacy Testing Tools

    - **[BrowserLeaks](https://browserleaks.com/)** - Comprehensive suite of tools to test browser information leakage
    - **[amIunique](https://amiunique.org/)** - Check how unique your browser fingerprint is
    - **[Arkenfox user.js](https://github.com/arkenfox/user.js)** - Firefox configuration hardening for privacy and security
    - **[PrivacyTests](https://privacytests.org/)** - Website to check which web browsers pass privacy tests (e.g., SP tests, Navigation tests, HTTPS tests, and others)
    - **[Arkenfox Test Sites Wiki](https://github.com/arkenfox/user.js/wiki/Appendix-A-Test-Sites)** - List of helpful test sites to check how private your browser is
    - **[XSinator](https://xsinator.com/)** - XS-Leak browser test suite
    - **[CoverYourTracks](https://coveryourtracks.eff.org/)** - Website to help you check your protection against tracking and fingerprinting
    - **[TestingYourSecurityPrivacy](https://www.billdietrich.me/TestingYourSecurityPrivacy.html?expandall=1#TestForLeaks)** - A list that covers a wide range of privacy and security tests
    - **[minbrowser](https://github.com/minbrowser/min)** - Open-source, minimal and privacy-focused browser, designed to help users focus by offering distraction-free browsing
    - **[awesome-privacy Web Browser Section](https://github.com/pluja/awesome-privacy?tab=readme-ov-file#web-browser)** - A section on web browser privacy from Awesome-Privacy
    - **[Hitchhiker’s Guide to Online - Anonymity](https://anonymousplanet.org/guide.html#appendix-v1-hardening-your-browsers)** - Guide to make your browser more private, it's good if you know what you're doing

- ## AdBlock Testers
    - **[d3ward adblock test](https://d3ward.github.io/toolz/adblock.html)** - Open-source test that allows you to check if your adblock solution is blocking enough hosts
    - **[AdBlock Tester](https://adblock-tester.com/)** - Test AdBlock with various advertising and analytic services
    - **[Can you block it?](https://canyoublockit.com/)** - AdBlock test website offering three types of tests (Simple, Extreme, and Advanced)
    - **[The AdBlock Test](https://adblocktest.com/)** - Comprehensive test for various ad-blocking solutions
    - **[Ad Blocker Test - 2IMAGES](https://www.2images.ch/en/adblock-detect.html)** - Simple test to check if your ad blocker is working

- ## Browser Security Best Practices

    - **Keep browsers updated**: Always run the latest version to get security patches
    - **Use strong, unique passwords**: Implement a password manager for website credentials
    - **Enable multi-factor authentication**: Add an extra layer of security for important accounts
    - **Regularly clear browsing data**: Remove cookies, cache, and browsing history periodically
    - **Be cautious with extensions**: Only install necessary extensions from official stores
    - **Check HTTPS**: Ensure websites use secure connections (look for the lock icon)
    - **Use private browsing**: For sensitive activities, use private/incognito mode
    - **Disable unnecessary features**: Turn off features like location services when not needed
    - **Manage cookie settings**: Set browsers to delete cookies after closing or block third-party cookies
    - **Use content blocking**: Enable tracking protection or ad blockers for better security

# Extensions 

![Warning](https://img.shields.io/badge/Warning-Google%20deprecating%20Manifest%20v2-orange)

⚠️ **Warning**: Since Google is going to deprecate Manifest v2, all ad-blocking, tracker-removal, etc. extensions won't work in future releases (they are currently testing it in the Canary build).

There are some workarounds to support Manifest V2. Here is one of the guides: https://gist.github.com/velzie/053ffedeaecea1a801a2769ab86ab376

- ## Chrome web store

    - **[uBlock Origin](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)** - A strong, popular, and highly effective ad and content blocker <br>How to setup uBlock Origin : https://github.com/gorhill/uBlock/wiki/Blocking-mode<br>
    Script to stop AdBlock detection : https://reek.github.io/anti-adblock-killer/#filterlist

    - **[Decentraleyes](https://chromewebstore.google.com/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj)** - Extension that protects you against tracking

    - **[Dark Reader](https://chromewebstore.google.com/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh)** - Allows you to enable dark mode for all web pages

    - **[Sponsor Block](https://chromewebstore.google.com/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)** - Skip sponsors, intros, outros, subscription reminders, and other annoying parts of YouTube videos

    - **[I still don't care about cookies](https://chromewebstore.google.com/detail/i-still-dont-care-about-c/edibdbjcniadpccecjdfdjjppcpchdlm)** - This add-on will remove cookie warnings from almost all websites (Community version of the popular extension "I don't care about cookies")

    - **[DeArrow](https://chromewebstore.google.com/detail/dearrow-better-titles-and/enamippconapkdmgfgjchkhakpfinmaj)** - Make titles and thumbnails on Youtube free from sensationalism, clickbaits and more

    - **[Boomerang](https://chromewebstore.google.com/detail/boomerang-soap-rest-clien/eipdnjedkpcnlmmdfdkgfpljanehloah)** - Allows you to easily test SOAP & REST services

    - **[Wappalyzer](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg)** - A utility that uncovers all the technologies used on websites

    - **[StayFocused](https://chromewebstore.google.com/detail/stayfocusd-block-distract/laankejkbhbdhmipfmgcngdelahlfoji)** - Helps you stay focused by limiting the amount of time spent on time-wasting websites

    - **[Bitwarden](https://chromewebstore.google.com/detail/mened%C5%BCer-hase%C5%82-bitwarden/nngceckbapebfimnlniiiahkandclblb)** - Simple, powerful and secure password manager 

    - **[Start.me](https://chromewebstore.google.com/detail/strona-nowej-karty-startm/cfmnkhhioonhiehehedmnjibmampjiab)** - Express yourself by customizing your start page

    - **[Volume master](https://chromewebstore.google.com/detail/volume-master-kontroler-g/jghecgabfgfdldnmbfkhmffcabddioke)** - Let you boost volume up to 600%
 
    - **[Chaff](https://chromewebstore.google.com/detail/chaff/jgjhamliocfhehbocekgcddfjpgdjnje)** - Generate random web browsing traffic to obfuscate actual browsing behavior to avoid profiling through 3rd party observation
    - **[ClearURLs](https://chromewebstore.google.com/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk)** - Automatically remove tracking elements from URLs to help protect your privacy when browse through the Internet
    - **[Wayback Machine](https://chromewebstore.google.com/detail/wayback-machine/fpnmgdkabkmnadcjpehmlllkndpkmiak)** - Go back in time to see how a website has changed through the history of the Web. Save websites, view missing 404 Not Found pages, or read archived books & papers
    - **[Perplexity - AI Companion](https://chromewebstore.google.com/detail/perplexity-ai-companion/hlgbcneanomplepojfcnclggenpcoldo)** - Ever found yourself buried in browser tabs, trying to find that one answer or summary that makes everything clear? Perplexity is your go-to solution—a harmonious blend of ChatGPT and Google, designed to serve your curiosity instantly
    - **[OneTab](https://chromewebstore.google.com/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall)** - Every time you have too many cards, click the OneTab icon to turn all cards into a list. If you want to access them again, you can restore all or individual cards
    - **[Extensity](https://chromewebstore.google.com/detail/extensity/jjmflmamggggndanpgfnpelongoepncg)** - Quickly enable / disable Google Chrome extensions
    - **[d3coder](https://chromewebstore.google.com/detail/d3coder/gncnbkghencmkfgeepfaonmegemakcol)** - Add-on that allows you to encode and decode different types of encoding, such as base64, rot13 or time
    - **[Distill Web Monitor](https://chromewebstore.google.com/detail/distill-web-monitor/inlikjemeeknofckkjolnjbpehgadgge)** - Monitor changes on websites and news channels. Receive email or text notifications about changes
    - **[GoFullPage](https://chromewebstore.google.com/detail/gofullpage-full-page-scre/fdpohaocaechififmbbbbbknoalclacl)** - Capture a screenshot of your current page in entity and reliably — without requesting any extra permissions
    - **[Fake news debunker](https://chromewebstore.google.com/detail/fake-news-debunker-by-inv/mhccpoafgdgbhnjfhkcmgknndkeenfhe)** - Plugin has been designed as a verification "Swiss army knife " helping journalists, fact-checkers, and human rights defenders to save time and be more efficient in their fact-checking and debunking tasks on social networks especially when verios 
    - **[Link Grabber](https://chromewebstore.google.com/detail/link-grabber/caodelkhipncidmoebgbbeemedohcdma)** - An easy to use extractor or grabber for hyperlinks on an HTML page, extract links from an HTML page and display them in another tab
    - **[Linkclump](https://chromewebstore.google.com/detail/linkclump/lfpjkncokllnfokkgpkobnkbkmelfefj)** - Linkclump gives you the ability to drag a selection box around links using your mouse to quickly open as new tabs, open in new window, save as bookmarks, or copy to clipboard. Similar to Snap Links or Multi Links for Firefox
    - **[NoScript](https://chromewebstore.google.com/detail/noscript/doojmbjmlfjjnbmnoijecmcbfeoakpjm)** - Maximum protection for your browser: NoScript allows active content only in trusted domains to prevent them
    - **[Project Naptha](https://chromewebstore.google.com/detail/project-naptha/molncoemjfmpgdkbdlbjmhlcgniigdnf)** - Highlight, copy, edit, and translate text from any image on the web
    - **[Office Editor](https://chromewebstore.google.com/detail/edytor-office/gbkeegbaiigmenfmjfclcdgdpimamgkj)** - Display and edit Microsoft Word, Excel and PowerPoint files even if you don't have Office installed on your computer
    - **[User-Agent Switcher and Manager](https://chromewebstore.google.com/detail/user-agent-switcher-and-m/bhchdcejhohfmigjafbampogmaanbfkg)** - Spoof websites trying to gather information about your web navigation to deliver distinct content you may not want
    - **[Shodan](https://chromewebstore.google.com/detail/shodan/jjalcfnidlmpjhdfepjhjbhnhkbgleap)** - The Shodan plugin tells you where the website is hosted (country, city), who owns the IP and what other services / ports are open
    - **[Grammarly](https://chromewebstore.google.com/detail/grammarly-ai-writing-and/kbfnbcaeplbcioakkpcpgfkobkghlhen)** - Improve your writing with all-in-one assistance — including generative AI, grammar check, and more
    - **[Vortimo OSINT Tool](https://chromewebstore.google.com/detail/vortimo-osint-tool/mnakbpdnkedaegeiaoakkjafhoidklnf)** - Bookmark / record pages, store screenshots, scrape and enrich entities. Finds text on every page + highlight

- ## Addons mozilla

    - **[uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)** - A strong, popular, and highly effective ad and content blocker <br>How to setup uBlock Origin : https://github.com/gorhill/uBlock/wiki/Blocking-mode<br>
    Script to stop AdBlock detection : https://reek.github.io/anti-adblock-killer/#filterlist
    
    - **[Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/)** - Extension that protects you against tracking

    - **[Unhook](https://addons.mozilla.org/en-US/firefox/addon/youtube-recommended-videos/)** - Hide YouTube related videos, comments, video suggestions wall, homepage recommendations, trending tab, and other distractions

    - **[I still don't care about cookies](https://addons.mozilla.org/en-US/firefox/addon/istilldontcareaboutcookies/)** - This add-on will remove cookie warnings from almost all websites (Community version of the popular extension "I don't care about cookies")

    - **[Dark Reader](https://addons.mozilla.org/en-US/firefox/addon/darkreader/)** - Allows you to enable dark mode for all web pages

    - **[Sponsor Block](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/)** - Skip sponsors, intros, outros, subscription reminders, and other annoying parts of YouTube videos

    - **[DeArrow](https://addons.mozilla.org/en-US/firefox/addon/dearrow/)** - Make titles and thumbnails on Youtube free from sensationalism, clickbaits and more

    - **[Wappalyzer](https://addons.mozilla.org/en-US/firefox/addon/wappalyzer/)** - A utility that uncovers all the technologies used on websites

    - **[Bitwarden](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/)** - Simple, powerful and secure password manager 

    - **[600% Sound Volume](https://addons.mozilla.org/en-US/firefox/addon/600-sound-volume/)** - Let you boost volume up to 600%

    - **[Search by Image](https://addons.mozilla.org/en-US/firefox/addon/search_by_image/)** - Makes effortless reverse image searches possible, and comes with support for more than 30 search engines

    - **[Tree Style Tab](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)** - Provides the ability to work with tabs as "trees"

    - **[Grammar and Spell Checker - LanguageTool ](https://addons.mozilla.org/en-US/firefox/addon/languagetool/)** - Check your texts for spelling and grammar problems everywhere on the web

    - **[Absolute Enable Right Click & Copy](https://addons.mozilla.org/en-US/firefox/addon/absolute-enable-right-click/)** - Force enable right click & copy, remove copy text protection from websites and more!

    - **[LeechBlock NG](https://addons.mozilla.org/en-US/firefox/addon/leechblock-ng/)** - Simple free productivity tool designed to block those time-wasting sites that can suck the life out of your working day

    - **[Undo Close Tab](https://addons.mozilla.org/en-US/firefox/addon/undoclosetabbutton/)** - Allows you to restore the most recently closed tab with a single button click and gives you access to the list of recently closed tabs in a context menu

    - **[Emoji](https://addons.mozilla.org/en-US/firefox/addon/emoji-sav/)** - Open-source project which permits you to copy and insert easily an emoji
    
    - **[Firefox Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)** - Keep different parts of your online life separated into color-coded tabs
    
    - **[Firefox Relay](https://addons.mozilla.org/en-US/firefox/addon/private-relay/)** - Create email aliases to protect your real email address
    
    - **[Privacy Badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)** - Automatically learns to block invisible trackers

- ## Extension Categories

    ### Privacy & Security
    - **Content Blockers**: uBlock Origin, AdGuard, Privacy Badger
    - **Anti-Tracking**: Decentraleyes, Privacy Possum, DuckDuckGo Privacy Essentials
    - **Password Managers**: Bitwarden, LastPass, 1Password, KeePassXC
    - **HTTPS Enforcement**: HTTPS Everywhere, Smart HTTPS
    - **Cookie Management**: Cookie AutoDelete, I still don't care about cookies

    ### Productivity
    - **Tab Management**: OneTab, Tab Session Manager, Tree Style Tab
    - **Focus Tools**: StayFocusd, Forest, LeechBlock NG
    - **Bookmark Managers**: Raindrop.io, Pocket
    - **Notes & Clipping**: Web Clipper, Notion Web Clipper

    ### Developer Tools
    - **Web Development**: Web Developer, JSON Formatter, React Developer Tools
    - **Testing & Debugging**: Lighthouse, Axe, Web Vitals
    - **API Tools**: Postman, Boomerang SOAP & REST Client
    - **Accessibility**: WAVE Evaluation Tool, Axe DevTools

    ### User Experience
    - **Dark Mode**: Dark Reader, Night Eye
    - **Readability**: Reader View, Just Read, Tranquility Reader
    - **Translation**: DeepL Translator
    - **Content Customization**: Stylus, Tampermonkey

# Browser Testing

Testing across different browsers is essential for web developers to ensure consistent experiences for all users.

## Browser Testing Tools

### Cross-Browser Testing Platforms
- **[BrowserStack](https://www.browserstack.com/)**: Live, interactive testing on real devices and browsers
- **[LambdaTest](https://www.lambdatest.com/)**: Cloud-based cross-browser testing platform
- **[Sauce Labs](https://saucelabs.com/)**: Automated testing infrastructure for web and mobile apps

### Automated Testing Tools
- **[Selenium](https://www.selenium.dev/)**: Automated browser testing framework
- **[Playwright](https://playwright.dev/)**: Modern automation tool for end-to-end testing
- **[Cypress](https://www.cypress.io/)**: JavaScript testing framework for end-to-end tests

### Compatibility Testing Resources
- **[Can I Use](https://caniuse.com/)**: Browser support tables for web technologies
- **[MDN Compatibility Tables](https://developer.mozilla.org/en-US/docs/MDN/Writing_guidelines/Page_structures/Compatibility_tables)**: Detailed browser compatibility information
- **[Browser Market Share](https://gs.statcounter.com/browser-market-share)**: Global browser usage statistics

### Performance Testing
- **[WebPageTest](https://www.webpagetest.org/)**: Website performance and optimization testing
- **[Lighthouse](https://developers.google.com/web/tools/lighthouse)**: Performance, accessibility, SEO auditing

# Choosing the Right Browser

Selecting the best browser depends on your specific needs and priorities. Here's a guide to help you make an informed decision:

## How to Choose Based on Your Priorities

### If you prioritize privacy:
- **Top choices**: Brave, Tor Browser, LibreWolf, Mullvad Browser
- **Look for**: Tracking protection, fingerprinting resistance, privacy-focused default settings
- **Note**: Firefox has recently faced criticism regarding data collection practices

### If you prioritize performance:
- **Top choices**: Chrome, Edge, Safari (on macOS), Brave
- **Look for**: Memory usage, startup time, JavaScript performance

### If you prioritize customization:
- **Top choices**: Vivaldi, Firefox (with about:config), Brave
- **Look for**: Theme support, UI customization, extension availability

### If you prioritize battery life:
- **Top choices**: Safari (on macOS), Edge, Brave
- **Look for**: Power efficiency features, background tab throttling

## Special Use Cases

### For developers:
- **Recommended**: Firefox Developer Edition, Chrome, Edge
- **Key features**: Advanced DevTools, extension support for web development

### For limited system resources:
- **Recommended**: Min Browser, Falkon, Firefox with performance tweaks
- **Key features**: Low memory usage, efficient resource management

### For maximum security:
- **Recommended**: Tor Browser, Brave, Mullvad Browser
- **Key features**: Enhanced sandboxing, regular security updates, privacy protections

## Decision Framework
1. **Identify your top 2-3 priorities** (privacy, speed, features, etc.)
2. **Consider your ecosystem** (Apple, Google, Microsoft)
3. **Evaluate extension needs** (which essential extensions do you require?)
4. **Consider using different browsers for different purposes** (e.g., one for work, one for personal)

# Browser Customization

Modern browsers offer various ways to personalize your browsing experience:

## Themes and Appearance
- **Chrome Themes**: [Chrome Web Store Themes](https://chrome.google.com/webstore/category/themes)
- **Firefox Themes**: [Firefox Browser Add-ons - Themes](https://addons.mozilla.org/en-US/firefox/themes/)
- **User CSS**: 
  - Firefox: [Firefox CSS Store](https://firefoxcss-store.github.io/)
  - Chrome: [Stylus Extension](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)

## User Interface Modifications
- **Firefox userChrome.css**: Customize Firefox UI elements
  - [How to create a userChrome.css file](https://www.userchrome.org/how-create-userchrome-css.html)
  - [Firefox CSS Hacks](https://github.com/MrOtherGuy/firefox-csshacks)
- **Arc Customization**: Spaces, boosts, and themes in Arc browser
- **Vivaldi UI Customization**: Built-in options for tab position, UI color, etc.

## New Tab Page Customization
- **Custom Start Pages**:
  - [Tabliss](https://tabliss.io/) - Beautiful, customizable new tab with stunning backgrounds
  - [Bonjourr](https://bonjourr.fr/) - Minimalist, iOS-inspired startpage
- **New Tab Extensions**:
  - [Infinity New Tab](https://chrome.google.com/webstore/detail/infinity-new-tab-producti/dbfmnekepjoapopniengjbcpnbljalfg)
  - [Momentum](https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca)

# Awesome Browser Resources

## Browser History & Evolution
- **[Evolution of the Web](http://www.evolutionoftheweb.com/)** - Interactive visualization of web technologies and browsers through time
- **[Browser Market Share (1996-Present)](https://gs.statcounter.com/browser-market-share/desktop/worldwide/#monthly-199601-202401)** - Historical browser usage statistics
- **[Internet Archive: Wayback Machine](https://web.archive.org/)** - View how websites looked in different browsers throughout history
- **[Browser Wars](https://en.wikipedia.org/wiki/Browser_wars)** - Wikipedia article on the historical competition between browsers

## Performance & Comparison Resources
- **[Speedometer 3.0](https://browserbench.org/Speedometer3.0/)** - Modern browser performance benchmark
- **[Browser Scope](https://www.browserscope.org/)** - Community-driven project for tracking browser functionality
- **[Browser Frame](https://browserframe.com/)** - Create beautiful browser mockups for screenshots
- **[Browser Hack](https://browserhacks.com/)** - Extensive list of browser-specific CSS and JavaScript hacks

## Unique Browser Tools
- **[Browser Calculator](https://www.browsercalculator.com/)** - Calculate a browser's CSS unit values in pixels
- **[VisBug](https://chrome.google.com/webstore/detail/visbug/cdockenadnadldjbbgcallicgledbeoc)** - Open source web design debug tools built with JavaScript
- **[Browserslist](https://browsersl.ist/)** - Share target browsers between different front-end tools
- **[Browser Rater](https://www.browserrater.com/)** - Test if visitors see your site correctly in their browsers
- **[Browser Stack Responsive](https://www.browserstack.com/responsive)** - Test your website's responsiveness on different screen sizes
- **[Browser Calories](https://browsercalories.info/)** - Monitor the size and performance impact of JavaScript libraries

## Learning Resources
- **[Inside look at modern web browser](https://developers.google.com/web/updates/2018/09/inside-browser-part1)** - Four-part series by Google on how browsers work
- **[HTML5 Rocks](https://www.html5rocks.com/en/)** - Resources for open web developers
- **[Chrome Experiments](https://experiments.withgoogle.com/collection/chrome)** - Creative experiments for the browser
- **[WebGL Samples](https://webglsamples.org/)** - Sample apps that demonstrate the use of WebGL

## Useful Extensions & Tools
- **[SingleFile](https://github.com/gildas-lormeau/SingleFile)** - Save a complete web page as a single HTML file
- **[Web Archive](https://github.com/dessant/web-archives)** - View archived and cached versions of web pages
- **[Night Eye](https://nighteye.app/)** - Dark mode for any website with customizable settings
- **[Hoppscotch](https://hoppscotch.io/)** - A free, fast, and beautiful API request builder (browser-based)
- **[Extension Source Downloader](https://github.com/Rob--W/crxviewer)** - View source code of Chrome, Firefox and Edge extensions
- **[12ft Ladder](https://12ft.io/)** - Bypass paywalls by removing the paywall overlay from news sites

## Browser Experiments & Next-Gen Features
- **[Browser Preview for VSCode](https://marketplace.visualstudio.com/items?itemName=auchenberg.vscode-browser-preview)** - A real browser preview inside VSCode
- **[WebAssembly Studio](https://webassembly.studio/)** - Learn and experiment with WebAssembly
- **[Chrome Experiments](https://experiments.withgoogle.com/collection/chrome)** - Creative experiences for the browser
- **[Web Components](https://www.webcomponents.org/)** - A collection of web components for modern browsers

## Browser Security Resources
- **[Browser Exploitation Framework (BeEF)](https://beefproject.com/)** - Security tool focusing on web browsers
- **[Browser Security Handbook](https://code.google.com/archive/p/browsersec/wikis/Main.wiki)** - Comprehensive guide to browser security
- **[Hackvertor](https://hackvertor.co.uk/public)** - Tool that helps with encoding/decoding data for security testing

# Browser Descriptions

## [Arc](https://arc.net/)
A newer browser from The Browser Company, Arc is designed with a focus on creativity and productivity. Its interface is radically different, emphasizing workspace organization and collaboration through features like tab management with cards and folders. Arc's experimental design has garnered attention, particularly among tech enthusiasts and designers, but it's still in its early stages, and some users find its non-traditional UI challenging. Its approach offers a fresh take, but adoption is currently niche

[Arc Boosts](https://arcboosts.com/boosts) - Boosts (Extensions) for Arc Browser


## [Brave](https://brave.com/)
Brave's big selling point is privacy. It blocks ads and trackers by default and even lets you earn cryptocurrency by opting into seeing some non-intrusive ads. That said, Brave has had some controversies, like when they added affiliate links into address bars without telling users. But if you want a faster, more private browsing experience and don't mind their crypto ecosystem, Brave is a solid choice


## [Chromium](https://www.chromium.org/)
Chromium is the open-source backbone for a lot of popular browsers out there. It's lightweight, fast, and always up-to-date with the latest web standards, but it doesn't come with some of the fancy stuff you get with Chrome, like automatic updates or built-in Google services. Some people think it gives too much power to Google, but it's also what makes a lot of your favorite browsers tick


## [Google Chrome](https://www.google.com/chrome/)
Chrome is basically the go-to browser for most people. It's fast, works with all your Google stuff, and has a massive library of extensions. But it does have a downside: it can be a bit of a memory hog and isn't great for privacy since Google collects a lot of data. Still, it's super reliable and gets the job done


## [Falkon](https://www.falkon.org/)
Falkon is a lightweight, open-source browser built with simplicity in mind. It's perfect for older systems or people who just want a browser that doesn't hog resources. It doesn't get updated as often as other browsers, and its support for extensions is pretty limited. It's a nice option if you're on Linux or just want something super lightweight


## [Kiwi Browser](https://kiwibrowser.com/)
Kiwi Browser is a fast, Chromium-based browser designed specifically for Android. One of its standout features is its ability to run Chrome desktop extensions on mobile, a rare capability among mobile browsers. It also includes an ad blocker, crypto-jacking protection, and dark mode. While Kiwi offers a highly customizable browsing experience with a clean interface, it doesn't get as frequent updates as some other browsers, which can occasionally lead to security concerns. It's a favorite for Android users who want a more customizable and private alternative to Chrome without compromising on speed and features


## [Microsoft Edge](https://www.microsoft.com/edge)
Edge was rebuilt on Chromium in 2020 after a less successful run on Microsoft's proprietary engine. It's appreciated for its seamless integration with Windows and Microsoft services like OneDrive and Office 365. Edge includes innovative features like Collections (for organizing content) and vertical tabs. However, some users are wary of Microsoft's data collection practices, and it faces competition from other privacy-focused alternatives. Edge's mandatory presence on Windows and persistent prompts urging users to switch from other browsers have sparked controversy among some users


## [Opera](https://www.opera.com/)
Opera stands out for its array of built-in features, including an ad blocker, free VPN, cryptocurrency wallet, and a sidebar for quick access to social media and messaging apps. While Opera's unique features make it popular with power users, some in the community question the browser's future after its acquisition by a Chinese consortium in 2016, raising concerns over privacy and data sharing. Opera has a loyal following but faces stiff competition from other Chromium-based browsers


## [Opera GX](https://www.opera.com/gx)
Opera GX is like Opera, but for gamers. It's got a slick design, with features to limit how much CPU or RAM it uses, so it doesn't slow down your games. There are integrations with Twitch and Discord too. Some think it's a bit gimmicky, but if you're into gaming and want a browser that matches your aesthetic, it's worth a try, but be aware that it mines data as well


## [Vivaldi](https://vivaldi.com/)
Vivaldi is for the tinkerers who love to customize everything. You can control every aspect of this browser, from how the tabs work to the layout and appearance. It's also privacy-focused and doesn't track you. But all those features can make it feel a bit overwhelming if you just want a simple, easy-to-use browser. It's a favorite for power users who want things their way


## [Yandex Browser](https://browser.yandex.com/)
Developed by Russia's largest tech company, Yandex, this Chromium-based browser includes a variety of features like built-in ad blocking, Turbo Mode for slow connections, and a distinctive "Alice" voice assistant. While it offers a streamlined and efficient browsing experience, the Yandex Browser is controversial due to its association with Russia, raising privacy and data security concerns, especially for users outside of the country. It also receives mixed reviews in Western markets, though it's quite popular in Russia and nearby regions


## [Mozilla Firefox](https://www.mozilla.org/firefox)
Firefox is an open-source browser developed by Mozilla with a long history of championing web standards and user privacy. It offers robust customization options and strong security features, including tracking protection and a growing number of privacy-focused add-ons. However, recent updates have raised concerns about data collection practices, with some users questioning Mozilla's commitment to privacy following changes to their data policies. Despite these concerns, Firefox remains more privacy-friendly than mainstream options like Chrome. It features excellent developer tools and a loyal user community.

[Firefox CSS Store](https://firefoxcss-store.github.io) - Store that includes various themes for your Firefox browser <br>
[Arc UI](https://github.com/dxdotdev/arc-ui) - A cool Firefox theme that makes you feel like you are using Arc Browser

## [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
A special version of Firefox tailored specifically for web developers. It includes cutting-edge development tools and experimental features, allowing developers to test against upcoming web standards and browser capabilities. Firefox Developer Edition has a distinct dark theme and comes with developer tools enabled by default, including a powerful CSS Grid inspector, JavaScript debugger, and responsive design mode. It receives updates before they reach the regular Firefox release, making it ideal for web professionals who want to stay ahead of browser technologies.

## [Firefox Nightly](https://www.mozilla.org/en-US/firefox/channel/desktop/#nightly)
Firefox Nightly is the bleeding-edge development version of Firefox, updated daily with the latest code changes. It's designed for early testing of new features and improvements before they reach the Developer Edition or Beta channels. Nightly builds are experimental and may sometimes be unstable, but they give users an early look at upcoming Firefox features and allow Mozilla to gather feedback on new implementations. Using Nightly is a way to contribute to Firefox development by reporting bugs and issues with emerging features.

## [Floorp](https://floorp.app/en)
A privacy-focused fork of Firefox, Floorp is developed by a Japanese student group aiming to create a more user-friendly and lightweight version of Firefox. It offers a minimalist interface and removes some of the telemetry features found in the original Firefox. Although relatively unknown, it's gaining traction among users seeking a streamlined, privacy-first browsing experience with familiar Firefox features


## [Libre Wolf](https://librewolf.net/)
LibreWolf is like Firefox, but even more hardcore about privacy. It strips out all telemetry (data collection) and enforces stronger privacy settings. It's great for people who want the security of Firefox without any of the tracking. The downside is it doesn't always get updates as fast, and the setup can be a bit tricky for new users


## [Safari](https://www.apple.com/safari/)
Safari is Apple's default browser for macOS and iOS, known for its speed, energy efficiency, and tight integration with the Apple ecosystem. It prioritizes privacy with features like Intelligent Tracking Prevention (ITP), which blocks third-party cookies and trackers. Safari is also optimized for Apple hardware, making it one of the fastest and most battery-efficient browsers on Macs and iPhones. However, its customization options and support for extensions are more limited compared to Chromium-based browsers. Safari's exclusivity to Apple devices also limits its reach, but it remains the go-to for many Mac and iOS users who value privacy and performance


## [Tor Browser](https://www.torproject.org/download/)
Tor Browser is all about anonymity. It routes your traffic through the Tor network, making it much harder to track what you're doing online. It's a go-to for journalists, activists, and anyone in high-risk areas where privacy is critical. The downside is it's slower than other browsers because of the way it handles your traffic. It's great for privacy, but not perfect for everyday browsing if speed is a priority


## [Mullvad Browser](https://mullvad.net/en/browser)
Developed in partnership with the creators of Mullvad VPN, the Mullvad Browser is a Tor-based browser designed to reduce tracking and increase anonymity, without necessarily routing traffic through the Tor network. It's popular among VPN users seeking a privacy-focused browser without the full overhead of the Tor network. It's still relatively new, and adoption is primarily among those already familiar with Mullvad's privacy products


## [Waterfox](https://www.waterfox.net/)
Waterfox started out as a way to keep using old Firefox extensions after Firefox dropped support for them. It's all about performance and privacy, without any of Mozilla's telemetry. But ever since it was bought by System1, which is involved in advertising, some users have questioned its future direction. Still, it's popular among those who miss the old Firefox experience


## [Pale Moon](https://www.palemoon.org/)
Pale Moon is a Firefox fork that diverged significantly from its parent. It uses its own rendering engine (Goanna) and focuses on efficiency and customization while maintaining support for traditional Firefox extensions. Pale Moon is popular among users who prefer a classic browser experience with low resource usage, but it's criticized for lagging behind in modern web standards and security features compared to mainstream browsers. Some find its development pace slower and its ecosystem smaller than Firefox or Chromium-based browsers

## [Min Browser](https://minbrowser.org/)
Min Browser is a minimalist, open-source browser designed to reduce distractions and improve focus. With a clean interface that eliminates clutter, Min emphasizes speed and simplicity. It includes built-in ad blocking, a "focus mode" that hides distracting content, and a unique "tasks" feature for organizing related tabs. Min is lightweight and privacy-focused, blocking trackers by default. It's ideal for users who want a streamlined browsing experience without the bloat of mainstream browsers.

## [DuckDuckGo Browser](https://duckduckgo.com/app)
The DuckDuckGo Browser is a privacy-focused mobile browser from the creators of the DuckDuckGo search engine. It automatically blocks third-party trackers, forces HTTPS connections when available, and includes a one-tap data clearing button. The browser features a privacy grading system for websites and built-in protection against email tracking. Available on iOS and Android, it offers a straightforward, privacy-centric browsing experience without complicated settings or configurations.

## [Bromite](https://www.bromite.org/)
Bromite is a Chromium-based browser for Android with a strong focus on privacy and ad blocking. It removes Google-specific features and tracking code from Chromium while maintaining compatibility with most websites. Bromite includes built-in advanced ad blocking capabilities, DNS-over-HTTPS support, and anti-fingerprinting measures. It's popular among privacy-conscious Android users who want a Chrome-like experience without Google's tracking elements.

## [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/)
Mull is a privacy-hardened fork of Firefox for Android, available through F-Droid. It incorporates security and privacy enhancements from the Tor Browser and hardening patches from GrapheneOS. Mull removes telemetry and tracking components, and comes pre-configured with privacy-focused settings. It supports Firefox add-ons, allowing users to further enhance privacy with extensions like uBlock Origin. It's popular among users of privacy-focused Android distributions.

## [Firefox Focus](https://www.mozilla.org/en-US/firefox/browsers/mobile/focus/)
Firefox Focus is Mozilla's privacy-focused mobile browser that automatically blocks a wide range of online trackers by default. It features a prominent "Erase" button that instantly clears browsing history, cookies, and cached data. Focus is designed for quick, private browsing sessions rather than as a primary browser. With a lightweight interface and minimal features, it emphasizes speed and simplicity while maintaining strong privacy protections.

## [Onion Browser](https://onionbrowser.com/)
Onion Browser is the leading open-source Tor-powered browser for iOS. It routes your web traffic through the Tor network to protect your anonymity and bypass censorship. Endorsed by the Tor Project, it offers similar privacy protections to the desktop Tor Browser, including protection against tracking and fingerprinting. Onion Browser is essential for iOS users who need strong privacy protections or access to blocked content in restricted regions.

## [Sidekick Browser](https://www.meetsidekick.com/)
Sidekick is a productivity-focused Chromium-based browser designed for professionals who work extensively with web applications. It features a vertical sidebar with app icons for quick access to frequently used web apps, dedicated workspaces for different projects or contexts, and built-in session management. Sidekick reduces memory usage by suspending inactive tabs while keeping web apps accessible. It's popular among knowledge workers and professionals who rely on multiple web services.

## [Thorium](https://thorium.rocks/)
Thorium is a Chromium fork focused on performance and privacy. It removes Google's telemetry and services while adding performance optimizations and memory management improvements. Thorium maintains compatibility with Chrome extensions while offering a more lightweight experience. It uses enhanced compiler optimizations to improve speed and responsiveness. Thorium is gaining popularity among performance-conscious users who want a more efficient Chrome alternative without Google's tracking components.

## [Orion](https://kagi.com/orion/)
Orion is a WebKit-based browser for macOS and iOS developed by Kagi. It combines Safari's rendering engine with support for Chrome and Firefox extensions, offering a unique hybrid approach. Orion emphasizes performance, privacy, and battery efficiency while providing the extension ecosystem that Safari lacks. Still in active development, it's gaining attention for its innovative approach to combining WebKit's efficiency with the flexibility of browser extensions from other platforms.

## [Zen Browser](https://zen-browser.app/)
Zen Browser is a privacy-focused fork of Firefox designed to enhance both security and the browsing experience. It's built on Firefox ESR (Extended Support Release) with performance optimizations and security enhancements. Zen Browser strips out telemetry and data collection features from Firefox while implementing stronger privacy defaults. It includes built-in content blocking and anti-fingerprinting measures. The browser maintains compatibility with Firefox extensions while offering a more private experience out of the box. Zen Browser is ideal for users who appreciate Firefox's engine and features but want stronger privacy protections without needing to modify about:config settings manually.
