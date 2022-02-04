# resume

Build LaTeX image:
```bash
docker build -t latex .
```

Create PDF:
```bash
docker run --rm -i -v "$PWD":/data latex pdflatex resume.tex
```

Sources:
- https://github.com/nakamin/resume
- https://github.com/sb2nov/resume
