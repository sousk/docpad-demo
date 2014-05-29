# Instlation

	npm install -g docpad

Be sure to use the stable version of Node.js.

# Publish

	docpad generate
	docpad deploy-ghpages --env static

if you want test in your local environment, just type

	docpad run

# Making a document

DocPad supports asset pipelining so that you can make your document with any formats you like.

For example, if you want you create a HTML document with Markdown format, you put the file named *pagename.html.md* into the *src/document* folder.

Note that you have to have the renderer which can handle the format you set to the extension of the document.


# Documents

**Basics**

- [DocPad overview](http://docpad.org/docs/overview) tells you the roles of directories, and files you make.
- [Bootstrap skeleton for DocPad](https://github.com/docpad/twitter-bootstrap.docpad) is the actual code set we use to host the site.

**Utilities**

- [Renderers List](http://docpad.org/docs/plugins) to extend formats you can use with DocPad.
