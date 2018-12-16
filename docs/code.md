# appup-code 

Appup Code component to provide code in Html, Js or CSS 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `type` ***String*** (*optional*) `default: 'html'` 

  Type of Alert Message
  
  `html, js, css` 

- `value` ***String*** (*required*) 

  Code that should be displayed in the Code Editor 

## data 

- `cmOptions` 

**initial value:** `[object Object]` 

- `editorCode` 

**initial value:** `[object Object]` 

## computed properties 

- `codemirror` 

   **dependencies:** `$refs` 


## events 

- `input` 

  console.log('Code :: this is new code', newCode) 

## methods 

- `onCmReady(cm)` 

- `onCmFocus(cm)` 

- `onCmCodeChange(newCode)` 

