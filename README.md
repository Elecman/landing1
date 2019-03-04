## Usage

- **Build the Project and Serve locally (for Production)** - `npm start` or `yarn start`. The Production port is `8000`.
- **Build the Project and Serve locally (for Development)** - `npm run dev` or `yarn run dev`. The Development port is `3000`.
- **Exporting the Project to zip file** - `npm run export` or `yarn run export`

Important Note: **Don't** run these npm scripts simultaneously.

## Appendix

- **Tooling** - Gulpfile Lives in `gulpfile.js` and Webpack config files live within `webpack` folder.
- **Source Files** - Lives in `public/src` folder
- **Compiled Files** - Lives in `public/dist` folder. When you clone, you won't get them but as soon as you run those any of above usage tasks (start/build/export), the `public/dist` will be created.
- **Exported Project** - The exported project is imported from `public` folder and gets exported as `website.zip` to project root