# Drupal 9 Portfolio Website

This is a Drupal 9 portfolio project showcasing custom theming, essential modules, and front-end development best practices using Twig and Bootstrap.

## Tech Stack

Drupal Version: 9.5.0<br/>
PHP Version: 8.1<br/>
Theme: olivero_child (Child of Olivero)<br/>
Twig Templates: Customized html.html.twig, page.html.twig<br/>
Modules Used:<br/>
  [Token](https://www.drupal.org/project/token)<br/>
  [Pathauto](https://www.drupal.org/project/pathauto)<br/>
Styling & Assets:<br/>
  Custom images/, js/, and css/ folders<br/>
  Bootstrap included in js and cs folder<br/>
Theme Debugging: Enabled<br/>
Global Styling: Disabled for parent Olivero theme<br/>

## Project Highlights<br/>

### Custom Theme: olivero_child<br/>

Built as a sub-theme of the default Olivero<br/>
Custom Twig templates used to override default layout<br/>
Included own CSS/JS/Images<br/>
Disabled global styling from parent theme for full control:<br/>
  yaml<br/>
libraries-override:<br/>
    olivero/global-styling: false<br/>

Content Types<br/>
Teacher<br/>
Fields: Name, Subject, Profile Image<br/>
Student<br/>
Fields: Name, Teacher, Grade<br/>

Taxonomy<br/>
Subject vocabulary created<br/>
Used as a referenced field in the Teacher content type<br/>

Views<br/>
View for listing Teachers by Department<br/>
View for listing Students with related Teachers<br/>
Views display blocks integrated into custom regions (e.g. sidebar)<br/>

Custom Regions<br/>
Defined in olivero_child.info.yml:<br/>
regions:<br/>
  header: 'Header'<br/>
  content: 'Content'<br/>
  sidebar: 'Sidebar'<br/>
  footer: 'Footer'<br/>

#### Screenshots
<img width="1920" height="1140" alt="Screenshot 2025-07-25 150156" src="https://github.com/user-attachments/assets/5828ec5c-192d-421f-bae7-6993bf55c42c" />


