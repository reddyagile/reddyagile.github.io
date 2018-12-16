---
layout: default
title: Date and Time
parent: Inputs
nav_order: 5
---


# appup-datetime 

Appup DateTime picker with capability to show only date, time or date & time 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `type` ***String*** (*required*) 

  The type attribute specifies the type of <strong>input</strong> element to display.
  
  `date, time, datetime, daterange` 

- `state` ***Boolean*** (*optional*) `default: null` 

  Validation state of the component 

- `value` ***[object Object]*** (*optional*) 

  Value for v-model binding. Not to be binded directly 

## data 

- `date` 

  Initial value 

**initial value:** `[object Object]` 

## computed properties 

- `config` 

  Get more form https://chmln.github.io/flatpickr/options/ 

   **dependencies:** `$emit` 


