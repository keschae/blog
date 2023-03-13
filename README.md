# blog
Faux API to be used with Typicode

json-server --watch db.json --port=5000

curl -X GET -H "Content-Type: application/json" "https://localhost:5000/users/"
curl -X DELETE -H "Content-Type: application/json" ""http://localhost:5000/users/5"
curl -X GET -H "Content-Type: application/json" "http://localhost:5000/users/"

curl -X POST -H "Content-Type: application/json" -d '{"id": 6,"name": "Kevin Schaefer","username": "keschae","email": "keschae@ilstu.edu","address": {"street": "1-2-3 Main St","suite": "","city": "Abnormal","zipcode": "61761","geo": {"lat": "29.4572","lng": "-164.2990"}},"phone": "493-170-9623 x156","company": {"name": "Robel-Corkery","bs": "transition cutting-edge web services"}}' "https://my-json-server.typicode.com/keschae/blog/users"

curl -X GET -H "Content-Type: application/json" "https://my-json-server.typicode.com/keschae/blog/users"
curl -X DELETE -H "Content-Type: application/json" "https://my-json-server.typicode.com/keschae/blog/users/3"
curl -X GET -H "Content-Type: application/json" "https://my-json-server.typicode.com/keschae/blog/users/"
curl -X DELETE -H "Content-Type: application/json" "https://my-json-server.typicode.com/keschae/blog/users/5"
curl -X GET -H "Content-Type: application/json" "https://my-json-server.typicode.com/keschae/blog/users/"

