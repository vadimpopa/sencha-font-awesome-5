# font awesome 5

In order to have only one font awesome version loaded in the page, this package replaces almost completely sencha's font awesome v4 located at ext/packages/font-awesome.

Use steps:

1. Copy the content of this repo into `project/packages/local/font-awesome`. This is just to have a local copy in your project. Local copy is needed, because some build enviroments may be configured on each production build to copy ext framework from remote into the project which will revert back to the sencha's font awesome package.

2. While being in 1 run `sencha package build` - this will copy and replace needed files from `project/packages/local/font-awesome` into `project/ext/packages/font-awesome`. For more details see `project/packages/local/font-awesome/build.xml`. Generally this command must be run only once, after step 1, but if in production you install ext on every build, you must run step 2 as well to copy the FA5 files.

3. Build your app