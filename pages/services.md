---
layout: list
title: Services
description: "A selection of our services."
permalink: "/services/"
header_transparent: true

hero:
  enabled: true
  heading: "Services"
  sub_heading: "A selection of our services."
  text_color: "#FFFFFF"
  background_color: "#222831"
  background_gradient: true
  #background_image: "/assets/images/gen/home/HL_back.png"
  #background_image_blend_mode: multiply # "overlay", "multiply", "screen"
  fullscreen_mobile: true
  fullscreen_desktop: true
#  height: "500px"
  buttons:
    enabled: true
    list:
      - text: "Contact Us"
        url: "/contact"
        external: false
        fa_icon: false
        size: large # "small", "normal", "large"
        outline: false
        style: "light" # "light", "dark", "primary"
      - text: "About us"
        url: "/about"
        external: false
        fa_icon: false
        size: large
        outline: true
        style: "light"

grid:
  collection: "services"
  sort_by: "weight" # "date", "weight"
  columns: 3
  prevent_click: false

intro:
  enabled: false
  align: left
  image: false
  heading: "A Full Service Agency"
  sub_heading: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget sapien in elit semper accumsan. Pellentesque accumsan ut tortor eu varius. Sed id tincidunt massa, ut egestas orci."
  buttons:
    enabled: false
    list:
      - text: "About Us"
        url: "/about/"
        external: false
        fa_icon: false
        size: normal

outro:
  enabled: true
  align: center
  image: false
  heading: "Ready to get started?"
  sub_heading: "Contact us today for a free quote!"
  buttons:
    enabled: true
    list:
      - text: "Get A Quote"
        url: "/contact"
        external: false
        fa_icon: false
        size: normal
        style: light
---
