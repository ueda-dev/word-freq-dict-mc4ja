# WORD-FREQ-DICT-MC4JA
## このデータについて
MC4の日本語サブセットから抽出した、単語出現回数の辞書です。 

## データ形式について
単語と出現回数がキー/バリューの関係になったJSON形式です。 
100個のファイルに分割されており、サイズは5MB前後。 
dataディレクトリ以下に格納されています。 
```
{
    "hoge": 20,
    "huga": 30,
    ...
}
```