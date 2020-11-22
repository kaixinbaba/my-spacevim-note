# my-spacevim-note
记录学习spacevim的过程

# 配置
```toml
[options]
    colorscheme = "desert"
    default_indent = 4
    expand_tab = true
    colorscheme_bg = "dark"
    enable_guicolors = true
    statusline_separator = "arrow"
    statusline_iseparator = "bar"
    statusline_left_sections = ['winnr', 'major mode', 'filename', 'fileformat', 'minor mode lighters', 'version control info', 'search status']
    statusline_right_sections = ['cursorpos', 'percentage', 'input method', 'date', 'time']
    buffer_index_type = 1
    enable_tabline_filetype_icon = true
    filemanager = "defx"
    enable_vimfiler_gitstatus = true
    filetree_direction = "left"
    autocomplete_method = "deoplete"
    automatic_update = true
[[layers]]
    name = "lang#python"
[[layers]]
  name = "core#statusline"
[[layers]]
  name = "lang#markdown"
[[layers]]
  name = "git"
[[layers]]
    name = "autocomplete"
    autocomplete_method = "deoplete"
    auto-completion-return-key-behavior = "complete"
    auto-completion-tab-key-behavior = "cycle"
[[layers]]
    name = "shell"

```


