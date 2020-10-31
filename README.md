# KurukuruTimer
勉強や仕事のために見やすいタイマーを作りました。  
サーボモータと7セグメントLEDディスプレイ(以下7セグ)、圧電スピーカー、タクトスイッチ、ArduinoUNOR3互換品で作りました。  

# 仕様

電源入れる  
↓  
ビープ音  
7セグF表示  
サーボモーターテスト動作(45度傾いて戻る)  
↓  
シリアルモニタでボタンの状態確認ON  
↓  
ボタン取得モード20秒  
7セグS表示(SelectのS)  
ボタンを押すとビープ音＋7セグに設定時間表示  
押さない→60分タイマー  
1回押す→10分タイマー  
2回押す→30分タイマー  
3回押す→60分タイマー  
4回押す→90分タイマー  
5回以上→テストモード(1分タイマー)  
↓  
7セグC表示(CheckedのC)
サーボモータ180度  
タイマー開始  
↓  
少しずつサーボ動く  
↓  
時間になると7セグE表示(ENDのE)して人形の夢と目覚めが鳴って終了。  


## copyright 2020 usuyuki