## setting

```sh
docker build -t test_model_viewer.
docker run -d -p 80:80 -v $(pwd)/public:/root/public --name robotkun test_model_viewer
```