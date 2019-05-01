#### 2019.05.01

## Midterm ─ [Embedded System Development and OS Design](http://www.nc.es.ncku.edu.tw/course/embedded/)

#### 請 fork 此 repo ，並完成以下要求(依完整度部份給分)：

1. 使用 HSI 作為 PLL 之 clock source，將 system clock 調整為168 MHz，並使用 MCO2 輸出 (divided by 4)

2. 使綠色 LED 恆亮

3. 宣告一個 global uint32_t array，並給予初始值`{0xA, 0xB, 0xC, 0xD, 0xE, 0xF}`，使用 gdb 驗證此 global array 有成功被初始化(請將 gdb 畫面截圖存放至原始碼目錄下)

#### 請將結果 push 回自己的 github

#### 評分方式：

1. make
2. make flash
3. 綠燈恆亮
4. MCO2 輸出
5. 附圖


####我所修改的部份：
基本上照著LAB6(2),
1.修改使用 HSI 作為 PLL 之 clock source,改n＝84以完成地一個要求
2.綠燈恆量的部份,把原本的blink(LED_BLUE)改為直接寫死後跑while(1)
3.宣告了一個global uint32_t array，可是不會用GDB看所宣告的這個陣列 因而放上一張開啟GDB的節圖以示自己還記得怎開～

