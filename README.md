JavaScript Unobtrusive ARIA Announce Method for Screen Reader Support
===

The Unobtrusive ARIA Announce Method is a vanilla JavaScript copy of the AccDC Announce Method that is built into the AccDC API. 

The code creates an unobtrusive Announce method that can be executed from within any web technology to announce string messages or DOM node content as needed for any purpose, and automatically tracks and parses repetitive message strings in the case of rapid fire implementations such as within live chat applications.

Moreover the Announce method is also automatically prototyped to the String object, so any string object or string variable can be announced automatically for screen reader users by using the simple statement syntax: stringVariable.announce();

When the AccDC API is loaded, all of this functionality is already included, however this particular implementation has no external dependencies and can be adapted for inclusion within any library or framework.

Support for the Unobtrusive ARIA Announce Method has been verified using all of the following combinations:

* Using NVDA and JAWS 11+> in IE8 with Win XP.
* Using NVDA and JAWS 12+> in IE 11 with Win7.
* Using NVDA and JAWS 14+> in IE 11 with Win8+>.
* Using NVDA and JAWS 12+> in FF with Win XP, Win7, Win8, and Win10.
* Using Voiceover in Safari with iOS on the iPhone/iPad.

Distributed under the terms of the Open Source Initiative OSI - MIT License.

Developed and maintained by: Bryan Garaventa https://www.linkedin.com/in/bgaraventa
Or on Twitter at https://twitter.com/bryanegaraventa

Related projects:
-----

The Accessibility Tree - A Training Guide for Advanced Web Development: https://github.com/accdc/training

The ARIA Role Conformance Matrices: https://github.com/accdc/aria-matrices

AccDC API
Standalone: https://github.com/accdc/accdc
For jQuery: https://github.com/accdc/accdc-jquery
For Dojo: https://github.com/accdc/accdc-dojo
For MooTools: https://github.com/accdc/accdc-mootools

AccDC Bootstrap
Standalone: https://github.com/accdc/bootstrap
For jQuery: https://github.com/accdc/bootstrap-jquery
For Dojo: https://github.com/accdc/bootstrap-dojo
For MooTools: https://github.com/accdc/bootstrap-mootools

AccDC Technical Style Guide and Coding Arena
For AccDC Standalone and jQuery: https://github.com/accdc/tsg
For Dojo: https://github.com/accdc/tsg-dojo
For MooTools: https://github.com/accdc/tsg-mootools