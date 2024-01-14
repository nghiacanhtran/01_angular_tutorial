1. Install node js  
   1. Trang chủ: [link](https://nodejs.org/en)
2. Install angular 
   1. Install angular cli: `npm install -g @angular/cli`
   2. Test version angular cli: `ng --version`
   3. Install angular project
      1. CD tới folder cần tạo
      2. Chạy lệnh: `ng new test-project`  
      
      Câu hỏi số 1:
        ```
          Would you like to enable autocompletion? This will set up your terminal so pressing TAB while typing Angular CLI commands will show possible options and autocomplete arguments. (Enabling autocompletion will modify configuration files in your home directory.)`  
        Đây là yêu cầu cài đặt tính năng auto comple của angualr cli.
        Chọn Yes để enable tính năng.  
       ```

      Câu hỏi số 2:  
       ```
       Which stylesheet format would you like to use?  
       Đây là câu hỏi lựa chọn trình CSS cho project 
        - CSS  
        - SCSS   [ https://sass-lang.com/documentation/syntax#scss  
        - Sass   [ https://sass-lang.com/documentation/syntax#the-indented-syntax ]
        - Less   [ http://lesscss.org]
      ```
      Câu hỏi số 3
      ```
      Do you want to enable Server-Side Rendering (SSR) and Static Site 
      Generation (SSG/Prerendering)?
      - SSR là gì?
        Server-side rendering là render nội dụng phía máy chủ server
        link tham khảo: 
        <https://angular.io/guide/ssr>
        <https://angular8.hashnode.dev/cac-khai-niem-lien-quan-server-side-rendering-vs-static-generation>
        <https://viblo.asia/p/so-sanh-server-side-rendering-vs-client-side-rendering-vs-pre-rendering-vs-dynamic-rendering-LzD5dWoOljY>
      - SSG/Prerendering là gì?
        Static-site Generation 
        link tham khảo:
        <https://angular.io/guide/prerendering>
        <https://angular8.hashnode.dev/cac-khai-niem-lien-quan-server-side-rendering-vs-static-generation>
        <https://viblo.asia/p/so-sanh-server-side-rendering-vs-client-side-rendering-vs-pre-rendering-vs-dynamic-rendering-LzD5dWoOljY>
      ```
