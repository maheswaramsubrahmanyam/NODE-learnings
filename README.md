# NODE-learnings



REPL 
READ 
EVAL
PRINT
LOOP

CLI 
command line interface 
node runs on a server non in a browser

built-in modules 

OS
PATH
FS
HTTP
![image](https://github.com/user-attachments/assets/c327cb64-922a-486d-a49a-1183cf622e43)

MODULE IMPORTING SYNTAX 

require('module Name')
const os = require('os')
console.log(os.type())
console.log(os.version())
console.log(os.freemem())
console.log(os.cpus())

#output 
node sample.js
Windows_NT
Windows 11 Home Single Language
3005128704
[
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 607609, nice: 0, sys: 670687, idle: 20962921, irq: 95687 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 367609, nice: 0, sys: 271015, idle: 21602421, irq: 29453 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 625515, nice: 0, sys: 492343, idle: 21123218, irq: 61281 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 396375, nice: 0, sys: 258734, idle: 21585968, irq: 26640 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 584546, nice: 0, sys: 400203, idle: 21256312, irq: 44921 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 417500, nice: 0, sys: 250546, idle: 21573031, irq: 23312 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 603734, nice: 0, sys: 371421, idle: 21265906, irq: 33546 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 430796, nice: 0, sys: 249265, idle: 21560968, irq: 22578 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 108921, nice: 0, sys: 126093, idle: 22006031, irq: 20312 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 102765, nice: 0, sys: 128109, idle: 22010156, irq: 22343 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 100953, nice: 0, sys: 119234, idle: 22020843, irq: 19984 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 110265, nice: 0, sys: 121031, idle: 22009734, irq: 15000 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 130890, nice: 0, sys: 144781, idle: 21965375, irq: 17453 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 133890, nice: 0, sys: 134546, idle: 21972593, irq: 15140 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 139015, nice: 0, sys: 136390, idle: 21965625, irq: 13546 }
  },
  {
    model: '13th Gen Intel(R) Core(TM) i7-1360P',
    speed: 2611,
    times: { user: 145906, nice: 0, sys: 153140, idle: 21941984, irq: 13421 }




__dirname 
__filename


console.log(__dirname)

console.log(__filename)

node sample.js
C:\Users\mahes\OneDrive\Desktop\Node learning
C:\Users\mahes\OneDrive\Desktop\Node learning\sample.js

  }
]
PS C:\Users\mahes\OneDrive\Desktop\Node learning>


const os = require('os')
const path = require('path')
// console.log(os.type())
// console.log(os.version())
// console.log(os.freemem())
// console.log(os.cpus())

console.log(__dirname)

console.log(__filename)
console.log(path)


node sample
C:\Users\mahes\OneDrive\Desktop\Node learning
C:\Users\mahes\OneDrive\Desktop\Node learning\sample.js
<ref *1> {
  resolve: [Function: resolve],
  normalize: [Function: normalize],
  isAbsolute: [Function: isAbsolute],
  join: [Function: join],
  relative: [Function: relative],
  toNamespacedPath: [Function: toNamespacedPath],
  dirname: [Function: dirname],
  basename: [Function: basename],
  extname: [Function: extname],
  format: [Function: bound _format],
  parse: [Function: parse],
  sep: '\\',
  delimiter: ';',
  win32: [Circular *1],
  posix: <ref *2> {
    resolve: [Function: resolve],
    normalize: [Function: normalize],
    isAbsolute: [Function: isAbsolute],
    join: [Function: join],
    relative: [Function: relative],
    toNamespacedPath: [Function: toNamespacedPath],
    dirname: [Function: dirname],
    basename: [Function: basename],
    extname: [Function: extname],
    format: [Function: bound _format],
    parse: [Function: parse],
    sep: '/',
    delimiter: ':',
    win32: [Circular *1],
    posix: [Circular *2],
    _makeLong: [Function: toNamespacedPath]
  },
  _makeLong: [Function: toNamespacedPath]
}


const os = require('os')
const path = require('path')
// console.log(os.type())
// console.log(os.version())
// console.log(os.freemem())
// console.log(os.cpus())

// console.log(__dirname)

// console.log(__filename)
// console.log(path)
console.log(path.__dirname(__filename))

node sample
C:\Users\mahes\OneDrive\Desktop\Node learning

