# Owl Carousel Neo - Particle for Gantry
This project contains a Gantry Particle and is based on the default **Gantry Helium - Owl Carousel** but extends it with many useful additional features (e.g. lazy load, timed slides, ...) and also includes slick new designs. **Owl Carousel Neo** is an advanced version of the standard Particle created by [Gantry](http://gantry.org/) and [RocketTheme](https://rockettheme.com/). Furthermore, it provides an easy, user friendly and GUI assisted configuration and integration. In the current revision the following CMSs are supported:
* Joomla
* Wordpress
* Grav

## Prerequisites
* CMS (Joomla, Wordpress, Grav)
* Gantry Templating Framework and Theme

## Download
Choose the correct download for your target platform. The Joomla Plugin System is supported for all Gantry themes globally or locally for the templates Helium and Hydrogen. The latest Particle version is **v1.3.0**.

**Attention:** When migrating from **v1.0.5** or below to **v1.2.0** or higher the existing settings of the Particle will be reset.
___
**Default Particle:**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.particle.only.EN.v1.3.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.particle.only.DE.v1.3.0.zip)

**Legacy Particle - Gantry <5.3.2:**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.particle.only.legacy.EN.v1.3.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.particle.only.legacy.DE.v1.3.0.zip)

**Joomla Plugin - All Templates (Global):**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.j3.global.EN.v1.3.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.j3.global.DE.v1.3.0.zip)

**Joomla Plugin - Hydrogen:**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.j3.hydrogen.EN.v1.3.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.j3.hydrogen.DE.v1.3.0.zip)

**Joomla Plugin - Helium:**
[English](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.j3.helium.EN.v1.3.0.zip) / [German](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/releases/download/v1.3.0/ocn.j3.helium.DE.v1.3.0.zip)
___

## Automatic Installation (Joomla only)
1. Download the Plugin of the *Owl Carousel Neo Particle* for **Hydrogen, Helium or Global** installation.
2. Install it over the Joomla Plugin System.
3. Create or modify the `custom.scss` file located under `/[GANTRY_THEME]/custom/scss` and add the following line `@import "owlcarousel-neo";` at the end. Please check the list below to determine where the template folder for your CMS is located.
4. Don't forget that you have to import the Gantry dependencies within the `custom.scss` file before you import the **Owl Carousel Neo** Particle if not already done. Please use the following statement to import the dependencies file: `@import "dependencies";`

*If you install the plugin globally be aware that the resource location changes to `/media/gantry5/engines/nucleus`*

