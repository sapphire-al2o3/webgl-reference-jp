WebGLリファレンス
==================

WebGLRenderingContext のメソッドのプロパティ、リファレンスです。WebGL Reference Card を元に OpenGL ES 2.0 のリファレンスページから説明を持ってきています。

[WebGL Reference Card](http://www.khronos.org/files/webgl/webgl-reference-card-1_0.pdf)

[OpenGL ES 2.0 Reference Pages](http://www.khronos.org/opengles/sdk/docs/man/)

プロパティ
--------------------------
```
HTMLCanvasElement canvas
```
コンテキストが作られた Canvas エレメント。
```
drawingBufferWidth
```
描画バッファの幅。(canvas タグの width と同じ値?)
```
drawingBufferHeight
```
描画バッファの高さ。(canvas タグの height と同じ値?)


Whole Framebuffer Operations
------------------

```
void clear(ulong mask)
```

画面をクリアする。

mask
: COLOR_BUFFER_BIT, DEPTH_BUFFER_BIT, STENCIL_BUFFER_BITをビット和で指定する。

### clearColor
カラーバッファが`clear`の時にクリアされる色を指定する.
```
void clearColor(float red, float green, float blue, float alpha)
```

### clearDepth
デプスバッファが`clear`の時にクリアされる値を指定する。
```
void clearDepth(float depth)
```
depth:
0から1の値を指定する.


