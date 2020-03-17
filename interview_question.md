# JavaScript Interview Questions & Answers

### Table of Contents

| No. | Questions |
|---- | ---------
|1  | [What are the possible ways to create objects in JavaScript?](#what-are-the-possible-ways-to-create-objects-in-javascript) |
|2  | [What is prototype chain?](#what-is-prototype-chain)|
|3  | [What is the difference between Call, Apply and Bind?](#what-is-the-difference-between-call-apply-and-bind)|
|4  | [What is JSON and its common operations](#what-is-json-and-its-common-operations)|
|5  | [What is the purpose of array slice method?](#what-is-the-purpose-of-array-slice-method)|
|6  | [What is the purpose of array splice method?](#what-is-the-purpose-of-array-splice-method)|
|7  | [What is the difference between slice and splice?](#what-is-the-difference-between-slice-and-splice)|
|8  | [How do you compare Object and Map?](#how-do-you-compare-object-and-map)|
|9  | [What is the difference between == and === operators?](#what-is-the-difference-between-==-and-===-operators)|
|10 | [What are lambda or arrow functions?](#what-are-lambda-or-arrow-functions)|
|11 | [What is a first class function?](#what-is-a-first-class-function)|
|12 | [What is a first order function?](#what-is-a-first-order-function)|
|13 | [What is a higher order function?](#what-is-a-higher-order-function)|
|14 | [What is a unary function?](#what-is-a-unary-function)|
|15 | [What is currying function?](#what-is-currying-function)|
|16 | [What is a pure function?](#what-is-a-pure-function)|
|17 | [What is the purpose of let keyword?](#what-is-the-purpose-of-let-keyword)|
|18 | [What is the difference between let and var?](#what-is-the-difference-between-let-and-var)|
|19 | [What is the reason to choose the name let as keyword?](#what-is-the-reason-to-choose-the-name-let-as-keyword)|
|20 | [How do you redeclare variables in switch block without an error?](#how-do-you-redeclare-variables-in-switch-block-without-an-error)|
|21 | [What is Temporal Dead Zone?](#what-is-temporal-dead-zone)|
|22 | [What is IIFE(Immediately Invoked Function Expression)?](#what-is-iife-(-immediately-invoked-function-expression-)-)|
|23 | [What is the benefit of using modules?](#what-is-the-benefit-of-using-modules)|
|24 | [What is memoization?](#what-is-memoization)|
|25 | [What is Hoisting?](#what-is-hoisting?)|
|26 | [What are classes in ES6?](#what-are-classes-in-es6)|
|27 | [What are closures?](#what-are-closures)|
|28 | [What are modules?](#what-are-modules)|
|29 | [Why do you need modules?](#why-do-you-need-modules)|
|30 | [What is scope in javascript?](#what-is-scope-in-javascript)|
|31 | [What is a service worker?](#what-is-a-service-worker)|
|32 | [How do you manipulate DOM using service worker?](#how-do-you-manipulate-dom-using-service-worker)|
|33 | [How do you reuse information across service worker restarts?](#how-do-you-reuse-information-across-service-worker-restarts)|
|34 | [What is IndexedDB?](#what-is-indexeddb)|
|35 | [What is web storage?](#what-is-web-storage)|
|36 | [What is a post message?](#what-is-a-post-message)|
|37 | [What is a cookie?](#what-is-a-cookie)|
|38 | [Why do you need a Cookie?](#why-do-you-need-a-cookie)|
|39 | [What are the options in a cookie?](#what-are-the-options-in-a-cookie)|
|40 | [How do you delete a cookie?](#how-do-you-delete-a-cookie)|
|41 | [What are the differences between cookie, local storage and session storage?](#What-are-the-differences-between-cookie,-local-storage-and-session-storage)|
|42 | [What is the main difference between localStorage and sessionStorage?](#what-is-the-main-difference-between-localstorage-and-sessionstorage)|
|43 | [How do you access web storage?](#how-do-you-access-web-storage)|
|44 | [What are the methods available on session storage?](#what-are-the-methods-available-on-session-storage)|
|45 | [What is a storage event and its event handler?](#what-is-a-storage-event-and-its-event-handler)|
|46 | [Why do you need web storage?](#why-do-you-need-web-storage)|
|47 | [How do you check web storage browser support?](#how-do-you-check-web-storage-browser-support)|
|48 | [How do you check web workers browser support?](#how-do-you-check-web-workers-browser-support)|
|49 | [Give an example of web worker?](#give-an-example-of-web-worker)|
|50 | [What are the restrictions of web workers on DOM?](#what-are-the-restrictions-of-web-workers-on-dom)|
|51 | [What is a promise?](#what-is-a-promise)|
|52 | [Why do you need a promise?](#why-do-you-need-a-promise)|
|53 | [What are the three states of promise?](#what-are-the-three-states-of-promise)|
|54 | [What is a callback function?](#what-is-a-callback-function)|
|55 | [Why do we need callbacks?](#why-do-we-need-callbacks)|
|56 | [What is a callback hell?](#what-is-a-callback-hell)|
|57 | [What is server-sent events?](#what-is-server-sent-events)|
|58 | [How do you receive server-sent event notifications?](#how-do-you-receive-server-sent-event-notifications)|
|59 | [How do you check browser support for server-sent events?](#how-do-you-check-browser-support-for-server-sent-events)|
|60 | [What are the events available for server sent events?](#what-are-the-events-available-for-server-sent-events)|
|61 | [What are the main rules of promise?](#what-are-the-main-rules-of-promise)|
|62 | [What is callback in callback?](#what-is-callback-in-callback)|
|63 | [What is promise chaining?](#what-is-promise-chaining)|
|64 | [What is promise.all](#what-is-promise.all)|
|65 | [What is the purpose of race method in promise?](#what-is-the-purpose-of-race-method-in-promise)|
|66 | [What is a strict mode in javascript?](#what-is-a-strict-mode-in-javascript)|
|67 | [Why do you need strict mode?](#why-do-you-need-strict-mode)|
|68 | [How do you declare strict mode?](#how-do-you-declare-strict-mode)|
|69 | [What is the purpose of double exclamation?](#what-is-the-purpose-of-double-exclamation)|
|70 | [What is the purpose of delete operator?](#what-is-the-purpose-of-delete-operator)|
|71 | [What is typeof operator?](#what-is-typeof-operator)|
|72 | [What is undefined property?](#what-is-undefined-property)|
|73 | [What is null value?](#what-is-null-value)|
|74 | [What is the difference between null and undefined?](#what-is-the-difference-between-null-and-undefined)|
|75 | [What is eval?](#What-is-eval)|
|76 | [What is the difference between window and document?](#what-is-the-difference-between-window-and-document)|
|77 | [How do you access history in javascript?](#how-do-you-access-history-in-javascript)|
|78 | [What are the javascript data types?](#what-are-the-javascript-data-types)|
|79 | [What is isNaN?](#what-is-isnan)|
|80 | [What are the differences between undeclared and undefined variables?](#what-are-the-differences-between-undeclared-and-undefined-variables)|
|81 | [What are global variables?](#what-are-global-variables)|
|82 | [What are the problems with global variables?](#what-are-the-problems-with-global-variables)|
|83 | [What is NaN property?](#what-is-nan-property)|
|84 | [What is the purpose of isFinite function?](#what-is-the-purpose-of-isfinite-function)
|85 | [What is an event flow?](#what-is-an-event-flow)|
|86 | [What is event bubbling?](#what-is-event-bubbling)|
|87 | [What is event capturing?](#what-is-event-capturing)|
|88 | [How do you submit a form using JavaScript?](#how-do-you-submit-a-form-using-javascript)|
|89 | [How do you find operating system details?](#how-do-you-find-operating-system-details)|
|90 | [What is the difference between document load and DOMContentLoaded events?](#what-is-the-difference-between-document-load-and-domcontentloaded-events)|
|91 | [What is the difference between native, host and user objects?](#what-is-the-difference-between-native,-host-and-user-objects)|
|92 | [What are the tools or techniques used for debugging JavaScript code?](#what-are-the-tools-or-techniques-used-for-debugging-javascript-code)|
|93 | [What are the pros and cons of promises over callbacks?](#what-are-the-pros-and-cons-of-promises-over-callbacks)|
|94 | [What is the difference between an attribute and a property?](#what-is-the-difference-between-an-attribute-and-a-property)|
|95 | [What is same-origin policy?](#what-is-same-origin-policy)|
|96 | [What is the purpose of void 0?](#what-is-the-purpose-of-void-0)|
|97 | [Is JavaScript a compiled or interpreted language?](#is-javascript-a-compiled-or-interpreted-language)|
|98 | [Is JavaScript a case-sensitive language?](#is-javascript-a-case-sensitive-language)|
|99 | [Is there any relation between Java and JavaScript?](#is-there-any-relation-between-java-and-javascript)|
|100| [What are events?](#what-are-events)|
|101| [Who created javascript?](#who-created-javascript)|
|102| [What is the use of preventDefault method?](#what-is-the-use-of-preventdefault-method)|
|103| [What is the use of stopPropagation method?](#what-is-the-use-of-stoppropagation-method)|
|104| [What are the steps involved in return false?](#what-are-the-steps-involved-in-return-false)|
|105| [What is BOM?](#what-is-bom)|
|106| [What is the use of setTimeout?](#what-is-the-use-of-settimeout)|
|107| [What is the use of setInterval?](#what-is-the-use-of-setinterval)|
|108| [Why is JavaScript treated as Single threaded?](#why-is-javascript-treated-as-single-threaded)|
|109| [What is an event delegation?](#what-is-an-event-delegation)|
|110| [What is ECMAScript?](#what-is-ecmascript)|
|111| [What is JSON?](#what-is-json)|
|112| [What are the syntax rules of JSON?](#what-are-the-syntax-rules-of-json)|
|113| [What is the purpose JSON stringify?](#what-is-the-purpose-json-stringify)|
|114| [How do you parse JSON string?](#how-do-you-parse-json-string)|
|115| [Why do you need JSON?](#why-do-you-need-json)|
|116| [What are PWAs?](#what-are-pwas?)|
|117| [What is the purpose of clearTimeout method?](#what-is-the-purpose-of-cleartimeout-method)|
|118| [What is the purpose of clearInterval method?](#what-is-the-purpose-of-clearinterval-method)|
|119| [How do you redirect new page in javascript?](#how-do-you-redirect-new-page-in-javascript)|
|120| [How do you check whether a string contains a substring?](#how-do-you-check-whether-a-string-contains-a-substring)|
|121| [How do you validate an email in javascript?](#how-do-you-validate-an-email-in-javascript)|
|122| [How do you get the current url with javascript?](#how-do-you-get-the-current-url-with-javascript)|
|123| [What are the various url properties of location object?](#what-are-the-various-url-properties-of-location-object)|
|124| [How do get query string values in javascript?](#how-do-get-query-string-values-in-javascript)|
|125| [How do you check if a key exists in an object?](#how-do-you-check-if-a-key-exists-in-an-object)|
|126| [How do you loop through or enumerate javascript object?](#how-do-you-loop-through-or-enumerate-javascript-object)|
|127| [How do you test for an empty object?](#how-do-you-test-for-an-empty-object)|
|128| [What is an arguments object?](#what-is-an-arguments-object)|
|129| [How do you make first letter of the string in an uppercase?](#how-do-you-make-first-letter-of-the-string-in-an-uppercase)|
|130| [What are the pros and cons of for loop?](#what-are-the-pros-and-cons-of-for-loop)|
|131| [How do you display the current date in javascript?](#how-do-you-display-the-current-date-in-javascript)|
|132| [How do you compare two date objects?](#how-do-you-compare-two-date-objects)|
|133| [How do you check if a string starts with another string?](#how-do-you-check-if-a-string-starts-with-another-string)|
|134| [How do you trim a string in javascript?](#how-do-you-trim-a-string-in-javascript)|
|135| [How do you add a key value pair in javascript?](#how-do-you-add-a-key-value-pair-in-javascript)|
|136| [Is the '!--' notation represents a special operator?](#is-the-'!--'-notation-represents-a-special-operator)|
|137| [How do you assign default values to variables?](#how-do-you-assign-default-values-to-variables)|
|138| [How do you define multiline strings?](#how-do-you-define-multiline-strings)|
|139| [What is an app shell model?](#what-is-an-app-shell-model)|
|140| [Can we define properties for functions?](#can-we-define-properties-for-functions)|
|141| [What is the way to find the number of parameters expected by a function?](#what-is-the-way-to-find-the-number-of-parameters-expected-by-a-function)|
|142| [What is a polyfill?](#what-is-a-polyfill)|
|143| [What are break and continue statements?](#what-are-break-and-continue-statements)|
|144| [What are js labels?](#what-are-js-labels)|
|145| [What are the benefits of keeping declarations at the top?](#what-are-the-benefits-of-keeping-declarations-at-the-top)|
|146| [What are the benefits of initializing variables?](#what-are-the-benefits-of-initializing-variables)|
|147| [What are the recommendations to create new object?](#what-are-the-recommendations-to-create-new-object)|
|148| [How do you define JSON arrays?](#how-do-you-define-json-arrays)|
|149| [How do you generate random integers?](#how-do-you-generate-random-integers)|
|150| [Can you write a random integers function to print integers with in a range?](#can-you-write-a-random-integers-function-to-print-integers-with-in-a-range)|
|151| [What is tree shaking?](#what-is-tree-shaking)|
|152| [What is the need of tree shaking?](#what-is-the-need-of-tree-shaking)|
|153| [Is it recommended to use eval?](#is-it-recommended-to-use-eval)|
|154| [What is a Regular Expression?](#what-is-a-regular-expression)|
|155| [What are the string methods available in Regular expression?](#what-are-the-string-methods-available-in-regular-expression)|
|156| [What are modifiers in regular expression?](#what-are-modifiers-in-regular-expression)|
|157| [What are regular expression patterns?](#what-are-regular-expression-patterns)|
|158| [What is a RegExp object?](#what-is-a-regexp-object)|
|159| [How do you search a string for a pattern?](#how-do-you-search-a-string-for-a-pattern)|
|160| [What is the purpose of exec method?](#what-is-the-purpose-of-exec-method)|
|161| [How do you change style of a HTML element?](#how-do-you-change-style-of-a-html-element)|
|162| [What would be the result of 1+2+'3'?](#what-would-be-the-result-of-1+2+'3')|
|163| [What is a debugger statement?](#what-is-a-debugger-statement)|
|164| [What is the purpose of breakpoints in debugging?](#what-is-the-purpose-of-breakpoints-indebugging)|
|165| [Can I use reserved words as identifiers?](#can-i-use-reserved-words-as-identifiers)|
|166| [How do you detect a mobile browser?](#how-do-you-detect-a-mobile-browser)|
|167| [How do you detect a mobile browser without regexp?](#how-do-you-detect-a-mobile-browser-without-regexp)|
|168| [How do you get the image width and height using JS?](#how-do-you-get-the-image-width-and-height-using-js)|
|169| [How do you make synchronous HTTP request?](#how-do-you-make-synchronous-http-request)|
|170| [How do you make asynchronous HTTP request?](#how-do-you-make-asynchronous-http-request)|
|171| [How do you convert date to another timezone in javascript?](#how-do-you-convert-date-to-another-timezone-in-javascript)|
|172| [What are the properties used to get size of window?](#what-are-the-properties-used-to-get-size-of-window)|
|173| [What is a conditional operator in javascript?](#what-is-a-conditional-operator-in-javascript)|
|174| [Can you apply chaining on conditional operator?](#Can-you-apply-chaining-on-conditional-operator)|
|175| [What are the ways to execute javascript after page load?](#what-are-the-ways-to-execute-javascript-after-page-load)|
|176| [What is the difference between proto and prototype?](#what-is-the-difference-between-proto-and-prototype)|
|177| [Give an example where do you really need semicolon?](#give-an-example-where-do-you-really-need-semicolon)|
|178| [What is a freeze method?](#what-is-a-freeze-method)|
|179| [What is the purpose of freeze method?](#what-is-the-purpose-of-freeze-method)|
|180| [Why do I need to use freeze method?](#why-do-i-need-to-use-freeze-method)|
|181| [How do you detect a browser language preference?](#how-do-you-detect-a-browser-language-preference)|
|182| [How to convert string to title case with javascript?](#how-to-convert-string-to-title-case-with-javascript)|
|183| [How do you detect javascript disabled in the page?](#how-do-you-detect-javascript-disabled-in-the-page)|
|184| [What are various operators supported by javascript?](#what-are-various-operators-supported-by-javascript)|
|185| [What is a rest parameter?](#what-is-a-rest-parameter)|
|186| [What happens if you do not use rest parameter as a last argument?](#what-happens-if-you-do-not-use-rest-parameter-as-a-last-argument)|
|187| [What are the bitwise operators available in javascript?](#what-are-the-bitwise-operators-available-in-javascript)|
|188| [What is a spread operator?](#what-is-a-spread-operator)|
|189| [How do you determine whether object is frozen or not?](#how-do-you-determine-whether-object-is-frozen-or-not)|
|190| [How do you determine two values same or not using object?](#how-do-you-determine-two-values-same-or-not-using-object)|
|191| [What is the purpose of using object is method?](#what-is-the-purpose-of-using-object-is-method)|
|192| [How do you copy properties from one object to other?](#how-do-you-copy-properties-from-one-object-to-other)|
|193| [What are the applications of assign method?](#what-are-the-applications-of-assign-method)|
|194| [What is a proxy object?](#what-is-a-proxy-object)|
|195| [What is the purpose of seal method?](#what-is-the-purpose-of-seal-method)|
|196| [What are the applications of seal method?](#what-are-the-applications-of-seal-method)|
|197| [What are the differences between freeze and seal methods?](#what-are-the-differences-between-freeze-and-seal-methods)|
|198| [How do you determine if an object is sealed or not?](#how-do-you-determine-if-an-object-is-sealed-or-not)|
|199| [How do you get enumerable key and value pairs?](#how-do-you-get-enumerable-key-and-value-pairs)|
|200| [What is the main difference between Object.values and Object.entries method?](#what-is-the-main-difference-between-object.values-and-object.entries-method)|
|201| [How can you get the list of keys of any object?](#how-can-you-get-the-list-of-keys-of-any-object)|
|202| [How do you create an object with prototype?](#how-do-you-create-an-object-with-prototype)|
|203| [What is a WeakSet?](#what-is-a-weakset)|
|204| [What are the differences between WeakSet and Set?](#what-are-the-differences-between-weakset-and-set)|
|205| [List down the collection of methods available on WeakSet?](#list-down-the-collection-of-methods-available-on-weakset)|
|206| [What is a WeakMap?](#what-is-a-weakmap)|
|207| [What are the differences between WeakMap and Map?](#what-are-the-differences-between-weakmap-and-map)|
|208| [List down the collection of methods available on WeakMap?](#list-down-the-collection-of-methods-available-on-weakmap)|
|209| [What is the purpose of uneval?](#what-is-the-purpose-of-uneval)|
|210| [How do you encode an URL?](#how-do-you-encode-an-url)|
|211| [How do you decode an URL?](#how-do-you-decode-an-url)|
|212| [How do you print the contents of web page?](#how-do-you-print-the-contents-of-web-page)|
|213| [What is the difference between uneval and eval?](#what-is-the-difference-between-uneval-and-eval)|
|214| [What is an anonymous function?](#what-is-an-anonymous-function)|
|215| [What is the precedence order between local and global variables?](#what-is-the-precedence-order-between-local-and-global-variables)|
|216| [What are javascript accessors?](#what-are-javascript-accessors)|
|217| [How do you define property on Object constructor?](#how-do-you-define-property-on-object-constructor)|
|218| [What is the difference between get and defineProperty?](#what-is-the-difference-between-get-and-defineproperty)|
|219| [What are the advantages of Getters and Setters?](#what-are-the-advantages-of-getters-and-setters)|
|220| [Can I add getters and setters using defineProperty method?](#can-i-add-getters-and-setters-using-defineproperty-method)|
|221| [What is the purpose of switch-case?](#what-is-the-purpose-of-switch-case)|
|222| [What are the conventions to be followed for the usage of swtich case?](#what-are-the-conventions-to-be-followed-for-the-usage-of-swtich-case)|
|223| [What are primitive data types?](#what-are-primitive-data-types)|
|224| [What are the different ways to access object properties?](#what-are-the-different-ways-to-access-object-properties)|
|225| [What are the function parameter rules?](#what-are-the-function-parameter-rules)|
|226| [What is an error object?](#what-is-an-error-object)|
|227| [When you get a syntax error?](#when-you-get-a-syntax-error)|
|228| [What are the different error names from error object?](#what-are-the-different-error-names-from-error-object)|
|229| [What are the various statements in error handling?](#what-are-the-various-statements-in-error-handling)|
|230| [What are the two types of loops in javascript?](#what-are-the-two-types-of-loops-in-javascript)|
|231| [What is nodejs?](#what-is-nodejs)|
|232| [What is an Intl object?](#what-is-an-intl-object)|
|233| [How do you perform language specific date and time formatting?](#how-do-you-perform-language-specific-date-and-time-formatting)|
|234| [What is an Iterator?](#what-is-an-iterator)|
|235| [What is an event loop?](#what-is-an-event-loop)|
|236| [What is call stack?](#what-is-call-stack)|
|237| [What is an event queue?](#what-is-an-event-queue)|
|238| [What is a decorator?](#what-is-a-decorator)|
|239| [What are the properties of Intl object?](#what-are-the-properties-of-intl-object)|
|240| [What is an Unary operator?](#what-is-an-unary-operator)|
|241| [How do you sort elements in an array?](#how-do-you-sort-elements-in-an-array)|
|242| [What is the purpose of compareFunction while sorting arrays?](#what-is-the-purpose-of-comparefunction-while-sorting-arrays)|
|243| [How do you reversing an array?](#how-do-you-reversing-an-array)|
|244| [How do you find min and max value in an array?](#how-do-you-find-min-and-max-value-in-an-array)|
|245| [How do you find min and max values without Math functions?](#how-do-you-find-min-and-max-values-without--math-functions)|
|246| [What is an empty statement and purpose of it?](#what-is-an-empty-statement-and-purpose-of-it)|
|247| [How do you get meta data of a module?](#how-do-you-get-meta-data-of-a-module)|
|248| [What is a comma operator?](#what-is-a-comma-operator)|
|249| [What is the advantage of a comma operator?](#what-is-the-advantage-of-a-comma-operator)|
|250| [What is typescript?](#what-is-typescript)|
|251| [What are the differences between javascript and typescript?](#what-are-the-differences-between-javascript-and-typescript)|
|252| [What are the advantages of typescript over javascript?](#what-are-the-advantages-of-typescript-over-javascript)|
|253| [What is an object initializer?](#what-is-an-object-initializer)|
|254| [What is a constructor method?](#what-is-a-constructor-method)|
|255| [What happens if you write constructor more than once in a class?](#what-happens-if-you-write-constructor-more-than-once-in-a-class)|
|256| [How do you call the constructor of a parent class?](#how-do-you-call-the-constructor-of-a-parent-class)|
|257| [How do you get the prototype of an object?](#how-do-you-get-the-prototype-of-an-object)|
|258| [What happens If I pass string type for getPrototype method?](#what-happens-if-i-pass-string-type-for-getprototype-method)|
|259| [How do you set prototype of one object to another?](#how-do-you-set-prototype-of-one-object-to-another)|
|260| [How do you check whether an object can be extendable or not?](#how-do-you-check-whether-an-object-can-be-extendable-or-not)|
|261| [How do you prevent an object to extend?](#how-do-you-prevent-an-object-to-extend)|
|262| [What are the different ways to make an object non-extensible?](#what-are-the-different-ways-to-make-an-object-non-extensible)|
|263| [How do you define multiple properties on an object?](#how-do-you-define-multiple-properties-on-an-object)|
|264| [What is MEAN in javascript?](#what-is-mean-in-javascript)|
|265| [What Is Obfuscation in javascript?](#what-is-obfuscation-in-javascript)|
|266| [Why do you need Obfuscation?](#why-do-you-need-obfuscation)|
|267| [What is Minification?](#what-is-minification)|
|268| [What are the advantages of minification?](#what-are-the-advantages-of-minification)|
|269| [What are the differences between Obfuscation and Encryption?](#what-are-the-differences-between-obfuscation-and-encryption)|
|270| [What are the common tools used for minification?](#what-are-the-common-tools-used-for-minification)|
|271| [How do you perform form validation using javascript?](#how-do-you-perform-form-validation-using-javascript)|
|272| [How do you perform form validation without javascript?](#how-do-you-perform-form-validation-without-javascript)|
|273| [What are the DOM methods available for constraint validation?](#what-are-the-dom-methods-available-for-constraint-validation)|
|274| [What are the available constraint validation DOM properties?](#what-are-the-available-constraint-validation-dom-properties)|
|275| [What are the list of validity properties?](#what-are-the-list-of-validity-properties)|
|276| [Give an example usage of rangeOverflow property?](#give-an-example-usage-of-rangeoverflow-property)|
|277| [Is enums feature available in javascript?](#is-enums-feature-available-in-javascript)|
|278| [What is an enum?](#What-is-an-enum)|
|279| [How do you list all properties of an object?](#how-do-you-list-all-properties-of-an-object)|
|280| [How do you get property descriptors of an object?](#how-do-you-get-property-descriptors-of-an-object)|
|281| [What are the attributes provided by a property descriptor?](#what-are-the-attributes-provided-by-a-property-descriptor)|
|282| [How do you extend classes?](#how-do-you-extend-classes)|
|283| [How do I modify the url without reloading the page?](#how-do-i-modify-the-url-without-reloading-the-page)|
|284| [How do you check whether an array includes a particular value or not?](#how-do-you-check-whether-an-array-includes-a-particular-value-or-not)|
|285| [How do you compare scalar arrays?](#how-do-you-compare-scalar-arrays)|
|286| [How to get the value from get parameters?](#how-to-get-the-value-from-get-parameters)|
|287| [How do you print numbers with commas as thousand separators?](#how-do-you-print-numbers-with-commas-as-thousand-separators)|
|288| [What is the difference between java and javascript?](#what-is-the-difference-between-java-and-javascript)|
|289| [Is javascript supports namespace?](#is-javascript-supports-namespace)|
|290| [How do you declare namespace?](#how-do-you-declare-namespace)|
|291| [How do you invoke javascript code in an iframe from parent page?](#how-do-you-invoke-javascript-code-in-an-iframe-from-parent-page)|
|292| [How do get the timezone offset from date?](#how-do-get-the-timezone-offset-from-date)|
|293| [How do you load CSS and JS files dynamically?](#how-do-you-load-css-and-js-files-dynamically)|
|294| [What are the different methods to find HTML elements in DOM?](#what-are-the-different-methods-to-find-html-elements-in-dom)|
|295| [What is jQuery?](#what-is-jquery)|
|296| [What is V8 JavaScript engine?](#what-is-v8-javascript-engine)|
|297| [Why do we call javascript as dynamic language?](#why-do-we-call-javascript-as-dynamic-language)|
|298| [What is a void operator?](#what-is-a-void-operator)|
|299| [How to set the cursor to wait?](#how-to-set-the-cursor-to-wait)|
|300| [How do you create an infinite loop?](#how-do-you-create-an-infinite-loop)|
|301| [Why do you need to avoid with statement?](#why-do-you-need-to-avoid-with-statement)|
|302| [What is the output of below for loops?](#what-is-the-output-of-below-for-loops)|
|303| [List down some of the features of ES6?](#list-down-some-of-the-features-of-es6)|
|304| [What is ES6?](#what-is-es6)|
|305| [Can I redeclare let and const variables?](#can-I-redeclare-let-and-const-variables)|
|306| [Is const variable makes the value immutable?](#is-const-variable-makes-the-value-immutable)|
|307| [What are default parameters?](#what-are-default-parameters)|
|308| [What are template literals?](#what-are-template-literals)|
|309| [How do you write multi-line strings in template literals?](#how-do-you-write-multi-line-strings-in-template-literals)|
|310| [What are nesting templates?](#what-are-nesting-templates)|
|311| [What are tagged templates?](#what-are-tagged-templates)|
|312| [What are raw strings?](#what-are-raw-strings)|
|313| [What is destructuring assignment?](#what-is-destructuring-assignment)|
|314| [What are default values in destructuring assignment?](#what-are-default-values-in-destructuring-assignment)|
|315| [How do you swap variables in destructuring assignment?](#how-do-you-swap-variables-in-destructuring-assignment)|
|316| [What are enhanced object literals?](#what-are-enhanced-object-literals)|
|317| [What are dynamic imports?](#what-are-dynamic-imports)|
|318| [What are the use cases for dynamic imports?](#what-are-the-use-cases-for-dynamic-imports)|
|319| [What are typed arrays?](#what-are-typed-arrays)|
|320| [What are the advantages of module loaders?](#what-are-the-advantages-of-module-loaders)|
|321| [What is collation?](#what-is-collation)|
|322| [What is for...of statement?](#what-is-for...of-statement)|
|323| [What is the output of below spread operator array?](#what-is-the-output-of-below-spread-operator-array)|
|324| [Is PostMessage secure?](#is-postmessage-secure)|
|325| [What are the problems with postmessage target origin as wildcard?](#what-are-the-problems-with-postmessage-target-origin-as-wildcard)|
|326| [How do you avoid receiving postMessages from attackers?](#how-do-you-avoid-receiving-postmessages-from-attackers)|
|327| [Can I avoid using postMessages completely?](#can-i-avoid-using-postmessages-completely)|
|328| [Is postMessages synchronous?](#is-postmessages-synchronous)|
|329| [What paradigm is Javascript?](#what-paradigm-is-javascript)|
|330| [What is the difference between internal and external javascript?](#what-is-the-difference-between-internal-and-external-javascript)|
|331| [Is JavaScript faster than server side script?](#is-javascript-faster-than-server-side-script)|
|332| [How do you get the status of a checkbox?](#how-do-you-get-the-status-of-a-checkbox)|
|333| [What is the purpose of double tilde operator?](#what-is-the-purpose-of-double-tilde-operator)|
|334| [How do you convert character to ASCII code?](#how-do-you-convert-character-to-ascii-code)|
|335| [What is ArrayBuffer?](#what-is-arraybuffer)|
|336| [What is the output of below string expression?](#what-is-the-output-of-below-string-expression)|
|337| [What is the purpose of Error object?](#what-is-the-purpose-of-error-object)|
|338| [What is the purpose of EvalError object?](#what-is-the-purpose-of-evalerror-object)|
|339| [What are the list of cases error thrown from non-strict mode to strict mode?](#what-are-the-list-of-cases-error-thrown-from-non-strict-mode-to-strict-mode)|
|340| [Is all objects have prototypes?](#is-all-objects-have-prototypes)|
|341| [What is the difference between a parameter and an argument?](#what-is-the-difference-between-a-parameter-and-an-argument)|
|342| [What is the purpose of some method in arrays?](#what-is-the-purpose-of-some-method-in-arrays)|
|343| [How do you combine two or more arrays?](#how-do-you-combine-two-or-more-arrays)|
|344| [What is the difference between Shallow and Deep copy?](#what-is-the-difference-between-shallow-and-deep-copy)|
|345| [How do you create specific number of copies of a string?](#how-do-you-create-specific-number-of-copies-of-a-string)|
|346| [How do you return all matching strings against a regular expression?](#how-do-you-return-all-matching-strings-against-a-regular-expression)|
|347| [How do you trim a string at the beginning or ending?](#how-do-you-trim-a-string-at-the-beginning-or-ending)|
|348| [What is the output of below console statement with unary operator?](#what-is-the-output-of-below-console-statement-with-unary-operator)|
|349| [Does javascript uses mixins?](#does-javascript-uses-mixins)|
|350| [What is a thunk function?](#what-is-a-thunk-function)|
|351| [What are asynchronous thunks?](#what-are-asynchronous-thunks)|
|352| [What is the output of below function calls?](#what-is-the-output-of-below-function-calls)|
|353| [How to remove all line breaks from a string?](#how-to-remove-all-line-breaks-from-a-string)|
|354| [What is the difference between reflow and repaint?](#what-is-the-difference-between-reflow-and-repaint)|
|355| [What happens with negating an array?](#what-happens-with-negating-an-array)|
|356| [What happens if we add two arrays?](#what-happens-if-we-add-two-arrays)|
|357| [What is the output of prepend additive operator on falsy values?](#what-is-the-output-of-prepend-additive-operator-on-falsy-values)|
|358| [How do you create self string using special characters?](#how-do-you-create-self-string-using-special-characters)|
|358| [How do you remove falsy values from an array?](#how-do-you-remove-falsy-values-from-an-array)|
|359| [How do you get unique values of an array?](#how-do-you-get-unique-values-of-an-array)|
|360| [What is destructuring aliases?](#what-is-destructuring-aliases)|
|361| [How do you map the array values without using map method?](#how-do-you-map-the-array-values-without-using-map-method)|
|362| [How do you empty an array?](#how-do-you-empty-an-array)|
|363| [How do you rounding numbers to certain decimals](#how-do-you-rounding-numbers-to-certain-decimals)|
|364| [What is the easiest way to convert an array to an object?](#what-is-the-easiest-way-to-convert-an-array-to-an-object)|
|365| [How do you create an array with some data?](#how-do-you-create-an-array-with-some-data)|
|366| [What are the placeholders from console object?](#what-are-the-placeholders-from-console-object)|
|367| [Is it possible to add CSS to console messages?](#is-it-possible-to-add-css-to-console-messages)|
|368| [What is the purpose of dir method of console object?](#what-is-the-purpose-of-dir-method-of-console-object)|
|369| [Is it possible to debug HTML elements in console?](#is-it-possible-to-debug-html-elements-in-console)|
|370| [How do you display data in a tabular format using console object?](#how-do-you-display-data-in-a-tabular-format-using-console-object)|
|371| [How do you verify that an argument is a Number or not?](#how-do-you-verify-that-an-argument-is-a-number-or-not)|
|372| [How do you create copy to clipboard button?](#how-do-you-create-copy-to-clipboard-button)|
|373| [What is the shortcut to get timestamp?](#what-is-the-shortcut-to-get-timestamp)|
|374| [How do you flattening multi dimensional arrays?](#how-do-you-flattening-multi-dimensional-arrays)|
|375| [What is the easiest multi condition checking?](#what-is-the-easiest-multi-condition-checking)|
|376| [How do you capture browser back button?](#how-do-you-capture-browser-back-button)|
|377| [How do you disable right click in the web page?](#how-do-you-disable-right-click-in-the-web-page)|
|378| [](#)|
|379| [](#)|
|380| [](#)|
|381| [](#)|
|382| [](#)|
|383| [](#)|
|384| [](#)|
|385| [](#)|
|386| [](#)|
|387| [](#)|
|388| [](#)|
|389| [](#)|
|390| [](#)|
|391| [](#)|
|392| [](#)|
|393| [](#)|
|394| [](#)|
|395| [](#)|
|396| [](#)|
|397| [](#)|
|398| [](#)|
|399| [](#)|
|400| [](#)|

1. ### What are the possible ways to create objects in JavaScript?

There are many ways to create objects in javascript as below,

1. **Object constructor:**

 The simplest way to create an empty object is using Object constructor. Currently this approach is not recommended.

 ```javascript
 var object = new Object();
 ```

 2. **Object's create method:**

 The create method of Object creates a new object by passing the prototype object as a parameter
 ```javascript
 var object = Object.create(null);
 ```

 3. **Object literal syntax:**
 The object literal syntax is equivalent to create method when it passes null as parameter
 ```javascript
 var object = {};
 ```

 4. **Function constructor:**
 Create any function and apply the new operator to create object instances,
 ```javascript
 function Person(name){
  var object = {};
  object.name=name;
  object.age=21;
  return object;
 }
 var object = new Person("Sudheer");
 ```

 5. **Function constructor with prototype:**
 This is similar to function constructor but it uses prototype for their properties and methods,

```javascript
function Person(){}
Person.prototype.name = "Sudheer";
var object = new Person();
```

This is equivalent to an instance created with an object create method with a function prototype and then call that function with an instance and parameters as arguments.
```javascript
function func {};

new func(x, y, z);

**(OR)**

// Create a new instance using function prototype.
var newInstance = Object.create(func.prototype)

// Call the function
var result = func.call(newInstance, x, y, z),

// If the result is a non-null object then use it otherwise just use the new instance.
console.log(result && typeof result === 'object' ? result : newInstance);
```

6. **ES6 Class syntax:**
ES6 introduces class feature to create the objects
```javascript
class Person {
 constructor(name) {
    this.name = name;
 }
}

var object = new Person("Sudheer");
```

7. **Singleton pattern:**
A Singleton is an object which can only be instantiated one time. Repeated calls to its constructor return the same instance and this way one can ensure that they don't accidentally create multiple instances.
```javascript
var object = new function(){
  this.name = "Sudheer";
}
```

**[⬆ Back to Top](#table-of-contents)**

2. ### What is prototype chain?

**Prototype chaining** is used to build new types of objects based on existing ones. It is similar to inheritance in a class based language. The prototype on object instance is available through Object.getPrototypeOf(object) or __proto__ property whereas prototype on constructors function is available through object.prototype.

**[⬆ Back to Top](#table-of-contents)**

3. ### What is the difference between Call, Apply and Bind?
The difference between Call, Apply and Bind can be explained with below examples,
**Call:** The call() method invokes a function with a given `this` value and arguments provided one by one
```javascript
var employee1 = {firstName: 'John', lastName: 'Rodson'};
var employee2 = {firstName: 'Jimmy', lastName: 'Baily'};

function invite(greeting1, greeting2) {
    console.log(greeting1 + ' ' + this.firstName + ' ' + this.lastName+ ', '+ greeting2);
}

invite.call(employee1, 'Hello', 'How are you?'); // Hello John Rodson, How are you?
invite.call(employee2, 'Hello', 'How are you?'); // Hello Jimmy Baily, How are you?
```
**Apply:** Invokes the function and allows you to pass in arguments as an array
```javascript
var employee1 = {firstName: 'John', lastName: 'Rodson'};
var employee2 = {firstName: 'Jimmy', lastName: 'Baily'};

function invite(greeting1, greeting2) {
    console.log(greeting1 + ' ' + this.firstName + ' ' + this.lastName+ ', '+ greeting2);
}

invite.apply(employee1, ['Hello', 'How are you?']); // Hello John Rodson, How are you?
invite.apply(employee2, ['Hello', 'How are you?']); // Hello Jimmy Baily, How are you?
```
**bind:** returns a new function, allowing you to pass in an array and any number of arguments
```javascript
var employee1 = {firstName: 'John', lastName: 'Rodson'};
var employee2 = {firstName: 'Jimmy', lastName: 'Baily'};

function invite(greeting1, greeting2) {
    console.log(greeting1 + ' ' + this.firstName + ' ' + this.lastName+ ', '+ greeting2);
}

var inviteEmployee1 = invite.bind(employee1);
var inviteEmployee2 = invite.bind(employee2);
inviteEmployee1('Hello', 'How are you?'); // Hello John Rodson, How are you?
inviteEmployee2('Hello', 'How are you?'); // Hello Jimmy Baily, How are you?
```
Call and apply are pretty interchangeable. Both execute the current function immediately. You need to decide whether it’s easier to send in an array or a comma separated list of arguments. You can remember by treating Call is for comma (separated list) and Apply is for Array. Whereas Bind creates a new function that will have `this` set to the first parameter passed to bind().

**[⬆ Back to Top](#table-of-contents)**

4. ### What is JSON and its common operations?

**JSON** is a text-based data format following JavaScript object syntax, which was popularized by Douglas Crockford. It is useful when you want to transmit data across a network and it is basically just a text file with an extension of .json, and a MIME type of application/json
Parsing: **Converting a string to a native object
```javascript
JSON.parse(text)
```
Stringification: **converting a native object to a string so it can be transmitted across the network
```javascript
JSON.stringify(object)
```

**[⬆ Back to Top](#table-of-contents)**

5. ### What is the purpose of array slice method?

The **slice()** method returns the selected elements in an array as a new array object. It selects the elements starting at the given start argument, and ends at the given optional end argument without including the last element. If you omit the second argument then it selects till the end. Some of the examples of this method are,
```javascript
let arrayIntegers = [1, 2, 3, 4, 5];
let arrayIntegers1 = arrayIntegers.slice(0,2); // returns [1,2]
let arrayIntegers2 = arrayIntegers.slice(2,3); // returns [3]
let arrayIntegers3 = arrayIntegers.slice(4); //returns [5]
```
**Note:** Slice method won't mutate the original array but it returns the subset as new array.

**[⬆ Back to Top](#table-of-contents)**

6. ### What is the purpose of array splice method?

The **splice()** method is used either adds/removes items to/from an array, and then returns the removed item. The first argument specifies the array position for insertion or deletion whereas the option second argument indicates the number of elements to be deleted. Each additional argument is added to the array. Some of the examples of this method are,
```javascript
let arrayIntegersOriginal1 = [1, 2, 3, 4, 5];
let arrayIntegersOriginal2 = [1, 2, 3, 4, 5];
let arrayIntegersOriginal3 = [1, 2, 3, 4, 5];

let arrayIntegers1 = arrayIntegersOriginal1.splice(0,2); // returns [1, 2]; original array: [3, 4, 5]
let arrayIntegers2 = arrayIntegersOriginal2.splice(3); // returns [4, 5]; original array: [1, 2, 3]
let arrayIntegers3 = arrayIntegersOriginal3.splice(3, 1, "a", "b", "c"); //returns [4]; original array: [1, 2, 3, "a", "b", "c", 5]
```
**Note:** Splice method modifies the original array and returns the deleted array.

**[⬆ Back to Top](#table-of-contents)**

7. ### What is the difference between slice and splice?

Some of the major difference in a tabular form

| Slice | Splice |
|---- | ---------
| Doesn't modify the original array(immutable)  | Modifies the original array(mutable) |
| Returns the subset of original array | Returns the deleted elements as array  |
| Used to pick the elements from array | Used to insert or delete elements to/from array|

**[⬆ Back to Top](#table-of-contents)**

8. ### How do you compare Object and Map?
**Objects** are similar to **Maps** in that both let you set keys to values, retrieve those values, delete keys, and detect whether something is stored at a key. Due to this reason, Objects have been used as Maps historically. But there are important differences that make using a Map preferable in certain cases.

1. The keys of an Object are Strings and Symbols, whereas they can be any value for a Map, including functions, objects, and any primitive.
2. The keys in Map are ordered while keys added to object are not. Thus, when iterating over it, a Map object returns keys in order of insertion.
3. You can get the size of a Map easily with the size property, while the number of properties in an Object must be determined manually.
4. A Map is an iterable and can thus be directly iterated, whereas iterating over an Object requires obtaining its keys in some fashion and iterating over them.
5. An Object has a prototype, so there are default keys in the map that could collide with your keys if you're not careful. As of ES5 this can be bypassed by using map = Object.create(null), but this is seldom done.
6. A Map may perform better in scenarios involving frequent addition and removal of key pairs.

**[⬆ Back to Top](#table-of-contents)**

9. ### What is the difference between == and === operators?
JavaScript provides both strict(===, !==) and type-converting(==, !=) equality comparison. The strict operators takes type of variable in consideration, while non-strict operators make type correction/conversion based upon values of variables. The strict operators follow the below conditions for different types,
1. Two strings are strictly equal when they have the same sequence of characters, same length, and same characters in corresponding positions.
2. Two numbers are strictly equal when they are numerically equal. i.e, Having the same number value.
   There are two special cases in this,
   1. NaN is not equal to anything, including NaN.
   2. Positive and negative zeros are equal to one another.
3. Two Boolean operands are strictly equal if both are true or both are false.
4. Two objects are strictly equal if they refer to the same Object.
5. Null and Undefined types are not equal with ===, but equal with ==. i.e,
    null===undefined --> false but null==undefined --> true

Some of the example which covers the above cases
```javascript
0 == false   // true
0 === false  // false
1 == "1"     // true
1 === "1"    // false
null == undefined // true
null === undefined // false
'0' == false // true
'0' === false // false
[]==[] or []===[] //false, refer different objects in memory
{}=={} or {}==={} //false, refer different objects in memory
```

**[⬆ Back to Top](#table-of-contents)**

10. ### What are lambda or arrow functions?
An arrow function is a shorter syntax for a function expression and does not have its own **this, arguments, super, or new.target**. These function are best suited for non-method functions, and they cannot be used as constructors.

**[⬆ Back to Top](#table-of-contents)**

11. ### What is a first class function?
In Javascript, functions are first class objects. First-class functions means when functions in that language are treated like any other variable. For example, in such a language, a function can be passed as an argument to other functions, can be returned by another function and can be assigned as a value to a variable. For example, in the below example, handler functions assigned to a listener
```javascript
const handler = () => console.log ('This is a click handler function');
document.addEventListener ('click', handler);
```

**[⬆ Back to Top](#table-of-contents)**

12. ### What is a first order function?
First-order function is a function that doesn’t accept other function as an argument and doesn’t return a function as its return value.
```javascript
const firstOrder = () => console.log ('I am a first order function!');
```

**[⬆ Back to Top](#table-of-contents)**

13. ### What is a higher order function?
Higher-order function is a function that accepts other function as an argument or returns a function as a return value.
```javascript
const firstOrderFunc = () => console.log ('Hello I am a First order function');
const higherOrder = ReturnFirstOrderFunc => ReturnFirstOrderFunc ();
higherOrder (firstOrderFunc);
```

**[⬆ Back to Top](#table-of-contents)**

14. ### What is a unary function?
Unary function (i.e. monadic) is a function that accepts exactly one argument. Let us take an example of unary function. It stands for single argument accepted by a function.
```javascript
const unaryFunction = a => console.log (a + 10); //Add 10 to the given argument and display the value
```

**[⬆ Back to Top](#table-of-contents)**

15. ### What is currying function?
Currying is the process of taking a function with multiple arguments and turning it into a sequence of functions each with only a single argument. Currying is named after a mathematician Haskell Curry. By applying currying, a n-ary function turns it into a unary function. Let's take an example of n-ary function and how it turns into a currying function
```javascript
const multiArgFunction = (a, b, c) => a + b + c;
const curryUnaryFunction = a => b => c => a + b + c;
curryUnaryFunction (1); // returns a function: b => c =>  1 + b + c
curryUnaryFunction (1) (2); // returns a function: c => 3 + c
curryUnaryFunction (1) (2) (3); // returns the number 6
```
Curried functions are great to improve code re-usability and functional composition.

**[⬆ Back to Top](#table-of-contents)**

16. ### What is a pure function?

A **Pure function** is a function where the return value is only determined by its arguments without any side effects. i.e, If you call a function with the same arguments 'n' number of times and 'n' number of places in the application then it will always return the same value. Let's take an example to see the difference between pure and impure functions,
```javascript
//Impure
let numberArray = [];
const impureAddNumber = number => numberArray.push (number);
//Pure
const pureAddNumber = number => argNumberArray =>
  argNumberArray.concat ([number]);

//Display the results
console.log (impureAddNumber (6)); // returns 6
console.log (numberArray); // returns [6]
console.log (pureAddNumber (7) (numberArray)); // returns [6, 7]
console.log (numberArray); // returns [6]
```
As per above code snippets, Push function is impure itself by altering the array and returning an push number index which is independent of parameter value. Whereas Concat on the other hand takes the array and concatenates it with the other array producing a whole new array without side effects. Also, the return value is a concatenation of previous array.
Remember that Pure functions are important as they simplify unit testing without any side effects and no need for dependency injection. They also avoid tight coupling and makes harder to break your application by not having any side effects. These principles are coming together with **Immutability** concept of ES6 by giving preference to **const** over **let** usage.

**[⬆ Back to Top](#table-of-contents)**

17. ### What is the purpose of let keyword?

The let statement declares a **block scope local variable**. Hence the variables defined with let keyword are limited in scope to the block, statement, or expression on which it is used. Whereas variables declared with the var keyword used to define a variable globally, or locally to an entire function regardless of block scope. Let's take an example to demonstrate the usage,
```javascript
let counter = 30;
if (counter === 30) {
  let counter = 31;
  console.log(counter); // 31
}
console.log(counter); // 30 (because if block variable won't exist here)
```

**[⬆ Back to Top](#table-of-contents)**

18. ### What is the difference between let and var?
You can list out the differences in a tabular format

| var | let |
|---- | ---------
| It is been available from the beginning of JavaScript  | Introduced as part of ES6 |
| It has function scope | It has block scope  |
| Variables will be hoisted | Hoisted but not initialized |

Let's take an example to see the difference,
```javascript
function userDetails(username) {
   if(username) {
     console.log(salary); // undefined(due to hoisting)
     console.log(age); // error: age is not defined
     let age = 30;
     var salary = 10000;
   }
   console.log(salary); //10000 (accessible to due function scope)
   console.log(age); //error: age is not defined(due to block scope)
}
```

**[⬆ Back to Top](#table-of-contents)**

19. ### What is the reason to choose the name let as keyword?
    Let is a mathematical statement that was adopted by early programming languages like Scheme and Basic. It has been borrowed from dozens of other languages that use let already as a traditional keyword as close to var as possible.

**[⬆ Back to Top](#table-of-contents)**

20. ### How do you redeclare variables in switch block without an error?
    If you try to redeclare variables in a `switch block` then it will cause errors because there is only one block. For example, the below code block throws a syntax error as below,
    ```javascript
    let counter = 1;
    switch(x) {
      case 0:
        let name;
        break;

      case 1:
        let name; // SyntaxError for redeclaration.
        break;
    }
    ```
    To avoid this error, you can create a nested block inside a case clause will create a new block scoped lexical environment.
    ```javascript
    let counter = 1;
        switch(x) {
          case 0: {
            let name;
            break;
          }
          case 1: {
            let name; // No SyntaxError for redeclaration.
            break;
          }
        }
    ```

    **[⬆ Back to Top](#table-of-contents)**

21. ### What is Temporal Dead Zone?
    The Temporal Dead Zone is a behavior in JavaScript that occurs when declaring a variable with the let and const keywords, but not with var. In ECMAScript 6, accessing a let or const variable before its declaration (within its scope) causes a ReferenceError. The time span when that happens, between the creation of a variable’s binding and its declaration, is called the temporal dead zone. Let's see this behavior with an example,
    ```javascript
    function somemethod() {
      console.log(counter1); // undefined
      console.log(counter2); // ReferenceError
      var counter1 = 1;
      let counter2 = 2;
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

22. ### What is IIFE(Immediately Invoked Function Expression)?
    IIFE (Immediately Invoked Function Expression) is a JavaScript function that runs as soon as it is defined. The signature of it would be as below,
    ```javascript
    (function ()
        {
          // logic here
        }
     )
    ();
    ```
    The primary reason to use an IIFE is to obtain data privacy because any variables declared within the IIFE cannot be accessed by the outside world. i.e, If you try to access variables with IIFE then it throws an error as below,
    ```javascript
    (function ()
            {
              var message = "IIFE";
              console.log(message);
            }
     )
    ();
    console.log(message); //Error: message is not defined
    ```

    **[⬆ Back to Top](#table-of-contents)**

23. ### What is the benefit of using modules?
    There are a lot of benefits to using modules in favour of a sprawling. Some of the benefits are,
    1. Maintainablity
    2. Reusability
    3. Namespacing

    **[⬆ Back to Top](#table-of-contents)**

24. ### What is memoization?
    Memoization is a programming technique which attempts to increase a function’s performance by caching its previously computed results.  Each time a memoized function is called, its parameters are used to index the cache. If the data is present, then it can be returned, without executing the entire function. Otherwise the function is executed and then the result is added to the cache.
    Let's take an example of adding function with memoization,
    ```javascript
    const memoizAddition = () => {
      let cache = {};
     return (value) => {
      if (value in cache) {
       console.log('Fetching from cache');
       return cache[value]; // Here, cache.value cannot be used as property name starts with the number which is not valid JavaScript  identifier. Hence, can only be accessed using the square bracket notation.
      }
      else {
       console.log('Calculating result');
       let result = value + 20;
       cache[value] = result;
       return result;
      }
     }
    }
    // returned function from memoizAddition
    const addition = memoizAddition();
    console.log(addition(20)); //output: 40 calculated
    console.log(addition(20)); //output: 40 cached
    ```

    **[⬆ Back to Top](#table-of-contents)**

25. ### What is Hoisting?
    Hoisting is a JavaScript mechanism where variables and function declarations are moved to the top of their scope before code execution. Remember that JavaScript only hoists declarations, not initialisation.
    Let's take a simple example of variable hoisting,
    ```javascript
    console.log(message); //output : undefined
    var message = ’The variable Has been hoisted’;
    ```
    The above code looks like as below to the interpreter,
    ```javascript
    var message;
    console.log(message);
    message = ’The variable Has been hoisted’;
    ```

    **[⬆ Back to Top](#table-of-contents)**

26. ### What are classes in ES6?
    In ES6, Javascript classes are primarily syntactical sugar over JavaScript’s existing prototype-based inheritance.
    For example, the prototype based inheritance written in function expression as below,
    ```javascript
    function Bike(model,color) {
        this.model = model;
        this.color = color;
    }

    Bike.prototype.getDetails = function() {
        return this.model + ' bike has' + this.color + ' color';
    };
    ```
    Whereas ES6 classes can be defined as an alternative
    ```javascript
    class Bike{
      constructor(color, model) {
        this.color= color;
        this.model= model;
      }

      getDetails() {
        return this.model + ' bike has' + this.color + ' color';
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

27. ### What are closures?
    A closure is the combination of a function and the lexical environment within which that function was declared. i.e, It is an inner function that has access to the outer or enclosing function’s variables. The closure has three scope chains
    1. Own scope where variables defined between its curly brackets
    2. Outer function’s variables
    3. Global variables
    Let's take an example of closure concept,
    ```javascript
    function Welcome(name){
      var greetingInfo = function(message){
       console.log(message+' '+name);
      }
    return greetingInfo;
    }
    var myFunction = Welcome('John');
    myFunction('Welcome '); //Output: Welcome John
    myFunction('Hello Mr.'); //output: Hello Mr.John
    ```
    As per the above code, the inner function(greetingInfo) has access to the variables in the outer function scope(Welcome) even after outer function has returned.

    **[⬆ Back to Top](#table-of-contents)**

28. ### What are modules?
    Modules refers small units of independent, reusable code and also act as foundation of many JavaScript design patterns.  Most of the JavaScript modules export an object literal, a function, or a constructor

    **[⬆ Back to Top](#table-of-contents)**

29. ### Why do you need modules?
    Below are the list of benefits using modules in javascript ecosystem
    1. Maintainablity
    2. Reusability
    3. Namespacing

    **[⬆ Back to Top](#table-of-contents)**

30. ### What is scope in javascript?
    Scope is the accessibility of variables, functions, and objects in some particular part of your code during runtime. In other words, scope determines the visibility of variables and other resources in areas of your code.

    **[⬆ Back to Top](#table-of-contents)**

31. ### What is a service worker?
    A Service worker is basically a script (JavaScript file) that runs in background, separate from a web page and provide features that don't need a web page or user interaction. Some of the major features of service workers are Rich offline experiences(offline first web application development), periodic background syncs, push notifications, intercept and handle network requests and programmatically managing a cache of responses.

    **[⬆ Back to Top](#table-of-contents)**

32. ### How do you manipulate DOM using service worker?
    Service worker can't access the DOM directly. But it can communicate with the pages it controls by responding to messages sent via the `postMessage` interface, and those pages can manipulate the DOM.

    **[⬆ Back to Top](#table-of-contents)**

33. ### How do you reuse information across service worker restarts?
    The problem with service worker is that it get terminated when not in use, and restarted when it's next needed, so you cannot rely on global state within a service worker's `onfetch` and `onmessage` handlers. In this case, service workers will have access to IndexedDB API in order to persist and reuse across restarts.

    **[⬆ Back to Top](#table-of-contents)**

34. ### What is IndexedDB?
    IndexedDB is a low-level API for client-side storage of larger amounts of structured data, including files/blobs. This API uses indexes to enable high-performance searches of this data.

    **[⬆ Back to Top](#table-of-contents)**

35. ### What is web storage?
    Web storage is an API that provides a mechanism by which browsers can store key/value pairs locally within the user's browser, in a much more intuitive fashion than using cookies. The web storage provides two mechanisms for storing data on the client.
    1. **Local storage:** It stores data for current origin with no expiration date.
    2. **Session storage:** It stores data for one session and the data is lost when the browser tab is closed.

    **[⬆ Back to Top](#table-of-contents)**

36. ### What is a post message?
    Post message is a method that enables cross-origin communication between Window objects.(i.e, between a page and a pop-up that it spawned, or between a page and an iframe embedded within it). Generally, scripts on different pages are allowed to access each other if and only if the pages follow same-origin policy(i.e, pages share the same protocol, port number, and host).

    **[⬆ Back to Top](#table-of-contents)**

37. ### What is a Cookie?
    A cookie is a piece of data that is stored on your computer to be accessed by your browser. Cookies are saved as key/value pairs.
    For example, you can create a cookie named username as below,
    ```javascript
    document.cookie = "username=John";
    ```

    **[⬆ Back to Top](#table-of-contents)**

38. ### Why do you need a Cookie?
    Cookies are used to remember information about the user profile(such as username). It basically involves two steps,
    1. When a user visits a web page, user profile can be stored in a cookie.
    2. Next time the user visits the page, the cookie remembers user profile.

    **[⬆ Back to Top](#table-of-contents)**

39. ### What are the options in a cookie?
    There are few below options available for a cookie,
    1. By default, the cookie is deleted when the browser is closed but you can change this behavior by setting expiry date (in UTC time).
    ```javascript
    document.cookie = "username=John expires=Sat, 8 Jun 2019 12:00:00 UTC";
    ```
    2. By default, the cookie belongs to a current page. But you can tell the browser what path the cookie belongs to using a path parameter.
    ```javascript
    document.cookie = "username=John path=/services";
    ```

    **[⬆ Back to Top](#table-of-contents)**

40. ### How do you delete a cookie?
    You can delete a cookie by setting the expiry date as a passed date. You don't need to specify a cookie value in this case.
    For example, you can delete a username cookie in the current page as below.
    ```javascript
    document.cookie = "username=; expires=Fri, 07 Jun 2019 00:00:00 UTC; path=/;";
    ```
    **Note:** You should define the cookie path option to ensure that you delete the right cookie. Some browsers doesn't allow to delete a cookie unless you specify a path parameter.

    **[⬆ Back to Top](#table-of-contents)**

41. ### What are the differences between cookie, local storage and session storage?
    Below are some of the differences between cookie, local storage and session storage,

    | Feature | Cookie | Local storage | Session storage |
    |---- | --------- | ----- | ----- |
    | Accessed on client or server side | Both server-side & client-side | client-side only | client-side only |
    | Lifetime | As configured using Expires option  | until deleted | until tab is closed |
    | SSL support | Supported | Not supported | Not supported |
    | Maximum data size | 4KB | 5 MB | 5MB |

    **[⬆ Back to Top](#table-of-contents)**

42. ### What is the main difference between localStorage and sessionStorage?
    LocalStorage is same as SessionStorage but it persists the data even when the browser is closed and reopened(i.e it has no expiration time) whereas in sessionStorage data gets cleared when the page session ends.

    **[⬆ Back to Top](#table-of-contents)**

43. ### How do you access web storage?
    The Window object implements the `WindowLocalStorage` and `WindowSessionStorage` objects which has `localStorage`(window.localStorage) and `sessionStorage`(window.sessionStorage) properties respectively. These properties create an instance of the Storage object, through which data items can be set, retrieved and removed for a specific domain and storage type (session or local).
    For example, you can read and write on local storage objects as below
    ```javascript
    localStorage.setItem('logo', document.getElementById('logo').value);
    localStorage.getItem('logo');
    ```

    **[⬆ Back to Top](#table-of-contents)**

44. ### What are the methods available on session storage?
    The session storage provided methods for reading, writing and clearing the session data
    ```javascript
    // Save data to sessionStorage
    sessionStorage.setItem('key', 'value');

    // Get saved data from sessionStorage
    let data = sessionStorage.getItem('key');

    // Remove saved data from sessionStorage
    sessionStorage.removeItem('key');

    // Remove all saved data from sessionStorage
    sessionStorage.clear();
    ```

    **[⬆ Back to Top](#table-of-contents)**

45. ### What is a storage event and its event handler?
    The StorageEvent is an event that fires when a storage area has been changed in the context of another document. Whereas onstorage property is an EventHandler for processing storage events.
    The syntax would be as below
    ```javascript
     window.onstorage = functionRef;
    ```
    Let's take the example usage of onstorage event handler which logs the storage key and it's values
    ```javascript
    window.onstorage = function(e) {
      console.log('The ' + e.key +
        ' key has been changed from ' + e.oldValue +
        ' to ' + e.newValue + '.');
    };
    ```

    **[⬆ Back to Top](#table-of-contents)**

46. ### Why do you need web storage?
    Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance. Also, the information is never transferred to the server. Hence this is recommended approach than Cookies.

    **[⬆ Back to Top](#table-of-contents)**

47. ### How do you check web storage browser support?
    You need to check browser support for localStorage and sessionStorage before using web storage,
    ```javascript
    if (typeof(Storage) !== "undefined") {
      // Code for localStorage/sessionStorage.
    } else {
      // Sorry! No Web Storage support..
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

48. ### How do you check web workers browser support?
    You need to check browser support for web workers before using it
    ```javascript
    if (typeof(Worker) !== "undefined") {
      // code for Web worker support.
    } else {
      // Sorry! No Web Worker support..
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

49. ### Give an example of web worker?
    You need to follow below steps to start using web workers for counting example
    1. Create a Web Worker File:  You need to write a script to increment the count value. Let's name it as counter.js
    ```javascript
    let i = 0;

    function timedCount() {
      i = i + 1;
      postMessage(i);
      setTimeout("timedCount()",500);
    }

    timedCount();
    ```
    Here postMessage() method is used to post a message back to the HTML page
    2. Create a Web Worker Object: You can create a web worker object by checking for browser support. Let's name this file as web_worker_example.js
    ```javascript
    if (typeof(w) == "undefined") {
      w = new Worker("counter.js");
    }
    ```
    and we can receive messages from web worker
    ```javascript
    w.onmessage = function(event){
      document.getElementById("message").innerHTML = event.data;
    };
    ```
    3. Terminate a Web Worker:
    Web workers will continue to listen for messages (even after the external script is finished) until it is terminated. You can use terminate() method to terminate listening the messages.
    ```javascript
    w.terminate();
    ```
    4. Reuse the Web Worker: If you set the worker variable to undefined you can reuse the code
    ```javascript
    w = undefined;
    ```

    **[⬆ Back to Top](#table-of-contents)**

50. ### What are the restrictions of web workers on DOM?
    WebWorkers don't have access to below javascript objects since they are defined in an external files
    1. Window object
    2. Document object
    3. Parent object

    **[⬆ Back to Top](#table-of-contents)**

51. ### What is a promise?
    A promise is an object that may produce a single value some time in the future with either a resolved value or a reason that it’s not resolved(for example, network error). It will be in one of the 3 possible states: fulfilled, rejected, or pending.
    The syntax of promise would be as below
    ```javascript
    const promise = new Promise(function(resolve, reject) {
      // promise description
    })
    ```

    **[⬆ Back to Top](#table-of-contents)**

52. ### Why do you need a promise?
    Promises are used to handle asynchronous operations. They provide an alternative approach for callbacks by reducing the callback hell and writing the cleaner code.

    **[⬆ Back to Top](#table-of-contents)**

53. ### What are the three states of promise?
    Promises have three states:
    1. **Pending:** This is an initial state of the Promise before an operation begins
    2. **Fulfilled:** This state indicates that specified operation was completed.
    3. **Rejected:** This state indicates that the operation did not complete. In this case an error value will be thrown.

    **[⬆ Back to Top](#table-of-contents)**

54. ### What is a callback function?
    A callback function is a function passed into another function as an argument. This function is invoked inside the outer function to complete an action.
    Let's take a simple example of how to use callback function
    ```javascript
    function callbackFunction(name) {
      console.log('Hello ' + name);
    }

    function outerFunction(callback) {
      let name = prompt('Please enter your name.');
      callback(name);
    }

    outerFunction(callbackFunction);
    ```
    **[⬆ Back to Top](#table-of-contents)**

55. ### Why do we need callbacks?
    The callbacks are needed because javascript is a event driven language. That means instead of waiting for a response javascript will keep executing while listening for other events.
    Let's take an example with first function invoking an API call(simulated by setTimeout) and next function which logs the message.
    ```javascript
    function firstFunction(){
      // Simulate a code delay
      setTimeout( function(){
        console.log('First function called');
      }, 1000 );
    }
    function secondFunction(){
      console.log('Second function called');
    }
    firstFunction();
    secondFunction();

    Output
    // Second function called
    // First function called
    ```
    As observed from the output, javascript didn't wait for the response of first function and remaining code block get executed. So callbacks used in a way to make sure that certain code doesn’t execute until other code finished execution.

    **[⬆ Back to Top](#table-of-contents)**

56. ### What is a callback hell?
    Callback Hell is an anti-pattern with multiple nested callbacks which makes code hard to read and debug when dealing with asynchronous logic. The callback hell looks like below,
    ```javascript
    async1(function(){
        async2(function(){
            async3(function(){
                async4(function(){
                    ....
                });
            });
        });
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

57. ### What is server-sent events?
    Server-sent events (SSE) is a server push technology enabling a browser to receive automatic updates from a server via HTTP connection without resorting to polling. These are a one way communications channel - events flow from server to client only. This is been used in Facebook/Twitter updates, stock price updates, news feeds etc.

    **[⬆ Back to Top](#table-of-contents)**

58. ### How do you receive server-sent event notifications?
    The EventSource object is used to receive server-sent event notifications. For example, you can receive messages from server as below,
    ```javascript
    if(typeof(EventSource) !== "undefined") {
      var source = new EventSource("sse_generator.js");
      source.onmessage = function(event) {
        document.getElementById("output").innerHTML += event.data + "<br>";
      };
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

59. ### How do you check browser support for server-sent events?
    You can perform browser support for server-sent events before using it as below,
    ```javascript
    if(typeof(EventSource) !== "undefined") {
      // Server-sent events supported. Let's have some code here!
    } else {
      // No server-sent events supported
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

60. ### What are the events available for server sent events?
    Below are the list of events available for server sent events
    | Event | Description |
    |---- | ---------
    | onopen  | It is used when a connection to the server is opened |
    | onmessage | This event is used when a message is received  |
    | onerror | It happens when an error occurs|

    **[⬆ Back to Top](#table-of-contents)**

61. ### What are the main rules of promise?
    A promise must follow a specific set of rules,
    1. A promise is an object that supplies a standard-compliant `.then()` method
    2. A pending promise may transition into either fulfilled or rejected state
    3. A fulfilled or rejected promise is settled and it must not transition into any other state.
    4. Once a promise is settled, the value must not change.

    **[⬆ Back to Top](#table-of-contents)**

62. ### What is callback in callback?
    You can nest one callback inside in another callback to execute the actions sequentially one by one. This is known as callbacks in callbacks.
    ```javascript
    loadScript('/script1.js', function(script) {
       console.log('first script is loaded');

      loadScript('/script2.js', function(script) {

        console.log('second script is loaded');

        loadScript('/script3.js', function(script) {

            console.log('third script is loaded');
          // after all scripts are loaded
        });

      })

    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

63. ### What is promise chaining?
    The process of executing a sequence of asynchronous tasks one after another using promises is known as Promise chaining. Let's take an example of promise chaining for calculating the final result,
    ```javascript
    new Promise(function(resolve, reject) {

      setTimeout(() => resolve(1), 1000);

    }).then(function(result) {

      console.log(result); // 1
      return result * 2;

    }).then(function(result) {

      console.log(result); // 2
      return result * 3;

    }).then(function(result) {

      console.log(result); // 6
      return result * 4;

    });
    ```
    In the above handlers, the result is passed to the chain of .then() handlers with the below work flow,
    1. The initial promise resolves in 1 second,
    2. After that `.then` handler is called by logging the result(1) and then return a promise with the value of result * 2.
    3. After that the value passed to the next `.then` handler by logging the result(2) and return a promise with result * 3.
    4. Finally the value passed to the last `.then` handler by logging the result(6) and return a promise with result * 4.

    **[⬆ Back to Top](#table-of-contents)**

64. ### What is promise.all?
    Promise.all is a promise that takes an array of promises as an input (an iterable), and it gets resolved when all the promises get resolved or any one of them gets rejected. For example, the syntax of promise.all method is below,
    ```javascript
    Promise.all([Promise1, Promise2, Promise3]) .then(result) => {   console.log(result) }) .catch(error => console.log(`Error in promises ${error}`))
    ```
    **Note:** Remember that the order of the promises(output the result) is maintained as per input order.

    **[⬆ Back to Top](#table-of-contents)**

65. ### What is the purpose of race method in promise?
    Promise.race() method will return the promise instance which is firstly resolved or rejected. Let's take an example of race() method where promise2 is resolved first
    ```javascript
    var promise1 = new Promise(function(resolve, reject) {
        setTimeout(resolve, 500, 'one');
    });
    var promise2 = new Promise(function(resolve, reject) {
        setTimeout(resolve, 100, 'two');
    });

    Promise.race([promise1, promise2]).then(function(value) {
      console.log(value); // "two" // Both promises will resolve, but promise2 is faster
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

66. ### What is a strict mode in javascript?
    Strict Mode is a new feature in ECMAScript 5 that allows you to place a program, or a function, in a “strict” operating context. This way it prevents certain actions from being taken and throws more exceptions. The literal expression `“use strict”;` instructs the browser to use the javascript code in the Strict mode.

    **[⬆ Back to Top](#table-of-contents)**

67. ### Why do you need strict mode?
    Strict mode is useful to write "secure" JavaScript by notifying "bad syntax" into real errors. For example, it eliminates accidentally creating a global variable by throwing an error and also throws an error for assignment to a non-writable property, a getter-only property, a non-existing property, a non-existing variable, or a non-existing object.

    **[⬆ Back to Top](#table-of-contents)**

68. ### How do you declare strict mode?
    The strict mode is declared by adding "use strict"; to the beginning of a script or a function.
    If declare at the beginning of a script, it has global scope.
    ```javascript
    "use strict";
    x = 3.14; // This will cause an error because x is not declared
    ```
    and if you declare inside a function, it has local scope
    ```javascript
    x = 3.14;       // This will not cause an error.
    myFunction();

    function myFunction() {
      "use strict";
      y = 3.14;   // This will cause an error
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

69. ### What is the purpose of double exclamation?
    The double exclamation or negation(!!) ensures the resulting type is a boolean. If it was falsey (e.g. 0, null, undefined, etc.), it will be false, otherwise, true.
    For example, you can test IE version using this expression as below,
    ```javascript
    let isIE8 = false;
    isIE8 = !! navigator.userAgent.match(/MSIE 8.0/);
    console.log(isIE8); // returns true or false
    ```
    If you don't use this expression then it returns the original value.
    ```javascript
    console.log(navigator.userAgent.match(/MSIE 8.0/));  // returns either an Array or null
    ```
    **Note:** The expression !! is not an operator, but it is just twice of ! operator.

    **[⬆ Back to Top](#table-of-contents)**

70. ### What is the purpose of delete operator?
    The delete keyword is used to delete the property as well as its value.
    ```javascript
    var user= {name: "John", age:20};
    delete user.age;

    console.log(user); // {name: "John"}
    ```

    **[⬆ Back to Top](#table-of-contents)**

71. ### What is typeof operator?
    You can use the JavaScript typeof operator to find the type of a JavaScript variable. It returns the type of a variable or an expression.
    ```javascript
    typeof "John Abraham"     // Returns "string"
    typeof (1 + 2)        // Returns "number"
    ```

    **[⬆ Back to Top](#table-of-contents)**

72. ### What is undefined property?
    The undefined property indicates that a variable has not been assigned a value, or not declared at all. The type of undefined value is undefined too.
    ```javascript
    var user;    // Value is undefined, type is undefined
    console.log(typeof(user)) //undefined
    ```
    Any variable can be emptied by setting the value to undefined.
    ```javascript
    user = undefined
    ```

    **[⬆ Back to Top](#table-of-contents)**

73. ### What is null value?
    The value null represents the intentional absence of any object value. It is one of JavaScript's primitive values. The type of null value is object.
    You can empty the variable by setting the value to null.
    ```javascript
    var user = null;
    console.log(typeof(user)) //object
    ```

    **[⬆ Back to Top](#table-of-contents)**

74. ### What is the difference between null and undefined?
    Below are the main differences between null and undefined,

    | Null | Undefined |
    |---- | -----------|
    | It is an assignment value which indicates that variable points to no object.  | It is not an assignment value where a variable has been declared but has not yet been assigned a value. |
    | Type of null is object | Type of undefined is undefined  |
    | The null value is a primitive value that represents the null, empty, or non-existent reference. | The undefined value is a primitive value used when a variable has not been assigned a value.|
    | Indicates the absence of a value for a variable | Indicates absence of variable itself |
    | Converted to zero (0) while performing primitive operations | Converted to NaN while performing primitive operations |

    **[⬆ Back to Top](#table-of-contents)**

75. ### What is eval?
    The eval() function evaluates JavaScript code represented as a string. The string can be a JavaScript expression, variable, statement, or sequence of statements.
    ```javascript
    console.log(eval('1 + 2')); //  3
    ```

    **[⬆ Back to Top](#table-of-contents)**

76. ### What is the difference between window and document?
    Below are the main differences between window and document,

    | Window | Document |
    |---- | ---------
    | It is the root level element in any web page  | It is the direct child of the window object. This is also known as Document Object Model(DOM) |
    | By default window object is available implicitly in the page | You can access it via window.document or document.  |
    | It has methods like alert(), confirm() and properties like document, location | It provides methods like getElementById, getElementByTagName, createElement etc  |

    **[⬆ Back to Top](#table-of-contents)**

77. ### How do you access history in javascript?
    The window.history object contains the browsers history. You can load previous and next URLs in the history using back() and next() methods.
    ```javascript
    function goBack() {
      window.history.back()
    }
    function goForward() {
      window.history.forward()
    }
    ```
    **Note:** You can also access history without window prefix.

    **[⬆ Back to Top](#table-of-contents)**

78. ### What are the javascript data types?
    Below are the list of javascript data types available
    1. Number
    2. String
    3. Boolean
    4. Object
    5. Undefined

    **[⬆ Back to Top](#table-of-contents)**

79. ### What is isNaN?
    The isNaN() function is used to determine whether a value is an illegal number (Not-a-Number) or not. i.e, This function returns true if the value equates to NaN. Otherwise it returns false.
    ```javascript
    isNaN('Hello') //true
    isNaN('100') //false
    ```

    **[⬆ Back to Top](#table-of-contents)**

80. ### What are the differences between undeclared and undefined variables?
    Below are the major differences between undeclared and undefined variables,

    | undeclared | undefined |
    |---- | ---------
    | These variables do not exist in a program and are not declared  | These variables declared in the program but have not assigned any value |
    | If you try to read the value of an undeclared variable, then a runtime error is encountered | If you try to read the value of an undefined variable, an undefined value is returned.  |

    **[⬆ Back to Top](#table-of-contents)**

81. ### What are global variables?
    Global variables are those that are available throughout the length of the code without any scope. The var keyword is used to declare a local variable but if you omit it then it will become global variable
    ```javascript
    msg = "Hello" // var is missing, it becomes global variable
    ```

    **[⬆ Back to Top](#table-of-contents)**

82. ### What are the problems with global variables?
    The problem with global variables is the conflict of variable names of local and global scope. It is also difficult to debug and test the code that relies on global variables.

    **[⬆ Back to Top](#table-of-contents)**

83. ### What is NaN property?
    The NaN property is a global property that represents "Not-a-Number" value. i.e, It indicates that a value is not a legal number. It is very rare to use NaN in a program but it can be used as return value for few cases
    ```javascript
    Math.sqrt(-1)
    parseInt("Hello")
    ```

    **[⬆ Back to Top](#table-of-contents)**

84. ### What is the purpose of isFinite function?
    The isFinite() function is used to determine whether a number is a finite, legal number. It returns false if the value is +infinity, -infinity, or NaN (Not-a-Number), otherwise it returns true.
    ```javascript
    isFinite(Infinity);  // false
    isFinite(NaN);       // false
    isFinite(-Infinity); // false

    isFinite(100);         // true
    ```

    **[⬆ Back to Top](#table-of-contents)**

85. ### What is an event flow?
    Event flow is the order in which event is received on the web page. When you click an element that is nested in various other elements, before your click actually reaches its destination, or target element, it must trigger the click event each of its parent elements first, starting at the top with the global window object.
    There are two ways of event flow
    1. Top to Bottom(Event Capturing)
    2. Bottom to Top (Event Bubbling)

    **[⬆ Back to Top](#table-of-contents)**

86. ### What is event bubbling?
    Event bubbling is a type of event propagation where the event first triggers on the innermost target element, and then successively triggers on the ancestors (parents) of the target element in the same nesting hierarchy till it reaches the outermost DOM element.

    **[⬆ Back to Top](#table-of-contents)**

87. ### What is event capturing?
    Event capturing is a type of event propagation where the event is first captured by the outermost element, and then successively triggers on the descendants (children) of the target element in the same nesting hierarchy till it reaches the innermost DOM element.

    **[⬆ Back to Top](#table-of-contents)**

88. ### How do you submit a form using JavaScript?
    You can submit a form using JavaScript use document.form[0].submit(). All the form input's information is submitted using onsubmit event handler
    ```javascript
    function submit() {
        document.form[0].submit();
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

89. ### How do you find operating system details?
    The window.navigator object contains information about the visitor's browser os details. Some of the OS properties are avaialble under platform property,
    ```javascript
    console.log(navigator.platform);
    ```

    **[⬆ Back to Top](#table-of-contents)**

90. ### What is the difference between document load and DOMContentLoaded events?
    The `DOMContentLoaded` event is fired when the initial HTML document has been completely loaded and parsed, without waiting for assets(stylesheets, images, and subframes) to finish loading. Whereas The load event is fired when the whole page has loaded, including all dependent resources(stylesheets, images).

    **[⬆ Back to Top](#table-of-contents)**

91. ### What is the difference between native, host and user objects?
    `Native objects` are objects that are part of the JavaScript language defined by the ECMAScript specification. For example, String, Math, RegExp, Object, Function etc core objects defined in the ECMAScript spec.
    `Host objects` are objects provided by the browser or runtime environment (Node). For example, window, XmlHttpRequest, DOM nodes etc considered as host objects.
    `User objects` are objects defined in the javascript code. For example, User object created for profile information.

    **[⬆ Back to Top](#table-of-contents)**

92. ### What are the tools or techniques used for debugging JavaScript code?
    You can use below tools or techniques for debugging javascript
    1. Chrome Devtools
    2. debugger statement
    3. Good old console.log statement

    **[⬆ Back to Top](#table-of-contents)**

93. ### What are the pros and cons of promises over callbacks?
    Below are the list of pros and cons of promises over callbacks,
    **Pros:**
    1. It avoids callback hell which is unreadable
    2. Easy to write sequential asynchronous code with .then()
    3. Easy to write parallel asynchronous code with Promise.all()
    4. Solves some of the common problems of callbacks(call the callback too late, too early, many times and swallow errors/exceptions)

    **Cons:**
    1. It makes little complex code
    2. You need to load a polyfill if ES6 is not supported

    **[⬆ Back to Top](#table-of-contents)**

94. ### What is the difference between an attribute and a property?
    Attributes are defined on the HTML markup whereas properties are defined on the DOM. For example, the below HTML element has 2 attributes type and value,
    ```javascript
    <input type="text" value="Name:">
    ```
    You can retrieve the attribute value as below,
    ```javascript
    const input = document.querySelector('input');
    console.log(input.getAttribute('value')); // Good morning
    console.log(input.value); // Good morning
    ```
    And after you change the value of the text field to "Good evening", it becomes like
    ```javascript
    console.log(input.getAttribute('value')); // Good morning
    console.log(input.value); // Good evening
    ```

    **[⬆ Back to Top](#table-of-contents)**

95. ### What is same-origin policy?
    The same-origin policy is a policy that prevents JavaScript from making requests across domain boundaries. An origin is defined as a combination of URI scheme, hostname, and port number. If you enable this policy then it prevents a malicious script on one page from obtaining access to sensitive data on another web page using Document Object Model(DOM).

    **[⬆ Back to Top](#table-of-contents)**

96. ### What is the purpose of void 0?
    Void(0) is used to prevent the page from refreshing. This will be helpful to eliminate the unwanted side-effect, because it will return the undefined primitive value. It is commonly used for HTML document that uses href="JavaScript:Void(0);" within an <a> element. i.e, when you click a link, the browser loads a new page or refreshes the same page. But this behavior will be prevented using this expression.
    For example, the below link notify the message without reloading the page
    ```javascript
    <a href="JavaScript:void(0);" onclick="alert('Well done!')">Click Me!</a>
    ```

    **[⬆ Back to Top](#table-of-contents)**

97. ### Is JavaScript a compiled or interpreted language?
    JavaScript is an interpreted language, not a compiled language. An interpreter in the browser reads over the JavaScript code, interprets each line, and runs it. Nowadays  modern browsers use a technology known as Just-In-Time (JIT) compilation, which compiles JavaScript to executable bytecode just as it is about to run.

    **[⬆ Back to Top](#table-of-contents)**

98. ### Is JavaScript a case-sensitive language?
    Yes, JavaScript is a case sensitive language. The language keywords, variables, function & object names, and any other identifiers must always be typed with a consistent capitalization of letters.

    **[⬆ Back to Top](#table-of-contents)**

99. ### Is there any relation between Java and JavaScript?
    No, they are entirely two different programming languages and has nothing to do with each other. But both of them are Object Oriented Programming languages and like many other languages, they follow similar syntax for basic features(if, else, for, switch, break, continue etc).

    **[⬆ Back to Top](#table-of-contents)**

100. ### What are events?
     Events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can `react` on these events. Some of the examples of HTML events are,

     1. Web page has finished loading
     2. Input field was changed
     3. Button was clicked

     Let's describe the behavior of click event for button element,

     ```javascript
     <!doctype html>
     <html>
      <head>
        <script>
          function greeting() {
            alert('Hello! Good morning');
          }
        </script>
      </head>
      <body>
        <button type="button" onclick="greeting()">Click me</button>
      </body>
     </html>
     ```

     **[⬆ Back to Top](#table-of-contents)**

101. ### Who created javascript?
     JavaScript was created by Brendan Eich in 1995 during his time at Netscape Communications. Initially it was developed under the name `Mocha`, but later the language was officially called `LiveScript` when it first shipped in beta releases of Netscape.

     **[⬆ Back to Top](#table-of-contents)**

102. ### What is the use of preventDefault method?
     The preventDefault() method cancels the event if it is cancelable, meaning that the default action or behaviour that belongs to the event will not occur. For example, prevent form submission when clicking on submit button and prevent opening the page URL when clicking on hyper link are some common usecases.
     ```javascript
     document.getElementById("link").addEventListener("click", function(event){
      event.preventDefault();
     });
     ```
     **Note:** Remember that not all events are cancelable.

     **[⬆ Back to Top](#table-of-contents)**

103. ### What is the use of stopPropagation method?
     The stopPropagation method is used to stop the event from bubbling up the event chain. For example, the below nested divs with stopPropagation method prevents default event propagation when clicking on nested div(Div1)
     ```javascript
     <p>Click DIV1 Element</p>
     <div onclick="secondFunc()">DIV 2
       <div onclick="firstFunc(event)">DIV 1</div>
     </div>

     <script>
     function firstFunc(event) {
       alert("DIV 1");
       event.stopPropagation();
     }

     function secondFunc() {
       alert("DIV 2");
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

104. ### What are the steps involved in return false usage?
     The return false statement in event handlers performs the below steps,
     1. First it stops the browser's default action or behaviour.
     2. It prevents the event from propagating the DOM
     3. Stops callback execution and returns immediately when called.

     **[⬆ Back to Top](#table-of-contents)**

105. ### What is BOM?
     The Browser Object Model (BOM) allows JavaScript to "talk to" the browser. It consists of the objects navigator, history, screen, location and document which are children of window. The Browser Object Model is not standardized and can change based on different browsers.

     **[⬆ Back to Top](#table-of-contents)**

106. ### What is the use of setTimeout?
     The setTimeout() method is used to call a function or evaluates an expression after a specified number of milliseconds. For example, let's log a message after 2 seconds using setTimeout method,
     ```javascript
     setTimeout(function(){ console.log("Good morning"); }, 2000);
     ```

     **[⬆ Back to Top](#table-of-contents)**

107. ### What is the use of setInterval?
     The setInterval() method is used to call a function or evaluates an expression at specified intervals (in milliseconds). For example, let's log a message after 2 seconds using setInterval method,
     ```javascript
     setInterval(function(){ console.log("Good morning"); }, 2000);
     ```

     **[⬆ Back to Top](#table-of-contents)**

108. ### Why is JavaScript treated as Single threaded?
     JavaScript is a single-threaded language. Because the language specification does not allow the programmer to write code so that the interpreter can run parts of it in parallel in multiple threads or processes. Whereas languages like java, go, C++ can make multi-threaded and multi-process programs.

     **[⬆ Back to Top](#table-of-contents)**

109. ### What is an event delegation?
     Event delegation is a technique for listening to events where you delegate a parent element as the listener for all of the events that happen inside it.
     For example, if you wanted to detect field changes in inside a specific form, you can use event delegation technique,
     ```javascript
     var form = document.querySelector('#registration-form');

     // Listen for changes to fields inside the form
     form.addEventListener('input', function (event) {

     	// Log the field that was changed
     	console.log(event.target);

     }, false);
     ```

     **[⬆ Back to Top](#table-of-contents)**

110. ### What is ECMAScript?
     ECMAScript is the scripting language that forms the basis of JavaScript. ECMAScript standardized by the ECMA International standards organization in the ECMA-262 and ECMA-402 specifications. The first edition of ECMAScript was released in 1997.

     **[⬆ Back to Top](#table-of-contents)**

111. ### What is JSON?
     JSON (JavaScript Object Notation) is a lightweight format that is used for data interchanging. It is based on a subset of JavaScript language in the way objects are built in JavaScript.

     **[⬆ Back to Top](#table-of-contents)**

112. ### What are the syntax rules of JSON?
     Below are the list of syntax rules of JSON
     1. The data is in name/value pairs
     2. The data is separated by commas
     3. Curly braces hold objects
     4. Square brackets hold arrays

     **[⬆ Back to Top](#table-of-contents)**

113. ### What is the purpose JSON stringify?
     When sending data to a web server, the data has to be in a string format. You can achieve this by converting JSON object into a string using stringify() method.
     ```javascript
     var userJSON = {'name': 'John', age: 31}
     var userString = JSON.stringify(user);
     console.log(userString); //"{"name":"John","age":31}"
     ```

     **[⬆ Back to Top](#table-of-contents)**

114. ### How do you parse JSON string?
     When receiving the data from a web server, the data is always in a string format. But you can convert this string value to javascript object using parse() method.
     ```javascript
     var userString = '{"name":"John","age":31}';
     var userJSON = JSON.parse(userString);
     console.log(userJSON);// {name: "John", age: 31}
     ```

     **[⬆ Back to Top](#table-of-contents)**

115. ### Why do you need JSON?
     When exchanging data between a browser and a server, the data can only be text. Since JSON is text only, it can easily be sent to and from a server, and used as a data format by any programming language.

     **[⬆ Back to Top](#table-of-contents)**

116. ### What are PWAs?
     Progressive web applications (PWAs) are a type of mobile app delivered through the web, built using common web technologies including HTML, CSS and JavaScript. These PWAs are deployed to servers, accessible through URLs, and indexed by search engines.

     **[⬆ Back to Top](#table-of-contents)**

117. ### What is the purpose of clearTimeout method?
     The clearTimeout() function is used in javascript to clear the timeout which has been set by setTimeout()function before that. i.e, The return value of setTimeout() function is stored in a variable and it’s passed into the clearTimeout() function to clear the timer.
     For example, the below setTimeout method is used to display the message after 3 seconds. This timeout can be cleared by clearTimeout() method.
     ```javascript
     <script>
     var msg;
     function greeting() {
        alert('Good morning');
     }
     function start() {
       msg =setTimeout(greeting, 3000);

     }

     function stop() {
         clearTimeout(msg);
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

118. ### What is the purpose of clearInterval method?
     The clearInterval() function is used in javascript to clear the interval which has been set by setInterval() function. i.e, The return value returned by setInterval() function is stored in a variable and it’s passed into the clearInterval() function to clear the interval.
     For example, the below setInterval method is used to display the message for every 3 seconds. This interval can be cleared by clearInterval() method.
     ```javascript
     <script>
     var msg;
     function greeting() {
        alert('Good morning');
     }
     function start() {
       msg = setInterval(greeting, 3000);

     }

     function stop() {
         clearInterval(msg);
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

119. ### How do you redirect new page in javascript?
     In vanilla javascript, you can redirect to a new page using `location` property of window object. The syntax would be as follows,
     ```javascript
     function redirect() {
        window.location.href = 'newPage.html';
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

120. ### How do you check whether a string contains a substring?
     There are 3 possible ways to check whether a string contains a substring or not,
     1. **Using includes:** ES6 provided `String.prototype.includes` method to test a string contains a substring
     ```javascript
     var mainString = "hello", subString = "hell";
     mainString.includes(subString)
     ```
     2. **Using indexOf:** In an ES5 or older environments, you can use `String.prototype.indexOf` which returns the index of a substring. If the index value is not equal to -1 then it means the substring exist in the main string.
     ```javascript
     var mainString = "hello", subString = "hell";
     mainString.indexOf(subString) !== -1
     ```
     3. **Using RegEx:** The advanced solution is using Regular expression's test method(`RegExp.test`), which allows for testing for against regular expressions
     ```javascript
     var mainString = "hello", regex = "/hell/";
     regex.test(mainString)
     ```

     **[⬆ Back to Top](#table-of-contents)**

121. ### How do you validate an email in javascript?
     You can validate an email in javascript using regular expressions. It is recommended to do validations on the server side instead client side. Because the javascript can be disabled on the client side.
     ```javascript
     function validateEmail(email) {
         var re = /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
         return re.test(String(email).toLowerCase());
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

     The above regular expression regular accepts unicode characters.
122. ### How do you get the current url with javascript?
     You can use `window.location.href` expression to get the current url path and you can use the same expression for updating the URL too. You can also use `document.URL` for read-only purpose but this solution has issues in FF.
     ```javascript
     console.log('location.href', window.location.href); // Returns full URL
     ```

     **[⬆ Back to Top](#table-of-contents)**

123. ### What are the various url properties of location object?
     The below `Location` object properties can be used to access URL components of the page,
     1. href - The entire URL
     2. protocol - The protocol of the URL
     3. host - The hostname and port of the URL
     4. hostname - The hostname of the URL
     5. port - The port number in the URL
     6. pathname - The path name of the URL
     7. search - The query portion of the URL
     8. hash - The anchor portion of the URL

     **[⬆ Back to Top](#table-of-contents)**

124. ### How do get query string values in javascript?
     You can use URLSearchParams to get query string values in javascript. Let's see an example to get the client code value from URL query string,
     ```javascript
     const urlParams = new URLSearchParams(window.location.search);
     const clientCode = urlParams.get('clientCode');
     ```

     **[⬆ Back to Top](#table-of-contents)**

125. ### How do you check if a key exists in an object?
     You can check whether a key exists in an object or not using two approaches,
     1. ** Using in operator:** You can use the in operator whether a key exists in an object or not
     ```javascript
     "key" in obj
     ```
     and If you want to check if a key doesn't exist, remember to use parenthesis,
     ```javascript
     !("key" in obj)
     ```
     2. ** Using hasOwnProperty method:** You can use `hasOwnProperty` to particularly test for properties of the object instance (and not inherited properties)
     ```javascript
     obj.hasOwnProperty("key") // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

126. ### How do you loop through or enumerate javascript object?
     You can use the `for-in` loop to loop through javascript object. You can also make sure that the key you get is an actual property of an object, and doesn't come from the prototype using `hasOwnProperty` method.
     ```javascript
     var object = {
         "k1": "value1",
         "k2": "value2",
         "k3": "value3"
     };

     for (var key in object) {
         if (object.hasOwnProperty(key)) {
             console.log(key + " -> " + object[key]); // k1 -> value1 ...
         }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

127. ### How do you test for an empty object?
     There are different solutions based on ECMAScript versions
     1. **Using Object entries(ECMA 7+):** You can use object entries length along with constructor type.
     ```javascript
     Object.entries(obj).length === 0 && obj.constructor === Object // Since date object length is 0, you need to check constructor check as well
     ```
     2. **Using Object keys(ECMA 5+):** You can use object keys length along with constructor type.
     ```javascript
     Object.keys(obj).length === 0 && obj.constructor === Object // Since date object length is 0, you need to check constructor check as well
     ```
     3. **Using for-in with hasOwnProperty(Pre-ECMA 5):** You can use for-in loop along with hasOwnProperty.
     ```javascript
     function isEmpty(obj) {
       for(var prop in obj) {
         if(obj.hasOwnProperty(prop)) {
           return false;
         }
       }

       return JSON.stringify(obj) === JSON.stringify({});
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

128. ### What is an arguments object?
     The arguments object is an Array-like object accessible inside functions that contains the values of the arguments passed to that function. For example, let's see how to use arguments object inside sum function,
     ```javascript
     function sum() {
         var total = 0;
         for (var i = 0, len = arguments.length; i < len; ++i) {
             total += arguments[i];
         }
         return total;
     }

     sum(1, 2, 3) // returns 6
     ```

     **[⬆ Back to Top](#table-of-contents)**

129. ### How do you make first letter of the string in an uppercase?
     You can create a function which uses chain of string methods such as charAt, toUpperCase and slice methods to generate a string with first letter in uppercase.
     ```javascript
     function capitalizeFirstLetter(string) {
         return string.charAt(0).toUpperCase() + string.slice(1);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

130. ### What are the pros and cons of for loop?
     The for-loop is a commonly used iteration syntax in javascript. It has both pros and cons
     **Pros**
     1. Works on every environment
     2. You can use break and continue flow control statements
     **Cons**
     1. Too verbose
     2. Imperative
     3. You might face one-by-off errors

     **[⬆ Back to Top](#table-of-contents)**

131. ### How do you display the current date in javascript?
     You can use `new Date()` to generate a new Date object containing the current date and time. For example, let's display the current date in mm/dd/yyyy
     ```javascript
     var today = new Date();
     var dd = String(today.getDate()).padStart(2, '0');
     var mm = String(today.getMonth() + 1).padStart(2, '0'); //January is 0!
     var yyyy = today.getFullYear();

     today = mm + '/' + dd + '/' + yyyy;
     document.write(today);
     ```

     **[⬆ Back to Top](#table-of-contents)**

132. ### How do you compare two date objects?
     You need to use use date.getTime() method to compare date values instead comparision operators (==, !=, ===, and !== operators)
     ```javascript
     var d1 = new Date();
     var d2 = new Date(d1);
     console.log(d1.getTime() === d2.getTime()); //True
     console.log(d1 === d2); // False
     ```

     **[⬆ Back to Top](#table-of-contents)**

133. ### How do you check if a string starts with another string?
     You can use ECMAScript 6's `String.prototype.startsWith()` method to check a string starts with another string or not. But it is not yet supported in all browsers. Let's see an example to see this usage,
     ```javascript
     "Good morning".startsWith("Good"); // true
     "Good morning".startsWith("morning"); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

134. ### How do you trim a string in javascript?
     JavaScript provided a trim method on string types to trim any whitespaces present at the begining or ending of the string.
     ```javascript
     "  Hello World   ".trim(); //Hello World
     ```
     If your browser(<IE9) doesn't support this method then you can use below polyfill.
     ```javascript
     if (!String.prototype.trim) {
         (function() {
             // Make sure we trim BOM and NBSP
             var rtrim = /^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g;
             String.prototype.trim = function() {
                 return this.replace(rtrim, '');
             };
         })();
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

135. ### How do you add a key value pair in javascript?
     There are two possible solutions to add new properties to an object. Let's take a simple object to explain these solutions.
     ```javascript
     var object = {
         key1: value1,
         key2: value2
     };
     ```
     1. **Using dot notation:** This solution is useful when you know the name of the property
     ```javascript
     object.key3 = "value3";
     ```
     2. **Using square bracket notation:** This solution is useful when the name of the property is dynamically determined.
     ```javascript
     obj["key3"] = "value3";
     ```

     **[⬆ Back to Top](#table-of-contents)**

136. ### Is the !-- notation represents a special operator?
     No,that's not a special operator. But it is a combination of 2 standard operators one after the other,
     1. A logical not (!)
     2. A prefix decrement (--)

     At first, the value decremented by one and then tested to see if it is equal to zero or not for determining the truthy/falsy value.

     **[⬆ Back to Top](#table-of-contents)**

137. ### How do you assign default values to variables?
     You can use the logical or operator `||` in an assignment expression to provide a default value. The syntax looks like as below,
     ```javascript
     var a = b || c;
     ```
     As per the above expression, variable 'a 'will get the value of 'c' only if 'b' is falsy (if is null, false, undefined, 0, empty string, or NaN), otherwise 'a' will get the value of 'b'.

     **[⬆ Back to Top](#table-of-contents)**

138. ### How do you define multiline strings?
     You can define multiline string literals using '\' character followed by line terminator.
     ```javascript
     var str = "This is a \
     very lengthy \
     sentence!";
     ```
     But if you have a space after the '\' character, the code will look exactly the same, but it will raise a SyntaxError.

     **[⬆ Back to Top](#table-of-contents)**

139. ### What is an app shell model?
     An application shell (or app shell) architecture is one way to build a Progressive Web App that reliably and instantly loads on your users' screens, similar to what you see in native applications. It is useful for getting some initial HTML to the screen fast without a network.

     **[⬆ Back to Top](#table-of-contents)**

140. ### Can we define properties for functions?
     Yes, We can define properties for functions because functions are also objects.
     ```javascript
     fn = function(x) {
        //Function code goes here
     }

     fn.name = "John";

     fn.profile = function(y) {
       //Profile code goes here
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

141. ### What is the way to find the number of parameters expected by a function?
     You can use `function.length` syntax to find the number of parameters expected by a function. Let's take an example of `sum` function to calculate the sum of numbers,
     ```javascript
     function sum(num1, num2, num3, num4){
         return num1 + num2 + num3 + num4;
     }
     sum.length // 4 is the number of parameters expected.
     ```

     **[⬆ Back to Top](#table-of-contents)**

142. ### What is a polyfill?
     A polyfill is a piece of JS code used to provide modern functionality on older browsers that do not natively support it. For example, Silverlight plugin polyfill can be used to mimic the functionality of an HTML Canvas element on Microsoft Internet Explorer 7.

     **[⬆ Back to Top](#table-of-contents)**

143. ### What are break and continue statements?
     The break statement is used to "jumps out" of a loop. i.e, It breaks the loop and continues executing the code after the loop.
     ```javascript
     for (i = 0; i < 10; i++) {
       if (i === 5) { break; }
       text += "Number: " + i + "<br>";
     }
     ```
     The continue statement is used to "jumps over" one iteration in the loop. i.e, It breaks one iteration (in the loop), if a specified condition occurs, and continues with the next iteration in the loop.
     ```javascript
     for (i = 0; i < 10; i++) {
         if (i === 5) { continue; }
         text += "Number: " + i + "<br>";
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

144. ### What are js labels?
     The label statement allows us to name loops and blocks in JavaScript. We can then use these labels to refer back to the code later. For example, the below code with labels avoids printing the numbers when they are same,
     ```javascript
     var i, j;

     loop1:
     for (i = 0; i < 3; i++) {
        loop2:
        for (j = 0; j < 3; j++) {
           if (i === j) {
              continue loop1;
           }
           console.log('i = ' + i + ', j = ' + j);
        }
     }

     // Output is:
     //   "i = 1, j = 0"
     //   "i = 2, j = 0"
     //   "i = 2, j = 1"
     ```

     **[⬆ Back to Top](#table-of-contents)**

145. ### What are the benefits of keeping declarations at the top?
     It is recommended to keep all declarations at the top of each script or function. The benefits of doing this are,
     1. Gives cleaner code
     2. It provides a single place to look for local variables
     3. Easy to avoid unwanted global variables
     4. It reduces the possibility of unwanted re-declarations

     **[⬆ Back to Top](#table-of-contents)**

146. ### What are the benefits of initializing variables?
     It is recommended to initialize variables because of the below benefits,
     1. It gives cleaner code
     2. It provides a single place to initialize variables
     3. Avoid undefined values in the code

     **[⬆ Back to Top](#table-of-contents)**

147. ### What are the recommendations to create new object?
     It is recommended to avoid creating new objects using `new Object()`. Instead you can initialize values based on it's type to create the objects.
     1. Assign {} instead of new Object()
     2. Assign "" instead of new String()
     3. Assign 0 instead of new Number()
     4. Assign false instead of new Boolean()
     5. Assign [] instead of new Array()
     6. Assign /()/ instead of new RegExp()
     7. Assign function (){} instead of new Function()

     You can define them as an example,

     ```javascript
     var v1 = {};
     var v2 = "";
     var v3 = 0;
     var v4 = false;
     var v5 = [];
     var v6 = /()/;
     var v7 = function(){};
     ```
     **[⬆ Back to Top](#table-of-contents)**

148. ### How do you define JSON arrays?
     JSON arrays are written inside square brackets and array contain javascript objects. For example, the JSON array of users would be as below,
     ```javascript
     "users":[
       {"firstName":"John", "lastName":"Abrahm"},
       {"firstName":"Anna", "lastName":"Smith"},
       {"firstName":"Shane", "lastName":"Warn"}
     ]
     ```

     **[⬆ Back to Top](#table-of-contents)**

149. ### How do you generate random integers?
     You can use Math.random() with Math.floor() to return random integers. For example, if you want generate random integers between 1 to 10, the multiplication factor should be 10,
     ```javascript
     Math.floor(Math.random() * 10) + 1;     // returns a random integer from 1 to 10
     Math.floor(Math.random() * 100) + 1;     // returns a random integer from 1 to 100
     ```
     **Note:** Math.random() returns a random number between 0 (inclusive),  and 1 (exclusive)

     **[⬆ Back to Top](#table-of-contents)**

150. ### Can you write a random integers function to print integers with in a range?
     Yes, you can create a proper random function to return a random number between min and max (both included)
     ```javascript
     function randomInteger(min, max) {
       return Math.floor(Math.random() * (max - min + 1) ) + min;
     }
     randomInteger(1, 100); // returns a random integer from 1 to 100
     randomInteger(1, 1000); // returns a random integer from 1 to 1000
     ```

     **[⬆ Back to Top](#table-of-contents)**

151. ### What is tree shaking?
     Tree shaking is a form of dead code elimination. It means that unused modules will not be included in the bundle during the build process and for that it relies on the static structure of ES2015 module syntax,( i.e. import and export). Initially this has been popularized by the ES2015 module bundler `rollup`.

     **[⬆ Back to Top](#table-of-contents)**

152. ### What is the need of tree shaking?
     Tree Shaking can significantly reduce the code size in any application. i.e, The less code we send over the wire the more performant the application will be. For example, if we just want to create a “Hello World” Application using SPA frameworks then it will take around  few MBs, but by tree shaking it can bring down the size to just few hundred KBs. Tree shaking is been implemented in Rollup and Webpack bundlers.

     **[⬆ Back to Top](#table-of-contents)**

153. ### Is it recommended to use eval?
     No, it allows arbitrary code to be run which casues a security problem. As we know that the eval() function is used to run text as code. In most of the cases, it should not be necessary to use it.

     **[⬆ Back to Top](#table-of-contents)**

154. ### What is a Regular Expression?
     A regular expression is a sequence of characters that forms a search pattern. You can use this search pattern for searching data in a text. These can be used to perform all types of text search and text replace operations. Let's see the syntax format now,
     ```javascript
     /pattern/modifiers;
     ```
     For example, the regular expression or search pattern with case-insensitive username would be,
     ```javascript
     /John/i
     ```

     **[⬆ Back to Top](#table-of-contents)**

155. ### What are the string methods available in Regular expression?
     Regular Expressions has two string methods: search() and replace().
     The search() method uses an expression to search for a match, and returns the position of the match.
     ```javascript
     var msg = "Hello John";
     var n = msg.search(/John/i); // 6
     ```
     The replace() method is used return a modified string where the pattern is replaced.
     ```javascript
     var msg = "Hello John";
     var n = msg.replace(/John/i, "Buttler"); // Hello Buttler
     ```

     **[⬆ Back to Top](#table-of-contents)**

156. ### What are modifiers in regular expression?
     Modifiers can be used to perform case-insensitive and global searches. Let's list down some of the modifiers,

     | Modifier | Description |
     |---- | ---------
     | i  | Perform case-insensitive matching |
     | g | 	Perform a global match rather than stops at first match  |
     | m | Perform multiline matching|

    Let's take an example of global modifier,
    ```javascript
      var text = "Learn JS one by one";
      var pattern = /one/g;
      var result = text.match(pattern); // one,one
    ```


   **[⬆ Back to Top](#table-of-contents)**

157. ### What are regular expression patterns?
     Regular Expressions provided group of patterns in order to match characters. Basically they are categorized into 3 types,
     1. **Brackets:** These are used to find a range of characters.
        For example, below are some use cases,
        1. [abc]: Used to find any of the characters between the brackets(a,b,c)
        2. [0-9]: Used to find any of the digits between the brackets
        3. (a|b): Used to find any of the alternatives separated with |
     2. **Metacharacters:** These are characters with a special meaning
        For example, below are some use cases,
        1. \d: Used to find a digit
        2. \s: Used to find a whitespace character
        3. \b: Used to find a match at the beginning or ending of a word
     3. **Quantifiers:** These are useful to define quantities
        For example, below are some use cases,
        1. n+: Used to find matches for any string that contains at least one n
        2. n*: Used to find matches for any string that contains zero or more occurrences of n
        3. n?: Used to find	matches for any string that contains zero or one occurrences of n

     **[⬆ Back to Top](#table-of-contents)**

158. ### What is a RegExp object?
     RegExp object is a regular expression object with predefined properties and methods. Let's see the simple usage of RegExp object,
     ```javascript
     var regexp = new RegExp('\\w+');
     console.log(regexp);
     // expected output: /\w+/
     ```

     **[⬆ Back to Top](#table-of-contents)**

159. ### How do you search a string for a pattern?
     You can use test() method of regular expression in order to search a string for a pattern, and returns true or false depending on the result.
     ```javascript
     var pattern = /you/;
     console.log(pattern.test("How are you?")); //true
     ```

     **[⬆ Back to Top](#table-of-contents)**

160. ### What is the purpose of exec method?
     The purpose of exec method is similar to test method but it returns a founded text as an object instead of returning true/false.
     ```javascript
     var pattern = /you/;
     console.log(pattern.test("How are you?")); //you
     ```

     **[⬆ Back to Top](#table-of-contents)**

161. ### How do you change style of a HTML element?
     You can change inline style or classname of a HTML element using javascript
     1. ** Using style property:** You can modify inline style using style property
     ```javascript
     document.getElementById("title").style.fontSize = "30px";
     ```
     2. ** Using ClassName property:** It is easy to modify element class using className property
     ```javascript
      document.getElementById("title").style.className = "custom-title";
      ```

     **[⬆ Back to Top](#table-of-contents)**

162. ### What would be the result of 1+2+'3'?
     The output is going to be `33`. Since `1` and `2` are numeric values, the result of first two digits is going to be a numeric value `3`. The next digit is a string type value because of that the addition of numeric value `3` and string type value `3` is just going to be a concatenation value `33`.

     **[⬆ Back to Top](#table-of-contents)**

163. ### What is a debugger statement?
     The debugger statement invokes any available debugging functionality, such as setting a breakpoint. If no debugging functionality is available, this statement has no effect.
     For example, in the below function a debugger statement has been inserted. So execution is paused at the debugger statement just like a breakpoint in the script source.
     ```javascript
     function getProfile() {
     // code goes here
     debugger;
     // code goes here
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

164. ### What is the purpose of breakpoints in debugging?
     You can set breakpoints in the javascript code once the debugger statement is executed and debugger window pops up. At each breakpoint, javascript will stop executing, and let you examine the JavaScript values. After examining values, you can resume the execution of code using play button.

     **[⬆ Back to Top](#table-of-contents)**

165. ### Can I use reserved words as identifiers?
     No, you cannot use the reserved words as variables, labels, object or function names. Let's see one simple example,
     ```javascript
     var else = "hello"; // Uncaught SyntaxError: Unexpected token else
     ```

     **[⬆ Back to Top](#table-of-contents)**

166. ### How do you detect a mobile browser?
     You can use regex which returns a true or false value depending on whether or not the user is browsing with a mobile.
     ```javascript
     window.mobilecheck = function() {
       var mobileCheck = false;
       (function(a){if(/(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows ce|xda|xiino/i.test(a)||/1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s\-)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|\-m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw\-(n|u)|c55\/|capi|ccwa|cdm\-|cell|chtm|cldc|cmd\-|co(mp|nd)|craw|da(it|ll|ng)|dbte|dc\-s|devi|dica|dmob|do(c|p)o|ds(12|\-d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(\-|_)|g1 u|g560|gene|gf\-5|g\-mo|go(\.w|od)|gr(ad|un)|haie|hcit|hd\-(m|p|t)|hei\-|hi(pt|ta)|hp( i|ip)|hs\-c|ht(c(\-| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i\-(20|go|ma)|i230|iac( |\-|\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc\-|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|\-[a-w])|libw|lynx|m1\-w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|m\-cr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(\-| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)\-|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|\-([1-8]|c))|phil|pire|pl(ay|uc)|pn\-2|po(ck|rt|se)|prox|psio|pt\-g|qa\-a|qc(07|12|21|32|60|\-[2-7]|i\-)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h\-|oo|p\-)|sdk\/|se(c(\-|0|1)|47|mc|nd|ri)|sgh\-|shar|sie(\-|m)|sk\-0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h\-|v\-|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl\-|tdg\-|tel(i|m)|tim\-|t\-mo|to(pl|sh)|ts(70|m\-|m3|m5)|tx\-9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|\-v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(\-| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas\-|your|zeto|zte\-/i.test(a.substr(0,4))) mobileCheck = true;})(navigator.userAgent||navigator.vendor||window.opera);
       return mobileCheck;
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

167. ### How do you detect a mobile browser without regexp?
     You can detect mobile browser by simply running through a list of devices and checking if the useragent matches anything. This is an alternative solution for RegExp usage,
     ```javascript
     function detectmob() {
      if( navigator.userAgent.match(/Android/i)
      || navigator.userAgent.match(/webOS/i)
      || navigator.userAgent.match(/iPhone/i)
      || navigator.userAgent.match(/iPad/i)
      || navigator.userAgent.match(/iPod/i)
      || navigator.userAgent.match(/BlackBerry/i)
      || navigator.userAgent.match(/Windows Phone/i)
      ){
         return true;
       }
      else {
         return false;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

168. ### How do you get the image width and height using JS?
     You can programmatically get the image and check the dimensions(width and height) using Javascript.
     ```javascript
     var img = new Image();
     img.onload = function() {
       console.log(this.width + 'x' + this.height);
     }
     img.src = 'http://www.google.com/intl/en_ALL/images/logo.gif';
     ```

     **[⬆ Back to Top](#table-of-contents)**

169. ### How do you make synchronous HTTP request?
     Browsers provide an XMLHttpRequest object which can be used to make synchronous HTTP requests from JavaScript
     ```javascript
     function httpGet(theUrl)
     {
         var xmlHttpReq = new XMLHttpRequest();
         xmlHttpReq.open( "GET", theUrl, false ); // false for synchronous request
         xmlHttpReq.send( null );
         return xmlHttpReq.responseText;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

170. ### How do you make asynchronous HTTP request?
     Browsers provide an XMLHttpRequest object which can be used to make asynchronous HTTP requests from JavaScript by passing 3rd parameter as true.
     ```javascript
     function httpGetAsync(theUrl, callback)
     {
         var xmlHttpReq = new XMLHttpRequest();
         xmlHttpReq.onreadystatechange = function() {
             if (xmlHttpReq.readyState == 4 && xmlHttpReq.status == 200)
                 callback(xmlHttpReq.responseText);
         }
         xmlHttp.open("GET", theUrl, true); // true for asynchronous
         xmlHttp.send(null);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

171. ### How do you convert date to another timezone in javascript?
     You can use toLocaleString() method to convert date in one timezone to another. For example, let's convert current date to British English timezone as below,
     ```javascript
     console.log(event.toLocaleString('en-GB', { timeZone: 'UTC' })); //29/06/2019, 09:56:00
     ```

     **[⬆ Back to Top](#table-of-contents)**

172. ### What are the properties used to get size of window?
     You can use innerWidth, innerHeight, clientWidth, clientHeight properties of windows, document element and document body objects to find the size of a window. Let's use them combination of these properties to calculate the size of a window or document,
     ```javascript
     var width = window.innerWidth
     || document.documentElement.clientWidth
     || document.body.clientWidth;

     var height = window.innerHeight
     || document.documentElement.clientHeight
     || document.body.clientHeight;
     ```

     **[⬆ Back to Top](#table-of-contents)**

173. ### What is a conditional operator in javascript?
     The conditional (ternary) operator is the only JavaScript operator that takes three operands which acts as a shortcut for if statement.
     ```javascript
     var isAuthenticated = false;
     console.log(isAuthenticated ? 'Hello, welcome' : 'Sorry, you are not authenticated'); //Sorry, you are not authenticated
     ```

     **[⬆ Back to Top](#table-of-contents)**

174. ### Can you apply chaining on conditional operator?
     Yes, you can apply chaining on conditional operator similar to if … else if … else if … else chain. The syntax is going to be as below,
     ```javascript
     function traceValue(someParam) {
         return condition1 ? value1
              : condition2 ? value2
              : condition3 ? value3
              : value4;
     }

     // The above conditional operator is equivalent to:

     function traceValue(someParam) {
         if (condition1) { return value1; }
         else if (condition2) { return value2; }
         else if (condition3) { return value3; }
         else { return value4; }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

175. ### What are the ways to execute javascript after page load?
     You can execute javascript after page load in many different ways,
     1. ** window.onload:**
     ```javascript
     window.onload = function ...
     ```
     2. **document.onload:**
     ```javascript
     document.onload = function ...
     ```
     3. ** body onload:**
     ```javascript
     <body onload="script();">
     ```

     **[⬆ Back to Top](#table-of-contents)**

176. ### What is the difference between proto and prototype?
     The `__proto__` object is the actual object that is used in the lookup chain to resolve methods, etc. Whereas `prototype` is the object that is used to build `__proto__` when you create an object with new
     ```javascript
     ( new Employee ).__proto__ === Employee.prototype;
     ( new Employee ).prototype === undefined;
     ```

     **[⬆ Back to Top](#table-of-contents)**

177. ### Give an example where do you really need semicolon?
     It is recommended to use semicolons after every statement in JavaScript. For example, in the below case it throws an error ".. is not a function" at runtime due to missing semicolon.
     ```javascript
     // define a function
     var fn = function () {
         //...
     } // semicolon missing at this line

     // then execute some code inside a closure
     (function () {
         //...
     })();
     ```
     and it will be interpreted as
     ```javascript
     var fn = function () {
         //...
     }(function () {
         //...
     })();
     ```
     In this case, we are passing second function as an argument to the first function and then trying to call the result of the first function call as a function. Hence, the second function will fail with a "... is not a function" error at runtime.

     **[⬆ Back to Top](#table-of-contents)**

178. ### What is a freeze method?
     The freeze() method is used to freeze an object. Freezing an object does'nt allow adding new properties to an object,prevents from removing and prevents changing the enumerability, configurability, or writability of existing properties. i.e, It returns the passed object and does not create a frozen copy.
     ```javascript
     const obj = {
       prop: 100
     };

     Object.freeze(obj);
     obj.prop = 200; // Throws an error in strict mode

     console.log(obj.prop); //100
     ```
     **Note:** It causes a TypeError if the argument passed is not an object.

     **[⬆ Back to Top](#table-of-contents)**

179. ### What is the purpose of freeze method?
     Below are the main benefits of using freeze method,
     1. It is used for freezing objects and arrays.
     2. It is used to make an object immutable.

     **[⬆ Back to Top](#table-of-contents)**

180. ### Why do I need to use freeze method?
     In Object-oriented paradigm, an existing API contains certain elements that are not intended to be extended, modified, or re-used outside of their current context. Hence it works as `final` keyword which is used in various languages.

     **[⬆ Back to Top](#table-of-contents)**

181. ### How do you detect a browser language preference?
     You can use navigator object to detect a browser language preference as below,
     ```javascript
     var language = navigator.languages && navigator.languages[0] || // Chrome / Firefox
                    navigator.language ||   // All browsers
                    navigator.userLanguage; // IE <= 10

     console.log(language);
     ```

     **[⬆ Back to Top](#table-of-contents)**

182. ### How to convert string to title case with javascript?
     Title case means that the first letter of each word is capitalized. You can convert a string to title case using the below function,
     ```javascript
         function toTitleCase(str) {
             return str.replace(
                 /\w\S*/g,
                 function(txt) {
                     return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
                 }
             );
         }
         toTitleCase("good morning john"); // Good Morning John
     ```

     **[⬆ Back to Top](#table-of-contents)**

183. ### How do you detect javascript disabled in the page?
     You can use `<noscript>` tag to detect javascript disabled or not. The code block inside `<noscript>` get executed when JavaScript is disabled, and are typically used to display alternative content when the page generated in JavaScript.
     ```javascript
     <script type="javascript">
         // JS related code goes here
     </script>
     <noscript>
         <a href="next_page.html?noJS=true">JavaScript is disabled in the apge. Please click Next Page</a>
     </noscript>
     ```

     **[⬆ Back to Top](#table-of-contents)**

184. ### What are various operators supported by javascript?
     An operator is capable of manipulating(mathematical and logical computations) a certain value or operand. There are various operators supported by JavaScript as below,
     1. **Arithmetic Operators:** Includes + (Addition),– (Subtraction), * (Multiplication), / (Division), % (Modulus), + + (Increment)  and – – (Decrement)
     2. **Comparison Operators:** Includes = =(Equal),!= (Not Equal), ===(Equal with type), > (Greater than),> = (Greater than or Equal to),< (Less than),<= (Less than or Equal to)
     3. **Logical Operators:** Includes &&(Logical AND),||(Logical OR),!(Logical NOT)
     4. **Assignment Operators:** Includes = (Assignment Operator), += (Add and Assignment Operator), – = (Subtract and Assignment Operator), *= (Multiply and Assignment), /= (Divide and Assignment), %= (Modules and Assignment)
     5. **Ternary Operators:** It includes conditional(: ?) Operator
     6. **typeof Operator:** It uses to find type of variable. The syntax looks like `typeof variable`

     **[⬆ Back to Top](#table-of-contents)**

185. ### What is a rest parameter?
     Rest parameter is an improved way to handle function parameter which allows us to represent an indefinite number of arguments as an array. The syntax would be as below,
     ```javascript
     function f(a, b, ...theArgs) {
       // ...
     }
     ```
     For example, let's take a sum example to calculate on dynamic number of parameters,
     ```javascript
     function total(…args){
     let sum = 0;
     for(let i of args){
     sum+=i;
     }
     return sum;
     }
     console.log(fun(1,2)); //3
     console.log(fun(1,2,3)); //6
     console.log(fun(1,2,3,4)); //13
     console.log(fun(1,2,3,4,5)); //15
     ```
     **Note:** Rest parameter is added in ES2015 or ES6

     **[⬆ Back to Top](#table-of-contents)**

186. ### What happens if you do not use rest parameter as a last argument?
     The rest parameter should be the last argument, as its job is to collect all the remaining arguments into an array. For example, if you define a function like below it doesn’t make any sense and will throw an error.
     ```javascript
     function someFunc(a,…b,c){
     //You code goes here
     return;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

187. ### What are the bitwise operators available in javascript?
     Below are the list of bit-wise logical operators used in JavaScript
     1. Bit-wise AND ( & )
     2. Bit-Wise OR ( | )
     3. Bit-Wise XOR ( ^ )
     4. Bit-Wise NOT ( ~ )
     5. Left Shift ( << )
     6. Sign Propagating Right Shift ( >> )
     7. Zero fill Right Shift ( >>> )

     **[⬆ Back to Top](#table-of-contents)**

188. ### What is a spread operator?
     Spread operator allows iterables( arrays / objects / strings ) to be expanded into single arguments/elements. Let's take an example to see this behavior,
     ```javascript
     function calculateSum(x, y, z) {
       return x + y + z;
     }

     const numbers = [1, 2, 3];

     console.log(calculateSum(...numbers)); // 6
     ```

     **[⬆ Back to Top](#table-of-contents)**

189. ### How do you determine whether object is frozen or not?
     Object.isFrozen() method is used to determine if an object is frozen or not.An object is frozen if all of the below conditions hold true,
     1. If it is not extensible.
     2. If all of its properties are non-configurable.
     3. If all its data properties are non-writable.
     The usage is going to be as follows,
     ```javascript
     const object = {
        property: 'Welcome JS world'
     };
     Object.freeze(object);
     console.log(Object.isFrozen(object));
     ```

     **[⬆ Back to Top](#table-of-contents)**

190. ### How do you determine two values same or not using object?
     The Object.is() method determines whether two values are the same value. For example, the usage with different types of values would be,
     ```javascript
     Object.is('hello', 'hello');     // true
     Object.is(window, window);   // true
     Object.is([], []) // false
     ```
     Two values are the same if one of the following holds:
     1. both undefined
     2. both null
     3. both true or both false
     4. both strings of the same length with the same characters in the same order
     5. both the same object (means both object have same reference)
     6. both numbers and
        both +0
        both -0
        both NaN
        both non-zero and both not NaN and both have the same value.

     **[⬆ Back to Top](#table-of-contents)**

191. ### What is the purpose of using object is method?
     Some of the applications of Object's `is` method are follows,
     1. It is used for comparison of two strings.
     2. It is used for comparison of two numbers.
     3. It is used for comparing the polarity of two numbers.
     4. It is used for comparison of two objects.

     **[⬆ Back to Top](#table-of-contents)**

192. ### How do you copy properties from one object to other?
     You can use Object.assign() method which is used to copy the values and properties from one or more source objects to a target object.  It returns the target object which has properties and values copied from the target object. The syntax would be as below,
     ```javascript
     Object.assign(target, ...sources)
     ```
     Let's take exampple with one source and one target object,
     ```javascript
     const target = { a: 1, b: 2 };
     const source = { b: 3, c: 4 };

     const returnedTarget = Object.assign(target, source);

     console.log(target); // { a: 1, b: 3, c: 4 }

     console.log(returnedTarget); // { a: 1, b: 3, c: 4 }
     ```
     As observed in the above code, there is a common property(`b`) from source to target so it's value is been overwritten.

     **[⬆ Back to Top](#table-of-contents)**

193. ### What are the applications of assign method?
     Below are the some of main applications of Object.assign() method,
     1. It is used for cloning an object.
     2. It is used to merge object with same properties.

     **[⬆ Back to Top](#table-of-contents)**

194. ### What is a proxy object?
     The Proxy object is used to define custom behavior for fundamental operations such as property lookup, assignment, enumeration, function invocation, etc. The syntax would be as follows,
     ```javascript
     var p = new Proxy(target, handler);
     ```
     Let's take an example of proxy object,
     ```javascript
     var handler = {
         get: function(obj, prop) {
             return prop in obj ?
                 obj[prop] :
                 100;
         }
     };

     var p = new Proxy({}, handler);
     p.a = 10;
     p.b = null;

     console.log(p.a, p.b); // 1, null
     console.log('c' in p, p.c); // false, 100
     ```
     In the above code, it uses `get` handler which define the behavior of the proxy when an operation is performed on it

     **[⬆ Back to Top](#table-of-contents)**

195. ### What is the purpose of seal method?
     The Object.seal() method is used seal an object, by preventing new properties from being added to it and marking all existing properties as non-configurable. But values of present properties can still be changed as long as they are writable. Let's see the below example to understand more about seal() method
     ```javascript
      const object = {
         property: 'Welcome JS world'
      };
      Object.seal(object);
      object.property = 'Welcome to object world';
      console.log(Object.isSealed(object)); // Welcome to object world
      delete object.property; // You cannot delete when sealed
      console.log(object.property); //Welcome to object world
     ```

     **[⬆ Back to Top](#table-of-contents)**

196. ### What are the applications of seal method?
     Below are the main applications of Object.seal() method,
     1. It is used for sealing objects and arrays.
     2. It is used to make an object immutable.

     **[⬆ Back to Top](#table-of-contents)**

197. ### What are the differences between freeze and seal methods?
     If an object is frozen using the Object.freeze() method then its properties become immutable and no changes can be made in them whereas if an object is sealed using the Object.seal() method then the changes can be made in the existing properties of the object.

     **[⬆ Back to Top](#table-of-contents)**

198. ### How do you determine if an object is sealed or not?
     The Object.isSealed() method is used to determine if an object is sealed or not. An object is sealed if all of the below conditions hold true
     1. If it is not extensible.
     2. If all of its properties are non-configurable.
     3. If it is not removable (but not necessarily non-writable).
     Let's see it in the action
     ```javascript
     const object = {
     property: 'Hello, Good morning'
     };

     Object.seal(object); // Using seal() method to seal the object

     console.log(Object.isSealed(object));      // checking whether the object is sealed or not
     ```

     **[⬆ Back to Top](#table-of-contents)**

199. ### How do you get enumerable key and value pairs?
     The Object.entries() method is used to return an array of a given object's own enumerable string-keyed property [key, value] pairs, in the same order as that provided by a for...in loop. Let's see the functionality of object.entries() method in an example,
     ```javascript
     const object = {
       a: 'Good morning',
       b: 100
     };

     for (let [key, value] of Object.entries(object)) {
       console.log(`${key}: ${value}`); // a: 'Good morning'
                                        // b: 100
     }
     ```
     **Note:** The order is not guaranteed as object defined.

     **[⬆ Back to Top](#table-of-contents)**

200. ### What is the main difference between Object.values and Object.entries method?
     The Object.values() method's behavior is similar to Object.entries() method but it returns an array of values instead [key,value] pairs.
     ```javascript
      const object = {
        a: 'Good morning',
        b: 100
      };

      for (let value of Object.values(object)) {
        console.log(`${value}`); // 'Good morning'
                                     100
      }
     ```

     **[⬆ Back to Top](#table-of-contents)**

201. ### How can you get the list of keys of any object?
     You can use `Object.keys()` method which is used return an array of a given object's own property names, in the same order as we get with a normal loop. For example, you can get the keys of a user object,
     ```javascript
     const user = {
       name: 'John',
       gender: 'male',
       age: 40
     };

     console.log(Object.keys(user)); //['name', 'gender', 'age']
     ```

     **[⬆ Back to Top](#table-of-contents)**

202. ### How do you create an object with prototype?
     The Object.create() method is used to create a new object with the specified prototype object and properties. i.e, It uses existing object as the prototype of the newly created object. It returns a new object with the specified prototype object and properties.
     ```javascript
      const user = {
        name: 'John',
        printInfo: function () {
          console.log(`My name is ${this.name}.`);
        }
      };

      const admin = Object.create(person);

      admin.name = "Nick"; // Remember that "name" is a property set on "admin" but not on "user" object

      admin.printInfo(); // My name is Nick
     ```

     **[⬆ Back to Top](#table-of-contents)**

203. ### What is a WeakSet?
     WeakSet is used to store a collection of weakly(weak references) held objects. The syntax would be as follows,
     ```javascript
     new WeakSet([iterable]);
     ```
     Let's see the below example to explain it's behavior,
     ```javascript
     var ws = new WeakSet();
     var user = {};
     ws.add(user);
     ws.has(user);    // true
     ws.delete(user); // removes user from the set
     ws.has(user);    // false, user has been removed
     ```

     **[⬆ Back to Top](#table-of-contents)**

204. ### What are the differences between WeakSet and Set?
     The main difference is that references to objects in Set are strong while references to objects in WeakSet are weak. i.e, An object in WeakSet can be garbage collected if there is no other reference to it.
     Other differences are,
     1. Sets can store any value Whereas WeakSets can store only collections of objects
     2. WeakSet does not have size property unlike Set
     3. WeakSet does not have methods such as clear, keys, values, entries, forEach.
     4. WeakSet is not iterable.

     **[⬆ Back to Top](#table-of-contents)**

205. ### List down the collection of methods available on WeakSet?
     Below are the list of methods available on WeakSet,
     1. add(value): A new object is appended with the given value to the weakset
     2. delete(value): Deletes the value from the WeakSet collection.
     3. has(value): It returns true if the value is present in the WeakSet Collection, otherwise it returns false.
     4. length(): It returns the length of weakSetObject
     Let's see the functionality of all the above methods in an example,
     ```javascript
     var weakSetObject = new WeakSet();
     var firstObject = {};
     var secondObject = {};
     // add(value)
     weakSetObject.add(firstObject);
     weakSetObject.add(secondObject);
     console.log(weakSetObject.has(firstObject)); //true
     console.log(weakSetObject.length()); //2
     weakSetObject.delete(secondObject);
     ```

     **[⬆ Back to Top](#table-of-contents)**

206. ### What is a WeakMap?
     The WeakMap object is a collection of key/value pairs in which the keys are weakly referenced. In this case, keys must be objects and the values can be arbitrary values. The syntax is looking like as below,
     ```javascript
     new WeakMap([iterable])
     ```
     Let's see the below example to explain it's behavior,
     ```javascript
      var ws = new WeakMap();
      var user = {};
      ws.set(user);
      ws.has(user);    // true
      ws.delete(user); // removes user from the map
      ws.has(user);    // false, user has been removed
     ```

     **[⬆ Back to Top](#table-of-contents)**

207. ### What are the differences between WeakMap and Map?
     The main difference is that references to key objects in Map are strong while references to key objects in WeakMap are weak. i.e, A key object in WeakMap can be garbage collected if there is no other reference to it.
     Other differences are,
     1. Maps can store any key type Whereas WeakMaps can store only collections of key objects
     2. WeakMap does not have size property unlike Map
     3. WeakMap does not have methods such as clear, keys, values, entries, forEach.
     4. WeakMap is not iterable.

     **[⬆ Back to Top](#table-of-contents)**

208. ### List down the collection of methods available on WeakMap?
     Below are the list of methods available on WeakMap,
     1. set(key, value): Sets the value for the key in the WeakMap object. Returns the WeakMap object.
     2. delete(key): Removes any value associated to the key.
     3. has(key): Returns a Boolean asserting whether a value has been associated to the key in the WeakMap object or not.
     4. get(key): Returns the value associated to the key, or undefined if there is none.
     Let's see the functionality of all the above methods in an example,
     ```javascript
     var weakMapObject = new WeakMap();
     var firstObject = {};
     var secondObject = {};
     // set(key, value)
     weakMapObject.set(firstObject, 'John');
     weakMapObject.set(secondObject, 100);
     console.log(weakMapObject.has(firstObject)); //true
     console.log(weakMapObject.get(firstObject)); // John
     weakMapObject.delete(secondObject);
     ```

     **[⬆ Back to Top](#table-of-contents)**

209. ### What is the purpose of uneval?
     The uneval() is an inbuilt function which is used to create a string representation of the source code of an Object. It is a top-level function and is not associated with any object. Let's see the below example to know more about it's functionality,
     ```javascript
     var a = 1;
     uneval(a); // returns a String containing 1
     uneval(function user() {}); // returns "(function user(){})"
     ```

     **[⬆ Back to Top](#table-of-contents)**

210. ### How do you encode an URL?
     The encodeURI() function is used to encode complete URI which has special characters except (, / ? : @ & = + $ #) characters.
     ```javascript
     var uri = 'https://mozilla.org/?x=шеллы';
     var encoded = encodeURI(uri);
     console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
     ```

     **[⬆ Back to Top](#table-of-contents)**

211. ### How do you decode an URL?
     The decodeURI() function is used to decode a Uniform Resource Identifier (URI) previously created by encodeURI().
     ```javascript
      var uri = 'https://mozilla.org/?x=шеллы';
      var encoded = encodeURI(uri);
      console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
     try {
       console.log(decodeURI(encoded)); // "https://mozilla.org/?x=шеллы"
     } catch(e) { // catches a malformed URI
       console.error(e);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

212. ### How do you print the contents of web page?
     The window object provided print() method which is used to prints the contents of the current window. It opens Print dialog box which lets you choose between various printing options. Let's see the usage of print method in an example,
     ```html
        <input type="button" value="Print" onclick="window.print()" />
     ```
     **Note:** In most browsers, it will block while the print dialog is open.

     **[⬆ Back to Top](#table-of-contents)**

213. ### What is the difference between uneval and eval?
     The `uneval` function returns the source of a given object; whereas the `eval` function does the opposite, by evaluating that source code in a different memory area. Let's see an example to clarify the difference,
     ```javascript
     var msg = uneval(function greeting() { return 'Hello, Good morning'; });
     var greeting = eval(msg);
     greeting(); // returns "Hello, Good morning"
     ```

     **[⬆ Back to Top](#table-of-contents)**

214. ### What is an anonymous function?
     An anonymous function is a function without a name! Anonymous functions are commonly assigned to a variable name or used as a callback function. The syntax would be as below,
     ```javascript
     function (optionalParameters) {
       //do something
     }

     const myFunction = function(){ //Anonymous function assigned to a variable
       //do something
     };

     [1, 2, 3].map(function(element){ //Anonymous function used as a callback function
       //do something
     });
     ```
     Let's see the above anonymous function in an example,
     ```javascript
     var x = function (a, b) {return a * b};
     var z = x(5, 10);
     console.log(z); // 50
     ```

     **[⬆ Back to Top](#table-of-contents)**

215. ### What is the precedence order between local and global variables?
     A local variable takes precedence over a global variable with the same name. Let's see this behavior in an example.
     ```javascript
     var msg = "Good morning";
     function greeting() {
        msg = "Good Evening";
        console.log(msg);
     }
     greeting();
     ```

     **[⬆ Back to Top](#table-of-contents)**

216. ### What are javascript accessors?
     ECMAScript 5 introduced javascript object accessors or computed properties through getters and setters. Getters uses `get` keyword whereas Setters uses `set` keyword.
     ```javascript
     var user = {
       firstName: "John",
       lastName : "Abraham",
       language : "en",
       get lang() {
         return this.language;
       }
       set lang(lang) {
       this.language = lang;
       }
     };
     console.log(user.lang); // getter access lang as en
     user.lang = 'fr';
     console.log(user.lang); // setter used to set lang as fr
     ```

     **[⬆ Back to Top](#table-of-contents)**

217. ### How do you define property on Object constructor?
     The Object.defineProperty() static method is used to define a new property directly on an object, or modifies an existing property on an object, and returns the object. Let's see an example to know how to define property,
     ```javascript
     const newObject = {};

     Object.defineProperty(newObject, 'newProperty', {
       value: 100,
       writable: false
     });

     console.log(newObject.newProperty); // 100

     newObject.newProperty = 200; // It throws an error in strict mode due to writable setting

     ```

     **[⬆ Back to Top](#table-of-contents)**

218. ### What is the difference between get and defineProperty?
     Both has similar results until unless you use classes. If you use `get` the property will be defined on the prototype of the object whereas using `Object.defineProperty()` the property will be defined on the instance it is applied to.

     **[⬆ Back to Top](#table-of-contents)**

219. ### What are the advantages of Getters and Setters?
     Below are the list of benefits of Getters and Setters,
     1. They provide simpler syntax
     2. They are used for defining computed properties, or accessors in JS.
     3. Useful to provide equivalence relation between properties and methods
     4. They can provide better data quality
     5. Useful for doing things behind the scenes with the encapsulated logic.

     **[⬆ Back to Top](#table-of-contents)**

220. ### Can I add getters and setters using defineProperty method?
     Yes, You can use `Object.defineProperty()` method to add Getters and Setters. For example, the below counter object uses increment, decrement, add and substract properties,
     ```javascript
     var counterObj = {counter : 0};

     // Define getters
     Object.defineProperty(obj, "increment", {
       get : function () {this.counter++;}
     });
     Object.defineProperty(obj, "decrement", {
       get : function () {this.counter--;}
     });

     // Define setters
     Object.defineProperty(obj, "add", {
       set : function (value) {this.counter += value;}
     });
     Object.defineProperty(obj, "subtract", {
       set : function (value) {this.counter -= value;}
     });

     obj.add = 10;
     obj.subtract = 5;
     console.log(obj.increment); //6
     console.log(obj.decrement); //5
     ```

     **[⬆ Back to Top](#table-of-contents)**

221. ### What is the purpose of switch-case?
     The switch case statement in JavaScript is used for decision making purposes. In few cases, using the switch case statement is going to be more convenient than if-else statements. The syntax would be as below,
     ```javascript
     switch (expression)
     {
         case value1:
             statement1;
             break;
         case value2:
             statement2;
             break;
         .
         .
         case valueN:
             statementN;
             break;
         default:
             statementDefault;
     }
     ```
     The above multi-way branch statement provides an easy way to dispatch execution to different parts of code based on the value of the expression.

     **[⬆ Back to Top](#table-of-contents)**

222. ### What are the conventions to be followed for the usage of switch case?
     Below are the list of conventions should be taken care,
     1. The expression can be of type either number or string.
     2. Duplicate values are not allowed for the expression.
     3. The default statement is optional. If the expression passed to switch does not matches with any case value then the statement within default case will be executed.
     4. The break statement is used inside the switch to terminate a statement sequence.
     5. The break statement is optional. But if it omitted, the execution will continue on into the next case.

     **[⬆ Back to Top](#table-of-contents)**

223. ### What are primitive data types?
     A primitive data type is data that has a primitive value (which has no properties or methods). There are 5 types of primitive data types.
     1. string
     2. number
     3. boolean
     4. null
     5. undefined

     **[⬆ Back to Top](#table-of-contents)**

224. ### What are the different ways to access object properties?
     There are 3 possible ways for accessing the property of an object.
     1. **Dot notation:** It uses dot for accessing the properties
     ```javascript
     objectName.property
     ```
     2. **Square brackets notation:** It uses square brackets for property access
     ```javascript
     objectName["property"]
     ```
     3. **Expression notation:** It uses expression in the square brackets
     ```javascript
     objectName[expression]
     ```

     **[⬆ Back to Top](#table-of-contents)**

225. ### What are the function parameter rules?
     JavaScript functions follow below rules for parameters,
     1. The function definitions do not specify data types for parameters.
     2. Do not perform type checking on the passed arguments.
     3. Do not check the number of arguments received.
     i.e, The below function follows the above rules,
     ```javascript
     function functionName(parameter1, parameter2, parameter3) {
       console.log(parameter1); // 1
     }
     functionName(1);
     ```

     **[⬆ Back to Top](#table-of-contents)**

226. ### What is an error object?
     An error object is a built in error object that provides error information when an error occurs. It has two properties: name and message. For example, the below function logs error details,
     ```javascript
     try {
       greeting("Welcome");
     }
     catch(err) {
       console.log(err.name + "<br>" + err.message);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

227. ### When you get a syntax error?
     A SyntaxError is thrown if you try to evaluate code with a syntax error. For example, the below missing quote for the function parameter throws a syntax error
     ```javascript
     try {
       eval("greeting('welcome)");   // Missing ' will produce an error
     }
     catch(err) {
       console.log(err.name);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

228. ### What are the different error names from error object?
     There are 6 different types of error names returned from error object,
     | Error Name | Description |
     |---- | ---------
     | EvalError  | An error has occurred in the eval() function |
     | RangeError | An error has occurred with a number "out of range"  |
     | ReferenceError | An error due to an illegal reference|
     | SyntaxError | An error due to a syntax error|
     | TypeError | An error due to a type error |
     | URIError | An error due to encodeURI() |

     **[⬆ Back to Top](#table-of-contents)**

229. ### What are the various statements in error handling?
     Below are the list of statements used in an error handling,
     1. **try:** This statement is used to test a block of code for errors
     2. **catch:** This statement is used to handle the error
     3. **throw:** This statement is used to create custom errors.
     4. **finally:** This statement is used to execute code after try and catch regardless of the result.

     **[⬆ Back to Top](#table-of-contents)**

230. ### What are the two types of loops in javascript?
     1. **Entry Controlled loops:** In this kind of loop type, the test condition is tested before entering the loop body. For example, For Loop and While Loop comes under this category.
     2. **Exit Controlled Loops:** In this kind of loop typpe, the test condition is tested or evaluated at the end of loop body. i.e, the loop body will execute atleast once irrespective of test condition true or false. For example, do-while loop comes under this category.

     **[⬆ Back to Top](#table-of-contents)**

231. ### What is nodejs?
     Node.js is a server-side platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. It is an event-based, non-blocking, asynchronous I/O runtime that uses Google's V8 JavaScript engine and libuv library.

     **[⬆ Back to Top](#table-of-contents)**

232. ### What is an Intl object?
     The Intl object is the namespace for the ECMAScript Internationalization API, which provides language sensitive string comparison, number formatting, and date and time formatting. It provides an access to several constructors and language sensitive functions.

     **[⬆ Back to Top](#table-of-contents)**

233. ### How do you perform language specific date and time formatting?
     You can use `Intl.DateTimeFormat` object which is constructor for objects that enable language-sensitive date and time formatting. Let's see this behavior with an example,
     ```javascript
     var date = new Date(Date.UTC(2019, 07, 07, 3, 0, 0));
     console.log(new Intl.DateTimeFormat('en-GB').format(date)); // 07/08/2019
     console.log(new Intl.DateTimeFormat('en-AU').format(date)); // 07/08/2019
     ```

     **[⬆ Back to Top](#table-of-contents)**

234. ### What is an Iterator?
     An iterator is an object which defines a sequence and a return value upon its termination. It implements the Iterator protocol with a next() method which returns an object with two properties: value (the next value in the sequence) and done (which is true if the last value in the sequence has been consumed).

     **[⬆ Back to Top](#table-of-contents)**

235. ### What is an event loop?
     The Event Loop is a queue of callback functions. When an async function executes, the callback function is pushed into the queue. The JavaScript engine doesn't start processing the event loop until async function has finished executing the code.
     **Note:** It allows Node.js to perform non-blocking I/O operations eventhough JavaScript is single-threaded.

     **[⬆ Back to Top](#table-of-contents)**

236. ### What is call stack?

     **[⬆ Back to Top](#table-of-contents)**

237. ### What is an event queue?

     **[⬆ Back to Top](#table-of-contents)**

238. ### What is a decorator?
     A decorator is an expression that evaluates to a function and that takes the target, name, and decorator descriptor as arguments. Also, it optionally returns a decorator descriptor to install on the target object. Let's define admin decorator for user class at design time,
     ```javascript
     function admin(isAdmin) {
        return function(target) {
            target.isAdmin = isAdmin;
        }
     }

     @admin(true)
     class User() {
     }
     console.log(User.isAdmin); //true

      @admin(false)
      class User() {
      }
      console.log(User.isAdmin); //false
     ```

     **[⬆ Back to Top](#table-of-contents)**

239. ### What are the properties of Intl object?
     Below are the list of properties available on Intl object,
     1. **Collator:** These are the objects that enable language-sensitive string comparison.
     2. **DateTimeFormat:** These are the objects that enable language-sensitive date and time formatting.
     3. **ListFormat:** These are the objects that enable language-sensitive list formatting.
     4. **NumberFormat:** Objects that enable language-sensitive number formatting.
     5. **PluralRules:** Objects that enable plural-sensitive formatting and language-specific rules for plurals.
     6. **RelativeTimeFormat:** Objects that enable language-sensitive relative time formatting.

     **[⬆ Back to Top](#table-of-contents)**

240. ### What is an Unary operator?
     The unary(+) operator is used to convert a variable to a number.If the variable cannot be converted, it will still become a number but with the value NaN. Let's see this behavior in an action.
     ```javascrippt
     var x = "100";
     var y = + x;
     console.log(typeof x, typeof y); // string, number

     var a = "Hello";
     var b = + a;
     console.log(typeof a, typeof b, b); // string, number, NaN
     ```

     **[⬆ Back to Top](#table-of-contents)**

241. ### How do you sort elements in an array?
     The sort() method is used to sort the elements of an array in place and returns the sorted array. The example usage would be as below,
     ```javascript
     var months = ["Aug", "Sep", "Jan", "June"];
     months.sort();
     console.log(months); //  ["Aug", "Jan", "June", "Sep"]
     ```

     **[⬆ Back to Top](#table-of-contents)**

242. ### What is the purpose of compareFunction while sorting arrays?
     The compareFunction is used to define the sort order. If omitted, the array elements are converted to strings, then sorted according to each character's Unicode code point value. Let's take an example to see the usage of compareFunction,
     ```javascript
     let numbers = [1, 2, 5, 3, 4];
     numbers.sort((a, b) => b - a);
     console.log(numbers); // [5, 4, 3, 2, 1]
     ```

     **[⬆ Back to Top](#table-of-contents)**

243. ### How do you reversing an array?
     You can use reverse() method is used reverse the elements in an array. This method is useful to sort an array in descending order. Let's see the usage of reverse() method in an example,
     ```javascript
     let numbers = [1, 2, 5, 3, 4];
     numbers.sort((a, b) => b - a);
     numbers.reverse();
     console.log(numbers); // [1, 2, 3, 4 ,5]
     ```

     **[⬆ Back to Top](#table-of-contents)**

244. ### How do you find min and max value in an array?
     You can use `Math.min` and `Math.max` methods on array variable to find the minimum and maximum elements with in an array. Let's create two functions to find the min and max value with in an array,
     ```javascript
     var marks = [50, 20, 70, 60, 45, 30];
     function findMin(arr) {
       return Math.min.apply(null, arr);
     }
     function findMax(arr) {
       return Math.max.apply(null, arr);
     }

     console.log(findMin(marks));
     console.log(findMax(marks));
     ```

     **[⬆ Back to Top](#table-of-contents)**

245. ### How do you find min and max values without Math functions?
     You can write functions which loops through an array comparing each value with the lowest value or highest value to find the min and max values. Let's create those functions to find min an max values,
     ```javascript
      var marks = [50, 20, 70, 60, 45, 30];
      function findMin(arr) {
        var length = arr.length
        var min = Infinity;
        while (length--) {
          if (arr[length] < min) {
            min = arr[len];
          }
        }
        return min;
      }

      function findMax(arr) {
        var length = arr.length
        var max = -Infinity;
        while (len--) {
          if (arr[length] > max) {
            max = arr[length];
          }
        }
        return max;
      }

      console.log(findMin(marks));
      console.log(findMax(marks));
     ```

     **[⬆ Back to Top](#table-of-contents)**

246. ### What is an empty statement and purpose of it?
     The empty statement is a semicolon (;) indicating that no statement will be executed, even if JavaScript syntax requires one. Since there is no action with an empty statement you might think that it's usage is quite less, but the empty statement is occasionally useful when you want to create a loop that has an empty body. For example, you can initialize an array with zero values as below,
     ```javascript
     // Initialize an array a
     for(int i=0; i < a.length; a[i++] = 0) ;
     ```

     **[⬆ Back to Top](#table-of-contents)**

247. ### How do you get meta data of a module?
     You can use `import.meta` object which is a meta-property exposing context-specific meta data to a JavaScript module. It contains information about the current module, such as module's URL. In browser, you might get different meta data than NodeJS.
     ```javascript
     <script type="module" src="welcome-module.js"></script>
     console.log(import.meta); // { url: "file:///home/user/welcome-module.js" }
     ```

     **[⬆ Back to Top](#table-of-contents)**

248. ### What is a comma operator?
     The comma operator is used to evaluate each of its operands from left to right and returns the value of the last operand. This is totally different from comma usage within arrays, objects, and function arguments and parameters. For example, the usage for numeric expressions would be as below,
     ```javascript
     var x = 1;
     x = (x++, x);

     console.log(x); // 2
     ```

     **[⬆ Back to Top](#table-of-contents)**

249. ### What is the advantage of a comma operator?
     It is normally used to include multiple expressions in a location that requires a single expression. One of the common usage of this comma operator is to supply multiple parameters in a `for` loop. For example, the below for loop uses multiple expressions in a single location using comma operator,
     ```javascript
     for (var a = 0, b =10; a <= 10; a++, b--)
     ```
     You can also use the comma operator in a return statement where it process before returning.
     ```javascript
     function myFunction() {
        var a = 1;
        return (a += 10, a); // 11
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

250. ### What is typescript?
    TypeScript is a typed superset of JavaScript created by Microsoft that adds optional types, classes, async/await, and many other features, and compiles to plain JavaScript. Angular built entirely in TypeScript and used as a primary language.
    You can install it globally as
    ```
    npm install -g typescript
    ```
    Let's see a simple example of TypeScript usage,
    ```typescript
    function greeting(person: string) {
        return "Hello, " + person;
    }

    let user = "Sudheer";

    document.body.innerHTML = greeting(user);
    ```
    The greeting method allows only string type as argument.

   **[⬆ Back to Top](#table-of-contents)**

251. ### What are the differences between javascript and typescript?
     Below are the list of differences between javascript and typescript,

     | feature | typescript | javascript |
     |---- | --------- | ----
     | Language paradigm  | Object oriented programming language  | Scripting language |
     | Typing support | Supports static typing  | It has dynamic typing |
     | Modules | Supported | Not supported |
     | Interface | It has interfaces concept | Doesn't support interfaces |
     | Optional parameters | Functions support optional parameters | No support of optional parameters for functions |

     **[⬆ Back to Top](#table-of-contents)**

252. ### What are the advantages of typescript over javascript?
     Below are some of the advantages of typescript over javascript,
     1. TypeScript is able to find compile time errors at the development time only and it make sures less runtime errors. Whereas javascript is interpreted language.
     2. TypeScript is is strongly-typed or supports static typing which allows for checking type correctness at compile time. This is not available in javascript.
     3. TypeScript compiler can compile the .ts files into ES3,ES4 and ES5 unlike ES6 features of javascript which may not be supported in some browsers.

     **[⬆ Back to Top](#table-of-contents)**

253. ### What is an object initializer?
     An object initializer is an expression that describes the initialization of an Object. The syntax for this expression is represented as a comma-delimited list of zero or more pairs of property names and associated values of an object, enclosed in curly braces ({}). This is also known as literal notation. It is one of the ways to create an object.
     ```javascript
     var initObject = {a: 'John', b: 50, c: {}};

     console.log(initObject.a); // John
     ```

     **[⬆ Back to Top](#table-of-contents)**

254. ### What is a constructor method?
     The constructor method is a special method for creating and initializing an object created within a class. If you do not specify a constructor method, a default constructor is used. The example usage of constructor would be as below,
     ```javascript
     class Employee {
       constructor() {
         this.name = "John";
       }
     }

     var employeeObject = new Employee();

     console.log(employeeObject.name); // John
     ```

     **[⬆ Back to Top](#table-of-contents)**

255. ### What happens if you write constructor more than once in a class?
     The "constructor" in a class is a special method and it should be defined only once in a class. i.e, If you write a constructor method more than once in a class it will throw a `SyntaxError` error.
     ```javascript
      class Employee {
        constructor() {
          this.name = "John";
        }
        constructor() {   //  Uncaught SyntaxError: A class may only have one constructor
          this.age = 30;
        }
      }

      var employeeObject = new Employee();

      console.log(employeeObject.name);
     ```

     **[⬆ Back to Top](#table-of-contents)**

256. ### How do you call the constructor of a parent class?
     You can use `super` keyword to call the constructor of a parent class. Remember that `super()` must be called before using 'this' reference. Otherwise it will cause a reference error. Let's the usage of it,
     ```javascript
     class Square extends Rectangle {
       constructor(length) {
         super(length, length);
         this.name = 'Square';
       }

       get area() {
         return this.width * this.height;
       }

       set area(value) {
         this.area = value;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

257. ### How do you get the prototype of an object?
     You can use `Object.getPrototypeOf(obj)` method is used to return the prototype of the specified object. i.e. The value of the internal `prototype` property. If there are no inherited properties then `null` value is returned.
     ```javascript
     const newPrototype = {};
     const newObject = Object.create(newPrototype);

     console.log(Object.getPrototypeOf(newObject) === newPrototype); // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

258. ### What happens If I pass string type for getPrototype method?
     In ES5, it will throw a TypeError exception if the obj parameter isn't an object. Whereas in ES2015, the parameter will be coerced to an `Object`.
     ```javascript
     // ES5
     Object.getPrototypeOf('James'); // TypeError: "James" is not an object
     // ES2015
     Object.getPrototypeOf('James'); // String.prototype
     ```

     **[⬆ Back to Top](#table-of-contents)**

259. ### How do you set prototype of one object to another?
     You can use `Object.setPrototypeOf()` method that sets the prototype (i.e., the internal `Prototype` property) of a specified object to another object or null. For example, if you want to set prototype of a square object to rectangle object would be as follows,
     ```javascript
     Object.setPrototypeOf(Square.prototype, Rectangle.prototype);
     Object.setPrototypeOf({}, null);
     ```

     **[⬆ Back to Top](#table-of-contents)**

260. ### How do you check whether an object can be extendable or not?
     The `Object.isExtensible()` method is used to determine if an object is extensible or not. i.e, Whether it can have new properties added to it or not.
     ```javascript
     const newObject = {};
     console.log(Object.isExtensible(newObject)); //true
     ```
     **Note:** By default, all the objects are extendable. i.e, The new properties can added or modified.

     **[⬆ Back to Top](#table-of-contents)**

261. ### How do you prevent an object to extend?
     The `Object.preventExtensions()` method is used to prevent new properties from ever being added to an object. In other words, it prevents future extensions to the object. Let's see the usage of this property,
     ```javascript
     const newObject = {};
     Object.preventExtensions(newObject); // NOT extendable

     try {
       Object.defineProperty(newObject, 'newProperty', { // Adding new property
         value: 100
       });
     } catch (e) {
       console.log(e); // TypeError: Cannot define property newProperty, object is not extensible
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

262. ### What are the different ways to make an object non-extensible?
     You can mark an object non-extensible in 3 ways,
     1. Object.preventExtensions
     2. Object.seal
     3. Object.freeze

     ```javascript
     var newObject = {};

     Object.preventExtensions(newObject); // Prevent objects are non-extensible
     Object.isExtensible(newObject); // false

     var sealedObject = Object.seal({}); // Sealed objects are non-extensible
     Object.isExtensible(sealedObject); // false

     var frozenObject = Object.freeze({}); // Frozen objects are non-extensible
     Object.isExtensible(frozenObject); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

263. ### How do you define multiple properties on an object?
     The `Object.defineProperties()` method is used to define new or modifies existing properties directly on an object and returning the object. Let's define multiple properties on an empty object,
     ```javascript
     const newObject = {};

     Object.defineProperties(newObject, {
       newProperty1: {
         value: 'John',
         writable: true
       },
       newProperty2: {}
     });
     ```

     **[⬆ Back to Top](#table-of-contents)**

264. ### What is MEAN in javascript?
     The MEAN (MongoDB, Express, AngularJS, and Node.js) stack is the most popular open-source JavaScript software tech stack available for building dynamic web apps where you can write both the server-side and client-side halves of the web project entirely in JavaScript.

     **[⬆ Back to Top](#table-of-contents)**

265. ### What Is Obfuscation in javascript?
     Obfuscation is the deliberate act of creating obfuscated javascript code(i.e, source or machine code) that is difficult for humans to understand. It is something similar to encryption, but a machine can understand the code and execute it.
     Let's see the below function before Obfuscation,
     ```javascript
     function greeeting() {
        console.log('Hello, welcome to JS world');
     }
     ```
     And after the code Obfuscation, it would be appeared as below,
     ```javascript
     eval(function(p,a,c,k,e,d){e=function(c){return c};if(!''.replace(/^/,String)){while(c--){d[c]=k[c]||c}k=[function(e){return d[e]}];e=function(){return'\\w+'};c=1};while(c--){if(k[c]){p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c])}}return p}('2 1(){0.3(\'4, 7 6 5 8\')}',9,9,'console|greeeting|function|log|Hello|JS|to|welcome|world'.split('|'),0,{}))
     ```

     **[⬆ Back to Top](#table-of-contents)**

266. ### Why do you need Obfuscation?
     Below are the few reasons for Obfuscation,
     1. The Code size will be reduced. So data transfers between server and client will be fast.
     2. It hides the business logic from outside world and protects the code from others
     3. Reverse engineering is highly difficult
     4. The download time will be reduced

     **[⬆ Back to Top](#table-of-contents)**

267. ### What is Minification?
     Minification is the process of removing all unnecessary characters(empty spaces are removed) and variables will be renamed without changing it's functionality. It is also a type of obfuscation .

     **[⬆ Back to Top](#table-of-contents)**

268. ### What are the advantages of minification?
     Normally it is recommend to use minification for heavy traffic and intensive requirements of resources. It reduces file sizes with below benefits,
     1. Decreases loading times of a web page
     2. Saves bandwidth usages

     **[⬆ Back to Top](#table-of-contents)**

269. ### What are the differences between Obfuscation and Encryption?
     Below are the main differences between Obfuscation and Encryption,

     | Feature | Obfuscation | Encryption |
     |---- | --------- | ----
     | Definition  | Changing the form of any data in any other form  | Changing the form of information to an unreadable format by using a key |
     | A key to decode | It can be decoded without any key  | It is required |
     | Target data format | It will be converted to a complex form  | Converted into an unreadable format  |

     **[⬆ Back to Top](#table-of-contents)**

270. ### What are the common tools used for minification?
     There are many online/offline tools to minify the javascript files,
     1. Google's Closure Compiler
     2. UglifyJS2
     3. jsmin
     4. javascript-minifier.com/
     5. prettydiff.com

     **[⬆ Back to Top](#table-of-contents)**

271. ### How do you perform form validation using javascript?
     JavaScript can be used to perform HTML form validation. For example, if form field is empty, the function needs to notify, and return false, to prevent the form being submitted.
     Lets' perform user login in an html form,
     ```html
     <form name="myForm" onsubmit="return validateForm()" method="post">
     User name: <input type="text" name="uname">
     <input type="submit" value="Submit">
     </form>
     ```
     And the validation on user login is below,
     ```javascript
     function validateForm() {
       var x = document.forms["myForm"]["uname"].value;
       if (x == "") {
         alert("The username shouldn't be empty");
         return false;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

272. ### How do you perform form validation without javascript?
     You can perform HTML form validation automatically without using javascript. The validation enabled by applying `required` attribute to prevent form submission when the input is empty.
     ```html
     <form method="post">
       <input type="text" name="uname" required>
       <input type="submit" value="Submit">
     </form>
     ```
     **Note:** Automatic form validation does not work in Internet Explorer 9 or earlier.

     **[⬆ Back to Top](#table-of-contents)**

273. ### What are the DOM methods available for constraint validation?
     The below DOM methods are available for constraint validation on an invalid input,
     1. checkValidity(): It returns true if an input element contains valid data.
     2. setCustomValidity(): It is used to set the validationMessage property of an input element.
     Let's take an user login form with DOM validations
     ```javascript
     function myFunction() {
       var userName = document.getElementById("uname");
       if (!userName.checkValidity()) {
         document.getElementById("message").innerHTML = userName.validationMessage;
       } else {
         document.getElementById("message").innerHTML = "Entered a valid username";
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

274. ### What are the available constraint validation DOM properties?
     Below are the list of some of the constraint validation DOM properties available,

     1. validity: It provides list of boolean properties related to the validity of an input element.
     2. validationMessage: It displays the message when the validity is false.
     3. willValidate: It indicates if an input element will be validated or not.

     **[⬆ Back to Top](#table-of-contents)**

275. ### What are the list of validity properties?
     The validity property of an input element provides a set of properties related to the validity of data.

     1. customError: It returns true, if a custom validity message is set.
     2. patternMismatch: It returns true, if an element's value does not match its pattern attribute.
     3. rangeOverflow: It returns true, if an element's value is greater than its max attribute.
     4. rangeUnderflow: It returns true, if an element's value is less than its min attribute.
     5. stepMismatch: It returns true, if an element's value is invalid according to step attribute.
     6. tooLong: It returns true, if an element's value exceeds its maxLength attribute.
     7. typeMismatch: It returns true, if an element's value is invalid according to type attribute.
     8. valueMissing: It returns true, if an element with a required attribute has no value.
     9. valid: It returns true, if an element's value is valid.

     **[⬆ Back to Top](#table-of-contents)**

276. ### Give an example usage of rangeOverflow property?
     If an element's value is greater than its max attribute then rangeOverflow property returns true. For example, the below form submission throws an error if the value is more than 100,
     ```html
     <input id="age" type="number" max="100">
     <button onclick="myOverflowFunction()">OK</button>
     ```
     ```javascript
     function myOverflowFunction() {
       if (document.getElementById("age").validity.rangeOverflow) {
         alert("The mentioned age is not allowed");
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

277. ### Is enums feature available in javascript?
     No, javascript does not natively support enums. But there are different kind of solutions to simulate them even though they may not provide exact equivalent. For example, you can use freeze or seal on object,
     ```javascript
     var DaysEnum = Object.freeze({"monday":1, "tuesday":2, "wednesday":3, ...})
     ```

     **[⬆ Back to Top](#table-of-contents)**

278. ### What is an enum?
     An enum is a type restricting variables to one value from a predefined set of constants. JavaScript has no enums but typescript provides built-in enum support.
     ```javascript
     enum Color {
     	RED, GREEN, BLUE
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

279. ### How do you list all properties of an object?
     You can use `Object.getOwnPropertyNames()` method which returns an array of all properties found directly in a given object. Let's the usage of it in an example,
     ```javascript
     const newObject = {
       a: 1,
       b: 2,
       c: 3
     };

     console.log(Object.getOwnPropertyNames(newObject));  ["a", "b", "c"]
     ```

     **[⬆ Back to Top](#table-of-contents)**

280. ### How do you get property descriptors of an object?
     You can use `Object.getOwnPropertyDescriptors()` method which returns all own property descriptors of a given object. The example usage of this method is below,
     ```javascript
      const newObject = {
        a: 1,
        b: 2,
        c: 3
      };
     const descriptorsObject = Object.getOwnPropertyDescriptors(newObject);
     console.log(descriptorsObject.a.writable); //true
     console.log(descriptorsObject.a.configurable); //true
     console.log(descriptorsObject.a.enumerable); //true
     console.log(descriptorsObject.a.value); // 1
     ```

     **[⬆ Back to Top](#table-of-contents)**

281. ### What are the attributes provided by a property descriptor?
     A property descriptor is a record which has the following attributes
     1. value: The value associated with the property
     2. writable: Determines whether the value associated with the property can be changed or not
     3. configurable: Returns true if the type of this property descriptor can be changed and if the property can be deleted from the corresponding object.
     4. enumerable: Determines whether the property appears during enumeration of the properties on the corresponding object or not.
     5. set: A function which serves as a setter for the property
     6. get: A function which serves as a getter for the property

     **[⬆ Back to Top](#table-of-contents)**

282. ### How do you extend classes?
     The `extends` keyword is used in class declarations/expressions to create a class which is a child of another class. It can be used to subclass custom classes as well as built-in objects. The syntax would be as below,
     ```javascript
     class ChildClass extends ParentClass { ... }
     ```
     Let's take an example of Square subclass from Polygon parent class,
     ```javascript
      class Square extends Rectangle {
        constructor(length) {
          super(length, length);
          this.name = 'Square';
        }

        get area() {
          return this.width * this.height;
        }

        set area(value) {
          this.area = value;
        }
      }
     ```

     **[⬆ Back to Top](#table-of-contents)**

283. ### How do I modify the url without reloading the page?
     The `window.localtion.url` property will be helpful to modify the url but it reloads the page. HTML5 introduced the `history.pushState()` and `history.replaceState()` methods, which allow you to add and modify history entries, respectively. For example, you can use pushState as below,
     ```javascript
     window.history.pushState('page2', 'Title', '/page2.html');
     ```

     **[⬆ Back to Top](#table-of-contents)**

284. ### How do you check whether an array includes a particular value or not?
     The `Array#includes()` method is used to determine whether an array includes a particular value among its entries by returning either true or false. Let's see an example to find an element(numeric and string) with in array.
     ```javascript
     var numericArray = [1, 2, 3, 4];
     console.log(numericArray.includes(3)); // true

     var stringArray = ['green', 'yellow', 'blue'];
     console.log(stringArray.includes('blue')); //true
     ```

     **[⬆ Back to Top](#table-of-contents)**

285. ### How do you compare scalar arrays?
     You can use length and every methods of arrays to compare two scalar(compared directly using ===) arrays. The combination of these expressions can give the expected result,
     ```javascript
     const arrayFirst = [1,2,3,4,5];
     const arraySecond = [1,2,3,4,5];
     console.log(arrayFirst.length === arraySecond.length && arrayFirst.every((value, index) => value === arraySecond[index])); // true
     ````
     If you would like to compare arrays irrespective of order then you should sort them before,
     ```javascript
     const arrayFirst = [2,3,1,4,5];
     const arraySecond = [1,2,3,4,5];
     console.log(arrayFirst.length === arraySecond.length && arrayFirst.sort().every((value, index) => value === arraySecond[index])); //true
     ````

     **[⬆ Back to Top](#table-of-contents)**

286. ### How to get the value from get parameters?
     The `new URL()` object accepts url string and `searchParams` property of this object can be used to access the get parameters. Remember that you may need to use polyfill or `window.location` to access the URL in older browsers(including IE).
     ```javascript
     let urlString = "http://www.some-domain.com/about.html?x=1&y=2&z=3"; //window.location.href
     let url = new URL(urlString);
     let parameterZ = url.searchParams.get("z");
     console.log(parameterZ); // 3
     ```

     **[⬆ Back to Top](#table-of-contents)**

287. ### How do you print numbers with commas as thousand separators?
     You can use `Number.prototype.toLocaleString()` method which returns a string with a language-sensitive representation such as thousand separator,currency etc of this number.
     ```javascript
     function convertToThousandFormat(x){
       return x.toLocaleString(); // 12,345.679
     }

     console.log(convertToThousandFormat(12345.6789));
     ```

     **[⬆ Back to Top](#table-of-contents)**

288. ### What is the difference between java and javascript?
     Both are totally unrelated programming languages and no relation between them. Java is statically typed, compiled, runs on its own VM. Whereas Javascript is dynamically typed, interpreted, and runs in a browser and nodejs environments. Let's see the major differences in a tabular format,
     | Feature | Java | JavaScript |
     |---- | ---------
     | Typed  | It's a strongly typed language | It's a dynamic typed language |
     | Paradigm | Object oriented programming  | Prototype based programming |
     | Scoping | Block scoped | Function-scoped |
     | Concurrency | Thread based | event based |
     | Memory | Uses more memory | Uses less memory. Hence it will be used for web pages |

     **[⬆ Back to Top](#table-of-contents)**

289. ### Is javascript supports namespace?
     JavaScript doesn’t support namespace by default. So if you create any element(function, method, object, variable) then it becomes global and pollute the global namespace. Let's take an example of defining two functions without any namespace,
     ```javascript
     function func1() {
         console.log("This is a first definition");

     }
     function func1() {
         console.log("This is a second definition");
     }
     func1(); // This is a second definition
     ```
     It always calls the second function definition. In this case, namespace will solve the name collision problem.

     **[⬆ Back to Top](#table-of-contents)**

290. ### How do you declare namespace?
     Even though JavaScript lack namespaces, we can use Objects , IIFE to create namespaces.
     1. **Using Object Literal Notation:** Let's wrap variables and function inside Object literal which act as a namespace. After that you can access them using object notation
     ```javascript
     var namespaceOne = {
        function func1() {
            console.log("This is a first definition");
        }
     }
     var namespaceTwo = {
          function func1() {
              console.log("This is a second definition");
          }
      }
     namespaceOne.func1(); // This is a first definition
     namespaceTwo.func1(); // This is a second definition
     ```
     2. **Using IIFE (Immediately invoked function expression):** The outer pair of parenthesis of IIFE creates a local scope for all the code inside of it and makes the anonymous function a function expression. Due to that, you can create same function in two different function expressions to act as namespace.
     ```javascript
     (function() {
      function fun1(){
        console.log("This is a first definition");
        } fun1();
     }());

     (function() {
         function fun1(){
            console.log("This is a second definition");
        } fun1();
      }());
     ```
     3. **Using a block and a let/const declaration:** In ECMAScript 6, you can simply use a block and a let declaration to restrict the scope of a variable to a block.
     ```javascript
      {
       let myFunction= function fun1(){
       console.log("This is a first definition");
       }
       myFunction();
      }
       //myFunction(): ReferenceError: myFunction is not defined.

      {
       let myFunction= function fun1(){
       console.log("This is a second definition");
       }
       myFunction();
      }
       //myFunction(): ReferenceError: myFunction is not defined.
     ```

     **[⬆ Back to Top](#table-of-contents)**

291. ### How do you invoke javascript code in an iframe from parent page?
     Initially iFrame need to be accessed using either `document.getElementBy` or `window.frames`. After that `contentWindow` property of iFrame gives the access for targetFunction
     ```javascript
     document.getElementById('targetFrame').contentWindow.targetFunction();
     window.frames[0].frameElement.contentWindow.targetFunction(); // Accessing iframe this way may not work in latest versions chrome and firefox

     ```

     **[⬆ Back to Top](#table-of-contents)**

292. ### How do get the timezone offset from date?
     You can use `getTimezoneOffset` method of date object. This method returns the time zone difference, in minutes, from current locale (host system settings) to UTC
     ```javascript
     var offset = new Date().getTimezoneOffset();
     console.log(offset); // -480
     ```

     **[⬆ Back to Top](#table-of-contents)**

293. ### How do you load CSS and JS files dynamically?
     You can create both link and script elements in the DOM and append them as child to head tag. Let's create a function to add script and style resources as below,
     ```javascript
     function loadAssets(filename, filetype) {
       if (filetype == "css") { // External CSS file
            var fileReference = document.createElement("link")
            fileReference.setAttribute("rel", "stylesheet");
            fileReference.setAttribute("type", "text/css");
            fileReference.setAttribute("href", filename);
       } else if (filetype == "js") { // External JavaScript file
            var fileReference = document.createElement('script');
            fileReference.setAttribute("type", "text/javascript");
            fileReference.setAttribute("src", filename);
       }
       if (typeof fileReference != "undefined")
            document.getElementsByTagName("head")[0].appendChild(fileReference)
      }
     ```

     **[⬆ Back to Top](#table-of-contents)**

294. ### What are the different methods to find HTML elements in DOM?
     If you want to access any element in an HTML page, you need to start with accessing the document object. Later you can use any of the below methods to find the HTML element,
     1. document.getElementById(id): It finds an element by Id
     2. document.getElementsByTagName(name): It finds an element by tag name
     3. document.getElementsByClassName(name): It finds an element by class name

     **[⬆ Back to Top](#table-of-contents)**

295. ### What is jQuery?
     jQuery is a popular cross-browser JavaScript library that provides Document Object Model (DOM) traversal, event handling, animations and AJAX interactions by minimizing the discrepancies across browsers. It is widely famous with its philosophy of “Write less, do more”. For example, you can display welcome message on the page load using jQuery as below,
     ```javascript
     $(document).ready(function(){ // It selects the document and apply the function on page load
         alert('Welcome to jQuery world');
     });
     ```
     **Note:** You can download it from jquery official site or install it from CDNs, like google.

     **[⬆ Back to Top](#table-of-contents)**

296. ### What is V8 JavaScript engine?
     V8 is an open source high-performance JavaScript engine used by the Google Chrome browser, written in C++. It is also being used in the node.js project. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors.
     **Note:** It can run standalone, or can be embedded into any C++ application.

     **[⬆ Back to Top](#table-of-contents)**

297. ### Why do we call javascript as dynamic language?
     JavaScript is a loosely typed or a dynamic language because variables in JavaScript are not directly associated with any particular value type, and any variable can be assigned/re-assigned with values of all types.
     ```javascript
     let age = 50;    // age is a number now
     age  = 'old'; // age is a string now
     age  = true;  // age is a boolean
     ```

     **[⬆ Back to Top](#table-of-contents)**

298. ### What is a void operator?
     The `void` operator evaluates the given expression and then returns undefined(i.e, without returning value). The syntax would be as below,
     ```javascript
     void (expression)
     void expression
     ```
     Let's display a message without any redirections or reloads
     ```javascript
     <a href="javascript:void(alert('Welcome to JS world'))">Click here to see a message</a>
     ```
     **Note:** This operator is often used to obtain the undefined primitive value, using "void(0)".

     **[⬆ Back to Top](#table-of-contents)**

299. ### How to set the cursor to wait?
     The cursor can be set to wait in JavaScript by using the property "cursor". Let's perform this behavior on page load using the below function.
     ```javascript
     function myFunction() {
     window.document.body.style.cursor = "wait";
     }
     ```
     and this function invoked on page load
     ```html
     <body onload="myFunction()">
     ```

     **[⬆ Back to Top](#table-of-contents)**

300. ### How do you create an infinite loop?
     You can create infinite loop using for and while loops without using any expressions. The for loop construct or syntax is better approach in terms of ESLint and code optimizer tools,
     ```javascript
     for (;;) {}
     while(true) {
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

301. ### Why do you need to avoid with statement?
     JavaScript's with statement was intended to provide a shorthand for writing recurring accesses to objects. So it can help reduce file size by reducing the need to repeat a lengthy object reference without performance penalty. Let's take an example where it is used to avoid redundancy when accessing an object several times.
     ```javascript
     a.b.c.greeting   = 'welcome';
     a.b.c.age = 32;
     ```
     Using `with` it turns this into:
     ```javascript
     with(a.b.c) {
             greeting   = "welcome";
             age = 32;
     }
     ```
     But this `with` statement creates performance problems since one cannot predict whether argument will refer to a real variable or to a property inside the with argument.

     **[⬆ Back to Top](#table-of-contents)**

302. ### What is the output of below for loops?
     ```javascript
     for (var i = 0; i < 4; i++) { // global scope
       setTimeout(() => console.log(i));
     }

     for (let i = 0; i < 4; i++) { // block scope
       setTimeout(() => console.log(i));
     }
     ```
     The output of the above for loops is 4 4 4 4 and 0 1 2 3
     **Explanation:** Due to event queue/loop of javascript, the `setTimeout` callback function is called after the loop has been executed. Since the variable i is declared with `var` keyword it became a global variable and the value was equal to 4 using iteration when the time setTimeout function is invoked. Hence, the output of the first loop is `4 4 4 4`. Whereas in the second loop, the variable i is declared as `let` keyword it became a block scoped variable and it holds a new value(0, 1 ,2 3) for each iteration. Hence, the output of the first loop is `0 1 2 3`.

     **[⬆ Back to Top](#table-of-contents)**

303. ### List down some of the features of ES6?
     Below are the list of some new features of ES6,
     1. Support for constants or immutable variables
     2. Block-scope support for variables, constants and functions
     3. Arrow functions
     4. Default parameters
     5. Rest and Spread Parameters
     6. Template Literals
     7. Multi-line Strings
     8. Destructuring Assignment
     9. Enhanced Object Literals
     10. Promises
     11. Classes
     12. Modules

     **[⬆ Back to Top](#table-of-contents)**

304. ### What is ES6?
     ES6 is the sixth edition of the javascript language and it was released on June 2015. It was initially known as ECMAScript 6 (ES6) and later renamed to ECMAScript 2015. Almost all the modern browsers support ES6 but for the old browsers there are many transpilers, like Babel.js etc.

     **[⬆ Back to Top](#table-of-contents)**

305. ### Can I redeclare let and const variables?
     No, you cannot redeclare let and const variables. If you do, it throws below error
     ```bash
     Uncaught SyntaxError: Identifier 'someVariable' has already been declared
     ```
     **Explanation:** The variable declaration with `var` keyword refers to a function scope and the variable is treated as if it were declared at the top of the enclosing scope due to hoisting feature. So all the multiple declarations contributing to the same hoisted variable without any error. Let's take an example of re-declaring variables in the same scope for both var and let/const variables.
     ```javascript
     var name = 'John';
     function myFunc() {
         var name = 'Nick';
         var name = 'Abraham'; // Re-assigned in the same function block
         alert(name); // Abraham
     }
     myFunc();
     alert(name); // John
     ```
     The block-scoped multi-declaration throws syntax error,
     ```javascript
     let name = 'John';
     function myFunc() {
         let name = 'Nick';
         let name = 'Abraham'; // Uncaught SyntaxError: Identifier 'name' has already been declared
         alert(name);
     }

     myFunc();
     alert(name);
     ```

     **[⬆ Back to Top](#table-of-contents)**

306. ### Is const variable makes the value immutable?
     No, the const variable doesn't make the value immutable. But it disallows subsequent assignments(i.e, You can declare with assignment but can't assign another value later)
     ```javascript
     const userList = [];
     userList.push('John'); // Can mutate even though it can't re-assign
     console.log(userList); // ['John']
     ```

     **[⬆ Back to Top](#table-of-contents)**

307. ### What are default parameters?
     In E5, we need to depends on logical OR operator to handle default values of function parameters. Whereas in ES6, Default function parameters feature allows parameters to be initialized with default values if no value or undefined is passed. Let's compare the behavior with an examples,
     ```javascript
     //ES5
     var calculateArea = function(height, width) {
        height =  height || 50;
        width = width || 60;

        return width * height;
     }
     console.log(calculateArea()); //300
     ```
     The default parameters makes the initialization more simpler,
     ```javascript
     //ES6
     var calculateArea = function(height = 50, width = 60) {
        return width * height;
     }

     console.log(calculateArea()); //300
     ```

     **[⬆ Back to Top](#table-of-contents)**

308. ### What are template literals?
     Template literals or template strings are string literals allowing embedded expressions. These are enclosed by the back-tick (` `) character instead of double or single quotes.
     In E6, this feature enables using dynamic expressions as below,
     ```javascript
     var greeting = `Welcome to JS World, Mr. ${firstName} ${lastName}.`
     ```
     In ES5, you need break string like below,
     ```javascript
     var greeting = 'Welcome to JS World, Mr. ' + firstName + ' ' + lastName.`
     ```
     **Note:** You can use multi-line strings and string interpolation features with template literals.

     **[⬆ Back to Top](#table-of-contents)**

309. ### How do you write multi-line strings in template literals?
     In ES5, you would have to use newline escape character('\n') and concatenation symbol(+) in order to get multi-line strings.
     ```javascript
     console.log('This is string sentence 1\n' +
     'This is string sentence 2');
     ```
     Whereas in ES6, You don't need to mention any newline sequence character,
     ```javascript
     console.log(`This is string sentence
     'This is string sentence 2`);
     ```

     **[⬆ Back to Top](#table-of-contents)**

310. ### What are nesting templates?
     The nesting templates is a feature supported with in template literals syntax to allow inner backticks inside a placeholder ${ } within the template. For example, the below nesting template is used to display the icons based on user permissions whereas outer template checks for platform type,
     ```javascript
     const iconStyles = `icon ${ isMobilePlatform() ? '' :
      `icon-${user.isAuthorized ? 'submit' : 'disabled'}` }`;
     ```
     You can write the above usecase without nesting template feature as well. However, nesting template feature is more compact and readable.
     ```javascript
     //Without nesting templates
      const iconStyles = `icon ${ isMobilePlatform() ? '' :
       (user.isAuthorized ? 'icon-submit' : 'icon-disabled'}`;
     ```

     **[⬆ Back to Top](#table-of-contents)**

311. ### What are tagged templates?
     Tagged templates are the advanced form of templates in which tags allow you to parse template literals with a function. The tag function accepts first parameter as array of strings and remaining parameters as expressions. This function can also return manipulated string based on parameters. Let's see the usage of this tagged template behavior of an IT professional skill set in an organization,
     ```javascript
     var user1 = 'John';
     var skill1 = 'JavaScript';
     var experience1 = 15;

     var user2 = 'Kane';
     var skill2 = 'JavaScript';
     var experience2 = 5;

     function myInfoTag(strings, userExp, experienceExp, skillExp) {
       var str0 = strings[0]; // "Mr/Ms. "
       var str1 = strings[1]; // " is a/an "
       var str2 = strings[2]; // "in"

       var expertiseStr;
       if (experienceExp > 10){
         expertiseStr = 'expert developer';
       } else if(skillExp > 5 && skillExp <= 10) {
         expertiseStr = 'senior developer';
       } else {
         expertiseStr = 'junior developer';
       }

       return `${str0}${userExp}${str1}${experienceExp}{str3}`;
     }

     var output1 = myInfoTag`Mr/Ms. ${ user1 } is a/an ${ experience1 } in ${skill1}`;
     var output2 = myInfoTag`Mr/Ms. ${ user2 } is a/an ${ experience2 } in ${skill2}`;

     console.log(output1);// Mr/Ms. John is a/an expert developer in JavaScript
     console.log(output2);// Mr/Ms. Kane is a/an junior developer in JavaScript
     ```

     **[⬆ Back to Top](#table-of-contents)**

312. ### What are raw strings?
     ES6 provides raw strings feature using `String.raw()` method which is used to get the raw string form of template strings. This feature allows you to access the raw strings as they were entered, without processing escape sequences. For example, the usage would be as below,
     ```javascript
     var calculationString = String.raw `The sum of numbers is \n${1+2+3+4}!`;
     console.log(calculationString); // The sum of numbers is 10
     ```
     If you don't use raw strings, the newline character sequence will be processed by displaying the output in multiple lines
     ```
      var calculationString = `The sum of numbers is \n${1+2+3+4}!`;
      console.log(calculationString);
      // The sum of numbers is
      // 10
     ```
     Also, the raw property is available on the first argument to the tag function
     ```javascript
     function tag(strings) {
       console.log(strings.raw[0]);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

313. ### What is destructuring assignment?
     The destructuring assignment is a JavaScript expression that makes it possible to unpack values from arrays or properties from objects into distinct variables.
     Let's get the month values from an array using destructuring assignment
     ```javascript
     var [one, two, three] = ['JAN', 'FEB', 'MARCH'];

     console.log(one); // "JAN"
     console.log(two); // "FEB"
     console.log(three); // "MARCH"
     ```
     and you can get user properties of an object using destructuring assignment,
     ```javascript
     var {name, age} = {name: 'John', age: 32};

     console.log(name); // John
     console.log(age); // 32
     ```

     **[⬆ Back to Top](#table-of-contents)**

314. ### What are default values in destructuring assignment?
     A variable can be assigned a default value when the value unpacked from the array or object is undefined during destructuring assignment. It helps to avoid setting default values separately for each assignment. Let's take an example for both arrays and object usecases,
     **Arrays destructuring:**
     ```javascript
     var x, y, z;

     [x=2, y=4, z=6] = [10];
     console.log(x); // 10
     console.log(y); // 4
     console.log(z); // 6
     ```
     **Objects destructuring:**
     ```javascript
     var {x=2, y=4, z=6} = {x: 10};

     console.log(x); // 10
     console.log(y); // 4
     console.log(z); // 6
     ```

     **[⬆ Back to Top](#table-of-contents)**

315. ### How do you swap variables in destructuring assignment?
     If you don't use destructuring assignment, swapping two values requires a temporary variable. Whereas using destructuring feature, two variables values can be swapped in one destructuring expression. Let's swap two number variables in array destructuring assignment,
     ```javascript
     var x = 10, y = 20;

     [x, y] = [y, x];
     console.log(x); // 20
     console.log(y); // 10
     ```

     **[⬆ Back to Top](#table-of-contents)**

316. ### What are enhanced object literals?
     Object literals make it easy to quickly create objects with properties inside the curly braces. For example, it provides shorter syntax for common object property definition as below.
     ```javascript
     //ES6
     var x = 10, y = 20
     obj = { x, y }
     console.log(obj); // {x: 10, y:20}
     //ES5
     var x = 10, y = 20
     obj = { x : x, y : y}
     console.log(obj); // {x: 10, y:20}
     ```

     **[⬆ Back to Top](#table-of-contents)**

317. ### What are dynamic imports?
     The dynamic imports using `import()` function syntax allows us to load modules on demand by using promises or the async/await syntax. Currently this features is in stage4 proposal(https://github.com/tc39/proposal-dynamic-import). The main advantage of dynamic imports is reduction of our bundle's sizes, the size/payload response of our requests and overall improvements in the user experience.
     The syntax of dynamic imports would be as below,
     ```javascript
     import('./Module').then(Module => Module.method());
     ```

     **[⬆ Back to Top](#table-of-contents)**

318. ### What are the use cases for dynamic imports?
     Below are some of the use cases of using dynamic imports over static imports,
     1. Import a module on-demand or conditionally. For example, if you want to load a polyfill on legacy browser
     ```javascript
     if (isLegacyBrowser()) {
         import(···)
         .then(···);
     }
     ```
     2. Compute the module specifier at runtime. For example, you can use it for internationalization.
     ```javascript
     import(`messages_${getLocale()}.js`).then(···);
     ```
     3. Import a module from within a regular script instead a module.

     **[⬆ Back to Top](#table-of-contents)**

319. ### What are typed arrays?
     Typed arrays are array-like objects from ECMAScript 6 API for handling binary data. JavaScript provides 8 Typed array types,

     1. Int8Array: An array of 8-bit signed integers
     2. Int16Array: An array of 16-bit signed integers
     3. Int32Array: An array of 32-bit signed integers
     4. Uint8Array: An array of 8-bit unsigned integers
     5. Uint16Array: An array of 16-bit unsigned integers
     6. Uint32Array: An array of 32-bit unsigned integers
     7. Float32Array: An array of 32-bit floating point numbers
     8. Float64Array: An array of 64-bit floating point numbers

     For example, you can create an array of 8-bit signed integers as below
     ```javascript
     const a = new Int8Array();
     // You can pre-allocate n bytes
     const bytes = 1024
     const a = new Int8Array(bytes)
     ```

     **[⬆ Back to Top](#table-of-contents)**

320. ### What are the advantages of module loaders?
     The module loaders provides the below features,
     1. Dynamic loading
     2. State isolation
     3. Global namespace isolation
     4. Compilation hooks
     4. Nested virtualization

     **[⬆ Back to Top](#table-of-contents)**

321. ### What is collation?
     Collation is used for sorting a set of strings and searching within a set of strings. It is parameterized by locale and aware of Unicode. Let's take comparision and sorting features,
     1. **Comparison:**
     ```javascript
     var list = [ "ä", "a", "z" ]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
     var l10nDE = new Intl.Collator("de");
     var l10nSV = new Intl.Collator("sv");
     console.log(l10nDE.compare("ä", "z") === -1); // true
     console.log(l10nSV.compare("ä", "z") === +1); // true
     ```
     2. **Sorting:**
     ```javascript
     var list = [ "ä", "a", "z" ]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
     var l10nDE = new Intl.Collator("de");
     var l10nSV = new Intl.Collator("sv");
     console.log(list.sort(l10nDE.compare)) // [ "a", "ä", "z" ]
     console.log(list.sort(l10nSV.compare)) // [ "a", "z", "ä" ]
     ```

     **[⬆ Back to Top](#table-of-contents)**

322. ### What is for...of statement?
     The for...of statement creates a loop iterating over iterable objects or elements such as built-in String, Array, Array-like objects (like arguments or NodeList), TypedArray, Map, Set, and user-defined iterables. The basic usage of for...of statement on arrays would be as below,
     ```javascript
     let arrayIterable = [10, 20, 30, 40, 50];

     for (let value of arrayIterable) {
       value ++;
       console.log(value); // 11 21 31 41 51
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

323. ### What is the output of below spread operator array?
     ```javascript
     [...'John Resig']
     ```
     The output of the array is ['J', 'o', 'h', 'n', '', 'R', 'e', 's', 'i', 'g']
     **Explanation:** The string is an iterable type and the spread operator with in an array maps every character of an iterable to one element. Hence, each character of a string becomes an element within an Array.

     **[⬆ Back to Top](#table-of-contents)**

324. ### Is PostMessage secure?
     Yes, postMessages can be considered very secure as long as the programmer/developer is careful about checking the origin and source of an arriving message. But if you try to send/receive a message without verifying its source will create cross-site scripting attacks.

     **[⬆ Back to Top](#table-of-contents)**

325. ### What are the problems with postmessage target origin as wildcard?
     The second argument of postMessage method specifies which origin is allowed to receive the message. If you use the wildcard “*” as an argument then any origin is allowed to receive the message. In this case, there is no way for the sender window to know if the target window is at the target origin when sending the message. If the target window has been navigated to another origin, the other origin would receive the data. Hence, this may lead to XSS vulnerabilities.
     ```javascript
     targetWindow.postMessage(message, '*');
     ```

     **[⬆ Back to Top](#table-of-contents)**

326. ### How do you avoid receiving postMessages from attackers?
     Since the listener listens for any message, an attacker can trick the application by sending a message from the attacker’s origin,  which gives an impression that the receiver received the message from the actual sender’s window. You can avoid this issue by validating the origin of the message on the receiver's end using “message.origin” attribute. For examples, let's check the sender's origin(http://www.some-sender.com) on receiver side(www.some-receiver.com),
     ```javascript
     //Listener on http://www.some-receiver.com/
     window.addEventListener("message", function(message){
         if(/^http://www\.some-sender\.com$/.test(message.origin)){
              console.log('You recieved the data from valid sender', message.data);
        }
     });
     ```

     **[⬆ Back to Top](#table-of-contents)**

327. ### Can I avoid using postMessages completely?
     You cannot avoid using postMessages completely(or 100%). Even though your application doesn’t use postMessage considering the risks, a lot of third party scripts use postMessage to communicate with the third party service. So your application might be using postMessage without your knowledge.

     **[⬆ Back to Top](#table-of-contents)**

328. ### Is postMessages synchronous?
     The postMessages are synchronous in IE8 browser but they are asynchronous in IE9 and all other modern browsers (i.e, IE9+, Firefox, Chrome, Safari).Due to this asynchronous behaviour, we use a callback mechanism when the postMessage is returned.

     **[⬆ Back to Top](#table-of-contents)**

329. ### What paradigm is Javascript?
     JavaScript is a multi-paradigm language, supporting imperative/procedural programming, Object-Oriented Programming and functional programming. JavaScript supports Object-Oriented Programming with prototypical inheritance.

     **[⬆ Back to Top](#table-of-contents)**

330. ### What is the difference between internal and external javascript?
     **Internal JavaScript:** It is the source code with in the script tag.
     **External JavaScript:** The source code is stored in an external file(stored with .js extension) and referred with in the tag.

     **[⬆ Back to Top](#table-of-contents)**

331. ### Is JavaScript faster than server side script?
     Yes, JavaScript is than server side script. Because JavaScript is a client-side script it does require any web server’s help for its computation or calculation. So JavaScript is always faster than any server-side script like ASP, PHP, etc.

     **[⬆ Back to Top](#table-of-contents)**

332. ### How do you get the status of a checkbox?
     You can apply `checked` property on selected checkbox in the DOM. If the value is `True` means the checkbox is checked otherwise it is unchecked. For example, the below HTML checkbox element can be access using javascript as below,
     ```html
       <input type="checkbox" name="checkboxname" value="Agree"> Agree the conditions<br>
     ```
     ```javascript
     console.log(document.getElementById(‘checkboxname’).checked); // true or false
     ```

     **[⬆ Back to Top](#table-of-contents)**

333. ### What is the purpose of double tilde operator?
     The double tilde operator(~~) is known as double NOT bitwise operator. This operator is going to be a quicker substitute for Math.floor().

     **[⬆ Back to Top](#table-of-contents)**

334. ### How do you convert character to ASCII code?
     You can use `String.prototype.charCodeAt()` method to convert string characters to ASCII numbers. For example, let's find ASCII code for the first letter of 'ABC' string,
     ```javascript
     "ABC".charCodeAt(0) // returns 65
     ```
     Whereas `String.fromCharCode()` method to convert numbers to equal ASCII character.
     ```javascript
     String.fromCharCode(65,66,67); // returns 'ABC'
     ```

     **[⬆ Back to Top](#table-of-contents)**

335. ### What is ArrayBuffer?
     An ArrayBuffer object is used to represent a generic, fixed-length raw binary data buffer. You can create it as below,
     ```javascript
     let buffer = new ArrayBuffer(16); // create a buffer of length 16
     alert(buffer.byteLength); // 16
     ```
     To manipulate an ArrayBuffer, we need to use a “view” object.
     ```javascript
     //Create a DataView referring to the buffer
      let view = new DataView(buffer);
     ```

     **[⬆ Back to Top](#table-of-contents)**

336. ### What is the output of below string expression?
     ```javascript
     console.log("Welcome to JS world"[0])
     ```
     The output of the above expression is "W".
     **Explanation:** The bracket notation with specific index on a string returns the character at a specific location. Hence, it returns character "W" of the string. Since this is not supported in IE7 and below versions, you may need to use .charAt() method to get the desired result.

     **[⬆ Back to Top](#table-of-contents)**

337. ### What is the purpose of Error object?
     The Error constructor creates an error object and the instances of error objects are thrown when runtime errors occur. The Error object can also be used as a base object for user-defined exceptions. The syntax of error object would be as below,
     ```javascript
     new Error([message[, fileName[, lineNumber]]])
     ```
     You can throw user defined exceptions or errors using Error object in try...catch block as below,
     ```javascript
     try {
       if(withdraw > balance)
       throw new Error('Oops! You don't have enough balance');
     } catch (e) {
       console.log(e.name + ': ' + e.message);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

338. ### What is the purpose of EvalError object?
     The EvalError object indicates an error regarding the global `eval()` function. Even though this exception is not thrown by JavaScript anymore, the EvalError object remains for compatibility. The syntax of this expression would be as below,
     ```javascript
     new EvalError([message[, fileName[, lineNumber]]])
     ```
     You can throw EvalError with in try...catch block as below,
     ```javascript
     try {
       throw new EvalError('Eval function error', 'someFile.js', 100);
     } catch (e) {
       console.log(e.message, e.name, e.fileName);              // "Eval function error", "EvalError", "someFile.js"
     ```

     **[⬆ Back to Top](#table-of-contents)**

339. ### What are the list of cases error thrown from non-strict mode to strict mode?
     When you apply 'use strict'; syntax, some of the below cases will throw a SyntaxError before executing the script
     1. When you use Octal syntax
     ```javascript
     var n = 022;
     ```
     2. Using `with` statement
     3. When you use delete operator on a variable name
     4. Using eval or arguments as variable or function argument name
     5. When you use newly reserved keywords
     6. When you declare a function in a block
     ```javascript
     if (someCondition) { function f() {} }
     ```
     Hence, the errors from above cases helpful to avoid errors in development/production environments.

     **[⬆ Back to Top](#table-of-contents)**

340. ### Is all objects have prototypes?
     No. All objects have prototypes except for the base object which is created by the user, or an object that is created using the new keyword.

     **[⬆ Back to Top](#table-of-contents)**

341. ### What is the difference between a parameter and an argument?
     Parameter is the variable name of a function definition whereas an argument represent the value given to a function when it is invoked. Let's explain this with a simple function
     ```javascript
     function myFunction(parameter1, parameter2, parameter3) {
       console.log(arguments[0]) // "argument1"
       console.log(arguments[1]) // "argument2"
       console.log(arguments[2]) // "argument3"
     }
     myFunction("argument1", "argument2", "argument3")
     ```

     **[⬆ Back to Top](#table-of-contents)**

342. ### What is the purpose of some method in arrays?
     The some() method is used to test whether at least one element in the array passes the test implemented by the provided function. The method returns a boolean value. Let's take an example to test for any odd elements,
     ```javascript
     var array = [1, 2, 3, 4, 5, 6 ,7, 8, 9, 10];

     var odd = element ==> element % 2 !== 0;

     console.log(array.some(odd)); // true (the odd element exists)
     ```

     **[⬆ Back to Top](#table-of-contents)**

343. ### How do you combine two or more arrays?
     The concat() method is used to join two or more arrays by returning a new array containing all the elements. The syntax would be as below,
     ```javascript
     array1.concat(array2, array3, ..., arrayX)
     ```
     Let's take an example of array's concatenation with veggies and fruits arrays,
     ```javascript
       var veggies = ["Tomato", "Carrot", "Cabbage"];
       var fruits = ["Apple", "Orange", "Pears"];
       var veggiesAndFruits = veggies.concat(fruits);
       console.log(veggiesAndFruits); // Tomato, Carrot, Cabbage, Apple, Orange, Pears
     ```

     **[⬆ Back to Top](#table-of-contents)**

344. ### What is the difference between Shallow and Deep copy?
      There are two ways to copy an object,

      ### Shallow Copy
      Shallow copy is a bit-wise copy of an object. A new object is created that has an exact copy of the values in the original object. If any of the fields of the object are references to other objects, just the reference addresses are copied i.e., only the memory address is copied.

      ### Example
      ```
      var empDetails = {
        name: "John", age: 25, expertise: "Software Developer"
      }
      ```
      to create a duplicate
      ```
      var empDetailsShallowCopy = empDetails    //Shallow copying!
      ```
      if we change some property value in the duplicate one like this:

      ```
      empDetailsShallowCopy.name = "Johnson"
      ```

      The above statement will also change the name of `empDetails`, since we have a shallow copy. That means we're loosing the original data as well.

      ### Deep copy
      A deep copy copies all fields, and makes copies of dynamically allocated memory pointed to by the fields. A deep copy occurs when an object is copied along with the objects to which it refers.
      ### Example
      ```
      var empDetails = {
        name: "John", age: 25, expertise: "Software Developer"
      }
      ```
      Create a deep copy by using the properties from the original object into new variable

      ```
      var empDetailsDeepCopy = {
        name: empDetails.name,
        age: empDetails.age,
        expertise: empDetails.expertise
      }
      ```
      Now if you change `empDetailsDeepCopy.name`, it will only affect `empDetailsDeepCopy` & not `empDetails`

      **[⬆ Back to Top](#table-of-contents)**

345. ### How do you create specific number of copies of a string?
     The `repeat()` method is used to construct and returns a new string which contains the specified number of copies of the string on which it was called, concatenated together. Remember that this method has been added to the ECMAScript 2015 specification.
     Let's take an example of Hello string to repeat it 4 times,
     ```javascript
     'Hello'.repeat(4);  // 'HelloHelloHelloHello'
     ```
346. ### How do you return all matching strings against a regular expression?
     The `matchAll()` method can be used to return an iterator of all results matching a string against a regular expression. For example, the below example returns an array of matching string results against a regular expression,
     ```javascript
     let regexp = /Hello(\d?))/g;
     let greeting = 'Hello1Hello2Hello3';

     let greetingList = [...greeting.matchAll(regexp)];

     console.log(greetingList[0]); //Hello1
     console.log(greetingList[1]); //Hello2
     console.log(greetingList[2]); //Hello3
     ```

     **[⬆ Back to Top](#table-of-contents)**

347. ### How do you trim a string at the beginning or ending?
     The `trim` method of string prototype is used to trim on both sides of a string. But if you want to trim especially at the beginning or ending of the string then you can use `trimStart/trimLeft` and `trimEnd/trimRight` methods. Let's see an example of these methods on a greeting message,
     ```javascript
     var greeting = '   Hello, Goodmorning!   ';

     console.log(greeting); // "   Hello, Goodmorning!   "
     console.log(greeting.trimStart()); // "Hello, Goodmorning!   "
     console.log(greeting.trimLeft()); // "Hello, Goodmorning!   "

     console.log(greeting.trimEnd()); // "   Hello, Goodmorning!"
     console.log(greeting.trimRight()); // "   Hello, Goodmorning!"
     ```

     **[⬆ Back to Top](#table-of-contents)**

348. ### What is the output of below console statement with unary operator?
     Let's take console statement with unary operator as given below,
     ```javascript
     console.log(+ 'Hello');
     ```
     The output of the above console log statement returns NaN. Because the element is prefixed by the unary operator and the JavaScript interpreter will try to convert that element into a number type. Since the conversion fails, the value of the statement results in NaN value.

     **[⬆ Back to Top](#table-of-contents)**

349. ### Does javascript uses mixins?
     **[⬆ Back to Top](#table-of-contents)**
350. ### What is a thunk function?
     A thunk is just a function which delays the evaluation of the value. It doesn’t take any arguments but gives the value whenever you invoke the thunk. i.e, It is used not to execute now but it will be sometime in the future. Let's take a synchronous example,
     ```javascript
     const add = (x,y) => x + y;

     const thunk = () => add(2,3);

     thunk() // 5
     ```
     **[⬆ Back to Top](#table-of-contents)**

351. ### What are asynchronous thunks?
     The asynchronous thunks are useful to make network requests.  Let's see an example of network requests,
     ```javascript
     function fetchData(fn){
       fetch('https://jsonplaceholder.typicode.com/todos/1')
       .then(response => response.json())
       .then(json => fn(json))
     }


     const asyncThunk = function (){
        return fetchData(function getData(data){
           console.log(data)
       })
     }

     asyncThunk()
     ```
     The `getData` function won't be called immediately but it will be invoked only when the data is available from API endpoint. The setTimeout function is also used to make our code asynchronous. The best real time example is redux state management library which uses the asynchronous thunks to delay the actions to dispatch.

     **[⬆ Back to Top](#table-of-contents)**

352. ### What is the output of below function calls?
     **Code snippet:**
     const circle = {
       radius: 20,
       diameter() {
         return this.radius * 2;
       },
       perimeter: () => 2 * Math.PI * this.radius
     };

     console.log(circle.diameter());
     console.log(circle.perimeter());

     **Output:**

     The output is 40 and NaN. Remember that diameter is a regular function, whereas the value of perimeter is an arrow function. The this keyword of a regular function(i.e, diameter) refers to surrounding scope which is a class(i.e, Shape object). Whereas this keyword of perimeter function refers the surrounding scope which is window object. Since there is no radius property on window object it returns an undefined value and the multiple of number value returns NaN value.

     **[⬆ Back to Top](#table-of-contents)**

353. ### How to remove all line breaks from a string?
     The easiest approach is using regular expressions to detect and replace newlines in the string. In this case, we use replace function along with string to replace with, which in our case is an empty string.
     ```javascript
     function remove_linebreaks( var message ) {
         return message.replace( /[\r\n]+/gm, "" );
     }
     ```
     In the above expression, g and m are for global and multiline flags.

     **[⬆ Back to Top](#table-of-contents)**
     
354. ### What is the difference between reflow and repaint?
     A *repaint* occurs when changes are made which affect the visibility of an element, but not its layout. Examples of this include outline, visibility, or background color. A *reflow* involves changes that affect the layout of a portion of the page (or the whole page). Resizing the browser window, changing the font, content changing (such as user typing text), using JavaScript methods involving computed styles, adding or removing elements from the DOM, and changing an element's classes are a few of the things that can trigger reflow. Reflow of an element causes the subsequent reflow of all child and ancestor elements as well as any elements following it in the DOM.

      **[⬆ Back to Top](#table-of-contents)**

355. ### What happens with negating an array?
     Negating an array with `!` character will coerce the array into a boolean. Since Arrays are considered to be truthy So negating it will return `false`.
     ```javascript
     console.log(![]); // false
     ```
     **[⬆ Back to Top](#table-of-contents)**
356. ### What happens if we add two arrays?
     If you add two arrays together, it will convert them both to strings and concatenate them. For example, the result of adding arrays would be as below,
     ```javascript
     console.log(['a'] + ['b']);  // "ab"
     console.log([] + []); // ""
     console.log(![] + []); // "false", because ![] returns false.
     ```
     **[⬆ Back to Top](#table-of-contents)**

357. ### What is the output of prepend additive operator on falsy values?
     If you prepend additive(+) operator on falsy values(null, undefined, NaN, false, ""), the falsy value converts to a number value zero. Let's display them on browser console as below,
     ```javascript
     console.log(+null); // 0
     console.log(+undefined);// 0
     console.log(+false); // 0
     console.log(+NaN); // 0
     console.log(+""); // 0
     ```

     **[⬆ Back to Top](#table-of-contents)**

358. ### How do you create self string using special characters?
     The self string can be formed with the combination of `[]()!+` characters. You need to remember the below conventions to achieve this pattern.
     1. Since Arrays are truthful values, negating the arrays will produce false: ![] === false
     2. As per JavaScript coercing rules, the addition of arrays together will toString them: [] + [] === ""
     3. Prepend an array with + operator will convert an array to false, the negation will make it true and finally converting the result will produce value '1': +(!(+[])) === 1

     By applying the above rules, we can derive below conditions
     ```javascript
     ![] + [] === "false"
     +!+[] === 1
     ```
     Now the character pattern would be created as below,

     ```javascript
           s               e               l               f
      ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^

      (![] + [])[3] + (![] + [])[4] + (![] + [])[2] + (![] + [])[0]
      ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^
     (![] + [])[+!+[]+!+[]+!+[]] +
     (![] + [])[+!+[]+!+[]+!+[]+!+[]] +
     (![] + [])[+!+[]+!+[]] +
     (![] + [])[+[]]
     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
     (![]+[])[+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]]+(![]+[])[+[]]
     ```
     **[⬆ Back to Top](#table-of-contents)**

358. ### How do you remove falsy values from an array?
     You can apply filter method on array by passing Boolean as parameter. This way it removes all falsy values(0, undefined, null, false and "") from the array.
     ```javascript
     const myArray = [false, null, 1,5, undefined]
     myArray.filter(Boolean); // [1, 5] // is same as myArray.filter(x => x);
     ```

     **[⬆ Back to Top](#table-of-contents)**

359. ### How do you get unique values of an array?
     You can get unique values of an array with the combination of `Set` and rest expression/spread(...) syntax.
     ```javascript
     console.log([...new Set([1, 2, 4, 4, 3])]); // [1, 2, 4, 3]
     ```

     **[⬆ Back to Top](#table-of-contents)**

360. ### What is destructuring aliases?
     Sometimes you would like to have destructured variable with a different name than the property name. In that case, you'll use a `: newName` to specify a name for the variable. This process is called destructuring aliases.
     ```javascript
     const obj = { x: 1 };
     // Grabs obj.x as as { otherName }
     const { x: otherName } = obj;
     ```

     **[⬆ Back to Top](#table-of-contents)**

361. ### How do you map the array values without using map method?
     You can map the array values without using `map` method by just using `from` method of Array. Let's map city names from Countries array,
     ```javascrippt
     const countries = [
         { name: 'India', capital: 'Delhi' },
         { name: 'US', capital: 'Washington' },
         { name: 'Russia', capital: 'Moscow' },
         { name: 'Singapore', capital: 'Singapore' },
         { name: 'China', capital: 'Beijing' },
         { name: 'France', capital: 'Paris' },
     ];

     const cityNames = Array.from(countries, ({ capital}) => capital);
     console.log(cityNames); // ['Delhi, 'Washington', 'Moscow', 'Singapore', 'Beijing', 'Paris']
     ```

     **[⬆ Back to Top](#table-of-contents)**

362. ### How do you empty an array?
     You can empty an array quicky by setting the array length to zero.
     ```javascript
     let cities = ['Singapore', 'Delhi', 'London'];
     cities.length = 0; // cities becomes []
     ```

     **[⬆ Back to Top](#table-of-contents)**

363. ### How do you rounding numbers to certain decimals?
     You can rounding numbers to a certain number of decimals using `toFixed` method from native javascript.
     ```javascript
     let pie = 3.141592653;
     pie = pie.toFixed(3); // 3.142
     ```

     **[⬆ Back to Top](#table-of-contents)**

364. ### What is the easiest way to convert an array to an object?
     You can convert an array to an object with the same data using spread(...) operator.
     ```javascript
     var fruits = ["banana", "apple", "orange", "watermelon"];
     var fruitsObject = {...fruits};
     console.log(fruitsObject); // {0: "banana", 1: "apple", 2: "orange", 3: "watermelon"}
     ```

     **[⬆ Back to Top](#table-of-contents)**

365. ### How do you create an array with some data?
     You can create an array with some data or an array with the same values using `fill` method.
     ```javascript
     var newArray = new Array(5).fill("0");
     console.log(newArray); // ["0", "0", "0", "0", "0"]
     ```

     **[⬆ Back to Top](#table-of-contents)**

366. ### What are the placeholders from console object?
     Below are the list of placeholders available from console object,
     1. %o — It takes an object,
     2. %s — It takes a string,
     3. %d — It is used for a decimal or integer
     These placeholders can be represented in the console.log as below
     ```javascript
     const user = { "name":"John", "id": 1, "city": "Delhi"};
     console.log("Hello %s, your details %o are available in the object form", "John", user); // Hello John, your details {name: "John", id: 1, city: "Delhi"} are available in object
     ```

     **[⬆ Back to Top](#table-of-contents)**

367. ### Is it possible to add CSS to console messages?
     Yes, you can apply CSS styles to console messages similar to html text on the web page.
     ```javascript
     console.log('%c The text has blue color, with large font and red background', 'color: blue; font-size: x-large; background: red');
     ```
     The text will be displayed as below,

     ![Screenshot](images/console-CSS.png)
     **Note:** All CSS styles can be applied to console messages.

     **[⬆ Back to Top](#table-of-contents)**

368. ### What is the purpose of dir method of console object?
     The `console.dir()` is used to display an interactive list of the properties of the specified JavaScript object as JSON.
     ```javascript
     const user = { "name":"John", "id": 1, "city": "Delhi"};
     console.dir(user);
     ```
     The user object displayed in JSON representation
     ![Screenshot](images/console-css.png)

     **[⬆ Back to Top](#table-of-contents)**

369. ### Is it possible to debug HTML elements in console?
     Yes, it is possible to get and debug HTML elements in the console just like inspecting elements.
     ```javascript
     const element = document.getElementsByTagName("body")[0];
     console.log(element);
     ```
     It prints the HTML element in the console
     ![Screenshot](images/console-html.png)

     **[⬆ Back to Top](#table-of-contents)**

370. ### How do you display data in a tabular format using console object?
     The `console.table()` is used to display data in the console in a tabular format to visualize complex arrays or objects.
     ```javascript
     const users = [{ "name":"John", "id": 1, "city": "Delhi"},
                   { "name":"Max", "id": 2, "city": "London"},
                   { "name":"Rod", "id": 3, "city": "Paris"}];
     console.table(users);
     ```
     The data visualized in a table format
     ![Screenshot](images/console-table.png)
     **Not:** Remember that `console.table()` is not supported in IE.

     **[⬆ Back to Top](#table-of-contents)**

371. ### How do you verify that an argument is a Number or not?
     The combination of IsNaN and isFinite methods are used to confirm whether an argument is a number or not.
     ```javascript
     function isNumber(n){
         return !isNaN(parseFloat(n)) && isFinite(n);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

372. ### How do you create copy to clipboard button?
     You need to select the content(using .select() method) of input element and execute the copy command with execCommand (i.e, execCommand('copy')). You can also execute another system commands like cut and paste.
     ```javascript
     document.querySelector("#copy-button").onclick = function() {
       // Select the content
       document.querySelector("#copy-input").select();
       // Copy to the clipboard
       document.execCommand('copy');
     };

     ```

     **[⬆ Back to Top](#table-of-contents)**

373. ### What is the shortcut to get timestamp?
     You can use `new Date().getTime()` to get the current timestamp. There is an alternative shortcut to get the value.
     ```javascript
     console.log(+new Date());
     console.log(Date.now());
     ```

     **[⬆ Back to Top](#table-of-contents)**

374. ### How do you flattening multi dimensional arrays?
     Flattening bi-dimensional arrays is trivial with Spread operator.
     ```javascript
     const biDimensionalArr = [11, [22, 33], [44, 55], [66, 77], 88, 99];
     const flattenArr = [].concat(...biDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
     ```
     But you can make it work with multi-dimensional arrays by recursive calls,

     ```javascript
     function flattenMultiArray(arr) {
         const flattened = [].concat(...arr);
         return flattened.some(item => Array.isArray(item)) ? flattenMultiArray(flattened) : flattened;
      }
     const multiDimensionalArr = [11, [22, 33], [44, [55, 66, [77, [88]], 99]]];
     const flatArr = flattenMultiArray(multiDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
     ```

     **[⬆ Back to Top](#table-of-contents)**

375. ### What is the easiest multi condition checking?

     You can use `indexOf` to compare input with multiple values instead of checking each value as one condition.
     ```javascript
     // Verbose approach
     if (input === 'first' || input === 1 || input === 'second' || input === 2) {
       someFunction();
     }
     // Shortcut
     if (['first', 1, 'second', 2].indexOf(input) !== -1) {
       someFunction();
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

376. ### How do you capture browser back button?
     The `window.onbeforeunload` method is used to capture browser back button event. This is helpful to warn user about loosing the current data.
     ```javascript
     window.onbeforeunload = function() {
     	alert("You work will be lost");
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

377. ### How do you disable right click in the web page?
     The right click on the page can be disabled by returning false from `oncontextmenu` attribute on body element.
     ```html
     <body oncontextmenu="return false;">
     ```

     **[⬆ Back to Top](#table-of-contents)**

378. ### ?

     **[⬆ Back to Top](#table-of-contents)**

379. ### ?

     **[⬆ Back to Top](#table-of-contents)**

380. ### ?

     **[⬆ Back to Top](#table-of-contents)**

381. ### ?

     **[⬆ Back to Top](#table-of-contents)**

382. ### ?

     **[⬆ Back to Top](#table-of-contents)**

383. ### ?

     **[⬆ Back to Top](#table-of-contents)**

384. ### ?

     **[⬆ Back to Top](#table-of-contents)**

385. ### ?

     **[⬆ Back to Top](#table-of-contents)**

386. ### ?

     **[⬆ Back to Top](#table-of-contents)**

387. ### ?

     **[⬆ Back to Top](#table-of-contents)**

388. ### ?

     **[⬆ Back to Top](#table-of-contents)**

389. ### ?

     **[⬆ Back to Top](#table-of-contents)**

390. ### ?

     **[⬆ Back to Top](#table-of-contents)**

391. ### ?

     **[⬆ Back to Top](#table-of-contents)**

392. ### ?

     **[⬆ Back to Top](#table-of-contents)**


| No. | Questions |
|---- | ---------
|  | [What is JavaScript?](#ques-What-is-JavaScript) |




1	What is JavaScript?
1	What is an ECMAScript?
2	Difference between Java and JavaScript?
3	JavaScript Data Type?
5	What is the javaScript Variable?
difference between var and Let?
What is Operate in javascript?
What is the javaScript Comment?
What is the difference between the operators '==' and '==='?
What is cookies?
What is Local Storage?
What is Session Storage?
What is JavaScript Function?
What is JavaScript Object?
What are the possible ways to create objects in javascript?
What are lambda or arrow functions?
What is currying function?
What is Generator function?
What is a proxy object?
What is the Array slice() Method?
What is the Array splice() Method?
What is the difference between slice & splice?
How do you combine two or more arrays?
What is the Array filter() Method?
What is the Array push() Method?
What is the Array pop() Method?
What is the Array shift() Method?
What is the Array unshift() Method?
What is the Array sort() Method?
What is the Array reverse() Method?
What is the Array concat() Method?
What is the Array join() Method?
What is the Array isArray() Method?
What is the Array indexOf() Method?
What is the Array lastIndexOf() Method?
What is the Array entries() Method?
What is the Array every() Method?
What is the Array filter() Method?
What is the Array find() Method?
What is the Array findindex() Method?
What is the Array includes() Method?
What is the Array some() Method?
What is the Array forEach() Method?
What is the Array toString() Method?
What is the Array valueOf() Method?
What is the Array fill() Method?

### Ques. What is JavaScript?
__Ans.__
* JavaScript is a Client-side as well as server side scripting language that can be inserted into HTML pages. JavaScript is also an object based Programming language.
* JavaScript is the programming language of HTML and the Web.
* JavaScript was created by Brendan Eich in September 1995.
* JavaScript is a case sensitive language.
* Netscape is the software company who developed JavaScript.

**[⬆ Back to Top](#table-of-contents)**
### Ques. What is an ECMAScript?
__Ans.__ ECMAScript (European Computer Manufacturers Association) Script is a specification for the scripting language standards. It has standardized Javascript which made Javascript the best implementation of ECMAScript.

**[⬆ Back to Top](#table-of-contents)**
###Ques. Difference between Java and JavaScript?
__Ans.__

Java	JavaScript
Java is an OOP Programming Language.	javaScript is an OOP scripting language.
It creates applications that run in a virtual machine or browser.	The code is run on a browser only.
Java code needs to be compiled.	JavaScript code are all in the form of text.
⬆ Back to Top

Ques. JavaScript Data Type?
Ans. JavaScript variables can hold many data types.

There are 7 primitive types: string, number, bigint, boolean, symbol, null and undefined.

String:– Represents single-character, multi-character, and alphanumeric values
let str = "Hello";
var a = 'Hi there!';  // using single quotes
var b = "Hi there!";  // using double quotes
var a = "Let's have a cup of coffee."; //single quote inside double quotes
var b = 'He said "Hello" and left.';  //double quotes inside single quotes
var c = 'We\'ll never give up.';     //escaping single quote with backslash
Number:– Represents both integer and floating point values
var a = 25;         // integer
var b = 80.5;       // floating-point number
var c = 4.25e+6;    // exponential notation, same as 4.25e6 or 4250000
var d = 4.25e-6;    // exponential notation, same as 0.00000425
Boolean:– Represents true and false values
var isReading = true;   // yes, I'm reading
var isSleeping = false; // no, I'm not sleeping

var a = 2, b = 5, c = 10; 
alert(b > a) // Output: true
alert(b > c) // Output: false
Null:– Represents empty, nothing, and unknown type of values
var a = null;
alert(a); // Output: null 
var b = "Hello World!"
alert(b); // Output: Hello World! 
b = null;
alert(b) // Output: null
Object:– Used for storing collections of data or more complex entities
var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};
Symbol – Used for creating unique identifiers for objects
Undefined – Represents value not assigned. If a variable is only declared and not assigned in JS, then it represents the undefined data type
⬆ Back to Top

Ques. What is the javaScript Variable?
Ans.

A javaScript Variable is simply a name of storage location. There are 2 types of variable in javaScript.
There are some rules with declaring a javascript varible.
Name must start with a letter(a to z or A to Z), underscore (_), or dollar ( $ ) sign.
After the first letter we can use digit (0 to 9), for example value1.
JavaScript variable are case sensitive, for example x and X are diffrent
We can declare variables to store data by using the var, let, or const keywords.
javaScript includes variables which hold the data value and it can be changed anytime.
To create a variable in JavaScript, use the let keyword.
Variables named apple and AppLE are two different variables.
⬆ Back to Top

Ques. Difference between var and let?
Ans.

Var	let
It has a global/function scope.	It is limited to block scope.
It can be declared globally and can be accessed globally.	It can be declared globally but cannot be accessed globally.
It is hoisted.	It is not hoisted.
Variable declared with var keyword can be re-declared and updated in the same scope.	Variable declared with let keyword can be updated but not re-declared.
Example:	
function varGreeter(){ 
var a = 10;
 var a = 20; //a is replaced
 console.log(a);
 } 
varGreeter();
Example: 
function varGreeter(){ 
let a = 10; 
let a = 20; //SyntaxError: 
//Identifier 'a' has already been declared console.log(a);
 } 
varGreeter();
Variables will be hoisted
Hoisted but not initialized

let message;
message = 'Hello!';
alert(message); // shows the variable content

let user = 'John', age = 25, message = 'Hello';   //We can also declare multiple variables in one line:

A real-life analogy:-

let message;
message = 'Hello!';
message = 'World!'; // value changed
alert(message);  //World

let hello = 'Hello world!';
let message;  // copy 'Hello world' from hello into message
message = hello;// now two variables hold the same data
alert(hello); // Hello world!
alert(message); // Hello world!

Variable naming:-
There are two limitations on variable names in JavaScript:
The name must contain only letters, digits, or the symbols $ and _.
The first character must not be a digit.
⬆ Back to Top

Ques. What is Operate in javascript?
Ans.

Arithmetic Operators:- Addition(+), Subtraction(-), Multiplication(*), Exponentiation (ES2016)(**), Division(/), Modulus(Division Remainder)(%), Increment(++), Decrement(--).

Assignment Operators:-

Comparison Operators:-

⬆ Back to Top

Ques. What is the use of a Map object in JavaScript?
Ans.

Map is a collection of keyed data items, just like an object. But the main difference is that map allows keys of any type.
Map – is a collection of keyed values.
The JavaScript Map object is used to map keys to values. It stores each element as key-value pair. It operates the elements such as search, update and delete on the basis of specified key.
new Map() – creates the map.
map.set(key, value) – stores the value by the key.
map.get(key) – returns the value by the key, undefined if key doesn’t exist in map.
map.has(key) – returns true if the key exists, false otherwise.
map.delete(key) – removes the value by the key.
map.clear() – removes everything from the map.
map.size – returns the current element count.
let map = new Map();

map.set('1', 'str1');   // a string key
map.set(1, 'num1');     // a numeric key
map.set(true, 'bool1'); // a boolean key

// remember the regular Object? it would convert keys to string
// Map keeps the type, so these two are different:
alert( map.get(1)   ); // 'num1'
alert( map.get('1') ); // 'str1'
alert( map.size ); // 3

function display()  
{  
var map=new Map();    
map.set(1,"jQuery");    
map.set(2,"AngularJS");    
map.set(3,"Bootstrap");    
document.writeln(map.get(1)+"<br>");    
document.writeln(map.get(2)+"<br>");    
document.writeln(map.get(3));    
}  
display(); 
⬆ Back to Top

Ques. What is the use of a WeakMap object in JavaScript?
Ans. The JavaScript WeakMap object is a type of collection which is almost similar to Map. It stores each element as a key-value pair where keys are weakly referenced. Here, the keys are objects and the values are arbitrary values. For example:

function display()  
{  
var wm = new WeakMap();    
var obj1 = {};    
var obj2 = {};    
var obj3= {};    
wm.set(obj1, "jQuery");    
wm.set(obj2, "AngularJS");    
wm.set(obj3,"Bootstrap");    
document.writeln(wm.has(obj2));     
}     
display();  
⬆ Back to Top

Ques. What is the use of a Set object in JavaScript?
Ans.

A set is a collection of items which are unique i.e no element can be repeated.
A Set is a special type collection – “set of values” (without keys), where each value may occur only once.
Set – is a collection of unique values.
new Set(iterable) – creates the set, and if an iterable object is provided (usually an array), copies values from it into the set.
set.add(value) – adds a value, returns the set itself.
set.delete(value) – removes the value, returns true if value existed at the moment of the call, otherwise false.
set.has(value) – returns true if the value exists in the set, otherwise false.
set.clear() – removes everything from the set.
set.size – is the elements count.
⬆ Back to Top

Ques. What is the javaScript Comment?
Ans. Single Line Comment:- Single line comment start with //

Multi-Line Comments:- Multi-Line comment start with /* and end with */

⬆ Back to Top

Ques. What is the difference between the operators '==' and '==='?
Ans. The operator '==' compares the value; whereas, the operator '===' compares both value and type.

⬆ Back to Top

Ques. What is cookies?
Ans. Php cookie is a small piece of information, which is stored on the client browser. Cookies are saved as key/value pairs.

Syntex:- document.cookie = "key1 = value1; key2 = value2; expires = date";

Example:-

document.cookie = "username=John Doe; expires=Thu, 18 Dec 2013 12:00:00 UTC; path=/";
Delete Cookie:- To delete a cookie, you just need to set the value of the cookie to empty and set the value of expires to a passed date.

Two Types Of Cookie:-

1. Persistent Cookie:- A persistent cookie is a cookie which is store information for certain time in a browser. By default cookie are temporary and are erased if we close the browser.

2. Non Persistent Cookie:- Non persistent cookies are stored in ram on the server. Ex:- login

Why do you need a Cookie?
Cookies are used to remember information about the user profile(such as username). It basically involves two steps,
When a user visits a web page, user profile can be stored in a cookie.
Next time the user visits the page, the cookie remembers user profile.
⬆ Back to Top

Ques. What is Local Storage in JavaScript?
Ans.

The local storage is a read only Property of window object.
It stores the data in a web browser specifically to the domain and protocol.
It does not get sent to the server as it is stored locally in the web browser with no expiration date.
The data will not be deleted when the browser is closed and reopened and will be available the next day, week or year.
Methods

1. setItem(key, value):- It allows to add a key/value pair to the storage obj. if the key already exists, the name value will overwrite the old value.

2. getItem(Key):- It returns the value of the item that is set with the given key.

3. key(n):- It returns the key of the item in the storage obj at the nth index which can be useful for looping.

4. removeItem(key):- It removes the item in the storage object with the given key.

window.localStorage.setItem("user","mohit");
window.localStorage.setItem("email","mksaxena27@gmail.com");
console.log(localStorage);
console.log(localStorage.length)		//2
console.log(localStorage.getItem('email'))	//mksaxena27@gmail.com
console.log(localStorage.key(0))		//email
localStorage.removeItem('email')		//email delete ho gaya
localStorage.clear()				// all localstorage clear
⬆ Back to Top

Ques. What is Session Storage in JavaScript?
Ans.

The session storage read only property of window object.
It store data in web browser specifically to the domain and protocol for a particular session.
It does not get sent to the server.
Data stored in session storage gets cleared when the page session ends.
A page session lasts for as long as the browser is open and survives over page reload and restore.
Q27. What is the difference between Local storage & Session storage?

Local Storage – The data is not sent back to the server for every HTTP request (HTML, images, JavaScript, CSS, etc) – reducing the amount of traffic between client and server. It will stay until it is manually cleared through settings or program.
Session Storage – It is similar to local storage; the only difference is while data stored in local storage has no expiration time, data stored in session storage gets cleared when the page session ends. Session Storage will leave when the browser is closed.

What is the main difference between localStorage and sessionStorage?
LocalStorage is same as SessionStorage but it persists the data even when the browser is closed and reopened(i.e it has no expiration time) whereas in sessionStorage data gets cleared when the page session ends.
⬆ Back to Top

Ques. What is the difference between Local Storage and Session Storage?
Ans. Local Storage will stay until it is manually cleared through settings or program.

Session Storage will leave when the browser is closed.

⬆ Back to Top

Ques. What is javascript Closure?
Ans.

Closure means that an inner function always has access to the vars and parameters of its outer function, even after the outer function has returned.
The closure is a function having access to the parent scope. It preserve the data from outside.
A closure is an inner function that has access to the outer (enclosing) function’s varibale.
For every closure we have 3 scopes:-

Local Scope
Outer scope:- jab hum ek function ke andar dusra function banate hai.(pahla function outer hota hai aur uske andar wale function ko inner functio)
Global scope
function OuterFunction() 
{ 
var outerVariable = 1; 
function InnerFunction() {
 alert(outerVariable); 
}
 InnerFunction();
 }
⬆ Back to Top

Ques. When to use Closure?
Ans. Closure is useful in hiding implementation detail in JavaScript. In other words, it can be useful to create private variables or functions.

⬆ Back to Top

Ques. What is JavaScript Function?
Ans.

A JavaScript function is a block of code designed to perform a particular task.
You can reuse code: Define the code once, and use it many times.
You can use the same code many times with different arguments, to produce different results.
⬆ Back to Top

Ques. What is JavaScript Object?
Ans.

An object can be created with curly brackets { } with an optional list of properties.
A property is a “Key:value” pair, where the key (or property name) is always a string, and value (or property value) can be any data type, like string, number, boolean or complex data type like array, function, and other objects.
⬆ Back to Top

Ques. What are the possible ways to create objects in javascript?
Ans.

Object constructor:- var object = new Object();
Object’s crate method:- var object = Object.create(null);
Object literal syntex:- var object = {};
Function Constructor:-
Function constructor with prototype:-
ES6 class Syntex:-
Singleton pattern:-
Accessing object:- var book = { "name": "Harry Potter and the Goblet of Fire", "author": "J. K. Rowling", "year": 2000 }; document.write(book.author); // Prints: J. K. Rowling document.write(book["year"]); // Prints: 2000

Setting object:- var person = { name: "Peter", age: 28, gender: "Male" }; // Setting a new property person.country = "United States"; document.write(person.country); // Prints: United States

Deleting object:- var person = { name: "Peter", age: 28, gender: "Male", displayName: function() { alert(this.name); } }; // Deleting property delete person.age; alert(person.age); // Outputs: undefined

⬆ Back to Top

Ques. What are lambda or arrow functions?
Ans. An arrow function is a shorter syntex for a function.

⬆ Back to Top

Ques. What is currying function?
Ans.

Currying is a technique of evaluating function with multiple arguments, into sequence of function with single argument.
Currying is a transformation of functions that translates a function from callable as f(a, b, c) into callable as f(a)(b)(c).
Currying is an advanced technique of working with functions. It’s used not only in JavaScript, but in other languages as well.
Currying helps you to avoid passing the same variable again and again.
function curry(f) { // curry(f) does the currying transform
  return function(a) {
    return function(b) {
      return f(a, b);
    };
  };
}

// usage
function sum(a, b) {
  return a + b;
}

let curriedSum = curry(sum);

alert( curriedSum(1)(2) ); // 3


A partial invocation of a Javascript function is called Currying. Few arguments of a function are processed and a function is returned. Few more arguments are added by the returning function.


What is currying function?
Currying is the process of taking a function with multiple arguments and turning it into a sequence of functions each with only a single argument. Currying is named after a mathematician Haskell Curry. By applying currying, a n-ary function turns it into a unary function. Let's take an example of n-ary function and how it turns into a currying function
const multiArgFunction = (a, b, c) => a + b + c;
const curryUnaryFunction = a => b => c => a + b + c;
curryUnaryFunction (1); // returns a function: b => c =>  1 + b + c
curryUnaryFunction (1) (2); // returns a function: c => 3 + c
curryUnaryFunction (1) (2) (3); // returns the number 6
Curried functions are great to improve code re-usability and functional composition.
⬆ Back to Top

Ques. What is Generator function?
Ans.

Generators are a special class of functions that simplify the task of writing iterators.
A generator is a function that produces a sequence of results instead of a single value, i.e you generate ​a series of values.
Regular functions return only one, single value (or nothing).
Generators can return (“yield”) multiple values, one after another, on-demand.


Syntax
function* name([param[, param[, ... param]]]) {
   statements
}

Generators are created by generator functions function* f(…) {…}.
⬆ Back to Top

Ques. What is the difference between write and writeln?
Ans. write and writeln are the same function. The only difference is that writeln adds a new line at the end of the text. writeln adds a \n character to the end of the string

document.write("Hello World!");
document.write("Have a nice day!"); 
output:- //Hello World!Have a nice day!

document.writeln("Hello World!");
document.writeln("Have a nice day!"); 
Output:- //Hello World!
	//Have a nice day!
⬆ Back to Top

Ques. What is JavaScript Math Object?
Ans. The JavaScript Math object allows you to perform mathematical tasks on a number.

Math.round(x) returns the value of x rounded to its nearest integer:
<p id="demo"></p>
<script>
document.getElementById("demo").innerHTML = Math.round(4.4);
</script>

Math.pow(x, y) returns the value of x to the power of y:
Math.pow(8, 2);      // returns 64

Math.sqrt(x) returns the square root of x:
Math.sqrt(64);      // returns 8

Math.abs(x) returns the absolute (positive) value of x:
Math.abs(-4.7);     // returns 4.7

Math.ceil(x) returns the value of x rounded up to its nearest integer:
Math.ceil(4.4);     // returns 5

Math.floor(x) returns the value of x rounded down to its nearest integer:
Math.floor(4.7);    // returns 4

Math.sin(x) returns the sine (a value between -1 and 1) of the angle x (given in radians).
If you want to use degrees instead of radians, you have to convert degrees to radians:
Angle in radians = Angle in degrees x PI / 180.
Math.sin(90 * Math.PI / 180);     // returns 1 (the sine of 90 degrees)
 
Math.cos(x) returns the cosine (a value between -1 and 1) of the angle x (given in radians).
If you want to use degrees instead of radians, you have to convert degrees to radians:
Angle in radians = Angle in degrees x PI / 180.
Math.cos(0 * Math.PI / 180);     // returns 1 (the cos of 0 degrees)
Math.min() and Math.max() can be used to find the lowest or highest value in a list of arguments:
		Math.min(0, 150, 30, 20, -8, -200);  // returns -200
		Math.max(0, 150, 30, 20, -8, -200);  // returns 150


Math.random() returns a random number between 0 (inclusive), and 1 (exclusive):
Math.random();     // returns a random number

Math.random() used with Math.floor() can be used to return random integers.
Math.floor(Math.random() * 10);     // returns a random integer from 0 to 9
Math.floor(Math.random() * 101);     // returns a random integer from 0 to 100
Math.floor(Math.random() * 10) + 1;  // returns a random integer from 1 to 10

<button onclick="document.getElementById('demo').innerHTML = getRndInteger(1,10)">Click Me</button>
<p id="demo"></p>
<script>
function getRndInteger(min, max) {
  return Math.floor(Math.random() * (max - min + 1) ) + min;
}
</script>

function getRndInteger(min, max) {
  return Math.floor(Math.random() * (max - min + 1) ) + min;
}
⬆ Back to Top

Ques. What is Proxy object?
Ans.

A Proxy object wraps another object and intercepts operations.
Proxy is an object in javascript which wraps an object or a function and monitors it via something called target.
Proxy is a wrapper around an object, that forwards operations on it to the object, optionally trapping some of them.
It can wrap any kind of object, including classes and functions.
Syntex

let proxy = new Proxy(target, handler)
What is a proxy object?
The Proxy object is used to define custom behavior for fundamental operations such as property lookup, assignment, enumeration, function invocation, etc. The syntax would be as follows,
var p = new Proxy(target, handler);
Let's take an example of proxy object,
var handler = {
    get: function(obj, prop) {
        return prop in obj ?
            obj[prop] :
            100;
    }
};

var p = new Proxy({}, handler);
p.a = 10;
p.b = null;

console.log(p.a, p.b); // 1, null
console.log('c' in p, p.c); // false, 100
In the above code, it uses get handler which define the behavior of the proxy when an operation is performed on it
⬆ Back to Top

Ques. What is Promise?
Ans.

A promise is an object that may produce a single value some time in the future.

Promises are used to handle asynchronous operations in JavaScript. They are easy to manage when dealing with multiple asynchronous operations where callbacks can create callback hell leading to unmanageable code.

fulfilled: Action related to the promise succeeded

rejected: Action related to the promise failed

pending: Promise is still pending i.e not fulfilled or rejected yet*

settled: Promise has fulfilled or rejected

Syntex:-
var promise = new Promise(function(resolve, reject){
     //do something
});
What is promise chaining?
The process of executing a sequence of asynchronous tasks one after another using promises is known as Promise chaining. Let's take an example of promise chaining for calculating the final result,
new Promise(function(resolve, reject) {

  setTimeout(() => resolve(1), 1000);

}).then(function(result) {

  console.log(result); // 1
  return result * 2;

}).then(function(result) {

  console.log(result); // 2
  return result * 3;

}).then(function(result) {

  console.log(result); // 6
  return result * 4;

});
In the above handlers, the result is passed to the chain of .then() handlers with the below work flow,
The initial promise resolves in 1 second,
After that .then handler is called by logging the result(1) and then return a promise with the value of result * 2.
After that the value passed to the next .then handler by logging the result(2) and return a promise with result * 3.
Finally the value passed to the last .then handler by logging the result(6) and return a promise with result * 4.
⬆ Back to Top
What is promise.all?
Promise.all is a promise that takes an array of promises as an input (an iterable), and it gets resolved when all the promises get resolved or any one of them gets rejected. For example, the syntax of promise.all method is below,
Promise.all([Promise1, Promise2, Promise3]) .then(result) => {   console.log(result) }) .catch(error => console.log(`Error in promises ${error}`))
Note: Remember that the order of the promises(output the result) is maintained as per input order.
⬆ Back to Top
What is the purpose of race method in promise?
Promise.race() method will return the promise instance which is firstly resolved or rejected. Let's take an example of race() method where promise2 is resolved first
var promise1 = new Promise(function(resolve, reject) {
    setTimeout(resolve, 500, 'one');
});
var promise2 = new Promise(function(resolve, reject) {
    setTimeout(resolve, 100, 'two');
});

Promise.race([promise1, promise2]).then(function(value) {
  console.log(value); // "two" // Both promises will resolve, but promise2 is faster
});

==========
Ques:- What are the pros and cons of promises over callbacks?
Below are the list of pros and cons of promises over callbacks, Pros:
It avoids callback hell which is unreadable
Easy to write sequential asynchronous code with .then()
Easy to write parallel asynchronous code with Promise.all()
Solves some of the common problems of callbacks(call the callback too late, too early, many times and swallow errors/exceptions)
Cons:
It makes little complex code
You need to load a polyfill if ES6 is not supported
⬆ Back to Top

Ques. What is the Array slice() Method?
Ans.

The slice() method returns the selected elements in array, as a new array object.
The slice() method selects the elements starting at the given start argument, and ends at, but does not include, the given end argument.
let arrayIntegers = [1, 2, 3, 4, 5,6];
let arrayIntegers1 = arrayIntegers.slice(0,2); // returns [1,2]
let arrayIntegers2 = arrayIntegers.slice(2,3); // returns [3]
let arrayIntegers3 = arrayIntegers.slice(4); //returns [5,6]
We made 2 objects called target and handler, target is a simple object with a message key and handler is an object that has a get key with a function associated with it.

⬆ Back to Top

Ques. What is the Array splice() Method?
Ans. The splice() method adds/removes items to/from an array, and returns the remove items(s).

Syntex:- array.aplice(index, remove_count, item1,item2, ....., itemX);

Example:- 1st position mtb add karna 2nd position mtb delete ho jana.

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.splice(2, 0, "Lemon", "Kiwi");
document.write(fruits);  // Banana,Orange,Lemon,Kiwi,Apple,Mango

var fruits = ["Banana", "Orange", "Apple", "Mango","mohit"];
fruits.splice(2, 2);		// dusri position sa 2 delete ho jaye. 
document.write(fruits); //	Banana,Orange,mohit

let arrayIntegersOriginal1 = [1, 2, 3, 4, 5];
let arrayIntegers1 = arrayIntegersOriginal1.splice(0,2); // returns [1, 2]; original array: [3, 4, 5]

let arrayIntegersOriginal2 = [1, 2, 3, 4, 5];
let arrayIntegers2 = arrayIntegersOriginal2.splice(3); // returns [4, 5]; original array: [1, 2, 3]

let arrayIntegersOriginal3 = [1, 2, 3, 4, 5];
let arrayIntegers3 = arrayIntegersOriginal3.splice(3, 1, "a", "b", "c"); //returns [4]; original array: [1, 2, 3, "a", "b", "c", 5]
⬆ Back to Top

Ques. What is the difference between slice & splice?
Ans.

slice()	splice()
Does not modify the original array(immutable)	Modifies the original array(mutable)
Returns the subset of original array	Return the delete element as array
Used to pick the element from array	Used to insert or delete elements to/from array.
⬆ Back to Top

Ques. How do you combine two or more arrays?
Ans. The concat() method is used to join two or more arrays by returning a new array containing all the elements.

Syntex:- array1.concat(array2, array3, ..., arrayX)

var veggies = ["Tomato", "Carrot", "Cabbage"];
var fruits = ["Apple", "Orange", "Pears"];
var veggiesAndFruits = veggies.concat(fruits);
console.log(veggiesAndFruits); // Tomato, Carrot, Cabbage, Apple, Orange, Pears
⬆ Back to Top

Ques. What is the Array filter() Method?
Ans. The filter() method creates an array filled with all array elements that pass a test (provided as a function).

Note: filter() does not execute the function for array elements without values.

Note: filter() does not change the original array.

Syntex:- array.filter(function(currentValue, index, arr), thisValue)

<button onclick="myFunction()">Try it</button>
<p id="demo"></p>
<script>
var ages = [32, 33, 16, 40];
function checkAdult(age) {
  return age >= 18;
}
function myFunction() {
  document.getElementById("demo").innerHTML = ages.filter(checkAdult);
}
</script>
⬆ Back to Top

Ques. What is the Array push() Method?
Ans. The push() method adds new items to the end of an array, and returns the new length.

Syntex:- array.push(item1, item2, ..., itemX)

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.push("Kiwi","Mango");
document.write(fruits);
⬆ Back to Top

Ques. What is the Array pop() Method?
Ans. The pop() method removes the last element of an array, and returns that element.

Syntex:- array.pop()

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.pop();
document.write(fruits);
⬆ Back to Top

Ques. What is the Array shift() Method?
Ans. The shift() method removes the first item of an array.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.shift();
document.write(fruits);	//Orange,Apple, Mango
⬆ Back to Top

Ques. What is the Array unshift() Method?
Ans. The unshift() method adds new items to the beginning of an array, and returns the new length.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.unshift("Lemon", "Pineapple");
document.write(fruits); 	//Lemon,Pineapple,Banana,Orange,Apple,Mango
⬆ Back to Top

Ques. What is the Array sort() Method?
Ans. The sort() method sorts the items of an array.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.sort();
document.write(fruits);
⬆ Back to Top

Ques. What is the Array reverse() Method?
Ans. The reverse() method reverses the order of the elements in an array.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.reverse();
document.write(fruits);
⬆ Back to Top

Ques. What is the Array concat() Method?
Ans. The concat() method is used to join two or more arrays.

Example:-

var hege = ["Cecilie", "Lone"];
var stale = ["Emil", "Tobias", "Linus"];
var kai = ["Robin"];
var children = hege.concat(stale,kai); 
document.write(children);
⬆ Back to Top

Ques. What is the Array join() Method?
Ans. The join() method returns the array as a string.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
document.write(fruits.join(" and "));
⬆ Back to Top

Ques. What is the Array isArray() Method?
Ans.

⬆ Back to Top

Ques. What is the Array indexOf() Method?
Ans. The indexOf() method searches the array for the specified item, and returns its position.

Example:-

var fruits = ["Banana", "Orange", "Apple", "Mango"];
document.write(fruits.indexOf("Orange"));  	//1
⬆ Back to Top

Ques. What is the Array lastIndexOf() Method?
Ans. ⬆ Back to Top

Ques. What is the Array entries() Method ?
Ans. The entries() method returns an Array Iterator object with key/value pairs.

⬆ Back to Top

Ques. What is the Array every() Method?
Ans. The every() method checks if all elements in an array pass a test (provided as a function).[every() function check karta hai ki sari valu 18 sa badi hai to hi true aayega otherwise fale.]

var ages = [32, 33, 58, 40];
var b = ages.every(checkAdult);
document.write(b);

function checkAdult(age) {
  return age >= 18;
}
const isBelowThreshold = (currentValue) => currentValue < 40;
const array1 = [1, 30, 39, 29, 10, 13];
console.log(array1.every(isBelowThreshold));
// expected output: true
⬆ Back to Top

Ques. What is the Array filter() Method?
Ans.

⬆ Back to Top

Ques. What is the Array find() Method?
Ans. ⬆ Back to Top

Ques. What is the Array findindex() Method?
Ans.

⬆ Back to Top

Ques. What is the Array includes() Method?
Ans. includes() method check the value in the array.

The includes() method is case sensitive.

var fruits = ["Banana", "Orange", "Apple", "Mango"];
var n = fruits.includes("Mango");
document.write(n); //True
⬆ Back to Top

Ques. What is the Array some() Method?
Ans.

⬆ Back to Top

Ques. What is the Array forEach() Method?
Ans. ⬆ Back to Top

Ques. What is the Array toString() Method?
Ans. The toString() method returns a string with all the array values, separated by commas.

var arr = new Array("orange", "mango", "banana", "sugar");        
var str = arr.toString();
document.write("Returned string is : " + str );
⬆ Back to Top

Ques. What is the Array valueOf() Method?
Ans.

⬆ Back to Top

Ques. What is the Array fill() Method?
Ans.

⬆ Back to Top

Ques. Find the length of the array?
Ans.

var fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.length;   // the length of fruits is 4
⬆ Back to Top

Ques. Accessing the first Element of the Array?
Ans.

var fruits = ["Banana", "Orange", "Apple", "Mango"];
var first = fruits[0];
document.getElementById("demo").innerHTML = first;
⬆ Back to Top

Ques. Accessing the last Element of the Array?
Ans.

fruits = ["Banana", "Orange", "Apple", "Mango"];
var last = fruits[fruits.length - 1]; //Mango
⬆ Back to Top

Ques. Changing an Array Element?
Ans.

var cars = ["Saab", "Volvo", "BMW"];
cars[0] = "Opel";
document.getElementById("demo").innerHTML = cars[0]; //Opel,Volvo,BMW
⬆ Back to Top

Ques. JavaScript String Length function?
Ans. The length property returns the length of a string.

var txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
len = txt.length;
document.write(len);	//26
⬆ Back to Top

Ques. What is isNaN?
Ans. The isNaN() function is used to determine whether a value is an illegal number (Not-a-Number) or not. i.e, This function returns true if the value equates to NaN. Otherwise it returns false.

isNaN('Hello') //true
isNaN('100') //false
⬆ Back to Top

Ques. How do you disable right click in the web page?
Ans. The right click on the page can be disabled by returning false from oncontextmenu attribute on body element.

<body oncontextmenu="return false;">
⬆ Back to Top

Ques. How do you display data in a tabular format using console object?
Ans. The console.table() is used to display data in the console in a tabular format to visualize complex arrays or objects.

const users = [{ "name":"John", "id": 1, "city": "Delhi"},
              { "name":"Max", "id": 2, "city": "London"},
              { "name":"Rod", "id": 3, "city": "Paris"}];
console.table(users);
The data visualized in a table format Not: Remember that console.table() is not supported in IE.

⬆ Back to Top

Ques.
Ans.

⬆ Back to Top

Ques.
Ans. ⬆ Back to Top

Ques.
Ans.

Ques. What is the javaScript Value/syntex?
Ans. The javascript syntex defines 2 types of value: Fixed & varible values. 
Fixed values are called literals.
Variable values are called variables.

Ques. JavaScript Event?
Ans. onchange, onclick, onmouseover, onmouseout, onkeydown, onload


 
JavaScript Display Possibilities:-
Writing into an HTML element, using innerHTML.
Writing into the HTML output using document.write().
Writing into an alert box, using window.alert().
Writing into the browser console, using console.log().
 

JavaScript Type Conversion:-

Number() converts to a Number, String() converts to a String, Boolean() converts to a Boolean.

You can use the typeof operator to find the data type of a JavaScript variable.
typeof "John"                 // Returns "string"
typeof 3.14                   // Returns "number"
typeof NaN                    // Returns "number"
typeof false                  // Returns "boolean"
typeof [1,2,3,4]              // Returns "object"
typeof {name:'John', age:34}  // Returns "object"
typeof new Date()             // Returns "object"
typeof function () {}         // Returns "function"
typeof myCar                  // Returns "undefined" *
typeof null                   // Returns "object"



Recursion and stack:- 
A recursive function is a function that calls itself.

function pow(x, n) {
  if (n == 1) {
    return x;
  } else {
    return x * pow(x, n - 1);
  }
}
alert( pow(2, 3) ); //8





Ques. Difference between “undefined” and “NULL” keywords?
Ans. When you define a var but not assign any value. typeof(undefine)=> undefine 
         Null- manually done. typeof(null)=> object






JavaScript Array:- 
JavaScript arrays are used to store multiple values in a single variable.

<p id="demo"></p>
<script>
var cars = ["Saab", "Volvo", "BMW"];
(OR) 
var cars = new Array("Saab", "Volvo", "BMW");
document.getElementById("demo").innerHTML = cars;
</script>

Array are object:-
Arrays are a special type of objects. The typeof operator in JavaScript returns "object" for arrays.
But, JavaScript arrays are best described as arrays.
Arrays use numbers to access its "elements". In this example, person[0] returns John

var person = {firstName:"John", lastName:"Doe", age:46};

<script>
var person = {firstName:"John", lastName:"Doe", age:46};
document.getElementById("demo").innerHTML = person["firstName"];
</script>



Adding Array Elements:-
<button onclick="myFunction()">Try it</button>
<p id="demo"></p>
<script>
var fruits = ["Banana", "Orange", "Apple", "Mango"];
document.getElementById("demo").innerHTML = fruits;
function myFunction() {
  fruits.push("Lemon");
  document.getElementById("demo").innerHTML = fruits;
}
</script>





JavaScript Array Method





Ques. What is the use of isNaN Function ?
Ans. isNan function returns true if the argument is not a number otherwise it is false.
NaN is a short form of Not a Number.

Ques. Why Is Javascript called Richer Interface?
Ans. You can use JavaScript to include such items as drag-and-drop components and sliders to give a Rich Interface to your site visitors.

Ques. How to define anonymous functions ?
Ans. 
An anonymous function can be defined in a similar way as a normal function but it would not have any name.
An anonymous function allows a developer to create a function that has no name. In other words, anonymous functions can be used to store a bit of functionality in a variable and pass that piece of functionality around.

Ques. What is the difference between an Anonymous function and a named function?
Ans. Anonymous functions exist only after they are called; whereas, Named functions exist even if not called.


Which built-in method calls a function for each element in the array?
forEach method calls a function for each element in the array.

Which type of variable among global and local, takes precedence over other if names are same?
A local variable takes precedence over a global variable with the same name.



What is prototypal Inheritance?
Every object has a property called a prototype, where we can add methods to it and when you create another object from these the newly created object will automatically inherit its parent’s property.

What is SetTimeout()?
When you setTimeout it becomes asynchronous and it has to wait on the stack to get everything got finished

What is closure and how do you use it?
When a function returns the other function the returning function will hold its environment and this is known as closure.

Output of below statements
 
<script>
document.write({});
</script>
Output:- [object Object]

How can you move element in lowercase to uppercase from an array?
toUpperCase method returns the calling string value converted to upper case.





========================================
2 div ke number ko add karna
=========================================
<html>
<head>
<script src="jquery.min.js"></script>
<script src="jquery-1.9.1.min"></script>
</head>
<body>
<select id="od_boxe" onchange="GetSelectedValue(this)">
  <option value="1">1</option>
  <option value="2">2</option>
  <option value="3">3</option>
  <option value="4">4</option>
  <option value="5">5</option>
</select>
<select id="os_boxe" onchange="GetSelectedValue1(this)">
  <option value="3">3</option>
  <option value="2">2</option>
  <option value="3">3</option>
  <option value="4">4</option>
  <option value="5">5</option>
</select>
<script type="text/javascript">
$(function(){
  var os_boxes = os_boxe.value;
        var od_boxes  = od_boxe.value;
         var totalBox = parseInt(os_boxes) + parseInt(od_boxes);
        // alert(totalBox);
        if(totalBox<num)
        { 
        $("#combo").show();
        }
        else
        {
        $("#combo").hide();
        }
})
    var num = '5';
    function GetSelectedValue(od_boxe)
    {
        var os_boxes = os_boxe.value;
        var od_boxes  = od_boxe.value;
         
        var totalBox = parseInt(os_boxes) + parseInt(od_boxes);
        // alert(totalBox);
        if(totalBox<num)
        { 
        $("#combo").show();
        }
        else
        {
        $("#combo").hide();
        }
    }
    function GetSelectedValue1(os_boxe) {
        var os_boxes = os_boxe.value;
        var od_boxes  = od_boxe.value;
         
        var totalBox = parseInt(os_boxes) + parseInt(od_boxes);
        if(totalBox<num){ 
        $("#combo").show();
        }
        else
        {
        $("#combo").hide();
        }
    }
</script>

<div id="combo"> frefrere</div>
</body>
</html>


Many button value in a text field

<input type="text" id="pressed" value="" />
<li><button class="number-button" type="button" value="1.00">$1.00</button></li>
<li><button class="number-button" type="button" value="5.00">$5.00</button></li>

<script type="text/javascript">
  $("button.number-button").click(function() {
    var val = $(this).val();
    $("#pressed, #total-val").val(val);
  });
</script>




2) Are Attributes and Property the same?
No. Attributes are something that can give more details on an element like id, type, value etc. Whereas, Property is the value assigned to the property like type="text", value='Name' etc.

3) List out the different ways an HTML element can be accessed in a Javascript code.
Here are the list of ways an HTML element can be accessed in a Javascript code,
(i) getElementById('idname'): Gets an element by its ID name
(ii) getElementsByClass('classname'): Gets all the elements that have the given classname.
(iii) getElementsByTagName('tagname'): Gets all the elements that have the given tag name.
(iv) querySelector(): This function takes css style selector (like #id/.classname/tagname) and returns the first selected element.
(v) querySelectorAll(): Similar to querySelector, this function returns a NodeList of html elements.

4) In how many ways a Javascript code can be involved in an HTML file?
The Javascript code can be involved in 3 ways (i) Inline (ii) Internal (iii) External
5) What are the new ways to define a variable in Javascript?
There are three possible ways of defining a variable in Javascript (i) var (which is used from the beginning) (ii) const (iii) let. The last two ways are the latest ways of defining a variable and are introduced in ES-2015(ES6 version).

6) What is a Typed Language?
Typed Language is in which the values are associated with values and not with variables. It is of two types:
Dynamically: in this, the variable can hold multiple types; like in JS a variable can take number, chars.
Statically: in this, the variable can hold only one type, like in Java a variable declared of string can take only set of characters and nothing else.
NOTE: Typescript is a superset of JS which is of typed language.

7) What does a typeof operator do?
The operator typeof gives the type of a variable/data available in it. The typeof operator can be used on Reference data types also.
You might want to explore: Top 40 Spring Interview Questions and Answers (Updated for 2018)
8) Name some of the ways in which Type Conversion is possible.
Type Conversion is to convert from one data type to another data type.
(i) Number to String Conversion.
toString: Other data type to String.
val = (5).toString(); converts integer to string.
val = (true).toString(); converts boolean to string.
Convert from Number/Boolean/Date to String.
Number to String: String(9) converts num to string
Boolean to String: String(true) converts bool to str
Date to String: String(new Date()) date to string
Array to String: String([2,2,2]) Array to string.
(ii) String to Number Conversion.
parseInt: String to Int only (no decimals)
val = parseInt('11'); outputs 100 as number
val = parseFloat('22.22') outputs 22.22 as float
Convert from String/Boolean to Number/Date.
String to Number: Number('9') converts str - num
(9).toFixed(4) gives 9.0000 as the output
Boolean to Number: Number(true) converts to no.
Null to Number: Number(null) converts to no. (0)
Chars to Number: Number('ss') give NaN.

10) What is the difference between the keywords var and let?
The keyword var is from the beginning of Javascript; whereas, let is introduced in ES2015/ES6. The keyword let has a block scope; whereas, the keyword var has a functional scope.

12) What is the difference between null and undefined?
When used the typeof operator on null; i.e., typeof(null), the value is an object. Whereas, when used the typeof operator on undefined; i.e., typeof(undefined), the value would be undefined.
13) Are Javascript and JScript the same?
No, Javascript was provided by Netscape; whereas, JScript was provided by Microsoft.
14) Are Typescript and Javascript the same?
Typescript is not the next version of Javascript but is developed by Microsoft and can be taken as a superset to Javascript; the code written in Typescript is later compiled into Javascript. Typescript adds new features like Interfaces, Generics, etc.
15) Name some of the Javascript frameworks.
There are many Javascript Frameworks available today, but the most commonly used frameworks are:
(i) Angular (ii) React (iii) Vue
16) Explain the typeof operator.
The operator typeof is an example of Unary Operators, which is used by placing it before its operand; which can be of any type.
You may also like: Top 30 Interview Questions and Answers on Angular 5
Javascript Console (Arrays & Functions) Questions


19) What are self Executing Functions?
These functions are executed right after its definition. Also called as Immediately Invoked Function Expressions (IIFE's). Syntax:
(function(){
console.log('in iffe');
})()
20) What is a function callback?
The callback function is a mechanism to send one function to another function as an argument; i.e., passing func as an argument to another function.
21) What happens when the recursion calling is applied on two functions?
The calling of recursion is possible in two functions, but the call comes to an end after some time.
22) Explain the term closure.
The inner functions can be called as closure when it has access to the outer function's variables.
23) Explain the terms synchronous and asynchronous code.
The synchronous code is something that should be finished before anything else can happen, or in other words, the synchronous code is blocking. And the Asynchronous code is something in which actions can happen and is not dependent on other actions- in other words, it is non-blocking.
24) Name the different types of pop up boxes in Javascript.
There are three types of pop up boxes in Javascript (i) alert() provides some information to the user with just an OK button (ii) confirm() asks a question to the user with two options Ok and cancel, and (iii) prompt() takes an input from the user.
25) What is the use of the ‘this’ keyword?
The keyword ‘this’ refers to the current instance of the object when used inside a function. But, when used outside a function, it refers to the window object.
26) Is Exception handling possible in Javascript?
With the latest version of Javascript, exception handling is possible; and this can be achieved using the following keywords try, catch and finally.
27) How is it possible to get the total number of arguments that are passed to a function?
The arguments.length property helps in getting the total number of arguments that are passed to a function.
28) What is the difference between typeof and instanceof operators in Javascript?
The typeof operator returns a string of what type the operand is. Whereas, the instanceof operator does not work with primitive data types; but works with objects and checks on what type the object is.
Explore Top 5 Skills That Make You A Sure Shot Programmer
Javascript DOM (Document Object Model) Questions
29) What is DOM?
DOM (Document Object Model) is an object-oriented representation of the HTML elements. All the elements (or nodes) are part of window.document.
30) Expand BOM and explain it.
BOM stands for Browser Object Model. Using BOM interaction with a browser is possible. Default object of the browser is a window.
31) What is the difference between window and document in Javascript?
Javascript window is a global object which holds variables, functions, history, location; the document also comes under the window and can be considered as the property of the window.
32) What is the difference between innerHTML and innerText?
innerHTML will process an HTML tag if found in a string, whereas innerText will not. For Example document.querySelector('p').innerHTML='one <br> two' gives the output one and two in two lines as <br> in html is a new line. Whereas document.querySelector('p').innerText='one <br> two' gives the output of the text as it is in one line.
33) What is the difference between textContent and innerText?
Let us have a paragraph element and a span element in it as a child element.
<p>some text and a <span style="visibility: hidden">span tag hidden <\span>in it</p>
Now, if the following two steps would result in the following-
console.log(document.querySelector('p').textContent); gives some text and a span tag hidden in it.
console.log(document.querySelector('p').innerText); gives some text and a in it.
34) What is the difference between HTMLCollection and NodeList?
The functions querySelectorAll() returns NodeList in which the forEach can be used directly to traverse the elements. Whereas, the getElementsByClassName() or getElementsByTagName() returns an HTMLCollection, which does not have a forEach by default.
35) How can an HTMLCollection be traversed?
The HTMLCollection by default does not have forEach, it needs to be converted into an array (eleName = Array.from(eleName)) and then the traversal is possible using forEach.
36) What is the difference between childNode and children?
A childNode, when used returns a NodeList. Whereas, children, when used; returns an HTMLCollection.
You may also like: Difference Between Java And Javascript
37) What is the difference between firstChild and firstElementChild?
A firstChild when used returns the first node. It could be an HTML element or even a space, or a new line. Whereas, firstElementChild, when used returns the first HTML element only.
38) Name the two functions that are used to create an HTML element dynamically.
To generate an html element dynamically, we need to use two functions:
(i) var ele = createElement ('elementName'), which creates an element and
(ii) parentElement.appendChild(ele)
39) What is the difference between remove() and removeChild()?
The remove() function just removes the element. Whereas, the removeChild() returns the deleted element.
40) List out the Mouse Events.
There are altogether 9 mouse events. Here is the list:
1. click: A single click
2. dblclick: A double click
3. mousedown: When the mouse button is clicked down.
4. mouseup: When the mouse button is released up.
5. mouseenter: When the mouse cursor enters an external element.
6. mouseleave: When the mouse cursor leaves an external element.
7. mouseover: When the mouse cursor enters an internal and external element.
8. mouseout: When the mouse cursor leaves an internal and external element.
9. mousemove: When the mouse cursor is moved.
41) What is the use of history object?
By using the history object you can change or switch back to history pages or forward from current page to another page.
42) What is an Event Bubbling in Javascript?
When an event is fired on an HTML element, the execution starts from that event and goes to its parent element. From there, the execution passes to its parent element and so on till the body element.
43) What does window.print() do in Javascript?
The print() function from window object prints the current web page when executed.
Read through: Top 55 Java Interview Questions and Answers for 2018
44) How can a Javascript code redirect the user to a different page?
The window.location is assigned a value; i.e., a web link. On its execution, the Javascript code can redirect the user to the mentioned web link.

46) How do Javascript primitive/object types passed in functions?
Primitive types in Javascript are passed by value; whereas, object types are passed by reference.
47) What is NaN in Javascript?
NaN is a short form of Not a Number. When a string or something else is being converted into a number and that cannot be done, then we get to see NaN. A strange thing about NaN is that it is not equal to anything including itself.
48) List out all the falsifying tokens in Javascript.
There are 6 tokens that falsify in Javascript and they are false, null, undefined, 0, NaN.
49) What is Currying in Javascript?
A partial invocation of a Javascript function is called Currying. Few arguments of a function are processed and a function is returned. Few more arguments are added by the returning function.

50) When do we use JSON.stringify()?
The JSON.stringify() method is used to convert a Javascript data to a string.

51) What does unshift() function do in Javascript?
Just like push() which inserts elements into an array at the end of it, the unshift() function inserts elements at the beginning of an array.

==========================================================

 
6. What is negative infinity?
Negative Infinity is a number in JavaScript which can be derived by dividing negative number by zero.
7. Is it possible to break JavaScript Code into several lines?
Breaking within a string statement can be done by the use of a backslash, '\', at the end of the first line
Example:
document.write("This is \a program");
And if you change to a new line when not within a string statement, then javaScript ignores break in line.
Example:
var x=1, y=2,
z=
x+y;
The above code is perfectly fine, though not advisable as it hampers debugging.
 
9. What are undeclared and undefined variables?
Undeclared variables are those that do not exist in a program and are not declared. If the program tries to read the value of an undeclared variable, then a runtime error is encountered.
Undefined variables are those that are declared in the program but have not been given any value. If the program tries to read the value of an undefined variable, an undefined value is returned.
10. Write the code for adding new elements dynamically?
<html> 
<head> 
<title>t1</title> 
<script type="text/javascript"> 
	function addNode() { var newP = document.createElement("p"); 
	var textNode = document.createTextNode(" This is a new text node"); 
	newP.appendChild(textNode); document.getElementById("firstP").appendChild(newP); } 
</script> </head> 
<body> <p id="firstP">firstP<p> </body> 
</html>

11. What are global variables? How are these variable declared and what are the problems associated with using them?
Global variables are those that are available throughout the length of the code, that is, these have no scope. The var keyword is used to declare a local variable or object. If the var keyword is omitted, a global variable is declared.
Example:
// Declare a global globalVariable = "Test";
The problems that are faced by using global variables are the clash of variable names of local and global scope. Also, it is difficult to debug and test the code that relies on global variables.
12. What is a prompt box?
A prompt box is a box which allows the user to enter input by providing a text box. Label and box will be provided to enter the text or number.
13. What is 'this' keyword in JavaScript?
'This' keyword refers to the object from where it was called.
14. Explain the working of timers in JavaScript? Also elucidate the drawbacks of using the timer, if any?
Timers are used to execute a piece of code at a set time or also to repeat the code in a given interval of time. This is done by using the functions setTimeout, setInterval and clearInterval.
The setTimeout(function, delay) function is used to start a timer that calls a particular function after the mentioned delay. The setInterval(function, delay) function is used to repeatedly execute the given function in the mentioned delay and only halts when cancelled. The clearInterval(id) function instructs the timer to stop.
Timers are operated within a single thread, and thus events might queue up, waiting to be executed.

16. What is the difference between ViewState and SessionState?
'ViewState' is specific to a page in a session.
'SessionState' is specific to user specific data that can be accessed across all pages in the web application.
17. What is === operator?
=== is called as strict equality operator which returns true when the two operands are having the same value without any type conversion.
18. Explain how can you submit a form using JavaScript?
To submit a form using JavaScript use document.form[0].submit();
document.form[0].submit();
19. Does JavaScript support automatic type conversion?
Yes JavaScript does support automatic type conversion, it is the common way of type conversion used by JavaScript developers
20. How can the style/class of an element be changed?
It can be done in the following way:
document.getElementById("myText").style.fontSize = "20?;
or
document.getElementById("myText").className = "anyclass";
21. Explain how to read and write a file using JavaScript?
There are two ways to read and write a file using JavaScript
Using JavaScript extensions
Using a web page and Active X objects

23. What is called Variable typing in Javascript?
Variable typing is used to assign a number to a variable and the same variable can be assigned to a string.
Example
i = 10;
i = "string";
This is called variable typing.

24. How can you convert the string of any base to integer in JavaScript?
The parseInt() function is used to convert numbers between different bases. parseInt() takes the string to be converted as its first parameter, and the second parameter is the base of the given string.
In order to convert 4F (of base 16) to integer, the code used will be -
parseInt ("4F", 16);

26. What would be the result of 3+2+"7"?
Since 3 and 2 are integers, they will be added numerically. And since 7 is a string, its concatenation will be done. So the result would be 57.
27. Explain how to detect the operating system on the client machine?
In order to detect the operating system on the client machine, the navigator.platform string (property) should be used.
28. What do mean by NULL in Javascript?
The NULL value is used to represent no value or no object. It implies no object or null string, no valid boolean value, no number and no array object.
29. What is the function of delete operator?
The delete keyword is used to delete the property as well as its value.
Example
var student= {age:20, batch:"ABC"};
delete student.age;
30. What is an undefined value in JavaScript?
Undefined value means the
Variable used in the code doesn't exist
Variable is not assigned to any value
Property doesn't exist

31. What are all the types of Pop up boxes available in JavaScript?
Alert
Confirm and
Prompt

35. What is the difference between an alert box and a confirmation box?
An alert box displays only one button which is the OK button.
But a Confirmation box displays two buttons namely OK and cancel.

32. What is the use of Void(0)?
Void(0) is used to prevent the page from refreshing and parameter "zero" is passed while calling.
Void(0) is used to call another method without refreshing the page.

33. How can a page be forced to load another page in JavaScript?
The following code has to be inserted to achieve the desired effect:
<script language="JavaScript" type="text/javascript" >

<!-- location.href="http://newhost/newpath/newfile.html"; //--></script>


36. What are escape characters?
Escape characters (Backslash) is used when working with special characters like single quotes, double quotes, apostrophes and ampersands. Place backslash before the characters to make it display.
Example:
document.write "I m a "good" boy"
document.write "I m a \"good\" boy"

37. What are JavaScript Cookies?
Cookies are the small test files stored in a computer and it gets created when the user visits the websites to store information that they need. Example could be User Name details and shopping cart information from the previous visits.
38. Explain what is pop()method in JavaScript?
The pop() method is similar as the shift() method but the difference is that the Shift method works at the start of the array. Also the pop() method take the last element off of the given array and returns it. The array on which is called is then altered.
Example:
var cloths = ["Shirt", "Pant", "TShirt"];
cloths.pop();
//Now cloth becomes Shirt,Pant
39. Whether JavaScript has concept level scope?
No. JavaScript does not have concept level scope. The variable declared inside the function has scope inside the function.
40. Mention what is the disadvantage of using innerHTML in JavaScript?
If you use innerHTML in JavaScript the disadvantage is
Content is replaced everywhere
We cannot use like "appending to innerHTML"
Even if you use +=like "innerHTML = innerHTML + 'html'" still the old content is replaced by html
The entire innerHTML content is re-parsed and build into elements, therefore its much slower
The innerHTML does not provide validation and therefore we can potentially insert valid and broken HTML in the document and break it
41. What is break and continue statements?
Break statement exits from the current loop.
Continue statement continues with next statement of the loop.
42. What are the two basic groups of dataypes in JavaScript?
They are as –
Primitive
Reference types.
Primitive types are number and Boolean data types. Reference types are more complex types like strings and dates.
43. How generic objects can be created?
Generic objects can be created as:
var I = new object();
44. What is the use of type of operator?
'Typeof' is an operator which is used to return a string description of the type of a variable.
45. Which keywords are used to handle exceptions?
Try… Catch---finally is used to handle exceptions in the JavaScript
Try{
	Code
}
Catch(exp){
	Code to throw an exception
}
Finally{
	Code runs either it finishes successfully or after catch
}
46. Which keyword is used to print the text in the screen?
document.write("Welcome") is used to print the text – Welcome in the screen.
47. What is the use of blur function?
Blur function is used to remove the focus from the specified object.
48. What is variable typing?
Variable typing is used to assign a number to a variable and then assign string to the same variable. Example is as follows:
i= 8;
i="john";
49. How to find operating system in the client machine using JavaScript?
The 'Navigator.appversion' is used to find the name of the operating system in the client machine.
50. What are the different types of errors in JavaScript?
There are three types of errors:
Load time errors: Errors which come up when loading a web page like improper syntax errors are known as Load time errors and it generates the errors dynamically.
Run time errors: Errors that come due to misuse of the command inside the HTML language.
Logical Errors: These are the errors that occur due to the bad logic performed on a function which is having different operation.
51. What is the use of Push method in JavaScript?
The push method is used to add or append one or more elements to the end of an Array. Using this method, we can append multiple elements by passing multiple arguments
52. What is unshift method in JavaScript?
Unshift method is like push method which works at the beginning of the array. This method is used to prepend one or more elements to the beginning of the array.
53. What is the difference between JavaScript and Jscript?
Both are almost similar. JavaScript is developed by Netscape and Jscript was developed by Microsoft .
54. How are object properties assigned?
Properties are assigned to objects in the following way -
obj["class"] = 12;
or
obj.class = 12;
55. What is the 'Strict' mode in JavaScript and how can it be enabled?
Strict Mode adds certain compulsions to JavaScript. Under the strict mode, JavaScript shows errors for a piece of codes, which did not show an error before, but might be problematic and potentially unsafe. Strict mode also solves some mistakes that hamper the JavaScript engines to work efficiently.
Strict mode can be enabled by adding the string literal "use strict" above the file. This can be illustrated by the given example:
function myfunction() {
    "use strict";
    var v = "This is a strict mode function";
}

56. What is the way to get the status of a CheckBox?
The status can be acquired as follows -
alert(document.getElementById('checkbox1').checked);
If the CheckBox will be checked, this alert will return TRUE.
57. How can the OS of the client machine be detected?
The navigator.appVersion string can be used to detect the operating system on the client machine.
58. Explain window.onload and onDocumentReady?
The onload function is not run until all the information on the page is loaded. This leads to a substantial delay before any code is executed.
onDocumentReady loads the code just after the DOM is loaded. This allows early manipulation of the code.
59. How will you explain closures in JavaScript? When are they used?
Closure is a locally declared variable related to a function which stays in memory when the function has returned.
For example:
function greet(message) {

    console.log(message);

}

function greeter(name, age) {

    return name + " says howdy!! He is " + age + " years old";

}

// Generate the message

var message = greeter("James", 23);

// Pass it explicitly to greet

greet(message);

This function can be better represented by using closures

function greeter(name, age) {

    var message = name + " says howdy!! He is " + age + " years old";

    return function greet() {

        console.log(message);

    };

}

// Generate the closure

var JamesGreeter = greeter("James", 23);

// Use the closure

JamesGreeter();

60. How can a value be appended to an array?
A value can be appended to an array in the given manner -
arr[arr.length] = value;
61. Explain the for-in loop?
The for-in loop is used to loop through the properties of an object.
The syntax for the for-in loop is -
for (variable name in object){
	statement or block to execute
}
In each repetition, one property from the object is associated to the variable name, and the loop is continued till all the properties of the object are depleted.
62. Describe the properties of an anonymous function in JavaScript?
A function that is declared without any named identifier is known as an anonymous function. In general, an anonymous function is inaccessible after its declaration.
Anonymous function declaration -
var anon = function() {
	alert('I am anonymous');
};
anon();
63. What is the difference between .call() and .apply()?
The function .call() and .apply() are very similar in their usage except a little difference. .call() is used when the number of the function's arguments are known to the programmer, as they have to be mentioned as arguments in the call statement. On the other hand, .apply() is used when the number is not known. The function .apply() expects the argument to be an array.
The basic difference between .call() and .apply() is in the way arguments are passed to the function. Their usage can be illustrated by the given example.
var someObject = {
myProperty : 'Foo',

myMethod : function(prefix, postfix) {

	alert(prefix + this.myProperty + postfix);
}
};
someObject.myMethod('<', '>'); // alerts '<Foo>'
var someOtherObject  = {

	myProperty : 'Bar'

};
someObject.myMethod.call(someOtherObject, '<', '>'); // alerts '<Bar>'

someObject.myMethod.apply(someOtherObject, ['<', '>']); // alerts '<Bar>'

64. Define event bubbling?
JavaScript allows DOM elements to be nested inside each other. In such a case, if the handler of the child is clicked, the handler of parent will also work as if it were clicked too.

66. What boolean operators can be used in JavaScript?
The 'And' Operator (&&), 'Or' Operator (||) and the 'Not' Operator (!) can be used in JavaScript.
*Operators are without the parenthesis.
67. How can a particular frame be targeted, from a hyperlink, in JavaScript?
This can be done by including the name of the required frame in the hyperlink using the 'target' attribute.
<a href="/newpage.htm" target="newframe">>New Page</a>
68. What is the role of break and continue statements?
Break statement is used to come out of the current loop while the continue statement continues the current loop with a new recurrence.
69. Write the point of difference between web-garden and a web-farm?
Both web-garden and web-farm are web hosting systems. The only difference is that web-garden is a setup that includes many processors in a single server while web-farm is a larger setup that uses more than one server.
70. How are object properties assigned?
Assigning properties to objects is done in the same way as a value is assigned to a variable. For example, a form object's action value is assigned as 'submit' in the following manner - Document.form.action="submit"
71. What is the method for reading and writing a file in JavaScript?
This can be done by Using JavaScript extensions (runs from JavaScript Editor), example for opening of a file -
fh = fopen(getScriptPath(), 0);
72. How are DOM utilized in JavaScript?
DOM stands for Document Object Model and is responsible for how various objects in a document interact with each other. DOM is required for developing web pages, which includes objects like paragraph, links, etc. These objects can be operated to include actions like add or delete. DOM is also required to add extra capabilities to a web page. On top of that, the use of API gives an advantage over other existing models.
73. How are event handlers utilized in JavaScript?
Events are the actions that result from activities, such as clicking a link or filling a form, by the user. An event handler is required to manage proper execution of all these events. Event handlers are an extra attribute of the object. This attribute includes event's name and the action taken if the event takes place.
74. Explain the role of deferred scripts in JavaScript?
By default, the parsing of the HTML code, during page loading, is paused until the script has not stopped executing. It means, if the server is slow or the script is particularly heavy, then the webpage is displayed with a delay. While using Deferred, scripts delays execution of the script till the time HTML parser is running. This reduces the loading time of web pages and they get displayed faster.
75. What are the various functional components in JavaScript?
The different functional components in JavaScript are-
First-class functions: Functions in JavaScript are utilized as first class objects. This usually means that these functions can be passed as arguments to other functions, returned as values from other functions, assigned to variables or can also be stored in data structures.
Nested functions: The functions, which are defined inside other functions, are called Nested functions. They are called 'everytime' the main function is invoked.
76. Write about the errors shown in JavaScript?
JavaScript gives a message if it encounters an error. The recognized errors are -
Load-time errors: The errors shown at the time of the page loading are counted under Load-time errors. These errors are encountered by the use of improper syntax, and thus are detected while the page is getting loaded.
Run-time errors: This is the error that comes up while the program is running. It is caused by illegal operations, for example, division of a number by zero, or trying to access a non-existent area of the memory.
Logic errors: It is caused by the use of syntactically correct code, which does not fulfill the required task. For example, an infinite loop.
77. What are Screen objects?
Screen objects are used to read the information from the client's screen. The properties of screen objects are -
AvailHeight: Gives the height of client's screen
AvailWidth: Gives the width of client's screen.
ColorDepth: Gives the bit depth of images on the client's screen
Height: Gives the total height of the client's screen, including the taskbar
Width: Gives the total width of the client's screen, including the taskbar
78. Explain the unshift() method ?
This method is functional at the starting of the array, unlike the push(). It adds the desired number of elements to the top of an array. For example -
var name = [ "john" ];
name.unshift( "charlie" );
name.unshift( "joseph", "Jane" );
console.log(name);
The output is shown below:
[" joseph "," Jane ", " charlie ", " john "]
79. Define unescape() and escape() functions?
The escape () function is responsible for coding a string so as to make the transfer of the information from one computer to the other, across a network.
For Example:
<script>
	document.write(escape("Hello? How are you!"));
</script>
Output: Hello%3F%20How%20are%20you%21
The unescape() function is very important as it decodes the coded string.
It works in the following way. For example:
<script>
	document.write(unescape("Hello%3F%20How%20are%20you%21"));
</script>
Output: Hello? How are you!
80. What are the decodeURI() and encodeURI()?
EncodeURl() is used to convert URL into their hex coding. And DecodeURI() is used to convert the encoded URL back to normal.
<script>
	var uri="my test.asp?name=ståle&car=saab";

	document.write(encodeURI(uri)+ "<br>");

	document.write(decodeURI(uri));
</script>

Output -
my%20test.asp?name=st%C3%A5le&car=saab
my test.asp?name=ståle&car=saab
81. Why it is not advised to use innerHTML in JavaScript?
innerHTML content is refreshed every time and thus is slower. There is no scope for validation in innerHTML and, therefore, it is easier to insert rouge code in the document and, thus, make the web page unstable.
82. What does the following statement declares?
var myArray = [[[]]];
It declares a three dimensional array.
83. How are JavaScript and ECMA Script related?
ECMA Script are like rules and guideline while Javascript is a scripting language used for web development.
84. What is namespacing in JavaScript and how is it used?
Namespacing is used for grouping the desired functions, variables etc. under a unique name. It is a name that has been attached to the desired functions, objects and properties. This improves modularity in the coding and enables code reuse.
85. How can JavaScript codes be hidden from old browsers that don't support JavaScript?
For hiding JavaScript codes from old browsers:
Add "<!--" without the quotes in the code just after the <script> tag.
Add "//-->" without the quotes in the code just before the <script> tag.
Old browsers will now treat this JavaScript code as a long HTML comment. While, a browser that supports JavaScript, will take the "<!--" and "//-->" as one-line comments.

========================================================

Q2. What is JavaScript?
JavaScript is a lightweight, interpreted programming language with object-oriented capabilities that allows you to build interactivity into otherwise static HTML pages. The general-purpose core of the language has been embedded in Netscape, Internet Explorer, and other web browsers.


Q4. What are the features of JavaScript?

Following are the features of JavaScript:
It is a lightweight, interpreted programming language.
It is designed for creating network-centric applications.
It is complementary to and integrated with Java.
It is an open and cross-platform scripting language.

Q5. Is JavaScript a case-sensitive language?
Yes, JavaScript is a case sensitive language.  The language keywords, variables, function names, and any other identifiers must always be typed with a consistent capitalization of letters.

Q6. What are the advantages of JavaScript?
Following are the advantages of using JavaScript −
Less server interaction − You can validate user input before sending the page off to the server. This saves server traffic, which means less load on your server.
Immediate feedback to the visitors − They don’t have to wait for a page reload to see if they have forgotten to enter something.
Increased interactivity − You can create interfaces that react when the user hovers over them with a mouse or activates them via the keyboard.
Richer interfaces − You can use JavaScript to include such items as drag-and-drop components and sliders to give a Rich Interface to your site visitors.

Q9. What is a name function in JavaScript & how to define it?
A named function declares a name as soon as it is defined. It can be defined using function keyword as :
1
2
3
function named(){
// write code here
}
Q10. Can you assign an anonymous function to a variable and pass it as an argument to another function?
Yes! An anonymous function can be assigned to a variable. It can also be passed as an argument to another function.
Q11. What is argument objects in JavaScript & how to get the type of arguments passed to a function?
JavaScript variable arguments represents the arguments that are passed to a function. Using typeof operator, we can get the type of arguments passed to a function. For example −

function func(x){
console.log(typeof x, arguments.length);
}
func(); //==> "undefined", 0
func(7); //==> "number", 7
func("1", "2", "3"); //==> "string", 3
Q12. What are the scopes of a variable in JavaScript?
The scope of a variable is the region of your program in which it is defined. JavaScript variable will have only two scopes.
• Global Variables − A global variable has global scope which means it is visible everywhere in your JavaScript code.
• Local Variables − A local variable will be visible only within a function where it is defined. Function parameters are always local to that function.
Q13. What is the purpose of ‘This’ operator in JavaScript?
The JavaScript this keyword refers to the object it belongs to. This has different values depending on where it is used. In a method, this refers to the owner object and in a function, this refers to the global object.
Powered by Edureka


Q14. What is Callback?
A callback is a plain JavaScript function passed to some method as an argument or option. It is a function that is to be executed after another function has finished executing, hence the name ‘call back‘. In JavaScript, functions are objects. Because of this, functions can take functions as arguments, and can be returned by other functions.

Q15. What is Closure? Give an example.
Closures are created whenever a variable that is defined outside the current scope is accessed from within some inner scope. It gives you access to an outer function’s scope from an inner function. In JavaScript, closures are created every time a function is created. To use a closure, simply define a function inside another function and expose it.
Q16. Name some of the built-in methods and the values returned by them.
Built-in Method
Values
CharAt()
It returns the character at the specified index.
Concat()
It joins two or more strings.
forEach()
It calls a function for each element in the array.
indexOf()
It returns the index within the calling String object of the first occurrence of the specified value.
length()
It returns the length of the string.
pop()
It removes the last element from an array and returns that element.
push()
It adds one or more elements to the end of an array and returns the new length of the array.
reverse()
It reverses the order of the elements of an array.
Q17. What are the variable naming conventions in JavaScript?
The following rules are to be followed while naming variables in JavaScript:
You should not use any of the JavaScript reserved keyword as variable name. For example, break or boolean variable names are not valid.
JavaScript variable names should not start with a numeral (0-9). They must begin with a letter or the underscore character. For example, 123name is an invalid variable name but _123name or name123 is a valid one.
JavaScript variable names are case sensitive. For example, Test and test are two different variables.
Q18. How does TypeOf Operator work?
The typeof operator is used to get the data type of its operand. The operand can be either a literal or a data structure such as a variable, a function, or an object. It is a unary operator that is placed before its single operand, which can be of any type. Its value is a string indicating the data type of the operand.


Q22. What is the difference between Attributes and Property?
Attributes-  provide more details on an element like id, type, value etc.
Property-  is the value assigned to the property like type=”text”, value=’Name’ etc.
Q23. List out the different ways an HTML element can be accessed in a JavaScript code.
Here are the list of ways an HTML element can be accessed in a Javascript code:
(i) getElementById(‘idname’): Gets an element by its ID name
(ii) getElementsByClass(‘classname’): Gets all the elements that have the given classname.
(iii) getElementsByTagName(‘tagname’): Gets all the elements that have the given tag name.
(iv) querySelector(): This function takes css style selector and returns the first selected element.
Q24. In how many ways a JavaScript code can be involved in an HTML file?
There are 3 different ways in which a JavaScript code can be involved in an HTML file:
Inline
Internal
External
An inline function is a JavaScript function, which is assigned to a variable created at runtime. You can differentiate between Inline Functions and Anonymous since an inline function is assigned to a variable and can be easily reused. When you need a JavaScript for a function, you can either have the script integrated in the page you are working on, or you can have it placed in a separate file that you call, when needed. This is the difference between an internal script and an external script.

Q26. What is a Typed language?
Typed Language is in which the values are associated with values and not with variables. It is of two types:
Dynamically: in this, the variable can hold multiple types; like in JS a variable can take number, chars.
Statically: in this, the variable can hold only one type, like in Java a variable declared of string can take only set of characters and nothing else.


Q30. What is the difference between undeclared & undefined?
Undeclared variables are those that do not exist in a program and are not declared. If the program tries to read the value of an undeclared variable, then a runtime error is encountered. Undefined variables are those that are declared in the program but have not been given any value. If the program tries to read the value of an undefined variable, an undefined value is returned.
Q31. Name some of the JavaScript Frameworks
A JavaScript framework is an application framework written in JavaScript. It differs from a JavaScript library in its control flow. There are many JavaScript Frameworks available but some of the most commonly used frameworks are:
Angular
React
Vue
Q32. What is the difference between window & document in JavaScript?
Window
Document
JavaScript window is a global object which holds variables, functions, history, location.
The document also comes under the window and can be considered as the property of the window.
Q33. What is the difference between innerHTML & innerText?
innerHTML – It will process an HTML tag if found in a string
innerText – It will not process an HTML tag if found in a string
Q34. What is an event bubbling in JavaScript?
Event bubbling is a way of event propagation in the HTML DOM API, when an event occurs in an element inside another element, and both elements have registered a handle for that event. With bubbling, the event is first captured and handled by the innermost element and then propagated to outer elements. The execution starts from that event and goes to its parent element. Then the execution passes to its parent element and so on till the body element.ript 
Q36. How do JavaScript primitive/object types passed in functions?
One of the differences between the two is that Primitive Data Types are passed By Value and Objects are passed By Reference.
By Value means creating a COPY of the original. Picture it like twins: they are born exactly the same, but the first twin doesn’t lose a leg when the second twin loses his in the war.
 By Reference means creating an ALIAS to the original. When your Mom calls you “Pumpkin Pie” although your name is Margaret, this doesn’t suddenly give birth to a clone of yourself: you are still one, but you can be called by these two very different names.
Q37. How can you convert the string of any base to integer in JavaScript?
The parseInt() function is used to convert numbers between different bases. It takes the string to be converted as its first parameter, and the second parameter is the base of the given string.
For example-
1
parseInt("4F", 16)
Q38. What would be the result of 2+5+”3″?
Since 2 and 5 are integers, they will be added numerically. And since 3 is a string, its concatenation will be done. So the result would be 73. The ” ” makes all the difference here and represents 3 as a string and not a number.
Q39. What are Exports & Imports?
Imports and exports help us to write modular JavaScript code. Using Imports and exports we can split our code into multiple files. For example-
1
2
3
4
5
6
7
8
9
10
11
12
13
//------ lib.js ------</span>
export const sqrt = Math.sqrt;</span>
export function square(x) {</span>
return x * x;</span>
}
export function diag(x, y) {
return sqrt(square(x) + square(y));
}
 
//------ main.js ------</span>
 { square, diag } from 'lib';
console.log(square(5)); // 25
console.log(diag(4, 3)); // 5
Now with this, we have reached the final section of JavaScript Interview Questions.
Advanced Level JavaScript Interview Questions
Q40. What is the ‘Strict’ mode in JavaScript and how can it be enabled?
Strict mode is a way to introduce better error-checking into your code.
When you use strict mode, you cannot use implicitly declared variables, or assign a value to a read-only property, or add a property to an object that is not extensible.
You can enable strict mode by adding “use strict” at the beginning of a file, a program, or a function.
Q41. What is a prompt box in JavaScript?
A prompt box is a box which allows the user to enter input by providing a text box. The prompt() method displays a dialog box that prompts the visitor for input. A prompt box is often used if you want the user to input a value before entering a page. When a prompt box pops up, the user will have to click either “OK” or “Cancel” to proceed after entering an input value.
Q42. What will be the output of the code below?
1
2
3
4
5
6
var Y = 1;
if (function F(){})
{
y += Typeof F;</span>
}
console.log(y);
The output would be 1undefined. The if condition statement evaluates using eval, so eval(function f(){}) returns function f(){} (which is true). Therefore, inside the if statement, executing typeof f returns undefined because the if statement code executes at run time, and the statement inside the if condition is evaluated during run time.
Q43. What is the difference between Call & Apply?
The call() method calls a function with a given this value and arguments provided individually.
Syntax-
1
fun.call(thisArg[, arg1[, arg2[, ...]]])
The apply() method calls a function with a given this value, and arguments provided as an array.
Syntax-
1
fun.apply(thisArg, [argsArray])
Q44. How to empty an Array in JavaScript?
There are a number of methods you can use to empty an array:
Method 1 –
1
arrayList = []
Above code will set the variable arrayList to a new empty array. This is recommended if you don’t have references to the original array arrayList anywhere else, because it will actually create a new, empty array. You should be careful with this method of emptying the array, because if you have referenced this array from another variable, then the original reference array will remain unchanged.
Method 2 –
1
arrayList.length = 0;
The code above will clear the existing array by setting its length to 0. This way of emptying the array also updates all the reference variables that point to the original array. Therefore, this method is useful when you want to update all reference variables pointing to arrayList.
Method 3 –
1
arrayList.splice(0, arrayList.length);
The implementation above will also work perfectly. This way of emptying the array will also update all the references to the original array.
Powered by Edureka
NEED HELP FOR YOUR UPCOMING INTERVIEW?
Take Javascript Mock Interview
Get Interviewed by Industry Experts
Personalized interview feedback
BOOK A SLOT
Method 4 –
1
2
3
4
while(arrayList.length)
{
arrayList.pop();
}
The implementation above can also empty arrays, but it is usually not recommended to use this method often.
Q45. What will be the output of the following code?
1
2
3
4
5
6
7
var Output = (function(x)
{
Delete X;
return X;
}
)(0);
console.log(output);
The output would be 0. The delete operator is used to delete properties from an object. Here x is not an object but a local variable. delete operators don’t affect local variables.
Q46. What will be the output of the following code?
1
2
3
4
5
6
7
8
var X = { Foo : 1};
var Output = (function()
{
delete X.foo;
return X.foo;
}
)();
console.log(output);
The output would be undefined. The delete operator is used to delete the property of an object. Here, x is an object which has the property foo, and as it is a self-invoking function, we will delete the foo property from object x. After doing so, when we try to reference a deleted property foo, the result is undefined.
Q47. What will be the output of the following code?
1
2
3
4
5
6
var Employee =
{
company: 'xyz'
}
var Emp1 = Object.create(employee);
delete Emp1.company Console.log(emp1.company);
The output would be xyz. Here, emp1 object has company as its prototype property. The delete operator doesn’t delete prototype property. emp1 object doesn’t have company as its own property. However, we can delete the company property directly from the Employee object using delete Employee.company.
Q48. What will be the output of the code below? 
1
2
3
4
5
6
//nfe (named function expression)
var Foo = Function Bar()
{
return 7;
};
typeof Bar();
The output would be Reference Error. A function definition can have only one reference variable as its function name.
Q49. What is the reason for wrapping the entire content of a JavaScript source file in a function book?
This is an increasingly common practice, employed by many popular JavaScript libraries. This technique creates a closure around the entire contents of the file which, perhaps most importantly, creates a private namespace and thereby helps avoid potential name clashes between different JavaScript modules and libraries.
Another feature of this technique is to allow for an easy alias for a global variable. This is often used in jQuery plugins.
Q50. What are escape characters in JavaScript?
JavaScript escape characters enable you to write special characters without breaking your application. Escape characters (Backslash) is used when working with special characters like single quotes, double quotes, apostrophes and ampersands. Place backslash before the characters to make it display.
For example-
1
2
document.write "I am a "good" boy"
document.write "I am a "good" boy"
===========================================
 

What are the features of JavaScript?
JavaScript is a lightweight, interpreted programming language.
JavaScript is designed for creating network-centric applications.
JavaScript is complementary to and integrated with Java.
JavaScript is complementary to and integrated with HTML.
JavaScript is open and cross-platform.




What are the advantages of JavaScript?
Less server interaction? You can validate user input before sending the page off to the server.
Immediate feedback to the visitors? They don’t have to wait for a page reload to see if they have forgotten to enter something.
Increased interactivity? You can create interfaces that react when the user hovers over them with a mouse or activates them via the keyboard

Why is javascript called Richer Interface?
You can use JavaScript to include such items as drag-and-drop components and sliders to give a Rich Interface to your site visitors.

Is javascript case-sensitive?
Yes, JavaScript is a case-sensitive language. This means that language keywords, variables, function names, and any other identifiers must always be typed with a consistent capitalization of letters.




How can we read the properties of an object in js?
Can write and read properties of an object using the dot(.) notation.

How to create an array in js and how to read array elements?
Can you define arrays using the array literal as follows?
var x = [];
var y = [1, 2, 3, 4, 5];
An array has a length property that is useful for iteration. Can we read elements of an array as follows?
for (var i = 0; i < x.length; i++)

How many types of functions JS support?
A function in JavaScript can be either named or anonymous.



How to define an anonymous function?
An anonymous function can be defined in a similar way as a normal function but it would not have any name.

Which built-in method calls a function for each element in the array?
forEach method calls a function for each element in the array.

Which type of variable among global and local, takes precedence over other if names are same?
A local variable takes precedence over a global variable with the same name.

Difference between “var” and “let” Keywords?
Var was there from the beginning but the let was introduced in ES2015/ES6.
Let has block scope and “Var” has function scope

Difference between “==” and “===” ?
” ==” only compares values “===” compare values and type both.

What is prototypal Inheritance?
Every object has a property called a prototype, where we can add methods to it and when you create another object from these the newly created object will automatically inherit its parent’s property.

Which built-in method reverses the order of the elements of an array?
Reverse method reverses the order of the elements of an array ?? the first becomes the last, and the last becomes the first.

What is SetTimeout()?
When you setTimeout it becomes asynchronous and it has to wait on the stack to get everything got finished

How to add one new element at end of an array in javascript?
Push method adds one or more elements to the end of an array and returns the new length of the array.

What is closure and how do you use it?
When a function returns the other function the returning function will hold its environment and this is known as closure.

Output of below statements
filter_none
edit
play_arrow
brightness_4
<script>
document.write({});
</script>
=====================================
 

2) List some features of JavaScript.
Some of the features of JavaScript are:
Lightweight
Interpreted programming language
Good for the applications which are network-centric
Complementary to Java
Complementary to HTML
Open source
Cross-platform
3) List some of the advantages of JavaScript.
Some of the advantages of JavaScript are:
Server interaction is less
Feedback to the visitors is immediate
Interactivity is high
Interfaces are richer

4) List some of the disadvantages of JavaScript.
Some of the disadvantages of JavaScript are:
No support for multithreading
No support for multiprocessing
Reading and writing of files is not allowed
No support for networking applications.

5) Define a named function in JavaScript.
The function which has named at the time of definition is called a named function. For example
function msg()  
{  
  document.writeln("Named Function");  
}  
msg();  

6) Name the types of functions
The types of function are:
Named - These type of functions contains name at the time of definition. For Example:
function display()  
{  
  document.writeln("Named Function");  
}  
display();  
Anonymous - These type of functions doesn't contain any name. They are declared dynamically at runtime.
var display=function()  
{  
  document.writeln("Anonymous Function");  
}  
display();  

7) Define anonymous function
It is a function that has no name. These functions are declared dynamically at runtime using the function operator instead of the function declaration. The function operator is more flexible than a function declaration. It can be easily used in the place of an expression. For example:
var display=function()  
{  
  alert("Anonymous Function is invoked");  
}  
display();  

8) Can an anonymous function be assigned to a variable?
Yes, you can assign an anonymous function to a variable.

9) In JavaScript what is an argument object?
The variables of JavaScript represent the arguments that are passed to a function.

10) Define closure.
In JavaScript, we need closures when a variable which is defined outside the scope in reference is accessed from some inner scope.
var num = 10;  
function sum()   
{  
document.writeln(num+num);  
}   
sum();  

11) If we want to return the character from a specific index which method is used?
The JavaScript string charAt() method is used to find out a char value present at the specified index. The index number starts from 0 and goes to n-1, where n is the length of the string. The index value can't be a negative, greater than or equal to the length of the string. For example:
var str="Javatpoint";    
document.writeln(str.charAt(4));    

12) What is the difference between JavaScript and JScript?
Netscape provided the JavaScript language. Microsoft changed the name and called it JScript to avoid the trademark issue. In other words, you can say JScript is the same as JavaScript, but Microsoft provides it.

13) How to write a hello world example of JavaScript?
A simple example of JavaScript hello world is given below. You need to place it inside the body tag of HTML.
<script type="text/javascript">  
document.write("JavaScript Hello World!");  
</script>  
More details.
14) How to use external JavaScript file?
I am assuming that js file name is message.js, place the following script tag inside the head tag.
<script type="text/javascript" src="message.js"></script>  
More details.
15) Is JavaScript case sensitive language?
Yes, JavaScript is a case sensitive language. For example:
Var msg = "JavaScript is a case-sensitive language"; //Here, var should be used to declare a variable  
function display()   
{  
document.writeln(msg); // It will not display the result.  
}   
display();  

16) What is BOM?
BOM stands for Browser Object Model. It provides interaction with the browser. The default object of a browser is a window. So, you can call all the functions of the window by specifying the window or directly. The window object provides various properties like document, history, screen, navigator, location, innerHeight, innerWidth,
 More Details: Browser Object Model
17) What is DOM? What is the use of document object?
DOM stands for Document Object Model. A document object represents the HTML document. It can be used to access and change the content of HTML.
More Details: Document Object Model
18) What is the use of window object?
The window object is created automatically by the browser that represents a window of a browser. It is not an object of JavaScript. It is a browser object.
The window object is used to display the popup dialog box. Let's see with description.
Method
Description
alert()
displays the alert box containing the message with ok button.
confirm()
displays the confirm dialog box containing the message with ok and cancel button.
prompt()
displays a dialog box to get input from the user.
open()
opens the new window.
close()
closes the current window.
setTimeout()
performs the action after specified time like calling function, evaluating expressions.
More details.
19) What is the use of history object?
The history object of a browser can be used to switch to history pages such as back and forward from the current page or another page. There are three methods of history object.
history.back() - It loads the previous page.
history.forward() - It loads the next page.
history.go(number) - The number may be positive for forward, negative for backward. It loads the given page number.
More details.
20) How to write a comment in JavaScript?
There are two types of comments in JavaScript.
Single Line Comment: It is represented by // (double forward slash)
Multi-Line Comment: Slash represents it with asterisk symbol as /* write comment here */
More details.
21) How to create a function in JavaScript?
To create a function in JavaScript, follow the following syntax.
function function_name(){  
//function body  
}  
More details.
22) What are the JavaScript data types?
There are two types of data types in JavaScript:
Primitive Data Types - The primitive data types are as follows:
Data Type
Description
String
represents a sequence of characters, e.g., "hello"
Number
represents numeric values, e.g., 100
Boolean
represents boolean value either false or true
Undefined
represents an undefined value
Null
represents null, i.e., no value at all
Non-primitive Data Types - The non-primitive data types are as follows:
Data Type
Description
Object
represents an instance through which we can access members
Array
represents a group of similar values
RegExp
represents regular expression
More details.
23) What is the difference between == and ===?
The == operator checks equality only whereas === checks equality, and data type, i.e., a value must be of the same type.

24) How to write HTML code dynamically using JavaScript?
The innerHTML property is used to write the HTML code using JavaScript dynamically. Let's see a simple example:
document.getElementById('mylocation').innerHTML="<h2>This is heading using JavaScript</h2>";   
More details.
25) How to write normal text code using JavaScript dynamically?
The innerText property is used to write the simple text using JavaScript dynamically. Let's see a simple example:
document.getElementById('mylocation').innerText="This is text using JavaScript";   
More details.
26) How to create objects in JavaScript?
There are 3 ways to create an object in JavaScript.
By object literal
By creating an instance of Object
By Object Constructor
Let's see a simple code to create an object using object literal.
emp={id:102,name:"Rahul Kumar",salary:50000}   
More details.
27) How to create an array in JavaScript?
There are 3 ways to create an array in JavaScript.
By array literal
By creating an instance of Array
By using an Array constructor
Let's see a simple code to create an array using object literal.
var emp=["Shyam","Vimal","Ratan"];    
More details.
28) What does the isNaN() function?
The isNan() function returns true if the variable value is not a number. For example:
function number(num) {  
  if (isNaN(num)) {  
    return "Not a Number";  
  }  
  return "Number";  
}  
console.log(number('1000F'));  
// expected output: "Not a Number"  
  
console.log(number('1000'));  
// expected output: "Number"  

29) What is the output of 10+20+"30" in JavaScript?
3030 because 10+20 will be 30. If there is numeric value before and after +, it treats as binary + (arithmetic operator).
function display()  
{  
  document.writeln(10+20+"30");  
}  
display();  

30) What is the output of "10"+20+30 in JavaScript?
102030 because after a string all the + will be treated as string concatenation operator (not binary +).
function display()  
{  
  document.writeln("10"+20+30);  
}  
display();  

31) Difference between Client side JavaScript and Server side JavaScript?
Client-side JavaScript comprises the basic language and predefined objects which are relevant to running JavaScript in a browser. The client-side JavaScript is embedded directly by in the HTML pages. The browser interprets this script at runtime.
Server-side JavaScript also resembles client-side JavaScript. It has a relevant JavaScript which is to run in a server. The server-side JavaScript are deployed only after compilation.

32) In which location cookies are stored on the hard disk?
The storage of cookies on the hard disk depends on the OS and the browser.
The Netscape Navigator on Windows uses a cookies.txt file that contains all the cookies. The path is c:\Program Files\Netscape\Users\username\cookies.txt
The Internet Explorer stores the cookies on a file username@website.txt. The path is: c:\Windows\Cookies\username@Website.txt.

33) What is the real name of JavaScript?
The original name was Mocha, a name chosen by Marc Andreessen, founder of Netscape. In September of 1995, the name was changed to LiveScript. In December 1995, after receiving a trademark license from Sun, the name JavaScript was adopted.

34) What is the difference between undefined value and null value?
Undefined value: A value that is not defined and has no keyword is known as undefined value. For example:
int number;//Here, a number has an undefined value.  
Null value: A value that is explicitly specified by the keyword "null" is known as a null value. For example:
String str=null;//Here, str has a null value.  

35) How to set the cursor to wait in JavaScript?
The cursor can be set to wait in JavaScript by using the property "cursor". The following example illustrates the usage:
<script>  
window.document.body.style.cursor = "wait";   
</script>  

36) What is this [[[]]]?
This is a three-dimensional array.
var myArray = [[[]]];  

37) Are Java and JavaScript same?
No, Java and JavaScript are the two different languages. Java is a robust, secured and object-oriented programming language whereas JavaScript is a client-side scripting language with some limitations.

38) What is negative infinity?
Negative Infinity is a number in JavaScript which can be derived by dividing the negative number by zero. For example:
var num=-5;  
function display()  
{  
  document.writeln(num/0);  
}  
display();  
//expected output: -Infinity  

39) What is the difference between View state and Session state?
"View state" is specific to a page in a session whereas "Session state" is specific to a user or browser that can be accessed across all pages in the web application.

40) What are the pop-up boxes available in JavaScript?
Alert Box
Confirm Box
Prompt Box
Example of alert() in JavaScript
<script type="text/javascript">  
function msg(){  
 alert("Hello Alert Box");  
}  
</script>  
<input type="button" value="click" onclick="msg()"/>  
Example of confirm() in JavaScript
<script type="text/javascript">  
function msg(){  
var v= confirm("Are u sure?");  
if(v==true){  
alert("ok");  
}  
else{  
alert("cancel");  
}  
  
}  
</script>  
  
<input type="button" value="delete record" onclick="msg()"/>  
Example of prompt() in JavaScript
<script type="text/javascript">  
function msg(){  
var v= prompt("Who are you?");  
alert("I am "+v);  
  
}  
</script>  
  
<input type="button" value="click" onclick="msg()"/>  

41) How can we detect OS of the client machine using JavaScript?
The navigator.appVersion string can be used to detect the operating system on the client machine.

42) How to submit a form using JavaScript by clicking a link?
Let's see the JavaScript code to submit the form by clicking the link.
<form name="myform" action="index.php">  
Search: <input type='text' name='query' />  
<a href="javascript: submitform()">Search</a>  
</form>  
<script type="text/javascript">  
function submitform()  
{  
  document.myform.submit();  
}  
</script>  

43) Is JavaScript faster than ASP script?
Yes, because it doesn't require web server's support for execution.

44) How to change the background color of HTML document using JavaScript?
<script type="text/javascript">  
document.body.bgColor="pink";  
</script>  

45) How to handle exceptions in JavaScript?
By the help of try/catch block, we can handle exceptions in JavaScript. JavaScript supports try, catch, finally and throw keywords for exception handling.

46) How to validate a form in JavaScript?
<script>  
function validateform(){  
var name=document.myform.name.value;  
var password=document.myform.password.value;  
  
if (name==null || name==""){  
  alert("Name can't be blank");  
  return false;  
}else if(password.length<6){  
  alert("Password must be at least 6 characters long.");  
  return false;  
  }  
}  
</script>  
<body>  
<form name="myform" method="post" action="abc.jsp" onsubmit="return validateform()" >  
Name: <input type="text" name="name"><br/>  
Password: <input type="password" name="password"><br/>  
<input type="submit" value="register">  
</form>  
Test it Now
Visit here: JavaScript form validation.

47) How to validate email in JavaScript?
<script>  
function validateemail()  
{  
var x=document.myform.email.value;  
var atposition=x.indexOf("@");  
var dotposition=x.lastIndexOf(".");  
if (atposition<1 || dotposition<atposition+2 || dotposition+2>=x.length){  
  alert("Please enter a valid e-mail address \n atpostion:"+atposition+"\n dotposition:"+dotposition);  
  return false;  
  }  
}  
</script>  
<body>  
<form name="myform"  method="post" action="#" onsubmit="return validateemail();">  
Email: <input type="text" name="email"><br/>  
  
<input type="submit" value="register">  
</form>  
Test it Now
Visit here: JavaScript Email validation.

48) What is this keyword in JavaScript?
The this keyword is a reference variable that refers to the current object. For example:
var address=    
{    
company:"Javatpoint",    
city:"Noida",    
state:"UP",    
fullAddress:function()    
{    
return this.company+" "+this.city+" "+this.state;    
}    
};    
var fetch=address.fullAddress();    
document.writeln(fetch);    

49) What is the requirement of debugging in JavaScript?
JavaScript didn't show any error message in a browser. However, these mistakes can affect the output. The best practice to find out the error is to debug the code. The code can be debugged easily by using web browsers like Google Chrome, Mozilla Firebox.
To perform debugging, we can use any of the following approaches:
Using console.log() method
Using debugger keyword

50) What is the use of debugger keyword in JavaScript?
JavaScript debugger keyword sets the breakpoint through the code itself. The debugger stops the execution of the program at the position it is applied. Now, we can start the flow of execution manually. If an exception occurs, the execution will stop again on that particular line.. For example:
function display()  
{  
x = 10;    
y = 15;    
z = x + y;    
debugger;    
document.write(z);    
document.write(a);     
}     
display();  

51) What is the role of a strict mode in JavaScript?
The JavaScript strict mode is used to generates silent errors. It provides "use strict"; expression to enable the strict mode. This expression can only be placed as the first statement in a script or a function. For example:
"use strict";    
x=10;    
console.log(x);   

52) What is the use of Math object in JavaScript?
The JavaScript math object provides several constants and methods to perform a mathematical operation. Unlike date object, it doesn't have constructors. For example:
function display()  
{  
  document.writeln(Math.random());  
}  
display();  

53) What is the use of a Date object in JavaScript?
The JavaScript date object can be used to get a year, month and day. You can display a timer on the webpage by the help of JavaScript date object.
function display()  
{  
  var date=new Date();    
var day=date.getDate();    
var month=date.getMonth()+1;    
var year=date.getFullYear();    
document.write("<br>Date is: "+day+"/"+month+"/"+year);    
}  
display();  

54) What is the use of a Number object in JavaScript?
The JavaScript number object enables you to represent a numeric value. It may be integer or floating-point. JavaScript number object follows the IEEE standard to represent the floating-point numbers.
function display()  
{  
var x=102;//integer value    
var y=102.7;//floating point value    
var z=13e4;//exponent value, output: 130000    
var n=new Number(16);//integer value by number object    
document.write(x+" "+y+" "+z+" "+n);    
}     
display();  

55) What is the use of a Boolean object in JavaScript?
The JavaScript Boolean is an object that represents value in two states: true or false. You can create the JavaScript Boolean object by Boolean() constructor.
function display()  
{  
document.writeln(10<20);//true    
document.writeln(10<5);//false     
}     
display();  

56) What is the use of a TypedArray object in JavaScript?
The JavaScript TypedArray object illustrates an array like a view of an underlying binary data buffer. There is any number of different global properties, whose values are TypedArray constructors for specific element types.
function display()  
{  
var arr1= [1,2,3,4,5,6,7,8,9,10];     
       arr1.copyWithin(2) ;   
       document.write(arr1);    
}  
display();  

57) What is the use of a Set object in JavaScript?
The JavaScript Set object is used to store the elements with unique values. The values can be of any type i.e. whether primitive values or object references. For example:
function display()  
{  
var set = new Set();    
set.add("jQuery");    
set.add("AngularJS");    
set.add("Bootstrap");    
for (let elements of set) {    
 document.writeln(elements+"<br>");    
}     
}  
display();  

58) What is the use of a WeakSet object in JavaScript?
The JavaScript WeakSet object is the type of collection that allows us to store weakly held objects. Unlike Set, the WeakSet are the collections of objects only. It doesn't contain the arbitrary values. For example:
function display()  
{  
var ws = new WeakSet();    
var obj1={};    
var obj2={};    
ws.add(obj1);    
ws.add(obj2);    
//Let's check whether the WeakSet object contains the added object    
document.writeln(ws.has(obj1)+"<br>");    
document.writeln(ws.has(obj2));     
}     
display()  


=====================




Question: Could you enumerate the various features of JavaScript?
Answer: Some important features of JavaScript are:
A lightweight interpreted a programming language with some object-oriented capabilities
An open, cross-platform scripting language
Complements and integrates with the Java programming language as well as other backend technologies.
Designed especially for creating network-centric applications
Question: Please describe the most important advantages of using JavaScript?
Answer: There are several advantages to using JavaScript. Most notable amongst them are listed down as follows:
Enhanced interactivity – JavaScript allows creating interfaces that react when the user activates them via the keyboard or merely hovers the cursor over the same
Immediate feedback – Visitors need not to wait for a page reload to see if they had forgotten to enter some important details
Low server interaction – JS allows validating user input before sending the webpage to the server. It means less server traffic and hence, less load on the server
Rich interfaces – JS has items like drag-and-drop components and sliders to present a richer interface to the website visitors
Question: Could you name some built-in methods in JavaScript?
Answer: Following are some of the inbuilt methods in JavaScript:
anchor() – Creates an HTML anchor to be used as a hypertext target
ceil() – returns the smallest integer that is greater than or equal to the given number
concat() – Combines two strings and returns the newer string
constructor() – Returns the function that created the corresponding instance of the object
Date() – Returns the present date and time
Date.parse() – Parses a string representation of a date and time, and then returns the internal millisecond representation for the same
exec() – Searches for a match in the string parameter
filter() – Creates a new array with all the elements of the array for which the filtering function returns true
fontcolor() – Displays a string in the specified color
link() – Creates an HTML hypertext link that requests another URL
localeCompare() – Returns a number that indicates whether a reference string comes before, after, or is the same as the given string in the sort order
match() – Used for matching a regular expression against a string
pop() – Removes and returns the last element from an array
reduce() – Applies a function simultaneously for two values of the array in order to reduce them to a single value
round() – Rounds off the value of the given number to the nearest integer and returns the same
slice() – Extracts a certain section of a string and returns the remaining string
some() – returns true if at least one element of the array satisfies the provided testing function
toLocaleString() – Return a string value of the current number in a format that depends on the browser’s locale settings
sup() – Displays a string as a superscript
toSource() – Returns a string containing the source of the Boolean object
toUpperCase() – Converts a text to uppercase
valueOf() – Returns the primitive value of the specified object
Question: Explain the use of debugger in JavaScript?
Answer: All modern browsers (Mozilla Firefox, Safari, Google Chrome, etc.) come with an inbuilt debugger that can be summoned by pressing the F12 key. You need to choose the Console tab to view the result. Here you can set breakpoints as well as view the value of the variables.
JavaScript also features a debugger keyword that replicates the function of using breakpoints using a debugger. However, it works only when the debugging option is enabled in the web browser settings.
Interested in JavaScript? Enquire for the best course suited for you.
   SUBMIT
Question: What are the different types of Error Name values in JavaScript?
Answer: There are 6 types of Error Name values. Each one of them is briefly explained as follows:
Eval Error – Thrown when coming across an error in eval() (Newer JS releases don’t have it)
Range Error – Generated when a number outside the specified range is used
Reference Error – It comes into play when an undeclared variable is used
Syntax Error – When the incorrect syntax is used, we get this error
Type Error – This error is thrown when a value outside the range of data types is tried to be used
URI Error – Generated due to the use of illegal characters
Question: Please explain Self Invoking Function and its syntax.
Answer: Functions that are automatically invoked are termed as Self Invoking Functions. These are also known as Immediately Invoked Function Expressions and Self Executing Anonymous Functions. The general syntax of a Self Invoking Function is:
(some_function () {
return () }) ();

Typically, a function is defined and then invoked. However, if there is a need to execute a function automatically at the place where it is given and it needs not to be called again then anonymous functions can be used. Such functions have no name, and thus the name.
Question: Explain the difference between function declaration and function expression?
Answer: Following are the various differences between function declaration and function expression:
Definition – A function that is declared as a separate statement in the main code flow is termed as the function declaration. When a function is created inside an expression or another syntax construct then it is called a function expression
Strict Mode – When a function declaration is within a code block in the Strict mode, it is visible everywhere inside that block but not outside of it. This isn’t the case for a function expression
Time of Use – A function expression is created when the execution reaches it. The function expression is usable only from that moment onwards. A function declaration, on the other hand, can be called before the same is defined
When to Use – Function declaration offers better readability and offers more freedom in organizing the code. Function expressions are typically restricted to be used when there is need of a conditional declaration
Question: Difference between attributes and property?
Answer: JS DOM objects have properties which are like instance variables for particular elements. A property can be of various data types. Properties are accessible by interacting with the object in Vanilla JS or using jQuery’s prop() method.
Rather than in the DOM, attributes are in the HTML. They are similar to properties but not as capable. It’s recommended to work with properties rather than attributes if the former is available. Unlike a property, an attribute is of the string data type.
Question: What are the various ways of embedding JavaScript code in an HTML file?
Answer: There are 4 ways of embedding JS code within HTML documents:
Adding it between tags From an external file that is specified by the src attribute of a tag. Old browsers treat this JS code as a long HTML comment.
Typically, JS code is hidden from old browsers for solving compatibility and UI issues. Interestingly, browsers that support JavaScript will take as one-line comments.
Question: What are the escape characters in JavaScript?
Answer: In JavaScript, we use escape characters, typically backslash (\ \) while working with special characters, such as ampersands (&), apostrophes (‘), double quotes (“ “), and single quotes (‘ ‘). Whatever enclosed within the escape characters gets displayed by the JavaScript.
Six additional escape characters are also available in JavaScript:
\b – Backspace
\f – Form feed
\n – New line
\r – Carriage return
\t – Horizontal tabulator
\v – Vertical tabulator
These aren’t in anyway executed in the HTML or JS code. These were originally designed for controlling fax machines, teletypes, and typewriters.
Question: What do you understand by cookies? How will you create, read, and delete a cookie using JavaScript?
Answer: A cookie is simply data, usually small, sent from a website and stored on the user’s computer by the web browser used to access the website. It is a reliable way for websites to remember stateful information as well as record the browsing activity of the user.
The most basic way of creating a cookie using JS is to assign a string value to the document.cookie object. The general syntax is:
document.cookie = “key1 = value1; key2 = value2; … ; keyN= valueN; expires = date”;
Reading a Cookie:
Reading a cookie using JS is as simple as creating the same. As the value of the document.cookie object is the cookie, use this string whenever you wish to access the cookie.
The document.cookie string keeps a list of name = value pairs, where each pair is separated by a semicolon. The name represents the name of a cookie and the value represents the respective cookie’s string value. For breaking the string into key and value, you can use the split() method.
Deleting a Cookie:
For deleting a cookie using JavaScript, simply set the expiration date (expires) to a time that’s already past. Some web browsers don’t let you delete a cookie unless you don’t specify the path of the cookie. Hence, defining the cookie path is important to ensure that the right cookie is deleted.
Question: What will be the output of the JS code below? Please explain.
var y = 1;
if (function F(){})
{
y += typeof F;
}
console.log(y);

Answer: The output of the aforementioned JavaScript code will be 1undefined. The if condition statement in the code evaluates using eval. Hence, eval(function F(){}) will return function F(){}.
Inside the if statement, executing typeof F returns undefined because the if statement code executes at run time while the statement inside the if condition is being evaluated.
Question: Can you differentiate between let and var?
Answer: Both let and var are used for variable and method declaration in JavaScript. However, the most important difference between the two JS keywords is that while the var keyword is function scoped, the let keyword is block scoped.
Question: What do you understand by Closures in JavaScript?
Answer: Closures provide a better, concise, creative, and expressive way of writing code for JavaScript developers and programmers. Technically speaking, closures are a combination of lexical environment and function.
In other words, a closure is a locally declared variable that is related to a function and stays in the memory when the related function has returned. All local variables that were in-scope at the time of the closure creation are contained by the closure.
Following code snippet demonstrates using a normal function in JavaScript:
function greet(message) {
console.log(message);
}
function greeter(name, age) {
return name + " says Hey!! He is " + age + " years old";
}
var message = greeter("Akhil", 26);
greet(message);

The aforementioned function can be represented in a better way by using closures. This is demonstrated in the following code snippet:
function greeter(name, age) {
var message = name + " says Hey!! He is " + age + " years old";
return function greet() {
console.log(message);
};
}

// Generate the closure
var AkhilGreeter = greeter("Akhil", 26);

// Use the closure
AkhilGreeter();

Question: Please explain NEGATIVE_INFINITY in JavaScript.
Answer: The NEGATIVE_INFINITY is a static property in JS that results when a negative number is divided by 0. Its important characteristics are:
There is no need for creating a number of objects for accessing NEGATIVE_INFINITY
The value of the NEGATIVE_INFINITY property is the same as the negative value of the infinity property of the global object
Question: Is there any short and concise way of writing function expressions in JS?
Answer: JavaScript offers a short and concise way of writing function expressions known as arrow functions. This way of writing function expressions is preferred typically for non-method functions. The general syntax of an arrow function is:
const function_name = ()=>{}

Arrow functions can’t be used as constructors. Moreover, they don’t provide support for arguments, new.target, super, and this.
Question: How can you import all exports of a file as an object in JavaScript?
Answer: In order to import all exported members of an object, one can use:
import * as object name from ‘./file.js’
The exported methods or variables can be easily accessed by using the dot (.) operator.
Question: How will you empty an array in JavaScript?
Answer: There are multiple ways of emptying an array in JavaScript. Four of the most important ones are:
By assigning an empty array:
var array1 = [1, 22, 24, 46];
array1 = [];
By assigning array length to 0:
var array1 = [1, 22, 24, 46];
array1.length=0;
By popping the elements of the array:
var array1 = [1, 22, 24, 46];
while(array1.length > 0) {
array1.pop();
}
By using the splice array function:
var array1 = [1, 22, 24, 46];
array1.splice(0, array1.length)
Question: What do you mean by Event Bubbling and Event Capturing?
Answer: There are two ways for accomplishing event propagation and the order in which an event is received in the HTML DOM API.
These are Event Bubbling and Event Capturing. In the former, the event is directed towards its intended target, whereas the event goes down to the element in the latter.
Event Capturing – Also known as trickling, Event Capturing is rarely used. The process starts with the outermost element capturing the event and then propagating the same to the innermost element.
Event Bubbling – In this process, the event gets handled by the innermost element first and then propagated to the outermost element.
Question: In how many ways can you create an array in JS?
Answer: There are three different ways of creating an array in JavaScript, namely:
By creating instance of an array:
var someArray = new Array();
By using an array constructor:
var someArray = new Array(‘value1’, ‘value2’,…, ‘valueN’);
By using an array literal:
var someArray = [value1, value2,…., valueN];
Question: Write a code to demonstrate how to get inner HTML of an element in JavaScript.
Answer:
Question: How will you remove duplicates from a JS array?
Answer: There are several possible ways of eliminating duplicates from a JS array. Three most-used ones are described as follows:
By using Filter – It is possible to remove duplicates from an array in JavaScript by applying a filter to the same. In order to call the filter() method, three arguments are required. These are namely array, current element, and index of the current element.function unque_array (arr){
let unique_array = arr.filter(function(elem, index, self) {
return index == self.indexOf(elem); }
return unique_array }
console.log(unique_array(array_with_duplicates));
By using the For loop – In this method of removing duplicate elements from an array, an empty array is used for storing all the repeating
elements.Array dups_names = ['Akhil', 'Vijay', 'Swapnil', 'Akhil', 'Vijay'];
function dups_array(dups_names) {
let unique = {};
names.forEach(function(i) {
If (!unique[i]) {
unique[i] = true; }
});
return Object.keys(unique);}
Dups_array(names);


By using Set – This is the simplest approach of removing duplicate elements from an array in JS. A set is an inbuilt object for storing unique values in an array. Here’s how to use it for eliminating repeating elements from an array:function uniquearray(array) {
let unique_array= Array.from(set(array))
return unique_array;}In the above example, a set is created out of the array having duplicate elements. As a set is an ordered collection of unique elements, the result is an array with non-repeating elements.
Question: Can you draw a simple JavaScript DOM (Document Object Model)?
Answer:

Question: Write the code to force a page to load another page in JavaScript.
Answer:
Question: Please explain the Strict mode in JavaScript. Also, tell how to enable it.
Answer: When in the Strict Mode, JS displays errors for some code segments that might be otherwise not available. In other words, the Strict mode adds certain compulsions to the JS. It is used for removing some code mistakes that result in dropped efficiency of JS engines.
In order to enable the Strict Mode, one needs to add the string literal “use strict” above the file that needs to be opened in the Strict Mode. For example:
function somefunction() {
"use strict";
var v = "Welcome to the Strict Mode";

Question: What is the for-in loop in JavaScript? Give its syntax.
Answer: The for-in loop is meant to be used for looping through the properties of a JavaScript object. Every iteration of the loop results in a property of the object getting associated with the variable name. The loop continues until all the object properties are exhausted.
The general syntax of using the for-in loop is:
for (variable name in object){
statement or block to execute
}

Question: Tell us about the difference between .call() and .apply() functions. Give an example of demonstrating the difference between the two JS functions.
Answer: Both .call() and .apply() functions are almost identical in their use with a major exception in the way in which arguments are passed to the function.
Because arguments are to be passed in the .call() method, it is compulsory to know about the arguments of the function. On the other hand, .apply() method is used when the number of arguments is not known. Following example demonstrates using the two functions:
var someObject = {
myProperty : 'Foo',
myMethod : function(prefix, postfix) {
alert(prefix + this.myProperty + postfix);
}
};
someObject.myMethod('<', '>');
var someOtherObject = {
myProperty : 'Bar'
};
someObject.myMethod.call(someOtherObject, '<', '>');
someObject.myMethod.apply(someOtherObject, ['<', '>']);

Question: What role do deferred scripts play in JavaScript?
Answer: During page loading, the parsing of the HTML code is paused by default until the script hasn’t stopped executing. This results in a delay in the display of the webpage if the server is slow or the script that is to be loaded is bulky.
Using deferred scripts results into a delay in the execution of the script for the time the HTML parser is running. Hence, this results in a reduction in the loading time of the webpage.
Question: Could you tell us about the various types of error constructors supported by JavaScript?
Answer: The Error constructor is responsible for creating an error object. Instances of the error objects are thrown when runtime errors occur. Moreover, the Error object can also be used as a base object for user-defined exceptions.
Other than the generic Error constructor, JS provides support for 7 error constructors that are:
EvalError – Creates an error instance regarding the global function eval().
InternalError – Creates an error instance regarding an internal error in the JS engine.
RangeError – Creates an error instance regarding a numeric variable or parameter that is outside of its valid range.
ReferenceError – Creates an error instance regarding de-referencing an invalid reference.
SyntaxError – Creates an error instance regarding a syntax error occurring while parsing code in eval().
TypeError – Creates an error instance regarding a parameter or variable not of a valid type.
URIError – Creates an error instance regarding when invalid parameters are passed to the decodeURI() or encodeURI().
Question: What do you understand by Screen objects? State their various properties.
Answer: In order to read the information from the client’s screen, screen objects are used in JavaScript. Properties of screen objects are:
AvailHeight – Gives out the height of the client screen (Excludes taskbar)
AvailWidth – Gives out the width of the client screen (Excludes taskbar)
ColorDepth – Gives out the bit depth of images supported by the client screen
Height – Gives out the total height of the client screen
Width – Gives out the total width of the client screen
Question: Could you explain escape() and unescape() functions?
Answer: The escape() function allows for converting a string into a coded form in JavaScript. It is used for securely transferring information from one system to another over some network. For instance, consider the following code snippet:
This%20string%20is%20encoded%21

The output of the aforementioned code snipped will be something like this:
This%3F%20string%20is%20encoded%21
The unescape() function does the exact opposite of the escape() function i.e. it decodes a coded string into the original string. Therefore, the following code snippet:
This? string is encoded!

Will yield the following output:
This string is encoded!
Question: Please write JavaScript code for adding new elements dynamically.
Answer:
firstP
All done! That was the list of most important JavaScript interview questions. Hope these questions will help you get a step closer to your dream JavaScript job. All the best!
Check out these best JavaScript tutorials to enhance your JS skill and knowledge.



================================================================================================================================
