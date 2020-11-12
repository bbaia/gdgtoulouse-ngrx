# GDG Toulouse "Redux with Angular & ngrx"

Code from the GDG Toulouse talk "Redux with Angular & ngrx" ([Slides](http://slides.com/brunobaia/redux-with-angular-ngrx) & [Video (FR)](https://www.youtube.com/watch?v=IBFXLgCw5Ek)).

:warning: For an up-to-date version of the TodoMVC app using Angular & NgRx, see [`bbaia/todomvc-angular-ngrx`](https://github.com/bbaia/todomvc-angular-ngrx). :warning:

# Demo

The code is splitted in 6 commits:

- **Initial commit**: Initializes a basic project with packages `ngrx/store` & `ngrx/store-devtools`.
- **effects: initialization**: Introduces `ngrx/effects` with a faked network request to load the to-do list.
- **effects: add loading state**: Adds a loading state to the application.
- **entity**: Introduces `ngrx/entity` to reduce & simplify the management of entity collections.
- **router: initialization**: Introduces `ngrx/router-store` that connect the Angular Router with the store.
- **router: use router state**: Uses the URL information as part of the application state.

## Development server

This project was generated with [Angular CLI](https://github.com/angular/angular-cli).

Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
