# What is component?

In your app.component.ts, you can see something like the code on the below:

```ts
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrls: ['./app.component.scss']
})
export class AppComponent {
  title = 'bookshelf';
}
```

*@Component* is the annotation (decorator) that tells Angular that the next defined class is a component. Its parameters in this case are: a HTML selector (in which the component is rendered), the template and the style files.

```export class AppComponent``` – this part looks a bit like Java or C#, right? The title in this case is a scoped variable that we outright defined now and that will be available in the template.
