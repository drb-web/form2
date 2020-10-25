<!DOCTYPE html>
<html>
<head>
<meta charset ="utf-8">
</head>
<body>
<h1>FORM1</hl>
<form action ="https://www.nyl68.tw/search_num"method ="GET">
<input type ="text"name="category">
<input type ="submit"value="go">
</form>
<br>
<hl>FORM2 category</hl>
<form action ="https://www.my168.tw/search_num"method="GET">
<select name ="category">
<option value="10">10元以內禮贈品</option>
<option value="20">20元以內禮贈品</option>
<option value="30">30元以內禮贈品</option>
<option value="50">50元以內禮贈品</option>
<option value="100">100元以內禮贈品</option>
<option value="150">150元以內禮贈品</option>
<option value="200">200元以內禮贈品</option>
<option value="250">250元以內禮贈品</option>
<option value="300">300元以內禮贈品</option>
<option value="350">350元以內禮贈品</option>
<option value="400">400元以內禮贈品</option>
</select>
<input type ="submit"value ="go">
</form>
<br>
<hl>FORM3</hl>
<form action ="https://www.nyl68.tw/search_num"method ="GET">
<input type ="text"name="key">
<input type ="hidden"name ="cat"value="DPA">
<input type ="submit"value="go">
</form>
<br>
<hl>FORM4 url</hl>
<form action ="https://www.nyl68.tw/search_num"method ="GET">
<input type ="url"name="url">
<input type ="submit"value="go">
</form>
<br>
<hl>FORM5 time date tel</hl>
<form action ="https://www.nyl68.tw/search_num"method="GET">
<input type ="time"name="time">
<input type ="date"name="date">
<input type ="tel"name="tel">
<input type ="submit"value="go">
</form>
</body>
</html>
$ git add index.html

$ git commit -m "add index"
[master (root-commit) 80450b2] add index
 1 file changed, 10 insertions(+)
 create mode 100644 index.html
 $ git remote add origin https://github.com/eddiekao/eddiekao.github.io.git

$ git push -u origin master
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 327 bytes | 327.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/eddiekao/eddiekao.github.io.git
 * [new branch]      master -> master
Branch master set up to track remote branch master from origin.
