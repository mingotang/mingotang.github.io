---
title: My Personal Blog
date: 2015-10-19 10:34:12
---

## Hexo使用方式

### Create a new post

``` bash
$ hexo new [layout] title
$ hexo n
```
#### Layout

|Layout|Path|
|---|---|
|post|source/_posts|
|page|source|
|draft|source/_drafts|

### Drafts

```bash
$ hexo publish [layout] title
```

More info: [Writing](https://hexo.io/docs/writing.html)

---

### Run server

``` bash
$ npm install hexo-server --save

$ hexo server
$ hexo s

$ hexo server -p 5000

$ hexo server -i 192.168.1.1
```

More info: [Server](https://hexo.io/docs/server.html)



---

### Generate static files

``` bash
$ hexo generate
$ hexo g
```

### Watch for File Changes

```bash
$ hexo generate --watch
```

More info: [Generating](https://hexo.io/docs/generating.html)

---

### Deploy to remote sites

``` bash
$ hexo deploy
$ hexo d
```

### Deploy After Generating
```bash
$ hexo generate --deploy
$ hexo deploy --generate
```

More info: [Deployment](https://hexo.io/docs/deployment.html)