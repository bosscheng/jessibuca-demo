# 方法

```js
var jessibuca = new Jessibuca()

```
## play([url]) 播放/暂停之后的播放

```js
jessibuca.play(url)
// 只有在已经调用过play(url) 之后才能生效
jessibuca.play()

```

## pause 暂停

```js
jessibuca.pause()
```


## mute 静音

```js
jessibuca.mute()
```

## cancelMute  取消静音

```js
jessibuca.cancelMute()

```

## resize 自适应窗口

```js
jessibuca.resize()
```



# 监听事件


## onRecord(flag)  录制

```js
jessibuca.onRecord = function(flag) {
  console.log(flag)
}
```
## onPause  暂停

```js
jessibuca.onPause = function() {
  
}
```

## onPlay  播放

```js
jessibuca.onPlay = function() {
  
}
```

## onFullscreen(flag) 全屏

```js
jessibuca.onFullscreen = function(flag) {
  console.log(flag);
}
```

## onMute(flag) 静音

```js
jessibuca.onMute = function(flag) {
  console.log(flag)
}
```

