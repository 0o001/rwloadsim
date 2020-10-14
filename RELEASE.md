# RWP\*Load Simulator Release Notes

## master

* Bug with dynamic SQL in threads fixed; tests added
* Warnings about uniform and comparison when double is taken as integer
* New syntax for control loop (old still supported, but not documented)
* Remove all sharding code that wasn't working anyway
* Correct $longoption:publicsearch 
* Allow concatenation as procedure/function arguments
* Fix wrong casts from ub4 to ub8
* Replace strcpy+strcat with snprintf to remove overrun risk
* Improve some diagnostics for bad input
* Remove legacy in various places and lots of #ifdef NEVER
* Various minor bug fixes
* Add tests for clob inside pl/sql
* Major changes to documentation

*DO NOT* check out the master branch unless you are developing the code.

If you need a binary prerelease, ask the developer.

## 2.2.3

This is the first release available on github.