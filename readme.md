# [Sidera](https://github.com/rabbarbaro/sidera)

Sidera is a simple customizable theme for static websites built with [Hugo](https://gohugo.io).  
Many thanks to [Eric Murphy](https://ericmurphy.xyz) for finally convincing me to use Hugo, for providing his free uncopyrighted code for a basic [starter theme](https://github.com/ericmurphyxyz/hugo-starter-theme) and for allowing me to look inside his own website's files to understand how it works and taking inspiration for a few code snippets.  
I am no web developer, and definitely not a UI designer or a front-end developer. This is what I settled with after a couple of evenings of work.

## Features

No bloat.  
No JS whatsoever, just pure straight CSS.  
Customizable configuring the `hugo.toml` file.  
Dark mode supported checking the user preferred theme.  
Supports multilingual sites using the i18n library.

## Installation

Inside your project folder, clone the theme to your `themes` folder.

```bash
git clone https://github.com/rabbarbaro/sidera themes/sidera
```

## Configuration

Please take a look at the provided `example-hugo.toml` file.  

Please do note that the description and the footer only work when language files (e.g. `en.toml`) are correctly configured with the correct variables in the `i18n` folder.

```bash
[description]
other = 'Your description'

[madeWith]
other = 'Made'
```

The avatar image is in the `static/images` folder.

To learn more about building themes in Hugo, refer to Hugo's [templating documentation](https://gohugo.io/templates/).

## License

This code is free to use under the [MIT license](https://github.com/rabbarbaro/sidera/blob/main/LICENSE) attached.

## Per aspera ad astra