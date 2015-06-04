# ccchart設定例

このレポジトリの変更は以下の設定で利用されています。


```js:
var config = {"config": { "type": "line",
			  "lineWidth": 2,
			  "minY": 0,
			  "maxWsColLen": 4500,
			  "maxY": 4500,
			  "colorSet": ["#368EBE"],
			  "width" : 500,
			  "height": 300,
			  "useVal": "no",
			  "paddingRight": 55,
			  "xScaleSkip": 60 * 5,
			  "useHanrei": "no",
			  "unit": "m3",
			  "minLineWidth": 0,     // xScaleSkipでスキップするときに線の太さ(追加)
			  "yScaleMin": 0,        // Y軸の最小値。選択中のアイテムの最小値を表示します(追加)
			  "yScaleMax": 4500      // Y軸の最大値。選択中のアイテムの最大値を表示します(追加)
			},
	      
	      "data": [
		  ["時刻"],
		  [this.dataName].concat(new Array(this.dataCount))
	      ]
	     };
```
