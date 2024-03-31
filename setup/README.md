# Run Webpage on Local Dev Server:

## Instructions for MacOS

### Installing Ruby + Jekyll

- [With Homebrew](https://jekyllrb.com/docs/installation/macos/) (Recommended)
- [Maybe with Anaconda?](https://s-canchi.github.io/2021-04-30-jekyll-conda/)
- [Installing Ruby via Chruby](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/#start-here-if-you-choose-the-long-and-manual-route)
  
### Running Local Server

```zsh
gem install webrick bundler jekyll
bundle exec jekyll clean
bundle exec jekyll serve
```