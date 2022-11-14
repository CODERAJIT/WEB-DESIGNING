// get number
function number(num) {
    var result=document .getElementById("input") ;
    result.value=result.value+num;
}
// get clear
function clearesult() {
    var result=document  .getElementById("input") ;
    result.value="";
    result.style.textAlign="right";
    result.style.color="black";
}
// get result
function result() {
    var result=document .getElementById("input") ;
    result.value=eval( result.value);
    result.style.color="red";
    result.style.textAlign="center";
    result.style.fontStyle="sans-serif";
}
// get delete
function deletenum(){
    var result=document .getElementById("input") ;
     var remove = result.value;
     remove= remove.slice(0,-1);
     result.value = remove;
     result.style.textAlign="right";
    result.style.color="black";


}
