# 名言BOT for Growthers

発言者と発言内容を紐づけて保存する。  
ID、発言者で検索することが可能。  

## ToDo

- [x] 名言の追加
- [ ] 名言の削除
- [ ] 名言を発言者で検索する
- [ ] 名言をIDで取得する
- [x] 名言の登録総数を取得する

削除について  
IDの割り振りを、レコードの総数 + 1　にしているので、レコードを完全に削除してしまうとIDの割り当てに整合性が取れなくなってしまう。  
どうにかして最新の名言IDを取得できないか？