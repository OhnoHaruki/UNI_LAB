## このリポジトリ内の主なファイルの説明
### Sort_asian_face01.py
-顔認証AIの試し作成を行なった。JAFFEデータセットを用いてその中の顔写真が同一人物であるがどうか判定し、その画像間のスコアをcos類似度を用いてスコア化した、
### Sort_asian_face02.py
-転移学習を用いてVGGFace2のデータで学習されたものを使用して、chapt06-model1.pthという学習済みモデルを作成する。
### Sort_asian_face03.ipynb
-capt06-model1.pthと、Sort_asian_face02.pyで用いたfinal scoreにある閾値(threathold)である0.58を用いて  
顔認証システムの開発を行う。このコードを実行すると画面上に画面が立ち上がり、顔の登録と、画面に映る顔が登録済みのユーザか否かを判定する。  
顔の情報はベクトルデータとして残されている。

