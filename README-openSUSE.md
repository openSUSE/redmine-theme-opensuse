Add customizations to `src/sass/components/_opensuse.scss`.

Overwrite default variables set by PurpleMine2 in `src/sass/_opensuse_variables.scss`.

Avoid changes in other files to avoid conflicts with upstream.

To build:

- `npm i`
- `node_modules/grunt/bin/grunt`

Expect a gazillion of warnings.

Currently the build artifacts are committed into the repository, to further avoid conflicts we should consider building during the package build instead.

The package lives at https://build.opensuse.org/package/show/openSUSE:infrastructure:redmine/redmine-theme-opensuse-ng.
