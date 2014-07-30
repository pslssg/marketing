# Start Stay Grow Marketing Site

## Getting Started
This project is using Jekyll and github pages for hosting. First install gem dependencies by running: 

```
gem install bundler
bundle install
```

Next, start the server by running:

```
jekyll serve
```

The website should now be running at http://localhost:4000. To make changes simply push up to the master branch. 

### Editing styles
This projects stylesheets are made using Sass. You will need to generate the CSS file by running:

```
sass --watch _sass:stylesheets --style compressed
```

This will compile the CSS into one file on one line.