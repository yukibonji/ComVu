# ComVu

[![Build status](https://ci.appveyor.com/api/projects/status/n8hmjy24a5t96g4i/branch/master?svg=true)](https://ci.appveyor.com/project/pocketberserker/comvu/branch/master)

ComVu is a computation expressions visualizer.
This tool can analysis your computation expressions.

## NuGet packages

* WPF tool [![NuGet Status](http://img.shields.io/nuget/v/ComVu.svg?style=flat)](https://www.nuget.org/packages/ComVu/)
* core library [![NuGet Status](http://img.shields.io/nuget/v/ComVu.Core.svg?style=flat)](https://www.nuget.org/packages/ComVu.Core/)

## Features

- Conversion rule
  - [x] ``let p = e in ce``
  - [x] ``let! p = e in ce``
  - [x] ``yield e``
  - [x] ``yield! e``
  - [x] ``return e``
  - [x] ``return! e``
  - [x] ``use p = e in ce``
  - [x] ``use! p = e in ce``
  - [x] ``while e do ce``
  - [x] ``try ce with pi -> cei``
  - [x] ``try ce finally e``
  - [x] ``if e then ce``
  - [x] ``if e then ce1 else ce2``
  - [x] ``for x in e do ce``
  - [x] ``do e in ce``
  - [x] ``do! e in ce``
  - [x] ``ce1; ce2``
  - [x] ``do! e;``
  - [x] ``e;``
  - [ ] ``joinOp``
  - [ ] ``groupJoinOp``
  - [ ] `onWord`
  - [x] Custom operator
- [x] Sequence expression like seq computation expression
- [ ] External function or method call
- [x] External libraries

- Not support
  - ``match e with pi -> cei``

