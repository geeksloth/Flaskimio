# flaskimio
Flask based api for image uploading and display WITHOUT saving to storage.

Below figure shows the image returned from server's memory, NOT STORAGE. This can be used as a template for image processing, AI, edged computing system.

![Screenshot](static/uploaded.png)

### Installation
1. install requirements via apt-get or pip: Flask, PIL, etc.
```bash
python3 -m pip install Pillow, Flask
```
2. clone this repository to desire directory
```bash
git clone https://github.com/nonsakhoo/flaskimio.git
```
3. run the main script by
```python
python3 main.py
```
4. access the api via typing ip:port in browser as:
```bash
http://192.168.0.101:5000
```
