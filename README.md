# minigrep
文件中搜索内容
# 如何使用
```js
IGNORE_CASE=1 cargo run -- searchstring example-filename.txt
```
例如：
```js
$ IGNORE_CASE=1 cargo run -- to poem.txt
```
结果
```js
Searching for to
In file poem.txt
Are you nobody, too?
How dreary to be somebody!
To tell your name the livelong day
To an admiring bog!
```