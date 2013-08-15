### Inline SVG+CSS Sharing Icons

I made this in order to avoid using the slow and/or poorly optimized sharing buttons from AddThis or ShareThis. It provides sharing buttons for four of the major social websites (Twitter, Facebook, Google+ and StumbleUpon) in inline SVG and CSS — not a lick of Javascript.

Simply cut and paste the CSS into your existing CSS file and the HTML into your web page! This code adds absolutely *zero* HTTP requests to your site and only weighs 6k in the standard version. That means a faster website.

You can see this code in action on the *[Multiplex](http://www.multiplexcomic.com)* website. (I’m using different opacity levels for the rollover states, but it’s essentially the same.)

This code is in the public domain. Do what you want with it; I don't care. I didn't design the icons; I just turned them into SVG. The SVG was optimized with [Peter Collingridge's Javascript SVG Editor](http://petercollingridge.appspot.com/svg-editor) and then edited to add the rollover and mousedown states.

[This entry on Stack Overflow](http://stackoverflow.com/questions/15074566/open-source-alternative-to-addthis-addtoany-sharethis-etcfor-social-bookmarking) should help you customize the sharing links as needed.

*UPDATED 7/16/13: I’ve added an alternate HTML file using base64-encoded PNG fallbacks for those of you who care to support janky browsers that don’t like inline SVG. While regular PNG images would work fine, using base64-encoded PNGs avoids the additional HTTP request(s) they would generate, even in browsers using the SVG versions.*

*[Web Coder Tools’ Online image to base64 converter](http://webcodertools.com/imagetobase64converter/Create) was used to encode the PNG fallbacks.*

— Gordon McAlpin

**UPDATE (8/15/13):** I’ve adjusted the markup slightly to address bugs with older IE versions, specifically removing the XML namespace attribute and separating the closing tag from self-closing SVG elements (per [Stuntbox’s “Making Inline SVG Play Nice in Legacy IE” post](http://stuntbox.com/blog/2013/06/bulletproof-inline-svg/)).

I’ve also moved the opacity to the CSS on all versions, because I found that having multiple instances of the share_icons on one page would conflict with each other (this was probably because of the id tag, but it also cuts down the size of the [non-cacheable] inline code a little more).