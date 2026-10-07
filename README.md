# Notebook minh họa — Tín hiệu và Hệ thống

Bộ notebook Jupyter minh họa cho học phần **Tín hiệu và Hệ thống**. Mỗi notebook gồm phần tóm tắt lý thuyết, code Python và hình vẽ minh họa. Sinh viên chỉ cần **đọc và chạy lần lượt các cell**, không phải tự viết code.

Tài liệu học tập: [Bài giảng Tín hiệu và hệ thống](https://github.com/dangquanghieu/book-thht)

**Lưu ý**: Các bài này có sử dụng hỗ trợ từ Claude AI và GitHub Copilot, và vẫn *đang trong quá trình hoàn thiện!*

## Danh sách notebook

| # | Chủ đề | Mở trên Colab |
|---|--------|---------------|
| 01 | Biểu diễn và các dạng tín hiệu cơ bản | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dangquanghieu/tinhieu-hethong-notebooks/blob/main/notebooks/01_bieu-dien-tin-hieu.ipynb) |

Thuật ngữ dùng trong các notebook: [`docs/thuat-ngu.md`](docs/thuat-ngu.md).

## Cách sử dụng

**Cách 1 — Google Colab (khuyến nghị):** bấm nút *Open in Colab* ở bảng trên, sau đó chọn *Runtime → Run all* (hoặc chạy từng cell bằng `Shift+Enter`). Không cần cài đặt gì. Muốn lưu lại bản đã chỉnh sửa: *File → Save a copy in Drive*.

**Cách 2 — Xem trực tiếp trên GitHub:** bấm vào file `.ipynb` trong thư mục `notebooks/`. Bạn sẽ thấy nội dung và hình vẽ, nhưng không chạy được code và (có thể) không dùng được một số tính năng tương tác nâng cao.

**Cách 3 — Chạy trên máy cá nhân:**

```bash
git clone https://github.com/dangquanghieu/tinhieu-hethong-notebooks.git
cd tinhieu-hethong-notebooks
python -m venv .venv
# Windows: .venv\Scripts\activate    |   macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
```

Sau đó mở thư mục bằng VS Code (cài extension *Python* và *Jupyter*), mở file notebook và chọn kernel `.venv`.
