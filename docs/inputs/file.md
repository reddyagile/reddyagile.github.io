# appup-file 

Appup File - Can select any file or specific file with provided extensions

TODO: Testing with API for file upload 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `state` ***Boolean*** (*optional*) `default: null` 

  Validation state of the component 

- `value` ***[object Object]*** (*optional*) 

  Value for v-model binding. Not to be binded directly 

- `placeholder` ***String*** (*optional*) 

  Placeholder to be displayed 

- `supported-formats` ***Array*** (*optional*) 

  Supported formats to be selected by extension
  
  Example: ['.jpg', '.pdf', '.docx'] etc.. 

## data 

- `accept` 

**initial value:** `null` 

- `file` 

**initial value:** `null` 

- `multiple` 

**initial value:** `false` 

## events 

- `input` 

## methods 

- `onSelect(selected)` 

