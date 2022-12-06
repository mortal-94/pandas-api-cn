# pandas-api-cn
翻译计划，pandas中文api参考文档
## 开发流程
1. 浏览器下载 Allow CORS: Access-Control-Allow-Origin 插件解决跨域问题（有该插件体验感更好，查阅也一样）
2. 从 [官网](https://pandas.pydata.org/docs/reference/index.html) 上保存HTML文件
3. 用你的IDE的查找-替换功能，将 `../` 或 `../../` 转成 `https://pandas.pydata.org/docs/`
4. 在HTML文件的 `main` 便签区域进行翻译即可
5. 翻译完成后，在 `footer` 标签中添加，格式如下：
    ```html
    <div class="footer-item">
    译者：{yourname}
    </div>
    </div>
    ```

> 在 Official 文件夹下有保存的 api，说明翻译完成或正在翻译。

[入口](https://mortal-94.github.io/pandas-api-cn/Personal)