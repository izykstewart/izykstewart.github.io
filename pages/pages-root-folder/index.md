---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

header:
  title: Isaac Stewart
  image_fullwidth: header_unsplash_12.jpg
#  caption: Artist/Author
#  caption_url: http://isaacstewart.com
widget1:
  title: "Stormlight Gallery"
  url: 'https://izykstewart.github.io/gallery/stormlight/'
  image: stormlight-303x182.jpg
  text: "Adding art to this website little by little. Here's some stuff I did for The Stormlight Archive."
widget2:
  title: "Mistborn Gallery"
  url: 'https://izykstewart.github.io/gallery/mistborn/'
  image: mistborn-303x182.jpg
  text: "Adding art to this website little by little. Here's some stuff I did for The Mistborn Saga."
widget3:
  title: "Map Resources"
  url: 'https://izykstewart.github.io/resources/'
  image: map-resources-303x182.jpg
  text: "I've written a few blog posts and done a few interviews you might find interesting."
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
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
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
