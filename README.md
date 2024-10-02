# Những điều cơ bản trong TypeScript
## TypeScript

### 1. Static type checking
- TypeScript giúp phát hiện ra lỗi ngay trong lúc code.
- Giúp tránh lỗi type
- Tiết kiệm thời gian debug 

### 2. Types for Tooling
- TypeScript con giúp hạn chế lỗi bằng việc hỗ trợ auto completions

# Explicit type vs infered type

### 1. Explicit types (tường minh)
* khai báo kiểu dữ liệu trong typescript thì sử dụng 2 dấu chấm đằng sau tên biến

```
let count: number = 123;
let stundentName: string = 'hung';
```

### 2. Infered Types (Tự suy diên)
* TS thông minh detect được kiểu dữ liệu tương ứng  ngay cả khi mình không khai báo cụ thể kiểu dữ liệu.

```
let count = 123;
let stundentName = 'hung';
```

### 3. Eraised types
* Sau khi compile từ typescript sang javascript, tất cả type annotation sẽ bị xóa