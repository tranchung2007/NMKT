## So sánh các hệ điều hành phổ biến Windows, Linux, MacOs dưới góc nhìn của người dùng và nhà phát triển

### Khung xương

***TODO: Điều chỉnh bộ khung sao cho hợp lý***

    1. Tổng quan về các hệ điều hành phổ biến hiện nay
       1. Hệ điều hành là gì
       2. Hệ điều hành gồm những thành phần cơ bản nào, cách mà hệ điều hành hoạt động
       3. Các loại hệ điều hành phổ biến hiện nay
       4. Thị phần hệ điều hành ngày nay <Bảng biểu, sơ đồ, thống kê>
          + Máy chủ và siêu máy tính
          + Máy tính cá nhân và thiết bị di động
    2. Quá trình hình thành và phát triển của từng hệ điều hành
       1. Từ **MS-DOS** cho đến sự thống trị của **Windows**
       2. Unix, **GNU và Linux** và **sức mạnh của cộng đồng mã nguồn mở**
       3. **MacOS** - sự kế thừa, hoàn thiện và phát triển hoàn hảo của OS X

    3. So sánh các hệ điều hành thông qua góc nhìn của người dùng phổ thông
       - Tiêu chí đánh giá: user-friendly: thân thiện người dùng, thao tác đơn giản, dễ sử dụng, tính ổn định, linh hoạt
       1. Windows
       2. GNU/Linux và các phần mềm mã nguồn mở
       3. MacOS
       4, Tổng kết <Bảng>

    4. So sánh các hệ điều hành thông qua con mắt của các nhà phát triển và lập trình viên
       - Tiêu chí đánh giá: mức độ hỗ trợ các phần mềm phát triển, khả năng setup môi trường lập trình, các công cụ tiêu biểu
       1. Windows
       2. GNU/Linux và các phần mềm mã nguồn mở
       3. MacOS
       4, Tổng kết <Bảng>

    5. Nguồn và tài liệu tham khảo
       - [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/intro.pdf)

### Nội dung chi tiết cho từng phần

