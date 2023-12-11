<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>美食部落格</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 20px;
        }

        header {
            padding: 20px;
            background-color: #f5f5f5;
        }

        h1 {
            color: #333;
        }

        .start-button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            text-align: center;
            background-color: black;
            color: white;
            text-decoration: none;
            border-radius: 17px;
			cursor:pointer;
			border-style:solid;
			
        }
		
		.start-button:hover{
			background-color:rgb(46,46,46);
		}
		.start-button:active{
		background-color:rgb(70,70,70);
		}
		

		.share-button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 16px;
            text-align: center;
            background-color: blue;
            color: white;
            text-decoration: none;
            border-radius: 17px;
			cursor:pointer;
			
        }
		
		.share-button:hover{
			background-color:rgb(46,46,46);
		}
		.share-button:active{
		background-color:rgb(10,10,70);
		}
		
		
    </style>
</head>
<body>

    <header>
        <h1>美食部落格</h1>
    </header>

    <main>
        <a class="start-button" href="file:///C:/Users/User/Desktop/%E4%BB%8B%E7%B4%B9.html">開始</a>
		<a class="share-button" href="file:///C:/Users/User/Desktop/%E9%A3%9F%E7%89%A9%E9%80%A3%E7%B5%90.html">分享</a>
    </main>
	 

</body>
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Collapsible 範例</title>
    <!-- 加入 Materialize CSS 的連結 -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css" rel="stylesheet">
</head>
<body>

    <ul class="collapsible">
        <li>
            <div class="collapsible-header"><i class="material-icons">收起來跟展開</i></div>
            <div class="collapsible-body"><span>https://materializecss.com/collapsible.html</span></div>
        </li>
        <li>
            <div class="collapsible-header"><i class="material-icons">檢視圖片</i></div>
            <div class="collapsible-body"><span>https://materializecss.com/media.html</span></div>
        </li>
        <li>
            <div class="collapsible-header"><i class="material-icons">跳出警告</i></div>
            <div class="collapsible-body"><span>https://materializecss.com/modals.html</span></div>
        </li>
    </ul>

    <!-- 加入 Materialize JavaScript 的連結 -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>

    <!-- 初始化 Collapsible -->
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            var elems = document.querySelectorAll('.collapsible');
            var instances = M.Collapsible.init(elems);
        });
    </script>

</body>
</html>
</html>
