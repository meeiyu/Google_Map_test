## Implement Google Map API

**Here's the Google Map API ➔ [Google Map API](https://developers.google.com/maps/web/)**

======================================

各網頁內容說明:

## task1.html
-- 設置基本的經緯度位置並將地圖嵌入DOM元素中

## task2.html
-- 按下start讓marker從bandrich出發往左上角移動

## task3.html
-- 輸入地址使其marker可以定位到所輸入的位置上
-- 拖拉marker,並將marker所在的經緯度顯示在console上。

## 3way.html
-- 使用使用google map 所提供的polyline，逐一讀取經緯度的位置描繪出行徑路徑
-- ※問題: 逐一描繪的過程會使起始點重覆被描繪，會導致線段呈現鋸齒狀

## 3way_draw.html
-- 讀取陣列中的經緯度數值，使用google map 所提供的polyline描繪出行徑路徑。

## count_distance.html
-- 使用`computeDistanceBetween()`計算行徑路徑的距離有多遠(提供五個點的經緯度)

## drawing_tools.html
-- 使用API畫出圓形或方形。
-- 方形：計算出其四個角的經緯度、中心點經緯度
-- 圓形：計算出圓心與其半徑的距離、圓心的經緯度