# Python 初學者教學：從零開始的程式設計與數據科學之旅

歡迎來到這個為 Python 初學者設計的教學課程！本課程旨在引導您從零開始，逐步掌握 Python 程式設計的基礎，並進一步探索資料處理與機器學習的有趣世界。

無論您是完全沒有程式設計經驗的新手，還是想從其他語言轉換跑道的開發者，這裡都提供了清晰、易懂的學習路徑。

## 課程大綱

本課程分為三個主要章節，每個章節都是一個 Jupyter Notebook (`.ipynb`) 檔案，包含了詳細的程式碼範例、中文註解與練習題。

---

### 📖 第一章：Python 程式設計入門 (`Ch1_introduction.ipynb`)

本章節將帶您認識 Python 的核心基礎語法，為後續的學習打下堅實的基礎。

**學習重點：**
- **變數與資料型別**：學習 `string`, `int`, `float` 等基本型別。
- **基本運算與輸入**：進行數學運算與接收使用者輸入。
- **流程控制**：掌握 `if/elif/else` 條件判斷與 `for`/`while` 迴圈。
- **函式**：學習如何定義與使用自己的函式。
- **資料結構**：介紹實用的 `list` (列表) 與 `dict` (字典)。
- **實作專案**：透過「互動心理測驗」與「學生管理系統」等小專案鞏固所學。

---

### 📊 第二章：CSV 資料處理與分析 (`Ch2_csvdata_process.ipynb`)

在學會基本語法後，本章節將帶您進入資料科學的領域，學習如何使用強大的 `pandas` 函式庫來處理與分析真實世界的資料。

**學習重點：**
- **讀取 CSV 檔案**：將表格資料載入 Python 中進行處理。
- **資料清理與轉換**：計算新欄位、處理缺失值、轉換資料型別。
- **條件篩選與排序**：根據特定條件篩選出您感興趣的資料。
- **分組與聚合**：學習 `groupby` 等進階操作，進行統計分析。
- **資料視覺化**：使用 `matplotlib` 將數據以圖表（如長條圖、直方圖）呈現。
- **進階應用**：樞紐分析、時間序列處理等。

---

### 🤖 第三章：機器學習初體驗 (`Ch3_machinelearning.ipynb`)

本章節是您踏入 AI 領域的第一步。您將學到如何使用 `scikit-learn` 函式庫來建立並訓練幾種常見的機器學習模型。

**學習重點：**
- **線性迴歸 (Linear Regression)**：預測連續數值，例如預測房價。
- **邏輯迴歸 (Logistic Regression)**：進行二元分類，例如判斷郵件是否為垃圾郵件。
- **支援向量機 (SVM)**：一種強大的分類演算法。
- **隨機森林 (Random Forest)**：一種更複雜的非線性分類模型。
- **模型評估**：學習如何評估模型的準確性與效能。

---

### 🧠 第四章：進階機器學習：模型評估與解釋 (`Ch4_machinelearning2.ipynb`)

在學會建立基本模型後，本章節將帶您深入了解如何評估模型的內部運作機制，並解釋其決策過程。這是機器學習在實務應用中非常重要的一環。

**學習重點：**
- **特徵重要性 (Feature Importance)**：分析並視覺化各個特徵對於模型預測的貢獻度。
- **主成分分析 (PCA)**：學習一種強大的降維技巧，將複雜的高維度資料視覺化。
- **模型解釋性 (LIME)**：使用 LIME (Local Interpretable Model-agnostic Explanations) 工具來解釋單一筆資料的預測結果，了解模型「為什麼」會這麼判斷。
- **進階模型評估**：對模型進行更全面的效能評估。

## 如何開始？

1.  **安裝環境**：
    請確保您的電腦已安裝 Python 與 Jupyter Notebook。推薦直接安裝 [Anaconda](https://www.anaconda.com/products/distribution)，它會包含所有您需要的工具。

2.  **下載教材**：
    將本專案的所有檔案下載到您的電腦中。

3.  **開啟 Notebook**：
    在您的終端機 (Terminal) 或命令提示字元 (Command Prompt) 中，切換到專案所在的資料夾，並執行以下指令：
    ```bash
    jupyter notebook
    ```
    這會在您的瀏覽器中開啟 Jupyter 介面，您可以在此點擊 `.ipynb` 檔案開始學習。

4.  **跟隨章節學習**：
    建議從第一章開始，依序學習。每個 Notebook 中的程式碼區塊 (Cell) 都可以單獨執行。動手修改、實驗並完成練習題，是最好的學習方式！

祝您學習愉快！ 