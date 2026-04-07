# Introduction

This is the Github repository for Mentorica.AI [blog site](blog.mentorica.ai).

On a new system, first make sure ruby is installed
```bash
sudo apt-get install -y ruby-dev build-essential
gem install bundler
```
Then install dependencies, run
```bash
bundle install
```

To preview the blog locally, run
```bash
bundle exec jekyll serve
```

Pushing to the repo will automatically deploy the site via Github Action.