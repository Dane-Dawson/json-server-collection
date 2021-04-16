# Blog with comments associated and likes
Empty template for blog with comments and likes
To run with connected associations
```
json-server -w db.json -r routes.json
```

Endpoints are
```
http://localhost:3000/images
http://localhost:3000/images/:id <=This path has associated comments included
http://localhost:3000/comments
http://localhost:3000/comments/:id
```
