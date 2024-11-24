# fake_endpoint
this repo is useful for mobile dev . when you have endpoint consumption but the backned is not yet ready you can use this repo as a server . this is the steps for using it .

1- npm install -g json-server
2- json-server --watch db.json --port 3000
3- test with GET http://localhost:3000/products?qrcode=QRCODE1 
the response will be [
  {
    "id": "1",
    "name": "Fake Product 1",
    "description": "This is a description for Fake Product 1.",
    "imageUrl": "https://via.placeholder.com/150",
    "qrcode": "QRCODE1"
  },
  {
    "id": "2",
    "name": "Fake Product 2",
    "description": "This is a description for Fake Product 2.",
    "imageUrl": "https://via.placeholder.com/150",
    "qrcode": "QRCODE1"
  }
]

