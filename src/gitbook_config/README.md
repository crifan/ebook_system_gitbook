# 配置Gitbook

Gitbook中的配置内容，主要就是一个`book.json`。

此外和配置算有关的，还有一个文件夹结构，即相关的目录、内容、图片等组织结构。

## book.json配置

最开始弄了个基本的book.json：

[【整理】Gitbook中的book.json参数配置](http://www.crifan.com/gitbook_book_json_parameter_config)

最后基本定型的book.json如下：

```json
{
  "title": "编程习惯和代码风格",
  "description": "介绍为何要和如何形成良好的编程习惯和代码风格",
  "author": "Crifan Li <admin@crifan.com>",
  "language": "zh-hans",
  "gitbook": "3.2.3",
  "root": "./src",
  "links": {
    "sidebar": {
      "主页": "http://www.crifan.com"
    }
  },
  "plugins": [
    "theme-comscore",
    "-lunr",
    "-search",
    "search-plus",
    "disqus",
    "-highlight",
    "prism",
    "prism-themes",
    "github-buttons",
    "splitter",
    "-sharing",
    "sharing-plus",
    "tbfed-pagefooter",
    "expandable-chapters-small",
    "ga",
    "donate",
    "sitemap-general",
    "copy-code-button",
    "alerts",
    "toolbar-button"
  ],
  "pluginsConfig": {
    "theme-default": {
        "showLevel": true
    },
    "disqus": {
      "shortName": "crifan"
    },
    "prism": {
      "css": [
        "prism-themes/themes/prism-atom-dark.css"
      ]
    },
    "github-buttons": {
      "buttons": [
        {
          "user": "crifan",
          "repo": "program_code_style",
          "type": "star",
          "count": true,
          "size": "small"
        }, {
          "user": "crifan",
          "type": "follow",
          "width": "120",
          "count": false,
          "size": "small"
        }
      ]
    },
    "sharing": {
      "douban": false,
      "facebook": true,
      "google": false,
      "hatenaBookmark": false,
      "instapaper": false,
      "line": false,
      "linkedin": false,
      "messenger": false,
      "pocket": false,
      "qq": true,
      "qzone": false,
      "stumbleupon": false,
      "twitter": true,
      "viber": false,
      "vk": false,
      "weibo": true,
      "whatsapp": false,
      "all": [
        "douban",
        "facebook",
        "google",
        "instapaper",
        "line",
        "linkedin",
        "messenger",
        "pocket",
        "qq",
        "qzone",
        "stumbleupon",
        "twitter",
        "viber",
        "vk",
        "weibo",
        "whatsapp"
      ]
    },
    "tbfed-pagefooter": {
      "copyright": "crifan.com，使用<a href='https://creativecommons.org/licenses/by-sa/4.0/deed.zh'>知识署名-相同方式共享4.0协议</a>发布",
      "modify_label": "该文件修订时间：",
      "modify_format": "YYYY-MM-DD HH:mm:ss"
    },
    "ga": {
      "token": "UA-28297199-1"
    },
    "donate": {
      "wechat": "https://www.crifan.com/files/res/crifan_com/crifan_wechat_pay.jpg",
      "alipay": "https://www.crifan.com/files/res/crifan_com/crifan_alipay_pay.jpg",
      "title": "",
      "button": "打赏",
      "alipayText": "支付宝打赏给Crifan",
      "wechatText": "微信打赏给Crifan"
    },
    "sitemap-general": {
      "prefix": "https://book.crifan.com/gitbook/program_code_style/website/"
    },
    "toolbar-button": {
      "icon": "fa-file-pdf-o",
      "label": "下载PDF",
      "url": "http://book.crifan.com/books/program_code_style/pdf/program_code_style.pdf"
    }
  }
}
```

## 文件结构

之前自己折腾的过程：

[【记录】gitbook优化book的文件组织结构](http://www.crifan.com/gitbook_optimize_book_file_foler_structure)

现在分享出自己的，供参考：

TODO：把自己的gitbook的

各个文件夹和文件的结构整理出来

且贴出来：

SUMMARY.md

README.md

等

相关md的基本内容，供参考。