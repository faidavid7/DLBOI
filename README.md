# DLBOI

11510IPT 553000 Deep Learning in Biomedical Optical Imaging — 作業 repo（115061534 江承瀚）。

| 作業 | 內容 |
|---|---|
| [HW2](HW2/HW2.ipynb) | NumPy array 基礎（建立 / indexing / operations）+ OpenCV：讀入胸部 X 光、`cv2.rotate` 轉正 180°、`cv2.medianBlur` (5×5) 去除 salt-and-pepper noise |

## 下載
按綠色 `Code` → `Download ZIP`，或 `git clone https://github.com/faidavid7/DLBOI.git`。

## 解壓縮
把 `.zip` 解壓縮，會得到 `DLBOI/` 資料夾。

## 選擇資料夾
進入對應作業資料夾（如 `HW2/`），在該資料夾內開啟 notebook，`hw2.png` 以相對路徑讀取。

## 用法
```
pip install numpy opencv-python matplotlib jupyter
cd HW2
jupyter notebook HW2.ipynb
```
執行全部 cell 後會輸出處理後影像 `115061534_江承瀚_HW2.png`。

## 授權
Licensed under the Apache License 2.0，詳見 [LICENSE](LICENSE)。
