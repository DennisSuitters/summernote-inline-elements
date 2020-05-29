# summernote-inline-elements v0.2

This Plugin adds a Dropdown Summernote toolbar that lets you change add inline HTML Elements, and it was dapted from Adapted from [https://github.com/tylerecouture/summernote-add-text-tags](https://github.com/tylerecouture/summernote-add-text-tags)

### Installation

#### 1. Include JS

Include the following code after Summernote:

```html
<script src="summernote-inline-elements.js"></script>
```

#### 2. Summernote options

```javascript
$('.summernote').summernote({
    toolbar:[
        ['style',['style', 'inline']], // The "Inline" Button
        ['font',['bold','italic','underline','clear']],
        ['fontname',['fontname']],
        ['color',['color']],
        ['para',['ul','ol','paragraph']],
        ['height',['height']],
        ['table',['table']],
        ['insert',['media','link','hr']],
        ['view',['fullscreen','codeview']],
        ['help',['help']]
    ]
});
```

#### 4. Check out our other Summernote Plugins via our main Github page.
- [Diemen Design](https://github.com/DiemenDesign/)
