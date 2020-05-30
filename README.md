* The source code is copied from sveltejs/template (https://github.com/sveltejs/template) except the package.json for parcel bundler.

# svelte app

This is a project template for [Svelte](https://svelte.dev) apps. 

To create a new project based on this template, you can clone it:

```bash
$ git clone https://github.com/Pei2tech/svelte-template-parcel.git svelte-app
```

*Note that you will need to have [Node.js](https://nodejs.org) installed for the following procedure.*


## Get started

Install the dependencies...

```bash
cd svelte-app
npm install
```

...then start [parcel](https://parceljs.org):

```bash
npm run dev
```

Check the console and Navigate to [localhost:xxxx](http://localhost:xxxx). You should see your app running. Edit a component file in `/src` or `/public`, save it, and reload the page to see your changes.


## Building and running in production mode

### svelte component

To create a production version of component only:

```bash
npm run build:component:
```

Then, you can check the optimised component within the folder `/public/build`.

### svelte app

To create an optimised version of the app:

```bash
npm run build
```

Then, the folder `/dist` is production mode of the app.  

