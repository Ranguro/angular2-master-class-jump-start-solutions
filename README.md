# Angular 2 Master Class

This repository contains all the **Exercise Solutions** for the Angular 2 Master Class courseware. 

## Modules

Each module of the **Angular 2 Master Class** course has 1 or more lab exercises. Each lab exercise adds features and enhancements to the previous lab exercise.

* The final module solutions are stored in module branches. 
* The lab exercise solutions are accessed via git tags; e.g. `jump-start-step-10` or `observables-step-3`.  

Shown below are quick-links and ordering of the A2MC courseware modules:

| Module | Git Command |
|--------|--------|
| Module 1: **[Jump-Start](https://github.com/thoughtram/angular2-master-class-solutions/tree/jump-start/src)**     | `git checkout jump-start-step-<xxx>`   | 
| Module 2: **[Observables](https://github.com/thoughtram/angular2-master-class-solutions/tree/observables/src)**   | `git checkout observables-step-<xxx>`  | 
| Module 3: **[Architecture](https://github.com/thoughtram/angular2-master-class-solutions/tree/architecture/src)** | `git checkout architecture-step-<xxx>` | 
| Module 4: **[Routing](https://github.com/thoughtram/angular2-master-class-solutions/tree/routing/src)**           | `git checkout routing-step-<xxx>`      | 
| Module 5: **[Forms](https://github.com/thoughtram/angular2-master-class-solutions/tree/forms/src)**               | `git checkout forms-step-<xxx>`        | 

For each lab exercise, simply use the *git* command to quickly checkout the solution for that lab exercise:

```
git checkout jump-start-step-11
```

And to *checkout* the final module solution (after all the lab exercises are completed), checkout the *branch* instead of the *tag*. So, for example, to checkout the final solution **Module 1: Jump-Start**, use:

```
git check jump-start
```

## Local Setup
If not done already, clone this repository using:

```
$ git clone https://github.com/thoughtram/angular2-master-class-starter.git
```

Done? Great, now install the dependencies (this might take a little while):

```
$ cd angular2-master-class-starter
$ npm install
```

> You may also need to globally install the Angular-Cli:  `npm i -g angular-cli@webpack`

## Web and App Servers

To launch your web application, use a Terminal session with the command:

```
$ ng serve
```

This starts a web server for the Angular 2 application; open with a browser url `http://localhost:4200`.

And since your Angular 2 application may request external, remote data [from `http://localhost:4201/api`], you will need a local app server to respond to the REST API calls. We have already configured a server as part of this repository.

Simply start a second, separate Terminal session with the commend:

```
$ npm run rest-api
```

> While only some of the solutions use the app server, it will not hurt to start it immediately.


## Important

Have fun and good luck!

Christoph & Pascal & Thomas
