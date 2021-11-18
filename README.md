- 👋 Hi, I’m @JADHOE
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
JADHOE/JADHOE is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
V abt/readme info (#199) Créez et déployez l'application ASP.Net Core (Bot Receive channel messages with RSC) sur Azure Web App - rsc-fetch-messages #4
r Ce;_.Be=function(a,b){b=(0,_.ka)(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c};Ce=function(a,b){for(var c in a)if(b.call(void 0,a[c],c,a))return!0;return!1};_.De=function(a,b){try{return _.rb(a[b]),!0}catch(c){}return!1};
_.Fe=function(a,b){this.type="undefined"!=typeof _.Ee&&a instanceof _.Ee?String(a):a;this.currentTarget=this.target=b;this.defaultPrevented=this.j=!1};_.Fe.prototype.stopPropagation=function(){this.j=!0};_.Fe.prototype.preventDefault=function(){this.defaultPrevented=!0};
_.Ge=function(a,b){_.Fe.call(this,a?a.type:"");this.relatedTarget=this.currentTarget=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=this.offsetY=this.offsetX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.Xa=null;a&&this.init(a,b)};_.z(_.Ge,_.Fe);var He={2:"touch",3:"pen",4:"mouse"};
_.Ge.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.currentTarget=b;(b=a.relatedTarget)?_.vb&&(_.De(b,"nodeName")||(b=null)):"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||0):(this.offsetX=_.wb||void 0!==
a.offsetX?a.offsetX:a.layerX,this.offsetY=_.wb||void 0!==a.offsetY?a.offsetY:a.layerY,this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===
typeof a.pointerType?a.pointerType:He[a.pointerType]||"";this.state=a.state;this.Xa=a;a.defaultPrevented&&_.Ge.T.preventDefault.call(this)};_.Ge.prototype.stopPropagation=function(){_.Ge.T.stopPropagation.call(this);this.Xa.stopPropagation?this.Xa.stopPropagation():this.Xa.cancelBubble=!0};_.Ge.prototype.preventDefault=function(){_.Ge.T.preventDefault.call(this);var a=this.Xa;a.preventDefault?a.preventDefault():a.returnValue=!1};
_.Ie="closure_listenable_"+(1E6*Math.random()|0);_.Je=function(a){return!(!a||!a[_.Ie])};
var Ke=0;
var Le;Le=function(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.we=e;this.key=++Ke;this.Rd=this.me=!1};_.Me=function(a){a.Rd=!0;a.listener=null;a.proxy=null;a.src=null;a.we=null};
_.Ne=function(a){this.src=a;this.j={};this.o=0};_.Ne.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.j[f];a||(a=this.j[f]=[],this.o++);var g=Oe(a,b,d,e);-1<g?(b=a[g],c||(b.me=!1)):(b=new Le(b,this.src,f,!!d,e),b.me=c,a.push(b));return b};_.Ne.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.j))return!1;var e=this.j[a];b=Oe(e,b,c,d);return-1<b?(_.Me(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.j[a],this.o--),!0):!1};
_.Pe=function(a,b){var c=b.type;if(!(c in a.j))return!1;var d=_.Be(a.j[c],b);d&&(_.Me(b),0==a.j[c].length&&(delete a.j[c],a.o--));return d};_.Ne.prototype.te=function(a,b){a=this.j[a.toString()];var c=[];if(a)for(var d=0;d<a.length;++d){var e=a[d];e.capture==b&&c.push(e)}return c};_.Ne.prototype.Jd=function(a,b,c,d){a=this.j[a.toString()];var e=-1;a&&(e=Oe(a,b,c,d));return-1<e?a[e]:null};
_.Ne.prototype.hasListener=function(a,b){var c=void 0!==a,d=c?a.toString():"",e=void 0!==b;return Ce(this.j,function(f){for(var g=0;g<f.length;++g)if(!(c&&f[g].type!=d||e&&f[g].capture!=b))return!0;return!1})};var Oe=function(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.Rd&&f.listener==b&&f.capture==!!c&&f.we==d)return e}return-1};
var Qe,Re,Se,Ve,Xe,Ye,Ze,bf;Qe="closure_lm_"+(1E6*Math.random()|0);Re={};Se=0;_.P=function(a,b,c,d,e){if(d&&d.once)return _.Te(a,b,c,d,e);if(Array.isArray(b)){for(var f=0;f<b.length;f++)_.P(a,b[f],c,d,e);return null}c=_.Ue(c);return _.Je(a)?a.listen(b,c,_.$a(d)?!!d.capture:!!d,e):Ve(a,b,c,!1,d,e)};
Ve=function(a,b,c,d,e,f){if(!b)throw Error("G");var g=_.$a(e)?!!e.capture:!!e,k=_.We(a);k||(a[Qe]=k=new _.Ne(a));c=k.add(b,c,d,g,f);if(c.proxy)return c;d=Xe();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)_.Xd||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Ye(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("H");Se++;return c};
Xe=function(){var a=Ze,b=function(c){return a.call(b.src,b.listener,c)};return b};_.Te=function(a,b,c,d,e){if(Array.isArray(b)){for(var f=0;f<b.length;f++)_.Te(a,b[f],c,d,e);return null}c=_.Ue(c);return _.Je(a)?a.Ab(b,c,_.$a(d)?!!d.capture:!!d,e):Ve(a,b,c,!0,d,e)};_.$e=function(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)_.$e(a,b[f],c,d,e);else d=_.$a(d)?!!d.capture:!!d,c=_.Ue(c),_.Je(a)?a.Aa(b,c,d,e):a&&(a=_.We(a))&&(b=a.Jd(b,c,d,e))&&_.af(b)};
_.af=function(a){if("number"===typeof a||!a||a.Rd)return!1;var b=a.src;if(_.Je(b))return b.ih(a);var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Ye(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Se--;(c=_.We(b))?(_.Pe(c,a),0==c.o&&(c.src=null,b[Qe]=null)):_.Me(a);return!0};Ye=function(a){return a in Re?Re[a]:Re[a]="on"+a};
Ze=function(a,b){if(a.Rd)a=!0;else{b=new _.Ge(b,this);var c=a.listener,d=a.we||a.src;a.me&&_.af(a);a=c.call(d,b)}return a};_.We=function(a){a=a[Qe];return a instanceof _.Ne?a:null};bf="__closure_events_fn_"+(1E9*Math.random()>>>0);_.Ue=function(a){if("function"===typeof a)return a;a[bf]||(a[bf]=function(b){return a.handleEvent(b)});return a[bf]};

}catch(e){_._DumpException(e)}
try{
/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
_.cf=function(a){return 0==a.Xa.button&&!(_.xb&&a.ctrlKey)};
_.df=function(a){_.J.call(this);this.U=a;this.O={}};_.z(_.df,_.J);var ef=[];_.df.prototype.listen=function(a,b,c,d){return ff(this,a,b,c,d)};_.df.prototype.B=function(a,b,c,d,e){return ff(this,a,b,c,d,e)};var ff=function(a,b,c,d,e,f){Array.isArray(c)||(c&&(ef[0]=c.toString()),c=ef);for(var g=0;g<c.length;g++){var k=_.P(b,c[g],d||a.handleEvent,e||!1,f||a.U||a);if(!k)break;a.O[k.key]=k}return a};_.df.prototype.Ab=function(a,b,c,d){return gf(this,a,b,c,d)};
var gf=function(a,b,c,d,e,f){if(Array.isArray(c))for(var g=0;g<c.length;g++)gf(a,b,c[g],d,e,f);else{b=_.Te(b,c,d||a.handleEvent,e,f||a.U||a);if(!b)return a;a.O[b.key]=b}return a};_.df.prototype.Aa=function(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)this.Aa(a,b[f],c,d,e);else c=c||this.handleEvent,d=_.$a(d)?!!d.capture:!!d,e=e||this.U||this,c=_.Ue(c),d=!!d,b=_.Je(a)?a.Jd(b,c,d,e):a?(a=_.We(a))?a.Jd(b,c,d,e):null:null,b&&(_.af(b),delete this.O[b.key]);return this};
_.hf=function(a){_.Ba(a.O,function(b,c){this.O.hasOwnProperty(c)&&_.af(b)},a);a.O={}};_.df.prototype.R=function(){_.df.T.R.call(this);_.hf(this)};_.df.prototype.handleEvent=function(){throw Error("I");};
