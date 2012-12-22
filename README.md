ServerJS
========

The ServerJS project is an extension of Node.js (http://nodejs.org), created to develop serverside javascript applications in an HTML-sheet. To define a serverside script-tag, you have the following choises:
	<script serverside>
	<script server>
	<script serverjs>
	<script language=serverjs>
	<script type=server>
	<server>
	<serverside>
	
Usage:

	$ nodejs serverjs.js [options] [file]
Options are:
	--help, -h: Print help and then exit.
	-l: Set javascript libaries imported. Eg: -lhttp://code.jquery.com/jquery.min.js, which is the default too.
The last argument passed will always be taken as the file to parse.

Dual-licensed under the MIT and the GPL license, see LICENSE
Mail: 0708andreas@gmail.com
Website: andreas.lha66.dk and serverjs.sourceforge.net
