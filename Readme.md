## Giới thiệu

Đây là báo cáo của **nhóm 15** cho **Dự án cuối khóa** của môn **Xử lí tiếng nói (2122II_INT3411_20)**. Trong dự án lần này, chúng em xây dựng ứng dụng VIC (Visually Impaired Camera) - ứng dụng sử dụng giọng nói để điều khiển, thực hiện 3 nhiệm vụ chính: chụp ảnh, mô tả ảnh cho người dùng bằng âm thanh, tải ảnh

## Báo cáo

Báo cáo chi tiết được đặt tại link [drive](https://docs.google.com/document/d/1wNBZ-HpxXiAgp-EQt3kjUYkEL1B9ABND8C47AFkYO08/edit?fbclid=IwAR0LlOsvY-Br-sXcXf11TUTfsmBFFbp3kpkxlffGi3QkBuRMGlPDAY-JATo#)

## Thành viên
- Nguyễn Đình Anh Tuấn - 18021362 (Đóng góp: 33,33%)
- Hồ Tuấn Long - 18020810 (Đóng góp: 33,33%)
- Lương Tuấn Dương - 18020403 (Đóng góp: 33,33%)

Nhiệm vụ chi tiết của từng thành viên được trình bày trong báo cáo mục **Phân chia công việc**

## Code
Code bao gồm 3 git repo:
- Repo frontend: https://github.com/TuanAnh081220/speech-app
- Repo backend 1: https://github.com/TuanAnh081220/speech-server
- Repo backend 2: https://github.com/TuanAnh081220/speech-socket

## Dữ liệu

Nhóm đã sử dụng dữ liệu đã thu của lớp cho các khẩu lệnh **a, ban, trai, phai, silent**.
Dữ liệu được đặt tại [drive của nhóm](https://drive.google.com/drive/folders/1mZRwE1U7EJtoJiPAcfQtPOdAp3jtrD4m) bao gồm 3 thư mục chính:
- [train](https://drive.google.com/drive/folders/1uTa82s1p1Oz-5VtOALtk8glOmzXoPux7) [train_2](https://drive.google.com/drive/u/2/folders/1VT4JLsG12vo9C-IW0SnaCkgPUw5gRaw7) - Thư mục chứa dữ liệu huấn luyện cho mô hình CNN. Bao gôm các thư mục con chứa file audio (wav) tương ứng với từng label (a, ban, trai, phai, silent). Số lượng các file wav từ 1000 - 2000 files tuỳ từng label. 
- [test](https://drive.google.com/drive/folders/1gMvdIxOPh4gztdE-bJqhW7tX-g-LqgAt) - Thư mục chứa các audio test không nằm trong 2 thư mục train

## Video demo
Video demo ứng dụng VIC
Link drive: [demo](https://drive.google.com/file/d/11KU6d8uM4rFFe9WY7LIsk4F-DGDHbcDz/view?usp=sharing)

