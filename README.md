{{- /* **NOTE: This  template comment will be removed by [`tmpl`].**
# tmpl.tmpl
[![Build Status](https://travis-ci.com/nwtgck/tmpl.tmpl.svg?branch=master)](https://travis-ci.com/nwtgck/tmpl.tmpl)

Template of Template

## How to use this template

```bash
# Install tmpl
go get -u github.com/nwtgck/tmpl

# Create a project from this template
tmpl new https://github.com/nwtgck/tmpl.tmpl.git yourtmpl
```

Then, you will have `yourtmpl/` directory.

[`tmpl`]: https://github.com/nwtgck/tmpl
<!-- The following section is a template of README.md-->
*/ -}}
{{"{{- /* **NOTE: This  template comment will be removed by [tmpl].**"}}
# {{.tmpl_name}}

{{.tmpl_description}}

{{print `
## How to use this template

` "```bash" `
# Install tmpl
go get -u github.com/nwtgck/tmpl

# Create a project from this template
tmpl new https://github.com/nwtgck/{{.project_name}}.git yourproject
` "```" `

Then, you will have yourproject/ directory.

[tmpl]: https://github.com/nwtgck/tmpl
<!-- The following section is a template of README.md-->
*/ -}}

# {{.project_name}}

{{.description}}
`}}
