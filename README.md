# Architectify Netlify CMS

## Table of contents

- [Architectify Netlify CMS](#architectify-netlify-cms)
  - [Table of contents](#table-of-contents)
  - [Features](#features)
  - [Screenshot](#screenshot)
  - [Depend repository](#depend-repository)
  - [Live demo](#live-demo)
  - [Install](#install)
  - [Documentations](#documentations)
  - [License](#license)


## Features
- rubrics `create false`
- pages
- persons
- offices
- projects
  - types (projects taxonomy)
  - tags (projects taxonomy)
- posts
  - categories (posts taxonomy)
  - tags (posts taxonomy)
- publications
- config
  - menu `create false`
    - primary
    - secondary
    - legal
    - social
  - top banner
  - seo

## Screenshot


## Depend repository
* Hugolify Netlify CMS : [Hugolify template](https://github.com/hugolify/hugolify-netlify-cms)

## Live demo
- Front: https://demo.lawyerify.fr

## Install

Edit `config/_default/module.yaml` to install the `architectify-netlify-cms` module with `hugolify-netlify-cms`:
```yml
imports:
  - path: github.com/hugolify/architectify-netlify-cms
  - path: github.com/hugolify/hugolify-netlify-cms
```

## Documentations
https://github.com/hugolify/hugolify-template/wiki

## License
Hugolify is free for personal or commercial projects (MIT license)
