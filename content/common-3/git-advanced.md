先看兩個特別的檔案

## `README.md`
* 「讀我」的意思
* `.md` 表示語法為 Markdown
* 是一個特殊的檔案；會出現在專案的首頁

## `LICENSE`
* 「授權條款」的意思
* 這個專案採用哪種授權 (MIT, Apache, GPL, ...)

---

## `git branch`
「分支」

---

## `git reset`
「回到過去」

---

## `git checkout`
「岔出世界線」

會產生 `detached state`:

```
Note : checking out '30c9e94'.
You are in 'detached HEAD' state. ...
git checkout -b <new-branch-name>

HEAD is now at 30c9e94...
```

有三個選擇：

1. 回到本來的 branch: `git checkout <branch>`
2. 建立新的 branch: `git checkout -b <new_branch>`
3. 另外一條世界線: `git commit`

---

## `git merge <branch>`

把**目前的 branch** 合併進指定的 branch 裡

順利的話：git 會自動合併兩邊
不然：衝突 (conflict)

---

## 練習 ◝(　ﾟ∀ ﾟ )◟

------

## GitHub Pages

迅速把一個專案變成靜態網頁！

---

### User Site
>&lt;username&gt;.github.io

例如部落格
建立一個 repo 叫作 `<username>.github.io`

### Project Site
> &lt;username&gt;.github.io/repo-name

例如專案的 demo
建立一個 branch 叫作 `gh-pages`

先確定 GitHub 帳號有驗證 Email

---

## 練習 ( ～'ω')～

---

## 自動產生精美網站(?)

* GitHub 產生器
* 現成的服務 ([挑一個好用的](https://www.staticgen.com/))
