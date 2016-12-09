# wpost.js
> Probably the most lightweight / simple Javscript POST request library.

## why?
> It does one thing and it does it well.

## Usage:

        //wpost(<endpoint>, <data>, <callback_function>)

        wpost("/api/registeruser", {"name": "John"}, function(data) {
            console.log(data);
        });

