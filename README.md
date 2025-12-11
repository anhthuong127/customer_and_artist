**🎵 Music Store SQL Analysis**

**📌 Project Description**

This project uses a database designed to simulate an online music store, including operations such as purchasing albums, tracks, and managing customer information.
The dataset supports practicing SQL skills such as joins, CTEs, window functions, aggregation, customer behavior analysis, and more.

The SQL tasks below demonstrate real-world analytical scenarios commonly seen in Data Analyst / BI Analyst roles.

**📚 SQL Queries & Business Questions**

1️⃣ Customers Who Purchased ≥2 Genres Including “Alternative & Punk”

Output: Customer_Id | FullName | Email | NumberOfGenres

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/39aa6609-5731-4c3e-8930-26ca2b32d156" />
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/cb96e27b-6c4e-4135-8804-b504e5d71291" />

2️⃣ Quarterly Revenue Analysis – Q4 2018

Output: Invoice_Id | Invoice_Date | Total_Sale | AverageInvoice | PercentageOfQuarterlyAverage
→ Tính doanh thu từng hóa đơn, trung bình quý 4, và % mỗi hóa đơn so với trung bình quý.

<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/8e9b444d-bf98-4a1d-af44-576e9dd7185e" />

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/e98dbf62-f221-4591-8211-e3e40e6229fc" />

3️⃣ Customer Tier Classification

Output: Customer_Id | FullName | TotalAmountSpent | CustomerTier

→ Khách hàng có ≥5 invoices và tổng chi tiêu > 25$ sẽ được phân vào 3 tier.

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/3516b53a-687e-4a5d-8eab-c946fda30f90" />
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/d49e58f6-ad30-4b8e-b80a-84ef80d8ebed" />

4️⃣ Genre Performance by Quarter (2017)

Output: Quarter | GenreName | Invoice_Count | Customer_Count | QuarterlyRank

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/a844a3be-e4ad-4813-83bc-a97ba4fc6f42" />

5️⃣ Loyal vs Churned Customers (2017 → 2018)

Output:CustomerType | CustomerCount | TotalRevenueIn2017

Loyal = mua năm 2017 và 2018
Churned = mua năm 2017 nhưng không mua năm 2018
Tính tổng doanh thu năm 2017 của từng nhóm
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/01886f15-35ed-43c0-8882-29c243722698" />

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/1e424d93-9eac-4c92-81a6-88eb9322c832" />

6️⃣ Month-over-Month Revenue Difference (2017)

Output: Month | MonthlyRevenue | PreviousMonthRevenue | RevenueDifference

Tính chênh lệch doanh thu từng tháng. Tháng đầu tiên có PreviousMonthRevenue = 0

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/debf321d-e6ea-417b-ae64-7e9b2831ca63" />
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/46de7829-6d61-4822-aa1f-1de4eec5ec6a" />


7️⃣ Customer Growth Rate (Invoices & Amount – 2017 vs 2018)

Output: FullName | Invoices2017 | Invoices2018 | InvoiceGrowthRate | TotalAmount2017 | TotalAmount2018 | AmountGrowthRate

Tính % tăng trưởng số hóa đơn
Tính % tăng trưởng tổng chi tiêu

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/7cc9b599-3c28-4853-923b-c4694d9017a7" />

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/892c8e29-a29f-47c5-a52c-e64fd164d436" />

8️⃣ Top Spenders by Country

Output: FullName | Country | TotalAmount

Trả ra khách hàng có chi tiêu cao nhất trong mỗi quốc gia
Nếu nhiều khách hàng đồng hạng, trả về tất cả

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/1b8a54e0-fc9d-4c00-858e-0745981f592f" />
<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/36cb99f9-c6a2-42c2-9b75-b0e3b65f4a4e" />



9️⃣ Employee → Manager → Senior Manager Hierarchy

Output: EmployeeName | ManagerName | SeniorManagerName | SubordinateCount

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/dba1b3e9-410d-4148-9aa1-00496c7b5568" />

🔟 Customers Who Bought the Same Track ≥2 Times

Output: FullName | Email | TrackName | NumberOfPurchases

Tìm khách hàng mua cùng 1 bài hát từ 2 hóa đơn trở lên
Tính số lần mua bài hát đó

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/0d3d2b83-b145-497d-87f3-7bd0fd7c0f66" />

<img width="300" height="200" alt="image" src="https://github.com/user-attachments/assets/de92b613-36b3-4df9-b267-1773f9f98612" />


**🛠 Tools**
- SQL / BigQuery
- Window Functions
- CTE (WITH statements)
- Aggregations & Joins
- Customer Behavior Analytics

- 🚀 Project Links | Liên kết dự án
📂 Authour: Thuong Tran
LinkedIn: https://www.linkedin.com/in/trananhthuong/

💻 GitHub (Code):
(https://github.com/anhthuong127/customer_and_artist/)

📂 Cleaned Data:
https://drive.google.com/drive/folders/104JpiiIovnQTQTMnIcI6lDdm9z57dLlE
