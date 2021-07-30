### Dependencies
Install `xelatex` via your package manager (e.g., `brew install xelatex` for macOS).
Install `docker`.

### PDF generation
xelatex cv.tex cv.pdf

### Using Docker
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex test.tex
