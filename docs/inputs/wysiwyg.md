---
layout: default
title: Quill JS
parent: Inputs
nav_order: 12
---

# wysiwyg 

import "quill/dist/quill.bubble.css"; 

## props 

- `id` ***String*** (*optional*) `default: null` 

- `surl` ***String*** (*optional*) `default: null` 

- `value` ***[object Object]*** (*optional*) 

- `state` ***Boolean*** (*optional*) `default: null` 

## data 

- `content` 

**initial value:** `[object Object]` 

- `s3Url` 

**initial value:** `''` 

- `aurl` 

**initial value:** `'https://tracklyapp.appup.cloud/trackly/presign?file_name='` 

- `editorOptions` 

**initial value:** `[object Object]` 

## events 

- `input` 

  console.log("this is the content"+this.content); 

## methods 

- `onEditorChange(content)` 

- `onEditorBlur(editor)` 

- `onEditorFocus(editor)` 

- `onEditorReady(editor)` 

