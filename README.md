# a
<html>
  <title>
    <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>クイズ</title>
<form action="https://www.google.co.jp/search" method="get">
  <input type="search" name="search" placeholder="キーワードを入力">
  <input type="submit" name="submit" value="検索">
</form>
      
   <form name="クイズ">
  <br>Q1)クイズを入力してください<br>
  <font size="2" color="#FF0000">
    （答え記入後、「回答する」をクリックしてください）
  </font><br>
    答え：<input type="text" name="anser">
  <input type="button" value="回答する" onClick="check()">
</form>
<div id="feedback"></div>

<script>
function check(){
  const feedback = document.getElementById("feedback")
  if (document.form.anser.value=="正解"){ 
    feedback.textContent = "正解の場合、"}
  else {alert("不正解の場合")}
}
</script>     

 <form name="クイズ2">
 Q2)クイズを入力してください
  <font size="2" color="#FF0000">
  <br>（答え記入後、「回答する」をクリックしてください）
  </font></br>
    答え：<input type="text" name="anser">
  <input type="button" value="回答する" onClick="check()">
</form>
<div id="feedback"></div>

<script>
function check(){
  const feedback = document.getElementById("feedback")
  if (document.form.anser.value=="正解"){ 
    feedback.textContent = "正解の場合"}
  else {alert("残念、間違いです")}
}</script>
  
<form name="クイズ4">
  Q3)クイズを入力してください
  <font size="2" color="#FF0000">
    <br>（答え記入後、「回答する」をクリックしてください）
  </font></br>
    答え：<input type="text" name="anser">
  <input type="button" value="回答する" onClick="check()">
</form>
<div id="feedback"></div>

<script>
function check(){
  const feedback = document.getElementById("feedback")
  if (document.form.anser.value=="正解"){ 
    feedback.textContent = "正解の場合"}
  else {alert("不正解の場合")}
}</script>
  
<form name="クイズ5">
  Q4)クイズを入力してください
  <font size="2" color="#FF0000">
    <br>（答え記入後、「回答する」をクリックしてください）
  </font></br>
    答え：<input type="text" name="anser">
  <input type="button" value="回答する" onClick="check()">
</form>
<div id="feedback"></div>

<script>
function check(){
  const feedback = document.getElementById("feedback")
  if (document.form.anser.value=="正解"){ 
    feedback.textContent = "正解の場合"}
  else {alert("不正解の場合")}
}</script>

<form name="クイズ6">
Q5)クイズを入力してください
  <font size="2" color="#FF0000">
    <br>（答え記入後、「回答する」をクリックしてください）
  </font></br>
    答え：<input type="text" name="anser">
  <input type="button" value="回答する" onClick="check()">
</form>
<div id="feedback"></div>

<script>
function check(){
  const feedback = document.getElementById("feedback")
  if (document.form.anser.value=="正解"){ 
    feedback.textContent = "正解の場合"}
  else {alert("不正解の場合")}
}</script>

<form name="クイズ3">
Q6)クイズを入力してください
  <br><font size="2" color="#FF0000">
  （答え記入後、「回答する」をクリックしてください）
  </font></br>
    答え：<input type="text" name="anser">
  <input type="button" value="回答する" onClick="check()">
</form>
<div id="feedback"></div>

<script>
function check(){
  const feedback = document.getElementById("feedback")
  if (document.form.anser.value=="正解"){ 
    feedback.textContent = "正解の場合"}
  else {alert("不正解の場合")}
}</script>
         
</html>
