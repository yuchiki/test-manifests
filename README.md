# yurichikiserver Manifest

## setup

- デプロイ先のkube cluster はすでに存在しているものとする。

## ArgoCD のインストール

手元のローカルPCで以下の操作。

- 手元の kubeconfig がデプロイ先のクラスターを向いている状態で、 `task install-argocd` を実行する。
