# Checklist Đầu Tư Giá Trị (Buffett) — 8 Cổ Phiếu Blue-chip Việt Nam

> "Quy tắc số 1 của đầu tư là không để mất tiền. Quy tắc số 2 là không quên quy tắc số 1." — Warren Buffett

**Ngày lập:** 2026-06-29 · **Đơn vị tiền tệ:** VND (trừ khi ghi rõ) · **Sàn:** HOSE
**Mã phân tích:** VIC, VHM, FPT, CTG, VCB, SSI, TCB, ACB
**Phương pháp:** Checklist 6 cửa của Buffett. Mục tiêu là **loại bỏ lựa chọn xấu**, không phải tìm cổ phiếu tốt nhất. P/E được tính chính xác bằng `tools/financial_rigor.py` (số thập phân `Decimal`, không nhẩm tay).

---

## ⚠️ Cảnh báo thiên lệch dữ liệu (đọc trước)

| Loại | Mã | Ý nghĩa |
|------|-----|---------|
| **A — Dữ liệu dồi dào** | VCB, CTG, TCB, ACB, FPT | Niêm yết lâu, báo cáo đầy đủ. Cảnh giác "bẫy đồng thuận" — số liệu rõ ≠ chắc chắn. |
| **B — Cần ước tính** | VHM, SSI, VIC | Một số chỉ tiêu (FCF, phải thu liên quan, P/B) phải suy ra hoặc nguồn xung đột. EPS dùng để tính P/E là ước tính/dẫn xuất. |

**Hạn chế quan trọng:** Bộ công cụ gốc (`ashare_data.py`) phục vụ cổ phiếu Trung Quốc, **không** lấy được dữ liệu Việt Nam. Toàn bộ số liệu dưới đây thu thập từ nguồn thứ cấp (báo cáo công ty, GTJAI/KBSV/Vietcap/MBS, stockanalysis, vietstock, theinvestor.vn...) qua tra web ngày 2026-06-29. **Giá và định giá biến động — phải kiểm tra lại bảng giá trực tiếp trước khi ra quyết định.** Các chỉ tiêu đánh dấu "ước tính" cần đối chiếu báo cáo tài chính đã kiểm toán.

**Lưu ý về 4 ngân hàng (CTG, VCB, TCB, ACB):** Checklist Buffett gốc thiết kế cho doanh nghiệp phi tài chính (chú trọng FCF, biên gộp, đòn bẩy thấp). Ngân hàng dùng đòn bẩy là bản chất nghề, nên cửa "good business" và "an toàn" được đánh giá lại theo bộ chỉ tiêu ngân hàng (ROE, NIM, NPL, tỷ lệ bao phủ nợ xấu, CASA, CAR, P/B). Buffett vẫn mua ngân hàng (Wells Fargo, BofA) — nhưng chỉ ngân hàng kỷ luật rủi ro và chi phí vốn thấp.

---

# PHẦN I — PHÂN TÍCH TỪNG CÔNG TY

---

## 1. FPT — FPT Corporation (Công nghệ) · Hạng A

**Mô hình kinh doanh (một câu):** Xuất khẩu dịch vụ phần mềm/CNTT (chủ yếu Nhật Bản, ~80% doanh thu công nghệ là quốc tế) + viễn thông trong nước + giáo dục.

| Chỉ tiêu cốt lõi | Giá trị | Nguồn/ngày |
|---|---|---|
| Giá | ~71,700 | 2026-06-29 (giảm ~31% so với đỉnh 135,700 ngày 23/01/2025) |
| Vốn hóa | ~125 nghìn tỷ (~4.9 tỷ USD) | 2026-06 |
| **P/E (tính chính xác)** | **13.30x** (71,700 / EPS 5,392) | financial_rigor.py |
| P/E dự phóng | ~11.6x | đồng thuận |
| P/B | ~3.5–4x (ước tính) | suy từ ROE/PE |
| ROE | FY24 ~26.6%, **TTM ~28.5%** | stockanalysis |
| Cổ tức | ~2.1–2.7%; tiền + cổ phiếu | FY24: 20% tiền + 15% cp |
| Net cash | **~+10.6 nghìn tỷ** (tiền 26.75T − nợ 16.1T) | TTM |
| DT FY2025 | 70,113 tỷ (+11.6%); LNST 11,232 tỷ (+19.1%) | BC chính thức 1/2026 |
| Backlog ký mới IT nước ngoài | **>1.5 tỷ USD (+23.2%)** | FY2025 |

### Bảng chấm 6 cửa

