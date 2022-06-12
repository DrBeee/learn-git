step1: git init
-> khởi tạo repo dưới local

step2: git checkout -b develop
-> tạo nhánh mới có tên là devolop

step3: commit code
-> git add filename -> add từng file 1
-> git add . -> add tất cả các file

-git commit -m "hola"

tạo nhánh mới: git checkout -b

git status

 quay lại branch git checkout

step4: add remote
- git remote add origin https://github.com/DrBeee/learn-git.git

step5: push code
- git push origin

-> làm xong task 


login task 

câu lệnh git cơ bản
-git branch -d tên_nhánh -> xóa 1 nhánh
-git checkout -b tên_nhánh -> tạo mới 1 nhánh và chuyển nhánh luôn
- git branch -> xem tên nhánh
- git checkout -> chuyển nhánh
- git add . -> add nhiều file cùng lúc
- fit add filename -> add 1 file 1
- git push origin tên_nhánh -> đẩy code lên nhánh ( origin là tên remote mà chúng ra đặt)
- git remote add tên_remote link_remote -> thêm mới một remote
- git commit -m "nội dung của message" -> commit code (note: để commit code thì phải add trước)
- git pull origin tên_nhánh -> pull code (kéo code) mới nhất của nhánh đó về local