# TODO: Automate tests

Running manual tests is very expensive. The test cases below should be considered for automation!

# Test Cases for JS EPP package

Any failure to those test cases should be reported to EPP or other Eclipse.org project causing the error, and shared with EPP mailing-list.

There is big room for improvements in these test-cases (more test-case, more detailed steps...). Feel free to contribute!

## Startup

. Startup package on a new workspace
. Check: error log doesn't report issue

## New Static Web Project enables HTML, CSS and JS

. Create a new Static Web Project
. Create/Open an HTML file => Check completion, highlighting and other features are enabled
. Create/Open an CSS file => Check completion, highlighting and other features are enabled
. Create/Open an JS file => Check completion, highlighting and other features are enabled

## Import an existing JS project

. File > Open Projects from Filesystem...  Pick a JS project such as mathjs (on GitHub), proceed
. Check: Project has the JavaScript nature and right content

## Editing JS

. From the mathjs project above, pick an interesting .js file
. Check: syntax highlighting, completion... are enabled and work as expected

## Node/NPM actions

. From the mathjs project above
. Check: Run As actions are available on projet, package.json and work as expected

## Debug

. From the mathjs project above
. put a breakpoint, start debug
. Check: breakpoint is hit, values are visibile, step into/over and debugger in general works