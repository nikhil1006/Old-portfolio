# Portfolio

This website is a simple portfolio developed by using [GatsbyJs](https://www.gatsbyjs.org/) & hosted by [GitHubPages](https://pages.github.com/)

[**Demo Website**](https://cara.lekoarts.de)

Also be sure to checkout other [Free & Open Source Gatsby Themes](https://themes.lekoarts.de)

## ✨ Features

- Theme UI-based theming
- react-spring parallax effect
- CSS Animations on Shapes

1.**Create a Gatsby site.**

Use the Gatsby CLI to create a new site, specifying this project

```sh
gatsby new project-name https://github.com/LekoArts/gatsby-starter-portfolio-cara
```

2.**Start developing.**

Navigate into your new site's directory and start it up.

```sh
cd project-name
gatsby develop
```

3.**Deploying to a GitHub Pages subdomain at github.io**

For a repository named like username.github.io, you don’t need to specify pathPrefix and your website needs to be pushed to the master branch.

```sh
{
  "scripts": {
    "deploy": "gatsby build && gh-pages -d public -b master"
  }
}
```

After running ```npm run deploy``` u should see ur website at ```username.github.io```
