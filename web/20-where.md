## Where we are <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

<!-- .element: class="fragment" --> ![Let's be honest](images/20-where/honest.png)

<!-- .element: class="fragment small" --> _**GAP Analisys**: In management literature, gap analysis involves the comparison of actual performance with potential or desired performance_


## The good parts <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

- <!-- .element: class="fragment" --> Joomla is a full multilingual CMS
- <!-- .element: class="fragment" --> Solid object-oriented foundation
  - MVC pattern
  - "Component - Module - Plugin" triad
- <!-- .element: class="fragment" --> A solid core to develop any system
- <!-- .element: class="fragment" --> Huge ecosystem of extensions
- <!-- .element: class="fragment" --> Rich, loyal, and diverse community


## Not so great <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

_Joomla is not a Headless CMS_

<!-- .element: class="fragment" --> Joomla has tight integration with Html views

<!-- .element: class="fragment" --> No WebService / RESTful API

<!-- .element: class="fragment" --> No Command Line Interface (CLI)

Note:
Build your own CLI or RESTful API.
You can write your own CLI and RESTful API... but
... and it is not going to be.


## Not so great <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

_Mobile support based on responsive design 1.0._

<!-- .element: class="fragment" --> Bootstrap 2.3 - jQuery 1.12

<!-- .element: class="fragment" --> Chosen 1.6, Mootools 1.6, etc.

Note:
TIP: Avoid them as much as possible.
Always Html, jQuery, Css... or die(1);


## Not so great <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

![Chrome Dev Tools](images/20-where/dev-tools.png) <!-- .element: style="width: 60%" -->


## Not so great <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

_Component, Modules and Plugins_

- <!-- .element: class="fragment" --> Any extension can add CSS and Scripts
- <!-- .element: class="fragment" --> Hugh number of HTTP requests
- <!-- .element: class="fragment" --> Slow loading time


## Not so great <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

_Old MVC implementation_

<!-- .element: class="fragment" --> `JControllerForm`, `JControllerAdmin`, `JControllerLegacy`, `JModelLegacy` (state), `JViewLegacy`, etc

<!-- .element: class="fragment" --> HTTP v1 GET - POST protocol (pre-Ajax)

Note:
This is a problem of all the current generation of CMSs


# GAP Analisys <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

Where we want to be


## New clients <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

- Mobile Apps
- Progressive Web Apps
- (Offline) Desktop Browser


## Backwards compatibility <!-- .slide: data-background-image="images/05-who/joomla_logo.png" data-background-size="auto auto" data-background-position="100% 5%" -->

- Reuse the current stack as much as possible
- Protect the current investment
- Extend the life of the current technology
