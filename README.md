## hacknetGUI

ハッキングされたとき,下の画面を表示して使う。

https://kanai-kiyoshi.github.io/incoming-connection/


### 使い方

次のリンクをブックマークに保存します。

[Google](`javascript:(()=>{var $jscomp=$jscomp||{};$jscomp.scope={};$jscomp.createTemplateTagFirstArg=function(b){return b.raw=b};$jscomp.createTemplateTagFirstArgWithRaw=function(b,c){b.raw=c;return b}; function doThis(){var b=document.getElementsByTagName("belt")[0],c=document.getElementsByTagName("triangle")[0],a=document.getElementsByTagName("message")[0];b.style.visibility="visible";b.animate([{height:"40px"},{height:"15vh"}],{duration:250,fill:"forwards"});c.style.visibility="visible";c.animate([{transform:"scale(0)"},{transform:"scale(1)"}],{duration:250,fill:"forwards"});a.style.visibility="visible";a.animate([{transform:"scale(0)"},{transform:"scale(1)"}],{duration:250,fill:"forwards"})} function load(){console.log("load");var b=document.createElement("link");b.setAttribute("href","https://fonts.cdnfonts.com/css/politik");b.setAttribute("rel","stylesheet");document.getElementsByTagName("head")[0].appendChild(b);console.log("here");b=document.createElement("div");b.style.clear="both";document.getElementsByTagName("body")[0].appendChild(b);b=document.createElement("belt");Object.assign(b.style,{display:"inline-block",position:"fixed",width:"calc(100% + 16px)",top:"50vh",left:"-8px", transform:"translateY(-50%)",backgroundColor:"black",boxSizing:"border-box",overflow:"hidden",zIndex:2147483647,visibility:"hidden"});document.getElementsByTagName("body")[0].appendChild(b);for(var c=(window.innerWidth/40|0)+4,a=0;a<2*c;a++){var d=document.createElement("parallelogram");a<c?(d.style.top=%220px%22,d.style.left=40*(a-1)+%22px%22):(d.style.bottom=%220px%22,d.style.left=40*(a-1-c)+%22px%22);Object.assign(d.style,{display:%22inline-block%22,position:%22absolute%22,width:%2218px%22,height:%2220px%22,backgroundColor:%22red%22,%20transform:%22skewX(-45deg)%22});b.appendChild(d)}a=document.createElement(%22popup%22);Object.assign(a.style,{display:%22inline-block%22,position:%22fixed%22,width:%22calc(100%%20+%2016px)%22,top:%2250vh%22,left:%22-8px%22,transform:%22translateY(-50%)%22,boxSizing:%22border-box%22,overflow:%22visible%22,zIndex:2147483647,textAlign:%22center%22});document.getElementsByTagName(%22body%22)[0].appendChild(a);c=document.createElement(%22triangle%22);c.innerHTML=%27\n\t%3Csvg%20viewbox=%22-22%20-22%20144%20130%22%20style=%22%22%3E\n\t\t%3Cpath%20stroke=%22black%22%20fill=%22black%22\n\t\t\td=%22\n\t\t\t\tM%2050%200\n\t\t\t\tL%200,%2086\n\t\t\t\tL%20100%2086\n\t\t\t\tz\n\t\t\t%22\n\t\t\tstroke-linecap=%22round%22\n\t\t\tstroke-linejoin=%22round%22\n\t\t\tstroke-width=%2244%22\n\t\t%3E%3C/path%3E\n\t\t%3Cpath%20stroke=%22red%22%20fill=%22red%22\n\t\t\td=%22\n\t\t\t\tM%2050%200\n\t\t\t\tL%200,%2086\n\t\t\t\tL%20100%2086\n\t\t\t\tz\n\t\t\t%22\n\t\t\tstroke-linecap=%22round%22\n\t\t\tstroke-linejoin=%22round%22\n\t\t\tstroke-width=%2240%22\n\t\t%3E%3C/path%3E\n\t\t%3Cpath%20stroke=%22black%22%20fill=%22black%22\n\t\t\td=%22\n\t\t\t\tM%2050%200\n\t\t\t\tL%200,%2086\n\t\t\t\tL%20100%2086\n\t\t\t\tz\n\t\t\t%22\n\t\t\tstroke-linecap=%22round%22\n\t\t\tstroke-linejoin=%22round%22\n\t\t\tstroke-width=%2220%22\n\t\t%3E%3C/path%3E\n\t\t%3Cpath%20stroke=%22red%22\n\t\t\td=%22\n\t\t\t\tM%2050%2020\n\t\t\t\tL%2050,%2050\n\t\t\t%22\n\t\t\tstroke-linecap=%22round%22\n\t\t\tstroke-linejoin=%22round%22\n\t\t\tstroke-width=%2220%22\n\t\t%3E%3C/path%3E\n\t\t%3Ccircle%20cx=%2250%22%20cy=%2276%22%20r=%2210%22\n\t\tfill=%22red%22\n\t\t%3E\n\t%3C/svg%3E\n\t%27;%20Object.assign(c.style,{display:%22inline-block%22,position:%22relative%22,width:%2220vh%22,height:%2218vh%22,top:%220px%22,textAlign:%22left%22,verticalAlign:%22middle%22,visibility:%22hidden%22});a.appendChild(c);c=document.createElement(%22message%22);Object.assign(c.style,{display:%22inline-block%22,position:%22relative%22,width:%22fit-content%22,height:%2215vh%22,top:%2222px%22,color:%22red%22,textAlign:%22left%22,verticalAlign:%22middle%22,whiteSpace:%22pre%22,visibility:%22hidden%22});a.appendChild(c);a=document.createElement(%22div%22);a.innerText=%22INCOMING%20CONNECTION%22;%20Object.assign(a.style,{fontSize:%22calc(8vh%20-%2024px)%22,fontFamily:%22Politik%22,lineHeight:%220.6em%22,whiteSpace:%22pre-line%22});c.appendChild(a);a=document.createElement(%22div%22);a.innerHTML=%22\n\t\t%3Cspan%3E\n\t\t\tExternal%20unsyndicated%20UDP%20traffic%20on%20port%2022\n\t\t%3C/span%3E\n\t\t%3Cspan%3E\n\t\t\tLogging%20all%20activity%20to%20~/Logging\n\t\t%3C/span%3E\n\t%22;Object.assign(a.style,{fontSize:%22calc((8vh%20-%2024px)*0.3)%22,fontFamily:%22monospace%22,lineHeight:%220.6em%22,whiteSpace:%22pre-line%22});c.appendChild(a);b.querySelectorAll(%22parallelogram%22).forEach(function(e){var%20f=%20~~e.style.left.slice(0,-2);e.animate([{left:f+%22px%22},{left:f+40+%22px%22}],{duration:1E3,iterations:Infinity})});setTimeout(doThis,1E3)}load();})();`)


適当なページを開いて、ブックマークレットを実行します。
