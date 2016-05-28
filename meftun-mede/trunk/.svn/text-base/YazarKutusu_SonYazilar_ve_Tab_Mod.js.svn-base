// ----------------------------------------
// YAZAR KUTUSU ÝÇÝN TAB MENÜ GÖSTER
// ----------------------------------------
// Mod by Meftun MEDE
// www.meftunmede.com
// ----------------------------------------
jQuery(document).ready(function(b){b(".meftunmede-yk-tabs > div").hide();b(".meftunmede-yk-tabs > div:first-child").show();b(".meftunmede-yk-list li:first-child").addClass("active");b(".meftunmede-yk-list li a").click(function(){b(this).closest(".meftunmede-yk-wrapper").find("li").removeClass("active");b(this).parent().addClass("active");var c=b(this).attr("href");-1!=c.indexOf("#")&&(currentTabExp=c.split("#"),c="#"+currentTabExp[1]);b(this).closest(".meftunmede-yk-wrapper").find(".meftunmede-yk-tabs > div").hide();
b(c).show();return!1})});
// ----------------------------------------
// YAZAR KUTUSU ÝÇÝN SON YAZILARI GÖSTER
// ----------------------------------------
// Mod by Meftun MEDE
// www.meftunmede.com
// ----------------------------------------
function showrecentposts(b){for(var c=0;c<numposts;c++){var a=b.feed.entry[c],e=a.title.$t,g;if(c==b.feed.entry.length)break;for(var d=0;d<a.link.length;d++)if("alternate"==a.link[d].rel){g=a.link[d].href;break}var e=e.link(g),d="....",d=d.link(g),f=a.published.$t,h=f.substring(0,4),k=f.substring(5,7),f=f.substring(8,10),l=[,"Ocak","\u015eubat","Mart","Nisan","May\u0131s","Haziran","Temmuz","A\u011fustos","Eyl\u00fcl","Ekim","Kas\u0131m","Aral\u0131k"],a="content"in a?a.content.$t:"summary"in a?a.summary.$t:
"",a=a.replace(/<\S[^>]*>/g,"");document.write('<div class="meftunsonyazilar">');standardstyling&&document.write("<br/>");document.write(e);1==showpostdate&&document.write(" - "+f+" "+l[parseInt(k,10)]+" "+h);document.write('</div><div class="meftunsonyazilarsumm">');1==showpostsummary&&(standardstyling&&document.write(""),a.length<numchars?(standardstyling&&document.write("<i>"),document.write(a),standardstyling&&document.write("</i>")):(standardstyling&&document.write(""),a=a.substring(0,numchars),
e=a.lastIndexOf(" "),a=a.substring(0,e),document.write(a+" "+d),standardstyling&&document.write("")));document.write("</div>");standardstyling&&document.write("")}standardstyling||document.write('<div class="meftunwidgetfooter">');standardstyling&&document.write("");document.write("");standardstyling||document.write("")};