#

| **Nhóm**      | **Chức năng**          | **Prefix (Gõ tắt)** | **Cú pháp (Body)**                                                   | **Mô tả**                                       |
| ------------- | ---------------------- | ------------------- | -------------------------------------------------------------------- | ----------------------------------------------- |
| **CONSOLE**   | Console Log            | `jlog`              | `console.log($1);`                                                   | Log biến ra màn hình console.                   |
| **CONSOLE**   | Console Error          | `jerr`              | `console.error($1);`                                                 | Log lỗi ra màn hình console.                    |
| **CONSOLE**   | Console Table          | `jtab`              | `console.table(${1:arrayOrObject});`                                 | Hiển thị mảng/đối tượng dưới dạng bảng.         |
| **FUNCTIONS** | Function Declaration   | `jfn`               | `function name(params) { ... }`                                      | Khai báo hàm truyền thống.                      |
| **FUNCTIONS** | Arrow Function (Short) | `jaf`               | `const name = (params) => expression;`                               | Hàm mũi tên ngắn gọn (Implicit return).         |
| **FUNCTIONS** | Arrow Function (Block) | `jafb`              | `const name = (params) => { ... };`                                  | Hàm mũi tên có thân hàm (Block body).           |
| **FUNCTIONS** | IIFE                   | `jiife`             | `(() => { ... })();`                                                 | Hàm thực thi ngay lập tức.                      |
| **ARRAYS**    | Array ForEach          | `jfore`             | `array.forEach((item) => { ... });`                                  | Duyệt mảng (không trả về giá trị).              |
| **ARRAYS**    | Array Map              | `jmap`              | `const newArray = array.map((item) => expression);`                  | Tạo mảng mới từ mảng cũ (Transformation).       |
| **ARRAYS**    | Array Filter           | `jfil`              | `const filteredArray = array.filter((item) => condition);`           | Lọc các phần tử thỏa mãn điều kiện.             |
| **ARRAYS**    | Array Find             | `jfind`             | `const foundItem = array.find((item) => condition);`                 | Tìm phần tử đầu tiên thỏa mãn điều kiện.        |
| **ARRAYS**    | Array Reduce           | `jred`              | `const result = array.reduce((acc, curr) => { ... }, initialValue);` | Gom mảng thành một giá trị duy nhất.            |
| **MODULES**   | Import Named           | `jimp`              | `import { module } from "path";`                                     | Import các thành phần có tên.                   |
| **MODULES**   | Import Default         | `jimpd`             | `import name from "path";`                                           | Import mặc định.                                |
| **MODULES**   | Import Dynamic         | `jimpdyn`           | `import("path").then((module) => { ... });`                          | Import động (Lazy loading).                     |
| **MODULES**   | Export Named           | `jexp`              | `export const name = value;`                                         | Xuất hằng số/biến có tên.                       |
| **MODULES**   | Export Default         | `jexpd`             | `export default name;`                                               | Xuất mặc định (Mỗi file chỉ 1 cái).             |
| **OBJECTS**   | Destructure Object     | `jdob`              | `const { prop } = object;`                                           | Bóc tách thuộc tính từ Object.                  |
| **OBJECTS**   | Destructure Array      | `jdar`              | `const [ first, rest ] = array;`                                     | Bóc tách phần tử từ Array.                      |
| **OBJECTS**   | Object Keys            | `jkeys`             | `Object.keys(obj)`                                                   | Lấy danh sách tên thuộc tính (keys).            |
| **OBJECTS**   | Object Entries         | `jentries`          | `Object.entries(obj)`                                                | Lấy danh sách cặp \[key, value\].               |
| **UTILITIES** | Ternary Operator       | `jtern`             | `condition ? trueValue : falseValue`                                 | Toán tử ba ngôi (Thay thế if-else ngắn gọn).    |
| **UTILITIES** | Template Literal Var   | `jvar`              | `\${variable}`                                                       | Chèn biến vào chuỗi (Dùng trong dấu backticks). |
| **UTILITIES** | Set Timeout Arrow      | `jtime`             | `setTimeout(() => { ... }, 1000);`                                   | Hẹn giờ dùng Arrow Function.                    |
