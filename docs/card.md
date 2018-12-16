---
layout: default
title: Card
parent: Using
nav_order: 1
---

# appup-card 

Appup Gridview component which can be used to display Grid items 

## slots 

- `sections` Slot of sorted Data. If key was given, it will have key, array or just array 

- `section` Slot for normal data 

- `category-header` 

- `card` 

- `category-header` 

- `card` 

## props 

- `url` ***String*** (*optional*) 

  Fetch data with url 

- `actions` ***Array*** (*optional*) 

  Action items for grid item
  
  'view','edit','delete' 

- `preload` ***String*** (*optional*) 

  URL to deserialize the grid initially. 

- `section` ***Boolean*** (*optional*) `default: false` 

## data 

- `data` 

**initial value:** `[object Object]` 

- `sortedData` 

**initial value:** `[object Object]` 

- `sortKey` 

**initial value:** `''` 

- `search` 

**initial value:** `null` 

- `delete_key` 

**initial value:** `null` 

## methods 

- `clickAction(item, action)` 

- `filter()` 

- `refresh()` 

