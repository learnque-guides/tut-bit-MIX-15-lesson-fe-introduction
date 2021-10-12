# Loops

* `*ngFor` attribute works as a loop parameter. Used for example to define how a list of elements should be displayed.
* If we have an array of data (let’s say a collection of names) in our component, we can access it in the template as `<div *ngFor="let item of items">{{item.name}}</div>`.