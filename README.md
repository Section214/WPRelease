# WPRelease #

### Welcome to our GitHub Repository ###

WPRelease is a simple Git to SVN deployment tool for WordPress developers. By that, we mean it assumes that the only Subversion repo you would possibly want to work with is the WordPress.org plugin repository. It's also designed to be incredibly simple to use! Try it!

## Installation ##

1. Clone the GitHub repository: `git clone git@github.com:Section214/WPRelease.git`
2. Or download a ZIP file directly: `https://github.com/Section214/WPRelease/archive/master.zip`

Either method will download the latest version of WPRelease. Once you have it, you will want to put the wprelease file somewhere in your `$PATH` and make it executable.

## Usage ##

* Just run `wprelease --help`... it's easier that way.

## Bugs ##

Oops! Bugs happen, but we can't fix bugs we don't know about! If you find one, please let us know [here](https://github.com/Section214/WPRelease/issues?state=open)!

## Contributing ##

1. Post an [issue](https://github.com/Section214/WPRelease/issues) on GitHub
2. Send a Pull Request with your own bug fixes and/or new features

## FAQ

#### Why no history in SVN?

Because WordPress.org infrastructure maintainers explicitly ask you to omit it.  You're using WordPress.org as a tool for publishing releases only.  If you don't develop on WordPress.org, there's no point in syncing the entire history.

Dump-export replacements for each release is all you want and need. — This fact inherently eliminates the topic of `git-svn`.

## Credits

WPRelease exists because of the work put into similar projects by numerous people:

* Dean Clatworthy, [@deanc](https://github.com/deanc/wordpress-plugin-git-svn)
* Brent Shepherd, [@thenbrent](https://github.com/thenbrent/multisite-user-management/blob/master/deploy.sh)
* Patrick Rauland, [@BFTrick](https://gist.github.com/BFTrick/3767319)
* Ben Balter, [@benbalter](https://github.com/benbalter/Github-to-WordPress-Plugin-Directory-Deployment-Script)
* Christoph S. Ackermann, [@acki](https://github.com/cubetech/wordpress.plugin-deployment-script.git)
* Daniel F. Kudwien, [@sun](https://github.com/sun/wordpress-git-svn-release)
