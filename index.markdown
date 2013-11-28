---
layout: html5
slug: home
---

<div class="columntext">
  <span style="font-size:28px;">Nous nous marions le 16&nbsp;juin&nbsp;2012 apr&egrave;s-midi &agrave; la mairie de 
  <a style="text-decoration:none;" href="/ceremonie/">Clermont-Ferrand</a>. 
  Un cocktail sera ensuite servi à l'Espace culturel de <a style="text-decoration:none;" href="/cocktail/">Montpeyroux</a></span>.
</div>

<div class="columnsmall">
<h2 class="savethedate">Save the date!</h2>
<img style="margin-left:20px;" src="images/banniere.png" height="100px" alt="Marie et Raph" />
<form name="count">
<input class="countdown" type="text" size="180" name="count2">
</form>
<script>
/*
Count down until any date script-
By JavaScript Kit (www.javascriptkit.com)
Over 200+ free scripts here!
*/

//change the text below to reflect your own,
var before="notre mariage"
var current="C'est aujourd'hui !"
var montharray=new Array("Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec")

function countdown(yr,m,d,h,min){
theyear=yr;themonth=m;theday=d;thehour=h;themin=min;
var today=new Date()
var todayy=today.getYear()
if (todayy < 1000)
todayy+=1900
var todaym=today.getMonth()
var todayd=today.getDate()
var todayh=today.getHours()
var todaymin=today.getMinutes()
var todaysec=today.getSeconds()
var todaystring=montharray[todaym]+" "+todayd+", "+todayy+" "+todayh+":"+todaymin+":"+todaysec
futurestring=montharray[m-1]+" "+d+", "+yr+" "+h+":"+min+":"+"00"
dd=Date.parse(futurestring)-Date.parse(todaystring)
dday=Math.floor(dd/(60*60*1000*24)*1)
dhour=Math.floor((dd%(60*60*1000*24))/(60*60*1000)*1)
dmin=Math.floor(((dd%(60*60*1000*24))%(60*60*1000))/(60*1000)*1)
dsec=Math.floor((((dd%(60*60*1000*24))%(60*60*1000))%(60*1000))/1000*1)
if(dday==0&&dhour==0&&dmin==0&&dsec==1){
document.forms.count.count2.value=current
return
}
else
document.forms.count.count2.value="Plus que "+dday+ " jours, "+dhour+" heures et "+dmin+" minutes avant "+before+" !"
setTimeout("countdown(theyear,themonth,theday)",60000)
}
//enter the count down date using the format year/month/day
countdown(2012,6,16,15,0)
</script>
</div>

<div class="columnsmall">
<h2 class="savethedate">Save the date!</h2>
<img style="margin-left:20px;" src="images/banniere.png" height="100px" alt="Marie et Raph" />
</div>
