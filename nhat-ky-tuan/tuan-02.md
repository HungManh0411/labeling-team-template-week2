# Nhật ký tuần NN · 14/09/2026

<!-- Copy file này thành tuan-NN.md mỗi đầu tuần. -->

**Lead tuần này:** Nguyễn Hùng Mạnh (2A202602062) — phần Face_Landmark · Nguyễn Tuấn Khôi (2A202602241)  lead phần HumanPose17
**Dữ liệu / task CVAT:**

## Thành viên và phân công

## Face_Landmark

| Thành viên | Vị trí | Face_Landmark |
|---|---|---|
| Nguyễn Hùng Mạnh (2A202602062) | Lead Face Landmark · Annotator · Reviewer | ửa vị trí điểm có sẵn 2765 và Tự dựng schema 2761  |
| Phạm Hữu Hải (2A202602098)  | Annotator, Reviewer |Sửa vị trí điểm có sẵn 2763 và Tự dựng schema 2759, Review 2758 và 2762    |
| Nguyễn Tuấn Khôi (2A202602241)  | Annotator, Reviewer |Sửa vị trí điểm có sẵn 2762 và Tự dựng schema 2758, Review 2760 và 2763.    |
| Vũ Tiến Thăng (2A202602087) | Annotator, Reviewer | Sửa vị trí điểm có sẵn 2764 và Tự dựng schema 2760, Review 2759 và 2765  |
| Nguyễn Hữu Dũng (2A202602153) | Không hoạt động | Sửa vị trí điểm có sẵn 2765 và Tự dựng schema 2761 -> chuyển sang cho Mạnh  |

## HumanPose17

| Thành viên                     | Vị trí                         | Phân công tuần này                                                          |
| ------------------------------ | ------------------------------ | --------------------------------------------------------------------------- |
| Nguyễn Tuấn Khôi (2A202602241) | Lead Human Pose · Annotator | Điều phối tiến độ; tiếp nhận annotation job 2753 và 2757 từ Nguyễn Hữu Dũng |
| Nguyễn Hữu Hải (2A202602098)   | Annotator · Reviewer           | Gán job 2750, 2754; review job 2751, 2755                                   |
| Vũ Tiến Thăng (2A202602087)    | Annotator · Reviewer           | Gán job 2751, 2755; review job 2752, 2756                                   |
| Nguyễn Hùng Mạnh (2A202602062) | Annotator · Reviewer           | Gán job 2752, 2756; review job 2750, 2754                                   |
| Nguyễn Hữu Dũng (2A202602153)  | Annotator ban đầu              | Job 2753, 2757 chưa bắt đầu; không liên hệ được nên chuyển lại cho lead     |


Tuần này review chéo (tạm thời): không ai review job do chính mình gán. Reviewer của từng job ghi trong bảng Công việc. Reviewer của job 2753, 2757, 2761, 2765 sẽ được phân công sau.

Thay đổi 24/09: Dũng không liên lạc được nên rút khỏi phân công. Job 2765 và 2761 chuyển cho Mạnh gán. Job 2753, 2757 chuyển sang cho Khôi
## Công việc
Mức hoàn thành: ✅ xong **và đã qua review** · 🟡 đang làm (ghi %) · ⛔ bị chặn (ghi lý do) · ⬜ chưa bắt đầu

### Face_Landmark

| # | Nội dung công việc | Annotator | Reviewer | Hoàn thành | Ghi chú |
|---|---|---|---|---|---|
| 1 |job 2758 - 5 frame   |Nguyễn Tuấn Khôi  |Phạm Hữu Hải  | 🟡 Annotation 100% |Đã review và trả lại để sửa  |
| 2 |job 2759 - 5 frame   |Phạm Hữu Hải   |Vũ Tiến Thăng   | 🟡 Annotation 100% |Đã review và trả lại để sửa    |
| 3 |job 2760 - 5 frame   |Vũ Tiến Thăng   |Phạm Hữu Hải   | 🟡 Annotation 100% |Đã review và trả lại để sửa    |
| 4 |job 2761 - 5 frame   |Nguyễn Hữu Dũng -> Nguyễn Hùng Mạnh  | chưa phân công | 🟡 Annotation 100% | không liên lạc được với Dũng nên chuyển sang cho Mạnh, chưa review  |
| 5 |job 2762 - 5 frame   |Nguyễn Tuấn Khôi  |Phạm Hữu Hải  | 🟡 Annotation 100% |Đã review và trả lại để sửa    |
| 6 |job 2763 - 5 frame   |Phạm Hữu Hải   |Nguyễn Tuấn Khôi  | 🟡 Annotation 100% |Đã review và trả lại để sửa    |
| 7 |job 2764 - 5 frame   |Vũ Tiến Thăng  |Nguyễn Tuấn Khôi  | 🟡 Annotation 100% |Đã review và trả lại để sửa   |
| 8 |job 2765 - 5 frame   |Nguyễn Hữu Dũng -> Nguyễn Hùng Mạnh | chưa phân công  | 🟡 Annotation 100% |không liên lạc được với Dũng nên chuyển sang cho Mạnh, chưa review  |

