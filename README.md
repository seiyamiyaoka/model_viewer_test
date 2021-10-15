## setting

```sh
docker build -t test_model_viewer .
docker run -d -p 80:80 -v $(pwd)/public:/root/public --name robotkun test_model_viewer
```

now open [http://0.0.0.0/](http://0.0.0.0/)