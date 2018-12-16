# appup-alert 

Appup Alert component which can be used to display success error messages 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `show` ***Boolean*** (*required*) `default: false` 

  Flag to show the alert or not
  
  `true, false` 

- `message` ***String*** (*required*) 

  Message to be displayed in the alert 

- `alert-type` ***String*** (*optional*) `default: 'success'` 

  Type of Alert Message
  
  `info, warn, success, failure` 

- `dismiss-count-down` ***Number*** (*optional*) `default: 5` 

  Time to hide alert 

- `count-down` ***Boolean*** (*optional*) `default: true` 

  Automatic hide alert after dismissCountDown time 

## data 

- `type` 

**initial value:** `[object Object]` 

- `showAlert` 

**initial value:** `[object Object]` 

## events 

- `dismissed` 

  Dismissed event. 

## methods 

- `dismissCallback()` 

