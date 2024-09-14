# Link youtube
https://www.youtube.com/watch?v=QE_mkDiu4hE&t=174s
# Terms
- Repo: kho lưu trữ
- Branch
- Conflict: xung đột, tạo xung đột master, và xung đột ở branch -> merge chọn 1 trong 2 hoặc cả 2
- local
- remote
- clone

# command
- git init: làm folder được đán lệnh thành repogit
- git status: xem trạng thái dự án
- git add: cho phép chuẩn bị lưu lại file
- git reset: lấy file chuẩn bị lưu ra
    * . lấy tất cả file, không thì thêm file cụ thể VD: add/reset index html

- git commit -m '': chính thức lưu

- git log: xem thời điểm commit (người commit, ghi chú, tgian)
    * Thêm --oneline: thu gọn

- git checkout master: trở lại dự án hiện tại
- git checkout <ID>: quay lại thời điểm ID đó được commit
- git checkout <branch>: vào nhánh branch

- git branch: xem branch hiện tại
- git checkout -b <new name branch>: tạo branch mới, set tại điểm đó

- git merge <branch>: set branch master, merge dev
- git branch -d <name branch bị xóa>
- git push link nhánh: đẩy lên remote


#### Thành viên (o phải chủ)
- git clone: clone dự án
    + xóa thư mục github
    + lên mục <> code lấy link https
    + Tạo folder rỗng, cd vào
    + git clone link 
    + gõ 'code .' -> dẫn ra vs code
    + push chỉ cần: git push không cần link 


#### Tạo branch trên local cách đẩy lên Repo
- git checkout -b dev
- git push -u origin dev

#### Lấy branch trên github
- VD: tạo tay branch staging
- git fetch origin
- git checkout -b staging origin/staging: tạo branch có tên staging lấy từ origin/staging
- git add, commit, push bthg

#### merge nhánh con vào master