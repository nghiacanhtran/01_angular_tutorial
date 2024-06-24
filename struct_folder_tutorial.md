# Cấu trúc thư mục của Angular Project
- [Cấu trúc thư mục của Angular Project](#cấu-trúc-thư-mục-của-angular-project)
  - [node\_modules](#node_modules)
  - [src](#src)
  - [.editorconfig](#editorconfig)
  - [.gitignore](#gitignore)
  - [angular.json](#angularjson)
    - [Giới thiệu](#giới-thiệu)
    - [Main angular.json properties](#main-angularjson-properties)
    - [Tài liệu tham khảo](#tài-liệu-tham-khảo)

## node_modules  
   Folder chứa các gói package npm.
## src
## .editorconfig  
   - .editorconfig là file gì?  
        File chứa các qui tắc định dạng văn bản cho trình soạn thảo, đảm bảo tính nhất quán trong việc định dạng văn bản của toàn dự án.  
   - Cú pháp cơ bản
   - 
         | Tên thuộc tính           | Ý nghiax                                            | Value nên dùng            |
         | ------------------------ | --------------------------------------------------- | ------------------------- |
         | charset                  | định dạng (encoding)                                | utf-8                     |
         | end_of_line              | Kí tự xuống dòng                                    | lf (Unix) ,crlf (Windows) |
         | indent_style             | tab hay spaces                                      | space                     |
         | indent_size              | thụt lề                                             | 2                         |
         | tab_width                | Độ rộng một tab (chỉ áp dụng khi indent_style = tab | 2                         |
         | max_line_length          | Số kí tự tối đa trên mỗi dòng                       | 80                        |
         | insert_final_newline     | Thêm một dòng trống ở cuối file                     | true                      |
         | trim_trailing_whitespace | Loại bỏ các space dư thừa ở cuối dòng               | true                      |
   - PLugin Vs Code
      <https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig>
## .gitignore
   - .gitignore là file gì?  
      Gitignore là file có tên là .gitignore do Git quy định, nhiệm vụ của file là liệt kê những file mà mình không mong muốn cho vào git hoặc hiểm nôm na là Git sẽ lờ những file đó đi.
   - Tài liệu tham khảo  
      <https://medium.com/blogk/gitignore-la-gi-no-co-quan-trong-khong-f652da33a804>
## angular.json
   ### Giới thiệu
   - Đây là file cấu hình cho phép chương trình cấu hình cách hoạt động của dự and và cách CLI tạo ra các thành phần của dự án
   ### Main angular.json properties
   ### Tài liệu tham khảo
   <https://dev.to/tomwebwalker/angularjson-structure-for-beginners-what-we-can-set-27f3>