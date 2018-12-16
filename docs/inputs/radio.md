# appup-radio 

Appup Radio - Can be used for single or group radios 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `options` ***Array*** (*optional*) 

  Options that should be displayed in radio group
  
  Array should include objects with label & value properties 

- `state` ***Boolean*** (*optional*) `default: null` 

  Validation state of the component 

- `value` ***[object Object]*** (*optional*) 

  Value for v-model binding. Not to be binded directly 

## data 

- `radioGroupOptions` 

**initial value:** `[object Object]` 

- `selected` 

**initial value:** `[object Object]` 

## events 

- `input` 

- `radioChange` 

## methods 

- `onSelect(selected)` 

