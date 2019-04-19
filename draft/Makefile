all:
	Rscript -e 'rmarkdown::render("draft.Rmd", output_format = c("html_document", "pdf_document", "word_document"))'

html:
	Rscript -e 'rmarkdown::render("draft.Rmd", output_format = "html_document")'

pdf:
	Rscript -e 'rmarkdown::render("draft.Rmd", output_format = "pdf_document")'

word: 
	Rscript -e 'rmarkdown::render("draft.Rmd", output_format = "word_document")'

outline: 
	Rscript -e 'rmarkdown::render("outline.Rmd", output_format = "pdf_document")'

quotes:
	Rscript -e 'rmarkdown::render("quotes.Rmd", output_format = c("pdf_document", "html_document"))'

clean:
	rm draft.pdf draft.tex draft.html draft.docx


