# [digipres.dspace.lib.unb.ca](https://digipres.dspace.lib.unb.ca/) : Lean Instance Repository
[![Build Status](https://github.com/unb-libraries/digipres.dspace.lib.unb.ca/actions/workflows/deployment-workflow.yaml/badge.svg?branch=prod)](https://github.com/unb-libraries/digipres.dspace.lib.unb.ca/actions/workflows/deployment-workflow.yaml)
[![GitHub license](https://img.shields.io/github/license/unb-libraries/digipres.dspace.lib.unb.ca)](https://github.com/unb-libraries/digipres.dspace.lib.unb.ca/blob/prod/LICENSE)
![GitHub repo size](https://img.shields.io/github/repo-size/unb-libraries/digipres.dspace.lib.unb.ca?label=lean%20repo%20size)

This repository contains the assets used to test, build, and deploy the digipres.dspace.lib.unb.ca application.

## Deploy this Application Yourself!
Local deployment, development and testing of digipres.dspace.lib.unb.ca is easy, as we leverage [dockworker](https://github.com/unb-libraries/dockworker), our unified framework of [Robo](https://robo.li/) commands that streamline local development of our application on Linux or OSX.

### Step 1: Install Dockworker's Dependencies
In your local development environment, a minimal number of 'one time' dependencies are required to deploy applications with dockworker. Some or all of these may already be installed in your environment; see the list of dependencies and installation instructions [here](https://github.com/unb-libraries/dockworker/blob/4.x/docs/prerequisites.md).

### Step 2: Deploy
With all dependencies installed, you are ready to deploy any of our applications locally and and begin development:

```
composer install
vendor/bin/dockworker deploy
```

And that's it! The application will build and deploy in your local environment.

If you work with unb-libraries applications often, you may also consider [installing a dockworker alias](https://gist.github.com/JacobSanford/1448fece856be371060d0f16ccb1b194), which avoids referencing vendor/bin for each dockworker command.

## Other useful commands
Run ```vendor/bin/dockworker``` to list available dockworker commands for this application.

## Author / Contributors
This application was created at [![UNB Libraries](https://github.com/unb-libraries/assets/raw/master/unblibbadge.png "UNB Libraries")](https://lib.unb.ca) by the following humans:

<a href="https://github.com/JacobSanford"><img src="https://avatars.githubusercontent.com/u/244894?v=3" title="Jacob Sanford" width="128" height="128"></a>
<a href="https://github.com/dreamyseashell"><img src="https://avatars.githubusercontent.com/u/46697350?v=3" title="Sarah Nearing" width="128" height="128"></a>

## License
- As part of our 'open' ethos, UNB Libraries licenses its applications and workflows to be freely available to all whenever possible.
- Consequently, the contents of this repository [unb-libraries/digipres.dspace.lib.unb.ca] are licensed under the [MIT License](http://opensource.org/licenses/mit-license.html). This license explicitly excludes:
   - Any website content, which remains the exclusive property of its author(s).
   - The UNB logo and any of the associated suite of visual identity assets, which remains the exclusive property of the University of New Brunswick.
