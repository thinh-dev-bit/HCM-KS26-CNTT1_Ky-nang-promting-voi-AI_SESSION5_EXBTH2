# Chuỗi Prompt Viết Bài PR Sản Phẩm Công Nghệ

## YÊU CẦU NHẬP DỮ LIỆU ĐẦU VÀO (Bắt buộc chuẩn bị cho Trạm 1)

Trước khi khởi chạy chuỗi Prompt, người dùng cần thu thập và điền đầy đủ **6 nhóm thông tin sản phẩm** dưới đây để cung cấp làm nguyên liệu phân tích cho **Trạm 1**:

1. **Tên sản phẩm & Đơn vị phát triển:** *(Tên chính thức của giải pháp AI Chatbot và thương hiệu công ty sở hữu).*
2. **Mô tả tổng quan & Công nghệ lõi:** *(Giải pháp hoạt động như thế nào, ứng dụng công nghệ gì như LLM, RAG, NLP, đa kênh...).*
3. **Danh sách tính năng cốt lõi (3–5 tính năng):** *(Các chức năng nổi bật nhất phục vụ bán hàng, chăm sóc khách hàng, tự động hóa).*
4. **Lĩnh vực & Quy mô doanh nghiệp mục tiêu:** *(Ngành nghề trọng tâm như E-commerce, Tài chính, Bán lẻ... và quy mô SME hay Enterprise).*
5. **Lợi thế cạnh tranh độc quyền (USP):** *(Điểm khác biệt vượt trội so với đối thủ về tốc độ, độ chính xác, chi phí hoặc thời gian triển khai).*
6. **Hiện trạng / Vấn đề thực tế của khách hàng (nếu có):** *(Những khó khăn phổ biến mà doanh nghiệp mục tiêu đang gặp phải trước khi dùng sản phẩm).*

---

## TRẠM 1: Prompt 1 — Nghiên cứu Khách hàng mục tiêu & Nỗi đau (Pain Points)

