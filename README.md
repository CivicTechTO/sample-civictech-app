# Sample CivicTech App

<!-- A short one-liner description of your app -->

{{cookiecutter.one_liner}}

<!-- A longer paragraph description -->

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus
nunc, cursus ut ultricies vel, fermentum et enim. Donec quis arcu
ornare, placerat tortor tempus, efficitur libero. Integer condimentum
aliquam neque, a venenatis enim hendrerit condimentum. Cras ut fringilla
justo. Maecenas a lectus nec justo vestibulum vulputate ac quis risus.

## Technologies Used

<!-- Add your own technologies here! -->

* [**Jekyll.**][jekyll] A static HTML website generator.
* [**GitHub Pages.**][gh-pages] A Jekyll website-hosting service provided by GitHub.
* [**Heroku.**][heroku] A platform for easily deploying applications.
* [**Review Apps.**][review-apps] A Heroku feature that deploys code
  from GitHub pull requests as a disposable app on the web.


## :computer: Local Development

### Requirements

* Ruby 2.3+
* `rbenv` (optional)

### Setup

You'll first need to ensure you are using a compatible version of Ruby.
We recommend managing Ruby versions with `rbenv`. (Installing and
setting ruby versions is out of scope of these instructions.)

```
ruby --version
>>> ruby 2.3.0p0 (2015-12-25 revision 53290) [x86_64-linux]
git clone https://github.com/patcon/toronto-shelter-map
bundle install
bundle exec jekyll serve
```

## :muscle: Contributing

Please make sure to read our [Contributing Guide](CONTRIBUTING.md) and
[Code of Conduct](CONDUCT.md) before making a pull request.

## :copyright: License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)

<!-- Links -->
   [gh-pages]: https://help.github.com/articles/what-is-github-pages/
   [jekyll]: https://jekyllrb.com/docs/home/
   [heroku]: https://www.heroku.com/what
   [review-apps]: https://devcenter.heroku.com/articles/github-integration-review-apps
