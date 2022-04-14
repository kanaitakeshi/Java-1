# Java-1　基本文法を使った自己紹介プログラム

### 【概要】
入力データを受け取り、処理を加えた後に出力する

### 【詳細】  
1. 「何人分の情報を入力しますか？」に対し、数字を入力すると◯人目を表示する
2. 氏名、年齢、身長、体重を入力すると、成年か未成年かを判別し、BMIを計算して出力する
3. 最後に最初に入力した◯人中の最高年齢と平均年齢を表示する

### 【文法】
- 文字列の表示【 System.out.println(); 】
- 入力値の受け取り【 scanner.next(); scanner.nextInt(); scanner.nextDouble(); 】
- 文字列の連結【 + 】
- 条件分岐【 if文 】
- クラス分けとメソッド【 class Main, class Person 】【 printData(); fullName(); bmi(); isHealthy(); 】
- BMIを四捨五入【 Math.round(bmi); 】
- 論理演算子と真偽値【 && boolean 】
- 繰り返し処理【 for文 】
- 最高年齢【 for文の中のif文でmaxAgeを更新 】
- 平均年齢【 for文の中でtotalAgeに加算、for文の外で人数nで割る 】