| Cửa | Điểm | Lý do |
|---|---|---|
| 1. Vòng tròn năng lực | ★★★★☆ | Mô hình rõ ràng; rủi ro 10 năm: AI có thể thay đổi gia công phần mềm. |
| 2. Good business | ★★★★☆ | ROE ~28%, net cash, FCF ~6.7T, biên ổn định. Trừ điểm vì viễn thông/data center ngốn capex. |
| 3. Hào kinh tế | ★★★★☆ | Quy mô xuất khẩu IT #1 VN, quan hệ Nhật 20 năm, chi phí nhân công rẻ, ĐH FPT tự đào tạo kỹ sư. Nhưng arbitrage lương sẽ mòn + đe dọa AI. |
| 4. Ban lãnh đạo | ★★★★☆ | Trương Gia Bình sáng lập, cổ tức đều, phân bổ vốn kỷ luật, M&A bổ trợ. Sở hữu ~6.9%. |
| 5. Biên an toàn | ★★★★☆ | P/E 13x (từng >20x), dự phóng 11.6x, net cash, tăng trưởng 15–19%/năm — định giá hấp dẫn cho chất lượng này. |

**Rủi ro chính:** (1) AI làm gián đoạn gia công phần mềm; (2) room ngoại kịch trần ~49% → NĐT nước ngoài khó mua, tạo áp lực; (3) chi tiêu IT toàn cầu chậm lại; (4) phụ thuộc thị trường Nhật.

**Bài test gương:** *"Tôi mua FPT giá ~71,700 vì: (1) bản chất là nhà xuất khẩu dịch vụ IT chi phí thấp #1 VN, tôi hiểu; (2) hào là quy mô + quan hệ Nhật + nguồn kỹ sư tự đào tạo, đang ổn định nhưng AI là biến số; (3) ban lãnh đạo sáng lập, kỷ luật, đáng tin; (4) P/E 13x dưới mức lịch sử 20x+, có biên an toàn khá; (5) nếu sai, rủi ro giảm có kiểm soát nhờ net cash + dòng tiền mạnh."* → **ĐỦ 5 CÂU.**

### ✅ KẾT LUẬN: QUA CHECKLIST (5/5 cửa đạt ≥4★) — chất lượng cao nhất nhóm phi-ngân hàng. Đáng nghiên cứu sâu.

---

## 2. VCB — Vietcombank (Ngân hàng SOE) · Hạng A

**Mô hình (một câu):** Ngân hàng quốc doanh chất lượng cao nhất Việt Nam, gốc tài trợ thương mại/ngoại hối, chi phí vốn thấp nhất hệ thống.

| Chỉ tiêu cốt lõi | Giá trị | Nguồn |
|---|---|---|
| Giá | ~61,800 | 16/06/2026 |
| Vốn hóa | ~516 nghìn tỷ (~19–20 tỷ USD) — lớn nhất ngành | 2026-06 |
| **P/E (tính chính xác)** | **15.67x** (61,800 / EPS 3,945) | financial_rigor.py |
| P/B | ~2.5–3x (premium ngành; chưa xác nhận) | ước tính |
| ROE 2025 | nguồn xung đột: ">21%" (cty) vs "16.5%" (phân tích) | cần kiểm chứng |
| NIM | nén còn ~2.65–2.7% (Q3/25) | KBSV |
| NPL | ~1.03% (Q3/25), thấp nhất hệ thống | KBSV |
| Bao phủ nợ xấu | **~202%** (cao nhất ngành) | KBSV |
| LNST 2025 | ~43,714 tỷ (+5.3%) | vietnam.vn 1/2026 |
| Sở hữu | SBV ~74.8%, Mizuho 15% | 2025 |

### Bảng chấm 6 cửa

| Cửa | Điểm | Lý do |
|---|---|---|
| 1. Vòng tròn năng lực | ★★★★☆ | Ngân hàng sạch nhất, dễ hiểu nhất Big-4. |
| 2. Good business (NH) | ★★★★☆ | ROE ~18–21%, NPL thấp nhất, bao phủ cao nhất, chi phí vốn thấp nhất. Trừ điểm vì NIM nén + tăng trưởng LN chỉ +5%. |
| 3. Hào kinh tế | ★★★★☆ | Franchise huy động + chi phí vốn thấp nhất + "flight-to-quality" + hậu thuẫn nhà nước. |
| 4. Ban lãnh đạo | ★★★☆☆ | Vận hành tốt nhưng bị nhà nước chi phối (~75%), định hướng tín dụng theo chính sách, cổ tức tiền mặt nhỏ. |
| 5. Biên an toàn | ★★★☆☆ | Đắt nhất nhóm ngân hàng: P/E 15.7x, P/B ~2.5–3x. Chất lượng đã phản ánh vào giá; biên an toàn hạn chế. |

**Rủi ro chính:** (1) NIM tiếp tục nén; (2) phát hành riêng lẻ ~543 triệu cp (~1.3–1.4 tỷ USD) + cổ tức cổ phiếu ~49.5% → pha loãng; (3) tăng trưởng LN khiêm tốn (+5%); (4) định giá premium, ít biên an toàn; (5) số liệu 2025 ROE/CAR/P/B nguồn xung đột.

**Bài test gương:** *"...P/E 15.7x, P/B ~3x — chất lượng tốt nhất nhưng giá premium, biên an toàn mỏng..."* → đủ 5 câu nhưng câu 4 (biên an toàn) yếu.

