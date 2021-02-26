<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>判断星期几</title>
</head>
<body>
<script>
    function  day(day){
        switch (day){
            case "星期一":
                alert("新的一周开始了!");
                break;
            case "星期二":
            case "星期三":
            case "星期四":
                alert("努力工作");
            case "星期五":
                alert("明天就是周末了");
                break;
            default:
                alert("放松休息");
                    break;
        }
    }
    day(prompt("请输入今天是星期几:"));
</script>
</body>
</html>
