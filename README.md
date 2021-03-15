- 默认相对路径是img文件夹, 相当于当前文件的路径, 而不是pwd给出的路径
- `<leader>p`
- 如果不想相对路径是img文件夹, 需要设置两项, `let g:mdip_imgdir_intext = /relative/path/to/imgdir`,这是修改markdown插入的内容, 以及`let g:mdip_imgdir = 'img'`, 这是修改真正的放入图片的路径, 两项必须都设置(多么奇怪的设定, 希望有朝一日修改这个行为, 这样只需要设置一处了)

