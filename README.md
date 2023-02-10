# Installation

---

## Installation
From the root folder, type `npm install`.

## Tasks
Typing `gulp --tasks`, or simply `gulp`, will render a list of tasks included in `gulpfile.js`. Tasks such as `build` and `serve` invoke other tasks and are executed in `<series>`.

Each task can be run on its own. For example, if all you want to do is validate your HTML, you can type `gulp validateHTML`.

## Running the Project

During development, run `gulp serve`, which runs multiple development-related tasks, then launches your default browser and reloads on file changes.

For production-ready projects, run `build`, which creates a folder called `prod`. This is the folder you’d upload to your server if you were going live with your project.
