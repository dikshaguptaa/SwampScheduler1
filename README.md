# 🐊 Swamp Scheduler 📆

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Issues](https://img.shields.io/github/issues/ufosc/SwampScheduler)
![License](https://img.shields.io/github/license/ufosc/SwampScheduler)
![Contributors](https://img.shields.io/github/contributors/ufosc/SwampScheduler)
![Last Commit](https://img.shields.io/github/last-commit/ufosc/SwampScheduler)
![Forks](https://img.shields.io/github/forks/ufosc/SwampScheduler)
![GitHub stars](https://img.shields.io/github/stars/ufosc/SwampScheduler?style=social)


An open-source web app developed to help students at the University of Florida plan for classes next
semester. [It's available now!](https://osc.rconde.xyz/)

Made with :heart: by [UF's Open Source Club](https://ufosc.org) ([@ufosc](https://github.com/ufosc/)).

## Table of Contents

- [Features](#Features)
- [Setup](#Setup)
- [Usage](#Usage)
- [Contribution](#Contribution)
- [Maintainers](#Maintainers)
- [License](#License)

## Features

- **Course Explorer:** Explore courses offered at the University of Florida
    - Find courses by *course code*, *title*, or *instructor*
- **Course Selections:** Make multiple courses selections with backup options.
    - Pick which classes you want (and remove which sections you don't)
- **Schedule Generator:** View and compare all the possible schedules and pick the one that fits your needs and wants.
    - View color-coded schedules that show what your day-to-day ~~struggle~~ workload will be

## Installation

### Prerequisites

This is to be done in command prompt.
Make sure to navigate to the desired directory you want to set up the project in using:
```shell
cd path/to/directory
```

Make sure to have `npm` and 'nodejs' installed.

```shell
sudo apt install nodejs
sudo apt install npm
```

### Setup

#### Clone the Repo

Clone the repository to your local machine:

```shell
git clone <repository-url>
```

#### Install the Dependencies

Enter the SwampScheduler directory, then navigate to the app folder and install the necessary dependencies (React, Tailwind CSS, etc.):

```shell
cd SwampScheduler/app
npm install
```

Install Prettier: Prettier is a code formatter that make sure the coding style is consistent.
```shell
npm install --save-dev prettier
```
Vulnerabilities: There might be some vulnerabilities within the package, so it is necessary run
  ```shell
  npm audit
  ```
This may not be necessarily important for everyone depending on their devices, so follow the instructions given by the terminal.

Run Prettier:
  ```shell
  npx prettier --write
  ```

### Usage:

In the web-app directory:
- **Development:** Run `npm run dev` to run the development server locally (with hot reloading).
  ```shell
  npm run dev
  ```
- **Production:** Run `npm run build` to build the app to `/app/dist`.
  ```shell
  npm run build
  ```
- Ensure that `dist` is a file in the `app` folder using `dir`
  ```shell
  dir
  ```

## Contribution

Before you can make good contributions, you need to know a little bit about what we're using and how the web-app works.
After that, you should be ready to get your hands dirty!

### What We're Using (our Tech Stack)

This project is built using a variety of exciting technologies, including:

- **TypeScript:** The JavaScript programming language with a typing system (for `Course` objects, etc.)
    - Familiarize yourself with [TypeScript’s documentation](https://www.typescriptlang.org/docs/) to understand the
      basics and best practices.
- **React:** A JavaScript library for building dynamic user interfaces.
    - The [official React documentation](https://reactjs.org/docs/getting-started.html) is a great resource for learning
      about component-based architecture and state management.
- **Tailwind CSS:** A utility-first CSS framework.
    - Review the [Tailwind CSS documentation](https://tailwindcss.com/docs) for understanding utility-first styling and
      theming.
- **Vite:** Simply used as a build tool and development server.
    - Learn how to set up, configure, and use Vite from [Vite’s official guide](https://vitejs.dev/guide/).

### How to Contribute

1. Fork the repository to your GitHub account.
2. Clone your fork to the local machine.
3. Create a branch for the changes.
4. Make the changes on the local branch.
5. Test to ensure the code passes all existing tests and create new tests when necessary.
6. Commit the changes in a clear message.
7. Push the changes to the GitHub fork.
8. Submit a pull request by going to the original repo and submit a PR by linking it to the relevant issue.
9. Be responsive to comments or reach out to repo owners to let them know of any changes.

### Follow The Projects' Style
Make sure the the following components follow the codes current format style.
- Indentation
- Naming Conventions
- Comments
- Code Structure

### How It All Works

Be sure to read (yes, read) some of our code. Everything works better when we all understand what we're talking about.

[SwampScheduler's documentation](https://docs.ufosc.org/docs/swamp-scheduler) is a work-in-progress.

### Give Me Something To Do!

There are lots of things that can be done, and a lot of them are on our back-burner.

Take a look at what [issues (enhancements, bug fixes, and ideas)](https://github.com/ufosc/SwampScheduler/issues) are
open. If you find one you like, assign yourself and
be sure to talk to other people about what you're doing (it helps us, the [maintainers](#Maintainers) best allocate our
resources).

## Maintainers

We're your Technical Leads, Product Managers, and Mentors all-in-one:

- [Robert Conde](https://github.com/RobertConde)
- [Brian Nielsen](https://github.com/bnielsen1)

## License

GNU Affero General Public License v3.0
