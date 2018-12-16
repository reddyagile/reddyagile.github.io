# appup-button 

Appup Button

`TODOs:`
action - invoke some method, open modal window, navigate to page

navigateTo 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `size` ***String*** (*optional*) `default: 'medium'` 

  Size of the button
  
  `small, medium, large` 

- `button-style` ***String*** (*optional*) `default: 'primary'` 

  Style varient of the button
  
  `primary, seconday, success, warning, danger` 

- `label` ***String*** (*optional*) `default: ''` 

  Lavel to be displayed for the button 

- `tooltip` ***String*** (*optional*) `default: ''` 

  Tooltip to be displayed when mouseover on it 

- `icon` ***String*** (*optional*) `default: ''` 

  Fontawesome icon name to be provided 

- `type` ***String*** (*optional*) `default: 'button'` 

  Type of the button
  
  `button, submit, reset` 

- `disabled` ***Boolean*** (*optional*) `default: false` 

  If the button should be disabled or not 

- `navigate-to` ***String*** (*optional*) `default: ''` 

  Page/Url it should be navigated to
  
  `
  Provide url with http / https
  
  Provide name of the Route to which we should be navigated to
  ` 

- `workflow` ***String*** (*optional*) `default: ''` 

## data 

- `buttonSize` 

**initial value:** `[object Object]` 

- `buttonVarient` 

**initial value:** `[object Object]` 

- `buttonType` 

**initial value:** `[object Object]` 

## events 

- `click` 

## methods 

- `onButtonClick()` 