#### 1.1:
- Trước khi vào chủ đề chính của báo cáo, chúng ta hãy làm một chuyến tham quan về lịch sử ra đời của hệ điều hành:
- Máy tính thời kì những năm 1940 đến đầu những năm 1950 là những cỗ máy vô cùng đồ sộ, tuy nhiên chúng chạy rất chậm và chỉ có thể chạy một chương trình một lúc. Lập trình viên khi đó sẽ viết những dòng mã ở bên ngoài sau đó mang vào trong phòng máy để chạy, lập trình viên khác sẽ mang chương trình của mình vào chạy sau khi đã chạy xong chương trình của người trước. Cứ lặp lại , lặp lại như thế ... Công việc "tay chân" đó đối với chúng ta ngày này sẽ thấy rất là kì lạ, nhưng vào ngày đấy đó là điều bình thường, máy tính tính toán rất chậm, một chương trình có thể tốn đến nhiều giờ hoặc nhiều ngày, người ta đã quen với điều đó như là chuyện thường ngày. Nhưng khoan đã, nếu mọi chuyện cứ tiếp diễn như vậy tại sao máy tính mà ta biết ngày nay lại không giống những gì vừa nghe? Rốt cuộc có chuyện gì đã xảy ra, hay nói đúng hơn là: **Cái gì đã được tạo ra** ?
- Tiếp tục quay trở lại vào những năm 50, máy tính đã và đang trở nên nhanh hơn, nhanh hơn, nhanh hơn rất nhiều, rất nhiều, đến mức theo cấp số nhân, tốc độ thực thi chương trình đã nhanh hơn thấy rất nhiều, việc nhét chương trình vào còn lâu hơn cả khi nó chạy xong. Đến khi đó người ta nhận ra rằng: Con người lúc này là không cần thiết, đã đến lúc để cho máy tính tự vận hành chính nó. Và đó chính là lúc mà **HỆ ĐIỀU HÀNH** ra đời.
- Hệ điều hành lúc sơ khai nhất được ra đời vào những năm 50, khi mà máy tính trở nên phổ biến rộng rãi hơn, làm nhiệm vụ đơn giản là tải chương trình một cách tự động, thay vì việc xử lí từng chương trình được nhét vào, máy tính giờ đây hoạt động theo cơ chế Batch Processing(tạm gọi là xử lý theo nhóm). Người ta sẽ đưa vào máy tính một nhóm các chương trình, khi một chương trình kết thúc, máy tính sẽ ngay lập tức chạy chương trình kế tiếp gần như ngay lập tức, không còn quãng nghỉ, không còn đau đầu việc chạy lung tung quanh văn phòng để tìm chương trình kế tiếp, công việc lúc này đã trở nên nhanh và liền mạch hơn.
- Khi mà máy tính nhanh hơn, điều đó đồng nghĩa là giá thành của một chiếc máy sẽ giảm đi đáng kể, tiếp cận nhiều đối tượng hơn, là các chính phủ, các công ty và các trường đại học. Và rồi người ta bắt đầu chia sẻ phần mềm cho nhau, nhưng vấn đề lại một lần nữa nảy sinh: các phần mềm chỉ được thiết kế chỉ để chạy trên một mẫu máy với một cấu hình duy nhất nơi mà phần cứng giống hệt nhau và không bị thay đổi. Nhưng khi có càng nhiều máy, cấu hình của chúng không lúc nào cũng vậy, chúng có thể có cùng vi xử lí nhưng có thể khác nhau về máy in, ... Điều này làm cho các lập trình viên vô cùng đau đầu, không chỉ việc phải viết chương trình, đồng thời còn phải lo làm sao để chương trình đó có thể chạy được ở trên một mẫu khác. Thêm một điều cực kì quan trọng, vào thời đó các ngôn ngữ lập trình chưa phát triển, hầu hết tất cả các chương trình đều được viết bằng hợp ngữ(Assembly language), mỗi lập trình viên khi muốn viết cho một thiết bị khác cần phải đọc rất nhiều sách hướng dẫn của từng thiết bị, điều này yêu cầu lập trình viên phải có hiểu biết tường tận về từng chi tiết phần cứng của từng thiết bị khác nhau. Hơn nữa, nếu lập trình viên muốn kiểm thử(Testing) phần mềm của mình thì sẽ phải mua hết tất cả những thiết bị ngoại vi khác chỉ để đảm bảo phần mềm của mình có thể hoạt động được trên máy của người khác. Họ không còn cách nào khác chỉ còn biết cách làm hết sức mình và cầu mong cho chương trình của mình sẽ chạy được. Thật sự đó là một cơn ác mộng.
- Nhằm giúp cho lập trình viên bớt đau khổ, hệ điều hành đã tiến hóa trở thành một trung gian giữa phần mềm và phần cứng(ở đây là các thiết bị ngoại vi). Hệ điều hành sẽ cung cấp software abstraction(tạm gọi là lớp trìu tượng) sẽ trìu tượng hóa mối quan hệ giữa phần mềm và phần cứng thông qua các API(ta có thể tạm coi là những luật lệ cụ thể quy ước giữa hệ điều hành và phần ) hoặc là các system call, cái mà chung ta ngày nay gọi là Device Drivers. Chúng sẽ cho phép lập trình viên "nói chuyện" với đầu vào và đầu ra cả phần cứng(I/O), thông qua một quy chuẩn chung duy nhất. Một hệ diều hành tiêu chuẩn sẽ có vài trăm syscall để cho ứng dụng sử dụng. Ta đôi khi cũng có thể nói rằng, hệ điều hành cung cấp một thư viện tiêu chuẩn(standard library) cho các ứng dụng.
- Vào cuối những năm 50, đại học Manchester(Anh) đã bắt đầu làm việc với siêu máy tính Atlas. Do chiếc máy này vô cùng nhanh, họ đã phải tìm cách làm sao để tối đa hóa công năng của chiếc máy cực kỳ đắt tiền này. Lời giải cho bài toán đó là một chương trình mang tên Atlas Supervisor(AS) được hoàn thiện vào năm 1962, phần mềm này cho phép chiếc máy chạy cùng lúc vài chương trình trên duy nhất một CPU. Thực tế, nó có thể chạy nhiều chương trình tính toán, đồng thời in ra kết quả, và đồng thời đọc dữ liệu đầu vào, tất cả diễn ra cùng một lúc. Khả năng này là cái mà chúng ta vẫn gọi là tính năng Đa Nhiệm(Multi Tasking), là điều cơ bản mà tất cả các máy tính bây giờ đều có, nhưng thời đó đây là một phát kiến vĩ đại, một bước tiến quan trọng trong lịch sử của hệ điều hành. AS cũng được nhiều người coi ràng là hệ điều hành hiện đại(modern OS) đầu tiên.
- Để hỗ trợ cho việc chạy nhiều ứng dụng cùng một lúc, hệ điều hành đã được cải tiến với tính năng Ảo hóa Bộ nhớ (virtualization memory), nói đơn giản là việc cấp phát bộ nhớ sẽ do hệ điều hành đảm nhận, nó sẽ tạo ra các bộ nhớ ảo từ bộ nhớ vật lý và cho ứng dụng sử dụng các phần bộ nhớ ảo đó để hoạt động. Vấn đề là tại sao phải làm như thế, chẳng phải cứ để chương trình chạy tự do là được rồi hay sao, hoàn toàn không có vấn đề gì hết? Đúng vậy, chương trình thì không có vấn đề gì cả, thứ gặp vấn đề chính là các nhà phát triển. Nhiều chương trình chạy cùng lúc mà mỗi chương trình lại chạy sang những vùng nhớ khác nhau, không theo quy luật nào cả, điều này khiến cho nhà phát triển rất khó để có thể theo dõi và sửa lỗi. Hệ điều hành bắt các chương trình chạy trong các vùng bộ nhớ ảo đã được cho sẵn để người dùng dễ dàng quản lý ứng dụng đang chạy, việc truy vết dữ liệu cũng trở nên đơn giản hơn.

