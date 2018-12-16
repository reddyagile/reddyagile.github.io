# appup-multiselect 

Appup Multiselect to load static options or dynamic options from API call 

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


