Personal resume for Scott Driggers

### Source

Forked from https://github.com/sb2nov/resume

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT but all the data is owned by Scott Driggers.