```
# VAI TRÒ (Context)
Bạn là một Chuyên gia Nghiên cứu Thị trường & Chiến lược Sản phẩm B2B (B2B Product Marketing Strategist) có hơn 10 năm kinh nghiệm phân tích hành vi khách hàng doanh nghiệp trong lĩnh vực phần mềm SaaS và trí tuệ nhân tạo (AI).

# NHIỆM VỤ (Request)
Tiếp nhận và phân tích toàn bộ dữ liệu sản phẩm AI Chatbot doanh nghiệp do người dùng cung cấp để xác định chính xác chân dung khách hàng mục tiêu (Target Persona) và xây dựng danh sách 5 nỗi đau (Pain Points) cốt lõi nhất mà sản phẩm giải quyết triệt để, làm nền tảng dữ liệu đầu vào cho Trạm 2.

# RÀNG BUỘC KỸ THUẬT BẮT BUỘC (Explanation)
1. **Kiểm tra dữ liệu đầu vào (Input Gate):** Trước khi phân tích, hãy rà soát các trường thông tin trong mục DỮ LIỆU ĐẦU VÀO. Nếu người dùng chưa nhập hoặc để trống các thông tin cốt lõi (tên sản phẩm, tính năng, lĩnh vực, USP), tuyệt đối không tự suy diễn; hãy dừng lại và liệt kê yêu cầu người dùng cung cấp bổ sung đầy đủ trước khi thực hiện.
2. Tuyệt đối không viết nội dung bài PR hoặc dàn ý bài viết ở trạm này.
3. Mỗi nỗi đau phải được gắn mã định danh duy nhất từ `PP-01` đến `PP-05` để phục vụ cơ chế truyền dữ liệu (Data Handoff) sang Trạm 2.
4. Mọi nỗi đau nêu ra phải gắn liền với số liệu/hệ quả vận hành thực tế của doanh nghiệp (chi phí nhân sự, thời gian phản hồi, tỷ lệ rớt đơn) và ánh xạ trực tiếp với một tính năng cụ thể của AI Chatbot.
5. Thực hiện chốt chặn kiểm định (Validation Gate): Tự rà soát đảm bảo đủ 5 mã `PP-01` đến `PP-05` và không trùng lặp ý trước khi xuất kết quả.

## DỮ LIỆU ĐẦU VÀO (Yêu cầu người dùng nhập đầy đủ các dữ liệu cần thiết bên dưới)
- **Tên sản phẩm AI Chatbot & Đơn vị phát triển:** [Nhập tên sản phẩm & công ty, VD: NovaBot Enterprise AI - Phát triển bởi NovaTech]
- **Mô tả tổng quan & Nền tảng công nghệ:** [Mô tả ngắn gọn công nghệ lõi, VD: Trợ lý ảo AI ứng dụng LLM kết hợp công nghệ RAG truy xuất dữ liệu nội bộ theo thời gian thực]
- **Tính năng cốt lõi (3–5 tính năng):** [Liệt kê chi tiết, VD: Hiểu ngữ cảnh hội thoại đa lượt, tích hợp API với CRM/ERP, tự động chốt đơn & đặt lịch 24/7, hỗ trợ đa ngôn ngữ]
- **Lĩnh vực & Quy mô doanh nghiệp hướng tới:** [Nhập ngành nghề & quy mô, VD: Doanh nghiệp SME và Enterprise ngành Thương mại điện tử, Tài chính - Ngân hàng, Bán lẻ chuỗi]
- **Lợi thế cạnh tranh độc quyền (USP):** [Nhập điểm khác biệt đo lường được, VD: Giảm 70% chi phí CSKH, độ chính xác câu trả lời 98%, triển khai hoàn thiện trong 48 giờ]
- **Hiện trạng / Vấn đề thực tế khách hàng đang gặp phải:** [Nhập bối cảnh thực tế, VD: Khách rời bỏ giỏ hàng do chờ phản hồi lâu ngoài giờ hành chính, nhân viên quá tải tin nhắn lặp lại]

# QUY TRÌNH LẬP LUẬN (Action)
Hãy thực hiện tuần tự theo 3 bước sau:
- **Bước 1: Xác định chân dung người ra quyết định (Decision Maker & User Persona)** — Phân tích chức danh (CEO, CMO, Trưởng phòng CSKH), quy mô doanh nghiệp, mục tiêu KPI họ đang bị áp lực và rào cản khi ứng dụng công nghệ mới.
- **Bước 2: Khai thác và phân loại 5 nỗi đau (Pain Points)** — Rà soát toàn bộ quy trình chăm sóc khách hàng và bán hàng truyền thống dựa trên dữ liệu đầu vào để chỉ ra 5 điểm nghẽn nghiêm trọng nhất, gán mã `PP-01` đến `PP-05`.
- **Bước 3: Ánh xạ giải pháp & Giá trị chuyển đổi (Pain-to-Gain Mapping)** — Đối chiếu từng mã `PP-xx` với tính năng tương ứng của AI Chatbot và lượng hóa lợi ích mang lại.

# GIỌNG ĐIỆU (Tone)
Chuyên nghiệp, sắc bén, phân tích dựa trên dữ liệu thực tiễn kinh doanh B2B, khách quan và đáng tin cậy.

# ĐỊNH DẠNG ĐẦU RA (Extras)
1. Trình bày kết quả phân tích gồm 2 phần rõ ràng:
   - **Phần 1: Chân dung khách hàng mục tiêu (B2B Persona)** (dạng danh sách gạch đầu dòng có cấu trúc).
   - **Phần 2: Bảng tổng hợp 5 Pain Points & Giải pháp ánh xạ** (Markdown Table gồm 5 cột: `Mã PP`, `Nỗi đau vận hành`, `Hệ quả kinh doanh`, `Tính năng AI Chatbot giải quyết`, `Giá trị cam kết`).
2. **Yêu cầu xuất file:** Sau khi hoàn tất phân tích, hãy xuất toàn bộ nội dung kết quả trên ra file Markdown với tên tệp **`tram1_khach_hang_pain_points.md`**.
```

---

## TRẠM 2: Prompt 2 — Thiết lập Dàn ý Bài viết PR chuẩn SEO (Outline)

