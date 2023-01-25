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
  title: "About Me"
  url: 'http://Grant-Giesbrecht.github.io/aboutme/'
  image: AboutMe_Thumbnail.jpg
  text: "Thanks for visiting my homepage! If you'd like to learn more about me and my goals, feel free to check out my about page."
widget2:
  title: "Homebrew CPU Update"
  url: 'https://Grant-Giesbrecht.github.io/projects/blinkenrechner/'
  text: "My absurd but hopefully interesting hobby project has been to build a computer processor from logic gates. The project has expanded into a fully functioning homebrew 8-bit computer. Checkout the overview video above, or use the button below to see it's project page!"
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://Grant-Giesbrecht.github.io/images/blinken_vid_thumbnail.png" width="302" height="182" alt=""/></a>'
widget3:
  title: "Research Overview"
  url: 'https://grant-giesbrecht.github.io/projects/'
  image: MEQALAC_Thumbnail.jpg
  text: 'Looking for the sparknotes version? Click here for an overview of my past and present research.'
widget4:
   title: "RF Power Amplifier Figure of Merit"
   url: 'https://grant-giesbrecht.github.io/projects/fom/'
	image: fom.png
   text: 'While earning my masters I developed a system of figures of merit to benefit designing RF power amplifiers.'
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
