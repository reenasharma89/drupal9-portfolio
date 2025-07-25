# Drupal 9 Portfolio Website

This is a Drupal 9 portfolio project showcasing custom theming, essential modules, and front-end development best practices using Twig and Bootstrap.

## Tech Stack

Drupal Version: 9.5.0
PHP Version: 8.1
Theme: olivero_child (Child of Olivero)
Twig Templates: Customized html.html.twig, page.html.twig
Modules Used:
  [Token](https://www.drupal.org/project/token)
  [Pathauto](https://www.drupal.org/project/pathauto)
Styling & Assets:
  Custom images/, js/, and css/ folders
  Bootstrap included in js and cs folder
Theme Debugging: Enabled
Global Styling: Disabled for parent Olivero theme

## Project Highlights

### Custom Theme: olivero_child

Built as a sub-theme of the default Olivero
Custom Twig templates used to override default layout
Included own CSS/JS/Images
Disabled global styling from parent theme for full control:
  yaml
libraries-override:
    olivero/global-styling: false

#### Screenshots
<img width="1920" height="1140" alt="Screenshot 2025-07-25 150156" src="https://github.com/user-attachments/assets/5828ec5c-192d-421f-bae7-6993bf55c42c" />


