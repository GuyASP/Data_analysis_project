# Data_analysis_project

## link to kaggle
https://www.kaggle.com/datasets/elianaj/mexico-air-quality-dataset

## อธิบายชุดข้อมูล
1.stations_daily.csv - เก็บข้อมูลเกี่ยวกับมลภาวะทางอากาศ เช่น pm2.5, pm10 , แก๊สต่างๆ ที่อยู่ในอากาศ, ความชื้น และ อุณหภูมิ เป็นต้น เก็บแยกตามสถานี เก็บเป็นรายวัน
2.stations_hourly.csv - เก็บข้อมูลเหมือน "stations_daily.csv" แต่เก็บเป็นรายชั่วโมง (เราไม่ได้ใช้ข้อมูลชุดนี้เลยเพราะ สิ่งที่เราวิเคราะห์ไม่ต้องใช้เป็นรายชั่วโมง)
3.stations_rsinaica.csv - เก็บข้อมูลเกี่ยวกับสถานี เช่น latitude, longitude และ network_name (urban or city) เป็นต้น
ข้อมูลที่ได้รับมามี missing values ค่อนข้างมาก โดยเฉพาะในปี "ลืมเดี๋ยวมาเพิ่ม" เราจึงได้ทำการคัดเลือกข้อมูลมาเฉพาะปี 2015 - 2021 เพื่อใช้ในการวิเคราะห์ต่อไป
