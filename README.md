# furious-clown
Furious clown contains code associated with demonstrating DOM-based XSS exploitation via JSON script injection.

# Overview
The javascript payload will search and extract all cookies and information within local storage and send it to an arbitrary servier via websockets.

(1) Read cookies
(2) Read localstore
(3) Send to remote server via HTTPS
