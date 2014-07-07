# hikari

Hikari is an open-source [Jekyll](http://jekyllrb.com) theme perfect for dev-savvy bloggers who wants to get started with Jekyll in a very minimal way. 

- SCSS!
- Responsive
- Lightweight (no JS library has been abused here)

![preview](https://dl.dropboxusercontent.com/u/7539881/Hikari/hikari-screenshot.png)

![preview](https://dl.dropboxusercontent.com/u/7539881/Hikari/hikari-screenshot-2.png)

![preview](https://dl.dropboxusercontent.com/u/7539881/Hikari/hikari-screenshot-3.png)

[View demo](http://m3xm.github.io/hikari-for-Jekyll)


### How to install

1. Clone this repo
2. Customize \_config.yml and replace all dummy posts by yours
3. Change your profile picture in ~/assets/img/avatar.jpg
3. Publish ([I recommend GitHub pages, it's free](https://help.github.com/articles/using-jekyll-with-pages))

Note that publishing a Jekyll 2.0 website with Github Pages is a bit tricky right now though. Depending on the configuration of your repo (whether it is your main GH page or not), you'll probably have to only push the ouput of `jekyll build`, meaning the content of `_site`. Open an [issue](https://github.com/m3xm/hikari-for-Jekyll/issues?state=open) if you know how to solve this.


### Development

- `master` for development and pull requests.
- `gh-pages` for the demo page; don't bother.


#### Running locally

1. Clone this repo
2. Install required dependencies with [Bundler](http://bundler.io/)

        bundle install
3. Run the site with Jekyll

        bundle exec jekyll serve --watch
4. Visit the site at [http://localhost:4000](http://localhost:4000)


### Author

**Mathieu Mayer-Mazzoli**
- <http://m3xm.github.io>
- <http://twitter.com/mx3m>
- <http://www.dribbble.com/m3xm>


### Main Contributors

**Ross Allen**
- <https://github.com/ssorallen>

**Julien Rousseau**
- <https://github.com/evarouss>


### License

Open source. [MIT license](http://opensource.org/licenses/MIT).
