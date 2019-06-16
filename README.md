# jsdaniell.github.io

## O que é este repositório?

Este repositório armazena todo o código utilizado na minha página pessoal hospedada com GitHub Pages, no qual me permite utilizar da integração contínua no desenvolvimento e manutenção da página, a geração da página acontece devido a utilização do da ferramenta Jekyll que já é suportada por padrão no GitHub Pages, para que assim a página seja gerada dinâmicamente de acordo com o deploy no branch **master**.

## Configurações Implementadas

```yml
# Site
title:              'José Daniel'
bio:                'Atualmente implementando para Web utilizando tecnologias JavaScript como Node.js, Express.js, React, persistência de dados com MongoDb, SQL, ferramentas como Pug (Jade), EJS, Jekyll com integração contínua com GitHub, desenvolvimento mobile com Flutter, Dart e React-Native. <br><br> Carrego comigo o cerne do aprendizado constante! Quando não se está aprendendo se está sendo desafiado e vice e versa!'
description:        "Aqui demonstro alguns de meus projetos e habilidades desenvolvidas ao longo da minha jornada como programador!"
reading_time:       true
words_per_minute:   200
logo:               'assets/img/danisboy.png'
background:         'assets/img/asus.jpg'
tiled_bg:           false   # Set this true if you want to tile your background image, otherwise it will be covered
locale:             
url:                https://jsdaniell.github.io

# Jekyll
permalink:          /:title/
markdown:           kramdown
highlighter:        rouge
kramdown:
  auto_ids:         true
  footnote_nr:      1
  entity_output:    as_char
  toc_levels:       1..6
  enable_coderay:   false
mathjax:            true
sass:
  sass_dir:         _sass
  style:            compressed

# Comments
disqus_shortname:   jsdaniell

# Social
# if you don't have any of social below, comment the line.
#google:
  #plus:            #username
  #analytics:
  #verify:
  #ad-client:
  #ad-slot:
#bing-verify:
email:              jose.daniell@outlook.com
#twitter:            username
#facebook:           username
github-url:         jsdaniell
#stackoverflow:     123456/username   from a "http://stackoverflow.com/users/123456/username" link
#linkedin:          username
#xing:              username
instagram:          jsdaniell
#lastfm:            username
#tumblr:            username
#medium:            '@username'
#pinterest:         username
#foursquare:        username
#steam:              username
#dribbble:          username
#youtube:           username
#youtube-channel:   channel
#soundcloud:        username
#weibo:             username
#flickr:            username
#codepen:           username
#keybase:           username
#xmpp:              username@server.com
#hackernews:        username

# Gems
gems:
  - jekyll-mentions
  - jekyll-feed
  - jekyll-sitemap
  - jekyll-gist

jekyll-mentions:
    base_url: https://github.com

# Exclude list
exclude: [README.md, Gemfile, Gemfile.lock, node_modules, gulpfile.js, package.json, _site, src, vendor, CNAME, LICENSE, Rakefile]
```

## Licença

Sinta-se a vontade para utilizar este projeto como base da sua página, as configurações podem ser modificadas no _config.yml e o restante da personalização fica ao seu critério.