![image](https://github.com/user-attachments/assets/10eccaec-9da7-4ef8-8271-d175513c8c4f)

![image](https://github.com/user-attachments/assets/f8f9a380-eb7f-464e-b5b6-8c645076c6db)

FS function 
const fs = require('fs')

fs.readFile("demo.txt", 'utf8',(err,data)=>{
    if(err){
        console.log(err)
    }
    console.log(data)
})

in the above code we have to creat a demo txt file and reading through fs.readFile function 
syntx for fs.readFile("txtfileName" , 'encoder' , function)

output 
 node index
hello everyone this is maheswaram subrahmanyam learining nodejs


if in case if we do not place encoder it returns the buffer code 


if we want  to create a file by using writeFile method 
syntax 
fs.writeFile('fileName','encoder',function)

![image](https://github.com/user-attachments/assets/0bef0778-a2e5-4b11-99ec-696042c58720)



if we want to create a content in the file in dynamic way its possible by writeFile method 
syntax 
fs.writeFile('fileName' , contentSample , function)

the file before content crested dynamically 
![image](https://github.com/user-attachments/assets/6c40e42d-7393-4c28-889b-a4e6990ec095)

code 
![image](https://github.com/user-attachments/assets/7cdb815c-27e8-43d3-a64b-59474db05dec)

the dynamic content in the webpage 
![image](https://github.com/user-attachments/assets/3daa065c-ad9b-452f-bd6d-e3a4e609c3ea)


if you want to changet the file name dynamically we use rename function
syntax 
fs.rename('old file name' , 'new file name' , function)

![image](https://github.com/user-attachments/assets/3c728c09-345d-4e2d-8219-d421d70ce91f)
output
![image](https://github.com/user-attachments/assets/9a68dc6e-6af9-4a2f-9673-fe6286b9a5af)


if you want to delet a file dynamically we use unlink function
syntax 
fs.unlink('file name',function)
![image](https://github.com/user-attachments/assets/fbc81898-dfa6-4075-84c8-6aff1d9e9c28)
output 
![image](https://github.com/user-attachments/assets/484680c5-4c92-4845-b351-fe997383b681)




HTTP module 
![image](https://github.com/user-attachments/assets/fd3570ac-eff3-4bda-91e6-07180db85b31)
![image](https://github.com/user-attachments/assets/fda4b3a1-7c2d-432b-bee8-c8f8282b6ebc)
![image](https://github.com/user-attachments/assets/f0820f37-d837-4366-aebe-9cb2ba38486a)
![image](https://github.com/user-attachments/assets/d64c7d08-87f3-43d8-b1fc-1e4b3a27a3f5)

creating a server using http menthos
![image](https://github.com/user-attachments/assets/0f6abe6e-f02e-41c7-b90c-759fa016358a)
explination of the code 
we are creating a http varbale by require of http
and created another varible for server port which is myserver varable in that varable i have been created a server with request and response arguments by using arrow function in thet we retrive the server info by response.write and after fecing the server we have to stop the surver and it was done by the response.end() method

after this function we have to create the port for accesing in clint side 
so we choose the port number as 5300 
by feching the localhost:5300 in browser we connet to the server 
![image](https://github.com/user-attachments/assets/1796256a-358e-4efe-a43a-8f7989283c39)

local modules 
![image](https://github.com/user-attachments/assets/70ecf2f8-9379-4253-8653-eb97f9328b23)

we can create module and use in another files
![image](https://github.com/user-attachments/assets/71270281-6547-4165-926a-12aa07af2ad8)
in the above code we seen that we create 4 module which is four functions 
in the last line of code we are exportig this module by placing the function name in curly braces by the method module.export 
![image](https://github.com/user-attachments/assets/e5772b94-c5da-496d-b9b7-9d1862d078ba)
and we can acces the modules by passing the module names in curly braces and passing the specifi path of the file ./demoModule in the require 
and we get the output accordingly

express JS
![image](https://github.com/user-attachments/assets/023adbf8-454c-42e2-8884-9630ae2f8b77)
lets start by installation 
first we have to create a file and i've named as express js 
![image](https://github.com/user-attachments/assets/7ce43fd4-0c88-48b7-bd7b-ae57d6f99518)

open the file and in the path type cmd and enter you will see like this 
![image](https://github.com/user-attachments/assets/10c0d362-50f8-4739-b63d-811c72a04fc2)
now type npm init command in the cmd it will create a node envorniment 
![image](https://github.com/user-attachments/assets/f8244164-7824-4123-8f66-acd0f7be9f46)
and i was not entered any data i just simpley enter all the cridentials at end i entered y
![image](https://github.com/user-attachments/assets/c5e4d648-cb70-458a-b298-e1815f06b48e)
now you can see thet in your file a package is created 
![image](https://github.com/user-attachments/assets/91c9fccb-e803-4cec-ab69-9711cee6446d)

when you open this package in your VS code you can see the details of your project 
![image](https://github.com/user-attachments/assets/fab9d338-22ac-4274-b6b5-3b0244ab10ce)

now you can create a app.js file in the folder 
and in the app.js file write some randome code to saw output 
![image](https://github.com/user-attachments/assets/e705f388-7f8d-4296-9da5-5e60b9d7a5fc)

you have to update code in regulara interavls and save and run by node app every time for seeing the output right 
so the altration for this problem is that you can install the thirdpart packages called npm 
installation process 
![image](https://github.com/user-attachments/assets/f3e9383a-b990-40da-890c-21fa39cfd170)
open the website and in the search bar you can search for nodemon 
![image](https://github.com/user-attachments/assets/df151e04-7146-4fa4-b72b-fde9955642c4)
coply the command npm i nodemon
and past it in your terminal 
![image](https://github.com/user-attachments/assets/0307ec3d-8508-4d35-abbd-47752169e5bd)
sucussfully installed nodemon with 0 errors 
![image](https://github.com/user-attachments/assets/adffc4c0-437d-4718-8f58-687ed70dbe92)
you can verify the installation is succesfull done or not by verifying the package 
in the package the nodemon will be displayed if not you are not folloing the correct process
![image](https://github.com/user-attachments/assets/b89277e0-a331-47a5-bd7e-1c8b7fb387f8)
now you have to do some simple process to connet the app.js file with our package to see the changes directly in the ternimal 
the process is pretty simple 
you have to open the package and create a key "start" and value as "nodemon app.js" 
"start:"nodemon app.js"
![image](https://github.com/user-attachments/assets/b80270fd-b0ad-4946-af31-70d609c264b6)

the next step is that you have to start the file 
in terminal you have to enter npm start
and it will start excuting the app.js file automatically 
![image](https://github.com/user-attachments/assets/3f4cd4e7-a110-4751-a31a-0cbae0e94bfc)
now test by changing the console.log() value 
![image](https://github.com/user-attachments/assets/6074a43a-c1ec-4c80-af73-b53fdf8f3ebe)
if you want to stop this application or terminal you have to do this 
ctrl + c 
it will ask yes no enter y 
you will seen like this
![image](https://github.com/user-attachments/assets/dd5e64ed-e8b0-4ff1-963a-dbae545fecc8)

again if you want to start use this command which is 
npm start




creating a webserver using express js
![image](https://github.com/user-attachments/assets/fd537fb5-f18d-4f9a-b976-ed7fbcf89178)





![image](https://github.com/user-attachments/assets/3fecca88-742b-458a-8008-90ae56e64e74)

![image](https://github.com/user-attachments/assets/f8ec2373-077a-40ab-b960-4f610e82c5b3)



![image](https://github.com/user-attachments/assets/9e945958-7087-46e6-9975-93a61ab0f881)

![image](https://github.com/user-attachments/assets/147abac1-3086-4184-b3e5-316ac5612306)



MiddleWare consept 

![image](https://github.com/user-attachments/assets/a0a12db1-c71b-4d3f-a85c-fbda2ee06a78)

![image](https://github.com/user-attachments/assets/d197afae-0122-4fc4-af6f-b7d57eb919bf)
![image](https://github.com/user-attachments/assets/a3838a5c-b5d0-4b1d-8a3b-d197ae9cab39)
![image](https://github.com/user-attachments/assets/3602e568-b4d9-4c8d-8b32-72faa1962aaa)


let's see what is middlewares, how to regestration & how to use Middlewares

middleware is a function that extends form the express js


app.use()

use method takes three arguments  use((req,res,next))

using the use() method we can mentions some conditions to load/response from the server
if the conditions satsfys then only the router will get the acces iof server to load information 
if not the its buffers the site 
![image](https://github.com/user-attachments/assets/a4ead5b0-c5ea-49ce-b128-3aeb4bbf5faf)

In the above code 
we use middleware by using use() method to pass the conditions 
output will be like this 

the condition 10<20 is true so it will get the server and shows the output corrspondingly 

let's make condition fales and see what happends
![image](https://github.com/user-attachments/assets/7e2f5a91-f888-4427-bf05-b19d372e4e74)

in the above if condiction was false 10>20 so now see the routers 

present we are in home page 
![image](https://github.com/user-attachments/assets/62f939cd-8d0b-4807-99c5-ca864f16b869)
lets change the router by about and see what happens
 its is browsing like this beacouse conditions are unsatsfyed 
 ![image](https://github.com/user-attachments/assets/5478ba84-2b85-45e9-b301-1a472708b583)
you can see that in network 
you will observe that status was cancled/ pending this is what happens when the conditions are not satsfyed 

![image](https://github.com/user-attachments/assets/52388694-839f-4fcc-839a-d403850d380d)

if you want to apply the middleware conditions for specific functions 
you can modify the code by storing the middleware conditions in a varible and passing it to the specific router 

let's see practically 
![image](https://github.com/user-attachments/assets/9fbf2a7f-eb1c-4ed4-bafc-a4a371983d18)

![image](https://github.com/user-attachments/assets/9acff3e9-d7cd-46e8-b962-b61ee06f64c3)








