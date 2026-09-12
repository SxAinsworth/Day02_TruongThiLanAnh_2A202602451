# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trương Thị Lan Anh
- Mã học viên: 2A202602451
- Nhóm: Zone C - Bừa
- Candidate problem nhóm chọn: Nhiều hộ gia đình mua, lưu trữ hoặc nấu thực phẩm nhưng không sử dụng hết trước khi hỏng/hết hạn, dẫn đến phải thường xuyên kiểm tra đồ còn lại và vẫn bỏ phí thực phẩm.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi tìm và phân tích nhiều vấn đề đời sống hằng ngày thay vì chỉ tập trung vào các vấn đề trong lĩnh vực công nghệ. Trong đó tôi đưa ra vấn đề về lãng phí thực phẩm trong hộ gia đình và tìm số liệu bên ngoài để kiểm tra mức độ phổ biến của vấn đề. | Giúp nhóm có thêm candidate problem gần với đời sống, actor dễ tiếp cận và có khả năng validation bằng interview/survey. |
| Pitch Problem Card | Tôi trình bày bài toán quản lý thực phẩm theo hướng người dùng không biết chính xác trong nhà còn gì và thực phẩm nào cần được sử dụng trước. Tôi cũng đề xuất đo impact bằng lượng thực phẩm bị bỏ, số món hết hạn và giá trị tiền bị lãng phí. | Candidate được nhóm lựa chọn để tiếp tục phân tích sâu và xây workflow. |
| Challenge bài của bạn khác |  Tôi đặt câu hỏi về actor, bottleneck và khả năng đo impact của một số candidate khác, thay vì chỉ đánh giá dựa trên việc solution có sử dụng AI hay không. | Giúp nhóm so sánh các bài dựa trên problem và khả năng validation thay vì chọn solution trước. |
| Gom trùng / cluster | Tôi cùng nhóm phân biệt các candidate theo pain và workflow, tránh gom các vấn đề khác nhau chỉ vì đều có thể sử dụng AI. | Nhóm thu hẹp được danh sách candidate và tập trung hơn vào các bài có workflow cụ thể. |
| Chọn candidate problem | Tôi ủng hộ bài toán food waste vì actor rõ, workflow mua → lưu trữ → kiểm tra → sử dụng → bỏ thực phẩm có thể vẽ được và impact có thể đo bằng số liệu. | Nhóm thống nhất chọn bài toán lãng phí thực phẩm trong hộ gia đình để deep-dive. |
| Validation / research | Tôi research số liệu về household food waste và các giải pháp hiện có như NoWaste, Fridgely, USDA FoodKeeper và Samsung Food. Tôi cũng xác định cần interview/survey người thường xuyên mua hoặc nấu ăn để kiểm tra pain thực tế. | Research giúp nhóm nhận ra pain không chỉ là “quên hạn sử dụng”, mà còn nằm ở việc duy trì inventory quá thủ công và thiếu visibility về thực phẩm đang có. |
| Workflow nhóm | Tôi tham gia xây current workflow từ lúc mua thực phẩm, lưu trữ, kiểm tra, quyết định sử dụng đến khi phát hiện thực phẩm hỏng/hết hạn. Sau đó tôi cùng nhóm xây future workflow gồm scan → confirm → inventory database → rule kiểm tra expiry/low stock → reminder. | Nhóm xác định được bottleneck ở bước kiểm tra, ghi nhớ và ưu tiên thực phẩm cần dùng trước; đồng thời chỉ rõ human boundary và fallback. |
| Problem Statement | Tôi góp phần thu hẹp problem từ “giảm toàn bộ food waste” thành “giảm food waste do thực phẩm không được sử dụng kịp thời vì thiếu inventory visibility”. Tôi cũng đề xuất metric giảm ít nhất 30% food waste do quên/hết hạn trong pilot. | Problem Statement có actor, bottleneck, impact, metric và boundary cụ thể hơn, tránh scope quá rộng. |
| Rule / Workflow / Agent | Ban đầu solution có nhiều ý tưởng AI như gợi ý món ăn và mua thêm thực phẩm. Sau khi phân tích, tôi nhận thấy phần cốt lõi như expiry reminder, low stock, cảnh báo mua trùng và ưu tiên use-first có thể xử lý bằng Rule-based. | Nhóm tránh nhảy thẳng sang Agent và định hướng MVP đơn giản hơn: scan + inventory + rule-based tracking/reminder; AI chỉ là phần mở rộng nếu thực sự cần. |
| Decision |  Tôi đề xuất hướng làm app scan, sau đó pilot với một nhóm nhỏ để đo food waste, thời gian quản lý inventory và mức độ duy trì sử dụng. | Giúp solution bám sát problem, giảm complexity và có thể kiểm chứng trước khi bổ sung các chức năng AI phức tạp. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là phần phân tích pain point và thu hẹp scope từ bài toán
“giảm food waste” rất rộng thành vấn đề inventory visibility và thực phẩm không được
sử dụng kịp thời. Tôi cũng góp phần chuyển hướng solution từ ý tưởng AI khá rộng sang
MVP Rule-based có thể kiểm chứng được bằng metric cụ thể.

