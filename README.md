# Recursive-Benchmark
Thay api key của bạn ở "YOUR_GEMINI_API_KEY" (chưa hỗ trợ key từ các mô hình ngoài Google).
Nếu bạn muốn tự dùng tập dữ liệu đánh giá của bạn thì đầu tiên hãy tuân thủ 4 trường sau đây cho mỗi bài: id, type, prompt, expected_keyword.
Hiện tại đoạn mã đang được viết cho các bài nêu đáp án trực tiếp, ví dụ: 5 phút, chưa được tinh chỉnh cho các bài câu trả lời là trắc nghiệm a, b, c, d.
Bạn hãy lưu tập đánh giá của bạn bằng dạng jsonl, trong drive của bạn hãy tạo thư mục rsibench_colab_exp và nhét tập dữ liệu jsonl của bạn vào đó.
Nếu chưa biết tạo file jsonl, bạn có thể chạy file này 1 lần để nó tự sinh tập dữ liệu mẫu (eval_set.jsonl và thư mục benchmark và chỉnh sửa file jsonl.
Bạn có thể thay đổi mô hình, hiện tại code đang chạy bằng mô hình gemini 3.6 flash.
