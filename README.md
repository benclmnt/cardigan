How to import CSV into sqlite

```
sqlite> .mode csv
sqlite> .separator ";" // if needed
sqlite> .import <path/to/file> <table name>
```