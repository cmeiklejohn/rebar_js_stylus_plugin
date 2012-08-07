# Rebar JS Stylus Plugin

Preprocess stylus files during compilation of your Erlang/OTP
application.

## Installation

Specify ```rebar_js_stylus_plugin``` as a dependency in your ```rebar.config```.

```erlang
{deps, [
       {rebar_js_stylus_plugin, ".*",
        {git, "git://github.com/cmeiklejohn/rebar_js_stylus_plugin.git", {branch, "master"}}}
]}.
```

Then, configure as a plugin in your ```rebar.config```.

```erlang
{plugins, [rebar_js_stylus_plugin]}.
```
