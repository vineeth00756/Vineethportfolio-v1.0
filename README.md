# vCard - Personal portfolio

![GitHub repo size](https://img.shields.io/github/repo-size/codewithsadee/vcard-personal-portfolio)
![GitHub stars](https://img.shields.io/github/stars/codewithsadee/vcard-personal-portfolio?style=social)
![GitHub forks](https://img.shields.io/github/forks/codewithsadee/vcard-personal-portfolio?style=social)
[![Twitter Follow](https://img.shields.io/twitter/follow/codewithsadee_?style=social)](https://twitter.com/intent/follow?screen_name=codewithsadee_)
[![YouTube Video Views](https://img.shields.io/youtube/views/SoxmIlgf2zM?style=social)](https://youtu.be/SoxmIlgf2zM)

vCard is a fully responsive personal portfolio website, responsive for all devices, built using HTML, CSS, and JavaScript.

## Demo

![vCard Desktop Demo](./website-demo-image/desktop.png "Desktop Demo")
![vCard Mobile Demo](./website-demo-image/mobile.png "Mobile Demo")

## Prerequisites

Before you begin, ensure you have met the following requirements:

* [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

## Installing vCard

To install **vCard**, follow these steps:

Linux and macOS:

```bash
sudo git clone https://github.com/codewithsadee/vcard-personal-portfolio.git
```

Windows:

```bash
git clone https://github.com/codewithsadee/vcard-personal-portfolio.git
```

## Deploying to Render

This portfolio is a plain static site, so it should be deployed on Render as a **Static Site**.

The repo now includes a root-level `render.yaml` Blueprint file with:

* `runtime: static`
* a no-op build command
* `staticPublishPath: .`

To deploy it on Render:

1. Push this project to GitHub.
2. In Render, click **New +** -> **Static Site**.
3. Connect the GitHub repository.
4. Render should detect the root `render.yaml` automatically.
5. Create the site and let Render deploy the contents of the repo root.

If Render asks for manual values, use:

* Build Command: `echo "Static site - no build step required"`
* Publish Directory: `.`

After deployment, your portfolio will be available on an `onrender.com` URL, and you can add a custom domain from the Render dashboard.

## Contact

If you want to contact me you can reach me at [Twitter](https://www.x.com/codewithsadee_).

## License

MIT
