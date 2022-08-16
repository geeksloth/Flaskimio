# Flaskimio
Flask based api for image uploading and display **WITHOUT** saving to storage.

Below figure shows the image returned from **server's memory (RAM)**, NOT STORAGE (HDD). This can be used as a template for image processing, AI, edged computing systems.

![Screenshot](static/uploaded.png)

## Prerequisite
Pillow and Flask are required for this template. If not installed please install them via your package manager, e.g., pip, apt, etc:
```bash
python3 -m pip install Pillow Flask
```

## Installation
1. Clone this repository and change directory into it:
```bash
git clone https://github.com/geeksloth/flaskimio.git && cd flaskimio
```
2. run the ```main.py``` script by
```python
python3 main.py
```
3. Access the api via typing ```ip:port``` in browser:
```bash
http://192.168.0.101:5000
```
