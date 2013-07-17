### Inline SVG+CSS Sharing Icons

I made this in order to avoid using the slow and/or poorly optimized sharing buttons from AddThis or ShareThis. If you cut and paste the CSS into your existing CSS file and the HTML into your web page, it adds absolutely zero HTTP requests to your site.

You can see this code in action on the *[Multiplex](http://www.multiplexcomic.com)* website. (I’m using different opacity levels for the rollover states, but it’s basically the same.)

This code is in the public domain. Do what you want with it; I don't care. I didn't design the icons; I just turned them into SVG. The SVG was optimized with [Peter Collingridge's Javascript SVG Editor](http://petercollingridge.appspot.com/svg-editor) and then edited to add the rollover and mousedown states.

[Web Coder Tools’ Online image to base64 converter](http://webcodertools.com/imagetobase64converter/Create) was used to encode the PNG fallbacks.

[This entry on Stack Overflow](http://stackoverflow.com/questions/15074566/open-source-alternative-to-addthis-addtoany-sharethis-etcfor-social-bookmarking) should help you customize the sharing links as needed.

*UPDATED 7/16/13: I’ve added base64-encoded PNG fallbacks for those of you who care to support janky browsers that don’t like inline SVG.*

— Gordon McAlpin