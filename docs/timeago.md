# appup-timeago 

Appup Timeago 

## props 

- `datetime` ***String*** (*required*) `default: ''` 

  datetime in DD/MM/yyyy HH:mm:ss format 

- `format` ***String*** (*optional*) `default: 'DD/MM/YYYY HH:mm:ss'` 

  Format in which datetime is provided.
  
  <b>Note: </b> Component will not render proper output if format provided doesn't match with the provided datetime 

- `autoupdate` ***Number*** (*optional*) `default: 60` 

  Seconds after which the component will be refereshed and shows updated timeago 

- `max-auto-update` ***Number*** (*optional*) `default: 300` 

  Max seconds after which component will not be refreshed to show the updated timeago 

## data 

- `moreThenYear` 

**initial value:** `[object Object]` 

- `notValidDatetime` 

**initial value:** `[object Object]` 

- `providedDatetime` 

**initial value:** `[object Object]` 

