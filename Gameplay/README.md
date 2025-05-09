# Thiết kế lối chơi
### Gameplay
- TODO: 
	- [ ] input handle 
	- [ ] playfield
	- [ ] note
	- [ ] audio + offset
	- [ ] score + combo
	- [ ] pasue button


## Audio 
- sử dụng Fmod
- lấy từ Fmod Project và file audio (.ogg,.wav,.mp3)
- trả về timing = tổng thời gian của nhạc bằng ms 
- các chức năng cơ bản
	- play/pause: chạy hoặc dừng nhạc 
	- nhảy cóc đến 1 khoảng nào đó trong giới hạn nhạc 
	- start:  chạy từ đầu
- Timing
	- lấy từ audio
	- dùng để tính toán chart timing (audio + offset)
	- dùng đề tính toán chêch lệch giữa note và input người dùng
	- dùng để note drawer tính toán thời gian xuất hiện

## Note Drawer
- Note Drawer (Note Spawner) 
	- Ở trên cùng màn hình
	- tốt độ di chuyển note sẽ tính bằng khoảng cách từ spawner đến jugdement và bpm
	- các chức năng cơ bản
		- update drawer: thay đổi vị trí phụ thuộc vào sự thay đổi của timing ( của audio ) 
- Velocity
	- thay đổi tốc độ rơi của note
	- chưa biết cách hoạt động....



# Tài liệu
- [Arccreate](https://github.com/Arcthesia/ArcCreate)
- [RhythmPlayer của các pháp sư hàn](https://github.com/rulutieh/rhythmplayer/tree/master)