name = slides
rose = css/rose-pine-andrea.css
pink = css/pink.css
pink-dark = css/pink-dark.css

clean:
	rm -f $(name)*.html
	rm -f $(name)*.pdf

all:
	marp --theme $(rose) --html $(name).md ; mv $(name).html $(name)-rose.html
	marp --theme $(pink) --html $(name).md ; mv $(name).html $(name)-pink.html
	marp --theme $(pink-dark) --html $(name).md ; mv $(name).html $(name)-pink-dark.html
	marp --theme $(rose) --html $(name).md --pdf ; mv $(name).pdf $(name)-rose.pdf
	marp --theme $(pink) --html $(name).md --pdf ; mv $(name).pdf $(name)-pink.pdf
	marp --theme $(pink-dark) --html $(name).md --pdf ; mv $(name).pdf $(name)-pink-dark.pdf

	