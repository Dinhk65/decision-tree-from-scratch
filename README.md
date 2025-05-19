# 🌳 Decision Tree Classifier - Explained from Scratch

> Học thuật toán cây quyết định một cách trực quan, dễ hiểu và **code bằng Python từ A-Z**, không dùng thư viện ML ngoài!

---

## 🔍 Mục tiêu notebook này

Notebook này được tạo ra với mục tiêu:
- Hiểu **nguyên lý hoạt động** của thuật toán Decision Tree.
- Tự xây dựng một mô hình Decision Tree **từ đầu bằng Python** (không dùng sklearn).
- Giải thích từng bước bằng markdown chi tiết: Entropy là gì? Thông tin nào là "tốt"? Cách cây chọn thuộc tính chia nhánh?

---

## 🧠 Những kiến thức được trình bày

| Chủ đề | Mô tả |
|--------|-------|
| ✅ Entropy | Đo lường độ hỗn loạn của dữ liệu |
| ✅ Information Gain | Chỉ số chọn thuộc tính tốt nhất để phân nhánh |
| ✅ Recursive Tree Building | Xây dựng cây theo cách đệ quy |
| ✅ Predict function | Cách sử dụng cây để dự đoán |
| ✅ Mini Demo | Thử mô hình trên bộ dữ liệu giả lập nhỏ |

---

## 📦 Yêu cầu môi trường

Notebook sử dụng các thư viện cơ bản:
```bash
numpy
Counter
