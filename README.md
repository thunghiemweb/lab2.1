# Lab 02.1

Nội dung bài tập thực hành:

Hãy làm các bài lab theo link dưới đây và đảm bảo rằng bạn sẽ không xoá repositories cho đến khi kết thúc môn học. Hãy lưu link git (và tên branh, ghi chú nếu có) vào file rồi nộp file lên hệ thống nộp bài trước khi review.

Đặt tên bài lab ở Github theo quy định sau: LAB+number_subnumber. Ví dụ: LAB01_1

Lab (Video): Getting Started with React
https://www.coursera.org/learn/front-end-react/lecture/7Reo7/exercise-video-getting-started-with-react

Lab (tài liệu hướng dẫn): Getting Started with React 
https://www.coursera.org/learn/front-end-react/supplement/lwfpx/exercise-instructions-getting-started-with-react

Lưu ý:
1. Ở thời điểm hiện tại, lời khuyên dành cho bạn là hãy sử dụng npm start, npm install thay vì sử dụng yarn vì đã lỗi thời.
2. Để tránh lỗi xảy ra do phiên bản khác (thường lúc dùng create-react-app sẽ được sử dụng thư viện mới nhất), bạn hãy sử dụng thư viện theo danh sách sau cho toàn bộ các bài lab, project trong môn học này (nếu không có trong danh sách thì bạn có thể sử dụng phiên bản mới nhất của thư viện đó).
Thư viện được mô tả trong file package.json dưới đây hoặc clone về từ repository này:


"dependencies": {

"bootstrap": "4.0.0",
"bootstrap-social": "5.1.1",
"cross-fetch": "2.1.0",
"dateformat": "^4.5.1",
"font-awesome": "4.7.0",
"prop-types": "15.6.0",
"react": "^16.3.2",
"react-animation-components": "3.0.0",
"react-dom": "^16.3.2",
"react-popper": "0.9.2",
"react-redux": "5.0.7",
"react-redux-form": "1.16.8",
"react-router-dom": "4.2.2",
"react-scripts": "1.1.4",
"react-transition-group": "2.3.0",
"reactstrap": "5.0.0",
"redux": "3.7.2",
"redux-logger": "3.0.6",
"redux-thunk": "2.2.0",
"web-vitals": "^1.1.2"

},


3. Nếu bạn cài đặt phiên bản Node.JS 17 trở lên thì hãy clone từ link này, hãy sử dụng các thư viện được mô tả trong file package.json dưới đây, đồng thời bỏ qua bước cài đặt create-react-app vì đã được tích hợp sẵn (nếu đã cài đặt create-react-app@1.5.2 thì hãy upgrade lên phiên bản mới nhất trước khi sử dụng):

"dependencies": {

"bootstrap": "^5.1.3",
"bootstrap-social": "^5.1.1",
"cross-fetch": "^3.1.5",
"dateformat": "^5.0.2",
"font-awesome": "^4.7.0",
"prop-types": "^15.8.1",
"react-popper": "^2.2.5",
"react-redux": "^7.2.6",
"react-redux-form": "^1.16.14",
"react-router-dom": "^6.2.1",
"react-scripts": "^5.0.0",
"react-transition-group": "^4.4.2",
"reactstrap": "^9.0.1",
"redux": "^4.1.2",
"redux-logger": "^3.0.6",
"redux-thunk": "^2.4.1",
"web-vitals": "^2.1.4"

}


Sau đó tham khảo sửa code ở những điểm này: (những thay đổi này đã được thử nghiệm trên lab10.4, ngoại trừ component Jumbotron được thay thế bằng div có class Jumbotron, bạn hãy tự thêm thuộc tính css cho class này để ra được kết quả như bài mẫu trong video).
Thời lượng làm bài dự kiến: 20 phút
