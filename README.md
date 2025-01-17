[![Build Status](https://travis-ci.com/coq-community/vscoq.svg?branch=master)](https://travis-ci.com/coq-community/vscoq)

VsCoq is an extension for [Visual Studio
Code](https://code.visualstudio.com/) with support for the [Coq Proof
Assistant](https://coq.inria.fr/).

This extension is currently developped by @maximedenes and contributors, as
part of [Coq Community](https://github.com/coq-community/manifesto). The
original author of this extension is @siegebell.

## Features
* Asynchronous proofs
* Syntax highlighting
* Commands: step forward, interpret to point, interrupt computation, queries, set display options, etc.
* Diff view for proof-view: highlight which terms change between states
* Smarter editing: does not roll back the state when editing whitespace or comments
* Works with [prettify-symbols-mode](https://marketplace.visualstudio.com/items?itemName=siegebell.prettify-symbols-mode)
* Supports \_CoqProject
* The proof-view can be opened in an external web browser
* LtacProf results treeview

## Requirements
* VsCode 1.23.0 or more recent
* Coq 8.7.0 or more recent

## Installation
The recommended way to install VsCoq is via the Visual Studio Marketplace.
However, this fork of VsCoq has not been released yet, so we suggest to wait
for a release.

## Screenshots
![vscoq](https://user-images.githubusercontent.com/647105/64025392-dbf12100-cb3c-11e9-8e7f-5c63296500f9.png)
