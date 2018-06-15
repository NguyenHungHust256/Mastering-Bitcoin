# Mastering Bitcoin
## Chương 1: Introducting
#### Bitcoin là gì?
<p>&nbsp Bitcoin là một tập các khái niệm và công nghệ tạo thành hệ sinh thái tiền kỹ thuật số. Đơn vị tiền bitcoin có thể được sử dung để lưu trữ và giao dịch với những người tham gia mạng lưới bitcoin. Người dung bitcoin  giao tiếp với người khác sử dụng giao thức của bitcoin. Ngăn xếp giao thức bitcoin, có sẵn như một phần mềm mã nguồn mở, có thể chạy trên nhiều thiết bị như laptop, smartphone, làm cho dễ dàng truy cập.</p>
<p>&nbsp Người dùng có thể giao dịch bitcoin thông qua mạng để có thể mua, bán hang, gửi tiền để mọi người, các tổ chức,... Công nghệ bitcoin dựa trên <b>mã hóa</b> và <b>chữ ký số</b> để đảm bảo an ninh trong mạng bitcoin. Bitcoin có thể mua, bán và trao đổi với các đồng tiền khác.Bitcoin là một dạng tiền hoàn hảo trên internet bởi vì nó nhanh, bảo mật và không giới hạn.</p>
<p>&nbsp  Không giống như tiền truyền thống, bitcoin hoàn toàn là ảo. Không có đồng tiền vật lý hoặc thậm chí tiền xu kĩ thuật số. Coins được áp dụng trong transactions chuyển từ người này đến người khác. Người dùng các khóa riêng bitcoin cho phép họ chứng minh giao dịch của chủ sỡ hữu trong mạng bitcoin, mở khóa giá trị để gửi và chuyển giao cho người nhận mới. Cái key này được lưu trữ trong digital wallet của mỗi máy tính người sử dụng. Sở hữu chìa khóa mở khóa giao dịch là điều kiện tiên quyết duy nhất để chi tiêu bitcoin, đưa toàn bộ quyền kiểm soát vào tay của mỗi người dùng.</p>
<p>&nbsp Bitcoin là một hệ thống peer to peer, fully-distributed. Như là không có server trung tâm hoặc điểm điều khiển. Bitcoin được tạo thông qua quy trình gọi là "mining"-quá trình tìm kiếm lời giải cho 1 bài toán khó. Bất kỳ người tham gia trong mạng lưới bitcoin có thể là tác nhân như 1 miner(người đào), sử dụng năng lượng máy tính để cố gắng tìm lời giải cho bài toán này. Cứ trung bình 10 phút thì sẽ có ai đó tìm ra lời giải, và được thưởng 1 số tiền bitcoin nào đó.</p>
<p>&nbsp Giao thức bitcoin bao gồm các thuật toán tích hợp điều chỉnh chức năng đào trên mạng. Khó khăn của vấn đề mà người đào phải giải quyết được điều chỉnh động sao cho cứ trung bình 10 phút thì tìm được 1 lời giải chính xác trong tổng tất cả các người tham gia đào. Giới hạn số coin là 21 triệu coin và theo tính toán thì đến năm 2140 thì số bitcoin sẽ tạo ra là 21 triệu coin.</p>
<p>&nbsp Bên cạnh đó thì bitcoin cũng là tên của giao thức, 1 mạng, và một sự đổi mới phân tán máy tính. Đồng tiền bitcoin thực sự chỉ là ứng dụng đầu tiên của sự sáng chế này. Là một nhà phát triển, tôi thấy bitcoin như là một đồng tiền internet, một mạng lưới để truyền bá giá trị đồng tiền và đảm bảo chủ sỡ hữu tài sản thông qua mạng lưới phân tán.</p>
<p>&nbsp Ở chương này, chúng tôi bắt đầu bởi giải thích vài khái niệm chính, đưa ra các phần mềm cần thiết và sử dụng bitcoin cho một vài giao dịch đơn giản. Trong các chương tiếp theo, chúng ta sẽ tìm hiểu về các công nghệ được sử dụng trong bitcoin.</p>

