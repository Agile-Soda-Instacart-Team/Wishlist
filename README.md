[![image](https://user-images.githubusercontent.com/95989232/166428931-1ee9948f-cc1c-42a2-b0a9-47dae9b8b90d.png)](https://www.kaggle.com/competitions/instacart-market-basket-analysis/overview)

## ๐์์๋ฆฌ์คํธ ํ ์๊ฐ
|์ด๋ฆ|์ญํ |๋ด๋น ์๋ฌด|
|---|---|:---:|
|๋ฐ์ฐ๋ค|ํ์ฅ|๋ฐ์ดํฐ ํ์ธ, EDA, ๋ชจ๋ธ๋ง|
|๊น์๋ค์ค|ํ์|||
|์ฅ๋ณ์ฉ|ํ์|ํ๋ก์ ํธ ๊ด๋ฆฌ, ๋ฐ์ดํฐ ํ์ธ, EDA|
|์ ๊ฒฝํ|ํ์|๋ชจ๋ธ๋ง|

<br/>

## ์ผ์ ํ
|๋จ๊ณ|๋ด์ฉ|M1|M2|H1|H2|H3|H4|H5|H6|  
|:---:|:-----:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|  
|1|์์์ผ ์๋ค OT|โ๏ธ|โ๏ธ|โพ|โพ|โพ|โพ|โพ|โพ|  
|2|์ฃผ์  ๋ฐ ๊ณํ ์ค์ |โพ|โ๏ธ|โ๏ธ|โพ|โพ|โพ|โพ|โพ|  
|3|๋ฐ์ดํฐ ๊ตฌ์ฑ ๋ฐ EDA|โพ|โพ|โ๏ธ|โ๏ธ|โ๏ธ|โ๏ธ|โพ|โพ|   
|4|๋ชจ๋ธ ๊ฐ๋ฐ|โพ|โพ|โพ|โพ|โพ|โ๏ธ|โ๏ธ|โ๏ธ|   
|5|์ต์ข ๋ณด๊ณ |โพ|โพ|โพ|โพ|โพ|โพ|โพ|โ๏ธ|

<br/>

## ํ๋ก์ ํธ ์๊ฐ

Instacart๋ ๋ฏธ๊ตญ๊ณผ ์บ๋๋ค์์ ์น๊ณผ ์ฑ์ ํตํด ์๋ฃํ ๋ฐฐ๋ฌ๊ณผ ํฝ์ ์๋น์ค๋ฅผ ์ด์ํ๋ ๋ฏธ๊ตญ ํ์ฌ์๋๋ค. instacart์์ ์ ๊ณตํ ์ต๋ชํ ๋ ๊ณ ๊ฐ์ ๊ตฌ๋งค๋ด์ญ ๋ฐ์ดํฐ๋ฅผ ๊ธฐ๋ฐ์ผ๋ก ๋ค์ ์ฃผ๋ฌธํ  ์ ํ์ ์์ธกํ๋ ๋ชจ๋ธ์ ๊ฐ๋ฐํฉ๋๋ค.

<br/>

## ๋ชฉํ
### ์ ๋์  ๋ชฉํ
- ์บ๊ธ ๋ฆฌ๋๋ณด๋ ์ ์ 0.40311 ์ด์ ๋ฌ์ฑ
### ์ ์ฑ์  ๋ชฉํ
- ์ ๊ณต๋ ๋ฐ์ดํฐ ๋ถ์
- ๋ ๋์ ๊ต์ฐจ ํ๋งค ๋ฐ ์ํฅ ํ๋งค๋ฅผ ์ํ ์ ํ ๊ฐ์ ์ฐ๊ด์ฑ ์ฐพ๊ธฐ
- ํ๊ฒ ๋ง์ผํ์ ์ํ ๊ณ ๊ฐ ์ธ๋ถํ ์ํ ๋ฐ ๊ณ ๊ฐ ํ๋ ์์ธก
- ๊ณ ๊ฐ ์ฃผ๋ฌธ์ ๋ํ ์ต๋ช ๋ฐ์ดํฐ๋ฅผ ์ฌ์ฉํ์ฌ ์ด์ ์ ๊ตฌ๋งคํ ์ ํ์ด ์ฌ์ฉ์์ ๋ค์ ์ฃผ๋ฌธ๋ชฉ๋ก์ ํฌํจ๋ ์ง๋ฅผ ์์ธกํ๋ ์ต์ ์ ๋ชจ๋ธ์ ๊ฐ๋ฐ

<br/>

## [๋ฐ์ดํฐ ์ค๋ช](https://www.kaggle.com/competitions/instacart-market-basket-analysis/data)
***

- aisles: ์ ํ์ ์ ๋ถ๋ฅ๊ฐ ์ด 134๊ฐ ๋์ด๋์ด ์์ต๋๋ค.
- Departments: ์ด ํ์ผ์๋ ์ ํ์ ๋ ๋ถ๋ฅ๊ฐ ์ด 21๊ฐ ๋์ด๋์ด ์์ต๋๋ค.
- orders: ์ด ํ์ผ์๋ ์ด 206209๋ช์ ์ฌ์ฉ์๊ฐ ์ฃผ๋ฌธํ ์ด 3421083๊ฐ์ ์ฃผ๋ฌธ์ด ์์ต๋๋ค.
    - Order_number: ๊ณ ๊ฐ๋ณ ์ฃผ๋ฌธ ํ์๋ 0์์ 100๊น์ง์๋๋ค.
    - Order_dow(day of week): 0, 1, 2, 3, 4, 5, 6์ด ๊ฐ๊ฐ ํ ์ผ์ํ์๋ชฉ๊ธ์ผ๋ก ๋งคํํ  ์ ์์ต๋๋ค. ํ ์์ผ๊ณผ ์ผ์์ผ ์ฃผ๋ฌธ์ด ๋ค์๋ฅผ ์ฐจ์งํฉ๋๋ค.
    - Order_hour_of_day: ๋๋ถ๋ถ์ ์ฃผ๋ฌธ์ ๋ฎ ์๊ฐ์ ์ด๋ฃจ์ด์ง๋๋ค.
    - Days_since_prior_order: ์ด์  ์ฃผ๋ฌธ ์ดํ ๊ฒฝ๊ณผ ์ผ์๋ฅผ ๋ณด๋ฉด 7, 14, 21, 30์ด ๋ง์ผ๋ฏ๋ก ์ผ์ฃผ์ผ์ ํ ๋ฒ ์ฃผ๋ฌธํ๋ ์ถ์ด๋ฅผ ๋ณด์๋๋ค.
- order_products_prior: ์ด ํ์ผ์ ์ฃผ๋ฌธํ ์ ํ๊ณผ ์ฅ๋ฐ๊ตฌ๋์ ์ถ๊ฐ๋ ์์์ ๋ํ ์ ๋ณด๋ฅผ ์ ๊ณตํ๋ฉฐ ์ ํ์ด ์ฌ ์ฃผ๋ฌธ ๋์๋์ง ์ฌ๋ถ๋ ์๋ ค์ค๋๋ค. ์ด ํ์ผ์๋ ์ด 49677๊ฐ์ ์ ํ์ด ์ฃผ๋ฌธ๋ ์ด 3214874๊ฐ์ ์ฃผ๋ฌธ ์ ๋ณด๊ฐ ์์ต๋๋ค.
- order_products_train: order_products_priorํ์ผ๊ณผ ๋ง์ฐฌ๊ฐ์ง๋ก ์ฃผ๋ฌธํ ์ ํ๊ณผ ์ฅ๋ฐ๊ตฌ๋์ ์ถ๊ฐ๋ ์์์ ๋ํ ์ ๋ณด์ ์ ํ์ด ์ฌ ์ฃผ๋ฌธ ๋์๋์ง ์ฌ๋ถ๋ฅผ ์๋ ค์ค๋๋ค. ์ด ํ์ผ์๋ ์ด 39123๊ฐ์ ์ ํ์ด ์ฃผ๋ฌธ๋ ์ด 131209๊ฐ์ ์ฃผ๋ฌธ ์ ๋ณด๊ฐ ์์ต๋๋ค.
- Products: ์ด ํ์ผ์๋ ์ด 49688๊ฐ์ ์ ํ ๋ชฉ๋ก๊ณผ ํด๋น ์นดํ๊ณ ๋ฆฌ ๋ฐ ๋ถ์๊ฐ ํฌํจ๋์ด ์์ต๋๋ค. ๋ค๋ฅธ ์นดํ๊ณ ๋ฆฌ์ ๋ค๋ฅธ ๋ถ์์ ์๋ ์ ํ์ ์๋ ๋ค๋ฆ๋๋ค.

<br/>

## ํ์์  ๋ฐ์ดํฐ ๋ถ์

๋ฐ์ดํฐ ์ค๋ช ๋จ๊ณ์์ ํ์ธํ ํน์ง๋ค์ ํ ๋๋ก EDA์ ๊ฐ์ค๊ฒ์ ์ ์งํํ์ต๋๋ค.

![image](https://user-images.githubusercontent.com/69462995/172520774-1098403a-a62e-4c96-a70a-0430e17db306.png)

### ๊ฐ์ค1. ์์ผ๊ณผ ์๊ฐ์ ๋ฐ๋ฅธ ๊ณ ๊ฐ ๊ตฌ๋งคํจํด์ด ์๋์ง ํ์ธ
* ์์ผ๋ณ ํธ๋๋ ๋ญํน์ ํ์ธํ์ฌ ์์ผ๊ณผ ์ ํ ํ๋งค๋์ ๋ณํ ์ฒดํฌ
![image](https://user-images.githubusercontent.com/69462995/172520920-fb29b811-db73-47b9-8024-743597b2183d.png)

* ์๊ฐ๋ณ ํธ๋๋ ๋ญํน์ ํ์ธํ์ฌ ์๊ฐ๊ณผ ์ ํ ํ๋งค๋์ ๋ณํ ์ฒดํฌ
![image](https://user-images.githubusercontent.com/69462995/172520935-662b96b5-f025-4b58-af81-e76ce3c371f5.png)

* ํน์  ์์ผ & ์๊ฐ์๋ง ์ฃผ๋ฌธ์ ์งํํ๋ ์ ์ ๊ฐ ์๋์ง ํ์ธ
![image](https://user-images.githubusercontent.com/69462995/172521868-87332421-179a-4796-877c-1afe94e83e0a.png)


### ๊ฐ์ค2. Order์์ ๊ตฌ๋งคํจํด ํ์ธ
* order_number๊ฐ ๋์ ์ฃผ๋ฌธ์ผ์๋ก ์ฌ๊ตฌ๋งค์จ์ ๋ณํ๋ ์ฒดํฌ
![image](https://user-images.githubusercontent.com/69462995/172521479-81b18df9-51c4-4648-9e18-1db471019eda.png)

* order_number๊ฐ 40์ด ๋๋ ํ์๋ค์ ์์ผ-์๊ฐ ํจํด ํ์ธ
![image](https://user-images.githubusercontent.com/69462995/172522206-6e73b080-dc18-4b98-bde7-90e5de5396aa.png)

* days_since_prior_order์ ์ฌ์ฃผ๋ฌธ์จ์ ๋ณํ๋ ์ฒดํฌ
* ![image](https://user-images.githubusercontent.com/69462995/172522432-7e5406d5-af61-454f-beea-c124fc9a5b63.png)

### ๊ฐ์ค3. ๊ณ ๊ฐ๋ณ ๊ตฌ๋งคํจํด ํ์ธํ๊ธฐ
* ์ ์ ๋ง๋ค ์ ํธํ๋ ์ ํ์ด ์๋์ง ํ์ธ
![image](https://user-images.githubusercontent.com/69462995/172522530-f435c08c-6e98-4bc6-867b-05f8cc61c0f6.png)

* ๊ฐ์ ์ ํ์ ์ ํธํ๋ ์ ์ ๋ค์ ๋น์ทํ ๊ตฌ๋งคํจํด์ ๋ณด์ด๋์ง ํ์ธ
![image](https://user-images.githubusercontent.com/69462995/172523104-b4677cb6-0a1d-4cf2-a897-2086f9dc2222.png)

### ๊ฐ์ค4. ์ ํ๋ณ ๊ตฌ๋งคํจํด ํ์ธํ๊ธฐ
* ๊ณ ๊ฐ๋ค์ด ์ ํธํ๋ ์ ํ ํค์๋๊ฐ ์๋์ง ์๋ ํด๋ผ์ฐ๋๋ก ํ์ธ
![image](https://user-images.githubusercontent.com/69462995/172523495-d60698a1-1fa0-4766-bbfd-42f340ac9d4c.png)

* ์ ํธ ํค์๋๋ค์ ์ฌ์ฃผ๋ฌธ์จ ํ์ธ
![image](https://user-images.githubusercontent.com/69462995/172523553-ca9d92be-e172-4bc0-be44-f3f6f7f4ef91.png)

<br/>

## ์ต์ข Feature
```
UP : ์ ์  ๊ตฌ๋งค๋ด์ญ
U : ์ ์  ๋ณ ์ ๋ณด
P : ์ ํ ๋ณ ์ ๋ณด
A : ์๋ถ๋ฅ ์ ๋ณด
D : ๋๋ถ๋ฅ ์ ๋ณด
```

### ์ ์  ๊ตฌ๋งค๋ด์ญ Feature
```
UP_total_orders	์ ์ ๋ณ ํด๋น ์ ํ ์ด ์ฃผ๋ฌธ ์
UP_total_reorders	์ ์ ๋ณ ํด๋น ์ ํ ์ด ์ฌ์ฃผ๋ฌธ ์
UP_mean_cart_order	์ ์ ๋ณ ํด๋น ์ ํ ํ๊ท  ์ฅ๋ฐ๊ตฌ๋ ์์
UP_reorder_ratio	ํด๋น ์ ํ์ ์ฒ์ ๊ตฌ๋งคํ ์ดํ ์ฌ์ฃผ๋ฌธ์ด ๊ฐ๋ฅํ ๊ธฐ๊ฐ(์ฃผ๋ฌธ์)๋์์ ์ฌ์ฃผ๋ฌธ ์จ
UP_order_percentage	์ ์ ์ ์ ์ฒด ์ฃผ๋ฌธ ์ค ํด๋น ์ ํ์ ๊ตฌ๋งคํ ๋น์จ
UP_order_days	ํด๋น ์ ํ์ ๊ตฌ๋งคํ ๊ธฐ๊ฐ
UP_mean_days_since_prior_order	ํ๊ท  ์ฌ์ฃผ๋ฌธ ๊ธฐ๊ฐ
order-3,2,1	๋ง์ง๋ง 3๋ฒ์ ์ฃผ๋ฌธ์์ ์ฌ์ฃผ๋ฌธ ์ฌ๋ถ (๊ตฌ๋งค ๋์ ์ด ์๋ค๋ฉด -1)
```

### ์ ์  ๋ณ ์ ๋ณด Feature
```
U_total_orders	์ ์ ๋ณ ์ดย ์ฃผ๋ฌธย ์
U_total_products	์ดย ๊ตฌ๋งคย ์ ํย ์
U_unique_products	์ดย ๊ตฌ๋งคย ์ ํย ์ข๋ฅย ์
U_total_reorders	์ดย ์ฌ์ฃผ๋ฌธย ์
U_unique_reordered_products	์ดย ์ฌ์ฃผ๋ฌธย ์ ํย ์ข๋ฅย ์
U_avg_basket_size	์ฃผ๋ฌธ๋นย ํ๊ท ย ๊ตฌ๋งคย ์ ํย ์
U_avg_reorder_in_order	์ฃผ๋ฌธ๋นย ํ๊ท ย ์ฌ๊ตฌ๋งคย ์ ํย ๋น์จ
U_order_days	์ดย ์ฃผ๋ฌธย ๊ธฐ๊ฐ
U_basket_size_order	๋ง์ง๋งย 3๊ฐ์ย ์ฃผ๋ฌธย ๊ตฌ๋งคย ์ ํย ์
U_re_in_order	๋ง์ง๋งย 3๊ฐ์ย ์ฃผ๋ฌธย ์ฌ์ฃผ๋ฌธย ์ ํย ํฌํจย ๋น์จ
```

### ์ ํ ๋ณ ์ ๋ณด Feature
```
P_total_orders	์ดย ํ๋งคย ์
P_unique_users	๊ตฌ๋งคํย ์ ์ ย ์
P_total_reorders	์ดย ์ฌ์ฃผ๋ฌธย ์
P_mean_cart_order	ํ๊ท ย ์ฅ๋ฐ๊ตฌ๋ย ์์
P_reorder_rate	์ฌ์ฃผ๋ฌธ์จ
P_sum_order_days	์ดย ๊ตฌ๋งคย ๊ธฐ๊ฐ
P_mean_order_days	ํ๊ท ย ๊ตฌ๋งคย ๊ธฐ๊ฐ
P_days_since_prior_order	ํ๊ท  ์ฌ์ฃผ๋ฌธ ๊ธฐ๊ฐ
P_keyword ์ ํ ์ด๋ฆ์ ๋ค์ด๊ฐ๋ ํค์๋ ๋ณ๋ก ๊ทธ๋ฃนํ
```

### ์๋ถ๋ฅ(aisle) Feature
```
A_total_orders	์ดย ํ๋งคย ์
A_total_reorders	์ดย ์ฌ์ฃผ๋ฌธย ์
A_reorder_rate	์ฌ์ฃผ๋ฌธย ์จ
A_mean_cart_order	ํ๊ท ย ์ฅ๋ฐ๊ตฌ๋ย ์์
A_mean_days_since_prior_order	ํ๊ท ย ์ฌ์ฃผ๋ฌธย ๊ธฐ๊ฐ
```

### ๋๋ถ๋ฅ(department) Feature
```
D_total_orders	์ดย ํ๋งคย ์
D_total_reorders	์ดย ์ฌ์ฃผ๋ฌธย ์
D_reorder_rate	์ฌ์ฃผ๋ฌธย ์จ
D_mean_cart_order	ํ๊ท ย ์ฅ๋ฐ๊ตฌ๋ย ์์
D_mean_days_since_prior_order	ํ๊ท ย ์ฌ์ฃผ๋ฌธย ๊ธฐ๊ฐ
```
<br/>

## ๋ฐ์ดํฐ ์ค๋น
์ต์ข ์ ํํ feature๋ค์ ๋ชจ๋ธ์ ๋ฃ๊ธฐ ์ํด ๊ด๋ จ๋ ๊ด๋ จ๋ ํน์ฑ๋ค์ ํ ๊ณณ์ ๋ชจ์ผ๋ ์์์ ์งํํ์ต๋๋ค.  
๋ฐ์ดํฐ์ ์ต์ข ํํ๋ ์ ์ ๋ณ ๊ตฌ๋งค๋ด์ญ์๋๋ค.  
์ ์ ๋ณ ๊ตฌ๋งค๋ด์ญ ํํ๋ก ๋ฐ์ดํฐ๋ฅผ ์ฌ๊ฐ๊ณตํ๊ณ  EDA๋ฅผ ์งํํ๋ฉฐ ์์ฑ๋ ์ ์ ๋ณ, ์ ํ๋ณ ์ ๋ณด ๋ฑ์ ์ถ๊ฐํ์ต๋๋ค.

์ต์ข ๋ฐ์ดํฐ๋ 13307953๊ฐ์ ํ๊ณผ 49๊ฐ์ ์ด์ ๋ณด์ ํฉ๋๋ค.  
๋ฐ์ดํฐ์ ์ฉ๋์ ์ฝ 4GB๋ก ๋ฐ์ดํฐ ํ์์ ์์ ์ ํตํด 1.5GB๊น์ง ์ฉ๋์ ์ ๊ฐํ์ต๋๋ค.

## ML ๋ชจ๋ธ
์ ํฌ๋ ํน์  ์ ์ ๊ฐ ์ด๋ค ์ ํ์ ๊ตฌ๋งคํ๋์ง ๋ถ๋ฅํ๊ธฐ ์ํด ๋ค์ํ ML ๊ธฐ๋ฒ ์ค ํธ๋ฆฌ ๊ธฐ๋ฐ์ LGBM, XGBoost, Catboost ๋ชจ๋ธ๋ก ์ ๊ทผํ์ต๋๋ค.  
๊ฒฐ์ ํธ๋ฆฌ ์๊ณ ๋ฆฌ์ฆ์ ์๊ฐ์ ์ผ๋ก ๋ช์์ ์ธ ๊ธฐ๋ฒ์ผ๋ก ์์ฌ๊ฒฐ์  ๊ณผ์ ๊ณผ ๊ฒฐ์ ๋ ์์ฌ๋ฅผ ๋ณด์ฌ์ฃผ๋๋ฐ ์ฌ์ฉํ์ง๋ง ๋ค๋ฅธ ML ์๊ณ ๋ฆฌ์ฆ์ ๋นํด ๋ฎ์ ์ฑ๋ฅ์ ๋ณด์ฌ ์ด๋ฅผ gradient boosting ๊ธฐ๋ฒ์ ์ฌ์ฉํ์ฌ ๋ณด์ํฉ๋๋ค.  
๋ค์ํ ์ฐ๊ตฌ์ฌ๋ก๋ค์ด ๋ถ๋ฅ์ ํ๊ท์ ์์ญ์์ gradient boosting ๊ธฐ๋ฐ์ ํธ๋ฆฌ ๋ชจ๋ธ์ด ๋ฐ์ด๋ ์ฑ๋ฅ์ ๋ณด์ธ๋ค๋ ๊ฒ์ ์์ฆํ์ฌ ์ ํฌ๋ ์ด๋ฅผ ๋ฒ ์ด์ค ๋ชจ๋ธ๋ก ์ ์ ํ์ต๋๋ค.  

### LGBM vs XGBoost vs Catboost
![image](https://user-images.githubusercontent.com/69462995/172525680-b7450ba2-39ca-4624-befe-cd15f5320ecf.png)

### ์ต์ข ์ค์ฝ์ด
![image](https://user-images.githubusercontent.com/69462995/172526479-52a3f6bd-a967-433a-bb7e-70e01460dab6.png)

## ๊ฐ์ ์ 
1. EDA ๊ด๋ จ
* ์ ํ๊ฐ ์ ์ฌ๋ ํ์ธ(Aprior ๋ฑ..)
* ์ข ๋ ์ง๊ด์ ์ธ ์๊ฐํ ๋๊ตฌ ๊ณ ๋ฏผ
2. Feature selection ๊ด๋ จ
* ์ข ๋ ๋ค์ํ ๊ฐ๋์์์ ์ ๊ทผ๊ณผ ํผ์ณ์์ฑ
* ์๊ณ ๋ฆฌ์ฆ์ ํ์ฉํด ์ฐจ์ ์ถ์
3. Modeling ๊ด๋ จ
* SMOTE ๋ฑ ์ค๋ฒ์ํ๋ง ๊ธฐ๋ฒ์ ์ ์ฉํ์ฌ ๋ฐ์ดํฐ์ ๋ถ๊ท ํ ํด์
* ํจ์จ์ ์ธ ํ์ ํ๋ก์ธ์ค๋ฅผ ์ ์ฉํ์ฌ ํ์ดํผํ๋ผ๋ฏธํฐ ์กฐ์ 
* ์์๋ธ ๋ชจ๋ธ์ ์ ์ฉํ์ฌ ์ฑ๋ฅ ๊ฐ์ 

## ํ๋ก์ ํธ๋ฅผ ์งํํ๋ฉฐ ์์ฌ์ ๋ ์ 
![image](https://user-images.githubusercontent.com/69462995/172691280-f1d4e48d-5cb6-46ee-a35d-2b5ba5af5d73.png)

