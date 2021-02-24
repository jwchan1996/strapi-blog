# Strapi application

A quick description of your strapi application

## tips

主要集合有 Post Tag User 三个，下面是集合字段：

Post

```sh
title # 文本
content # 富文本
cover # 多媒体，只勾选 image，但是表现为数组（缺陷）
is_publish # 布尔值
tags # 关联 多对多关系
user # 关联 一对一
```

Tag

```sh
title # 文本
posts # 关联 多对多关系
```

User

```sh
# 自有，需要新建一个用户
```

### 关于权限

认证的权限：一般勾选所有操作权限

公开的权限：一般只读，每个集合都要勾选开放