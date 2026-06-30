# htan-library

VueJS library web application for FIT5032 Assessed Lab 2.

The app demonstrates:

- importing local JSON files
- computed properties
- built-in Vue directives
- `v-for`, `v-if`, `v-else`
- attribute binding
- class binding
- style binding
- highlighting the author `George Orwell`

## Run the App

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the localhost URL shown in the terminal:

```text
http://127.0.0.1:5173/
```

## Build Check

To check that the Vue app builds successfully:

```bash
npm run build
```

## Important Files

- `src/components/JSON.vue` - main Lab 2 component with Activities 1-13.
- `src/assets/json/authors.json` - author data used by the app.
- `src/assets/json/bookstores.json` - bookstore data used by the app.
- `src/App.vue` - renders the `JSON.vue` component.
- `src/assets/main.css` - global app styling.

## Lab 2 Features

- Activity 1 imports `authors.json` and `bookstores.json`.
- Activities 2-5 use computed properties to filter, map, and find author data.
- Activities 6-12 render arrays and objects with Vue directives.
- Activity 13 toggles message visibility with `@click`, `v-if`, and `v-else`.
- Task 2.2 highlights `George Orwell` using `:title`, `:class`, and `:style`.

## Screenshot Guide

For the PDF report, capture:

1. Multiple screenshots showing activities 1-13 completed in the running VueJS app.
2. A screenshot showing the George Orwell author-highlight functionality.
3. A screenshot of `src/components/JSON.vue` showing the binding code.
4. A screenshot of the GitHub commit/history page after pushing the project update.
