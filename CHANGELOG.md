# Changelog

** 2.3.1

* Adds `--dev` flag to `npm update` when running `create-project` with the `--setup` flag so that devDependencies are installed.

** 2.3.0

* Automatically configures `disabledFileKey` for projects that have that option in `app.js` (not present in the standard apostrophe-boilerplate but we use it in our own in-house boilerplate). See the `uploadfs` documentation for the benefits.

** 2.2.0

* Automatically generates session secret, if the boilerplate has a placeholder for it (and apostrophe-boilerplate now does).

** 2.1.5

* Shortnames are not titles, data/local.js doesn't have an example worth copying in and isn't essential in dev

** 2.1.4

* Uses `npm update` rather than `npm install` so that we're not married to an ancient patchlevel of Apostrophe from the start when birthing a new project.

** 2.1.3

* Fixed pieces generator.

** 2.1.1-2.1.2

* Removed bad dependencies and bad patches.

** 2.1.0

Added commands for widget, piece, and module creation. Updated documentation.
