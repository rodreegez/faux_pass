Faux Pass
=========

This is a simply a test to use when testing things that test bigger, more complicated things. I'm working on a few tweaks for [Integrity](http://github.com/integrity/integrity) and don't want to build a whole project every time, so I'm building this instead. 

Usage
-----

Fork this project then, in /test/test_truth.rb change line 5 to 'assert true' for a passing test, or 'assert false' for a failing one. Push the change and Integrity (or other ci) will build it and (hopefully) let you know the result.

This was really all [Phil](http://twitter.com/philnash)'s idea and even code. I'm just taking the credit ;)

Cheers Phil!