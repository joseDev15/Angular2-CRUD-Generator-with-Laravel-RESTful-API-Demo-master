# Angular 2+/4/6 CRUD Code Generator
- Generate Angular component create/read/update/delete code from API
- Include a local Laravel back-end RESTful API demo
- Support custom and remote API 
- Easily add to exists Angular project
- Not effect to other exists components

![web-demo-index-page](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/web-demo-index-page-003.png)

![windows-angular-crud-code-generator](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/windows-angular-crud-code-generator-002.png)

![file-structure.png](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/file-structure.png)


# How to install
1. Requirements
    > git, php 7, npm, composer, sqlite db (already exists for most Linux/Mac/Windows7+)
2. Clone code
    ```
    git clone https://github.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo.git angular-crud-generator
    ```
    or
    > git clone https://github.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo.git angular-crud-generator
3. cd angular-crud-generator
    > cd angular-crud-generator
4. Run code generator script:
    - **For Windows**: run windows_ng_crud_generator.bat
        > windows_ng_crud_generator.bat
    - **For Mac or Linux**: run sh ./mac_linux_ng_crud_generator.sh
        > sh ./mac_linux_ng_crud_generator.sh
5. Done

![How to install](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/how-to-install.png)

# How it works
- The generator script will run npm install for Angualr environment and run composer update for Laravel back-end RESTful API environment
- It's will need 3-10 minutes for the first time
    > For windows os, it will open another 2 cmd windows for Angular frontend ng serve and Laravel API back-end server
    > For Mac and linux os, it will run Angular frontend ng serve and Laravel API back-end server in the same terminal
- Run the same script again if you need generate more Angular code
- There are few API demos exists, you can use your own RESTful API from local or remote server

# Some screenshots

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/windows-angular-crud-code-generator-001.png)

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/windows-angular-crud-code-generator-001-result.png)

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/web-demo-index-page-001.png)

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/web-demo-index-page-002-search.png)

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/web-demo-detail-page-001.png)

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/web-demo-edit-page-001.png)

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/web-demo-delete.png)

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/windows-angular-crud-code-generator-002.png)

![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/windows-angular-crud-code-generator-002-result.png)



![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/web-demo-index-page-003.png)


![Screenshot](https://raw.githubusercontent.com/AlexStack/Angular2-CRUD-Generator-with-Laravel-RESTful-API-Demo/master/docs/images/windows-angular-crud-code-generator-003-own-api.png)