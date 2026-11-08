# Các tài liệu tham khảo

## Mục lục chủ đề

Dưới mỗi chủ đề là bảng các paper liên quan, gồm STT, tên paper, năm, chủ đề khác mà bài cũng thuộc và trích dẫn đầy đủ. Một paper có thể thuộc nhiều nhóm và được lặp lại trong bảng của tất cả các nhóm liên quan.

| Chủ đề | Số bài trong danh mục chính | STT | Cần kiểm tra thêm |
|---|---:|---|---|
| [Xe tự hành](#xe-tự-hành) | 1 | 2 | — |
| [Xử lý tín hiệu](#xử-lý-tín-hiệu) | 18 | 5, 7, 10, 11, 12, 13, 14, 15, 16, 17, 20, 23, 24, 26, 28, 31, 32, 33 | — |
| [Xử lý ảnh](#xử-lý-ảnh) | 12 | 4, 6, 7, 8, 9, 11, 16, 19, 20, 23, 25, 26 | 34 |
| [IoT](#iot) | 12 | 1, 3, 7, 13, 14, 15, 16, 17, 21, 27, 28, 29 | — |
| [Năng lượng tái tạo](#năng-lượng-tái-tạo) | 2 | 1, 21 | — |
| [Điều khiển và robot](#điều-khiển-và-robot) (bổ sung) | 4 | 18, 22, 24, 30 | — |
| [Giáo dục](#giáo-dục) (bổ sung) | 0 | — | 35 |

Số bài ở các nhóm có chồng lặp nên không cộng lại để suy ra số công bố. Danh mục chính gồm 33 bài; mục 34–35 cần kiểm tra thông tin thư mục trước khi trích dẫn chính thức.

## Xe tự hành

**1 bài.** Xe/robot di động có điều hướng tự động. Bài 2 được xếp vào đây theo nội dung LiDAR-SLAM và điều hướng; không gắn nhãn xử lý ảnh chỉ vì có LiDAR. Bài điều khiển đèn giao thông (bài 9) không xếp vào nhóm này mà thuộc xử lý ảnh trong giao thông thông minh. Bài 27 dùng cảm biến di động Zigbee nhưng chưa có đủ căn cứ để coi điều hướng tự hành là nội dung nghiên cứu, nên chỉ thuộc IoT.

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 2 | [Thiết kế và chế tạo xe tự hành dẫn hướng ứng dụng LiDAR-SLAM cho điều hướng tự động trong nhà](https://doi.org/10.34238/tnu-jst.15495) | 2026 | — | Bùi Văn Huy, Phạm Văn Nam, Vũ Thị Yến, and Hoàng Văn Thắm, “Thiết kế và chế tạo xe tự hành dẫn hướng ứng dụng LiDAR-SLAM cho điều hướng tự động trong nhà,” *TNU Journal of Science and Technology*, vol. 231, no. 10, pp. 406–412, Jun. 2026, doi: 10.34238/tnu-jst.15495. |

## Xử lý tín hiệu

**18 bài.** Thu nhận, lọc, phân tích, trích xuất đặc trưng hoặc nhận dạng từ tín hiệu rung, ECG, EMG.

### Tín hiệu rung – chẩn đoán lỗi động cơ, ổ bi, máy biến áp

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 5 | [Multi-Modal Attention Fusion Network for Marine Diesel Engine Fault Diagnosis with Limited Single-Sensor Vibration Data](https://doi.org/10.1109/RIVF68649.2025.11365206) | 2025 | — | Duc-Thanh Nguyen, Hoai-Linh Tran, Thi-Hang Tran, and Van-Nam Pham, “Multi-Modal Attention Fusion Network for Marine Diesel Engine Fault Diagnosis with Limited Single-Sensor Vibration Data,” in *2025 RIVF International Conference on Computing and Communication Technologies (RIVF)*, pp. 25–30, Dec. 2025, doi: 10.1109/RIVF68649.2025.11365206. |
| 7 | [A Novel Deep Learning Framework for Predictive Fault Diagnosis in Dry-Type Transformers Using Vibration Signal Data Analysis Technique](https://doi.org/10.18280/jesa.581013) | 2025 | [Xử lý ảnh](#xử-lý-ảnh), [IoT](#iot) | Trong-Chuong Trinh, Van-Nam Pham, and Ngoc-Khoat Nguyen, “A Novel Deep Learning Framework for Predictive Fault Diagnosis in Dry-Type Transformers Using Vibration Signal Data Analysis Technique,” *Journal Européen des Systèmes Automatisés*, vol. 58, no. 10, pp. 2133–2142, Oct. 2025, doi: 10.18280/jesa.581013. |
| 10 | [Multi-domain feature-based early detection of bearing faults using MLP classifier on NASA IMS dataset](https://doi.org/10.54939/1859-1043.j.mst.106.2025.48-54) | 2025 | — | Pham Van Nam, Nguyen Vu Thang, Trinh Trong Chuong, and Tran Thi Hang, “Multi-domain feature-based early detection of bearing faults using MLP classifier on NASA IMS dataset,” *J. Mil. Sci. Technol.*, vol. 106, no. 106, pp. 48–54, Oct. 2025, doi: 10.54939/1859-1043.j.mst.106.2025.48-54. |
| 11 | [Application of Artificial Intelligence (AI) Networks in Diagnosing Electrical Motor Faults](https://doi.org/10.1007/978-3-032-00267-9_21) | 2025 | [Xử lý ảnh](#xử-lý-ảnh) | Vu-Thang Nguyen, Trong-Chuong Trinh, Alberto Ernesto Coboi, Duy-Duong Do, and Van-Nam Pham, “Application of Artificial Intelligence (AI) Networks in Diagnosing Electrical Motor Faults,” in *Advances in Data Science and Optimization of Complex Systems*, Lecture Notes in Networks and Systems, vol. 1569, Springer, pp. 230–238, 2025, doi: 10.1007/978-3-032-00267-9_21. |
| 15 | [An Implementation of IoT System for Collecting Vibration Signals of Ships Engines to Support Engine Failures Detection](https://doi.org/10.1109/ICCE62051.2024.10634686) | 2024 | [IoT](#iot) | Hoai-Linh Tran, Duc-Thanh Nguyen, Quang-Huy Do Ba, and Van-Nam Pham, “An Implementation of IoT System for Collecting Vibration Signals of Ships Engines to Support Engine Failures Detection,” in *2024 Tenth International Conference on Communications and Electronics (ICCE)*, pp. 475–480, 2024, doi: 10.1109/ICCE62051.2024.10634686. |
| 16 | [Áp dụng trí tuệ nhân tạo (AI) và IoT để xây dựng hệ thống giám sát và chẩn đoán lỗi động cơ điện](https://doi.org/10.57001/huih5804.2024.240) | 2024 | [Xử lý ảnh](#xử-lý-ảnh), [IoT](#iot) | Nguyễn Vũ Thắng, Trịnh Trọng Chương, Đỗ Bá Quang Huy, and Phạm Văn Nam, “Áp dụng trí tuệ nhân tạo (AI) và IoT để xây dựng hệ thống giám sát và chẩn đoán lỗi động cơ điện,” *Tạp chí Khoa học và Công nghệ Trường Đại học Công nghiệp Hà Nội*, vol. 60, no. 7, pp. 68–75, Jul. 2024, doi: 10.57001/huih5804.2024.240. |
| 20 | [Diagnosing Electric Motor Faults based on Vibration Signals Using YOLOv8](https://doi.org/10.1109/ICDV61346.2024.10617366) | 2024 | [Xử lý ảnh](#xử-lý-ảnh) | Hoai-Linh Tran, Van-Nam Pham, Duc-Thanh Nguyen, Quang-Huy Do Ba, Xuan-Hai Le, and Dinh-Thai Kim, “Diagnosing Electric Motor Faults based on Vibration Signals Using YOLOv8,” in *2024 9th International Conference on Integrated Circuits, Design, and Verification (ICDV)*, pp. 191–196, Jun. 2024, doi: 10.1109/ICDV61346.2024.10617366. |
| 23 | [Application of neural networks in diagnosing engine faults based on vibration signals](https://doi.org/10.54939/1859-1043.j.mst.94.2024.22-30) | 2024 | [Xử lý ảnh](#xử-lý-ảnh) | Nguyen Duc Thanh, Tran Hoai Linh, Nguyen Cong Phuong, and Pham Van Nam, “Application of neural networks in diagnosing engine faults based on vibration signals,” *J. Mil. Sci. Technol.*, vol. 94, no. 94, pp. 22–30, 2024, doi: 10.54939/1859-1043.j.mst.94.2024.22-30. |
| 26 | [Using Artificial Intelligence (AI) for Monitoring and Diagnosing Electric Motor Faults Based on Vibration Signals](https://doi.org/10.1109/ICOIN59985.2024.10572186) | 2024 | [Xử lý ảnh](#xử-lý-ảnh) | Van-Nam Pham, Quang-Huy Do Ba, Duc-Anh Tran Le, Quang-Minh Nguyen, Thanh-Lam Bui, and Alberto Ernesto Coboi, “Using Artificial Intelligence (AI) for Monitoring and Diagnosing Electric Motor Faults Based on Vibration Signals,” in *2024 International Conference on Information Networking (ICOIN)*, pp. 720–725, Jan. 2024, doi: 10.1109/ICOIN59985.2024.10572186. |

### Điện tim (ECG) và bệnh tim mạch

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 12 | [Cardiovascular Disorders Recognition Through Signal Processing Using Hybrid Conventional CNN Architecture](https://doi.org/10.1007/978-3-032-00267-9_20) | 2025 | — | Van-Thanh Nguyen, Danh-Minh Le, Van-Nam Pham, Xuan-Thinh Cao, Tien-Nhat Tien, and Ngoc-Linh Nguyen, “Cardiovascular Disorders Recognition Through Signal Processing Using Hybrid Conventional CNN Architecture,” in *Advances in Data Science and Optimization of Complex Systems*, Lecture Notes in Networks and Systems, vol. 1569, Springer, pp. 220–229, 2025, doi: 10.1007/978-3-032-00267-9_20. |
| 13 | [Designing an ECG signal measurement and analysis system using SVM algorithm for arrhythmia classification](https://doi.org/10.54939/1859-1043.j.mst.105.2025.36-43) | 2025 | [IoT](#iot) | Pham Van Nam, Nguyen Thu Ha, Pham Van Hung, Pham Van Minh, and Tran Thi Hang, “Designing an ECG signal measurement and analysis system using SVM algorithm for arrhythmia classification,” *J. Mil. Sci. Technol.*, vol. 105, no. 105, pp. 36–43, Aug. 2025, doi: 10.54939/1859-1043.j.mst.105.2025.36-43. |
| 14 | [Design of ECG Circuit and Patient Remote Monitoring System Using MQTT Protocol for ECG Signals](https://doi.org/10.56557/jobari/2024/v30i48836) | 2024 | [IoT](#iot) | Van-Nam Pham, Alberto Coboi, Do Dinh Nam, Lai Gia Vien, and Pham Duy Thai, “Design of ECG Circuit and Patient Remote Monitoring System Using MQTT Protocol for ECG Signals,” *Journal of Basic and Applied Research International*, vol. 30, no. 4, pp. 32–42, Sep. 2024, doi: 10.56557/jobari/2024/v30i48836. |
| 17 | [Patient Remote Monitoring System Using MQTT Protocol for ECG Signals](https://doi.org/10.1109/ICDV61346.2024.10617252) | 2024 | [IoT](#iot) | Duc-Anh Tran Le, Ba-Thong Vo, Van-Nam Pham, Quang-Huy Do Ba, Thi-Nga Nguyen, Manh-Hung Ha, and Dinh-Thai Kim, “Patient Remote Monitoring System Using MQTT Protocol for ECG Signals,” in *2024 9th International Conference on Integrated Circuits, Design, and Verification (ICDV)*, pp. 114–118, Jun. 2024, doi: 10.1109/ICDV61346.2024.10617252. |
| 28 | [Electrocardiogram (ECG) Circuit Design and Using the Random Forest to ECG Arrhythmia Classification](https://doi.org/10.1007/978-3-031-22200-9_54) | 2023 | [IoT](#iot) | Van Nam Pham and Hoai Linh Tran, “Electrocardiogram (ECG) Circuit Design and Using the Random Forest to ECG Arrhythmia Classification,” in *Advances in Engineering Research and Application*, Lecture Notes in Networks and Systems, vol. 602, Springer, pp. 477–494, 2023, doi: 10.1007/978-3-031-22200-9_54. |
| 31 | [Ứng dụng cây quyết định cho giải pháp nâng cao chất lượng nhận dạng tín hiệu điện tim](https://jst.tnu.edu.vn/jst/article/view/1074) | 2017 | — | Phạm Văn Nam, Nguyễn Thị Lan Hương, and Trần Hoài Linh, “Ứng dụng cây quyết định cho giải pháp nâng cao chất lượng nhận dạng tín hiệu điện tim,” *Tạp chí Khoa học và Công nghệ – Đại học Thái Nguyên*, vol. 169, no. 9, pp. 81–87, 2017. |
| 32 | [A hardware implementation of intelligent ECG classifier](https://doi.org/10.1108/COMPEL-05-2014-0119) | 2015 | — | Hoai Linh Tran, Van Nam Pham, and Duc Thao Nguyen, “A hardware implementation of intelligent ECG classifier,” *COMPEL: The International Journal for Computation and Mathematics in Electrical and Electronic Engineering*, vol. 34, no. 3, pp. 905–919, 2015, doi: 10.1108/COMPEL-05-2014-0119. |
| 33 | [Multiple neural network integration using a binary decision tree to improve the ECG signal recognition accuracy](https://doi.org/10.2478/amcs-2014-0047) | 2014 | — | Hoai Linh Tran, Van Nam Pham, and Hoang Nam Vuong, “Multiple neural network integration using a binary decision tree to improve the ECG signal recognition accuracy,” *International Journal of Applied Mathematics and Computer Science*, vol. 24, no. 3, pp. 647–655, Sep. 2014, doi: 10.2478/amcs-2014-0047. |

### Điện cơ (EMG)

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 24 | [Novel Design of a Robotic Arm Prototype with Complex Movements Based on Surface EMG Signals to Assist Disabilities in Vietnam](https://doi.org/10.14569/IJACSA.2024.0150348) | 2024 | [Điều khiển và robot](#điều-khiển-và-robot) | Ngoc-Khoat Nguyen, Thi-Mai-Phuong Dao, Van-Kien Nguyen, Van-Hung Pham, Van-Minh Pham, and Van-Nam Pham, “Novel Design of a Robotic Arm Prototype with Complex Movements Based on Surface EMG Signals to Assist Disabilities in Vietnam,” *International Journal of Advanced Computer Science and Applications*, vol. 15, no. 3, pp. 473–478, 2024, doi: 10.14569/IJACSA.2024.0150348. |

## Xử lý ảnh

**12 bài + 1 mục cần kiểm tra thêm.** Phân đoạn, phát hiện hoặc phân loại ảnh; bao gồm ảnh phổ/ảnh biểu diễn tín hiệu khi bài thực sự dùng mô hình xử lý ảnh. CNN trên tín hiệu 1D không mặc nhiên thuộc nhóm xử lý ảnh.

### Ảnh y tế

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 4 | [Multi-Modal Brain Tumor Segmentation with ResSE-LKA Enhanced U-Net Architecture](https://doi.org/10.18280/jesa.590223) | 2026 | — | Van-Huy Hoang, Van-Nam Pham, Thanh-Trung Nguyen, and Thi-Hang Tran, “Multi-Modal Brain Tumor Segmentation with ResSE-LKA Enhanced U-Net Architecture,” *Journal Européen des Systèmes Automatisés*, vol. 59, no. 2, pp. 541–549, Feb. 2026, doi: 10.18280/jesa.590223. |
| 6 | [Hybrid CNN-transformer model for accurate and efficient histopathological image classification](https://doi.org/10.57001/huih5804.2025.424) | 2025 | — | Van Huy Hoang, Thanh Trung Nguyen, Thi Hang Tran, and Van Nam Pham, “Hybrid CNN-transformer model for accurate and efficient histopathological image classification,” *HaUI Journal of Science and Technology*, vol. 61, no. 11B, pp. 82–88, Nov. 2025, doi: 10.57001/huih5804.2025.424. |

### Ảnh biểu diễn tín hiệu rung – chẩn đoán lỗi

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 7 | [A Novel Deep Learning Framework for Predictive Fault Diagnosis in Dry-Type Transformers Using Vibration Signal Data Analysis Technique](https://doi.org/10.18280/jesa.581013) | 2025 | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [IoT](#iot) | Trong-Chuong Trinh, Van-Nam Pham, and Ngoc-Khoat Nguyen, “A Novel Deep Learning Framework for Predictive Fault Diagnosis in Dry-Type Transformers Using Vibration Signal Data Analysis Technique,” *Journal Européen des Systèmes Automatisés*, vol. 58, no. 10, pp. 2133–2142, Oct. 2025, doi: 10.18280/jesa.581013. |
| 11 | [Application of Artificial Intelligence (AI) Networks in Diagnosing Electrical Motor Faults](https://doi.org/10.1007/978-3-032-00267-9_21) | 2025 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Vu-Thang Nguyen, Trong-Chuong Trinh, Alberto Ernesto Coboi, Duy-Duong Do, and Van-Nam Pham, “Application of Artificial Intelligence (AI) Networks in Diagnosing Electrical Motor Faults,” in *Advances in Data Science and Optimization of Complex Systems*, Lecture Notes in Networks and Systems, vol. 1569, Springer, pp. 230–238, 2025, doi: 10.1007/978-3-032-00267-9_21. |
| 16 | [Áp dụng trí tuệ nhân tạo (AI) và IoT để xây dựng hệ thống giám sát và chẩn đoán lỗi động cơ điện](https://doi.org/10.57001/huih5804.2024.240) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [IoT](#iot) | Nguyễn Vũ Thắng, Trịnh Trọng Chương, Đỗ Bá Quang Huy, and Phạm Văn Nam, “Áp dụng trí tuệ nhân tạo (AI) và IoT để xây dựng hệ thống giám sát và chẩn đoán lỗi động cơ điện,” *Tạp chí Khoa học và Công nghệ Trường Đại học Công nghiệp Hà Nội*, vol. 60, no. 7, pp. 68–75, Jul. 2024, doi: 10.57001/huih5804.2024.240. |
| 20 | [Diagnosing Electric Motor Faults based on Vibration Signals Using YOLOv8](https://doi.org/10.1109/ICDV61346.2024.10617366) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Hoai-Linh Tran, Van-Nam Pham, Duc-Thanh Nguyen, Quang-Huy Do Ba, Xuan-Hai Le, and Dinh-Thai Kim, “Diagnosing Electric Motor Faults based on Vibration Signals Using YOLOv8,” in *2024 9th International Conference on Integrated Circuits, Design, and Verification (ICDV)*, pp. 191–196, Jun. 2024, doi: 10.1109/ICDV61346.2024.10617366. |
| 23 | [Application of neural networks in diagnosing engine faults based on vibration signals](https://doi.org/10.54939/1859-1043.j.mst.94.2024.22-30) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Nguyen Duc Thanh, Tran Hoai Linh, Nguyen Cong Phuong, and Pham Van Nam, “Application of neural networks in diagnosing engine faults based on vibration signals,” *J. Mil. Sci. Technol.*, vol. 94, no. 94, pp. 22–30, 2024, doi: 10.54939/1859-1043.j.mst.94.2024.22-30. |
| 26 | [Using Artificial Intelligence (AI) for Monitoring and Diagnosing Electric Motor Faults Based on Vibration Signals](https://doi.org/10.1109/ICOIN59985.2024.10572186) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Van-Nam Pham, Quang-Huy Do Ba, Duc-Anh Tran Le, Quang-Minh Nguyen, Thanh-Lam Bui, and Alberto Ernesto Coboi, “Using Artificial Intelligence (AI) for Monitoring and Diagnosing Electric Motor Faults Based on Vibration Signals,” in *2024 International Conference on Information Networking (ICOIN)*, pp. 720–725, Jan. 2024, doi: 10.1109/ICOIN59985.2024.10572186. |

### Kiểm tra, phân loại sản phẩm công nghiệp và nông sản

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 8 | [Research on Designing a Fabric Surface Defect Detection System Using YOLO in Vietnam](https://doi.org/10.14445/22315381/IJETT-V73I10P101) | 2025 | — | Huong Dinh Mai, Nam Pham Van, Huong Pham Thi Quynh, and Hung Pham Van, “Research on Designing a Fabric Surface Defect Detection System Using YOLO in Vietnam,” *International Journal of Engineering Trends and Technology*, vol. 73, no. 10, pp. 1–9, Oct. 2025, doi: 10.14445/22315381/IJETT-V73I10P101. |
| 19 | [Developed a Tomato-Condition Classification System using Image Processing and YOLO Technology](https://doi.org/10.1109/ICDV61346.2024.10616990) | 2024 | — | Quang-Huy Do Ba, Van-Nam Pham, Van-Thanh Nguyen, Quang-Minh Nguyen, Ba-Thong Vo, Manh-Hung Ha, and Dinh-Thai Kim, “Developed a Tomato-Condition Classification System using Image Processing and YOLO Technology,” in *2024 9th International Conference on Integrated Circuits, Design, and Verification (ICDV)*, pp. 108–113, Jun. 2024, doi: 10.1109/ICDV61346.2024.10616990. |
| 25 | [A Low-Cost Deep-Learning-Based System for Grading Cashew Nuts](https://doi.org/10.3390/computers13030071) | 2024 | — | Van-Nam Pham, Quang-Huy Do Ba, Duc-Anh Tran Le, Quang-Minh Nguyen, Dinh Do Van, and Linh Nguyen, “A Low-Cost Deep-Learning-Based System for Grading Cashew Nuts,” *Computers*, vol. 13, no. 3, Art. no. 71, Mar. 2024, doi: 10.3390/computers13030071. |
| 34 | [Phát triển hệ thống tự động nhận dạng và phân loại chất lượng hạt điều sử dụng mô hình học sâu YOLO tối ưu hóa tài nguyên](https://www.researchgate.net/publication/417205696_Phat_trien_he_thong_tu_dong_nhan_dang_va_phan_loai_chat_luong_hat_dieu_su_dung_mo_hinh_hoc_sau_YOLO_toi_uu_hoa_tai_nguyen) *(cần kiểm tra thêm)* | 2026 | — | *Chưa có trích dẫn chính thức.* Hội thảo “Ứng dụng Công nghệ cao vào thực tiễn”, 2026. Chương trình liệt kê Phạm Văn Nam, Nguyễn Tuấn Anh, Trần Thị Hằng, Chu Nguyễn Thành Quân và Trương Đức Thắng. Nguồn tác giả cung cấp có chương trình và tóm tắt; chưa xác minh đây là bài toàn văn trong kỷ yếu hay chỉ tóm tắt hội thảo, cũng như khoảng trang của bài toàn văn. |

### Giao thông thông minh

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 9 | [Adaptive Traffic Light Control Using YOLOv10 and DeepSort: A Vision-Based Approach for Smart Cities](https://doi.org/10.1109/ATC67618.2025.11268737) | 2025 | — | Thai Dinh Kim, Quang-Anh Nguyen-Duc, Thu-Hien Nguyen Thi, Thi-Nguyen Nguyen, and Van-Nam Pham, “Adaptive Traffic Light Control Using YOLOv10 and DeepSort: A Vision-Based Approach for Smart Cities,” in *2025 International Conference on Advanced Technologies for Communications (ATC)*, pp. 1–6, Oct. 2025, doi: 10.1109/ATC67618.2025.11268737. |


## IoT

**12 bài.** Mạng cảm biến, truyền dữ liệu không dây, giám sát từ xa hoặc kiến trúc hệ thống IoT được nghiên cứu/đề xuất trong bài. Việc chỉ nhắc IoT ở phần bối cảnh chưa đủ để gắn nhãn.

### Mạng cảm biến không dây, LoRa, Zigbee

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 1 | [Design and implementation of a LoRa-enabled IoT system for photovoltaic monitoring and machine learning-based power estimation](https://doi.org/10.54939/1859-1043.j.mst.114.2026.12-21) | 2026 | [Năng lượng tái tạo](#năng-lượng-tái-tạo) | Pham Van Nam, Tran Van Duy, Alberto Coboi, Trinh Trong Chuong, Ninh Van Nam, Quach Duc Cuong, and Bui Van Huy, “Design and implementation of a LoRa-enabled IoT system for photovoltaic monitoring and machine learning-based power estimation,” *J. Mil. Sci. Technol.*, vol. 114, no. 114, pp. 12–21, Oct. 2026, doi: 10.54939/1859-1043.j.mst.114.2026.12-21. |
| 3 | [Application of ARM-Based Integrated Circuits and Wireless Sensor Networks in the Development of a Data-Logging System for Coal and Mineral Plants in Vietnam](https://doi.org/10.18280/jesa.590307) | 2026 | — | Alberto Coboi, Nam Pham Van, and Oraiden Manuel Sabonete, “Application of ARM-Based Integrated Circuits and Wireless Sensor Networks in the Development of a Data-Logging System for Coal and Mineral Plants in Vietnam,” *Journal Européen des Systèmes Automatisés*, vol. 59, no. 3, pp. 631–640, Mar. 2026, doi: 10.18280/jesa.590307. |
| 21 | [Towards Multiple Sources for Energy Harvesting in Wireless Sensor Networks in Practical Applications](https://doi.org/10.37256/cnc.2120244457) | 2024 | [Năng lượng tái tạo](#năng-lượng-tái-tạo) | Alberto Coboi, Minh T. Nguyen, Ildo Zidane Primeiro, Pham Van Nam, Bui Van Huy, Tien Minh Ta, and Thuong TK. Nguyen, “Towards Multiple Sources for Energy Harvesting in Wireless Sensor Networks in Practical Applications,” *Computer Networks and Communications*, vol. 2, no. 1, pp. 123–145, May 2024, doi: 10.37256/cnc.2120244457. |
| 27 | [Zigbee Based Mobile Sensing for Wireless Sensor Networks](https://doi.org/10.37256/cnc.1220233923) | 2023 | — | Alberto Coboi, Minh T. Nguyen, Van Nam Pham, Thang C. Vu, Mui D. Nguyen, and Dung T. Nguyen, “Zigbee Based Mobile Sensing for Wireless Sensor Networks,” *Computer Networks and Communications*, vol. 1, no. 2, pp. 325–342, Dec. 2023, doi: 10.37256/cnc.1220233923. |
| 29 | [Effective LoRa – Based Centralized Digital Water Meters: Real Case Study in Vietnam](https://doi.org/10.14445/22315381/IJETT-V71I2P228) | 2023 | — | Van-Nam Pham and Ngoc-Khoat Nguyen, “Effective LoRa – Based Centralized Digital Water Meters: Real Case Study in Vietnam,” *International Journal of Engineering Trends and Technology*, vol. 71, no. 2, pp. 249–258, Feb. 2023, doi: 10.14445/22315381/IJETT-V71I2P228. |

### Đo và theo dõi ECG từ xa

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 13 | [Designing an ECG signal measurement and analysis system using SVM algorithm for arrhythmia classification](https://doi.org/10.54939/1859-1043.j.mst.105.2025.36-43) | 2025 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Pham Van Nam, Nguyen Thu Ha, Pham Van Hung, Pham Van Minh, and Tran Thi Hang, “Designing an ECG signal measurement and analysis system using SVM algorithm for arrhythmia classification,” *J. Mil. Sci. Technol.*, vol. 105, no. 105, pp. 36–43, Aug. 2025, doi: 10.54939/1859-1043.j.mst.105.2025.36-43. |
| 14 | [Design of ECG Circuit and Patient Remote Monitoring System Using MQTT Protocol for ECG Signals](https://doi.org/10.56557/jobari/2024/v30i48836) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Van-Nam Pham, Alberto Coboi, Do Dinh Nam, Lai Gia Vien, and Pham Duy Thai, “Design of ECG Circuit and Patient Remote Monitoring System Using MQTT Protocol for ECG Signals,” *Journal of Basic and Applied Research International*, vol. 30, no. 4, pp. 32–42, Sep. 2024, doi: 10.56557/jobari/2024/v30i48836. |
| 17 | [Patient Remote Monitoring System Using MQTT Protocol for ECG Signals](https://doi.org/10.1109/ICDV61346.2024.10617252) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Duc-Anh Tran Le, Ba-Thong Vo, Van-Nam Pham, Quang-Huy Do Ba, Thi-Nga Nguyen, Manh-Hung Ha, and Dinh-Thai Kim, “Patient Remote Monitoring System Using MQTT Protocol for ECG Signals,” in *2024 9th International Conference on Integrated Circuits, Design, and Verification (ICDV)*, pp. 114–118, Jun. 2024, doi: 10.1109/ICDV61346.2024.10617252. |
| 28 | [Electrocardiogram (ECG) Circuit Design and Using the Random Forest to ECG Arrhythmia Classification](https://doi.org/10.1007/978-3-031-22200-9_54) | 2023 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Van Nam Pham and Hoai Linh Tran, “Electrocardiogram (ECG) Circuit Design and Using the Random Forest to ECG Arrhythmia Classification,” in *Advances in Engineering Research and Application*, Lecture Notes in Networks and Systems, vol. 602, Springer, pp. 477–494, 2023, doi: 10.1007/978-3-031-22200-9_54. |


### Giám sát rung động máy móc

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 7 | [A Novel Deep Learning Framework for Predictive Fault Diagnosis in Dry-Type Transformers Using Vibration Signal Data Analysis Technique](https://doi.org/10.18280/jesa.581013) | 2025 | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Xử lý ảnh](#xử-lý-ảnh) | Trong-Chuong Trinh, Van-Nam Pham, and Ngoc-Khoat Nguyen, “A Novel Deep Learning Framework for Predictive Fault Diagnosis in Dry-Type Transformers Using Vibration Signal Data Analysis Technique,” *Journal Européen des Systèmes Automatisés*, vol. 58, no. 10, pp. 2133–2142, Oct. 2025, doi: 10.18280/jesa.581013. |
| 15 | [An Implementation of IoT System for Collecting Vibration Signals of Ships Engines to Support Engine Failures Detection](https://doi.org/10.1109/ICCE62051.2024.10634686) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Hoai-Linh Tran, Duc-Thanh Nguyen, Quang-Huy Do Ba, and Van-Nam Pham, “An Implementation of IoT System for Collecting Vibration Signals of Ships Engines to Support Engine Failures Detection,” in *2024 Tenth International Conference on Communications and Electronics (ICCE)*, pp. 475–480, 2024, doi: 10.1109/ICCE62051.2024.10634686. |
| 16 | [Áp dụng trí tuệ nhân tạo (AI) và IoT để xây dựng hệ thống giám sát và chẩn đoán lỗi động cơ điện](https://doi.org/10.57001/huih5804.2024.240) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Xử lý ảnh](#xử-lý-ảnh) | Nguyễn Vũ Thắng, Trịnh Trọng Chương, Đỗ Bá Quang Huy, and Phạm Văn Nam, “Áp dụng trí tuệ nhân tạo (AI) và IoT để xây dựng hệ thống giám sát và chẩn đoán lỗi động cơ điện,” *Tạp chí Khoa học và Công nghệ Trường Đại học Công nghiệp Hà Nội*, vol. 60, no. 7, pp. 68–75, Jul. 2024, doi: 10.57001/huih5804.2024.240. |


## Năng lượng tái tạo

**2 bài.** Hệ PV/năng lượng mặt trời và nội dung thu hoạch năng lượng có liên quan. Bài về động cơ, máy biến áp hoặc nhà máy than không mặc nhiên thuộc nhóm này.

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 1 | [Design and implementation of a LoRa-enabled IoT system for photovoltaic monitoring and machine learning-based power estimation](https://doi.org/10.54939/1859-1043.j.mst.114.2026.12-21) | 2026 | [IoT](#iot) | Pham Van Nam, Tran Van Duy, Alberto Coboi, Trinh Trong Chuong, Ninh Van Nam, Quach Duc Cuong, and Bui Van Huy, “Design and implementation of a LoRa-enabled IoT system for photovoltaic monitoring and machine learning-based power estimation,” *J. Mil. Sci. Technol.*, vol. 114, no. 114, pp. 12–21, Oct. 2026, doi: 10.54939/1859-1043.j.mst.114.2026.12-21. |
| 21 | [Towards Multiple Sources for Energy Harvesting in Wireless Sensor Networks in Practical Applications](https://doi.org/10.37256/cnc.2120244457) | 2024 | [IoT](#iot) | Alberto Coboi, Minh T. Nguyen, Ildo Zidane Primeiro, Pham Van Nam, Bui Van Huy, Tien Minh Ta, and Thuong TK. Nguyen, “Towards Multiple Sources for Energy Harvesting in Wireless Sensor Networks in Practical Applications,” *Computer Networks and Communications*, vol. 2, no. 1, pp. 123–145, May 2024, doi: 10.37256/cnc.2120244457. |


## Điều khiển và robot

**4 bài.** Nhóm bổ sung cho nội dung nằm ngoài năm nhóm được yêu cầu: điều khiển bám quỹ đạo robot, tay máy và hệ cân bằng.

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 18 | [Trajectory Tracking Control of 3-DOF Delta Robot Using Dynamic Surface Control](https://doi.org/10.1109/ICDV61346.2024.10616484) | 2024 | — | Nguyen Van Ninh, Dang Xuan Dang, Nguyen Quang Huy, Pham Van Nam, Luong Hoang Phong, and Nguyen Ngoc Linh, “Trajectory Tracking Control of 3-DOF Delta Robot Using Dynamic Surface Control,” in *2024 9th International Conference on Integrated Circuits, Design, and Verification (ICDV)*, pp. 201–206, Jun. 2024, doi: 10.1109/ICDV61346.2024.10616484. |
| 22 | [An Effective Trajectory Tracking Control Method for Delta Robot Based on Backstepping Sliding Mode Control Techniques](https://doi.org/10.14445/23488379/IJEEE-V11I4P107) | 2024 | — | Hung Pham Van, Xuan Minh Dinh, Minh Pham Van, Nam Pham Van, Hai Le Xuan, and Nam Khanh Nguyen, “An Effective Trajectory Tracking Control Method for Delta Robot Based on Backstepping Sliding Mode Control Techniques,” *International Journal of Electrical and Electronics Engineering*, vol. 11, no. 4, pp. 55–63, Apr. 2024, doi: 10.14445/23488379/IJEEE-V11I4P107. |
| 24 | [Novel Design of a Robotic Arm Prototype with Complex Movements Based on Surface EMG Signals to Assist Disabilities in Vietnam](https://doi.org/10.14569/IJACSA.2024.0150348) | 2024 | [Xử lý tín hiệu](#xử-lý-tín-hiệu) | Ngoc-Khoat Nguyen, Thi-Mai-Phuong Dao, Van-Kien Nguyen, Van-Hung Pham, Van-Minh Pham, and Van-Nam Pham, “Novel Design of a Robotic Arm Prototype with Complex Movements Based on Surface EMG Signals to Assist Disabilities in Vietnam,” *International Journal of Advanced Computer Science and Applications*, vol. 15, no. 3, pp. 473–478, 2024, doi: 10.14569/IJACSA.2024.0150348. |
| 30 | [Designing an Effective Hybrid Control Strategy to Balance a Practical Inverted Pendulum System](https://doi.org/10.14445/22490183/IJETT-V70I5P210) | 2022 | — | Ngoc-Khoat Nguyen, Van-Nam Pham, Tran-Chinh Ho, and Thi-Mai-Phuong Dao, “Designing an Effective Hybrid Control Strategy to Balance a Practical Inverted Pendulum System,” *International Journal of Engineering Trends and Technology*, vol. 70, no. 5, pp. 80–87, May 2022, doi: 10.14445/22490183/IJETT-V70I5P210. |

## Giáo dục

**1 mục cần kiểm tra thêm.** Nhóm bổ sung; chưa có bài nào trong danh mục chính.

| STT | Tên paper | Năm | Cũng thuộc | Trích dẫn theo mẫu |
|---:|---|---:|---|---|
| 35 | [Khuyến khích học tập theo cơ chế dòng chảy cho sinh viên khối công nghệ kỹ thuật trong bối cảnh chuyển đổi số](https://www.researchgate.net/publication/414126938_Khuyen_khich_hoc_tap_theo_co_che_dong_chay_cho_sinh_vien_khoi_cong_nghe_ky_thuat_trong_boi_canh_chuyen_doi_so_Ky_yeu_KHQG_lan_thu_V_nam_2026) *(cần kiểm tra thêm)* | 2026 | — | *Chưa có trích dẫn chính thức.* Hồ sơ tác giả ghi Bui Van Huy, Vu Thi Yen, Ngo Manh Tung và Pham Van Nam; kỷ yếu hội thảo khoa học quốc gia lần thứ V, 2026. Bản PDF bị lỗi trích xuất phông chữ. Cần đối chiếu trực quan tên đầy đủ của kỷ yếu, thứ tự tác giả và trang trước khi dùng trích dẫn chính thức. |

## Tra nhanh theo STT

| STT | Năm | Tên paper | Chủ đề |
|---:|---:|---|---|
| 1 | 2026 | [Design and implementation of a LoRa-enabled IoT system for photovoltaic monitoring and machine learning-based power estimation](https://doi.org/10.54939/1859-1043.j.mst.114.2026.12-21) | [IoT](#iot), [Năng lượng tái tạo](#năng-lượng-tái-tạo) |
| 2 | 2026 | [Thiết kế và chế tạo xe tự hành dẫn hướng ứng dụng LiDAR-SLAM cho điều hướng tự động trong nhà](https://doi.org/10.34238/tnu-jst.15495) | [Xe tự hành](#xe-tự-hành) |
| 3 | 2026 | [Application of ARM-Based Integrated Circuits and Wireless Sensor Networks in the Development of a Data-Logging System for Coal and Mineral Plants in Vietnam](https://doi.org/10.18280/jesa.590307) | [IoT](#iot) |
| 4 | 2026 | [Multi-Modal Brain Tumor Segmentation with ResSE-LKA Enhanced U-Net Architecture](https://doi.org/10.18280/jesa.590223) | [Xử lý ảnh](#xử-lý-ảnh) |
| 5 | 2025 | [Multi-Modal Attention Fusion Network for Marine Diesel Engine Fault Diagnosis with Limited Single-Sensor Vibration Data](https://doi.org/10.1109/RIVF68649.2025.11365206) | [Xử lý tín hiệu](#xử-lý-tín-hiệu) |
| 6 | 2025 | [Hybrid CNN-transformer model for accurate and efficient histopathological image classification](https://doi.org/10.57001/huih5804.2025.424) | [Xử lý ảnh](#xử-lý-ảnh) |
| 7 | 2025 | [A Novel Deep Learning Framework for Predictive Fault Diagnosis in Dry-Type Transformers Using Vibration Signal Data Analysis Technique](https://doi.org/10.18280/jesa.581013) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Xử lý ảnh](#xử-lý-ảnh), [IoT](#iot) |
| 8 | 2025 | [Research on Designing a Fabric Surface Defect Detection System Using YOLO in Vietnam](https://doi.org/10.14445/22315381/IJETT-V73I10P101) | [Xử lý ảnh](#xử-lý-ảnh) |
| 9 | 2025 | [Adaptive Traffic Light Control Using YOLOv10 and DeepSort: A Vision-Based Approach for Smart Cities](https://doi.org/10.1109/ATC67618.2025.11268737) | [Xử lý ảnh](#xử-lý-ảnh) |
| 10 | 2025 | [Multi-domain feature-based early detection of bearing faults using MLP classifier on NASA IMS dataset](https://doi.org/10.54939/1859-1043.j.mst.106.2025.48-54) | [Xử lý tín hiệu](#xử-lý-tín-hiệu) |
| 11 | 2025 | [Application of Artificial Intelligence (AI) Networks in Diagnosing Electrical Motor Faults](https://doi.org/10.1007/978-3-032-00267-9_21) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Xử lý ảnh](#xử-lý-ảnh) |
| 12 | 2025 | [Cardiovascular Disorders Recognition Through Signal Processing Using Hybrid Conventional CNN Architecture](https://doi.org/10.1007/978-3-032-00267-9_20) | [Xử lý tín hiệu](#xử-lý-tín-hiệu) |
| 13 | 2025 | [Designing an ECG signal measurement and analysis system using SVM algorithm for arrhythmia classification](https://doi.org/10.54939/1859-1043.j.mst.105.2025.36-43) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [IoT](#iot) |
| 14 | 2024 | [Design of ECG Circuit and Patient Remote Monitoring System Using MQTT Protocol for ECG Signals](https://doi.org/10.56557/jobari/2024/v30i48836) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [IoT](#iot) |
| 15 | 2024 | [An Implementation of IoT System for Collecting Vibration Signals of Ships Engines to Support Engine Failures Detection](https://doi.org/10.1109/ICCE62051.2024.10634686) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [IoT](#iot) |
| 16 | 2024 | [Áp dụng trí tuệ nhân tạo (AI) và IoT để xây dựng hệ thống giám sát và chẩn đoán lỗi động cơ điện](https://doi.org/10.57001/huih5804.2024.240) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Xử lý ảnh](#xử-lý-ảnh), [IoT](#iot) |
| 17 | 2024 | [Patient Remote Monitoring System Using MQTT Protocol for ECG Signals](https://doi.org/10.1109/ICDV61346.2024.10617252) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [IoT](#iot) |
| 18 | 2024 | [Trajectory Tracking Control of 3-DOF Delta Robot Using Dynamic Surface Control](https://doi.org/10.1109/ICDV61346.2024.10616484) | [Điều khiển và robot](#điều-khiển-và-robot) |
| 19 | 2024 | [Developed a Tomato-Condition Classification System using Image Processing and YOLO Technology](https://doi.org/10.1109/ICDV61346.2024.10616990) | [Xử lý ảnh](#xử-lý-ảnh) |
| 20 | 2024 | [Diagnosing Electric Motor Faults based on Vibration Signals Using YOLOv8](https://doi.org/10.1109/ICDV61346.2024.10617366) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Xử lý ảnh](#xử-lý-ảnh) |
| 21 | 2024 | [Towards Multiple Sources for Energy Harvesting in Wireless Sensor Networks in Practical Applications](https://doi.org/10.37256/cnc.2120244457) | [IoT](#iot), [Năng lượng tái tạo](#năng-lượng-tái-tạo) |
| 22 | 2024 | [An Effective Trajectory Tracking Control Method for Delta Robot Based on Backstepping Sliding Mode Control Techniques](https://doi.org/10.14445/23488379/IJEEE-V11I4P107) | [Điều khiển và robot](#điều-khiển-và-robot) |
| 23 | 2024 | [Application of neural networks in diagnosing engine faults based on vibration signals](https://doi.org/10.54939/1859-1043.j.mst.94.2024.22-30) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Xử lý ảnh](#xử-lý-ảnh) |
| 24 | 2024 | [Novel Design of a Robotic Arm Prototype with Complex Movements Based on Surface EMG Signals to Assist Disabilities in Vietnam](https://doi.org/10.14569/IJACSA.2024.0150348) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Điều khiển và robot](#điều-khiển-và-robot) |
| 25 | 2024 | [A Low-Cost Deep-Learning-Based System for Grading Cashew Nuts](https://doi.org/10.3390/computers13030071) | [Xử lý ảnh](#xử-lý-ảnh) |
| 26 | 2024 | [Using Artificial Intelligence (AI) for Monitoring and Diagnosing Electric Motor Faults Based on Vibration Signals](https://doi.org/10.1109/ICOIN59985.2024.10572186) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [Xử lý ảnh](#xử-lý-ảnh) |
| 27 | 2023 | [Zigbee Based Mobile Sensing for Wireless Sensor Networks](https://doi.org/10.37256/cnc.1220233923) | [IoT](#iot) |
| 28 | 2023 | [Electrocardiogram (ECG) Circuit Design and Using the Random Forest to ECG Arrhythmia Classification](https://doi.org/10.1007/978-3-031-22200-9_54) | [Xử lý tín hiệu](#xử-lý-tín-hiệu), [IoT](#iot) |
| 29 | 2023 | [Effective LoRa – Based Centralized Digital Water Meters: Real Case Study in Vietnam](https://doi.org/10.14445/22315381/IJETT-V71I2P228) | [IoT](#iot) |
| 30 | 2022 | [Designing an Effective Hybrid Control Strategy to Balance a Practical Inverted Pendulum System](https://doi.org/10.14445/22490183/IJETT-V70I5P210) | [Điều khiển và robot](#điều-khiển-và-robot) |
| 31 | 2017 | [Ứng dụng cây quyết định cho giải pháp nâng cao chất lượng nhận dạng tín hiệu điện tim](https://jst.tnu.edu.vn/jst/article/view/1074) | [Xử lý tín hiệu](#xử-lý-tín-hiệu) |
| 32 | 2015 | [A hardware implementation of intelligent ECG classifier](https://doi.org/10.1108/COMPEL-05-2014-0119) | [Xử lý tín hiệu](#xử-lý-tín-hiệu) |
| 33 | 2014 | [Multiple neural network integration using a binary decision tree to improve the ECG signal recognition accuracy](https://doi.org/10.2478/amcs-2014-0047) | [Xử lý tín hiệu](#xử-lý-tín-hiệu) |
| 34 | 2026 | [Phát triển hệ thống tự động nhận dạng và phân loại chất lượng hạt điều sử dụng mô hình học sâu YOLO tối ưu hóa tài nguyên](https://www.researchgate.net/publication/417205696_Phat_trien_he_thong_tu_dong_nhan_dang_va_phan_loai_chat_luong_hat_dieu_su_dung_mo_hinh_hoc_sau_YOLO_toi_uu_hoa_tai_nguyen) *(cần kiểm tra thêm)* | [Xử lý ảnh](#xử-lý-ảnh) |
| 35 | 2026 | [Khuyến khích học tập theo cơ chế dòng chảy cho sinh viên khối công nghệ kỹ thuật trong bối cảnh chuyển đổi số](https://www.researchgate.net/publication/414126938_Khuyen_khich_hoc_tap_theo_co_che_dong_chay_cho_sinh_vien_khoi_cong_nghe_ky_thuat_trong_boi_canh_chuyen_doi_so_Ky_yeu_KHQG_lan_thu_V_nam_2026) *(cần kiểm tra thêm)* | [Giáo dục](#giáo-dục) |
