Vue.component('MyItem',{
data : function() {
return  {
	message : "$"
	}
},
template : 	"<div  class='item'><img :src=src>   <p>{{name}}</p><p>{{price}} {{message}}</p><a :href=id>click hrere</a></div>",
props : ['name','price','id','src']
})