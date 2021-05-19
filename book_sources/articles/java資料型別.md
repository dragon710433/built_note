# java資料型別
## 基本資料型別(Primitive Data Type)
 1. 整數
>byte  
>short  
>int(整數的預設型別)  
>long(數字最末需要加上L宣告)  
 2. 浮點數
>float(數字最末需要加上F宣告)  
>double(浮點數的預設型別)  
 3.字元
>char(開頭與結尾需要加入單引號 ' )
 4.布林
>boolean(ture or false)  

直接輸出範例程式
```JAVA
        System.out.println(10 / 3D);
        System.out.println(2147483648L);
        System.out.println(72.3);
        System.out.println(72.3F);
        System.out.println(true);
```
輸出顯示
```
3.3333333333333335  
2147483648  
72.3  
72.3  
true  
```

亦可以宣告變數輸出進行運算
```
        //double 英文=89.2;
        //double 總分 = 英文 + 80;
        double 英文 = 89.2, 總分;
        int 數學 = 80;
        //英文 = 89.2;
        總分 = 英文 + 數學;
        System.out.print("總分: ");
        System.out.print(總分+"\n");

        //System.out.println("A"+3);
        System.out.println("平均: " + 總分 / 2);
```
輸出顯示
```
總分: 169.2
平均: 84.6
```

## 類別資料型別(Reference Data Type)
 1. 字串(String)
 2. 陣列(Array)
 3. 物件(Object)

※(待後續編寫完成再附上超連接
