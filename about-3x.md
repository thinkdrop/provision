# About Provision 4.x

## History

Provision 4.x is a total rewrite of [Aegir Provision](https://www.drupal.org/project/provision "Provision on Drupal.org") using Symfony Console and other components.

Before 4.x, Provision was a Drush extension, so it followed the Drupal module version scheme: The main development branch was 7.x-3.x

Once Drush announced that new versions will only support Drupal 8, we knew it was time to get Provision off of Drush.

To do this, Symfony Console was the obvious choice.

## Goals

### 4.0.x

In 4.0.x, the main goal is command parity with Provision 7.x-3.x. If we can match the provison drush commands that exist, we can swap out the CLI in Aegir Hostmaster 7.x to use Provision 4.x instead.

### 4.1.x

???

## Architecture Inspiration

Symfony Console apps are flourishing. We were able to take inspiration from the following projects:

* [Composer](https://github.com/composer/composer)
* [Drush](https://github.com/drush-ops/drush)
* [DrupalConsole](https://github.com/hechoendrupal/drupal-console)
* [Robo](http://robo.li/)
* [Terminus](https://github.com/pantheon-systems/terminus)
* [Acquia BLT](https://github.com/acquia/blt)
* [PlatformSH CLI](https://github.com/platformsh/platformsh-cli)
* [Terra CLI](https://github.com/terra-ops/terra-cli)

## MORE COMING SOON



