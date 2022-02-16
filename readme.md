* Install instructions (Ubuntu)
- sudo apt-get update
- sudo apt-get -y install python3-pip
- pip3 install flask waitress
- sudo apt-get install -y poppler-utils
- sudo add-apt-repository -y ppa:alex-p/tesseract-ocr5
- sudo apt install -y tesseract-ocr

* Run server
- production: python app.py 
- development: flask run