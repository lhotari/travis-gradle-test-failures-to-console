travis-gradle-test-failures-to-console
======================================

Sample project for testing travis after_failure script that outputs failed test output to console.

Example output can be seen in the very last part in the Travis build console output
https://travis-ci.org/lhotari/travis-gradle-test-failures-to-console/

The output is collapsed by default. Click on the after_failure label to expand the output.
```
$ ./travis-after-failure.sh
```

On command line you can use the ```travis logs``` command to view the output.

install the [travis command line client](https://github.com/travis-ci/travis.rb#readme) with
```
gem install travis
```