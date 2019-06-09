# LanguageServer

[![Project Status: Active - The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Build Status](https://travis-ci.org/JuliaEditorSupport/LanguageServer.jl.svg?branch=master)](https://travis-ci.org/JuliaEditorSupport/LanguageServer.jl)
[![Build status](https://ci.appveyor.com/api/projects/status/ft7i2f9y5pggl4vn/branch/master?svg=true)](https://ci.appveyor.com/project/davidanthoff/languageserver-jl/branch/master)
[![codecov](https://codecov.io/gh/JuliaEditorSupport/LanguageServer.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/JuliaEditorSupport/LanguageServer.jl)

## Overview

This package implements the Microsoft [Language Server Protocol](https://github.com/Microsoft/language-server-protocol)
for the [Julia](http://julialang.org/) programming language.

Text editors with a client for the Language Server Protocol are able to
make use of the Julia Language Server for various code editing features:

- [VS Code](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia)
- [Atom](https://github.com/pfitzseb/atom-julia-lsp-client)
- [Vim and Neovim](../../wiki/Vim-and-Neovim)
- [Emacs](../../wiki/Emacs)
- [Sublime Text](https://github.com/tomv564/LSP)
