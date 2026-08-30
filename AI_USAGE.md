# AI Usage Disclosure — Group [ID]

Tài liệu này ghi log chi tiết việc sử dụng công cụ AI trong course project CO3133 (Semester-261),
theo yêu cầu Section 5 của Course Project Handbook.

## Nếu nhóm KHÔNG dùng AI cho một assignment nào đó

Ghi nguyên văn:

> The group declares that no generative AI tool was used in this assignment.

## Nếu nhóm CÓ dùng AI — mỗi công cụ ghi đầy đủ các trường sau (Section 5.2)

### Assignment [1/2/3] — Entry [số thứ tự]

- **Tool name / version:** [Tên công cụ + version/model nếu biết]
- **Used by:** [Tên thành viên sử dụng]
- **Time / development stage:** [Giai đoạn, ví dụ: M1 Draft / M2 Final...]
- **Purpose:** [Mục đích, ví dụ: literature search / concept explanation /
  architecture or experiment design / coding assistance / debugging /
  test generation / report writing / grammar checks / figure or slide generation / result analysis]
- **Affected assignment section(s):** [Ví dụ: report Sec. 3.2, src/train.py]
- **Representative prompt example or prompt-log link:** [Nội dung prompt tiêu biểu hoặc link log]
- **How AI output was edited and verified:** [Mô tả cách chỉnh sửa và kiểm tra lại]
- **Member responsible for final verification:** [Tên thành viên chịu trách nhiệm]
- **Sources used for verification:** [Docs / papers / tests đã dùng để kiểm chứng]

---

### Ví dụ mẫu (theo Section 5.3 của handbook — điền tương tự cho từng lần dùng thật)

```
Tool: [Tool/model name]
Used by: [Member name]
Task: Debugging the validation loop in train.py
Prompt summary: Asked why validation loss was accumulated incorrectly
AI contribution: Suggested sample-weighted loss accumulation
Student verification: Compared with PyTorch docs; tested on a small controlled set
Affected files/sections: src/train.py; report Sec. 3.2
Responsible member: [Member name]
```

## Lưu ý (Section 5.5)

- Nhóm chịu trách nhiệm hoàn toàn về code, số liệu, hình ảnh, và các phát biểu đã nộp.
- Phải hiểu và giải thích được mọi phần trong bài nộp.
- Không nộp code/text do AI tạo ra mà chưa kiểm tra.
- Không dùng AI để bịa dữ liệu, kết quả thực nghiệm, trích dẫn, tài liệu tham khảo.
- Không khai báo thí nghiệm chưa thực sự chạy.
- Không dán dữ liệu riêng tư/hạn chế/chứa credential vào công cụ AI.
- Nội dung AI hỗ trợ phải được kiểm chứng qua source code, chạy thực tế, tài liệu chính thức, hoặc nguồn học thuật.
- Khai báo thiếu hoặc sai có thể bị coi là vi phạm liêm chính học thuật.
