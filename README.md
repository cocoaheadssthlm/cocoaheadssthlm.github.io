# CocoaHeads Stockholm website

This website aims to be a central place for CocoaHeads Stockholm, making it easy
to find everything about the meetups. We always want to improve and
contributions are very welcome.

## Dependencies

- Ruby 2.3.3 and bundler

## Getting started

1. Clone the repo and make sure you've got Ruby and bundler installed. macOS
   system Ruby should suffice, otherwise `brew install ruby23` will get you
   there. `gem install bundler` installs bundler.
2. Fetch Ruby dependencies with `bundle install`.
3. Run `bundle exec jekyll serve` to get a local HTTP server hosting the site,
   keeping up with changes.

## Contributing

Please follow these guidelines and open Pull Requests with isolated changes.
Feel free to open issues with suggestions if you're not able to make the changes
directly.

### Git

- Keep commit messages clear and descriptive. See [How to Write a Git Commit
  Message](http://chris.beams.io/posts/git-commit/) for some good guidelines.
- Rebase your branch and remove WIP or fix commits to make it ready for merge.

### Style guide

CSS/SCSS:

- We follow [Aribnb's CSS/Sass guide](https://github.com/airbnb/css.), except
  `lower-case` instead of `PascalCase` for blocks.
- Structure is inspired by [SMACSS](https://smacss.com/book/categorizing).
