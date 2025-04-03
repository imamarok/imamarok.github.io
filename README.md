# imamarok.github.io

## Local test

1. Update repos
    ```bash
    sudo apt-get update -y && sudo apt-get upgrade -y
    sudo apt-add-repository ppa:brightbox/ruby-ng
    sudo apt-get update
    ```
2. Install ruby and gems
    ```bash
    sudo apt-get install ruby2.5 ruby2.5-dev build-essential dh-autoreconf
    gem update
    ```
3. Install jekyll gem
    ```bash
    gem install jekyll bundler
    jekyll -v
    ```
4. Install bundle
    ```bash
    bundle install
    ```
5. Execute locally
    ```bash
    bundle exec jekyll serve
    ```
6. Open `http://localhost:4000`

## Sources

* [jekyll](https://jekyllrb.com/docs/installation/)
* [modern-resume-theme](https://github.com/sproogen/modern-resume-theme/tree/master)
