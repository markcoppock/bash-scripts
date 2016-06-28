# simple BASH scripts

## 1. slugme

Takes a text input and converts to a slug&mdash;lowercase, dashes instead of spaces and slashes, "-and-" instead of ampersand. Simpler than many other slugify scripts (for better or worse).  

Echoes the output and also copies it to the OS-X clipboard. So far doesn't accommodate multiple dashes, backslashes.  

### usage

Copy this file to /usr/local/bin/  

`slugme "This phrase BADLY needs slugging&more"`  

	this-phrase-badly-needs-slugging-and-more
	copied to clipboard

---

## 2. nuvvv

Very simple script to create a new WordPress site in a [Varying Vagrant Vagrants](https://github.com/Varying-Vagrant-Vagrants/VVV) Vagrant install.  

Set for if your VVV install is at ~/vvv/vagrant-local; modify the script if not.

### usage 

Once you've copied it to /usr/local/bin, create a new site with the command: `nuvvv sitename`  
