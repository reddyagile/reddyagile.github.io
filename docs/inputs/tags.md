# appup-tags 

Appup Tag component to load static options or dynamic options from API call

Tags values are always name based only. Values sent will be comma seperated list of labels received in options.

If a new tag is added, then its name will be added to the selected labels. 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `options` ***Array*** (*optional*) 

  Options that should be displayed in the dropdown
  
  Array should include objects with label & value properties 

- `state` ***Boolean*** (*optional*) `default: null` 

  Validation state of the component 

- `value` ***[object Object]*** (*optional*) 

  Value for v-model binding. Not to be binded directly 

- `url` ***String*** (*optional*) 

  Url from which data should be populated in dropdown 

- `placeholder` ***String*** (*optional*) `default: ''` 

  Placeholder if needed 

- `key_value` ***String*** (*optional*) 

- `key_label` ***String*** (*optional*) 

## data 

- `dropdownItems` 

**initial value:** `[object Object]` 

- `selectedObjects` 

**initial value:** `[object Object]` 

- `selectedValues` 

**initial value:** `[object Object]` 

## computed properties 

- `isInvalid` 

   **dependencies:** `state`, `state` 


## methods 

- `addTag(newTag)` 

  Method to be invoked on adding a new tag 

