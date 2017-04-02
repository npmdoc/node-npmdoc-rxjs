# api documentation for  [rxjs (v5.2.0)](https://github.com/ReactiveX/RxJS)  [![npm package](https://img.shields.io/npm/v/npmdoc-rxjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-rxjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-rxjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-rxjs)
#### Reactive Extensions for modern JavaScript

[![NPM](https://nodei.co/npm/rxjs.png?downloads=true)](https://www.npmjs.com/package/rxjs)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rxjs/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-rxjs_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rxjs/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-rxjs/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Lesh",
        "email": "ben@benlesh.com"
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
            "name": "Ben Lesh",
            "email": "ben@benlesh.com"
        },
        {
            "name": "Paul Taylor",
            "email": "paul.e.taylor@me.com"
        },
        {
            "name": "Jeff Cross",
            "email": "crossj@google.com"
        },
        {
            "name": "Matthew Podwysocki",
            "email": "matthewp@microsoft.com"
        },
        {
            "name": "OJ Kwon",
            "email": "kwon.ohjoong@gmail.com"
        },
        {
            "name": "Andre Staltz",
            "email": "andre@staltz.com"
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
        "fs-extra": "^0.30.0",
        "glob": "^7.0.3",
        "gm": "^1.22.0",
        "google-closure-compiler-js": "^20160916.0.0",
        "gzip-size": "^3.0.0",
        "http-server": "^0.9.0",
        "husky": "^0.12.0",
        "lint-staged": "^3.2.5",
        "lodash": "^4.15.0",
        "madge": "^1.4.3",
        "markdown-doctest": "^0.8.1",
        "minimist": "^1.2.0",
        "mkdirp": "^0.5.1",
        "mocha": "^3.0.2",
        "mocha-in-sauce": "0.0.1",
        "npm-run-all": "^3.1.0",
        "npm-scripts-info": "^0.3.4",
        "nyc": "^8.3.0",
        "opn-cli": "^3.1.0",
        "platform": "^1.3.1",
        "promise": "^7.1.1",
        "protractor": "^3.1.1",
        "rollup": "0.36.3",
        "rollup-plugin-inject": "^2.0.0",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rx": "latest",
        "shx": "^0.1.4",
        "sinon": "^2.0.0-pre",
        "sinon-chai": "^2.8.0",
        "source-map-support": "^0.4.0",
        "tslib": "^1.5.0",
        "tslint": "^4.4.2",
        "typescript": "~2.0.6",
        "typings": "^2.0.0",
        "validate-commit-msg": "^2.3.1",
        "watch": "^1.0.1",
        "watchify": "3.7.0",
        "webpack": "^1.13.1",
        "xmlhttprequest": "1.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "db537de8767c05fa73721587a29e0085307d318b",
        "tarball": "https://registry.npmjs.org/rxjs/-/rxjs-5.2.0.tgz"
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
            "name": "blesh",
            "email": "ben@benlesh.com"
        },
        {
            "name": "jeffbcross",
            "email": "middlefloor@gmail.com"
        }
    ],
    "name": "rxjs",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
    "version": "5.2.0"
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
1.  object <span class="apidocSignatureSpan">rxjs.</span>Action
1.  object <span class="apidocSignatureSpan">rxjs.</span>AjaxError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>AjaxTimeoutError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>AnimationFrame
1.  object <span class="apidocSignatureSpan">rxjs.</span>AnimationFrameAction
1.  object <span class="apidocSignatureSpan">rxjs.</span>AnimationFrameScheduler
1.  object <span class="apidocSignatureSpan">rxjs.</span>AnonymousSubject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>ArgumentOutOfRangeError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>ArrayLikeObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>ArrayObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>AsapAction
1.  object <span class="apidocSignatureSpan">rxjs.</span>AsapScheduler
1.  object <span class="apidocSignatureSpan">rxjs.</span>AsyncAction
1.  object <span class="apidocSignatureSpan">rxjs.</span>AsyncScheduler
1.  object <span class="apidocSignatureSpan">rxjs.</span>AsyncSubject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>BehaviorSubject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>BoundCallbackObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>BoundNodeCallbackObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>ColdObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>ConnectableObservable.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>DeferObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>EmptyError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>EmptyObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>ErrorObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>FastMap
1.  object <span class="apidocSignatureSpan">rxjs.</span>ForkJoinObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>FromEventObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>FromEventPatternObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>FromObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>GenerateObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>HotObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>IfObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>Immediate
1.  object <span class="apidocSignatureSpan">rxjs.</span>InnerSubscriber
1.  object <span class="apidocSignatureSpan">rxjs.</span>IntervalObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>IteratorObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>Map
1.  object <span class="apidocSignatureSpan">rxjs.</span>MapPolyfill
1.  object <span class="apidocSignatureSpan">rxjs.</span>NeverObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>Notification.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>ObjectUnsubscribedError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>Observable.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>OuterSubscriber
1.  object <span class="apidocSignatureSpan">rxjs.</span>PairsObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>PromiseObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>QueueAction
1.  object <span class="apidocSignatureSpan">rxjs.</span>QueueScheduler
1.  object <span class="apidocSignatureSpan">rxjs.</span>RangeObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>ReplaySubject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>ScalarObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>Scheduler
1.  object <span class="apidocSignatureSpan">rxjs.</span>Set
1.  object <span class="apidocSignatureSpan">rxjs.</span>Subject.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>SubjectSubscription
1.  object <span class="apidocSignatureSpan">rxjs.</span>SubscribeOnObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>Subscriber.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>Subscription.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>SubscriptionLog
1.  object <span class="apidocSignatureSpan">rxjs.</span>SubscriptionLoggable
1.  object <span class="apidocSignatureSpan">rxjs.</span>Symbol
1.  object <span class="apidocSignatureSpan">rxjs.</span>TestScheduler.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>TimeoutError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>TimerObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>UnsubscriptionError.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>UsingObservable
1.  object <span class="apidocSignatureSpan">rxjs.</span>VirtualTimeScheduler.prototype
1.  object <span class="apidocSignatureSpan">rxjs.</span>applyMixins
1.  object <span class="apidocSignatureSpan">rxjs.</span>assign
1.  object <span class="apidocSignatureSpan">rxjs.</span>audit
1.  object <span class="apidocSignatureSpan">rxjs.</span>auditTime
1.  object <span class="apidocSignatureSpan">rxjs.</span>bindCallback
1.  object <span class="apidocSignatureSpan">rxjs.</span>bindNodeCallback
1.  object <span class="apidocSignatureSpan">rxjs.</span>buffer
1.  object <span class="apidocSignatureSpan">rxjs.</span>bufferCount
1.  object <span class="apidocSignatureSpan">rxjs.</span>bufferTime
1.  object <span class="apidocSignatureSpan">rxjs.</span>bufferToggle
1.  object <span class="apidocSignatureSpan">rxjs.</span>bufferWhen
1.  object <span class="apidocSignatureSpan">rxjs.</span>catch
1.  object <span class="apidocSignatureSpan">rxjs.</span>combineAll
1.  object <span class="apidocSignatureSpan">rxjs.</span>combineLatest
1.  object <span class="apidocSignatureSpan">rxjs.</span>concat
1.  object <span class="apidocSignatureSpan">rxjs.</span>concatAll
1.  object <span class="apidocSignatureSpan">rxjs.</span>concatMap
1.  object <span class="apidocSignatureSpan">rxjs.</span>concatMapTo
1.  object <span class="apidocSignatureSpan">rxjs.</span>count
1.  object <span class="apidocSignatureSpan">rxjs.</span>debounce
1.  object <span class="apidocSignatureSpan">rxjs.</span>debounceTime
1.  object <span class="apidocSignatureSpan">rxjs.</span>defaultIfEmpty
1.  object <span class="apidocSignatureSpan">rxjs.</span>defer
1.  object <span class="apidocSignatureSpan">rxjs.</span>delay
1.  object <span class="apidocSignatureSpan">rxjs.</span>delayWhen
1.  object <span class="apidocSignatureSpan">rxjs.</span>dematerialize
1.  object <span class="apidocSignatureSpan">rxjs.</span>distinct
1.  object <span class="apidocSignatureSpan">rxjs.</span>distinctUntilChanged
1.  object <span class="apidocSignatureSpan">rxjs.</span>distinctUntilKeyChanged
1.  object <span class="apidocSignatureSpan">rxjs.</span>do
1.  object <span class="apidocSignatureSpan">rxjs.</span>elementAt
1.  object <span class="apidocSignatureSpan">rxjs.</span>empty
1.  object <span class="apidocSignatureSpan">rxjs.</span>every
1.  object <span class="apidocSignatureSpan">rxjs.</span>exhaust
1.  object <span class="apidocSignatureSpan">rxjs.</span>exhaustMap
1.  object <span class="apidocSignatureSpan">rxjs.</span>expand
1.  object <span class="apidocSignatureSpan">rxjs.</span>filter
1.  object <span class="apidocSignatureSpan">rxjs.</span>finally
1.  object <span class="apidocSignatureSpan">rxjs.</span>find
1.  object <span class="apidocSignatureSpan">rxjs.</span>findIndex
1.  object <span class="apidocSignatureSpan">rxjs.</span>first
1.  object <span class="apidocSignatureSpan">rxjs.</span>forkJoin
1.  object <span class="apidocSignatureSpan">rxjs.</span>from
1.  object <span class="apidocSignatureSpan">rxjs.</span>fromEvent
1.  object <span class="apidocSignatureSpan">rxjs.</span>fromEventPattern
1.  object <span class="apidocSignatureSpan">rxjs.</span>fromPromise
1.  object <span class="apidocSignatureSpan">rxjs.</span>groupBy
1.  object <span class="apidocSignatureSpan">rxjs.</span>if
1.  object <span class="apidocSignatureSpan">rxjs.</span>ignoreElements
1.  object <span class="apidocSignatureSpan">rxjs.</span>interval
1.  object <span class="apidocSignatureSpan">rxjs.</span>isArray
1.  object <span class="apidocSignatureSpan">rxjs.</span>isArrayLike
1.  object <span class="apidocSignatureSpan">rxjs.</span>isDate
1.  object <span class="apidocSignatureSpan">rxjs.</span>isEmpty
1.  object <span class="apidocSignatureSpan">rxjs.</span>isFunction
1.  object <span class="apidocSignatureSpan">rxjs.</span>isNumeric
1.  object <span class="apidocSignatureSpan">rxjs.</span>isObject
1.  object <span class="apidocSignatureSpan">rxjs.</span>isPromise
1.  object <span class="apidocSignatureSpan">rxjs.</span>isScheduler
1.  object <span class="apidocSignatureSpan">rxjs.</span>iterator
1.  object <span class="apidocSignatureSpan">rxjs.</span>last
1.  object <span class="apidocSignatureSpan">rxjs.</span>let
1.  object <span class="apidocSignatureSpan">rxjs.</span>map
1.  object <span class="apidocSignatureSpan">rxjs.</span>mapTo
1.  object <span class="apidocSignatureSpan">rxjs.</span>materialize
1.  object <span class="apidocSignatureSpan">rxjs.</span>max
1.  object <span class="apidocSignatureSpan">rxjs.</span>merge
1.  object <span class="apidocSignatureSpan">rxjs.</span>mergeAll
1.  object <span class="apidocSignatureSpan">rxjs.</span>mergeMap
1.  object <span class="apidocSignatureSpan">rxjs.</span>mergeMapTo
1.  object <span class="apidocSignatureSpan">rxjs.</span>mergeScan
1.  object <span class="apidocSignatureSpan">rxjs.</span>multicast
1.  object <span class="apidocSignatureSpan">rxjs.</span>never
1.  object <span class="apidocSignatureSpan">rxjs.</span>noop
1.  object <span class="apidocSignatureSpan">rxjs.</span>not
1.  object <span class="apidocSignatureSpan">rxjs.</span>observeOn
1.  object <span class="apidocSignatureSpan">rxjs.</span>of
1.  object <span class="apidocSignatureSpan">rxjs.</span>onErrorResumeNext
1.  object <span class="apidocSignatureSpan">rxjs.</span>pairs
1.  object <span class="apidocSignatureSpan">rxjs.</span>pairwise
1.  object <span class="apidocSignatureSpan">rxjs.</span>partition
1.  object <span class="apidocSignatureSpan">rxjs.</span>pluck
1.  object <span class="apidocSignatureSpan">rxjs.</span>publish
1.  object <span class="apidocSignatureSpan">rxjs.</span>publishBehavior
1.  object <span class="apidocSignatureSpan">rxjs.</span>publishLast
1.  object <span class="apidocSignatureSpan">rxjs.</span>publishReplay
1.  object <span class="apidocSignatureSpan">rxjs.</span>race
1.  object <span class="apidocSignatureSpan">rxjs.</span>range
1.  object <span class="apidocSignatureSpan">rxjs.</span>reduce
1.  object <span class="apidocSignatureSpan">rxjs.</span>repeat
1.  object <span class="apidocSignatureSpan">rxjs.</span>repeatWhen
1.  object <span class="apidocSignatureSpan">rxjs.</span>retry
1.  object <span class="apidocSignatureSpan">rxjs.</span>retryWhen
1.  object <span class="apidocSignatureSpan">rxjs.</span>sample
1.  object <span class="apidocSignatureSpan">rxjs.</span>sampleTime
1.  object <span class="apidocSignatureSpan">rxjs.</span>scan
1.  object <span class="apidocSignatureSpan">rxjs.</span>sequenceEqual
1.  object <span class="apidocSignatureSpan">rxjs.</span>share
1.  object <span class="apidocSignatureSpan">rxjs.</span>single
1.  object <span class="apidocSignatureSpan">rxjs.</span>skip
1.  object <span class="apidocSignatureSpan">rxjs.</span>skipUntil
1.  object <span class="apidocSignatureSpan">rxjs.</span>skipWhile
1.  object <span class="apidocSignatureSpan">rxjs.</span>startWith
1.  object <span class="apidocSignatureSpan">rxjs.</span>subscribeOn
1.  object <span class="apidocSignatureSpan">rxjs.</span>subscribeToResult
1.  object <span class="apidocSignatureSpan">rxjs.</span>switch
1.  object <span class="apidocSignatureSpan">rxjs.</span>switchMap
1.  object <span class="apidocSignatureSpan">rxjs.</span>switchMapTo
1.  object <span class="apidocSignatureSpan">rxjs.</span>take
1.  object <span class="apidocSignatureSpan">rxjs.</span>takeLast
1.  object <span class="apidocSignatureSpan">rxjs.</span>takeUntil
1.  object <span class="apidocSignatureSpan">rxjs.</span>takeWhile
1.  object <span class="apidocSignatureSpan">rxjs.</span>throttle
1.  object <span class="apidocSignatureSpan">rxjs.</span>throttleTime
1.  object <span class="apidocSignatureSpan">rxjs.</span>throw
1.  object <span class="apidocSignatureSpan">rxjs.</span>timeInterval
1.  object <span class="apidocSignatureSpan">rxjs.</span>timeout
1.  object <span class="apidocSignatureSpan">rxjs.</span>timeoutWith
1.  object <span class="apidocSignatureSpan">rxjs.</span>timer
1.  object <span class="apidocSignatureSpan">rxjs.</span>timestamp
1.  object <span class="apidocSignatureSpan">rxjs.</span>toArray
1.  object <span class="apidocSignatureSpan">rxjs.</span>toPromise
1.  object <span class="apidocSignatureSpan">rxjs.</span>toSubscriber
1.  object <span class="apidocSignatureSpan">rxjs.</span>tryCatch
1.  object <span class="apidocSignatureSpan">rxjs.</span>using
1.  object <span class="apidocSignatureSpan">rxjs.</span>window
1.  object <span class="apidocSignatureSpan">rxjs.</span>windowCount
1.  object <span class="apidocSignatureSpan">rxjs.</span>windowTime
1.  object <span class="apidocSignatureSpan">rxjs.</span>windowToggle
1.  object <span class="apidocSignatureSpan">rxjs.</span>windowWhen
1.  object <span class="apidocSignatureSpan">rxjs.</span>withLatestFrom
1.  object <span class="apidocSignatureSpan">rxjs.</span>zip
1.  object <span class="apidocSignatureSpan">rxjs.</span>zipAll

#### [module rxjs.Action](#apidoc.module.rxjs.Action)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Action (scheduler, work)](#apidoc.element.rxjs.Action.Action)

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

