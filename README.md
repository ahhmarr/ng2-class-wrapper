# Simple POC for grouping classes seperately

## Installation

* clone repo
* run `npm install`
* run `npm devserver`
* natak hoga thodi der uske baad app wil be available @ http://localhost:8080

## Implementation

* The mapping is in the module `components/tax-bootstrap/index.ts`
* base class is currently @ `components/home/base.ts`
* all new components should extend base class
* in the constructor need to add `super()`
* the new css classes will be available via `this.customBoot` in the templete files
