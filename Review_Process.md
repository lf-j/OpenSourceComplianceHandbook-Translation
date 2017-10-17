# レビュー手順
レビューおよび変更提案をされる場合には、以下のレビュー手順に従って下さい。


## レビュー・変更提案　方法１　（OmegaTとPull Requestで変更提案）：

* [git]
    * gitを使って自分の作業環境（PC等）にCloneを作ります
    * git上で適当な名前のブランチ（Review_xxxなど）を作成します

* [Omega-T]
    * 上記ブランチでOmegaT上でレビューをします
    * 変更提案をまとめます
    * OmegaTで変更を実施します
    * 変更作業後に、OmegaTでTargetを生成します
  
* [git]
    * git上で作成したブランチでPull Request作成します
        * 題名、概要説明、理由を記載します
        * Pull Requestには1案件のみを入れます
        * 依存関係のある複数のPull Requestを作成する場合には、依存関係に従って、適切な順番でPull Requestを作成します
    * Pull Requestを提出します

## レビュー・変更提案　方法２　（Issueで変更提案）：

* [git]
    * gitを使って自分の作業環境（PC等）にCloneを作ります

* [Omega-T]
    * 上記ブランチでOmegaT上でレビューをします
    * 変更提案をまとめます

* [git]
    * git上のMasterブランチでIssueを記載します
        * 題名、概要説明、理由を記載します
        * Issueには1案件のみを入れます
    * Issueを提出します


## メンテナー　方法１の場合：

* [git]
    * Pull Requestの受領可否を判断します
    * Pull Requestのコメントに判断結果を記入します
    * 受け取る場合には、Merge作業を行います

## メンテナー　方法２の場合：

* [git]
    * Issueの受領可否を判断します
    * Issueのコメントに判断結果を記入します
    * 受け取る場合
        * メンテナーが自分の環境でブランチを作成します
        * メンテナーがOmegaTを使って変更作業を行います
        * メンテナーが自分の環境でPull Requestを作成し提出します
        * メンテナーがPull RequestをMergeします

## その他参考情報

* [GitHub] 
    * WatchをOnにするとメールやGitHub上で通知が来ます