````
# VAI TRÒ (Context)
Bạn là một Giám đốc Nội dung & Chuyên gia Chiến lược SEO (Content Director & SEO Strategist) chuyên thiết kế cấu trúc bài PR công nghệ B2B có tỷ lệ chuyển đổi cao trên các báo chí kinh doanh và trang tin công nghệ uy tín.

# NHIỆM VỤ (Request)
Dựa trên dữ liệu chân dung khách hàng và danh sách Pain Points từ Trạm 1 cùng các dữ liệu khảo sát thực tiễn và chính sách ưu đãi được cung cấp, hãy thiết kế một bản dàn ý chi tiết (Outline) chuẩn SEO cho bài viết PR giới thiệu giải pháp AI Chatbot doanh nghiệp với tổng độ dài mục tiêu từ **1.000 đến 1.500 từ**.

# RÀNG BUỘC KỸ THUẬT BẮT BUỘC (Explanation)
1. Bắt buộc sử dụng 100% dữ liệu đầu vào từ Trạm 1 và các số liệu khảo sát/ưu đãi được cung cấp; không tự ý bịa đặt thêm tính năng hay con số ngoài phạm vi dữ liệu.
2. Tuyệt đối không viết thành bài văn hoàn chỉnh ở bước này; chỉ xây dựng khung dàn ý chi tiết kèm chỉ dẫn viết cho Trạm 3.
3. Dàn ý phải đảm bảo đầy đủ các thành phần cấu trúc PR chuẩn SEO: **Tiêu đề chính (H1/Headline)**, **Đoạn mở đầu (Lead)**, **Các đề mục thân bài phân cấp (H2, H3)** (bắt buộc có phân mục đối chiếu số liệu khảo sát AI thực tiễn), và **Khối ưu đãi hợp tác kèm Lời kêu gọi hành động (CTA)**.
4. Thực hiện chốt chặn kiểm định (Validation Gate): Cộng tổng định mức số từ của tất cả các phần phải nằm chính xác trong khoảng **1.100 – 1.400 từ** (vùng an toàn của 1.000 – 1.500 từ) và toàn bộ mã `PP-01` đến `PP-05` đều được phân bổ vào các đề mục.

## DỮ LIỆU ĐẦU VÀO
- **Kết quả từ Trạm 1 (Bắt buộc dán toàn bộ nội dung file `tram1_khach_hang_pain_points.md` vào đây):**
  ```markdown
  [Dán toàn bộ nội dung Phần 1 và Bảng Phần 2 từ Trạm 1]
  ```
- **Số liệu khảo sát AI thực tiễn (Benchmark / Dữ liệu đối chiếu):** [VD: Khảo sát 200 doanh nghiệp B2B cho thấy thời gian phản hồi giảm từ 15 phút xuống 3 giây, tỷ lệ giữ chân khách hàng tăng 42% và tiết kiệm 65% chi phí nhân sự CSKH so với vận hành thủ công]
- **Chính sách ưu đãi khi hợp tác (Partnership Offers):** [VD: Tặng gói tư vấn & tích hợp CRM miễn phí trị giá 20.000.000 VNĐ, chiết khấu 20% phí bản quyền năm đầu cho 30 doanh nghiệp đăng ký hợp tác sớm trong tháng]
- **Từ khóa SEO chính (Primary Keyword):** [VD: giải pháp AI Chatbot cho doanh nghiệp]
- **Từ khóa SEO phụ (Secondary Keywords):** [VD: chatbot AI chăm sóc khách hàng, tự động hóa CSKH, tối ưu chi phí vận hành]
- **Mục tiêu chuyển đổi (CTA Target):** [VD: Đăng ký dùng thử miễn phí 14 ngày / Đặt lịch demo 1-1]

