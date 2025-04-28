# Thiết kế lối chơi
### Gameplay
- TODO: 
	- [ ] input handle 
	- [ ] playfield
	- [ ] note
	- [ ] audio + offset
	- [ ] score + combo
	- [ ] pasue button

### Idea
- hiện tại đang tìm hiều và viết các chức năng cơ bản của audio sử dụng [fmod](https://www.fmod.com/) làm audio library 
- input handle sẽ sử dụng [EnhancedTouch](https://docs.unity3d.com/Packages/com.unity.inputsystem@1.0/api/UnityEngine.InputSystem.EnhancedTouch.html)
- playfield sẽ dùng sprite 2D trên canvas
- note sẽ di chuyển trong môi trường 3D và đi theo hướng Z 
### Issue
- quy định 2D hay 3D cho note
- hạn chế kiến thức về xử lý note 
- xử lý âm thanh và input theo ms


## Nốt (note)
### Ý tưởng
- Note spawner: sẽ là particle và nhiệm vụ chính sẽ là xử lý tốc độ và các thay đổi trong game với các note  ( ví du nhanh chậm có thể là đi lùi) - Nguồn : Arcreate - TapNode Prefab )
	-  Trong Particle có thể spawn note nên có thể dùng 1 gameobject particlespawn để làm visual note spawn, vì đây là rhythm game nên timing có thể ko nằm ở note mà sẽ nằm ở hàm tính toán đâu đó khác....
	- 