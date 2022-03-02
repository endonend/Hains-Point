# Hain's Point Theme

A customizable newsletter-focused theme for Micro.blog. Includes featured posts, asides, and more!

Written for [Micro.blog](https://micro.blog) by [Jason Dettbarn](http://endonend.org) [@endonend](https://micro.blog/endonend).

[My site](https://endonend.micro.blog) currently uses this theme, if you'd like to see it in action.

## How to install

Hain's Point for Micro.blog is freely available to members of Micro.blog. Log into your account, choose Plugins in your settings, click on Find Plug-ins, and choose to install Hain's Point as your theme.

Once installed, visit the theme's Settings screen to customize for your site. Settings available:

- Social usernames: Twitter, Instagram
- Set newsletter name and homepage subscribe blurbs
- Set Micro.blog newsletter ID (see the tips section below)
- Set the "about" blurb on the sidebar and About page URL
- Set header logo (see the tips section below)

Also, you will need to create the following categories:

- Featured (the two latest posts in this category show above the subscribe box on the homepage)
- Asides (the posts in this category get an Aside tag and show in the sidebar in post pages)

### Theme Install Tips

- Get your newsletter ID on the Subscribe page created when you enable Newsletters for your micro.blog account. The ID is in the form action URL it adds to that page. In this example the ID is 61826: https://micro.blog/users/subscribe/61826

- For your header logo, upload a PNG file to your Uploads and grab the Micro.blog URL for that image. For my site, the image was 600x120 pixels with white text on a transparent background. You can also use a black background (in this case the file can be a JPEG) or what ever color you want if you choose to customize the theme.

### Plugin Support

Hain's Point currently supports these plugins:

- [Conversation on Micro.blog](https://github.com/svendahlstrand/plugin-conversation-on-mb)
- [Plausible Analytics](https://github.com/LukasRos/plugin-plausible)
- [Open Graph Cards](https://github.com/thatguygriff/plugin-open-graph)
- [Twitter cards](https://github.com/microdotblog/plugin-twitter-cards)

These are all tested and confirmed by me. Others may work, though!

Note: I am working on support for the Photos plugin and Photos page. (as of 3/1/22)

### Note on Upgrading

After installing via plug-in, you will be prompted for upgrades in the future as I make changes to the theme. Please note, when you upgrade (as of 3/2/22), **your settings will not be saved**, so please document these settings prior to upgrading until this is fixed. You will need to go into Settings and re-enter your settings after each upgrade.

## Donations

If you use the theme (and like it) you can [donate to support its development](https://www.buymeacoffee.com/jdettbarn). Thanks in advance!

## Version History

**2022.1 - February 23, 2022**

- Initial release

**2022.1.1 - March 1, 2022**

- Quick Fix - changed Flickr to Twitter, poor copy + paste!

**2022.1.2 - March 2, 2022**

- Added upgrade note to Readme (save your settings prior to upgrading!)
- Added some CSS for blockquote captions (wrap your blockquote captions/citations and add the class .blockquote-footer), pre styling, horizontal rule styling, and image captions (wrap your image captions and add the class .image-footer)


Base theme files forked from [Cypress for Micro.blog](https://github.com/cdevroe/cypress-microblog) by Colin Devroe -- to learn Hugo templating. 