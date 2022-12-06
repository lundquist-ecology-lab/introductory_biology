# Slides for Introductory Biology II

These are images (.jpg) of slides for my Introductory Biology II course. The
slides can also be found on [LundquistEcology.com](https://www.lundquistecology.com/biology-home).

All work is my own and figures and images used are from:

* [OpenStax Biology 2e](https://openstax.org/details/books/biology-2e)
* [Wikimedia commons](https://commons.wikimedia.org/wiki/Main_Page)
* [Unsplash](https://www.unsplash.com)


![front page](/screenshots/front.png)

Each set of images can be converted to PDF for presentations in any order that 
you want. For example, if you want to produce a PDF of the fungi slides:

```bash

## Requires imagemagick and github-files-fetcher

# npm install -g github-files-fetcher

fetcher --url=https://github.com/lundquist-ecology-lab/introductory_biology/tree/main/fungi --out=/tmp
cd /tmp/fungi
convert `ls -1v` fungi.pdf #`ls -1v` sorts .JPG files numerically, not alphabetically
mv fungi.pdf ~/fungi.pdf
cd ~/
rm -R /tmp/fungi

```
