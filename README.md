# resume
This is my resume in LaTex. It's just basic LaTex that I used docker with

### docker build

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex resume_anon.tex
```

