# Columbia Science Olympiad Website

The defacto site for coaches to see information on Columbia University and for Columbia/Barnard Students to find out more about our club

-   If you have questions about joining or want to help with the website then email columbiascienceolympiad@gmail.com

## Documentation:

The site is constructed using [Jekyll](https://jekyllrb.com/), a static site generator. To get started, follow the instructions on [Jekyll's installation page](https://jekyllrb.com/docs/installation/). To build and serve the site locally, run `bundle exec jekyll serve` from the root of this repository.

##### Requirements for Jekyll:

-   Ruby version **2.5.0** or higher
-   RubyGems
-   GCC and Make

> Install all prereqs following the guide here [installation guide](https://jekyllrb.com/docs/installation/#requirements)

> Installation Notes:
> installation following the guide on Jekyll's site might not work properly and run into issues so, I recommend following these steps instead:
>
> -   To install Ruby; you should use a ruby virtual environment from [rbenv](https://github.com/rbenv/rbenv#readme).
>     -   Using homebrew install using `brew install rbenv ruby-build`
>     -   Configure to load your shell with "rbenv init" you can do this through a command like `echo 'status --is-interactive; and ~/.rbenv/bin/rbenv init - fish | source' >> ~/.config/fish/config.fish` _Note that I am using fish, your commmand for zsh will be different_
>     -   Install the proper version of ruby of 3.1.3 with rbenv install 3.1.3
>     -   Set local ruby version through `rbvenv global 3.1.3`
> -   Make sure that the file paths of ruby and everything are correct and fix where needed. You can do this through `which ruby`, it should return something like `/Users/daleyu/.rbenv/shims/ruby` and not `/usr/bin`.
> -   Run gem install bundler
> -   Try to follow instructions on any other mission packages and it should now work!
>     Feel free to fork to make it your own, or contribute!

#### Installation of Jekyll locally

If you want to manage your website in a local web development environment, you'll be using [Ruby](https://jekyllrb.com/docs/installation/).

Jekyll is a Ruby Gem that can be installed on all systems basically, follow these commands to get it done:

1. Install full Ruby development environment [Ruby](https://jekyllrb.com/docs/installation/)

    1. cd into our director `cd cu-science-olympiad.github.io`
    2. install missing gem packages`bundle install`
    3. build the site on your local server `bundle exec jekyll serve`

    If you are using vscode then you should do this in the integrated terminal there and you can also open it with command+click.

## Contributions:

If you want to contribute to this site, then reach out to dy2446@columbia.edu or contact columbiascienceolympiad@gmail.com, and they can add you in as a colaborator.

-   Feel free to fork it and make it your own or fix a typo and something and create a PR. We will try to look at PR as fast as we can.

In the future if more people are working then we will use branch-rebase workflow. [Merging vs Rebasing Guide](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)

Code style is dictated in the `.editorconfig` file. If you are using VS Code, you can download the [extension](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) to automatically apply the right formatting settings.

See the [EditorConfig documentation](https://editorconfig.org/) for more information and for how to use EditorConfig on different editors.

#### Credits and Mentions:


