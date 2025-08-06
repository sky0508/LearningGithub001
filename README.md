# LearningGithub001

## Gitブランチの作成方法

### 1. git branch コマンド
新しいブランチを作成しますが、現在のブランチは変更されません。
```bash
git branch <ブランチ名>
```
例: `git branch feature/new-feature`

### 2. git checkout -b コマンド
新しいブランチを作成して、同時にそのブランチに切り替えます。
```bash
git checkout -b <ブランチ名>
```
例: `git checkout -b feature/another-feature`

### 3. git switch -c コマンド（推奨）
Git 2.23以降で利用可能。新しいブランチを作成して、同時にそのブランチに切り替えます。
```bash
git switch -c <ブランチ名>
```
例: `git switch -c feature/modern-feature`

### ブランチの確認
```bash
# ローカルブランチの一覧
git branch

# すべてのブランチ（リモート含む）の一覧
git branch -a
```

### ブランチの切り替え
```bash
# 従来の方法
git checkout <ブランチ名>

# 新しい方法（推奨）
git switch <ブランチ名>
```
