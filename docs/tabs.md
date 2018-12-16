# appup-tabs 

Tab component to group content with only one displayed at a time 

## slots 

- `default` 

## props 

- `items` ***[object Object]*** (*required*) 

  Items are array of objects which should be displayed as tabs with content within them.
  
  Content within an Item should be appup-form
  
  Schema:
  
  `
  [
  {
  id: 'ID of the Accordion item',
  label:'Label of the accordion item',
  content: {
  ... FormField Schema
  }
  }
  ]
  ` 

- `position` ***[object Object]*** (*optional*) `default: 'top'` 

  Setup position of menu
  
  `top, bottom, left, right` 

- `type` ***[object Object]*** (*optional*) 

  Set style of tab button
  
  `tab, button` 

- `set-width` ***[object Object]*** (*optional*) 

  Set width for tab menu
  
  `w-25, w-50` 

- `justified` ***Boolean*** (*optional*) 

  Set css justified for tab header
  
  `true, false` 

- `justify-content` ***String*** (*optional*) 

  Set css justified for tab header
  
  `start, end, center, between, around` 

## data 

- `tabIndex` 

**initial value:** `0` 

- `listTab` 

**initial value:** `[object Object]` 

- `end` 

**initial value:** `[object Object]` 

- `vertical` 

**initial value:** `[object Object]` 

- `pills` 

**initial value:** `[object Object]` 

- `justify_content` 

**initial value:** `[object Object]` 

## methods 

- `activeTab()` 

  }, 

