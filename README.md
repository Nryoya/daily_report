# 使用方法  
1. リポジトリのクローン  
    ```zsh  
    // リポジトリのクローン  
    git clone $url  

    // ブランチの作成(アッパーキャメルケース)  
    git switch -c $MyName  

    // READMEファイルの名前変更  
    mv README.md $MyName.md
    ```  
1. 日報用テンプレートを使用し日報を記入  
1. 自身のブランチにpush
    ```zsh  
    // ステージング
    git add $MyName.md

    // コミット
    git commit -m '日報：$MyName'

    //プッシュ
    git push origin $branch
    ```
1. リモートリポジトリで自身のブランチからfor-mergeブランチへpull request  
1. merge  
# 注意事項
- ## .githubディレクトリは変更しないでください。  

# 日報用テンプレート(コピーして使用してください)
## :名前  
- ⚪︎月⚪︎日(⚪︎)  
## 【進捗に関して】  
- example  
## 【取組詳細】  
> - example  
## 【次回の目標】  
- example  
## 【その他相談したいこと】  
- example  