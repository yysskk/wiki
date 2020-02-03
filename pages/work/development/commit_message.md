# Commit message
# TL;DR
- コミットメッセージの書き方
- 使用しているコミットメッセージのprefixとformat

# Motivation
- メッセージの意味解釈をするエネルギーを減らしたい

# Format

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> 変更のまとめ.
|
+-------> Type: #Prefix List を参照.
```

# Prefix List

| prefix | 意味 |
|:---:|:---:|
| feat | プロダクションコードの機能の追加。ツールやCI機能の追加は含まない |
| fix | プロダクションのバグ修正。ツールやCI機能の修正は含まない |
| refactor | リファクタリング。変数名の変更など |
| perf | パフォーマンス改善の変更 |
| test | テストコードの追加変更。プロダクションコードは変更されない |
| chore | 些細な変更 |

# 参照
- [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
- [Angular.js Git Commit Guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)
