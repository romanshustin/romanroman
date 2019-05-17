<!DOCTYPE html>
<html>
<head>
<title> Немношко о смайликах </title>
</head>
<body>
<header> <h1> <p align="center" <div name="message"> Немношко о смайликах </div></header></h1></p>
<div style = "background-color:#FFE4E1">
<div name="message"><span style = "color:red"> Улыбка </span>
<span><img src="https://avatars.mds.yandex.net/get-pdb/1779909/7cdb26d9-d8f5-46ee-aca5-49e911677572/s1200?webp=false "width=25" width="15" height="25"" ></span>
<div name="message"> Улыбка ето круто </div>
<p> <div name="message">Ещё <span style = "color:gray"> улыбка </span>
<span><img src="https://otvet.imgsmail.ru/download/71119681_30f88d79bcdbada2725083c7e44703fc_800.png "width=25" width="15" height="25"" ></span>
<div name="message"> Улыбаться еще сильнее - вообще пездос как круто </div>
<p> <div name="message"> <span style = "background-color:orangered">Типа</span> <span style = "color:green">ржака</span>
<span><img src="http://wallpaperget.com/images/happy-images-23.png "width=25" width="15" height="25"" ></span>
<div name="message"> Когда орёшь вот ето и есть ржака </div>
<p> <div name="message">Грустб </span> 
<span><img src=https://i.ya-webdesign.com/images/crying-smiley-png-2.png "width=25" width="25" height="25"" ></span>
<div name="message"> Грустишь - получаешь пиздюля-кебаб </span>
<p><span><img src=http://shaurmamarket.ru/assets/images/products/28/31.png "width=250" width="400" height="300"" ></span>
<script type="text/javascript">
var elems = document.getElementsByName("message");
var smiles = [":)",":D",":-)",":("];
for(var i=0; i<elems.length; i++) 
{
    for (var x=4;x<smiles.length;x++)
    {
    if (elems[i].innerHTML.indexOf(smiles[x])>-1)
        {
            elems[i].innerHTML = elems[i].innerHTML.replace(smiles[x],"<img title=\""+smiles[x]+"\" src=\"smile.gif\">");
        }
    }

}

</script>
</body>
