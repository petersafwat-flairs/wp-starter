
## Boustan Website

Based on **Bedrock** , **Sage** , WP Multisite and WPML.

Bedrock is a modern WordPress stack that helps you get started with the best development tools and project structure. https://roots.io/bedrock/
Sage is WordPress starter theme with a modern development workflow. https://roots.io/sage/


## Installation

- Create new directory inside laragon(Or Any Web Server) directory named "alboustan.
- Clone Repository inside directory.
- Restart Laragon to pickup the new directory and make sure the docroot of the new vhost created pointing to /web directory.
- Make sure .env file contains the plugin keys and DB credentials.
- Import DB using the following command :
    ```sh
        mysql -u root -p dbname < dbfile.sql
    ```
- Run in terminal in root directory:
    ```sh
        composer install
    ```
- Run in terminal in /web/themes/boustan directory:
    ```sh
      yarn
    ```
- Run in terminal in /web/themes/boustan directory:
    ```sh
      composer install
    ```
- Run in terminal in /web/themes/boustan directory:
  ```sh
      yarn build
  ```      
- Run in terminal in /web/themes/boustan directory to start development environment:
  ```sh
      yarn start
  ``` 
- Enjoy...

## Requirements

- PHP >= 7.2
- Composer
- Yarn >= 1.22.0
