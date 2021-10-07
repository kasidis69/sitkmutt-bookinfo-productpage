# sitkmutt-bookinfo-productpage



## Run Python


```bash
pip3 install -r requirements.txt
python3 productpage.py 9080
```

## How to run Docker

```bash
# Build Docker Image for productpage service
docker build -t productpage .

# Run productpage service on port 8083
docker run -d --name productpage -p 8083:8083 productpage
```



