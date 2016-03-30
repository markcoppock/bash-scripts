# simple BASH scripts

## 1. slugme

Takes a text input and converts to a slug&mdash;lowercase, dashes instead of spaces and slashes, "-and-" instead of ampersand. Simpler than many other slugify scripts (for better or worse).  

Echoes the output and also copies it to the OS-X clipboard. So far doesn't accommodate multiple dashes, backslashes.  

### usage

Copy this file to /usr/local/bin/  

`slugme "This phrase BADLY needs slugging&more"`  

	this-phrase-badly-needs-slugging-and-more
	copied to clipboard

