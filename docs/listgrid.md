---
layout: default
parent: Not Using
---
# appup-listgrid 

Appup ListGrid 

## props 

- `id` ***String*** (*optional*) 

  id of the element 

- `default-view` ***String*** (*optional*) `default: ''` 

  Default type is list view or grid view 

- `list-type` ***String*** (*optional*) `default: ''` 

  Type of the table is data table or basic table data 

- `url` ***String*** (*optional*) `default: ''` 

  Fetch data with url 

- `label` ***String*** (*optional*) 

  label for grid item in header 

- `description` ***String*** (*optional*) 

  Description for Grid item 

- `reference` ***String*** (*optional*) 

  Reference for grid item 

- `items` ***Array*** (*optional*) 

  Message to be displayed in the alert 

- `fields-table` ***[object Object]*** (*optional*) 

  Customize the table columns headings 

- `sort-by` ***[object Object]*** (*optional*) 

  Sort by key 

- `sort-desc` ***[object Object]*** (*optional*) 

  Config sort
  
  `true` -> Descending
  `false` -> Ascending 

- `columns` ***Array*** (*optional*) 

  Setup columns table
  `label, type, field, width` 

- `freeze` ***String*** (*optional*) 

  Setup freeze columns 

## data 

- `currentView` 

**initial value:** `[object Object]` 

## methods 

- `switchToListView()` 

- `switchToGridView()` 

