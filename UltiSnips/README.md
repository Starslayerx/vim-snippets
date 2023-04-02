在`init.vim`中的配置
```
" Ultisnips
let g:UltiSnipsEnableSnipMate = 1 " 开启ultisnips插件
let g:UltiSnipsSnippetDirectories=["~/.config/nvim/UltiSnips"] " 指定UltiSnips配置文件夹位置

let g:UltiSnipsExpandTrigger="<c-j>"
let g:UltiSnipsJumpForwardTrigger="<tab>"
let g:UltiSnipsJumpBackwardTrigger="<s-tab>"
```
在UltiSnips文件夹下cpp.ultisnips就是c++的配置文件，可以通过打开一个c++文件后输入`:UltiSnipsEdit`来打开这个文件  
同理，也可以使用该方法添加其他语言代码片段
