---
layout: default
parent: Not Using
---
# appup-grid 

Appup Gridview component which can be used to display Grid items 

## props 

- `id` ***String*** (*optional*) 

  Id of grid 

- `label` ***String*** (*optional*) 

  label for grid item in header 

- `description` ***String*** (*optional*) 

  Description for Grid item 

- `image` ***String*** (*optional*) 

  Image for Grid item 

- `reference` ***String*** (*optional*) 

  Reference for grid item 

- `url` ***String*** (*optional*) 

  Fetch data with url 

- `actions` ***Array*** (*optional*) 

  Action items for grid item
  
  'view','edit','delete' 

- `sort-key` ***String*** (*optional*) 

- `preload` ***String*** (*optional*) 

  URL to deserialize the grid initially. 

- `edit` ***Object*** (*optional*) 

  Edit route based 

- `navigate-to` ***String*** (*optional*) 

- `button-label` ***String*** (*optional*) 

## data 

- `data` 

**initial value:** `[object Object]` 

- `sortedData` 

**initial value:** `[object Object]` 

## methods 

- `getLabel(item)` 

- `getDescription(item)` 

- `getReference(item)` 

- `getImage(item)` 

- `parse()` 

- `clickAction(item, action)` 

