jvmtipack
======
これはなに？
----
これはjvmtiの勉強用のプロジェクトです．少しずつサンプルを増やしていきます．ちなみに作者はC/C++初心者です．

ディレクトリ構成
----
- agent  
  c++で書かれたjvmti関係のプロジェクトが入ります
- bin  
  jvmtiのコンパイルシェル等が入ります
- java  
  jvmtiのエージェントを試してみる為のjava関係のプロジェクトが入ります

お品書き
----
### 初級編(基本的なコールバックをいくつか)
#### VM開始＆初期化＆終了イベント
- プロジェクト: VMTrace
- agentへのコマンドラインオプションの渡し方等も

#### メソッドの開始と終了イベント等
- プロジェクト: MethodTrace

#### スレッドの開始＆終了
- プロジェクト: ThreadTrace

#### クラスのロードとアンロードイベント等
- プロジェクト: ClassLoadTrace


### 中級編

#### クラス名の取得とか

#### メソッド名の取得とか

#### フィールドアクセスイベント
- プロジェクト: FieldTrace


### 上級編
#### フィールド名の取得とかスレッド名の取得とか

#### 局所変数
- プロジェクト: HeapTrace

Q&A
----
Q.エージェントをコンパイルできないんだけど？

Q.コンパイルしたけど使い方わかんないんだけど？

Q.どうしたらいいの？


