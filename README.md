
<html><head>
<br>
<p align="center"> <img src="https://scontent.fpku1-1.fna.fbcdn.net/v/t1.0-9/s851x315/44057268_310008729833650_3327749822106042368_n.jpg?_nc_cat=105&_nc_eui2=AeFh4IpAg7au8POH8Iv0uzmMm-NXa_j1KwU44qHEZdMZ_-s9pe98-uswDNhm0kG94zsq75I08N2jlT_DOp_wFxq9DTY_QLUUDea3N1LAiK2NycB5htcmxz57SLQ2Tt80HVM&_nc_ht=scontent.fpku1-1.fna&oh=d3bda02e1b3a223a0e60447edbf1b9de&oe=5C582CBC"> </p>
</br>
<title>Touched By Mr.MythStyx </title>
<link rel="icon" href="none" type="image/x-icon" />
<link rel="shortcut icon" href="none" type="image/x-icon" />
<style type="text/css">
<!--
.ahgcrewstyle {
        color: #F00;
}
.ahg {
        color: #0F0;
}
#message font strong {
        font-family: Tahoma, Geneva, sans-serif;
        font-size: 18px;
}
.gre {
        color: #9F3;
        font-size: 36px;
}
#message font {
        font-size: 16px;
}
-->
</style>
</head><body alink="gray" bgcolor="black" vlink="gray" link="gray" text="gray">
<p></p><center>
<center></center>
<script type="text/javascript">
TypingText = function(element, interval, cursor, finishedCallback) {
  if((typeof document.getElementById == "undefined") || (typeof element.innerHTML == "undefined")) {
    this.running = true;
    return;
  }
  this.element = element;
  this.finishedCallback = (finishedCallback ? finishedCallback : function() { return; });
  this.interval = (typeof interval == "undefined" ? 100 : interval);
  this.origText = this.element.innerHTML;
  this.unparsedOrigText = this.origText;
  this.cursor = (cursor ? cursor : "");
  this.currentText = "";
  this.currentChar = 0;
  this.element.typingText = this;
  if(this.element.id == "") this.element.id = "typingtext" + TypingText.currentIndex++;
  TypingText.all.push(this);
  this.running = false;
  this.inTag = false;
  this.tagBuffer = "";
  this.inHTMLEntity = false;
  this.HTMLEntityBuffer = "";
}
TypingText.all = new Array();
TypingText.currentIndex = 0;
TypingText.runAll = function() {
  for(var i = 0; i < TypingText.all.length; i++) TypingText.all[i].run();
}
TypingText.prototype.run = function() {
 if(this.running) return;
 if(typeof this.origText == "undefined") {
   setTimeout("document.getElementById('" + this.element.id + "').typingText.run()", this.interval);
   return;
 }
 if(this.currentText == "") this.element.innerHTML = "";
 if(this.currentChar < this.origText.length) {
   if(this.origText.charAt(this.currentChar) == "<" && !this.inTag) {
     this.tagBuffer = "<";
     this.inTag = true;
     this.currentChar++;
     this.run();
     return;
   } else if(this.origText.charAt(this.currentChar) == ">" && this.inTag) {
     this.tagBuffer += ">";
      this.inTag = false;
      this.currentText += this.tagBuffer;
      this.currentChar++;
      this.run();
      return;
    } else if(this.inTag) {
      this.tagBuffer += this.origText.charAt(this.currentChar);
      this.currentChar++;
      this.run();
      return;
    } else if(this.origText.charAt(this.currentChar) == "&" && !this.inHTMLEntity) {
     this.HTMLEntityBuffer = "&";
      this.inHTMLEntity = true;
      this.currentChar++;
      this.run();
      return;
    } else if(this.origText.charAt(this.currentChar) == ";" && this.inHTMLEntity) {
     this.HTMLEntityBuffer += ";";
      this.inHTMLEntity = false;
      this.currentText += this.HTMLEntityBuffer;
      this.currentChar++;
      this.run();
      return;
    } else if(this.inHTMLEntity) {
      this.HTMLEntityBuffer += this.origText.charAt(this.currentChar);
      this.currentChar++;
      this.run();
      return;
    } else {
      this.currentText += this.origText.charAt(this.currentChar);
    }
    this.element.innerHTML = this.currentText;
    this.element.innerHTML += (this.currentChar < this.origText.length - 1 ? (typeof this.cursor == "function" ? this.cursor(this.currentText) : this.cursor) : "");
   this.currentChar++;
   setTimeout("document.getElementById('" + this.element.id + "').typingText.run()", this.interval);
 } else {
        this.currentText = "";
        this.currentChar = 0;
       this.running = false;
       this.finishedCallback();
 }
}
</script>
<center>
  <b class="Gre">Explosion Squad Cyber</b>
  <br>
  <font>
