# 简易留言微信小程序

## 目的在于小程序的学习，涵盖了页面展示，数据绑定，数据库的增删查，云函数的编写和调用


## 日志（截至2019-9-9）
- 添加开发日志页面。
- 留言添加空值判断，删掉了重复空值的记录，略微美化了留言界面。
- 留言按钮设置了15秒的不可用时间，防止再有人滥用。<
- 留言改为最新的留言显示在最前方。。搞笑的是用不用的参数获取逆序的顺序竟然不一样..把我搞懵了
- 图片展示改为最新上传的图片显示在最前方。
- 图片展示添加用户昵称和上传时间。

## 近期
- 图片展示将可以点击图片查看大图。
- 图片展示将可以可以单独预览自己上传的图片。

## tip
- 未来（看心情）页面将使用 WeUI 组件进行重新开发。tabbar，按钮等等的改动。
- 不做留言的回复功能！不做、不做！除非要做社区，不然回复没有任何意义。
    


### 微信预览

![留言](https://www.cnblogs.com/images/cnblogs_com/famine/1451354/o_gh_25b2f1b6bcd7_258.jpg)

### 相关操作，参考我的博文：

- [地址](https://www.cnblogs.com/famine/p/10716787.html)
- [即将出现关于图片展示的一系列问题的说明文章]

### 存在问题:

- 删除留言的权限未处理
- 关于留言模块不同条件的逆序查值得顺序的不同问题。

## 参考文档

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

