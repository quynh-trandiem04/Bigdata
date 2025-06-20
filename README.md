# Hệ thống Quản lý Dữ liệu Phân tán sử dụng Hadoop Ecosystem

## 🎓 Thông tin đề tài
- **Môn học:** Nhập môn Dữ liệu Lớn  
- **Trường:** Đại học Sư phạm Kỹ thuật TP. HCM  
- **Giảng viên hướng dẫn:** ThS. Lê Thị Minh Châu  
- **Nhóm thực hiện:** Nhóm 9  
- **Lớp:** BDES333877_Nhom1

## 👨‍💻 Thành viên nhóm
- Dương Thành Sơn – 22133048 (Nhóm trưởng)  
- Trần Diễm Quỳnh – 22133046  
- Lê Văn Sang – 22133047  
- Nguyễn Đinh Hồng Phúc – 22133041  

## 📝 Mô tả dự án
Dự án nhằm xây dựng và triển khai một **hệ thống quản lý dữ liệu phân tán** dựa trên **Apache Hadoop** và các thành phần trong hệ sinh thái của nó bao gồm:
- **HBase**: Cơ sở dữ liệu NoSQL phân tán.
- **Zookeeper**: Dịch vụ điều phối hệ thống phân tán.
- **Mahout**: Công cụ học máy để phân tích dữ liệu.
- **Sqoop**: Công cụ chuyển dữ liệu giữa RDBMS và Hadoop.

## 🎯 Mục tiêu chính
- Cài đặt và cấu hình hệ thống Hadoop và các công cụ đi kèm.
- Thu thập, xử lý, phân tích và lưu trữ dữ liệu đánh giá phim từ file `MovieRating.csv`.
- Xây dựng hệ thống gợi ý phim bằng thuật toán **item-based collaborative filtering** với Mahout.

## 🔧 Công nghệ sử dụng
- Hadoop (HDFS, MapReduce, YARN)
- HBase
- Zookeeper
- Mahout
- Sqoop
- MySQL

## 📊 Dữ liệu mẫu
- **File:** `MovieRating.csv`
- **Trường dữ liệu:** CustId, MovieId, Rating

## 🏁 Kết quả nổi bật
- Dữ liệu được nhập thành công từ MySQL vào HDFS thông qua Sqoop.
- Phân tích dữ liệu với Mahout cho kết quả gợi ý chính xác.
- Kết quả gợi ý được lưu trữ vào HBase, sẵn sàng tích hợp vào hệ thống thực tế.

## 📌 Kết luận
Dự án giúp sinh viên hiểu rõ cách xây dựng và vận hành hệ thống dữ liệu lớn phân tán bằng cách ứng dụng các công cụ thực tế trong Hadoop Ecosystem. Qua đó rèn luyện kỹ năng cấu hình hệ thống, xử lý dữ liệu và triển khai thuật toán học máy.

## 📚 Tài liệu tham khảo
- [GeeksforGeeks – Hadoop Ecosystem](https://www.geeksforgeeks.org/hadoop-ecosystem/)
- [Tutorialspoint – Sqoop Installation](https://www.tutorialspoint.com/sqoop/sqoop_installation.htm)
- [StackOverflow – HBase in Multi-node Cluster](https://stackoverflow.com/questions/29397659/hbase-installation-in-three-node-hadoop-cluster)
