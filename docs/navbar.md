---
layout: default
parent: Not Using
---
# appup-navbar 

Appup Navbar with capabilty to render controls either left or right or both

TODOs:

Actions for navbar controls

Icons are not aligned properly 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `brand-info` ***Object*** (*optional*) 

  Details of the brand that should be shown on the extreme left
  
  {
  name: "",
  link_to: "#",
  image: "https://www.agilecrm.com/img/agilecrmlogo.svg",
  image_alt: "Agile CRM"
  } 

- `left-controls` ***Array*** (*optional*) 

  Controls to be displayed on left-hand side of navigation
  
  `
  [
  {
  type: "link",
  label: "Pages",
  icon: "pages",
  link_to: "#alert"
  },
  {
  type: "link",
  label: "Blocks",
  icon: "dashboard",
  link_to: "#code"
  }
  ]
  ` 

- `right-controls` ***Array*** (*optional*) 

  Controls to be displayed on right-hand side of navigation
  
  `
  [
  {
  type: "dropdown",
  label: "Madan",
  image: "http://agilecrm.dash.sweet-simple.com/assets/img/human01.jpg",
  items: [
  {
  type: "link",
  label: "Profile",
  link_to: "#"
  },
  {
  type: "link",
  label: "Signout",
  link_to: "#"
  }
  ]
  }
  ]
  ` 

- `icon` ***String*** (*optional*) 

## data 

- `navItemActive` 

**initial value:** `false` 

