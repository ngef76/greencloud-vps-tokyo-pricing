# vps nhật bản giá rẻ: Tokyo Softbank từ 48 USD/năm, kèm bảng giá đầy đủ và những điều khoản nhỏ nên đọc trước khi xuống tiền

Cần một VPS đặt tại Nhật với chi phí thấp, lựa chọn đáng tiền nhất hiện tại là gói **Budget KVM VPS 1GB tại Tokyo (line Softbank)** của GreenCloud: khoảng **48 USD/năm, tính ra chưa đến 4 USD/tháng**, cổng mạng 10Gbps, SSD RAID-10, kèm 1 backup/snapshot miễn phí. Đây là mức giá thấp hơn rõ rệt so với VPS Nhật bán theo tháng của các nhà cung cấp tại Việt Nam, vốn có gói rẻ nhất từ khoảng 100.000đ/tháng cho cấu hình tương đương.

Nhưng "giá rẻ" chỉ là một nửa câu chuyện. GreenCloud bán theo kiểu unmanaged, và gói giá rẻ đi kèm vài điều khoản viết nhỏ mà nếu không đọc trước, bạn sẽ bất ngờ sau khi thanh toán: gói giảm giá không được hoàn tiền, mua thêm lưu lượng ở khu vực châu Á–Thái Bình Dương đắt gấp 5 lần Mỹ/Châu Âu, và CPU dùng chung có ngưỡng sử dụng trung bình. Bài viết đi qua đủ cả hai phần: bảng giá đầy đủ, và những điều bạn chỉ thấy trong điều khoản dịch vụ.

