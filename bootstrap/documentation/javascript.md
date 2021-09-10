# Javascript Compilation (Pipelines)

## General Notes

- all javascripts are added as async and deferred scripts in the footer (might change via configuration)
- blocks offers concatenated javascripts (simple pipe config) and a module build (JSBuild pipe config)
- configuration of pipes see their respective sections further below.

## Configuration

- js method can be set via `params.dnb.config.js.method` which can be one of `all`, `js` or `jsbuild`


## Simple Pipe Configuration

- 

## JSBuild Pipe Configuration

- options for JSBuild can be set via `params.dnb.config.jsbuild.options`
  - `minify` - minify resulting build, bool, default = true
  - `avoidTDZ` - default true
  - `target` - build target, can be one of es5, es2015, es2016, es2017, es2018 (default), es2019, es2020 or esnext
  - `externals` - if a dependency should not be included in the bundle (Ex. library loaded from a CDN.), it should 
    be listed here (slice)
  - `defines` - Allow to define a set of string replacement to be performed when building. Should be a map where 
    each key is to be replaced by its value. (dict)
  - `format` = The output format. One of: iife, cjs, esm. Default is iife, a self-executing function, suitable for inclusion as a tag.
  - `sourceMap` - setup the sourcemap (inline, whether to generate source maps inline

