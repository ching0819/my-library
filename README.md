# practice
### 一些練習
**001 - 012 內容來自《進擊的資料科學》**
* [001](https://github.com/ching0819/my-library/blob/master/practice/practice_001.ipynb) **讀取檔案**: 
    * CSV: `pd.read_csv()`
    * TXT: `pd.read_table()`
    * Excel: `pd.read_excel()`
    * mat: `scio.loadmat()`
    
* [002](https://github.com/ching0819/my-library/blob/master/practice/practice_002.ipynb) **常用的資料結構**: 
    * DataFrame: 創建、讀取、
    * List/Dict: 創建、讀取、新增、改值、迭代索引
      dict就是有命名的list
     
* [003](https://github.com/ching0819/my-library/blob/master/practice/practice_003.ipynb) **DataFrame基礎操作**: 
    * 創建
    * 讀檔: `pd.read_csv()`
    * 檢視:  
    `df.head()` 查看前五列觀測值  
    `df.tail()` 查看末五列觀測值  
    `df.info()` 查看複合資訊  
    `df.describe()` 查看數值變數的描述性統計  
    `df.shape` 查看大小  
    * 選取:   
    `df.loc[]` 以索引為準  
    `df.iloc[]` 以位置為準  
    `df.isin()` 透過變數內觀察值索引  
    * 排序:   
    `df.sort_index()` 依照索引排序  
    `df.sort_values()` 依照變數排序  
    * 新增: 新增變數、新增觀察值
    * 統計摘要: `df.sum()`
    
* [004](https://github.com/ching0819/my-library/blob/master/practice/practice_004.ipynb) **DataFrame進階操作**: 
    * 調整變數型別: `df.astype()`
    * 重新編碼: `df.map()`
    * 處理缺值:   
    `df.isna()` 判斷是否缺值  
    `df.notna()` 判斷是否有值  
    `df.fillna()` 填補所有缺值  
    * 處理時序: `df.to_datetime()`
    * 設定索引: `df.set_index()`
    * 表格轉置:   
    `df.stack()` 寬表格轉長表格  
    `df.unstack()` 長表格轉寬表格  
    * 合併:   
    `pd.merge()`   
    `df.join()`   
    `pd.concat()`  
    * 重塑: `df.pivot()`
* [005](https://github.com/ching0819/my-library/blob/master/practice/practice_005.ipynb) **文字處理**: 
    * 測量長度: `len()`
    * 擷取:   
    `.upper()` 全部變大寫  
    `.lower()` 全部變小寫  
    `.title()` 單字字首大寫  
    `.capitalize()` 字手變成大寫  
    `.swapcase()` 大小寫轉換  
    * 去除空格:   
    `.lstrip()` 去除左邊空格  
    `.rstrip()` 去除右邊空格  
    `.strip()` 去除左右兩邊空格  
    * 格式化輸出: {} 搭配 `.format()`
    * 轉換日期時間格式:   
    %a ：縮寫的星期幾，從 Sun 至 Sat  
    %A ：全稱的星期幾，從 Sunday 至 Saturday  
    %b ：縮寫的月份，從 Jan 至 Dec  
    %B ：全稱的月份，從 January 至 December  
    %d ：月份中的第幾天，從 01 至 31  
    %m ：以兩位數字表示的月份，從 01 至 12  
    %Y ：以四位數字表示的西元年份，從 0 至 9999  
    %H ：以兩位數字表示的小時，從 00 至 23  
    %M ：以兩位數字表示的分鐘，從 00 至 59  
    %S ：以兩位數字表示的秒數，從 00 至 61  
    * 分隔: `.split()`
    * 判斷存在: `.find()`
    * 取代: `.replace()`
    * 正規表達式
* [006](https://github.com/ching0819/my-library/blob/master/practice/practice_006.ipynb) **基礎資料視覺化**: 
    * 長條圖: `plt.bar()`
    * 直方圖: `plt.hist()`
    * 盒鬚圖: `plt.boxplot()`
    * 散點圖: `plt.scatter()`
    * 線圖: `plt.line()`
* [007](https://github.com/ching0819/my-library/blob/master/practice/practice_007.ipynb) **資料視覺化中的元件**: 
    * 佈景主題: `plt.style.use()`
    * 圖標題:   
    `plt.title()` 加入標題  
    `plt.suptitle()` 加入副標題(在畫布更上方的置中位置)  
    * 軸標題: `pl.xlabel()` `plt.ylabel()`
    * 軸刻度、刻度標籤: `plt.xticks()` `plt.yticks()`
    * 調整座標軸(最大最小值):`plt.xlim()` `plt.ylim()` 
    * 顯示中文:
    * 註釋: `plt.text()`
    * 圖例: `plt.legend()`
    * 水平線: `plt.axhline()`
    * 陰影: `plt.fill_between()`
    * 添加箭頭: `plt.annotate()`
    * 子圖形: `plt.subplts(m, n)` 將畫布切割成 m 乘 n 的外觀
* [008](https://github.com/ching0819/my-library/blob/master/practice/practice_008.ipynb) **其他視覺化類型**: 
    * 樹狀圖(Treemap): `squarify.plot()`
    * 棒棒糖圖(Lollipop): `plt.plot()`+`plt.hline()`
    * 密度圖(Density plot): `sns.kdeplot` 
    * 堆疊密度圖:`sns.kdeplot() ` or `subplots()`
    * 小提琴圖(Violin plot): `sns.violinplot() `
    * 熱圖(heatmap): `sns.heatmap()`
    * Candlestick圖: `import plotly.graph_objs as go` `go.Candlestick`
    * Choropleth map

* [009](https://github.com/ching0819/my-library/blob/master/practice/practice_009.ipynb) **尋找迴歸模型的係數**: 
    * 拆分 訓練 / 驗證 / 測試資料
    * 用相關係數篩選變數
    * 尋找係數
    * 正規方程
    * 梯度遞減
    * 繪製3D曲面圖
    * 繪製動態曲面圖 *有error尚未未修正*
    * 使用模組或套件尋找係數
    * 將模型繪製到散佈圖上



# note
### 寫程式時的筆記




# project
### 專案練習