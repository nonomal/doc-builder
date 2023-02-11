# h1

## h2

### h3

[链接](https://baidu.com)

段落*斜体*段落**粗体**段落**_加粗斜体_**段落~~删除线~~段落==mark==段落`行内代码`段落段落段落段落段落段落段落段落段落段落段落
段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落段落

emoji 表情 ❤😁

脚注 1 链接[^first]。

脚注 2 链接[^second]。

行内的脚注^[行内脚注文本] 定义。

重复的页脚定义[^second]。

- 列表
- 列表
  - 列表
  - 列表
- [ ] 任务
- [x] 任务

![](https://temp.im/100/4CD964/fff '图片 title')

![](https://temp.im/100/4CD964/fff '自定义尺寸' =100x200)

> 引用引用引用引用
> 引用引用引用引用
> 引用引用引用引用

```typescript
const randomString = (len?: number): string => {
  len = len || 32;
  const t = 'ABCDEFGHJKMNPQRSTWXYZabcdefhijkmnprstwxyz2345678';
  const a = t.length;
  let n = '';
  for (let i = 0; i < len; i++) {
    n += t.charAt(Math.floor(Math.random() * a));
  }
  return n;
};
```

[//]: # (分割线)

---

::: info 容器

info

:::

::: note 容器

note

:::

::: tip 容器

tip

:::

::: warning 容器

warning

:::

::: danger 容器

danger

:::

| 表头 | 表头 |
|-----|-----|
| 单元格 | 单元格 |
| 单元格 | 单元格 |
| 单元格 | 单元格 |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

[^first]: 脚注 **可以包含特殊标记**

    也可以由多个段落组成

[^second]: 脚注文字。


