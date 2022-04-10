## Java-1　自己紹介プログラム

【概要】  
1. 人数を入力　→　n人目を表示する
2. 名前、名字、年齢、身長、体重を入力　→　名前、年齢（成年か未成年か）を表示、BMIを計算（健康か不健康か）を表示する
3. n人中の最高年齢と平均年齢を表示する

【内容】
- 文字列の表示【 System.out.println("xxx"); 】
- 入力値の受け取り【 scanner.next(); scanner.nextInt(); scanner.nextDouble(); 】
- 文字列の連結【 + 】
- 条件分岐【 if文 】
- クラスを分けメソッドをまとめる【 class Main、 class Person 】【 printData()、fullName()、bmi()、isHealthy() 】
- BMIを四捨五入【Math.round(bmi);】
- 論理演算子と真偽値【&& boolean】
- 繰り返し処理【for文】
- 最高年齢【for文の中でint maxAgeを更新】
- 平均年齢【for文の中でtotalAgeに加算、for文の外で人数nで割る】
