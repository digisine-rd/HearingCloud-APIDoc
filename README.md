# Modify Documentation

```bash
docker run --rm -d -p 8080:8080 --name swagger_editor swaggerapi/swagger-editor
docker stop swagger_editor
```

# Preview
```
python -m http.server -d docs
```