> **Chọn nhanh nếu đang vội:** đa số người cần VPS Nhật giá rẻ chỉ để chạy bot, proxy, website nhỏ hoặc thử nghiệm → gói **1GB RAM Tokyo Softbank, 48 USD/năm** là đủ. Cần nhiều RAM hơn mà vẫn rẻ → lên gói 2GB hoặc 4GB. Xem giá và cấu hình mới nhất tại đây: [👉 Xem bảng giá Budget KVM VPS Tokyo của GreenCloud](https://greencloudvps.com/billing/aff.php?aff=6679)

## Bảng giá đầy đủ Budget KVM VPS của GreenCloud

Toàn bộ dòng Budget KVM (Linux) của GreenCloud gồm 5 bậc, tất cả đều cổng 10Gbps, SSD enterprise RAID-10, full root, tặng 1 backup/snapshot, có cloud panel để tự cài lại hệ điều hành và quản lý nguồn. Giá dưới đây là giá theo tháng niêm yết trên trang Budget KVM chính thức:

| Gói | CPU · RAM | Ổ cứng | Lưu lượng (toàn cầu / APAC) | Giá niêm yết | Đặt mua |
| --- | --- | --- | --- | --- | --- |
| SSDKVM-1 | 1 core · 1GB | 15GB SSD | 1.5TB / **750GB** | $6/tháng | [ Đặt gói SSDKVM-1](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-2 | 1 core · 2GB | 15GB SSD | 2TB / **1TB** | $10/tháng | [ Đặt gói SSDKVM-2](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-3 | 2 core · 4GB | 30GB SSD | 4TB / **2TB** | $20/tháng | [ Đặt gói SSDKVM-3](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-4 | 4 core · 8GB | 60GB SSD | 8TB / **4TB** | $40/tháng | [ Đặt gói SSDKVM-4](https://greencloudvps.com/billing/aff.php?aff=6679) |
| SSDKVM-5 | 8 core · 16GB | 120GB SSD | 12TB / **6TB** | $80/tháng | [ Đặt gói SSDKVM-5](https://greencloudvps.com/billing/aff.php?aff=6679) |

Cột lưu lượng là điểm đầu tiên mà nhiều bài giới thiệu bỏ qua: **vị trí Nhật Bản thuộc khu vực APAC, nên lưu lượng thực tế bạn nhận được bằng một nửa (hoặc thấp hơn) con số quảng cáo trên bảng giá chung**. Gói rẻ nhất không phải 1.5TB mà là 750GB/tháng. Với người dùng Việt kết nối tới server Nhật, 750GB đã đủ cho website vừa và nhỏ hoặc bot; nhưng nếu định làm máy tải file hoặc stream, hãy tính lại trước.

Về cách tính giá, cần nói rõ để bạn không nhầm: bảng trên là giá niêm yết theo tháng. Với vị trí Tokyo, các gói Budget KVM thường chỉ bán theo năm, và các bài đánh giá cùng công cụ theo dõi giá độc lập gần đây đều ghi nhận gói nhỏ nhất 1GB/15GB SSD/750GB tại Tokyo Softbank ở mức **48 USD/năm (tương đương 4 USD/tháng)** — rẻ hơn khoảng một phần ba so với quy đổi từ giá tháng. Con số cuối cùng hiện ra ở trang thanh toán mới là chuẩn; nếu trang bán Tokyo hiển thị khác bảng này, hãy tin trang bán. Line Softbank cũng là lý do chính để chọn Tokyo: đây là một trong các nhà mạng Tier-1 mà GreenCloud kết nối trực tiếp tại Nhật, đi kèm cổng 10Gbps.

## Dòng CN Premium Optimized Tokyo: cấu hình mạnh hơn, nhưng hiện không còn hàng

Nếu mục đích của bạn là tối ưu đường truyền về Trung Quốc đại lục (CN2 GIA / CU Premium / CMIN2), GreenCloud có riêng dòng CN Premium Optimized tại Tokyo, dùng CPU EPYC Milan, NVMe RAID-10, backup hàng ngày và chỉ hỗ trợ Linux:

| Gói | RAM | Ổ cứng | CPU | Lưu lượng | Cổng | Đặt mua |
| --- | --- | --- | --- | --- | --- | --- |
| Mini | 2GB | 20GB NVMe | 1 core | 500GB | 500Mbps | [ Kiểm tra gói Mini Tokyo](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Plan 1 | 4GB | 40GB NVMe | 2 core | 1TB | 1Gbps | [ Kiểm tra gói Plan 1 Tokyo](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Plan 2 | 8GB | 80GB NVMe | 4 core | 2TB | 1.5Gbps | [ Kiểm tra gói Plan 2 Tokyo](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Plan 3 | 16GB | 160GB NVMe | 8 core | 4TB | 2Gbps | [ Kiểm tra gói Plan 3 Tokyo](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Plan 4 | 32GB | 320GB NVMe | 8 core | 8TB | 3Gbps | [ Kiểm tra gói Plan 4 Tokyo](https://greencloudvps.com/billing/aff.php?aff=6679) |

Hai điều cần biết trước khi bấm vào. Một, tại thời điểm kiểm tra, **toàn bộ 10 SKU Tokyo và Singapore của dòng CN Premium đều hiển thị "0 Available"** — hết hàng, và các gói dạng này thường chỉ mở bán theo đợt; các link trong bảng dẫn tới trang mua để bạn tự kiểm tra tình trạng hàng mới nhất. Hai, dòng ghi chú ngay trên trang mua viết rõ: **"No refund/Money back on this plan"** — các gói CN Premium không áp dụng chính sách hoàn tiền 7 ngày, và trang mua không niêm yết công khai giá mặc định.

Với người dùng Việt thuần túy cần IP Nhật (proxy, truy cập dịch vụ theo khu vực, bot), line Softbank của Budget KVM đã đủ và rẻ hơn đáng kể. CN Premium chỉ thực sự đáng theo dõi khi bạn cần route tối ưu về Trung Quốc.

## So với VPS Nhật bán theo tháng của nhà cung cấp Việt Nam

Để có mốc so sánh cụ thể, bảng dưới đây đối chiếu với hai gói VPS Nhật rẻ nhất của nhà cung cấp Cloud Cheap (thông tin lấy từ bảng giá công khai của họ, cập nhật tháng 10 vừa qua):

| Tiêu chí | Cloud Cheap Mini | Cloud Cheap Global | GreenCloud Tokyo (Budget KVM) |
| --- | --- | --- | --- |
| Cấu hình thấp nhất | 1 core · 1GB · 12GB SSD | 2 vCore · 4GB · 30GB SSD | 1 core · 1GB · 15GB SSD |
| Giá khởi điểm | 100.000đ/tháng | 250.000đ/tháng | $6/tháng niêm yết; Tokyo thường tính theo năm, khoảng $48/năm |
| Băng thông cổng | Download 100 Mbps, upload 10 Mbps | Không công bố | 10Gbps |
| Lưu lượng | 1TB/tháng | 2TB/tháng trở lên | 750GB/tháng (APAC) |
| Thanh toán | Chỉ theo tháng | Tháng → năm | Năm (Tokyo) |

*Lưu ý về cách đọc bảng: hai cột Cloud Cheap tính theo tháng, cột GreenCloud Tokyo chủ yếu tính theo năm — khi quy đổi về cùng một chu kỳ, gói Tokyo tương đương khoảng 4 USD/tháng (khoảng 100.000đ với tỷ giá hiện hành) cho cấu hình nhỏ nhất.*

Ba khác biệt quyết định. Thứ nhất là **cổng mạng**: 100 Mbps download/10 Mbps upload với 1TB lưu lượng nghĩa là nếu ứng dụng của bạn tải nhiều dữ liệu, đường ống này sẽ là nút cổ chai; GreenCloud Tokyo cho 10Gbps. Thứ hai là **tổng chi phí năm**: 100.000đ/tháng của Cloud Cheap Mini cộng lại khoảng 1,2 triệu đồng/năm cho 1GB RAM, trong khi gói tương đương của GreenCloud ở mức 48 USD/năm. Thứ ba, và cũng là điểm Cloud Cheap thắng: **họ bán theo tháng, nhận thanh toán trong nước, hỗ trợ tiếng Việt** — nếu bạn chỉ cần server dùng thử 1–2 tháng hoặc ngại thanh toán quốc tế, cách này đỡ rắc rối hơn. Còn nếu dùng dài hạn, chênh lệch giá khiến phía GreenCloud gần như không có đối trọng ở cấu hình 1–4GB.

## Những điều khoản nhỏ quyết định "chi phí thật" — phần không ai nói rõ

Bảng giá chỉ là khởi đầu. Bốn mục dưới đây lấy trực tiếp từ điều khoản dịch vụ và trang sản phẩm của GreenCloud, và chúng ảnh hưởng đến ví của bạn nhiều hơn bất kỳ con số benchmark nào.

**1. Hoàn tiền chỉ áp dụng cho VPS đầu tiên của khách mới, trong 7 ngày.** Nếu không hài lòng, bạn có thể hủy và yêu cầu hoàn tiền trong 7 ngày đầu — nhưng chỉ dành cho VPS đầu tiên của khách hàng mới, và **các gói giảm giá đặc biệt bị loại trừ**. Thanh toán bằng tiền điện tử thì không hoàn tiền trong mọi trường hợp. Với các gói Budget KVM Sale (dạng listing khuyến mãi theo khu vực), trang mua ghi thẳng "No refund/Money back on this plan". Kết luận thực tế: trước khi thanh toán gói Tokyo, đọc dòng ghi chú ngay cạnh nút mua — nếu có chữ no refund, coi như tiền đã chốt.

> Nếu bạn vẫn còn phân vân giữa các bậc cấu hình, mở bảng giá, so sánh lưu lượng APAC với nhu cầu thực tế, rồi mới quyết: [👉 Xem lại toàn bộ gói và giá của GreenCloud](https://greencloudvps.com/billing/aff.php?aff=6679)

**2. Mua thêm lưu lượng ở châu Á đắt gấp 5 lần Mỹ.** Cần thêm băng thông? Theo điều khoản dịch vụ, KVM VPS ở Mỹ/Châu Âu tính 3 USD/TB/tháng, còn **khu vực châu Á–Thái Bình Dương là 15 USD/TB/tháng**. Trên gói 48 USD/năm, mua thêm 1TB ở Tokyo tốn gần bằng 3 tháng tiền server. Đây là lý do nên chọn bậc gói cao hơn ngay từ đầu thay vì mua rẻ rồi mua thêm sau.

**3. CPU dùng chung có ngưỡng, không phải "xài thả".** Các gói Budget KVM chạy trên node chia sẻ, và điều khoản quy định rõ: mức sử dụng trung bình không vượt **30% CPU**, chỉ được đẩy lên 100% trong các đợt burst tối đa 10 phút mỗi 24 giờ. Load liên tục vượt ngưỡng có thể bị giảm tài nguyên, restart hoặc tạm khóa. Các bài đánh giá độc lập (ví dụ bài review chuyên về VPS Nhật của GreenCloud) cũng nhận xét dải giá rẻ này có dấu hiệu oversell khá rõ trên điểm CPU — đúng thực tế, nhưng đó là cái giá của mức 4 USD/tháng. Nếu workload của bạn cần CPU chạy liên tục (render, xử lý dữ liệu nặng), hãy nhìn sang dòng EPYC NVMe VPS dùng nhân vật lý riêng — bên thứ ba ghi nhận mức từ 216 USD/năm cho 4 nhân EPYC Milan thật, nhưng hãy xác nhận giá hiện hành trên trang bán trước khi quyết.

**4. Đổi vị trí, đổi line và đổi IP đều tốn phí.** Gói khuyến mãi đổi khu vực mất 10 USD/lần, và ở khu vực APAC chỉ được đổi trong cùng quốc gia. Riêng Tokyo, đổi giữa hai line SoftBank và IIJ mất 10 USD, IP sẽ thay đổi và bạn phải tự backup. Đổi IP mất 2 USD/lần (theo điều khoản; không đảm bảo truy cập được các dịch vụ như Netflix hay Etsy). Chi tiết này quan trọng với ai mua VPS Nhật vì line cụ thể: hãy chắc chắn đúng line mình cần ngay từ lần đặt đầu.

## Vận hành thực tế: giao server, thanh toán và những gì bạn phải tự làm

Sau khi thanh toán, server thường được cấp trong **15 phút**, có khi kéo dài tới 2 giờ; đơn có thông tin thanh toán không khớp có thể bị hệ thống chống gian lận giữ lại thêm. Thanh toán chấp nhận PayPal, thẻ tín dụng/ghi nợ, Alipay, UnionPay, tiền điện tử (BTC/ETH/BNB/USDT) và chuyển khoản ngân hàng Mỹ/Anh/EU — riêng thẻ và PayPal, khách mới cần xác minh một lần.

Quản lý qua Cloud Control Panel (các gói sale mới dùng Virtfusion): cài lại OS, bật/tắt nguồn, quản lý snapshot đều tự thao tác được. Bạn nhận full root qua SSH. Điểm cần nói thẳng: **GreenCloud là dịch vụ unmanaged** — họ chỉ chịu trách nhiệm phần cứng và uptime (tự công bố 99.99% cho mạng và điện), mọi vấn đề hệ điều hành, cấu hình phần mềm, ứng dụng đều do bạn. Nếu bạn cần ai đó "sửa hộ" khi server lỗi, đây không phải nơi phù hợp.

Về đánh giá từ người dùng, bức tranh chia đôi. Phía tích cực: trên LowEndTalk, GreenCloud được gắn nhãn "#1 Top Provider" và "#1 Most Stable Provider" (do chính trang sản phẩm trích dẫn), và các đánh giá dài hạn từ cộng đồng ghi nhận uptime ổn định qua nhiều năm với giá cạnh tranh; một số người dùng cũ so sánh cho rằng cùng cấu hình thì rẻ hơn Contabo. Phía tiêu cực: Trustpilot có đánh giá phản ánh server bị tạm khóa sau khi được yêu cầu đổi phương thức thanh toán sang crypto và không được hoàn tiền, cùng phản ánh về IP bị đưa vào blacklist. Không có bức tranh một màu — điểm chung của các phản hồi tiêu cực là xoay quanh chính sách thanh toán và hoàn tiền, vốn đã khắt khe như phần trên. Đặt hàng bằng phương thức quen thuộc (thẻ, PayPal), đọc kỹ ghi chú refund ngay tại bước checkout, và bạn đã loại bỏ được phần lớn rủi ro này.

## Ai không nên mua gói giá rẻ của GreenCloud

Ba trường hợp nên dừng lại trước khi thanh toán. Bạn cần **Windows Server tại Nhật**: dòng Budget Windows VPS của GreenCloud (từ 8 USD/tháng) chỉ liệt kê vị trí Mỹ; gói Tokyo Budget KVM chỉ có Linux, và dòng CN Premium Tokyo cũng vậy. Bạn cần **hỗ trợ kỹ thuật về phần mềm**: unmanaged nghĩa là tự lo từ A đến Z. Bạn muốn **trả theo tháng, hủy bất cứ lúc nào**: Tokyo bán theo năm, trong khi các nhà cung cấp Việt bán VPS Nhật theo tháng — nếu đây là lần đầu bạn thử server Nhật, trả theo tháng 1–2 tháng để test rồi mới mua năm là cách ít rủi ro hơn.

## Chọn gói nào, theo nhu cầu thực tế

- **Bot, webhook, proxy cá nhân, website nhỏ:** SSDKVM-1 Tokyo Softbank, 48 USD/năm, 750GB lưu lượng. Đủ dùng cho phần lớn nhu cầu "VPS Nhật giá rẻ".
- **Database, app vừa, cần nhiều RAM hơn nhưng vẫn tiết kiệm:** SSDKVM-3 (2 core/4GB/2TB APAC) — bước nhảy cấu hình lớn nhất trên mỗi đồng tiền trong bảng giá.
- **CPU chạy liên tục, cần hiệu năng thật:** bỏ qua dòng Budget, nhìn sang EPYC NVMe VPS dùng nhân vật lý riêng.
- **Cần test ngắn hạn, thanh toán trong nước:** nhà cung cấp nội địa bán theo tháng phù hợp hơn cho giai đoạn thử nghiệm, dù tổng chi phí năm sẽ cao hơn.

Trước khi bấm mua, còn lại hai việc nên làm: kiểm tra dòng ghi chú hoàn tiền ngay cạnh nút đặt hàng của đúng gói Tokyo bạn chọn, và chắc chắn 750GB–6TB lưu lượng APAC là đủ cho ứng dụng của bạn (mua thêm lưu lượng ở châu Á tốn 15 USD/TB). Nếu cả hai đều ổn, gói 1GB Tokyo Softbank với mức [👉 48 USD/năm trên GreenCloud](https://greencloudvps.com/billing/aff.php?aff=6679) là điểm khởi đầu hợp lý nhất cho nhu cầu VPS Nhật giá rẻ hiện nay.
