# コメントではその内容の前後へ空白文字を置く

いくつかの文字はコメントの開始タグの直後や終了タグの直前に書けません。

悪い例:

    <!--This section is non-normative-->

良い例:

    <!-- This section is non-normative -->


## 解説

コメントは、仕様によるといくつかの制限はあるものの、比較的自由に書けます。その数少ない制限の多くはコメント内の最初と最後に使えない文字（列）があるというものです。具体的には以下の3つです。

1. >で開始
2. ->で開始
3. -で終了

コメントは自身で能動的に書く以外にも様々な形で自動的に挿入される可能性があるものです。そういった場合も含めてこれらの制限を確実に避けるためには、良い例で挙げたようにコメントの最初と最後に*半角空白*を入れるのが良いでしょう。

理論上は半角空白以外の何かしらの文字でも構いませんが、読みやすさや入力のしやすさを考慮すると半角空白が適当です。
