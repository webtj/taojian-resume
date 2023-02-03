---
# 语言 （可选）
lang: zh-cn
# 网页关键词和描述
keywords: 简历主题,Hexo主题,简历模板
description: 精之又精,习与性成
# 简历标题
resume_title: Tao Jian's Resume
# 应聘者姓名
name: Tao Jian
avatar: https://vkceyugu.cdn.bspapp.com/VKCEYUGU-0d01685b-3633-4c56-94c6-f3ea1bbccf64/4cdc2b60-574a-4af6-89b5-5fe2e1777bfa.jpeg
# 联系方式
contact:
  # github
  - icon: fab fa-github
    text: https://github.com/webtj
    url: https://github.com/webtj
  - icon: fas fa-globe-asia
    text: https://taojian.icu
    url: https://taojian.icu
  # 邮箱
  - icon: fas fa-envelope
    text: taojian@petalmail.com
    url: mailto:taojian@petalmail.com
  # 电话号码
  - icon: fas fa-phone-alt
    text: 19951755275
    url: tel:19951755275
# PDF下载链接
download:
  title: 下载本站源码
  icon: fas fa-download fa-fw
  url: https://github.com/xaoxuu/resume-docs
---

{% raw %}
<center>
<a href='/'>简体中文</a> | <a href='/en/'>English</a>
</center>
{% endraw %}



## <i class="fas fa-flag"></i> 开始使用

由于本主题与普通 Hexo 主题有较大区别，建议请直接下载本站的源码，参考源码进行改写。

- 本站源码：https://github.com/xaoxuu/resume-docs
- 主题源码：https://github.com/xaoxuu/hexo-theme-resume

也可以创建全新的博客，通过 `npm` 命令安装：

```bash
npm i hexo-theme-resume

## <i class="fas fa-user-graduate"></i> 教育背景

**XX大学 X学院 X系 X专业 X年毕业**


## <i class="fas fa-user-tie"></i> 工作经验


#### 2000年 ~ 至今：XX公司

- 主要负责XXX
- 也负责XXX


#### 1900年 ~ 2000年：XX公司

- 主要负责XXX
- 也负责XXX

#### 1800年 ~ 1900年：XX公司

- 主要负责XXX
- 也负责XXX


## <i class="fas fa-award"></i> 精选项目


{% raw %}
<btns rounded>
<a href='https://apps.apple.com/cn/app/heart-mate-pro-hrm-utility/id1463348922?ls=1'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/heartmate/icon.png'>
  xxxx
</a>
</btns><br>
{% endraw %}


### A项目

#### 2000/01 ~ 2019/01：于XX公司开发，团队项目，维护至今

啦啦啦

### B项目

#### 1900/01 ~ 2000/01：于XX公司开发

啦啦啦

### C项目

#### 1800/01 ~ 1900/01：于XX公司开发

啦啦啦

## <i class="fab fa-github"></i> 开源贡献


### Volantis

#### 2017 ~ 至今，xxxxxxxxxxxx

- 1
- 2
- 3
- 4

<fancybox>
<img src='https://mp-0d01685b-3633-4c56-94c6-f3ea1bbccf64.cdn.bspapp.com/VKCEYUGU-0d01685b-3633-4c56-94c6-f3ea1bbccf64/4cdc2b60-574a-4af6-89b5-5fe2e1777bfa.jpeg' />
</fancybox>

## <i class="fas fa-phone-alt"></i> 与我联系

目前状态为：在职，考虑换工作，100年内可到岗。

<i class="fas fa-envelope fa-fw"></i> your email
<i class="fas fa-phone-alt fa-fw"></i> 1xxxxxxxxxx


## 主题配置

```yaml
cdn:
  # These base libraries cannot be deleted
  jquery: https://cdn.jsdelivr.net/npm/jquery@3.4.1/dist/jquery.min.js
  vue: https://cdn.jsdelivr.net/npm/vue@2.5.21/dist/vue.min.js
  # When these CDN resources are deleted, local resources are loaded.
  common: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/common.js
  escape: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/css.escape.js
  smooth_scroll: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/smooth-scroll.min.js
  css: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/css/style.min.css
  # Optional plug-in: image zoom
  fancybox:
    css: https://cdn.jsdelivr.net/npm/@fancyapps/fancybox@3.5.7/dist/jquery.fancybox.min.css
    js: https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.7/dist/jquery.fancybox.min.js

# robots meta tag
robots: noindex,nofollow

# the footer of your site
copyright: '[Copyright © 2017-2020 Mr. X](https://xaoxuu.com)'
```

## 评论

{% raw %}
<script src="https://utteranc.es/client.js"
        repo="webtj/my-resume"
        issue-number="18"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
{% endraw %}
