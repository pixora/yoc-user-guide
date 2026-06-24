# Docker setup and run
    docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .
    docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material

# Python setup and Mkdocs run
    python3 -m venv .venv
    source ./.venv/bin/activate

    pip install mkdocs-material
    pip install mkdocs-print-site-plugin
    pip install mkdocs-static-i18n

    mkdocs serve

# Generate static site
    mkdocs build
