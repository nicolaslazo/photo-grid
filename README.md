# Photo Grid

This responsive grid theme provides a beautiful layout to showcase your photograghy and manage your gallery with ease.

## Distinguishing Features

- Easy photo management
    - Configurable photo display order
    - Automatic thumbnail creation
    - Automatic EXIF info extraction
- Full lazy loading for maximum bandwidth savings

## Origin

Photo Grid is based on [Hugird](http://themes.gohugo.io/theme/hugrid/), a responsive grid-layout boilerplate theme for Hugo.

## Demo

- [My own photo gallery](https://chen-zhe.github.io/portfolio/)


## Screenshot

![Hugrid screenshot](images/screenshot.png)


## Contents

- [Installation](#installation)
- [Getting started](#getting-started)
    - [The config file](#the-config-file)
	- [Photo Management](#photo-management)
    - [Nearly finished](#nearly-finished)
- [Contributing](#contributing)
- [License](#license)
- [Annotations](#annotations)


## Installation

Inside the folder of your new Hugo site run:

```sh
    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/chen-zhe/photo-grid
```
For more information read the official [setup guide](https://gohugo.io/overview/installing/) of Hugo.


## Getting started

After installing the theme successfully it requires a just a few more steps to get your site running.


### The config file

Take a look inside the [`exampleSite`](exampleSite) folder of this theme. You'll find a file called [`config.toml`](exampleSite/config.toml). To use it, copy the `config.toml` in the root folder of your Hugo site. Feel free to change the strings in this theme.

### Photo Management

All photos are stored in the [`photo`](exampleSite/content/photo) folder under the `content` folder. You can put multiple directories under it and the theme will enumerate all photos within in order of the directory listing. Within each subfolder, e.g. [`1-trip1`](exampleSite/content/photo/1-trip1), you can put all relevant photos in it and then copy over the `index.md` file.

Within [`index.md`](exampleSite/content/photo/1-trip1/index.md) file, you can specify each photo's name, description and other properties. Take a look at the descriptions to understand what can be customized.

### Nearly finished

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server

Now enter `localhost:1313` in the address bar of your browser.


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/chen-zhe/photo-grid/issues) to let me know. Or make directly a [pull request](https://github.com/chen-zhe/photo-grid/pulls).


## License

This work is licensed under the MIT License. For more information read the [License](LICENSE.md).


## Annotations

Thanks 

- to [spf13](https://github.com/spf13) for creating Hugo and the awesome community around the project
- to [digitalcraftsman](https://github.com/digitalcraftsman) for creating Hugo themes and writing nice READMEs
- to Codrops for original [Thumbnail Grid with Expanding Preview](http://tympanus.net/codrops/?p=14530).
- to Pavel for porting over the aforementioned theme to Hugo as [Hugrid](https://github.com/aerohub/hugrid)