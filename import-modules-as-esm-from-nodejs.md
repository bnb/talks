# import { modules } as esm from “nodejs”

**Title:**
```
import { modules } as esm from “nodejs”
```

**Abstract:**
```
After years of hard work from the Modules Team, ESM is shipping in Node.js. In this talk we'll go over the distinct patterns you'll want to use when adopting ESM as a first-class module system in Node.js.
```


**1000 Characters:**
```
In with ES6 JavaScript landed a fully-fledged module system, ECMAScript Modules (ESM). This module system was initially built for the front-end, and works rather well for that use case. However, JavaScript had already had multiple ecosystem-built module systems prior to this - one of which won: CommonJS (CJS).

Over the last few years, the Node.js project has been working on implementing ESM in a way that wouldn't break the 1+ million modules published to npm that folks already rely on for their production systems.

That implementation is (hopefully!) here, providing the ability to use ESM natively in Node.js.

In this talk, we'll go over the various distinct features of the new module system in Node.js. This includes implicit and explicit ESM and CommonJS, the current state of interoperability between the two, and The Nice Parts of CommonJS that are different in ESM like JSON imports and no file extensions. 

You'll walk away ready to use ESM as a first-class module within your next Node.js project.```

**Impact:**
```
With ESM being one of Node.js's most requested features - and most worked on features - having an entry-level talk that simplifies what's new into something digestible and immediately usable.
```
Recordings:
* Recording 1
