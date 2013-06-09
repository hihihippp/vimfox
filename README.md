vimfox
======

Instantly applies css / less changes in your browser without reloading the page.
The idea for this plugin is not mine. I forked this plugin: [https://github.com/Bogdanp/browser-connect.vim](browser-connect)
because I wanted to add support for LESS. 
The project seemed to be inactive and thats why I decided to rewrite it from 
scratch.


Very quick howto
================

1. add this plugin to vim using Pathogen / Vundle.
2. cd to the basedir of the vimfox repo and:
     sudo pip install -r requirements.txt
3. optionally change the default host / port for the vimfox server:
     let g:Vimfox_host = 127.0.0.1
     let g:Vimfox_port = 9000
4. add this line to the html page you want to work on:
     <script type='text/javascript' src="http://localhost:9000/vimfox/vimfox.js"></script>
5. reload the page and you're done.
