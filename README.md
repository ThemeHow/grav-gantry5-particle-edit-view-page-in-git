Forked from https://github.com/hibbitts-design/grav-gantry5-particle-edit-view-page-in-git



# Gantry 5 'Edit/View Page in Git' Particle for Grav

Particles are small, modular blocks with preset scripting that enable you to add elements to your Grav Gantry 5 pages.

## Installing Particle

Upload `edit_view_page_in_git.html.twig` and `edit_view_page_in_git.yaml` files to your `/user/themes/THEME_DIR/custom/particles` directory. For example, to install in the default Grav Gantry 5 theme Hydrogen copy the two particle files to `/user/themes/g5_hydrogen/custom/particles`. If the `custom` folder does not exist create it.

The perfect companion to this Gantry 5 particle is the [Grav GitSync Plugin](http://www.hibbittsdesign.org/blog/posts/2016-12-22-touchdown-seamless-2-way-syncing-arrives-for-grav).

## Particle Options
!['Edit this Page' options](https://github.com/hibbitts-design/grav-gantry5-particle-edit-page-in-git/blob/master/edit-view-this-page-options.png?raw=true)

## Page Options
Once the particle is installed, Grav pages will support the following Page Header/FrontMatter option:

```
hide_git_repo_link: true    # hide Git Repository edit link for this page, up to but not including the '/pages/...' For example, 'https://github.com/paulhibbitts/grav-skeleton-gantry-oer-content/tree/master'.  
git_repo_link_url: https://github.com/hibbitts-design/grav-skeleton-course-hub/tree/master/pages/01.home   # to override the automatically calculated Git Repository URL
```

## Site Config Options
Once the particle is installed, Grav pages will support the following Site Config option:

```
hide_git_repo_link_pages:    # list of pages to hide Git Repository edit link on
    - login
    - logout                        
```
