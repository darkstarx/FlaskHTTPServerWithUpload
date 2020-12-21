# FlaskHTTPServerWithUpload
This is a simple http server for testing multiple file upload.

# Run
`pip3 install -r requirements.txt`

`./main.py`

# Usage
You can upload files using browser (just load `http://localhost:5000/`) as well as using curl like this ` curl -X POST -F file1=@index.html -F file2=@logo.png http://localhost:5000/`
