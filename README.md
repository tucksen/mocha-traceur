Mocha Traceur
=============
  Simple plugin for mocha that passes "js" files through the traceur compler.
Traceur is intentionally not included in this package so you can install your
preferred version. Use with Mocha from the command line like so:

    mocha --compilers js:mocha-traceur my_test_dir/*.js