***TODOS: hoàn thiện Virtual Memory và Memory Protection***

- Ngoài ra hệ điều hành còn đảm nhận công việc quản lý bộ nhớ với tính năng Ảo hóa bộ nhớ ...
- Đi cùng với VM, còn có cả tính năng Memory Protection ...

***TODO: Điều chỉnh phần dưới cho hợp lý, sửa xóa cho thích hợp***

- Nếu theo khối ngành công nghệ thông tin thì chắc hẳn bạn cũng có một chút mường tượng về cách mà một chương trình hoạt động. Vậy chuyện gì thực sự xảy ra khi một phần mềm chạy ? Rất đơn giản, khi một chương trình chạy trong hệ thống, nó làm duy nhất một điều đó chính là: **thực thi các mã lệnh (executes instructions)**. Một chương trình có thể được coi là tập hợp các mã lệnh, khi chương trình bắt đầu chạy, vi xử lí sẽ lấy(fetchs) mã lệnh từ bộ nhớ, giải mã(decodes), xong rồi thực thi(executes), quá trình này lặp đi lặp lại cho đến khi chương trình kết thúc.

- Tuy nhiên,  nếu chương trình được viết theo cách đấy thì sẽ gây khó khăn rất lớn bởi nhà phát triển sẽ phải học cả cách làm việc chuyên sâu với cả phần cứng lẫn phần mềm. Chính vì điều đó mà hệ điều hành ra đời, giống như phần thân của chương trình, nó khiến cho chương trình dễ dàng chạy hơn(easy-to-run), cho phép chương trình truy cập bộ nhớ, giao tiếp với các thiết bị phần cứng, hoặc những việc tương đương. Hệ điều hành còn cung cấp một số tính năng giúp cho việc sử dụng máy tính an toàn và hiệu quả hơn vd: Cấp phát bộ nhớ tự động(Dynamic Memory Allocation), Protected Memory(bảo vệ bộ nhớ), Đa nhiệm(Multi Threading), 

- Chúng ta cùng đi qua một chút lịch sử về sự ra đời của hệ điều hành đầu tiên
+ Vào

- Nói tóm lại, Hệ điểu hành(Operating System) là 1 loại phần mềm hệ thống, có nhiệm vụ chính là kiểm tra, kiểm soát nhằm chắc chắn rằng hệ thống hoạt động chính xác và hiệu quả đúng mong muốn.

#### 1.2:
- Khi bạn viết một chương trình máy tính, nếu bạn để ý thì sẽ không chỉ có mỗi chương trình của bạn chạy mà sẽ còn có cả vô số thứ khác của hệ điều hành chạy kèm theo chỉ với mục tiêu duy nhất là khiến cho hệ thống dễ dàng để sủ dụng.
- Hệ điều hành nói chung sẽ đều hoạt động theo một nguyên tắc chung đó là **Ảo hóa(Virtualization)**. Nghĩa là hệ điều hành sẽ chuyển đổi tài nguyên vật lý của máy(vi xử lí, bộ nhớ, ...) trở thành một phiên bản ảo chung hơn, mạnh mẽ hơn, dễ sử dụng hơn của chính nó. Chính vì điều này ta đôi khí cũng có thể hệ điều hành giống như một máy ảo(virtual machine).
- Khi người dùng muốn giao tiếp với OS, các OS sẽ cung cấp một vài phương thức(APIs) để người dùng có thể gọi.