### ✅ KẾT LUẬN: QUA CHECKLIST về chất lượng (ngân hàng tốt nhất VN) nhưng ĐỊNH GIÁ ĐẮT — chờ giá tốt hơn. Buffett: "Giá tuyệt vời cho công ty tầm thường không bằng giá tầm thường cho công ty tuyệt vời" — VCB là công ty tuyệt vời ở giá không rẻ.

---

## 3. ACB — Asia Commercial Bank (Ngân hàng tư nhân) · Hạng A

**Mô hình (một câu):** Ngân hàng tư nhân bán lẻ/SME, văn hóa rủi ro bảo thủ, ít BĐS/trái phiếu, chất lượng tài sản tốt nhất hệ thống.

| Chỉ tiêu cốt lõi | Giá trị | Nguồn |
|---|---|---|
| Giá | ~22,200–22,500 | 21–24/06/2026 (gần đáy nhiều năm) |
| Vốn hóa | ~129–131 nghìn tỷ (~5 tỷ USD) | 2026-06 |
| **P/E (tính chính xác)** | **7.60x** (22,350 / EPS ~2,940) | financial_rigor.py |
| P/B | ~1.2–1.4x (ước tính) | — |
| ROE | **>20%** (duy trì qua 2024–25) | Vietstock |
| NIM | nén còn **2.92%** (từ ~4.0%) | Vietstock |
| NPL | **0.97%** — thấp nhất hệ thống | ACB 1/2026 |
| CASA | 22.6% | FY2025 |
| LNTT 2025 | 19,500 tỷ (**−7% YoY, giảm lần đầu từ 2013**) | theinvestor 3/2026 |
| Cổ tức | 2026 khôi phục 25% (15% cp + 10% tiền) | AGM 4/2026 |

### Bảng chấm 6 cửa

| Cửa | Điểm | Lý do |
|---|---|---|
| 1. Vòng tròn năng lực | ★★★★☆ | Ngân hàng bán lẻ/SME đơn giản, bảo thủ. |
| 2. Good business (NH) | ★★★★☆ | ROE >20%, NPL thấp nhất, CIR ~32%. Trừ điểm vì NIM nén mạnh (4→2.9%) + LN 2025 giảm 7%. |
| 3. Hào kinh tế | ★★★☆☆ | Văn hóa rủi ro bảo thủ + danh tiếng chất lượng tài sản là khác biệt thật, nhưng hào ngân hàng nhìn chung nông; chi phí vốn không thấp như VCB/TCB. |
| 4. Ban lãnh đạo | ★★★★☆ | Gia đình Trần (Trần Hùng Huy) + chuyên nghiệp hóa hậu 2012, cổ tức đều. Không bị nhà nước chi phối. |
| 5. Biên an toàn | ★★★★☆ | P/E 7.6x, P/B ~1.3x, lợi suất ~3%, gần đáy nhiều năm — biên an toàn tốt. |

**Rủi ro chính:** (1) NIM nén do cạnh tranh lãi suất; (2) LN giảm 7% năm 2025 — chu kỳ kiếm lời chững lại; (3) mở rộng cho vay DN lớn/FDI (+62%/+170%) làm lệch khỏi mô hình bán lẻ bảo thủ truyền thống → cần theo dõi chất lượng tài sản; (4) NPL 0.97% có nguồn cũ ghi ~1.5%, cần kiểm chứng.

**Bài test gương:** *"Tôi mua ACB ~22,350 vì: (1) ngân hàng bán lẻ/SME bảo thủ, tôi hiểu; (2) hào là văn hóa rủi ro + NPL thấp nhất, ổn định; (3) gia đình sáng lập + chuyên nghiệp, đáng tin; (4) P/E 7.6x, P/B 1.3x, gần đáy — biên an toàn tốt; (5) nếu sai, đệm an toàn nhờ chất lượng tài sản tốt nhất + định giá rẻ."* → **ĐỦ 5 CÂU.**

### ✅ KẾT LUẬN: QUA CHECKLIST — ngân hàng chất lượng cao + định giá rẻ nhất nhóm. Điểm trừ: đà lợi nhuận đang chững (NIM nén). Đáng nghiên cứu sâu.

---

## 4. CTG — VietinBank (Ngân hàng SOE) · Hạng A

**Mô hình (một câu):** Ngân hàng quốc doanh Big-4, thiên về cho vay doanh nghiệp lớn/FDI, đối tác chiến lược MUFG (Nhật).

| Chỉ tiêu cốt lõi | Giá trị | Nguồn |
|---|---|---|
| Giá | ~35,550 | 2026 (đỉnh 43,500 ngày 12/01/2026) |
| Vốn hóa | ~271–274 nghìn tỷ (~10 tỷ USD) | 2026 |
| **P/E (tính chính xác)** | **7.98x** (35,550 / EPS 4,453.6) | financial_rigor.py |
| **P/B** | **1.46x**; ROE nội suy 18.3% | financial_rigor.py |
| ROE 2025 | **21.25%** (bước nhảy) | vietnam.vn FY25 |
| NIM | 2.59% | FY2025 |
| NPL | **1.10%** (Q1/26: 1.02%) | FY25 |
| Bao phủ nợ xấu | 158.8% | FY25 |
| LNTT 2025 | **43,400 tỷ (+36.8%)** — vượt BIDV lên #2 | FY25 |
| LNTT Q1/2026 | 11,139 tỷ (**+63.3%** — nhanh nhất nhóm SOE) | theinvestor |
| Sở hữu | SBV ~64.5%, MUFG 19.73% | — |

