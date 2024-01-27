# weather_check
predicateのweather_checkに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】weather_checkで天候を条件にする【predicate】](https://natsumake.com/weather_check/)』を参考にしてください。

<h3>使い方</h3>

導入後、適宜weatherコマンドで天候を変更してください。

雨であるかどうかは
```/execute if predicate sample:rain run give @a diamond 1```

雷雨であるかどうかは
```/execute if predicate sample:thunder run give @a diamond 1```

晴れである（雨でも雷雨でもない）かどうかは
```/execute if predicate sample:clear run give @a diamond 1```

で確認できます。
