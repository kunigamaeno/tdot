# tdot
application template

# 
```` js
(function(root,t){

 var plugin={};
  plugin.id ="";
  plugin.name="";
  plugin.md="";
  //...
  
 var obj={};
  obj.m={};
  obj.v = function(){}
  obj.c = function(){}
  
 var call={};
  call.i = function(dat){}
  call.o = function(dat){}
  call.c = function(dat){}
  
//if( t.add.test(plugin,obj,call)) //debug test, info console.log. plz final, comment-out.
  t.add(plugin,obj,call); //plugin add
  
})(this,t)

````
