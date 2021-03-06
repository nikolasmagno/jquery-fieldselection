# jQuery - fieldSelection

A jQuery plugin to get'n'set the caret/selection.  

## Description

Retrieve the caret (text cursor) position from textareas and input
fields as well as the actual selection and its index boundaries.
Replacing the selection string is also supported. Unfortunately special
treatment for such a simple thing is needed, because MSIE doesn't
support the easy DOM 3.0 methods.

## Status

First public release: `getSelection` and `replaceSelection` basically works.

## Requirements

[jQuery](http://jquery.com) (tested with version 1.0.2+)

## Usage sample

```html
<script type="text/javascript" src="jquery-fieldselection.js"></script>

```

```js
//Get Selected text
var selectedText = $('#id_textarea').getSelection();
           
//Replacing selection
$('#id_textarea').replaceSelection('new text here');

```

getSelection return sample:
```json
{start: 162, end: 171, length: 9, text: "Selected text here"}
```

## Gratitude 

Thankyou to [localhost](https://github.com/localhost) a person who started this plugin.

## License

<pre>
           DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
                   Version 2, December 2004 

Copyright (C) 2017 Nikolas Leite 
              2006 Alex Brem <alex@0xab.cd>
Everyone is permitted to copy and distribute verbatim or modified 
copies of this license document, and changing it is allowed as long 
as the name is changed. 

           DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
  TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

 0. You just DO WHAT THE FUCK YOU WANT TO.
</pre>

### Warranty

> This program is free software. It comes without any warranty, to
> the extent permitted by applicable law. You can redistribute it
> and/or modify it under the terms of the Do What The Fuck You Want
> To Public License, Version 2, as published by Sam Hocevar. See
> [http://sam.zoy.org/wtfpl/COPYING](http://sam.zoy.org/wtfpl/COPYING) for more details.
