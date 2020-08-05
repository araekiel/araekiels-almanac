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

## Prerequisites

### Ruby 

Download and install Ruby from this [link](https://www.ruby-lang.org/en/downloads/).

Run the following commands to confirm if the installation was successful:

```
$ ruby -v
$ gem -v
```

### Jekyll

Run the following command to install Jekyll:

```
$ gem install bundler jekyll
```

## Build & Run

Clone the repo and cd into the directory:

```
$ git clone https://github.com/Araekiel/araekiels-almanac.git
$ cd araekiels-almanac
```

> Set the port in *_config.yml*

Run the site:

```
$ bundle exec jekyll serve
```

> Note: '**bundle exec**' is not required unless you are running the website for the first time.

Open a browser and type **localhost:_port_**

## Directory Structure

   ```
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