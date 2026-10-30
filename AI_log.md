# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Ngô Văn Hoàng Hải ]
- Mã sinh viên – Lớp: [ CNTT 20-02 ]
- Ngày thực hiện: [ 30/10/2026 ]
- Link repository: [ (https://github.com/discorsmemaybeo-maker/K20_Fortfolio_CNTT20-02.git) ]
- URL website: [ (https://discorsmemaybeo-maker.github.io/K20_Fortfolio_CNTT20-02/) ]
- Tình huống: [x] Website của tôi  [] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ Chưa xác định được lỗi cụ thể trên website ]
- Mong muốn và hiện tượng thực tế: [ Mong muốn website Portfolio cá nhân hiển thị đầy đủ nội dung, hình ảnh và giao diện khi truy cập bằng GitHub Pages ]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [ Đã có địa chỉ repository GitHub và URL website GitHub Pages. Request URL, Status của các tài nguyên và cấu trúc tệp liên quan: Chưa kiểm tra ]
- Tôi nghi nguyên nhân là: [ Có thể liên quan đến đường dẫn tài nguyên hoặc cấu hình triển khai GitHub Pages ]
- Vì sao tôi nhận định như vậy: [ Website được triển khai trên GitHub Pages nên đường dẫn đến hình ảnh, CSS, JavaScript cần phù hợp với đường dẫn repository. Tuy nhiên, chưa có dữ kiện xác nhận đây là nguyên nhân thực tế ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: [ ChatGPT ]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [ Hãy giúp tôi kiểm tra và tìm nguyên nhân có thể gây lỗi khi triển khai website Portfolio cá nhân bằng GitHub Pages. Hướng dẫn kiểm tra đường dẫn hình ảnh, CSS, JavaScript, Request URL, Status trong DevTools và cách khắc phục nếu đường dẫn tài nguyên không chính xác ]

- Gợi ý chính của AI:

  [ 1.Kiểm tra cấu trúc thư mục và tên các tệp trong repository
    2.Kiểm tra đường dẫn hình ảnh, CSS và JavaScript, đặc biệt khi website được triển khai trong một repository riêng
    3.Mở Developer Tools bằng phím F12, chọn tab Network để kiểm tra Request URL và Status
    4.Nếu tài nguyên bị lỗi 404, kiểm tra lại đường dẫn, tên tệp và chữ hoa, chữ thường
    5.Kiểm tra cấu hình GitHub Pages và bảo đảm phiên bản mới nhất đã được triển khai.
    6.Tải lại website sau khi triển khai để xác nhận kết quả ]

## 3. Quyết định của tôi

- [ ] Chấp nhận gợi ý
- [x] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ Ưu tiên kiểm tra đường dẫn tài nguyên, cấu trúc thư mục và trạng thái triển khai GitHub Pages trước khi chỉnh sửa mã nguồn. Chỉ thay đổi những vị trí có dữ kiện xác nhận là sai ]
- Lý do, dựa trên dữ kiện nào: [ Website sử dụng GitHub Pages với repository riêng nên cần bảo đảm đường dẫn tài nguyên tương thích với đường dẫn triển khai. Chưa có bằng chứng xác nhận lỗi 404 nên không sửa mã nguồn một cách tùy tiện ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [ Chưa sửa tệp nào do chưa xác định được vị trí phát sinh lỗi ]
- Nội dung thay đổi hoặc cách xử lý khác: [ Đề ra quy trình kiểm tra đường dẫn tài nguyên, cấu trúc thư mục và cấu hình GitHub Pages trước khi thực hiện sửa lỗi ]
- Commit của bản sửa, nếu có: [ Không phát sinh commit sửa lỗi ]
- Bản sửa đã deploy: [ ] Có  [ ] Chưa  [x] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | [ chưa kiểm tra ] | [ chưa kiểm tra ] |
| Giao diện/chức năng trên URL website | [ hoạt động bình thường ] | [ hoạt động bình thường ] |

- Cách thử lại và kết quả thực tế: [ chưa kiểm tra ]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [ (https://github.com/discorsmemaybeo-maker/K20_Fortfolio_CNTT20-02.git) 
https://discorsmemaybeo-maker.github.io/K20_Fortfolio_CNTT20-02/]

## 5. Kết luận

- [ ] Đã xử lý được  [ ] Xử lý được một phần  [x] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [ Tôi hiểu rằng khi triển khai website bằng GitHub Pages cần chú ý đến đường dẫn tương đối, cấu trúc thư mục và tên tài nguyên. Khi gặp lỗi, cần sử dụng Developer Tools để kiểm tra Request URL và Status trước khi sửa mã nguồn. Việc tiếp theo là kiểm tra trực tiếp website, xác định tài nguyên có lỗi (nếu có), tiến hành sửa và kiểm chứng lại sau khi deploy ]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
