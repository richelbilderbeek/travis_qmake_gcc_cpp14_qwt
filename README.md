# travis_qmake_gcc_cpp14_qwt

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_qwt.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_qwt)
develop|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_qwt.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_qwt)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL` and `Qwt`
 * Code coverage: none
 * Source: one single file, `main.cpp`

You cannot use Qwt without choosing a Qt version.

Choose the Qt version you want to use:

 * Use Qt4: [travis_qmake_gcc_cpp14_qt4_qwt](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_qt4_qwt)
 * Use Qt5 (recommended): [travis_qmake_gcc_cpp14_qt5_qwt](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_qt5_qwt)
