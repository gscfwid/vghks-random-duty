# VGHKS Random Duty Generator

A single page application to assist resident duty arrangement in General or VGHKS mode.

輔助住院醫師排班的網頁版小工具，可使用「一般」或「VGHKS」模式。[Demo Site](http://radtools.tsai.it/vghks-random-duty/)

## Feature

1. 從 Google calendar 下載台灣版假日行事曆，如與實際有差異，也可自訂假日。
2. 可設定不值人員。
3. 可依該月總點數（平日及星期五為 1 點，假日為 2 點）產生建議班數分配，也可手動調整。
4. 亂數產生班表，預設為不連值，可設定 qod 值班上限，或班距標準差上限。

## Limitation

1. 因需要大量運算，會用到 Web Workers 技術，故建議使用新版的瀏覽器，IE9 以下並不支援。
2. 無法於網頁版儲存結果，可以 excel 檔或螢幕截圖的方式匯出。
3. 經更動的 google calendar 假日無法永久儲存，若重新整理頁面會失效。

## License

MIT License
