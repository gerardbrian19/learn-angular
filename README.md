< ng-content > = { this.props.children }

10 - Data flow (the net ninja) \
String interpolation: {{ title }} \
Property binding: <input [required]='expression'> \
Event binding: <button (click)='expression/function> \

Two-way binding: <input [(ngModel)]='model/object'>

@Input() = expected props (from parent)
@Output() = pass data (from child to parent)

$event = event

Spec file = test file

Directives:
[routerLink]
<router-outlet>
ngClass
ngIf
*ngFor
ngStyle

| (pipe) = how the data will display (filters/uppercases etc.)
