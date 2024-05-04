---
completed: true
created: 2024-04-11
tags:
  - project
Areas: 
---

# Win10学习使用日志

Area:: [[]]
Status:: #done

___

## Description
> [!info] 项目描述: 这个项目是关于什么的？目标？特性？学习成果？

---

## Notes
> [!tip] 项目的笔记和文档
```dataviewjs
dv.table(["Doc", "创建时间"],
     dv.pages()
    .where(p => 
      p.file.folder == dv.current().file.folder
    )
    .sort(p => 
      p.created, 'asc'
    )
    .map(p => 
      [p.file.link,  p.created.toFormat('yyyy-MM-dd')]
    )
)
```
