# Unity Theme Starter
When installing the [**Unity**](https://github.com/Involts/jekyll-theme-Unity/) theme through [RubyGems.org](https://rubygems.org/gems/jekyll-theme-unity), Jekyll can only read files in the folders `/_data`, `/_layouts`, `/_includes`, `/_sass` and `/assets`, as well as a small part of options of the `/_config.yml` file from the theme's gem. If you have ever installed this theme gem, you can use the command `bundle info --path jekyll-theme-Unity` to locate these files.

The Jekyll team claims that this is to leave the ball in the user’s court, but this also results in users not being able to enjoy the out-of-the-box experience when using feature-rich themes.

To fully use all the features of **Unity**, you need to copy the other critical files from the theme's gem to your Jekyll site. The following is a list of targets:

```shell
.
├── _config.yml
├── _plugins
├── _tabs
└── index.html
```

To save you time, and also in case you lose some files while copying, we extract those files/configurations of the latest version of the **Unity** theme.

## Prerequisites

Follow the instructions in the [Jekyll Docs](https://jekyllrb.com/docs/installation/) to complete the installation of `Ruby`, `RubyGems`, `Jekyll` and `Bundler`.

## Installation

[**Use this template**]( https://github.com/Involts/Unity-Theme-Starter/generate) to generate a brand new repository and name it `<GH_USERNAME>.github.io`, where `GH_USERNAME` represents your GitHub username.

Then clone it to your local machine and run:

```
$ bundle
```

## Usage

Please see the [theme's docs](https://github.com/Involts/jekyll-theme-Unity#documentation).

## License

This work is published under [MIT](https://github.com/Involts/Unity-Theme-tarter/blob/master/LICENSE.txt) License.
