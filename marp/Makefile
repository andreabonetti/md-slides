name = slides
rose = css/rose-pine-andrea.css
pink = css/pink.css
pink-dark = css/pink-dark.css
exp = export

clean:
	rm -f $(name)*.html
	rm -f $(name)*.pdf

all:
	# html
	marp --theme $(rose) --html $(name).md ; mv $(name).html $(name)-rose.html
	marp --theme $(pink) --html $(name).md ; mv $(name).html $(name)-pink.html
	marp --theme $(pink-dark) --html $(name).md ; mv $(name).html $(name)-pink-dark.html
	# pdf
	marp --theme $(rose) --html $(name).md --pdf ; mv $(name).pdf $(name)-rose.pdf
	marp --theme $(pink) --html $(name).md --pdf ; mv $(name).pdf $(name)-pink.pdf
	marp --theme $(pink-dark) --html $(name).md --pdf ; mv $(name).pdf $(name)-pink-dark.pdf
	# png
	marp $(name).md --theme $(rose) --html -o $(exp)/$(name)-rose.png
	marp $(name).md --theme $(pink) --html -o $(exp)/$(name)-pink.png
	marp $(name).md --theme $(pink-dark) --html -o $(exp)/$(name)-pink-dark.png


	