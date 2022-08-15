#### script html for Yuii
```bash
    <!DOCTYPE HTML>
<html>
<head><title>Hai oncom</title>
<!-- Created By Yuli -->
<script>alert ('hai')
alert ('Ini isi hatiku yang sesungguhnya')</script>
<script language="JavaScript"> 
 
function tb5_makeArray(n){
 this.length = n;
 return this.length;
}
 
tb5_messages = new tb5_makeArray(7);
tb5_messages[0] = "Hay tod";
tb5_messages[1] = "Aku Mau Kamu Tau";
tb5_messages[2] = "Kalo Bakwan oncom itu enak";
tb5_messages[3] = "Aku Serius tod";
tb5_messages[4] = "Kamu Mau Ngga Jadi Makanan aku";
tb5_messages[5] = "Aku berharap kamu menerimanya";
tb5_messages[6] = "I Love You oncom!!!";
tb5_rptType = 'infinite';
tb5_rptNbr = 20;
tb5_speed = 30;
tb5_delay = 2000;
var tb5_counter=2;
var tb5_currMsg=0;
var tb5_stsmsg="";
function tb5_shuffle(arr){
var k;
for (i=0; i<arr.length; i++){
 k = Math.round(Math.random() * (arr.length - i - 1)) + i;
 temp = arr[i];arr[i]=arr[k];arr[k]=temp;
}
return arr;
}
tb5_arr = new tb5_makeArray(tb5_messages[tb5_currMsg].length);
tb5_sts = new tb5_makeArray(tb5_messages[tb5_currMsg].length);
for (var i=0; i<tb5_messages[tb5_currMsg].length; i++){
 tb5_arr[i] = i;
 tb5_sts[i] = "_";
}
tb5_arr = tb5_shuffle(tb5_arr);
function tb5_init(n){
var k;
if (n == tb5_arr.length){
 if (tb5_currMsg == tb5_messages.length-1){
 if ((tb5_rptType == 'finite') && (tb5_counter==tb5_rptNbr)){
 clearTimeout(tb5_timerID);
 return;
 }
 tb5_counter++;
 tb5_currMsg=0;
 }
 else{
 tb5_currMsg++;
 }
 n=0;
 tb5_arr = new tb5_makeArray(tb5_messages[tb5_currMsg].length);
 tb5_sts = new tb5_makeArray(tb5_messages[tb5_currMsg].length);
 for (var i=0; i<tb5_messages[tb5_currMsg].length; i++){
 tb5_arr[i] = i;
 tb5_sts[i] = "_";
 }
 tb5_arr = tb5_shuffle(tb5_arr);
 tb5_sp=tb5_delay;
}
else{
 tb5_sp=tb5_speed;
 k = tb5_arr[n];
 tb5_sts[k] = tb5_messages[tb5_currMsg].charAt(k);
 tb5_stsmsg = "";
 for (var i=0; i<tb5_sts.length; i++)
 tb5_stsmsg += tb5_sts[i];
 document.title = tb5_stsmsg;
 n++;
 }
 tb5_timerID = setTimeout("tb5_init("+n+")", tb5_sp);
}
function tb5_randomizetitle(){
 tb5_init(0);
}
tb5_randomizetitle();
 
</script>
</br><center><a href="https://github.com/Yuii042"><img src="https://assets.jalantikus.com/assets/cache/500/346/userfiles/2018/11/15/gambar-anime-romantis-10-3bbdd.jpg"alt="Lolykuu" width="30% atau xpx" height="40% atau ypx"/></a> 
</head>
<body BGCOLOR="black">
<center><center>
<br><font size="6"><font color="red" face="courier new">Touched by:Yuli404</font>
<br><br><!-- Created By Yuli -->
<font size="5"><font color="white" face="courier new">Hai ini dia isi hatiku yang sesungguhnya</font>
<br><font size="5"><font color="white" face="courier new">Selama ini ku hanya dapat diam dan berdoa kepada Yang Kuasa agar diri mu bisa bersamaku</font>
<br><font size="5"><font color="white" face="courier new">Namun kali ini Aku ingin mengutarakannya</font>
<br><font size="5"><font color="white" face="courier new">Mau ga jadi Makanan aku?!?</font>
<br><a href="https://api.whatsapp.com/send?phone=6283811179628text=Ya%20aku%20Mau%20Terima"><input type="button" value="Yes I do" onclick="alert('Thanks yah udah mau jadi Makanan akyuu');" style="font size="5"></a><><><><a href="https://api.whatsapp.com/send?phone=6283811179628text=maaf%20aku%20nggabisa%20Terima"><input type="button" value=" Im sorry" onclick="alert('Baik lah kalau itu mau mu ^_^');" style="font size="5"></a>
<br><br><br><hr color="red"><!-- Created By Yuli -->
<font size="4"><font color="white" face="courier new">("Thanks to:")</font>
<marquee><font size="3"><font color="white" face="courier new">[FCSI-Nanggul Black Hat-banten Cyber Ghost-Dark Force Army-Indonesia Cyber Lite-Cyber Patah Hati-Hacker Patah Hati-INSULINDER TEAM-Sora Cyber Team-Cyber Kacang Team-Galau Cyber Team-Never Die AFK Cyber-Dunsanak Cyber Security-Kentang Cyber Security-Lollycorp Team-GHD Cyber Army Team-JancoXploit-N45HT-coizter_team]</marquee>
<br><br><font size="4.5"><font color="white" face="courier new">My friends:)</font>
<br><font size="3.5"><font color="white" face="courier new">[My.Spicy sugars-Brilly4n-0N3FR13ND5-L4LA-S4K1LA-katenbad-5TUP1D-LADIES- All member MASK RABBIT Illusion]</font>
<br><br><br><a href="https://www.facebook.com/profile.php?id=100073210824165"><input type="button" value="Contact me on facebook" onclick="alert('Loading, click ok');""></a>
</body>
<style type="text/css">
body, a:hover {cursor: url(http://cur.cursors-4u.net/cursors/cur-9/cur862.ani), url(http://cur.cursors-4u.net/cursors/cur-9/cur862.png), progress !important; 
</style>



<style type="text/css">
