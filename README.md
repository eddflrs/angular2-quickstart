# Angular2 Quickstart

## Get Started

```
$ nvm use
```

> If you don't have the listed version, then do `$ nvm install`

Install all dependencies:

```
$ npm install
```

Start up the dev server:

```
$ npm start
```

## Setting up Vim

Assuming you're using Vundle, in your `.vimrc`:

```
  Plugin 'leafgarland/typescript-vim' "Syntax highlighting
  Plugin 'Shougo/vimproc.vim' "Dependency to get autocompletion
  Plugin 'Quramy/tsuquyomi' "Autocompletion
```

**You also want to ignore the types directory**

```
let g:ctrlp_custom_ignore = '\v[\/](node_modules|types|target|dist|tmp|bower_components|vendor)|(\.(swp|ico|git|svn))$'
```


