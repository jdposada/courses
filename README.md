# Jose Posada Courses Webpage

This repo contains the code to generate the webpage on

https://jdposada.github.io/courses/

The amin directory contains the rendered files as well as the original files

The original markdown files are located on the folders

- `config`:  folder with global configurations
- `content`:  folder where the content resides
- `assets`:  folder with the images required
- `local`: folder containing instructions for local deployment and testing
- `.github`: folder with the automation to build the page using Github Actions. No other action is needed besides pushing. To build this webpage we need a Docker image available on `jdposa/hugo_backend`. That is the hugo modified image that includes go. That image is built using the code on https://github.com/jdposada/hugo. 

This repo is based on a Wowchemy template that can be found here

https://github.com/wowchemy/starter-hugo-online-course