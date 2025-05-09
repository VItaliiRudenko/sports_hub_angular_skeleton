# AngularjsFeGenaiPlgrnd

## Project Description

This is a draft pet project for testing Generative AI on different software engineering tasks. It is planned to evolve and grow over time. Specifically, this repo will be a Angular playground.
For now, we only have the:
[Ruby on Rails](https://github.com/rtriska/ruby_be_genai_plgrnd),
[PHP](https://github.com/rtriska/php_be_genai_plgrnd),
[Java](https://github.com/rtriska/java_be_genai_plgrnd),
[.Net](https://github.com/rtriska/net_be_genai_plgrnd)
applications as a Back-End, but we plan to extend it to other technologies in the future.
This application can be started with a `docker compose` using the Back-End applications mentioned.

The application's legend is based on the sports-hub application description from the following repo: [Sports-Hub](https://github.com/dark-side/sports-hub).

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Dependencies


- Rancher (for container orchestration and management)

You can install Rancher by following the [Rancher Quick Start Guide](https://ranchermanager.docs.rancher.com/pages-for-subheaders/quick-start-guide).

## Setup and Running the Application

### Clone the Repositories

To run the web application with the back-end, clone the following repository within the same folder:

```sh
Ruby
git clone git@github.com:rtriska/ruby_be_genai_plgrnd.git

PHP
git clone git@github.com:rtriska/php_be_genai_plgrnd.git

Java
git clone git@github.com:rtriska/java_be_genai_plgrnd.git

.Net
git clone git@github.com:rtriska/net_be_genai_plgrnd.git
```

### Change Frontend


If you are using Rancher, you can import your existing `docker-compose.yml` file into Rancher to create the necessary workloads. In the Rancher UI, go to your cluster, select "Deploy from Compose", and upload your compose file. Adjust the frontend service path as needed before importing.


### Deploy with Rancher

1. Open the Rancher UI and navigate to your cluster.
2. Use the "Deploy from Compose" option to import your `docker-compose.yml` file, or manually create workloads for the frontend and backend services using the Dockerfiles provided.
3. Adjust environment variables, ports, and volumes as needed in the Rancher UI.
4. Start the workloads and monitor their status from the Rancher dashboard.


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## License

Licensed under either of

- [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)
- [MIT license](http://opensource.org/licenses/MIT)

Just to let you know, at your option.

## Contribution
Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in your work, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.

**Should you have any suggestions, please create an Issue for this repository**
