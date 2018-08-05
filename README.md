# Model constitution for unincorporated UK charities that are member associations
Having recently needed to update the [Camberley Finnish School's](http://www.suomikoulu.org) constitution, I discovered whilst the UK's [Charity Commission](https://www.gov.uk/government/organisations/charity-commission) provides [model constitutions](https://www.gov.uk/government/publications/setting-up-a-charity-model-governing-documents) for [unincorporated charities that are member associations](https://www.gov.uk/government/uploads/system/uploads/attachment_data/file/586359/GD3.pdf), it only does so in PDF format, a [copy](resources/docs/GD3.pdf) of the PDF is mirrored within this repository.
In order to draft the charity's own constitution, I recreated the model constitution in [Markdown](https://en.m.wikipedia.org/wiki/Markdown) to have it in an easily editable format. To save others the time required to recreate the document from scratch, I am making it available here.

**DISCLAIMER** I do not accept any liability for constitutions drafted using this model, I suggest you seek legal advice before using a drafted constitution for your own purposes.

## Usage
The [model-constitution.md](model-constitution.md) makes use of Pandoc's `fancy_lists` extension and therefore requires compilation using [Pandoc](https://pandoc.org), the syntax for compiling the constitution into a word document is as follows:

```pandoc --from=markdown+fancy_lists --to=docx --output=model-constitution.docx model-constitution.md```

A precompiled copy of the Microsoft Word version of the model constitution is available [here](model-constitution.docx)