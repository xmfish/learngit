## php 常用方法

1. alert function
```
function alert($title){
  echo "<script type='text/javascript'>alert('$title');</script>";
}
```

2. href link
```
function href($url){
  echo "<script type='text/javascript'>window.location.href='$url'</script>";
}
```

3. println 
```
function println($string){
    echo $string."<br>";
}
```

4. print red line
```
function printline(){
    echo "<hr color='red' width='20%' align='left'>";
}
```
