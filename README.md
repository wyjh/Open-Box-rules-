# Open-Box rules

自用规则集，只给自己在 [Open-Box](https://github.com/liandu2024/Open-Box) 面板里分流用。

- 按需随手加，不保证齐全、不保证及时更新
- 只保证自己环境能用，不保证兼容其它面板 / 客户端
- 请勿转载

## 列表

| 文件 | 内容 |
| --- | --- |
| `tmdb.list` | TMDB（The Movie Database）全部域名：主站 / API / 图片 / 文件 / CDN |

## 用法

面板 → 站点集 → 添加规则 → 类型选「规则集链接」，粘 raw 地址：

```
https://raw.githubusercontent.com/wyjh/Open-Box-rules-/main/tmdb.list
```

raw 拉不动时换镜像（内容一致）：

```
https://cdn.jsdelivr.net/gh/wyjh/Open-Box-rules-@main/tmdb.list
https://ghfast.top/https://raw.githubusercontent.com/wyjh/Open-Box-rules-/main/tmdb.list
```

> 必须用 raw / 镜像地址。填 GitHub 的 `/blob/` 网页地址会拉下一整页 HTML，预览必然是 0 条。

保存后点行尾「立即更新」让内核立刻重拉；不点就等下次启动内核时更新（每 24 小时一次）。只想一次性落地、之后不依赖外链，可以用「导入规则」把明细导进站点集（≤200 条）。
