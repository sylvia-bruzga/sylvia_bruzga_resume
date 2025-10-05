FROM hugomods/hugo:exts

COPY . /src

# Build site.
RUN hugo --minify

# Serve the site
CMD ["hugo", "server", "--bind", "0.0.0.0", "--port", "8080"]