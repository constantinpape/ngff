# ome-ngff

[Next-generation file format (NGFF) specifications](https://ngff.openmicroscopy.org/latest/) for storing bioimaging data in the cloud.

## Editing

Specifications are written in markdown, or technically
[bikeshed](https://github.com/tabatkins/bikeshed) -- a markdown document, with
special extensions understood by the bikeshed tool. The bikeshed tool is run
on-commit via the [spec-prod github action](https://github.com/w3c/spec-prod),
generating the familiar "spec looking" ReSpec format. ReSpec is just html with
a javascript ReSpec library.

Specification files end with the .bs file extension. The github action runs on
commit to automatically convert to respec/html, via bikeshed. 

[Learn more about bikeshed](https://w3c-ccg.github.io/bikeshed_instructions.html)

## Citing

Please see https://ngff.openmicroscopy.org/latest#citing for the latest
citation.
