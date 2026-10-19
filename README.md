# Bài tập chương 11 – Publish App/API

Các ứng dụng WinForms được tổ chức riêng trong folder theo số thứ tự câu. Project dùng .NET 8, EF Core SQL Server và script SQL mẫu.

## Chạy ứng dụng

1. Mở SQL Server Management Studio và chạy `Database.sql` trong folder bài tương ứng.
2. Tạo `appsettings.json` từ `appsettings.example.json`, sau đó cập nhật connection string theo máy.
3. Mở file `.csproj` bằng Visual Studio hoặc chạy `dotnet run --project <project>.csproj` trong folder đó.

| Folder | Project |
| --- | --- |
| `1/` | Sổ chi tiêu cá nhân |
| `2/` | Quản lý nhà trọ |
| `3/` | Kế hoạch dã ngoại |
| `4/` | Bán hàng quán trà sữa |

Yêu cầu môi trường Windows, .NET 8 Desktop Runtime và SQL Server. Các chức năng gọi API cần có kết nối Internet.
