Vận dụng cơ bản 2: Khắc phục lỗi rò rỉ dữ liệu mật khi chat với AI công cộng


**Bước 1: Chỉ ra các thông tin nhạy cảm:**
**2 biến số chứa thông tin cực kỳ nguy hiểm nếu bị người ngoài biết được:**

- db_password = 'rikkei_secret_password_2026'  
- api_key = 'google_gemini_api_abc123'

**Bước 2: Làm sạch code và viết prompt an toàn:**

sửa lại đoạn code trên bằng cách thay thế thông tin mật thành các biến tượng trưng:

def connect_database():
    db_password = '[YOUR_DATABASE_PASSWORD]'
    api_key = '[YOUR_API_KEY]'
    print('Đang kết nối...')


Viết prompt gửi kèm đoạn code đã làm sạch này lên AI để nhờ tối ưu:

Tôi đang có một hàm Python dùng để kết nối cơ sở dữ liệu và gọi API, thì tôi cần nhờ bạn làm tối ưu đoạn code này cho chuẩn phong cách lập trình (Pythonic), đồng thời gợi ý cách quản lý các biến môi trường an toàn hơn bằng thư viện os hoặc python-dotenv, đây là đoạn mã 

Python
def connect_database():
    db_password = '[YOUR_DATABASE_PASSWORD]'
    api_key = '[YOUR_API_KEY]'
    print('Đang kết nối...')

