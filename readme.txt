<?php 
 global $device;
 global $viewType;
 global $errormsg;
?>

<html><head><meta http-equiv="Content-Type" content="text/html; charset=Shift_JIS"><title>�����s�n���S</title></head>
<body>
<center><img src="/mobile/img/logo.png" alt="�����s�n���S"></center><br>

<?php if($viewType == "Index") { ?>
<hr>
<center><font color="#0000DD">��������</font></center>
<hr>
<font color="#009900">�����w����w��I�����ĉ������</font>
<hr>

<form action="./fare_index.php?p1=<?php echo $device ?>" method="get" name="ST">
<input type="hidden" name="m" value="search">
<input type="hidden" name="p1" value="<?php echo $device ?>">

�����w�� <br>
�@<select name="s1">
<option value="">���w����I��</option>
<option value="�Õl" >�Õl</option>
<option value="����" >����</option>
<option value="����" >����</option>
<option value="���V" >���V</option>
<option value="���l��" >���l��</option>
<option value="�半����" >�半����</option>
<option value="�ԍ�" >�ԍ�</option>
<option value="�V�_" >�V�_</option>
<option value="���F��[" >���F��[</option>
<option value="�_��" >�_��</option>
<option value="����" >����</option>
<option value="����b" >����b</option>
<option value="������`" >������`</option>
<option value="������" >������</option>
<option value="��㌧����" >��㌧����</option>
<option value="�n�o���a�@�O" >�n�o���a�@�O</option>
<option value="����{�O" >����{�O</option>
<option value="������O" >������O</option>
<option value="�L��" >�L��</option>
<option value="���{">���{</option>
<option value="���Y��">���Y��</option>
<option value="���">���</option>
<option value="��H">��H</option>
<option value="�~��">�~��</option>
<option value="����O">����O</option>
<option value="���G">���G</option>
<option value="���R">���R</option>
<option value="���R">���R</option>
<option value="�ʕ{">�ʕ{</option>
<option value="�Z�{��">�Z�{��</option>
<option value="����">����</option>
<option value="��@���">��@���</option>
<option value="��@">��@</option>
<option value="�n�Ӓ�">�n�Ӓ�</option>
<option value="�V�_��">�V�_��</option>
</select>
<br>
�����w�� <br>
�@<select name="s2">
<option value="">���w����I��</option>
<option value="�Õl" >�Õl</option>
<option value="����" >����</option>
<option value="����" >����</option>
<option value="���V" >���V</option>
<option value="���l��" >���l��</option>
<option value="�半����" >�半����</option>
<option value="�ԍ�" >�ԍ�</option>
<option value="�V�_" >�V�_</option>
<option value="���F��[" >���F��[</option>
<option value="�_��" >�_��</option>
<option value="����" >����</option>
<option value="����b" >����b</option>
<option value="������`" >������`</option>
<option value="������" >������</option>
<option value="��㌧����" >��㌧����</option>
<option value="�n�o���a�@�O" >�n�o���a�@�O</option>
<option value="����{�O" >����{�O</option>
<option value="������O" >������O</option>
<option value="�L��" >�L��</option>
<option value="���{">���{</option>
<option value="���Y��">���Y��</option>
<option value="���">���</option>
<option value="��H">��H</option>
<option value="�~��">�~��</option>
<option value="����O">����O</option>
<option value="���G">���G</option>
<option value="���R">���R</option>
<option value="���R">���R</option>
<option value="�ʕ{">�ʕ{</option>
<option value="�Z�{��">�Z�{��</option>
<option value="����">����</option>
<option value="��@���">��@���</option>
<option value="��@">��@</option>
<option value="�n�Ӓ�">�n�Ӓ�</option>
<option value="�V�_��">�V�_��</option>
<option value="���R��">JR�}���(���R��)</option>
<option value="���h">JR�}���(���h)</option>
<option value="���w���s�s">JR�}���(���w���s�s)</option>
<option value="���D��">JR�}���(���D��)</option>
<option value="�g���]">JR�}���(�g���])</option>
<option value="�}�O�O��">JR�}���(�}�O�O��)</option>
<option value="���炪�u">JR�}���(���炪�u)</option>
<option value="���z��">JR�}���(���z��)</option>
<option value="��M�R">JR�}���(��M�R)</option>
<option value="�}�O�[�]">JR�}���(�}�O�[�])</option>
<option value="���">JR�}���(���)</option>
<option value="���g">JR�}���(���g)</option>
<option value="����">JR�}���(����)</option>
<option value="�l��">JR�}���(�l��)</option>
<option value="���m����">JR�}���(���m����)</option>
<option value="������">JR�}���(������)</option>
<option value="�a���c">JR�}���(�a���c)</option>
<option value="����">JR�}���(����)</option>
<option value="������">JR�}���(������)</option>
<option value="����">�L�ː�(����)</option>
<option value="���S�瑁">�L�ː�(���S�瑁)</option>
<option value="���ŋ{�O">�L�ː�(���ŋ{�O)</option>
<option value="���S����">�L�ː�(���S����)</option>
<option value="���ŉԉ��O">�L�ː�(���ŉԉ��O)</option>
<option value="���̌�">�L�ː�(���̌�)</option>
<option value="�a��">�L�ː�(�a��)</option>
<option value="�O��">�L�ː�(�O��)</option>
<option value="���S�V�{">�L�ː�(���S�V�{)</option>
</select>
<br>

<div  style="font-weight:bold; color:blue; margin-top:4px; margin-bottom:4px; font-size: 70%;">
�E���X�g�͏ォ��C�@�h��`�� �� ����� �� ���G�� �� JR�}��� �� ���S�L�ː��h�̏��ɕ���ł��܂��B<br/>
�E�i�q�}����C���S�L�ː��̉w�͒��w���őI�����ĉ�����
</div>
						
<input type="submit" value="�^������">
</form>



<?php } else if($viewType == "Search") { global $php_data; ?>

<hr>
<center><font color="#0000DD">������������</font></center>
<hr>
�y��ԋ�ԁz
<br>
<?php echo $php_data['fromEki'] . "�`" . $php_data['toEki'];?>
<br>
�y�����z
<br>
<?php echo $php_data['data']['distance'];?>km
<br>
<hr>
<center><font color="#0000DD">�ڍ׏��</font></center>
<hr>
�y��ԗ����i�~�j�z<br>
<font color="red">����ԗ���</font><br>
��l <?php echo $php_data['data']['fare']['fare_adult'];?>�~
<?php if($php_data['data']['fare']['fare_child'] > 0){
	echo '(����'  .  $php_data['data']['fare']['fare_child'] . '�~)<br> ';
}
?>

<?php
if($php_data['data']['fare']['fare_welfare'] != '-')
{
	echo '<br><font color="red">����������</font><br>��l' . $php_data['data']['fare']['fare_welfare'] . '�~';
	if($php_data['data']['fare']['fare_child'] > 0){
		echo '(����' . $php_data['data']['fare']['fare_welfare_child'] . '�~)<br>';
	}
}	
if($php_data['data']['fare']['fare_adult']  == 100)
{
	echo '<br><font size="-2">���@�n���S�����P�w��Ԃɂ��ẮC���ƂȂ肫���՗����ł��ē����Ă���܂��B�ڂ����� <a href="/cgi-bin/m/m_card.cgi?m=a">���ƂȂ肫���Տڍ׃y�[�W</a>���������������B</font>';
}
if($php_data['data']['fare']['fare_welfare'] != '-')
{		
	echo '<br><font size="-2">���@<a href="/cgi-bin/m/m_qa.cgi?mode=CATEPAGE&pa01_id=20140222175914_5926#20140222175914_5926">�������������̓K�p�����ɂ��Ă͂�����</a></font>';
}


?>


<hr>
�y������i�~�j�z<br>
<font color="red">���ʋ΁i��l�j</font><br>
�1����<?php echo $php_data['data']['teiki']['work1'];?><br>
�3����<?php echo $php_data['data']['teiki']['work3'];?><br>
�6����<?php echo $php_data['data']['teiki']['work6'];?><br>
<br>
<font color="red">���ʊw�i��l�j</font><br>
�1����<?php echo $php_data['data']['teiki']['college1'];?><br>
�3����<?php echo $php_data['data']['teiki']['college3'];?><br>
�6����<?php echo $php_data['data']['teiki']['college6'];?><br>
<br>
<?php if($php_data['data']['teiki']['senior1'] !== '-'){?>
<font color="red">���ʊw�i���Z�j</font><br>
�1����<?php echo $php_data['data']['teiki']['senior1'];?><br>
�3����<?php echo $php_data['data']['teiki']['senior3'];?><br>
�6����<?php echo $php_data['data']['teiki']['senior6'];?><br>
<br>
<?php }?>


�y�����p�X�i�~�j�z<br>
<font color="red">���ʋ΁i��l�j</font><br>
�1����<?php echo $php_data['data']['chikapass']['work1'];?><br>
�3����<?php echo $php_data['data']['chikapass']['work3'];?><br>
�6����<?php echo $php_data['data']['chikapass']['work6'];?><br>
<br>
<font color="red">���ʊw�i��l�j</font><br>
�1����<?php echo $php_data['data']['chikapass']['college1'];?><br>
�3����<?php echo $php_data['data']['chikapass']['college3'];?><br>
�6����<?php echo $php_data['data']['chikapass']['college6'];?><br>
<br>
<?php if($php_data['data']['teiki']['senior1'] !== '-'){?>
<font color="red">���ʊw�i���Z�j</font><br>
�1����<?php echo $php_data['data']['chikapass']['senior1'];?><br>
�3����<?php echo $php_data['data']['chikapass']['senior3'];?><br>
�6����<?php echo $php_data['data']['chikapass']['senior6'];?><br>
<br>
<?php }?>
<font size="-2">���@�����E����������������́C��l�̔��z�i10�~�����؂�グ�j�ł��i�n���S����������Ɍ���j</font><br>
<font size="-2">���@��L�ɋL�ڂ̖���������ɂ��ẮC<a href="/cgi-bin/m/index.cgi?p=int">���q�l�T�[�r�X�Z���^�[�i�e��ē��j</a>�܂ł��₢���킹���������B</font>
<hr>
<a href="./fare_index.php?p1=2">����������</a>
<?php } else { ?>
<hr>
<center><font color="#0000DD">������������</font></center>
<hr>
<font color="red"><?php echo $errormsg ?></font>
<p><a href="./fare_index.php?p1=2">��Č�������</a></p>
<?php } ?>

<hr>
<a href="/cgi-bin/m/index.cgi?p=top">į���߰�ނ�</a>



</body></html>