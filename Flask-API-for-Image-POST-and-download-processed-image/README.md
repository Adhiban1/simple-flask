# Flask API for Image POST and download processed image

requirement:

```
pip install flask
```

Run Python file:

```
python app.py
```

Upload image and download using `curl`:

```
curl -X POST -F "file=@<input file path>" --output "<output file path>" http://localhost:5000/upload
```