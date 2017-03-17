![](https://ww2.sinaimg.cn/large/006tNc79gy1fdmbzcpt9qj31kw0wxgov.jpg)

#### 安装

``` bash
hexo init Blog 
cd Blog 
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/angelen10/hexo-theme-apollo themes/apollo
```



#### 启用主题

修改 `_config.yml` 的 `theme` 配置项为 `apollo`:

```yaml
theme: apollo

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```



#### 启用标签云（Tag Cloud）

参照 https://github.com/MikeCoder/hexo-tag-cloud



#### 更新

``` bash
cd themes/apollo 
git pull
```



#### Thanks

- hexo-theme-apollo 作者 [pinggod](https://github.com/pinggod)


- hexo-tag-cloud 作者 [MikeCoder](https://github.com/MikeCoder)



#### License

MIT
