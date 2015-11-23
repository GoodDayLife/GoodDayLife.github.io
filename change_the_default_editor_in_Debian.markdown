# 树莓派改默认浏览器问题解决方法: 


> 在安装树莓派后,发现默认的编辑器变成了nano,
> 这让我这个vim党很不爽,好在问题解决了.
> 记录以便后续回忆和分享供大家参考.

## 问题描述:
> 在树莓派安装后,系统会默认把nano编辑器设置为默认的编辑器.
> 如果运行 
``` crontab -e ```
时会默认调用nano,需要改默认为vim!

问题很简单,运行下列命令:
```bash
	update-alternatives --config editor
```
如图选择vim即可.
> 
> ![set_default_editor_as_vim.png] (/assets/set_vim_as_default_editor.png )

