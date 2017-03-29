Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in configure
and tests weren't explicitly disabled.

After configuring, they can be run with 'make check'.

To run the pcibd tests manually, launch src/test/test_pcib .

To add more pcibd tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the test/ directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the pcib-qt tests manually, launch src/qt/test/pcib-qt_test

To add more pcib-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
