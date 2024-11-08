## 项目

使用memos的API构建一个微信朋友圈的页面

https://github.com/jkjoy/memos

## 使用

更改`index.html`中的`host`  `limit` `creatorId`  `twikoo` 即可
```js
                    <script>
                        const memos = {
                            host: 'https://memos.ee', //memos地址
                            limit: '1000',
                            creatorId: '3',
                            domId: '#posts',
                            twikoo: 'https://t.memos.ee',
                        };
                    </script>
```
