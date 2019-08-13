These are templates for onboarding new users into GitHub Actions. There are a few directories:
* [ci](ci): solutions for Continuous Integration
* [automation](automation): templates for automating workflow.
* [icons](icons): svg icons for the relevant template

Each template must be written in YAML and have a `.yml` extension. Each template needs a corresponding `.properties.json` file that contains extra metadata about the template.

For example: `ci/python-django.yml` and `ci/python-django.properties.json`.

Valid properties:
* `name`: the name shown in onboarding
* `description`: the description shown in onboarding
* `iconName`: the icon name in the relevant folder, for example `django` should have an icon `icons/django.svg`. Only SVG is supported at this time.
* `categories`: the categories that it will be shown under

