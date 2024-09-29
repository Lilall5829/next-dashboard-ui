# Dev School Management Dashboard

## Getting Started

### First, run the development server:

```
npm install
npm run dev
```

  Visit [http://localhost:3000](http://localhost:3000) to see the result.

### Add some snippets to typescriptreact, search:
```
> Snippets
```
  Then, choose typescriptreact.json And add snippets to it.

### Create admin/parent/student/teacher pages under the app/(dashboard)

- app/layout is the root layout for all of the pages
- Create a layout.tsx for the dashboard folder
- Add **parenthesis** to the folder's name so that React can ignore it when typing the path in the browser.

### Create sign-in folder under the app
### Create components folder under the src
- Create Menu.tsx and Navbar.tsx
### Edit the dashboard layout
Redirect to the homepage
```js
<Link href="/">
  <Image src="/logo.png" /> /*there is a slash before the "logo.png" */
</Link>
```
