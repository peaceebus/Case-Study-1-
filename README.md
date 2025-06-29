# Case-Study-1
DSA Project: Amazon Product Review Analysis 

The pivot table and dashboard will be pasted via screenshot

![Screenshot (3)](https://github.com/user-attachments/assets/04cf80c7-a146-47bd-ab09-aaab9ecbf567)
![Screenshot (4)](https://github.com/user-attachments/assets/faf8b8ab-2b79-4e57-acf3-474d285a58b5)
![Screenshot (5)](https://github.com/user-attachments/assets/630612c5-55fd-44db-9fe8-b70a00649950)
![Screenshot (6)](https://github.com/user-attachments/assets/2fad865c-a65e-4066-b775-30f6bf1ade80)
![Screenshot (7)](https://github.com/user-attachments/assets/e8dee4a5-2060-4f14-8111-467dcb3ab43f)
![Screenshot (8)](https://github.com/user-attachments/assets/249385e1-18f0-43a2-a972-a974f14bea98)
![Screenshot (9)](https://github.com/user-attachments/assets/bcbd68e8-2d3e-4e91-9cb6-d226d89cfd7a)
![Screenshot (10)](https://github.com/user-attachments/assets/f3a6fa37-5732-40df-b1b7-861f9d065abe)
![Screenshot (11)](https://github.com/user-attachments/assets/67e5b4fc-94f9-4009-bb7f-c0e1493f9c77)
![Screenshot (12)](https://github.com/user-attachments/assets/31b66728-a564-4c11-b3e1-41e1d3e7e85f)
![Screenshot (13)](https://github.com/user-attachments/assets/d9946170-509b-428e-a5c8-5f6d67348663)
![Screenshot (14)](https://github.com/user-attachments/assets/a1ca0395-61a5-4935-9e72-4d975876a5ff)
![Screenshot (15)](https://github.com/user-attachments/assets/34a0c37e-0d68-4ad4-822f-bab2286c4c39)
![Screenshot (16)](https://github.com/user-attachments/assets/16fe87a6-790b-4790-a8e6-df795adbea46)
![Screenshot (17)](https://github.com/user-attachments/assets/8ad01be2-a8b3-4116-8fab-9394b860cab6)
![Screenshot (18)](https://github.com/user-attachments/assets/8814127c-6495-4151-a3d4-bc4abfefa94f)
![Screenshot (19)](https://github.com/user-attachments/assets/a35c202e-f974-4ef8-bcb1-c1c837d17fa0)
![Screenshot (20)](https://github.com/user-attachments/assets/7d1178b2-b657-47ab-8429-e84790028c95)
![Screenshot (21)](https://github.com/user-attachments/assets/179f5221-929d-4922-903d-2a8b7da439b1)
![Screenshot (22)](https://github.com/user-attachments/assets/b23ddad6-c6be-4197-beca-87a3e6f40317)
![Screenshot (23)](https://github.com/user-attachments/assets/cb60c043-dc18-482f-aff8-3b17a84c48bf)



**The following questions that require formula;**

7. How many products have a discount of 50% or more?

   ANSWER: =IF(B3 >=50%, "Yes", "No")

9. What is the total potential revenue (actual_price × rating_count) by category?

    ANSWER: =B5 * C5

10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?

    ANSWER: =IF(C4 < 200, "<200", IF(C4 <=500, "200-500", ">500"))

12.  How many products have fewer than 1,000 reviews?

    ANSWER: =COUNTIF(B4, "<1000")




