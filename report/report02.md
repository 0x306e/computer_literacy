# 階調数と疑似輪郭
  
      ORG=imread('../img/origin.png');
      ORG = rgb2gray(ORG); colormap(gray); colorbar;
      imagesc(ORG); axis image;

  によって原画像の読み込み、グレースケールへの変換、表示した結果を図1に示す。

  ![img](../img/2-1.png)
  <div style="text-align: center;">図1. グレースケール変換</div>

  この画像を2階調化するには、
