# Collective Logic Website

Collective Logic Website, designed to run on GitHub pages.

## Prerequisites

### Ruby (>2.1.0)

To check which version is installed, try:
```bash
ruby --version
```

To install Ruby, check the Ruby download and installation instructions:
https://www.ruby-lang.org/en/downloads/

Or my preferred method is to use rbenv to control Ruby versions (to allow different versions for different projects
rather than a single version globally on your system):
https://github.com/rbenv/rbenv

### Bundler

To check which version is installed, try:
```bash
bundle --version
```

If bundler is not installed, you can use:
```bash
gem install bundler
```

## Run the site locally

```bash
bundle exec jekyll serve
```

Then visit http://localhost:4000
