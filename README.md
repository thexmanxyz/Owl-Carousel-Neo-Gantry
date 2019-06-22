# Owl Carousel Neo - Particle for Gantry
This project contains a Gantry Particle and is based on the default **Gantry Helium - Owl Carousel Particle** but extends it with many useful additional features (e.g. lazy load, timed slides, ...) and also includes slick new designs. **Owl Carousel Neo** is an advanced version of the standard Particle created by [Gantry](http://gantry.org/) and [RocketTheme](https://rockettheme.com/). Furthermore, it provides an easy, user friendly and GUI assisted configuration and integration. In the current revision the following CMSs are supported:
* Joomla
* Wordpress
* Grav

## Prerequisites
* CMS (Joomla, Wordpress, Grav)
* Gantry Templating Framework and Theme

## Download
Choose the correct download for your target platform. The Joomla Plugin System is supported for all Gantry themes globally or locally for the templates Helium and Hydrogen. The latest Particle version is **v1.0.0**.
___
**Default Particle:**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.particle.only.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.particle.only.DE.v1.0.0.zip)

**Legacy Particle - Gantry <5.3.2:**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.particle.only.legacy.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.particle.only.legacy.DE.v1.0.0.zip)

**Joomla Plugin - All Templates (Global):**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.j3.global.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.j3.global.DE.v1.0.0.zip)

**Joomla Plugin - Hydrogen:**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.j3.hydrogen.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.j3.hydrogen.DE.v1.0.0.zip)

**Joomla Plugin - Helium:**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.j3.helium.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.0.0/lih.j3.helium.DE.v1.0.0.zip)
___

## Automatic Installation (Joomla only)
1. Download the Plugin of the *Owl Carousel Neo Particle* for **Hydrogen, Helium or Global** installation.
2. Install it over the Joomla Plugin System.
3. Modify the `custom.scss` file located under `/[GANTRY_THEME]/custom/scss` and add the following line `@import "owlcarousel-neo";` at the end. Please check the list below to determine where the template folder for your CMS is located.

*If you install the plugin globally be aware that the resource location changes to `/media/gantry5/engines/nucleus`*

## Manual Installation
1. Download the **Default or Legacy Package** of the *Owl Carousel Neo Particle*. If you are using Gantry **<5.3.2** please use the **Legacy Package** for compatibility reasons.
2. Extract the files.
3. Copy the `.html.twig` and the `.yaml` file to your particle folder `/[GANTRY_THEME]/custom/particles`. Please check the [listing](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry#cms-template-folder) below to determine where the template folder for your CMS is located.
4. Copy the `.js` file to the folder `/[GANTRY_THEME]/custom/js`. Create the folder if it does not exist.
5. Copy the `.scss` file to the folder `/[GANTRY_THEME]/custom/scss`. Create the folder if it does not exist.
6. Modify the `custom.scss` file located under `/[GANTRY_THEME]/custom/scss` and add the following line `@import "owlcarousel-neo";` at the end.

## CMS Template Folder
Please be aware that the template folder path varies in dependence of the used CMS. Here is a list of the folders for the different platforms:

### Wordpress
`/wp-content/themes/[GANTRY_THEME]`

### Joomla
`/templates/[GANTRY_THEME]`

### Grav
`/user/data/gantry5/themes/[GANTRY_THEME]`
   
## Configuration
1. Go to your Gantry templating backend (e.g. Extensions/Templates).
2. Switch to **Layout** and add the new appearing Particle called **Owl Carousel Neo** either globally to your site (**base outline**), to a specific template or page by dragging it to the designated section.
3. Configure the appearance according to your favor.
 
## Supported Parameters, Particle Options and Features
* All settings of the original Particle are included and compatible
* Updated to latest version of [OwlCarousel2](https://owlcarousel2.github.io/OwlCarousel2/)
* Lazy loading of images included
* Timing of slides (annual or one-time)
* Slide link can be applied to title as well
* Slide button can be "replaced" by the title link
* Four new styles (additionally also the default Helium style)
* Two themes (black or white)
* Seven different control colors
* Border radius (square or round)
* Dot navigation alignment
* Configuration of next/previous arrows
* Overlay image improvement
  * all six Helium overlays included
  * five new overlays
  * or use accent overlay of current template  

## Showroom
Insight of the *Owl Carousel Neo - Gantry Particle* configuration:

**Backend (1)** - *[General](/screenshots/backend_general.png)*

![1](/screenshots/backend_general.png)

**Backend (2)** - *[Appearance](/screenshots/backend_appearance.png)*

![2](/screenshots/backend_appearance.png)

**Frontend (1)** - *[Demo 1 - Black Mode](/screenshots/frontend_demo1.png)*

![3](/screenshots/frontend_demo1.png)

**Frontend (2)** - *[Demo 2 - Black Mode](/screenshots/frontend_demo2.png)*

![4](/screenshots/frontend_demo2.png)


**Frontend (3)** - *[Demo 3 - White Mode](/screenshots/frontend_demo3.png)*

![5](/screenshots/frontend_demo3.png)


**Frontend (4)** - *[Demo 4 - White Mode](/screenshots/frontend_demo4.png)*

![6](/screenshots/frontend_demo4.png)

## Future Tasks
- [ ] Include JS resource loading scheme to provide CDN support for OwlCarousel2
- [ ] Include `aria` attributes for links

## Known Issues
None

## Dependencies
[Gantry Framework](http://gantry.org/)

[Helium Template](https://github.com/gantry/gantry5)

## Credits
Thanks to the [Gantry](https://github.com/gantry) team for providing a modern templating framework.

## by [thex](https://github.com/thexmanxyz) | [gantryprojects](https://gantryprojects.com)
Copyright (c) 2019, free to use in personal and commercial software as per the [license](/LICENSE.md).
