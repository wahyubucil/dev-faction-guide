# JavaScript: No Console

`console` only for development when you need to debug data. When you complete debugging, remove it. Avoid `console` on production unless it's really needed to log any data on production.

If you want to log an error, it's better to show the error to the user, so the user knows what happens. If you need detail about the error to be shown and can't show that to the user, you can use `console.error` or better use `throw` to stop execution to prevent unexpected effects on error.
