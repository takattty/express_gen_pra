# express_gen_pra
書籍Node.js入門 chapter4 Expressのgeneratorを触ってみた。



## アロー関数について
比較

```
const normalFunc = function(x) {
  console.log(x);
 }
const arrowFunc = (y) => {
  console.log(y);
}

normalFunc('今までの関数');
arrowFunc('アロー関数');
```

これが違い。
