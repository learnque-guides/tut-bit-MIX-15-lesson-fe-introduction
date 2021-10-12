# What is component II?

In src/index.html, you can see something like this:

```html
<body><app-root></app-root></body>
```

This new ```<app-root>``` tag is what tells the Angular app to render our newly created component. The *@Component* selector attribute is what connects our component to it! Try changing the selector parameter in your new Angular application.

Angular has a built-in shell for generating new components. Try the following command:

```bash
ng generate component dog
```

As you can see a new component was created in your working directory! We'll return to it a bit later.