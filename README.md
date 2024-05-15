# learn-2d-game 

learn to make 2d game from flappy bird game
![](https://scontent.fsgn5-14.fna.fbcdn.net/v/t1.15752-9/441443157_3614999768738770_2823607306850250601_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFVtDvDuOGHqtXL9PweW6YidOKMQ6ucIAx04oxDq5wgDB8CLCFmeo1NJvu9KXTqktQQDY88uOIoywRfR3X54QU0&_nc_ohc=glnn5Mp79i8Q7kNvgGSPOjb&_nc_ht=scontent.fsgn5-14.fna&oh=03_Q7cD1QG12FE8okybwMxyYavJ5KV8vgqQh1T9x7hulksVkBXNsA&oe=666BF027)

**Những phần mềm cần có để thiết lập tải xuống dự án này dùng cho mục đích tham khảo hay cho các cộng tác viên**
* Git : https://git-scm.com/downloads
* Tortoise Git : https://tortoisegit.org/download/
* Unity : https://unity.com/download

**Hướng dẫn cài đặt :**
1. Tải xuống `Git, Tortoise Git` dưới bản cập nhật mới nhất và cài đặt theo mặc định của nhà phát triển đề xuất ( không cần thiết phải tùy chỉnh lại ) 
2. Tải xuống `Unity` ( có thể tùy chỉnh gói nhưng sẽ tốn phí, cá nhân tôi dùng personal vì tôi nghèo ) và cài như tương tự
   
 `Cài đặt bổ sung trong Unity bắt buộc phải có`
   1. Unity Editor ( theo mặc định )
   2. Unity Archive ( theo mặc định )
   3. Modules [ Dev Tools : Microsoft Visual Studio Community ] tích hợp trong Unity Archive
   4. Sau khi cài xong thì Microsoft Visual Studio Community sẽ mở ra 1 cửa sổ, hãy kéo xuống phần Gaming và chọn " Game Development with Unity " (optional bỏ tick chọn Unity Hub vì đã cài rồi) tiếp tục cài đặt

**_Sau khi cài đặt xong không cần thiết phải đăng ký cứ bỏ qua và tắt nó đi_**

3. Lúc này khi đã cài `Git, Tortoise Git` chúng ta sẽ dùng nó để tạo thư mục ở dưới máy và dẫn dự án ở trên `github` về bằng cách :
+ Tạo 1 folder ở đường dẫn chúng ta muốn lưu và đảm bảo folder phải trống
+ Rồi chúng ta lên lại trên Repository của dự án Github mà ta muốn sử dụng, đứng tại mục code , bấm vào nút Code màu xanh lá rồi ta copy Url to clipboard trong mục local bằng phương thức https

  Ví dụ: ![](https://scontent.fsgn5-8.fna.fbcdn.net/v/t1.15752-9/440880502_463939726100899_4899839131298972889_n.png?_nc_cat=109&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeGu4YjF_TmilydQ8ohVyioBvnzkETl0912-fOQROXT3Xeb2GFAx4TYCCqrzwPqYmBtV0mR5Ltob3uo16ilNt1Sb&_nc_ohc=tCoyMyY5iZEQ7kNvgEDl3xK&_nc_ht=scontent.fsgn5-8.fna&oh=03_Q7cD1QGPXEyG8EIjhSkLpenRbrt0ypxj7EBlkGI9ReAKZH2AlA&oe=666BEF60)
+ Về lại folder của chúng ta hãy click chuột phải vào vùng trống của folder (chọn Git Clone để mở ra 1 cửa sổ), hãy copy url trên github đó vào phần URL và hãy chắc chắn phần directory đứng đúng thư mục mà bạn muốn lưu và chọn OK
  
  Ví dụ: ![](https://scontent.fsgn5-9.fna.fbcdn.net/v/t1.15752-9/440888866_974772040816393_2028507364070920349_n.png?_nc_cat=102&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeHfiiX4R2tKFBKOdCPKu8j07ThU7bC0LivtOFTtsLQuK-7EVDb0sUey9nvaZmnonlmT4U3c3drZEpiZzL-JF02k&_nc_ohc=-SiXp9eNTAcQ7kNvgGocBUv&_nc_ht=scontent.fsgn5-9.fna&oh=03_Q7cD1QFpZywZkxghIr6-6Scnf2mLSE0T0zN8N6NdUhpORlxe7g&oe=666C00C2)
  ![](https://scontent.fsgn5-5.fna.fbcdn.net/v/t1.15752-9/440932863_1127956271660909_567241398487057716_n.png?_nc_cat=100&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFwrv6cggflPsXNCMCIbhjbrKHqsZkC9WWsoeqxmQL1ZQS2RIfonuGccC-quJm-erI2hkIeD6e6bnNicXoougEd&_nc_ohc=HBPfMEJPiPsQ7kNvgE-B3Jl&_nc_ht=scontent.fsgn5-5.fna&oh=03_Q7cD1QH9a-KQbY-jUedd2iux32ZvyPDwVfxqksWsufJJT5K4_g&oe=666BFFF2)
+ Sau khi đã clone được về giờ chúng ta có thể mở dự án bằng unity bằng cách thêm project vào từ thư mục mình đã clone dự án

  Ví dụ: ![](https://scontent.fsgn5-5.fna.fbcdn.net/v/t1.15752-9/440943812_1244931143149747_8913728558467002741_n.png?_nc_cat=108&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeEsnoifiJ-jgXRHcGwHRn-m1OXjckhUc_jU5eNySFRz-GxCzyJURbbY50n6Oid7Qn_JAcK6EUUZ6Jx7ibCJsU6p&_nc_ohc=jk6hzFKsp8oQ7kNvgEDnvpd&_nc_ht=scontent.fsgn5-5.fna&oh=03_Q7cD1QGFaPzvt22TMLsptgjDVgEFxr2UNMBf1F4V2lx30U7fMg&oe=666BE753)
  ![](https://scontent.fsgn5-10.fna.fbcdn.net/v/t1.15752-9/440835547_1132127561246154_45054042683485107_n.png?_nc_cat=107&ccb=1-7&_nc_sid=5f2048&_nc_eui2=AeFMtfG_gb_uKWBZaGkVibjc0M8miOmHn4zQzyaI6YefjM72rtIGek0ew4ool-MIcX3pznbvkZuZAOEeOMM-cmG_&_nc_ohc=nA0tNXh1O1kQ7kNvgHbLnPR&_nc_ht=scontent.fsgn5-10.fna&oh=03_Q7cD1QGSH1867s9cWssomRQSzfMXestXTI9PZ6FZ9pHTVh145Q&oe=666BF62B)
