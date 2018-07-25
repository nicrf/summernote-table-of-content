# summernote-table-of-content
Button to create a table of content in summer note
This crate a sample table of content with link to H1 and H2.

Todo :
Language support
Option (h1,h2,h3..)


Add link to 
```
<script src="js/summernote-table-of-content.js"></script>
```
And button 'tableofcontent' :
```javascript
$('#editor-container').summernote({
				toolbar:[					
					..
					['insert',['picture','link','videoAttributes','hr','tableofcontent']],
          ..
				],
        })
```