#### [module rxjs.AnimationFrame](#apidoc.module.rxjs.AnimationFrame)
1.  [function <span class="apidocSignatureSpan">rxjs.AnimationFrame.</span>RequestAnimationFrameDefinition (root)](#apidoc.element.rxjs.AnimationFrame.RequestAnimationFrameDefinition)
1.  object <span class="apidocSignatureSpan">rxjs.</span>AnimationFrame

#### [module rxjs.AnimationFrameAction](#apidoc.module.rxjs.AnimationFrameAction)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AnimationFrameAction (scheduler, work)](#apidoc.element.rxjs.AnimationFrameAction.AnimationFrameAction)

#### [module rxjs.AnimationFrameScheduler](#apidoc.module.rxjs.AnimationFrameScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AnimationFrameScheduler ()](#apidoc.element.rxjs.AnimationFrameScheduler.AnimationFrameScheduler)

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

#### [module rxjs.ArrayLikeObservable](#apidoc.module.rxjs.ArrayLikeObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ArrayLikeObservable (arrayLike, scheduler)](#apidoc.element.rxjs.ArrayLikeObservable.ArrayLikeObservable)

#### [module rxjs.ArrayObservable](#apidoc.module.rxjs.ArrayObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ArrayObservable (array, scheduler)](#apidoc.element.rxjs.ArrayObservable.ArrayObservable)

#### [module rxjs.AsapAction](#apidoc.module.rxjs.AsapAction)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AsapAction (scheduler, work)](#apidoc.element.rxjs.AsapAction.AsapAction)

#### [module rxjs.AsapScheduler](#apidoc.module.rxjs.AsapScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AsapScheduler ()](#apidoc.element.rxjs.AsapScheduler.AsapScheduler)

#### [module rxjs.AsyncAction](#apidoc.module.rxjs.AsyncAction)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AsyncAction (scheduler, work)](#apidoc.element.rxjs.AsyncAction.AsyncAction)

#### [module rxjs.AsyncScheduler](#apidoc.module.rxjs.AsyncScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>AsyncScheduler ()](#apidoc.element.rxjs.AsyncScheduler.AsyncScheduler)

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

#### [module rxjs.BoundCallbackObservable](#apidoc.module.rxjs.BoundCallbackObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>BoundCallbackObservable (callbackFunc, selector, args, context, scheduler)](#apidoc.element.rxjs.BoundCallbackObservable.BoundCallbackObservable)

#### [module rxjs.BoundNodeCallbackObservable](#apidoc.module.rxjs.BoundNodeCallbackObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>BoundNodeCallbackObservable (callbackFunc, selector, args, context, scheduler)](#apidoc.element.rxjs.BoundNodeCallbackObservable.BoundNodeCallbackObservable)

#### [module rxjs.ColdObservable](#apidoc.module.rxjs.ColdObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ColdObservable (messages, scheduler)](#apidoc.element.rxjs.ColdObservable.ColdObservable)

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

#### [module rxjs.DeferObservable](#apidoc.module.rxjs.DeferObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>DeferObservable (observableFactory)](#apidoc.element.rxjs.DeferObservable.DeferObservable)

#### [module rxjs.EmptyError](#apidoc.module.rxjs.EmptyError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>EmptyError ()](#apidoc.element.rxjs.EmptyError.EmptyError)
1.  [function <span class="apidocSignatureSpan">rxjs.EmptyError.</span>captureStackTrace ()](#apidoc.element.rxjs.EmptyError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.EmptyError.</span>stackTraceLimit

#### [module rxjs.EmptyError.prototype](#apidoc.module.rxjs.EmptyError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.EmptyError.prototype.</span>constructor ()](#apidoc.element.rxjs.EmptyError.prototype.constructor)

#### [module rxjs.EmptyObservable](#apidoc.module.rxjs.EmptyObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>EmptyObservable (scheduler)](#apidoc.element.rxjs.EmptyObservable.EmptyObservable)

#### [module rxjs.ErrorObservable](#apidoc.module.rxjs.ErrorObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ErrorObservable (error, scheduler)](#apidoc.element.rxjs.ErrorObservable.ErrorObservable)

#### [module rxjs.FastMap](#apidoc.module.rxjs.FastMap)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>FastMap ()](#apidoc.element.rxjs.FastMap.FastMap)

#### [module rxjs.ForkJoinObservable](#apidoc.module.rxjs.ForkJoinObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ForkJoinObservable (sources, resultSelector)](#apidoc.element.rxjs.ForkJoinObservable.ForkJoinObservable)

#### [module rxjs.FromEventObservable](#apidoc.module.rxjs.FromEventObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>FromEventObservable (sourceObj, eventName, selector, options)](#apidoc.element.rxjs.FromEventObservable.FromEventObservable)

#### [module rxjs.FromEventPatternObservable](#apidoc.module.rxjs.FromEventPatternObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>FromEventPatternObservable (addHandler, removeHandler, selector)](#apidoc.element.rxjs.FromEventPatternObservable.FromEventPatternObservable)

#### [module rxjs.FromObservable](#apidoc.module.rxjs.FromObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>FromObservable (ish, scheduler)](#apidoc.element.rxjs.FromObservable.FromObservable)

#### [module rxjs.GenerateObservable](#apidoc.module.rxjs.GenerateObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>GenerateObservable (initialState, condition, iterate, resultSelector, scheduler)](#apidoc.element.rxjs.GenerateObservable.GenerateObservable)

#### [module rxjs.HotObservable](#apidoc.module.rxjs.HotObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>HotObservable (messages, scheduler)](#apidoc.element.rxjs.HotObservable.HotObservable)

#### [module rxjs.IfObservable](#apidoc.module.rxjs.IfObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>IfObservable (condition, thenSource, elseSource)](#apidoc.element.rxjs.IfObservable.IfObservable)

#### [module rxjs.Immediate](#apidoc.module.rxjs.Immediate)
1.  [function <span class="apidocSignatureSpan">rxjs.Immediate.</span>ImmediateDefinition (root)](#apidoc.element.rxjs.Immediate.ImmediateDefinition)
1.  object <span class="apidocSignatureSpan">rxjs.</span>Immediate

#### [module rxjs.InnerSubscriber](#apidoc.module.rxjs.InnerSubscriber)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>InnerSubscriber (parent, outerValue, outerIndex)](#apidoc.element.rxjs.InnerSubscriber.InnerSubscriber)

#### [module rxjs.IntervalObservable](#apidoc.module.rxjs.IntervalObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>IntervalObservable (period, scheduler)](#apidoc.element.rxjs.IntervalObservable.IntervalObservable)

#### [module rxjs.IteratorObservable](#apidoc.module.rxjs.IteratorObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>IteratorObservable (iterator, scheduler)](#apidoc.element.rxjs.IteratorObservable.IteratorObservable)

#### [module rxjs.Map](#apidoc.module.rxjs.Map)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Map ()](#apidoc.element.rxjs.Map.Map)

#### [module rxjs.MapPolyfill](#apidoc.module.rxjs.MapPolyfill)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>MapPolyfill ()](#apidoc.element.rxjs.MapPolyfill.MapPolyfill)

#### [module rxjs.NeverObservable](#apidoc.module.rxjs.NeverObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>NeverObservable ()](#apidoc.element.rxjs.NeverObservable.NeverObservable)

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

#### [module rxjs.OuterSubscriber](#apidoc.module.rxjs.OuterSubscriber)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>OuterSubscriber ()](#apidoc.element.rxjs.OuterSubscriber.OuterSubscriber)

#### [module rxjs.PairsObservable](#apidoc.module.rxjs.PairsObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>PairsObservable (obj, scheduler)](#apidoc.element.rxjs.PairsObservable.PairsObservable)

#### [module rxjs.PromiseObservable](#apidoc.module.rxjs.PromiseObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>PromiseObservable (promise, scheduler)](#apidoc.element.rxjs.PromiseObservable.PromiseObservable)

#### [module rxjs.QueueAction](#apidoc.module.rxjs.QueueAction)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>QueueAction (scheduler, work)](#apidoc.element.rxjs.QueueAction.QueueAction)

#### [module rxjs.QueueScheduler](#apidoc.module.rxjs.QueueScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>QueueScheduler ()](#apidoc.element.rxjs.QueueScheduler.QueueScheduler)

#### [module rxjs.RangeObservable](#apidoc.module.rxjs.RangeObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>RangeObservable (start, count, scheduler)](#apidoc.element.rxjs.RangeObservable.RangeObservable)

#### [module rxjs.ReplaySubject](#apidoc.module.rxjs.ReplaySubject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ReplaySubject (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.ReplaySubject.ReplaySubject)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.</span>create (destination, source)](#apidoc.element.rxjs.ReplaySubject.create)

#### [module rxjs.ReplaySubject.prototype](#apidoc.module.rxjs.ReplaySubject.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_getNow ()](#apidoc.element.rxjs.ReplaySubject.prototype._getNow)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_subscribe (subscriber)](#apidoc.element.rxjs.ReplaySubject.prototype._subscribe)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>_trimBufferThenGetEvents ()](#apidoc.element.rxjs.ReplaySubject.prototype._trimBufferThenGetEvents)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>constructor (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.ReplaySubject.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.ReplaySubject.prototype.</span>next (value)](#apidoc.element.rxjs.ReplaySubject.prototype.next)

#### [module rxjs.ScalarObservable](#apidoc.module.rxjs.ScalarObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ScalarObservable (value, scheduler)](#apidoc.element.rxjs.ScalarObservable.ScalarObservable)

#### [module rxjs.Scheduler](#apidoc.module.rxjs.Scheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Scheduler (SchedulerAction, now)](#apidoc.element.rxjs.Scheduler.Scheduler)

#### [module rxjs.Set](#apidoc.module.rxjs.Set)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>Set ()](#apidoc.element.rxjs.Set.Set)
1.  [function <span class="apidocSignatureSpan">rxjs.Set.</span>minimalSetImpl ()](#apidoc.element.rxjs.Set.minimalSetImpl)

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

#### [module rxjs.SubjectSubscription](#apidoc.module.rxjs.SubjectSubscription)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>SubjectSubscription (subject, subscriber)](#apidoc.element.rxjs.SubjectSubscription.SubjectSubscription)

#### [module rxjs.SubscribeOnObservable](#apidoc.module.rxjs.SubscribeOnObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>SubscribeOnObservable (source, delayTime, scheduler)](#apidoc.element.rxjs.SubscribeOnObservable.SubscribeOnObservable)

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

#### [module rxjs.SubscriptionLog](#apidoc.module.rxjs.SubscriptionLog)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>SubscriptionLog (subscribedFrame, unsubscribedFrame)](#apidoc.element.rxjs.SubscriptionLog.SubscriptionLog)

#### [module rxjs.SubscriptionLoggable](#apidoc.module.rxjs.SubscriptionLoggable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>SubscriptionLoggable ()](#apidoc.element.rxjs.SubscriptionLoggable.SubscriptionLoggable)

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

#### [module rxjs.TimerObservable](#apidoc.module.rxjs.TimerObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>TimerObservable (dueTime, period, scheduler)](#apidoc.element.rxjs.TimerObservable.TimerObservable)

#### [module rxjs.UnsubscriptionError](#apidoc.module.rxjs.UnsubscriptionError)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>UnsubscriptionError (errors)](#apidoc.element.rxjs.UnsubscriptionError.UnsubscriptionError)
1.  [function <span class="apidocSignatureSpan">rxjs.UnsubscriptionError.</span>captureStackTrace ()](#apidoc.element.rxjs.UnsubscriptionError.captureStackTrace)
1.  number <span class="apidocSignatureSpan">rxjs.UnsubscriptionError.</span>stackTraceLimit

#### [module rxjs.UnsubscriptionError.prototype](#apidoc.module.rxjs.UnsubscriptionError.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.UnsubscriptionError.prototype.</span>constructor (errors)](#apidoc.element.rxjs.UnsubscriptionError.prototype.constructor)

#### [module rxjs.UsingObservable](#apidoc.module.rxjs.UsingObservable)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>UsingObservable (resourceFactory, observableFactory)](#apidoc.element.rxjs.UsingObservable.UsingObservable)

#### [module rxjs.VirtualTimeScheduler](#apidoc.module.rxjs.VirtualTimeScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>VirtualTimeScheduler (SchedulerAction, maxFrames)](#apidoc.element.rxjs.VirtualTimeScheduler.VirtualTimeScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.</span>now ()](#apidoc.element.rxjs.VirtualTimeScheduler.now)
1.  number <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.</span>frameTimeFactor

#### [module rxjs.VirtualTimeScheduler.prototype](#apidoc.module.rxjs.VirtualTimeScheduler.prototype)
1.  [function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.prototype.</span>constructor (SchedulerAction, maxFrames)](#apidoc.element.rxjs.VirtualTimeScheduler.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">rxjs.VirtualTimeScheduler.prototype.</span>flush ()](#apidoc.element.rxjs.VirtualTimeScheduler.prototype.flush)

#### [module rxjs.applyMixins](#apidoc.module.rxjs.applyMixins)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>applyMixins (derivedCtor, baseCtors)](#apidoc.element.rxjs.applyMixins.applyMixins)

#### [module rxjs.assign](#apidoc.module.rxjs.assign)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>assign ()](#apidoc.element.rxjs.assign.assign)
1.  [function <span class="apidocSignatureSpan">rxjs.assign.</span>assignImpl (target)](#apidoc.element.rxjs.assign.assignImpl)
1.  [function <span class="apidocSignatureSpan">rxjs.assign.</span>getAssign (root)](#apidoc.element.rxjs.assign.getAssign)

#### [module rxjs.audit](#apidoc.module.rxjs.audit)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>audit (durationSelector)](#apidoc.element.rxjs.audit.audit)

#### [module rxjs.auditTime](#apidoc.module.rxjs.auditTime)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>auditTime (duration, scheduler)](#apidoc.element.rxjs.auditTime.auditTime)

#### [module rxjs.bindCallback](#apidoc.module.rxjs.bindCallback)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>bindCallback (func, selector, scheduler)](#apidoc.element.rxjs.bindCallback.bindCallback)

#### [module rxjs.bindNodeCallback](#apidoc.module.rxjs.bindNodeCallback)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>bindNodeCallback (func, selector, scheduler)](#apidoc.element.rxjs.bindNodeCallback.bindNodeCallback)

#### [module rxjs.buffer](#apidoc.module.rxjs.buffer)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>buffer (closingNotifier)](#apidoc.element.rxjs.buffer.buffer)

#### [module rxjs.bufferCount](#apidoc.module.rxjs.bufferCount)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>bufferCount (bufferSize, startBufferEvery)](#apidoc.element.rxjs.bufferCount.bufferCount)

#### [module rxjs.bufferTime](#apidoc.module.rxjs.bufferTime)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>bufferTime (bufferTimeSpan)](#apidoc.element.rxjs.bufferTime.bufferTime)

#### [module rxjs.bufferToggle](#apidoc.module.rxjs.bufferToggle)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>bufferToggle (openings, closingSelector)](#apidoc.element.rxjs.bufferToggle.bufferToggle)

#### [module rxjs.bufferWhen](#apidoc.module.rxjs.bufferWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>bufferWhen (closingSelector)](#apidoc.element.rxjs.bufferWhen.bufferWhen)

#### [module rxjs.catch](#apidoc.module.rxjs.catch)
1.  [function <span class="apidocSignatureSpan">rxjs.catch.</span>_catch (selector)](#apidoc.element.rxjs.catch._catch)

#### [module rxjs.combineAll](#apidoc.module.rxjs.combineAll)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>combineAll (project)](#apidoc.element.rxjs.combineAll.combineAll)

#### [module rxjs.combineLatest](#apidoc.module.rxjs.combineLatest)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>combineLatest ()](#apidoc.element.rxjs.combineLatest.combineLatest)

#### [module rxjs.concat](#apidoc.module.rxjs.concat)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>concat ()](#apidoc.element.rxjs.concat.concat)

#### [module rxjs.concatAll](#apidoc.module.rxjs.concatAll)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>concatAll ()](#apidoc.element.rxjs.concatAll.concatAll)

#### [module rxjs.concatMap](#apidoc.module.rxjs.concatMap)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>concatMap (project, resultSelector)](#apidoc.element.rxjs.concatMap.concatMap)

#### [module rxjs.concatMapTo](#apidoc.module.rxjs.concatMapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>concatMapTo (innerObservable, resultSelector)](#apidoc.element.rxjs.concatMapTo.concatMapTo)

#### [module rxjs.count](#apidoc.module.rxjs.count)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>count (predicate)](#apidoc.element.rxjs.count.count)

#### [module rxjs.debounce](#apidoc.module.rxjs.debounce)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>debounce (durationSelector)](#apidoc.element.rxjs.debounce.debounce)

#### [module rxjs.debounceTime](#apidoc.module.rxjs.debounceTime)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>debounceTime (dueTime, scheduler)](#apidoc.element.rxjs.debounceTime.debounceTime)

#### [module rxjs.defaultIfEmpty](#apidoc.module.rxjs.defaultIfEmpty)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>defaultIfEmpty (defaultValue)](#apidoc.element.rxjs.defaultIfEmpty.defaultIfEmpty)

#### [module rxjs.defer](#apidoc.module.rxjs.defer)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>defer (observableFactory)](#apidoc.element.rxjs.defer.defer)

#### [module rxjs.delay](#apidoc.module.rxjs.delay)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>delay (delay, scheduler)](#apidoc.element.rxjs.delay.delay)

#### [module rxjs.delayWhen](#apidoc.module.rxjs.delayWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>delayWhen (delayDurationSelector, subscriptionDelay)](#apidoc.element.rxjs.delayWhen.delayWhen)

#### [module rxjs.dematerialize](#apidoc.module.rxjs.dematerialize)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>dematerialize ()](#apidoc.element.rxjs.dematerialize.dematerialize)

#### [module rxjs.distinct](#apidoc.module.rxjs.distinct)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>distinct (keySelector, flushes)](#apidoc.element.rxjs.distinct.distinct)
1.  [function <span class="apidocSignatureSpan">rxjs.distinct.</span>DistinctSubscriber (destination, keySelector, flushes)](#apidoc.element.rxjs.distinct.DistinctSubscriber)

#### [module rxjs.distinctUntilChanged](#apidoc.module.rxjs.distinctUntilChanged)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>distinctUntilChanged (compare, keySelector)](#apidoc.element.rxjs.distinctUntilChanged.distinctUntilChanged)

#### [module rxjs.distinctUntilKeyChanged](#apidoc.module.rxjs.distinctUntilKeyChanged)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>distinctUntilKeyChanged (key, compare)](#apidoc.element.rxjs.distinctUntilKeyChanged.distinctUntilKeyChanged)

#### [module rxjs.do](#apidoc.module.rxjs.do)
1.  [function <span class="apidocSignatureSpan">rxjs.do.</span>_do (nextOrObserver, error, complete)](#apidoc.element.rxjs.do._do)

#### [module rxjs.elementAt](#apidoc.module.rxjs.elementAt)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>elementAt (index, defaultValue)](#apidoc.element.rxjs.elementAt.elementAt)

#### [module rxjs.empty](#apidoc.module.rxjs.empty)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>empty (scheduler)](#apidoc.element.rxjs.empty.empty)

#### [module rxjs.every](#apidoc.module.rxjs.every)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>every (predicate, thisArg)](#apidoc.element.rxjs.every.every)

#### [module rxjs.exhaust](#apidoc.module.rxjs.exhaust)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>exhaust ()](#apidoc.element.rxjs.exhaust.exhaust)

#### [module rxjs.exhaustMap](#apidoc.module.rxjs.exhaustMap)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>exhaustMap (project, resultSelector)](#apidoc.element.rxjs.exhaustMap.exhaustMap)

#### [module rxjs.expand](#apidoc.module.rxjs.expand)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>expand (project, concurrent, scheduler)](#apidoc.element.rxjs.expand.expand)
1.  [function <span class="apidocSignatureSpan">rxjs.expand.</span>ExpandOperator (project, concurrent, scheduler)](#apidoc.element.rxjs.expand.ExpandOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.expand.</span>ExpandSubscriber (destination, project, concurrent, scheduler)](#apidoc.element.rxjs.expand.ExpandSubscriber)

#### [module rxjs.filter](#apidoc.module.rxjs.filter)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>filter (predicate, thisArg)](#apidoc.element.rxjs.filter.filter)

#### [module rxjs.finally](#apidoc.module.rxjs.finally)
1.  [function <span class="apidocSignatureSpan">rxjs.finally.</span>_finally (callback)](#apidoc.element.rxjs.finally._finally)

#### [module rxjs.find](#apidoc.module.rxjs.find)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>find (predicate, thisArg)](#apidoc.element.rxjs.find.find)
1.  [function <span class="apidocSignatureSpan">rxjs.find.</span>FindValueOperator (predicate, source, yieldIndex, thisArg)](#apidoc.element.rxjs.find.FindValueOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.find.</span>FindValueSubscriber (destination, predicate, source, yieldIndex, thisArg)](#apidoc.element.rxjs.find.FindValueSubscriber)

#### [module rxjs.findIndex](#apidoc.module.rxjs.findIndex)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>findIndex (predicate, thisArg)](#apidoc.element.rxjs.findIndex.findIndex)

#### [module rxjs.first](#apidoc.module.rxjs.first)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>first (predicate, resultSelector, defaultValue)](#apidoc.element.rxjs.first.first)

#### [module rxjs.forkJoin](#apidoc.module.rxjs.forkJoin)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>forkJoin ()](#apidoc.element.rxjs.forkJoin.forkJoin)

#### [module rxjs.from](#apidoc.module.rxjs.from)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>from (ish, scheduler)](#apidoc.element.rxjs.from.from)

#### [module rxjs.fromEvent](#apidoc.module.rxjs.fromEvent)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>fromEvent (target, eventName, options, selector)](#apidoc.element.rxjs.fromEvent.fromEvent)

#### [module rxjs.fromEventPattern](#apidoc.module.rxjs.fromEventPattern)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>fromEventPattern (addHandler, removeHandler, selector)](#apidoc.element.rxjs.fromEventPattern.fromEventPattern)

#### [module rxjs.fromPromise](#apidoc.module.rxjs.fromPromise)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>fromPromise (promise, scheduler)](#apidoc.element.rxjs.fromPromise.fromPromise)

#### [module rxjs.groupBy](#apidoc.module.rxjs.groupBy)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>groupBy (keySelector, elementSelector, durationSelector, subjectSelector)](#apidoc.element.rxjs.groupBy.groupBy)
1.  [function <span class="apidocSignatureSpan">rxjs.groupBy.</span>GroupedObservable (key, groupSubject, refCountSubscription)](#apidoc.element.rxjs.groupBy.GroupedObservable)

#### [module rxjs.if](#apidoc.module.rxjs.if)
1.  [function <span class="apidocSignatureSpan">rxjs.if.</span>_if (condition, thenSource, elseSource)](#apidoc.element.rxjs.if._if)

#### [module rxjs.ignoreElements](#apidoc.module.rxjs.ignoreElements)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>ignoreElements ()](#apidoc.element.rxjs.ignoreElements.ignoreElements)

#### [module rxjs.interval](#apidoc.module.rxjs.interval)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>interval (period, scheduler)](#apidoc.element.rxjs.interval.interval)

#### [module rxjs.isArray](#apidoc.module.rxjs.isArray)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isArray ()](#apidoc.element.rxjs.isArray.isArray)

#### [module rxjs.isArrayLike](#apidoc.module.rxjs.isArrayLike)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isArrayLike (x)](#apidoc.element.rxjs.isArrayLike.isArrayLike)

#### [module rxjs.isDate](#apidoc.module.rxjs.isDate)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isDate (value)](#apidoc.element.rxjs.isDate.isDate)

#### [module rxjs.isEmpty](#apidoc.module.rxjs.isEmpty)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isEmpty ()](#apidoc.element.rxjs.isEmpty.isEmpty)

#### [module rxjs.isFunction](#apidoc.module.rxjs.isFunction)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isFunction (x)](#apidoc.element.rxjs.isFunction.isFunction)

#### [module rxjs.isNumeric](#apidoc.module.rxjs.isNumeric)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isNumeric (val)](#apidoc.element.rxjs.isNumeric.isNumeric)

#### [module rxjs.isObject](#apidoc.module.rxjs.isObject)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isObject (x)](#apidoc.element.rxjs.isObject.isObject)

#### [module rxjs.isPromise](#apidoc.module.rxjs.isPromise)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isPromise (value)](#apidoc.element.rxjs.isPromise.isPromise)

#### [module rxjs.isScheduler](#apidoc.module.rxjs.isScheduler)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>isScheduler (value)](#apidoc.element.rxjs.isScheduler.isScheduler)

#### [module rxjs.iterator](#apidoc.module.rxjs.iterator)
1.  [function <span class="apidocSignatureSpan">rxjs.iterator.</span>symbolIteratorPonyfill (root)](#apidoc.element.rxjs.iterator.symbolIteratorPonyfill)

#### [module rxjs.last](#apidoc.module.rxjs.last)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>last (predicate, resultSelector, defaultValue)](#apidoc.element.rxjs.last.last)

#### [module rxjs.let](#apidoc.module.rxjs.let)
1.  [function <span class="apidocSignatureSpan">rxjs.let.</span>letProto (func)](#apidoc.element.rxjs.let.letProto)

#### [module rxjs.map](#apidoc.module.rxjs.map)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>map (project, thisArg)](#apidoc.element.rxjs.map.map)
1.  [function <span class="apidocSignatureSpan">rxjs.map.</span>MapOperator (project, thisArg)](#apidoc.element.rxjs.map.MapOperator)

#### [module rxjs.mapTo](#apidoc.module.rxjs.mapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>mapTo (value)](#apidoc.element.rxjs.mapTo.mapTo)

#### [module rxjs.materialize](#apidoc.module.rxjs.materialize)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>materialize ()](#apidoc.element.rxjs.materialize.materialize)

#### [module rxjs.max](#apidoc.module.rxjs.max)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>max (comparer)](#apidoc.element.rxjs.max.max)

#### [module rxjs.merge](#apidoc.module.rxjs.merge)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>merge ()](#apidoc.element.rxjs.merge.merge)

#### [module rxjs.mergeAll](#apidoc.module.rxjs.mergeAll)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>mergeAll (concurrent)](#apidoc.element.rxjs.mergeAll.mergeAll)
1.  [function <span class="apidocSignatureSpan">rxjs.mergeAll.</span>MergeAllOperator (concurrent)](#apidoc.element.rxjs.mergeAll.MergeAllOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.mergeAll.</span>MergeAllSubscriber (destination, concurrent)](#apidoc.element.rxjs.mergeAll.MergeAllSubscriber)

#### [module rxjs.mergeMap](#apidoc.module.rxjs.mergeMap)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>mergeMap (project, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMap.mergeMap)
1.  [function <span class="apidocSignatureSpan">rxjs.mergeMap.</span>MergeMapOperator (project, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMap.MergeMapOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.mergeMap.</span>MergeMapSubscriber (destination, project, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMap.MergeMapSubscriber)

#### [module rxjs.mergeMapTo](#apidoc.module.rxjs.mergeMapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>mergeMapTo (innerObservable, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMapTo.mergeMapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.mergeMapTo.</span>MergeMapToOperator (ish, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMapTo.MergeMapToOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.mergeMapTo.</span>MergeMapToSubscriber (destination, ish, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMapTo.MergeMapToSubscriber)

#### [module rxjs.mergeScan](#apidoc.module.rxjs.mergeScan)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>mergeScan (accumulator, seed, concurrent)](#apidoc.element.rxjs.mergeScan.mergeScan)
1.  [function <span class="apidocSignatureSpan">rxjs.mergeScan.</span>MergeScanOperator (accumulator, seed, concurrent)](#apidoc.element.rxjs.mergeScan.MergeScanOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.mergeScan.</span>MergeScanSubscriber (destination, accumulator, acc, concurrent)](#apidoc.element.rxjs.mergeScan.MergeScanSubscriber)

#### [module rxjs.multicast](#apidoc.module.rxjs.multicast)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>multicast (subjectOrSubjectFactory, selector)](#apidoc.element.rxjs.multicast.multicast)
1.  [function <span class="apidocSignatureSpan">rxjs.multicast.</span>MulticastOperator (subjectFactory, selector)](#apidoc.element.rxjs.multicast.MulticastOperator)

#### [module rxjs.never](#apidoc.module.rxjs.never)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>never ()](#apidoc.element.rxjs.never.never)

#### [module rxjs.noop](#apidoc.module.rxjs.noop)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>noop ()](#apidoc.element.rxjs.noop.noop)

#### [module rxjs.not](#apidoc.module.rxjs.not)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>not (pred, thisArg)](#apidoc.element.rxjs.not.not)

#### [module rxjs.observeOn](#apidoc.module.rxjs.observeOn)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>observeOn (scheduler, delay)](#apidoc.element.rxjs.observeOn.observeOn)
1.  [function <span class="apidocSignatureSpan">rxjs.observeOn.</span>ObserveOnMessage (notification, destination)](#apidoc.element.rxjs.observeOn.ObserveOnMessage)
1.  [function <span class="apidocSignatureSpan">rxjs.observeOn.</span>ObserveOnOperator (scheduler, delay)](#apidoc.element.rxjs.observeOn.ObserveOnOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.observeOn.</span>ObserveOnSubscriber (destination, scheduler, delay)](#apidoc.element.rxjs.observeOn.ObserveOnSubscriber)

#### [module rxjs.of](#apidoc.module.rxjs.of)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>of ()](#apidoc.element.rxjs.of.of)

#### [module rxjs.onErrorResumeNext](#apidoc.module.rxjs.onErrorResumeNext)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>onErrorResumeNext ()](#apidoc.element.rxjs.onErrorResumeNext.onErrorResumeNext)
1.  [function <span class="apidocSignatureSpan">rxjs.onErrorResumeNext.</span>onErrorResumeNextStatic ()](#apidoc.element.rxjs.onErrorResumeNext.onErrorResumeNextStatic)

#### [module rxjs.pairs](#apidoc.module.rxjs.pairs)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>pairs (obj, scheduler)](#apidoc.element.rxjs.pairs.pairs)

#### [module rxjs.pairwise](#apidoc.module.rxjs.pairwise)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>pairwise ()](#apidoc.element.rxjs.pairwise.pairwise)

#### [module rxjs.partition](#apidoc.module.rxjs.partition)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>partition (predicate, thisArg)](#apidoc.element.rxjs.partition.partition)

#### [module rxjs.pluck](#apidoc.module.rxjs.pluck)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>pluck ()](#apidoc.element.rxjs.pluck.pluck)

#### [module rxjs.publish](#apidoc.module.rxjs.publish)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>publish (selector)](#apidoc.element.rxjs.publish.publish)

#### [module rxjs.publishBehavior](#apidoc.module.rxjs.publishBehavior)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>publishBehavior (value)](#apidoc.element.rxjs.publishBehavior.publishBehavior)

#### [module rxjs.publishLast](#apidoc.module.rxjs.publishLast)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>publishLast ()](#apidoc.element.rxjs.publishLast.publishLast)

#### [module rxjs.publishReplay](#apidoc.module.rxjs.publishReplay)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>publishReplay (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.publishReplay.publishReplay)

#### [module rxjs.race](#apidoc.module.rxjs.race)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>race ()](#apidoc.element.rxjs.race.race)
1.  [function <span class="apidocSignatureSpan">rxjs.race.</span>RaceOperator ()](#apidoc.element.rxjs.race.RaceOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.race.</span>RaceSubscriber (destination)](#apidoc.element.rxjs.race.RaceSubscriber)
1.  [function <span class="apidocSignatureSpan">rxjs.race.</span>raceStatic ()](#apidoc.element.rxjs.race.raceStatic)

#### [module rxjs.range](#apidoc.module.rxjs.range)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>range (start, count, scheduler)](#apidoc.element.rxjs.range.range)

#### [module rxjs.reduce](#apidoc.module.rxjs.reduce)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>reduce (accumulator, seed)](#apidoc.element.rxjs.reduce.reduce)
1.  [function <span class="apidocSignatureSpan">rxjs.reduce.</span>ReduceOperator (accumulator, seed, hasSeed)](#apidoc.element.rxjs.reduce.ReduceOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.reduce.</span>ReduceSubscriber (destination, accumulator, seed, hasSeed)](#apidoc.element.rxjs.reduce.ReduceSubscriber)

#### [module rxjs.repeat](#apidoc.module.rxjs.repeat)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>repeat (count)](#apidoc.element.rxjs.repeat.repeat)

#### [module rxjs.repeatWhen](#apidoc.module.rxjs.repeatWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>repeatWhen (notifier)](#apidoc.element.rxjs.repeatWhen.repeatWhen)

#### [module rxjs.retry](#apidoc.module.rxjs.retry)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>retry (count)](#apidoc.element.rxjs.retry.retry)

#### [module rxjs.retryWhen](#apidoc.module.rxjs.retryWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>retryWhen (notifier)](#apidoc.element.rxjs.retryWhen.retryWhen)

#### [module rxjs.sample](#apidoc.module.rxjs.sample)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>sample (notifier)](#apidoc.element.rxjs.sample.sample)

#### [module rxjs.sampleTime](#apidoc.module.rxjs.sampleTime)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>sampleTime (period, scheduler)](#apidoc.element.rxjs.sampleTime.sampleTime)

#### [module rxjs.scan](#apidoc.module.rxjs.scan)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>scan (accumulator, seed)](#apidoc.element.rxjs.scan.scan)

#### [module rxjs.sequenceEqual](#apidoc.module.rxjs.sequenceEqual)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>sequenceEqual (compareTo, comparor)](#apidoc.element.rxjs.sequenceEqual.sequenceEqual)
1.  [function <span class="apidocSignatureSpan">rxjs.sequenceEqual.</span>SequenceEqualOperator (compareTo, comparor)](#apidoc.element.rxjs.sequenceEqual.SequenceEqualOperator)
1.  [function <span class="apidocSignatureSpan">rxjs.sequenceEqual.</span>SequenceEqualSubscriber (destination, compareTo, comparor)](#apidoc.element.rxjs.sequenceEqual.SequenceEqualSubscriber)

#### [module rxjs.share](#apidoc.module.rxjs.share)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>share ()](#apidoc.element.rxjs.share.share)

#### [module rxjs.single](#apidoc.module.rxjs.single)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>single (predicate)](#apidoc.element.rxjs.single.single)

#### [module rxjs.skip](#apidoc.module.rxjs.skip)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>skip (count)](#apidoc.element.rxjs.skip.skip)

#### [module rxjs.skipUntil](#apidoc.module.rxjs.skipUntil)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>skipUntil (notifier)](#apidoc.element.rxjs.skipUntil.skipUntil)

#### [module rxjs.skipWhile](#apidoc.module.rxjs.skipWhile)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>skipWhile (predicate)](#apidoc.element.rxjs.skipWhile.skipWhile)

#### [module rxjs.startWith](#apidoc.module.rxjs.startWith)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>startWith ()](#apidoc.element.rxjs.startWith.startWith)

#### [module rxjs.subscribeOn](#apidoc.module.rxjs.subscribeOn)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>subscribeOn (scheduler, delay)](#apidoc.element.rxjs.subscribeOn.subscribeOn)

#### [module rxjs.subscribeToResult](#apidoc.module.rxjs.subscribeToResult)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>subscribeToResult (outerSubscriber, result, outerValue, outerIndex)](#apidoc.element.rxjs.subscribeToResult.subscribeToResult)

#### [module rxjs.switch](#apidoc.module.rxjs.switch)
1.  [function <span class="apidocSignatureSpan">rxjs.switch.</span>_switch ()](#apidoc.element.rxjs.switch._switch)

#### [module rxjs.switchMap](#apidoc.module.rxjs.switchMap)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>switchMap (project, resultSelector)](#apidoc.element.rxjs.switchMap.switchMap)

#### [module rxjs.switchMapTo](#apidoc.module.rxjs.switchMapTo)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>switchMapTo (innerObservable, resultSelector)](#apidoc.element.rxjs.switchMapTo.switchMapTo)

#### [module rxjs.take](#apidoc.module.rxjs.take)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>take (count)](#apidoc.element.rxjs.take.take)

#### [module rxjs.takeLast](#apidoc.module.rxjs.takeLast)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>takeLast (count)](#apidoc.element.rxjs.takeLast.takeLast)

#### [module rxjs.takeUntil](#apidoc.module.rxjs.takeUntil)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>takeUntil (notifier)](#apidoc.element.rxjs.takeUntil.takeUntil)

#### [module rxjs.takeWhile](#apidoc.module.rxjs.takeWhile)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>takeWhile (predicate)](#apidoc.element.rxjs.takeWhile.takeWhile)

#### [module rxjs.throttle](#apidoc.module.rxjs.throttle)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>throttle (durationSelector)](#apidoc.element.rxjs.throttle.throttle)

#### [module rxjs.throttleTime](#apidoc.module.rxjs.throttleTime)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>throttleTime (duration, scheduler)](#apidoc.element.rxjs.throttleTime.throttleTime)

#### [module rxjs.throw](#apidoc.module.rxjs.throw)
1.  [function <span class="apidocSignatureSpan">rxjs.throw.</span>_throw (error, scheduler)](#apidoc.element.rxjs.throw._throw)

#### [module rxjs.timeInterval](#apidoc.module.rxjs.timeInterval)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>timeInterval (scheduler)](#apidoc.element.rxjs.timeInterval.timeInterval)
1.  [function <span class="apidocSignatureSpan">rxjs.timeInterval.</span>TimeInterval (value, interval)](#apidoc.element.rxjs.timeInterval.TimeInterval)

#### [module rxjs.timeout](#apidoc.module.rxjs.timeout)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>timeout (due, scheduler)](#apidoc.element.rxjs.timeout.timeout)

#### [module rxjs.timeoutWith](#apidoc.module.rxjs.timeoutWith)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>timeoutWith (due, withObservable, scheduler)](#apidoc.element.rxjs.timeoutWith.timeoutWith)

#### [module rxjs.timer](#apidoc.module.rxjs.timer)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>timer (initialDelay, period, scheduler)](#apidoc.element.rxjs.timer.timer)

#### [module rxjs.timestamp](#apidoc.module.rxjs.timestamp)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>timestamp (scheduler)](#apidoc.element.rxjs.timestamp.timestamp)
1.  [function <span class="apidocSignatureSpan">rxjs.timestamp.</span>Timestamp (value, timestamp)](#apidoc.element.rxjs.timestamp.Timestamp)

#### [module rxjs.toArray](#apidoc.module.rxjs.toArray)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>toArray ()](#apidoc.element.rxjs.toArray.toArray)

#### [module rxjs.toPromise](#apidoc.module.rxjs.toPromise)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>toPromise (PromiseCtor)](#apidoc.element.rxjs.toPromise.toPromise)

#### [module rxjs.toSubscriber](#apidoc.module.rxjs.toSubscriber)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>toSubscriber (nextOrObserver, error, complete)](#apidoc.element.rxjs.toSubscriber.toSubscriber)

#### [module rxjs.tryCatch](#apidoc.module.rxjs.tryCatch)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>tryCatch (fn)](#apidoc.element.rxjs.tryCatch.tryCatch)

#### [module rxjs.using](#apidoc.module.rxjs.using)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>using (resourceFactory, observableFactory)](#apidoc.element.rxjs.using.using)

#### [module rxjs.window](#apidoc.module.rxjs.window)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>window (windowBoundaries)](#apidoc.element.rxjs.window.window)

#### [module rxjs.windowCount](#apidoc.module.rxjs.windowCount)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>windowCount (windowSize, startWindowEvery)](#apidoc.element.rxjs.windowCount.windowCount)

#### [module rxjs.windowTime](#apidoc.module.rxjs.windowTime)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>windowTime (windowTimeSpan)](#apidoc.element.rxjs.windowTime.windowTime)

#### [module rxjs.windowToggle](#apidoc.module.rxjs.windowToggle)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>windowToggle (openings, closingSelector)](#apidoc.element.rxjs.windowToggle.windowToggle)

#### [module rxjs.windowWhen](#apidoc.module.rxjs.windowWhen)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>windowWhen (closingSelector)](#apidoc.element.rxjs.windowWhen.windowWhen)

#### [module rxjs.withLatestFrom](#apidoc.module.rxjs.withLatestFrom)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>withLatestFrom ()](#apidoc.element.rxjs.withLatestFrom.withLatestFrom)

#### [module rxjs.zip](#apidoc.module.rxjs.zip)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>zip ()](#apidoc.element.rxjs.zip.zip)

#### [module rxjs.zipAll](#apidoc.module.rxjs.zipAll)
1.  [function <span class="apidocSignatureSpan">rxjs.</span>zipAll (project)](#apidoc.element.rxjs.zipAll.zipAll)



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
...
    BoundCallbackObservable.prototype._subscribe = function (subscriber) {
var callbackFunc = this.callbackFunc;
var args = this.args;
var scheduler = this.scheduler;
var subject = this.subject;
if (!scheduler) {
    if (!subject) {
        subject = this.subject = new AsyncSubject_1.AsyncSubject();
        var handler = function handlerFn() {
            var innerArgs = [];
            for (var _i = 0; _i < arguments.length; _i++) {
                innerArgs[_i - 0] = arguments[_i];
            }
            var source = handlerFn.source;
            var selector = source.selector, subject = source.subject;
...
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
...
/**
 * @param value
 * @return {ConnectableObservable<T>}
 * @method publishBehavior
 * @owner Observable
 */
function publishBehavior(value) {
    return multicast_1.multicast.call(this, new BehaviorSubject_1.BehaviorSubject(value));
}
exports.publishBehavior = publishBehavior;
//# sourceMappingURL=publishBehavior.js.map
...
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
...
* 'error'. Such Observable is the output of a 'materialize' operation. Those
* notifications are then unwrapped using the metadata they contain, and emitted
* as 'next', 'error', and 'complete' on the output Observable.
*
* Use this operator in conjunction with {@link materialize}.
*
* @example <caption>Convert an Observable of Notifications to an actual Observable</caption>
* var notifA = new Rx.Notification('N', 'A');
* var notifB = new Rx.Notification('N', 'B');
* var notifE = new Rx.Notification('E', void 0,
*   new TypeError('x.toUpperCase is not a function')
* );
* var materialized = Rx.Observable.of(notifA, notifB, notifE);
* var upperCase = materialized.dematerialize();
* upperCase.subscribe(x => console.log(x), e => console.error(e));
...
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
...
    return subscription;
};
BehaviorSubject.prototype.getValue = function () {
    if (this.hasError) {
        throw this.thrownError;
    }
    else if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    else {
        return this._value;
    }
};
BehaviorSubject.prototype.next = function (value) {
    _super.prototype.next.call(this, this._value = value);
...
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
...
    }
    else {
        this.observers.push(subscriber);
        return new SubjectSubscription_1.SubjectSubscription(this, subscriber);
    }
};
Subject.prototype.asObservable = function () {
    var observable = new Observable_1.Observable();
    observable.source = this;
    return observable;
};
Subject.create = function (destination, source) {
    return new AnonymousSubject(destination, source);
};
return Subject;
...
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
...
 * @return {ConnectableObservable<T>}
 * @method publishReplay
 * @owner Observable
 */
function publishReplay(bufferSize, windowTime, scheduler) {
    if (bufferSize === void 0) { bufferSize = Number.POSITIVE_INFINITY; }
    if (windowTime === void 0) { windowTime = Number.POSITIVE_INFINITY; }
    return multicast_1.multicast.call(this, new ReplaySubject_1.ReplaySubject(bufferSize, windowTime, scheduler));
}
exports.publishReplay = publishReplay;
//# sourceMappingURL=publishReplay.js.map
...
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
...
        this.error(err);
    }
}
else {
    element = value;
}
if (!group) {
    group = this.subjectSelector ? this.subjectSelector() : new Subject_1.Subject();
    groups.set(key, group);
    var groupedObservable = new GroupedObservable(key, group, this);
    this.destination.next(groupedObservable);
    if (this.durationSelector) {
        var duration = void 0;
        try {
            duration = this.durationSelector(new GroupedObservable(key, group));
...
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
...
 * @ignore
 * @extends {Ignored}
 */
var DoSubscriber = (function (_super) {
__extends(DoSubscriber, _super);
function DoSubscriber(destination, nextOrObserver, error, complete) {
    _super.call(this, destination);
    var safeSubscriber = new Subscriber_1.Subscriber(nextOrObserver, error, complete);
    safeSubscriber.syncErrorThrowable = true;
    this.add(safeSubscriber);
    this.safeSubscriber = safeSubscriber;
}
DoSubscriber.prototype._next = function (value) {
    var safeSubscriber = this.safeSubscriber;
    safeSubscriber.next(value);
...
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
...
        this._subject = this.subjectFactory();
    }
    return this._subject;
};
ConnectableObservable.prototype.connect = function () {
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
...
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
...
 * @method timeout
 * @owner Observable
 */
function timeout(due, scheduler) {
if (scheduler === void 0) { scheduler = async_1.async; }
var absoluteTimeout = isDate_1.isDate(due);
var waitFor = absoluteTimeout ? (+due - scheduler.now()) : Math.abs(due);
return this.lift(new TimeoutOperator(waitFor, absoluteTimeout, scheduler, new TimeoutError_1.TimeoutError()));
}
exports.timeout = timeout;
var TimeoutOperator = (function () {
function TimeoutOperator(waitFor, absoluteTimeout, scheduler, errorInstance) {
    this.waitFor = waitFor;
    this.absoluteTimeout = absoluteTimeout;
    this.scheduler = scheduler;
...
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
...
                        errors.push(err);
                    }
                }
            }
        }
    }
    if (hasErrors) {
        throw new UnsubscriptionError_1.UnsubscriptionError(errors);
    }
};
/**
 * Adds a tear down to be called during the unsubscribe() of this
 * Subscription.
 *
 * If the tear down being added is a subscription that is already
...
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



# <a name="apidoc.module.rxjs.Action"></a>[module rxjs.Action](#apidoc.module.rxjs.Action)

#### <a name="apidoc.element.rxjs.Action.Action"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Action (scheduler, work)](#apidoc.element.rxjs.Action.Action)
- description and source-code
```javascript
function Action(scheduler, work) {
    _super.call(this);
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



# <a name="apidoc.module.rxjs.AnimationFrame"></a>[module rxjs.AnimationFrame](#apidoc.module.rxjs.AnimationFrame)

#### <a name="apidoc.element.rxjs.AnimationFrame.RequestAnimationFrameDefinition"></a>[function <span class="apidocSignatureSpan">rxjs.AnimationFrame.</span>RequestAnimationFrameDefinition (root)](#apidoc.element.rxjs.AnimationFrame.RequestAnimationFrameDefinition)
- description and source-code
```javascript
function RequestAnimationFrameDefinition(root) {
    if (root.requestAnimationFrame) {
        this.cancelAnimationFrame = root.cancelAnimationFrame.bind(root);
        this.requestAnimationFrame = root.requestAnimationFrame.bind(root);
    }
    else if (root.mozRequestAnimationFrame) {
        this.cancelAnimationFrame = root.mozCancelAnimationFrame.bind(root);
        this.requestAnimationFrame = root.mozRequestAnimationFrame.bind(root);
    }
    else if (root.webkitRequestAnimationFrame) {
        this.cancelAnimationFrame = root.webkitCancelAnimationFrame.bind(root);
        this.requestAnimationFrame = root.webkitRequestAnimationFrame.bind(root);
    }
    else if (root.msRequestAnimationFrame) {
        this.cancelAnimationFrame = root.msCancelAnimationFrame.bind(root);
        this.requestAnimationFrame = root.msRequestAnimationFrame.bind(root);
    }
    else if (root.oRequestAnimationFrame) {
        this.cancelAnimationFrame = root.oCancelAnimationFrame.bind(root);
        this.requestAnimationFrame = root.oRequestAnimationFrame.bind(root);
    }
    else {
        this.cancelAnimationFrame = root.clearTimeout.bind(root);
        this.requestAnimationFrame = function (cb) { return root.setTimeout(cb, 1000 / 60); };
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AnimationFrameAction"></a>[module rxjs.AnimationFrameAction](#apidoc.module.rxjs.AnimationFrameAction)

#### <a name="apidoc.element.rxjs.AnimationFrameAction.AnimationFrameAction"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AnimationFrameAction (scheduler, work)](#apidoc.element.rxjs.AnimationFrameAction.AnimationFrameAction)
- description and source-code
```javascript
function AnimationFrameAction(scheduler, work) {
    _super.call(this, scheduler, work);
    this.scheduler = scheduler;
    this.work = work;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AnimationFrameScheduler"></a>[module rxjs.AnimationFrameScheduler](#apidoc.module.rxjs.AnimationFrameScheduler)

#### <a name="apidoc.element.rxjs.AnimationFrameScheduler.AnimationFrameScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AnimationFrameScheduler ()](#apidoc.element.rxjs.AnimationFrameScheduler.AnimationFrameScheduler)
- description and source-code
```javascript
function AnimationFrameScheduler() {
    _super.apply(this, arguments);
}
```
- example usage
```shell
...
 * // You will see .some-div element growing in height
 *
 *
 * @static true
 * @name animationFrame
 * @owner Scheduler
 */
exports.animationFrame = new AnimationFrameScheduler_1.AnimationFrameScheduler(AnimationFrameAction_1.AnimationFrameAction);
//# sourceMappingURL=animationFrame.js.map
...
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
...
            throw sink.syncErrorValue;
        }
    }
    return sink;
};
Observable.prototype._trySubscribe = function (sink) {
    try {
        return this._subscribe(sink);
    }
    catch (err) {
        sink.syncErrorThrown = true;
        sink.syncErrorValue = err;
        sink.error(err);
    }
};
...
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



# <a name="apidoc.module.rxjs.ArrayLikeObservable"></a>[module rxjs.ArrayLikeObservable](#apidoc.module.rxjs.ArrayLikeObservable)

#### <a name="apidoc.element.rxjs.ArrayLikeObservable.ArrayLikeObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ArrayLikeObservable (arrayLike, scheduler)](#apidoc.element.rxjs.ArrayLikeObservable.ArrayLikeObservable)
- description and source-code
```javascript
function ArrayLikeObservable(arrayLike, scheduler) {
    _super.call(this);
    this.arrayLike = arrayLike;
    this.scheduler = scheduler;
    if (!scheduler && arrayLike.length === 1) {
        this._isScalar = true;
        this.value = arrayLike[0];
    }
}
```
- example usage
```shell
...
        else if (isPromise_1.isPromise(ish)) {
            return new PromiseObservable_1.PromiseObservable(ish, scheduler);
        }
        else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
            return new IteratorObservable_1.IteratorObservable(ish, scheduler);
        }
        else if (isArrayLike_1.isArrayLike(ish)) {
            return new ArrayLikeObservable_1.ArrayLikeObservable(ish, scheduler);
        }
    }
    throw new TypeError((ish !== null && typeof ish || ish) + ' is not observable');
};
FromObservable.prototype._subscribe = function (subscriber) {
    var ish = this.ish;
    var scheduler = this.scheduler;
...
```



# <a name="apidoc.module.rxjs.ArrayObservable"></a>[module rxjs.ArrayObservable](#apidoc.module.rxjs.ArrayObservable)

#### <a name="apidoc.element.rxjs.ArrayObservable.ArrayObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ArrayObservable (array, scheduler)](#apidoc.element.rxjs.ArrayObservable.ArrayObservable)
- description and source-code
```javascript
function ArrayObservable(array, scheduler) {
    _super.call(this);
    this.array = array;
    this.scheduler = scheduler;
    if (!scheduler && array.length === 1) {
        this._isScalar = true;
        this.value = array[0];
    }
}
```
- example usage
```shell
...
if (typeof ish[observable_1.$$observable] === 'function') {
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
else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
    return new IteratorObservable_1.IteratorObservable(ish, scheduler);
}
...
```



# <a name="apidoc.module.rxjs.AsapAction"></a>[module rxjs.AsapAction](#apidoc.module.rxjs.AsapAction)

#### <a name="apidoc.element.rxjs.AsapAction.AsapAction"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AsapAction (scheduler, work)](#apidoc.element.rxjs.AsapAction.AsapAction)
- description and source-code
```javascript
function AsapAction(scheduler, work) {
    _super.call(this, scheduler, work);
    this.scheduler = scheduler;
    this.work = work;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AsapScheduler"></a>[module rxjs.AsapScheduler](#apidoc.module.rxjs.AsapScheduler)

#### <a name="apidoc.element.rxjs.AsapScheduler.AsapScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AsapScheduler ()](#apidoc.element.rxjs.AsapScheduler.AsapScheduler)
- description and source-code
```javascript
function AsapScheduler() {
    _super.apply(this, arguments);
}
```
- example usage
```shell
...
 * // "async"
 * // ... but 'asap' goes first!
 *
 * @static true
 * @name asap
 * @owner Scheduler
 */
exports.asap = new AsapScheduler_1.AsapScheduler(AsapAction_1.AsapAction);
//# sourceMappingURL=asap.js.map
...
```



# <a name="apidoc.module.rxjs.AsyncAction"></a>[module rxjs.AsyncAction](#apidoc.module.rxjs.AsyncAction)

#### <a name="apidoc.element.rxjs.AsyncAction.AsyncAction"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AsyncAction (scheduler, work)](#apidoc.element.rxjs.AsyncAction.AsyncAction)
- description and source-code
```javascript
function AsyncAction(scheduler, work) {
    _super.call(this, scheduler, work);
    this.scheduler = scheduler;
    this.work = work;
    this.pending = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.AsyncScheduler"></a>[module rxjs.AsyncScheduler](#apidoc.module.rxjs.AsyncScheduler)

#### <a name="apidoc.element.rxjs.AsyncScheduler.AsyncScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>AsyncScheduler ()](#apidoc.element.rxjs.AsyncScheduler.AsyncScheduler)
- description and source-code
```javascript
function AsyncScheduler() {
    _super.apply(this, arguments);
    this.actions = [];
<span class="apidocCodeCommentSpan">    /**
     * A flag to indicate whether the Scheduler is currently executing a batch of
     * queued actions.
     * @type {boolean}
     */
</span>    this.active = false;
    /**
     * An internal ID used to track the latest asynchronous task such as those
     * coming from 'setTimeout', 'setInterval', 'requestAnimationFrame', and
     * others.
     * @type {any}
     */
    this.scheduled = undefined;
}
```
- example usage
```shell
...
 * // 2 after 5s
 * // 3 after 6s
 *
 * @static true
 * @name async
 * @owner Scheduler
 */
exports.async = new AsyncScheduler_1.AsyncScheduler(AsyncAction_1.AsyncAction);
//# sourceMappingURL=async.js.map
...
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
...
    BoundCallbackObservable.prototype._subscribe = function (subscriber) {
var callbackFunc = this.callbackFunc;
var args = this.args;
var scheduler = this.scheduler;
var subject = this.subject;
if (!scheduler) {
    if (!subject) {
        subject = this.subject = new AsyncSubject_1.AsyncSubject();
        var handler = function handlerFn() {
            var innerArgs = [];
            for (var _i = 0; _i < arguments.length; _i++) {
                innerArgs[_i - 0] = arguments[_i];
            }
            var source = handlerFn.source;
            var selector = source.selector, subject = source.subject;
...
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
...
            throw sink.syncErrorValue;
        }
    }
    return sink;
};
Observable.prototype._trySubscribe = function (sink) {
    try {
        return this._subscribe(sink);
    }
    catch (err) {
        sink.syncErrorThrown = true;
        sink.syncErrorValue = err;
        sink.error(err);
    }
};
...
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
...
/**
 * @param value
 * @return {ConnectableObservable<T>}
 * @method publishBehavior
 * @owner Observable
 */
function publishBehavior(value) {
    return multicast_1.multicast.call(this, new BehaviorSubject_1.BehaviorSubject(value));
}
exports.publishBehavior = publishBehavior;
//# sourceMappingURL=publishBehavior.js.map
...
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
...
            throw sink.syncErrorValue;
        }
    }
    return sink;
};
Observable.prototype._trySubscribe = function (sink) {
    try {
        return this._subscribe(sink);
    }
    catch (err) {
        sink.syncErrorThrown = true;
        sink.syncErrorValue = err;
        sink.error(err);
    }
};
...
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
...
__extends(BehaviorSubject, _super);
function BehaviorSubject(_value) {
    _super.call(this);
    this._value = _value;
}
Object.defineProperty(BehaviorSubject.prototype, "value", {
    get: function () {
        return this.getValue();
    },
    enumerable: true,
    configurable: true
});
BehaviorSubject.prototype._subscribe = function (subscriber) {
    var subscription = _super.prototype._subscribe.call(this, subscriber);
    if (subscription && !subscription.closed) {
...
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



# <a name="apidoc.module.rxjs.BoundCallbackObservable"></a>[module rxjs.BoundCallbackObservable](#apidoc.module.rxjs.BoundCallbackObservable)

#### <a name="apidoc.element.rxjs.BoundCallbackObservable.BoundCallbackObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>BoundCallbackObservable (callbackFunc, selector, args, context, scheduler)](#apidoc.element.rxjs.BoundCallbackObservable.BoundCallbackObservable)
- description and source-code
```javascript
function BoundCallbackObservable(callbackFunc, selector, args, context, scheduler) {
    _super.call(this);
    this.callbackFunc = callbackFunc;
    this.selector = selector;
    this.args = args;
    this.context = context;
    this.scheduler = scheduler;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.BoundNodeCallbackObservable"></a>[module rxjs.BoundNodeCallbackObservable](#apidoc.module.rxjs.BoundNodeCallbackObservable)

#### <a name="apidoc.element.rxjs.BoundNodeCallbackObservable.BoundNodeCallbackObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>BoundNodeCallbackObservable (callbackFunc, selector, args, context, scheduler)](#apidoc.element.rxjs.BoundNodeCallbackObservable.BoundNodeCallbackObservable)
- description and source-code
```javascript
function BoundNodeCallbackObservable(callbackFunc, selector, args, context, scheduler) {
    _super.call(this);
    this.callbackFunc = callbackFunc;
    this.selector = selector;
    this.args = args;
    this.context = context;
    this.scheduler = scheduler;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.ColdObservable"></a>[module rxjs.ColdObservable](#apidoc.module.rxjs.ColdObservable)

#### <a name="apidoc.element.rxjs.ColdObservable.ColdObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ColdObservable (messages, scheduler)](#apidoc.element.rxjs.ColdObservable.ColdObservable)
- description and source-code
```javascript
function ColdObservable(messages, scheduler) {
    _super.call(this, function (subscriber) {
        var observable = this;
        var index = observable.logSubscribedFrame();
        subscriber.add(new Subscription_1.Subscription(function () {
            observable.logUnsubscribedFrame(index);
        }));
        observable.scheduleMessages(subscriber);
        return subscriber;
    });
    this.messages = messages;
    this.subscriptions = [];
    this.scheduler = scheduler;
}
```
- example usage
```shell
...
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
};
TestScheduler.prototype.createHotObservable = function (marbles, values, error) {
    if (marbles.indexOf('!') !== -1) {
        throw new Error('hot observable cannot have unsubscription marker "!"');
    }
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
...
* provides convenient error handling and probably is a better choice.
* 'bindCallback' will treat such functions without any difference and error parameter
* (whether passed or not) will always be interpreted as regular callback argument.
*
*
* @example <caption>Convert jQuery's getJSON to an Observable API</caption>
* // Suppose we have jQuery.getJSON('/my/url', callback)
* var getJSONAsObservable = Rx.Observable.bindCallback(jQuery.getJSON);
* var result = getJSONAsObservable('/my/url');
* result.subscribe(x => console.log(x), e => console.error(e));
*
*
* @example <caption>Receive array of arguments passed to callback</caption>
* someFunction((a, b, c) => {
*   console.log(a); // 5
...
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
...
*
* Note that even if error parameter is technically present in callback, but its value
* is falsy, it still won't appear in array emitted by Observable or in selector function.
*
*
* @example <caption>Read a file from the filesystem and get the data as an Observable</caption>
* import * as fs from 'fs';
* var readFileAsObservable = Rx.Observable.bindNodeCallback(fs.readFile);
* var result = readFileAsObservable('./roadNames.txt', 'utf8');
* result.subscribe(x => console.log(x), e => console.error(e));
*
*
* @example <caption>Use on function calling callback with multiple arguments</caption>
* someFunction((err, a, b) => {
*   console.log(err); // null
...
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
...
* of values, but values themselves. That means default 'project' can be imagined
* as function that takes all its arguments and puts them into an array.
*
*
* @example <caption>Combine two timer Observables</caption>
* const firstTimer = Rx.Observable.timer(0, 1000); // emit 0, 1, 2... after every second, starting from now
* const secondTimer = Rx.Observable.timer(500, 1000); // emit 0, 1, 2... after every second, starting 0,5s from now
* const combinedTimers = Rx.Observable.combineLatest(firstTimer, secondTimer);
* combinedTimers.subscribe(value => console.log(value));
* // Logs
* // [0, 0] after 0.5s
* // [1, 0] after 1s
* // [1, 1] after 1.5s
* // [2, 1] after 2s
*
...
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
...
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
...
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
...
* an Observer subscribes to it, and then it generates an Observable,
* typically with an Observable factory function. It does this afresh for each
* subscriber, so although each subscriber may think it is subscribing to the
* same Observable, in fact each subscriber gets its own individual
* Observable.
*
* @example <caption>Subscribe to either an Observable of clicks or an Observable of interval, at random</caption>
* var clicksOrInterval = Rx.Observable.defer(function () {
*   if (Math.random() > 0.5) {
*     return Rx.Observable.fromEvent(document, 'click');
*   } else {
*     return Rx.Observable.interval(1000);
*   }
* });
* clicksOrInterval.subscribe(x => console.log(x));
...
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
...
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
};
/**
 * A shortcut to create a Notification instance of the type 'next' from a
 * given value.
 * @param {T} value The 'next' value.
...
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
        if (typeof ish[observable_1.$$observable] === 'function') {
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
        else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
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
...
* object into an Observable that emits the items in that promise or array or
* iterable. A String, in this context, is treated as an array of characters.
* Observable-like objects (contains a function named with the ES2015 Symbol
* for Observable) can also be converted through this operator.
*
* @example <caption>Converts an array to an Observable</caption>
* var array = [10, 20, 30];
* var result = Rx.Observable.from(array);
* result.subscribe(x => console.log(x));
*
* // Results in the following:
* // 10 20 30
*
* @example <caption>Convert an infinite iterable (from a generator) to an Observable</caption>
* function* generateDoubles(seed) {
...
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
...
* subscriber, so although each subscriber may think it is subscribing to the
* same Observable, in fact each subscriber gets its own individual
* Observable.
*
* @example <caption>Subscribe to either an Observable of clicks or an Observable of interval, at random</caption>
* var clicksOrInterval = Rx.Observable.defer(function () {
*   if (Math.random() > 0.5) {
*     return Rx.Observable.fromEvent(document, 'click');
*   } else {
*     return Rx.Observable.interval(1000);
*   }
* });
* clicksOrInterval.subscribe(x => console.log(x));
*
* // Results in the following behavior:
...
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
...
*   document.addEventListener('click', handler);
* }
*
* function removeClickHandler(handler) {
*   document.removeEventListener('click', handler);
* }
*
* var clicks = Rx.Observable.fromEventPattern(
*   addClickHandler,
*   removeClickHandler
* );
* clicks.subscribe(x => console.log(x));
*
* @see {@link from}
* @see {@link fromEvent}
...
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
...
*
* Converts an ES2015 Promise or a Promises/A+ spec compliant Promise to an
* Observable. If the Promise resolves with a value, the output Observable
* emits that resolved value as a 'next', and then completes. If the Promise
* is rejected, then the output Observable emits the corresponding Error.
*
* @example <caption>Convert the Promise returned by Fetch to an Observable</caption>
* var result = Rx.Observable.fromPromise(fetch('http://myserver.com/'));
* result.subscribe(x => console.log(x), e => console.error(e));
*
* @see {@link bindCallback}
* @see {@link from}
*
* @param {Promise<T>} promise The promise to be converted.
* @param {Scheduler} [scheduler] An optional IScheduler to use for scheduling
...
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
...
* By default, it uses a 'null' IScheduler, which means the 'next'
* notifications are sent synchronously, although with a different IScheduler
* it is possible to determine when those notifications will be delivered.
*
* @example <caption>Emit 10, 20, 30, then 'a', 'b', 'c', then start ticking every second.</caption>
* var numbers = Rx.Observable.of(10, 20, 30);
* var letters = Rx.Observable.of('a', 'b', 'c');
* var interval = Rx.Observable.interval(1000);
* var result = numbers.concat(letters).concat(interval);
* result.subscribe(x => console.log(x));
*
* @see {@link create}
* @see {@link empty}
* @see {@link never}
* @see {@link throw}
...
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
...
* subscription from being disposed automatically. Subscriptions need to be
* manually disposed.
*
* @example <caption>Emit the number 7, then never emit anything else (not even complete).</caption>
* function info() {
*   console.log('Will not be called');
* }
* var result = Rx.Observable.never().startWith(7);
* result.subscribe(x => console.log(x), info, info);
*
* @see {@link create}
* @see {@link empty}
* @see {@link of}
* @see {@link throw}
*
...
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
...
* @example <caption>Converts a javascript object to an Observable</caption>
* var obj = {
*   foo: 42,
*   bar: 56,
*   baz: 78
* };
*
* var source = Rx.Observable.pairs(obj);
*
* var subscription = source.subscribe(
*   function (x) {
*     console.log('Next: %s', x);
*   },
*   function (err) {
*     console.log('Error: %s', err);
...
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
...
// connection Subscription on the shared ConnectableObservable. In cases
// where the ConnectableObservable source synchronously emits values, and
// the RefCountSubscriber's downstream Observers synchronously unsubscribe,
// execution continues to here before the RefCountOperator has a chance to
// supply the RefCountSubscriber with the shared connection Subscription.
// For example:
// '''
// Observable.range(0, 10)
//   .publish()
//   .refCount()
//   .take(5)
//   .subscribe();
// '''
// In order to account for this case, RefCountSubscriber should only dispose
// the ConnectableObservable's shared connection Subscription if the
...
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
...
 */
Notification.prototype.toObservable = function () {
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
};
/**
 * A shortcut to create a Notification instance of the type 'next' from a
...
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
...
* 'initialDelay'. The initial delay may be a {@link Date}. By default, this
* operator uses the 'async' IScheduler to provide a notion of time, but you
* may pass any IScheduler to it. If 'period' is not specified, the output
* Observable emits only one value, '0'. Otherwise, it emits an infinite
* sequence.
*
* @example <caption>Emits ascending numbers, one every second (1000ms), starting after 3 seconds</caption>
* var numbers = Rx.Observable.timer(3000, 1000);
* numbers.subscribe(x => console.log(x));
*
* @example <caption>Emits one number after five seconds</caption>
* var numbers = Rx.Observable.timer(5000);
* numbers.subscribe(x => console.log(x));
*
* @see {@link interval}
...
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
...
            group.complete();
        });
        groups.clear();
    }
    this.destination.complete();
};
GroupBySubscriber.prototype.removeGroup = function (key) {
    this.groups.delete(key);
};
GroupBySubscriber.prototype.unsubscribe = function () {
    if (!this.closed) {
        this.attemptedToUnsubscribe = true;
        if (this.count === 0) {
            _super.prototype.unsubscribe.call(this);
        }
...
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
...
    this._group(value, key);
};
GroupBySubscriber.prototype._group = function (value, key) {
    var groups = this.groups;
    if (!groups) {
        groups = this.groups = typeof key === 'string' ? new FastMap_1.FastMap() : new Map_1.Map();
    }
    var group = groups.get(key);
    var element;
    if (this.elementSelector) {
        try {
            element = this.elementSelector(value);
        }
        catch (err) {
            this.error(err);
...
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
...
* optional error parameter signaling whether call failed or not), {@link bindNodeCallback}
* provides convenient error handling and probably is a better choice.
* 'bindCallback' will treat such functions without any difference and error parameter
* (whether passed or not) will always be interpreted as regular callback argument.
*
*
* @example <caption>Convert jQuery's getJSON to an Observable API</caption>
* // Suppose we have jQuery.getJSON('/my/url', callback)
* var getJSONAsObservable = Rx.Observable.bindCallback(jQuery.getJSON);
* var result = getJSONAsObservable('/my/url');
* result.subscribe(x => console.log(x), e => console.error(e));
*
*
* @example <caption>Receive array of arguments passed to callback</caption>
* someFunction((a, b, c) => {
...
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
...
            throw sink.syncErrorValue;
        }
    }
    return sink;
};
Observable.prototype._trySubscribe = function (sink) {
    try {
        return this._subscribe(sink);
    }
    catch (err) {
        sink.syncErrorThrown = true;
        sink.syncErrorValue = err;
        sink.error(err);
    }
};
...
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
...
}
RefCountOperator.prototype.call = function (subscriber, source) {
    var connectable = this.connectable;
    connectable._refCount++;
    var refCounter = new RefCountSubscriber(subscriber, connectable);
    var subscription = source.subscribe(refCounter);
    if (!refCounter.closed) {
        refCounter.connection = connectable.connect();
    }
    return subscription;
};
return RefCountOperator;
}());
var RefCountSubscriber = (function (_super) {
__extends(RefCountSubscriber, _super);
...
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
...
function ConnectableObservable(source, subjectFactory) {
    _super.call(this);
    this.source = source;
    this.subjectFactory = subjectFactory;
    this._refCount = 0;
}
ConnectableObservable.prototype._subscribe = function (subscriber) {
    return this.getSubject().subscribe(subscriber);
};
ConnectableObservable.prototype.getSubject = function () {
    var subject = this._subject;
    if (!subject || subject.isStopped) {
        this._subject = this.subjectFactory();
    }
    return this._subject;
...
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
...
// the RefCountSubscriber's downstream Observers synchronously unsubscribe,
// execution continues to here before the RefCountOperator has a chance to
// supply the RefCountSubscriber with the shared connection Subscription.
// For example:
// '''
// Observable.range(0, 10)
//   .publish()
//   .refCount()
//   .take(5)
//   .subscribe();
// '''
// In order to account for this case, RefCountSubscriber should only dispose
// the ConnectableObservable's shared connection Subscription if the
// connection Subscription exists, *and* either:
//   a. RefCountSubscriber doesn't have a reference to the shared connection
...
```



# <a name="apidoc.module.rxjs.DeferObservable"></a>[module rxjs.DeferObservable](#apidoc.module.rxjs.DeferObservable)

#### <a name="apidoc.element.rxjs.DeferObservable.DeferObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>DeferObservable (observableFactory)](#apidoc.element.rxjs.DeferObservable.DeferObservable)
- description and source-code
```javascript
function DeferObservable(observableFactory) {
    _super.call(this);
    this.observableFactory = observableFactory;
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



# <a name="apidoc.module.rxjs.EmptyObservable"></a>[module rxjs.EmptyObservable](#apidoc.module.rxjs.EmptyObservable)

#### <a name="apidoc.element.rxjs.EmptyObservable.EmptyObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>EmptyObservable (scheduler)](#apidoc.element.rxjs.EmptyObservable.EmptyObservable)
- description and source-code
```javascript
function EmptyObservable(scheduler) {
    _super.call(this);
    this.scheduler = scheduler;
}
```
- example usage
```shell
...
        this._isScalar = true;
        this.value = arrayLike[0];
    }
}
ArrayLikeObservable.create = function (arrayLike, scheduler) {
    var length = arrayLike.length;
    if (length === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    else if (length === 1) {
        return new ScalarObservable_1.ScalarObservable(arrayLike[0], scheduler);
    }
    else {
        return new ArrayLikeObservable(arrayLike, scheduler);
    }
...
```



# <a name="apidoc.module.rxjs.ErrorObservable"></a>[module rxjs.ErrorObservable](#apidoc.module.rxjs.ErrorObservable)

#### <a name="apidoc.element.rxjs.ErrorObservable.ErrorObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ErrorObservable (error, scheduler)](#apidoc.element.rxjs.ErrorObservable.ErrorObservable)
- description and source-code
```javascript
function ErrorObservable(error, scheduler) {
    _super.call(this);
    this.error = error;
    this.scheduler = scheduler;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.FastMap"></a>[module rxjs.FastMap](#apidoc.module.rxjs.FastMap)

#### <a name="apidoc.element.rxjs.FastMap.FastMap"></a>[function <span class="apidocSignatureSpan">rxjs.</span>FastMap ()](#apidoc.element.rxjs.FastMap.FastMap)
- description and source-code
```javascript
function FastMap() {
    this.values = {};
}
```
- example usage
```shell
...
        return;
    }
    this._group(value, key);
};
GroupBySubscriber.prototype._group = function (value, key) {
    var groups = this.groups;
    if (!groups) {
        groups = this.groups = typeof key === 'string' ? new FastMap_1.FastMap() : new Map_1.Map();
    }
    var group = groups.get(key);
    var element;
    if (this.elementSelector) {
        try {
            element = this.elementSelector(value);
        }
...
```



# <a name="apidoc.module.rxjs.ForkJoinObservable"></a>[module rxjs.ForkJoinObservable](#apidoc.module.rxjs.ForkJoinObservable)

#### <a name="apidoc.element.rxjs.ForkJoinObservable.ForkJoinObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ForkJoinObservable (sources, resultSelector)](#apidoc.element.rxjs.ForkJoinObservable.ForkJoinObservable)
- description and source-code
```javascript
function ForkJoinObservable(sources, resultSelector) {
    _super.call(this);
    this.sources = sources;
    this.resultSelector = resultSelector;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.FromEventObservable"></a>[module rxjs.FromEventObservable](#apidoc.module.rxjs.FromEventObservable)

#### <a name="apidoc.element.rxjs.FromEventObservable.FromEventObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>FromEventObservable (sourceObj, eventName, selector, options)](#apidoc.element.rxjs.FromEventObservable.FromEventObservable)
- description and source-code
```javascript
function FromEventObservable(sourceObj, eventName, selector, options) {
    _super.call(this);
    this.sourceObj = sourceObj;
    this.eventName = eventName;
    this.selector = selector;
    this.options = options;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.FromEventPatternObservable"></a>[module rxjs.FromEventPatternObservable](#apidoc.module.rxjs.FromEventPatternObservable)

#### <a name="apidoc.element.rxjs.FromEventPatternObservable.FromEventPatternObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>FromEventPatternObservable (addHandler, removeHandler, selector)](#apidoc.element.rxjs.FromEventPatternObservable.FromEventPatternObservable)
- description and source-code
```javascript
function FromEventPatternObservable(addHandler, removeHandler, selector) {
    _super.call(this);
    this.addHandler = addHandler;
    this.removeHandler = removeHandler;
    this.selector = selector;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.FromObservable"></a>[module rxjs.FromObservable](#apidoc.module.rxjs.FromObservable)

#### <a name="apidoc.element.rxjs.FromObservable.FromObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>FromObservable (ish, scheduler)](#apidoc.element.rxjs.FromObservable.FromObservable)
- description and source-code
```javascript
function FromObservable(ish, scheduler) {
    _super.call(this, null);
    this.ish = ish;
    this.scheduler = scheduler;
}
```
- example usage
```shell
...
    nextSources[_i - 0] = arguments[_i];
}
var source = null;
if (nextSources.length === 1 && isArray_1.isArray(nextSources[0])) {
    nextSources = nextSources[0];
}
source = nextSources.shift();
return new FromObservable_1.FromObservable(source, null).lift(new OnErrorResumeNextOperator(nextSources));
}
exports.onErrorResumeNextStatic = onErrorResumeNextStatic;
var OnErrorResumeNextOperator = (function () {
function OnErrorResumeNextOperator(nextSources) {
    this.nextSources = nextSources;
}
OnErrorResumeNextOperator.prototype.call = function (subscriber, source) {
...
```



# <a name="apidoc.module.rxjs.GenerateObservable"></a>[module rxjs.GenerateObservable](#apidoc.module.rxjs.GenerateObservable)

#### <a name="apidoc.element.rxjs.GenerateObservable.GenerateObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>GenerateObservable (initialState, condition, iterate, resultSelector, scheduler)](#apidoc.element.rxjs.GenerateObservable.GenerateObservable)
- description and source-code
```javascript
function GenerateObservable(initialState, condition, iterate, resultSelector, scheduler) {
    _super.call(this);
    this.initialState = initialState;
    this.condition = condition;
    this.iterate = iterate;
    this.resultSelector = resultSelector;
    this.scheduler = scheduler;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.HotObservable"></a>[module rxjs.HotObservable](#apidoc.module.rxjs.HotObservable)

#### <a name="apidoc.element.rxjs.HotObservable.HotObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>HotObservable (messages, scheduler)](#apidoc.element.rxjs.HotObservable.HotObservable)
- description and source-code
```javascript
function HotObservable(messages, scheduler) {
    _super.call(this);
    this.messages = messages;
    this.subscriptions = [];
    this.scheduler = scheduler;
}
```
- example usage
```shell
...
    return cold;
};
TestScheduler.prototype.createHotObservable = function (marbles, values, error) {
    if (marbles.indexOf('!') !== -1) {
        throw new Error('hot observable cannot have unsubscription marker "!"');
    }
    var messages = TestScheduler.parseMarbles(marbles, values, error);
    var subject = new HotObservable_1.HotObservable(messages, this);
    this.hotObservables.push(subject);
    return subject;
};
TestScheduler.prototype.materializeInnerObservable = function (observable, outerFrame) {
    var _this = this;
    var messages = [];
    observable.subscribe(function (value) {
...
```



# <a name="apidoc.module.rxjs.IfObservable"></a>[module rxjs.IfObservable](#apidoc.module.rxjs.IfObservable)

#### <a name="apidoc.element.rxjs.IfObservable.IfObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>IfObservable (condition, thenSource, elseSource)](#apidoc.element.rxjs.IfObservable.IfObservable)
- description and source-code
```javascript
function IfObservable(condition, thenSource, elseSource) {
    _super.call(this);
    this.condition = condition;
    this.thenSource = thenSource;
    this.elseSource = elseSource;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Immediate"></a>[module rxjs.Immediate](#apidoc.module.rxjs.Immediate)

#### <a name="apidoc.element.rxjs.Immediate.ImmediateDefinition"></a>[function <span class="apidocSignatureSpan">rxjs.Immediate.</span>ImmediateDefinition (root)](#apidoc.element.rxjs.Immediate.ImmediateDefinition)
- description and source-code
```javascript
function ImmediateDefinition(root) {
    this.root = root;
    if (root.setImmediate && typeof root.setImmediate === 'function') {
        this.setImmediate = root.setImmediate.bind(root);
        this.clearImmediate = root.clearImmediate.bind(root);
    }
    else {
        this.nextHandle = 1;
        this.tasksByHandle = {};
        this.currentlyRunningATask = false;
        // Don't get fooled by e.g. browserify environments.
        if (this.canUseProcessNextTick()) {
            // For Node.js before 0.9
            this.setImmediate = this.createProcessNextTickSetImmediate();
        }
        else if (this.canUsePostMessage()) {
            // For non-IE10 modern browsers
            this.setImmediate = this.createPostMessageSetImmediate();
        }
        else if (this.canUseMessageChannel()) {
            // For web workers, where supported
            this.setImmediate = this.createMessageChannelSetImmediate();
        }
        else if (this.canUseReadyStateChange()) {
            // For IE 6–8
            this.setImmediate = this.createReadyStateChangeSetImmediate();
        }
        else {
            // For older browsers
            this.setImmediate = this.createSetTimeoutSetImmediate();
        }
        var ci = function clearImmediate(handle) {
            delete clearImmediate.instance.tasksByHandle[handle];
        };
        ci.instance = this;
        this.clearImmediate = ci;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.InnerSubscriber"></a>[module rxjs.InnerSubscriber](#apidoc.module.rxjs.InnerSubscriber)

#### <a name="apidoc.element.rxjs.InnerSubscriber.InnerSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.</span>InnerSubscriber (parent, outerValue, outerIndex)](#apidoc.element.rxjs.InnerSubscriber.InnerSubscriber)
- description and source-code
```javascript
function InnerSubscriber(parent, outerValue, outerIndex) {
    _super.call(this);
    this.parent = parent;
    this.outerValue = outerValue;
    this.outerIndex = outerIndex;
    this.index = 0;
}
```
- example usage
```shell
...
var isPromise_1 = require('./isPromise');
var isObject_1 = require('./isObject');
var Observable_1 = require('../Observable');
var iterator_1 = require('../symbol/iterator');
var InnerSubscriber_1 = require('../InnerSubscriber');
var observable_1 = require('../symbol/observable');
function subscribeToResult(outerSubscriber, result, outerValue, outerIndex) {
var destination = new InnerSubscriber_1.InnerSubscriber(outerSubscriber, outerValue, outerIndex);
if (destination.closed) {
    return null;
}
if (result instanceof Observable_1.Observable) {
    if (result._isScalar) {
        destination.next(result.value);
        destination.complete();
...
```



# <a name="apidoc.module.rxjs.IntervalObservable"></a>[module rxjs.IntervalObservable](#apidoc.module.rxjs.IntervalObservable)

#### <a name="apidoc.element.rxjs.IntervalObservable.IntervalObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>IntervalObservable (period, scheduler)](#apidoc.element.rxjs.IntervalObservable.IntervalObservable)
- description and source-code
```javascript
function IntervalObservable(period, scheduler) {
    if (period === void 0) { period = 0; }
    if (scheduler === void 0) { scheduler = async_1.async; }
    _super.call(this);
    this.period = period;
    this.scheduler = scheduler;
    if (!isNumeric_1.isNumeric(period) || period < 0) {
        this.period = 0;
    }
    if (!scheduler || typeof scheduler.schedule !== 'function') {
        this.scheduler = async_1.async;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.IteratorObservable"></a>[module rxjs.IteratorObservable](#apidoc.module.rxjs.IteratorObservable)

#### <a name="apidoc.element.rxjs.IteratorObservable.IteratorObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>IteratorObservable (iterator, scheduler)](#apidoc.element.rxjs.IteratorObservable.IteratorObservable)
- description and source-code
```javascript
function IteratorObservable(iterator, scheduler) {
    _super.call(this);
    this.scheduler = scheduler;
    if (iterator == null) {
        throw new Error('iterator cannot be null.');
    }
    this.iterator = getIterator(iterator);
}
```
- example usage
```shell
...
        else if (isArray_1.isArray(ish)) {
            return new ArrayObservable_1.ArrayObservable(ish, scheduler);
        }
        else if (isPromise_1.isPromise(ish)) {
            return new PromiseObservable_1.PromiseObservable(ish, scheduler);
        }
        else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
            return new IteratorObservable_1.IteratorObservable(ish, scheduler);
        }
        else if (isArrayLike_1.isArrayLike(ish)) {
            return new ArrayLikeObservable_1.ArrayLikeObservable(ish, scheduler);
        }
    }
    throw new TypeError((ish !== null && typeof ish || ish) + ' is not observable');
};
...
```



# <a name="apidoc.module.rxjs.Map"></a>[module rxjs.Map](#apidoc.module.rxjs.Map)

#### <a name="apidoc.element.rxjs.Map.Map"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Map ()](#apidoc.element.rxjs.Map.Map)
- description and source-code
```javascript
function Map() { [native code] }
```
- example usage
```shell
...
        return;
    }
    this._group(value, key);
};
GroupBySubscriber.prototype._group = function (value, key) {
    var groups = this.groups;
    if (!groups) {
        groups = this.groups = typeof key === 'string' ? new FastMap_1.FastMap() : new Map_1.Map();
    }
    var group = groups.get(key);
    var element;
    if (this.elementSelector) {
        try {
            element = this.elementSelector(value);
        }
...
```



# <a name="apidoc.module.rxjs.MapPolyfill"></a>[module rxjs.MapPolyfill](#apidoc.module.rxjs.MapPolyfill)

#### <a name="apidoc.element.rxjs.MapPolyfill.MapPolyfill"></a>[function <span class="apidocSignatureSpan">rxjs.</span>MapPolyfill ()](#apidoc.element.rxjs.MapPolyfill.MapPolyfill)
- description and source-code
```javascript
function MapPolyfill() {
    this.size = 0;
    this._values = [];
    this._keys = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.NeverObservable"></a>[module rxjs.NeverObservable](#apidoc.module.rxjs.NeverObservable)

#### <a name="apidoc.element.rxjs.NeverObservable.NeverObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>NeverObservable ()](#apidoc.element.rxjs.NeverObservable.NeverObservable)
- description and source-code
```javascript
function NeverObservable() {
    _super.call(this);
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
...
* 'error'. Such Observable is the output of a 'materialize' operation. Those
* notifications are then unwrapped using the metadata they contain, and emitted
* as 'next', 'error', and 'complete' on the output Observable.
*
* Use this operator in conjunction with {@link materialize}.
*
* @example <caption>Convert an Observable of Notifications to an actual Observable</caption>
* var notifA = new Rx.Notification('N', 'A');
* var notifB = new Rx.Notification('N', 'B');
* var notifE = new Rx.Notification('E', void 0,
*   new TypeError('x.toUpperCase is not a function')
* );
* var materialized = Rx.Observable.of(notifA, notifB, notifE);
* var upperCase = materialized.dematerialize();
* upperCase.subscribe(x => console.log(x), e => console.error(e));
...
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
...
};
DelaySubscriber.prototype._error = function (err) {
    this.errored = true;
    this.queue = [];
    this.destination.error(err);
};
DelaySubscriber.prototype._complete = function () {
    this.scheduleNotification(Notification_1.Notification.createComplete());
};
return DelaySubscriber;
}(Subscriber_1.Subscriber));
var DelayMessage = (function () {
function DelayMessage(time, notification) {
    this.time = time;
    this.notification = notification;
...
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
...
    _super.call(this, destination);
}
MaterializeSubscriber.prototype._next = function (value) {
    this.destination.next(Notification_1.Notification.createNext(value));
};
MaterializeSubscriber.prototype._error = function (err) {
    var destination = this.destination;
    destination.next(Notification_1.Notification.createError(err));
    destination.complete();
};
MaterializeSubscriber.prototype._complete = function () {
    var destination = this.destination;
    destination.next(Notification_1.Notification.createComplete());
    destination.complete();
};
...
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
...
    var message = new DelayMessage(scheduler.now() + this.delay, notification);
    this.queue.push(message);
    if (this.active === false) {
        this._schedule(scheduler);
    }
};
DelaySubscriber.prototype._next = function (value) {
    this.scheduleNotification(Notification_1.Notification.createNext(value));
};
DelaySubscriber.prototype._error = function (err) {
    this.errored = true;
    this.queue = [];
    this.destination.error(err);
};
DelaySubscriber.prototype._complete = function () {
...
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
...
 * @return {any}
 */
Notification.prototype.accept = function (nextOrObserver, error, complete) {
    if (nextOrObserver && typeof nextOrObserver.next === 'function') {
        return this.observe(nextOrObserver);
    }
    else {
        return this.do(nextOrObserver, error, complete);
    }
};
/**
 * Returns a simple Observable that just delivers the notification represented
 * by this Notification instance.
 * @return {any}
 */
...
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
...
 * the 'next' callback.
 * @param {function(err: any): void} [error] An Observer 'error' callback.
 * @param {function(): void} [complete] An Observer 'complete' callback.
 * @return {any}
 */
Notification.prototype.accept = function (nextOrObserver, error, complete) {
    if (nextOrObserver && typeof nextOrObserver.next === 'function') {
        return this.observe(nextOrObserver);
    }
    else {
        return this.do(nextOrObserver, error, complete);
    }
};
/**
 * Returns a simple Observable that just delivers the notification represented
...
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
...
    return subscription;
};
BehaviorSubject.prototype.getValue = function () {
    if (this.hasError) {
        throw this.thrownError;
    }
    else if (this.closed) {
        throw new ObjectUnsubscribedError_1.ObjectUnsubscribedError();
    }
    else {
        return this._value;
    }
};
BehaviorSubject.prototype.next = function (value) {
    _super.prototype.next.call(this, this._value = value);
...
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
...
    }
    else {
        this.observers.push(subscriber);
        return new SubjectSubscription_1.SubjectSubscription(this, subscriber);
    }
};
Subject.prototype.asObservable = function () {
    var observable = new Observable_1.Observable();
    observable.source = this;
    return observable;
};
Subject.create = function (destination, source) {
    return new AnonymousSubject(destination, source);
};
return Subject;
...
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
...
* provides convenient error handling and probably is a better choice.
* 'bindCallback' will treat such functions without any difference and error parameter
* (whether passed or not) will always be interpreted as regular callback argument.
*
*
* @example <caption>Convert jQuery's getJSON to an Observable API</caption>
* // Suppose we have jQuery.getJSON('/my/url', callback)
* var getJSONAsObservable = Rx.Observable.bindCallback(jQuery.getJSON);
* var result = getJSONAsObservable('/my/url');
* result.subscribe(x => console.log(x), e => console.error(e));
*
*
* @example <caption>Receive array of arguments passed to callback</caption>
* someFunction((a, b, c) => {
*   console.log(a); // 5
...
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
...
*
* Note that even if error parameter is technically present in callback, but its value
* is falsy, it still won't appear in array emitted by Observable or in selector function.
*
*
* @example <caption>Read a file from the filesystem and get the data as an Observable</caption>
* import * as fs from 'fs';
* var readFileAsObservable = Rx.Observable.bindNodeCallback(fs.readFile);
* var result = readFileAsObservable('./roadNames.txt', 'utf8');
* result.subscribe(x => console.log(x), e => console.error(e));
*
*
* @example <caption>Use on function calling callback with multiple arguments</caption>
* someFunction((err, a, b) => {
*   console.log(err); // null
...
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
...
* of values, but values themselves. That means default 'project' can be imagined
* as function that takes all its arguments and puts them into an array.
*
*
* @example <caption>Combine two timer Observables</caption>
* const firstTimer = Rx.Observable.timer(0, 1000); // emit 0, 1, 2... after every second, starting from now
* const secondTimer = Rx.Observable.timer(500, 1000); // emit 0, 1, 2... after every second, starting 0,5s from now
* const combinedTimers = Rx.Observable.combineLatest(firstTimer, secondTimer);
* combinedTimers.subscribe(value => console.log(value));
* // Logs
* // [0, 0] after 0.5s
* // [1, 0] after 1s
* // [1, 1] after 1.5s
* // [2, 1] after 2s
*
...
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
...
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
...
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
...
* an Observer subscribes to it, and then it generates an Observable,
* typically with an Observable factory function. It does this afresh for each
* subscriber, so although each subscriber may think it is subscribing to the
* same Observable, in fact each subscriber gets its own individual
* Observable.
*
* @example <caption>Subscribe to either an Observable of clicks or an Observable of interval, at random</caption>
* var clicksOrInterval = Rx.Observable.defer(function () {
*   if (Math.random() > 0.5) {
*     return Rx.Observable.fromEvent(document, 'click');
*   } else {
*     return Rx.Observable.interval(1000);
*   }
* });
* clicksOrInterval.subscribe(x => console.log(x));
...
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
...
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
};
/**
 * A shortcut to create a Notification instance of the type 'next' from a
 * given value.
 * @param {T} value The 'next' value.
...
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
        if (typeof ish[observable_1.$$observable] === 'function') {
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
        else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
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
...
* object into an Observable that emits the items in that promise or array or
* iterable. A String, in this context, is treated as an array of characters.
* Observable-like objects (contains a function named with the ES2015 Symbol
* for Observable) can also be converted through this operator.
*
* @example <caption>Converts an array to an Observable</caption>
* var array = [10, 20, 30];
* var result = Rx.Observable.from(array);
* result.subscribe(x => console.log(x));
*
* // Results in the following:
* // 10 20 30
*
* @example <caption>Convert an infinite iterable (from a generator) to an Observable</caption>
* function* generateDoubles(seed) {
...
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
...
* subscriber, so although each subscriber may think it is subscribing to the
* same Observable, in fact each subscriber gets its own individual
* Observable.
*
* @example <caption>Subscribe to either an Observable of clicks or an Observable of interval, at random</caption>
* var clicksOrInterval = Rx.Observable.defer(function () {
*   if (Math.random() > 0.5) {
*     return Rx.Observable.fromEvent(document, 'click');
*   } else {
*     return Rx.Observable.interval(1000);
*   }
* });
* clicksOrInterval.subscribe(x => console.log(x));
*
* // Results in the following behavior:
...
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
...
*   document.addEventListener('click', handler);
* }
*
* function removeClickHandler(handler) {
*   document.removeEventListener('click', handler);
* }
*
* var clicks = Rx.Observable.fromEventPattern(
*   addClickHandler,
*   removeClickHandler
* );
* clicks.subscribe(x => console.log(x));
*
* @see {@link from}
* @see {@link fromEvent}
...
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
...
*
* Converts an ES2015 Promise or a Promises/A+ spec compliant Promise to an
* Observable. If the Promise resolves with a value, the output Observable
* emits that resolved value as a 'next', and then completes. If the Promise
* is rejected, then the output Observable emits the corresponding Error.
*
* @example <caption>Convert the Promise returned by Fetch to an Observable</caption>
* var result = Rx.Observable.fromPromise(fetch('http://myserver.com/'));
* result.subscribe(x => console.log(x), e => console.error(e));
*
* @see {@link bindCallback}
* @see {@link from}
*
* @param {Promise<T>} promise The promise to be converted.
* @param {Scheduler} [scheduler] An optional IScheduler to use for scheduling
...
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
...
* By default, it uses a 'null' IScheduler, which means the 'next'
* notifications are sent synchronously, although with a different IScheduler
* it is possible to determine when those notifications will be delivered.
*
* @example <caption>Emit 10, 20, 30, then 'a', 'b', 'c', then start ticking every second.</caption>
* var numbers = Rx.Observable.of(10, 20, 30);
* var letters = Rx.Observable.of('a', 'b', 'c');
* var interval = Rx.Observable.interval(1000);
* var result = numbers.concat(letters).concat(interval);
* result.subscribe(x => console.log(x));
*
* @see {@link create}
* @see {@link empty}
* @see {@link never}
* @see {@link throw}
...
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
...
* subscription from being disposed automatically. Subscriptions need to be
* manually disposed.
*
* @example <caption>Emit the number 7, then never emit anything else (not even complete).</caption>
* function info() {
*   console.log('Will not be called');
* }
* var result = Rx.Observable.never().startWith(7);
* result.subscribe(x => console.log(x), info, info);
*
* @see {@link create}
* @see {@link empty}
* @see {@link of}
* @see {@link throw}
*
...
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
...
* @example <caption>Converts a javascript object to an Observable</caption>
* var obj = {
*   foo: 42,
*   bar: 56,
*   baz: 78
* };
*
* var source = Rx.Observable.pairs(obj);
*
* var subscription = source.subscribe(
*   function (x) {
*     console.log('Next: %s', x);
*   },
*   function (err) {
*     console.log('Error: %s', err);
...
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
...
// connection Subscription on the shared ConnectableObservable. In cases
// where the ConnectableObservable source synchronously emits values, and
// the RefCountSubscriber's downstream Observers synchronously unsubscribe,
// execution continues to here before the RefCountOperator has a chance to
// supply the RefCountSubscriber with the shared connection Subscription.
// For example:
// '''
// Observable.range(0, 10)
//   .publish()
//   .refCount()
//   .take(5)
//   .subscribe();
// '''
// In order to account for this case, RefCountSubscriber should only dispose
// the ConnectableObservable's shared connection Subscription if the
...
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
...
 */
Notification.prototype.toObservable = function () {
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
};
/**
 * A shortcut to create a Notification instance of the type 'next' from a
...
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
...
* 'initialDelay'. The initial delay may be a {@link Date}. By default, this
* operator uses the 'async' IScheduler to provide a notion of time, but you
* may pass any IScheduler to it. If 'period' is not specified, the output
* Observable emits only one value, '0'. Otherwise, it emits an infinite
* sequence.
*
* @example <caption>Emits ascending numbers, one every second (1000ms), starting after 3 seconds</caption>
* var numbers = Rx.Observable.timer(3000, 1000);
* numbers.subscribe(x => console.log(x));
*
* @example <caption>Emits one number after five seconds</caption>
* var numbers = Rx.Observable.timer(5000);
* numbers.subscribe(x => console.log(x));
*
* @see {@link interval}
...
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
...
            throw sink.syncErrorValue;
        }
    }
    return sink;
};
Observable.prototype._trySubscribe = function (sink) {
    try {
        return this._subscribe(sink);
    }
    catch (err) {
        sink.syncErrorThrown = true;
        sink.syncErrorValue = err;
        sink.error(err);
    }
};
...
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
...
    Observable.prototype.subscribe = function (observerOrNext, error, complete) {
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
...
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
...
* source value, which returns the "duration" Observable. When the duration
* Observable emits a value or completes, the timer is disabled, then the most
* recent source value is emitted on the output Observable, and this process
* repeats for the next source value.
*
* @example <caption>Emit clicks at a rate of at most one click per second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.audit(ev => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link auditTime}
* @see {@link debounce}
* @see {@link delayWhen}
* @see {@link sample}
* @see {@link throttle}
...
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
...
* the time unit determined internally by the optional 'scheduler') has passed,
* the timer is disabled, then the most recent source value is emitted on the
* output Observable, and this process repeats for the next source value.
* Optionally takes a {@link IScheduler} for managing timers.
*
* @example <caption>Emit clicks at a rate of at most one click per second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.auditTime(1000);
* result.subscribe(x => console.log(x));
*
* @see {@link audit}
* @see {@link debounceTime}
* @see {@link delay}
* @see {@link sampleTime}
* @see {@link throttleTime}
...
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
...
* Observable emits a value, at which point it emits the buffer on the output
* Observable and starts a new buffer internally, awaiting the next time
* 'closingNotifier' emits.
*
* @example <caption>On every click, emit array of most recent interval events</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var interval = Rx.Observable.interval(1000);
* var buffered = interval.buffer(clicks);
* buffered.subscribe(x => console.log(x));
*
* @see {@link bufferCount}
* @see {@link bufferTime}
* @see {@link bufferToggle}
* @see {@link bufferWhen}
* @see {@link window}
...
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
...
* emits the buffer and clears it, and starts a new buffer each
* 'startBufferEvery' values. If 'startBufferEvery' is not provided or is
* 'null', then new buffers are started immediately at the start of the source
* and when each buffer closes and is emitted.
*
* @example <caption>Emit the last two click events as an array</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferCount(2);
* buffered.subscribe(x => console.log(x));
*
* @example <caption>On every click, emit the last two click events as an array</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferCount(2, 1);
* buffered.subscribe(x => console.log(x));
*
...
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
...
* 'bufferCreationInterval' milliseconds and closes (emits and resets) the
* buffer every 'bufferTimeSpan' milliseconds. When the optional argument
* 'maxBufferSize' is specified, the buffer will be closed either after
* 'bufferTimeSpan' milliseconds or when it contains 'maxBufferSize' elements.
*
* @example <caption>Every second, emit an array of the recent click events</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferTime(1000);
* buffered.subscribe(x => console.log(x));
*
* @example <caption>Every 5 seconds, emit the click events from the next 2 seconds</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferTime(2000, 5000);
* buffered.subscribe(x => console.log(x));
*
...
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
...
* Buffers values from the source by opening the buffer via signals from an
* Observable provided to 'openings', and closing and sending the buffers when
* a Subscribable or Promise returned by the 'closingSelector' function emits.
*
* @example <caption>Every other second, emit the click events from the next 500ms</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var openings = Rx.Observable.interval(1000);
* var buffered = clicks.bufferToggle(openings, i =>
*   i % 2 ? Rx.Observable.interval(500) : Rx.Observable.empty()
* );
* buffered.subscribe(x => console.log(x));
*
* @see {@link buffer}
* @see {@link bufferCount}
* @see {@link bufferTime}
...
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
...
*
* Opens a buffer immediately, then closes the buffer when the observable
* returned by calling 'closingSelector' function emits a value. When it closes
* the buffer, it immediately opens a new buffer and repeats the process.
*
* @example <caption>Emit an array of the last clicks every [1-5] random seconds</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferWhen(() =>
*   Rx.Observable.interval(1000 + Math.random() * 4000)
* );
* buffered.subscribe(x => console.log(x));
*
* @see {@link buffer}
* @see {@link bufferCount}
* @see {@link bufferTime}
...
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
...
* Observable.of(1, 2, 3, 4, 5)
*   .map(n => {
* 	   if (n == 4) {
* 	     throw 'four!';
*     }
*	   return n;
*   })
*   .catch(err => Observable.of('I', 'II', 'III', 'IV', 'V'))
*   .subscribe(x => console.log(x));
*   // 1, 2, 3, I, II, III, IV, V
*
* @example <caption>Retries the caught source Observable again in case of error, similar to retry() operator</caption>
*
* Observable.of(1, 2, 3, 4, 5)
*   .map(n => {
...
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
...
*     values is emitted by the output Observable.
*
* @example <caption>Map two click events to a finite interval Observable, then apply combineAll</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map(ev =>
*   Rx.Observable.interval(Math.random()*2000).take(3)
* ).take(2);
* var result = higherOrder.combineAll();
* result.subscribe(x => console.log(x));
*
* @see {@link combineLatest}
* @see {@link mergeAll}
*
* @param {function} [project] An optional function to map the most recent
* values from each inner Observable into a new result. Takes each of the most
...
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
...
* of values, but values themselves. That means default 'project' can be imagined
* as function that takes all its arguments and puts them into an array.
*
*
* @example <caption>Combine two timer Observables</caption>
* const firstTimer = Rx.Observable.timer(0, 1000); // emit 0, 1, 2... after every second, starting from now
* const secondTimer = Rx.Observable.timer(500, 1000); // emit 0, 1, 2... after every second, starting 0,5s from now
* const combinedTimers = Rx.Observable.combineLatest(firstTimer, secondTimer);
* combinedTimers.subscribe(value => console.log(value));
* // Logs
* // [0, 0] after 0.5s
* // [1, 0] after 1s
* // [1, 1] after 1.5s
* // [2, 1] after 2s
*
...
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
...
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
...
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
...
*
* Note: 'concatAll' is equivalent to 'mergeAll' with concurrency parameter set
* to '1'.
*
* @example <caption>For each click event, tick every second from 0 to 3, with no concurrency</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map(ev => Rx.Observable.interval(1000).take(4));
* var firstOrder = higherOrder.concatAll();
* firstOrder.subscribe(x => console.log(x));
*
* // Results in the following:
* // (results are not concurrent)
* // For every click on the "document" it will emit values 0 to 3 spaced
* // on a 1000ms interval
* // one click = 1000ms-> 0 -1000ms-> 1 -1000ms-> 2 -1000ms-> 3
...
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
...
* be subscribed to.
*
* Note: 'concatMap' is equivalent to 'mergeMap' with concurrency parameter set
* to '1'.
*
* @example <caption>For each click event, tick every second from 0 to 3, with no concurrency</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.concatMap(ev => Rx.Observable.interval(1000).take(4));
* result.subscribe(x => console.log(x));
*
* // Results in the following:
* // (results are not concurrent)
* // For every click on the "document" it will emit values 0 to 3 spaced
* // on a 1000ms interval
* // one click = 1000ms-> 0 -1000ms-> 1 -1000ms-> 2 -1000ms-> 3
...
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
...
* be subscribed to.
*
* Note: 'concatMapTo' is equivalent to 'mergeMapTo' with concurrency parameter
* set to '1'.
*
* @example <caption>For each click event, tick every second from 0 to 3, with no concurrency</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.concatMapTo(Rx.Observable.interval(1000).take(4));
* result.subscribe(x => console.log(x));
*
* // Results in the following:
* // (results are not concurrent)
* // For every click on the "document" it will emit values 0 to 3 spaced
* // on a 1000ms interval
* // one click = 1000ms-> 0 -1000ms-> 1 -1000ms-> 2 -1000ms-> 3
...
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
...
* as argument, in which case the output emission will represent the number of
* source values that matched 'true' with the 'predicate'.
*
* @example <caption>Counts how many seconds have passed before the first click happened</caption>
* var seconds = Rx.Observable.interval(1000);
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var secondsBeforeClick = seconds.takeUntil(clicks);
* var result = secondsBeforeClick.count();
* result.subscribe(x => console.log(x));
*
* @example <caption>Counts how many odd numbers are there between 1 and 7</caption>
* var numbers = Rx.Observable.range(1, 7);
* var result = numbers.count(i => i % 2 === 1);
* result.subscribe(x => console.log(x));
*
...
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
...
*
* Like {@link debounceTime}, this is a rate-limiting operator, and also a
* delay-like operator since output emissions do not necessarily occur at the
* same time as they did on the source Observable.
*
* @example <caption>Emit the most recent click after a burst of clicks</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.debounce(() => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link audit}
* @see {@link debounceTime}
* @see {@link delayWhen}
* @see {@link throttle}
*
...
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
...
* value to be emitted in any time window of duration 'dueTime', but it is also
* a delay-like operator since output emissions do not occur at the same time as
* they did on the source Observable. Optionally takes a {@link IScheduler} for
* managing timers.
*
* @example <caption>Emit the most recent click after a burst of clicks</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.debounceTime(1000);
* result.subscribe(x => console.log(x));
*
* @see {@link auditTime}
* @see {@link debounce}
* @see {@link delay}
* @see {@link sampleTime}
* @see {@link throttleTime}
...
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
...
* 'defaultIfEmpty' emits the values emitted by the source Observable or a
* specified default value if the source Observable is empty (completes without
* having emitted any 'next' value).
*
* @example <caption>If no clicks happen in 5 seconds, then emit "no clicks"</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var clicksBeforeFive = clicks.takeUntil(Rx.Observable.interval(5000));
* var result = clicksBeforeFive.defaultIfEmpty('no clicks');
* result.subscribe(x => console.log(x));
*
* @see {@link empty}
* @see {@link last}
*
* @param {any} [defaultValue=null] The default value used if the source
* Observable is empty.
...
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
...
* // [1, 0] after 1s
* // [1, 1] after 1.5s
* // [2, 1] after 2s
*
*
* @example <caption>Combine an array of Observables</caption>
* const observables = [1, 5, 10].map(
*   n => Rx.Observable.of(n).delay(n * 1000).startWith(0) // emit 0 and then emit n after n seconds
* );
* const combined = Rx.Observable.combineLatest(observables);
* combined.subscribe(value => console.log(value));
* // Logs
* // [0, 0, 0] immediately
* // [1, 0, 0] after 1s
* // [1, 5, 0] after 5s
...
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
...
* completes, the source Observable is subscribed to and starts behaving like
* described in the previous paragraph. If 'subscriptionDelay' is not provided,
* 'delayWhen' will subscribe to the source Observable as soon as the output
* Observable is subscribed.
*
* @example <caption>Delay each click by a random amount of time, between 0 and 5 seconds</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var delayedClicks = clicks.delayWhen(event =>
*   Rx.Observable.interval(Math.random() * 5000)
* );
* delayedClicks.subscribe(x => console.log(x));
*
* @see {@link debounce}
* @see {@link delay}
*
...
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
...
* @example <caption>Convert an Observable of Notifications to an actual Observable</caption>
* var notifA = new Rx.Notification('N', 'A');
* var notifB = new Rx.Notification('N', 'B');
* var notifE = new Rx.Notification('E', void 0,
*   new TypeError('x.toUpperCase is not a function')
* );
* var materialized = Rx.Observable.of(notifA, notifB, notifE);
* var upperCase = materialized.dematerialize();
* upperCase.subscribe(x => console.log(x), e => console.error(e));
*
* // Results in:
* // A
* // B
* // TypeError: x.toUpperCase is not a function
*
...
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
...
* In other runtimes, this operator will use a minimal implementation of 'Set' that relies on an 'Array' and 'indexOf' under the
* hood, so performance will degrade as more values are checked for distinction. Even in newer browsers, a long-running 'distinct
'
* use might result in memory leaks. To help alleviate this in some scenarios, an optional 'flushes' parameter is also provided so
* that the internal 'Set' can be "flushed", basically clearing it of values.
*
* @example <caption>A simple example with numbers</caption>
* Observable.of(1, 1, 2, 2, 2, 1, 2, 3, 4, 3, 2, 1)
*   .distinct()
*   .subscribe(x => console.log(x)); // 1, 2, 3, 4
*
* @example <caption>An example using a keySelector function</caption>
* interface Person {
*    age: number,
*    name: string
* }
...
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
...
*
* If a comparator function is provided, then it will be called for each item to test for whether or not that value should be emitted
.
*
* If a comparator function is not provided, an equality check is used by default.
*
* @example <caption>A simple example with numbers</caption>
* Observable.of(1, 1, 2, 2, 2, 1, 1, 2, 3, 3, 4)
*   .distinctUntilChanged()
*   .subscribe(x => console.log(x)); // 1, 2, 1, 2, 3, 4
*
* @example <caption>An example using a compare function</caption>
* interface Person {
*    age: number,
*    name: string
* }
...
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
...
*  }
*
* Observable.of<Person>(
*     { age: 4, name: 'Foo'},
*     { age: 7, name: 'Bar'},
*     { age: 5, name: 'Foo'},
*     { age: 6, name: 'Foo'})
*     .distinctUntilKeyChanged('name')
*     .subscribe(x => console.log(x));
*
* // displays:
* // { age: 4, name: 'Foo' }
* // { age: 7, name: 'Bar' }
* // { age: 5, name: 'Foo' }
*
...
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
...
 * @return {any}
 */
Notification.prototype.accept = function (nextOrObserver, error, complete) {
    if (nextOrObserver && typeof nextOrObserver.next === 'function') {
        return this.observe(nextOrObserver);
    }
    else {
        return this.do(nextOrObserver, error, complete);
    }
};
/**
 * Returns a simple Observable that just delivers the notification represented
 * by this Notification instance.
 * @return {any}
 */
...
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
...
* 'index' in the source Observable, or a default value if that 'index' is out
* of range and the 'default' argument is provided. If the 'default' argument is
* not given and the 'index' is out of range, the output Observable will emit an
* 'ArgumentOutOfRangeError' error.
*
* @example <caption>Emit only the third click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.elementAt(2);
* result.subscribe(x => console.log(x));
*
* // Results in:
* // click 1 = nothing
* // click 2 = nothing
* // click 3 = MouseEvent object logged to console
*
...
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
...
};
var Subscriber_1 = require('../Subscriber');
/**
* Returns an Observable that emits whether or not every item of the source satisfies the condition specified.
*
* @example <caption>A simple example emitting true if all elements are less than 5, false otherwise</caption>
*  Observable.of(1, 2, 3, 4, 5, 6)
*     .every(x => x < 5)
*     .subscribe(x => console.log(x)); // -> false
*
* @param {function} predicate A function for determining if an item meets a specified condition.
* @param {any} [thisArg] Optional object to use for 'this' in the callback.
* @return {Observable} An Observable of booleans that determines if all items of the source Observable meet the condition specified
.
* @method every
* @owner Observable
...
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
...
* 'exhaust' ignores every new inner Observable if the previous Observable has
* not yet completed. Once that one completes, it will accept and flatten the
* next inner Observable and repeat this process.
*
* @example <caption>Run a finite timer for each click, only if there is no currently active timer</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map((ev) => Rx.Observable.interval(1000));
* var result = higherOrder.exhaust();
* result.subscribe(x => console.log(x));
*
* @see {@link combineAll}
* @see {@link concatAll}
* @see {@link switch}
* @see {@link mergeAll}
* @see {@link exhaustMap}
...
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
...
* that projected Observable. However, 'exhaustMap' ignores every new projected
* Observable if the previous projected Observable has not yet completed. Once
* that one completes, it will accept and flatten the next projected Observable
* and repeat this process.
*
* @example <caption>Run a finite timer for each click, only if there is no currently active timer</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.exhaustMap((ev) => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link concatMap}
* @see {@link exhaust}
* @see {@link mergeMap}
* @see {@link switchMap}
*
...
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
...
* given to the 'project' function to produce new output values. This is how
* *expand* behaves recursively.
*
* @example <caption>Start emitting the powers of two on every click, at most 10 of them</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var powersOfTwo = clicks
*   .mapTo(1)
*   .expand(x => Rx.Observable.of(2 * x).delay(1000))
*   .take(10);
* powersOfTwo.subscribe(x => console.log(x));
*
* @see {@link mergeMap}
* @see {@link mergeScan}
*
* @param {function(value: T, index: number) => Observable} project A function
...
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
...
var Subscriber_1 = require('../Subscriber');
/* tslint:enable:max-line-length */
/**
* Filter items emitted by the source Observable by only emitting those that
* satisfy a specified predicate.
*
* <span class="informal">Like
* [Array.prototype.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter),
* it only emits a value from the source if it passes a criterion function.</span>
*
* <img src="./img/filter.png" width="100%">
*
* Similar to the well-known 'Array.prototype.filter' method, this operator
* takes values from the source Observable, passes them through a 'predicate'
* function and only emits those values that yielded 'true'.
...
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
...
* 'find' searches for the first item in the source Observable that matches the
* specified condition embodied by the 'predicate', and returns the first
* occurrence in the source. Unlike {@link first}, the 'predicate' is required
* in 'find', and does not emit an error if a valid value is not found.
*
* @example <caption>Find and emit the first click that happens on a DIV element</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.find(ev => ev.target.tagName === 'DIV');
* result.subscribe(x => console.log(x));
*
* @see {@link filter}
* @see {@link first}
* @see {@link findIndex}
* @see {@link take}
*
...
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
...
* the specified condition embodied by the 'predicate', and returns the
* (zero-based) index of the first occurrence in the source. Unlike
* {@link first}, the 'predicate' is required in 'findIndex', and does not emit
* an error if a valid value is not found.
*
* @example <caption>Emit the index of first click that happens on a DIV element</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.findIndex(ev => ev.target.tagName === 'DIV');
* result.subscribe(x => console.log(x));
*
* @see {@link filter}
* @see {@link find}
* @see {@link first}
* @see {@link take}
*
...
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
...
* may also take a 'resultSelector' function to produce the output value from
* the input value, and a 'defaultValue' to emit in case the source completes
* before it is able to emit a valid value. Throws an error if 'defaultValue'
* was not provided and a matching element is not found.
*
* @example <caption>Emit only the first click that happens on the DOM</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.first();
* result.subscribe(x => console.log(x));
*
* @example <caption>Emits the first click that happens on a DIV</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.first(ev => ev.target.tagName === 'DIV');
* result.subscribe(x => console.log(x));
*
...
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
        var subscription = _this.subscribe(function (value) {
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
...
    if (!group.closed) {
        group.next(element);
    }
};
GroupBySubscriber.prototype._error = function (err) {
    var groups = this.groups;
    if (groups) {
        groups.forEach(function (group, key) {
            group.error(err);
        });
        groups.clear();
    }
    this.destination.error(err);
};
GroupBySubscriber.prototype._complete = function () {
...
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
...
        else {
            this._connection = connection;
        }
    }
    return connection;
};
ConnectableObservable.prototype.refCount = function () {
    return this.lift(new RefCountOperator(this));
};
return ConnectableObservable;
}(Observable_1.Observable));
exports.ConnectableObservable = ConnectableObservable;
exports.connectableObservableDescriptor = {
operator: { value: null },
_refCount: { value: 0, writable: true },
...
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
...
* output Observable. Those output values resulting from the projection are also
* given to the 'project' function to produce new output values. This is how
* *expand* behaves recursively.
*
* @example <caption>Start emitting the powers of two on every click, at most 10 of them</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var powersOfTwo = clicks
*   .mapTo(1)
*   .expand(x => Rx.Observable.of(2 * x).delay(1000))
*   .take(10);
* powersOfTwo.subscribe(x => console.log(x));
*
* @see {@link mergeMap}
* @see {@link mergeScan}
*
...
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
...
* This operator is useful for producing metadata of the source Observable, to
* be consumed as 'next' emissions. Use it in conjunction with
* {@link dematerialize}.
*
* @example <caption>Convert a faulty Observable to an Observable of Notifications</caption>
* var letters = Rx.Observable.of('a', 'b', 13, 'd');
* var upperCase = letters.map(x => x.toUpperCase());
* var materialized = upperCase.materialize();
* materialized.subscribe(x => console.log(x));
*
* // Results in the following:
* // - Notification {kind: "N", value: "A", error: undefined, hasValue: true}
* // - Notification {kind: "N", value: "B", error: undefined, hasValue: true}
* // - Notification {kind: "E", value: undefined, error: TypeError:
* //   x.toUpperCase is not a function at MapSubscriber.letters.map.x
...
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
...
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
};
return ReplaySubject;
...
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
...
* inner Observable on the output Observable. The output Observable only
* completes once all inner Observables have completed. Any error delivered by
* a inner Observable will be immediately emitted on the output Observable.
*
* @example <caption>Spawn a new interval Observable for each click event, and blend their outputs as one Observable</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map((ev) => Rx.Observable.interval(1000));
* var firstOrder = higherOrder.mergeAll();
* firstOrder.subscribe(x => console.log(x));
*
* @example <caption>Count from 0 to 9 every second for each click, but only allow 2 concurrent timers</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map((ev) => Rx.Observable.interval(1000).take(10));
* var firstOrder = higherOrder.mergeAll(2);
* firstOrder.subscribe(x => console.log(x));
...
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
...
*
* @example <caption>Emit the number 7, then complete.</caption>
* var result = Rx.Observable.empty().startWith(7);
* result.subscribe(x => console.log(x));
*
* @example <caption>Map and flatten only odd numbers to the sequence 'a', 'b', 'c'</caption>
* var interval = Rx.Observable.interval(1000);
* var result = interval.mergeMap(x =>
*   x % 2 === 1 ? Rx.Observable.of('a', 'b', 'c') : Rx.Observable.empty()
* );
* result.subscribe(x => console.log(x));
*
* // Results in the following to the console:
* // x is equal to the count on the interval eg(0,1,2,3,...)
* // x will occur every 1000ms
...
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
...
*
* Maps each source value to the given Observable 'innerObservable' regardless
* of the source value, and then merges those resulting Observables into one
* single Observable, which is the output Observable.
*
* @example <caption>For each click event, start an interval Observable ticking every 1 second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.mergeMapTo(Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link concatMapTo}
* @see {@link merge}
* @see {@link mergeAll}
* @see {@link mergeMap}
* @see {@link mergeScan}
...
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
...
* <span class="informal">It's like {@link scan}, but the Observables returned
* by the accumulator are merged into the outer Observable.</span>
*
* @example <caption>Count the number of click events</caption>
* const click$ = Rx.Observable.fromEvent(document, 'click');
* const one$ = click$.mapTo(1);
* const seed = 0;
* const count$ = one$.mergeScan((acc, one) => Rx.Observable.of(acc + one), seed);
* count$.subscribe(x => console.log(x));
*
* // Results:
* 1
* 2
* 3
* 4
...
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
...
* to emit an array [(N-1)th, Nth] of the previous and the current value, as a
* pair. For this reason, 'pairwise' emits on the second and subsequent
* emissions from the source Observable, but not on the first emission, because
* there is no previous value in that case.
*
* @example <caption>On every click (starting from the second), emit the relative distance to the previous click</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var pairs = clicks.pairwise();
* var distance = pairs.map(pair => {
*   var x0 = pair[0].clientX;
*   var y0 = pair[0].clientY;
*   var x1 = pair[1].clientX;
*   var y1 = pair[1].clientY;
*   return Math.sqrt(Math.pow(x0 - x1, 2) + Math.pow(y0 - y1, 2));
* });
...
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
...
* Observable in that array emits source values for which the predicate argument
* returns true. The second Observable emits source values for which the
* predicate returns false. The first behaves like {@link filter} and the second
* behaves like {@link filter} with the predicate negated.
*
* @example <caption>Partition click events into those on DIV elements and those elsewhere</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var parts = clicks.partition(ev => ev.target.tagName === 'DIV');
* var clicksOnDivs = parts[0];
* var clicksElsewhere = parts[1];
* clicksOnDivs.subscribe(x => console.log('DIV clicked: ', x));
* clicksElsewhere.subscribe(x => console.log('Other clicked: ', x));
*
* @see {@link filter}
*
...
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
...
* Given a list of strings describing a path to an object property, retrieves
* the value of a specified nested property from all values in the source
* Observable. If a property can't be resolved, it will return 'undefined' for
* that value.
*
* @example <caption>Map every every click to the tagName of the clicked target element</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var tagNames = clicks.pluck('target', 'tagName');
* tagNames.subscribe(x => console.log(x));
*
* @see {@link map}
*
* @param {...string} properties The nested properties to pluck from each source
* value (an object).
* @return {Observable} A new Observable of property values from the source values.
...
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
...
// where the ConnectableObservable source synchronously emits values, and
// the RefCountSubscriber's downstream Observers synchronously unsubscribe,
// execution continues to here before the RefCountOperator has a chance to
// supply the RefCountSubscriber with the shared connection Subscription.
// For example:
// '''
// Observable.range(0, 10)
//   .publish()
//   .refCount()
//   .take(5)
//   .subscribe();
// '''
// In order to account for this case, RefCountSubscriber should only dispose
// the ConnectableObservable's shared connection Subscription if the
// connection Subscription exists, *and* either:
...
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
...
        empty.closed = true;
        return empty;
    }(new Subscription()));
    return Subscription;
}());
exports.Subscription = Subscription;
function flattenUnsubscriptionErrors(errors) {
    return errors.reduce(function (errs, err) { return errs.concat((err instanceof UnsubscriptionError_1.UnsubscriptionError) ?
err.errors : err); }, []);
}
//# sourceMappingURL=Subscription.js.map
...
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
...
* emitted since the previous sampling, unless the source has not emitted
* anything since the previous sampling. The 'notifier' is subscribed to as soon
* as the output Observable is subscribed.
*
* @example <caption>On every click, sample the most recent "seconds" timer</caption>
* var seconds = Rx.Observable.interval(1000);
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = seconds.sample(clicks);
* result.subscribe(x => console.log(x));
*
* @see {@link audit}
* @see {@link debounce}
* @see {@link sampleTime}
* @see {@link throttle}
*
...
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
...
* source has not emitted anything since the previous sampling. The sampling
* happens periodically in time every 'period' milliseconds (or the time unit
* defined by the optional 'scheduler' argument). The sampling starts as soon as
* the output Observable is subscribed.
*
* @example <caption>Every second, emit the most recent click at most once</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.sampleTime(1000);
* result.subscribe(x => console.log(x));
*
* @see {@link auditTime}
* @see {@link debounceTime}
* @see {@link delay}
* @see {@link sample}
* @see {@link throttleTime}
...
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
...
* that value will be used as the initial value for the accumulator. If no seed
* value is specified, the first item of the source is used as the seed.
*
* @example <caption>Count the number of click events</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var ones = clicks.mapTo(1);
* var seed = 0;
* var count = ones.scan((acc, one) => acc + one, seed);
* count.subscribe(x => console.log(x));
*
* @see {@link expand}
* @see {@link mergeScan}
* @see {@link reduce}
*
* @param {function(acc: R, value: T, index: number): R} accumulator
...
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
...
*
* var keys = Rx.Observable.fromEvent(document, 'keyup')
*  .map(e => e.code);
* var matches = keys.bufferCount(11, 1)
*  .mergeMap(
*    last11 =>
*      Rx.Observable.from(last11)
*        .sequenceEqual(code)
*   );
* matches.subscribe(matched => console.log('Successful cheat at Contra? ', matched));
*
* @see {@link combineLatest}
* @see {@link zip}
* @see {@link withLatestFrom}
*
...
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
...
* Observable. If 'startWindowEvery' is not provided, then new windows are
* started immediately at the start of the source and when each window completes
* with size 'windowSize'.
*
* @example <caption>Ignore every 3rd click event, starting from the first one</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.windowCount(3)
*   .map(win => win.skip(1)) // skip first of every 3 clicks
*   .mergeAll(); // flatten the Observable-of-Observables
* result.subscribe(x => console.log(x));
*
* @example <caption>Ignore every 3rd click event, starting from the third one</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.windowCount(2, 3)
*   .mergeAll(); // flatten the Observable-of-Observables
...
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
...
* <img src="./img/empty.png" width="100%">
*
* This static operator is useful for creating a simple Observable that only
* emits the complete notification. It can be used for composing with other
* Observables, such as in a {@link mergeMap}.
*
* @example <caption>Emit the number 7, then complete.</caption>
* var result = Rx.Observable.empty().startWith(7);
* result.subscribe(x => console.log(x));
*
* @example <caption>Map and flatten only odd numbers to the sequence 'a', 'b', 'c'</caption>
* var interval = Rx.Observable.interval(1000);
* var result = interval.mergeMap(x =>
*   x % 2 === 1 ? Rx.Observable.of('a', 'b', 'c') : Rx.Observable.empty()
* );
...
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
...
* subscribes to the new inner Observable and begins emitting items from it. It
* continues to behave like this for subsequent inner Observables.
*
* @example <caption>Rerun an interval Observable on every click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* // Each click event is mapped to an Observable that ticks every second
* var higherOrder = clicks.map((ev) => Rx.Observable.interval(1000));
* var switched = higherOrder.switch();
* // The outcome is that 'switched' is essentially a timer that restarts
* // on every click. The interval Observables from older clicks do not merge
* // with the current interval Observable.
* switched.subscribe(x => console.log(x));
*
* @see {@link combineAll}
* @see {@link concatAll}
...
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
...
* that inner Observable. When a new inner Observable is emitted, 'switchMap'
* stops emitting items from the earlier-emitted inner Observable and begins
* emitting items from the new one. It continues to behave like this for
* subsequent inner Observables.
*
* @example <caption>Rerun an interval Observable on every click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.switchMap((ev) => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link concatMap}
* @see {@link exhaustMap}
* @see {@link mergeMap}
* @see {@link switch}
* @see {@link switchMapTo}
...
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
...
* of the source value, and then flattens those resulting Observables into one
* single Observable, which is the output Observable. The output Observables
* emits values only from the most recently emitted instance of
* 'innerObservable'.
*
* @example <caption>Rerun an interval Observable on every click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.switchMapTo(Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link concatMapTo}
* @see {@link switch}
* @see {@link switchMap}
* @see {@link mergeMapTo}
*
...
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
...
// execution continues to here before the RefCountOperator has a chance to
// supply the RefCountSubscriber with the shared connection Subscription.
// For example:
// '''
// Observable.range(0, 10)
//   .publish()
//   .refCount()
//   .take(5)
//   .subscribe();
// '''
// In order to account for this case, RefCountSubscriber should only dispose
// the ConnectableObservable's shared connection Subscription if the
// connection Subscription exists, *and* either:
//   a. RefCountSubscriber doesn't have a reference to the shared connection
//      Subscription yet, or,
...
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
...
* 'complete' notification emission from the source in order to emit the 'next'
* values on the output Observable, because otherwise it is impossible to know
* whether or not more values will be emitted on the source. For this reason,
* all values are emitted synchronously, followed by the complete notification.
*
* @example <caption>Take the last 3 values of an Observable with many values</caption>
* var many = Rx.Observable.range(1, 100);
* var lastThree = many.takeLast(3);
* lastThree.subscribe(x => console.log(x));
*
* @see {@link take}
* @see {@link takeUntil}
* @see {@link takeWhile}
* @see {@link skip}
*
...
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
...
* a value nor terminate. This operator takes an optional 'predicate' function
* as argument, in which case the output emission will represent the number of
* source values that matched 'true' with the 'predicate'.
*
* @example <caption>Counts how many seconds have passed before the first click happened</caption>
* var seconds = Rx.Observable.interval(1000);
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var secondsBeforeClick = seconds.takeUntil(clicks);
* var result = secondsBeforeClick.count();
* result.subscribe(x => console.log(x));
*
* @example <caption>Counts how many odd numbers are there between 1 and 7</caption>
* var numbers = Rx.Observable.range(1, 7);
* var result = numbers.count(i => i % 2 === 1);
* result.subscribe(x => console.log(x));
...
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
...
* boolean, representing a condition to be satisfied by the source values. The
* output Observable emits the source values until such time as the 'predicate'
* returns false, at which point 'takeWhile' stops mirroring the source
* Observable and completes the output Observable.
*
* @example <caption>Emit click events only while the clientX property is greater than 200</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.takeWhile(ev => ev.clientX > 200);
* result.subscribe(x => console.log(x));
*
* @see {@link take}
* @see {@link takeLast}
* @see {@link takeUntil}
* @see {@link skip}
*
...
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
...
* is enabled by calling the 'durationSelector' function with the source value,
* which returns the "duration" Observable. When the duration Observable emits a
* value or completes, the timer is disabled, and this process repeats for the
* next source value.
*
* @example <caption>Emit clicks at a rate of at most one click per second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.throttle(ev => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link audit}
* @see {@link debounce}
* @see {@link delayWhen}
* @see {@link sample}
* @see {@link throttleTime}
...
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
...
* is enabled. After 'duration' milliseconds (or the time unit determined
* internally by the optional 'scheduler') has passed, the timer is disabled,
* and this process repeats for the next source value. Optionally takes a
* {@link IScheduler} for managing timers.
*
* @example <caption>Emit clicks at a rate of at most one click per second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.throttleTime(1000);
* result.subscribe(x => console.log(x));
*
* @see {@link auditTime}
* @see {@link debounceTime}
* @see {@link delay}
* @see {@link sampleTime}
* @see {@link throttle}
...
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
...
/**
* Converts an Observable sequence to a ES2015 compliant promise.
*
* @example
* // Using normal ES2015
* let source = Rx.Observable
*   .just(42)
*   .toPromise();
*
* source.then((value) => console.log('Value: %s', value));
* // => Value: 42
*
* // Rejected Promise
* // Using normal ES2015
* let source = Rx.Observable
...
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
...
* windows. It emits the current window and opens a new one whenever the
* Observable 'windowBoundaries' emits an item. Because each window is an
* Observable, the output is a higher-order Observable.
*
* @example <caption>In every window of 1 second each, emit at most 2 click events</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var interval = Rx.Observable.interval(1000);
* var result = clicks.window(interval)
*   .map(win => win.take(2)) // each window has at most 2 emissions
*   .mergeAll(); // flatten the Observable-of-Observables
* result.subscribe(x => console.log(x));
*
* @see {@link windowCount}
* @see {@link windowTime}
* @see {@link windowToggle}
...
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
...
* the current window and propagates the notification from the source
* Observable. If 'startWindowEvery' is not provided, then new windows are
* started immediately at the start of the source and when each window completes
* with size 'windowSize'.
*
* @example <caption>Ignore every 3rd click event, starting from the first one</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.windowCount(3)
*   .map(win => win.skip(1)) // skip first of every 3 clicks
*   .mergeAll(); // flatten the Observable-of-Observables
* result.subscribe(x => console.log(x));
*
* @example <caption>Ignore every 3rd click event, starting from the third one</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.windowCount(2, 3)
...
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
...
* emitted by the source Observable between the time when the 'openings'
* Observable emits an item and when the Observable returned by
* 'closingSelector' emits an item.
*
* @example <caption>Every other second, emit the click events from the next 500ms</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var openings = Rx.Observable.interval(1000);
* var result = clicks.windowToggle(openings, i =>
*   i % 2 ? Rx.Observable.interval(500) : Rx.Observable.empty()
* ).mergeAll();
* result.subscribe(x => console.log(x));
*
* @see {@link window}
* @see {@link windowCount}
* @see {@link windowTime}
...
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
...
* It emits the current window and opens a new one whenever the Observable
* produced by the specified 'closingSelector' function emits an item. The first
* window is opened immediately when subscribing to the output Observable.
*
* @example <caption>Emit only the first two clicks events in every window of [1-5] random seconds</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks
*   .windowWhen(() => Rx.Observable.interval(1000 + Math.random() * 4000))
*   .map(win => win.take(2)) // each window has at most 2 emissions
*   .mergeAll(); // flatten the Observable-of-Observables
* result.subscribe(x => console.log(x));
*
* @see {@link window}
* @see {@link windowCount}
* @see {@link windowTime}
...
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
...
* the source emits a value, optionally using a 'project' function to determine
* the value to be emitted on the output Observable. All input Observables must
* emit at least one value before the output Observable will emit a value.
*
* @example <caption>On every click event, emit an array with the latest timer event plus the click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var timer = Rx.Observable.interval(1000);
* var result = clicks.withLatestFrom(timer);
* result.subscribe(x => console.log(x));
*
* @see {@link combineLatest}
*
* @param {ObservableInput} other An input Observable to combine with the source
* Observable. More than one input Observables may be given as argument.
* @param {Function} [project] Projection function for combining values
...
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



# <a name="apidoc.module.rxjs.OuterSubscriber"></a>[module rxjs.OuterSubscriber](#apidoc.module.rxjs.OuterSubscriber)

#### <a name="apidoc.element.rxjs.OuterSubscriber.OuterSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.</span>OuterSubscriber ()](#apidoc.element.rxjs.OuterSubscriber.OuterSubscriber)
- description and source-code
```javascript
function OuterSubscriber() {
    _super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.PairsObservable"></a>[module rxjs.PairsObservable](#apidoc.module.rxjs.PairsObservable)

#### <a name="apidoc.element.rxjs.PairsObservable.PairsObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>PairsObservable (obj, scheduler)](#apidoc.element.rxjs.PairsObservable.PairsObservable)
- description and source-code
```javascript
function PairsObservable(obj, scheduler) {
    _super.call(this);
    this.obj = obj;
    this.scheduler = scheduler;
    this.keys = Object.keys(obj);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.PromiseObservable"></a>[module rxjs.PromiseObservable](#apidoc.module.rxjs.PromiseObservable)

#### <a name="apidoc.element.rxjs.PromiseObservable.PromiseObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>PromiseObservable (promise, scheduler)](#apidoc.element.rxjs.PromiseObservable.PromiseObservable)
- description and source-code
```javascript
function PromiseObservable(promise, scheduler) {
    _super.call(this);
    this.promise = promise;
    this.scheduler = scheduler;
}
```
- example usage
```shell
...
    }
    return new FromObservable(ish, scheduler);
}
else if (isArray_1.isArray(ish)) {
    return new ArrayObservable_1.ArrayObservable(ish, scheduler);
}
else if (isPromise_1.isPromise(ish)) {
    return new PromiseObservable_1.PromiseObservable(ish, scheduler);
}
else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
    return new IteratorObservable_1.IteratorObservable(ish, scheduler);
}
else if (isArrayLike_1.isArrayLike(ish)) {
    return new ArrayLikeObservable_1.ArrayLikeObservable(ish, scheduler);
}
...
```



# <a name="apidoc.module.rxjs.QueueAction"></a>[module rxjs.QueueAction](#apidoc.module.rxjs.QueueAction)

#### <a name="apidoc.element.rxjs.QueueAction.QueueAction"></a>[function <span class="apidocSignatureSpan">rxjs.</span>QueueAction (scheduler, work)](#apidoc.element.rxjs.QueueAction.QueueAction)
- description and source-code
```javascript
function QueueAction(scheduler, work) {
    _super.call(this, scheduler, work);
    this.scheduler = scheduler;
    this.work = work;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.QueueScheduler"></a>[module rxjs.QueueScheduler](#apidoc.module.rxjs.QueueScheduler)

#### <a name="apidoc.element.rxjs.QueueScheduler.QueueScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>QueueScheduler ()](#apidoc.element.rxjs.QueueScheduler.QueueScheduler)
- description and source-code
```javascript
function QueueScheduler() {
    _super.apply(this, arguments);
}
```
- example usage
```shell
...
 * // "after", 1
 *
 *
 * @static true
 * @name queue
 * @owner Scheduler
 */
exports.queue = new QueueScheduler_1.QueueScheduler(QueueAction_1.QueueAction);
//# sourceMappingURL=queue.js.map
...
```



# <a name="apidoc.module.rxjs.RangeObservable"></a>[module rxjs.RangeObservable](#apidoc.module.rxjs.RangeObservable)

#### <a name="apidoc.element.rxjs.RangeObservable.RangeObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>RangeObservable (start, count, scheduler)](#apidoc.element.rxjs.RangeObservable.RangeObservable)
- description and source-code
```javascript
function RangeObservable(start, count, scheduler) {
    _super.call(this);
    this.start = start;
    this._count = count;
    this.scheduler = scheduler;
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
...
 * @return {ConnectableObservable<T>}
 * @method publishReplay
 * @owner Observable
 */
function publishReplay(bufferSize, windowTime, scheduler) {
    if (bufferSize === void 0) { bufferSize = Number.POSITIVE_INFINITY; }
    if (windowTime === void 0) { windowTime = Number.POSITIVE_INFINITY; }
    return multicast_1.multicast.call(this, new ReplaySubject_1.ReplaySubject(bufferSize, windowTime, scheduler));
}
exports.publishReplay = publishReplay;
//# sourceMappingURL=publishReplay.js.map
...
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
...
    _super.call(this);
    this.scheduler = scheduler;
    this._events = [];
    this._bufferSize = bufferSize < 1 ? 1 : bufferSize;
    this._windowTime = windowTime < 1 ? 1 : windowTime;
}
ReplaySubject.prototype.next = function (value) {
    var now = this._getNow();
    this._events.push(new ReplayEvent(now, value));
    this._trimBufferThenGetEvents();
    _super.prototype.next.call(this, value);
};
ReplaySubject.prototype._subscribe = function (subscriber) {
    var _events = this._trimBufferThenGetEvents();
    var scheduler = this.scheduler;
...
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
...
            throw sink.syncErrorValue;
        }
    }
    return sink;
};
Observable.prototype._trySubscribe = function (sink) {
    try {
        return this._subscribe(sink);
    }
    catch (err) {
        sink.syncErrorThrown = true;
        sink.syncErrorValue = err;
        sink.error(err);
    }
};
...
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
...
    this._events = [];
    this._bufferSize = bufferSize < 1 ? 1 : bufferSize;
    this._windowTime = windowTime < 1 ? 1 : windowTime;
}
ReplaySubject.prototype.next = function (value) {
    var now = this._getNow();
    this._events.push(new ReplayEvent(now, value));
    this._trimBufferThenGetEvents();
    _super.prototype.next.call(this, value);
};
ReplaySubject.prototype._subscribe = function (subscriber) {
    var _events = this._trimBufferThenGetEvents();
    var scheduler = this.scheduler;
    var subscription;
    if (this.closed) {
...
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



# <a name="apidoc.module.rxjs.ScalarObservable"></a>[module rxjs.ScalarObservable](#apidoc.module.rxjs.ScalarObservable)

#### <a name="apidoc.element.rxjs.ScalarObservable.ScalarObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ScalarObservable (value, scheduler)](#apidoc.element.rxjs.ScalarObservable.ScalarObservable)
- description and source-code
```javascript
function ScalarObservable(value, scheduler) {
    _super.call(this);
    this.value = value;
    this.scheduler = scheduler;
    this._isScalar = true;
    if (scheduler) {
        this._isScalar = false;
    }
}
```
- example usage
```shell
...
}
ArrayLikeObservable.create = function (arrayLike, scheduler) {
    var length = arrayLike.length;
    if (length === 0) {
        return new EmptyObservable_1.EmptyObservable();
    }
    else if (length === 1) {
        return new ScalarObservable_1.ScalarObservable(arrayLike[0], scheduler);
    }
    else {
        return new ArrayLikeObservable(arrayLike, scheduler);
    }
};
ArrayLikeObservable.dispatch = function (state) {
    var arrayLike = state.arrayLike, index = state.index, length = state.length, subscriber = state.subscriber;
...
```



# <a name="apidoc.module.rxjs.Scheduler"></a>[module rxjs.Scheduler](#apidoc.module.rxjs.Scheduler)

#### <a name="apidoc.element.rxjs.Scheduler.Scheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Scheduler (SchedulerAction, now)](#apidoc.element.rxjs.Scheduler.Scheduler)
- description and source-code
```javascript
function Scheduler(SchedulerAction, now) {
    if (now === void 0) { now = Scheduler.now; }
    this.SchedulerAction = SchedulerAction;
    this.now = now;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.Set"></a>[module rxjs.Set](#apidoc.module.rxjs.Set)

#### <a name="apidoc.element.rxjs.Set.Set"></a>[function <span class="apidocSignatureSpan">rxjs.</span>Set ()](#apidoc.element.rxjs.Set.Set)
- description and source-code
```javascript
function Set() { [native code] }
```
- example usage
```shell
...
 * @extends {Ignored}
 */
var DistinctSubscriber = (function (_super) {
__extends(DistinctSubscriber, _super);
function DistinctSubscriber(destination, keySelector, flushes) {
    _super.call(this, destination);
    this.keySelector = keySelector;
    this.values = new Set_1.Set();
    if (flushes) {
        this.add(subscribeToResult_1.subscribeToResult(this, flushes));
    }
}
DistinctSubscriber.prototype.notifyNext = function (outerValue, innerValue, outerIndex, innerIndex, innerSub) {
    this.values.clear();
};
...
```

#### <a name="apidoc.element.rxjs.Set.minimalSetImpl"></a>[function <span class="apidocSignatureSpan">rxjs.Set.</span>minimalSetImpl ()](#apidoc.element.rxjs.Set.minimalSetImpl)
- description and source-code
```javascript
function minimalSetImpl() {
    // THIS IS NOT a full impl of Set, this is just the minimum
    // bits of functionality we need for this library.
    return (function () {
        function MinimalSet() {
            this._values = [];
        }
        MinimalSet.prototype.add = function (value) {
            if (!this.has(value)) {
                this._values.push(value);
            }
        };
        MinimalSet.prototype.has = function (value) {
            return this._values.indexOf(value) !== -1;
        };
        Object.defineProperty(MinimalSet.prototype, "size", {
            get: function () {
                return this._values.length;
            },
            enumerable: true,
            configurable: true
        });
        MinimalSet.prototype.clear = function () {
            this._values.length = 0;
        };
        return MinimalSet;
    }());
}
```
- example usage
```shell
n/a
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
...
        this.error(err);
    }
}
else {
    element = value;
}
if (!group) {
    group = this.subjectSelector ? this.subjectSelector() : new Subject_1.Subject();
    groups.set(key, group);
    var groupedObservable = new GroupedObservable(key, group, this);
    this.destination.next(groupedObservable);
    if (this.durationSelector) {
        var duration = void 0;
        try {
            duration = this.durationSelector(new GroupedObservable(key, group));
...
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
...
            throw sink.syncErrorValue;
        }
    }
    return sink;
};
Observable.prototype._trySubscribe = function (sink) {
    try {
        return this._subscribe(sink);
    }
    catch (err) {
        sink.syncErrorThrown = true;
        sink.syncErrorValue = err;
        sink.error(err);
    }
};
...
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
...
    Observable.prototype.subscribe = function (observerOrNext, error, complete) {
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
...
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
...
        else {
            this._connection = connection;
        }
    }
    return connection;
};
ConnectableObservable.prototype.refCount = function () {
    return this.lift(new RefCountOperator(this));
};
return ConnectableObservable;
}(Observable_1.Observable));
exports.ConnectableObservable = ConnectableObservable;
exports.connectableObservableDescriptor = {
operator: { value: null },
_refCount: { value: 0, writable: true },
...
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
...
        this.index = 0;
    }
    InnerSubscriber.prototype._next = function (value) {
        this.parent.notifyNext(this.outerValue, value, this.outerIndex, this.index++, this);
    };
    InnerSubscriber.prototype._error = function (error) {
        this.parent.notifyError(error, this);
        this.unsubscribe();
    };
    InnerSubscriber.prototype._complete = function () {
        this.parent.notifyComplete(this);
        this.unsubscribe();
    };
    return InnerSubscriber;
}(Subscriber_1.Subscriber));
...
```



# <a name="apidoc.module.rxjs.SubjectSubscription"></a>[module rxjs.SubjectSubscription](#apidoc.module.rxjs.SubjectSubscription)

#### <a name="apidoc.element.rxjs.SubjectSubscription.SubjectSubscription"></a>[function <span class="apidocSignatureSpan">rxjs.</span>SubjectSubscription (subject, subscriber)](#apidoc.element.rxjs.SubjectSubscription.SubjectSubscription)
- description and source-code
```javascript
function SubjectSubscription(subject, subscriber) {
    _super.call(this);
    this.subject = subject;
    this.subscriber = subscriber;
    this.closed = false;
}
```
- example usage
```shell
...
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
...
```



# <a name="apidoc.module.rxjs.SubscribeOnObservable"></a>[module rxjs.SubscribeOnObservable](#apidoc.module.rxjs.SubscribeOnObservable)

#### <a name="apidoc.element.rxjs.SubscribeOnObservable.SubscribeOnObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>SubscribeOnObservable (source, delayTime, scheduler)](#apidoc.element.rxjs.SubscribeOnObservable.SubscribeOnObservable)
- description and source-code
```javascript
function SubscribeOnObservable(source, delayTime, scheduler) {
    if (delayTime === void 0) { delayTime = 0; }
    if (scheduler === void 0) { scheduler = asap_1.asap; }
    _super.call(this);
    this.source = source;
    this.delayTime = delayTime;
    this.scheduler = scheduler;
    if (!isNumeric_1.isNumeric(delayTime) || delayTime < 0) {
        this.delayTime = 0;
    }
    if (!scheduler || typeof scheduler.schedule !== 'function') {
        this.scheduler = asap_1.asap;
    }
}
```
- example usage
```shell
...
exports.subscribeOn = subscribeOn;
var SubscribeOnOperator = (function () {
    function SubscribeOnOperator(scheduler, delay) {
        this.scheduler = scheduler;
        this.delay = delay;
    }
    SubscribeOnOperator.prototype.call = function (subscriber, source) {
        return new SubscribeOnObservable_1.SubscribeOnObservable(source, this.delay, this.scheduler).subscribe(subscriber);
    };
    return SubscribeOnOperator;
}());
//# sourceMappingURL=subscribeOn.js.map
...
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
...
 * @ignore
 * @extends {Ignored}
 */
var DoSubscriber = (function (_super) {
__extends(DoSubscriber, _super);
function DoSubscriber(destination, nextOrObserver, error, complete) {
    _super.call(this, destination);
    var safeSubscriber = new Subscriber_1.Subscriber(nextOrObserver, error, complete);
    safeSubscriber.syncErrorThrowable = true;
    this.add(safeSubscriber);
    this.safeSubscriber = safeSubscriber;
}
DoSubscriber.prototype._next = function (value) {
    var safeSubscriber = this.safeSubscriber;
    safeSubscriber.next(value);
...
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
...
 * 'complete' from the Observable. Notifies the Observer that the Observable
 * has finished sending push-based notifications.
 * @return {void}
 */
Subscriber.prototype.complete = function () {
    if (!this.isStopped) {
        this.isStopped = true;
        this._complete();
    }
};
Subscriber.prototype.unsubscribe = function () {
    if (this.closed) {
        return;
    }
    this.isStopped = true;
...
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
...
 * the Observable has experienced an error condition.
 * @param {any} [err] The 'error' exception.
 * @return {void}
 */
Subscriber.prototype.error = function (err) {
    if (!this.isStopped) {
        this.isStopped = true;
        this._error(err);
    }
};
/**
 * The {@link Observer} callback to receive a valueless notification of type
 * 'complete' from the Observable. Notifies the Observer that the Observable
 * has finished sending push-based notifications.
 * @return {void}
...
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
...
 * the Observable, with a value. The Observable may call this method 0 or more
 * times.
 * @param {T} [value] The 'next' value.
 * @return {void}
 */
Subscriber.prototype.next = function (value) {
    if (!this.isStopped) {
        this._next(value);
    }
};
/**
 * The {@link Observer} callback to receive notifications of type 'error' from
 * the Observable, with an attached {@link Error}. Notifies the Observer that
 * the Observable has experienced an error condition.
 * @param {any} [err] The 'error' exception.
...
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
...
            try {
                result = this.selector(err, this.caught);
            }
            catch (err2) {
                _super.prototype.error.call(this, err2);
                return;
            }
            this._unsubscribeAndRecycle();
            this.add(subscribeToResult_1.subscribeToResult(this, result));
        }
    };
    return CatchSubscriber;
}(OuterSubscriber_1.OuterSubscriber));
//# sourceMappingURL=catch.js.map
...
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
...
        this.index = 0;
    }
    InnerSubscriber.prototype._next = function (value) {
        this.parent.notifyNext(this.outerValue, value, this.outerIndex, this.index++, this);
    };
    InnerSubscriber.prototype._error = function (error) {
        this.parent.notifyError(error, this);
        this.unsubscribe();
    };
    InnerSubscriber.prototype._complete = function () {
        this.parent.notifyComplete(this);
        this.unsubscribe();
    };
    return InnerSubscriber;
}(Subscriber_1.Subscriber));
...
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
...
        this._subject = this.subjectFactory();
    }
    return this._subject;
};
ConnectableObservable.prototype.connect = function () {
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
...
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
...
            }
            break;
        default:
            throw new Error('unrecognized teardown ' + teardown + ' added to Subscription.');
    }
    var subscriptions = this._subscriptions || (this._subscriptions = []);
    subscriptions.push(subscription);
    subscription._addParent(this);
    return subscription;
};
/**
 * Removes a Subscription from the internal list of subscriptions that will
 * unsubscribe during the unsubscribe process of this Subscription.
 * @param {Subscription} subscription The subscription to remove.
 * @return {void}
...
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
...
    Observable.prototype.subscribe = function (observerOrNext, error, complete) {
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
...
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
...
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
...
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
...
        this.index = 0;
    }
    InnerSubscriber.prototype._next = function (value) {
        this.parent.notifyNext(this.outerValue, value, this.outerIndex, this.index++, this);
    };
    InnerSubscriber.prototype._error = function (error) {
        this.parent.notifyError(error, this);
        this.unsubscribe();
    };
    InnerSubscriber.prototype._complete = function () {
        this.parent.notifyComplete(this);
        this.unsubscribe();
    };
    return InnerSubscriber;
}(Subscriber_1.Subscriber));
...
```



# <a name="apidoc.module.rxjs.SubscriptionLog"></a>[module rxjs.SubscriptionLog](#apidoc.module.rxjs.SubscriptionLog)

#### <a name="apidoc.element.rxjs.SubscriptionLog.SubscriptionLog"></a>[function <span class="apidocSignatureSpan">rxjs.</span>SubscriptionLog (subscribedFrame, unsubscribedFrame)](#apidoc.element.rxjs.SubscriptionLog.SubscriptionLog)
- description and source-code
```javascript
function SubscriptionLog(subscribedFrame, unsubscribedFrame) {
    if (unsubscribedFrame === void 0) { unsubscribedFrame = Number.POSITIVE_INFINITY; }
    this.subscribedFrame = subscribedFrame;
    this.unsubscribedFrame = unsubscribedFrame;
}
```
- example usage
```shell
...
"use strict";
var SubscriptionLog_1 = require('./SubscriptionLog');
var SubscriptionLoggable = (function () {
function SubscriptionLoggable() {
    this.subscriptions = [];
}
SubscriptionLoggable.prototype.logSubscribedFrame = function () {
    this.subscriptions.push(new SubscriptionLog_1.SubscriptionLog(this.scheduler.now()));
    return this.subscriptions.length - 1;
};
SubscriptionLoggable.prototype.logUnsubscribedFrame = function (index) {
    var subscriptionLogs = this.subscriptions;
    var oldSubscriptionLog = subscriptionLogs[index];
    subscriptionLogs[index] = new SubscriptionLog_1.SubscriptionLog(oldSubscriptionLog.subscribedFrame, this.scheduler.now());
};
...
```



# <a name="apidoc.module.rxjs.SubscriptionLoggable"></a>[module rxjs.SubscriptionLoggable](#apidoc.module.rxjs.SubscriptionLoggable)

#### <a name="apidoc.element.rxjs.SubscriptionLoggable.SubscriptionLoggable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>SubscriptionLoggable ()](#apidoc.element.rxjs.SubscriptionLoggable.SubscriptionLoggable)
- description and source-code
```javascript
function SubscriptionLoggable() {
    this.subscriptions = [];
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
...
    }
    else if (this.isStopped) {
        subscriber.complete();
    }
    return subscription;
};
ReplaySubject.prototype._getNow = function () {
    return (this.scheduler || queue_1.queue).now();
};
ReplaySubject.prototype._trimBufferThenGetEvents = function () {
    var now = this._getNow();
    var _bufferSize = this._bufferSize;
    var _windowTime = this._windowTime;
    var _events = this._events;
    var eventsCount = _events.length;
...
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
...
TestScheduler.prototype.createColdObservable = function (marbles, values, error) {
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
};
TestScheduler.prototype.createHotObservable = function (marbles, values, error) {
    if (marbles.indexOf('!') !== -1) {
        throw new Error('hot observable cannot have unsubscription marker "!"');
...
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
...
};
TestScheduler.prototype.expectObservable = function (observable, unsubscriptionMarbles) {
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
...
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
...
QueueAction.prototype.schedule = function (state, delay) {
    if (delay === void 0) { delay = 0; }
    if (delay > 0) {
        return _super.prototype.schedule.call(this, state, delay);
    }
    this.delay = delay;
    this.state = state;
    this.scheduler.flush(this);
    return this;
};
QueueAction.prototype.execute = function (state, delay) {
    return (delay > 0 || this.closed) ?
        _super.prototype.execute.call(this, state, delay) :
        this._execute(state, delay);
};
...
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
...
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
...
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
...
 * @method timeout
 * @owner Observable
 */
function timeout(due, scheduler) {
if (scheduler === void 0) { scheduler = async_1.async; }
var absoluteTimeout = isDate_1.isDate(due);
var waitFor = absoluteTimeout ? (+due - scheduler.now()) : Math.abs(due);
return this.lift(new TimeoutOperator(waitFor, absoluteTimeout, scheduler, new TimeoutError_1.TimeoutError()));
}
exports.timeout = timeout;
var TimeoutOperator = (function () {
function TimeoutOperator(waitFor, absoluteTimeout, scheduler, errorInstance) {
    this.waitFor = waitFor;
    this.absoluteTimeout = absoluteTimeout;
    this.scheduler = scheduler;
...
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



# <a name="apidoc.module.rxjs.TimerObservable"></a>[module rxjs.TimerObservable](#apidoc.module.rxjs.TimerObservable)

#### <a name="apidoc.element.rxjs.TimerObservable.TimerObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>TimerObservable (dueTime, period, scheduler)](#apidoc.element.rxjs.TimerObservable.TimerObservable)
- description and source-code
```javascript
function TimerObservable(dueTime, period, scheduler) {
    if (dueTime === void 0) { dueTime = 0; }
    _super.call(this);
    this.period = -1;
    this.dueTime = 0;
    if (isNumeric_1.isNumeric(period)) {
        this.period = Number(period) < 1 && 1 || Number(period);
    }
    else if (isScheduler_1.isScheduler(period)) {
        scheduler = period;
    }
    if (!isScheduler_1.isScheduler(scheduler)) {
        scheduler = async_1.async;
    }
    this.scheduler = scheduler;
    this.dueTime = isDate_1.isDate(dueTime) ?
        (+dueTime - this.scheduler.now()) :
        dueTime;
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
...
                        errors.push(err);
                    }
                }
            }
        }
    }
    if (hasErrors) {
        throw new UnsubscriptionError_1.UnsubscriptionError(errors);
    }
};
/**
 * Adds a tear down to be called during the unsubscribe() of this
 * Subscription.
 *
 * If the tear down being added is a subscription that is already
...
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



# <a name="apidoc.module.rxjs.UsingObservable"></a>[module rxjs.UsingObservable](#apidoc.module.rxjs.UsingObservable)

#### <a name="apidoc.element.rxjs.UsingObservable.UsingObservable"></a>[function <span class="apidocSignatureSpan">rxjs.</span>UsingObservable (resourceFactory, observableFactory)](#apidoc.element.rxjs.UsingObservable.UsingObservable)
- description and source-code
```javascript
function UsingObservable(resourceFactory, observableFactory) {
    _super.call(this);
    this.resourceFactory = resourceFactory;
    this.observableFactory = observableFactory;
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
...
    }
    else if (this.isStopped) {
        subscriber.complete();
    }
    return subscription;
};
ReplaySubject.prototype._getNow = function () {
    return (this.scheduler || queue_1.queue).now();
};
ReplaySubject.prototype._trimBufferThenGetEvents = function () {
    var now = this._getNow();
    var _bufferSize = this._bufferSize;
    var _windowTime = this._windowTime;
    var _events = this._events;
    var eventsCount = _events.length;
...
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
...
QueueAction.prototype.schedule = function (state, delay) {
    if (delay === void 0) { delay = 0; }
    if (delay > 0) {
        return _super.prototype.schedule.call(this, state, delay);
    }
    this.delay = delay;
    this.state = state;
    this.scheduler.flush(this);
    return this;
};
QueueAction.prototype.execute = function (state, delay) {
    return (delay > 0 || this.closed) ?
        _super.prototype.execute.call(this, state, delay) :
        this._execute(state, delay);
};
...
```



# <a name="apidoc.module.rxjs.applyMixins"></a>[module rxjs.applyMixins](#apidoc.module.rxjs.applyMixins)

#### <a name="apidoc.element.rxjs.applyMixins.applyMixins"></a>[function <span class="apidocSignatureSpan">rxjs.</span>applyMixins (derivedCtor, baseCtors)](#apidoc.element.rxjs.applyMixins.applyMixins)
- description and source-code
```javascript
function applyMixins(derivedCtor, baseCtors) {
    for (var i = 0, len = baseCtors.length; i < len; i++) {
        var baseCtor = baseCtors[i];
        var propertyKeys = Object.getOwnPropertyNames(baseCtor.prototype);
        for (var j = 0, len2 = propertyKeys.length; j < len2; j++) {
            var name_1 = propertyKeys[j];
            derivedCtor.prototype[name_1] = baseCtor.prototype[name_1];
        }
    }
}
```
- example usage
```shell
...
                message.notification.observe(subscriber);
            }, message.frame, { message: message, subscriber: subscriber }));
        }
    };
    return ColdObservable;
}(Observable_1.Observable));
exports.ColdObservable = ColdObservable;
applyMixins_1.applyMixins(ColdObservable, [SubscriptionLoggable_1.SubscriptionLoggable]);
//# sourceMappingURL=ColdObservable.js.map
...
```



# <a name="apidoc.module.rxjs.assign"></a>[module rxjs.assign](#apidoc.module.rxjs.assign)

#### <a name="apidoc.element.rxjs.assign.assign"></a>[function <span class="apidocSignatureSpan">rxjs.</span>assign ()](#apidoc.element.rxjs.assign.assign)
- description and source-code
```javascript
function assign() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.assign.assignImpl"></a>[function <span class="apidocSignatureSpan">rxjs.assign.</span>assignImpl (target)](#apidoc.element.rxjs.assign.assignImpl)
- description and source-code
```javascript
function assignImpl(target) {
    var sources = [];
    for (var _i = 1; _i < arguments.length; _i++) {
        sources[_i - 1] = arguments[_i];
    }
    var len = sources.length;
    for (var i = 0; i < len; i++) {
        var source = sources[i];
        for (var k in source) {
            if (source.hasOwnProperty(k)) {
                target[k] = source[k];
            }
        }
    }
    return target;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.assign.getAssign"></a>[function <span class="apidocSignatureSpan">rxjs.assign.</span>getAssign (root)](#apidoc.element.rxjs.assign.getAssign)
- description and source-code
```javascript
function getAssign(root) {
    return root.Object.assign || assignImpl;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.audit"></a>[module rxjs.audit](#apidoc.module.rxjs.audit)

#### <a name="apidoc.element.rxjs.audit.audit"></a>[function <span class="apidocSignatureSpan">rxjs.</span>audit (durationSelector)](#apidoc.element.rxjs.audit.audit)
- description and source-code
```javascript
function audit(durationSelector) {
    return this.lift(new AuditOperator(durationSelector));
}
```
- example usage
```shell
...
* source value, which returns the "duration" Observable. When the duration
* Observable emits a value or completes, the timer is disabled, then the most
* recent source value is emitted on the output Observable, and this process
* repeats for the next source value.
*
* @example <caption>Emit clicks at a rate of at most one click per second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.audit(ev => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link auditTime}
* @see {@link debounce}
* @see {@link delayWhen}
* @see {@link sample}
* @see {@link throttle}
...
```



# <a name="apidoc.module.rxjs.auditTime"></a>[module rxjs.auditTime](#apidoc.module.rxjs.auditTime)

#### <a name="apidoc.element.rxjs.auditTime.auditTime"></a>[function <span class="apidocSignatureSpan">rxjs.</span>auditTime (duration, scheduler)](#apidoc.element.rxjs.auditTime.auditTime)
- description and source-code
```javascript
function auditTime(duration, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new AuditTimeOperator(duration, scheduler));
}
```
- example usage
```shell
...
* the time unit determined internally by the optional 'scheduler') has passed,
* the timer is disabled, then the most recent source value is emitted on the
* output Observable, and this process repeats for the next source value.
* Optionally takes a {@link IScheduler} for managing timers.
*
* @example <caption>Emit clicks at a rate of at most one click per second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.auditTime(1000);
* result.subscribe(x => console.log(x));
*
* @see {@link audit}
* @see {@link debounceTime}
* @see {@link delay}
* @see {@link sampleTime}
* @see {@link throttleTime}
...
```



# <a name="apidoc.module.rxjs.bindCallback"></a>[module rxjs.bindCallback](#apidoc.module.rxjs.bindCallback)

#### <a name="apidoc.element.rxjs.bindCallback.bindCallback"></a>[function <span class="apidocSignatureSpan">rxjs.</span>bindCallback (func, selector, scheduler)](#apidoc.element.rxjs.bindCallback.bindCallback)
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
...
* provides convenient error handling and probably is a better choice.
* 'bindCallback' will treat such functions without any difference and error parameter
* (whether passed or not) will always be interpreted as regular callback argument.
*
*
* @example <caption>Convert jQuery's getJSON to an Observable API</caption>
* // Suppose we have jQuery.getJSON('/my/url', callback)
* var getJSONAsObservable = Rx.Observable.bindCallback(jQuery.getJSON);
* var result = getJSONAsObservable('/my/url');
* result.subscribe(x => console.log(x), e => console.error(e));
*
*
* @example <caption>Receive array of arguments passed to callback</caption>
* someFunction((a, b, c) => {
*   console.log(a); // 5
...
```



# <a name="apidoc.module.rxjs.bindNodeCallback"></a>[module rxjs.bindNodeCallback](#apidoc.module.rxjs.bindNodeCallback)

#### <a name="apidoc.element.rxjs.bindNodeCallback.bindNodeCallback"></a>[function <span class="apidocSignatureSpan">rxjs.</span>bindNodeCallback (func, selector, scheduler)](#apidoc.element.rxjs.bindNodeCallback.bindNodeCallback)
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
...
*
* Note that even if error parameter is technically present in callback, but its value
* is falsy, it still won't appear in array emitted by Observable or in selector function.
*
*
* @example <caption>Read a file from the filesystem and get the data as an Observable</caption>
* import * as fs from 'fs';
* var readFileAsObservable = Rx.Observable.bindNodeCallback(fs.readFile);
* var result = readFileAsObservable('./roadNames.txt', 'utf8');
* result.subscribe(x => console.log(x), e => console.error(e));
*
*
* @example <caption>Use on function calling callback with multiple arguments</caption>
* someFunction((err, a, b) => {
*   console.log(err); // null
...
```



# <a name="apidoc.module.rxjs.buffer"></a>[module rxjs.buffer](#apidoc.module.rxjs.buffer)

#### <a name="apidoc.element.rxjs.buffer.buffer"></a>[function <span class="apidocSignatureSpan">rxjs.</span>buffer (closingNotifier)](#apidoc.element.rxjs.buffer.buffer)
- description and source-code
```javascript
function buffer(closingNotifier) {
    return this.lift(new BufferOperator(closingNotifier));
}
```
- example usage
```shell
...
* Observable emits a value, at which point it emits the buffer on the output
* Observable and starts a new buffer internally, awaiting the next time
* 'closingNotifier' emits.
*
* @example <caption>On every click, emit array of most recent interval events</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var interval = Rx.Observable.interval(1000);
* var buffered = interval.buffer(clicks);
* buffered.subscribe(x => console.log(x));
*
* @see {@link bufferCount}
* @see {@link bufferTime}
* @see {@link bufferToggle}
* @see {@link bufferWhen}
* @see {@link window}
...
```



# <a name="apidoc.module.rxjs.bufferCount"></a>[module rxjs.bufferCount](#apidoc.module.rxjs.bufferCount)

#### <a name="apidoc.element.rxjs.bufferCount.bufferCount"></a>[function <span class="apidocSignatureSpan">rxjs.</span>bufferCount (bufferSize, startBufferEvery)](#apidoc.element.rxjs.bufferCount.bufferCount)
- description and source-code
```javascript
function bufferCount(bufferSize, startBufferEvery) {
    if (startBufferEvery === void 0) { startBufferEvery = null; }
    return this.lift(new BufferCountOperator(bufferSize, startBufferEvery));
}
```
- example usage
```shell
...
* emits the buffer and clears it, and starts a new buffer each
* 'startBufferEvery' values. If 'startBufferEvery' is not provided or is
* 'null', then new buffers are started immediately at the start of the source
* and when each buffer closes and is emitted.
*
* @example <caption>Emit the last two click events as an array</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferCount(2);
* buffered.subscribe(x => console.log(x));
*
* @example <caption>On every click, emit the last two click events as an array</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferCount(2, 1);
* buffered.subscribe(x => console.log(x));
*
...
```



# <a name="apidoc.module.rxjs.bufferTime"></a>[module rxjs.bufferTime](#apidoc.module.rxjs.bufferTime)

#### <a name="apidoc.element.rxjs.bufferTime.bufferTime"></a>[function <span class="apidocSignatureSpan">rxjs.</span>bufferTime (bufferTimeSpan)](#apidoc.element.rxjs.bufferTime.bufferTime)
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
...
* 'bufferCreationInterval' milliseconds and closes (emits and resets) the
* buffer every 'bufferTimeSpan' milliseconds. When the optional argument
* 'maxBufferSize' is specified, the buffer will be closed either after
* 'bufferTimeSpan' milliseconds or when it contains 'maxBufferSize' elements.
*
* @example <caption>Every second, emit an array of the recent click events</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferTime(1000);
* buffered.subscribe(x => console.log(x));
*
* @example <caption>Every 5 seconds, emit the click events from the next 2 seconds</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferTime(2000, 5000);
* buffered.subscribe(x => console.log(x));
*
...
```



# <a name="apidoc.module.rxjs.bufferToggle"></a>[module rxjs.bufferToggle](#apidoc.module.rxjs.bufferToggle)

#### <a name="apidoc.element.rxjs.bufferToggle.bufferToggle"></a>[function <span class="apidocSignatureSpan">rxjs.</span>bufferToggle (openings, closingSelector)](#apidoc.element.rxjs.bufferToggle.bufferToggle)
- description and source-code
```javascript
function bufferToggle(openings, closingSelector) {
    return this.lift(new BufferToggleOperator(openings, closingSelector));
}
```
- example usage
```shell
...
* Buffers values from the source by opening the buffer via signals from an
* Observable provided to 'openings', and closing and sending the buffers when
* a Subscribable or Promise returned by the 'closingSelector' function emits.
*
* @example <caption>Every other second, emit the click events from the next 500ms</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var openings = Rx.Observable.interval(1000);
* var buffered = clicks.bufferToggle(openings, i =>
*   i % 2 ? Rx.Observable.interval(500) : Rx.Observable.empty()
* );
* buffered.subscribe(x => console.log(x));
*
* @see {@link buffer}
* @see {@link bufferCount}
* @see {@link bufferTime}
...
```



# <a name="apidoc.module.rxjs.bufferWhen"></a>[module rxjs.bufferWhen](#apidoc.module.rxjs.bufferWhen)

#### <a name="apidoc.element.rxjs.bufferWhen.bufferWhen"></a>[function <span class="apidocSignatureSpan">rxjs.</span>bufferWhen (closingSelector)](#apidoc.element.rxjs.bufferWhen.bufferWhen)
- description and source-code
```javascript
function bufferWhen(closingSelector) {
    return this.lift(new BufferWhenOperator(closingSelector));
}
```
- example usage
```shell
...
*
* Opens a buffer immediately, then closes the buffer when the observable
* returned by calling 'closingSelector' function emits a value. When it closes
* the buffer, it immediately opens a new buffer and repeats the process.
*
* @example <caption>Emit an array of the last clicks every [1-5] random seconds</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var buffered = clicks.bufferWhen(() =>
*   Rx.Observable.interval(1000 + Math.random() * 4000)
* );
* buffered.subscribe(x => console.log(x));
*
* @see {@link buffer}
* @see {@link bufferCount}
* @see {@link bufferTime}
...
```



# <a name="apidoc.module.rxjs.catch"></a>[module rxjs.catch](#apidoc.module.rxjs.catch)

#### <a name="apidoc.element.rxjs.catch._catch"></a>[function <span class="apidocSignatureSpan">rxjs.catch.</span>_catch (selector)](#apidoc.element.rxjs.catch._catch)
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



# <a name="apidoc.module.rxjs.combineAll"></a>[module rxjs.combineAll](#apidoc.module.rxjs.combineAll)

#### <a name="apidoc.element.rxjs.combineAll.combineAll"></a>[function <span class="apidocSignatureSpan">rxjs.</span>combineAll (project)](#apidoc.element.rxjs.combineAll.combineAll)
- description and source-code
```javascript
function combineAll(project) {
    return this.lift(new combineLatest_1.CombineLatestOperator(project));
}
```
- example usage
```shell
...
*     values is emitted by the output Observable.
*
* @example <caption>Map two click events to a finite interval Observable, then apply combineAll</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map(ev =>
*   Rx.Observable.interval(Math.random()*2000).take(3)
* ).take(2);
* var result = higherOrder.combineAll();
* result.subscribe(x => console.log(x));
*
* @see {@link combineLatest}
* @see {@link mergeAll}
*
* @param {function} [project] An optional function to map the most recent
* values from each inner Observable into a new result. Takes each of the most
...
```



# <a name="apidoc.module.rxjs.combineLatest"></a>[module rxjs.combineLatest](#apidoc.module.rxjs.combineLatest)

#### <a name="apidoc.element.rxjs.combineLatest.combineLatest"></a>[function <span class="apidocSignatureSpan">rxjs.</span>combineLatest ()](#apidoc.element.rxjs.combineLatest.combineLatest)
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
...
* of values, but values themselves. That means default 'project' can be imagined
* as function that takes all its arguments and puts them into an array.
*
*
* @example <caption>Combine two timer Observables</caption>
* const firstTimer = Rx.Observable.timer(0, 1000); // emit 0, 1, 2... after every second, starting from now
* const secondTimer = Rx.Observable.timer(500, 1000); // emit 0, 1, 2... after every second, starting 0,5s from now
* const combinedTimers = Rx.Observable.combineLatest(firstTimer, secondTimer);
* combinedTimers.subscribe(value => console.log(value));
* // Logs
* // [0, 0] after 0.5s
* // [1, 0] after 1s
* // [1, 1] after 1.5s
* // [2, 1] after 2s
*
...
```



# <a name="apidoc.module.rxjs.concat"></a>[module rxjs.concat](#apidoc.module.rxjs.concat)

#### <a name="apidoc.element.rxjs.concat.concat"></a>[function <span class="apidocSignatureSpan">rxjs.</span>concat ()](#apidoc.element.rxjs.concat.concat)
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
...
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
...
```



# <a name="apidoc.module.rxjs.concatAll"></a>[module rxjs.concatAll](#apidoc.module.rxjs.concatAll)

#### <a name="apidoc.element.rxjs.concatAll.concatAll"></a>[function <span class="apidocSignatureSpan">rxjs.</span>concatAll ()](#apidoc.element.rxjs.concatAll.concatAll)
- description and source-code
```javascript
function concatAll() {
    return this.lift(new mergeAll_1.MergeAllOperator(1));
}
```
- example usage
```shell
...
*
* Note: 'concatAll' is equivalent to 'mergeAll' with concurrency parameter set
* to '1'.
*
* @example <caption>For each click event, tick every second from 0 to 3, with no concurrency</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map(ev => Rx.Observable.interval(1000).take(4));
* var firstOrder = higherOrder.concatAll();
* firstOrder.subscribe(x => console.log(x));
*
* // Results in the following:
* // (results are not concurrent)
* // For every click on the "document" it will emit values 0 to 3 spaced
* // on a 1000ms interval
* // one click = 1000ms-> 0 -1000ms-> 1 -1000ms-> 2 -1000ms-> 3
...
```



# <a name="apidoc.module.rxjs.concatMap"></a>[module rxjs.concatMap](#apidoc.module.rxjs.concatMap)

#### <a name="apidoc.element.rxjs.concatMap.concatMap"></a>[function <span class="apidocSignatureSpan">rxjs.</span>concatMap (project, resultSelector)](#apidoc.element.rxjs.concatMap.concatMap)
- description and source-code
```javascript
function concatMap(project, resultSelector) {
    return this.lift(new mergeMap_1.MergeMapOperator(project, resultSelector, 1));
}
```
- example usage
```shell
...
* be subscribed to.
*
* Note: 'concatMap' is equivalent to 'mergeMap' with concurrency parameter set
* to '1'.
*
* @example <caption>For each click event, tick every second from 0 to 3, with no concurrency</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.concatMap(ev => Rx.Observable.interval(1000).take(4));
* result.subscribe(x => console.log(x));
*
* // Results in the following:
* // (results are not concurrent)
* // For every click on the "document" it will emit values 0 to 3 spaced
* // on a 1000ms interval
* // one click = 1000ms-> 0 -1000ms-> 1 -1000ms-> 2 -1000ms-> 3
...
```



# <a name="apidoc.module.rxjs.concatMapTo"></a>[module rxjs.concatMapTo](#apidoc.module.rxjs.concatMapTo)

#### <a name="apidoc.element.rxjs.concatMapTo.concatMapTo"></a>[function <span class="apidocSignatureSpan">rxjs.</span>concatMapTo (innerObservable, resultSelector)](#apidoc.element.rxjs.concatMapTo.concatMapTo)
- description and source-code
```javascript
function concatMapTo(innerObservable, resultSelector) {
    return this.lift(new mergeMapTo_1.MergeMapToOperator(innerObservable, resultSelector, 1));
}
```
- example usage
```shell
...
* be subscribed to.
*
* Note: 'concatMapTo' is equivalent to 'mergeMapTo' with concurrency parameter
* set to '1'.
*
* @example <caption>For each click event, tick every second from 0 to 3, with no concurrency</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.concatMapTo(Rx.Observable.interval(1000).take(4));
* result.subscribe(x => console.log(x));
*
* // Results in the following:
* // (results are not concurrent)
* // For every click on the "document" it will emit values 0 to 3 spaced
* // on a 1000ms interval
* // one click = 1000ms-> 0 -1000ms-> 1 -1000ms-> 2 -1000ms-> 3
...
```



# <a name="apidoc.module.rxjs.count"></a>[module rxjs.count](#apidoc.module.rxjs.count)

#### <a name="apidoc.element.rxjs.count.count"></a>[function <span class="apidocSignatureSpan">rxjs.</span>count (predicate)](#apidoc.element.rxjs.count.count)
- description and source-code
```javascript
function count(predicate) {
    return this.lift(new CountOperator(predicate, this));
}
```
- example usage
```shell
...
* as argument, in which case the output emission will represent the number of
* source values that matched 'true' with the 'predicate'.
*
* @example <caption>Counts how many seconds have passed before the first click happened</caption>
* var seconds = Rx.Observable.interval(1000);
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var secondsBeforeClick = seconds.takeUntil(clicks);
* var result = secondsBeforeClick.count();
* result.subscribe(x => console.log(x));
*
* @example <caption>Counts how many odd numbers are there between 1 and 7</caption>
* var numbers = Rx.Observable.range(1, 7);
* var result = numbers.count(i => i % 2 === 1);
* result.subscribe(x => console.log(x));
*
...
```



# <a name="apidoc.module.rxjs.debounce"></a>[module rxjs.debounce](#apidoc.module.rxjs.debounce)

#### <a name="apidoc.element.rxjs.debounce.debounce"></a>[function <span class="apidocSignatureSpan">rxjs.</span>debounce (durationSelector)](#apidoc.element.rxjs.debounce.debounce)
- description and source-code
```javascript
function debounce(durationSelector) {
    return this.lift(new DebounceOperator(durationSelector));
}
```
- example usage
```shell
...
*
* Like {@link debounceTime}, this is a rate-limiting operator, and also a
* delay-like operator since output emissions do not necessarily occur at the
* same time as they did on the source Observable.
*
* @example <caption>Emit the most recent click after a burst of clicks</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.debounce(() => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link audit}
* @see {@link debounceTime}
* @see {@link delayWhen}
* @see {@link throttle}
*
...
```



# <a name="apidoc.module.rxjs.debounceTime"></a>[module rxjs.debounceTime](#apidoc.module.rxjs.debounceTime)

#### <a name="apidoc.element.rxjs.debounceTime.debounceTime"></a>[function <span class="apidocSignatureSpan">rxjs.</span>debounceTime (dueTime, scheduler)](#apidoc.element.rxjs.debounceTime.debounceTime)
- description and source-code
```javascript
function debounceTime(dueTime, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new DebounceTimeOperator(dueTime, scheduler));
}
```
- example usage
```shell
...
* value to be emitted in any time window of duration 'dueTime', but it is also
* a delay-like operator since output emissions do not occur at the same time as
* they did on the source Observable. Optionally takes a {@link IScheduler} for
* managing timers.
*
* @example <caption>Emit the most recent click after a burst of clicks</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.debounceTime(1000);
* result.subscribe(x => console.log(x));
*
* @see {@link auditTime}
* @see {@link debounce}
* @see {@link delay}
* @see {@link sampleTime}
* @see {@link throttleTime}
...
```



# <a name="apidoc.module.rxjs.defaultIfEmpty"></a>[module rxjs.defaultIfEmpty](#apidoc.module.rxjs.defaultIfEmpty)

#### <a name="apidoc.element.rxjs.defaultIfEmpty.defaultIfEmpty"></a>[function <span class="apidocSignatureSpan">rxjs.</span>defaultIfEmpty (defaultValue)](#apidoc.element.rxjs.defaultIfEmpty.defaultIfEmpty)
- description and source-code
```javascript
function defaultIfEmpty(defaultValue) {
    if (defaultValue === void 0) { defaultValue = null; }
    return this.lift(new DefaultIfEmptyOperator(defaultValue));
}
```
- example usage
```shell
...
* 'defaultIfEmpty' emits the values emitted by the source Observable or a
* specified default value if the source Observable is empty (completes without
* having emitted any 'next' value).
*
* @example <caption>If no clicks happen in 5 seconds, then emit "no clicks"</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var clicksBeforeFive = clicks.takeUntil(Rx.Observable.interval(5000));
* var result = clicksBeforeFive.defaultIfEmpty('no clicks');
* result.subscribe(x => console.log(x));
*
* @see {@link empty}
* @see {@link last}
*
* @param {any} [defaultValue=null] The default value used if the source
* Observable is empty.
...
```



# <a name="apidoc.module.rxjs.defer"></a>[module rxjs.defer](#apidoc.module.rxjs.defer)

#### <a name="apidoc.element.rxjs.defer.defer"></a>[function <span class="apidocSignatureSpan">rxjs.</span>defer (observableFactory)](#apidoc.element.rxjs.defer.defer)
- description and source-code
```javascript
defer = function (observableFactory) {
    return new DeferObservable(observableFactory);
}
```
- example usage
```shell
...
* an Observer subscribes to it, and then it generates an Observable,
* typically with an Observable factory function. It does this afresh for each
* subscriber, so although each subscriber may think it is subscribing to the
* same Observable, in fact each subscriber gets its own individual
* Observable.
*
* @example <caption>Subscribe to either an Observable of clicks or an Observable of interval, at random</caption>
* var clicksOrInterval = Rx.Observable.defer(function () {
*   if (Math.random() > 0.5) {
*     return Rx.Observable.fromEvent(document, 'click');
*   } else {
*     return Rx.Observable.interval(1000);
*   }
* });
* clicksOrInterval.subscribe(x => console.log(x));
...
```



# <a name="apidoc.module.rxjs.delay"></a>[module rxjs.delay](#apidoc.module.rxjs.delay)

#### <a name="apidoc.element.rxjs.delay.delay"></a>[function <span class="apidocSignatureSpan">rxjs.</span>delay (delay, scheduler)](#apidoc.element.rxjs.delay.delay)
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
...
* // [1, 0] after 1s
* // [1, 1] after 1.5s
* // [2, 1] after 2s
*
*
* @example <caption>Combine an array of Observables</caption>
* const observables = [1, 5, 10].map(
*   n => Rx.Observable.of(n).delay(n * 1000).startWith(0) // emit 0 and then emit n after n seconds
* );
* const combined = Rx.Observable.combineLatest(observables);
* combined.subscribe(value => console.log(value));
* // Logs
* // [0, 0, 0] immediately
* // [1, 0, 0] after 1s
* // [1, 5, 0] after 5s
...
```



# <a name="apidoc.module.rxjs.delayWhen"></a>[module rxjs.delayWhen](#apidoc.module.rxjs.delayWhen)

#### <a name="apidoc.element.rxjs.delayWhen.delayWhen"></a>[function <span class="apidocSignatureSpan">rxjs.</span>delayWhen (delayDurationSelector, subscriptionDelay)](#apidoc.element.rxjs.delayWhen.delayWhen)
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
...
* completes, the source Observable is subscribed to and starts behaving like
* described in the previous paragraph. If 'subscriptionDelay' is not provided,
* 'delayWhen' will subscribe to the source Observable as soon as the output
* Observable is subscribed.
*
* @example <caption>Delay each click by a random amount of time, between 0 and 5 seconds</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var delayedClicks = clicks.delayWhen(event =>
*   Rx.Observable.interval(Math.random() * 5000)
* );
* delayedClicks.subscribe(x => console.log(x));
*
* @see {@link debounce}
* @see {@link delay}
*
...
```



# <a name="apidoc.module.rxjs.dematerialize"></a>[module rxjs.dematerialize](#apidoc.module.rxjs.dematerialize)

#### <a name="apidoc.element.rxjs.dematerialize.dematerialize"></a>[function <span class="apidocSignatureSpan">rxjs.</span>dematerialize ()](#apidoc.element.rxjs.dematerialize.dematerialize)
- description and source-code
```javascript
function dematerialize() {
    return this.lift(new DeMaterializeOperator());
}
```
- example usage
```shell
...
* @example <caption>Convert an Observable of Notifications to an actual Observable</caption>
* var notifA = new Rx.Notification('N', 'A');
* var notifB = new Rx.Notification('N', 'B');
* var notifE = new Rx.Notification('E', void 0,
*   new TypeError('x.toUpperCase is not a function')
* );
* var materialized = Rx.Observable.of(notifA, notifB, notifE);
* var upperCase = materialized.dematerialize();
* upperCase.subscribe(x => console.log(x), e => console.error(e));
*
* // Results in:
* // A
* // B
* // TypeError: x.toUpperCase is not a function
*
...
```



# <a name="apidoc.module.rxjs.distinct"></a>[module rxjs.distinct](#apidoc.module.rxjs.distinct)

#### <a name="apidoc.element.rxjs.distinct.distinct"></a>[function <span class="apidocSignatureSpan">rxjs.</span>distinct (keySelector, flushes)](#apidoc.element.rxjs.distinct.distinct)
- description and source-code
```javascript
function distinct(keySelector, flushes) {
    return this.lift(new DistinctOperator(keySelector, flushes));
}
```
- example usage
```shell
...
* In other runtimes, this operator will use a minimal implementation of 'Set' that relies on an 'Array' and 'indexOf' under the
* hood, so performance will degrade as more values are checked for distinction. Even in newer browsers, a long-running 'distinct
'
* use might result in memory leaks. To help alleviate this in some scenarios, an optional 'flushes' parameter is also provided so
* that the internal 'Set' can be "flushed", basically clearing it of values.
*
* @example <caption>A simple example with numbers</caption>
* Observable.of(1, 1, 2, 2, 2, 1, 2, 3, 4, 3, 2, 1)
*   .distinct()
*   .subscribe(x => console.log(x)); // 1, 2, 3, 4
*
* @example <caption>An example using a keySelector function</caption>
* interface Person {
*    age: number,
*    name: string
* }
...
```

#### <a name="apidoc.element.rxjs.distinct.DistinctSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.distinct.</span>DistinctSubscriber (destination, keySelector, flushes)](#apidoc.element.rxjs.distinct.DistinctSubscriber)
- description and source-code
```javascript
function DistinctSubscriber(destination, keySelector, flushes) {
    _super.call(this, destination);
    this.keySelector = keySelector;
    this.values = new Set_1.Set();
    if (flushes) {
        this.add(subscribeToResult_1.subscribeToResult(this, flushes));
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.distinctUntilChanged"></a>[module rxjs.distinctUntilChanged](#apidoc.module.rxjs.distinctUntilChanged)

#### <a name="apidoc.element.rxjs.distinctUntilChanged.distinctUntilChanged"></a>[function <span class="apidocSignatureSpan">rxjs.</span>distinctUntilChanged (compare, keySelector)](#apidoc.element.rxjs.distinctUntilChanged.distinctUntilChanged)
- description and source-code
```javascript
function distinctUntilChanged(compare, keySelector) {
    return this.lift(new DistinctUntilChangedOperator(compare, keySelector));
}
```
- example usage
```shell
...
*
* If a comparator function is provided, then it will be called for each item to test for whether or not that value should be emitted
.
*
* If a comparator function is not provided, an equality check is used by default.
*
* @example <caption>A simple example with numbers</caption>
* Observable.of(1, 1, 2, 2, 2, 1, 1, 2, 3, 3, 4)
*   .distinctUntilChanged()
*   .subscribe(x => console.log(x)); // 1, 2, 1, 2, 3, 4
*
* @example <caption>An example using a compare function</caption>
* interface Person {
*    age: number,
*    name: string
* }
...
```



# <a name="apidoc.module.rxjs.distinctUntilKeyChanged"></a>[module rxjs.distinctUntilKeyChanged](#apidoc.module.rxjs.distinctUntilKeyChanged)

#### <a name="apidoc.element.rxjs.distinctUntilKeyChanged.distinctUntilKeyChanged"></a>[function <span class="apidocSignatureSpan">rxjs.</span>distinctUntilKeyChanged (key, compare)](#apidoc.element.rxjs.distinctUntilKeyChanged.distinctUntilKeyChanged)
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
...
*  }
*
* Observable.of<Person>(
*     { age: 4, name: 'Foo'},
*     { age: 7, name: 'Bar'},
*     { age: 5, name: 'Foo'},
*     { age: 6, name: 'Foo'})
*     .distinctUntilKeyChanged('name')
*     .subscribe(x => console.log(x));
*
* // displays:
* // { age: 4, name: 'Foo' }
* // { age: 7, name: 'Bar' }
* // { age: 5, name: 'Foo' }
*
...
```



# <a name="apidoc.module.rxjs.do"></a>[module rxjs.do](#apidoc.module.rxjs.do)

#### <a name="apidoc.element.rxjs.do._do"></a>[function <span class="apidocSignatureSpan">rxjs.do.</span>_do (nextOrObserver, error, complete)](#apidoc.element.rxjs.do._do)
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



# <a name="apidoc.module.rxjs.elementAt"></a>[module rxjs.elementAt](#apidoc.module.rxjs.elementAt)

#### <a name="apidoc.element.rxjs.elementAt.elementAt"></a>[function <span class="apidocSignatureSpan">rxjs.</span>elementAt (index, defaultValue)](#apidoc.element.rxjs.elementAt.elementAt)
- description and source-code
```javascript
function elementAt(index, defaultValue) {
    return this.lift(new ElementAtOperator(index, defaultValue));
}
```
- example usage
```shell
...
* 'index' in the source Observable, or a default value if that 'index' is out
* of range and the 'default' argument is provided. If the 'default' argument is
* not given and the 'index' is out of range, the output Observable will emit an
* 'ArgumentOutOfRangeError' error.
*
* @example <caption>Emit only the third click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.elementAt(2);
* result.subscribe(x => console.log(x));
*
* // Results in:
* // click 1 = nothing
* // click 2 = nothing
* // click 3 = MouseEvent object logged to console
*
...
```



# <a name="apidoc.module.rxjs.empty"></a>[module rxjs.empty](#apidoc.module.rxjs.empty)

#### <a name="apidoc.element.rxjs.empty.empty"></a>[function <span class="apidocSignatureSpan">rxjs.</span>empty (scheduler)](#apidoc.element.rxjs.empty.empty)
- description and source-code
```javascript
empty = function (scheduler) {
    return new EmptyObservable(scheduler);
}
```
- example usage
```shell
...
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
};
/**
 * A shortcut to create a Notification instance of the type 'next' from a
 * given value.
 * @param {T} value The 'next' value.
...
```



# <a name="apidoc.module.rxjs.every"></a>[module rxjs.every](#apidoc.module.rxjs.every)

#### <a name="apidoc.element.rxjs.every.every"></a>[function <span class="apidocSignatureSpan">rxjs.</span>every (predicate, thisArg)](#apidoc.element.rxjs.every.every)
- description and source-code
```javascript
function every(predicate, thisArg) {
    return this.lift(new EveryOperator(predicate, thisArg, this));
}
```
- example usage
```shell
...
};
var Subscriber_1 = require('../Subscriber');
/**
* Returns an Observable that emits whether or not every item of the source satisfies the condition specified.
*
* @example <caption>A simple example emitting true if all elements are less than 5, false otherwise</caption>
*  Observable.of(1, 2, 3, 4, 5, 6)
*     .every(x => x < 5)
*     .subscribe(x => console.log(x)); // -> false
*
* @param {function} predicate A function for determining if an item meets a specified condition.
* @param {any} [thisArg] Optional object to use for 'this' in the callback.
* @return {Observable} An Observable of booleans that determines if all items of the source Observable meet the condition specified
.
* @method every
* @owner Observable
...
```



# <a name="apidoc.module.rxjs.exhaust"></a>[module rxjs.exhaust](#apidoc.module.rxjs.exhaust)

#### <a name="apidoc.element.rxjs.exhaust.exhaust"></a>[function <span class="apidocSignatureSpan">rxjs.</span>exhaust ()](#apidoc.element.rxjs.exhaust.exhaust)
- description and source-code
```javascript
function exhaust() {
    return this.lift(new SwitchFirstOperator());
}
```
- example usage
```shell
...
* 'exhaust' ignores every new inner Observable if the previous Observable has
* not yet completed. Once that one completes, it will accept and flatten the
* next inner Observable and repeat this process.
*
* @example <caption>Run a finite timer for each click, only if there is no currently active timer</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map((ev) => Rx.Observable.interval(1000));
* var result = higherOrder.exhaust();
* result.subscribe(x => console.log(x));
*
* @see {@link combineAll}
* @see {@link concatAll}
* @see {@link switch}
* @see {@link mergeAll}
* @see {@link exhaustMap}
...
```



# <a name="apidoc.module.rxjs.exhaustMap"></a>[module rxjs.exhaustMap](#apidoc.module.rxjs.exhaustMap)

#### <a name="apidoc.element.rxjs.exhaustMap.exhaustMap"></a>[function <span class="apidocSignatureSpan">rxjs.</span>exhaustMap (project, resultSelector)](#apidoc.element.rxjs.exhaustMap.exhaustMap)
- description and source-code
```javascript
function exhaustMap(project, resultSelector) {
    return this.lift(new SwitchFirstMapOperator(project, resultSelector));
}
```
- example usage
```shell
...
* that projected Observable. However, 'exhaustMap' ignores every new projected
* Observable if the previous projected Observable has not yet completed. Once
* that one completes, it will accept and flatten the next projected Observable
* and repeat this process.
*
* @example <caption>Run a finite timer for each click, only if there is no currently active timer</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.exhaustMap((ev) => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link concatMap}
* @see {@link exhaust}
* @see {@link mergeMap}
* @see {@link switchMap}
*
...
```



# <a name="apidoc.module.rxjs.expand"></a>[module rxjs.expand](#apidoc.module.rxjs.expand)

#### <a name="apidoc.element.rxjs.expand.expand"></a>[function <span class="apidocSignatureSpan">rxjs.</span>expand (project, concurrent, scheduler)](#apidoc.element.rxjs.expand.expand)
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
...
* given to the 'project' function to produce new output values. This is how
* *expand* behaves recursively.
*
* @example <caption>Start emitting the powers of two on every click, at most 10 of them</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var powersOfTwo = clicks
*   .mapTo(1)
*   .expand(x => Rx.Observable.of(2 * x).delay(1000))
*   .take(10);
* powersOfTwo.subscribe(x => console.log(x));
*
* @see {@link mergeMap}
* @see {@link mergeScan}
*
* @param {function(value: T, index: number) => Observable} project A function
...
```

#### <a name="apidoc.element.rxjs.expand.ExpandOperator"></a>[function <span class="apidocSignatureSpan">rxjs.expand.</span>ExpandOperator (project, concurrent, scheduler)](#apidoc.element.rxjs.expand.ExpandOperator)
- description and source-code
```javascript
function ExpandOperator(project, concurrent, scheduler) {
    this.project = project;
    this.concurrent = concurrent;
    this.scheduler = scheduler;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.expand.ExpandSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.expand.</span>ExpandSubscriber (destination, project, concurrent, scheduler)](#apidoc.element.rxjs.expand.ExpandSubscriber)
- description and source-code
```javascript
function ExpandSubscriber(destination, project, concurrent, scheduler) {
    _super.call(this, destination);
    this.project = project;
    this.concurrent = concurrent;
    this.scheduler = scheduler;
    this.index = 0;
    this.active = 0;
    this.hasCompleted = false;
    if (concurrent < Number.POSITIVE_INFINITY) {
        this.buffer = [];
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.filter"></a>[module rxjs.filter](#apidoc.module.rxjs.filter)

#### <a name="apidoc.element.rxjs.filter.filter"></a>[function <span class="apidocSignatureSpan">rxjs.</span>filter (predicate, thisArg)](#apidoc.element.rxjs.filter.filter)
- description and source-code
```javascript
function filter(predicate, thisArg) {
    return this.lift(new FilterOperator(predicate, thisArg));
}
```
- example usage
```shell
...
var Subscriber_1 = require('../Subscriber');
/* tslint:enable:max-line-length */
/**
* Filter items emitted by the source Observable by only emitting those that
* satisfy a specified predicate.
*
* <span class="informal">Like
* [Array.prototype.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter),
* it only emits a value from the source if it passes a criterion function.</span>
*
* <img src="./img/filter.png" width="100%">
*
* Similar to the well-known 'Array.prototype.filter' method, this operator
* takes values from the source Observable, passes them through a 'predicate'
* function and only emits those values that yielded 'true'.
...
```



# <a name="apidoc.module.rxjs.finally"></a>[module rxjs.finally](#apidoc.module.rxjs.finally)

#### <a name="apidoc.element.rxjs.finally._finally"></a>[function <span class="apidocSignatureSpan">rxjs.finally.</span>_finally (callback)](#apidoc.element.rxjs.finally._finally)
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



# <a name="apidoc.module.rxjs.find"></a>[module rxjs.find](#apidoc.module.rxjs.find)

#### <a name="apidoc.element.rxjs.find.find"></a>[function <span class="apidocSignatureSpan">rxjs.</span>find (predicate, thisArg)](#apidoc.element.rxjs.find.find)
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
...
* 'find' searches for the first item in the source Observable that matches the
* specified condition embodied by the 'predicate', and returns the first
* occurrence in the source. Unlike {@link first}, the 'predicate' is required
* in 'find', and does not emit an error if a valid value is not found.
*
* @example <caption>Find and emit the first click that happens on a DIV element</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.find(ev => ev.target.tagName === 'DIV');
* result.subscribe(x => console.log(x));
*
* @see {@link filter}
* @see {@link first}
* @see {@link findIndex}
* @see {@link take}
*
...
```

#### <a name="apidoc.element.rxjs.find.FindValueOperator"></a>[function <span class="apidocSignatureSpan">rxjs.find.</span>FindValueOperator (predicate, source, yieldIndex, thisArg)](#apidoc.element.rxjs.find.FindValueOperator)
- description and source-code
```javascript
function FindValueOperator(predicate, source, yieldIndex, thisArg) {
    this.predicate = predicate;
    this.source = source;
    this.yieldIndex = yieldIndex;
    this.thisArg = thisArg;
}
```
- example usage
```shell
...
 * in the 'predicate' function.
 * @return {Observable} An Observable of the index of the first item that
 * matches the condition.
 * @method find
 * @owner Observable
 */
function findIndex(predicate, thisArg) {
    return this.lift(new find_1.FindValueOperator(predicate, this, true, thisArg));
}
exports.findIndex = findIndex;
//# sourceMappingURL=findIndex.js.map
...
```

#### <a name="apidoc.element.rxjs.find.FindValueSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.find.</span>FindValueSubscriber (destination, predicate, source, yieldIndex, thisArg)](#apidoc.element.rxjs.find.FindValueSubscriber)
- description and source-code
```javascript
function FindValueSubscriber(destination, predicate, source, yieldIndex, thisArg) {
    _super.call(this, destination);
    this.predicate = predicate;
    this.source = source;
    this.yieldIndex = yieldIndex;
    this.thisArg = thisArg;
    this.index = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.findIndex"></a>[module rxjs.findIndex](#apidoc.module.rxjs.findIndex)

#### <a name="apidoc.element.rxjs.findIndex.findIndex"></a>[function <span class="apidocSignatureSpan">rxjs.</span>findIndex (predicate, thisArg)](#apidoc.element.rxjs.findIndex.findIndex)
- description and source-code
```javascript
function findIndex(predicate, thisArg) {
    return this.lift(new find_1.FindValueOperator(predicate, this, true, thisArg));
}
```
- example usage
```shell
...
* the specified condition embodied by the 'predicate', and returns the
* (zero-based) index of the first occurrence in the source. Unlike
* {@link first}, the 'predicate' is required in 'findIndex', and does not emit
* an error if a valid value is not found.
*
* @example <caption>Emit the index of first click that happens on a DIV element</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.findIndex(ev => ev.target.tagName === 'DIV');
* result.subscribe(x => console.log(x));
*
* @see {@link filter}
* @see {@link find}
* @see {@link first}
* @see {@link take}
*
...
```



# <a name="apidoc.module.rxjs.first"></a>[module rxjs.first](#apidoc.module.rxjs.first)

#### <a name="apidoc.element.rxjs.first.first"></a>[function <span class="apidocSignatureSpan">rxjs.</span>first (predicate, resultSelector, defaultValue)](#apidoc.element.rxjs.first.first)
- description and source-code
```javascript
function first(predicate, resultSelector, defaultValue) {
    return this.lift(new FirstOperator(predicate, resultSelector, defaultValue, this));
}
```
- example usage
```shell
...
* may also take a 'resultSelector' function to produce the output value from
* the input value, and a 'defaultValue' to emit in case the source completes
* before it is able to emit a valid value. Throws an error if 'defaultValue'
* was not provided and a matching element is not found.
*
* @example <caption>Emit only the first click that happens on the DOM</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.first();
* result.subscribe(x => console.log(x));
*
* @example <caption>Emits the first click that happens on a DIV</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.first(ev => ev.target.tagName === 'DIV');
* result.subscribe(x => console.log(x));
*
...
```



# <a name="apidoc.module.rxjs.forkJoin"></a>[module rxjs.forkJoin](#apidoc.module.rxjs.forkJoin)

#### <a name="apidoc.element.rxjs.forkJoin.forkJoin"></a>[function <span class="apidocSignatureSpan">rxjs.</span>forkJoin ()](#apidoc.element.rxjs.forkJoin.forkJoin)
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



# <a name="apidoc.module.rxjs.from"></a>[module rxjs.from](#apidoc.module.rxjs.from)

#### <a name="apidoc.element.rxjs.from.from"></a>[function <span class="apidocSignatureSpan">rxjs.</span>from (ish, scheduler)](#apidoc.element.rxjs.from.from)
- description and source-code
```javascript
from = function (ish, scheduler) {
    if (ish != null) {
        if (typeof ish[observable_1.$$observable] === 'function') {
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
        else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
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
...
* object into an Observable that emits the items in that promise or array or
* iterable. A String, in this context, is treated as an array of characters.
* Observable-like objects (contains a function named with the ES2015 Symbol
* for Observable) can also be converted through this operator.
*
* @example <caption>Converts an array to an Observable</caption>
* var array = [10, 20, 30];
* var result = Rx.Observable.from(array);
* result.subscribe(x => console.log(x));
*
* // Results in the following:
* // 10 20 30
*
* @example <caption>Convert an infinite iterable (from a generator) to an Observable</caption>
* function* generateDoubles(seed) {
...
```



# <a name="apidoc.module.rxjs.fromEvent"></a>[module rxjs.fromEvent](#apidoc.module.rxjs.fromEvent)

#### <a name="apidoc.element.rxjs.fromEvent.fromEvent"></a>[function <span class="apidocSignatureSpan">rxjs.</span>fromEvent (target, eventName, options, selector)](#apidoc.element.rxjs.fromEvent.fromEvent)
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
...
* subscriber, so although each subscriber may think it is subscribing to the
* same Observable, in fact each subscriber gets its own individual
* Observable.
*
* @example <caption>Subscribe to either an Observable of clicks or an Observable of interval, at random</caption>
* var clicksOrInterval = Rx.Observable.defer(function () {
*   if (Math.random() > 0.5) {
*     return Rx.Observable.fromEvent(document, 'click');
*   } else {
*     return Rx.Observable.interval(1000);
*   }
* });
* clicksOrInterval.subscribe(x => console.log(x));
*
* // Results in the following behavior:
...
```



# <a name="apidoc.module.rxjs.fromEventPattern"></a>[module rxjs.fromEventPattern](#apidoc.module.rxjs.fromEventPattern)

#### <a name="apidoc.element.rxjs.fromEventPattern.fromEventPattern"></a>[function <span class="apidocSignatureSpan">rxjs.</span>fromEventPattern (addHandler, removeHandler, selector)](#apidoc.element.rxjs.fromEventPattern.fromEventPattern)
- description and source-code
```javascript
fromEventPattern = function (addHandler, removeHandler, selector) {
    return new FromEventPatternObservable(addHandler, removeHandler, selector);
}
```
- example usage
```shell
...
*   document.addEventListener('click', handler);
* }
*
* function removeClickHandler(handler) {
*   document.removeEventListener('click', handler);
* }
*
* var clicks = Rx.Observable.fromEventPattern(
*   addClickHandler,
*   removeClickHandler
* );
* clicks.subscribe(x => console.log(x));
*
* @see {@link from}
* @see {@link fromEvent}
...
```



# <a name="apidoc.module.rxjs.fromPromise"></a>[module rxjs.fromPromise](#apidoc.module.rxjs.fromPromise)

#### <a name="apidoc.element.rxjs.fromPromise.fromPromise"></a>[function <span class="apidocSignatureSpan">rxjs.</span>fromPromise (promise, scheduler)](#apidoc.element.rxjs.fromPromise.fromPromise)
- description and source-code
```javascript
fromPromise = function (promise, scheduler) {
    return new PromiseObservable(promise, scheduler);
}
```
- example usage
```shell
...
*
* Converts an ES2015 Promise or a Promises/A+ spec compliant Promise to an
* Observable. If the Promise resolves with a value, the output Observable
* emits that resolved value as a 'next', and then completes. If the Promise
* is rejected, then the output Observable emits the corresponding Error.
*
* @example <caption>Convert the Promise returned by Fetch to an Observable</caption>
* var result = Rx.Observable.fromPromise(fetch('http://myserver.com/'));
* result.subscribe(x => console.log(x), e => console.error(e));
*
* @see {@link bindCallback}
* @see {@link from}
*
* @param {Promise<T>} promise The promise to be converted.
* @param {Scheduler} [scheduler] An optional IScheduler to use for scheduling
...
```



# <a name="apidoc.module.rxjs.groupBy"></a>[module rxjs.groupBy](#apidoc.module.rxjs.groupBy)

#### <a name="apidoc.element.rxjs.groupBy.groupBy"></a>[function <span class="apidocSignatureSpan">rxjs.</span>groupBy (keySelector, elementSelector, durationSelector, subjectSelector)](#apidoc.element.rxjs.groupBy.groupBy)
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

#### <a name="apidoc.element.rxjs.groupBy.GroupedObservable"></a>[function <span class="apidocSignatureSpan">rxjs.groupBy.</span>GroupedObservable (key, groupSubject, refCountSubscription)](#apidoc.element.rxjs.groupBy.GroupedObservable)
- description and source-code
```javascript
function GroupedObservable(key, groupSubject, refCountSubscription) {
    _super.call(this);
    this.key = key;
    this.groupSubject = groupSubject;
    this.refCountSubscription = refCountSubscription;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.if"></a>[module rxjs.if](#apidoc.module.rxjs.if)

#### <a name="apidoc.element.rxjs.if._if"></a>[function <span class="apidocSignatureSpan">rxjs.if.</span>_if (condition, thenSource, elseSource)](#apidoc.element.rxjs.if._if)
- description and source-code
```javascript
_if = function (condition, thenSource, elseSource) {
    return new IfObservable(condition, thenSource, elseSource);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.ignoreElements"></a>[module rxjs.ignoreElements](#apidoc.module.rxjs.ignoreElements)

#### <a name="apidoc.element.rxjs.ignoreElements.ignoreElements"></a>[function <span class="apidocSignatureSpan">rxjs.</span>ignoreElements ()](#apidoc.element.rxjs.ignoreElements.ignoreElements)
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



# <a name="apidoc.module.rxjs.interval"></a>[module rxjs.interval](#apidoc.module.rxjs.interval)

#### <a name="apidoc.element.rxjs.interval.interval"></a>[function <span class="apidocSignatureSpan">rxjs.</span>interval (period, scheduler)](#apidoc.element.rxjs.interval.interval)
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
...
* By default, it uses a 'null' IScheduler, which means the 'next'
* notifications are sent synchronously, although with a different IScheduler
* it is possible to determine when those notifications will be delivered.
*
* @example <caption>Emit 10, 20, 30, then 'a', 'b', 'c', then start ticking every second.</caption>
* var numbers = Rx.Observable.of(10, 20, 30);
* var letters = Rx.Observable.of('a', 'b', 'c');
* var interval = Rx.Observable.interval(1000);
* var result = numbers.concat(letters).concat(interval);
* result.subscribe(x => console.log(x));
*
* @see {@link create}
* @see {@link empty}
* @see {@link never}
* @see {@link throw}
...
```



# <a name="apidoc.module.rxjs.isArray"></a>[module rxjs.isArray](#apidoc.module.rxjs.isArray)

#### <a name="apidoc.element.rxjs.isArray.isArray"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isArray ()](#apidoc.element.rxjs.isArray.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
...
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
...
```



# <a name="apidoc.module.rxjs.isArrayLike"></a>[module rxjs.isArrayLike](#apidoc.module.rxjs.isArrayLike)

#### <a name="apidoc.element.rxjs.isArrayLike.isArrayLike"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isArrayLike (x)](#apidoc.element.rxjs.isArrayLike.isArrayLike)
- description and source-code
```javascript
isArrayLike = function (x) { return x && typeof x.length === 'number'; }
```
- example usage
```shell
...
        }
        else if (isPromise_1.isPromise(ish)) {
            return new PromiseObservable_1.PromiseObservable(ish, scheduler);
        }
        else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
            return new IteratorObservable_1.IteratorObservable(ish, scheduler);
        }
        else if (isArrayLike_1.isArrayLike(ish)) {
            return new ArrayLikeObservable_1.ArrayLikeObservable(ish, scheduler);
        }
    }
    throw new TypeError((ish !== null && typeof ish || ish) + ' is not observable');
};
FromObservable.prototype._subscribe = function (subscriber) {
    var ish = this.ish;
...
```



# <a name="apidoc.module.rxjs.isDate"></a>[module rxjs.isDate](#apidoc.module.rxjs.isDate)

#### <a name="apidoc.element.rxjs.isDate.isDate"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isDate (value)](#apidoc.element.rxjs.isDate.isDate)
- description and source-code
```javascript
function isDate(value) {
    return value instanceof Date && !isNaN(+value);
}
```
- example usage
```shell
...
    else if (isScheduler_1.isScheduler(period)) {
        scheduler = period;
    }
    if (!isScheduler_1.isScheduler(scheduler)) {
        scheduler = async_1.async;
    }
    this.scheduler = scheduler;
    this.dueTime = isDate_1.isDate(dueTime) ?
        (+dueTime - this.scheduler.now()) :
        dueTime;
}
/**
 * Creates an Observable that starts emitting after an 'initialDelay' and
 * emits ever increasing numbers after each 'period' of time thereafter.
 *
...
```



# <a name="apidoc.module.rxjs.isEmpty"></a>[module rxjs.isEmpty](#apidoc.module.rxjs.isEmpty)

#### <a name="apidoc.element.rxjs.isEmpty.isEmpty"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isEmpty ()](#apidoc.element.rxjs.isEmpty.isEmpty)
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



# <a name="apidoc.module.rxjs.isFunction"></a>[module rxjs.isFunction](#apidoc.module.rxjs.isFunction)

#### <a name="apidoc.element.rxjs.isFunction.isFunction"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isFunction (x)](#apidoc.element.rxjs.isFunction.isFunction)
- description and source-code
```javascript
function isFunction(x) {
    return typeof x === 'function';
}
```
- example usage
```shell
...
var SafeSubscriber = (function (_super) {
__extends(SafeSubscriber, _super);
function SafeSubscriber(_parentSubscriber, observerOrNext, error, complete) {
    _super.call(this);
    this._parentSubscriber = _parentSubscriber;
    var next;
    var context = this;
    if (isFunction_1.isFunction(observerOrNext)) {
        next = observerOrNext;
    }
    else if (observerOrNext) {
        context = observerOrNext;
        next = observerOrNext.next;
        error = observerOrNext.error;
        complete = observerOrNext.complete;
...
```



# <a name="apidoc.module.rxjs.isNumeric"></a>[module rxjs.isNumeric](#apidoc.module.rxjs.isNumeric)

#### <a name="apidoc.element.rxjs.isNumeric.isNumeric"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isNumeric (val)](#apidoc.element.rxjs.isNumeric.isNumeric)
- description and source-code
```javascript
function isNumeric(val) {
    // parseFloat NaNs numeric-cast false positives (null|true|false|"")
    // ...but misinterprets leading-number strings, particularly hex literals ("0x...")
    // subtraction forces infinities to NaN
    // adding 1 corrects loss of precision from parseFloat (#15100)
    return !isArray_1.isArray(val) && (val - parseFloat(val) + 1) >= 0;
}
```
- example usage
```shell
...
__extends(IntervalObservable, _super);
function IntervalObservable(period, scheduler) {
    if (period === void 0) { period = 0; }
    if (scheduler === void 0) { scheduler = async_1.async; }
    _super.call(this);
    this.period = period;
    this.scheduler = scheduler;
    if (!isNumeric_1.isNumeric(period) || period < 0) {
        this.period = 0;
    }
    if (!scheduler || typeof scheduler.schedule !== 'function') {
        this.scheduler = async_1.async;
    }
}
/**
...
```



# <a name="apidoc.module.rxjs.isObject"></a>[module rxjs.isObject](#apidoc.module.rxjs.isObject)

#### <a name="apidoc.element.rxjs.isObject.isObject"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isObject (x)](#apidoc.element.rxjs.isObject.isObject)
- description and source-code
```javascript
function isObject(x) {
    return x != null && typeof x === 'object';
}
```
- example usage
```shell
...
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
...
```



# <a name="apidoc.module.rxjs.isPromise"></a>[module rxjs.isPromise](#apidoc.module.rxjs.isPromise)

#### <a name="apidoc.element.rxjs.isPromise.isPromise"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isPromise (value)](#apidoc.element.rxjs.isPromise.isPromise)
- description and source-code
```javascript
function isPromise(value) {
    return value && typeof value.subscribe !== 'function' && typeof value.then === 'function';
}
```
- example usage
```shell
...
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
else if (typeof ish[iterator_1.$$iterator] === 'function' || typeof ish === 'string') {
    return new IteratorObservable_1.IteratorObservable(ish, scheduler);
}
else if (isArrayLike_1.isArrayLike(ish)) {
    return new ArrayLikeObservable_1.ArrayLikeObservable(ish, scheduler);
...
```



# <a name="apidoc.module.rxjs.isScheduler"></a>[module rxjs.isScheduler](#apidoc.module.rxjs.isScheduler)

#### <a name="apidoc.element.rxjs.isScheduler.isScheduler"></a>[function <span class="apidocSignatureSpan">rxjs.</span>isScheduler (value)](#apidoc.element.rxjs.isScheduler.isScheduler)
- description and source-code
```javascript
function isScheduler(value) {
    return value && typeof value.schedule === 'function';
}
```
- example usage
```shell
...
 */
ArrayObservable.of = function () {
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
...
```



# <a name="apidoc.module.rxjs.iterator"></a>[module rxjs.iterator](#apidoc.module.rxjs.iterator)

#### <a name="apidoc.element.rxjs.iterator.symbolIteratorPonyfill"></a>[function <span class="apidocSignatureSpan">rxjs.iterator.</span>symbolIteratorPonyfill (root)](#apidoc.element.rxjs.iterator.symbolIteratorPonyfill)
- description and source-code
```javascript
function symbolIteratorPonyfill(root) {
    var Symbol = root.Symbol;
    if (typeof Symbol === 'function') {
        if (!Symbol.iterator) {
            Symbol.iterator = Symbol('iterator polyfill');
        }
        return Symbol.iterator;
    }
    else {
        // [for Mozilla Gecko 27-35:](https://mzl.la/2ewE1zC)
        var Set_1 = root.Set;
        if (Set_1 && typeof new Set_1()['@@iterator'] === 'function') {
            return '@@iterator';
        }
        var Map_1 = root.Map;
        // required for compatability with es6-shim
        if (Map_1) {
            var keys = Object.getOwnPropertyNames(Map_1.prototype);
            for (var i = 0; i < keys.length; ++i) {
                var key = keys[i];
                // according to spec, Map.prototype[@@iterator] and Map.orototype.entries must be equal.
                if (key !== 'entries' && key !== 'size' && Map_1.prototype[key] === Map_1.prototype['entries']) {
                    return key;
                }
            }
        }
        return '@@iterator';
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.last"></a>[module rxjs.last](#apidoc.module.rxjs.last)

#### <a name="apidoc.element.rxjs.last.last"></a>[function <span class="apidocSignatureSpan">rxjs.</span>last (predicate, resultSelector, defaultValue)](#apidoc.element.rxjs.last.last)
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



# <a name="apidoc.module.rxjs.let"></a>[module rxjs.let](#apidoc.module.rxjs.let)

#### <a name="apidoc.element.rxjs.let.letProto"></a>[function <span class="apidocSignatureSpan">rxjs.let.</span>letProto (func)](#apidoc.element.rxjs.let.letProto)
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



# <a name="apidoc.module.rxjs.map"></a>[module rxjs.map](#apidoc.module.rxjs.map)

#### <a name="apidoc.element.rxjs.map.map"></a>[function <span class="apidocSignatureSpan">rxjs.</span>map (project, thisArg)](#apidoc.element.rxjs.map.map)
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

#### <a name="apidoc.element.rxjs.map.MapOperator"></a>[function <span class="apidocSignatureSpan">rxjs.map.</span>MapOperator (project, thisArg)](#apidoc.element.rxjs.map.MapOperator)
- description and source-code
```javascript
function MapOperator(project, thisArg) {
    this.project = project;
    this.thisArg = thisArg;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.mapTo"></a>[module rxjs.mapTo](#apidoc.module.rxjs.mapTo)

#### <a name="apidoc.element.rxjs.mapTo.mapTo"></a>[function <span class="apidocSignatureSpan">rxjs.</span>mapTo (value)](#apidoc.element.rxjs.mapTo.mapTo)
- description and source-code
```javascript
function mapTo(value) {
    return this.lift(new MapToOperator(value));
}
```
- example usage
```shell
...
* output Observable. Those output values resulting from the projection are also
* given to the 'project' function to produce new output values. This is how
* *expand* behaves recursively.
*
* @example <caption>Start emitting the powers of two on every click, at most 10 of them</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var powersOfTwo = clicks
*   .mapTo(1)
*   .expand(x => Rx.Observable.of(2 * x).delay(1000))
*   .take(10);
* powersOfTwo.subscribe(x => console.log(x));
*
* @see {@link mergeMap}
* @see {@link mergeScan}
*
...
```



# <a name="apidoc.module.rxjs.materialize"></a>[module rxjs.materialize](#apidoc.module.rxjs.materialize)

#### <a name="apidoc.element.rxjs.materialize.materialize"></a>[function <span class="apidocSignatureSpan">rxjs.</span>materialize ()](#apidoc.element.rxjs.materialize.materialize)
- description and source-code
```javascript
function materialize() {
    return this.lift(new MaterializeOperator());
}
```
- example usage
```shell
...
* This operator is useful for producing metadata of the source Observable, to
* be consumed as 'next' emissions. Use it in conjunction with
* {@link dematerialize}.
*
* @example <caption>Convert a faulty Observable to an Observable of Notifications</caption>
* var letters = Rx.Observable.of('a', 'b', 13, 'd');
* var upperCase = letters.map(x => x.toUpperCase());
* var materialized = upperCase.materialize();
* materialized.subscribe(x => console.log(x));
*
* // Results in the following:
* // - Notification {kind: "N", value: "A", error: undefined, hasValue: true}
* // - Notification {kind: "N", value: "B", error: undefined, hasValue: true}
* // - Notification {kind: "E", value: undefined, error: TypeError:
* //   x.toUpperCase is not a function at MapSubscriber.letters.map.x
...
```



# <a name="apidoc.module.rxjs.max"></a>[module rxjs.max](#apidoc.module.rxjs.max)

#### <a name="apidoc.element.rxjs.max.max"></a>[function <span class="apidocSignatureSpan">rxjs.</span>max (comparer)](#apidoc.element.rxjs.max.max)
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
...
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
};
return ReplaySubject;
...
```



# <a name="apidoc.module.rxjs.merge"></a>[module rxjs.merge](#apidoc.module.rxjs.merge)

#### <a name="apidoc.element.rxjs.merge.merge"></a>[function <span class="apidocSignatureSpan">rxjs.</span>merge ()](#apidoc.element.rxjs.merge.merge)
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



# <a name="apidoc.module.rxjs.mergeAll"></a>[module rxjs.mergeAll](#apidoc.module.rxjs.mergeAll)

#### <a name="apidoc.element.rxjs.mergeAll.mergeAll"></a>[function <span class="apidocSignatureSpan">rxjs.</span>mergeAll (concurrent)](#apidoc.element.rxjs.mergeAll.mergeAll)
- description and source-code
```javascript
function mergeAll(concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    return this.lift(new MergeAllOperator(concurrent));
}
```
- example usage
```shell
...
* inner Observable on the output Observable. The output Observable only
* completes once all inner Observables have completed. Any error delivered by
* a inner Observable will be immediately emitted on the output Observable.
*
* @example <caption>Spawn a new interval Observable for each click event, and blend their outputs as one Observable</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map((ev) => Rx.Observable.interval(1000));
* var firstOrder = higherOrder.mergeAll();
* firstOrder.subscribe(x => console.log(x));
*
* @example <caption>Count from 0 to 9 every second for each click, but only allow 2 concurrent timers</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var higherOrder = clicks.map((ev) => Rx.Observable.interval(1000).take(10));
* var firstOrder = higherOrder.mergeAll(2);
* firstOrder.subscribe(x => console.log(x));
...
```

#### <a name="apidoc.element.rxjs.mergeAll.MergeAllOperator"></a>[function <span class="apidocSignatureSpan">rxjs.mergeAll.</span>MergeAllOperator (concurrent)](#apidoc.element.rxjs.mergeAll.MergeAllOperator)
- description and source-code
```javascript
function MergeAllOperator(concurrent) {
    this.concurrent = concurrent;
}
```
- example usage
```shell
...
 *
 * @return {Observable} An Observable emitting values from all the inner
 * Observables concatenated.
 * @method concatAll
 * @owner Observable
 */
function concatAll() {
    return this.lift(new mergeAll_1.MergeAllOperator(1));
}
exports.concatAll = concatAll;
//# sourceMappingURL=concatAll.js.map
...
```

#### <a name="apidoc.element.rxjs.mergeAll.MergeAllSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.mergeAll.</span>MergeAllSubscriber (destination, concurrent)](#apidoc.element.rxjs.mergeAll.MergeAllSubscriber)
- description and source-code
```javascript
function MergeAllSubscriber(destination, concurrent) {
    _super.call(this, destination);
    this.concurrent = concurrent;
    this.hasCompleted = false;
    this.buffer = [];
    this.active = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.mergeMap"></a>[module rxjs.mergeMap](#apidoc.module.rxjs.mergeMap)

#### <a name="apidoc.element.rxjs.mergeMap.mergeMap"></a>[function <span class="apidocSignatureSpan">rxjs.</span>mergeMap (project, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMap.mergeMap)
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
...
*
* @example <caption>Emit the number 7, then complete.</caption>
* var result = Rx.Observable.empty().startWith(7);
* result.subscribe(x => console.log(x));
*
* @example <caption>Map and flatten only odd numbers to the sequence 'a', 'b', 'c'</caption>
* var interval = Rx.Observable.interval(1000);
* var result = interval.mergeMap(x =>
*   x % 2 === 1 ? Rx.Observable.of('a', 'b', 'c') : Rx.Observable.empty()
* );
* result.subscribe(x => console.log(x));
*
* // Results in the following to the console:
* // x is equal to the count on the interval eg(0,1,2,3,...)
* // x will occur every 1000ms
...
```

#### <a name="apidoc.element.rxjs.mergeMap.MergeMapOperator"></a>[function <span class="apidocSignatureSpan">rxjs.mergeMap.</span>MergeMapOperator (project, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMap.MergeMapOperator)
- description and source-code
```javascript
function MergeMapOperator(project, resultSelector, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    this.project = project;
    this.resultSelector = resultSelector;
    this.concurrent = concurrent;
}
```
- example usage
```shell
...
 * projection function (and the optional 'resultSelector') to each item emitted
 * by the source Observable and taking values from each projected inner
 * Observable sequentially.
 * @method concatMap
 * @owner Observable
 */
function concatMap(project, resultSelector) {
    return this.lift(new mergeMap_1.MergeMapOperator(project, resultSelector, 1));
}
exports.concatMap = concatMap;
//# sourceMappingURL=concatMap.js.map
...
```

#### <a name="apidoc.element.rxjs.mergeMap.MergeMapSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.mergeMap.</span>MergeMapSubscriber (destination, project, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMap.MergeMapSubscriber)
- description and source-code
```javascript
function MergeMapSubscriber(destination, project, resultSelector, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    _super.call(this, destination);
    this.project = project;
    this.resultSelector = resultSelector;
    this.concurrent = concurrent;
    this.hasCompleted = false;
    this.buffer = [];
    this.active = 0;
    this.index = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.mergeMapTo"></a>[module rxjs.mergeMapTo](#apidoc.module.rxjs.mergeMapTo)

#### <a name="apidoc.element.rxjs.mergeMapTo.mergeMapTo"></a>[function <span class="apidocSignatureSpan">rxjs.</span>mergeMapTo (innerObservable, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMapTo.mergeMapTo)
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
...
*
* Maps each source value to the given Observable 'innerObservable' regardless
* of the source value, and then merges those resulting Observables into one
* single Observable, which is the output Observable.
*
* @example <caption>For each click event, start an interval Observable ticking every 1 second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.mergeMapTo(Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link concatMapTo}
* @see {@link merge}
* @see {@link mergeAll}
* @see {@link mergeMap}
* @see {@link mergeScan}
...
```

#### <a name="apidoc.element.rxjs.mergeMapTo.MergeMapToOperator"></a>[function <span class="apidocSignatureSpan">rxjs.mergeMapTo.</span>MergeMapToOperator (ish, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMapTo.MergeMapToOperator)
- description and source-code
```javascript
function MergeMapToOperator(ish, resultSelector, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    this.ish = ish;
    this.resultSelector = resultSelector;
    this.concurrent = concurrent;
}
```
- example usage
```shell
...
 * @return {Observable} An observable of values merged together by joining the
 * passed observable with itself, one after the other, for each value emitted
 * from the source.
 * @method concatMapTo
 * @owner Observable
 */
function concatMapTo(innerObservable, resultSelector) {
    return this.lift(new mergeMapTo_1.MergeMapToOperator(innerObservable, resultSelector, 1));
}
exports.concatMapTo = concatMapTo;
//# sourceMappingURL=concatMapTo.js.map
...
```

#### <a name="apidoc.element.rxjs.mergeMapTo.MergeMapToSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.mergeMapTo.</span>MergeMapToSubscriber (destination, ish, resultSelector, concurrent)](#apidoc.element.rxjs.mergeMapTo.MergeMapToSubscriber)
- description and source-code
```javascript
function MergeMapToSubscriber(destination, ish, resultSelector, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    _super.call(this, destination);
    this.ish = ish;
    this.resultSelector = resultSelector;
    this.concurrent = concurrent;
    this.hasCompleted = false;
    this.buffer = [];
    this.active = 0;
    this.index = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.mergeScan"></a>[module rxjs.mergeScan](#apidoc.module.rxjs.mergeScan)

#### <a name="apidoc.element.rxjs.mergeScan.mergeScan"></a>[function <span class="apidocSignatureSpan">rxjs.</span>mergeScan (accumulator, seed, concurrent)](#apidoc.element.rxjs.mergeScan.mergeScan)
- description and source-code
```javascript
function mergeScan(accumulator, seed, concurrent) {
    if (concurrent === void 0) { concurrent = Number.POSITIVE_INFINITY; }
    return this.lift(new MergeScanOperator(accumulator, seed, concurrent));
}
```
- example usage
```shell
...
* <span class="informal">It's like {@link scan}, but the Observables returned
* by the accumulator are merged into the outer Observable.</span>
*
* @example <caption>Count the number of click events</caption>
* const click$ = Rx.Observable.fromEvent(document, 'click');
* const one$ = click$.mapTo(1);
* const seed = 0;
* const count$ = one$.mergeScan((acc, one) => Rx.Observable.of(acc + one), seed);
* count$.subscribe(x => console.log(x));
*
* // Results:
* 1
* 2
* 3
* 4
...
```

#### <a name="apidoc.element.rxjs.mergeScan.MergeScanOperator"></a>[function <span class="apidocSignatureSpan">rxjs.mergeScan.</span>MergeScanOperator (accumulator, seed, concurrent)](#apidoc.element.rxjs.mergeScan.MergeScanOperator)
- description and source-code
```javascript
function MergeScanOperator(accumulator, seed, concurrent) {
    this.accumulator = accumulator;
    this.seed = seed;
    this.concurrent = concurrent;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.mergeScan.MergeScanSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.mergeScan.</span>MergeScanSubscriber (destination, accumulator, acc, concurrent)](#apidoc.element.rxjs.mergeScan.MergeScanSubscriber)
- description and source-code
```javascript
function MergeScanSubscriber(destination, accumulator, acc, concurrent) {
    _super.call(this, destination);
    this.accumulator = accumulator;
    this.acc = acc;
    this.concurrent = concurrent;
    this.hasValue = false;
    this.hasCompleted = false;
    this.buffer = [];
    this.active = 0;
    this.index = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.multicast"></a>[module rxjs.multicast](#apidoc.module.rxjs.multicast)

#### <a name="apidoc.element.rxjs.multicast.multicast"></a>[function <span class="apidocSignatureSpan">rxjs.</span>multicast (subjectOrSubjectFactory, selector)](#apidoc.element.rxjs.multicast.multicast)
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

#### <a name="apidoc.element.rxjs.multicast.MulticastOperator"></a>[function <span class="apidocSignatureSpan">rxjs.multicast.</span>MulticastOperator (subjectFactory, selector)](#apidoc.element.rxjs.multicast.MulticastOperator)
- description and source-code
```javascript
function MulticastOperator(subjectFactory, selector) {
    this.subjectFactory = subjectFactory;
    this.selector = selector;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.never"></a>[module rxjs.never](#apidoc.module.rxjs.never)

#### <a name="apidoc.element.rxjs.never.never"></a>[function <span class="apidocSignatureSpan">rxjs.</span>never ()](#apidoc.element.rxjs.never.never)
- description and source-code
```javascript
never = function () {
    return new NeverObservable();
}
```
- example usage
```shell
...
* subscription from being disposed automatically. Subscriptions need to be
* manually disposed.
*
* @example <caption>Emit the number 7, then never emit anything else (not even complete).</caption>
* function info() {
*   console.log('Will not be called');
* }
* var result = Rx.Observable.never().startWith(7);
* result.subscribe(x => console.log(x), info, info);
*
* @see {@link create}
* @see {@link empty}
* @see {@link of}
* @see {@link throw}
*
...
```



# <a name="apidoc.module.rxjs.noop"></a>[module rxjs.noop](#apidoc.module.rxjs.noop)

#### <a name="apidoc.element.rxjs.noop.noop"></a>[function <span class="apidocSignatureSpan">rxjs.</span>noop ()](#apidoc.element.rxjs.noop.noop)
- description and source-code
```javascript
function noop() { }
```
- example usage
```shell
...
     * @name never
     * @owner Observable
     */
    NeverObservable.create = function () {
        return new NeverObservable();
    };
    NeverObservable.prototype._subscribe = function (subscriber) {
        noop_1.noop();
    };
    return NeverObservable;
}(Observable_1.Observable));
exports.NeverObservable = NeverObservable;
//# sourceMappingURL=NeverObservable.js.map
...
```



# <a name="apidoc.module.rxjs.not"></a>[module rxjs.not](#apidoc.module.rxjs.not)

#### <a name="apidoc.element.rxjs.not.not"></a>[function <span class="apidocSignatureSpan">rxjs.</span>not (pred, thisArg)](#apidoc.element.rxjs.not.not)
- description and source-code
```javascript
function not(pred, thisArg) {
    function notPred() {
        return !(notPred.pred.apply(notPred.thisArg, arguments));
    }
    notPred.pred = pred;
    notPred.thisArg = thisArg;
    return notPred;
}
```
- example usage
```shell
...
 * pass the predicate.
 * @method partition
 * @owner Observable
 */
function partition(predicate, thisArg) {
    return [
        filter_1.filter.call(this, predicate, thisArg),
        filter_1.filter.call(this, not_1.not(predicate, thisArg))
    ];
}
exports.partition = partition;
//# sourceMappingURL=partition.js.map
...
```



# <a name="apidoc.module.rxjs.observeOn"></a>[module rxjs.observeOn](#apidoc.module.rxjs.observeOn)

#### <a name="apidoc.element.rxjs.observeOn.observeOn"></a>[function <span class="apidocSignatureSpan">rxjs.</span>observeOn (scheduler, delay)](#apidoc.element.rxjs.observeOn.observeOn)
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

#### <a name="apidoc.element.rxjs.observeOn.ObserveOnMessage"></a>[function <span class="apidocSignatureSpan">rxjs.observeOn.</span>ObserveOnMessage (notification, destination)](#apidoc.element.rxjs.observeOn.ObserveOnMessage)
- description and source-code
```javascript
function ObserveOnMessage(notification, destination) {
    this.notification = notification;
    this.destination = destination;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.observeOn.ObserveOnOperator"></a>[function <span class="apidocSignatureSpan">rxjs.observeOn.</span>ObserveOnOperator (scheduler, delay)](#apidoc.element.rxjs.observeOn.ObserveOnOperator)
- description and source-code
```javascript
function ObserveOnOperator(scheduler, delay) {
    if (delay === void 0) { delay = 0; }
    this.scheduler = scheduler;
    this.delay = delay;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.observeOn.ObserveOnSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.observeOn.</span>ObserveOnSubscriber (destination, scheduler, delay)](#apidoc.element.rxjs.observeOn.ObserveOnSubscriber)
- description and source-code
```javascript
function ObserveOnSubscriber(destination, scheduler, delay) {
    if (delay === void 0) { delay = 0; }
    _super.call(this, destination);
    this.scheduler = scheduler;
    this.delay = delay;
}
```
- example usage
```shell
...
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
...
```



# <a name="apidoc.module.rxjs.of"></a>[module rxjs.of](#apidoc.module.rxjs.of)

#### <a name="apidoc.element.rxjs.of.of"></a>[function <span class="apidocSignatureSpan">rxjs.</span>of ()](#apidoc.element.rxjs.of.of)
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



# <a name="apidoc.module.rxjs.onErrorResumeNext"></a>[module rxjs.onErrorResumeNext](#apidoc.module.rxjs.onErrorResumeNext)

#### <a name="apidoc.element.rxjs.onErrorResumeNext.onErrorResumeNext"></a>[function <span class="apidocSignatureSpan">rxjs.</span>onErrorResumeNext ()](#apidoc.element.rxjs.onErrorResumeNext.onErrorResumeNext)
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

#### <a name="apidoc.element.rxjs.onErrorResumeNext.onErrorResumeNextStatic"></a>[function <span class="apidocSignatureSpan">rxjs.onErrorResumeNext.</span>onErrorResumeNextStatic ()](#apidoc.element.rxjs.onErrorResumeNext.onErrorResumeNextStatic)
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



# <a name="apidoc.module.rxjs.pairs"></a>[module rxjs.pairs](#apidoc.module.rxjs.pairs)

#### <a name="apidoc.element.rxjs.pairs.pairs"></a>[function <span class="apidocSignatureSpan">rxjs.</span>pairs (obj, scheduler)](#apidoc.element.rxjs.pairs.pairs)
- description and source-code
```javascript
pairs = function (obj, scheduler) {
    return new PairsObservable(obj, scheduler);
}
```
- example usage
```shell
...
* @example <caption>Converts a javascript object to an Observable</caption>
* var obj = {
*   foo: 42,
*   bar: 56,
*   baz: 78
* };
*
* var source = Rx.Observable.pairs(obj);
*
* var subscription = source.subscribe(
*   function (x) {
*     console.log('Next: %s', x);
*   },
*   function (err) {
*     console.log('Error: %s', err);
...
```



# <a name="apidoc.module.rxjs.pairwise"></a>[module rxjs.pairwise](#apidoc.module.rxjs.pairwise)

#### <a name="apidoc.element.rxjs.pairwise.pairwise"></a>[function <span class="apidocSignatureSpan">rxjs.</span>pairwise ()](#apidoc.element.rxjs.pairwise.pairwise)
- description and source-code
```javascript
function pairwise() {
    return this.lift(new PairwiseOperator());
}
```
- example usage
```shell
...
* to emit an array [(N-1)th, Nth] of the previous and the current value, as a
* pair. For this reason, 'pairwise' emits on the second and subsequent
* emissions from the source Observable, but not on the first emission, because
* there is no previous value in that case.
*
* @example <caption>On every click (starting from the second), emit the relative distance to the previous click</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var pairs = clicks.pairwise();
* var distance = pairs.map(pair => {
*   var x0 = pair[0].clientX;
*   var y0 = pair[0].clientY;
*   var x1 = pair[1].clientX;
*   var y1 = pair[1].clientY;
*   return Math.sqrt(Math.pow(x0 - x1, 2) + Math.pow(y0 - y1, 2));
* });
...
```



# <a name="apidoc.module.rxjs.partition"></a>[module rxjs.partition](#apidoc.module.rxjs.partition)

#### <a name="apidoc.element.rxjs.partition.partition"></a>[function <span class="apidocSignatureSpan">rxjs.</span>partition (predicate, thisArg)](#apidoc.element.rxjs.partition.partition)
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
...
* Observable in that array emits source values for which the predicate argument
* returns true. The second Observable emits source values for which the
* predicate returns false. The first behaves like {@link filter} and the second
* behaves like {@link filter} with the predicate negated.
*
* @example <caption>Partition click events into those on DIV elements and those elsewhere</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var parts = clicks.partition(ev => ev.target.tagName === 'DIV');
* var clicksOnDivs = parts[0];
* var clicksElsewhere = parts[1];
* clicksOnDivs.subscribe(x => console.log('DIV clicked: ', x));
* clicksElsewhere.subscribe(x => console.log('Other clicked: ', x));
*
* @see {@link filter}
*
...
```



# <a name="apidoc.module.rxjs.pluck"></a>[module rxjs.pluck](#apidoc.module.rxjs.pluck)

#### <a name="apidoc.element.rxjs.pluck.pluck"></a>[function <span class="apidocSignatureSpan">rxjs.</span>pluck ()](#apidoc.element.rxjs.pluck.pluck)
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
...
* Given a list of strings describing a path to an object property, retrieves
* the value of a specified nested property from all values in the source
* Observable. If a property can't be resolved, it will return 'undefined' for
* that value.
*
* @example <caption>Map every every click to the tagName of the clicked target element</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var tagNames = clicks.pluck('target', 'tagName');
* tagNames.subscribe(x => console.log(x));
*
* @see {@link map}
*
* @param {...string} properties The nested properties to pluck from each source
* value (an object).
* @return {Observable} A new Observable of property values from the source values.
...
```



# <a name="apidoc.module.rxjs.publish"></a>[module rxjs.publish](#apidoc.module.rxjs.publish)

#### <a name="apidoc.element.rxjs.publish.publish"></a>[function <span class="apidocSignatureSpan">rxjs.</span>publish (selector)](#apidoc.element.rxjs.publish.publish)
- description and source-code
```javascript
function publish(selector) {
    return selector ? multicast_1.multicast.call(this, function () { return new Subject_1.Subject(); }, selector) :
        multicast_1.multicast.call(this, new Subject_1.Subject());
}
```
- example usage
```shell
...
// where the ConnectableObservable source synchronously emits values, and
// the RefCountSubscriber's downstream Observers synchronously unsubscribe,
// execution continues to here before the RefCountOperator has a chance to
// supply the RefCountSubscriber with the shared connection Subscription.
// For example:
// '''
// Observable.range(0, 10)
//   .publish()
//   .refCount()
//   .take(5)
//   .subscribe();
// '''
// In order to account for this case, RefCountSubscriber should only dispose
// the ConnectableObservable's shared connection Subscription if the
// connection Subscription exists, *and* either:
...
```



# <a name="apidoc.module.rxjs.publishBehavior"></a>[module rxjs.publishBehavior](#apidoc.module.rxjs.publishBehavior)

#### <a name="apidoc.element.rxjs.publishBehavior.publishBehavior"></a>[function <span class="apidocSignatureSpan">rxjs.</span>publishBehavior (value)](#apidoc.element.rxjs.publishBehavior.publishBehavior)
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



# <a name="apidoc.module.rxjs.publishLast"></a>[module rxjs.publishLast](#apidoc.module.rxjs.publishLast)

#### <a name="apidoc.element.rxjs.publishLast.publishLast"></a>[function <span class="apidocSignatureSpan">rxjs.</span>publishLast ()](#apidoc.element.rxjs.publishLast.publishLast)
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



# <a name="apidoc.module.rxjs.publishReplay"></a>[module rxjs.publishReplay](#apidoc.module.rxjs.publishReplay)

#### <a name="apidoc.element.rxjs.publishReplay.publishReplay"></a>[function <span class="apidocSignatureSpan">rxjs.</span>publishReplay (bufferSize, windowTime, scheduler)](#apidoc.element.rxjs.publishReplay.publishReplay)
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



# <a name="apidoc.module.rxjs.race"></a>[module rxjs.race](#apidoc.module.rxjs.race)

#### <a name="apidoc.element.rxjs.race.race"></a>[function <span class="apidocSignatureSpan">rxjs.</span>race ()](#apidoc.element.rxjs.race.race)
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

#### <a name="apidoc.element.rxjs.race.RaceOperator"></a>[function <span class="apidocSignatureSpan">rxjs.race.</span>RaceOperator ()](#apidoc.element.rxjs.race.RaceOperator)
- description and source-code
```javascript
function RaceOperator() {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.race.RaceSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.race.</span>RaceSubscriber (destination)](#apidoc.element.rxjs.race.RaceSubscriber)
- description and source-code
```javascript
function RaceSubscriber(destination) {
    _super.call(this, destination);
    this.hasFirst = false;
    this.observables = [];
    this.subscriptions = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.race.raceStatic"></a>[function <span class="apidocSignatureSpan">rxjs.race.</span>raceStatic ()](#apidoc.element.rxjs.race.raceStatic)
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



# <a name="apidoc.module.rxjs.range"></a>[module rxjs.range](#apidoc.module.rxjs.range)

#### <a name="apidoc.element.rxjs.range.range"></a>[function <span class="apidocSignatureSpan">rxjs.</span>range (start, count, scheduler)](#apidoc.element.rxjs.range.range)
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
...
// connection Subscription on the shared ConnectableObservable. In cases
// where the ConnectableObservable source synchronously emits values, and
// the RefCountSubscriber's downstream Observers synchronously unsubscribe,
// execution continues to here before the RefCountOperator has a chance to
// supply the RefCountSubscriber with the shared connection Subscription.
// For example:
// '''
// Observable.range(0, 10)
//   .publish()
//   .refCount()
//   .take(5)
//   .subscribe();
// '''
// In order to account for this case, RefCountSubscriber should only dispose
// the ConnectableObservable's shared connection Subscription if the
...
```



# <a name="apidoc.module.rxjs.reduce"></a>[module rxjs.reduce](#apidoc.module.rxjs.reduce)

#### <a name="apidoc.element.rxjs.reduce.reduce"></a>[function <span class="apidocSignatureSpan">rxjs.</span>reduce (accumulator, seed)](#apidoc.element.rxjs.reduce.reduce)
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
...
        empty.closed = true;
        return empty;
    }(new Subscription()));
    return Subscription;
}());
exports.Subscription = Subscription;
function flattenUnsubscriptionErrors(errors) {
    return errors.reduce(function (errs, err) { return errs.concat((err instanceof UnsubscriptionError_1.UnsubscriptionError) ?
err.errors : err); }, []);
}
//# sourceMappingURL=Subscription.js.map
...
```

#### <a name="apidoc.element.rxjs.reduce.ReduceOperator"></a>[function <span class="apidocSignatureSpan">rxjs.reduce.</span>ReduceOperator (accumulator, seed, hasSeed)](#apidoc.element.rxjs.reduce.ReduceOperator)
- description and source-code
```javascript
function ReduceOperator(accumulator, seed, hasSeed) {
    if (hasSeed === void 0) { hasSeed = false; }
    this.accumulator = accumulator;
    this.seed = seed;
    this.hasSeed = hasSeed;
}
```
- example usage
```shell
...
 * @method max
 * @owner Observable
 */
function max(comparer) {
    var max = (typeof comparer === 'function')
        ? function (x, y) { return comparer(x, y) > 0 ? x : y; }
        : function (x, y) { return x > y ? x : y; };
    return this.lift(new reduce_1.ReduceOperator(max));
}
exports.max = max;
//# sourceMappingURL=max.js.map
...
```

#### <a name="apidoc.element.rxjs.reduce.ReduceSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.reduce.</span>ReduceSubscriber (destination, accumulator, seed, hasSeed)](#apidoc.element.rxjs.reduce.ReduceSubscriber)
- description and source-code
```javascript
function ReduceSubscriber(destination, accumulator, seed, hasSeed) {
    _super.call(this, destination);
    this.accumulator = accumulator;
    this.hasSeed = hasSeed;
    this.index = 0;
    this.hasValue = false;
    this.acc = seed;
    if (!this.hasSeed) {
        this.index++;
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.repeat"></a>[module rxjs.repeat](#apidoc.module.rxjs.repeat)

#### <a name="apidoc.element.rxjs.repeat.repeat"></a>[function <span class="apidocSignatureSpan">rxjs.</span>repeat (count)](#apidoc.element.rxjs.repeat.repeat)
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



# <a name="apidoc.module.rxjs.repeatWhen"></a>[module rxjs.repeatWhen](#apidoc.module.rxjs.repeatWhen)

#### <a name="apidoc.element.rxjs.repeatWhen.repeatWhen"></a>[function <span class="apidocSignatureSpan">rxjs.</span>repeatWhen (notifier)](#apidoc.element.rxjs.repeatWhen.repeatWhen)
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



# <a name="apidoc.module.rxjs.retry"></a>[module rxjs.retry](#apidoc.module.rxjs.retry)

#### <a name="apidoc.element.rxjs.retry.retry"></a>[function <span class="apidocSignatureSpan">rxjs.</span>retry (count)](#apidoc.element.rxjs.retry.retry)
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



# <a name="apidoc.module.rxjs.retryWhen"></a>[module rxjs.retryWhen](#apidoc.module.rxjs.retryWhen)

#### <a name="apidoc.element.rxjs.retryWhen.retryWhen"></a>[function <span class="apidocSignatureSpan">rxjs.</span>retryWhen (notifier)](#apidoc.element.rxjs.retryWhen.retryWhen)
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



# <a name="apidoc.module.rxjs.sample"></a>[module rxjs.sample](#apidoc.module.rxjs.sample)

#### <a name="apidoc.element.rxjs.sample.sample"></a>[function <span class="apidocSignatureSpan">rxjs.</span>sample (notifier)](#apidoc.element.rxjs.sample.sample)
- description and source-code
```javascript
function sample(notifier) {
    return this.lift(new SampleOperator(notifier));
}
```
- example usage
```shell
...
* emitted since the previous sampling, unless the source has not emitted
* anything since the previous sampling. The 'notifier' is subscribed to as soon
* as the output Observable is subscribed.
*
* @example <caption>On every click, sample the most recent "seconds" timer</caption>
* var seconds = Rx.Observable.interval(1000);
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = seconds.sample(clicks);
* result.subscribe(x => console.log(x));
*
* @see {@link audit}
* @see {@link debounce}
* @see {@link sampleTime}
* @see {@link throttle}
*
...
```



# <a name="apidoc.module.rxjs.sampleTime"></a>[module rxjs.sampleTime](#apidoc.module.rxjs.sampleTime)

#### <a name="apidoc.element.rxjs.sampleTime.sampleTime"></a>[function <span class="apidocSignatureSpan">rxjs.</span>sampleTime (period, scheduler)](#apidoc.element.rxjs.sampleTime.sampleTime)
- description and source-code
```javascript
function sampleTime(period, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new SampleTimeOperator(period, scheduler));
}
```
- example usage
```shell
...
* source has not emitted anything since the previous sampling. The sampling
* happens periodically in time every 'period' milliseconds (or the time unit
* defined by the optional 'scheduler' argument). The sampling starts as soon as
* the output Observable is subscribed.
*
* @example <caption>Every second, emit the most recent click at most once</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.sampleTime(1000);
* result.subscribe(x => console.log(x));
*
* @see {@link auditTime}
* @see {@link debounceTime}
* @see {@link delay}
* @see {@link sample}
* @see {@link throttleTime}
...
```



# <a name="apidoc.module.rxjs.scan"></a>[module rxjs.scan](#apidoc.module.rxjs.scan)

#### <a name="apidoc.element.rxjs.scan.scan"></a>[function <span class="apidocSignatureSpan">rxjs.</span>scan (accumulator, seed)](#apidoc.element.rxjs.scan.scan)
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
...
* that value will be used as the initial value for the accumulator. If no seed
* value is specified, the first item of the source is used as the seed.
*
* @example <caption>Count the number of click events</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var ones = clicks.mapTo(1);
* var seed = 0;
* var count = ones.scan((acc, one) => acc + one, seed);
* count.subscribe(x => console.log(x));
*
* @see {@link expand}
* @see {@link mergeScan}
* @see {@link reduce}
*
* @param {function(acc: R, value: T, index: number): R} accumulator
...
```



# <a name="apidoc.module.rxjs.sequenceEqual"></a>[module rxjs.sequenceEqual](#apidoc.module.rxjs.sequenceEqual)

#### <a name="apidoc.element.rxjs.sequenceEqual.sequenceEqual"></a>[function <span class="apidocSignatureSpan">rxjs.</span>sequenceEqual (compareTo, comparor)](#apidoc.element.rxjs.sequenceEqual.sequenceEqual)
- description and source-code
```javascript
function sequenceEqual(compareTo, comparor) {
    return this.lift(new SequenceEqualOperator(compareTo, comparor));
}
```
- example usage
```shell
...
*
* var keys = Rx.Observable.fromEvent(document, 'keyup')
*  .map(e => e.code);
* var matches = keys.bufferCount(11, 1)
*  .mergeMap(
*    last11 =>
*      Rx.Observable.from(last11)
*        .sequenceEqual(code)
*   );
* matches.subscribe(matched => console.log('Successful cheat at Contra? ', matched));
*
* @see {@link combineLatest}
* @see {@link zip}
* @see {@link withLatestFrom}
*
...
```

#### <a name="apidoc.element.rxjs.sequenceEqual.SequenceEqualOperator"></a>[function <span class="apidocSignatureSpan">rxjs.sequenceEqual.</span>SequenceEqualOperator (compareTo, comparor)](#apidoc.element.rxjs.sequenceEqual.SequenceEqualOperator)
- description and source-code
```javascript
function SequenceEqualOperator(compareTo, comparor) {
    this.compareTo = compareTo;
    this.comparor = comparor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.rxjs.sequenceEqual.SequenceEqualSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.sequenceEqual.</span>SequenceEqualSubscriber (destination, compareTo, comparor)](#apidoc.element.rxjs.sequenceEqual.SequenceEqualSubscriber)
- description and source-code
```javascript
function SequenceEqualSubscriber(destination, compareTo, comparor) {
    _super.call(this, destination);
    this.compareTo = compareTo;
    this.comparor = comparor;
    this._a = [];
    this._b = [];
    this._oneComplete = false;
    this.add(compareTo.subscribe(new SequenceEqualCompareToSubscriber(destination, this)));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.share"></a>[module rxjs.share](#apidoc.module.rxjs.share)

#### <a name="apidoc.element.rxjs.share.share"></a>[function <span class="apidocSignatureSpan">rxjs.</span>share ()](#apidoc.element.rxjs.share.share)
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



# <a name="apidoc.module.rxjs.single"></a>[module rxjs.single](#apidoc.module.rxjs.single)

#### <a name="apidoc.element.rxjs.single.single"></a>[function <span class="apidocSignatureSpan">rxjs.</span>single (predicate)](#apidoc.element.rxjs.single.single)
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



# <a name="apidoc.module.rxjs.skip"></a>[module rxjs.skip](#apidoc.module.rxjs.skip)

#### <a name="apidoc.element.rxjs.skip.skip"></a>[function <span class="apidocSignatureSpan">rxjs.</span>skip (count)](#apidoc.element.rxjs.skip.skip)
- description and source-code
```javascript
function skip(count) {
    return this.lift(new SkipOperator(count));
}
```
- example usage
```shell
...
* Observable. If 'startWindowEvery' is not provided, then new windows are
* started immediately at the start of the source and when each window completes
* with size 'windowSize'.
*
* @example <caption>Ignore every 3rd click event, starting from the first one</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.windowCount(3)
*   .map(win => win.skip(1)) // skip first of every 3 clicks
*   .mergeAll(); // flatten the Observable-of-Observables
* result.subscribe(x => console.log(x));
*
* @example <caption>Ignore every 3rd click event, starting from the third one</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.windowCount(2, 3)
*   .mergeAll(); // flatten the Observable-of-Observables
...
```



# <a name="apidoc.module.rxjs.skipUntil"></a>[module rxjs.skipUntil](#apidoc.module.rxjs.skipUntil)

#### <a name="apidoc.element.rxjs.skipUntil.skipUntil"></a>[function <span class="apidocSignatureSpan">rxjs.</span>skipUntil (notifier)](#apidoc.element.rxjs.skipUntil.skipUntil)
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



# <a name="apidoc.module.rxjs.skipWhile"></a>[module rxjs.skipWhile](#apidoc.module.rxjs.skipWhile)

#### <a name="apidoc.element.rxjs.skipWhile.skipWhile"></a>[function <span class="apidocSignatureSpan">rxjs.</span>skipWhile (predicate)](#apidoc.element.rxjs.skipWhile.skipWhile)
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



# <a name="apidoc.module.rxjs.startWith"></a>[module rxjs.startWith](#apidoc.module.rxjs.startWith)

#### <a name="apidoc.element.rxjs.startWith.startWith"></a>[function <span class="apidocSignatureSpan">rxjs.</span>startWith ()](#apidoc.element.rxjs.startWith.startWith)
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
...
* <img src="./img/empty.png" width="100%">
*
* This static operator is useful for creating a simple Observable that only
* emits the complete notification. It can be used for composing with other
* Observables, such as in a {@link mergeMap}.
*
* @example <caption>Emit the number 7, then complete.</caption>
* var result = Rx.Observable.empty().startWith(7);
* result.subscribe(x => console.log(x));
*
* @example <caption>Map and flatten only odd numbers to the sequence 'a', 'b', 'c'</caption>
* var interval = Rx.Observable.interval(1000);
* var result = interval.mergeMap(x =>
*   x % 2 === 1 ? Rx.Observable.of('a', 'b', 'c') : Rx.Observable.empty()
* );
...
```



# <a name="apidoc.module.rxjs.subscribeOn"></a>[module rxjs.subscribeOn](#apidoc.module.rxjs.subscribeOn)

#### <a name="apidoc.element.rxjs.subscribeOn.subscribeOn"></a>[function <span class="apidocSignatureSpan">rxjs.</span>subscribeOn (scheduler, delay)](#apidoc.element.rxjs.subscribeOn.subscribeOn)
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



# <a name="apidoc.module.rxjs.subscribeToResult"></a>[module rxjs.subscribeToResult](#apidoc.module.rxjs.subscribeToResult)

#### <a name="apidoc.element.rxjs.subscribeToResult.subscribeToResult"></a>[function <span class="apidocSignatureSpan">rxjs.</span>subscribeToResult (outerSubscriber, result, outerValue, outerIndex)](#apidoc.element.rxjs.subscribeToResult.subscribeToResult)
- description and source-code
```javascript
function subscribeToResult(outerSubscriber, result, outerValue, outerIndex) {
    var destination = new InnerSubscriber_1.InnerSubscriber(outerSubscriber, outerValue, outerIndex);
    if (destination.closed) {
        return null;
    }
    if (result instanceof Observable_1.Observable) {
        if (result._isScalar) {
            destination.next(result.value);
            destination.complete();
            return null;
        }
        else {
            return result.subscribe(destination);
        }
    }
    else if (isArrayLike_1.isArrayLike(result)) {
        for (var i = 0, len = result.length; i < len && !destination.closed; i++) {
            destination.next(result[i]);
        }
        if (!destination.closed) {
            destination.complete();
        }
    }
    else if (isPromise_1.isPromise(result)) {
        result.then(function (value) {
            if (!destination.closed) {
                destination.next(value);
                destination.complete();
            }
        }, function (err) { return destination.error(err); })
            .then(null, function (err) {
            // Escaping the Promise trap: globally throw unhandled errors
            root_1.root.setTimeout(function () { throw err; });
        });
        return destination;
    }
    else if (result && typeof result[iterator_1.$$iterator] === 'function') {
        var iterator = result[iterator_1.$$iterator]();
        do {
            var item = iterator.next();
            if (item.done) {
                destination.complete();
                break;
            }
            destination.next(item.value);
            if (destination.closed) {
                break;
            }
        } while (true);
    }
    else if (result && typeof result[observable_1.$$observable] === 'function') {
        var obs = result[observable_1.$$observable]();
        if (typeof obs.subscribe !== 'function') {
            destination.error(new TypeError('Provided object does not correctly implement Symbol.observable'));
        }
        else {
            return obs.subscribe(new InnerSubscriber_1.InnerSubscriber(outerSubscriber, outerValue, outerIndex));
        }
    }
    else {
        var value = isObject_1.isObject(result) ? 'an invalid object' : "'" + result + "'";
        var msg = ("You provided " + value + " where a stream was expected.")
            + ' You can provide an Observable, Promise, Array, or Iterable.';
        destination.error(new TypeError(msg));
    }
    return null;
}
```
- example usage
```shell
...
        catch (err) {
            this._error(err);
        }
    };
    DeferSubscriber.prototype._callFactory = function () {
        var result = this.factory();
        if (result) {
            this.add(subscribeToResult_1.subscribeToResult(this, result));
        }
    };
    return DeferSubscriber;
}(OuterSubscriber_1.OuterSubscriber));
//# sourceMappingURL=DeferObservable.js.map
...
```



# <a name="apidoc.module.rxjs.switch"></a>[module rxjs.switch](#apidoc.module.rxjs.switch)

#### <a name="apidoc.element.rxjs.switch._switch"></a>[function <span class="apidocSignatureSpan">rxjs.switch.</span>_switch ()](#apidoc.element.rxjs.switch._switch)
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



# <a name="apidoc.module.rxjs.switchMap"></a>[module rxjs.switchMap](#apidoc.module.rxjs.switchMap)

#### <a name="apidoc.element.rxjs.switchMap.switchMap"></a>[function <span class="apidocSignatureSpan">rxjs.</span>switchMap (project, resultSelector)](#apidoc.element.rxjs.switchMap.switchMap)
- description and source-code
```javascript
function switchMap(project, resultSelector) {
    return this.lift(new SwitchMapOperator(project, resultSelector));
}
```
- example usage
```shell
...
* that inner Observable. When a new inner Observable is emitted, 'switchMap'
* stops emitting items from the earlier-emitted inner Observable and begins
* emitting items from the new one. It continues to behave like this for
* subsequent inner Observables.
*
* @example <caption>Rerun an interval Observable on every click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.switchMap((ev) => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link concatMap}
* @see {@link exhaustMap}
* @see {@link mergeMap}
* @see {@link switch}
* @see {@link switchMapTo}
...
```



# <a name="apidoc.module.rxjs.switchMapTo"></a>[module rxjs.switchMapTo](#apidoc.module.rxjs.switchMapTo)

#### <a name="apidoc.element.rxjs.switchMapTo.switchMapTo"></a>[function <span class="apidocSignatureSpan">rxjs.</span>switchMapTo (innerObservable, resultSelector)](#apidoc.element.rxjs.switchMapTo.switchMapTo)
- description and source-code
```javascript
function switchMapTo(innerObservable, resultSelector) {
    return this.lift(new SwitchMapToOperator(innerObservable, resultSelector));
}
```
- example usage
```shell
...
* of the source value, and then flattens those resulting Observables into one
* single Observable, which is the output Observable. The output Observables
* emits values only from the most recently emitted instance of
* 'innerObservable'.
*
* @example <caption>Rerun an interval Observable on every click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.switchMapTo(Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link concatMapTo}
* @see {@link switch}
* @see {@link switchMap}
* @see {@link mergeMapTo}
*
...
```



# <a name="apidoc.module.rxjs.take"></a>[module rxjs.take](#apidoc.module.rxjs.take)

#### <a name="apidoc.element.rxjs.take.take"></a>[function <span class="apidocSignatureSpan">rxjs.</span>take (count)](#apidoc.element.rxjs.take.take)
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
...
// execution continues to here before the RefCountOperator has a chance to
// supply the RefCountSubscriber with the shared connection Subscription.
// For example:
// '''
// Observable.range(0, 10)
//   .publish()
//   .refCount()
//   .take(5)
//   .subscribe();
// '''
// In order to account for this case, RefCountSubscriber should only dispose
// the ConnectableObservable's shared connection Subscription if the
// connection Subscription exists, *and* either:
//   a. RefCountSubscriber doesn't have a reference to the shared connection
//      Subscription yet, or,
...
```



# <a name="apidoc.module.rxjs.takeLast"></a>[module rxjs.takeLast](#apidoc.module.rxjs.takeLast)

#### <a name="apidoc.element.rxjs.takeLast.takeLast"></a>[function <span class="apidocSignatureSpan">rxjs.</span>takeLast (count)](#apidoc.element.rxjs.takeLast.takeLast)
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
...
* 'complete' notification emission from the source in order to emit the 'next'
* values on the output Observable, because otherwise it is impossible to know
* whether or not more values will be emitted on the source. For this reason,
* all values are emitted synchronously, followed by the complete notification.
*
* @example <caption>Take the last 3 values of an Observable with many values</caption>
* var many = Rx.Observable.range(1, 100);
* var lastThree = many.takeLast(3);
* lastThree.subscribe(x => console.log(x));
*
* @see {@link take}
* @see {@link takeUntil}
* @see {@link takeWhile}
* @see {@link skip}
*
...
```



# <a name="apidoc.module.rxjs.takeUntil"></a>[module rxjs.takeUntil](#apidoc.module.rxjs.takeUntil)

#### <a name="apidoc.element.rxjs.takeUntil.takeUntil"></a>[function <span class="apidocSignatureSpan">rxjs.</span>takeUntil (notifier)](#apidoc.element.rxjs.takeUntil.takeUntil)
- description and source-code
```javascript
function takeUntil(notifier) {
    return this.lift(new TakeUntilOperator(notifier));
}
```
- example usage
```shell
...
* a value nor terminate. This operator takes an optional 'predicate' function
* as argument, in which case the output emission will represent the number of
* source values that matched 'true' with the 'predicate'.
*
* @example <caption>Counts how many seconds have passed before the first click happened</caption>
* var seconds = Rx.Observable.interval(1000);
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var secondsBeforeClick = seconds.takeUntil(clicks);
* var result = secondsBeforeClick.count();
* result.subscribe(x => console.log(x));
*
* @example <caption>Counts how many odd numbers are there between 1 and 7</caption>
* var numbers = Rx.Observable.range(1, 7);
* var result = numbers.count(i => i % 2 === 1);
* result.subscribe(x => console.log(x));
...
```



# <a name="apidoc.module.rxjs.takeWhile"></a>[module rxjs.takeWhile](#apidoc.module.rxjs.takeWhile)

#### <a name="apidoc.element.rxjs.takeWhile.takeWhile"></a>[function <span class="apidocSignatureSpan">rxjs.</span>takeWhile (predicate)](#apidoc.element.rxjs.takeWhile.takeWhile)
- description and source-code
```javascript
function takeWhile(predicate) {
    return this.lift(new TakeWhileOperator(predicate));
}
```
- example usage
```shell
...
* boolean, representing a condition to be satisfied by the source values. The
* output Observable emits the source values until such time as the 'predicate'
* returns false, at which point 'takeWhile' stops mirroring the source
* Observable and completes the output Observable.
*
* @example <caption>Emit click events only while the clientX property is greater than 200</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.takeWhile(ev => ev.clientX > 200);
* result.subscribe(x => console.log(x));
*
* @see {@link take}
* @see {@link takeLast}
* @see {@link takeUntil}
* @see {@link skip}
*
...
```



# <a name="apidoc.module.rxjs.throttle"></a>[module rxjs.throttle](#apidoc.module.rxjs.throttle)

#### <a name="apidoc.element.rxjs.throttle.throttle"></a>[function <span class="apidocSignatureSpan">rxjs.</span>throttle (durationSelector)](#apidoc.element.rxjs.throttle.throttle)
- description and source-code
```javascript
function throttle(durationSelector) {
    return this.lift(new ThrottleOperator(durationSelector));
}
```
- example usage
```shell
...
* is enabled by calling the 'durationSelector' function with the source value,
* which returns the "duration" Observable. When the duration Observable emits a
* value or completes, the timer is disabled, and this process repeats for the
* next source value.
*
* @example <caption>Emit clicks at a rate of at most one click per second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.throttle(ev => Rx.Observable.interval(1000));
* result.subscribe(x => console.log(x));
*
* @see {@link audit}
* @see {@link debounce}
* @see {@link delayWhen}
* @see {@link sample}
* @see {@link throttleTime}
...
```



# <a name="apidoc.module.rxjs.throttleTime"></a>[module rxjs.throttleTime](#apidoc.module.rxjs.throttleTime)

#### <a name="apidoc.element.rxjs.throttleTime.throttleTime"></a>[function <span class="apidocSignatureSpan">rxjs.</span>throttleTime (duration, scheduler)](#apidoc.element.rxjs.throttleTime.throttleTime)
- description and source-code
```javascript
function throttleTime(duration, scheduler) {
    if (scheduler === void 0) { scheduler = async_1.async; }
    return this.lift(new ThrottleTimeOperator(duration, scheduler));
}
```
- example usage
```shell
...
* is enabled. After 'duration' milliseconds (or the time unit determined
* internally by the optional 'scheduler') has passed, the timer is disabled,
* and this process repeats for the next source value. Optionally takes a
* {@link IScheduler} for managing timers.
*
* @example <caption>Emit clicks at a rate of at most one click per second</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.throttleTime(1000);
* result.subscribe(x => console.log(x));
*
* @see {@link auditTime}
* @see {@link debounceTime}
* @see {@link delay}
* @see {@link sampleTime}
* @see {@link throttle}
...
```



# <a name="apidoc.module.rxjs.throw"></a>[module rxjs.throw](#apidoc.module.rxjs.throw)

#### <a name="apidoc.element.rxjs.throw._throw"></a>[function <span class="apidocSignatureSpan">rxjs.throw.</span>_throw (error, scheduler)](#apidoc.element.rxjs.throw._throw)
- description and source-code
```javascript
_throw = function (error, scheduler) {
    return new ErrorObservable(error, scheduler);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.rxjs.timeInterval"></a>[module rxjs.timeInterval](#apidoc.module.rxjs.timeInterval)

#### <a name="apidoc.element.rxjs.timeInterval.timeInterval"></a>[function <span class="apidocSignatureSpan">rxjs.</span>timeInterval (scheduler)](#apidoc.element.rxjs.timeInterval.timeInterval)
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

#### <a name="apidoc.element.rxjs.timeInterval.TimeInterval"></a>[function <span class="apidocSignatureSpan">rxjs.timeInterval.</span>TimeInterval (value, interval)](#apidoc.element.rxjs.timeInterval.TimeInterval)
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



# <a name="apidoc.module.rxjs.timeout"></a>[module rxjs.timeout](#apidoc.module.rxjs.timeout)

#### <a name="apidoc.element.rxjs.timeout.timeout"></a>[function <span class="apidocSignatureSpan">rxjs.</span>timeout (due, scheduler)](#apidoc.element.rxjs.timeout.timeout)
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



# <a name="apidoc.module.rxjs.timeoutWith"></a>[module rxjs.timeoutWith](#apidoc.module.rxjs.timeoutWith)

#### <a name="apidoc.element.rxjs.timeoutWith.timeoutWith"></a>[function <span class="apidocSignatureSpan">rxjs.</span>timeoutWith (due, withObservable, scheduler)](#apidoc.element.rxjs.timeoutWith.timeoutWith)
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



# <a name="apidoc.module.rxjs.timer"></a>[module rxjs.timer](#apidoc.module.rxjs.timer)

#### <a name="apidoc.element.rxjs.timer.timer"></a>[function <span class="apidocSignatureSpan">rxjs.</span>timer (initialDelay, period, scheduler)](#apidoc.element.rxjs.timer.timer)
- description and source-code
```javascript
timer = function (initialDelay, period, scheduler) {
    if (initialDelay === void 0) { initialDelay = 0; }
    return new TimerObservable(initialDelay, period, scheduler);
}
```
- example usage
```shell
...
* 'initialDelay'. The initial delay may be a {@link Date}. By default, this
* operator uses the 'async' IScheduler to provide a notion of time, but you
* may pass any IScheduler to it. If 'period' is not specified, the output
* Observable emits only one value, '0'. Otherwise, it emits an infinite
* sequence.
*
* @example <caption>Emits ascending numbers, one every second (1000ms), starting after 3 seconds</caption>
* var numbers = Rx.Observable.timer(3000, 1000);
* numbers.subscribe(x => console.log(x));
*
* @example <caption>Emits one number after five seconds</caption>
* var numbers = Rx.Observable.timer(5000);
* numbers.subscribe(x => console.log(x));
*
* @see {@link interval}
...
```



# <a name="apidoc.module.rxjs.timestamp"></a>[module rxjs.timestamp](#apidoc.module.rxjs.timestamp)

#### <a name="apidoc.element.rxjs.timestamp.timestamp"></a>[function <span class="apidocSignatureSpan">rxjs.</span>timestamp (scheduler)](#apidoc.element.rxjs.timestamp.timestamp)
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

#### <a name="apidoc.element.rxjs.timestamp.Timestamp"></a>[function <span class="apidocSignatureSpan">rxjs.timestamp.</span>Timestamp (value, timestamp)](#apidoc.element.rxjs.timestamp.Timestamp)
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



# <a name="apidoc.module.rxjs.toArray"></a>[module rxjs.toArray](#apidoc.module.rxjs.toArray)

#### <a name="apidoc.element.rxjs.toArray.toArray"></a>[function <span class="apidocSignatureSpan">rxjs.</span>toArray ()](#apidoc.element.rxjs.toArray.toArray)
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



# <a name="apidoc.module.rxjs.toPromise"></a>[module rxjs.toPromise](#apidoc.module.rxjs.toPromise)

#### <a name="apidoc.element.rxjs.toPromise.toPromise"></a>[function <span class="apidocSignatureSpan">rxjs.</span>toPromise (PromiseCtor)](#apidoc.element.rxjs.toPromise.toPromise)
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
...
/**
* Converts an Observable sequence to a ES2015 compliant promise.
*
* @example
* // Using normal ES2015
* let source = Rx.Observable
*   .just(42)
*   .toPromise();
*
* source.then((value) => console.log('Value: %s', value));
* // => Value: 42
*
* // Rejected Promise
* // Using normal ES2015
* let source = Rx.Observable
...
```



# <a name="apidoc.module.rxjs.toSubscriber"></a>[module rxjs.toSubscriber](#apidoc.module.rxjs.toSubscriber)

#### <a name="apidoc.element.rxjs.toSubscriber.toSubscriber"></a>[function <span class="apidocSignatureSpan">rxjs.</span>toSubscriber (nextOrObserver, error, complete)](#apidoc.element.rxjs.toSubscriber.toSubscriber)
- description and source-code
```javascript
function toSubscriber(nextOrObserver, error, complete) {
    if (nextOrObserver) {
        if (nextOrObserver instanceof Subscriber_1.Subscriber) {
            return nextOrObserver;
        }
        if (nextOrObserver[rxSubscriber_1.$$rxSubscriber]) {
            return nextOrObserver[rxSubscriber_1.$$rxSubscriber]();
        }
    }
    if (!nextOrObserver && !error && !complete) {
        return new Subscriber_1.Subscriber(Observer_1.empty);
    }
    return new Subscriber_1.Subscriber(nextOrObserver, error, complete);
}
```
- example usage
```shell
...
    var observable = new Observable();
    observable.source = this;
    observable.operator = operator;
    return observable;
};
Observable.prototype.subscribe = function (observerOrNext, error, complete) {
    var operator = this.operator;
    var sink = toSubscriber_1.toSubscriber(observerOrNext, error, complete);
    if (operator) {
        operator.call(sink, this.source);
    }
    else {
        sink.add(this._trySubscribe(sink));
    }
    if (sink.syncErrorThrowable) {
...
```



# <a name="apidoc.module.rxjs.tryCatch"></a>[module rxjs.tryCatch](#apidoc.module.rxjs.tryCatch)

#### <a name="apidoc.element.rxjs.tryCatch.tryCatch"></a>[function <span class="apidocSignatureSpan">rxjs.</span>tryCatch (fn)](#apidoc.element.rxjs.tryCatch.tryCatch)
- description and source-code
```javascript
function tryCatch(fn) {
    tryCatchTarget = fn;
    return tryCatcher;
}
```
- example usage
```shell
...
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
...
```



# <a name="apidoc.module.rxjs.using"></a>[module rxjs.using](#apidoc.module.rxjs.using)

#### <a name="apidoc.element.rxjs.using.using"></a>[function <span class="apidocSignatureSpan">rxjs.</span>using (resourceFactory, observableFactory)](#apidoc.element.rxjs.using.using)
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



# <a name="apidoc.module.rxjs.window"></a>[module rxjs.window](#apidoc.module.rxjs.window)

#### <a name="apidoc.element.rxjs.window.window"></a>[function <span class="apidocSignatureSpan">rxjs.</span>window (windowBoundaries)](#apidoc.element.rxjs.window.window)
- description and source-code
```javascript
function window(windowBoundaries) {
    return this.lift(new WindowOperator(windowBoundaries));
}
```
- example usage
```shell
...
* windows. It emits the current window and opens a new one whenever the
* Observable 'windowBoundaries' emits an item. Because each window is an
* Observable, the output is a higher-order Observable.
*
* @example <caption>In every window of 1 second each, emit at most 2 click events</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var interval = Rx.Observable.interval(1000);
* var result = clicks.window(interval)
*   .map(win => win.take(2)) // each window has at most 2 emissions
*   .mergeAll(); // flatten the Observable-of-Observables
* result.subscribe(x => console.log(x));
*
* @see {@link windowCount}
* @see {@link windowTime}
* @see {@link windowToggle}
...
```



# <a name="apidoc.module.rxjs.windowCount"></a>[module rxjs.windowCount](#apidoc.module.rxjs.windowCount)

#### <a name="apidoc.element.rxjs.windowCount.windowCount"></a>[function <span class="apidocSignatureSpan">rxjs.</span>windowCount (windowSize, startWindowEvery)](#apidoc.element.rxjs.windowCount.windowCount)
- description and source-code
```javascript
function windowCount(windowSize, startWindowEvery) {
    if (startWindowEvery === void 0) { startWindowEvery = 0; }
    return this.lift(new WindowCountOperator(windowSize, startWindowEvery));
}
```
- example usage
```shell
...
* the current window and propagates the notification from the source
* Observable. If 'startWindowEvery' is not provided, then new windows are
* started immediately at the start of the source and when each window completes
* with size 'windowSize'.
*
* @example <caption>Ignore every 3rd click event, starting from the first one</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.windowCount(3)
*   .map(win => win.skip(1)) // skip first of every 3 clicks
*   .mergeAll(); // flatten the Observable-of-Observables
* result.subscribe(x => console.log(x));
*
* @example <caption>Ignore every 3rd click event, starting from the third one</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks.windowCount(2, 3)
...
```



# <a name="apidoc.module.rxjs.windowTime"></a>[module rxjs.windowTime](#apidoc.module.rxjs.windowTime)

#### <a name="apidoc.element.rxjs.windowTime.windowTime"></a>[function <span class="apidocSignatureSpan">rxjs.</span>windowTime (windowTimeSpan)](#apidoc.element.rxjs.windowTime.windowTime)
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



# <a name="apidoc.module.rxjs.windowToggle"></a>[module rxjs.windowToggle](#apidoc.module.rxjs.windowToggle)

#### <a name="apidoc.element.rxjs.windowToggle.windowToggle"></a>[function <span class="apidocSignatureSpan">rxjs.</span>windowToggle (openings, closingSelector)](#apidoc.element.rxjs.windowToggle.windowToggle)
- description and source-code
```javascript
function windowToggle(openings, closingSelector) {
    return this.lift(new WindowToggleOperator(openings, closingSelector));
}
```
- example usage
```shell
...
* emitted by the source Observable between the time when the 'openings'
* Observable emits an item and when the Observable returned by
* 'closingSelector' emits an item.
*
* @example <caption>Every other second, emit the click events from the next 500ms</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var openings = Rx.Observable.interval(1000);
* var result = clicks.windowToggle(openings, i =>
*   i % 2 ? Rx.Observable.interval(500) : Rx.Observable.empty()
* ).mergeAll();
* result.subscribe(x => console.log(x));
*
* @see {@link window}
* @see {@link windowCount}
* @see {@link windowTime}
...
```



# <a name="apidoc.module.rxjs.windowWhen"></a>[module rxjs.windowWhen](#apidoc.module.rxjs.windowWhen)

#### <a name="apidoc.element.rxjs.windowWhen.windowWhen"></a>[function <span class="apidocSignatureSpan">rxjs.</span>windowWhen (closingSelector)](#apidoc.element.rxjs.windowWhen.windowWhen)
- description and source-code
```javascript
function windowWhen(closingSelector) {
    return this.lift(new WindowOperator(closingSelector));
}
```
- example usage
```shell
...
* It emits the current window and opens a new one whenever the Observable
* produced by the specified 'closingSelector' function emits an item. The first
* window is opened immediately when subscribing to the output Observable.
*
* @example <caption>Emit only the first two clicks events in every window of [1-5] random seconds</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var result = clicks
*   .windowWhen(() => Rx.Observable.interval(1000 + Math.random() * 4000))
*   .map(win => win.take(2)) // each window has at most 2 emissions
*   .mergeAll(); // flatten the Observable-of-Observables
* result.subscribe(x => console.log(x));
*
* @see {@link window}
* @see {@link windowCount}
* @see {@link windowTime}
...
```



# <a name="apidoc.module.rxjs.withLatestFrom"></a>[module rxjs.withLatestFrom](#apidoc.module.rxjs.withLatestFrom)

#### <a name="apidoc.element.rxjs.withLatestFrom.withLatestFrom"></a>[function <span class="apidocSignatureSpan">rxjs.</span>withLatestFrom ()](#apidoc.element.rxjs.withLatestFrom.withLatestFrom)
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
...
* the source emits a value, optionally using a 'project' function to determine
* the value to be emitted on the output Observable. All input Observables must
* emit at least one value before the output Observable will emit a value.
*
* @example <caption>On every click event, emit an array with the latest timer event plus the click event</caption>
* var clicks = Rx.Observable.fromEvent(document, 'click');
* var timer = Rx.Observable.interval(1000);
* var result = clicks.withLatestFrom(timer);
* result.subscribe(x => console.log(x));
*
* @see {@link combineLatest}
*
* @param {ObservableInput} other An input Observable to combine with the source
* Observable. More than one input Observables may be given as argument.
* @param {Function} [project] Projection function for combining values
...
```



# <a name="apidoc.module.rxjs.zip"></a>[module rxjs.zip](#apidoc.module.rxjs.zip)

#### <a name="apidoc.element.rxjs.zip.zip"></a>[function <span class="apidocSignatureSpan">rxjs.</span>zip ()](#apidoc.element.rxjs.zip.zip)
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



# <a name="apidoc.module.rxjs.zipAll"></a>[module rxjs.zipAll](#apidoc.module.rxjs.zipAll)

#### <a name="apidoc.element.rxjs.zipAll.zipAll"></a>[function <span class="apidocSignatureSpan">rxjs.</span>zipAll (project)](#apidoc.element.rxjs.zipAll.zipAll)
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



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
