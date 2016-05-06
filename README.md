# ngConf 2016 notes

## debugging
augury.angular.io

angular.io/styleguide

codelyzer
gives feedback as you are developing

cli.angular.io

mobile.angular.io

progressive web apps

ionic web app > access to camera
nativescript

wijmo.com

primeng
ng-lightning
vaadin.com

telerik
ng2 bootstrap

angular.io/resources



CSS with native components
dev cycle auto-refresh ios/android
simultaneous ios/android
kiva and nativescript with rangle.io

## NativeScript 2.0
ui components native

nativescript.org/ng-conf

living on a dollar --netflix


Lucidchart.com/ngconf

changeDetection: ng.core.ChangeDetectionStrategy.OnPush

john papa style guide

jpapa.me/a2ps1stlook


## Styling

view encapsulation modes 
native, none, emulated

encapsulation: ViewEncapsulation.Emulated /Native (shadow-root)

none: head in dome --no encapsulation

emulated : default style to head with shims

:host   --css selector custom element display:block


:host-context(.card) {display: block}   if matching selector is found on host

## TypeScript
blog. dan whalin

Types
accessories: number | 

angular 2 code snippets

Tooling
peek definition : right click import
find references

Interfaces
interface (Customer {
firstName: string;
lastName: string;
age?: number;   -----> optional
}

Generics
code templates 

getCustomers() : Observable<ICustomer[]> {}

tynyurl.com/tssecretweapon



## Angular Universal
server side rendering


## rethinkdb
horizon.io


## Routing
@Routes([]}

petebacondarwin.github.io/ng1-component-demo

ng-conf.org

augury.angular.io
chrome dev tool

## Angular Material 1
mdPanel service

material.angular.io

## Protractor = testing tasks
zone.js
zones track and control asynchrounus activity

github.com/angular/zone.js

## NativeScript 2
animations
bit.ly/nativescript-angular-seed

## ng2 art
teropa.info/chime

teropa windchimes

## Progressive web app
mobile.angular.io

angular cli:   ng new --mobile
github.com/angular/issue-zero
github.com/angular/mobile-toolkit


## server rendering

https://github.com/angular/universal-starter

https://github.com/angular/universal/tree/master/modules/preboot

## ngconf slides
github.com/mikedice 

### ng cli
ng build
ng test
ng e2e
ng serve
ng deploy (github pages, firebase)

ng g component my-comp
ng g directive my-dir
ng g pipe, service, route, class ...

### demo
ng new my-app --prefix myapp
cd my-app
ng test --no-watch
ng serve
ng g class shared/hero model
ng g service shared/hero
gitwip
gitlog
ng g route dashboard
ng build
ng test
ng g route hero-detail --inline-template --inline-style
ng g r hero-list -it -is    : generate route inline template inline style

cli.angular.io


### ng material demo
https://github.com/kara/puppy-love

**codelyzer
