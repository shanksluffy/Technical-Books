# Technical-Books
some useful technical books

1. 一次性安装
git lfs install
2. 声明哪些文件走 LFS
git lfs track "*.pdf"
这一步会写入 .gitattributes，必须把它也提交，否则别人 clone 后不会走 LFS：
git add .gitattributes
3. 正常提交并推送
git add .
git commit -m "add books"
git push
