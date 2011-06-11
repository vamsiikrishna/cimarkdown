Markdown library for CodeIgniter
====================
Markdown is awesome it is a text-to-HTML conversion tool for web writers

Based on PHP Markdown by Michel Fortin
[PHP Markdown](http://michelf.com/projects/php-markdown/).

Original Markdown
John Gruber
[Markdown] (http://daringfireball.net/projects/markdown/).



Installation
------------

1. Copy the cimarkdown.php to your libraries directory

2. Load the cimarkdown library in your controller

Usage
-----

	$this->load->library('cimarkdown');
	
	$this->cimarkdown->markit($markdowndemo);


	
where $markdowndemo is a variable which contains the markdown text entered by the user


