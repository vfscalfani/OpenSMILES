The specification in built with [ASCIIDOC](http://www.methods.co.nz/asciidoc/).

```
make html
make pdf
make all
```

### Installing ASCIIDOC

#### Mac OS X

Requirements:
  * [homebrew](http://brew.sh/)
  * [MacTex](https://tug.org/mactex/)

```
brew install asciidoc
curl -o /usr/local/Library/Formula/dblatex.rb -L http://gist.github.com/dustinschultz/6544364/raw/5bbe233fbe953b8070c5453fdf09cd65eb515e9e/dblatex.rb
# May need to set MacTex path
brew install dblatex
```

Environment
```
export XML_CATALOG_FILES=/usr/local/etc/xml/catalog
```