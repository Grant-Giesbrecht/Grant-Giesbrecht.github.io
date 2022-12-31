---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Blog & Portfolio"
  url: 'http://Grant-Giesbrecht.github.io/aboutme/'
  image: AboutMe_Thumbnail.jpg
  text: 'Thanks for visiting my homepage! If youd like to learn more about me and my goals, feel free to check out my about page.'
widget2:
  title: "Homebrew CPU Update"
  url: 'https://Grant-Giesbrecht.github.io/projects/blinkenrechner/'
  text: 'Heres an overview of my homemade CPU project.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://Grant-Giesbrecht.github.io/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Research Overview"
  url: 'https://grant-giesbrecht.github.io/projects/research summary'
  image: MEQALAC_Thumbnail.jpg
  text: 'Looking for the sparknotes version? Click here for an overview of my past and present research.'
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
