# view-triangle-and-dot
三角形と点を座標を元に描画する

# 使いかた
* urlのパラメータ(pos)にコンマ区切りで数値を羅列する。
* 各数値は、小数（整数も可）
* 各数値は、8つで一つの単位となっており、それぞれ、三角形の頂点の座標がx,yの順で3つ並ぶ(6つの数字)と点の座標x,y(2つの数字)の計８つである。
例：`<URL>?pos=0,1,2,3,4,5,6,7,0.1,1.1,2.1,3.1,4.1,5.1,6.1,7.1`
* 最大100種類の出力が可能

## 例
`https://palmneko.github.io/view-triangle-and-dot/?pos=1.00,0.15,1.85,1.85,0.15,1.85,1.0,1.0,3.0,0.15,3.85,1.85,2.15,1.85,2.44,1.83,1,2.15,1.85,3.85,0.15,3.85,1.07,2.48,3,2.15,3.85,3.85,2.15,3.85,3.72,3.78`