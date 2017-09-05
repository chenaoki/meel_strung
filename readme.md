* Install Docker on your computer.

*For the first time, run below command to pull docker image.

```bash
docker pull jupyter/datascience-notebook
```

* On the terminal of host, run below.

```bash
docker run -it --rm -p 8888:8888 jupyter/datascience-notebook:latest
```

* Copy and paste the URL with token on browser.

* On the terminal in Jupyter notebook, run below.

```bash
cd work
git clone https://github.com/chenaoki/meel_strung.git
```
