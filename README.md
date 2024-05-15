# learn-2d-game 

learn to make 2d game from flappy bird game
![](https://scontent.fsgn5-14.fna.fbcdn.net/v/t1.15752-9/441443157_3614999768738770_2823607306850250601_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFVtDvDuOGHqtXL9PweW6YidOKMQ6ucIAx04oxDq5wgDB8CLCFmeo1NJvu9KXTqktQQDY88uOIoywRfR3X54QU0&_nc_ohc=glnn5Mp79i8Q7kNvgGSPOjb&_nc_ht=scontent.fsgn5-14.fna&oh=03_Q7cD1QG12FE8okybwMxyYavJ5KV8vgqQh1T9x7hulksVkBXNsA&oe=666BF027)

**Những phần mềm để thiết lập tải xuống dự án game này dùng cho mục đích tham khảo hay cho các cộng tác viên**
* [Git](https://git-scm.com/downloads)
* [Tortoise Git](https://tortoisegit.org/download/)
* [Unity](https://unity.com/download)

**Hướng dẫn cài đặt :**
1. Tải xuống `Git, Tortoise Git` dưới bản cập nhật mới nhất và cài đặt theo mặc định của nhà phát triển đề xuất ( không cần thiết phải tùy chỉnh lại ) 
2. Tải xuống `Unity` ( có thể tùy chỉnh gói nhưng sẽ tốn phí, cá nhân tôi dùng personal vì tôi nghèo ) và cài như tương tự
3. Cài đặt bổ sung cho Unity
   ```
   1. Unity Editor ( theo mặc định )
   2. Unity Archive ( theo mặc định )
   3. Modules [ Dev Tools : Microsoft Visual Studio Community ] tích hợp trong Unity Archive
   4. Sau khi cài xong thì Microsoft Visual Studio Community sẽ mở ra 1 cửa sổ, hãy kéo xuống phần Gaming và chọn " Game Development with Unity " (trong phần optional hãy bỏ tick chọn Unity Hub vì đã cài rồi) tiếp tục cài đặt
   ```
>> Sau khi cài đặt xong Visual Studio nó sẽ hiện ra phần sign up không cần thiết phải đăng ký cứ bỏ qua và tắt nó đi

4. Lúc này khi đã cài `Git, Tortoise Git` chúng ta sẽ dùng nó để tạo thư mục ở dưới máy và dẫn dự án ở trên `github` về bằng cách :
   1. Tạo 1 folder tại đường dẫn mà chúng ta muốn lưu dự án và đảm bảo ở bên trong folder đó phải trống
   2. Rồi chúng ta lên lại trên Repository của dự án Github mà ta muốn sử dụng, đứng tại mục code , bấm vào nút Code màu xanh lá rồi ta copy Url to clipboard trong mục local bằng phương thức https

![](https://scontent.fsgn5-8.fna.fbcdn.net/v/t1.15752-9/440880502_463939726100899_4899839131298972889_n.png?_nc_cat=109&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGu4YjF_TmilydQ8ohVyioBvnzkETl0912-fOQROXT3Xeb2GFAx4TYCCqrzwPqYmBtV0mR5Ltob3uo16ilNt1Sb&_nc_ohc=tCoyMyY5iZEQ7kNvgEDl3xK&_nc_ht=scontent.fsgn5-8.fna&oh=03_Q7cD1QGPXEyG8EIjhSkLpenRbrt0ypxj7EBlkGI9ReAKZH2AlA&oe=666BEF60)
  
5. Về lại folder của chúng ta hãy click chuột phải vào vùng trống của folder (chọn Git Clone để mở ra 1 cửa sổ), hãy copy url trên github đó vào phần URL và hãy chắc chắn phần directory đứng đúng thư mục mà bạn muốn lưu và chọn OK

![](https://scontent.fsgn5-9.fna.fbcdn.net/v/t1.15752-9/440888866_974772040816393_2028507364070920349_n.png?_nc_cat=102&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHfiiX4R2tKFBKOdCPKu8j07ThU7bC0LivtOFTtsLQuK-7EVDb0sUey9nvaZmnonlmT4U3c3drZEpiZzL-JF02k&_nc_ohc=-SiXp9eNTAcQ7kNvgGocBUv&_nc_ht=scontent.fsgn5-9.fna&oh=03_Q7cD1QFpZywZkxghIr6-6Scnf2mLSE0T0zN8N6NdUhpORlxe7g&oe=666C00C2)
![](https://scontent.fsgn5-9.fna.fbcdn.net/v/t1.15752-9/440846132_756833479623001_5681607853521538501_n.png?_nc_cat=105&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeG6pNTqByAoXOqzc5hcfNdlXpaNvT5tMFtelo29Pm0wWykhZKlOAWqmZ2XThco1dIbIQ_xceTL4VM0sPJsV4sd8&_nc_ohc=SabNhHDHJ2kQ7kNvgEAd7IO&_nc_ht=scontent.fsgn5-9.fna&oh=03_Q7cD1QGT6I2IVRIclqSQCOW995YQKqeLsDZUXytY5WRqx2gC_Q&oe=666C08D5)
  
6. Sau khi đã clone được về giờ chúng ta có thể mở dự án bằng cách thêm project vào Unity, hãy thiết lập đường dẫn tới thư mục mà bạn đã tạo trước đó và chọn thư mục dự án đã được clone từ github xuống

![](https://scontent.fsgn5-5.fna.fbcdn.net/v/t1.15752-9/440943812_1244931143149747_8913728558467002741_n.png?_nc_cat=108&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEsnoifiJ-jgXRHcGwHRn-m1OXjckhUc_jU5eNySFRz-GxCzyJURbbY50n6Oid7Qn_JAcK6EUUZ6Jx7ibCJsU6p&_nc_ohc=jk6hzFKsp8oQ7kNvgEDnvpd&_nc_ht=scontent.fsgn5-5.fna&oh=03_Q7cD1QGFaPzvt22TMLsptgjDVgEFxr2UNMBf1F4V2lx30U7fMg&oe=666BE753)
![](https://scontent.fsgn5-9.fna.fbcdn.net/v/t1.15752-9/440840534_957509792778463_8652348353261031171_n.png?_nc_cat=105&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGFjYpDaSjq5Xk-WbEwdDbYzAEjgOLJMN_MASOA4skw37OXZoRuVp66N2jxaSclNu4U3J6aA0-DufuiH_hw5PG6&_nc_ohc=-neF_gcGaCQQ7kNvgFku4nJ&_nc_ht=scontent.fsgn5-9.fna&oh=03_Q7cD1QH8mQ1gPbfGgckJfaIOSrwvzgc2t2W46FjtfCzqMTWH2g&oe=666C1D78)
