# dunt
The toy that likes to be pushed

Motivated by increased modern hardware support in the BSDs (particularly OpenBSD), dunt aspires to be a clean window manager and environment for touchscreens and touchscreen-based devices.  Perhaps even a separate distribution optimised for mobile devices.

* Dunt's core should have few dependencies (if any) outwith a full OpenBSD base system with Xenocara.
* Dunt should be reactive, in that it optimises itself for any screen size - large or small.
* The [LICENSE](LICENSE) of dunt and any 3rd-party code should be equal or compatible with the (Open)BSD license.
* [style(9)](https://man.openbsd.org/style) is perpetually à la mode.

Proposed features:

* Minimalist window manager (can we use and extend cwm?)
* Frontend for manipulating dunt and system settings
* Wrapper/frontend for some userland stuff
* On-screen keyboard - this may be a big task, many existing implementations suck - needs researched.
* Web browser