### HumanPose17

|   # | Nội dung công việc      | Annotator                          | Reviewer         | Hoàn thành         | Ghi chú                                                                  |
| --: | ----------------------- | ---------------------------------- | ---------------- | ------------------ | ------------------------------------------------------------------------ |
|   1 | Job 2750 — 5 frame, 2D  | Nguyễn Hữu Hải                     | Nguyễn Hùng Mạnh | 🟡 Annotation 100% | CVAT: `validation new`, assignee reviewer 2A202602062                    |
|   2 | Job 2754 — 10 frame, 2D | Nguyễn Hữu Hải                     | Nguyễn Hùng Mạnh | 🟡 Annotation 100% | CVAT: `validation new`, assignee reviewer 2A202602062                    |
|   3 | Job 2751 — 5 frame, 2D  | Vũ Tiến Thăng                      | Phạm Hữu Hải     | 🟡 Annotation 100% | CVAT: `validation new`, assignee reviewer 2A202602098                    |
|   4 | Job 2755 — 10 frame, 2D | Vũ Tiến Thăng                      | Phạm Hữu Hải     | 🟡 Annotation 100% | CVAT: `validation new`, assignee reviewer 2A202602098                    |
|   5 | Job 2752 — 5 frame, 2D  | Nguyễn Hùng Mạnh                   | Vũ Tiến Thăng    | 🟡 Annotation 100% | CVAT: `validation new`, assignee reviewer 2A202602087                    |
|   6 | Job 2756 — 10 frame, 2D | Nguyễn Hùng Mạnh                   | Vũ Tiến Thăng    | 🟡 Annotation 100% | CVAT: `validation new`, assignee reviewer 2A202602087                    |
|   7 | Job 2753 — 5 frame, 2D  | Nguyễn Hữu Dũng → Nguyễn Tuấn Khôi | Chưa phân công   | ⬜ 0%              | CVAT: `annotation new`; cần đổi assignee từ 2A202602153 sang 2A202602241 |
|   8 | Job 2757 — 10 frame, 2D | Nguyễn Hữu Dũng → Nguyễn Tuấn Khôi | Chưa phân công   | ⬜ 0%              | CVAT: `annotation new`; cần đổi assignee từ 2A202602153 sang 2A202602241 |

Mức hoàn thành: ✅ xong **và đã qua review** · 🟡 đang làm (ghi %) · ⛔ bị chặn (ghi lý do) · ⬜ chưa bắt đầu
## Tiêu chí review Face Landmark

- Mỗi frame có đủ 7 skeleton và 50 điểm; không có bounding box `Face`.
- Trái và phải được xác định theo cách nhìn trên ảnh, không theo giải phẫu của người.
- Point ID giữ liên tục từ 0 đến 49; không reset ID trong từng skeleton.
- Hai mắt, môi ngoài và môi trong là contour kín, không có đường bắt chéo; môi trong nằm hoàn toàn trong môi ngoài.
- Điểm 13 nằm ở chân sống mũi, phía trên lỗ mũi và chưa chạm chóp mũi.
- Mỗi điểm phải được kiểm tra và đặt đúng trạng thái `Visible`, `Occluded` hoặc `Outside`; không giữ trạng thái mặc định của pre-label nếu không phù hợp.
- Điểm bị che nhưng còn suy ra được phải có tọa độ ước lượng hợp lý; không giữ nguyên một pre-label sai vị trí rồi chỉ đánh `Occluded`.
- Không đặt điểm lên gọng kính. Khi mắt hoặc lông mày bị gọng kính che, đặt điểm vào vị trí giải phẫu ước lượng và dùng trạng thái phù hợp.
- Với frame liên tiếp, kiểm tra độ mượt của landmark nhưng không sao chép nguyên annotation từ frame trước.
- Không tự upload annotation lên task vì thao tác này có thể ghi đè dữ liệu hiện có.

## Tiêu chí review Human Pose 17

