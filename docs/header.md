# appup-header 

Appup Header with capabilty to render controls either left or right or both

TODOs:

Actions for header controls

Icons are not aligned properly 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `title` ***Object*** (*optional*) 

  Details of the title that should be shown on the extreme left
  
  {
  name: "",
  } 

- `left-controls` ***Array*** (*optional*) 

  Controls to be displayed on left-hand side of header
  
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

  Controls to be displayed on right-hand side of header
  
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

- `navbgcolor` ***String*** (*optional*) `default: 'light'` 

  Style varient of the navbar background color
  
  `primary, seconday, success, warning, danger` 

- `textcolor` ***String*** (*optional*) `default: 'light'` 

  type of the navbar color
  
  `light, dark` 

## data 

- `navItemActive` 

**initial value:** `false` 

- `titleVarient` 

**initial value:** `[object Object]` 

- `titletextcolor` 

**initial value:** `[object Object]` 

