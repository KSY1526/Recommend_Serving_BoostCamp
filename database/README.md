# ๊ตฌ์กฐ๋ 

```bash
๐ฆdatabase
 โฃ ๐data
 โ โฃ ๐data.csv
 โ โฃ ๐data_all.csv
 โ โฃ ๐rest.csv
 โ โฃ ๐tag_tag.csv
 โ โฃ ๐test_rand.csv
 โ โฃ ๐test_time.csv
 โ โฃ ๐train_rand.csv
 โ โฃ ๐train_time.csv
 โ โ ๐user.csv
 โฃ ๐rest_csv
 โ โฃ ๐rest_concat_Dobong.csv
 โ โฃ ๐rest_concat_Dongdaemun.csv
 โ โฃ ๐rest_concat_Dongjag.csv
 โ โ ๐...(์ดํ 26๊ฐ ์ง์ญ๋ค)
 โฃ ๐user_csv
 โ โฃ ๐Dobong.csv
 โ โฃ ๐Dongdaemun.csv
 โ โฃ ๐Dongjag.csv
 โ โ ๐...(์ดํ 26๊ฐ ์ง์ญ๋ค)
 โฃ ๐data_EDA.ipynb
 โฃ ๐data_processing_DB.ipynb
 โฃ ๐data_processing_DataAll.ipynb
 โฃ ๐simple_model_recall.ipynb
 โฃ ๐personal.py
 โ ๐reccar_0130.db
```

## rest_csv, user_csv
ํฌ๋กค๋ง์ ํตํด ๋ง๋ค์ด์ง ์๋น๊ณผ ์ ์  ์ ๋ณด csv๊ฐ ๊ตฌ ๋ณ๋ก ์กด์ฌํฉ๋๋ค.

## data_EDA.ipynb
data_all.csv ํ์ผ์ ์ด์ฉํด ๊ฐ๋จํ๊ฒ ๋ฐ์ดํฐ EDA๋ฅผ ์งํํ์ต๋๋ค.

## data_processing_DB.ipynb
rest_csv, user_csv ํด๋ ๋ด csv ํ์ผ์ ์ด์ฉํด ๋ฐ์ดํฐ๋ฅผ ์ ์ฒ๋ฆฌํ์์ต๋๋ค.

data ํด๋ ๋ด data, user, rest, train, test ์ด๋ฆ์ csv ํ์ผ์ ๋ง๋ค์์ผ๋ฉฐ DB๋ ๊ตฌ์ถํ์ต๋๋ค.

## data_processing_DataAll.ipynb
Cold Start user๋ ํฌํจ๋ data_all.csv ํ์ผ์ ๋ง๋ค์์ต๋๋ค.

## simple_model_recall.ipynb
๋๋ค ์ถ์ถ, ๋จ์ ์ธ๊ธฐ๋ ๊ธฐ๋ฐ ์ถ์ฒ์ recall ๊ฐ์ ๊ตฌํฉ๋๋ค.

## personal.py
์ผ๋ง๋ ๊ฐ์ธํ ๋ ์ถ์ฒ์ ํ๋์ง ์์๋ณด๋ personalization์ด๋ผ๋ ์งํ๋ฅผ ๊ตฌํ๋ ํจ์ ์๋๋ค.

## tag_tag.csv
์ธ์ธํ๊ฒ ๋๋ ์ ธ ์๋ ์๋ถ๋ฅ ํ๊ทธ๋ฅผ ์ด 10๊ฐ์ ๋๋ถ๋ฅ ํ๊ทธ๋ก ๋ณํํ๊ธฐ ์ํด ์ฌ์ฉํ๋ csvํ์ผ์๋๋ค.
