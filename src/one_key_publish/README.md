# 一键发布

后来为了便于管理手上如此多（几十个）的`gitbook`的电子书，所以去优化结构，利用`Makefile`去实现生成`gitbook`、代码上传、上传/发布生成的文件等操作，实现了一键发布（到自己的网站和github的pages上）的效果。

详见：

[【已解决】搭建Gitbook环境使得可以发布book到crifan.com上](http://www.crifan.com/build_gitbook_environment_for_publish_books_to_crifan_com)

[【记录】Mac本地搭建Gitbook环境](http://www.crifan.com/mac_local_build_gitbook_environment)

[【记录】把http_summary的gitbook上传到二级域名book.crifan.com中](http://www.crifan.com/gitbook_upload_to_sub_domain_book_crifan_com)

且后来，把自己的gitbook的整套环境做成一个模板了，需要的可以去参考：

[crifan/gitbook_template: 演示如何使用crifan的gitbook的模板去创建自己的gitbook电子书](https://github.com/crifan/gitbook_template)

对应的`Makefile`在[GitbookCommon.mk](https://github.com/crifan/gitbook_template/blob/master/GitbookCommon.mk)，需要的可以去参考。