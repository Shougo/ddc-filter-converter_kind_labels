# ddc-filter-converter_kind_labels

Kind labels converter for ddc.vim

## Required

### denops.vim

https://github.com/vim-denops/denops.vim

### ddc.vim

https://github.com/Shougo/ddc.vim

## Configuration

```vim
call ddc#custom#patch_global('sourceOptions', #{
      \  lsp: #{
      \    converters: ['converter_kind_labels'],
      \  }
      \})
```

`kindLabels` changes the displayed kind label, and `kindHlGroups` highlights
that displayed label using its converted width.
