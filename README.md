# kotoba_player
テキストをこねこねして遊ぶライブラリ

# discussion
つねに、未知語であるかどうか気にかけないといけなくて、そのせいでシンプルな実装が難しい。
例えば、名詞以外について処理をしたいとき、未知語を名詞とするのか、名詞以外とするのか任意の処理について定めるのは難しい。
名詞に対して伏せ字処理をして匿名性を高めたいときは、安全のために未知語も伏せて欲しい。しかし、parrot関数のようにオウム返しをしたい場合は、未知語は対象から外す方が望ましい。