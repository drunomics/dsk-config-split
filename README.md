# DSK config split

Adds suiting default config for config_split and [drunomics/drush-phapp-env-mode](https://github.com/drunomics/drush-phapp-env-mode).

## Usage

- Install and enable the module - on all environments.

- Add development modules as needed to your site's `config_split.config_split.development.yml`:

    module:
      default_content: 0
      devel: 0

- Put environment-mode specific config into `config/env/development` or `config/env/production`.
