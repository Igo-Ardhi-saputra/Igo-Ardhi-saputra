# Igo-Ardhi-saputra.github.io

<!DOCTYPE HTML>
<html>
<head><title>Hai febb</title>
<!-- Created By L3M4R1 -->
<script>alert ('Hallo Febri')
alert ('Semoga kamu selalu sehat yahh ;)')</script>
<script language="JavaScript"> 
 
function tb5_makeArray(n){
 this.length = n;
 return this.length;
}
 
tb5_messages = new tb5_makeArray(7);
tb5_messages[0] = "Hallo Febb";
tb5_messages[1] = "Aku Mau Kamu Tau";
tb5_messages[2] = "Aku Sayang Sama Kamu";
tb5_messages[3] = "Aku Serius Febb";
//tb5_messages[4] = "Kamu Mau Ngga Jadi Pacar ku";
//tb5_messages[5] = "Aku berharap kamu menerimanya";
tb5_messages[6] = "I Love You FEBRII!!!";
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
</br><center><a href="http://L3m4r1.blogspot.com"><img src="https://d5f1t0vbfwydq.cloudfront.net/public/wp-content/uploads/2021/05/anime-romance-your-name-750x427.jpg"alt="Lolykuu" width="30% atau xpx" height="40% atau ypx"/></a> 
</head>
<body BGCOLOR="black">
<center><center>
<br><font size="6"><font color="red" face="courier new">Dewi Febri Lestari</font>
<br><br><!-- Created By L3M4R1 -->
<font size="5"><font color="white" face="courier new">Sakbenere aku bingung feb arep ngomong seko ngendi, aku pengin ngomong langsung aring awakmu. Tapi ya mergo kahanan awak dewe due kesibukan masing" durung nemu wektu sing pas.</font>
<br><font size="5"><font color="white" face="courier new">Mungkin iki terlalu cepet, tapi roso wedi kelangan koe koyo mbien kae pas koe ngilang lewih gedi. Mumpung Saiki isih ono kesempatan aku ngewakneke awak.</font>
<br><font size="5"><font color="white" face="courier new">Aku seneng koe feb, aku ra ngerti carane ngomong sing bener kui piye. Tapi aku seneng karo awakmu febb, aku nyaman karo koe.</font>
<br><font size="5"><font color="white" face="courier new">Febriii, seko atiku sing paling jeru. Aku Suka kamu.</font>
<br><a href="https://api.whatsapp.com/send?phone=6289666451395&text=Ya%20aku%20Mau%20Mas"><input type="button" value="Yes I do" onclick="alert('Terima kasih febb, aku sayang kamu');" style="font size="8"></a><><><><a href="https://api.whatsapp.com/send?phone=6289666451395&text=Maaf%20aku%20belum%20bisa"><input type="button" value=" Im sorry" onclick="alert('Terima kasih atas waktumu febb, meskipun singkat namun berkesan,maaf aku belum bisa menjadi apa yang kamu harapkan :)');" style="font size="8"></a>
<br><br><br><hr color="red"><!-- Created By L3M4R1 -->
<font size="4"><font color="white" face="courier new">( Dari Aku, Untukmu)</font>
<marquee><font size="3.5"><font color="white" face="courier new">[IGO ARDHI SAPUTRA ~~~~~~~ IGO ARDHI SAPUTRA ~~~~~~~ IGO ARDHI SAPUTTA]</marquee>
<br><br><font size="3"><font color="white" face="courier new">" Oscar Wilde "</font>
<br><font size="2.5"><font color="white" face="courier new">[Aku mampu menghadapi segala bencana, kecuali satu. Kehilangan CINTA]</font>
<br><br><br><a href="http://m.facebook.com/L3M4R1.go.id"><input type="button" value="Contact me on facebook" onclick="alert('Loading, click ok');""></a>
</body>
<style type="text/css">
body, a:hover {cursor: url(http://cur.cursors-4u.net/cursors/cur-9/cur862.ani), url(http://cur.cursors-4u.net/cursors/cur-9/cur862.png), progress !important; 
</style>


</script>
<!-- copyright@2k19 by L3M4R1 --> <!-- Tolong jangan hapus copyright nya yah :v tolong hargai karya saya L3M4R1 -->
<iframe width="0%" height="0" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/314301457&color=%23ff5500&auto_play=true&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe>
</html>
