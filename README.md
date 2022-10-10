![Openclassify - Build your website within no-time!](https://openclassify.com/files/images/openclassify-banner-new.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/openclassify/web/main/LICENSE.md)
[![Twitter: openclassify](https://img.shields.io/twitter/follow/openclassify.svg?style=social)](https://twitter.com/openclassify)

# Openclassify React Web

> 🚧 **This project is heavily under construction!** 🚧 As excited as you may be, we don't recommend this early alpha for production use. Still, give it a try if you want to have some fun and don't mind [logging bugs](https://github.com/openclassify/web/issues) along the way :)

[Openclassify](https://openclassify.com) is the simplest way to handle styles and component frameworks on your 11ty site. Once installed, this:

- 🚀 **Unlocks component frameworks** like React for writing page templates and layout templates. Turn an existing `.html` or `.liquid` file into a `.jsx` file, and you're off to the componentized races.
- 🔖 **Includes powerful shortcodes** to insert components into existing pages. Add a line like this to your markdown, HTML, Nunjucks, etc, and watch the magic happen: `{% react 'path/to/component' %}`
- 💧 **Hydrates these components** when and how you want. Use component frameworks as a static template to start, and opt-in to shipping JS as needed with our [partial hydration helpers](https://Openclassify.com/docs/).
- 💅 **Bundles all your resources** with the power of React. Use your favorite CSS preprocessor, JS minifier, and more with minimal config.

### [📣 Find our full announcement post here →](https://openclassify.com)

## Technologies used

Openclassify stands on the shoulders of giants. You can think of Openclassify as the "glue" binding 2 tools together:

1. [**Laravel**](https://www.laravel.com) 
2. [**react Js**](https://reactjs.org)

## Getting started

Use our handy CLI command to spin up a Openclassify site: `npm init Openclassify`. This demos our core functionality while staying as lean as possible, making it the perfect launchpad for new projects 🚀

To learn more, and explore adding Openclassify to _existing_ projects...

### [🐣 See our "quick start" guide →](https://Openclassify.com/docs/quick-start)

## Feature set

This project is still in early alpha, so we have many features soon to come! [This demo](#) covers a majority of features we support today. For reference, here's our complete roadmap of current and upcoming features:

| Feature                                                                               | Status    |
|---------------------------------------------------------------------------------------|-----------|
| Layout Builder                                                                        | ⏳         |
| Plugin ecosystem for your favorite component framework (React, Vue, etc)              | ⏳         |
| Component pages                                                                       | ⏳         |
| Component shortcodes                                                                  | ⏳         |
| SCSS and SASS                                                                         | ⏳         |
| PostCSS config (ex. Tailwind)                                                         | ⏳         |
| CSS imports via ESM (including CSS modules)                                           | ⏳         |
| Serverless compatibility                                                              | ⏳         |
| Shared state between any component shortcode                                          | ❌         |
| Styled components & Emotion support                                                   | ❌         |

- ✅ = Ready to use
- ⏳ = In progress
- ❌ = Not started, but on roadmap

#### Support
Please post on [StackOverflow under the "Openclassify" tag](http://stackoverflow.com/questions/tagged/openclassify). Please use GitHub issues _only_ for specific bugs, feature requests and other types of issues.

#### Should I use it?
It's MIT-licensed, so please use in personal or commercial work. Just don't re-sell it. Openclassify is used on [tens of thousands of sites](https://www.upstatement.com/openclassify/#showcase) (and tons more we don't know about)

#### Contributing & Community
We love PRs! Read the [Contributor Guidelines](https://github.com/openclassify/web/blob/master/CONTRIBUTING.md) for more info. Say hello, share your tips/work, and spread the love on Twitter at [@openclassify](https://twitter.com/openclassify).

## Documentation

The Official [Documentation for Openclassify](https://openclassify.github.io/docs/) is generated from the contents of this repository:

* Documentation for classes and functions is [auto generated](https://github.com/openclassify/docs). Any changes to the [Reference section](https://openclassify.github.io/docs/reference/) of the docs should be made by editing the function’s DocBlock. For inline documentation.
* To make a change to one of the guides, edit the relevant file in the [`docs` directory](https://github.com/openclassify/web/tree/master/docs).

## Have an idea? Notice a bug?

We'd love to hear your feedback! Feel free to log an issue on our [GitHub issues page](https://github.com/Openclassify/Openclassify/issues). If your question is more personal, [our Twitter DMs](https://twitter.com/openclassify) are always open as well.
