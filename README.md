# fw-test
Test that you can clone a project thru a f/w, use NPM and Bower to install it, build it, and then serve it at an unfamiliar location. If this works, everything else should work.


1. `git clone https://github.com/kenpritchard/fw-test`
2. `cd fw-test`
3. `npm install`
4. `bower cache clean` (Need to make sure we're doing a pull)
5. `bower install`
6. `grunt serve`
