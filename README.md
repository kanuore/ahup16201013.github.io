# github博客写作说明

##　构建blob框架

１.申请github账号：，同时以ｇithub账号名为名，创建一个仓库，在设置中自动开启域名GitPage．这一步其实已经可以访问自己的网站了，但是还没有什么具体的内容．

２.下载别人blob框架，再上传到自己建立的那个仓库下，下载地址<https://github.com/Simpleyyt/jekyll-theme-next>

３.在本地文件中修改_config.yaml文件，主要修改：

`title: ＃全局标题` 　

`subtitle: ＃全局标题下一句话`

`description: ＃个人头像下一句话 `

`author：＃头像名字'`

`language: zh-Hans`

４.这样一个模板网站就建立了，有一些内容了．

５.主要是写博客，没必要注意多余的东西，关注_post文件夹，博文都在文件夹中，但是要按照一定的格式来，格式参照模板中的格式，框架会自动抽取博文内容，给予显示．只需要在文件夹中新建文件写就行了，然后push

## github_mardown注意

１．段落：唯一决定两行文字是否是段落的,就在于这两行文字之间是否有空行．所以在这个编辑器中，每当新起一段，都会自动加入空行，而不是在尾部插入空格．

２．缩进问题,中文书写总要有缩进才好看,缩进的方式网上有很多内容,经过实验,全角输入下，两个空格能实现在段首缩进

3.# 在_config中设置 excerpt_separator＂<＂!-- more --＂>＂截取以上部分，用于首页文章简介显示！




　　
