# PostgreSQL on Kubernetes Sample Manifests

## 環境構築
各種ツールはrtx(asdf)を利用してインストールする
### rtxのインストール
https://github.com/jdx/rtx
``` bash
curl https://rtx.pub/rtx-latest-macos-arm64 > ~/bin/rtx
chmod +x ~/bin/rtx
```

### 各種ツールのインストール
```bash
rtx plugin add kind https://github.com/reegnz/asdf-kind.git
rtx plugin add kubectl https://github.com/asdf-community/asdf-kubectl.git
rtx plugin add pluto https://github.com/FairwindsOps/asdf-pluto.git
rtx plugin add kubesec https://github.com/vitalis/asdf-kubesec.git
```

## Todo
- [] 
- [] 
