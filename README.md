# Vim ES2015 Snippets

Fork of [epilande/vim-react-snippets](https://github.com/epilande/vim-react-snippets)

Requires [UltiSnips](https://github.com/SirVer/ultisnips).

## Installation

Using vim-plug:

```vim
" ES2015 code snippets
Plug 'paupalou/vim-es2015-snippets'

" Ultisnips
Plug 'SirVer/ultisnips'
```

## Usage
```javascript
c=><UltiSnips-trigger-key>
```

Will expand to

```javascript
const name = (args) => {
  return
}
```
