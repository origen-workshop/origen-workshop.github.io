---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_5.jpg
widget1:
  title: "Programme"
  url: 'http://origen-workshop.github.io/programme/'
  image: 
  text: 'Schedule and Accepted Papers'
widget2:
  title: "Invited Speakers"
  url: 'http://origen-workshop.github.io/speakers/'
  image: 
  text: 'Invited Talks and Panelists'
widget3:
  title: "Organizers"
  url: 'http://origen-workshop.github.io/organizers/'
  image: 
  text: 'About the Organizers'
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
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
