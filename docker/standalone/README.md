# A standalone Docker image

Build with

```shell
docker build --rm -t lcdm/standalone-rppdss .
```

or simply pull

```shell
docker pull lcdm/standalone-rppdss
```

To run a Jupyter notebook server, run

```shell
docker run -d -p 8888:8888 --name standalone lcdm/standalone-rppdss
```
