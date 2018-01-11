<script type="text/javascript">
    for (var i = 2; i < 100; i++) {
        for (var j = 2; j < i;j ++) {
            if(i % j == 0){
            break;
            }
        }
        if (i == j)
        document.write(i + ' ');
    }
</script>

<script type="text/javascript">
    var n = parseInt(window.prompt('请输入n的值'));
    while (n > 0) {
        document.write(n % 10);
        n = (n - n % 10) / 10;
    }
</script>