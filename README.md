# BADcamp — Living Style Guides in Drupal 8 for Designers and Front-enders

This Drupal site uses the Four Kitchens base theme with Pattern Lab, found at https://github.com/fourkitchens/emulsify. (Formerly fourk)


## Before you start

Install the following dependencies:

  - [Node.js](https://nodejs.org/)

    We suggest using [nvm](https://github.com/creationix/nvm#installation) to [install and use](https://github.com/creationix/nvm#usage) node.js 6.x.

  - [Composer](https://getcomposer.org/download/)

  - [Drush](http://www.drush.org/en/master/install/)

    Composer downloads a version of drush to `build/vendor/bin/drush` if you do not wish to use the global version.

## Installation

1. Clone this repository locally and enter the directory.

  ```bash
  git clone git@github.com:fourkitchens/nyu-wagner.git && cd nyu-wagner
  ```

2. Install PHP dependencies.

   ```bash
   composer install
   ```
   
3. Install JavaScript developer tools into the `fourk` theme for the Drupal instance.

   ```bash
   cd fourk
   npm install
   ```

4. Serve up the Drupal site at `/web`. This project assumes that you have a method of serving up a Drupal site locally.

### What to do if you can't serve up `/web` locally.
- Create a Drupal 8 site using your preferred method
- Copy the `fourk` theme into the `themes` folder.
- Run `npm i` inside `fourk` if you haven't already.
- Install the [Component Libraries}(https://www.drupal.org/project/components) module and enable it.

## Get started

    ```bash
    npm start
    ```
  
This will compile and serve up assets, as well as run a watch task.
