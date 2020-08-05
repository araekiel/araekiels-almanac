<h1 align="center">
  <br>
  <a href="https://araekiel.netlify.app"><img src="https://github.com/Araekiel/araekiels-almanac/blob/master/assets/images/almanac.png" alt="Araekiel's Almanac" width="200"></a>
  <br>
  Araekiel's Almanac
  <br>
</h1>

<h4 align="center">
  This repository contains the source code for my personal website built with <a href="https://jekyllrb.com/">Jekyll</a>.
</h4>

<p align="center">
  <a><img alt="MIT License" src="https://img.shields.io/apm/l/atomic-design-ui.svg?"></a>
  <a><img alt="Github Release" src="https://img.shields.io/badge/release-v1.0-blue"></a>
  <a href="https://app.netlify.com/sites/araekiel/deploys"><img alt="Netlify Status" src="https://api.netlify.com/api/v1/badges/e55d05c3-64c6-4f9f-ac79-4b5f369879f7/deploy-status"></a>
</p>

<p align="center">
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#build--run">Build & Run</a> •
  <a href="#directory-structure">Directory Structure</a> •
  <a href="#refs">Refs</a> •
  <a href="#authors">Authors</a> •
  <a href="#license">License</a>
</p>

## Prerequisites

### Ruby 

Download and install Ruby from this [link](https://www.ruby-lang.org/en/downloads/).

Run the following commands to confirm if the installation was successful:

```bash
$ ruby -v
$ gem -v
```

### Jekyll

Run the following command to install Jekyll:

```bash
$ gem install bundler jekyll
```

## Build & Run

Clone the repo and cd into the directory:

```bash
$ git clone https://github.com/Araekiel/araekiels-almanac.git
$ cd araekiels-almanac
```

> Set the port in *_config.yml*

Run the site:

```bash
$ bundle exec jekyll serve
```

> Note: '**bundle exec**' is not required unless you are running the website for the first time.

Open a browser and type **localhost:_port_**

## Directory Structure

   ```bash
   .
   ├── _data                      
   |   ├── binge.yml
   |   ├── navingation.yml
   |   ├── projects.yml
   |   └── sketches.yml
   ├── _includes                      
   |   ├── footer.html
   |   ├── head.html
   |   ├── header.html
   |   └── scripts.html
   ├── _pages                       
   |   ├── 404.html
   |   ├── about.html
   |   ├── binge.html
   |   ├── journal.html
   |   ├── projects.html
   |   └── sketches.html
   ├── _posts
   ├── _site
   ├── assets                      
   |   ├── images
   |   |   ├── binge
   |   |   ├── posts
   |   |   ├── sketches
   |   |   └── almanac.png
   |   └── styles
   ├── _config.yml
   ├── Gemfile
   └── Gemfile.lock
   ```

> Note: I would advise against relying on this repository. It will not be updated frequently since the website relies on a different repo(private). Also, you will encounter file not found errors upon execution since this repo does not contain images for 'binge' and 'sketches' pages.

## Refs

- The design is inspired by [aweekj](https://github.com/aweekj)'s [Kiko-plus](https://github.com/aweekj/Kiko-plus) jekyll theme.


## Authors

- [Araekiel](https://www.github.com/Araekiel)

## License 

[MIT](https://choosealicense.com/licenses/mit/)