# 宅内ネットワーク用の導入コマンド

## IX3110(1)
グローバルコンフィグレーションモード移行
```
configure
```
### ホスト名設定
```
hostname IX3110-1
```
### ログインタイマーの設定
```
terminal timeout 60
```
### タイムゾーンの設定
```
timezone jst
```
### ランニングコンフィグの保存
```
write memory
```
### インタフェースコンフィグモードへの移行 
```
interface GigaEthernet0.0
```
#### インターフェイス停止の解除
```
no shutdown
```
--
## IX3110(2)
グローバルコンフィグレーションモード移行
```
configure
```
### ホスト名設定
```
hostname IX3110-2
```
### ログインタイマーの設定
```
terminal timeout 60
```
### タイムゾーンの設定
```
timezone jst
```
### ランニングコンフィグの保存
```
write memory
```
### インタフェースコンフィグモードへの移行 
```
interface GigaEthernet0.0
```
#### インターフェイス停止の解除
```
no shutdown
```
--

## X510(1)
```

```

--

## X510(2)
```

```

--

## X200
```

```
