---
layout: default
title: Select
parent: Inputs
nav_order: 2
---

# appup-dropdown 

Appup Dropdown to load static options or dynamic options from API call

TODOs:

Dynamic Options from API call 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `name` ***String*** (*optional*) 

- `options` ***Array*** (*optional*) 

  Options that should be displayed in the dropdown
  
  Array should include objects with label & value properties 

- `state` ***Boolean*** (*optional*) `default: null` 

  Validation state of the component 

- `value` ***[object Object]*** (*optional*) 

  Value for v-model binding. Not to be binded directly 

- `url` ***String*** (*optional*) 

  Url from which data should be populated in dropdown 

- `key_value` ***String*** (*optional*) 

- `key_label` ***String*** (*optional*) 

- `add-element` ***Boolean*** (*optional*) `default: false` 

  Flag to check type of add element or valid the value.
  
  `true, false` 

## data 

- `dropdownItems` 

**initial value:** `[object Object]` 

- `selected` 

**initial value:** `[object Object]` 

## events 

- `input` 

- `dropdownChange` 

## methods 

- `onSelect(selected)` 

- `loadData()` 

