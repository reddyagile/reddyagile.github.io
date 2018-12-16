# appup-imageupload 

Appup Image Uploader - Can upload an image to the provided url 

## props 

- `id` ***String*** (*optional*) 

  Id of input elements. 

- `label` ***String*** (*required*) 

  Id of input elements. 

- `value` ***[object Object]*** (*optional*) 

  Value for v-model binding. Not to be binded directly 

- `size` ***String*** (*optional*) `default: 'medium'` 

  size of the avatar
  
  `ssmall, small, smedium, medium, slarge, large, xlarge` 

- `initial-image` ***String*** (*required*) `default: ''` 

  Initial image that should be displayed when the component loads 

- `url` ***String*** (*required*) 

  URL which should be invoked when the image is uploaded 

## data 

- `src` 

**initial value:** `[object Object]` 

- `imageSize` 

**initial value:** `[object Object]` 

## methods 

- `imageuploaded(res)` 

