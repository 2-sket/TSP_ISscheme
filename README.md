# TSP_ISscheme
1. モナリザTSPのデータをhttps://www.math.uwaterloo.ca/tsp/data/ml/monalisa.htmlよりダウンロードする.
2. Instance.ipynbにて２つの類似した90,000都市インスタンスを作成
3. LKHソルバーの環境を構築する⇨http://webhotel4.ruc.dk/~keld/research/LKH-3/
4. 片方のインスタンスの解をソルバーにて求める
5. matching.ipynbにて二部グラフの最小重み完全マッチングを行い, 頂点を対応付ける
6. overwrite_ID.ipynbにて4で得たツアーをもとに上書きする.
7. 6にて得られた巡回路を初期解としてLKHソルバーに渡す.
