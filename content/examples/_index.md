---
title: Showcase
description: "MADLAB Docs websites powered by Hugo Blox."
type: landing



sections:
  - block: hero
    content:
      title: Packages/Libraries
      text: 'View examples from packages and libraries created by the MADLAB group'
      primary_action:
        #icon: brands/x
        text: MADLAB Website
        url: "https://steyvers.socsci.uci.edu/madlab/"
      secondary_action:
        text: Dr. Mark Steyvers (MADLAB P.I.)
        url: https://steyvers.socsci.uci.edu/
    design:
      no_padding: true
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
  - block: collection
    content:
      title: 'MPLib.js'
      text: 'Multiplayer Gaming Library'
      filters:
        folders:
          - examples
        tag: 'mplib'
    design:
      view: card
      spacing:
        padding: ['3rem', 0, '6rem', 0]
  #- block: collection
  #  content:
  #    title: Testing
  #    subtitle: More Test
  #    filters:
  #      folders:
  #        - examples
  #  design:
  #    view: card
  #    spacing:
  #      padding: ['3rem', 0, '6rem', 0]
---
