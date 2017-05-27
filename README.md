# tinymce-plugin_image + zoom

add Zooming check BOX  
 Addition of **Zooming check box**   
`<img ....>`  
  to  
`<a class="zoom" href="...." rel="zoom-image"><img ....></a>`  

## install ##
image_zoom/*.* --> tinymce/plugins/image_zoom/*.*  

## Edit init file ##
```
  plugins: [
    ....,
    "image ････",
    ････
  ],
  ```  
  
  to
```  
  plugins: [
    ....,
    "image ････",
    ････
    ,"image_zoom"
  ],

  external_plugins: {
    ...,
    'image_zoom': 'http:// your web site path  /tinymce/plugins/image_zoom/plugin.min.js',
    ...
  }
```
 `toolbar Do not change the toolbar`  
   
 ### Tested ### 
 CDN(cdn.tinymce.com) and local
