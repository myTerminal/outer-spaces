# outer-spaces

[![Marmalade](https://img.shields.io/badge/marmalade-available-8A2A8B.svg)](https://marmalade-repo.org/packages/outer-spaces)  
[![License](https://img.shields.io/badge/LICENSE-GPL%20v3.0-blue.svg)](https://www.gnu.org/licenses/gpl.html)

A minimalistic minor-mode to highlight redundant spaces

![Demo](images/demo.gif)

## Installation

### Manual

Save the file *outer-spaces.el* to disk and add the directory containing it to `load-path` using a command in your *.emacs* file like:

    (add-to-list 'load-path "~/.emacs.d/")

The above line assumes that you've placed the file into the Emacs directory '.emacs.d'.

Start the package with:

    (require 'outer-spaces)

### Marmalade

If you have Marmalade added as a repository to your Emacs, you can just install *outer-spaces* with

    M-x package-install outer-spaces RET

## Usage

Enable outer-spaces-mode in any buffer to highlight spaces in that buffer. Disabling minor-mode will unhighlight the highlighted spaces.
