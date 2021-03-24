Create (multiple) WordPress plugins that use React, TypeScript, and object-oriented PHP in a fully customizable Docker development environment, commited in a monorepo.

Wow, I didn't know the WordPress plugin development could look like this!

🚀 Instant no-config plugin creation with create-wp-react-app 🔥

GitHub stars Join on Slack codecov GitLab CI/CD

🤗 Why WordPress plugin development is fun with WP React Starter
Everyone tells us: WordPress plugins are a mess. Our answer is always: Let’s take this opportunity to make the system that powers every third website on the Internet better.

With WP React Starter we have created a modern WordPress development boilerplate which contains everything you are used to from modern web development projects:

React Frontend for reactive user interfaces (with PHP fallback for server-side rendering) - React is a part of WordPress since the Gutenberg release
TypeScript for typesafe frontend development
PHP in an object-oriented style with namespaces for better backend code
Docker development environment to develop all you plugins without manual setup steps
CI/CD integration for automated code quality checks and release management (publish on wordpress.org or wherever you want)
Does that sound like crappy WordPress plugin development or what you really have been looking for for your plugins for a long time? Let's start today with your first WordPress plugin! Create it within 5 minutes, thanks to our CLI create-wp-react-app

Client-Side Features
Familiar React API & patterns (ES6) with TypeScript

React with Babel env preset + Hooks
MobX for state management
webpack build for assets
core-js puts automatically needed polyfills to your distribution files
Sourcemap generation for debugging purposes (CSS and TypeScript files)
SASS stylesheets compiler (.scss files) for next-gen CSS
PostCSS for transforming SCSS (including autoprefixing) to CSS
Minified sources automatically generated for production (JS, CSS)
Grunt for automation tasks (build the installable plugin)
ESLint predefined configuration for proper linting
TypeDoc for JavaScript Documentation
WP HookDoc for Filters & Actions Documentation
Translation (i18n) with automatic generation of .pot files
Add-On Development (multiple WordPress plugins), based on a predefined utils package that allows you to share TypeScript types across plugins.
Admin backend components, in this case an own page with a button (admin.ts)
Frontend components, in this case a simple widget (widget.ts)