</font><p id="message"><font> <strong><br>We Are ESC<br>
<br>We Are Legion<br>
<br>We Don't Forget<br>
<br>We Don't Forgive<br>
<br>Expect Us!<br>
 <br>
 [ Explosion Squad Cyber ]</strong><br>
<br>
[ <span class="ahgcrewstyle"><strong><strong>My Friends: ./Mr onion ./ebi404 ./kamarM4yaT404 ./Mr.Plug1n ./X404_LOSER ./XssNuser404 ./Mr.Xcyber ./.ZEROH3RO ./Mr.EM3RG3NCY </strong></strong></span><strong> ] <br>
</font></p>
<p align="center"><em>Thanks To</em>: <b><font size="6"><span class="ahgcrewstyle">Anonymous Black Shadow</span></font></b></p>
<p><font><br>
 <br>
 <p align="center"><font color="red" size="+1" face="Times New Roman"> <br>NO SYSTEM<br>IS<br>SAFE<br></p>
<div class="fb-like-box" data-href="https://www.facebook.com/IndonesiaFighterCyber" data-width="292" data-show-faces="false" data-stream="false" data-header="false"></div>
<div id="fb-root"></div>
<script>(function(d, s, id) {
 var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_US/all.js#xfbml=1&appId=384191914936497";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));</script>
<p align="center"><font size="8" face="Times New Roman"><font color="red"> YOUR <font color="red"> SYSTEM <font color="red"> ARE <font color="red"> EXPLODED</p>
<script>alert('This Site Hacked By Mr.MythStyx');</script>
<script>alert('I'm Just A Script Kiddie');</script>
<p align="center">
  <script type="text/javascript">
new TypingText(document.getElementById("message"), 50, function(i){ var ar = new Array("\\", "|", "/", "-"); return " " + ar[i.length % ar.length]; });
//Type out examples:
TypingText.runAll();
  </script>
</font></p>
</center></center>
</body></html>
<!-- aghaze larzeshe safhe-->
<meta http-equiv="Content-Language" content="en-us">
<SCRIPT language=JavaScript>
<!-- Begin
function shake(n) {
if (parent.moveBy) {
for (i = 10; i > 0; i--) {
for (j = n; j > 0; j--) {
parent.moveBy(-i,0);
parent.moveBy(0,-i);
parent.moveBy(-i,0);
parent.moveBy(0,i);
parent.moveBy(i,0);
parent.moveBy(0,-i);
parent.moveBy(-i,0);
parent.moveBy(0,i);
parent.moveBy(i,0);
parent.moveBy(0,-i);
parent.moveBy(-i,0);
parent.moveBy(0,-i);
parent.moveBy(i,0);
parent.moveBy(0,i);
parent.moveBy(i,0);
parent.moveBy(0,i);
        }
     }
  }
}
//  End -->
<!--
shake(1);
//-->
</SCRIPT>
<!-- p align="center"><font size="7" color="#FF0000">chi?</font></p> -->
<!--payan--></SCRIPT>
</body>
</html>
</body>
</html>
<P align=center></P>
<style>
