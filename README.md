## hexo-theme-prontera
A light theme for Hexo.
Online Demo: http://powman.org

![](https://raw.githubusercontent.com/AngryPowman/hexo-theme-prontera/master/doc/image/snapshot.png)

## Theme Features
- Custom Navigation Menu
* Custom Shortcut Icons
* Archive List
* ABOUT Information
* Links
* Supported `Duoshuo Comment` and `disqus`
* Supproted `Google Analytics` and `Tencent Analytics`

## Installation
### Install
`git clone https://github.com/AngryPowman/hexo-theme-prontera themes/prontera`

### Using
Change your theme config `_config.yml` to `prontera`  on the root of your Hexo directory:
```yaml
# Extensions
## Plugins: https://hexo.io/plugins/
## Themes: https://hexo.io/themes/
theme: prontera
```

### Plugin Dependencies
To use this theme for your Hexo blog, you may install `hexo-generator-archive` and add the configuration to your `_config.yml` on the root as follows: 
```yaml
# Show all articles on archive page
archive_generator:
    per_page: 0
    yearly: false
    monthly: true
    daily: false
```

## Change theme style
You can just change the constant `$MAIN_COLOR` in `themes/prontera/source/scss/_partial/base.scss` to change the basic color.

**NOTICE**: Do remember to run `gulp`  after you modify a scss file.


## License
MIT
