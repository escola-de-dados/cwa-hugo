# Site Prêmio Jornalismo de Dados

# Gerar galeria

- Exportar o CSV do Airtable
- Usar a coluna com a URL da imagem para baixar tudo em lote (`wget -i listadeurls.txt`)
- Salvar as imagens na pasta statics/edicao
- E ajustar o conteúdo da edição do ano

## Customização

Alterar o arquivo CSS em `themes/kross-hugo/assets/css/estilo.css` 

Boostrap 4.5

Converter YAML: https://onlineyamltools.com/convert-csv-to-yaml

Os templates HTML estão `layouts/`

![Homepage](https://user-images.githubusercontent.com/37659754/58154295-1a9c5300-7c93-11e9-992c-ad8d2ff8d99f.png)

[Live Preview](http://demo.themefisher.com/kross-hugo/)

[Kross Hugo theme](https://github.com/themefisher/kross-hugo/) is developed by Themefisher.

## Requirements

- GitHub, GitLab or BitBucket account
- Hugo > 0.65.0 (tested with latest Hugo)

## Content Management

![](static/images/kross-forestry.jpg)

[![import to Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=forestryio/kross-hugo-starter&engine=hugo&version=0.81.0)

This project has been pre-configured to work with [Forestry](https://forestry.io) a git-based CMS, [import your repository in Forestry](https://app.forestry.io/quick-start?repo=forestryio/kross-hugo-starter&engine=hugo&version=0.81.0) and you'll be able to edit and preview your site ✨.

Any changes you make in Forestry will be commited back to the repo, and deployed when your Git repository is connected to [Netlify](#netlify).

## Deployment

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/forestryio/kross-hugo-starter)

1. Set the build command to: `hugo --gc --minify`
2. Set the publish directory to: `public`
3. Make sure to set `HUGO_VERSION` to 0.65.0 or above (tested with latest version)
3. Set the publish directory to: `public`

That's it, now your site gets deployed automatically on `git push` or when saving documents from Forestry.

## Local development

This starter is using [Hugo](https://gohugo.io) as a static site generator.
Once imported in Forestry, clone your repository and develop locally with Hugo.

```bash
# Clone your repository
# Go in the project directory
# Start local dev server
hugo server
```

## Feedback

[Open an issue](https://github.com/themefisher/kross-hugo/issues) in the theme's repository.

## LICENSE

[MIT](https://github.com/themefisher/kross-hugo/blob/master/LICENSE)
