# This repo hosts the styling for the following discourse navigations:

- https://forum.snapcraft.io/ on the [snapcraft-forum](https://github.com/canonical-web-and-design/discourse-nav/blob/snapcraft-forum) branch
- https://discourse.ubuntu.com/ on the [ubuntu-discourse](https://github.com/canonical-web-and-design/discourse-nav/blob/ubuntu-discourse) branch
- https://discourse.maas.io/ on the [maas-discourse](https://github.com/canonical-web-and-design/discourse-nav/blob/maas-discourse) branch
- https://discourse.charmhub.io/ on the [charmhub-discourse](https://github.com/canonical-web-and-design/discourse-nav/blob/charmhub-discourse) branch

## Bugs and issues

If you have found a bug related to the navigation on the sites mentinoned above, feel free to [create a new issue](https://github.com/canonical-web-and-design/discourse-nav/issues/new/choose), or suggest a fix by [creating a pull request](https://help.github.com/articles/creating-a-pull-request/).

## How to develop

Checkout the branch that is coresponding to the discourse website you want to update.

Start editing the files you need to edit in the `src` folder.

Once your PR is merged, a GitHub action will run and it will update all the files in the `common` folder.

_You can also run `npm run build` to build the content of the `common` folder locally, but it is not recommended to commit any file inside the `common` folder._

## How it works

Discourse will read the theme from one of the branches available on this repo. Any change in the `common` folder will apply to both mobile & desktop views. If you wish to add changes for a specific layput, you should use a `desktop` or `mobile` folder.

You can read more information on [how to add a discourse theme from a grihub repo](https://meta.discourse.org/t/developer-s-guide-to-discourse-themes/93648).

You can find more discourse theme examplese on [GitHub](https://github.com/topics/discourse-theme-component).

## License

The content of this project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/), and the underlying code used to format and display that content is licensed under the [LGPLv3](http://opensource.org/licenses/lgpl-3.0.html) by [Canonical Ltd](http://www.canonical.com/).

With ♥ from Canonical
