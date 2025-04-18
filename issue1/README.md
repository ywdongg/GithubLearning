# Git 版本控制系統學習大綱

## 目錄
1. [Git 基礎概念](#git-基礎概念)
2. [基本指令](#基本指令)
3. [分支管理](#分支管理)
4. [遠端操作](#遠端操作)
5. [進階技巧](#進階技巧)

## Git 基礎概念
- 什麼是版本控制
- Git 的特點
- 工作區、暫存區和版本庫
- Git 工作流程

## 基本指令
- `git init`: 初始化儲存庫
- `git add`: 加入暫存區
- `git commit`: 提交變更
- `git status`: 檢查狀態
- `git log`: 查看提交歷史

## 分支管理
- `git branch`: 建立/查看分支
- `git checkout`: 切換分支
- `git merge`: 合併分支
- 解決衝突

## 遠端操作
- `git remote`: 管理遠端儲存庫
- `git push`: 推送到遠端
- `git pull`: 從遠端拉取
- `git clone`: 複製儲存庫

## 進階技巧
- `git rebase`: 重整分支
- `git stash`: 暫存修改
- `git tag`: 版本標籤
- `git reset`: 重設修改

---

# Markdown 語法字典

## 標題語法
```markdown
# 一級標題
## 二級標題
### 三級標題
#### 四級標題
##### 五級標題
###### 六級標題
```

## 文字格式
- **粗體**: `**文字**`
- *斜體*: `*文字*`
- ~~刪除線~~: `~~文字~~`
- `程式碼`: ````程式碼```

## 列表
### 無序列表
```markdown
- 項目1
- 項目2
  - 子項目2.1
  - 子項目2.2
```

### 有序列表
```markdown
1. 第一項
2. 第二項
   1. 子項目2.1
   2. 子項目2.2
```

## 連結和圖片
- 連結: `[顯示文字](URL)`
- 圖片: `![替代文字](圖片URL)`

## 表格
```markdown
| 標題1 | 標題2 |
|-------|-------|
| 內容1 | 內容2 |
| 內容3 | 內容4 |
```

## 引用
```markdown
> 這是一段引用文字
>> 這是嵌套引用
```

## 程式碼區塊
````markdown
```python
def hello_world():
    print("Hello, World!")
```
````

## 分隔線
```markdown
---
或
***
```

## 待辦清單
```markdown
- [x] 已完成項目
- [ ] 未完成項目
```