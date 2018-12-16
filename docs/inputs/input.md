---
layout: default
title: Input
parent: Inputs
nav_order: 1
---

# appup-input 

Appup Input - The single component which should be used to render any form element for

text, datepicker, password, textarea,code, editor, radio, checkbox, dropdown etc.. 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `name` ***String*** (*optional*) 

  Name of input elements. 

- `type` ***String*** (*optional*) `default: 'text'` 

  The type attribute specifies the type of <strong>input</strong> element to display.
  
  <var>text, password, email, number,url, tel</var>
  <br/><var>date, time, datetime, daterange</var>
  <br/><var>radio, checkbox, textarea, hidden, code, editor</var>
  <br/><var>dropdown, multiselect, tags</var> 

- `placeholder` ***String*** (*optional*) 

  The placeholder attribute specifies a short hint that describes the expected value of an input field. 

- `value` ***[object Object]*** (*optional*) 

  Model Object that should be passed to the input 

- `options` ***Array*** (*optional*) 

  Options for Dropdown, Radio & Checkbox 

- `state` ***Boolean*** (*optional*) `default: null` 

  State of the input field based upon validation rules
  
  false - highlights the field in red
  <br/>true - highlights the field in green
  <br/>null - nothing 

- `url` ***String*** (*optional*) 

  Url from which data should be populated in the input field
  
  Applicable for appup-dropdown, appup-multiselect, appup-tags 

- `supported-formats` ***Array*** (*optional*) 

  Supported extension files to be selected when input type is File
  
  Example: ['.jpg', '.pdf', '.docx'] etc.. 

- `disabled` ***Boolean*** (*optional*) 

## data 

- `inputValue` 

**initial value:** `[object Object]` 

## computed properties 

- `isDateComponent` 

   **dependencies:** `type`, `type`, `type`, `type` 


## events 

- `input` 

- `dynamicAddInput` 

## methods 

- `onInput(value)` 

- `dynamicAddInput(value, id, type)` 

