# Clean Code

The simplest way to understand this is, make sure your code is self explanatory so you don't even need a comment to explain it.
There may be an exception to use comment, ex: RegEx.

Here's the list:

- Clear naming, eg. variable name, function name, key/property in an object, and function parameter name. Better long name than nothing.
- Don't use a general variable name if the variable scope is big. Eg. variable `data` is used on a page with more than one table.
- Only create util, helper, or global thing when it fixes uses by a lot of files.
- Always use `function` compare to a `variable with an arrow function`, unless you can make it a one-line arrow function. But it's okay if there's a TypeScript issue.

TODO: I hope the list will be increasing 😅
