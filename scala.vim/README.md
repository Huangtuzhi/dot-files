第一步，执行下面这个脚本：

```
mkdir -p ~/.vim/{ftdetect,indent,syntax} && for d in ftdetect indent syntax ; do curl -o ~/.vim/$d/scala.vim
https://raw.githubusercontent.com/Huangtuzhi/dot-files/master/scala.vim/scala.vim; done
```

第二步，在~/.vimrc中添加：

```
syntax on
```