- Mỗi frame có đúng một skeleton `person` cho người lái, đủ 17 keypoint được đánh số từ 1 đến 17; không gán hành khách nếu mentor chưa yêu cầu.
- Ảnh bị xoay 90°, vì vậy phải xác định hướng đầu và chân trước khi đặt điểm. Quy ước trái/phải vẫn theo khung hình VinFast: R ở bên phải ảnh, L ở bên trái ảnh.
- Không còn keypoint tại tọa độ `(0, 0)` hoặc sát góc trên-trái. Các điểm này phải được xác định lại từ đầu hoặc đánh `Outside` nếu không có đủ căn cứ.
- Vai, khuỷu, cổ tay, hông, gối và cổ chân phải nằm ở tâm khớp; không đặt lên quần áo, vô-lăng, ghế, cần số hoặc bảng táp-lô.
- Mỗi tay và mỗi chân tạo thành chuỗi liền mạch, không bắt chéo sang phía đối diện của thân.
- Không để hai keypoint khác nhau trùng tọa độ khi cả hai đều `Visible`.
- Cả 17 điểm phải có trạng thái đúng: `Visible` nếu nhìn thấy trực tiếp, `Occluded` nếu bị che nhưng còn suy ra được vị trí, và `Outside` nếu ngoài khung hoặc không đủ căn cứ ước lượng.
- Chi dưới bị che hoàn toàn hoặc bị cắt khỏi khung phải đánh `Outside`; không ước lượng gối và cổ chân chỉ dựa trên tỉ lệ cơ thể.
- Nếu toàn bộ skeleton bị lệch có hệ thống, báo mentor thay vì sửa tay hàng loạt.
- Không tự upload annotation lên task vì thao tác này có thể ghi đè dữ liệu hiện có.

## Tổng kết

- Đã gán: Face_Landmark đã fans đủ 70/70
- Qua review lần đầu: Face_Landmark đã review lần 1 và trả lại để sửa. HumanPose17 Chưa có job nào được xác nhận đã qua review tại thời điểm cập nhật. Sáu job đã hoàn thành annotation đang ở trạng thái `validation new`.

- Edge case mới / đã chốt: Chưa ghi nhận edge case Human Pose và Face_Landmark mới trong tuần 2. Nếu gặp tình huống guideline chưa trả lời rõ, annotator mở Issue trên đúng frame và ghi vào `problem-backlog.md` thay vì tự đặt quy ước mới.

### Face_Landmark

| Chỉ số                        | Kết quả tại thời điểm cập nhật            |
| ----------------------------- | ----------------------------------------- |
| Đã gán                        | 70 / 70 frame (100%)                      |
| Đã chuyển sang bước validation | 6 / 8 job (75%)                           |
| Đã xác nhận qua review        | 6 / 8 job (75%)                           |
| Chưa gán                      | 0 / 70 frame (0%)                         |

### HumanPose17
| Chỉ số                         | Kết quả tại thời điểm cập nhật            |
| ------------------------------ | ----------------------------------------- |
| Đã gán                         | 45 / 60 frame (75%)                       |
| Đã chuyển sang bước validation | 6 / 8 job (75%)                           |
| Đã xác nhận qua review         | 0 / 8 job                                 |
| Chưa gán                       | 15 / 60 frame (25%), gồm job 2753 và 2757 |
## Vướng mắc

Chưa liên hệ được 1 thành viên (Nguyễn Hữu Dũng): không có trong nhóm Discord, liên hệ riêng chưa phản hồi, đã báo BTC. Ngày 23/09 đã chuyển job 2761, 2765 cho Mạnh.
Team có 2 lead, mỗi lead chỉ thấy một phần: lead 1 chỉ thấy Face_Landmark, lead 2 chỉ thấy HumanPose17. Khó tổng hợp tiến độ, edge case và quyết định chung của cả đội.
Không liên hệ được Nguyễn Hữu Dũng, làm chậm 15 frame thuộc job 2753 và 2757.
Sáu job đã hoàn thành annotation nhưng chưa có kết quả review, nên chưa thể đánh dấu hoàn tất.
Repo đội `AI20K-Build-Phase-Cohort-4A/P-042` hiện mới có `README.md`; chưa có thư mục nhật ký tuần, problem backlog và sổ quyết định như repo mẫu.

## Kế hoạch tuần sau

- Cập nhật assignee job 2753 và 2757 trên CVAT sang Nguyễn Tuấn Khôi.
- Hoàn thành 15 frame còn lại của job 2753 và 2757 theo guideline HumanPose-17.
- Phân công reviewer chéo cho job 2753 và 2757, 2761 và 2765 sau khi annotation hoàn tất.
- Hoàn thành review 8 job đang ở `validation new`; ghi rõ job nào qua ngay lần đầu và job nào bị trả lại để sửa.
- Rà tối thiểu các trường hợp chi dưới bị khuất, người lái vặn mình, ảnh thiếu sáng và pre-label có nhiều điểm ở `(0, 0)` trước khi chốt chất lượng.
- Đưa file này vào `nhat-ky-tuan/tuan-02.md` trong repo P-042; bổ sung `problem-backlog.md` và `so-quyet-dinh.md` khi phát sinh vấn đề hoặc quyết định mới.
- Chốt cập nhật trước mốc mentor duty 12:00 Chủ nhật 27/09/2026 trên Phoenix.
