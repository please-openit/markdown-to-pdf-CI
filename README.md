# Minimal markdown-pdf with styles and email send

> Currently based on debian, with node 12 due to some compatibilities issues with phantomjs and node 8


#### Thanks to :
- https://hub.docker.com/r/mkenney/npm/
- https://github.com/BlueHatbRit/mdpdf

> **Docker Hub** : https://hub.docker.com/r/dprslt/mdpdf/

## Usage

```bash
docker run --rm -v $(pwd):/data registry.please-open.it/mdpdf mdpdf README.md
```

See `mdpdf` [Github](https://github.com/BlueHatbRit/mdpdf) for more documentation.

See /doc for an example
