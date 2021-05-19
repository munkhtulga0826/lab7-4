# lab7-4
<html>
<head>
<meta charset="UTF-8" />
<script>
 {
            let str = window.prompt("Өгүүлбэр өг. Монголоор").toLowerCase();
            let er = ['а', 'у', 'о'];
            let em = ['э', 'ө', 'ү'];
            sep = str.split(' ');
            // console.log(sep.length)
            er.forEach(letter => {
                for (i = 0; i < sep.length; i++) {
                    if (sep[i].includes(letter)) {
                        console.log("er: " + sep[i]);
                    }

                }
            })
            em.forEach(letter => {
                for (i = 0; i < sep.length; i++) {
                    if (sep[i].includes(letter)) {
                        console.log("em: " + sep[i]);
                    }

                }
            })


        }
</script>
</head>
<body>
   <a href="https://munkhtulga0826.github.io/lab7/">bod1<a>
  <a href="https://munkhtulga0826.github.io/lab7-2/">bod2<a>
   <a href="https://munkhtulga0826.github.io/lab7-3/">bod3<a>
    <a href="https://munkhtulga0826.github.io/lab7-5/">bod5<a>
</body>
</html>