# QUY TRÌNH LẬP LUẬN (Action)
Thực hiện tuần tự qua 4 bước:
- **Bước 1: Đề xuất Tiêu đề (Headline - H1) & Đoạn mở đầu (Lead)** — Tạo 3 phương án tiêu đề chứa từ khóa chính (chọn 1 phương án tối ưu nhất) và phác thảo ý chính cho đoạn Lead (120–150 từ) đánh trúng `PP-01` và `PP-02`.
- **Bước 2: Cấu trúc hóa Thân bài theo các thẻ H2, H3** — Chia thân bài thành 4 thẻ `H2` lớn theo mạch logic chặt chẽ:
  + `H2.1`: Thực trạng thị trường & Các điểm nghẽn vận hành của doanh nghiệp.
  + `H2.2`: Giải pháp công nghệ cốt lõi của AI Chatbot (giải quyết trực diện các mã `PP-xx`).
  + `H2.3`: **Bức tranh hiệu quả từ số liệu khảo sát AI thực tiễn** — Thiết kế các thẻ `H3` chỉ rõ cách trình bày bảng/luận điểm so sánh đối chiếu giữa **mô hình CSKH truyền thống (Trước khi ứng dụng)** và **hiệu suất thực tế sau khi triển khai AI Chatbot (Sau khi ứng dụng)** dựa trên dữ liệu khảo sát đầu vào.
  + `H2.4`: Lộ trình triển khai nhanh chóng & Cam kết bảo mật dữ liệu doanh nghiệp.
- **Bước 3: Gắn nhãn Data Handoff & Phân bổ định mức** — Tại mỗi mục `H2/H3`, ghi rõ: *(a) Mã `PP-xx` hoặc dữ liệu khảo sát được sử dụng*, *(b) Từ khóa SEO cần chèn*, *(c) Luận điểm chính cần triển khai*, và *(d) Định mức số từ*.
- **Bước 4: Thiết kế khối Ưu đãi hợp tác & Lời kêu gọi hành động (CTA)** — Thiết kế phần kết bài (120–150 từ) tóm lược giá trị chiến lược, trình bày nổi bật **các chính sách ưu đãi độc quyền dành cho đối tác triển khai sớm** và gắn kèm nút/thông điệp CTA rõ ràng.

# GIỌNG ĐIỆU (Tone)
Chuyên nghiệp, mạch lạc, có tính định hướng biên tập cao, giữ vững sắc thái tin cậy và khách quan của một ấn phẩm báo chí công nghệ.

# ĐỊNH DẠNG ĐẦU RA (Extras)
1. Trình bày dàn ý dưới dạng cây cấu trúc Markdown phân cấp rõ ràng (`# H1`, `## H2`, `### H3`), kèm bảng tổng hợp phân bổ số từ và từ khóa SEO ở cuối để kiểm soát chất lượng trước khi chuyển sang Trạm 3.
2. **Yêu cầu xuất file:** Sau khi hoàn tất dàn ý, hãy xuất toàn bộ nội dung kết quả trên ra file Markdown với tên tệp **`tram2_dan_y_bai_pr_seo.md`**.
````

---

## TRẠM 3: Prompt 3 — Triển khai Viết bài PR Chi tiết & Tối ưu SEO

````
# VAI TRÒ (Context)
Bạn là một Cây bút PR Công nghệ Cấp cao & Chuyên gia Tối ưu Nội dung SEO (Senior Tech PR Copywriter & SEO Content Specialist) chuyên chấp bút các bài viết phân tích chuyên sâu trên các tạp chí kinh tế - công nghệ hàng đầu (như Forbes Vietnam, CafeF, VnExpress Số hóa).

# NHIỆM VỤ (Request)
Dựa trên bản dàn ý chi tiết đã được phê duyệt ở Trạm 2, hãy triển khai viết hoàn chỉnh bài viết PR giới thiệu giải pháp AI Chatbot cho doanh nghiệp với độ dài từ **1.000 đến 1.500 từ**, đảm bảo chiều sâu phân tích, thuyết phục khách hàng B2B và tối ưu hóa chuẩn SEO.

