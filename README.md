# ZR Para Media Text Content Recipe Installation Guide

To install the ZR Para Media Text Content Recipe, follow the steps below:

1. Ensure the below has been added to the `composer.json` **installer-paths**:
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-recipe"]
    ```
2. Run `composer require zr/zr-para-media-text-content`
3. Run the following command (within the `/web` directory):

    ```sh
    ddev drush recipe recipes/custom/zr-para-media-text-content
    ```

