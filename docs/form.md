---
layout: default
title: Form
parent: Using
nav_order: 3
---

# appup-form 

Appup Form component rendering form elements based upon provided schema. Includes validation rules as well.

TODOs:

Reset form elements

Submit form data to API

Testing edit with form data prepopulated

Dynamic element added based on other component selection 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `position` ***String*** (*optional*) `default: 'bottom'` 

  Position of group buttons.
  
  `top`, `bottom` 

- `direction` ***String*** (*optional*) `default: 'left'` 

  Position of group buttons.
  
  `center`, `left`, `right` 

- `preload` ***String*** (*optional*) 

  URL to deserialize the form initially. 

- `submit` ***String*** (*optional*) 

  Submit Workflow ID 

- `name` ***String*** (*optional*) 

  Name of input elements. 

- `url` ***String*** (*optional*) 

  Fetch data with url 

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

- `supported-formats` ***Array*** (*optional*) 

  Supported extension files to be selected when input type is File
  
  Example: ['.jpg', '.pdf', '.docx'] etc.. 

- `disabled` ***Boolean*** (*optional*) 

- `add-element` ***Boolean*** (*optional*) `default: false` 

  Flag to check type of add element or valid the value.
  
  `true, false` 

- `form-tittle` ***String*** (*optional*) 

  form tittle 

## data 

- `form` 

**initial value:** `[object Object]` 

- `typeAlert` 

**initial value:** `'failure'` 

- `showSuccess` 

**initial value:** `false` 

- `showError` 

**initial value:** `false` 

- `messageAlert` 

**initial value:** `''` 

- `inputValue` 

**initial value:** `[object Object]` 

- `formFields` 

**initial value:** `[object Object]` 

- `buttons` 

**initial value:** `[object Object]` 

- `tabs` 

**initial value:** `[object Object]` 

## events 

- `dynamicAddInput` 

## methods 

- `onSubmit(evt)` 

- `onReset(evt)` 

- `onCancel(evt)` 

- `onSuccess(evt, success, response)` 

- `onError(evt, error)` 

- `onInput(e)` 

- `fetchValidationRules(field)` 

- `wait(ms, cb)` 

- `dynamicAddInput(value, id, type)` 

- `showAlertError(error)` 

- `showAlertSuccess(error, transfer)` 

- `designer_save(callback)` 

- `condition(item)` 

- `editorInit()` 

- `getNextTabs(index)` 

- `setActiveTab(tab)` 

- `showInTab(item)` 