# RÀNG BUỘC KỸ THUẬT BẮT BUỘC (Explanation)
1. **Tuân thủ tuyệt đối Dàn ý Trạm 2:** Triển khai đúng thứ tự các thẻ `H1`, `H2`, `H3`, giải quyết đủ các mã `PP-01` đến `PP-05` và bám sát định mức số từ từng phần để tổng bài đạt **1.000 – 1.500 từ** (tuyệt đối không viết tóm tắt sơ sài dưới 1.000 từ).
2. **Cấu trúc chuẩn SEO bắt buộc:**
   - Có **Tiêu đề thu hút (H1)** chứa từ khóa chính.
   - Có **Đoạn mở đầu (Lead)** in đậm/nổi bật dẫn dắt trực diện từ nỗi đau doanh nghiệp.
   - Các **Tiêu đề con (`## H2`, `### H3`)** rõ ràng, phân bổ từ khóa chính và từ khóa phụ tự nhiên (mật độ 1% – 1.5%, không nhồi nhét).
   - Có **Khối ưu đãi hợp tác & Lời kêu gọi hành động (CTA)** thuyết phục ở cuối bài.
3. **Tính nhất quán giọng điệu:** Duy trì xuyên suốt một giọng văn **chuyên nghiệp, khách quan, am hiểu công nghệ và đáng tin cậy** từ câu mở đầu đến dòng CTA cuối cùng; không chuyển sang văn phong quảng cáo phóng đại hay suồng sã.
4. **Quy tắc xử lý khi bị ngắt quãng (Max Output Tokens):** Nếu bài viết dài chạm giới hạn xuất ký tự trong một lượt và bị dừng giữa chừng, khi nhận được lệnh nối tiếp kèm 3–5 từ cuối, bạn phải viết tiếp nối ngay lập tức sau cụm từ đó, giữ nguyên cấu trúc đề mục `H2/H3` đang dang dở và không lặp lại nội dung đã viết.

## DỮ LIỆU ĐẦU VÀO
- **Dàn ý chi tiết từ Trạm 2 (Bắt buộc dán toàn bộ nội dung file `tram2_dan_y_bai_pr_seo.md` vào đây):**
  ```markdown
  [Dán toàn bộ nội dung dàn ý từ Trạm 2]
  ```

# QUY TRÌNH LẬP LUẬN (Action)
Thực hiện tuần tự từng phần theo đúng mạch bài PR:
- **Bước 1: Viết Tiêu đề (H1) & Đoạn mở đầu (Lead)** — Đặt vấn đề bằng bức tranh áp lực vận hành của doanh nghiệp, chạm đúng nỗi đau cốt lõi và hé lộ giải pháp AI Chatbot như một bước ngoặt tất yếu.
- **Bước 2: Triển khai chi tiết từng phân mục Thân bài (`H2` và `H3`)** — Với mỗi mục, trình bày theo công thức: *Nêu thực trạng/nỗi đau $\rightarrow$ Phân tích cơ chế công nghệ của AI Chatbot $\rightarrow$ Dẫn chứng lợi ích định lượng*. Sử dụng bullet points và in đậm các cụm từ khóa quan trọng để tăng khả năng đọc lướt (scannability).
- **Bước 3: Viết Kết bài, Ưu đãi hợp tác & Lời kêu gọi hành động (CTA)** — Tóm lược giá trị chiến lược dài hạn, làm nổi bật gói ưu đãi dành cho đối tác sớm và đưa ra lời mời trải nghiệm sản phẩm rõ ràng, chuyên nghiệp.
- **Bước 4: Rà soát SEO & Độ dài (Self-Check)** — Kiểm tra sự hiện diện của toàn bộ từ khóa chính/phụ và đảm bảo tổng dung lượng đạt chuẩn 1.000 – 1.500 từ.

# GIỌNG ĐIỆU (Tone)
Chuyên nghiệp, tin cậy, chuẩn mực báo chí kinh doanh – công nghệ; sắc sảo, thuyết phục bằng lập luận logic và giá trị thực tiễn.

# ĐỊNH DẠNG ĐẦU RA (Extras)
1. Xuất toàn bộ bài viết PR hoàn chỉnh định dạng chuẩn Markdown (`#` cho Headline, đoạn Lead dẫn nhập, `##` cho H2, `###` cho H3, và khối trích dẫn/nổi bật cho phần Ưu đãi & CTA cuối bài).
2. **Yêu cầu xuất file:** Sau khi hoàn tất bài viết PR, hãy xuất toàn bộ nội dung bài viết ra file Markdown với tên tệp **`tram3_bai_viet_pr_hoan_chinh.md`**.
````

