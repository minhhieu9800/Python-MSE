
# Sau khi chắt lọc ý kiến của mọi người, e đã chạy được ngon hết, nay tổng hợp lại cần sửa 3 cái nhé:
1. Thêm các dòng lệnh để downgrade vài package về đúng version đang dùng (trước phần Import thư viện ở đầu chương trình nhé)
```
!pip install pandas==1.1.3
!pip install pystan==2.19.1.1
!pip install fbprophet 
```
2. Thay thế các đường dẫn lấy data
```
sell_prices_df = pd.read_csv('https://media.githubusercontent.com/media/minhhieu9800/Python-MSE/main/Data/sell_prices.csv')
train_sales_df = pd.read_csv('https://media.githubusercontent.com/media/minhhieu9800/Python-MSE/main/Data/sales_train_validation.csv')
calendar_df = pd.read_csv('https://media.githubusercontent.com/media/minhhieu9800/Python-MSE/main/Data/calendar.csv')
submission_file = pd.read_csv('https://media.githubusercontent.com/media/minhhieu9800/Python-MSE/main/Data/sample_submission.csv')
```
3. Khi chạy nếu gặp các lỗi liên quan đến hàm `sum(axis=1)`, mọi người sửa thành `sum()` là ok nhé!


## Good luck everyone!
