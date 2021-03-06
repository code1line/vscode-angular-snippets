# Angular TypeScript Snippets for VS Code

**Now Updated for Angular 4.0.0 release**

This extension for Visual Studio Code adds snippets for Angular for TypeScript and HTML.

![Use Extension](images/use-extension-1.gif)

See the [CHANGELOG](CHANGELOG.md) for the latest changes

## Usage
Type part of a snippet, press `enter`, and the snippet unfolds.

### TypeScript Angular Snippets
```typescript
a-component                 // component
a-component-root            // root app component
a-directive                 // directive
a-guard-can-activate        // CanActivate guard
a-guard-can-activate-child  // CanActivateChild guard
a-guard-can-deactivate      // CanDeactivate guard
a-guard-can-load            // CanLoad guard
a-http-get                  // http.get with Rx Observable
a-httpclient-get            // httpClient.get with Rx Observable
a-module                    // module
a-module-root               // root app module
a-module-routing            // routing module file (forChild)
a-output-event              // @Output event and emitter
a-pipe                      // pipe
a-route-path-404            // 404 route path
a-route-path-default        // default route path
a-route-path-eager          // eager route path
a-route-path-lazy           // lazy route path
a-service                   // service
a-service-http              // service with Http
a-service-httpclient        // service with HttpClient
a-ctor-skip-self            // angular ngmodule's skipself constructor
a-subscribe                 // Rx Observable subscription
```

### TypeScript RxJS Snippets
```typescript
rx-observable               // Rx Observable import
rx-subject                  // Rx Subject import
rx-replay-subject           // Rx ReplaySubject import
rx-behavior-subject         // Rx BehaviorSubject import
rx-add-operator             // Rx add operator import
rx-add-observable           // Rx add observable import
```

### HTML Snippets
```html
a-class                     // [class] binding
a-select                    // <select> control
a-style                     // [style] binding
a-ngClass                   // ngClass
a-ngFor                     // *ngFor
a-ngForAsync                // *ngFor with async
a-ngIf                      // *ngIf
a-ngIfElse                  // *ngIf with else
a-ngModel                   // ngModel
a-routerLink                // routerLink
a-routerLink-param          // routerLink with a route parameter
a-ngStyle                   // ngStyle
a-ngSwitch                  // ngSwitch
a-prej                      // <pre>{{model | json}}</pre>
a-preja                     // <pre>{{model | async | json}}</pre>
```

Alternatively, press `Ctrl`+`Space` (Windows, Linux) or `Cmd`+`Space` (OSX) to activate snippets from within the editor.

## Installation

1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code

![Install Extension](images/install-extension.gif)
