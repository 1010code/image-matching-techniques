

影像比對是一種用於比較兩個或多個影像之間相似性的技術。這種技術在圖像處理和模式識別領域都有廣泛的應用。以下是一些常見的影像比對方法和技術：

- [基於模板的匹配（Template-based Matching）](./Template_Matching.ipynb)：這種方法通過在影像中尋找與參考影像中相似的圖案或結構來進行比對。通常使用的技術包括模板匹配、相關性匹配等。

- [特徵點匹配（Feature-based Matching）](./Feature_Matching.ipynb)：特徵點是在影像中具有顯著性的點，比如角點、斑點等。特徵點匹配的方法通過提取影像中的特徵點，然後比較這些特徵點之間的相似性來進行比對。常見的特徵點匹配算法包括SIFT（尺度不變特徵變換）、SURF（加速穩健特徵）和ORB（Oriented FAST and Rotated BRIEF）等。

- 結構比對（Structure-based Matching）：這種方法通過比較影像的結構、輪廓或邊緣來進行比對。常見的技術包括邊緣檢測、角點檢測和形狀描述符。

- 光學字符識別（Optical Character Recognition, OCR）：用於比對包含文本的影像。OCR技術能夠識別影像中的字符，並將其轉換成可編輯的文本，從而進行文本級別的比對。

- 神經網路方法（Neural Network-based Methods）：使用卷積神經往ˇ路（CNN）等深度學習模型，學習影像之間的高級特徵，實現更準確的比對。
