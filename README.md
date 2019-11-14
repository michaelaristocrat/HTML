# HTML
Notes and simple projects

* HTML is a markup language, not a programming language (doesn’t have logic).
* Strictly presentational
* Building blocks of the web

index.html is the root/home page of a website (www.anywebsite.com)

### Tag Syntax
* Element names surrounded by angle brackets
* Normally come in pairs (start tag and end tag)
* End tag is usually the same bu with a forward slash 
* Some tags close themselves

`<head></head>`
* nothing to do with the output seen in the browser
* has page titles
* links to javescript and css files
* descriptions and keywords (used by search engines)

`<body>`
* Things you see in the browser 

`<!DOCTYPE html>`
* Thing at the top, a declaration. Tells the browser which html it was written in. 


### Shortcuts
Type `head` then hit tab -> `<head></head>`
Type `lurem` then hit tab ->  

`Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.`

### 
Comment something out
 `<!—- Something —>`

`<p></p>`
* has margins 
* displayed as a block


Inline Elements: 
* Do not start on a new line 
* Take only the necessary width
* Ie. <span>, <img>, <a> 

Block elements:
* Start on a new line 
* Take full width available 
* <div>, <h1>-<h6>, <p>, <form>

Links elements are represented as <a>
* Has attributes 
* Href=“`where you want the user to go`”
* Target=`_blank` -> opens up a new tab… otherwise the will leave your page
	
Attributes: 
* Provide more information about the element.
* Placed within the start tag 
* key/value pairs (id=“someid”)

Lists:
* `<ul></ul`  stands for unordered lists… typically seen in nav bars
* `<ol></ol>` stands for ordered lists.  List items are numbered. 

```
	<ul>
		<li>List Item 1</li>
		<li>List Item 2</li>
		<li>List Item 3</li>
		<li>List Item 4</li>
	</ul>

	<ol>
		<li>List Item 1</li>
		<li>List Item 2</li>
		<li>List Item 3</li>
		<li>List Item 4</li>
	</ol>
```

Table:
```
	<table>
		<thead>
			<tr>
				<th>Name</th>
				<th>Email</th>
				<th>Age</th>
			</tr>
		<tbody>
			<tr>
				<td>Michael</td>
				<td>mikearistocrat@gmail.com</td>
				<td>25</td>
			</tr>			
		</tbody>
		</thead>
	</table>
```

Form:
`<form action="process.php" method="POST"></form>`
* If you want to submit the form to a specific page, u’d use the attribute actions
* Method  is an attribute, usually `POST` which is used to add data to a database. You may see `GET`, usually for search, but you do see the exact search in the browser. 

 
Random:
<strong></strong> -> usually makes things bold 
<em></em> -> stands for emphasize (tends to italicize)





