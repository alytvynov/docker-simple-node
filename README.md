```bash
docker build -t simple-node .
docker run --rm -p 3000:3000 simple-node    
```

```bash
docker pull lytvynov/simple-node
docker tag simple-node lytvynov/simple-node:0.0.1
docker push lytvynov/simple-node:0.0.1
```
