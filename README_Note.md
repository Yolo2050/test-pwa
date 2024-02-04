You can load assets by

- either importing them directly
- or linking them in the public directory.
  Either solution is valid.

Any files placed in the public directory are copied over in the final bundle.

If you place files inside the src directory, they'll be processed by Vite before they're shipped with the bundle.

<97> ESLint break rule

- link: https://eslint.vuejs.org/
- link: https://eslint.vuejs.org/rules/multi-word-component-names.html
- .eslintrc.cjs
- rules: {
  "vue/multi-word-component-names" : "off"
  }

<98>
