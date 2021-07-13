# All-about-Markdown
**I. Markdown là gì?**

  Markdown là ngôn ngữ đánh dấu văn bản thô được tạo ra bởi John Gruber năm 2004, với mục đích cho phép người sử dụng "dễ viết các định dạng văn bản đơn giản dễ đọc và tùy chọn chuyển đổi nó thành các mã XHTML hợp lệ (hoặc HTML). 

  Các phần mềm sử dụng ngôn ngữ Markdown: GitHub, GitBook, Reddit, Diaspora, Stack Overflow, OpenStreetMap và các ứng dụng khác. 

  Một tài liệu Markdown là một file văn bản với phần mở rộng là .md.

**II. Tại sao cần dùng Markdown**
  
  HTML là một ngôn ngữ phổ biến, được sử dụng rộng rãi trong các ứng dụng internet từ các trang web tới nội dung email hay rất nhiều các tài liệu hướng dẫn online cũng đều sử dụng ngôn ngữ này. 
  
  Tuy nhiên, nhược điểm của nó là cú pháp của ngôn ngữ này không được thân thiện lắm với người dùng. Nếu như không có kiến thức về ngôn ngữ HTML thì bạn rất có thể đọc được nội dung của đoạn văn bản trên. Và ngay cả khi bạn đã hiểu về HTML thì đoạn mã vẫn gây rối mắt
  
 Không chỉ vậy, nếu so sánh với các phần mềm soạn thảo online/offline như MS Word (Google Docs nếu viết online) phải sử dụng các phím tắt hoặc nút công cụ để _bôi đậm, in nghiêng, định dạng thành danh sách hay chèn link, chèn ảnh v.v..._ thì thao tác sử dụng thẻ bằng Markdown đơn giản và nhanh chóng hơn rất nhiều.

