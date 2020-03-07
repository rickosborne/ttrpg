FROM pandoc/latex:2.6

# https://github.com/lierdakil/pandoc-crossref/releases/download/v0.3.4.1a/linux-pandoc_2_7_3.tar.gz
# https://github.com/lierdakil/pandoc-crossref/releases/download/v0.3.6.2/linux-pandoc_2_9_2.tar.gz

RUN wget https://github.com/lierdakil/pandoc-crossref/releases/download/v0.3.4.1a/linux-pandoc_2_7_3.tar.gz -q -O - | tar xz && \
	mv pandoc-crossref /usr/bin/

ENTRYPOINT ["pandoc"]
CMD ["--help"]
