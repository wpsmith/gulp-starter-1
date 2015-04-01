# npm-angular-resource

This repo is for distribution on `NPM`. This is basically an NPM require-able clone of the bower repo from [angular/bower-angular-resource](https://github.com/angular/bower-angular-resource).

The source for this module is in the
[main AngularJS repo](https://github.com/angular/angular.js/tree/master/src/ngResource).
Please file issues and pull requests against that repo. Only file issues here if I forget to bump a version.

## Install

Install with npm:

```shell
npm install npm-angular-resource
```

You can then require it by requiring it.
```javascript
var angular = require('angular')
require('npm-angular-resource')(window, angular)
```

Which in turns allows you to add it to your module's dependencies and use it as you wish.


## License

The MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