**III. Các cú pháp thường dùng**
 
 **1. Tạo tiêu đề**
    
   Các lớp tiêu đề h1,h2,h3 cho đến h6 có thể viết được bằng các thêm số lượng ký tự `#` tương ứng vào đầu dòng. Một ký tự `#` tương đương với h1, 2 ký tự `#` tương đương với h2. Ví dụ như sau:
   
  `# Tiêu đề 1 (h1)`
  
  `## Tiêu đề 2 (h2)`
  
  `###Tiêu đề 3 (h3)`
  
  Sẽ nhận được kết quả như sau:
  
  # Tiêu đề 1 (h1)
  
  ## Tiêu đề 2 (h2)
  
  ### Tiêu đề 3 (h3)
  
  **2. Định dạng kiểu chữ**
  
  - Tạo kiểu chữ in đậm: `**Text**`
  - Tạo kiểu chữ in nghiêng: `_Text_`
  - Tạo kiểu chữ in đậm và in nghiêng: `**_Text_**`
  - Tạo kiểu chữ gạch ngang: `~~Text~~`
  
  **3. Định dạng danh sách**
  
  Để định dạng một đoạn văn bản thành các gạch đầu dòng, bạn dùng kỹ tự `*` và một dấu cách ở mỗi ý và dùng thêm 2 dấu cách ở đằng trước nếu muốn lùi vào một level
  
  `* Tổng quan về kỹ thuật`
  
    * Chức năng dẫn nhập trong C++
    
    * Thư viện C++
    
  `* Các ví dụ về C++`
  
    * Các ví dụ đơn giản`
    
     * Hello world
      
      * Đọc bàn phím và hiển thị ra màn hình chuẩn
      
    * Viết theo mẫu hình tiêu bản
    
    * Viết theo mẫu hình hướng đối tượng
  
 sẽ trở thành:
 
  
      * Tổng quan về kĩ thuật
      
        * Chức năng dẫn nhập trên C++
        
        * Thư viện C++
        
      * Các ví dụ về C++
      
        * Các ví dụ đơn giản
      
          * Hello world
        
          * Đọc bàn phím và hiển thị ra màn hình chuẩn
      
        * Viết theo mẫu hình tiêu bản
      
        * Viết theo mẫu hình đối tượng
        
        
  Nếu bạn muốn dùng số để đánh dấu viết số và một dấu chấm `.`
   
         1. Xe đạp
         2. Xe hơi
         3. Xe gắn máy
    
    sẽ trở thành: 
         
         1. Xe đạp
         
         2. Xe hơi
         
         3. Xe gắn máy
       
  **4. Dẫn link liên kết**
  
   Chỉ cần gõ đường link tuyệt đối (có http hoặc https), Markdown sẽ tạo liên kết tự động
   
        `https://en.wikipedia.org/wiki/John_Gruber`
   
     sẽ dẫn thẳng tới đường link: https://en.wikipedia.org/wiki/John_Gruber
   
   Ngoài ra, bạn có thể tạo liên kết bằng cách kết hợp dấu ngoặc cho văn bản liên kết và dấu ngoặc cho URL.
   
        `[Trang web vẽ Mockup online](https://moqups.com/)`
        
        
      sẽ hiển thị như sau: [Trang web vẽ Mockup online](https://moqups.com/)
     
   **5. Chèn hình ảnh**
   
   Dẫn hình ảnh trên cùng dòng:
   
    ![alt text] (link)
   
   Dẫn hình ảnh theo cách tham chiếu:
   
     ![alt text][Text]
      [Text]:link
     
  **6. Tạo bảng**
     
      Các cột được tách nau bằng dấu ngăn thẳng dduwngs`|` và header được tách với content bằng dấu gạch ngang `-`.Ở dòng ngăn cách giữa header và content bạn sẽ thấy ký hiệu căn lề trái phải (cột 2 và cột 3) bằng dấu hai chấm `:`
     
      | Previous number |     Number     | Next number  |
      | --------------- |:--------------:| ------------:|
      |    Five         |       Six      |     Seven    |
      |    Two          |     Three      |     Four     |
      |    Eight        |      Nine      |      Ten     |
      
sẽ nhận được kết quả sau:      
      
| Previous number |     Number     | Next number  |
| --------------- |:--------------:| ------------:|
|    Five         |       Six      |     Seven    |
|    Two          |     Three      |     Four     |
|    Eight        |      Nine      |      Ten     |

**7. Trích dẫn**
 
  Để tạo trích dẫn, bạn sử dụng ký tự `>`
  
`> John Gruber (born 1973) is a technology blogger, UI designer, and the inventor of the Markdown markup language. Gruber is from the Philadelphia, Pennsylvania, area. He received his Bachelor of Science in computer science from Drexel University, then worked for Bare Bones Software (2000–2002) and Joyent (2005–2006). Since 2002, he has written and produced Daring Fireball, a technology-focused blog.`

> John Gruber (born 1973) is a technology blogger, UI designer, and the inventor of the Markdown markup language. Gruber is from the Philadenlphia, Pennsylvania, area. He received his Bachelor of Science in computer science from Drexel University, then worked for Bare Bones Software (2000-2002) and Joyent (2005-2006). Since 2002, he has wwritten and produces Daring Fireball, a technology-focused blog.


**8. Chú thích**

Dùng ký tự `^` bên trong ngoặc vuông `[]` để đánh dấu và viết lại giải thích ở cuối

`John Gruber[^1].`

 `...`
 
 `...`
 
 `[^1]: writer, blog publisher, UI designer, the inventor of the Markdown publishing format.` 

  **9. Emoji**
  
  Bạn có thể chèn thêm các biểu tượng thể hiện cảm xúc bằng ký tự `:Text:`
  
  Ví dụ như khi gõ `:smile:`, bạn sẽ nhận được icon 😄
  
  Tham khảo bộ emoji theo cheatsheet của Github [tại đây](https://www.webfx.com/tools/emoji-cheat-sheet/)
  
  ***************
  
  Nguồn tham khảo:
  
  1. Kipalog (https://kipalog.com/posts/Huong-dan-su-dung-Markdown-tren-Kipalog)
  2. Codehub (https://www.codehub.com.vn/Markdown-La-Gi)
