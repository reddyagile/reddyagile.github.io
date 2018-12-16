---
layout: default
parent: Not Using
---

# appup-accordion 

Accordion component to group content with only one displayed at a time 

## slots 

- `default` 

## props 

- `items` ***Array*** (*required*) `default: [object Object]` 

  Items are array of objects which should be displayed as accordions with content within them.
  
  Content within an Item can be any appup component such as appup-form, data table etc..
  
  Schema:
  
  `
  [
  {
  id: 'ID of the Accordion item',
  label:'Label of the accordion item',
  content: {
  ... FormField Schema
  }
  },
  {
  id: 'ID of the Accordion item',
  label:'Label of the accordion item',
  content: {
  ... datatable Schema
  }
  }
  ]
  ` 

## data 

- `current_view` 

**initial value:** `''` 

