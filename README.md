# Python Docker App with CI/CD

Dự án mẫu Python chạy trên Docker với đầy đủ cấu hình CI/CD và Docker Compose.

## Chức năng
- **Dockerized**: Chạy hoàn toàn trên Docker.
- **Hot Reload**: Mount project root để cập nhật code tức thì.
- **CI/CD**: Tự động kiểm tra code (Linting) khi đẩy lên GitHub.

## Hướng dẫn nhanh

### 1. Chạy dự án
```bash
docker compose up -d
```

### 2. Chạy thử script
```bash
docker exec python-app python app/main.py
```

## Cấu hình CI/CD
File cấu hình nằm tại [`.github/workflows/ci.yml`](.github/workflows/ci.yml).
