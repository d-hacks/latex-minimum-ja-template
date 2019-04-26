# Japanese Minimum LaTeX Template for Overleaf

Overleaf上で日本語でLaTeXの文章を作成するための最小限のファイル群です．  

## インストール
- このレポジトリをcloneする．
```
git clone https://github.com/d-hacks/latex-minimum-ja-template.git
```
- 不要なファイル群を削除する
```
cd latex-minimum-ja-template
rm -rf .git
rm LICENSE README.md
```
- zipファイルを作成
```
zip ja-tmplate.zip -r ./
```
- OverleafにUpload  
[Overleaf](https://www.overleaf.com/project)へアクセスして，Ner Project -> Upload Projectで先ほど作成したja-template.zipファイルをUpload．
- Compilerの変更  
左上のMenu -> CompilerのところをLaTeXに変更する．  
main documentはmain.texに設定．
