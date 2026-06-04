Paper 17 — Machine Learning-Enhanced Requirements Engineering: A Systematic Literature Review (2024)

Bài báo này tổng hợp các nghiên cứu về việc sử dụng Machine Learning (ML) và Natural Language Processing (NLP) trong Requirements Engineering (RE). Mục tiêu chính là tìm hiểu cách AI có thể hỗ trợ xử lý requirement trong phát triển phần mềm.

Tác giả thu thập hơn 1,219 bài nghiên cứu từ các nguồn lớn như IEEE, ACM, Scopus và Web of Science, sau đó lọc còn 74 bài chất lượng cao trong giai đoạn 2012–06/2023 để phân tích.

Nội dung chính của bài báo tập trung vào các hoạt động quan trọng trong Requirements Engineering như:

-Requirement elicitation (khai thác requirement)
-Requirement extraction (trích xuất requirement)
-Requirement classification (phân loại requirement)
-Requirement validation (kiểm tra requirement)
-Requirement prioritization (ưu tiên requirement)

Hướng nghiên cứu phổ biến nhất là requirement classification. Machine Learning được dùng để phân loại:

-Functional Requirement (FR)
-Non-Functional Requirement (NFR)
-Security Requirement
-Performance Requirement

Các thuật toán thường được sử dụng gồm:

-SVM
-Random Forest
-Naive Bayes
-Decision Tree
-Deep Learning
-BERT và Transformer

Một nội dung rất quan trọng trong bài là Requirement Smell Detection và Ambiguity Detection. AI được dùng để phát hiện các requirement:

-mơ hồ,
-thiếu thông tin,
-khó kiểm thử,
-hoặc chứa từ ngữ không rõ nghĩa như “fast”, “efficient”, “user-friendly”.

Ví dụ:

“The system should be fast.”

AI sẽ nhận ra rằng requirement này không có tiêu chí đo lường cụ thể nên khó kiểm thử.

Bài báo cũng cho thấy NLP đóng vai trò cốt lõi trong lĩnh vực này vì requirement thường được viết bằng ngôn ngữ tự nhiên. Các kỹ thuật phổ biến gồm:

-Tokenization
-POS Tagging
-Semantic Similarity
-Word Embedding
-BERT
-Transformer

Kết quả nghiên cứu cho thấy sau năm 2018, số lượng nghiên cứu kết hợp AI và Requirements Engineering tăng rất mạnh nhờ sự phát triển của Deep Learning và Transformer.

Ngoài ra, bài báo cũng chỉ ra một số hạn chế lớn:

thiếu dataset requirement công khai,
thiếu benchmark chuẩn,
nhiều nghiên cứu chỉ thử nghiệm trong môi trường nhỏ,
chưa được áp dụng rộng rãi trong thực tế doanh nghiệp.

Tổng kết lại, bài báo cho thấy Machine Learning và NLP đang trở thành công nghệ quan trọng trong Requirements Engineering, đặc biệt trong các bài toán:

-requirement classification,
-ambiguity detection,
-smell detection,
-validation,
-use case generation.

Đây là bài nền tảng rất phù hợp cho sinh viên làm đề tài AI + Requirements Engineering.

Paper 16 — Large Language Models (LLMs) for Requirements Engineering (2025)

Bài báo này khảo sát việc ứng dụng Large Language Models (LLMs) như:

ChatGPT,
GPT-based models,
Llama

trong Requirements Engineering.

Khác với paper trước tập trung vào Machine Learning truyền thống, bài này tập trung vào Generative AI và các mô hình ngôn ngữ lớn hiện đại.

Tác giả phân tích 74 nghiên cứu chính trong giai đoạn 2023–2024, tức giai đoạn AI phát triển rất mạnh sau khi ChatGPT xuất hiện.

Bài báo cho thấy LLM đang được dùng trong nhiều hoạt động của Requirements Engineering như:

-Requirement elicitation
-Requirement classification
-Requirement validation
-Defect detection
-Use case generation
-Test case generation

Một ứng dụng nổi bật là Requirement Classification. LLM có thể phân loại:

-Functional Requirement
-Non-Functional Requirement
-Security Requirement

Điểm mạnh của LLM là:

-không cần nhiều dữ liệu train,
-có khả năng zero-shot,
-hiểu ngữ cảnh tốt hơn traditional ML.

Ngoài ra, LLM còn được dùng để phát hiện lỗi requirement và requirement mơ hồ.

Ví dụ:

“The system should be fast.”

LLM có thể giải thích rằng:

requirement thiếu số liệu cụ thể,
không có tiêu chí đo lường,
khó kiểm thử.

Một hướng nghiên cứu rất nổi bật khác là Use Case Generation và Test Case Generation. LLM có khả năng tự động sinh:

-use case,
-user story,
-acceptance criteria,
-test scenario,
-test case.

Ví dụ:
Requirement:

“User đăng nhập bằng Google.”

LLM có thể sinh:

-use case flow,
-success flow,
-exception flow,
-test case tương ứng.

Bài báo cũng nhấn mạnh Prompt Engineering là yếu tố cực kỳ quan trọng khi sử dụng LLM.

Các kỹ thuật prompting phổ biến gồm:

-Zero-shot Prompting
-Few-shot Prompting
-Chain-of-Thought Prompting

Few-shot prompting thường cho kết quả tốt hơn trong:

-requirement classification,
-ambiguity detection,
-validation.

Tuy nhiên, bài báo cũng chỉ ra nhiều hạn chế:

-kết quả phụ thuộc vào prompt,
-thiếu benchmark chuẩn,
-khó đánh giá giữa các nghiên cứu,
-LLM chưa đủ ổn định để thay thế hoàn toàn analyst.

Do đó, Human-in-the-loop vẫn rất cần thiết để:

-review,
-validation,
-refinement requirement.

Tổng kết lại, bài báo cho thấy LLM đang mở ra hướng phát triển mới cho Requirements Engineering. AI không chỉ hỗ trợ phân loại requirement mà còn có thể:

-phát hiện lỗi,
-kiểm tra requirement,
-sinh use case,
-sinh test case,
hỗ trợ analyst trong toàn bộ quy trình phát triển phần mềm.
