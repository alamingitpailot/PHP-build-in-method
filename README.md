# PHP-build-in-method
### array_diff_assoc

```
$a1=array("t"=>"red","b"=>"green","c"=>"blue","d"=>"yellow");
$a2=array("a"=>"red","b"=>"green","c"=>"blue");
$result=array_diff_assoc($a1,$a2); 

Output: Array ( [t] => red [d] => yellow )
```

 দুই টা অ্যারে যদি Key ও value একই হয় তাহলে সে গুলি বাদ দিয়ে দিবে আর বাকি যে গুলি Key ও value আলাদা সে গুলি একটা অ্যারে লিস্ট দিবে । 
