# ISA-tab BIH Germline Cookie Cutter

This is a [cookiecutter](https://github.com/cookiecutter/cookiecutter) template for the [ISA-Tab](https://isa-specs.readthedocs.io/en/latest/isatab.html) file format.
The template allows for easily bootstrapping a ISA-Tab project project for BIH germline projects.

## What It Does

- Call `cookiecutter` as given below and follow through with the interactive prompts.
- Prompts (I'm usually filling the first 1-2 and then just press return for the remaining)
    - Enter investigation title (all required identifiers will be generated based on this in a sensible way).
    - Enter comma-separated list of samples.
    - Select sequencing type (exome/genome sequencing).
    - Select the used library kit.
    - Enter the batch number.
    - Usually confirm all other settings as their defaults.

NB: you can also use cookiecutter's [User Config](https://cookiecutter.readthedocs.io/en/stable/advanced/user_config.html) in the case that you want to save a different set of presets for exome/genome projects.

## Installing & Calling Cookiecutter

```bash
# pip install cookiecutter  # <-- if you don't have it already

# cookiecutter -o /tmp/ gh:holtgrewe/cookiecutter-isatab-bih-germline
```
