# quant-macro-econ
[『定量的マクロ経済学と数値計算』（2024）日本評論社](https://www.nippyo.co.jp/shop/book/9287.html) のレプリケーション

[サポートページ (Github)](https://github.com/quant-macro-book)

## 環境
[conda-forge](https://conda-forge.org/) で作成してみた。

仮想環境をアクティベート（`conda activate quant-macro`）する際に、エラーが発生するときがある。

```bash
CondaError: Run 'conda init' before 'conda activate'
```

その場合は conda をシェルに紐づけた後に、シェルの設定ファイルを読み込む必要がある。
```bash
$ conda init zsh
$ source ~/.zshrc
```
[参考](https://manabi-corpeng.com/conda-activate-init-error/)