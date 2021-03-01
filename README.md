<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>只属于我大哥的网页</title>
</head>
<body>
<h1>大哥跟猪有区别嘛？</h1>
<input id="rs" type="text"/>
<input type="button" value="提交" onclick="dage()">
</body>
</html>
<script>
    function dage(){
        var result =document.getElementById("rs");

        switch (result.value){
            case "没有":
                alert("小弟晓得!")
                break;
            case "有":
                alert("因为大哥是只属于小弟的猪!")
                break;
        }
    }
</script>
