# Recursive-File-Info-Extractor-Python-Proj

Python script that will recursively get file information from a given path on the client. 
The path can be given as an argument in the script. The script should work for both Linux and Windows environments. 
The file information will be put into a list of JSON objects containing the filename, path, and file size (in bytes). 
This JSON content will then be sent via POST to the following test endpoint: https://jsonplaceholder.typicode.com/posts
