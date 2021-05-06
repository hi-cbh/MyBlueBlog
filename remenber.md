
## 后端
1. 首先是SQL

model.py

```
Admin # 管理者
    - id
    - username 
    - password_hash
    - blog_title
    - blog_sub_title
    - name
    - about
    
Category # 种类类型
    - id
    - name
    - posts # 关联文章
    
Post # 文章
    - id
    - title
    - body
    - timestamp
    - can_comment 
    - category_id # 类型id
    - category # 关联类型
    - comments # 关联评论
    
Comment # 评论
    - id
    - author # 作者
    - email
    - site
    - body 
    - from_admin #？
    - reviewed 
    - timestamp
    - replied_id
    - post_id
    - post
    - replies
    - replied
Link
    - id
    - name
    - url
```