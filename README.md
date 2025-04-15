# 🧪 Restaurant - Angular Product Catalog App

This is a front-end web application built with [Angular CLI](https://github.com/angular/angular-cli) version 18.1.0. It showcases a modular product catalog, user authentication (login/register), and profile handling with Angular best practices.

---

## 🚀 Development Server

Run the app locally with:

```bash
ng serve
```

Navigate to `http://localhost:4200/`. The app will automatically reload if you change any source files.

---

## 📁 Project Structure

```
src/
  app/
    home/               → Home page
    about/              → About page
    catalog/            → Product catalog
    combined-catalog/   → Combined catalog view
    product-details/    → Product detail page
    profile/            → User profile section
      login/            → Login component
      register/         → Registration component
      user-details/     → User info
    model/              → Data models & services
    navbar/             → Navigation bar
    footer/             → Footer component
    notfound/           → 404 Not Found page
  assets/               → Static assets (images, icons)
  main.ts               → Application bootstrap
  styles.css            → Global styles
  index.html            → Root HTML
```

---

## 📦 Build

Run the following command to build the project:

```bash
ng build
```

The compiled output will be in the `dist/` folder.

---

## ✅ Code Scaffolding

Use Angular CLI to generate components or services:

```bash
ng generate component component-name
ng generate service service-name
```

---

## 🧪 Unit Tests

Run unit tests using Karma:

```bash
ng test
```

---

## 🧪 End-to-End Tests

To run e2e tests:

```bash
ng e2e
```

You may need to install a package that supports end-to-end testing first.

---

## 🧰 Helpful CLI Commands

Get help on Angular CLI:

```bash
ng help
```

Or check out the [Angular CLI Reference](https://angular.dev/tools/cli) for full documentation.

---

## 📜 License

This project is for educational purposes. You may reuse the structure for your own Angular projects.
