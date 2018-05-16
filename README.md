# Remark

A simple Julia package to create presentations from markdown using [Remark](https://github.com/gnab/remark).

## Example use

Check [Remark documentation](https://github.com/gnab/remark/wiki/Markdown) on how to write the markdown for it to work with Remark. The most important thing is to use `---` to separate slides.

```julia
import Remark

# Create folder with presentation (html+markdown) from the markdown file "index.md"
slideshowdir = Remark.slideshow("index.md", "presentation/mybeautifulslides")

# Open presentation in default terminal
Remark.open(slideshowdir)
```

## To do

Allow offline version where all dependencies are downloaded.
