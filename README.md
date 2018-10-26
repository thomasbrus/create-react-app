# Fork of [Create React App](https://github.com/facebook/create-react-app)

Includes:

- Tailwind CSS
- Purgecss to reduce bundle size

Try and keep it up to date with [facebook/create-react-app#next](https://github.com/facebook/create-react-app/tree/next).

To publish a new version:

- Make some changes in `packages/react-scripts/config/webpack.config.prod.js`
- Update the version number in [react-scripts/package.json](https://github.com/thomasbrus/create-react-app/commit/8a3a4799fe2a0a4c0e1dc2f973f16c4eca9bbaf1#diff-28dda38a2b752a205b23cc9333c0fe45R3)
- `cd packages/react-scripts`
- Then run `npm publish` (might need credentials first, ask @thomasbrus)