## Manual Installation
1. Download the **Default or Legacy Package** of the *Owl Carousel Neo Particle*. If you are using Gantry **<5.3.2** please use the **Legacy Package** for compatibility reasons.
2. Extract the files.
3. Copy the `.html.twig` and the `.yaml` file to your particle folder `/[GANTRY_THEME]/custom/particles`. Please check the [listing](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry#cms-template-folder) below to determine where the template folder for your CMS is located.
4. Copy the `.js` file to the folder `/[GANTRY_THEME]/custom/js`. Create the folder if it does not exist.
5. Copy the `.scss` file to the folder `/[GANTRY_THEME]/custom/scss`. Create the folder if it does not exist.
6. Create or modify the `custom.scss` file located under `/[GANTRY_THEME]/custom/scss` and add the following line `@import "owlcarousel-neo";` at the end.
7. Don't forget that you have to import the Gantry dependencies within the `custom.scss` file before you import the **Owl Carousel Neo** Particle if not already done. Please use the following statement to import the dependencies file: `@import "dependencies";`

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

Many of the provided options are directly passed over to the [OwlCarousel2 API](https://owlcarousel2.github.io/OwlCarousel2/docs/api-options.html). Please check out the link to find out more about the available options.

Please also take a look at the [OwlCarousel2 demo page ](https://owlcarousel2.github.io/OwlCarousel2/demos/demos.html) which provides many useful hints on how the carousel plugin works. Many of the existing options are already included in **Owl Carousel Neo** but if you are desperately missing a feature. Please [open an issue](https://github.com/thexmanxyz/Owl-Carousel-Neo-Gantry/issues/new) with your feature request.

If you need a list of all supported API [options](https://owlcarousel2.github.io/OwlCarousel2/docs/api-options.html) for the responsive mode of the carousel, please [visit this page](https://owlcarousel2.github.io/OwlCarousel2/demos/responsive.html) and scroll to the bottom.
 
## Supported Parameters, Particle Options and Features
* All settings of the original Particle are included and compatible
* Updated to latest version of [Owl Carousel 2](https://owlcarousel2.github.io/OwlCarousel2/)
* Supports most of the [API options](https://owlcarousel2.github.io/OwlCarousel2/docs/api-options.html) offered by Owl Carousel 2
* Four new basic alignment styles for the slider
* Two themes (black or white) for the new styles
* Default Helium style with many additional settings (dots, navigation and text)
* Lazy and responsive loading of images included
* Timing of slides (annual or one-time)
* Seven different control colors (independently per control type)
* Dot navigation alignment
* Configuration of navigation arrows
* Full responsive configuration of all controls
* Overlay image improvement
  * all six Helium overlays included
  * five new overlays
  * or use accent overlay of current template
* Border radius for buttons, dots underlay and carousel (square or round)
* Link can be applied to title and slide as well
* Slide button can be "replaced" by the title link
* Delay the loading of carousel controls
* Option to define JS run time
* JS priority and placement (head or footer)
* JS configuration
  * Remote, Local and Default
* JS execution
  * Asynchronous
  * Deferred

If you need more information on how Owl Carousel 2 works please mind also these resources:
 * [General Documentation](https://owlcarousel2.github.io/OwlCarousel2/docs/started-welcome.html)
 * [API Options](https://owlcarousel2.github.io/OwlCarousel2/docs/api-options.html)
 * [Demo Page](https://owlcarousel2.github.io/OwlCarousel2/demos/demos.html)

Most of the settings outlined within the API options are also supported by this Particle. Even though some of them are named differently to reflect their real behavior. Please also check the field descriptions in the Particle which offer more information about each option.

## Showroom
Insight of the *Owl Carousel Neo - Gantry Particle* configuration:

**Backend (1)** - *[General](/screenshots/backend_general_1.png)*

![1](/screenshots/backend_general.png)


**Backend (2)** - *[Look](/screenshots/backend_look.png)*

![2](/screenshots/backend_look.png)


**Backend (3)** - *[Behavior](/screenshots/backend_behavior_1.png)*

![3](/screenshots/backend_behavior_1.png)


**Backend (4)** - *[Behavior Responsive](/screenshots/backend_behavior_2.png)*

![4](/screenshots/backend_behavior_2.png)

**Backend (5)** - *[Animate](/screenshots/backend_animate.png)*

![5](/screenshots/backend_animate.png)

**Backend (6)** - *[Controls](/screenshots/backend_controls.png)*

![6](/screenshots/backend_controls.png)

**Backend (7)** - *[Slides (1)](/screenshots/backend_slides1.png)*

![7](/screenshots/backend_slides1.png)

**Backend (8)** - *[Slides (2)](/screenshots/backend_slides2.png)*

![8](/screenshots/backend_slides2.png)

**Backend (9)** - *[Timing](/screenshots/backend_timing.png)*

![9](/screenshots/backend_timing.png)

**Backend (10)** - *[API](/screenshots/backend_api.png)*

![10](/screenshots/backend_api.png)
___

A few example configurations which show the new design of the Particle:

**Frontend (1)** - *[Demo 1 - Black Mode](/screenshots/frontend_demo1.png)*

![9](/screenshots/frontend_demo1.png)

**Frontend (2)** - *[Demo 2 - Black Mode](/screenshots/frontend_demo2.png)*

![10](/screenshots/frontend_demo2.png)


**Frontend (3)** - *[Demo 3 - White Mode](/screenshots/frontend_demo3.png)*

![11](/screenshots/frontend_demo3.png)


**Frontend (4)** - *[Demo 4 - White Mode](/screenshots/frontend_demo4.png)*

![12](/screenshots/frontend_demo4.png)

**Frontend (5)** - *[Demo 5 - Helium-based](/screenshots/frontend_demo5.png)*

![13](/screenshots/frontend_demo5.png)

**Frontend (6)** - *[Demo 6 - Helium-based](/screenshots/frontend_demo6.png)*

![14](/screenshots/frontend_demo6.png)

**Frontend (7)** - *[Demo 7 - Helium-based](/screenshots/frontend_demo7.png)*

![15](/screenshots/frontend_demo7.png)

## Future Tasks
- [ ] Add more OwlCarousel2 API options / events / callbacks if necessary.

## Known Issues
None

## Dependencies
[Gantry Framework](http://gantry.org/)

[Helium Template](https://github.com/gantry/gantry5)

[Owl Carousel 2](https://owlcarousel2.github.io/OwlCarousel2/)

## Credits
Thanks to the [Gantry](https://github.com/gantry) team for providing a modern templating framework.

## by [thex](https://github.com/thexmanxyz) | [gantryprojects](https://gantryprojects.com)
Copyright (c) 2020, free to use in personal and commercial software as per the [license](/LICENSE).
