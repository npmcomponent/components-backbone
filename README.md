*This repository is a mirror of the [component](http://component.io) module [components/backbone](http://github.com/components/backbone). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/components-backbone`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
     ____                     __      __
    /\  _`\                  /\ \    /\ \                                   __
    \ \ \ \ \     __      ___\ \ \/'\\ \ \____    ___     ___      __      /\_\    ____
     \ \  _ <'  /'__`\   /'___\ \ , < \ \ '__`\  / __`\ /' _ `\  /'__`\    \/\ \  /',__\
      \ \ \ \ \/\ \ \.\_/\ \__/\ \ \\`\\ \ \ \ \/\ \ \ \/\ \/\ \/\  __/  __ \ \ \/\__, `\
       \ \____/\ \__/.\_\ \____\\ \_\ \_\ \_,__/\ \____/\ \_\ \_\ \____\/\_\_\ \ \/\____/
        \/___/  \/__/\/_/\/____/ \/_/\/_/\/___/  \/___/  \/_/\/_/\/____/\/_/\ \_\ \/___/
                                                                           \ \____/
                                                                            \/___/
    (_'_______________________________________________________________________________'_)
    (_.———————————————————————————————————————————————————————————————————————————————._)

NOTE: When requiring Backbone, you should globally declare jQuery, like this:
    
    Backbone.$ = require("jquery");
    
Otherwise, Backbone won't be able to find jQuery. (You'll need to specifiy jQuery as a dependency)

------------

Backbone supplies structure to JavaScript-heavy applications by providing models key-value binding and custom events, collections with a rich API of enumerable functions, views with declarative event handling, and connects it all to your existing application over a RESTful JSON interface.

For Docs, License, Tests, pre-packed downloads, and everything else, really, see:
http://backbonejs.org

To suggest a feature, report a bug, or general discussion:
http://github.com/jashkenas/backbone/issues

Backbone is an open-sourced component of DocumentCloud:
https://github.com/documentcloud

Many thanks to our contributors:
http://github.com/jashkenas/backbone/contributors

Special thanks to Robert Kieffer for the original philosophy behind Backbone.
http://github.com/broofa
