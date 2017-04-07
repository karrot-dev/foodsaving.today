#  Foodsaving Today!

[Foodsaving Today](https://foodsaving.today) is a blog about foodsaving. This is the [grav](https://getgrav.org/) site for it, based on the [multilang](https://github.com/getgrav/grav-skeleton-multilang-site) skeleton site.

# Requirements

- PHP 5.5.9 or higher. Check the [required modules list](https://learn.getgrav.org/basics/requirements#php-requirements)
- Check the [Apache](https://learn.getgrav.org/basics/requirements#apache-requirements) or [IIS](https://learn.getgrav.org/basics/requirements#iis-requirements) requirements

# Running Locally

First install the dev dependencies by running `composer update` from the root, then:

```
$ php -S 127.0.0.1:8000 system/router.php
```

And the site will be running at [localhost:8000](http://localhost:8000).


# Adding Functionality

You can download [plugins](https://getgrav.org/downloads/plugins) or [themes](https://getgrav.org/downloads/themes) manually from the appropriate tab on the [Downloads page on https://getgrav.org](https://getgrav.org/downloads), but the preferred solution is to use the [Grav Package Manager](https://learn.getgrav.org/advanced/grav-gpm) or `GPM`:

```
$ bin/gpm index
```

This will display all the available plugins and then you can install one or more with:

```
$ bin/gpm install <plugin/theme>
```

# Updating

To update Grav you should use the [Grav Package Manager](https://learn.getgrav.org/advanced/grav-gpm) or `GPM`:

```
$ bin/gpm selfupgrade
```

To update plugins and themes:

```
$ bin/gpm update
```


# Contributing

We appreciate any contribution to Foodsaving Today, whether it is related to bugs, grammar, or simply a suggestion or improvement. Blog posts are especially welcome though. Please tell us how foodsaving is working in your community!

You can contribute by:
- github pull request
- joining [yunity slack](https://slackin.yunity.org/) #foodsaving-worldwide channel


# License

See [LICENSE](LICENSE.txt)