### Bảng chấm 6 cửa

| Cửa | Điểm | Lý do |
|---|---|---|
| 1. Vòng tròn năng lực | ★★★★☆ | Ngân hàng SOE dễ hiểu. |
| 2. Good business (NH) | ★★★★☆ | ROE bứt lên 21.25%, NPL giảm, LN +37%. Đà cải thiện mạnh. Trừ điểm vì CAR lịch sử mỏng, NIM thấp 2.59%. |
| 3. Hào kinh tế | ★★★★☆ | Hậu thuẫn nhà nước, quy mô #2, franchise huy động, kênh MUFG (FDI Nhật). |
| 4. Ban lãnh đạo | ★★★☆☆ | SOE bị nhà nước chi phối (~64.5%), cổ tức tiền mặt lịch sử ít (do thiếu vốn), cải thiện gần đây. |
| 5. Biên an toàn | ★★★★☆ | P/E 8.0x, P/B 1.46x trên ROE 21% — rẻ tương đối so với khả năng sinh lời. |

**Rủi ro chính:** (1) CAR lịch sử là điểm yếu, phải tăng vốn bằng cổ tức cổ phiếu; (2) thiên cho vay DN lớn/FDI → rủi ro tập trung; (3) bị nhà nước chi phối, định hướng chính sách; (4) NIM thấp 2.59%; (5) áp lực giảm sở hữu nhà nước về 51% (Quyết định 986).

**Bài test gương:** *"...P/E 8x, P/B 1.46x trên ROE 21% đang cải thiện, đà LN +37%..."* → **ĐỦ 5 CÂU.**

### ✅ KẾT LUẬN: QUA CHECKLIST — định giá rẻ + đà cải thiện mạnh nhất nhóm SOE. Điểm trừ: quản trị SOE + CAR mỏng. Đáng nghiên cứu sâu.

---

## 5. TCB — Techcombank (Ngân hàng tư nhân) · Hạng A

**Mô hình (một câu):** Ngân hàng tư nhân dẫn đầu CASA + ngân hàng số, hệ sinh thái (TCBS chứng khoán, bảo hiểm), thiên BĐS/trái phiếu.

| Chỉ tiêu cốt lõi | Giá trị | Nguồn |
|---|---|---|
| Giá | ~33,400 | 26/06/2026 |
| Vốn hóa | ~232 nghìn tỷ (~8.3 tỷ USD) | 2026-06 |
| **P/E (tính chính xác)** | **9.11x** (33,400 / EPS 3,666) — *thấp hơn con số 12.5x từ nguồn cũ 8/2025* | financial_rigor.py |
| P/B | ~1.7x | Vietcap (8/2025, có thể cũ) |
| ROE | **16.0%** (FY25) | BC TCB |
| NIM | nén còn **3.1%** (Q1/26, từ 5.3% 2022) | BC TCB |
| NPL | 1.13% (FY25); bao phủ 127.9% | BC TCB |
| **CASA** | **40.4%** — cao nhất hệ thống | BC TCB |
| CAR | 14.6% (FY25) | BC TCB |
| LNTT 2025 | 32,500 tỷ (+18.2%) | BC TCB |
| Sở hữu | Gia đình Hồ Hùng Anh ~33% + Masan 14.89% | VnExpress |

### Bảng chấm 6 cửa

| Cửa | Điểm | Lý do |
|---|---|---|
| 1. Vòng tròn năng lực | ★★★★☆ | Dễ hiểu nhưng phức tạp hơn vì thiên BĐS/trái phiếu + hệ sinh thái. |
| 2. Good business (NH) | ★★★★☆ | ROE 16%, CASA cao nhất, CIR thấp ~30%. Trừ điểm vì NIM nén rất mạnh (5.3→3.1%) + tập trung BĐS. |
| 3. Hào kinh tế | ★★★★☆ | Franchise CASA (chi phí vốn thấp nhất), số hóa #1, hệ sinh thái (TCBS #1 chứng khoán, bảo hiểm #1 banca). |
| 4. Ban lãnh đạo | ★★★☆☆ | CEO chuyên nghiệp (Jens Lottner) là điểm cộng, nhưng gia đình Hồ Hùng Anh + Masan kiểm soát ~48% → rủi ro tập trung + liên quan (Vingroup/Masterise BĐS). |
| 5. Biên an toàn | ★★★★☆ | P/E ~9x, P/B ~1.7x, lợi suất ~3% — hợp lý đến hấp dẫn cho ROE 16% + CASA tốt nhất. |