```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Tôi dùng AI để mở rộng danh sách problem và research các pain thường gặp trong đời sống. | AI giúp tôi nhanh chóng nhìn ra nhiều nhóm problem khác nhau như food waste, subscription, privacy, travel và scam. | Ban đầu AI tập trung quá nhiều vào problem của developer và một số problem khá rộng. | Tôi yêu cầu chuyển sang các vấn đề đời sống hằng ngày và loại các ý tưởng trùng nhau hoặc quá chung chung. |
| Problem Card | Tôi dùng AI để phản biện actor, workflow, bottleneck và metric của bài food waste. | AI giúp tách symptom “thực phẩm bị bỏ đi” khỏi pain “không biết đang có gì và món nào cần dùng trước”. | Một số đề xuất ban đầu bao phủ quá nhiều nguyên nhân food waste cùng lúc. | Tôi giữ scope vào thực phẩm bị quên/hết hạn và không cố giải quyết nấu thừa, bảo quản sai hay mọi nguyên nhân khác. |
| Workflow | Tôi dùng AI để hệ thống hóa current/future workflow và phân biệt bước của máy, Rule, AI và người dùng. | AI giúp biểu diễn workflow rõ hơn và nhìn ra human boundary/fallback. | Future workflow ban đầu có khá nhiều bước và dễ biến thành một AI kitchen assistant quá lớn. | Tôi thu hẹp MVP vào scan, inventory database, expiry tracking, reminder và low-stock rule. |
| Research | Tôi dùng AI để tìm và tổng hợp các sản phẩm hiện có và nguồn tham khảo. | AI giúp tìm NoWaste, Fridgely, FoodKeeper và Samsung Food để so sánh feature và limitation. | Có những claim hoặc con số không thể dùng nếu chưa kiểm tra nguồn chính thức. | Tôi chỉ giữ thông tin có link kiểm tra được và coi estimated expiry là guideline chứ không phải kết luận an toàn thực phẩm. |
| Problem Statement | Tôi dùng AI để challenge các field còn mơ hồ. | AI chỉ ra Actor còn rộng, baseline chưa có dữ liệu thật và boundary phải rõ hơn. | AI có thể đề xuất metric cụ thể khi nhóm chưa có baseline thật. | Tôi ghi rõ các con số hiện tại là target/hypothesis và cần thay bằng dữ liệu validation/pilot thực tế. |
| Rule / Workflow / Agent | Tôi dùng AI để so sánh ba mức solution. | AI giúp tôi hiểu các bước deterministic như expiry, low stock và duplicate item không cần Agent. | Nếu đi theo toàn bộ suggestion của AI, solution dễ có thêm recipe recommendation, meal planning và shopping agent quá sớm. | Tôi chọn Rule-based cho core MVP và chỉ giữ AI như khả năng mở rộng cho các bài toán có ambiguity cao. |
| Decision | Tôi dùng AI để kiểm tra tính hợp lý của hướng pilot và success metric. | AI giúp gợi ý cách đo before/after và các risk như OCR sai, notification overload hoặc inventory không được cập nhật. | AI không thể quyết định thay nhóm liệu solution có thực sự được user sử dụng hay không. | Tôi coi Go là quyết định có điều kiện: phải pilot với người dùng thật và sẵn sàng thay đổi solution nếu validation không xác nhận pain. |
> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Qua buổi làm bài, tôi nhận ra một problem tốt không nhất thiết phải là problem nghe
“AI” nhất mà phải có actor, workflow và bottleneck đủ rõ để kiểm chứng. Ban đầu khi
nghĩ về bài toán lãng phí thực phẩm, tôi có xu hướng nghĩ ngay tới một ứng dụng AI có
thể scan đồ ăn, nhắc hạn sử dụng, gợi ý món ăn và đề xuất mua thêm. Tuy nhiên sau khi
phân tích workflow, tôi nhận ra phần lớn chức năng cốt lõi như theo dõi hạn sử dụng,
cảnh báo sắp hết hạn, low stock hay mua trùng đều có thể giải quyết bằng Rule-based.

Điều khó nhất với tôi là thu hẹp Problem Statement vì “food waste” có rất nhiều nguyên
nhân và nhóm không thể giải quyết tất cả trong một solution. Sau khi research, tôi thấy
pain phù hợp hơn là người dùng thiếu visibility về thực phẩm đang có và không sử dụng
chúng kịp thời trước khi hỏng hoặc hết hạn. Tôi cũng nhận ra metric không thể chỉ ghi
“giảm lãng phí thực phẩm” mà phải có baseline, cách đo và target cụ thể, ví dụ đo lượng
food waste trước và sau pilot.

Phần tôi thấy mình đóng góp rõ nhất là việc thu hẹp pain point, xây workflow và đặt câu
hỏi xem AI có thật sự cần thiết ở từng bước hay không. Nếu làm lại, tôi sẽ validation
với người dùng thật sớm hơn trước khi đi sâu vào thiết kế solution, vì có thể nguyên nhân
food waste mà người dùng gặp thực tế khác với giả định ban đầu của nhóm. Tôi cũng sẽ
challenge nhóm mạnh hơn mỗi khi xuất hiện một feature mới bằng câu hỏi: feature này
đang giải quyết bottleneck nào và nếu bỏ AI đi thì Rule hoặc process fix đã đủ chưa?
```


---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

