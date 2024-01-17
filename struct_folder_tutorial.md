# Cấu trúc thư mục của Angular Project

1. node_modules  
   Folder chứa các gói package npm.
2. src
3. .editorconfig  
   1. .editorconfig là file gì?  
        File chứa các qui tắc định dạng văn bản cho trình soạn thảo, đảm bảo tính nhất quán trong việc định dạng văn bản của toàn dự án.  
    2. Cú pháp cơ bản

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
   3. PLugin Vs Code
      1. link: <https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig>