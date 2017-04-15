# api documentation for  [rxjs (v5.3.0)](https://github.com/ReactiveX/RxJS)  [![npm package](https://img.shields.io/npm/v/npmdoc-rxjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rxjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rxjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rxjs)
#### Reactive Extensions for modern JavaScript

[![NPM](https://nodei.co/npm/rxjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rxjs)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rxjs/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rxjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-rxjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-rxjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Lesh"
    },
    "bugs": {
        "url": "https://github.com/ReactiveX/RxJS/issues"
    },
    "config": {
        "commitizen": {
            "path": "cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Ben Lesh"
        },
        {
            "name": "Paul Taylor"
        },
        {
            "name": "Jeff Cross"
        },
        {
            "name": "Matthew Podwysocki"
        },
        {
            "name": "OJ Kwon"
        },
        {
            "name": "Andre Staltz"
        }
    ],
    "dependencies": {
        "symbol-observable": "^1.0.1"
    },
    "description": "Reactive Extensions for modern JavaScript",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "benchpress": "2.0.0-beta.1",
        "chai": "^3.5.0",
        "color": "^0.11.1",
        "colors": "1.1.2",
        "commitizen": "^2.8.6",
        "coveralls": "^2.11.13",
        "cz-conventional-changelog": "^1.2.0",
        "doctoc": "^1.0.0",
        "escape-string-regexp": "^1.0.5 ",
        "esdoc": "^0.4.7",
        "eslint": "^3.8.0",
        "fs-extra": "^2.1.2",
        "glob": "^7.0.3",
        "gm": "^1.22.0",
        "google-closure-compiler-js": "^20170218.0.0",
        "gzip-size": "^3.0.0",
        "http-server": "^0.9.0",
        "husky": "^0.13.3",
        "lint-staged": "^3.2.5",
        "lodash": "^4.15.0",
        "madge": "^1.4.3",
        "markdown-doctest": "^0.9.1",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "mocha": "^3.0.2",
        "mocha-in-sauce": "0.0.1",
        "npm-run-all": "^4.0.2",
        "npm-scripts-info": "^0.3.4",
        "nyc": "^10.2.0",
        "opn-cli": "^3.1.0",
        "platform": "^1.3.1",
        "promise": "^7.1.1",
        "protractor": "^3.1.1",
        "rollup": "0.36.3",
        "rollup-plugin-inject": "^2.0.0",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rx": "latest",
        "shx": "^0.2.2",
        "sinon": "^2.1.0",
        "sinon-chai": "^2.9.0",
        "source-map-support": "^0.4.0",
        "tslib": "^1.5.0",
        "tslint": "^4.4.2",
        "typescript": "~2.0.6",
        "typings": "^2.0.0",
        "validate-commit-msg": "^2.3.1",
        "watch": "^1.0.1",
        "webpack": "^1.13.1",
        "xmlhttprequest": "1.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d88ccbdd46af290cbdb97d5d8055e52453fabe2d",
        "tarball": "https://registry.npmjs.org/rxjs/-/rxjs-5.3.0.tgz"
    },
    "engines": {
        "npm": ">=2.0.0"
    },
    "homepage": "https://github.com/ReactiveX/RxJS",
    "keywords": [
        "Rx",
        "RxJS",
        "ReactiveX",
        "ReactiveExtensions",
        "Streams",
        "Observables",
        "Observable",
        "Stream",
        "ES6",
        "ES2015"
    ],
    "license": "Apache-2.0",
    "lint-staged": {
        "*.@(js)": [
            "eslint --fix",
            "git add"
        ],
        "*.@(ts)": [
            "tslint --fix",
            "git add"
        ]
    },
    "main": "Rx.js",
    "maintainers": [
        {
            "name": "blesh"
        },
        {
            "name": "jeffbcross"
        }
    ],
    "name": "rxjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/ReactiveX/RxJS.git"
    },
    "scripts": {},
    "scripts-info": {
        "info": "List available script",
        "build_all": "Build all packages (ES6, CJS, UMD) and generate packages",
        "build_cjs": "Build CJS package with clean up existing build, copy source into dist",
        "build_es6": "Build ES6 package with clean up existing build, copy source into dist",
        "build_closure_core": "Minify Global core build using closure compiler",
        "build_global": "Build Global package, then minify build",
        "build_perf": "Build CJS & Global build, run macro performance test",
        "build_test": "Build CJS package & test spec, execute mocha test runner",
        "build_cover": "Run lint to current code, build CJS & test spec, execute test coverage",
        "build_docs": "Build ES6 & global package, create documentation using it",
        "build_spec": "Build test specs",
        "check_circular_dependencies": "Check codebase has circular dependencies",
        "clean_spec": "Clean up existing test spec build output",
        "clean_dist_cjs": "Clean up existing CJS package output",
        "clean_dist_es6": "Clean up existing ES6 package output",
        "clean_dist_global": "Clean up existing Global package output",
        "commit": "Run git commit wizard",
        "compile_dist_cjs": "Compile codebase into CJS module",
        "compile_module_es6": "Compile codebase into ES6",
        "cover": "Execute test coverage",
        "lint_perf": "Run lint against performance test suite",
        "lint_spec": "Run lint against test spec",
        "lint_src": "Run lint against source",
        "lint": "Run lint against everything",
        "perf": "Run macro performance benchmark",
        "perf_micro": "Run micro performance benchmark",
        "test_mocha": "Execute mocha test runner against existing test spec build",
        "test_browser": "Execute mocha test runner on browser against existing test spec build",
        "test": "Clean up existing test spec build, build test spec and execute mocha test runner",
        "tests2png": "Generate marble diagram image from test spec",
        "watch": "Watch codebase, trigger compile when source code changes"
    },
    "typings": "Rx.d.ts",
    "version": "5.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module rxjs](#apidoc.module.rxjs)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AjaxError (message, xhr, request)](#apidoc.element.rxjs.AjaxError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AjaxResponse (originalEvent, xhr, request)](#apidoc.element.rxjs.AjaxResponse)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AjaxTimeoutError (xhr, request)](#apidoc.element.rxjs.AjaxTimeoutError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AnonymousSubject (destination, source)](#apidoc.element.rxjs.AnonymousSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ArgumentOutOfRangeError ()](#apidoc.element.rxjs.ArgumentOutOfRangeError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AsyncSubject ()](#apidoc.element.rxjs.AsyncSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>BehaviorSubject (_value)](#apidoc.element.rxjs.BehaviorSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ConnectableObservable (source, subjectFactory)](#apidoc.element.rxjs.ConnectableObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ConnectableObservable.ajax (urlOrRequest)](#apidoc.element.rxjs.ConnectableObservable.ajax)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>EmptyError ()](#apidoc.element.rxjs.EmptyError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Notification (kind, value, error)](#apidoc.element.rxjs.Notification)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ObjectUnsubscribedError ()](#apidoc.element.rxjs.ObjectUnsubscribedError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Observable (subscribe)](#apidoc.element.rxjs.Observable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ReplaySubject (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.ReplaySubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Subject ()](#apidoc.element.rxjs.Subject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Subscriber (destinationOrNext, error, complete)](#apidoc.element.rxjs.Subscriber)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Subscription (unsubscribe)](#apidoc.element.rxjs.Subscription)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>TestScheduler (assertDeepEqual)](#apidoc.element.rxjs.TestScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>TimeInterval (value, interval)](#apidoc.element.rxjs.TimeInterval)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>TimeoutError ()](#apidoc.element.rxjs.TimeoutError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Timestamp (value, timestamp)](#apidoc.element.rxjs.Timestamp)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>UnsubscriptionError (errors)](#apidoc.element.rxjs.UnsubscriptionError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>VirtualTimeScheduler (SchedulerAction, maxFrames)](#apidoc.element.rxjs.VirtualTimeScheduler)
1.  object <span class="apidocSignatureSpan">rxjs.</span>AjaxError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>AjaxTimeoutError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>AnonymousSubject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>ArgumentOutOfRangeError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>AsyncSubject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>BehaviorSubject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>ConnectableObservable.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>EmptyError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>Notification.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>ObjectUnsubscribedError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>Observable.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>ReplaySubject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>Scheduler
1.  object <span class="apidocSignatureSpan">rxjs.</span>Subject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>Subscriber.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>Subscription.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>Symbol
1.  object <span class="apidocSignatureSpan">rxjs.</span>TestScheduler.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>TimeoutError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>UnsubscriptionError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>VirtualTimeScheduler.prototype

#### [module rxjs.AjaxError](#apidoc.module.rxjs.AjaxError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AjaxError (message, xhr, request)](#apidoc.element.rxjs.AjaxError.AjaxError)
1.  [function <span class="apidocSignatureSpan">rxjs.AjaxError.</span>captureStackTrace ()](#apidoc.element.rxjs.AjaxError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.AjaxError.</span>stackTraceLimit

#### [module rxjs.AjaxError.prototype](#apidoc.module.rxjs.AjaxError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.AjaxError.prototype.</span>constructor (message, xhr, request)](#apidoc.element.rxjs.AjaxError.prototype.constructor)

#### [module rxjs.AjaxTimeoutError](#apidoc.module.rxjs.AjaxTimeoutError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AjaxTimeoutError (xhr, request)](#apidoc.element.rxjs.AjaxTimeoutError.AjaxTimeoutError)
1.  [function <span class="apidocSignatureSpan">rxjs.AjaxTimeoutError.</span>captureStackTrace ()](#apidoc.element.rxjs.AjaxTimeoutError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.AjaxTimeoutError.</span>stackTraceLimit

#### [module rxjs.AjaxTimeoutError.prototype](#apidoc.module.rxjs.AjaxTimeoutError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.AjaxTimeoutError.prototype.</span>constructor (xhr, request)](#apidoc.element.rxjs.AjaxTimeoutError.prototype.constructor)

#### [module rxjs.AnonymousSubject](#apidoc.module.rxjs.AnonymousSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AnonymousSubject (destination, source)](#apidoc.element.rxjs.AnonymousSubject.AnonymousSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.</span>create (destination, source)](#apidoc.element.rxjs.AnonymousSubject.create)

#### [module rxjs.AnonymousSubject.prototype](#apidoc.module.rxjs.AnonymousSubject.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.AnonymousSubject.prototype._subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>complete ()](#apidoc.element.rxjs.AnonymousSubject.prototype.complete)
1.  [function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>constructor (destination, source)](#apidoc.element.rxjs.AnonymousSubject.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>error (err)](#apidoc.element.rxjs.AnonymousSubject.prototype.error)
1.  [function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>next (value)](#apidoc.element.rxjs.AnonymousSubject.prototype.next)

#### [module rxjs.ArgumentOutOfRangeError](#apidoc.module.rxjs.ArgumentOutOfRangeError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ArgumentOutOfRangeError ()](#apidoc.element.rxjs.ArgumentOutOfRangeError.ArgumentOutOfRangeError)
1.  [function <span class="apidocSignatureSpan">rxjs.ArgumentOutOfRangeError.</span>captureStackTrace ()](#apidoc.element.rxjs.ArgumentOutOfRangeError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.ArgumentOutOfRangeError.</span>stackTraceLimit

#### [module rxjs.ArgumentOutOfRangeError.prototype](#apidoc.module.rxjs.ArgumentOutOfRangeError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.ArgumentOutOfRangeError.prototype.</span>constructor ()](#apidoc.element.rxjs.ArgumentOutOfRangeError.prototype.constructor)

#### [module rxjs.AsyncSubject](#apidoc.module.rxjs.AsyncSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AsyncSubject ()](#apidoc.element.rxjs.AsyncSubject.AsyncSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.AsyncSubject.</span>create (destination, source)](#apidoc.element.rxjs.AsyncSubject.create)

#### [module rxjs.AsyncSubject.prototype](#apidoc.module.rxjs.AsyncSubject.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.AsyncSubject.prototype._subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>complete ()](#apidoc.element.rxjs.AsyncSubject.prototype.complete)
1.  [function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>constructor ()](#apidoc.element.rxjs.AsyncSubject.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>error (error)](#apidoc.element.rxjs.AsyncSubject.prototype.error)
1.  [function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>next (value)](#apidoc.element.rxjs.AsyncSubject.prototype.next)

#### [module rxjs.BehaviorSubject](#apidoc.module.rxjs.BehaviorSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>BehaviorSubject (_value)](#apidoc.element.rxjs.BehaviorSubject.BehaviorSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.</span>create (destination, source)](#apidoc.element.rxjs.BehaviorSubject.create)

#### [module rxjs.BehaviorSubject.prototype](#apidoc.module.rxjs.BehaviorSubject.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.BehaviorSubject.prototype._subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.prototype.</span>constructor (_value)](#apidoc.element.rxjs.BehaviorSubject.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.prototype.</span>getValue ()](#apidoc.element.rxjs.BehaviorSubject.prototype.getValue)
1.  [function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.prototype.</span>next (value)](#apidoc.element.rxjs.BehaviorSubject.prototype.next)

#### [module rxjs.ConnectableObservable](#apidoc.module.rxjs.ConnectableObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ConnectableObservable (source, subjectFactory)](#apidoc.element.rxjs.ConnectableObservable.ConnectableObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>ajax (urlOrRequest)](#apidoc.element.rxjs.ConnectableObservable.ajax)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>bindCallback (func, selector, scheduler)](#apidoc.element.rxjs.ConnectableObservable.bindCallback)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>bindNodeCallback (func, selector, scheduler)](#apidoc.element.rxjs.ConnectableObservable.bindNodeCallback)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>combineLatest ()](#apidoc.element.rxjs.ConnectableObservable.combineLatest)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>concat ()](#apidoc.element.rxjs.ConnectableObservable.concat)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>create (subscribe)](#apidoc.element.rxjs.ConnectableObservable.create)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>defer (observableFactory)](#apidoc.element.rxjs.ConnectableObservable.defer)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>empty (scheduler)](#apidoc.element.rxjs.ConnectableObservable.empty)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>forkJoin ()](#apidoc.element.rxjs.ConnectableObservable.forkJoin)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>from (ish, scheduler)](#apidoc.element.rxjs.ConnectableObservable.from)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>fromEvent (target, eventName, options, selector)](#apidoc.element.rxjs.ConnectableObservable.fromEvent)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>fromEventPattern (addHandler, removeHandler, selector)](#apidoc.element.rxjs.ConnectableObservable.fromEventPattern)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>fromPromise (promise, scheduler)](#apidoc.element.rxjs.ConnectableObservable.fromPromise)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>generate (initialStateOrOptions, condition, iterate, resultSelectorOrObservable, scheduler)](#apidoc.element.rxjs.ConnectableObservable.generate)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>if (condition, thenSource, elseSource)](#apidoc.element.rxjs.ConnectableObservable.if)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>interval (period, scheduler)](#apidoc.element.rxjs.ConnectableObservable.interval)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>merge ()](#apidoc.element.rxjs.ConnectableObservable.merge)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>never ()](#apidoc.element.rxjs.ConnectableObservable.never)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>of ()](#apidoc.element.rxjs.ConnectableObservable.of)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>onErrorResumeNext ()](#apidoc.element.rxjs.ConnectableObservable.onErrorResumeNext)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>pairs (obj, scheduler)](#apidoc.element.rxjs.ConnectableObservable.pairs)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>race ()](#apidoc.element.rxjs.ConnectableObservable.race)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>range (start, count, scheduler)](#apidoc.element.rxjs.ConnectableObservable.range)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>throw (error, scheduler)](#apidoc.element.rxjs.ConnectableObservable.throw)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>timer (initialDelay, period, scheduler)](#apidoc.element.rxjs.ConnectableObservable.timer)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>using (resourceFactory, observableFactory)](#apidoc.element.rxjs.ConnectableObservable.using)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>webSocket (urlConfigOrSource)](#apidoc.element.rxjs.ConnectableObservable.webSocket)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>zip ()](#apidoc.element.rxjs.ConnectableObservable.zip)

#### [module rxjs.ConnectableObservable.ajax](#apidoc.module.rxjs.ConnectableObservable.ajax)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>ajax (urlOrRequest)](#apidoc.element.rxjs.ConnectableObservable.ajax.ajax)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>delete (url, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.delete)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>get (url, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.get)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>getJSON (url, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.getJSON)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>patch (url, body, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.patch)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>post (url, body, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.post)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>put (url, body, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.put)

#### [module rxjs.ConnectableObservable.prototype](#apidoc.module.rxjs.ConnectableObservable.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.ConnectableObservable.prototype._subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>connect ()](#apidoc.element.rxjs.ConnectableObservable.prototype.connect)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>constructor (source, subjectFactory)](#apidoc.element.rxjs.ConnectableObservable.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>getSubject ()](#apidoc.element.rxjs.ConnectableObservable.prototype.getSubject)
1.  [function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>refCount ()](#apidoc.element.rxjs.ConnectableObservable.prototype.refCount)

#### [module rxjs.EmptyError](#apidoc.module.rxjs.EmptyError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>EmptyError ()](#apidoc.element.rxjs.EmptyError.EmptyError)
1.  [function <span class="apidocSignatureSpan">rxjs.EmptyError.</span>captureStackTrace ()](#apidoc.element.rxjs.EmptyError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.EmptyError.</span>stackTraceLimit

#### [module rxjs.EmptyError.prototype](#apidoc.module.rxjs.EmptyError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.EmptyError.prototype.</span>constructor ()](#apidoc.element.rxjs.EmptyError.prototype.constructor)

#### [module rxjs.Notification](#apidoc.module.rxjs.Notification)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Notification (kind, value, error)](#apidoc.element.rxjs.Notification.Notification)
1.  [function <span class="apidocSignatureSpan">rxjs.Notification.</span>createComplete ()](#apidoc.element.rxjs.Notification.createComplete)
1.  [function <span class="apidocSignatureSpan">rxjs.Notification.</span>createError (err)](#apidoc.element.rxjs.Notification.createError)
1.  [function <span class="apidocSignatureSpan">rxjs.Notification.</span>createNext (value)](#apidoc.element.rxjs.Notification.createNext)
1.  object <span class="apidocSignatureSpan">rxjs.Notification.</span>completeNotification
1.  object <span class="apidocSignatureSpan">rxjs.Notification.</span>undefinedValueNotification

#### [module rxjs.Notification.prototype](#apidoc.module.rxjs.Notification.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.Notification.prototype.</span>accept (nextOrObserver, error, complete)](#apidoc.element.rxjs.Notification.prototype.accept)
1.  [function <span class="apidocSignatureSpan">rxjs.Notification.prototype.</span>do (next, error, complete)](#apidoc.element.rxjs.Notification.prototype.do)
1.  [function <span class="apidocSignatureSpan">rxjs.Notification.prototype.</span>observe (observer)](#apidoc.element.rxjs.Notification.prototype.observe)
1.  [function <span class="apidocSignatureSpan">rxjs.Notification.prototype.</span>toObservable ()](#apidoc.element.rxjs.Notification.prototype.toObservable)

#### [module rxjs.ObjectUnsubscribedError](#apidoc.module.rxjs.ObjectUnsubscribedError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ObjectUnsubscribedError ()](#apidoc.element.rxjs.ObjectUnsubscribedError.ObjectUnsubscribedError)
1.  [function <span class="apidocSignatureSpan">rxjs.ObjectUnsubscribedError.</span>captureStackTrace ()](#apidoc.element.rxjs.ObjectUnsubscribedError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.ObjectUnsubscribedError.</span>stackTraceLimit

#### [module rxjs.ObjectUnsubscribedError.prototype](#apidoc.module.rxjs.ObjectUnsubscribedError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.ObjectUnsubscribedError.prototype.</span>constructor ()](#apidoc.element.rxjs.ObjectUnsubscribedError.prototype.constructor)

#### [module rxjs.Observable](#apidoc.module.rxjs.Observable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Observable (subscribe)](#apidoc.element.rxjs.Observable.Observable)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>ajax (urlOrRequest)](#apidoc.element.rxjs.Observable.ajax)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>bindCallback (func, selector, scheduler)](#apidoc.element.rxjs.Observable.bindCallback)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>bindNodeCallback (func, selector, scheduler)](#apidoc.element.rxjs.Observable.bindNodeCallback)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>combineLatest ()](#apidoc.element.rxjs.Observable.combineLatest)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>concat ()](#apidoc.element.rxjs.Observable.concat)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>create (subscribe)](#apidoc.element.rxjs.Observable.create)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>defer (observableFactory)](#apidoc.element.rxjs.Observable.defer)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>empty (scheduler)](#apidoc.element.rxjs.Observable.empty)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>forkJoin ()](#apidoc.element.rxjs.Observable.forkJoin)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>from (ish, scheduler)](#apidoc.element.rxjs.Observable.from)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>fromEvent (target, eventName, options, selector)](#apidoc.element.rxjs.Observable.fromEvent)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>fromEventPattern (addHandler, removeHandler, selector)](#apidoc.element.rxjs.Observable.fromEventPattern)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>fromPromise (promise, scheduler)](#apidoc.element.rxjs.Observable.fromPromise)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>generate (initialStateOrOptions, condition, iterate, resultSelectorOrObservable, scheduler)](#apidoc.element.rxjs.Observable.generate)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>if (condition, thenSource, elseSource)](#apidoc.element.rxjs.Observable.if)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>interval (period, scheduler)](#apidoc.element.rxjs.Observable.interval)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>merge ()](#apidoc.element.rxjs.Observable.merge)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>never ()](#apidoc.element.rxjs.Observable.never)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>of ()](#apidoc.element.rxjs.Observable.of)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>onErrorResumeNext ()](#apidoc.element.rxjs.Observable.onErrorResumeNext)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>pairs (obj, scheduler)](#apidoc.element.rxjs.Observable.pairs)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>race ()](#apidoc.element.rxjs.Observable.race)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>range (start, count, scheduler)](#apidoc.element.rxjs.Observable.range)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>throw (error, scheduler)](#apidoc.element.rxjs.Observable.throw)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>timer (initialDelay, period, scheduler)](#apidoc.element.rxjs.Observable.timer)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>using (resourceFactory, observableFactory)](#apidoc.element.rxjs.Observable.using)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>webSocket (urlConfigOrSource)](#apidoc.element.rxjs.Observable.webSocket)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.</span>zip ()](#apidoc.element.rxjs.Observable.zip)

#### [module rxjs.Observable.prototype](#apidoc.module.rxjs.Observable.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_catch (selector)](#apidoc.element.rxjs.Observable.prototype._catch)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_do (nextOrObserver, error, complete)](#apidoc.element.rxjs.Observable.prototype._do)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_finally (callback)](#apidoc.element.rxjs.Observable.prototype._finally)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.Observable.prototype._subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_switch ()](#apidoc.element.rxjs.Observable.prototype._switch)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_trySubscribe (sink)](#apidoc.element.rxjs.Observable.prototype._trySubscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>audit (durationSelector)](#apidoc.element.rxjs.Observable.prototype.audit)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>auditTime (duration, scheduler)](#apidoc.element.rxjs.Observable.prototype.auditTime)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>buffer (closingNotifier)](#apidoc.element.rxjs.Observable.prototype.buffer)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>bufferCount (bufferSize, startBufferEvery)](#apidoc.element.rxjs.Observable.prototype.bufferCount)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>bufferTime (bufferTimeSpan)](#apidoc.element.rxjs.Observable.prototype.bufferTime)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>bufferToggle (openings, closingSelector)](#apidoc.element.rxjs.Observable.prototype.bufferToggle)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>bufferWhen (closingSelector)](#apidoc.element.rxjs.Observable.prototype.bufferWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>catch (selector)](#apidoc.element.rxjs.Observable.prototype.catch)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>combineAll (project)](#apidoc.element.rxjs.Observable.prototype.combineAll)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>combineLatest ()](#apidoc.element.rxjs.Observable.prototype.combineLatest)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>concat ()](#apidoc.element.rxjs.Observable.prototype.concat)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>concatAll ()](#apidoc.element.rxjs.Observable.prototype.concatAll)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>concatMap (project, resultSelector)](#apidoc.element.rxjs.Observable.prototype.concatMap)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>concatMapTo (innerObservable, resultSelector)](#apidoc.element.rxjs.Observable.prototype.concatMapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>count (predicate)](#apidoc.element.rxjs.Observable.prototype.count)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>debounce (durationSelector)](#apidoc.element.rxjs.Observable.prototype.debounce)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>debounceTime (dueTime, scheduler)](#apidoc.element.rxjs.Observable.prototype.debounceTime)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>defaultIfEmpty (defaultValue)](#apidoc.element.rxjs.Observable.prototype.defaultIfEmpty)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>delay (delay, scheduler)](#apidoc.element.rxjs.Observable.prototype.delay)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>delayWhen (delayDurationSelector, subscriptionDelay)](#apidoc.element.rxjs.Observable.prototype.delayWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>dematerialize ()](#apidoc.element.rxjs.Observable.prototype.dematerialize)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>distinct (keySelector, flushes)](#apidoc.element.rxjs.Observable.prototype.distinct)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>distinctUntilChanged (compare, keySelector)](#apidoc.element.rxjs.Observable.prototype.distinctUntilChanged)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>distinctUntilKeyChanged (key, compare)](#apidoc.element.rxjs.Observable.prototype.distinctUntilKeyChanged)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>do (nextOrObserver, error, complete)](#apidoc.element.rxjs.Observable.prototype.do)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>elementAt (index, defaultValue)](#apidoc.element.rxjs.Observable.prototype.elementAt)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>every (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.every)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>exhaust ()](#apidoc.element.rxjs.Observable.prototype.exhaust)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>exhaustMap (project, resultSelector)](#apidoc.element.rxjs.Observable.prototype.exhaustMap)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>expand (project, concurrent, scheduler)](#apidoc.element.rxjs.Observable.prototype.expand)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>filter (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.filter)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>finally (callback)](#apidoc.element.rxjs.Observable.prototype.finally)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>find (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.find)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>findIndex (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.findIndex)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>first (predicate, resultSelector, defaultValue)](#apidoc.element.rxjs.Observable.prototype.first)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>flatMap (project, resultSelector, concurrent)](#apidoc.element.rxjs.Observable.prototype.flatMap)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>flatMapTo (innerObservable, resultSelector, concurrent)](#apidoc.element.rxjs.Observable.prototype.flatMapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>forEach (next, PromiseCtor)](#apidoc.element.rxjs.Observable.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>groupBy (keySelector, elementSelector, durationSelector, subjectSelector)](#apidoc.element.rxjs.Observable.prototype.groupBy)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>ignoreElements ()](#apidoc.element.rxjs.Observable.prototype.ignoreElements)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>isEmpty ()](#apidoc.element.rxjs.Observable.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>last (predicate, resultSelector, defaultValue)](#apidoc.element.rxjs.Observable.prototype.last)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>let (func)](#apidoc.element.rxjs.Observable.prototype.let)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>letBind (func)](#apidoc.element.rxjs.Observable.prototype.letBind)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>lift (operator)](#apidoc.element.rxjs.Observable.prototype.lift)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>map (project, thisArg)](#apidoc.element.rxjs.Observable.prototype.map)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mapTo (value)](#apidoc.element.rxjs.Observable.prototype.mapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>materialize ()](#apidoc.element.rxjs.Observable.prototype.materialize)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>max (comparer)](#apidoc.element.rxjs.Observable.prototype.max)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>merge ()](#apidoc.element.rxjs.Observable.prototype.merge)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mergeAll (concurrent)](#apidoc.element.rxjs.Observable.prototype.mergeAll)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mergeMap (project, resultSelector, concurrent)](#apidoc.element.rxjs.Observable.prototype.mergeMap)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mergeMapTo (innerObservable, resultSelector, concurrent)](#apidoc.element.rxjs.Observable.prototype.mergeMapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mergeScan (accumulator, seed, concurrent)](#apidoc.element.rxjs.Observable.prototype.mergeScan)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>min (comparer)](#apidoc.element.rxjs.Observable.prototype.min)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>multicast (subjectOrSubjectFactory, selector)](#apidoc.element.rxjs.Observable.prototype.multicast)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>observeOn (scheduler, delay)](#apidoc.element.rxjs.Observable.prototype.observeOn)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>onErrorResumeNext ()](#apidoc.element.rxjs.Observable.prototype.onErrorResumeNext)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>pairwise ()](#apidoc.element.rxjs.Observable.prototype.pairwise)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>partition (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.partition)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>pluck ()](#apidoc.element.rxjs.Observable.prototype.pluck)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>publish (selector)](#apidoc.element.rxjs.Observable.prototype.publish)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>publishBehavior (value)](#apidoc.element.rxjs.Observable.prototype.publishBehavior)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>publishLast ()](#apidoc.element.rxjs.Observable.prototype.publishLast)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>publishReplay (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.Observable.prototype.publishReplay)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>race ()](#apidoc.element.rxjs.Observable.prototype.race)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>reduce (accumulator, seed)](#apidoc.element.rxjs.Observable.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>repeat (count)](#apidoc.element.rxjs.Observable.prototype.repeat)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>repeatWhen (notifier)](#apidoc.element.rxjs.Observable.prototype.repeatWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>retry (count)](#apidoc.element.rxjs.Observable.prototype.retry)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>retryWhen (notifier)](#apidoc.element.rxjs.Observable.prototype.retryWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>sample (notifier)](#apidoc.element.rxjs.Observable.prototype.sample)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>sampleTime (period, scheduler)](#apidoc.element.rxjs.Observable.prototype.sampleTime)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>scan (accumulator, seed)](#apidoc.element.rxjs.Observable.prototype.scan)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>sequenceEqual (compareTo, comparor)](#apidoc.element.rxjs.Observable.prototype.sequenceEqual)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>share ()](#apidoc.element.rxjs.Observable.prototype.share)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>single (predicate)](#apidoc.element.rxjs.Observable.prototype.single)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>skip (count)](#apidoc.element.rxjs.Observable.prototype.skip)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>skipUntil (notifier)](#apidoc.element.rxjs.Observable.prototype.skipUntil)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>skipWhile (predicate)](#apidoc.element.rxjs.Observable.prototype.skipWhile)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>startWith ()](#apidoc.element.rxjs.Observable.prototype.startWith)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>subscribe (observerOrNext, error, complete)](#apidoc.element.rxjs.Observable.prototype.subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>subscribeOn (scheduler, delay)](#apidoc.element.rxjs.Observable.prototype.subscribeOn)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>switch ()](#apidoc.element.rxjs.Observable.prototype.switch)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>switchMap (project, resultSelector)](#apidoc.element.rxjs.Observable.prototype.switchMap)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>switchMapTo (innerObservable, resultSelector)](#apidoc.element.rxjs.Observable.prototype.switchMapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>take (count)](#apidoc.element.rxjs.Observable.prototype.take)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>takeLast (count)](#apidoc.element.rxjs.Observable.prototype.takeLast)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>takeUntil (notifier)](#apidoc.element.rxjs.Observable.prototype.takeUntil)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>takeWhile (predicate)](#apidoc.element.rxjs.Observable.prototype.takeWhile)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>throttle (durationSelector)](#apidoc.element.rxjs.Observable.prototype.throttle)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>throttleTime (duration, scheduler)](#apidoc.element.rxjs.Observable.prototype.throttleTime)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>timeInterval (scheduler)](#apidoc.element.rxjs.Observable.prototype.timeInterval)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>timeout (due, scheduler)](#apidoc.element.rxjs.Observable.prototype.timeout)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>timeoutWith (due, withObservable, scheduler)](#apidoc.element.rxjs.Observable.prototype.timeoutWith)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>timestamp (scheduler)](#apidoc.element.rxjs.Observable.prototype.timestamp)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>toArray ()](#apidoc.element.rxjs.Observable.prototype.toArray)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>toPromise (PromiseCtor)](#apidoc.element.rxjs.Observable.prototype.toPromise)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>window (windowBoundaries)](#apidoc.element.rxjs.Observable.prototype.window)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>windowCount (windowSize, startWindowEvery)](#apidoc.element.rxjs.Observable.prototype.windowCount)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>windowTime (windowTimeSpan)](#apidoc.element.rxjs.Observable.prototype.windowTime)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>windowToggle (openings, closingSelector)](#apidoc.element.rxjs.Observable.prototype.windowToggle)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>windowWhen (closingSelector)](#apidoc.element.rxjs.Observable.prototype.windowWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>withLatestFrom ()](#apidoc.element.rxjs.Observable.prototype.withLatestFrom)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>zip ()](#apidoc.element.rxjs.Observable.prototype.zip)
1.  [function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>zipAll (project)](#apidoc.element.rxjs.Observable.prototype.zipAll)

#### [module rxjs.ReplaySubject](#apidoc.module.rxjs.ReplaySubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ReplaySubject (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.ReplaySubject.ReplaySubject)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.</span>create (destination, source)](#apidoc.element.rxjs.ReplaySubject.create)

#### [module rxjs.ReplaySubject.prototype](#apidoc.module.rxjs.ReplaySubject.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_getNow ()](#apidoc.element.rxjs.ReplaySubject.prototype._getNow)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.ReplaySubject.prototype._subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_trimBufferThenGetEvents ()](#apidoc.element.rxjs.ReplaySubject.prototype._trimBufferThenGetEvents)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>constructor (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.ReplaySubject.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>next (value)](#apidoc.element.rxjs.ReplaySubject.prototype.next)

#### [module rxjs.Subject](#apidoc.module.rxjs.Subject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Subject ()](#apidoc.element.rxjs.Subject.Subject)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.</span>create (destination, source)](#apidoc.element.rxjs.Subject.create)

#### [module rxjs.Subject.prototype](#apidoc.module.rxjs.Subject.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.Subject.prototype._subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>_trySubscribe (subscriber)](#apidoc.element.rxjs.Subject.prototype._trySubscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>asObservable ()](#apidoc.element.rxjs.Subject.prototype.asObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>complete ()](#apidoc.element.rxjs.Subject.prototype.complete)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>constructor ()](#apidoc.element.rxjs.Subject.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>error (err)](#apidoc.element.rxjs.Subject.prototype.error)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>lift (operator)](#apidoc.element.rxjs.Subject.prototype.lift)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>next (value)](#apidoc.element.rxjs.Subject.prototype.next)
1.  [function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>unsubscribe ()](#apidoc.element.rxjs.Subject.prototype.unsubscribe)

#### [module rxjs.Subscriber](#apidoc.module.rxjs.Subscriber)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Subscriber (destinationOrNext, error, complete)](#apidoc.element.rxjs.Subscriber.Subscriber)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.</span>create (next, error, complete)](#apidoc.element.rxjs.Subscriber.create)
1.  object <span class="apidocSignatureSpan">rxjs.Subscriber.</span>EMPTY

#### [module rxjs.Subscriber.prototype](#apidoc.module.rxjs.Subscriber.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>_complete ()](#apidoc.element.rxjs.Subscriber.prototype._complete)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>_error (err)](#apidoc.element.rxjs.Subscriber.prototype._error)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>_next (value)](#apidoc.element.rxjs.Subscriber.prototype._next)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>_unsubscribeAndRecycle ()](#apidoc.element.rxjs.Subscriber.prototype._unsubscribeAndRecycle)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>complete ()](#apidoc.element.rxjs.Subscriber.prototype.complete)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>constructor (destinationOrNext, error, complete)](#apidoc.element.rxjs.Subscriber.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>error (err)](#apidoc.element.rxjs.Subscriber.prototype.error)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>next (value)](#apidoc.element.rxjs.Subscriber.prototype.next)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>unsubscribe ()](#apidoc.element.rxjs.Subscriber.prototype.unsubscribe)

#### [module rxjs.Subscription](#apidoc.module.rxjs.Subscription)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Subscription (unsubscribe)](#apidoc.element.rxjs.Subscription.Subscription)
1.  object <span class="apidocSignatureSpan">rxjs.Subscription.</span>EMPTY

#### [module rxjs.Subscription.prototype](#apidoc.module.rxjs.Subscription.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscription.prototype.</span>_addParent (parent)](#apidoc.element.rxjs.Subscription.prototype._addParent)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscription.prototype.</span>add (teardown)](#apidoc.element.rxjs.Subscription.prototype.add)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscription.prototype.</span>remove (subscription)](#apidoc.element.rxjs.Subscription.prototype.remove)
1.  [function <span class="apidocSignatureSpan">rxjs.Subscription.prototype.</span>unsubscribe ()](#apidoc.element.rxjs.Subscription.prototype.unsubscribe)

#### [module rxjs.TestScheduler](#apidoc.module.rxjs.TestScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>TestScheduler (assertDeepEqual)](#apidoc.element.rxjs.TestScheduler.TestScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.</span>now ()](#apidoc.element.rxjs.TestScheduler.now)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.</span>parseMarbles (marbles, values, errorValue, materializeInnerObservables)](#apidoc.element.rxjs.TestScheduler.parseMarbles)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.</span>parseMarblesAsSubscriptions (marbles)](#apidoc.element.rxjs.TestScheduler.parseMarblesAsSubscriptions)
1.  number <span class="apidocSignatureSpan">rxjs.TestScheduler.</span>frameTimeFactor

#### [module rxjs.TestScheduler.prototype](#apidoc.module.rxjs.TestScheduler.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>constructor (assertDeepEqual)](#apidoc.element.rxjs.TestScheduler.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>createColdObservable (marbles, values, error)](#apidoc.element.rxjs.TestScheduler.prototype.createColdObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>createHotObservable (marbles, values, error)](#apidoc.element.rxjs.TestScheduler.prototype.createHotObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>createTime (marbles)](#apidoc.element.rxjs.TestScheduler.prototype.createTime)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>expectObservable (observable, unsubscriptionMarbles)](#apidoc.element.rxjs.TestScheduler.prototype.expectObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>expectSubscriptions (actualSubscriptionLogs)](#apidoc.element.rxjs.TestScheduler.prototype.expectSubscriptions)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>flush ()](#apidoc.element.rxjs.TestScheduler.prototype.flush)
1.  [function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>materializeInnerObservable (observable, outerFrame)](#apidoc.element.rxjs.TestScheduler.prototype.materializeInnerObservable)

#### [module rxjs.TimeoutError](#apidoc.module.rxjs.TimeoutError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>TimeoutError ()](#apidoc.element.rxjs.TimeoutError.TimeoutError)
1.  [function <span class="apidocSignatureSpan">rxjs.TimeoutError.</span>captureStackTrace ()](#apidoc.element.rxjs.TimeoutError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.TimeoutError.</span>stackTraceLimit

#### [module rxjs.TimeoutError.prototype](#apidoc.module.rxjs.TimeoutError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.TimeoutError.prototype.</span>constructor ()](#apidoc.element.rxjs.TimeoutError.prototype.constructor)

#### [module rxjs.UnsubscriptionError](#apidoc.module.rxjs.UnsubscriptionError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>UnsubscriptionError (errors)](#apidoc.element.rxjs.UnsubscriptionError.UnsubscriptionError)
1.  [function <span class="apidocSignatureSpan">rxjs.UnsubscriptionError.</span>captureStackTrace ()](#apidoc.element.rxjs.UnsubscriptionError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.UnsubscriptionError.</span>stackTraceLimit

#### [module rxjs.UnsubscriptionError.prototype](#apidoc.module.rxjs.UnsubscriptionError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.UnsubscriptionError.prototype.</span>constructor (errors)](#apidoc.element.rxjs.UnsubscriptionError.prototype.constructor)

#### [module rxjs.VirtualTimeScheduler](#apidoc.module.rxjs.VirtualTimeScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>VirtualTimeScheduler (SchedulerAction, maxFrames)](#apidoc.element.rxjs.VirtualTimeScheduler.VirtualTimeScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.</span>now ()](#apidoc.element.rxjs.VirtualTimeScheduler.now)
1.  number <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.</span>frameTimeFactor

#### [module rxjs.VirtualTimeScheduler.prototype](#apidoc.module.rxjs.VirtualTimeScheduler.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.prototype.</span>constructor (SchedulerAction, maxFrames)](#apidoc.element.rxjs.VirtualTimeScheduler.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.prototype.</span>flush ()](#apidoc.element.rxjs.VirtualTimeScheduler.prototype.flush)



# <a name="apidoc.module.rxjs"></a>[module rxjs](#apidoc.module.rxjs)

#### <a name="apidoc.element.rxjs.AjaxError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AjaxError (message, xhr, request)](#apidoc.element.rxjs.AjaxError)
- description and source-code
```javascript
function AjaxError(message, xhr, request) {
    _super.call(this, message);
    this.message = message;
    this.xhr = xhr;
    this.request = request;
    this.status = xhr.status;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AjaxResponse"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AjaxResponse (originalEvent, xhr, request)](#apidoc.element.rxjs.AjaxResponse)
- description and source-code
```javascript
function AjaxResponse(originalEvent, xhr, request) {
    this.originalEvent = originalEvent;
    this.xhr = xhr;
    this.request = request;
    this.status = xhr.status;
    this.responseType = xhr.responseType || request.responseType;
    switch (this.responseType) {
        case 'json':
            if ('response' in xhr) {
                //IE does not support json as responseType, parse it internally
                this.response = xhr.responseType ? xhr.response : JSON.parse(xhr.response || xhr.responseText || 'null');
            }
            else {
                this.response = JSON.parse(xhr.responseText || 'null');
            }
            break;
        case 'xml':
            this.response = xhr.responseXML;
            break;
        case 'text':
        default:
            this.response = ('response' in xhr) ? xhr.response : xhr.responseText;
            break;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AjaxTimeoutError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AjaxTimeoutError (xhr, request)](#apidoc.element.rxjs.AjaxTimeoutError)
- description and source-code
```javascript
function AjaxTimeoutError(xhr, request) {
    _super.call(this, 'ajax timeout', xhr, request);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AnonymousSubject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AnonymousSubject (destination, source)](#apidoc.element.rxjs.AnonymousSubject)
- description and source-code
```javascript
function AnonymousSubject(destination, source) {
    _super.call(this);
    this.destination = destination;
    this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ArgumentOutOfRangeError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ArgumentOutOfRangeError ()](#apidoc.element.rxjs.ArgumentOutOfRangeError)
- description and source-code
```javascript
function ArgumentOutOfRangeError() {
    var err = _super.call(this, 'argument out of range');
    this.name = err.name = 'ArgumentOutOfRangeError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AsyncSubject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AsyncSubject ()](#apidoc.element.rxjs.AsyncSubject)
- description and source-code
```javascript
function AsyncSubject() {
    _super.apply(this, arguments);
    this.value = null;
    this.hasNext = false;
    this.hasCompleted = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.BehaviorSubject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>BehaviorSubject (_value)](#apidoc.element.rxjs.BehaviorSubject)
- description and source-code
```javascript
function BehaviorSubject(_value) {
    _super.call(this);
    this._value = _value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ConnectableObservable (source, subjectFactory)](#apidoc.element.rxjs.ConnectableObservable)
- description and source-code
```javascript
function ConnectableObservable(source, subjectFactory) {
    _super.call(this);
    this.source = source;
    this.subjectFactory = subjectFactory;
    this._refCount = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ConnectableObservable.ajax (urlOrRequest)](#apidoc.element.rxjs.ConnectableObservable.ajax)
- description and source-code
```javascript
ConnectableObservable.ajax = function (urlOrRequest) {
    return new AjaxObservable(urlOrRequest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.EmptyError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>EmptyError ()](#apidoc.element.rxjs.EmptyError)
- description and source-code
```javascript
function EmptyError() {
    var err = _super.call(this, 'no elements in sequence');
    this.name = err.name = 'EmptyError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Notification"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Notification (kind, value, error)](#apidoc.element.rxjs.Notification)
- description and source-code
```javascript
function Notification(kind, value, error) {
    this.kind = kind;
    this.value = value;
    this.error = error;
    this.hasValue = kind === 'N';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ObjectUnsubscribedError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ObjectUnsubscribedError ()](#apidoc.element.rxjs.ObjectUnsubscribedError)
- description and source-code
```javascript
function ObjectUnsubscribedError() {
    var err = _super.call(this, 'object unsubscribed');
    this.name = err.name = 'ObjectUnsubscribedError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Observable (subscribe)](#apidoc.element.rxjs.Observable)
- description and source-code
```javascript
function Observable(subscribe) {
    this._isScalar = false;
    if (subscribe) {
        this._subscribe = subscribe;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ReplaySubject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ReplaySubject (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.ReplaySubject)
- description and source-code
```javascript
function ReplaySubject(bufferSize, windowTime, scheduler) {
    if (bufferSize === void 0) { bufferSize = Number.POSITIVE_INFINITY; }
    if (windowTime === void 0) { windowTime = Number.POSITIVE_INFINITY; }
    _super.call(this);
    this.scheduler = scheduler;
    this._events = [];
    this._bufferSize = bufferSize < 1 ? 1 : bufferSize;
    this._windowTime = windowTime < 1 ? 1 : windowTime;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Subject ()](#apidoc.element.rxjs.Subject)
- description and source-code
```javascript
function Subject() {
    _super.call(this);
    this.observers = [];
    this.closed = false;
    this.isStopped = false;
    this.hasError = false;
    this.thrownError = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscriber"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Subscriber (destinationOrNext, error, complete)](#apidoc.element.rxjs.Subscriber)
- description and source-code
```javascript
function Subscriber(destinationOrNext, error, complete) {
    _super.call(this);
    this.syncErrorValue = null;
    this.syncErrorThrown = false;
    this.syncErrorThrowable = false;
    this.isStopped = false;
    switch (arguments.length) {
        case 0:
            this.destination = Observer_1.empty;
            break;
        case 1:
            if (!destinationOrNext) {
                this.destination = Observer_1.empty;
                break;
            }
            if (typeof destinationOrNext === 'object') {
                if (destinationOrNext instanceof Subscriber) {
                    this.destination = destinationOrNext;
                    this.destination.add(this);
                }
                else {
                    this.syncErrorThrowable = true;
                    this.destination = new SafeSubscriber(this, destinationOrNext);
                }
                break;
            }
        default:
            this.syncErrorThrowable = true;
            this.destination = new SafeSubscriber(this, destinationOrNext, error, complete);
            break;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscription"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Subscription (unsubscribe)](#apidoc.element.rxjs.Subscription)
- description and source-code
```javascript
function Subscription(unsubscribe) {
<span class="apidocCodeCommentSpan">    /**
     * A flag to indicate whether this Subscription has already been unsubscribed.
     * @type {boolean}
     */
</span>    this.closed = false;
    this._parent = null;
    this._parents = null;
    this._subscriptions = null;
    if (unsubscribe) {
        this._unsubscribe = unsubscribe;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>TestScheduler (assertDeepEqual)](#apidoc.element.rxjs.TestScheduler)
- description and source-code
```javascript
function TestScheduler(assertDeepEqual) {
    _super.call(this, VirtualTimeScheduler_1.VirtualAction, defaultMaxFrame);
    this.assertDeepEqual = assertDeepEqual;
    this.hotObservables = [];
    this.coldObservables = [];
    this.flushTests = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TimeInterval"></a>[function <span class="apidocSignatureSpan">rxjs.</span>TimeInterval (value, interval)](#apidoc.element.rxjs.TimeInterval)
- description and source-code
```javascript
function TimeInterval(value, interval) {
    this.value = value;
    this.interval = interval;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TimeoutError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>TimeoutError ()](#apidoc.element.rxjs.TimeoutError)
- description and source-code
```javascript
function TimeoutError() {
    var err = _super.call(this, 'Timeout has occurred');
    this.name = err.name = 'TimeoutError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Timestamp"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Timestamp (value, timestamp)](#apidoc.element.rxjs.Timestamp)
- description and source-code
```javascript
function Timestamp(value, timestamp) {
    this.value = value;
    this.timestamp = timestamp;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.UnsubscriptionError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>UnsubscriptionError (errors)](#apidoc.element.rxjs.UnsubscriptionError)
- description and source-code
```javascript
function UnsubscriptionError(errors) {
    _super.call(this);
    this.errors = errors;
    var err = Error.call(this, errors ?
        errors.length + " errors occurred during unsubscription:\n  " + errors.map(function (err, i) { return ((i + 1) + ") " +
err.toString()); }).join('\n  ') : '');
    this.name = err.name = 'UnsubscriptionError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.VirtualTimeScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>VirtualTimeScheduler (SchedulerAction, maxFrames)](#apidoc.element.rxjs.VirtualTimeScheduler)
- description and source-code
```javascript
function VirtualTimeScheduler(SchedulerAction, maxFrames) {
    var _this = this;
    if (SchedulerAction === void 0) { SchedulerAction = VirtualAction; }
    if (maxFrames === void 0) { maxFrames = Number.POSITIVE_INFINITY; }
    _super.call(this, SchedulerAction, function () { return _this.frame; });
    this.maxFrames = maxFrames;
    this.frame = 0;
    this.index = -1;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AjaxError"></a>[module rxjs.AjaxError](#apidoc.module.rxjs.AjaxError)

#### <a name="apidoc.element.rxjs.AjaxError.AjaxError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AjaxError (message, xhr, request)](#apidoc.element.rxjs.AjaxError.AjaxError)
- description and source-code
```javascript
function AjaxError(message, xhr, request) {
    _super.call(this, message);
    this.message = message;
    this.xhr = xhr;
    this.request = request;
    this.status = xhr.status;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AjaxError.captureStackTrace"></a>[function <span class="apidocSignatureSpan">rxjs.AjaxError.</span>captureStackTrace ()](#apidoc.element.rxjs.AjaxError.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AjaxError.prototype"></a>[module rxjs.AjaxError.prototype](#apidoc.module.rxjs.AjaxError.prototype)

#### <a name="apidoc.element.rxjs.AjaxError.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.AjaxError.prototype.</span>constructor (message, xhr, request)](#apidoc.element.rxjs.AjaxError.prototype.constructor)
- description and source-code
```javascript
function AjaxError(message, xhr, request) {
    _super.call(this, message);
    this.message = message;
    this.xhr = xhr;
    this.request = request;
    this.status = xhr.status;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AjaxTimeoutError"></a>[module rxjs.AjaxTimeoutError](#apidoc.module.rxjs.AjaxTimeoutError)

#### <a name="apidoc.element.rxjs.AjaxTimeoutError.AjaxTimeoutError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AjaxTimeoutError (xhr, request)](#apidoc.element.rxjs.AjaxTimeoutError.AjaxTimeoutError)
- description and source-code
```javascript
function AjaxTimeoutError(xhr, request) {
    _super.call(this, 'ajax timeout', xhr, request);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AjaxTimeoutError.captureStackTrace"></a>[function <span class="apidocSignatureSpan">rxjs.AjaxTimeoutError.</span>captureStackTrace ()](#apidoc.element.rxjs.AjaxTimeoutError.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AjaxTimeoutError.prototype"></a>[module rxjs.AjaxTimeoutError.prototype](#apidoc.module.rxjs.AjaxTimeoutError.prototype)

#### <a name="apidoc.element.rxjs.AjaxTimeoutError.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.AjaxTimeoutError.prototype.</span>constructor (xhr, request)](#apidoc.element.rxjs.AjaxTimeoutError.prototype.constructor)
- description and source-code
```javascript
function AjaxTimeoutError(xhr, request) {
    _super.call(this, 'ajax timeout', xhr, request);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AnonymousSubject"></a>[module rxjs.AnonymousSubject](#apidoc.module.rxjs.AnonymousSubject)

#### <a name="apidoc.element.rxjs.AnonymousSubject.AnonymousSubject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AnonymousSubject (destination, source)](#apidoc.element.rxjs.AnonymousSubject.AnonymousSubject)
- description and source-code
```javascript
function AnonymousSubject(destination, source) {
    _super.call(this);
    this.destination = destination;
    this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AnonymousSubject.create"></a>[function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.</span>create (destination, source)](#apidoc.element.rxjs.AnonymousSubject.create)
- description and source-code
```javascript
create = function (destination, source) {
    return new AnonymousSubject(destination, source);
}
```
- example usage
```shell
...



"use strict";
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var Subject_1 = require('./Subject');
var Subscription_1 = require('./Subscription');
/**
 * @class AsyncSubject<T>
 */
var AsyncSubject = (function (_super) {
...
```



# <a name="apidoc.module.rxjs.AnonymousSubject.prototype"></a>[module rxjs.AnonymousSubject.prototype](#apidoc.module.rxjs.AnonymousSubject.prototype)

#### <a name="apidoc.element.rxjs.AnonymousSubject.prototype._subscribe"></a>[function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.AnonymousSubject.prototype._subscribe)
- description and source-code
```javascript
_subscribe = function (subscriber) {
    var source = this.source;
    if (source) {
        return this.source.subscribe(subscriber);
    }
    else {
        return Subscription_1.Subscription.EMPTY;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AnonymousSubject.prototype.complete"></a>[function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>complete ()](#apidoc.element.rxjs.AnonymousSubject.prototype.complete)
- description and source-code
```javascript
complete = function () {
    var destination = this.destination;
    if (destination && destination.complete) {
        this.destination.complete();
    }
}
```
- example usage
```shell
...
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
        this.value = value;
...
```

#### <a name="apidoc.element.rxjs.AnonymousSubject.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>constructor (destination, source)](#apidoc.element.rxjs.AnonymousSubject.prototype.constructor)
- description and source-code
```javascript
function AnonymousSubject(destination, source) {
    _super.call(this);
    this.destination = destination;
    this.source = source;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AnonymousSubject.prototype.error"></a>[function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>error (err)](#apidoc.element.rxjs.AnonymousSubject.prototype.error)
- description and source-code
```javascript
error = function (err) {
    var destination = this.destination;
    if (destination && destination.error) {
        this.destination.error(err);
    }
}
```
- example usage
```shell
...
    _super.apply(this, arguments);
    this.value = null;
    this.hasNext = false;
    this.hasCompleted = false;
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
...
```

#### <a name="apidoc.element.rxjs.AnonymousSubject.prototype.next"></a>[function <span class="apidocSignatureSpan">rxjs.AnonymousSubject.prototype.</span>next (value)](#apidoc.element.rxjs.AnonymousSubject.prototype.next)
- description and source-code
```javascript
next = function (value) {
    var destination = this.destination;
    if (destination && destination.next) {
        destination.next(value);
    }
}
```
- example usage
```shell
...
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
...
```



# <a name="apidoc.module.rxjs.ArgumentOutOfRangeError"></a>[module rxjs.ArgumentOutOfRangeError](#apidoc.module.rxjs.ArgumentOutOfRangeError)

#### <a name="apidoc.element.rxjs.ArgumentOutOfRangeError.ArgumentOutOfRangeError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ArgumentOutOfRangeError ()](#apidoc.element.rxjs.ArgumentOutOfRangeError.ArgumentOutOfRangeError)
- description and source-code
```javascript
function ArgumentOutOfRangeError() {
    var err = _super.call(this, 'argument out of range');
    this.name = err.name = 'ArgumentOutOfRangeError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ArgumentOutOfRangeError.captureStackTrace"></a>[function <span class="apidocSignatureSpan">rxjs.ArgumentOutOfRangeError.</span>captureStackTrace ()](#apidoc.element.rxjs.ArgumentOutOfRangeError.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.ArgumentOutOfRangeError.prototype"></a>[module rxjs.ArgumentOutOfRangeError.prototype](#apidoc.module.rxjs.ArgumentOutOfRangeError.prototype)

#### <a name="apidoc.element.rxjs.ArgumentOutOfRangeError.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.ArgumentOutOfRangeError.prototype.</span>constructor ()](#apidoc.element.rxjs.ArgumentOutOfRangeError.prototype.constructor)
- description and source-code
```javascript
function ArgumentOutOfRangeError() {
    var err = _super.call(this, 'argument out of range');
    this.name = err.name = 'ArgumentOutOfRangeError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AsyncSubject"></a>[module rxjs.AsyncSubject](#apidoc.module.rxjs.AsyncSubject)

#### <a name="apidoc.element.rxjs.AsyncSubject.AsyncSubject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AsyncSubject ()](#apidoc.element.rxjs.AsyncSubject.AsyncSubject)
- description and source-code
```javascript
function AsyncSubject() {
    _super.apply(this, arguments);
    this.value = null;
    this.hasNext = false;
    this.hasCompleted = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AsyncSubject.create"></a>[function <span class="apidocSignatureSpan">rxjs.AsyncSubject.</span>create (destination, source)](#apidoc.element.rxjs.AsyncSubject.create)
- description and source-code
```javascript
create = function (destination, source) {
    return new AnonymousSubject(destination, source);
}
```
- example usage
```shell
...



"use strict";
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var Subject_1 = require('./Subject');
var Subscription_1 = require('./Subscription');
/**
 * @class AsyncSubject<T>
 */
var AsyncSubject = (function (_super) {
...
```



# <a name="apidoc.module.rxjs.AsyncSubject.prototype"></a>[module rxjs.AsyncSubject.prototype](#apidoc.module.rxjs.AsyncSubject.prototype)

#### <a name="apidoc.element.rxjs.AsyncSubject.prototype._subscribe"></a>[function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.AsyncSubject.prototype._subscribe)
- description and source-code
```javascript
_subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AsyncSubject.prototype.complete"></a>[function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>complete ()](#apidoc.element.rxjs.AsyncSubject.prototype.complete)
- description and source-code
```javascript
complete = function () {
    this.hasCompleted = true;
    if (this.hasNext) {
        _super.prototype.next.call(this, this.value);
    }
    _super.prototype.complete.call(this);
}
```
- example usage
```shell
...
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
        this.value = value;
...
```

#### <a name="apidoc.element.rxjs.AsyncSubject.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>constructor ()](#apidoc.element.rxjs.AsyncSubject.prototype.constructor)
- description and source-code
```javascript
function AsyncSubject() {
    _super.apply(this, arguments);
    this.value = null;
    this.hasNext = false;
    this.hasCompleted = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.AsyncSubject.prototype.error"></a>[function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>error (error)](#apidoc.element.rxjs.AsyncSubject.prototype.error)
- description and source-code
```javascript
error = function (error) {
    if (!this.hasCompleted) {
        _super.prototype.error.call(this, error);
    }
}
```
- example usage
```shell
...
    _super.apply(this, arguments);
    this.value = null;
    this.hasNext = false;
    this.hasCompleted = false;
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
...
```

#### <a name="apidoc.element.rxjs.AsyncSubject.prototype.next"></a>[function <span class="apidocSignatureSpan">rxjs.AsyncSubject.prototype.</span>next (value)](#apidoc.element.rxjs.AsyncSubject.prototype.next)
- description and source-code
```javascript
next = function (value) {
    if (!this.hasCompleted) {
        this.value = value;
        this.hasNext = true;
    }
}
```
- example usage
```shell
...
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
...
```



# <a name="apidoc.module.rxjs.BehaviorSubject"></a>[module rxjs.BehaviorSubject](#apidoc.module.rxjs.BehaviorSubject)

#### <a name="apidoc.element.rxjs.BehaviorSubject.BehaviorSubject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>BehaviorSubject (_value)](#apidoc.element.rxjs.BehaviorSubject.BehaviorSubject)
- description and source-code
```javascript
function BehaviorSubject(_value) {
    _super.call(this);
    this._value = _value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.BehaviorSubject.create"></a>[function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.</span>create (destination, source)](#apidoc.element.rxjs.BehaviorSubject.create)
- description and source-code
```javascript
create = function (destination, source) {
    return new AnonymousSubject(destination, source);
}
```
- example usage
```shell
...



"use strict";
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var Subject_1 = require('./Subject');
var Subscription_1 = require('./Subscription');
/**
 * @class AsyncSubject<T>
 */
var AsyncSubject = (function (_super) {
...
```



# <a name="apidoc.module.rxjs.BehaviorSubject.prototype"></a>[module rxjs.BehaviorSubject.prototype](#apidoc.module.rxjs.BehaviorSubject.prototype)

#### <a name="apidoc.element.rxjs.BehaviorSubject.prototype._subscribe"></a>[function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.BehaviorSubject.prototype._subscribe)
- description and source-code
```javascript
_subscribe = function (subscriber) {
    var subscription = _super.prototype._subscribe.call(this, subscriber);
    if (subscription && !subscription.closed) {
        subscriber.next(this._value);
    }
    return subscription;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.BehaviorSubject.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.prototype.</span>constructor (_value)](#apidoc.element.rxjs.BehaviorSubject.prototype.constructor)
- description and source-code
```javascript
function BehaviorSubject(_value) {
    _super.call(this);
    this._value = _value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.BehaviorSubject.prototype.getValue"></a>[function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.prototype.</span>getValue ()](#apidoc.element.rxjs.BehaviorSubject.prototype.getValue)
- description and source-code
```javascript
getValue = function () {
    if (this.hasError) {
        throw this.thrownError;
    }
    else if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    else {
        return this._value;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.BehaviorSubject.prototype.next"></a>[function <span class="apidocSignatureSpan">rxjs.BehaviorSubject.prototype.</span>next (value)](#apidoc.element.rxjs.BehaviorSubject.prototype.next)
- description and source-code
```javascript
next = function (value) {
    _super.prototype.next.call(this, this._value = value);
}
```
- example usage
```shell
...
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
...
```



# <a name="apidoc.module.rxjs.ConnectableObservable"></a>[module rxjs.ConnectableObservable](#apidoc.module.rxjs.ConnectableObservable)

#### <a name="apidoc.element.rxjs.ConnectableObservable.ConnectableObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ConnectableObservable (source, subjectFactory)](#apidoc.element.rxjs.ConnectableObservable.ConnectableObservable)
- description and source-code
```javascript
function ConnectableObservable(source, subjectFactory) {
    _super.call(this);
    this.source = source;
    this.subjectFactory = subjectFactory;
    this._refCount = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>ajax (urlOrRequest)](#apidoc.element.rxjs.ConnectableObservable.ajax)
- description and source-code
```javascript
ajax = function (urlOrRequest) {
    return new AjaxObservable(urlOrRequest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.bindCallback"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>bindCallback (func, selector, scheduler)](#apidoc.element.rxjs.ConnectableObservable.bindCallback)
- description and source-code
```javascript
bindCallback = function (func, selector, scheduler) {
    if (selector === void 0) { selector = undefined; }
    return function () {
        var args = [];
        for (var _i = 0; _i < arguments.length; _i++) {
            args[_i - 0] = arguments[_i];
        }
        return new BoundCallbackObservable(func, selector, args, this, scheduler);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.bindNodeCallback"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>bindNodeCallback (func, selector, scheduler)](#apidoc.element.rxjs.ConnectableObservable.bindNodeCallback)
- description and source-code
```javascript
bindNodeCallback = function (func, selector, scheduler) {
    if (selector === void 0) { selector = undefined; }
    return function () {
        var args = [];
        for (var _i = 0; _i < arguments.length; _i++) {
            args[_i - 0] = arguments[_i];
        }
        return new BoundNodeCallbackObservable(func, selector, args, this, scheduler);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.combineLatest"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>combineLatest ()](#apidoc.element.rxjs.ConnectableObservable.combineLatest)
- description and source-code
```javascript
function combineLatest() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var project = null;
    var scheduler = null;
    if (isScheduler_1.isScheduler(observables[observables.length - 1])) {
        scheduler = observables.pop();
    }
    if (typeof observables[observables.length - 1] === 'function') {
        project = observables.pop();
    }
    // if the first and only other argument besides the resultSelector is an array
    // assume it's been called with 'combineLatest([obs1, obs2, obs3], project)'
    if (observables.length === 1 && isArray_1.isArray(observables[0])) {
        observables = observables[0];
    }
    return new ArrayObservable_1.ArrayObservable(observables, scheduler).lift(new combineLatest_1.CombineLatestOperator(project));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.concat"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>concat ()](#apidoc.element.rxjs.ConnectableObservable.concat)
- description and source-code
```javascript
function concatStatic() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var scheduler = null;
    var args = observables;
    if (isScheduler_1.isScheduler(args[observables.length - 1])) {
        scheduler = args.pop();
    }
    if (scheduler === null && observables.length === 1 && observables[0] instanceof Observable_1.Observable) {
        return observables[0];
    }
    return new ArrayObservable_1.ArrayObservable(observables, scheduler).lift(new mergeAll_1.MergeAllOperator(1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.create"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>create (subscribe)](#apidoc.element.rxjs.ConnectableObservable.create)
- description and source-code
```javascript
create = function (subscribe) {
    return new Observable(subscribe);
}
```
- example usage
```shell
...



"use strict";
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var Subject_1 = require('./Subject');
var Subscription_1 = require('./Subscription');
/**
 * @class AsyncSubject<T>
 */
var AsyncSubject = (function (_super) {
...
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.defer"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>defer (observableFactory)](#apidoc.element.rxjs.ConnectableObservable.defer)
- description and source-code
```javascript
defer = function (observableFactory) {
    return new DeferObservable(observableFactory);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.empty"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>empty (scheduler)](#apidoc.element.rxjs.ConnectableObservable.empty)
- description and source-code
```javascript
empty = function (scheduler) {
    return new EmptyObservable(scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.forkJoin"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>forkJoin ()](#apidoc.element.rxjs.ConnectableObservable.forkJoin)
- description and source-code
```javascript
forkJoin = function () {
    var sources = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        sources[_i - 0] = arguments[_i];
    }
    if (sources === null || arguments.length === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    var resultSelector = null;
    if (typeof sources[sources.length - 1] === 'function') {
        resultSelector = sources.pop();
    }
    // if the first and only other argument besides the resultSelector is an array
    // assume it's been called with 'forkJoin([obs1, obs2, obs3], resultSelector)'
    if (sources.length === 1 && isArray_1.isArray(sources[0])) {
        sources = sources[0];
    }
    if (sources.length === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    return new ForkJoinObservable(sources, resultSelector);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.from"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>from (ish, scheduler)](#apidoc.element.rxjs.ConnectableObservable.from)
- description and source-code
```javascript
from = function (ish, scheduler) {
    if (ish != null) {
        if (typeof ish[observable_1.observable] === 'function') {
            if (ish instanceof Observable_1.Observable && !scheduler) {
                return ish;
            }
            return new FromObservable(ish, scheduler);
        }
        else if (isArray_1.isArray(ish)) {
            return new ArrayObservable_1.ArrayObservable(ish, scheduler);
        }
        else if (isPromise_1.isPromise(ish)) {
            return new PromiseObservable_1.PromiseObservable(ish, scheduler);
        }
        else if (typeof ish[iterator_1.iterator] === 'function' || typeof ish === 'string') {
            return new IteratorObservable_1.IteratorObservable(ish, scheduler);
        }
        else if (isArrayLike_1.isArrayLike(ish)) {
            return new ArrayLikeObservable_1.ArrayLikeObservable(ish, scheduler);
        }
    }
    throw new TypeError((ish !== null && typeof ish || ish) + ' is not observable');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.fromEvent"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>fromEvent (target, eventName, options, selector)](#apidoc.element.rxjs.ConnectableObservable.fromEvent)
- description and source-code
```javascript
fromEvent = function (target, eventName, options, selector) {
    if (isFunction_1.isFunction(options)) {
        selector = options;
        options = undefined;
    }
    return new FromEventObservable(target, eventName, selector, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.fromEventPattern"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>fromEventPattern (addHandler, removeHandler, selector)](#apidoc.element.rxjs.ConnectableObservable.fromEventPattern)
- description and source-code
```javascript
fromEventPattern = function (addHandler, removeHandler, selector) {
    return new FromEventPatternObservable(addHandler, removeHandler, selector);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.fromPromise"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>fromPromise (promise, scheduler)](#apidoc.element.rxjs.ConnectableObservable.fromPromise)
- description and source-code
```javascript
fromPromise = function (promise, scheduler) {
    return new PromiseObservable(promise, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.generate"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>generate (initialStateOrOptions, condition, iterate, resultSelectorOrObservable, scheduler)](#apidoc.element.rxjs.ConnectableObservable.generate)
- description and source-code
```javascript
generate = function (initialStateOrOptions, condition, iterate, resultSelectorOrObservable, scheduler) {
    if (arguments.length == 1) {
        return new GenerateObservable(initialStateOrOptions.initialState, initialStateOrOptions.condition, initialStateOrOptions
.iterate, initialStateOrOptions.resultSelector || selfSelector, initialStateOrOptions.scheduler);
    }
    if (resultSelectorOrObservable === undefined || isScheduler_1.isScheduler(resultSelectorOrObservable)) {
        return new GenerateObservable(initialStateOrOptions, condition, iterate, selfSelector, resultSelectorOrObservable);
    }
    return new GenerateObservable(initialStateOrOptions, condition, iterate, resultSelectorOrObservable, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.if"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>if (condition, thenSource, elseSource)](#apidoc.element.rxjs.ConnectableObservable.if)
- description and source-code
```javascript
if = function (condition, thenSource, elseSource) {
    return new IfObservable(condition, thenSource, elseSource);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.interval"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>interval (period, scheduler)](#apidoc.element.rxjs.ConnectableObservable.interval)
- description and source-code
```javascript
interval = function (period, scheduler) {
    if (period === void 0) { period = 0; }
    if (scheduler === void 0) { scheduler = async_1.async; }
    return new IntervalObservable(period, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.merge"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>merge ()](#apidoc.element.rxjs.ConnectableObservable.merge)
- description and source-code
```javascript
function mergeStatic() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var concurrent = Number.POSITIVE_INFINITY;
    var scheduler = null;
    var last = observables[observables.length - 1];
    if (isScheduler_1.isScheduler(last)) {
        scheduler = observables.pop();
        if (observables.length > 1 && typeof observables[observables.length - 1] === 'number') {
            concurrent = observables.pop();
        }
    }
    else if (typeof last === 'number') {
        concurrent = observables.pop();
    }
    if (scheduler === null && observables.length === 1 && observables[0] instanceof Observable_1.Observable) {
        return observables[0];
    }
    return new ArrayObservable_1.ArrayObservable(observables, scheduler).lift(new mergeAll_1.MergeAllOperator(concurrent));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.never"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>never ()](#apidoc.element.rxjs.ConnectableObservable.never)
- description and source-code
```javascript
never = function () {
    return new NeverObservable();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.of"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>of ()](#apidoc.element.rxjs.ConnectableObservable.of)
- description and source-code
```javascript
of = function () {
    var array = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        array[_i - 0] = arguments[_i];
    }
    var scheduler = array[array.length - 1];
    if (isScheduler_1.isScheduler(scheduler)) {
        array.pop();
    }
    else {
        scheduler = null;
    }
    var len = array.length;
    if (len > 1) {
        return new ArrayObservable(array, scheduler);
    }
    else if (len === 1) {
        return new ScalarObservable_1.ScalarObservable(array[0], scheduler);
    }
    else {
        return new EmptyObservable_1.EmptyObservable(scheduler);
    }
}
```
- example usage
```shell
...
'''

To import the entire core set of functionality:

'''js
import Rx from 'rxjs/Rx';

Rx.Observable.of(1,2,3)
'''

To import only what you need by patching (this is useful for size-sensitive bundling):

'''js
import { Observable } from 'rxjs/Observable';
import 'rxjs/add/observable/of';
...
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.onErrorResumeNext"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>onErrorResumeNext ()](#apidoc.element.rxjs.ConnectableObservable.onErrorResumeNext)
- description and source-code
```javascript
function onErrorResumeNextStatic() {
    var nextSources = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        nextSources[_i - 0] = arguments[_i];
    }
    var source = null;
    if (nextSources.length === 1 && isArray_1.isArray(nextSources[0])) {
        nextSources = nextSources[0];
    }
    source = nextSources.shift();
    return new FromObservable_1.FromObservable(source, null).lift(new OnErrorResumeNextOperator(nextSources));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.pairs"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>pairs (obj, scheduler)](#apidoc.element.rxjs.ConnectableObservable.pairs)
- description and source-code
```javascript
pairs = function (obj, scheduler) {
    return new PairsObservable(obj, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.race"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>race ()](#apidoc.element.rxjs.ConnectableObservable.race)
- description and source-code
```javascript
function raceStatic() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    // if the only argument is an array, it was most likely called with
    // 'pair([obs1, obs2, ...])'
    if (observables.length === 1) {
        if (isArray_1.isArray(observables[0])) {
            observables = observables[0];
        }
        else {
            return observables[0];
        }
    }
    return new ArrayObservable_1.ArrayObservable(observables).lift(new RaceOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.range"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>range (start, count, scheduler)](#apidoc.element.rxjs.ConnectableObservable.range)
- description and source-code
```javascript
range = function (start, count, scheduler) {
    if (start === void 0) { start = 0; }
    if (count === void 0) { count = 0; }
    return new RangeObservable(start, count, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.throw"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>throw (error, scheduler)](#apidoc.element.rxjs.ConnectableObservable.throw)
- description and source-code
```javascript
throw = function (error, scheduler) {
    return new ErrorObservable(error, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.timer"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>timer (initialDelay, period, scheduler)](#apidoc.element.rxjs.ConnectableObservable.timer)
- description and source-code
```javascript
timer = function (initialDelay, period, scheduler) {
    if (initialDelay === void 0) { initialDelay = 0; }
    return new TimerObservable(initialDelay, period, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.using"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>using (resourceFactory, observableFactory)](#apidoc.element.rxjs.ConnectableObservable.using)
- description and source-code
```javascript
using = function (resourceFactory, observableFactory) {
    return new UsingObservable(resourceFactory, observableFactory);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.webSocket"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>webSocket (urlConfigOrSource)](#apidoc.element.rxjs.ConnectableObservable.webSocket)
- description and source-code
```javascript
webSocket = function (urlConfigOrSource) {
    return new WebSocketSubject(urlConfigOrSource);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.zip"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>zip ()](#apidoc.element.rxjs.ConnectableObservable.zip)
- description and source-code
```javascript
function zipStatic() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var project = observables[observables.length - 1];
    if (typeof project === 'function') {
        observables.pop();
    }
    return new ArrayObservable_1.ArrayObservable(observables).lift(new ZipOperator(project));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.ConnectableObservable.ajax"></a>[module rxjs.ConnectableObservable.ajax](#apidoc.module.rxjs.ConnectableObservable.ajax)

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax.ajax"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.</span>ajax (urlOrRequest)](#apidoc.element.rxjs.ConnectableObservable.ajax.ajax)
- description and source-code
```javascript
ajax = function (urlOrRequest) {
    return new AjaxObservable(urlOrRequest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax.delete"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>delete (url, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.delete)
- description and source-code
```javascript
function ajaxDelete(url, headers) {
    return new AjaxObservable({ method: 'DELETE', url: url, headers: headers });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax.get"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>get (url, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.get)
- description and source-code
```javascript
function ajaxGet(url, headers) {
    if (headers === void 0) { headers = null; }
    return new AjaxObservable({ method: 'GET', url: url, headers: headers });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax.getJSON"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>getJSON (url, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.getJSON)
- description and source-code
```javascript
function ajaxGetJSON(url, headers) {
    return new AjaxObservable({ method: 'GET', url: url, responseType: 'json', headers: headers })
        .lift(new map_1.MapOperator(function (x, index) { return x.response; }, null));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax.patch"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>patch (url, body, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.patch)
- description and source-code
```javascript
function ajaxPatch(url, body, headers) {
    return new AjaxObservable({ method: 'PATCH', url: url, body: body, headers: headers });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax.post"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>post (url, body, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.post)
- description and source-code
```javascript
function ajaxPost(url, body, headers) {
    return new AjaxObservable({ method: 'POST', url: url, body: body, headers: headers });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.ajax.put"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.ajax.</span>put (url, body, headers)](#apidoc.element.rxjs.ConnectableObservable.ajax.put)
- description and source-code
```javascript
function ajaxPut(url, body, headers) {
    return new AjaxObservable({ method: 'PUT', url: url, body: body, headers: headers });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.ConnectableObservable.prototype"></a>[module rxjs.ConnectableObservable.prototype](#apidoc.module.rxjs.ConnectableObservable.prototype)

#### <a name="apidoc.element.rxjs.ConnectableObservable.prototype._subscribe"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.ConnectableObservable.prototype._subscribe)
- description and source-code
```javascript
_subscribe = function (subscriber) {
    return this.getSubject().subscribe(subscriber);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.prototype.connect"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>connect ()](#apidoc.element.rxjs.ConnectableObservable.prototype.connect)
- description and source-code
```javascript
connect = function () {
    var connection = this._connection;
    if (!connection) {
        connection = this._connection = new Subscription_1.Subscription();
        connection.add(this.source
            .subscribe(new ConnectableSubscriber(this.getSubject(), this)));
        if (connection.closed) {
            this._connection = null;
            connection = Subscription_1.Subscription.EMPTY;
        }
        else {
            this._connection = connection;
        }
    }
    return connection;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>constructor (source, subjectFactory)](#apidoc.element.rxjs.ConnectableObservable.prototype.constructor)
- description and source-code
```javascript
function ConnectableObservable(source, subjectFactory) {
    _super.call(this);
    this.source = source;
    this.subjectFactory = subjectFactory;
    this._refCount = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.prototype.getSubject"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>getSubject ()](#apidoc.element.rxjs.ConnectableObservable.prototype.getSubject)
- description and source-code
```javascript
getSubject = function () {
    var subject = this._subject;
    if (!subject || subject.isStopped) {
        this._subject = this.subjectFactory();
    }
    return this._subject;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ConnectableObservable.prototype.refCount"></a>[function <span class="apidocSignatureSpan">rxjs.ConnectableObservable.prototype.</span>refCount ()](#apidoc.element.rxjs.ConnectableObservable.prototype.refCount)
- description and source-code
```javascript
refCount = function () {
    return this.lift(new RefCountOperator(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.EmptyError"></a>[module rxjs.EmptyError](#apidoc.module.rxjs.EmptyError)

#### <a name="apidoc.element.rxjs.EmptyError.EmptyError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>EmptyError ()](#apidoc.element.rxjs.EmptyError.EmptyError)
- description and source-code
```javascript
function EmptyError() {
    var err = _super.call(this, 'no elements in sequence');
    this.name = err.name = 'EmptyError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.EmptyError.captureStackTrace"></a>[function <span class="apidocSignatureSpan">rxjs.EmptyError.</span>captureStackTrace ()](#apidoc.element.rxjs.EmptyError.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.EmptyError.prototype"></a>[module rxjs.EmptyError.prototype](#apidoc.module.rxjs.EmptyError.prototype)

#### <a name="apidoc.element.rxjs.EmptyError.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.EmptyError.prototype.</span>constructor ()](#apidoc.element.rxjs.EmptyError.prototype.constructor)
- description and source-code
```javascript
function EmptyError() {
    var err = _super.call(this, 'no elements in sequence');
    this.name = err.name = 'EmptyError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Notification"></a>[module rxjs.Notification](#apidoc.module.rxjs.Notification)

#### <a name="apidoc.element.rxjs.Notification.Notification"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Notification (kind, value, error)](#apidoc.element.rxjs.Notification.Notification)
- description and source-code
```javascript
function Notification(kind, value, error) {
    this.kind = kind;
    this.value = value;
    this.error = error;
    this.hasValue = kind === 'N';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Notification.createComplete"></a>[function <span class="apidocSignatureSpan">rxjs.Notification.</span>createComplete ()](#apidoc.element.rxjs.Notification.createComplete)
- description and source-code
```javascript
createComplete = function () {
    return this.completeNotification;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Notification.createError"></a>[function <span class="apidocSignatureSpan">rxjs.Notification.</span>createError (err)](#apidoc.element.rxjs.Notification.createError)
- description and source-code
```javascript
createError = function (err) {
    return new Notification('E', undefined, err);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Notification.createNext"></a>[function <span class="apidocSignatureSpan">rxjs.Notification.</span>createNext (value)](#apidoc.element.rxjs.Notification.createNext)
- description and source-code
```javascript
createNext = function (value) {
    if (typeof value !== 'undefined') {
        return new Notification('N', value);
    }
    return this.undefinedValueNotification;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Notification.prototype"></a>[module rxjs.Notification.prototype](#apidoc.module.rxjs.Notification.prototype)

#### <a name="apidoc.element.rxjs.Notification.prototype.accept"></a>[function <span class="apidocSignatureSpan">rxjs.Notification.prototype.</span>accept (nextOrObserver, error, complete)](#apidoc.element.rxjs.Notification.prototype.accept)
- description and source-code
```javascript
accept = function (nextOrObserver, error, complete) {
    if (nextOrObserver && typeof nextOrObserver.next === 'function') {
        return this.observe(nextOrObserver);
    }
    else {
        return this.do(nextOrObserver, error, complete);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Notification.prototype.do"></a>[function <span class="apidocSignatureSpan">rxjs.Notification.prototype.</span>do (next, error, complete)](#apidoc.element.rxjs.Notification.prototype.do)
- description and source-code
```javascript
do = function (next, error, complete) {
    var kind = this.kind;
    switch (kind) {
        case 'N':
            return next && next(this.value);
        case 'E':
            return error && error(this.error);
        case 'C':
            return complete && complete();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Notification.prototype.observe"></a>[function <span class="apidocSignatureSpan">rxjs.Notification.prototype.</span>observe (observer)](#apidoc.element.rxjs.Notification.prototype.observe)
- description and source-code
```javascript
observe = function (observer) {
    switch (this.kind) {
        case 'N':
            return observer.next && observer.next(this.value);
        case 'E':
            return observer.error && observer.error(this.error);
        case 'C':
            return observer.complete && observer.complete();
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Notification.prototype.toObservable"></a>[function <span class="apidocSignatureSpan">rxjs.Notification.prototype.</span>toObservable ()](#apidoc.element.rxjs.Notification.prototype.toObservable)
- description and source-code
```javascript
toObservable = function () {
    var kind = this.kind;
    switch (kind) {
        case 'N':
            return Observable_1.Observable.of(this.value);
        case 'E':
            return Observable_1.Observable.throw(this.error);
        case 'C':
            return Observable_1.Observable.empty();
    }
    throw new Error('unexpected notification kind value');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.ObjectUnsubscribedError"></a>[module rxjs.ObjectUnsubscribedError](#apidoc.module.rxjs.ObjectUnsubscribedError)

#### <a name="apidoc.element.rxjs.ObjectUnsubscribedError.ObjectUnsubscribedError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ObjectUnsubscribedError ()](#apidoc.element.rxjs.ObjectUnsubscribedError.ObjectUnsubscribedError)
- description and source-code
```javascript
function ObjectUnsubscribedError() {
    var err = _super.call(this, 'object unsubscribed');
    this.name = err.name = 'ObjectUnsubscribedError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ObjectUnsubscribedError.captureStackTrace"></a>[function <span class="apidocSignatureSpan">rxjs.ObjectUnsubscribedError.</span>captureStackTrace ()](#apidoc.element.rxjs.ObjectUnsubscribedError.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.ObjectUnsubscribedError.prototype"></a>[module rxjs.ObjectUnsubscribedError.prototype](#apidoc.module.rxjs.ObjectUnsubscribedError.prototype)

#### <a name="apidoc.element.rxjs.ObjectUnsubscribedError.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.ObjectUnsubscribedError.prototype.</span>constructor ()](#apidoc.element.rxjs.ObjectUnsubscribedError.prototype.constructor)
- description and source-code
```javascript
function ObjectUnsubscribedError() {
    var err = _super.call(this, 'object unsubscribed');
    this.name = err.name = 'ObjectUnsubscribedError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Observable"></a>[module rxjs.Observable](#apidoc.module.rxjs.Observable)

#### <a name="apidoc.element.rxjs.Observable.Observable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Observable (subscribe)](#apidoc.element.rxjs.Observable.Observable)
- description and source-code
```javascript
function Observable(subscribe) {
    this._isScalar = false;
    if (subscribe) {
        this._subscribe = subscribe;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.ajax"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>ajax (urlOrRequest)](#apidoc.element.rxjs.Observable.ajax)
- description and source-code
```javascript
ajax = function (urlOrRequest) {
    return new AjaxObservable(urlOrRequest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.bindCallback"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>bindCallback (func, selector, scheduler)](#apidoc.element.rxjs.Observable.bindCallback)
- description and source-code
```javascript
bindCallback = function (func, selector, scheduler) {
    if (selector === void 0) { selector = undefined; }
    return function () {
        var args = [];
        for (var _i = 0; _i < arguments.length; _i++) {
            args[_i - 0] = arguments[_i];
        }
        return new BoundCallbackObservable(func, selector, args, this, scheduler);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.bindNodeCallback"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>bindNodeCallback (func, selector, scheduler)](#apidoc.element.rxjs.Observable.bindNodeCallback)
- description and source-code
```javascript
bindNodeCallback = function (func, selector, scheduler) {
    if (selector === void 0) { selector = undefined; }
    return function () {
        var args = [];
        for (var _i = 0; _i < arguments.length; _i++) {
            args[_i - 0] = arguments[_i];
        }
        return new BoundNodeCallbackObservable(func, selector, args, this, scheduler);
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.combineLatest"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>combineLatest ()](#apidoc.element.rxjs.Observable.combineLatest)
- description and source-code
```javascript
function combineLatest() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var project = null;
    var scheduler = null;
    if (isScheduler_1.isScheduler(observables[observables.length - 1])) {
        scheduler = observables.pop();
    }
    if (typeof observables[observables.length - 1] === 'function') {
        project = observables.pop();
    }
    // if the first and only other argument besides the resultSelector is an array
    // assume it's been called with 'combineLatest([obs1, obs2, obs3], project)'
    if (observables.length === 1 && isArray_1.isArray(observables[0])) {
        observables = observables[0];
    }
    return new ArrayObservable_1.ArrayObservable(observables, scheduler).lift(new combineLatest_1.CombineLatestOperator(project));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.concat"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>concat ()](#apidoc.element.rxjs.Observable.concat)
- description and source-code
```javascript
function concatStatic() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var scheduler = null;
    var args = observables;
    if (isScheduler_1.isScheduler(args[observables.length - 1])) {
        scheduler = args.pop();
    }
    if (scheduler === null && observables.length === 1 && observables[0] instanceof Observable_1.Observable) {
        return observables[0];
    }
    return new ArrayObservable_1.ArrayObservable(observables, scheduler).lift(new mergeAll_1.MergeAllOperator(1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.create"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>create (subscribe)](#apidoc.element.rxjs.Observable.create)
- description and source-code
```javascript
create = function (subscribe) {
    return new Observable(subscribe);
}
```
- example usage
```shell
...



"use strict";
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var Subject_1 = require('./Subject');
var Subscription_1 = require('./Subscription');
/**
 * @class AsyncSubject<T>
 */
var AsyncSubject = (function (_super) {
...
```

#### <a name="apidoc.element.rxjs.Observable.defer"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>defer (observableFactory)](#apidoc.element.rxjs.Observable.defer)
- description and source-code
```javascript
defer = function (observableFactory) {
    return new DeferObservable(observableFactory);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.empty"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>empty (scheduler)](#apidoc.element.rxjs.Observable.empty)
- description and source-code
```javascript
empty = function (scheduler) {
    return new EmptyObservable(scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.forkJoin"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>forkJoin ()](#apidoc.element.rxjs.Observable.forkJoin)
- description and source-code
```javascript
forkJoin = function () {
    var sources = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        sources[_i - 0] = arguments[_i];
    }
    if (sources === null || arguments.length === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    var resultSelector = null;
    if (typeof sources[sources.length - 1] === 'function') {
        resultSelector = sources.pop();
    }
    // if the first and only other argument besides the resultSelector is an array
    // assume it's been called with 'forkJoin([obs1, obs2, obs3], resultSelector)'
    if (sources.length === 1 && isArray_1.isArray(sources[0])) {
        sources = sources[0];
    }
    if (sources.length === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    return new ForkJoinObservable(sources, resultSelector);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.from"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>from (ish, scheduler)](#apidoc.element.rxjs.Observable.from)
- description and source-code
```javascript
from = function (ish, scheduler) {
    if (ish != null) {
        if (typeof ish[observable_1.observable] === 'function') {
            if (ish instanceof Observable_1.Observable && !scheduler) {
                return ish;
            }
            return new FromObservable(ish, scheduler);
        }
        else if (isArray_1.isArray(ish)) {
            return new ArrayObservable_1.ArrayObservable(ish, scheduler);
        }
        else if (isPromise_1.isPromise(ish)) {
            return new PromiseObservable_1.PromiseObservable(ish, scheduler);
        }
        else if (typeof ish[iterator_1.iterator] === 'function' || typeof ish === 'string') {
            return new IteratorObservable_1.IteratorObservable(ish, scheduler);
        }
        else if (isArrayLike_1.isArrayLike(ish)) {
            return new ArrayLikeObservable_1.ArrayLikeObservable(ish, scheduler);
        }
    }
    throw new TypeError((ish !== null && typeof ish || ish) + ' is not observable');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.fromEvent"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>fromEvent (target, eventName, options, selector)](#apidoc.element.rxjs.Observable.fromEvent)
- description and source-code
```javascript
fromEvent = function (target, eventName, options, selector) {
    if (isFunction_1.isFunction(options)) {
        selector = options;
        options = undefined;
    }
    return new FromEventObservable(target, eventName, selector, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.fromEventPattern"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>fromEventPattern (addHandler, removeHandler, selector)](#apidoc.element.rxjs.Observable.fromEventPattern)
- description and source-code
```javascript
fromEventPattern = function (addHandler, removeHandler, selector) {
    return new FromEventPatternObservable(addHandler, removeHandler, selector);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.fromPromise"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>fromPromise (promise, scheduler)](#apidoc.element.rxjs.Observable.fromPromise)
- description and source-code
```javascript
fromPromise = function (promise, scheduler) {
    return new PromiseObservable(promise, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.generate"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>generate (initialStateOrOptions, condition, iterate, resultSelectorOrObservable, scheduler)](#apidoc.element.rxjs.Observable.generate)
- description and source-code
```javascript
generate = function (initialStateOrOptions, condition, iterate, resultSelectorOrObservable, scheduler) {
    if (arguments.length == 1) {
        return new GenerateObservable(initialStateOrOptions.initialState, initialStateOrOptions.condition, initialStateOrOptions
.iterate, initialStateOrOptions.resultSelector || selfSelector, initialStateOrOptions.scheduler);
    }
    if (resultSelectorOrObservable === undefined || isScheduler_1.isScheduler(resultSelectorOrObservable)) {
        return new GenerateObservable(initialStateOrOptions, condition, iterate, selfSelector, resultSelectorOrObservable);
    }
    return new GenerateObservable(initialStateOrOptions, condition, iterate, resultSelectorOrObservable, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.if"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>if (condition, thenSource, elseSource)](#apidoc.element.rxjs.Observable.if)
- description and source-code
```javascript
if = function (condition, thenSource, elseSource) {
    return new IfObservable(condition, thenSource, elseSource);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.interval"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>interval (period, scheduler)](#apidoc.element.rxjs.Observable.interval)
- description and source-code
```javascript
interval = function (period, scheduler) {
    if (period === void 0) { period = 0; }
    if (scheduler === void 0) { scheduler = async_1.async; }
    return new IntervalObservable(period, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.merge"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>merge ()](#apidoc.element.rxjs.Observable.merge)
- description and source-code
```javascript
function mergeStatic() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var concurrent = Number.POSITIVE_INFINITY;
    var scheduler = null;
    var last = observables[observables.length - 1];
    if (isScheduler_1.isScheduler(last)) {
        scheduler = observables.pop();
        if (observables.length > 1 && typeof observables[observables.length - 1] === 'number') {
            concurrent = observables.pop();
        }
    }
    else if (typeof last === 'number') {
        concurrent = observables.pop();
    }
    if (scheduler === null && observables.length === 1 && observables[0] instanceof Observable_1.Observable) {
        return observables[0];
    }
    return new ArrayObservable_1.ArrayObservable(observables, scheduler).lift(new mergeAll_1.MergeAllOperator(concurrent));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.never"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>never ()](#apidoc.element.rxjs.Observable.never)
- description and source-code
```javascript
never = function () {
    return new NeverObservable();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.of"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>of ()](#apidoc.element.rxjs.Observable.of)
- description and source-code
```javascript
of = function () {
    var array = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        array[_i - 0] = arguments[_i];
    }
    var scheduler = array[array.length - 1];
    if (isScheduler_1.isScheduler(scheduler)) {
        array.pop();
    }
    else {
        scheduler = null;
    }
    var len = array.length;
    if (len > 1) {
        return new ArrayObservable(array, scheduler);
    }
    else if (len === 1) {
        return new ScalarObservable_1.ScalarObservable(array[0], scheduler);
    }
    else {
        return new EmptyObservable_1.EmptyObservable(scheduler);
    }
}
```
- example usage
```shell
...
'''

To import the entire core set of functionality:

'''js
import Rx from 'rxjs/Rx';

Rx.Observable.of(1,2,3)
'''

To import only what you need by patching (this is useful for size-sensitive bundling):

'''js
import { Observable } from 'rxjs/Observable';
import 'rxjs/add/observable/of';
...
```

#### <a name="apidoc.element.rxjs.Observable.onErrorResumeNext"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>onErrorResumeNext ()](#apidoc.element.rxjs.Observable.onErrorResumeNext)
- description and source-code
```javascript
function onErrorResumeNextStatic() {
    var nextSources = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        nextSources[_i - 0] = arguments[_i];
    }
    var source = null;
    if (nextSources.length === 1 && isArray_1.isArray(nextSources[0])) {
        nextSources = nextSources[0];
    }
    source = nextSources.shift();
    return new FromObservable_1.FromObservable(source, null).lift(new OnErrorResumeNextOperator(nextSources));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.pairs"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>pairs (obj, scheduler)](#apidoc.element.rxjs.Observable.pairs)
- description and source-code
```javascript
pairs = function (obj, scheduler) {
    return new PairsObservable(obj, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.race"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>race ()](#apidoc.element.rxjs.Observable.race)
- description and source-code
```javascript
function raceStatic() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    // if the only argument is an array, it was most likely called with
    // 'pair([obs1, obs2, ...])'
    if (observables.length === 1) {
        if (isArray_1.isArray(observables[0])) {
            observables = observables[0];
        }
        else {
            return observables[0];
        }
    }
    return new ArrayObservable_1.ArrayObservable(observables).lift(new RaceOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.range"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>range (start, count, scheduler)](#apidoc.element.rxjs.Observable.range)
- description and source-code
```javascript
range = function (start, count, scheduler) {
    if (start === void 0) { start = 0; }
    if (count === void 0) { count = 0; }
    return new RangeObservable(start, count, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.throw"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>throw (error, scheduler)](#apidoc.element.rxjs.Observable.throw)
- description and source-code
```javascript
throw = function (error, scheduler) {
    return new ErrorObservable(error, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.timer"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>timer (initialDelay, period, scheduler)](#apidoc.element.rxjs.Observable.timer)
- description and source-code
```javascript
timer = function (initialDelay, period, scheduler) {
    if (initialDelay === void 0) { initialDelay = 0; }
    return new TimerObservable(initialDelay, period, scheduler);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.using"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>using (resourceFactory, observableFactory)](#apidoc.element.rxjs.Observable.using)
- description and source-code
```javascript
using = function (resourceFactory, observableFactory) {
    return new UsingObservable(resourceFactory, observableFactory);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.webSocket"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>webSocket (urlConfigOrSource)](#apidoc.element.rxjs.Observable.webSocket)
- description and source-code
```javascript
webSocket = function (urlConfigOrSource) {
    return new WebSocketSubject(urlConfigOrSource);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.zip"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.</span>zip ()](#apidoc.element.rxjs.Observable.zip)
- description and source-code
```javascript
function zipStatic() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var project = observables[observables.length - 1];
    if (typeof project === 'function') {
        observables.pop();
    }
    return new ArrayObservable_1.ArrayObservable(observables).lift(new ZipOperator(project));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Observable.prototype"></a>[module rxjs.Observable.prototype](#apidoc.module.rxjs.Observable.prototype)

#### <a name="apidoc.element.rxjs.Observable.prototype._catch"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_catch (selector)](#apidoc.element.rxjs.Observable.prototype._catch)
- description and source-code
```javascript
function _catch(selector) {
    var operator = new CatchOperator(selector);
    var caught = this.lift(operator);
    return (operator.caught = caught);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype._do"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_do (nextOrObserver, error, complete)](#apidoc.element.rxjs.Observable.prototype._do)
- description and source-code
```javascript
function _do(nextOrObserver, error, complete) {
    return this.lift(new DoOperator(nextOrObserver, error, complete));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype._finally"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_finally (callback)](#apidoc.element.rxjs.Observable.prototype._finally)
- description and source-code
```javascript
function _finally(callback) {
    return this.lift(new FinallyOperator(callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype._subscribe"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.Observable.prototype._subscribe)
- description and source-code
```javascript
_subscribe = function (subscriber) {
    return this.source.subscribe(subscriber);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype._switch"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_switch ()](#apidoc.element.rxjs.Observable.prototype._switch)
- description and source-code
```javascript
function _switch() {
    return this.lift(new SwitchOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype._trySubscribe"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>_trySubscribe (sink)](#apidoc.element.rxjs.Observable.prototype._trySubscribe)
- description and source-code
```javascript
_trySubscribe = function (sink) {
    try {
        return this._subscribe(sink);
    }
    catch (err) {
        sink.syncErrorThrown = true;
        sink.syncErrorValue = err;
        sink.error(err);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.audit"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>audit (durationSelector)](#apidoc.element.rxjs.Observable.prototype.audit)
- description and source-code
```javascript
function audit(durationSelector) {
    return this.lift(new AuditOperator(durationSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.auditTime"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>auditTime (duration, scheduler)](#apidoc.element.rxjs.Observable.prototype.auditTime)
- description and source-code
```javascript
function auditTime(duration, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new AuditTimeOperator(duration, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.buffer"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>buffer (closingNotifier)](#apidoc.element.rxjs.Observable.prototype.buffer)
- description and source-code
```javascript
function buffer(closingNotifier) {
    return this.lift(new BufferOperator(closingNotifier));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.bufferCount"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>bufferCount (bufferSize, startBufferEvery)](#apidoc.element.rxjs.Observable.prototype.bufferCount)
- description and source-code
```javascript
function bufferCount(bufferSize, startBufferEvery) {
    if (startBufferEvery === void 0) { startBufferEvery = null; }
    return this.lift(new BufferCountOperator(bufferSize, startBufferEvery));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.bufferTime"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>bufferTime (bufferTimeSpan)](#apidoc.element.rxjs.Observable.prototype.bufferTime)
- description and source-code
```javascript
function bufferTime(bufferTimeSpan) {
    var length = arguments.length;
    var scheduler = async_1.async;
    if (isScheduler_1.isScheduler(arguments[arguments.length - 1])) {
        scheduler = arguments[arguments.length - 1];
        length--;
    }
    var bufferCreationInterval = null;
    if (length >= 2) {
        bufferCreationInterval = arguments[1];
    }
    var maxBufferSize = Number.POSITIVE_INFINITY;
    if (length >= 3) {
        maxBufferSize = arguments[2];
    }
    return this.lift(new BufferTimeOperator(bufferTimeSpan, bufferCreationInterval, maxBufferSize, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.bufferToggle"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>bufferToggle (openings, closingSelector)](#apidoc.element.rxjs.Observable.prototype.bufferToggle)
- description and source-code
```javascript
function bufferToggle(openings, closingSelector) {
    return this.lift(new BufferToggleOperator(openings, closingSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.bufferWhen"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>bufferWhen (closingSelector)](#apidoc.element.rxjs.Observable.prototype.bufferWhen)
- description and source-code
```javascript
function bufferWhen(closingSelector) {
    return this.lift(new BufferWhenOperator(closingSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.catch"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>catch (selector)](#apidoc.element.rxjs.Observable.prototype.catch)
- description and source-code
```javascript
function _catch(selector) {
    var operator = new CatchOperator(selector);
    var caught = this.lift(operator);
    return (operator.caught = caught);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.combineAll"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>combineAll (project)](#apidoc.element.rxjs.Observable.prototype.combineAll)
- description and source-code
```javascript
function combineAll(project) {
    return this.lift(new combineLatest_1.CombineLatestOperator(project));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.combineLatest"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>combineLatest ()](#apidoc.element.rxjs.Observable.prototype.combineLatest)
- description and source-code
```javascript
function combineLatest() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    var project = null;
    if (typeof observables[observables.length - 1] === 'function') {
        project = observables.pop();
    }
    // if the first and only other argument besides the resultSelector is an array
    // assume it's been called with 'combineLatest([obs1, obs2, obs3], project)'
    if (observables.length === 1 && isArray_1.isArray(observables[0])) {
        observables = observables[0].slice();
    }
    observables.unshift(this);
    return this.lift.call(new ArrayObservable_1.ArrayObservable(observables), new CombineLatestOperator(project));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.concat"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>concat ()](#apidoc.element.rxjs.Observable.prototype.concat)
- description and source-code
```javascript
function concat() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    return this.lift.call(concatStatic.apply(void 0, [this].concat(observables)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.concatAll"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>concatAll ()](#apidoc.element.rxjs.Observable.prototype.concatAll)
- description and source-code
```javascript
function concatAll() {
    return this.lift(new mergeAll_1.MergeAllOperator(1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.concatMap"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>concatMap (project, resultSelector)](#apidoc.element.rxjs.Observable.prototype.concatMap)
- description and source-code
```javascript
function concatMap(project, resultSelector) {
    return this.lift(new mergeMap_1.MergeMapOperator(project, resultSelector, 1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.concatMapTo"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>concatMapTo (innerObservable, resultSelector)](#apidoc.element.rxjs.Observable.prototype.concatMapTo)
- description and source-code
```javascript
function concatMapTo(innerObservable, resultSelector) {
    return this.lift(new mergeMapTo_1.MergeMapToOperator(innerObservable, resultSelector, 1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.count"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>count (predicate)](#apidoc.element.rxjs.Observable.prototype.count)
- description and source-code
```javascript
function count(predicate) {
    return this.lift(new CountOperator(predicate, this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.debounce"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>debounce (durationSelector)](#apidoc.element.rxjs.Observable.prototype.debounce)
- description and source-code
```javascript
function debounce(durationSelector) {
    return this.lift(new DebounceOperator(durationSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.debounceTime"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>debounceTime (dueTime, scheduler)](#apidoc.element.rxjs.Observable.prototype.debounceTime)
- description and source-code
```javascript
function debounceTime(dueTime, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new DebounceTimeOperator(dueTime, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.defaultIfEmpty"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>defaultIfEmpty (defaultValue)](#apidoc.element.rxjs.Observable.prototype.defaultIfEmpty)
- description and source-code
```javascript
function defaultIfEmpty(defaultValue) {
    if (defaultValue === void 0) { defaultValue = null; }
    return this.lift(new DefaultIfEmptyOperator(defaultValue));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.delay"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>delay (delay, scheduler)](#apidoc.element.rxjs.Observable.prototype.delay)
- description and source-code
```javascript
function delay(delay, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    var absoluteDelay = isDate_1.isDate(delay);
    var delayFor = absoluteDelay ? (+delay - scheduler.now()) : Math.abs(delay);
    return this.lift(new DelayOperator(delayFor, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.delayWhen"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>delayWhen (delayDurationSelector, subscriptionDelay)](#apidoc.element.rxjs.Observable.prototype.delayWhen)
- description and source-code
```javascript
function delayWhen(delayDurationSelector, subscriptionDelay) {
    if (subscriptionDelay) {
        return new SubscriptionDelayObservable(this, subscriptionDelay)
            .lift(new DelayWhenOperator(delayDurationSelector));
    }
    return this.lift(new DelayWhenOperator(delayDurationSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.dematerialize"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>dematerialize ()](#apidoc.element.rxjs.Observable.prototype.dematerialize)
- description and source-code
```javascript
function dematerialize() {
    return this.lift(new DeMaterializeOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.distinct"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>distinct (keySelector, flushes)](#apidoc.element.rxjs.Observable.prototype.distinct)
- description and source-code
```javascript
function distinct(keySelector, flushes) {
    return this.lift(new DistinctOperator(keySelector, flushes));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.distinctUntilChanged"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>distinctUntilChanged (compare, keySelector)](#apidoc.element.rxjs.Observable.prototype.distinctUntilChanged)
- description and source-code
```javascript
function distinctUntilChanged(compare, keySelector) {
    return this.lift(new DistinctUntilChangedOperator(compare, keySelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.distinctUntilKeyChanged"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>distinctUntilKeyChanged (key, compare)](#apidoc.element.rxjs.Observable.prototype.distinctUntilKeyChanged)
- description and source-code
```javascript
function distinctUntilKeyChanged(key, compare) {
    return distinctUntilChanged_1.distinctUntilChanged.call(this, function (x, y) {
        if (compare) {
            return compare(x[key], y[key]);
        }
        return x[key] === y[key];
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.do"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>do (nextOrObserver, error, complete)](#apidoc.element.rxjs.Observable.prototype.do)
- description and source-code
```javascript
function _do(nextOrObserver, error, complete) {
    return this.lift(new DoOperator(nextOrObserver, error, complete));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.elementAt"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>elementAt (index, defaultValue)](#apidoc.element.rxjs.Observable.prototype.elementAt)
- description and source-code
```javascript
function elementAt(index, defaultValue) {
    return this.lift(new ElementAtOperator(index, defaultValue));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.every"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>every (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.every)
- description and source-code
```javascript
function every(predicate, thisArg) {
    return this.lift(new EveryOperator(predicate, thisArg, this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.exhaust"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>exhaust ()](#apidoc.element.rxjs.Observable.prototype.exhaust)
- description and source-code
```javascript
function exhaust() {
    return this.lift(new SwitchFirstOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.exhaustMap"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>exhaustMap (project, resultSelector)](#apidoc.element.rxjs.Observable.prototype.exhaustMap)
- description and source-code
```javascript
function exhaustMap(project, resultSelector) {
    return this.lift(new SwitchFirstMapOperator(project, resultSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.expand"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>expand (project, concurrent, scheduler)](#apidoc.element.rxjs.Observable.prototype.expand)
- description and source-code
```javascript
function expand(project, concurrent, scheduler) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    if (scheduler === void 0) { scheduler = undefined; }
    concurrent = (concurrent || 0) < 1 ? Number.POSITIVE_INFINITY : concurrent;
    return this.lift(new ExpandOperator(project, concurrent, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.filter"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>filter (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.filter)
- description and source-code
```javascript
function filter(predicate, thisArg) {
    return this.lift(new FilterOperator(predicate, thisArg));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.finally"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>finally (callback)](#apidoc.element.rxjs.Observable.prototype.finally)
- description and source-code
```javascript
function _finally(callback) {
    return this.lift(new FinallyOperator(callback));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.find"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>find (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.find)
- description and source-code
```javascript
function find(predicate, thisArg) {
    if (typeof predicate !== 'function') {
        throw new TypeError('predicate is not a function');
    }
    return this.lift(new FindValueOperator(predicate, this, false, thisArg));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.findIndex"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>findIndex (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.findIndex)
- description and source-code
```javascript
function findIndex(predicate, thisArg) {
    return this.lift(new find_1.FindValueOperator(predicate, this, true, thisArg));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.first"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>first (predicate, resultSelector, defaultValue)](#apidoc.element.rxjs.Observable.prototype.first)
- description and source-code
```javascript
function first(predicate, resultSelector, defaultValue) {
    return this.lift(new FirstOperator(predicate, resultSelector, defaultValue, this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.flatMap"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>flatMap (project, resultSelector, concurrent)](#apidoc.element.rxjs.Observable.prototype.flatMap)
- description and source-code
```javascript
function mergeMap(project, resultSelector, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    if (typeof resultSelector === 'number') {
        concurrent = resultSelector;
        resultSelector = null;
    }
    return this.lift(new MergeMapOperator(project, resultSelector, concurrent));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.flatMapTo"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>flatMapTo (innerObservable, resultSelector, concurrent)](#apidoc.element.rxjs.Observable.prototype.flatMapTo)
- description and source-code
```javascript
function mergeMapTo(innerObservable, resultSelector, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    if (typeof resultSelector === 'number') {
        concurrent = resultSelector;
        resultSelector = null;
    }
    return this.lift(new MergeMapToOperator(innerObservable, resultSelector, concurrent));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.forEach"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>forEach (next, PromiseCtor)](#apidoc.element.rxjs.Observable.prototype.forEach)
- description and source-code
```javascript
forEach = function (next, PromiseCtor) {
    var _this = this;
    if (!PromiseCtor) {
        if (root_1.root.Rx && root_1.root.Rx.config && root_1.root.Rx.config.Promise) {
            PromiseCtor = root_1.root.Rx.config.Promise;
        }
        else if (root_1.root.Promise) {
            PromiseCtor = root_1.root.Promise;
        }
    }
    if (!PromiseCtor) {
        throw new Error('no Promise impl found');
    }
    return new PromiseCtor(function (resolve, reject) {
        // Must be declared in a separate statement to avoid a RefernceError when
        // accessing subscription below in the closure due to Temporal Dead Zone.
        var subscription;
        subscription = _this.subscribe(function (value) {
            if (subscription) {
                // if there is a subscription, then we can surmise
                // the next handling is asynchronous. Any errors thrown
                // need to be rejected explicitly and unsubscribe must be
                // called manually
                try {
                    next(value);
                }
                catch (err) {
                    reject(err);
                    subscription.unsubscribe();
                }
            }
            else {
                // if there is NO subscription, then we're getting a nexted
                // value synchronously during subscription. We can just call it.
                // If it errors, Observable's 'subscribe' will ensure the
                // unsubscription logic is called, then synchronously rethrow the error.
                // After that, Promise will trap the error and send it
                // down the rejection path.
                next(value);
            }
        }, reject, resolve);
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.groupBy"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>groupBy (keySelector, elementSelector, durationSelector, subjectSelector)](#apidoc.element.rxjs.Observable.prototype.groupBy)
- description and source-code
```javascript
function groupBy(keySelector, elementSelector, durationSelector, subjectSelector) {
    return this.lift(new GroupByOperator(keySelector, elementSelector, durationSelector, subjectSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.ignoreElements"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>ignoreElements ()](#apidoc.element.rxjs.Observable.prototype.ignoreElements)
- description and source-code
```javascript
function ignoreElements() {
    return this.lift(new IgnoreElementsOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>isEmpty ()](#apidoc.element.rxjs.Observable.prototype.isEmpty)
- description and source-code
```javascript
function isEmpty() {
    return this.lift(new IsEmptyOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.last"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>last (predicate, resultSelector, defaultValue)](#apidoc.element.rxjs.Observable.prototype.last)
- description and source-code
```javascript
function last(predicate, resultSelector, defaultValue) {
    return this.lift(new LastOperator(predicate, resultSelector, defaultValue, this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.let"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>let (func)](#apidoc.element.rxjs.Observable.prototype.let)
- description and source-code
```javascript
function letProto(func) {
    return func(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.letBind"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>letBind (func)](#apidoc.element.rxjs.Observable.prototype.letBind)
- description and source-code
```javascript
function letProto(func) {
    return func(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.lift"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>lift (operator)](#apidoc.element.rxjs.Observable.prototype.lift)
- description and source-code
```javascript
lift = function (operator) {
    var observable = new Observable();
    observable.source = this;
    observable.operator = operator;
    return observable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.map"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>map (project, thisArg)](#apidoc.element.rxjs.Observable.prototype.map)
- description and source-code
```javascript
function map(project, thisArg) {
    if (typeof project !== 'function') {
        throw new TypeError('argument is not a function. Are you looking for 'mapTo()'?');
    }
    return this.lift(new MapOperator(project, thisArg));
}
```
- example usage
```shell
...
To import only what you need by patching (this is useful for size-sensitive bundling):

'''js
import { Observable } from 'rxjs/Observable';
import 'rxjs/add/observable/of';
import 'rxjs/add/operator/map';

Observable.of(1,2,3).map(x => x + '!!!'); // etc
'''

To import what you need and use it with proposed [bind operator](https://github.com/tc39/proposal-bind-operator):

> Note: This additional syntax requires [transpiler support](http://babeljs.io/docs/plugins/transform-function-bind/) and this syntax
 may be completely withdrawn from TC39 without notice! Use at your own risk.

'''js
...
```

#### <a name="apidoc.element.rxjs.Observable.prototype.mapTo"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mapTo (value)](#apidoc.element.rxjs.Observable.prototype.mapTo)
- description and source-code
```javascript
function mapTo(value) {
    return this.lift(new MapToOperator(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.materialize"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>materialize ()](#apidoc.element.rxjs.Observable.prototype.materialize)
- description and source-code
```javascript
function materialize() {
    return this.lift(new MaterializeOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.max"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>max (comparer)](#apidoc.element.rxjs.Observable.prototype.max)
- description and source-code
```javascript
function max(comparer) {
    var max = (typeof comparer === 'function')
        ? function (x, y) { return comparer(x, y) > 0 ? x : y; }
        : function (x, y) { return x > y ? x : y; };
    return this.lift(new reduce_1.ReduceOperator(max));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.merge"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>merge ()](#apidoc.element.rxjs.Observable.prototype.merge)
- description and source-code
```javascript
function merge() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    return this.lift.call(mergeStatic.apply(void 0, [this].concat(observables)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.mergeAll"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mergeAll (concurrent)](#apidoc.element.rxjs.Observable.prototype.mergeAll)
- description and source-code
```javascript
function mergeAll(concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    return this.lift(new MergeAllOperator(concurrent));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.mergeMap"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mergeMap (project, resultSelector, concurrent)](#apidoc.element.rxjs.Observable.prototype.mergeMap)
- description and source-code
```javascript
function mergeMap(project, resultSelector, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    if (typeof resultSelector === 'number') {
        concurrent = resultSelector;
        resultSelector = null;
    }
    return this.lift(new MergeMapOperator(project, resultSelector, concurrent));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.mergeMapTo"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mergeMapTo (innerObservable, resultSelector, concurrent)](#apidoc.element.rxjs.Observable.prototype.mergeMapTo)
- description and source-code
```javascript
function mergeMapTo(innerObservable, resultSelector, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    if (typeof resultSelector === 'number') {
        concurrent = resultSelector;
        resultSelector = null;
    }
    return this.lift(new MergeMapToOperator(innerObservable, resultSelector, concurrent));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.mergeScan"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>mergeScan (accumulator, seed, concurrent)](#apidoc.element.rxjs.Observable.prototype.mergeScan)
- description and source-code
```javascript
function mergeScan(accumulator, seed, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    return this.lift(new MergeScanOperator(accumulator, seed, concurrent));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.min"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>min (comparer)](#apidoc.element.rxjs.Observable.prototype.min)
- description and source-code
```javascript
function min(comparer) {
    var min = (typeof comparer === 'function')
        ? function (x, y) { return comparer(x, y) < 0 ? x : y; }
        : function (x, y) { return x < y ? x : y; };
    return this.lift(new reduce_1.ReduceOperator(min));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.multicast"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>multicast (subjectOrSubjectFactory, selector)](#apidoc.element.rxjs.Observable.prototype.multicast)
- description and source-code
```javascript
function multicast(subjectOrSubjectFactory, selector) {
    var subjectFactory;
    if (typeof subjectOrSubjectFactory === 'function') {
        subjectFactory = subjectOrSubjectFactory;
    }
    else {
        subjectFactory = function subjectFactory() {
            return subjectOrSubjectFactory;
        };
    }
    if (typeof selector === 'function') {
        return this.lift(new MulticastOperator(subjectFactory, selector));
    }
    var connectable = Object.create(this, ConnectableObservable_1.connectableObservableDescriptor);
    connectable.source = this;
    connectable.subjectFactory = subjectFactory;
    return connectable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.observeOn"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>observeOn (scheduler, delay)](#apidoc.element.rxjs.Observable.prototype.observeOn)
- description and source-code
```javascript
function observeOn(scheduler, delay) {
    if (delay === void 0) { delay = 0; }
    return this.lift(new ObserveOnOperator(scheduler, delay));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.onErrorResumeNext"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>onErrorResumeNext ()](#apidoc.element.rxjs.Observable.prototype.onErrorResumeNext)
- description and source-code
```javascript
function onErrorResumeNext() {
    var nextSources = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        nextSources[_i - 0] = arguments[_i];
    }
    if (nextSources.length === 1 && isArray_1.isArray(nextSources[0])) {
        nextSources = nextSources[0];
    }
    return this.lift(new OnErrorResumeNextOperator(nextSources));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.pairwise"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>pairwise ()](#apidoc.element.rxjs.Observable.prototype.pairwise)
- description and source-code
```javascript
function pairwise() {
    return this.lift(new PairwiseOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.partition"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>partition (predicate, thisArg)](#apidoc.element.rxjs.Observable.prototype.partition)
- description and source-code
```javascript
function partition(predicate, thisArg) {
    return [
        filter_1.filter.call(this, predicate, thisArg),
        filter_1.filter.call(this, not_1.not(predicate, thisArg))
    ];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.pluck"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>pluck ()](#apidoc.element.rxjs.Observable.prototype.pluck)
- description and source-code
```javascript
function pluck() {
    var properties = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        properties[_i - 0] = arguments[_i];
    }
    var length = properties.length;
    if (length === 0) {
        throw new Error('list of properties cannot be empty.');
    }
    return map_1.map.call(this, plucker(properties, length));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.publish"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>publish (selector)](#apidoc.element.rxjs.Observable.prototype.publish)
- description and source-code
```javascript
function publish(selector) {
    return selector ? multicast_1.multicast.call(this, function () { return new Subject_1.Subject(); }, selector) :
        multicast_1.multicast.call(this, new Subject_1.Subject());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.publishBehavior"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>publishBehavior (value)](#apidoc.element.rxjs.Observable.prototype.publishBehavior)
- description and source-code
```javascript
function publishBehavior(value) {
    return multicast_1.multicast.call(this, new BehaviorSubject_1.BehaviorSubject(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.publishLast"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>publishLast ()](#apidoc.element.rxjs.Observable.prototype.publishLast)
- description and source-code
```javascript
function publishLast() {
    return multicast_1.multicast.call(this, new AsyncSubject_1.AsyncSubject());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.publishReplay"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>publishReplay (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.Observable.prototype.publishReplay)
- description and source-code
```javascript
function publishReplay(bufferSize, windowTime, scheduler) {
    if (bufferSize === void 0) { bufferSize = Number.POSITIVE_INFINITY; }
    if (windowTime === void 0) { windowTime = Number.POSITIVE_INFINITY; }
    return multicast_1.multicast.call(this, new ReplaySubject_1.ReplaySubject(bufferSize, windowTime, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.race"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>race ()](#apidoc.element.rxjs.Observable.prototype.race)
- description and source-code
```javascript
function race() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    // if the only argument is an array, it was most likely called with
    // 'pair([obs1, obs2, ...])'
    if (observables.length === 1 && isArray_1.isArray(observables[0])) {
        observables = observables[0];
    }
    return this.lift.call(raceStatic.apply(void 0, [this].concat(observables)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.reduce"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>reduce (accumulator, seed)](#apidoc.element.rxjs.Observable.prototype.reduce)
- description and source-code
```javascript
function reduce(accumulator, seed) {
    var hasSeed = false;
    // providing a seed of 'undefined' *should* be valid and trigger
    // hasSeed! so don't use 'seed !== undefined' checks!
    // For this reason, we have to check it here at the original call site
    // otherwise inside Operator/Subscriber we won't know if 'undefined'
    // means they didn't provide anything or if they literally provided 'undefined'
    if (arguments.length >= 2) {
        hasSeed = true;
    }
    return this.lift(new ReduceOperator(accumulator, seed, hasSeed));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.repeat"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>repeat (count)](#apidoc.element.rxjs.Observable.prototype.repeat)
- description and source-code
```javascript
function repeat(count) {
    if (count === void 0) { count = -1; }
    if (count === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    else if (count < 0) {
        return this.lift(new RepeatOperator(-1, this));
    }
    else {
        return this.lift(new RepeatOperator(count - 1, this));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.repeatWhen"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>repeatWhen (notifier)](#apidoc.element.rxjs.Observable.prototype.repeatWhen)
- description and source-code
```javascript
function repeatWhen(notifier) {
    return this.lift(new RepeatWhenOperator(notifier));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.retry"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>retry (count)](#apidoc.element.rxjs.Observable.prototype.retry)
- description and source-code
```javascript
function retry(count) {
    if (count === void 0) { count = -1; }
    return this.lift(new RetryOperator(count, this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.retryWhen"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>retryWhen (notifier)](#apidoc.element.rxjs.Observable.prototype.retryWhen)
- description and source-code
```javascript
function retryWhen(notifier) {
    return this.lift(new RetryWhenOperator(notifier, this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.sample"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>sample (notifier)](#apidoc.element.rxjs.Observable.prototype.sample)
- description and source-code
```javascript
function sample(notifier) {
    return this.lift(new SampleOperator(notifier));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.sampleTime"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>sampleTime (period, scheduler)](#apidoc.element.rxjs.Observable.prototype.sampleTime)
- description and source-code
```javascript
function sampleTime(period, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new SampleTimeOperator(period, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.scan"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>scan (accumulator, seed)](#apidoc.element.rxjs.Observable.prototype.scan)
- description and source-code
```javascript
function scan(accumulator, seed) {
    var hasSeed = false;
    // providing a seed of 'undefined' *should* be valid and trigger
    // hasSeed! so don't use 'seed !== undefined' checks!
    // For this reason, we have to check it here at the original call site
    // otherwise inside Operator/Subscriber we won't know if 'undefined'
    // means they didn't provide anything or if they literally provided 'undefined'
    if (arguments.length >= 2) {
        hasSeed = true;
    }
    return this.lift(new ScanOperator(accumulator, seed, hasSeed));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.sequenceEqual"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>sequenceEqual (compareTo, comparor)](#apidoc.element.rxjs.Observable.prototype.sequenceEqual)
- description and source-code
```javascript
function sequenceEqual(compareTo, comparor) {
    return this.lift(new SequenceEqualOperator(compareTo, comparor));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.share"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>share ()](#apidoc.element.rxjs.Observable.prototype.share)
- description and source-code
```javascript
function share() {
    return multicast_1.multicast.call(this, shareSubjectFactory).refCount();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.single"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>single (predicate)](#apidoc.element.rxjs.Observable.prototype.single)
- description and source-code
```javascript
function single(predicate) {
    return this.lift(new SingleOperator(predicate, this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.skip"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>skip (count)](#apidoc.element.rxjs.Observable.prototype.skip)
- description and source-code
```javascript
function skip(count) {
    return this.lift(new SkipOperator(count));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.skipUntil"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>skipUntil (notifier)](#apidoc.element.rxjs.Observable.prototype.skipUntil)
- description and source-code
```javascript
function skipUntil(notifier) {
    return this.lift(new SkipUntilOperator(notifier));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.skipWhile"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>skipWhile (predicate)](#apidoc.element.rxjs.Observable.prototype.skipWhile)
- description and source-code
```javascript
function skipWhile(predicate) {
    return this.lift(new SkipWhileOperator(predicate));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.startWith"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>startWith ()](#apidoc.element.rxjs.Observable.prototype.startWith)
- description and source-code
```javascript
function startWith() {
    var array = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        array[_i - 0] = arguments[_i];
    }
    var scheduler = array[array.length - 1];
    if (isScheduler_1.isScheduler(scheduler)) {
        array.pop();
    }
    else {
        scheduler = null;
    }
    var len = array.length;
    if (len === 1) {
        return concat_1.concatStatic(new ScalarObservable_1.ScalarObservable(array[0], scheduler), this);
    }
    else if (len > 1) {
        return concat_1.concatStatic(new ArrayObservable_1.ArrayObservable(array, scheduler), this);
    }
    else {
        return concat_1.concatStatic(new EmptyObservable_1.EmptyObservable(scheduler), this);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.subscribe"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>subscribe (observerOrNext, error, complete)](#apidoc.element.rxjs.Observable.prototype.subscribe)
- description and source-code
```javascript
subscribe = function (observerOrNext, error, complete) {
    var operator = this.operator;
    var sink = toSubscriber_1.toSubscriber(observerOrNext, error, complete);
    if (operator) {
        operator.call(sink, this.source);
    }
    else {
        sink.add(this._trySubscribe(sink));
    }
    if (sink.syncErrorThrowable) {
        sink.syncErrorThrowable = false;
        if (sink.syncErrorThrown) {
            throw sink.syncErrorValue;
        }
    }
    return sink;
}
```
- example usage
```shell
...

#### Node.js Usage:

'''js
var Rx = require('@reactivex/rxjs');

Rx.Observable.of('hello world')
  .subscribe(function(x) { console.log(x); });
'''

## Goals

- Provide better performance than preceding versions of RxJS
- To model/follow the [Observable Spec Proposal](https://github.com/zenparsing/es-observable) to the observable.
- Provide more modular file structure in a variety of formats
...
```

#### <a name="apidoc.element.rxjs.Observable.prototype.subscribeOn"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>subscribeOn (scheduler, delay)](#apidoc.element.rxjs.Observable.prototype.subscribeOn)
- description and source-code
```javascript
function subscribeOn(scheduler, delay) {
    if (delay === void 0) { delay = 0; }
    return this.lift(new SubscribeOnOperator(scheduler, delay));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.switch"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>switch ()](#apidoc.element.rxjs.Observable.prototype.switch)
- description and source-code
```javascript
function _switch() {
    return this.lift(new SwitchOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.switchMap"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>switchMap (project, resultSelector)](#apidoc.element.rxjs.Observable.prototype.switchMap)
- description and source-code
```javascript
function switchMap(project, resultSelector) {
    return this.lift(new SwitchMapOperator(project, resultSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.switchMapTo"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>switchMapTo (innerObservable, resultSelector)](#apidoc.element.rxjs.Observable.prototype.switchMapTo)
- description and source-code
```javascript
function switchMapTo(innerObservable, resultSelector) {
    return this.lift(new SwitchMapToOperator(innerObservable, resultSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.take"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>take (count)](#apidoc.element.rxjs.Observable.prototype.take)
- description and source-code
```javascript
function take(count) {
    if (count === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    else {
        return this.lift(new TakeOperator(count));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.takeLast"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>takeLast (count)](#apidoc.element.rxjs.Observable.prototype.takeLast)
- description and source-code
```javascript
function takeLast(count) {
    if (count === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    else {
        return this.lift(new TakeLastOperator(count));
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.takeUntil"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>takeUntil (notifier)](#apidoc.element.rxjs.Observable.prototype.takeUntil)
- description and source-code
```javascript
function takeUntil(notifier) {
    return this.lift(new TakeUntilOperator(notifier));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.takeWhile"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>takeWhile (predicate)](#apidoc.element.rxjs.Observable.prototype.takeWhile)
- description and source-code
```javascript
function takeWhile(predicate) {
    return this.lift(new TakeWhileOperator(predicate));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.throttle"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>throttle (durationSelector)](#apidoc.element.rxjs.Observable.prototype.throttle)
- description and source-code
```javascript
function throttle(durationSelector) {
    return this.lift(new ThrottleOperator(durationSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.throttleTime"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>throttleTime (duration, scheduler)](#apidoc.element.rxjs.Observable.prototype.throttleTime)
- description and source-code
```javascript
function throttleTime(duration, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new ThrottleTimeOperator(duration, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.timeInterval"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>timeInterval (scheduler)](#apidoc.element.rxjs.Observable.prototype.timeInterval)
- description and source-code
```javascript
function timeInterval(scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new TimeIntervalOperator(scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.timeout"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>timeout (due, scheduler)](#apidoc.element.rxjs.Observable.prototype.timeout)
- description and source-code
```javascript
function timeout(due, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    var absoluteTimeout = isDate_1.isDate(due);
    var waitFor = absoluteTimeout ? (+due - scheduler.now()) : Math.abs(due);
    return this.lift(new TimeoutOperator(waitFor, absoluteTimeout, scheduler, new TimeoutError_1.TimeoutError()));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.timeoutWith"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>timeoutWith (due, withObservable, scheduler)](#apidoc.element.rxjs.Observable.prototype.timeoutWith)
- description and source-code
```javascript
function timeoutWith(due, withObservable, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    var absoluteTimeout = isDate_1.isDate(due);
    var waitFor = absoluteTimeout ? (+due - scheduler.now()) : Math.abs(due);
    return this.lift(new TimeoutWithOperator(waitFor, absoluteTimeout, withObservable, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.timestamp"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>timestamp (scheduler)](#apidoc.element.rxjs.Observable.prototype.timestamp)
- description and source-code
```javascript
function timestamp(scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new TimestampOperator(scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.toArray"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>toArray ()](#apidoc.element.rxjs.Observable.prototype.toArray)
- description and source-code
```javascript
function toArray() {
    return this.lift(new ToArrayOperator());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.toPromise"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>toPromise (PromiseCtor)](#apidoc.element.rxjs.Observable.prototype.toPromise)
- description and source-code
```javascript
function toPromise(PromiseCtor) {
    var _this = this;
    if (!PromiseCtor) {
        if (root_1.root.Rx && root_1.root.Rx.config && root_1.root.Rx.config.Promise) {
            PromiseCtor = root_1.root.Rx.config.Promise;
        }
        else if (root_1.root.Promise) {
            PromiseCtor = root_1.root.Promise;
        }
    }
    if (!PromiseCtor) {
        throw new Error('no Promise impl found');
    }
    return new PromiseCtor(function (resolve, reject) {
        var value;
        _this.subscribe(function (x) { return value = x; }, function (err) { return reject(err); }, function () { return resolve
(value); });
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.window"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>window (windowBoundaries)](#apidoc.element.rxjs.Observable.prototype.window)
- description and source-code
```javascript
function window(windowBoundaries) {
    return this.lift(new WindowOperator(windowBoundaries));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.windowCount"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>windowCount (windowSize, startWindowEvery)](#apidoc.element.rxjs.Observable.prototype.windowCount)
- description and source-code
```javascript
function windowCount(windowSize, startWindowEvery) {
    if (startWindowEvery === void 0) { startWindowEvery = 0; }
    return this.lift(new WindowCountOperator(windowSize, startWindowEvery));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.windowTime"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>windowTime (windowTimeSpan)](#apidoc.element.rxjs.Observable.prototype.windowTime)
- description and source-code
```javascript
function windowTime(windowTimeSpan) {
    var scheduler = async_1.async;
    var windowCreationInterval = null;
    var maxWindowSize = Number.POSITIVE_INFINITY;
    if (isScheduler_1.isScheduler(arguments[3])) {
        scheduler = arguments[3];
    }
    if (isScheduler_1.isScheduler(arguments[2])) {
        scheduler = arguments[2];
    }
    else if (isNumeric_1.isNumeric(arguments[2])) {
        maxWindowSize = arguments[2];
    }
    if (isScheduler_1.isScheduler(arguments[1])) {
        scheduler = arguments[1];
    }
    else if (isNumeric_1.isNumeric(arguments[1])) {
        windowCreationInterval = arguments[1];
    }
    return this.lift(new WindowTimeOperator(windowTimeSpan, windowCreationInterval, maxWindowSize, scheduler));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.windowToggle"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>windowToggle (openings, closingSelector)](#apidoc.element.rxjs.Observable.prototype.windowToggle)
- description and source-code
```javascript
function windowToggle(openings, closingSelector) {
    return this.lift(new WindowToggleOperator(openings, closingSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.windowWhen"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>windowWhen (closingSelector)](#apidoc.element.rxjs.Observable.prototype.windowWhen)
- description and source-code
```javascript
function windowWhen(closingSelector) {
    return this.lift(new WindowOperator(closingSelector));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.withLatestFrom"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>withLatestFrom ()](#apidoc.element.rxjs.Observable.prototype.withLatestFrom)
- description and source-code
```javascript
function withLatestFrom() {
    var args = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        args[_i - 0] = arguments[_i];
    }
    var project;
    if (typeof args[args.length - 1] === 'function') {
        project = args.pop();
    }
    var observables = args;
    return this.lift(new WithLatestFromOperator(observables, project));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.zip"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>zip ()](#apidoc.element.rxjs.Observable.prototype.zip)
- description and source-code
```javascript
function zipProto() {
    var observables = [];
    for (var _i = 0; _i < arguments.length; _i++) {
        observables[_i - 0] = arguments[_i];
    }
    return this.lift.call(zipStatic.apply(void 0, [this].concat(observables)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Observable.prototype.zipAll"></a>[function <span class="apidocSignatureSpan">rxjs.Observable.prototype.</span>zipAll (project)](#apidoc.element.rxjs.Observable.prototype.zipAll)
- description and source-code
```javascript
function zipAll(project) {
    return this.lift(new zip_1.ZipOperator(project));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.ReplaySubject"></a>[module rxjs.ReplaySubject](#apidoc.module.rxjs.ReplaySubject)

#### <a name="apidoc.element.rxjs.ReplaySubject.ReplaySubject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ReplaySubject (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.ReplaySubject.ReplaySubject)
- description and source-code
```javascript
function ReplaySubject(bufferSize, windowTime, scheduler) {
    if (bufferSize === void 0) { bufferSize = Number.POSITIVE_INFINITY; }
    if (windowTime === void 0) { windowTime = Number.POSITIVE_INFINITY; }
    _super.call(this);
    this.scheduler = scheduler;
    this._events = [];
    this._bufferSize = bufferSize < 1 ? 1 : bufferSize;
    this._windowTime = windowTime < 1 ? 1 : windowTime;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ReplaySubject.create"></a>[function <span class="apidocSignatureSpan">rxjs.ReplaySubject.</span>create (destination, source)](#apidoc.element.rxjs.ReplaySubject.create)
- description and source-code
```javascript
create = function (destination, source) {
    return new AnonymousSubject(destination, source);
}
```
- example usage
```shell
...



"use strict";
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var Subject_1 = require('./Subject');
var Subscription_1 = require('./Subscription');
/**
 * @class AsyncSubject<T>
 */
var AsyncSubject = (function (_super) {
...
```



# <a name="apidoc.module.rxjs.ReplaySubject.prototype"></a>[module rxjs.ReplaySubject.prototype](#apidoc.module.rxjs.ReplaySubject.prototype)

#### <a name="apidoc.element.rxjs.ReplaySubject.prototype._getNow"></a>[function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_getNow ()](#apidoc.element.rxjs.ReplaySubject.prototype._getNow)
- description and source-code
```javascript
_getNow = function () {
    return (this.scheduler || queue_1.queue).now();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ReplaySubject.prototype._subscribe"></a>[function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.ReplaySubject.prototype._subscribe)
- description and source-code
```javascript
_subscribe = function (subscriber) {
    var _events = this._trimBufferThenGetEvents();
    var scheduler = this.scheduler;
    var subscription;
    if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    else if (this.hasError) {
        subscription = Subscription_1.Subscription.EMPTY;
    }
    else if (this.isStopped) {
        subscription = Subscription_1.Subscription.EMPTY;
    }
    else {
        this.observers.push(subscriber);
        subscription = new SubjectSubscription_1.SubjectSubscription(this, subscriber);
    }
    if (scheduler) {
        subscriber.add(subscriber = new observeOn_1.ObserveOnSubscriber(subscriber, scheduler));
    }
    var len = _events.length;
    for (var i = 0; i < len && !subscriber.closed; i++) {
        subscriber.next(_events[i].value);
    }
    if (this.hasError) {
        subscriber.error(this.thrownError);
    }
    else if (this.isStopped) {
        subscriber.complete();
    }
    return subscription;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ReplaySubject.prototype._trimBufferThenGetEvents"></a>[function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_trimBufferThenGetEvents ()](#apidoc.element.rxjs.ReplaySubject.prototype._trimBufferThenGetEvents)
- description and source-code
```javascript
_trimBufferThenGetEvents = function () {
    var now = this._getNow();
    var _bufferSize = this._bufferSize;
    var _windowTime = this._windowTime;
    var _events = this._events;
    var eventsCount = _events.length;
    var spliceCount = 0;
    // Trim events that fall out of the time window.
    // Start at the front of the list. Break early once
    // we encounter an event that falls within the window.
    while (spliceCount < eventsCount) {
        if ((now - _events[spliceCount].time) < _windowTime) {
            break;
        }
        spliceCount++;
    }
    if (eventsCount > _bufferSize) {
        spliceCount = Math.max(spliceCount, eventsCount - _bufferSize);
    }
    if (spliceCount > 0) {
        _events.splice(0, spliceCount);
    }
    return _events;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ReplaySubject.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>constructor (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.ReplaySubject.prototype.constructor)
- description and source-code
```javascript
function ReplaySubject(bufferSize, windowTime, scheduler) {
    if (bufferSize === void 0) { bufferSize = Number.POSITIVE_INFINITY; }
    if (windowTime === void 0) { windowTime = Number.POSITIVE_INFINITY; }
    _super.call(this);
    this.scheduler = scheduler;
    this._events = [];
    this._bufferSize = bufferSize < 1 ? 1 : bufferSize;
    this._windowTime = windowTime < 1 ? 1 : windowTime;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.ReplaySubject.prototype.next"></a>[function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>next (value)](#apidoc.element.rxjs.ReplaySubject.prototype.next)
- description and source-code
```javascript
next = function (value) {
    var now = this._getNow();
    this._events.push(new ReplayEvent(now, value));
    this._trimBufferThenGetEvents();
    _super.prototype.next.call(this, value);
}
```
- example usage
```shell
...
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
...
```



# <a name="apidoc.module.rxjs.Subject"></a>[module rxjs.Subject](#apidoc.module.rxjs.Subject)

#### <a name="apidoc.element.rxjs.Subject.Subject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Subject ()](#apidoc.element.rxjs.Subject.Subject)
- description and source-code
```javascript
function Subject() {
    _super.call(this);
    this.observers = [];
    this.closed = false;
    this.isStopped = false;
    this.hasError = false;
    this.thrownError = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subject.create"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.</span>create (destination, source)](#apidoc.element.rxjs.Subject.create)
- description and source-code
```javascript
create = function (destination, source) {
    return new AnonymousSubject(destination, source);
}
```
- example usage
```shell
...



"use strict";
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var Subject_1 = require('./Subject');
var Subscription_1 = require('./Subscription');
/**
 * @class AsyncSubject<T>
 */
var AsyncSubject = (function (_super) {
...
```



# <a name="apidoc.module.rxjs.Subject.prototype"></a>[module rxjs.Subject.prototype](#apidoc.module.rxjs.Subject.prototype)

#### <a name="apidoc.element.rxjs.Subject.prototype._subscribe"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.Subject.prototype._subscribe)
- description and source-code
```javascript
_subscribe = function (subscriber) {
    if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    else if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.isStopped) {
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    else {
        this.observers.push(subscriber);
        return new SubjectSubscription_1.SubjectSubscription(this, subscriber);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subject.prototype._trySubscribe"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>_trySubscribe (subscriber)](#apidoc.element.rxjs.Subject.prototype._trySubscribe)
- description and source-code
```javascript
_trySubscribe = function (subscriber) {
    if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    else {
        return _super.prototype._trySubscribe.call(this, subscriber);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subject.prototype.asObservable"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>asObservable ()](#apidoc.element.rxjs.Subject.prototype.asObservable)
- description and source-code
```javascript
asObservable = function () {
    var observable = new Observable_1.Observable();
    observable.source = this;
    return observable;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subject.prototype.complete"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>complete ()](#apidoc.element.rxjs.Subject.prototype.complete)
- description and source-code
```javascript
complete = function () {
    if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    this.isStopped = true;
    var observers = this.observers;
    var len = observers.length;
    var copy = observers.slice();
    for (var i = 0; i < len; i++) {
        copy[i].complete();
    }
    this.observers.length = 0;
}
```
- example usage
```shell
...
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
        this.value = value;
...
```

#### <a name="apidoc.element.rxjs.Subject.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>constructor ()](#apidoc.element.rxjs.Subject.prototype.constructor)
- description and source-code
```javascript
function Subject() {
    _super.call(this);
    this.observers = [];
    this.closed = false;
    this.isStopped = false;
    this.hasError = false;
    this.thrownError = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subject.prototype.error"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>error (err)](#apidoc.element.rxjs.Subject.prototype.error)
- description and source-code
```javascript
error = function (err) {
    if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    this.hasError = true;
    this.thrownError = err;
    this.isStopped = true;
    var observers = this.observers;
    var len = observers.length;
    var copy = observers.slice();
    for (var i = 0; i < len; i++) {
        copy[i].error(err);
    }
    this.observers.length = 0;
}
```
- example usage
```shell
...
    _super.apply(this, arguments);
    this.value = null;
    this.hasNext = false;
    this.hasCompleted = false;
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
...
```

#### <a name="apidoc.element.rxjs.Subject.prototype.lift"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>lift (operator)](#apidoc.element.rxjs.Subject.prototype.lift)
- description and source-code
```javascript
lift = function (operator) {
    var subject = new AnonymousSubject(this, this);
    subject.operator = operator;
    return subject;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subject.prototype.next"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>next (value)](#apidoc.element.rxjs.Subject.prototype.next)
- description and source-code
```javascript
next = function (value) {
    if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    if (!this.isStopped) {
        var observers = this.observers;
        var len = observers.length;
        var copy = observers.slice();
        for (var i = 0; i < len; i++) {
            copy[i].next(value);
        }
    }
}
```
- example usage
```shell
...
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
...
```

#### <a name="apidoc.element.rxjs.Subject.prototype.unsubscribe"></a>[function <span class="apidocSignatureSpan">rxjs.Subject.prototype.</span>unsubscribe ()](#apidoc.element.rxjs.Subject.prototype.unsubscribe)
- description and source-code
```javascript
unsubscribe = function () {
    this.isStopped = true;
    this.closed = true;
    this.observers = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Subscriber"></a>[module rxjs.Subscriber](#apidoc.module.rxjs.Subscriber)

#### <a name="apidoc.element.rxjs.Subscriber.Subscriber"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Subscriber (destinationOrNext, error, complete)](#apidoc.element.rxjs.Subscriber.Subscriber)
- description and source-code
```javascript
function Subscriber(destinationOrNext, error, complete) {
    _super.call(this);
    this.syncErrorValue = null;
    this.syncErrorThrown = false;
    this.syncErrorThrowable = false;
    this.isStopped = false;
    switch (arguments.length) {
        case 0:
            this.destination = Observer_1.empty;
            break;
        case 1:
            if (!destinationOrNext) {
                this.destination = Observer_1.empty;
                break;
            }
            if (typeof destinationOrNext === 'object') {
                if (destinationOrNext instanceof Subscriber) {
                    this.destination = destinationOrNext;
                    this.destination.add(this);
                }
                else {
                    this.syncErrorThrowable = true;
                    this.destination = new SafeSubscriber(this, destinationOrNext);
                }
                break;
            }
        default:
            this.syncErrorThrowable = true;
            this.destination = new SafeSubscriber(this, destinationOrNext, error, complete);
            break;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscriber.create"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.</span>create (next, error, complete)](#apidoc.element.rxjs.Subscriber.create)
- description and source-code
```javascript
create = function (next, error, complete) {
    var subscriber = new Subscriber(next, error, complete);
    subscriber.syncErrorThrowable = false;
    return subscriber;
}
```
- example usage
```shell
...



"use strict";
var __extends = (this && this.__extends) || function (d, b) {
    for (var p in b) if (b.hasOwnProperty(p)) d[p] = b[p];
    function __() { this.constructor = d; }
    d.prototype = b === null ? Object.create(b) : (__.prototype = b.prototype, new __());
};
var Subject_1 = require('./Subject');
var Subscription_1 = require('./Subscription');
/**
 * @class AsyncSubject<T>
 */
var AsyncSubject = (function (_super) {
...
```



# <a name="apidoc.module.rxjs.Subscriber.prototype"></a>[module rxjs.Subscriber.prototype](#apidoc.module.rxjs.Subscriber.prototype)

#### <a name="apidoc.element.rxjs.Subscriber.prototype._complete"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>_complete ()](#apidoc.element.rxjs.Subscriber.prototype._complete)
- description and source-code
```javascript
_complete = function () {
    this.destination.complete();
    this.unsubscribe();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscriber.prototype._error"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>_error (err)](#apidoc.element.rxjs.Subscriber.prototype._error)
- description and source-code
```javascript
_error = function (err) {
    this.destination.error(err);
    this.unsubscribe();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscriber.prototype._next"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>_next (value)](#apidoc.element.rxjs.Subscriber.prototype._next)
- description and source-code
```javascript
_next = function (value) {
    this.destination.next(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscriber.prototype._unsubscribeAndRecycle"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>_unsubscribeAndRecycle ()](#apidoc.element.rxjs.Subscriber.prototype._unsubscribeAndRecycle)
- description and source-code
```javascript
_unsubscribeAndRecycle = function () {
    var _a = this, _parent = _a._parent, _parents = _a._parents;
    this._parent = null;
    this._parents = null;
    this.unsubscribe();
    this.closed = false;
    this.isStopped = false;
    this._parent = _parent;
    this._parents = _parents;
    return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscriber.prototype.complete"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>complete ()](#apidoc.element.rxjs.Subscriber.prototype.complete)
- description and source-code
```javascript
complete = function () {
    if (!this.isStopped) {
        this.isStopped = true;
        this._complete();
    }
}
```
- example usage
```shell
...
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
        this.value = value;
...
```

#### <a name="apidoc.element.rxjs.Subscriber.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>constructor (destinationOrNext, error, complete)](#apidoc.element.rxjs.Subscriber.prototype.constructor)
- description and source-code
```javascript
function Subscriber(destinationOrNext, error, complete) {
    _super.call(this);
    this.syncErrorValue = null;
    this.syncErrorThrown = false;
    this.syncErrorThrowable = false;
    this.isStopped = false;
    switch (arguments.length) {
        case 0:
            this.destination = Observer_1.empty;
            break;
        case 1:
            if (!destinationOrNext) {
                this.destination = Observer_1.empty;
                break;
            }
            if (typeof destinationOrNext === 'object') {
                if (destinationOrNext instanceof Subscriber) {
                    this.destination = destinationOrNext;
                    this.destination.add(this);
                }
                else {
                    this.syncErrorThrowable = true;
                    this.destination = new SafeSubscriber(this, destinationOrNext);
                }
                break;
            }
        default:
            this.syncErrorThrowable = true;
            this.destination = new SafeSubscriber(this, destinationOrNext, error, complete);
            break;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscriber.prototype.error"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>error (err)](#apidoc.element.rxjs.Subscriber.prototype.error)
- description and source-code
```javascript
error = function (err) {
    if (!this.isStopped) {
        this.isStopped = true;
        this._error(err);
    }
}
```
- example usage
```shell
...
    _super.apply(this, arguments);
    this.value = null;
    this.hasNext = false;
    this.hasCompleted = false;
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
...
```

#### <a name="apidoc.element.rxjs.Subscriber.prototype.next"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>next (value)](#apidoc.element.rxjs.Subscriber.prototype.next)
- description and source-code
```javascript
next = function (value) {
    if (!this.isStopped) {
        this._next(value);
    }
}
```
- example usage
```shell
...
}
AsyncSubject.prototype._subscribe = function (subscriber) {
    if (this.hasError) {
        subscriber.error(this.thrownError);
        return Subscription_1.Subscription.EMPTY;
    }
    else if (this.hasCompleted && this.hasNext) {
        subscriber.next(this.value);
        subscriber.complete();
        return Subscription_1.Subscription.EMPTY;
    }
    return _super.prototype._subscribe.call(this, subscriber);
};
AsyncSubject.prototype.next = function (value) {
    if (!this.hasCompleted) {
...
```

#### <a name="apidoc.element.rxjs.Subscriber.prototype.unsubscribe"></a>[function <span class="apidocSignatureSpan">rxjs.Subscriber.prototype.</span>unsubscribe ()](#apidoc.element.rxjs.Subscriber.prototype.unsubscribe)
- description and source-code
```javascript
unsubscribe = function () {
    if (this.closed) {
        return;
    }
    this.isStopped = true;
    _super.prototype.unsubscribe.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Subscription"></a>[module rxjs.Subscription](#apidoc.module.rxjs.Subscription)

#### <a name="apidoc.element.rxjs.Subscription.Subscription"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Subscription (unsubscribe)](#apidoc.element.rxjs.Subscription.Subscription)
- description and source-code
```javascript
function Subscription(unsubscribe) {
<span class="apidocCodeCommentSpan">    /**
     * A flag to indicate whether this Subscription has already been unsubscribed.
     * @type {boolean}
     */
</span>    this.closed = false;
    this._parent = null;
    this._parents = null;
    this._subscriptions = null;
    if (unsubscribe) {
        this._unsubscribe = unsubscribe;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Subscription.prototype"></a>[module rxjs.Subscription.prototype](#apidoc.module.rxjs.Subscription.prototype)

#### <a name="apidoc.element.rxjs.Subscription.prototype._addParent"></a>[function <span class="apidocSignatureSpan">rxjs.Subscription.prototype.</span>_addParent (parent)](#apidoc.element.rxjs.Subscription.prototype._addParent)
- description and source-code
```javascript
_addParent = function (parent) {
    var _a = this, _parent = _a._parent, _parents = _a._parents;
    if (!_parent || _parent === parent) {
        // If we don't have a parent, or the new parent is the same as the
        // current parent, then set this._parent to the new parent.
        this._parent = parent;
    }
    else if (!_parents) {
        // If there's already one parent, but not multiple, allocate an Array to
        // store the rest of the parent Subscriptions.
        this._parents = [parent];
    }
    else if (_parents.indexOf(parent) === -1) {
        // Only add the new parent to the _parents list if it's not already there.
        _parents.push(parent);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscription.prototype.add"></a>[function <span class="apidocSignatureSpan">rxjs.Subscription.prototype.</span>add (teardown)](#apidoc.element.rxjs.Subscription.prototype.add)
- description and source-code
```javascript
add = function (teardown) {
    if (!teardown || (teardown === Subscription.EMPTY)) {
        return Subscription.EMPTY;
    }
    if (teardown === this) {
        return this;
    }
    var subscription = teardown;
    switch (typeof teardown) {
        case 'function':
            subscription = new Subscription(teardown);
        case 'object':
            if (subscription.closed || typeof subscription.unsubscribe !== 'function') {
                return subscription;
            }
            else if (this.closed) {
                subscription.unsubscribe();
                return subscription;
            }
            else if (typeof subscription._addParent !== 'function' /* quack quack */) {
                var tmp = subscription;
                subscription = new Subscription();
                subscription._subscriptions = [tmp];
            }
            break;
        default:
            throw new Error('unrecognized teardown ' + teardown + ' added to Subscription.');
    }
    var subscriptions = this._subscriptions || (this._subscriptions = []);
    subscriptions.push(subscription);
    subscription._addParent(this);
    return subscription;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscription.prototype.remove"></a>[function <span class="apidocSignatureSpan">rxjs.Subscription.prototype.</span>remove (subscription)](#apidoc.element.rxjs.Subscription.prototype.remove)
- description and source-code
```javascript
remove = function (subscription) {
    var subscriptions = this._subscriptions;
    if (subscriptions) {
        var subscriptionIndex = subscriptions.indexOf(subscription);
        if (subscriptionIndex !== -1) {
            subscriptions.splice(subscriptionIndex, 1);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.Subscription.prototype.unsubscribe"></a>[function <span class="apidocSignatureSpan">rxjs.Subscription.prototype.</span>unsubscribe ()](#apidoc.element.rxjs.Subscription.prototype.unsubscribe)
- description and source-code
```javascript
unsubscribe = function () {
    var hasErrors = false;
    var errors;
    if (this.closed) {
        return;
    }
    var _a = this, _parent = _a._parent, _parents = _a._parents, _unsubscribe = _a._unsubscribe, _subscriptions = _a._subscriptions
;
    this.closed = true;
    this._parent = null;
    this._parents = null;
    // null out _subscriptions first so any child subscriptions that attempt
    // to remove themselves from this subscription will noop
    this._subscriptions = null;
    var index = -1;
    var len = _parents ? _parents.length : 0;
    // if this._parent is null, then so is this._parents, and we
    // don't have to remove ourselves from any parent subscriptions.
    while (_parent) {
        _parent.remove(this);
        // if this._parents is null or index >= len,
        // then _parent is set to null, and the loop exits
        _parent = ++index < len && _parents[index] || null;
    }
    if (isFunction_1.isFunction(_unsubscribe)) {
        var trial = tryCatch_1.tryCatch(_unsubscribe).call(this);
        if (trial === errorObject_1.errorObject) {
            hasErrors = true;
            errors = errors || (errorObject_1.errorObject.e instanceof UnsubscriptionError_1.UnsubscriptionError ?
                flattenUnsubscriptionErrors(errorObject_1.errorObject.e.errors) : [errorObject_1.errorObject.e]);
        }
    }
    if (isArray_1.isArray(_subscriptions)) {
        index = -1;
        len = _subscriptions.length;
        while (++index < len) {
            var sub = _subscriptions[index];
            if (isObject_1.isObject(sub)) {
                var trial = tryCatch_1.tryCatch(sub.unsubscribe).call(sub);
                if (trial === errorObject_1.errorObject) {
                    hasErrors = true;
                    errors = errors || [];
                    var err = errorObject_1.errorObject.e;
                    if (err instanceof UnsubscriptionError_1.UnsubscriptionError) {
                        errors = errors.concat(flattenUnsubscriptionErrors(err.errors));
                    }
                    else {
                        errors.push(err);
                    }
                }
            }
        }
    }
    if (hasErrors) {
        throw new UnsubscriptionError_1.UnsubscriptionError(errors);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.TestScheduler"></a>[module rxjs.TestScheduler](#apidoc.module.rxjs.TestScheduler)

#### <a name="apidoc.element.rxjs.TestScheduler.TestScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>TestScheduler (assertDeepEqual)](#apidoc.element.rxjs.TestScheduler.TestScheduler)
- description and source-code
```javascript
function TestScheduler(assertDeepEqual) {
    _super.call(this, VirtualTimeScheduler_1.VirtualAction, defaultMaxFrame);
    this.assertDeepEqual = assertDeepEqual;
    this.hotObservables = [];
    this.coldObservables = [];
    this.flushTests = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.now"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.</span>now ()](#apidoc.element.rxjs.TestScheduler.now)
- description and source-code
```javascript
function now() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.parseMarbles"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.</span>parseMarbles (marbles, values, errorValue, materializeInnerObservables)](#apidoc.element.rxjs.TestScheduler.parseMarbles)
- description and source-code
```javascript
parseMarbles = function (marbles, values, errorValue, materializeInnerObservables) {
    if (materializeInnerObservables === void 0) { materializeInnerObservables = false; }
    if (marbles.indexOf('!') !== -1) {
        throw new Error('conventional marble diagrams cannot have the ' +
            'unsubscription marker "!"');
    }
    var len = marbles.length;
    var testMessages = [];
    var subIndex = marbles.indexOf('^');
    var frameOffset = subIndex === -1 ? 0 : (subIndex * -this.frameTimeFactor);
    var getValue = typeof values !== 'object' ?
        function (x) { return x; } :
        function (x) {
            // Support Observable-of-Observables
            if (materializeInnerObservables && values[x] instanceof ColdObservable_1.ColdObservable) {
                return values[x].messages;
            }
            return values[x];
        };
    var groupStart = -1;
    for (var i = 0; i < len; i++) {
        var frame = i * this.frameTimeFactor + frameOffset;
        var notification = void 0;
        var c = marbles[i];
        switch (c) {
            case '-':
            case ' ':
                break;
            case '(':
                groupStart = frame;
                break;
            case ')':
                groupStart = -1;
                break;
            case '|':
                notification = Notification_1.Notification.createComplete();
                break;
            case '^':
                break;
            case '#':
                notification = Notification_1.Notification.createError(errorValue || 'error');
                break;
            default:
                notification = Notification_1.Notification.createNext(getValue(c));
                break;
        }
        if (notification) {
            testMessages.push({ frame: groupStart > -1 ? groupStart : frame, notification: notification });
        }
    }
    return testMessages;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.parseMarblesAsSubscriptions"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.</span>parseMarblesAsSubscriptions (marbles)](#apidoc.element.rxjs.TestScheduler.parseMarblesAsSubscriptions)
- description and source-code
```javascript
parseMarblesAsSubscriptions = function (marbles) {
    if (typeof marbles !== 'string') {
        return new SubscriptionLog_1.SubscriptionLog(Number.POSITIVE_INFINITY);
    }
    var len = marbles.length;
    var groupStart = -1;
    var subscriptionFrame = Number.POSITIVE_INFINITY;
    var unsubscriptionFrame = Number.POSITIVE_INFINITY;
    for (var i = 0; i < len; i++) {
        var frame = i * this.frameTimeFactor;
        var c = marbles[i];
        switch (c) {
            case '-':
            case ' ':
                break;
            case '(':
                groupStart = frame;
                break;
            case ')':
                groupStart = -1;
                break;
            case '^':
                if (subscriptionFrame !== Number.POSITIVE_INFINITY) {
                    throw new Error('found a second subscription point \'^\' in a ' +
                        'subscription marble diagram. There can only be one.');
                }
                subscriptionFrame = groupStart > -1 ? groupStart : frame;
                break;
            case '!':
                if (unsubscriptionFrame !== Number.POSITIVE_INFINITY) {
                    throw new Error('found a second subscription point \'^\' in a ' +
                        'subscription marble diagram. There can only be one.');
                }
                unsubscriptionFrame = groupStart > -1 ? groupStart : frame;
                break;
            default:
                throw new Error('there can only be \'^\' and \'!\' markers in a ' +
                    'subscription marble diagram. Found instead \'' + c + '\'.');
        }
    }
    if (unsubscriptionFrame < 0) {
        return new SubscriptionLog_1.SubscriptionLog(subscriptionFrame);
    }
    else {
        return new SubscriptionLog_1.SubscriptionLog(subscriptionFrame, unsubscriptionFrame);
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.TestScheduler.prototype"></a>[module rxjs.TestScheduler.prototype](#apidoc.module.rxjs.TestScheduler.prototype)

#### <a name="apidoc.element.rxjs.TestScheduler.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>constructor (assertDeepEqual)](#apidoc.element.rxjs.TestScheduler.prototype.constructor)
- description and source-code
```javascript
function TestScheduler(assertDeepEqual) {
    _super.call(this, VirtualTimeScheduler_1.VirtualAction, defaultMaxFrame);
    this.assertDeepEqual = assertDeepEqual;
    this.hotObservables = [];
    this.coldObservables = [];
    this.flushTests = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.prototype.createColdObservable"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>createColdObservable (marbles, values, error)](#apidoc.element.rxjs.TestScheduler.prototype.createColdObservable)
- description and source-code
```javascript
createColdObservable = function (marbles, values, error) {
    if (marbles.indexOf('^') !== -1) {
        throw new Error('cold observable cannot have subscription offset "^"');
    }
    if (marbles.indexOf('!') !== -1) {
        throw new Error('cold observable cannot have unsubscription marker "!"');
    }
    var messages = TestScheduler.parseMarbles(marbles, values, error);
    var cold = new ColdObservable_1.ColdObservable(messages, this);
    this.coldObservables.push(cold);
    return cold;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.prototype.createHotObservable"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>createHotObservable (marbles, values, error)](#apidoc.element.rxjs.TestScheduler.prototype.createHotObservable)
- description and source-code
```javascript
createHotObservable = function (marbles, values, error) {
    if (marbles.indexOf('!') !== -1) {
        throw new Error('hot observable cannot have unsubscription marker "!"');
    }
    var messages = TestScheduler.parseMarbles(marbles, values, error);
    var subject = new HotObservable_1.HotObservable(messages, this);
    this.hotObservables.push(subject);
    return subject;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.prototype.createTime"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>createTime (marbles)](#apidoc.element.rxjs.TestScheduler.prototype.createTime)
- description and source-code
```javascript
createTime = function (marbles) {
    var indexOf = marbles.indexOf('|');
    if (indexOf === -1) {
        throw new Error('marble diagram for time should have a completion marker "|"');
    }
    return indexOf * TestScheduler.frameTimeFactor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.prototype.expectObservable"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>expectObservable (observable, unsubscriptionMarbles)](#apidoc.element.rxjs.TestScheduler.prototype.expectObservable)
- description and source-code
```javascript
expectObservable = function (observable, unsubscriptionMarbles) {
    var _this = this;
    if (unsubscriptionMarbles === void 0) { unsubscriptionMarbles = null; }
    var actual = [];
    var flushTest = { actual: actual, ready: false };
    var unsubscriptionFrame = TestScheduler
        .parseMarblesAsSubscriptions(unsubscriptionMarbles).unsubscribedFrame;
    var subscription;
    this.schedule(function () {
        subscription = observable.subscribe(function (x) {
            var value = x;
            // Support Observable-of-Observables
            if (x instanceof Observable_1.Observable) {
                value = _this.materializeInnerObservable(value, _this.frame);
            }
            actual.push({ frame: _this.frame, notification: Notification_1.Notification.createNext(value) });
        }, function (err) {
            actual.push({ frame: _this.frame, notification: Notification_1.Notification.createError(err) });
        }, function () {
            actual.push({ frame: _this.frame, notification: Notification_1.Notification.createComplete() });
        });
    }, 0);
    if (unsubscriptionFrame !== Number.POSITIVE_INFINITY) {
        this.schedule(function () { return subscription.unsubscribe(); }, unsubscriptionFrame);
    }
    this.flushTests.push(flushTest);
    return {
        toBe: function (marbles, values, errorValue) {
            flushTest.ready = true;
            flushTest.expected = TestScheduler.parseMarbles(marbles, values, errorValue, true);
        }
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.prototype.expectSubscriptions"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>expectSubscriptions (actualSubscriptionLogs)](#apidoc.element.rxjs.TestScheduler.prototype.expectSubscriptions)
- description and source-code
```javascript
expectSubscriptions = function (actualSubscriptionLogs) {
    var flushTest = { actual: actualSubscriptionLogs, ready: false };
    this.flushTests.push(flushTest);
    return {
        toBe: function (marbles) {
            var marblesArray = (typeof marbles === 'string') ? [marbles] : marbles;
            flushTest.ready = true;
            flushTest.expected = marblesArray.map(function (marbles) {
                return TestScheduler.parseMarblesAsSubscriptions(marbles);
            });
        }
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.prototype.flush"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>flush ()](#apidoc.element.rxjs.TestScheduler.prototype.flush)
- description and source-code
```javascript
flush = function () {
    var hotObservables = this.hotObservables;
    while (hotObservables.length > 0) {
        hotObservables.shift().setup();
    }
    _super.prototype.flush.call(this);
    var readyFlushTests = this.flushTests.filter(function (test) { return test.ready; });
    while (readyFlushTests.length > 0) {
        var test = readyFlushTests.shift();
        this.assertDeepEqual(test.actual, test.expected);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TestScheduler.prototype.materializeInnerObservable"></a>[function <span class="apidocSignatureSpan">rxjs.TestScheduler.prototype.</span>materializeInnerObservable (observable, outerFrame)](#apidoc.element.rxjs.TestScheduler.prototype.materializeInnerObservable)
- description and source-code
```javascript
materializeInnerObservable = function (observable, outerFrame) {
    var _this = this;
    var messages = [];
    observable.subscribe(function (value) {
        messages.push({ frame: _this.frame - outerFrame, notification: Notification_1.Notification.createNext(value) });
    }, function (err) {
        messages.push({ frame: _this.frame - outerFrame, notification: Notification_1.Notification.createError(err) });
    }, function () {
        messages.push({ frame: _this.frame - outerFrame, notification: Notification_1.Notification.createComplete() });
    });
    return messages;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.TimeoutError"></a>[module rxjs.TimeoutError](#apidoc.module.rxjs.TimeoutError)

#### <a name="apidoc.element.rxjs.TimeoutError.TimeoutError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>TimeoutError ()](#apidoc.element.rxjs.TimeoutError.TimeoutError)
- description and source-code
```javascript
function TimeoutError() {
    var err = _super.call(this, 'Timeout has occurred');
    this.name = err.name = 'TimeoutError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.TimeoutError.captureStackTrace"></a>[function <span class="apidocSignatureSpan">rxjs.TimeoutError.</span>captureStackTrace ()](#apidoc.element.rxjs.TimeoutError.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.TimeoutError.prototype"></a>[module rxjs.TimeoutError.prototype](#apidoc.module.rxjs.TimeoutError.prototype)

#### <a name="apidoc.element.rxjs.TimeoutError.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.TimeoutError.prototype.</span>constructor ()](#apidoc.element.rxjs.TimeoutError.prototype.constructor)
- description and source-code
```javascript
function TimeoutError() {
    var err = _super.call(this, 'Timeout has occurred');
    this.name = err.name = 'TimeoutError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.UnsubscriptionError"></a>[module rxjs.UnsubscriptionError](#apidoc.module.rxjs.UnsubscriptionError)

#### <a name="apidoc.element.rxjs.UnsubscriptionError.UnsubscriptionError"></a>[function <span class="apidocSignatureSpan">rxjs.</span>UnsubscriptionError (errors)](#apidoc.element.rxjs.UnsubscriptionError.UnsubscriptionError)
- description and source-code
```javascript
function UnsubscriptionError(errors) {
    _super.call(this);
    this.errors = errors;
    var err = Error.call(this, errors ?
        errors.length + " errors occurred during unsubscription:\n  " + errors.map(function (err, i) { return ((i + 1) + ") " +
err.toString()); }).join('\n  ') : '');
    this.name = err.name = 'UnsubscriptionError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.UnsubscriptionError.captureStackTrace"></a>[function <span class="apidocSignatureSpan">rxjs.UnsubscriptionError.</span>captureStackTrace ()](#apidoc.element.rxjs.UnsubscriptionError.captureStackTrace)
- description and source-code
```javascript
function captureStackTrace() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.UnsubscriptionError.prototype"></a>[module rxjs.UnsubscriptionError.prototype](#apidoc.module.rxjs.UnsubscriptionError.prototype)

#### <a name="apidoc.element.rxjs.UnsubscriptionError.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.UnsubscriptionError.prototype.</span>constructor (errors)](#apidoc.element.rxjs.UnsubscriptionError.prototype.constructor)
- description and source-code
```javascript
function UnsubscriptionError(errors) {
    _super.call(this);
    this.errors = errors;
    var err = Error.call(this, errors ?
        errors.length + " errors occurred during unsubscription:\n  " + errors.map(function (err, i) { return ((i + 1) + ") " +
err.toString()); }).join('\n  ') : '');
    this.name = err.name = 'UnsubscriptionError';
    this.stack = err.stack;
    this.message = err.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.VirtualTimeScheduler"></a>[module rxjs.VirtualTimeScheduler](#apidoc.module.rxjs.VirtualTimeScheduler)

#### <a name="apidoc.element.rxjs.VirtualTimeScheduler.VirtualTimeScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>VirtualTimeScheduler (SchedulerAction, maxFrames)](#apidoc.element.rxjs.VirtualTimeScheduler.VirtualTimeScheduler)
- description and source-code
```javascript
function VirtualTimeScheduler(SchedulerAction, maxFrames) {
    var _this = this;
    if (SchedulerAction === void 0) { SchedulerAction = VirtualAction; }
    if (maxFrames === void 0) { maxFrames = Number.POSITIVE_INFINITY; }
    _super.call(this, SchedulerAction, function () { return _this.frame; });
    this.maxFrames = maxFrames;
    this.frame = 0;
    this.index = -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.VirtualTimeScheduler.now"></a>[function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.</span>now ()](#apidoc.element.rxjs.VirtualTimeScheduler.now)
- description and source-code
```javascript
function now() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.VirtualTimeScheduler.prototype"></a>[module rxjs.VirtualTimeScheduler.prototype](#apidoc.module.rxjs.VirtualTimeScheduler.prototype)

#### <a name="apidoc.element.rxjs.VirtualTimeScheduler.prototype.constructor"></a>[function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.prototype.</span>constructor (SchedulerAction, maxFrames)](#apidoc.element.rxjs.VirtualTimeScheduler.prototype.constructor)
- description and source-code
```javascript
function VirtualTimeScheduler(SchedulerAction, maxFrames) {
    var _this = this;
    if (SchedulerAction === void 0) { SchedulerAction = VirtualAction; }
    if (maxFrames === void 0) { maxFrames = Number.POSITIVE_INFINITY; }
    _super.call(this, SchedulerAction, function () { return _this.frame; });
    this.maxFrames = maxFrames;
    this.frame = 0;
    this.index = -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.VirtualTimeScheduler.prototype.flush"></a>[function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.prototype.</span>flush ()](#apidoc.element.rxjs.VirtualTimeScheduler.prototype.flush)
- description and source-code
```javascript
flush = function () {
    var _a = this, actions = _a.actions, maxFrames = _a.maxFrames;
    var error, action;
    while ((action = actions.shift()) && (this.frame = action.delay) <= maxFrames) {
        if (error = action.execute(action.state, action.delay)) {
            break;
        }
    }
    if (error) {
        while (action = actions.shift()) {
            action.unsubscribe();
        }
        throw error;
    }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
