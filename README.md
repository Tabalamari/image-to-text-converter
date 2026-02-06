# ImageToTextConverter

## Description: 

A web application built with Angular that uses a public API (e.g., API Ninjas) to extract text from user-uploaded images (JPEG/PNG, up to 2 MB). The app includes image preview, displays extracted text, and allows copying the result to the clipboard.

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.19.

## API Key Setup

This project uses the **API Ninjas** service for image-to-text extraction.

To run the project locally:

1. Create an account at https://api-ninjas.com
2. Get your API key
3. Open the file:

   src/environments/environment.ts

4. Replace the placeholder value:

   apiNinjasApiKey: 'PASTE_YOUR_API_KEY_HERE'

! Note:  
API keys cannot be fully hidden in frontend applications.  
For production use, the API call should be moved to a backend service.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
