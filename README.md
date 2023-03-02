# Serverless-Python-Code-Editor-
A python web code editor that can execute python code without the need of a backend server to process the code from the client editor.
The execution of the code is done at the client's machine but there is no need to install python thanks to WebAssembly.

Tools used:
* Pyodide - a CPython interpreter compiled to WASM.
* JS
* Tailwind - for styling

Note:
The main version of this app is not 100% serverless since it still use Flask server to serve HTML page. 
I'm planning to build a completely static website version of the app soon :)
