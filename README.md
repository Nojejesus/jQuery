# jQuery

松下问童子，言师采药去。
只在此山中，云深不知处。

在jQuery对象中无法使用DOM对象的任何方法。
例如$("#id").innerHTML和$("#id").checked之类的写法都是错误的，可以用$("#id").html()和$("#id").attr("checked")之类的jQuery方法来代替。
同样，DOM对象也不能使用jQuery里的方法。例如document.getElementById("id").html()会报错。
