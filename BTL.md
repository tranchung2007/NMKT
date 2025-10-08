## So sánh các hệ điều hành phổ biến Windows, Linux, MacOs dưới góc nhìn của người dùng và nhà phát triển

### Khung xương

    1. Tổng quan về các hệ điều hành phổ biến hiện nay
       1. Hệ điều hành là gì
       2. Hệ điều hành gồm những thành phần cơ bản nào
       3. Các loại hệ điều hành phổ biến hiện nay
       4. Thị phần hệ điều hành ngày nay <Bảng biểu, sơ đồ, thống kê>
          + Máy chủ và siêu máy tính
          + Máy tính cá nhân và thiết bị di động
    2. Quá trình hình thành và phát triển của từng hệ điều hành
       1. Từ **MS-DOS** cho đến sự thống trị của **Windows**
       2. Unix, **GNU và Linux** và **sức mạnh của cộng đồng mã nguồn mở**
       3. **MacOS** - sự kế thừa, hoàn thiện và phát triển hoàn hảo của OS X

    2. So sánh các hệ điều hành thông qua góc nhìn của người dùng phổ thông
       - Tiêu chí đánh giá: user-friendly: thân thiện người dùng, thao tác đơn giản, dễ sử dụng, tính ổn định, linh hoạt
       1. Windows
       2. GNU/Linux và các phần mềm mã nguồn mở
       3. MacOS
       4, Tổng kết <Bảng>

    3. So sánh các hệ điều hành thông qua con mắt của các nhà phát triển và lập trình viên
       - Tiêu chí đánh giá: mức độ hỗ trợ các phần mềm phát triển, khả năng setup môi trường lập trình, các công cụ tiêu biểu
       1. Windows
       2. GNU/Linux và các phần mềm mã nguồn mở
       3. MacOS
       4, Tổng kết <Bảng>

    4. Nguồn và tài liệu tham khảo
       - [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf)

### Nội dung chi tiết cho từng phần

#### 1.1:
- Nếu theo khối ngành công nghệ thông tin thì chắc hẳn bạn cũng có một chút mường tượng về cách mà một chương trình hoạt động. Vậy chuyện gì thực sự xảy ra khi một phần mềm chạy ? Rất đơn giản, khi một chương trình chạy trong hệ thống, nó làm duy nhất một điều đó chính là: **thực thi các mã lệnh (executes instructions)**. Một chương trình có thể được coi là tập hợp các mã lệnh, Khi chương trình bắt đầu chạy, vi xử lí sẽ lấy(fetchs) mã lệnh từ bộ nhớ, giải mã(decodes), xong rồi thực thi(executes), quá trình này lặp đi lặp lại cho đến khi chương trình kết thúc. Tuy nhiên,  nếu chương trình được viết theo cách đấy thì sẽ gây khó khăn rất lớn bởi nhà phát triển sẽ phải học cả cách làm việc chuyên sâu với cả phần cứng lẫn phần mềm. Chính vì điều đó mà hệ điều hành ra đời, giống như phần thân của chương trình, nó khiến cho chương trình dễ dàng chạy hơn(easy-to-run), cho phép chương trình truy cập bộ nhớ, giao tiếp với các thiết bị phần cứng, hoặc những việc tương tự.

- Nói tóm lại, Hệ điểu hành(Operating System) là 1 loại phần mềm hệ thống, có nhiệm vụ chính là kiểm tra, kiểm soát nhằm chắc chắn rằng hệ thống hoạt động chính xác và hiệu quả đúng mong muốn.

-

#### 1.2:
- Khi bạn viết một chương trình máy tính, nếu bạn để ý
