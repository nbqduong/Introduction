## Tham khảo git
	- [Các lệnh cơ bản liên quan đến quản lý nội dung](https://git-scm.com/docs/gittutorial) 
	- [Cách trình bày file Readme](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
## Tạo một repositor mới:
	git init
## Tải 1 repositor về máy
	git clone <link trang web>
## Các bước để đẩy code lên git - Phải cập nhật bản mới nhất thì mới đẩy được code lên, nếu không sẽ gây xung đột
	git add -all|.|<tên file>	thêm các file vào staging area
	git commit -m "mess" 		commit các file
	git push orign main		đẩy code lên
- Hoặc ngắn gọn hơn
	- git commit -a -m "mess"
	- git push
## Chỉnh sửa trong commit
	git commit --amend
## Cập nhật code về máy 
	git pull
## Có thể ghi đè lên trên bản xung đột bằng lệnh (sẽ xóa lịch sử đi, không thể lấy lại, không nên dùng)
	git push --force
## Cập nhật trạng thái của git
	git status
## Hiển thị lịch sử của nhánh hiện tại
	git log | git log --oneline
