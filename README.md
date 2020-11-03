綾鷹とおーいお茶と伊右衛門と生茶を判別します。
#使用ライブラリ
tensorflow v2

#実行方法

```
python label_image.py --graph=retrained_graph.pb --labels=retrained_labels.txt --input_layer=Placeholder --output_layer=final_result --image="画像フォルダパス"
