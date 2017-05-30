# https://lukaszwiecek.com
My personal website. Built using [Github Pages](https://pages.github.com/) and [jekyll](https://jekyllrb.com/).

## Setup (OS X)
```
brew install ruby
# make sure the ruby is from Homebrew (e.g. using ruby --version)
gem install bundler
bundle install
bundle exec jekyll serve
```

The site is now available locally at: http://localhost:4000

## Progressive Web Apps

I decided that home page is the perfect place to try out making [Progressive Web App (PWA)](https://developers.google.com/web/progressive-web-apps/).

To see how this website is getting closer to achive that goal I am using [Lighthouse](https://developers.google.com/web/tools/lighthouse/).
```
npm install -g lighthouse
lighthouse --view https://lukaszwiecek.com
```

Works locally as well: `lighthouse --view http://localhost:4000`