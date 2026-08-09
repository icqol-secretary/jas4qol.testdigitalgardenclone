```dataview
LIST WITHOUT ID file.lists
WHERE file.path = this.file.path
FLATTEN keywordBulletList as file.lists
```