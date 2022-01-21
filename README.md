# mastermind-4-digit-guessing-game-
complete mastermind algorithm 

this is an algorithm for guessing 4 digit number(ex. 1234, 4662)
but the 4 digit must be smaller than 6667 and more than 1111
if we suppose the number is abcd, than 0< a,b,c,d < 7

the first guess is 1122 and this is a default.

in the algorithm, you will be asked to enter your first guess's hit and blow
if you enter those number, the algorithm will give you the optimal 2nd guess.

then you will be asked to enter your second guess's hit and blow and it goes on.

theoretically, you will be able to guess correctly in less than 6 tries.

in the algorithm, you will be asked to enter your first guess's hit and blow

このアルゴリズムは４桁の数字を見つけるためのもので、遊び大全のヒットアンドブローで使われることを目的としています。
Pythonで動くのでpythonをダウンロードして、コードをコピペして、そのファイルを実行すれば（macだとterminal）動きます。
　
アルゴリズムは各位が１以上６以下の４桁の数字を当てるようになっています。
遊び大全では６つの色がありますが、１は青、２は赤、３は緑、４は黄色、５はピンク、６は白を表します。

以下の手順で動かします。
1.	遊び大全で青青赤赤と入力（最初の推測は1122（青青赤赤）とデフォルトでなっています。）
2.	何らかのヒットアンドブローを得る。（例えばヒットが２でブローが０）
3.	2,0と入力してenterきーを押す
4.	２回目の推測として最適なものをアルゴリズムが弾き出してくれる。
5.	これを遊び大全で入力して何らかのヒットアンドブローを得る。（例えばヒットが３でブローが０）
6.	以下手順３−５を繰り返す。
