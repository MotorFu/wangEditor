# 当前遗留的一些问题

- 删除掉`./release`之后，执行`npm run release`会报错，原因是`fonts`文件没拷贝全，就要去替换`css`中的字体文件为`base64`格式，导致找不到文件。
- 针对编辑区域的`max-height`和`min-height`做一些处理，而且和全屏还不能通用
- 先点击'B'再输入内容这种形式，前期先支持 webkit 和 IE，火狐的支持后面再加上
- Panel 在右上角增加一个“关闭”按钮
- src/js/editor/Bar 改为 Progress，仅供上传图片使用


项目徽章 https://github.com/EyreFree/GitHubBadgeIntroduction
