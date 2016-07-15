# Annotator for NER

![Screenshot of web interface](/src/main/resources/static/img/screenshot.png?raw=true "Screenshot")

A tool for annotating word sequences, based on TextAnnotations.

Note: this requires a file called config/folders.txt that maps a folder name (anything you want) to a path. This
path must contain serialized TextAnnotations.

## Usage

Requires Java 8 and Maven. Run:

    $ ./run.sh

This will start the server on port 8080. Point a browser to [localhost:8080](http://localhost:8080).