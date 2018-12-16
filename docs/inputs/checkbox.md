---
layout: default
title: Checkbox
parent: Inputs
nav_order: 4
---


# appup-checkbox 

Appup Checbox - Can be used for single or group checboxes 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `options` ***Array*** (*optional*) 

  Options that should be displayed in checkbox group
  
  Array should include objects with label & value properties 

- `state` ***Boolean*** (*optional*) `default: null` 

  Validation state of the component 

- `value` ***[object Object]*** (*optional*) 

  Value for v-model binding. Not to be binded directly 

## data 

- `checkboxGroupOptions` 

**initial value:** `[object Object]` 

- `selected` 

  Must be an array reference! 

**initial value:** `[object Object]` 

## events 

- `input` 

- `checkboxChange` 

## methods 

- `onSelect(selected)` 

