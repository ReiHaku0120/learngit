<?php 
 global $device;
 global $viewType;
 global $errormsg;
?>

<html><head><meta http-equiv="Content-Type" content="text/html; charset=Shift_JIS"><title>福岡市地下鉄</title></head>
<body>
<center><img src="/mobile/img/logo.png" alt="福岡市地下鉄"></center><br>

<?php if($viewType == "Index") { ?>
<hr>
<center><font color="#0000DD">料金検索</font></center>
<hr>
<font color="#009900">☆発駅､着駅を選択して下さい｡</font>
<hr>

<form action="./fare_index.php?p1=<?php echo $device ?>" method="get" name="ST">
<input type="hidden" name="m" value="search">
<input type="hidden" name="p1" value="<?php echo $device ?>">

■発駅名 <br>
　<select name="s1">
<option value="">▼駅名を選択</option>
<option value="姪浜" >姪浜</option>
<option value="室見" >室見</option>
<option value="藤崎" >藤崎</option>
<option value="西新" >西新</option>
<option value="唐人町" >唐人町</option>
<option value="大濠公園" >大濠公園</option>
<option value="赤坂" >赤坂</option>
<option value="天神" >天神</option>
<option value="中洲川端" >中洲川端</option>
<option value="祇園" >祇園</option>
<option value="博多" >博多</option>
<option value="東比恵" >東比恵</option>
<option value="福岡空港" >福岡空港</option>
<option value="呉服町" >呉服町</option>
<option value="千代県庁口" >千代県庁口</option>
<option value="馬出九大病院前" >馬出九大病院前</option>
<option value="箱崎宮前" >箱崎宮前</option>
<option value="箱崎九大前" >箱崎九大前</option>
<option value="貝塚" >貝塚</option>
<option value="橋本">橋本</option>
<option value="次郎丸">次郎丸</option>
<option value="賀茂">賀茂</option>
<option value="野芥">野芥</option>
<option value="梅林">梅林</option>
<option value="福大前">福大前</option>
<option value="七隈">七隈</option>
<option value="金山">金山</option>
<option value="茶山">茶山</option>
<option value="別府">別府</option>
<option value="六本松">六本松</option>
<option value="桜坂">桜坂</option>
<option value="薬院大通">薬院大通</option>
<option value="薬院">薬院</option>
<option value="渡辺通">渡辺通</option>
<option value="天神南">天神南</option>
</select>
<br>
■着駅名 <br>
　<select name="s2">
<option value="">▼駅名を選択</option>
<option value="姪浜" >姪浜</option>
<option value="室見" >室見</option>
<option value="藤崎" >藤崎</option>
<option value="西新" >西新</option>
<option value="唐人町" >唐人町</option>
<option value="大濠公園" >大濠公園</option>
<option value="赤坂" >赤坂</option>
<option value="天神" >天神</option>
<option value="中洲川端" >中洲川端</option>
<option value="祇園" >祇園</option>
<option value="博多" >博多</option>
<option value="東比恵" >東比恵</option>
<option value="福岡空港" >福岡空港</option>
<option value="呉服町" >呉服町</option>
<option value="千代県庁口" >千代県庁口</option>
<option value="馬出九大病院前" >馬出九大病院前</option>
<option value="箱崎宮前" >箱崎宮前</option>
<option value="箱崎九大前" >箱崎九大前</option>
<option value="貝塚" >貝塚</option>
<option value="橋本">橋本</option>
<option value="次郎丸">次郎丸</option>
<option value="賀茂">賀茂</option>
<option value="野芥">野芥</option>
<option value="梅林">梅林</option>
<option value="福大前">福大前</option>
<option value="七隈">七隈</option>
<option value="金山">金山</option>
<option value="茶山">茶山</option>
<option value="別府">別府</option>
<option value="六本松">六本松</option>
<option value="桜坂">桜坂</option>
<option value="薬院大通">薬院大通</option>
<option value="薬院">薬院</option>
<option value="渡辺通">渡辺通</option>
<option value="天神南">天神南</option>
<option value="下山門">JR筑肥線(下山門)</option>
<option value="今宿">JR筑肥線(今宿)</option>
<option value="九大学研都市">JR筑肥線(九大学研都市)</option>
<option value="周船寺">JR筑肥線(周船寺)</option>
<option value="波多江">JR筑肥線(波多江)</option>
<option value="筑前前原">JR筑肥線(筑前前原)</option>
<option value="美咲が丘">JR筑肥線(美咲が丘)</option>
<option value="加布里">JR筑肥線(加布里)</option>
<option value="一貴山">JR筑肥線(一貴山)</option>
<option value="筑前深江">JR筑肥線(筑前深江)</option>
<option value="大入">JR筑肥線(大入)</option>
<option value="福吉">JR筑肥線(福吉)</option>
<option value="鹿家">JR筑肥線(鹿家)</option>
<option value="浜崎">JR筑肥線(浜崎)</option>
<option value="虹ノ松原">JR筑肥線(虹ノ松原)</option>
<option value="東唐津">JR筑肥線(東唐津)</option>
<option value="和多田">JR筑肥線(和多田)</option>
<option value="唐津">JR筑肥線(唐津)</option>
<option value="西唐津">JR筑肥線(西唐津)</option>
<option value="名島">貝塚線(名島)</option>
<option value="西鉄千早">貝塚線(西鉄千早)</option>
<option value="香椎宮前">貝塚線(香椎宮前)</option>
<option value="西鉄香椎">貝塚線(西鉄香椎)</option>
<option value="香椎花園前">貝塚線(香椎花園前)</option>
<option value="唐の原">貝塚線(唐の原)</option>
<option value="和白">貝塚線(和白)</option>
<option value="三苫">貝塚線(三苫)</option>
<option value="西鉄新宮">貝塚線(西鉄新宮)</option>
</select>
<br>

<div  style="font-weight:bold; color:blue; margin-top:4px; margin-bottom:4px; font-size: 70%;">
・リストは上から，　”空港線 → 箱崎線 → 七隈線 → JR筑肥線 → 西鉄貝塚線”の順に並んでいます。<br/>
・ＪＲ筑肥線，西鉄貝塚線の駅は着駅側で選択して下さい
</div>
						
<input type="submit" value="運賃検索">
</form>



<?php } else if($viewType == "Search") { global $php_data; ?>

<hr>
<center><font color="#0000DD">料金検索結果</font></center>
<hr>
【乗車区間】
<br>
<?php echo $php_data['fromEki'] . "～" . $php_data['toEki'];?>
<br>
【距離】
<br>
<?php echo $php_data['data']['distance'];?>km
<br>
<hr>
<center><font color="#0000DD">詳細情報</font></center>
<hr>
【乗車料金（円）】<br>
<font color="red">▼乗車料金</font><br>
大人 <?php echo $php_data['data']['fare']['fare_adult'];?>円
<?php if($php_data['data']['fare']['fare_child'] > 0){
	echo '(小児'  .  $php_data['data']['fare']['fare_child'] . '円)<br> ';
}
?>

<?php
if($php_data['data']['fare']['fare_welfare'] != '-')
{
	echo '<br><font color="red">▼福祉割引</font><br>大人' . $php_data['data']['fare']['fare_welfare'] . '円';
	if($php_data['data']['fare']['fare_child'] > 0){
		echo '(小児' . $php_data['data']['fare']['fare_welfare_child'] . '円)<br>';
	}
}	
if($php_data['data']['fare']['fare_adult']  == 100)
{
	echo '<br><font size="-2">※　地下鉄線内１駅区間については，おとなりきっぷ料金でご案内しております。詳しくは <a href="/cgi-bin/m/m_card.cgi?m=a">おとなりきっぷ詳細ページ</a>をご覧ください。</font>';
}
if($php_data['data']['fare']['fare_welfare'] != '-')
{		
	echo '<br><font size="-2">※　<a href="/cgi-bin/m/m_qa.cgi?mode=CATEPAGE&pa01_id=20140222175914_5926#20140222175914_5926">福祉割引料金の適用条件についてはこちら</a></font>';
}


?>


<hr>
【定期券（円）】<br>
<font color="red">●通勤（大人）</font><br>
･1ヶ月<?php echo $php_data['data']['teiki']['work1'];?><br>
･3ヶ月<?php echo $php_data['data']['teiki']['work3'];?><br>
･6ヶ月<?php echo $php_data['data']['teiki']['work6'];?><br>
<br>
<font color="red">●通学（大人）</font><br>
･1ヶ月<?php echo $php_data['data']['teiki']['college1'];?><br>
･3ヶ月<?php echo $php_data['data']['teiki']['college3'];?><br>
･6ヶ月<?php echo $php_data['data']['teiki']['college6'];?><br>
<br>
<?php if($php_data['data']['teiki']['senior1'] !== '-'){?>
<font color="red">●通学（高校）</font><br>
･1ヶ月<?php echo $php_data['data']['teiki']['senior1'];?><br>
･3ヶ月<?php echo $php_data['data']['teiki']['senior3'];?><br>
･6ヶ月<?php echo $php_data['data']['teiki']['senior6'];?><br>
<br>
<?php }?>


【ちかパス（円）】<br>
<font color="red">●通勤（大人）</font><br>
･1ヶ月<?php echo $php_data['data']['chikapass']['work1'];?><br>
･3ヶ月<?php echo $php_data['data']['chikapass']['work3'];?><br>
･6ヶ月<?php echo $php_data['data']['chikapass']['work6'];?><br>
<br>
<font color="red">●通学（大人）</font><br>
･1ヶ月<?php echo $php_data['data']['chikapass']['college1'];?><br>
･3ヶ月<?php echo $php_data['data']['chikapass']['college3'];?><br>
･6ヶ月<?php echo $php_data['data']['chikapass']['college6'];?><br>
<br>
<?php if($php_data['data']['teiki']['senior1'] !== '-'){?>
<font color="red">●通学（高校）</font><br>
･1ヶ月<?php echo $php_data['data']['chikapass']['senior1'];?><br>
･3ヶ月<?php echo $php_data['data']['chikapass']['senior3'];?><br>
･6ヶ月<?php echo $php_data['data']['chikapass']['senior6'];?><br>
<br>
<?php }?>
<font size="-2">※　小児・福祉割引定期料金は，大人の半額（10円未満切り上げ）です（地下鉄線内定期券に限る）</font><br>
<font size="-2">※　上記に記載の無い定期券については，<a href="/cgi-bin/m/index.cgi?p=int">お客様サービスセンター（各種案内）</a>までお問い合わせください。</font>
<hr>
<a href="./fare_index.php?p1=2">料金検索へ</a>
<?php } else { ?>
<hr>
<center><font color="#0000DD">料金検索結果</font></center>
<hr>
<font color="red"><?php echo $errormsg ?></font>
<p><a href="./fare_index.php?p1=2">≪再検索する</a></p>
<?php } ?>

<hr>
<a href="/cgi-bin/m/index.cgi?p=top">ﾄｯﾌﾟﾍﾟｰｼﾞへ</a>



</body></html>