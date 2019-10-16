ARRAY

// METHOD PADA ARRAY 

1. toString() :

method array ini digunakan untuk mengubah array menjadi string , contoh :

var parfum = ["bulgaria", "hugoboss", "dadifof"];

console.log(parfum.toString());


2. join() :


method array ini digunakan untuk menggabungkan / menambahkan bilangan tertentu disetiap element array, contoh :

var parfum = ["bulgaria", "hugoboss", "dadifof"];

console.log(parfum.join(!));


3. push() :

method array ini digunakan untuk menambahkan pada element array, contoh :

var parfum = ["bulgaria", "hugoboss", "dadifof"];

parfum.push("bulgarimotion");

console.log(parfum);


4. pop() :

method array ini digunakan untuk menghapus pada element array, contoh :

var parfum = ["bulgaria", "hugoboss", "dadifof", "bulgarimotion"];

parfum.pop("bulgarimotion");

console.log(parfum);


5. unshift() :

method array ini digunakan untuk menambahkan element pertama pada array, contoh:

var parfum = ["bulgaria", "hugoboss", "dadifof"];

parfum.unshift("bulgarimotion");

console.log(parfum);


6. shift() :

jika tadi menambahkan element pertama pada array, kali ini ada method shift() untuk menghapus element pertama pada array, contoh :

var parfum = ["bulgarimotion", "bulgaria", "hugoboss", "dadifof"];

parfum.shift();

console.log(parfum);


7. splice() :

method array ini digunakan untuk menambahkan element baru pada array, contoh :

var parfum = ["bulgaria", "hugoboss", "dadifof"];

parfum.splice(0, 0, "bulgarimotion", "anasuidream"];

console.log(parfum);


8. concat() :

method array ini digunakan untuk menggabungkan 2 array, contoh :

var parfum1 = ["cokelat", "strawberry", "melon"];

var parfum2 = ["sunkist", "bulgarilondon", "dadifofmen"];

parfum = parfum1.concat(parfum2);

console.log(parfum);


9. slice() :

method array ini digunakan untuk mengeluarkan element ke -n pada array :

var parfum = ["cokelat", "strawberry", "melon", "sunkist", "bulgarilondon", "dadifofmen"];

var parfum1 = parfum.slice(2);


nb : kita juga dapat mengeluarkan dua element array, contoh :

var parfum = ["cokelat", "strawberry", "melon", "sunkist", "bulgarilondon", "dadifofmen"];

var parfum1 = parfum.slice(2, 3);
 


 
