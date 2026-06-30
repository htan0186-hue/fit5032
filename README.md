# htan-library

This project is a VueJS app for FIT5032 Assessed Lab 2. It demonstrates
computed properties, built-in directives, attribute binding, class binding, and
style binding in a library web application.

## Run the App

Install dependencies first:

```bash
npm install
```

Start the local development server:

```bash
npm run dev
```

Open the localhost URL shown in the terminal. By default it should be:

```text
http://127.0.0.1:5173/
```

## Build Check

To check that the Vue app builds successfully:

```bash
npm run build
```

## Important Files

- `src/components/JSON.vue` - implements Activities 1-13 and the George Orwell highlight functionality.
- `src/assets/json/authors.json` - author data imported by `JSON.vue`.
- `src/assets/json/bookstores.json` - bookstore data imported by `JSON.vue`.
- `src/App.vue` - displays the `JSON.vue` component.

## Screenshot Guide

For the PDF submission, capture:

1. Multiple screenshots showing activities 1-13 completed in the running VueJS app.
2. A screenshot showing the George Orwell author-highlight functionality.
3. A screenshot of `src/components/JSON.vue` showing the binding code.
4. A screenshot of the GitHub commit/history page after pushing the project update.
