# appup-table 

Appup Table component which can be used to display list data with custom action. 

## props 

- `id` ***String*** (*optional*) 

  Id of table 

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

- `url` ***[object Object]*** (*optional*) 

  Fetch data with url 

## data 

- `focusItem` 

**initial value:** `[object Object]` 

- `formFieldsTable` 

**initial value:** `[object Object]` 

- `listBtn` 

**initial value:** `[object Object]` 

- `dataTable` 

**initial value:** `[object Object]` 

- `configReq` 

**initial value:** `[object Object]` 

## events 

- `onView` 

- `onEdit` 

- `onDelete` 

## methods 

- `onAction(item, data)` 

