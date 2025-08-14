# Article Format Template (AFT)

<!-- ALL THE BELOW SHOULD BE IN YOUR README -->

This is a Quarto template that assists you in creating a manuscript for Article Format Template journals. You can learn more about ...

## Creating a New Article

You can use this as a template to create an article for an AFT journal. To do this, use the following command:

```bash
quarto use template norcalbiostat/journal615-quarto-template
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation For Existing Document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add norcalbiostat/journal615-quarto-template
```

## Usage

To use the format, you can use the format names `aft-pdf` and `aft-html`. For example:

or in your document yaml

```yaml
format:
  pdf: default
  aft-pdf:
    keep-tex: true    
```
