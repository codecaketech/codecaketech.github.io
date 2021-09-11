---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: back.jpg
widget1:
  title: "Blogs & Tricks"
  url: '/blog/'
  image: widget-1-302x182.jpg
  text: '<em>Codecake</em> offers a collection of random yet powerful tricks for your day-to-day coding horrors. These are random but can be life-saving if you are building something unique.'
widget2:
  title: "Java Jungle"
  url: '/java/'
  image: header_roadmap_3.jpg
  text: 'Java Jungle gets its name from the idea that it is a jungle of totally random java utility codes on topics I spent hours to get done. '
widget3:
  title: "Utility Tools"
  url: '/utility/'
  image: header_unsplash_1.jpg
  text: '<em>CodeCake</em> also offers mostly language independent (sometimes, lucky-to-find) guide for useful tools.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: /contact/
  text: Inform me about new updates and features ›
  style: success
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
