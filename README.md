# TCM Books (中医古籍库)

Traditional Chinese Medicine classic books and literature repository.

## 包含内容

- 黄帝内经
- 伤寒论
- 金匮要略
- 四诊宝鉴
- 本草纲目

## 结构

```
├── books/              # 古籍文本
├── chapters/           # 章节内容
└── metadata.json       # 元数据
```

## 使用

```typescript
const books = await fetch('https://cdn.jsdelivr.net/gh/renhanxu/tcm-books@main/metadata.json')
```

## 许可证

MIT License
