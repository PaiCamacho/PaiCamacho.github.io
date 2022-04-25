**Lecture Notes 3/23

functions can be called from child window (frames), parent window and any window opened on the same domain. 
window.frames[0].frames[1].fname()

Javascript Array = Java's array + List (LinkedList + ArrayList) + stack 
let/var/const arrName = new Array(); 
arr.splice -takes up to 3 arguments
shift = left_pop
unshift = left_push

let x = [1,2];
let p =
Object = Java's Hashmap/Hashtable = associative = extension of Array
Object = {id : "D100", lastName: "Smith", firstName: "John", info: x};

**Lecture Notes 3/28

JSON.stringify(object)
why to stringify? To store and transmit the object

object = JSON.parse(string)

localStorage[key] = zip(string);
string.indexOf('target') (-1 not found)
str.substring(starting, endposition);
s = "abc"
s.substring(0,2):ab
str.replace(/reg/ig,"dfd");

**Lecture Notes 3/30

let ele = document.getElementBy('id);
to delete:ele.parentNote.removeChild(ele);
ele.style.color = 'red';
ele.stlye.bakcground-color = 'white';

let newele =
document.createElement('p');
newele.innerHTML = "any HTML code";
document.body.appendChild(newele);
ele.innerHTML = "sddf";
<div attribute1 = value> inner html </div>
let dv =
document.createElement('div');
dv.id = "meaningfulid";
dv.style.cssText = "color:red;background-color:whote;font-size:17px";
dv.innerHTML = "what ever";
document.body.appendChild(dv);


**Lecture Notes 4/4

window.onclick = function()
window.addEventListener('click', handle);

function handle(){


}

window.onclick = handle;
long polling
short polling

**Lecture Notes 4/6

(1) tomcat server
    https://www.apache.org
    
(2) download v9.062 64-but window or tar.gz for Mac

(3) unzip 

(4) go inside bin 

(5) macbook user find the location JDK on your PC

(6) edit startup.sh (Mac) or startup.bat (Window) on beginning, add line 
Mac: JAVA_HOME = /Library/Java...
export $JAVA_HOME

tomcat hosts applications, application server
classic web server hosts static files





**Lecture Notes 4/13



regular expression: 
usage: remove all digits
str.replace(/[0-9]+/g, "";

g: all occurrences
i: case insensitive

replace a pattern by a new string 
str.replace(/pattern/gi,"new string");

str.replace(/[A-Z]+/gi,"A");
+: 1 or more
?: 0 or 1
*: 0 or more 
^: on being 
second usage: logic Not
task: remove all non-digits:
cardnumber.replace(/[^0-9]/g,'');
. dot means any single char
.*:everything 

(1) delete everything following a pattern

str.replace(/pattern.*/,'');

let username = string.replace(/@.*/,'');

let y = username.replace(/[a-b|0-9|\-\_|\.]/g.'');
valid username <==> y == ''

let domainname = string.replace(/[^@]+@,'');

domainname.replace(/\.io/,''); != domainname <==> domainname contains ".io" <==> domainname.includes(".io")

domainname.replace(/\.com|.gov|.edu|.tv|.io|.mil|.buz|.org)




**Lecture Notes 4/20




Configure Tomcat and Examine websocket

(1) download tomcat from apache.org
(2) Java JDK
(3) find the path of Java JDK
(4) go to tomcat/bin/
    edit startup.sh (Mac)
(5) Mac sh ./tartup.sh to launch tomcat
(6) visit http://localhost:8080/examples/
(7) http://10.33.18.4:8080/examples/

(1) separated by comma "," 
(2) within object, always prefix family name
(3) using column ":" for inital value
(4) equivalent to name-space in C++
(5) JSON.stringify(Exchange);
(6) a = JSON.parse(JSON.stringify(Exchange));
(7) multi-dimensional objects



**Lecture Notes 4/25



Debugger using Chrome
(1) load js
(2) using inspector to find function (handler) name
(3) find the function body
(4) set break points
(5) reload page
(6) step over and step into

Try debugger: https://zhongyanlin.github.io/site/

Learn how to create and modify displaying Shapes

Quiz question 1: how many arguments in the constructor of Shape class in https://zhongyanlin.github.io/site/showcase ? 14

Quiz question 2: Create a reverse method for String using charAt(i) to retrieve each character
String.prototype.reverse

Quiz question 3: Write a sum method for array that sum up elements if they are numeric and concatenation of toString() if not 

