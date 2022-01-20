# Vue: Styling

Never use global `<style>`, to prvent unexpected conflict. Always use `<style scoped>`. Global style only acceptable on `App.vue` or create a specific file for global style eg. `global.css` and put all global styles there and import it on `main.js`, so it's trackable where global styles came from.

Use preprocessor if possible, eg. SCSS.