<h4>Lịch sử bitcoin</h4>
<p>&nbsp Bitcoin được phát minh vào năm 2008 bởi Satoshi Nakamoto với việc đăng 1 bài báo có title :"Bitcoin: A Peer-to-Peer Electronic Cash System". Satoshi Nakamoto kết hợp một số phát minh trước như b-money và HashCash để tạo ra một hệ thống tiền mặt điện tử hoàn toàn không  tập trung mà không dựa vào một cơ quan trung ương để phát hành tiền tệ hoặc thanh toán và xác nhận giao dịch. Sự đổi mới quan trọng là sử dụng hệ thống tính toán phân tán để tạo ra 1 bitcoin sau 10 phút, cho phép mạng không tập trung đi đến sự đồng thuận về trạng thái giao dịch. Có 1 vấn đề ở đây là double-spend, tức là 1 đồng tiền có thể được tiêu 2 lần thì bitcoin đã giải quyết được. Trước đây, vấn đề này là một sự nhạy cảm của các đồng tiền kĩ thuật số và được giải quyết bằng cách xóa tất cả các giao dịch thông qua một trung tâm thanh toán bù trừ trung tâm.</p>
<p>Mạng lưới bitcoin được bắt đầu vào năm 2009, dựa trên một tài liệu tham khảo được publish bởi Nakamoto và bởi nhiều lập trình viên khác. Tính toán phân tán cung cấp bảo mật và khả năng phục hồi bitcoin tăng theo cấp số nhân và bây giờ vượt qua năng lực tính toán của các siêu máy tính trên thế giới kết hợp lại với nhau. Tổng giá trị thị trường của Bitcoin ước tính từ 5 đến 10 tỷ đô la Mỹ. Giao dịch lớn nhất tính đến hiện nay.</p>
<p>Satoshi Nakamoto rút khỏi công chúng vào tháng 4 năm 2011, để lại trách nhiệm phát triển mã và mạng cho các group tình nguyện. Tên của Satoshi Nakamoto là 1 tên bí danh và hiện giờ vẫn chưa biết được chính xác người đó là ai. Tuy nhiên, Nakamoto hay ai đó cũng không thể điều khiển hệ thống bitcoin. Bản thân phát minh này là đột phá và đã sinh ra khoa học mới trong các lĩnh vực điện toán phân tán, kinh tế và kinh tế lượng.</p>
<h4>Bitcoin Uses, Users và Their Stories</h4>
<p>Bitcoin là một công nghệ, nhưng nó thể hiện bản chất là tiền. Hãy xem mọi người sử dụng bitcoin và một số cách sử dụng tiền tệ và các giao thức thông qua their stories. Chúng tôi sẽ tái sử dụng những câu chuyện này trong suốt cuốn sách để minh họa việc sử dụng tiền kỹ thuật số trong thực tế và cách chúng được tạo ra bởi các công nghệ khác nhau.</p>
<h4>Getting Started</h4>
<p>Để tham gia vào mạng lưới bitcoin và bắt đầu sử dụng tiền, tất cả người dùng tải xuống một ứng dụng hoặc sử dụng 1 trang web. Vì bitcoin là một chuẩn, có nhiều cách triển khai của bitcoin client software. Cũng có một "reference implementation", cũng được biết tới như Satoshi Client, cái này được quản lý như một dự án mã nguồn mở bởi 1 team phát triển và  có nguồn gốc từ việc thực hiện ban đầu của Satoshi Nakamoto</p>
<ul>Ba hình thức chính của bitcoin client là: 
<li>Full Client : Một full client hoặc "full node" là một client lưu trữ toàn bộ lịch sử giao dịch của bitcoin ( Mọi giao dịch bởi mọi người), quản lý ví người dùng và có thể khởi tạo giao dịch trực tiếp trên mạng bitcoin. Điều này tương tự một máy chủ mail độc lập, xử lý tất cả các khía cạnh của giao thức mà không dựa vào bất kỳ máy chủ nào khác hoặc dịch vụ của bên thứ ba.
</li>
<li>
Light client: Một lightweight client lưu trữ ví người dùng nhưng dựa vào máy chủ bên thứ 3 cho truy cập giao dịch bitcoin và mạng. The light client không lưu trữ một bản sao đầy đủ của tất cả các giao dịch và vì thế phải tin tưởng vào máy chủ của bên thứ 3 cho việc xác thực giao dịch. Điều này tương tự một máy khách email client độc lập kết nối với một mail server cho việc truy cập một mailbox, nó dựa vào bên thứ 3 cho việc tương tác với mạng.
</li>
<li>Web Client: Web-Client được truy cập thông qua trình duyệt web browser và lưu trữ ví người dùng trên một server-được làm chủ bên thứ 3. Nó tương tự như một webmail dựa vào hoàn toàn server bên thứ 3.</li>
</ul>
---------------------------------------------
<h4>Mobile Bitcoin</h4>
<p>Mobile clients cho điện thoại thông minh, chẳng hạn như Android, có thể hoạt động như full clients, light clients hoặc web clients. Một vài mobile client được đồng bộ hoá với web hoặc desktop client, cung cấp ví đa nền tảng trên nhiều thiết bị nhưng chung một nguồn tiền.</p>
----------------------------------------
<p>Một full client sẽ cung cấp mức kiểm soát và độc lập cao nhất cho người sử dụng, nhưng lần lượt đặt gánh nặng của sao lưu và bảo mật cho người dùng. Một khía cạnh khác của phạm vi lựa chọn, một web client là cách dễ nhất để cài đặt và sử dụng, nhưng có sự rủ ro về bảo mật. Nếu một web-wallet service bị tổn hại, như nhiều người đã tưng, người sử dụng có thể mất tất cả tiền của họ. Ngược lại, nếu một người dùng có một full client mà không sao lưu đầy đủ, họ có lẽ mất tiền của họ thông qua một tai nạn máy tính.</p>
<h2>Chương 2: How Bitcoin Works</h2>
<h4> Transactions, Blocks, Mining and the Blockchain</h4>
<p>Hệ thống bitcoin, không giống với hệ thống banking và thanh toán truyền thống, dựa trên sự tin tưởng phi tập trung. Thay vì một cơ quan trung tâm đáng tin cậy, trong bitcoin, sự tin tưởng được thực hiện như là một tài sản nổi bật từ các tương tác của những người tham gia khác nhau trong hệ thống bitcoin. Ở trong chương này chúng ta sẽ xem xét bitcoin từ một mức cao bởi theo dõi một giao dịch thông qua hệ thống bitcoin và xem như nó trở thành " đã tin cậy" và chấp nhận bởi cơ chế đồng thuận phân tán và cuối cùng được ghi lại trên chuỗi blockchain, sổ cái phân tán của tất cả các transaction.</p>
<p>Mỗi ví dụ dưới đây được dựa trên vi dụ thực tế được thực hiện trên mạng bitcoin, mô phỏng tương tác giữa người dùng (joe, Alice, và Bod) bởi gửi tiền từ một ví đến người khác. Trong khi theo dõi một giao dịch thông qua mạng bitcoin network và blockchain, chúng ta sẽ sử dụng blockchain explorer để hình dung từng bước. Một blockchain explorer là một ứng dụng web mà hoạt động như là một công cụ tìm kiếm bitcoin (bitcoin search engine), nó chấp nhận bạn tìm kiếm address, transaction và block và nhìn mối quan hệ và theo dõi giữa chúng</p>
<ul>Popular blockchain explorers bao gồm:
<li>blockchain.info</li>
<li>blockexplorer.com</li>
<li>insight.bitpay.com</li>
<li>blockr.io</li>
</ul>
<p>Mỗi một trong số này có chức năng tìm kiếm có thể lấy một địa chỉ, số băm giao dịch hoặc số khối và tìm dữ liệu tương đương trên mạng bitcoin và blockchain. Với mỗi ví dụ, bạn sẽ cung cấp một URL để đưa bạn đến trực tiếp mục có liên quan để bạn có thể nghiên cứu chi tiết </p>
<h4>Bitcoin Overview</h4>
<p>Ở trong biểu đồ tổng quan bên dưới chúng ta có thể thấy rằng hệ thống bitcoin bao gồm user với ví chứ keys, transactions cái mà được truyền qua mạng và thợ mỏ sản xuất (thông qua cạnh tranh tính toán)  thông qua cơ chế đồng thuận, sổ cái có thẩm quyền của tất cả các giao dịch. Trong chương này, chúng tôi sẽ theo dõi một giao dịch duy nhất khi nó di chuyển qua mạng và kiểm tra tương tác giữa mỗi phần của hệ thống bitcoin, ở mức cao. Chương tiếp theo chúng tôi sẽ đào sâu về công nghệ phía sau wallets, hệ thống mining và buôn bán.</p>