---

## XỬ LÝ ĐỨT GÃY NGỮ CẢNH KHI VIẾT BÀI DÀI (MAX OUTPUT TOKENS)

Khi triển khai **Trạm 3** (bài viết 1.000 – 1.500 từ), nếu AI chạm ngưỡng giới hạn xuất chữ trong một lượt (`Max Output Tokens`) và bị dừng giữa câu, hãy áp dụng quy tắc điều khiển sau để đoạn văn viết tiếp nối khớp hoàn hảo với câu trước đó:

### 1. Nguyên tắc điều khiển bắt buộc
* **Không dùng lệnh chung chung:** Tuyệt đối không gõ *"Tiếp tục"*, *"Viết tiếp đi"* hoặc *"Continue"* vì AI dễ bị mất định hướng cấu trúc `H2/H3`, lặp lại ý hoặc đổi giọng điệu.
* **Kỹ thuật Continue Prompting (Mớm câu nối tiếp):** Sao chép chính xác **3–5 từ cuối cùng** ngay trước điểm AI bị ngắt để làm điểm neo ngữ pháp và mạch văn.
* **Kỹ thuật Context Anchoring (Neo bối cảnh):** Nhắc lại ngắn gọn vai trò, giọng điệu (**chuyên nghiệp, tin cậy**) và yêu cầu xuất file Markdown ở cuối cùng để chống trôi dạt ngữ cảnh (*Context Drift*).

### 2. Mẫu câu lệnh điều khiển tiếp tục chính xác (Copy-Paste Template)

```
[NEO BỐI CẢNH]: Tiếp tục hoàn thiện bài viết PR giải pháp AI Chatbot doanh nghiệp theo đúng Dàn ý Trạm 2, giữ nguyên giọng điệu chuyên nghiệp, tin cậy, chuẩn báo chí công nghệ và cấu trúc thẻ H2/H3 hiện tại.

[LỆNH NỐI TIẾP]: Bạn đã dừng lại ở cụm từ: "**[Dán chính xác 3–5 từ cuối cùng ngay trước điểm ngắt]**". Hãy viết tiếp nối liền mạch ngay sau cụm từ này (không lặp lại phần đã viết, không viết lời dẫn mở đầu) cho đến hết phần Ưu đãi & CTA cuối bài, sau đó xuất toàn bộ bài viết hoàn chỉnh ra file Markdown tên **`tram3_bai_viet_pr_hoan_chinh.md`**.
```

### 3. Ví dụ minh họa thực tế
* **Tình huống AI bị ngắt cụt giữa câu tại phân mục thân bài:**
  > *"...Nhờ khả năng đồng bộ dữ liệu thời gian thực với hệ thống CRM, doanh nghiệp không chỉ rút ngắn thời gian phản hồi xuống dưới 3 giây mà còn"* $\leftarrow$ **(Bị ngắt tại đây)**
* **Câu lệnh người dùng gửi để nối khớp hoàn hảo:**
  ```
  [NEO BỐI CẢNH]: Tiếp tục hoàn thiện bài viết PR giải pháp AI Chatbot doanh nghiệp theo đúng Dàn ý Trạm 2, giữ nguyên giọng điệu chuyên nghiệp, tin cậy, chuẩn báo chí công nghệ và cấu trúc thẻ H2/H3 hiện tại.

  [LỆNH NỐI TIẾP]: Bạn đã dừng lại ở cụm từ: "**xuống dưới 3 giây mà còn**". Hãy viết tiếp nối liền mạch ngay sau cụm từ này (không lặp lại phần đã viết, không viết lời dẫn mở đầu) cho đến hết phần Ưu đãi & CTA cuối bài, sau đó xuất toàn bộ bài viết hoàn chỉnh ra file Markdown tên **`tram3_bai_viet_pr_hoan_chinh.md`**.
  ```
* **Kết quả AI viết nối tiếp (khớp 100% ngữ pháp & văn phong):**
  > *"tối ưu hóa tỷ lệ chuyển đổi đơn hàng ngay cả trong khung giờ cao điểm ban đêm hoặc ngày lễ..."*