# Open-IMP
はじめてのオープンソース（開発協力歓迎）

```
// 大事なことリスト
const preciousArr = ["負けない", "投げ出さない", "逃げ出さない", "信じ抜く"]

// 涙を見せていいか否か
function ArrowShowTears(CurrentStatus, memory) {
  // 現在のステータス
  if(CurrentStatus == "ダメになりそう"){
    // 1番大事なことを取得
    var mostPrecious = GetMostPrecious(CurrentStatus)
    // 忘れなければ
    if(memory.includes()){
      // 涙を見せることを許可
      return true
    } 
  }
  return false
}

//TODO:1番大事なことを取得
function GetMostPrecious(CurrentStatus){
  // １つに絞る方法が見いだせずランダム処理しています
  return preciousArr[Math.floor(Math.random() * preciousArr.length)];
} 
```
