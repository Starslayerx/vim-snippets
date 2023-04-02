在`init.vim`中的配置
```
" 开启ultisnips插件
let g:UltiSnipsEnableSnipMate = 1
let g:UltiSnipsSnippetDirectories=["~/.config/nvim/UltiSnips"] " 指定代码片段文件夹的位置

" 设置快捷键
let g:UltiSnipsExpandTrigger="<tab>"
let g:UltiSnipsJumpForwardTrigger="<c-b>"
let g:UltiSnipsJumpBackwardTrigger="<c-z>"
```
再UltiSnips文件夹下cpp.ultisnips就是c++的配置文件，可以通过打开一个c++文件后输入`:UltiSnipsEdit`来打开这个文件  
同理，也可以使用该方法添加其他语言代码片段
