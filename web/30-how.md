## A recipe for modernity


## The Application Mode

Foto


## The Application Mode

![Grow fast or die slow](images/30-how/intersection.svg)<!-- .element: style="width: 40%" -->

Joomla - Application


## The Application Mode

A single component per page

<!-- .element: class="small fragment" --> `index.php?option=com_content&view=articles&tmpl=component`


## Benefits of the App Mode

- <!-- .element: class="fragment" --> Under control
- <!-- .element: class="fragment" --> No more spagetthi of mixed scripts
- <!-- .element: class="fragment" --> No more modules or plugins
- <!-- .element: class="fragment" --> My code or die(1);


## User Interface

- Mobile Apps
- Progressive Web Apps
- Desktop

_**Holy Grial**: Support of all interfaces with a single code base._


## User Interface

We are in JavaScript (ES6) World.

- Angular / Ionic
- React
- Vue.js

_... and WebComponents are around the corner._

- <!-- .element: class="small" --> Recommended reading: [Stencil](https://stenciljs.com/), the magical, reusable web components compiler.

## UI - Ionic case

_Joocial 9_


## UI - React case

_WordPress Gutenberg_


## UI - Vue.js case

_Joomla Media Manager_


## UI - Progressive Web Apps

Service Workers are already implemented in all major browsers.

- Offline Navigation
- Advanced Cache
- Splash screen
- Lazy (Background) Loading
- Web Push Notifications
- Theming
- Home Screen Management

XT Workbox

## UI - Sample extension

Stack Ideas' Easy Articles

[stackideas.com/easyarticles](https://stackideas.com/easyarticles)

## The communication UI-Backend

Our App must communicate in some way.

- Reduce the number of requests
- Semantic communication
- Microservices


## WebServices 911

Implement any kind of WebService

- Symfony 4 / Silex
- Laravel Lumen
- SlimFramework

FOF Json DataView


## The Domain

Choose the right stack:

- Joomla Models
- FOF Models
- Laravel Eloquent
- Doctrine
- Your own flavour


## CMS Agnostic Layer

Define a "The World as I See It"

- Be ready for Joomla 3 / 4 ... X
- Build Interfaces to the World
- Learn from other CMSs
  - Bolt
  - Grav
  - October
  - PrestaShop
  - WordPress


## A modern toolbox

_Configuration Management_

- YML
- JSON is fine

Avoid XML as much as possible (Run for your life).


## A modern toolbox

Automate your test s- always -

- Unit Testing (phpunit / jasmine)
- Integration Testing
- End-to-end testing (Protractor)

## A modern toolbox

Composer and Node are your friends.


## A modern toolbox

Build tool

Webpack is my pal.

Avoid Phing as much as possible (Run for your life).
