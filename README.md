# Đồ án tốt nghiệp.
## Phân tích yêu cầu người dùng
### chủ đề: Game âm nhạc nhịp điệu
#### phân tích yêu cầu người dùng
- **Đối tượng:** Tất cả mọi người, đặc biệt là người chơi nhịp điệu thử thách giới hạn độ khó
- Mục tiêu:
	- Tập trung vào độ chính xác và đồng bộ trong game nhịp điệu, cũng như tăng trải nghiệm người dùng và thử thách độ khó cao
	- cốt truyện tối giản
	- quản lí thông tin và thành tựu cơ bản 
#### Cơ chế gameplay

- **cài đặt** :
	- Tăng giảm âm lượng 
	- tắt bật xử lý hậu kỳ ( hiệu năng )
	- tăng giảm tốc độ cuộn cho note
- **độ khó màn chơi**
	- thay đổi độ khó
	- quy định cập độ mỗi màn chơi
	- ( nâng cao ) thêm độ khó đặc biệt
- **màn chơi**
	- thiết kế khu vực chơi
	- quy định note
		- vị trí note
		- di chuyển note
		- xử lý phản hổi khi chạm
		- quy định các thể loại note 
			- note chạm ( tap )
			- note giữ ( hold )
			- note trượt ( trace )
			- note vuốt ( flick )
	- xử lý con trỏ ( touch input handle )
	- hiển thị thống số:
		- điểm số
		- độ khó
			- tên độ khó
			- tên màn chơi
		- thêm nút tạm dừng màn chơi
			- ( nâng cao ) thêm nút khởi động lại màn chơi
- **Âm nhạc, độ khó**
	- các thể loại nhạc: jpop,tech,hardcore,....
	- xử lý âm thanh
		- sử dùng Fmod để quản lý tài nguyên và âm thanh
	- thông tin độ khó
		- tên nhạc
		- nghệ sĩ sáng tác 
		- người thiết kế độ khó
		- hoạ sĩ ảnh bìa ( thumbnail )
	- nhập độ khó từ 1 file bên ngoài
	- đồng bộ nhạc và độ khó  theo mili giây (ms)
	- ( nâng cao )xử lý hậu kỳ 