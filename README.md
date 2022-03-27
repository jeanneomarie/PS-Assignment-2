# Software Design - Assignment 2 ![Deadline 07.04.2022 17:00](https://img.shields.io/badge/deadline-07.04.2022%2017%3A00-blue.svg "Deadline: 07.04.2022 17:00")
This is the second assignment of the Software Design laboratory.

## Resources
The feature descriptions may be found in [this presentation](https://docs.google.com/document/d/1tVYAyPtw45p4jIwGaeIKsNPpqTvS5VukwBIKkj6pv8A/edit?usp=sharing), whilst the theoretical background may be found in [this presentation](https://docs.google.com/presentation/d/1fP1jNASx-uFSlEHTI0pQbam6Spi7KoE5stC8ININkjs/edit?usp=sharing).

## Design Constraints
 * MV* architecture (MVC or MVP recommended),
 * Without any backend for persistance,
 * Holding the state purely in memory.

## Recommended Technologies
 * NodeJS,
 * React / Angular / Vue.

## Getting started
 * Install [NodeJS](https://nodejs.org/en/),
 * Run `npm i -g create-react-app` in a command line (installs [Create React App](https://github.com/facebook/create-react-app)),
 * Open a command line in your working directory and run `create-react-app assignment-2`,
 * Move into the newly created `assignment-2` directory (`cd assignment-2`),
 * Run `npm start` to start your application,
 * A web browser should be launched to display the new app (a hello world).

Now you can directly change the code and the application will automatically reload your browser.

## Grading
Minimum requirements for a passing grade:
 * Browser-based U.I.,
 * Feature 1,
 * Clear MV* separation.

Additional requirements:

| Requirement                        | Grade |
|------------------------------------|-------|
| React Router for handling routing  |   6   |
| Feature 2                          |   8   |
| Feature 3                          |  10   |

Bonus requirements:

| Requirement                                                | Points |
|------------------------------------------------------------|--------|
| Prepare and present mockups (picture / wireframe / paper) using for example [Marvel](https://marvelapp.com/)   | 1.0    |
| Use Redux for holding the state                            | 2.0    |
| Use a CSS library (e.g. Bulma, Bootstrap) for styling     | 1.0    |
| Write [component tests](https://facebook.github.io/create-react-app/docs/running-tests#option-2-react-testing-library) for your views | 1.0    | 
