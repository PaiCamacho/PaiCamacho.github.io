##Lecture Notes 3/23
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

##Lecture Notes 3/28

JSON.stringify(object)
why to stringify? To store and transmit the object

object = JSON.parse(string)

localStorage[key] = zip(string);
string.indexOf('target') (-1 not found)
str.substring(starting, endposition);
s = "abc"
s.substring(0,2):ab
str.replace(/reg/ig,"dfd");

##Lecture Notes 3/30

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