**Rủi ro chính:** (1) NIM nén mạnh nhất nhóm (xuống 3.1%); (2) tập trung BĐS ~29% dư nợ + franchise trái phiếu DN — rủi ro chu kỳ BĐS; (3) sở hữu gia đình + Masan ~48% → tập trung/quan hệ liên quan; (4) CASA tụt còn 37.9% Q1/26 khi lãi suất cao.

**Bài test gương:** *"...hào CASA 40% chi phí vốn thấp nhất; P/E 9x hợp lý; rủi ro tập trung BĐS + sở hữu gia đình là điểm cần canh..."* → **ĐỦ 5 CÂU** (với cảnh báo BĐS).

### ✅ KẾT LUẬN: QUA CHECKLIST — franchise CASA mạnh nhất + định giá rẻ. ĐIỂM CANH: tập trung BĐS/trái phiếu + sở hữu gia đình/Masan. Đáng nghiên cứu sâu với khẩu vị rủi ro phù hợp.

---

## 6. SSI — SSI Securities (Chứng khoán) · Hạng B

**Mô hình (một câu):** Công ty chứng khoán #1 VN — môi giới + cho vay margin + tự doanh (chủ yếu trái phiếu/CD) + IB; thu nhập mang tính **chu kỳ cao**.

| Chỉ tiêu cốt lõi | Giá trị | Nguồn |
|---|---|---|
| Giá | ~26,850 (gần đáy 52 tuần 24,000–44,150) | 2026-06 |
| Vốn hóa | ~67 nghìn tỷ (~2.5 tỷ USD) | 2026-06 |
| **P/E (tính chính xác)** | **12.91x** (26,850 / EPS ~2,080, ước tính) | financial_rigor.py |
| P/B | ~2.1x (tính từ vốn CSH ~31T) | ước tính |
| ROE | 13.5% (cuối 2025, gần đỉnh dải) | cafef |
| LNTT 2025 | **5,085 tỷ — kỷ lục** | ssi.com.vn |
| Thị phần môi giới | 11.53% (#1, cao nhất 5 năm) | VIR |
| Dư nợ margin | 38,940 tỷ (+77% trong năm) | FY25 |
| Đòn bẩy (nợ/VCSH) | ~1.93x | vietnam.vn |
| Sở hữu | Nguyễn Duy Hưng ~8.7%, Daiwa 15.26% | 2025-12 |

### Bảng chấm 6 cửa

| Cửa | Điểm | Lý do |
|---|---|---|
| 1. Vòng tròn năng lực | ★★★☆☆ | Hiểu được nhưng lợi nhuận khó dự báo (phụ thuộc thanh khoản thị trường). |
| 2. Good business | ★★☆☆☆ | Chu kỳ cao, không có quyền định giá (chiến tranh phí về 0), đòn bẩy 1.9x, pha loãng vốn liên tục. ROE 13.5% là đỉnh chu kỳ. |
| 3. Hào kinh tế | ★★☆☆☆ | Là DN hàng hóa hóa (commodity). Lợi thế của SSI chỉ là quy mô (bảng cân đối lớn nhất → margin lớn nhất), không phải quyền định giá. |
| 4. Ban lãnh đạo | ★★★☆☆ | Sáng lập Nguyễn Duy Hưng (~9%), Daiwa giám sát. Nhưng phát hành cổ phiếu lặp lại để bơm dư nợ margin → pha loãng cổ đông. |
| 5. Biên an toàn | ★★☆☆☆ | P/E 13x trên **lợi nhuận đỉnh chu kỳ** — mua chu kỳ ở đỉnh với P/E thấp là cái bẫy. Gần đáy 52 tuần không bù được rủi ro chu kỳ. |

**Rủi ro chính:** (1) chu kỳ — thị trường giảm sẽ nén đồng thời cả 3 mảng (môi giới, margin, tự doanh); (2) chiến tranh phí môi giới về 0; (3) pha loãng vốn lặp lại; (4) đòn bẩy 1.9x + rủi ro margin call hệ thống; (5) câu chuyện nâng hạng FTSE EM (hiệu lực 21/09/2026) là chất xúc tác nhưng mang tính đầu cơ/đồng thuận thị trường.

**Bài test gương:** *"...hào? — gần như không, là DN hàng hóa chu kỳ; mua ở đỉnh lợi nhuận; lý do chính là câu chuyện nâng hạng FTSE..."* → **CÂU 2 và 4 KHÔNG VIẾT NỔI** (không có hào bền + biên an toàn yếu khi mua đỉnh chu kỳ).

### ❓ KẾT LUẬN: VÙNG XÁM, NGHIÊNG VỀ KHÔNG ĐẠT — Theo tiêu chí Buffett: **thiếu hào bền vững** + **mua DN chu kỳ ở đỉnh lợi nhuận**. SSI là công ty đầu ngành thật, nhưng không phải kiểu DN Buffett mua để giữ. Nếu đầu tư, đây là cược chu kỳ/nâng hạng, không phải đầu tư giá trị dài hạn. Tranh cãi cốt lõi NĐT phải tự quyết: *FTSE EM có đẩy thanh khoản đủ lâu để bù rủi ro chu kỳ + pha loãng không?*

---

## 7. VHM — Vinhomes (Bất động sản nhà ở) · Hạng B

**Mô hình (một câu):** Nhà phát triển BĐS nhà ở lớn nhất VN (các đại đô thị Ocean Park, Royal Island, Green Paradise), công ty con của Vingroup.

| Chỉ tiêu cốt lõi | Giá trị | Nguồn |
|---|---|---|
| Giá | ~162,000 (chạy từ đáy 67,000) | 26/06/2026 |
| Vốn hóa | ~665 nghìn tỷ (~21 tỷ USD) | 2026-06 |
| **P/E (tính chính xác)** | **10.32x** TTM (162,000 / EPS ~15,700) — *méo do Q1/26* | financial_rigor.py |
| P/E dự phóng | ~14x (đại diện hơn) | SimplyWallSt |
| Biên LNST | 27% (FY25), lịch sử 27–32% — rất cao | stockanalysis |
| ROE | ~13.2% | SimplyWallSt |
| Nợ/VCSH ròng | ~42% — vừa phải | SimplyWallSt |
| DT 2025 | 154,102 tỷ (+50%); LNST 42,100 tỷ (+32%) | BC Q4/25 |
| Quỹ đất | **~29,500 ha — lớn nhất VN** | BC thường niên 2025 |
| Cổ tức | tiền mặt 60% (~6,000đ/cp, kỷ lục VN) + cp 100% | AGM 4/2026 |
| Sở hữu | Vingroup ~90% | — |

### Bảng chấm 6 cửa

| Cửa | Điểm | Lý do |
|---|---|---|
| 1. Vòng tròn năng lực | ★★★☆☆ | Doanh thu lồi lõm (ghi nhận lúc bàn giao) + cấu trúc BCC/liên quan phức tạp. |
| 2. Good business | ★★★☆☆ | Biên LNST 27–32% (rất cao cho nhà phát triển), quỹ đất lớn nhất. Nhưng chu kỳ, FCF không xác định được, chất lượng LN phụ thuộc giao dịch liên quan. |
| 3. Hào kinh tế | ★★★☆☆ | Quỹ đất lớn nhất + thương hiệu + hệ sinh thái Vingroup. Nhưng phụ thuộc công ty mẹ. |
| 4. Ban lãnh đạo | ★★☆☆☆ | Vingroup kiểm soát ~90%, cấu trúc BCC + phải thu lớn từ công ty mẹ, quản trị cổ đông thiểu số phụ thuộc mẹ. 3 năm (2022–24) không cổ tức rồi đột ngột chia kỷ lục. |
| 5. Biên an toàn | ★★★☆☆ | P/E TTM 10x (méo), dự phóng 14x; cổ phiếu đã chạy 2.4 lần từ đáy. Định giá hợp lý sau khi tăng mạnh. |

**Rủi ro chính:** (1) **Phụ thuộc công ty mẹ Vingroup** — không xác minh được phải thu liên quan (cần BCTC kiểm toán); (2) khoảng cách ~30 nghìn tỷ giữa doanh thu thống kê và "điều chỉnh" (BCC) báo hiệu giao dịch liên quan lớn; (3) chu kỳ BĐS + pháp lý dự án; (4) doanh thu lồi lõm khó dự báo; (5) đã dừng mua đất mới trong nước → chuyển sang "thu hoạch" quỹ đất hiện có.

**Bài test gương:** *"...hào là quỹ đất + thương hiệu nhưng phụ thuộc mẹ Vingroup; ban lãnh đạo — quản trị cổ đông thiểu số là dấu hỏi do giao dịch liên quan..."* → **CÂU 3 (quản trị) KHÓ VIẾT TRỌN.**

### ❓ KẾT LUẬN: VÙNG XÁM — Kinh tế BĐS tốt (biên cao, quỹ đất lớn nhất) nhưng **quan hệ với công ty mẹ Vingroup là câu hỏi trung tâm** không xác minh được bằng dữ liệu công khai. Tranh cãi cốt lõi NĐT phải tự quyết: *chất lượng lợi nhuận có "thật" và độc lập với giao dịch nội bộ Vingroup không?* Cần đọc thuyết minh giao dịch liên quan trong BCTC kiểm toán 2025 trước khi quyết.

---

## 8. VIC — Vingroup (Tập đoàn đa ngành) · Hạng B

**Mô hình (một câu):** Tập đoàn tư nhân lớn nhất VN — Vinhomes (BĐS, máy in tiền) gánh VinFast (xe điện, lỗ nặng) + Vinpearl + đường sắt/năng lượng mới.

| Chỉ tiêu cốt lõi | Giá trị | Nguồn |
|---|---|---|
| Giá | ~228,000 (đỉnh lịch sử 242,000 ngày 24/06/2026) | 28/06/2026 |
| Vốn hóa | **~1,728 nghìn tỷ (~66 tỷ USD)** | 2026-06 |
| **P/E (tính chính xác)** | **156.16x** (228,000 / EPS ~1,460) — cực cao | financial_rigor.py |
| P/B | ~10x | MRQ |
| ROE | ~7.3–9.3% (đòn bẩy thổi phồng) | Investing.com |
| Biên LNST | ~3.3% (VinFast kéo xuống) | FY25 |
| DT 2025 | 332,770 tỷ (+76%); LNST 11,150 tỷ (+111%) | BC FY25 |
| Nợ/VCSH | **~2.2–2.4x — cao** | GuruFocus |
| VinFast | lỗ ròng ~97–99 nghìn tỷ; **kiểm toán nêu "nghi ngờ hoạt động liên tục"** | 20-F |
| Sở hữu | Phạm Nhật Vượng + gia đình/thực thể ~65% | — |
| Cổ tức | ~0% | — |

### Bảng chấm 6 cửa

| Cửa | Điểm | Lý do |
|---|---|---|
| 1. Vòng tròn năng lực | ★★☆☆☆ | Tập đoàn đa ngành phức tạp (BĐS + xe điện + mọi thứ), rất khó định giá. |
| 2. Good business | ★★☆☆☆ | Hợp nhất: ROE 7–9%, biên ròng 3%, **FCF nhóm âm** (VinFast đốt ~44T/năm), **going-concern flag**, D/E 2.2–2.4x. Vinhomes tuyệt vời nhưng bị VinFast kéo xuống. |
| 3. Hào kinh tế | ★★★☆☆ | BĐS + quan hệ chính trị mạnh; VinFast **không có hào** (biên âm, cạnh tranh EV toàn cầu khốc liệt). Câu chuyện hào là đòn bẩy + quan hệ, không phải quyền định giá kiểu Buffett. |
| 4. Ban lãnh đạo | ★★☆☆☆ | Sáng lập Vượng kiểm soát ~65%, nhưng phân bổ vốn gây tranh cãi: trợ cấp/cho vay cá nhân ~2 tỷ USD cứu VinFast; vụ Novatech (mua tài sản R&D VinFast ~1.6 tỷ USD) bị nghi ngại quản trị; lấy dòng tiền BĐS bù lỗ EV. |
| 5. Biên an toàn | ★☆☆☆☆ | **P/E 156x, P/B 10x, đỉnh lịch sử sau khi tăng ~1000%, không cổ tức** — định giá đầu cơ cực đoan, không có biên an toàn. |

**Rủi ro chính:** (1) **VinFast bị kiểm toán nêu nghi ngờ hoạt động liên tục** — phụ thuộc dòng tiền liên tục từ Vingroup/người sáng lập; (2) đòn bẩy cao D/E 2.2–2.4x, current ratio ~0.32 (thanh khoản ngắn hạn yếu); (3) P/E 156x đầu cơ — cần "người mua sau trả giá cao hơn"; (4) giao dịch liên quan (Novatech, chuyển nợ) gây lo ngại quản trị; (5) toàn bộ luận điểm phụ thuộc Vinhomes tiếp tục bơm tiền cho VinFast.

**Bài test gương:** *"...biên an toàn? — P/E 156x đầu cơ, không có; good business? — FCF nhóm âm, VinFast going-concern..."* → **CÂU 2 và 4 KHÔNG VIẾT NỔI.**

### ❌ KẾT LUẬN: KHÔNG QUA CHECKLIST — Kích hoạt nhiều lằn ranh đỏ: (a) FCF nhóm âm nhiều năm do VinFast + kiểm toán nêu going-concern; (b) định giá P/E 156x cần "kẻ ngốc lớn hơn" (博傻); (c) lo ngại quản trị giao dịch liên quan. Vinhomes bên trong là tài sản tuyệt vời, nhưng mua VIC = mua cả canh bạc VinFast với đòn bẩy cao ở định giá đầu cơ. *(Lưu ý: cổ phiếu tăng mạnh và đà lợi nhuận tốt — nhưng đó là câu chuyện động lượng/đầu cơ, không phải đầu tư giá trị.)*

---

# PHẦN II — DANH SÁCH PHỦ QUYẾT NHANH

| Lằn ranh đỏ | VIC | VHM | FPT | CTG | VCB | SSI | TCB | ACB |
|---|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| Không nói rõ cách kiếm tiền | | | | | | | | |
| FCF âm 3 năm, không cải thiện | ⚠️ | | | n/a | n/a | | n/a | n/a |
| Ban lãnh đạo có tì vết liêm chính | | | | | | | | |
| Lợi thế cạnh tranh bị xói mòn không đảo ngược | | | | | | ⚠️ | | |
| Cần "kẻ ngốc lớn hơn" (博傻) để lời | 🔴 | | | | | ⚠️ | | |
| Không chịu nổi nếu khoản này về 0 | ⚠️ | | | | | | | |
| Lý do mua chính là "ai cũng mua/mới tăng" | ⚠️ | | | | | ⚠️ | | |
| Quản trị/giao dịch liên quan đáng ngại | ⚠️ | ⚠️ | | | | | ⚠️ | |

🔴 = kích hoạt rõ · ⚠️ = cảnh báo/một phần · (trống) = không kích hoạt

**VIC kích hoạt phủ quyết** (博傻 + FCF nhóm âm). **SSI, VHM ở vùng xám** vì cảnh báo hào/quản trị.

---

# PHẦN III — BẢNG SO SÁNH TỔNG QUAN

| Mã | Qua Checklist? | Năng lực | Good biz | Hào | Lãnh đạo | An toàn | P/E | Kết luận cốt lõi |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|---|
| **FPT** | ✅ Qua (5/5) | ★★★★☆ | ★★★★☆ | ★★★★☆ | ★★★★☆ | ★★★★☆ | 13.3x | Chất lượng cao nhất, định giá hấp dẫn. Canh AI + room ngoại. |
| **ACB** | ✅ Qua | ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★★★★☆ | ★★★★☆ | 7.6x | NH chất lượng + rẻ nhất. Canh NIM nén. |
| **CTG** | ✅ Qua | ★★★★☆ | ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★★★★☆ | 8.0x | Rẻ + đà cải thiện mạnh nhất SOE. Canh CAR. |
| **TCB** | ✅ Qua | ★★★★☆ | ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★★★★☆ | 9.1x | CASA mạnh nhất + rẻ. Canh BĐS + sở hữu gia đình. |
| **VCB** | ✅ Qua (đắt) | ★★★★☆ | ★★★★☆ | ★★★★☆ | ★★★☆☆ | ★★★☆☆ | 15.7x | NH tốt nhất VN nhưng giá premium, ít biên an toàn. |
| **VHM** | ❓ Xám | ★★★☆☆ | ★★★☆☆ | ★★★☆☆ | ★★☆☆☆ | ★★★☆☆ | 10.3x | BĐS biên cao, quỹ đất #1; nhưng phụ thuộc mẹ Vingroup. |
| **SSI** | ❓ Xám (nghiêng ❌) | ★★★☆☆ | ★★☆☆☆ | ★★☆☆☆ | ★★★☆☆ | ★★☆☆☆ | 12.9x | Môi giới #1 nhưng hào nông, chu kỳ, mua ở đỉnh LN. |
| **VIC** | ❌ Không qua | ★★☆☆☆ | ★★☆☆☆ | ★★★☆☆ | ★★☆☆☆ | ★☆☆☆☆ | 156x | VinFast going-concern + đòn bẩy cao + P/E đầu cơ. |

**Xếp hạng theo tiêu chí Buffett (chất lượng × giá):**
1. **FPT** — chất lượng cao nhất + giá hợp lý (ứng viên số 1 nghiên cứu sâu)
2. **ACB / CTG / TCB** — bộ ba ngân hàng vừa tốt vừa rẻ (P/E 7.6–9.1x)
3. **VCB** — chất lượng nhất nhưng đợi giá tốt hơn
4. **VHM / SSI** — vùng xám, cần xác minh thêm trước khi quyết
5. **VIC** — loại theo tiêu chí giá trị (canh bạc đầu cơ)

---

# KẾT NGỮ

> "Giá là cái bạn trả, giá trị là cái bạn nhận." — Warren Buffett
> "Thà bỏ lỡ còn hơn làm sai." — nguyên tắc Checklist

Trong 8 mã: **5 ngân hàng/công nghệ qua Checklist** (FPT + 4 ngân hàng), với FPT nổi bật về chất lượng và bộ ba ACB/CTG/TCB hấp dẫn về định giá (P/E 7.6–9.1x). **VCB** xuất sắc nhưng đắt. **VHM và SSI** ở vùng xám — không phải vì xấu, mà vì câu hỏi cốt lõi (phụ thuộc công ty mẹ / chu kỳ + không hào) chưa được giải đáp bằng dữ liệu công khai. **VIC** bị loại theo kỷ luật giá trị: dù đà lợi nhuận và cổ phiếu rất mạnh, P/E 156x + VinFast going-concern + đòn bẩy cao là canh bạc đầu cơ, không phải đầu tư giá trị.

**Lưu ý chung cho cả 8 mã:**
- Toàn bộ định giá biến động — **kiểm tra bảng giá trực tiếp** trước khi hành động.
- EPS dùng tính P/E phần lớn là **ước tính/dẫn xuất** — đối chiếu BCTC kiểm toán.
- 4 ngân hàng đều đang **nén NIM** (xu hướng toàn ngành 2025–26) — đây là rủi ro chung.
- Checklist này chỉ là **bước sàng lọc loại bỏ**, không phải khuyến nghị mua. Các mã "qua" cần nghiên cứu sâu (`/investment-research` hoặc `/investment-team`) trước khi quyết định.

> *Báo cáo dựa trên dữ liệu thứ cấp thu thập ngày 2026-06-29. Lợi nhuận quá khứ không đại diện tương lai. Đây không phải khuyến nghị đầu tư.*
