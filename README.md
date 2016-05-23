# jekyll2medium
This project is meant for those looking to migrate a Jekyll- (or Octopress-) based blog to the Medium platform. 

Medium currently [only accepts Wordpress XML](https://help.medium.com/hc/en-us/articles/218572107) ([sample XML](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml)) when importing a blog, so this plugin will shove your entire blog into a Wordpress XML, which is suitable for import into Medium. 

### Installation

Just put this file in your root jekyll directory (the same directory where you have your `index.html`). Of course, replace all the foobar items in the Front Matter with your own details. NOTE: Make sure your site_root does _not_ have a trailing slash. 

### Usage

After the file is present, re-build your Jekyll site (`jekyll build`), and you will then have an export.xml file in your site's root. Use this file to [import into Medium](https://help.medium.com/hc/en-us/articles/218445047). 
