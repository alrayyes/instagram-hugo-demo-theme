[![wercker status](https://app.wercker.com/status/dc30c64139b94a8024dd86e33b9e642b/m/master "wercker status")](https://app.wercker.com/project/byKey/dc30c64139b94a8024dd86e33b9e642b)

Instagram Hugo Demo Theme
=================

This is a simple demo theme that shows how to use [Instagram](https://www.instagram.com/) with [hugo](https://gohugo.io). Running demo can be found [here][demo_page].

Installation
------------

Inside the folder of your Hugo site run:

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/alrayyes/instagram-hugo-demo-theme

For more information read the official [setup guide][setup_guide] of Hugo.

### The Config File ###

Add the following to your config.toml:

```toml
[Params]
access_token = "<access_token>"
```

You can generate an access token [here](http://instagram.pixelunion.net/).

Used Libraries
---------

- [Boostrap](https://getbootstrap.com/)
- [Momentjs](http://momentjs.com/)
- [Jquery](https://jquery.com/)

Contributing
------------

Report any bugs using the [issue tracker][issue_tracker]. Submit your own bug
fixes or feature additions via a [pull request][pull_request].

License
-------

This theme is released under the MIT License. For more information read the
[license][license].

[demo_page]: https://instagram-hugo-demo.ryankes.eu/
[setup_guide]: http://gohugo.io/overview/installing/
[issue_tracker]: https://github.com/alrayyes/instagram-hugo-demo-theme/issues
[pull_request]: https://github.com/alrayyes/instagram-hugo-demo-theme/pulls
[license]: https://github.com/alrayyes/instagram-hugo-demo-theme/blob/master/LICENSE.md
