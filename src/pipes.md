# Pipes

* Pipes are used to transform tham data that we are getting in templates.
* To apply a pipe, use the pipe operator (|) within a template expression as shown in the following code example, along with the name of the pipe, which is date for the built-in DatePipe. The tabs in the example show the following.

```ts
{{ birthday | date | uppercase}}
```