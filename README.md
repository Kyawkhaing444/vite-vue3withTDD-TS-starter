# Vue 3 + Typescript + Vite + TDD
Setting up the side project boilerplate with Vite is little tedious rather than setting project up with Vue cli.
Vue cli use webpack as the module bundler, it is kind of slow in the development process. Therefore, I create this vue side project boilderplate with vite for the best development experience.
## Basic Skeleton
In basic skeleton, I use **vuex**, **vue_router** and data fetching with **swrv**.
## Code Style
For code style, I use editorconfig, prettier, and eslint. For the linter, I use all of the plugin [ essential, strongly-recommended, recommended] of Vue3 style guideline. And typescript plugin and jest. Finally, I use **husky** as pre-commit hook to enforce validation of the linting standard and coding format of the project.
## Git Commit Message Conventions
For the commit conventions, I use **Commitizen** and **husky + commitlint** to enforce validation in the commit message.
Usage for the commit - **yarn cz** instead of **git commit**.
## Unit Test
**vue-test-utils**, **jest**, **vue-jest**, **ts-jest**
Finally, I use husky as the pre-push hook to validate all the testing during pushing to the remote repo.
