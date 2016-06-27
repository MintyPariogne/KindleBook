# KindleBook
files needed for a kindle book

## TODO
- [x] requirement for hello.mobi file
- [ ] requirement for cover (idpf 3.0)
- [ ] requirement for table of content (html)
- [ ] requirement for table of content (xhtml in manifest & spine)
- [ ] requirement for table of content (ncx in manifest & spine)
- [ ] landmarks nav ???

## hello.mobi
### hello.html
Used the title tag for the title. Used the meta tag with the cover location as content. These two files created a book with no errors.
### cover.jpg
I have the dimensions at 1500x2400. Suggestions are appreciated.

## opf
1. Know your title `<dc:title>`*string*`</dc:title>`
2. determine [language](http://www.w3.org/International/articles/language-tags) `<dc:language>`*code from link*`</dc:language>`
3. meta name is cover attribute
4. know your manifest [element](http://www.idpf.org/2007/opf/OPF_2.0_final_spec.html#Section2.3)
5. table of content as [ncx](http://www.niso.org/workrooms/daisy/Z39-86-2005.html#NCX)
6. [guide](http://www.idpf.org/2007/opf/OPF_2.0_final_spec.html#Section2.6)

## ncx
## toc
