# Harshit-Team-Kalam-Website-Code-And-URL
<!DOCTYPE html>
<!-- saved from url=(0079)https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/ -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <script type="module">
import { createHotContext } from "/@vite/client";
const hot = createHotContext("/__dummy__runtime-error-plugin");

function sendError(error) {
  if (!(error instanceof Error)) {
    error = new Error("(unknown runtime error)");
  }
  const serialized = {
    message: error.message,
    stack: error.stack,
  };
  hot.send("runtime-error-plugin:error", serialized);
}

// Only notify the parent frame after the server confirms the error passed
// the filter and the overlay will be shown.
hot.on("runtime-error-plugin:notify-parent", () => {
  try {
    window.parent.postMessage({ type: "runtime-error", id: null }, "*");
  } catch (_) {}
});

window.addEventListener("error", (evt) => {
  sendError(evt.error);
});

window.addEventListener("unhandledrejection", (evt) => {
  sendError(evt.reason);
});
</script>

    <script type="module">import { injectIntoGlobalHook } from "/@react-refresh";
injectIntoGlobalHook(window);
window.$RefreshReg$ = () => {};
window.$RefreshSig$ = () => (type) => type;</script>

    <script type="module" src="./Team Kalam_files/client"></script>

    
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1">
    <title>Team Kalam</title>
    <meta name="description" content="Team Kalam — built on Replit. Update this description to reflect the app.">
    <meta name="robots" content="index, follow">
    <meta property="og:title" content="Team Kalam">
    <meta property="og:description" content="Team Kalam — built on Replit. Update this description to reflect the app.">
    <meta property="og:type" content="website">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Team Kalam">
    <meta name="twitter:description" content="Team Kalam — built on Replit. Update this description to reflect the app.">
    <link rel="icon" type="image/svg+xml" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/favicon.svg">
    <link rel="preconnect" href="https://fonts.googleapis.com/">
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="">
    <link href="./Team Kalam_files/css2" rel="stylesheet">
    <script type="module">"use strict";(()=>{var B="0.5.21";var y={HIGHLIGHT_COLOR:"#0079F2",HIGHLIGHT_BG:"#0079F210",ALLOWED_PARENT_DOMAINS:[".replit.dev",".replit.com",".replit-staging.com",".rp-humain.com",".repl.co"],THEME_PREVIEW_STYLE_ID:"replit-theme-preview",MAX_SIBLING_HIGHLIGHTERS:1e3,MAX_DESCENDANTS_FOR_SCREENSHOT:1500},oe=`
  [contenteditable] {
    outline: none !important;
  }

  [contenteditable]:focus {
    outline: none !important;
  }
`,se=`
  .beacon-highlighter {
    content: '';
    position: absolute;
    z-index: ${Number.MAX_SAFE_INTEGER-3};
    box-sizing: border-box;
    pointer-events: none;
    outline: 2px dashed ${y.HIGHLIGHT_COLOR} !important;
    outline-offset: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
    background: ${y.HIGHLIGHT_BG} !important;
    opacity: 0;
  }
  
  .beacon-hover-highlighter {
    position: fixed;
    z-index: ${Number.MAX_SAFE_INTEGER};
  }
  
  .beacon-selected-highlighter {
    position: fixed;
    pointer-events: none;
    outline: 2px solid ${y.HIGHLIGHT_COLOR} !important;
    outline-offset: 3px !important;
    background: none !important;
  }
  
  .beacon-label {
    position: absolute;
    background-color: ${y.HIGHLIGHT_COLOR};
    color: #FFFFFF;
    padding: 4px 8px;
    border-radius: 4px;
    font-size: 14px;
    font-family: monospace;
    line-height: 1;
    white-space: nowrap;
    box-shadow: 0 2px 4px rgba(0,0,0,0.2);
    transform: translateY(-100%);
    margin-top: -4px;
    left: 0;
    z-index: ${Number.MAX_SAFE_INTEGER-2};
    pointer-events: none;
    opacity: 0;
  }
  
  .beacon-hover-label {
    position: fixed;
    z-index: ${Number.MAX_SAFE_INTEGER};
  }
  
  .beacon-selected-label {
    position: fixed;
    pointer-events: none;
  }
  
  .beacon-sibling-highlighter {
    position: fixed;
    pointer-events: none;
    outline: 2px dashed ${y.HIGHLIGHT_COLOR} !important;
    outline-offset: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
    transform: none !important;
    background: ${y.HIGHLIGHT_BG} !important;
  }
`;function je(n,t){return n[13]=1,n[14]=t>>8,n[15]=t&255,n[16]=t>>8,n[17]=t&255,n}var ge=112,me=72,fe=89,pe=115,$;function qe(){let n=new Int32Array(256);for(let t=0;t<256;t++){let e=t;for(let i=0;i<8;i++)e=e&1?3988292384^e>>>1:e>>>1;n[t]=e}return n}function Qe(n){let t=-1;$||($=qe());for(let e=0;e<n.length;e++)t=$[(t^n[e])&255]^t>>>8;return t^-1}function Ze(n){let t=n.length-1;for(let e=t;e>=4;e--)if(n[e-4]===9&&n[e-3]===ge&&n[e-2]===me&&n[e-1]===fe&&n[e]===pe)return e-3;return 0}function Je(n,t,e=!1){let i=new Uint8Array(13);t*=39.3701,i[0]=ge,i[1]=me,i[2]=fe,i[3]=pe,i[4]=t>>>24,i[5]=t>>>16,i[6]=t>>>8,i[7]=t&255,i[8]=i[4],i[9]=i[5],i[10]=i[6],i[11]=i[7],i[12]=1;let r=Qe(i),o=new Uint8Array(4);if(o[0]=r>>>24,o[1]=r>>>16,o[2]=r>>>8,o[3]=r&255,e){let l=Ze(n);return n.set(i,l),n.set(o,l+13),n}else{let l=new Uint8Array(4);l[0]=0,l[1]=0,l[2]=0,l[3]=9;let s=new Uint8Array(54);return s.set(n,0),s.set(l,33),s.set(i,37),s.set(o,50),s}}var Ee="[modern-screenshot]",A=typeof window<"u",et=A&&"Worker"in window,tt=A&&"atob"in window,Fn=A&&"btoa"in window,Y=A?window.navigator?.userAgent:"",be=Y.includes("Chrome"),k=Y.includes("AppleWebKit")&&!be,X=Y.includes("Firefox"),nt=n=>n&&"__CONTEXT__"in n,it=n=>n.constructor.name==="CSSFontFaceRule",rt=n=>n.constructor.name==="CSSImportRule",v=n=>n.nodeType===1,I=n=>typeof n.className=="object",ye=n=>n.tagName==="image",ot=n=>n.tagName==="use",L=n=>v(n)&&typeof n.style<"u"&&!I(n),st=n=>n.nodeType===8,lt=n=>n.nodeType===3,H=n=>n.tagName==="IMG",F=n=>n.tagName==="VIDEO",at=n=>n.tagName==="CANVAS",ct=n=>n.tagName==="TEXTAREA",ht=n=>n.tagName==="INPUT",dt=n=>n.tagName==="STYLE",ut=n=>n.tagName==="SCRIPT",gt=n=>n.tagName==="SELECT",mt=n=>n.tagName==="SLOT",ft=n=>n.tagName==="IFRAME",pt=(...n)=>console.warn(Ee,...n);function Et(n){let t=n?.createElement?.("canvas");return t&&(t.height=t.width=1),!!t&&"toDataURL"in t&&!!t.toDataURL("image/webp").includes("image/webp")}var K=n=>n.startsWith("data:");function we(n,t){if(n.match(/^[a-z]+:\/\//i))return n;if(A&&n.match(/^\/\//))return window.location.protocol+n;if(n.match(/^[a-z]+:/i)||!A)return n;let e=U().implementation.createHTMLDocument(),i=e.createElement("base"),r=e.createElement("a");return e.head.appendChild(i),e.body.appendChild(r),t&&(i.href=t),r.href=n,r.href}function U(n){return(n&&v(n)?n?.ownerDocument:n)??window.document}var V="http://www.w3.org/2000/svg";function bt(n,t,e){let i=U(e).createElementNS(V,"svg");return i.setAttributeNS(null,"width",n.toString()),i.setAttributeNS(null,"height",t.toString()),i.setAttributeNS(null,"viewBox",`0 0 ${n} ${t}`),i}function yt(n,t){let e=new XMLSerializer().serializeToString(n);return t&&(e=e.replace(/[\u0000-\u0008\v\f\u000E-\u001F\uD800-\uDFFF\uFFFE\uFFFF]/gu,"")),`data:image/svg+xml;charset=utf-8,${encodeURIComponent(e)}`}async function wt(n,t="image/png",e=1){try{return await new Promise((i,r)=>{n.toBlob(o=>{o?i(o):r(new Error("Blob is null"))},t,e)})}catch(i){if(tt)return St(n.toDataURL(t,e));throw i}}function St(n){let[t,e]=n.split(","),i=t.match(/data:(.+);/)?.[1]??void 0,r=window.atob(e),o=r.length,l=new Uint8Array(o);for(let s=0;s<o;s+=1)l[s]=r.charCodeAt(s);return new Blob([l],{type:i})}function Se(n,t){return new Promise((e,i)=>{let r=new FileReader;r.onload=()=>e(r.result),r.onerror=()=>i(r.error),r.onabort=()=>i(new Error(`Failed read blob to ${t}`)),t==="dataUrl"?r.readAsDataURL(n):t==="arrayBuffer"&&r.readAsArrayBuffer(n)})}var vt=n=>Se(n,"dataUrl"),Tt=n=>Se(n,"arrayBuffer");function R(n,t){let e=U(t).createElement("img");return e.decoding="sync",e.loading="eager",e.src=n,e}function M(n,t){return new Promise(e=>{let{timeout:i,ownerDocument:r,onError:o,onWarn:l}=t??{},s=typeof n=="string"?R(n,U(r)):n,c=null,h=null;function a(){e(s),c&&clearTimeout(c),h?.()}if(i&&(c=setTimeout(a,i)),F(s)){let d=s.currentSrc||s.src;if(!d)return s.poster?M(s.poster,t).then(e):a();if(s.readyState>=2)return a();let u=a,m=g=>{l?.("Failed video load",d,g),o?.(g),a()};h=()=>{s.removeEventListener("loadeddata",u),s.removeEventListener("error",m)},s.addEventListener("loadeddata",u,{once:!0}),s.addEventListener("error",m,{once:!0})}else{let d=ye(s)?s.href.baseVal:s.currentSrc||s.src;if(!d)return a();let u=async()=>{if(H(s)&&"decode"in s)try{await s.decode()}catch(g){l?.("Failed to decode image, trying to render anyway",s.dataset.originalSrc||d,g)}a()},m=g=>{l?.("Failed image load",s.dataset.originalSrc||d,g),a()};if(H(s)&&s.complete)return u();h=()=>{s.removeEventListener("load",u),s.removeEventListener("error",m)},s.addEventListener("load",u,{once:!0}),s.addEventListener("error",m,{once:!0})}})}async function Ct(n,t){L(n)&&(H(n)||F(n)?await M(n,t):await Promise.all(["img","video"].flatMap(e=>Array.from(n.querySelectorAll(e)).map(i=>M(i,t)))))}var ve=function(){let t=0,e=()=>`0000${(Math.random()*36**4<<0).toString(36)}`.slice(-4);return()=>(t+=1,`u${e()}${t}`)}();function Te(n){return n?.split(",").map(t=>t.trim().replace(/"|'/g,"").toLowerCase()).filter(Boolean)}var le=0;function At(n){let t=`${Ee}[#${le}]`;return le++,{time:e=>n&&console.time(`${t} ${e}`),timeEnd:e=>n&&console.timeEnd(`${t} ${e}`),warn:(...e)=>n&&pt(...e)}}function Rt(n){return{cache:n?"no-cache":"force-cache"}}async function z(n,t){return nt(n)?n:Ht(n,{...t,autoDestruct:!0})}async function Ht(n,t){let{scale:e=1,workerUrl:i,workerNumber:r=1}=t||{},o=!!t?.debug,l=t?.features??!0,s=n.ownerDocument??(A?window.document:void 0),c=n.ownerDocument?.defaultView??(A?window:void 0),h=new Map,a={width:0,height:0,quality:1,type:"image/png",scale:e,backgroundColor:null,style:null,filter:null,maximumCanvasSize:0,timeout:3e4,progress:null,debug:o,fetch:{requestInit:Rt(t?.fetch?.bypassingCache),placeholderImage:"data:image/png;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7",bypassingCache:!1,...t?.fetch},fetchFn:null,font:{},drawImageInterval:100,workerUrl:null,workerNumber:r,onCloneNode:null,onEmbedNode:null,onCreateForeignObjectSvg:null,includeStyleProperties:null,autoDestruct:!1,...t,__CONTEXT__:!0,log:At(o),node:n,ownerDocument:s,ownerWindow:c,dpi:e===1?null:96*e,svgStyleElement:Ce(s),svgDefsElement:s?.createElementNS(V,"defs"),svgStyles:new Map,defaultComputedStyles:new Map,workers:[...Array.from({length:et&&i&&r?r:0})].map(()=>{try{let m=new Worker(i);return m.onmessage=async g=>{let{url:f,result:E}=g.data;E?h.get(f)?.resolve?.(E):h.get(f)?.reject?.(new Error(`Error receiving message from worker: ${f}`))},m.onmessageerror=g=>{let{url:f}=g.data;h.get(f)?.reject?.(new Error(`Error receiving message from worker: ${f}`))},m}catch(m){return a.log.warn("Failed to new Worker",m),null}}).filter(Boolean),fontFamilies:new Map,fontCssTexts:new Map,acceptOfImage:`${[Et(s)&&"image/webp","image/svg+xml","image/*","*/*"].filter(Boolean).join(",")};q=0.8`,requests:h,drawImageCount:0,tasks:[],features:l,isEnable:m=>m==="restoreScrollPosition"?typeof l=="boolean"?!1:l[m]??!1:typeof l=="boolean"?l:l[m]??!0};a.log.time("wait until load"),await Ct(n,{timeout:a.timeout,onWarn:a.log.warn}),a.log.timeEnd("wait until load");let{width:d,height:u}=xt(n,a);return a.width=d,a.height=u,a}function Ce(n){if(!n)return;let t=n.createElement("style"),e=t.ownerDocument.createTextNode(`
.______background-clip--text {
  background-clip: text;
  -webkit-background-clip: text;
}
`);return t.appendChild(e),t}function xt(n,t){let{width:e,height:i}=t;if(v(n)&&(!e||!i)){let r=n.getBoundingClientRect();e=e||r.width||Number(n.getAttribute("width"))||0,i=i||r.height||Number(n.getAttribute("height"))||0}return{width:e,height:i}}async function Lt(n,t){let{log:e,timeout:i,drawImageCount:r,drawImageInterval:o}=t;e.time("image to canvas");let l=await M(n,{timeout:i,onWarn:t.log.warn}),{canvas:s,context2d:c}=Mt(n.ownerDocument,t),h=()=>{try{c?.drawImage(l,0,0,s.width,s.height)}catch(a){t.log.warn("Failed to drawImage",a)}};if(h(),t.isEnable("fixSvgXmlDecode"))for(let a=0;a<r;a++)await new Promise(d=>{setTimeout(()=>{h(),d()},a+o)});return t.drawImageCount=0,e.timeEnd("image to canvas"),s}function Mt(n,t){let{width:e,height:i,scale:r,backgroundColor:o,maximumCanvasSize:l}=t,s=n.createElement("canvas");s.width=Math.floor(e*r),s.height=Math.floor(i*r),s.style.width=`${e}px`,s.style.height=`${i}px`,l&&(s.width>l||s.height>l)&&(s.width>l&&s.height>l?s.width>s.height?(s.height*=l/s.width,s.width=l):(s.width*=l/s.height,s.height=l):s.width>l?(s.height*=l/s.width,s.width=l):(s.width*=l/s.height,s.height=l));let c=s.getContext("2d");return c&&o&&(c.fillStyle=o,c.fillRect(0,0,s.width,s.height)),{canvas:s,context2d:c}}function Ae(n,t){if(n.ownerDocument)try{let o=n.toDataURL();if(o!=="data:,")return R(o,n.ownerDocument)}catch(o){t.log.warn("Failed to clone canvas",o)}let e=n.cloneNode(!1),i=n.getContext("2d"),r=e.getContext("2d");try{return i&&r&&r.putImageData(i.getImageData(0,0,n.width,n.height),0,0),e}catch(o){t.log.warn("Failed to clone canvas",o)}return e}function _t(n,t){try{if(n?.contentDocument?.body)return j(n.contentDocument.body,t)}catch(e){t.log.warn("Failed to clone iframe",e)}return n.cloneNode(!1)}function It(n){let t=n.cloneNode(!1);return n.currentSrc&&n.currentSrc!==n.src&&(t.src=n.currentSrc,t.srcset=""),t.loading==="lazy"&&(t.loading="eager"),t}async function Pt(n,t){if(n.ownerDocument&&!n.currentSrc&&n.poster)return R(n.poster,n.ownerDocument);let e=n.cloneNode(!1);e.crossOrigin="anonymous",n.currentSrc&&n.currentSrc!==n.src&&(e.src=n.currentSrc);let i=e.ownerDocument;if(i){let r=!0;if(await M(e,{onError:()=>r=!1,onWarn:t.log.warn}),!r)return n.poster?R(n.poster,n.ownerDocument):e;e.currentTime=n.currentTime,await new Promise(l=>{e.addEventListener("seeked",l,{once:!0})});let o=i.createElement("canvas");o.width=n.offsetWidth,o.height=n.offsetHeight;try{let l=o.getContext("2d");l&&l.drawImage(e,0,0,o.width,o.height)}catch(l){return t.log.warn("Failed to clone video",l),n.poster?R(n.poster,n.ownerDocument):e}return Ae(o,t)}return e}function Dt(n,t){return at(n)?Ae(n,t):ft(n)?_t(n,t):H(n)?It(n):F(n)?Pt(n,t):n.cloneNode(!1)}function Nt(n){let t=n.sandbox;if(!t){let{ownerDocument:e}=n;try{e&&(t=e.createElement("iframe"),t.id=`__SANDBOX__-${ve()}`,t.width="0",t.height="0",t.style.visibility="hidden",t.style.position="fixed",e.body.appendChild(t),t.contentWindow?.document.write('<!DOCTYPE html><meta charset="UTF-8"><title></title><body>'),n.sandbox=t)}catch(i){n.log.warn("Failed to getSandBox",i)}}return t}var Ot=["width","height","-webkit-text-fill-color"],Bt=["stroke","fill"];function Re(n,t,e){let{defaultComputedStyles:i}=e,r=n.nodeName.toLowerCase(),o=I(n)&&r!=="svg",l=o?Bt.map(f=>[f,n.getAttribute(f)]).filter(([,f])=>f!==null):[],s=[o&&"svg",r,l.map((f,E)=>`${f}=${E}`).join(","),t].filter(Boolean).join(":");if(i.has(s))return i.get(s);let h=Nt(e)?.contentWindow;if(!h)return new Map;let a=h?.document,d,u;o?(d=a.createElementNS(V,"svg"),u=d.ownerDocument.createElementNS(d.namespaceURI,r),l.forEach(([f,E])=>{u.setAttributeNS(null,f,E)}),d.appendChild(u)):d=u=a.createElement(r),u.textContent=" ",a.body.appendChild(d);let m=h.getComputedStyle(u,t),g=new Map;for(let f=m.length,E=0;E<f;E++){let p=m.item(E);Ot.includes(p)||g.set(p,m.getPropertyValue(p))}return a.body.removeChild(d),i.set(s,g),g}function He(n,t,e){let i=new Map,r=[],o=new Map;if(e)for(let s of e)l(s);else for(let s=n.length,c=0;c<s;c++){let h=n.item(c);l(h)}for(let s=r.length,c=0;c<s;c++)o.get(r[c])?.forEach((h,a)=>i.set(a,h));function l(s){let c=n.getPropertyValue(s),h=n.getPropertyPriority(s),a=s.lastIndexOf("-"),d=a>-1?s.substring(0,a):void 0;if(d){let u=o.get(d);u||(u=new Map,o.set(d,u)),u.set(s,[c,h])}t.get(s)===c&&!h||(d?r.push(d):i.set(s,[c,h]))}return i}function kt(n,t,e,i){let{ownerWindow:r,includeStyleProperties:o,currentParentNodeStyle:l}=i,s=t.style,c=r.getComputedStyle(n),h=Re(n,null,i);l?.forEach((d,u)=>{h.delete(u)});let a=He(c,h,o);a.delete("transition-property"),a.delete("all"),a.delete("d"),a.delete("content"),e&&(a.delete("margin-top"),a.delete("margin-right"),a.delete("margin-bottom"),a.delete("margin-left"),a.delete("margin-block-start"),a.delete("margin-block-end"),a.delete("margin-inline-start"),a.delete("margin-inline-end"),a.set("box-sizing",["border-box",""])),a.get("background-clip")?.[0]==="text"&&t.classList.add("______background-clip--text"),be&&(a.has("font-kerning")||a.set("font-kerning",["normal",""]),(a.get("overflow-x")?.[0]==="hidden"||a.get("overflow-y")?.[0]==="hidden")&&a.get("text-overflow")?.[0]==="ellipsis"&&n.scrollWidth===n.clientWidth&&a.set("text-overflow",["clip",""]));for(let d=s.length,u=0;u<d;u++)s.removeProperty(s.item(u));return a.forEach(([d,u],m)=>{s.setProperty(m,d,u)}),a}function Ft(n,t){(ct(n)||ht(n)||gt(n))&&t.setAttribute("value",n.value)}var Ut=[":before",":after"],Vt=[":-webkit-scrollbar",":-webkit-scrollbar-button",":-webkit-scrollbar-thumb",":-webkit-scrollbar-track",":-webkit-scrollbar-track-piece",":-webkit-scrollbar-corner",":-webkit-resizer"];function Gt(n,t,e,i,r){let{ownerWindow:o,svgStyleElement:l,svgStyles:s,currentNodeStyle:c}=i;if(!l||!o)return;function h(a){let d=o.getComputedStyle(n,a),u=d.getPropertyValue("content");if(!u||u==="none")return;r?.(u),u=u.replace(/(')|(")|(counter\(.+\))/g,"");let m=[ve()],g=Re(n,a,i);c?.forEach((b,S)=>{g.delete(S)});let f=He(d,g,i.includeStyleProperties);f.delete("content"),f.delete("-webkit-locale"),f.get("background-clip")?.[0]==="text"&&t.classList.add("______background-clip--text");let E=[`content: '${u}';`];if(f.forEach(([b,S],C)=>{E.push(`${C}: ${b}${S?" !important":""};`)}),E.length===1)return;try{t.className=[t.className,...m].join(" ")}catch(b){i.log.warn("Failed to copyPseudoClass",b);return}let p=E.join(`
  `),w=s.get(p);w||(w=[],s.set(p,w)),w.push(`.${m[0]}:${a}`)}Ut.forEach(h),e&&Vt.forEach(h)}var ae=new Set(["symbol"]);async function ce(n,t,e,i,r){if(v(e)&&(dt(e)||ut(e))||i.filter&&!i.filter(e))return;ae.has(t.nodeName)||ae.has(e.nodeName)?i.currentParentNodeStyle=void 0:i.currentParentNodeStyle=i.currentNodeStyle;let o=await j(e,i,!1,r);i.isEnable("restoreScrollPosition")&&Wt(n,o),t.appendChild(o)}async function he(n,t,e,i){let r=(v(n)?n.shadowRoot?.firstChild:void 0)??n.firstChild;for(let o=r;o;o=o.nextSibling)if(!st(o))if(v(o)&&mt(o)&&typeof o.assignedNodes=="function"){let l=o.assignedNodes();for(let s=0;s<l.length;s++)await ce(n,t,l[s],e,i)}else await ce(n,t,o,e,i)}function Wt(n,t){if(!L(n)||!L(t))return;let{scrollTop:e,scrollLeft:i}=n;if(!e&&!i)return;let{transform:r}=t.style,o=new DOMMatrix(r),{a:l,b:s,c,d:h}=o;o.a=1,o.b=0,o.c=0,o.d=1,o.translateSelf(-i,-e),o.a=l,o.b=s,o.c=c,o.d=h,t.style.transform=o.toString()}function $t(n,t){let{backgroundColor:e,width:i,height:r,style:o}=t,l=n.style;if(e&&l.setProperty("background-color",e,"important"),i&&l.setProperty("width",`${i}px`,"important"),r&&l.setProperty("height",`${r}px`,"important"),o)for(let s in o)l[s]=o[s]}var Kt=/^[\w-:]+$/;async function j(n,t,e=!1,i){let{ownerDocument:r,ownerWindow:o,fontFamilies:l}=t;if(r&&lt(n))return i&&/\S/.test(n.data)&&i(n.data),r.createTextNode(n.data);if(r&&o&&v(n)&&(L(n)||I(n))){let c=await Dt(n,t);if(t.isEnable("removeAbnormalAttributes")){let g=c.getAttributeNames();for(let f=g.length,E=0;E<f;E++){let p=g[E];Kt.test(p)||c.removeAttribute(p)}}let h=t.currentNodeStyle=kt(n,c,e,t);e&&$t(c,t);let a=!1;if(t.isEnable("copyScrollbar")){let g=[h.get("overflow-x")?.[0],h.get("overflow-y")?.[0]];a=g.includes("scroll")||(g.includes("auto")||g.includes("overlay"))&&(n.scrollHeight>n.clientHeight||n.scrollWidth>n.clientWidth)}let d=h.get("text-transform")?.[0],u=Te(h.get("font-family")?.[0]),m=u?g=>{d==="uppercase"?g=g.toUpperCase():d==="lowercase"?g=g.toLowerCase():d==="capitalize"&&(g=g[0].toUpperCase()+g.substring(1)),u.forEach(f=>{let E=l.get(f);E||l.set(f,E=new Set),g.split("").forEach(p=>E.add(p))})}:void 0;return Gt(n,c,a,t,m),Ft(n,c),F(n)||await he(n,c,t,m),c}let s=n.cloneNode(!1);return await he(n,s,t),s}function Yt(n){if(n.ownerDocument=void 0,n.ownerWindow=void 0,n.svgStyleElement=void 0,n.svgDefsElement=void 0,n.svgStyles.clear(),n.defaultComputedStyles.clear(),n.sandbox){try{n.sandbox.remove()}catch(t){n.log.warn("Failed to destroyContext",t)}n.sandbox=void 0}n.workers=[],n.fontFamilies.clear(),n.fontCssTexts.clear(),n.requests.clear(),n.tasks=[]}function Xt(n){let{url:t,timeout:e,responseType:i,...r}=n,o=new AbortController,l=e?setTimeout(()=>o.abort(),e):void 0;return fetch(t,{signal:o.signal,...r}).then(s=>{if(!s.ok)throw new Error("Failed fetch, not 2xx response",{cause:s});switch(i){case"arrayBuffer":return s.arrayBuffer();case"dataUrl":return s.blob().then(vt);case"text":default:return s.text()}}).finally(()=>clearTimeout(l))}function _(n,t){let{url:e,requestType:i="text",responseType:r="text",imageDom:o}=t,l=e,{timeout:s,acceptOfImage:c,requests:h,fetchFn:a,fetch:{requestInit:d,bypassingCache:u,placeholderImage:m},font:g,workers:f,fontFamilies:E}=n;i==="image"&&(k||X)&&n.drawImageCount++;let p=h.get(e);if(!p){u&&u instanceof RegExp&&u.test(l)&&(l+=(/\?/.test(l)?"&":"?")+new Date().getTime());let w=i.startsWith("font")&&g&&g.minify,b=new Set;w&&i.split(";")[1].split(",").forEach(O=>{E.has(O)&&E.get(O).forEach(re=>b.add(re))});let S=w&&b.size,C={url:l,timeout:s,responseType:S?"arrayBuffer":r,headers:i==="image"?{accept:c}:void 0,...d};p={type:i,resolve:void 0,reject:void 0,response:null},p.response=(async()=>{if(a&&i==="image"){let T=await a(e);if(T)return T}return!k&&e.startsWith("http")&&f.length?new Promise((T,O)=>{f[h.size&f.length-1].postMessage({rawUrl:e,...C}),p.resolve=T,p.reject=O}):Xt(C)})().catch(T=>{if(h.delete(e),i==="image"&&m)return n.log.warn("Failed to fetch image base64, trying to use placeholder image",l),typeof m=="string"?m:m(o);throw T}),h.set(e,p)}return p.response}async function xe(n,t,e,i){if(!Le(n))return n;for(let[r,o]of zt(n,t))try{let l=await _(e,{url:o,requestType:i?"image":"text",responseType:"dataUrl"});n=n.replace(jt(r),`$1${l}$3`)}catch(l){e.log.warn("Failed to fetch css data url",r,l)}return n}function Le(n){return/url\((['"]?)([^'"]+?)\1\)/.test(n)}var Me=/url\((['"]?)([^'"]+?)\1\)/g;function zt(n,t){let e=[];return n.replace(Me,(i,r,o)=>(e.push([o,we(o,t)]),i)),e.filter(([i])=>!K(i))}function jt(n){let t=n.replace(/([.*+?^${}()|\[\]\/\\])/g,"\\$1");return new RegExp(`(url\\(['"]?)(${t})(['"]?\\))`,"g")}var qt=["background-image","border-image-source","-webkit-border-image","-webkit-mask-image","list-style-image"];function Qt(n,t){return qt.map(e=>{let i=n.getPropertyValue(e);return!i||i==="none"?null:((k||X)&&t.drawImageCount++,xe(i,null,t,!0).then(r=>{!r||i===r||n.setProperty(e,r,n.getPropertyPriority(e))}))}).filter(Boolean)}function Zt(n,t){if(H(n)){let e=n.currentSrc||n.src;if(!K(e))return[_(t,{url:e,imageDom:n,requestType:"image",responseType:"dataUrl"}).then(i=>{i&&(n.srcset="",n.dataset.originalSrc=e,n.src=i||"")})];(k||X)&&t.drawImageCount++}else if(I(n)&&!K(n.href.baseVal)){let e=n.href.baseVal;return[_(t,{url:e,imageDom:n,requestType:"image",responseType:"dataUrl"}).then(i=>{i&&(n.dataset.originalSrc=e,n.href.baseVal=i||"")})]}return[]}function Jt(n,t){let{ownerDocument:e,svgDefsElement:i}=t,r=n.getAttribute("href")??n.getAttribute("xlink:href");if(!r)return[];let[o,l]=r.split("#");if(l){let s=`#${l}`,c=e?.querySelector(`svg ${s}`);if(o&&n.setAttribute("href",s),i?.querySelector(s))return[];if(c)return i?.appendChild(c.cloneNode(!0)),[];if(o)return[_(t,{url:o,responseType:"text"}).then(h=>{i?.insertAdjacentHTML("beforeend",h)})]}return[]}function _e(n,t){let{tasks:e}=t;v(n)&&((H(n)||ye(n))&&e.push(...Zt(n,t)),ot(n)&&e.push(...Jt(n,t))),L(n)&&e.push(...Qt(n.style,t)),n.childNodes.forEach(i=>{_e(i,t)})}async function en(n,t){let{ownerDocument:e,svgStyleElement:i,fontFamilies:r,fontCssTexts:o,tasks:l,font:s}=t;if(!(!e||!i||!r.size))if(s&&s.cssText){let c=ue(s.cssText,t);i.appendChild(e.createTextNode(`${c}
`))}else{let c=Array.from(e.styleSheets).filter(a=>{try{return"cssRules"in a&&!!a.cssRules.length}catch(d){return t.log.warn(`Error while reading CSS rules from ${a.href}`,d),!1}});await Promise.all(c.flatMap(a=>Array.from(a.cssRules).map(async(d,u)=>{if(rt(d)){let m=u+1,g=d.href,f="";try{f=await _(t,{url:g,requestType:"text",responseType:"text"})}catch(p){t.log.warn(`Error fetch remote css import from ${g}`,p)}let E=f.replace(Me,(p,w,b)=>p.replace(b,we(b,g)));for(let p of nn(E))try{a.insertRule(p,p.startsWith("@import")?m+=1:a.cssRules.length)}catch(w){t.log.warn("Error inserting rule from remote css import",{rule:p,error:w})}}}))),c.flatMap(a=>Array.from(a.cssRules)).filter(a=>it(a)&&Le(a.style.getPropertyValue("src"))&&Te(a.style.getPropertyValue("font-family"))?.some(d=>r.has(d))).forEach(a=>{let d=a,u=o.get(d.cssText);u?i.appendChild(e.createTextNode(`${u}
`)):l.push(xe(d.cssText,d.parentStyleSheet?d.parentStyleSheet.href:null,t).then(m=>{m=ue(m,t),o.set(d.cssText,m),i.appendChild(e.createTextNode(`${m}
`))}))})}}var tn=/(\/\*[\s\S]*?\*\/)/g,de=/((@.*?keyframes [\s\S]*?){([\s\S]*?}\s*?)})/gi;function nn(n){if(n==null)return[];let t=[],e=n.replace(tn,"");for(;;){let o=de.exec(e);if(!o)break;t.push(o[0])}e=e.replace(de,"");let i=/@import[\s\S]*?url\([^)]*\)[\s\S]*?;/gi,r=new RegExp("((\\s*?(?:\\/\\*[\\s\\S]*?\\*\\/)?\\s*?@media[\\s\\S]*?){([\\s\\S]*?)}\\s*?})|(([\\s\\S]*?){([\\s\\S]*?)})","gi");for(;;){let o=i.exec(e);if(o)r.lastIndex=i.lastIndex;else if(o=r.exec(e),o)i.lastIndex=r.lastIndex;else break;t.push(o[0])}return t}var rn=/url\([^)]+\)\s*format\((["']?)([^"']+)\1\)/g,on=/src:\s*(?:url\([^)]+\)\s*format\([^)]+\)[,;]\s*)+/g;function ue(n,t){let{font:e}=t,i=e?e?.preferredFormat:void 0;return i?n.replace(on,r=>{for(;;){let[o,,l]=rn.exec(r)||[];if(!l)return"";if(l===i)return`src: ${o};`}}):n}async function sn(n,t){let e=await z(n,t);if(v(e.node)&&I(e.node))return e.node;let{ownerDocument:i,log:r,tasks:o,svgStyleElement:l,svgDefsElement:s,svgStyles:c,font:h,progress:a,autoDestruct:d,onCloneNode:u,onEmbedNode:m,onCreateForeignObjectSvg:g}=e;r.time("clone node");let f=await j(e.node,e,!0);if(l&&i){let S="";c.forEach((C,T)=>{S+=`${C.join(`,
`)} {
  ${T}
}
`}),l.appendChild(i.createTextNode(S))}r.timeEnd("clone node"),await u?.(f),h!==!1&&v(f)&&(r.time("embed web font"),await en(f,e),r.timeEnd("embed web font")),r.time("embed node"),_e(f,e);let E=o.length,p=0,w=async()=>{for(;;){let S=o.pop();if(!S)break;try{await S}catch(C){e.log.warn("Failed to run task",C)}a?.(++p,E)}};a?.(p,E),await Promise.all([...Array.from({length:4})].map(w)),r.timeEnd("embed node"),await m?.(f);let b=ln(f,e);return s&&b.insertBefore(s,b.children[0]),l&&b.insertBefore(l,b.children[0]),d&&Yt(e),await g?.(b),b}function ln(n,t){let{width:e,height:i}=t,r=bt(e,i,n.ownerDocument),o=r.ownerDocument.createElementNS(r.namespaceURI,"foreignObject");return o.setAttributeNS(null,"x","0%"),o.setAttributeNS(null,"y","0%"),o.setAttributeNS(null,"width","100%"),o.setAttributeNS(null,"height","100%"),o.append(n),r.appendChild(o),r}async function an(n,t){let e=await z(n,t),i=await sn(e),r=yt(i,e.isEnable("removeControlCharacter"));e.autoDestruct||(e.svgStyleElement=Ce(e.ownerDocument),e.svgDefsElement=e.ownerDocument?.createElementNS(V,"defs"),e.svgStyles.clear());let o=R(r,i.ownerDocument);return await Lt(o,e)}async function q(n,t){let e=await z(n,t),{log:i,type:r,quality:o,dpi:l}=e,s=await an(e);i.time("canvas to blob");let c=await wt(s,r,o);if(["image/png","image/jpeg"].includes(r)&&l){let h=await Tt(c.slice(0,33)),a=new Uint8Array(h);return r==="image/png"?a=Je(a,l):r==="image/jpeg"&&(a=je(a,l)),i.timeEnd("canvas to blob"),new Blob([a,c.slice(33)],{type:r})}return i.timeEnd("canvas to blob"),c}var P={METADATA:"data-replit-metadata",COMPONENT_NAME:"data-component-name"};var Ie={color:"color",radius:"borderTopLeftRadius",text:"fontSize",font:"fontFamily"};function De(n){try{let t=new URL(n);return cn(t)?!0:y.ALLOWED_PARENT_DOMAINS.some(e=>t.hostname===e.slice(1)||t.hostname.endsWith(e))}catch{return!1}}function cn(n){return n.protocol!=="http:"||!n.port?!1:n.hostname==="localhost"||n.hostname==="127.0.0.1"||n.hostname==="[::1]"}function W(n){if(!n)return null;let t=document.elementFromPoint(n.clientX,n.clientY);return t instanceof HTMLElement?t:null}function hn(n,t=300){if(!n)return"";let e=String(n);return e.length<=t?e:e.slice(0,t)+"..."}function x(n){let t=n.getAttribute(P.COMPONENT_NAME)??n.tagName.toLowerCase();return hn(t,50)}function Q(n){return n.className.toString?n.className.toString():String(n.className)}function Ne(n,t=80){let e="";for(let i=0;i<n.childNodes.length;i++){let r=n.childNodes[i];if(r.nodeType===Node.TEXT_NODE&&(e+=r.textContent??"",e.length>t))return e.slice(0,t)+"..."}return e.trim()}var dn=new Set(["script","style","noscript","link","meta","br","svg"]);function Oe(n){let t={children:[],parent:null};return Object.defineProperty(t,"parent",{value:n,writable:!0,enumerable:!1,configurable:!0}),t}function Be(n,t,e,i){let r=Oe(t),o={tagName:n.tagName.toLowerCase(),textContent:Ne(n),id:n.id||void 0,className:Q(n)||void 0,nodeId:e.get(n),relatedElements:r};i.set(n,o);for(let l=0;l<n.children.length;l++)Be(n.children[l],o,e,i)}var G=class{ids=new WeakMap;nextId=0;get(t){let e=this.ids.get(t);if(e!==void 0)return e;let i=this.nextId++;return this.ids.set(t,i),i}};function Z(n,t,e,i,r){let o=e.get(n),l=Oe(t),s=l.children,c={tagName:n.tagName.toLowerCase(),textContent:Ne(n),id:n.id||void 0,className:Q(n)||void 0,nodeId:o,relatedElements:l};i.set(n,c);for(let h=0;h<n.children.length;h++){let a=n.children[h],d=a.tagName.toLowerCase();if(a!==r){if(d==="svg"){Be(a,c,e,i);continue}dn.has(d)||s.push(Z(a,c,e,i,r))}}return c}function un(n){let t={};if(typeof document>"u"||typeof CSS>"u")return t;let e=document.createElement("div");e.style.cssText="position:fixed;left:-9999px;top:-9999px;visibility:hidden;pointer-events:none";try{document.body.appendChild(e);let i=window.getComputedStyle(e);for(let[r,o]of Object.entries(n)){let l=Ie[r];l&&(t[r]=o.map(({suffix:s,expr:c})=>{let h="";try{e.style[l]="",e.style[l]=c,h=i[l]}catch{h=""}return{suffix:s,value:h}}))}}catch{}finally{e.remove()}return t}function gn(){let n=typeof window>"u"?void 0:window.REPLIT_APP_THEME_TOKENS;if(n)return un(n)}function J(n,t){let e=window.getComputedStyle(n),i=p=>p.toLowerCase()==="currentcolor"?e.color:p,r=i(e.borderTopColor),o=i(e.borderRightColor),l=i(e.borderBottomColor),s=i(e.borderLeftColor),c=n.nextElementSibling,h=n.parentElement?.parentElement??null,a=mn(n),d={backgroundColor:e.backgroundColor,borderTopColor:r,borderRightColor:o,borderBottomColor:l,borderLeftColor:s,borderTopLeftRadius:e.borderTopLeftRadius,borderTopRightRadius:e.borderTopRightRadius,borderBottomRightRadius:e.borderBottomRightRadius,borderBottomLeftRadius:e.borderBottomLeftRadius,borderTopWidth:e.borderTopWidth,borderRightWidth:e.borderRightWidth,borderBottomWidth:e.borderBottomWidth,borderLeftWidth:e.borderLeftWidth,color:e.color,display:e.display,position:e.position,width:e.width,height:e.height,fontSize:e.fontSize,fontFamily:e.fontFamily,fontWeight:e.fontWeight,margin:e.margin,padding:e.padding,opacity:e.opacity,textAlign:e.textAlign,flexDirection:e.flexDirection,flexWrap:e.flexWrap,justifyContent:e.justifyContent,alignItems:e.alignItems,gap:e.gap,rowGap:e.rowGap,columnGap:e.columnGap},u=t.get(n),m=n.parentElement?t.get(n.parentElement)??null:null,g={children:u?.relatedElements.children??[],parent:u?.relatedElements.parent??m,nextSibling:c?t.get(c)??void 0:void 0,grandParent:h?t.get(h)??void 0:void 0},f=gn();return{tagName:n.tagName.toLowerCase(),nodeId:u?.nodeId,elementPath:n.getAttribute(P.METADATA)??"",elementName:x(n),textContent:n.textContent??"",originalTextContent:n.getAttribute("data-original-text")?decodeURIComponent(n.getAttribute("data-original-text")??""):void 0,srcAttribute:n.getAttribute("src")??"",hasChildElements:n.childElementCount>0,id:n.id,className:Q(n),colorVariables:a,...f?{themeTokens:f}:{},computedStyles:d,textAlign:e.textAlign,relatedElements:g}}function mn(n){let t=new Set(["inherit","initial","unset","revert","revert-layer"]),e={},i=window.getComputedStyle(n);for(let r=0;r<i.length;r++){let o=i.item(r);if(!o.startsWith("--"))continue;let l=i.getPropertyValue(o).trim();!l||t.has(l.toLowerCase())||!CSS.supports("color",l)||(e[o]=l)}return e}async function ke(n){try{let e=window.getComputedStyle(n).backgroundColor;return Fe(e)&&(e=window.getComputedStyle(document.documentElement).backgroundColor),await q(n,{type:"image/png",backgroundColor:e})}catch(t){console.error("[replit-cartographer] Failed to take screenshot:",t);return}}function Fe(n){return n==="transparent"||n==="rgba(0, 0, 0, 0)"||n.endsWith(", 0)")||n.endsWith(",0)")}async function ee({restoreScrollPosition:n=!1}={}){try{let t=document.documentElement,e=window.getComputedStyle(t).backgroundColor,i=Fe(e)?"#ffffff":e;return await q(t,{type:"image/png",backgroundColor:i,...n?{features:{restoreScrollPosition:!0}}:{}})}catch(t){console.error("[replit-cartographer] Failed to take page screenshot:",t);return}}function fn(){return{x:window.scrollX||document.documentElement.scrollLeft||document.body?.scrollLeft||0,y:window.scrollY||document.documentElement.scrollTop||document.body?.scrollTop||0}}function pn(){return{width:Math.max(1,Math.ceil(window.innerWidth||document.documentElement.clientWidth)),height:Math.max(1,Math.ceil(window.innerHeight||document.documentElement.clientHeight))}}function En(n){let t=document.documentElement,e=document.body;return{width:Math.max(n.width,t.scrollWidth,t.offsetWidth,t.clientWidth,e?.scrollWidth??0,e?.offsetWidth??0,e?.clientWidth??0),height:Math.max(n.height,t.scrollHeight,t.offsetHeight,t.clientHeight,e?.scrollHeight??0,e?.offsetHeight??0,e?.clientHeight??0)}}function bn(n){return new Promise((t,e)=>{let i=URL.createObjectURL(n),r=new Image,o=()=>{URL.revokeObjectURL(i)};r.onload=()=>{o(),t(r)},r.onerror=()=>{o(),e(new Error("Failed to load screenshot blob"))},r.src=i})}function yn(n){return new Promise(t=>{n.toBlob(e=>{t(e??void 0)},"image/png")})}function Pe({documentSize:n,imageSize:t,scrollOffset:e,viewportSize:i}){if(t<=i+1)return{start:0,size:Math.max(1,t)};let r=t/n,o=Math.max(1,Math.min(t,Math.ceil(i*r))),l=Math.max(0,t-o);return{start:Math.min(l,Math.max(0,Math.floor(e*r))),size:o}}function wn({documentSize:n,rootRect:t,scrollOffset:e,viewport:i}){let r=({rootAxisSize:l,viewportAxisSize:s})=>Math.ceil(l)<=s+1,o=({documentAxisSize:l,rootAxisSize:s,scrollAxisOffset:c,viewportAxisSize:h})=>c!==0&&l>h+1&&r({rootAxisSize:s,viewportAxisSize:h});return o({documentAxisSize:n.width,rootAxisSize:t.width,scrollAxisOffset:e.x,viewportAxisSize:i.width})||o({documentAxisSize:n.height,rootAxisSize:t.height,scrollAxisOffset:e.y,viewportAxisSize:i.height})}async function Ue(){try{let n=pn(),t=En(n),e=fn(),i=document.documentElement.getBoundingClientRect(),r=wn({documentSize:t,rootRect:i,scrollOffset:e,viewport:n}),o=r?{x:0,y:0}:e,l=await ee({restoreScrollPosition:r});if(!l)return;let s=await bn(l),c={height:s.naturalHeight||s.height,width:s.naturalWidth||s.width},h=Pe({documentSize:t.width,imageSize:c.width,scrollOffset:o.x,viewportSize:n.width}),a=Pe({documentSize:t.height,imageSize:c.height,scrollOffset:o.y,viewportSize:n.height}),d=document.createElement("canvas");d.width=h.size,d.height=a.size;let u=d.getContext("2d");return u?(u.drawImage(s,h.start,a.start,h.size,a.size,0,0,h.size,a.size),await yn(d)):void 0}catch{return}}function te(n){let t=n.getBoundingClientRect(),e=window.innerHeight,i=window.innerWidth;return t.bottom>0&&t.top<e&&t.right>0&&t.left<i}function D(n,t=y.MAX_SIBLING_HIGHLIGHTERS,e=!1){let o=n.getAttribute(P.METADATA);if(!o)return[];let l=`[${P.METADATA}="${o}"]`,s=document,c=n.parentElement;c&&c.childElementCount>50&&(s=c);let h=s.querySelectorAll(l),a=Math.min(t,5e3),d=[],u=0;for(let m=0;m<h.length&&u<a;m++){let g=h[m];if(g instanceof HTMLElement&&g!==n){if(e&&!te(g))continue;d.push(g),u++}}return d}function Ve(n,t,e){let i=n.children;for(let r=0;r<i.length;r++)if(e.value+=1,e.value>t||Ve(i[r],t,e))return!0;return!1}function Ge(n){let t={value:0};return Ve(n,y.MAX_DESCENDANTS_FOR_SCREENSHOT,t)}var Sn=9,We=2,vn=new Set(["auto","scroll","overlay"]),Tn=32;function Cn(n,t){let e=document.createElement("div").style;e.cssText=n;let i=document.createElement("div").style;i.cssText=t;for(let r=0;r<i.length;r+=1){let o=i.item(r);o&&e.setProperty(o,i.getPropertyValue(o),i.getPropertyPriority(o))}return e.cssText.trim()}function An(n){let t=n.getAttribute("data-original-style");return t!==null?decodeURIComponent(t):n.getAttribute("style")??""}function Rn(n){return Math.ceil(Math.max(n.body?.scrollHeight??0,n.documentElement?.scrollHeight??0,n.body?.offsetHeight??0,n.documentElement?.offsetHeight??0,n.body?.clientHeight??0,n.documentElement?.clientHeight??0))}function $e(n){return vn.has(n)}function Hn(n,t){let i=(n.defaultView??window).getComputedStyle(t);return t.scrollHeight>t.clientHeight&&($e(i.overflowY)||$e(i.overflow))}function xn(n){if(n.parentElement)return n.parentElement;let t=n.getRootNode();return t instanceof ShadowRoot&&t.host instanceof HTMLElement?t.host:null}function Ln(n,t){let e=n.defaultView??window,i=t;for(;i;){let r=e.getComputedStyle(i);if(r.visibility==="hidden"||r.display==="none"||parseFloat(r.opacity)===0)return!0;i=xn(i)}return!1}function*Ye(n){for(let t of n.querySelectorAll("*"))yield t,t.shadowRoot&&(yield*Ye(t.shadowRoot))}function Mn(n,t){let e=Xe(n,t);return e.height>0&&e.width>0}function _n(n){return Math.ceil(Math.max(n.scrollHeight,n.offsetHeight,n.clientHeight))}function Xe(n,t){let e=n.defaultView??window,i=t.getBoundingClientRect(),r=Math.max(i.top,0),o=Math.min(i.right,e.innerWidth),l=Math.min(i.bottom,e.innerHeight),s=Math.max(i.left,0);return{height:Math.max(0,Math.ceil(l-r)),width:Math.max(0,Math.ceil(o-s))}}function Ke(n){return n.visibleHeight*n.visibleWidth}function In(n,t){if(!t)return!0;let e=Ke(n),i=Ke(t);return e!==i?e>i:n.visibleWidth!==t.visibleWidth?n.visibleWidth>t.visibleWidth:n.visibleHeight!==t.visibleHeight?n.visibleHeight>t.visibleHeight:n.contentHeight>t.contentHeight}function Pn(n){if(!n.body)return 0;let t=null;for(let e of Ye(n.body)){if(!Hn(n,e)||Ln(n,e)||!Mn(n,e))continue;let i=Xe(n,e),r={contentHeight:_n(e),visibleHeight:i.height,visibleWidth:i.width};In(r,t)&&(t=r)}return t?.contentHeight??0}function Dn(n,t){let e=n.documentElement?.clientHeight??0;return t>e+Tn}function Nn(n=document){let t=Rn(n);return Dn(n,t)?t:Math.max(t,Pn(n))}function On(n){Event.prototype.stopPropagation.call(n)}var N=class n{selectedElement=null;selectedSiblingElements=[];visibleSelectedSiblingElements=[];isActive=!1;isCanvasGestureRelayEnabled=!1;isContextMenuRelayEnabled=!1;lastHighlightedElement=null;enableEditing=!1;dragStartPointer=null;dragRelayPointerId=null;scrollGestureState="idle";scrollGestureTimer=null;hoverMessages=!1;shadowHost=null;shadowRoot=null;hoverHighlighter=null;hoverLabel=null;selectedHighlighter=null;selectedLabel=null;hoverSiblingHighlighters=[];selectedSiblingHighlighters=[];mutationObserver=null;stableIds=new G;nodeMap=new Map;throttledRecalculate=null;source;acceptsRawMessages;installedVersion;constructor({source:t="installed",acceptsRawMessages:e=!0,installedVersion:i}={}){this.source=t,this.acceptsRawMessages=e,this.installedVersion=i,this.setupMessageListener(),this.observeLightDarkModeSwitch(),this.setupPinchInterception(),this.setupScrollChaining(),this.setupDragInterception(),this.setupIframeDoubleClickRelay(),this.setupContextMenuInterception(),this.notifyScriptLoaded(),this.throttledRecalculate=this.throttleRAF(this.recalculateSelectedElement.bind(this))}throttleRAF(t){let e=null,i=null;return(...r)=>{i=r,e===null&&(e=requestAnimationFrame(()=>{i!==null&&t(...i),e=null,i=null}))}}isPureTextElement(t){if(!t||!(t instanceof HTMLElement))return!1;let e=t.tagName.toLowerCase();return e==="style"||e==="script"||e==="img"||t.childElementCount>0?!1:Array.from(t.childNodes).every(r=>r.nodeType===Node.TEXT_NODE)}initializeHighlighter(){this.shadowHost=document.createElement("div"),this.shadowHost.style.all="initial",this.shadowRoot=this.shadowHost.attachShadow({mode:"open"}),document.body.appendChild(this.shadowHost);let t=document.createElement("style");t.textContent=se,this.shadowRoot.appendChild(t);let e=document.createElement("style");e.textContent=oe,document.head.appendChild(e),this.hoverHighlighter=document.createElement("div"),this.hoverLabel=document.createElement("div"),this.hoverHighlighter.className="beacon-highlighter beacon-hover-highlighter",this.hoverLabel.className="beacon-label beacon-hover-label",this.selectedHighlighter=document.createElement("div"),this.selectedLabel=document.createElement("div"),this.selectedHighlighter.className="beacon-highlighter beacon-selected-highlighter",this.selectedLabel.className="beacon-label beacon-selected-label",this.shadowRoot.appendChild(this.selectedHighlighter),this.shadowRoot.appendChild(this.selectedLabel),this.shadowRoot.appendChild(this.hoverHighlighter),this.shadowRoot.appendChild(this.hoverLabel)}setupMessageListener(){window.addEventListener("message",this.handleMessage.bind(this))}setupPinchInterception(){window.self!==window.top&&window.addEventListener("wheel",t=>{!this.isCanvasGestureRelayEnabled||!this.isZoomModifierWheel(t)||(t.preventDefault(),this.postMessageToParent({type:"PINCH_WHEEL",timestamp:Date.now(),deltaY:t.deltaY,clientX:t.clientX,clientY:t.clientY,shiftKey:t.shiftKey,altKey:t.altKey,ctrlKey:t.ctrlKey,metaKey:t.metaKey}))},{passive:!1})}setupIframeDoubleClickRelay(){window.self!==window.top&&(document.addEventListener("mousedown",t=>{!this.shouldRelayIframeDoubleClick()||t.detail<2||t.preventDefault()},!0),document.addEventListener("dblclick",t=>{this.shouldRelayIframeDoubleClick()&&(t.preventDefault(),On(t),this.postMessageToParent({type:"IFRAME_DOUBLE_CLICK",timestamp:Date.now(),clientX:t.clientX,clientY:t.clientY}))},!0))}setupContextMenuInterception(){window.self!==window.top&&window.addEventListener("contextmenu",t=>{if(!this.isContextMenuRelayEnabled)return;t.preventDefault(),t["stopImmediatePropagation"](),this.postMessageToParent({type:"IFRAME_CONTEXT_MENU",timestamp:Date.now(),clientX:t.clientX,clientY:t.clientY,altKey:t.altKey,ctrlKey:t.ctrlKey,metaKey:t.metaKey,shiftKey:t.shiftKey})},{capture:!0})}isZoomModifierWheel(t){return t.ctrlKey||t.altKey||t.metaKey}static SCROLL_GESTURE_GAP_MS=150;setupScrollChaining(){window.self!==window.top&&window.addEventListener("wheel",t=>{!this.isCanvasGestureRelayEnabled||this.isZoomModifierWheel(t)||(this.scrollGestureState==="idle"&&(this.scrollGestureState=this.shouldHandOffScrollToParent(t)?"at-boundary":"scrolling"),this.scrollGestureTimer&&clearTimeout(this.scrollGestureTimer),this.scrollGestureTimer=setTimeout(()=>{this.scrollGestureState="idle",this.scrollGestureTimer=null},n.SCROLL_GESTURE_GAP_MS),this.scrollGestureState==="at-boundary"&&(t.preventDefault(),this.postMessageToParent({type:"SCROLL_BOUNDARY",timestamp:Date.now(),deltaX:t.deltaX,deltaY:t.deltaY,clientX:t.clientX,clientY:t.clientY,shiftKey:t.shiftKey,altKey:t.altKey,ctrlKey:t.ctrlKey,metaKey:t.metaKey})))},{passive:!1})}shouldHandOffScrollToParent(t){let e=this.getRelevantScrollAxes(this.normalizeScrollDeltas(t));if(e.length===0)return!1;let i=document.elementFromPoint(t.clientX,t.clientY),r=e.map(({axis:o,delta:l})=>this.canAnyAncestorContinueScrollingOnAxis(i,o,l));return e.length===1?!r[0]:r.every(o=>!o)}getRelevantScrollAxes(t){let e=Math.abs(t.deltaX),i=Math.abs(t.deltaY);return e===0&&i===0?[]:e===0?[{axis:"y",delta:t.deltaY}]:i===0?[{axis:"x",delta:t.deltaX}]:e>=i*We?[{axis:"x",delta:t.deltaX}]:i>=e*We?[{axis:"y",delta:t.deltaY}]:[{axis:"x",delta:t.deltaX},{axis:"y",delta:t.deltaY}]}normalizeScrollDeltas(t){let{deltaX:e,deltaY:i}=t;return t.shiftKey&&!this.isMacPlatform()&&(e=i,i=0),{deltaX:e,deltaY:i}}isMacPlatform(){return navigator.platform.toUpperCase().includes("MAC")}canAnyAncestorContinueScrollingOnAxis(t,e,i){let r=t;for(;r;){if(r instanceof HTMLElement&&this.canElementScrollInDirection(r,e,i))return!0;r=r.parentElement}let o=document.scrollingElement;return o instanceof HTMLElement&&this.canElementScrollInDirection(o,e,i)}canElementScrollInDirection(t,e,i){if(i===0||!this.isScrollableOnAxis(t,e))return!1;let r=e==="x"?t.scrollLeft:t.scrollTop,o=e==="x"?t.scrollWidth-t.clientWidth:t.scrollHeight-t.clientHeight;return o<=0?!1:i>0?r<o-1:r>1}isScrollableOnAxis(t,e){let i=e==="x"?getComputedStyle(t).overflowX:getComputedStyle(t).overflowY;return t===document.scrollingElement||t===document.documentElement||t===document.body?i!=="hidden"&&i!=="clip":i==="auto"||i==="overlay"||i==="scroll"}setupDragInterception(){if(window.self===window.top)return;window.addEventListener("pointerdown",e=>{if(!this.shouldRelayCanvasPointerGestures()){this.dragStartPointer=null,this.dragRelayPointerId=null;return}e.button!==0||e.isPrimary===!1||(this.dragStartPointer={pointerId:e.pointerId,button:e.button,clientX:e.clientX,clientY:e.clientY,shiftKey:e.shiftKey,altKey:e.altKey,ctrlKey:e.ctrlKey,metaKey:e.metaKey})}),window.addEventListener("pointermove",e=>{if(!this.shouldRelayCanvasPointerGestures()){this.dragStartPointer=null,this.dragRelayPointerId=null;return}if(this.dragRelayPointerId===e.pointerId){e.preventDefault(),this.postMessageToParent({type:"DRAG_MOVE",timestamp:Date.now(),pointerId:e.pointerId,movementX:e.movementX,movementY:e.movementY,pressure:e.pressure,shiftKey:e.shiftKey,altKey:e.altKey,ctrlKey:e.ctrlKey,metaKey:e.metaKey});return}let i=this.dragStartPointer;if(i===null||i.pointerId!==e.pointerId)return;let r=e.clientX-i.clientX,o=e.clientY-i.clientY;r*r+o*o<Sn||(e.preventDefault(),this.cancelInteraction(),this.dragStartPointer=null,this.dragRelayPointerId=e.pointerId,this.postMessageToParent({type:"DRAG_START",timestamp:Date.now(),pointerId:e.pointerId,button:i.button,pressure:e.pressure,isPen:e.pointerType==="pen",clientX:e.clientX,clientY:e.clientY,startClientX:i.clientX,startClientY:i.clientY,shiftKey:i.shiftKey,altKey:i.altKey,ctrlKey:i.ctrlKey,metaKey:i.metaKey}))});let t=e=>{this.dragStartPointer?.pointerId===e.pointerId&&(this.dragStartPointer=null),this.dragRelayPointerId===e.pointerId&&(this.postMessageToParent({type:"DRAG_END",timestamp:Date.now(),pointerId:e.pointerId,button:e.button,clientX:e.clientX,clientY:e.clientY,pressure:e.pressure,isPen:e.pointerType==="pen",shiftKey:e.shiftKey,altKey:e.altKey,ctrlKey:e.ctrlKey,metaKey:e.metaKey}),this.dragRelayPointerId=null)};window.addEventListener("pointerup",t),window.addEventListener("pointercancel",t)}shouldRelayCanvasPointerGestures(){return this.isCanvasGestureRelayEnabled&&!(this.enableEditing&&this.selectedElement!==null)}shouldRelayIframeDoubleClick(){return this.isCanvasGestureRelayEnabled&&!this.enableEditing}notifyScriptLoaded(){let t={type:"SELECTOR_SCRIPT_LOADED",timestamp:Date.now(),version:B,source:this.source,supportsTargetedRouting:!0,...this.installedVersion?{installedVersion:this.installedVersion}:{}};this.postMessageToParent(t)}postMessageToParent(t){window.parent&&window.parent.postMessage(t,"*")}handleMouseMove=t=>{if(this.isActive){if(this.hoverMessages){let e=W(t);if(!e||e===this.shadowHost||e===this.selectedElement||e===this.lastHighlightedElement)return;this.lastHighlightedElement=e;let i=e===document.body||e===document.documentElement?document.body:e,r=i.getBoundingClientRect();this.postMessageToParent({type:"ELEMENT_HOVERED",timestamp:Date.now(),elementBounds:{x:r.x,y:r.y,width:r.width,height:r.height},elementName:x(i)});return}if(this.hoverHighlighter){let e=W(t);if(!e||e===this.hoverHighlighter||e===this.selectedHighlighter||e===this.shadowHost||this.selectedSiblingHighlighters.includes(e)||this.hoverSiblingHighlighters.includes(e)){this.hideHighlight(this.hoverHighlighter,this.hoverLabel),this.lastHighlightedElement=null,this.clearHoverSiblingHighlighters();return}if(e===this.selectedElement){this.hideHighlight(this.hoverHighlighter,this.hoverLabel),this.lastHighlightedElement=null,this.clearHoverSiblingHighlighters();return}this.lastHighlightedElement&&this.lastHighlightedElement!==e&&this.lastHighlightedElement!==this.selectedElement&&this.lastHighlightedElement.removeAttribute("contenteditable"),this.lastHighlightedElement=e,this.updateHighlighterPosition(e,this.hoverHighlighter,this.hoverLabel)}}};handleMouseLeave=()=>{if(this.isActive){if(this.hoverMessages){this.lastHighlightedElement&&(this.lastHighlightedElement=null,this.postMessageToParent({type:"ELEMENT_HOVERED",timestamp:Date.now(),elementBounds:null,elementName:""}));return}this.hoverHighlighter&&(this.hoverHighlighter.style.opacity="0"),this.hoverLabel&&(this.hoverLabel.style.opacity="0"),this.hoverSiblingHighlighters.length>0&&this.clearHoverSiblingHighlighters(),this.lastHighlightedElement&&this.lastHighlightedElement!==this.selectedElement&&this.lastHighlightedElement.removeAttribute("contenteditable")}};calculateLabelPosition(t,e){return e<28?{top:`${e}px`,left:`${t.left}px`,transform:"none",marginTop:"2px"}:{top:`${e}px`,left:`${t.left}px`,transform:"translateY(-100%)",marginTop:"-4px"}}updateHighlighterPosition(t,e,i){if(!e||!i)return;let r=D(t,y.MAX_SIBLING_HIGHLIGHTERS,!1);this.enableEditing&&r.length<=1&&t===this.selectedElement&&this.isPureTextElement(t)&&t.setAttribute("contenteditable","plaintext-only");let o=t.getBoundingClientRect(),l=window.innerHeight,s=Math.max(0,o.top),c=Math.min(l,o.bottom),h=Math.max(0,c-s);Object.assign(e.style,{opacity:h>0?"1":"0",top:`${s}px`,left:`${o.left}px`,width:`${o.width}px`,height:`${h}px`}),i.textContent=x(t);let a=this.calculateLabelPosition(o,s);Object.assign(i.style,{...a,opacity:h>0?"1":"0"}),e===this.selectedHighlighter?this.highlightSelectedSiblings(t):this.highlightHoverSiblings(t)}hideHighlight(t,e){t&&(t.style.opacity="0"),e&&(e.style.opacity="0");let i=t===this.hoverHighlighter,r=t===this.selectedHighlighter;i&&this.clearHoverSiblingHighlighters(),r&&this.clearSelectedSiblingHighlighters()}async buildElementPayload(t){this.nodeMap=new Map,Z(document.body,null,this.stableIds,this.nodeMap,this.shadowHost);let e=J(t,this.nodeMap),i;if(!Ge(t))try{i=await ke(t)}catch(r){console.error("[replit-cartographer] Error capturing element screenshot:",r)}return{metadata:e,screenshotBlob:i}}handleClick=async t=>{if(!this.isActive)return;t.preventDefault(),t.stopPropagation();let e=W(t);if((!e||e===this.hoverHighlighter||e===this.selectedHighlighter||e===this.shadowHost)&&(e=this.lastHighlightedElement),!e||e===this.selectedElement)return;if(this.hoverMessages){this.selectedElement=e,document.getElementById("replit-beacon-crosshair")?.remove();let s=e===document.body||e===document.documentElement?document.body:e,{metadata:c,screenshotBlob:h}=await this.buildElementPayload(s),a=s.getBoundingClientRect();this.postMessageToParent({type:"ELEMENT_SELECTED",payload:{...c,screenshotBlob:h??void 0,siblingCount:0},elementBounds:{x:a.x,y:a.y,width:a.width,height:a.height},timestamp:Date.now()});return}this.clearSelection(),this.selectedElement=e;let i=D(e),r=i.length>0;r&&this.highlightSelectedSiblings(e),e.hasAttribute("data-original-text")||e.setAttribute("data-original-text",encodeURIComponent(e.textContent??"")),!e.hasAttribute("data-original-style")&&e.hasAttribute("style")&&e.setAttribute("data-original-style",encodeURIComponent(e.getAttribute("style")??"")),!e.hasAttribute("data-original-src")&&e.hasAttribute("src")&&e.setAttribute("data-original-src",encodeURIComponent(e.getAttribute("src")??"")),!r&&this.enableEditing&&this.isPureTextElement(e)&&(this.selectedElement.setAttribute("contenteditable","plaintext-only"),this.selectedElement.focus()),this.selectedHighlighter&&this.selectedLabel&&(this.selectedHighlighter.style.outlineStyle="solid",this.selectedHighlighter.style.opacity="1",this.selectedHighlighter.style.pointerEvents="none",this.selectedLabel.style.opacity="1",this.selectedLabel.textContent=x(e)),this.hoverHighlighter&&(this.hoverHighlighter.style.opacity="0",this.hoverHighlighter.style.pointerEvents="none"),this.hoverLabel&&(this.hoverLabel.style.opacity="0"),this.clearHoverSiblingHighlighters(),this.updateHighlighterPosition(e,this.selectedHighlighter,this.selectedLabel);let{metadata:o,screenshotBlob:l}=await this.buildElementPayload(e);this.observeSelectedElement(),this.postMessageToParent({type:"ELEMENT_SELECTED",payload:{...o,screenshotBlob:l??void 0,siblingCount:r?i.length:0},timestamp:Date.now()})};restoreElements(){document.querySelectorAll('[data-replit-dirty="true"], [data-original-text], [data-original-style], [data-original-src]').forEach(e=>{if(e.hasAttribute("data-original-text")){if(e.textContent!==decodeURIComponent(e.getAttribute("data-original-text")||"")){let i=decodeURIComponent(e.getAttribute("data-original-text")||"");e.textContent=i}e.removeAttribute("data-original-text")}if(e.hasAttribute("data-original-style")){let i=decodeURIComponent(e.getAttribute("data-original-style")||"");e.setAttribute("style",i),e.removeAttribute("data-original-style")}else e.removeAttribute("style");if(e.hasAttribute("data-original-src")&&e.getAttribute("src")!==decodeURIComponent(e.getAttribute("data-original-src")||"")){let i=decodeURIComponent(e.getAttribute("data-original-src")||"");e.setAttribute("src",i),e.removeAttribute("data-original-src")}e.removeAttribute("data-replit-dirty")})}clearSelection(){this.selectedElement&&(this.selectedElement.removeAttribute("contenteditable"),this.selectedElement=null),this.clearSelectedSiblingHighlighters(),this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null)}isCommandMessage(t){switch(t.type){case"TOGGLE_REPLIT_VISUAL_EDITOR":case"CLEAR_SELECTION":case"UPDATE_SELECTED_ELEMENT":case"CLEAR_ELEMENT_DIRTY":case"RESTORE_DIRTY_ELEMENTS":case"APPLY_THEME_PREVIEW":case"CLEAR_THEME_PREVIEW":case"SCREENSHOT_PAGE":case"REQUEST_CONTENT_HEIGHT":case"RELAY_TO_IFRAME":return!0;default:return!1}}getMessageForThisBeacon(t){return t.type==="REPLIT_BEACON_TARGETED_MESSAGE"?t.targetSource!==this.source||!t.message||!this.isCommandMessage(t.message)?null:t.message:!this.acceptsRawMessages||!this.isCommandMessage(t)?null:t}handleMessage=t=>{if(!De(t.origin))return;let e=t.data;if(!e||typeof e!="object")return;let i=this.getMessageForThisBeacon(e);if(i)switch(i.type){case"TOGGLE_REPLIT_VISUAL_EDITOR":{this.handleVisualEditorToggle(i);break}case"CLEAR_SELECTION":{if(this.clearSelection(),this.hideHighlight(this.selectedHighlighter,this.selectedLabel),this.lastHighlightedElement=null,this.hoverMessages&&!document.getElementById("replit-beacon-crosshair")){let r=document.createElement("style");r.id="replit-beacon-crosshair",r.textContent="* { cursor: crosshair !important; }",document.head.appendChild(r)}break}case"UPDATE_SELECTED_ELEMENT":{if(!this.selectedElement)return;let{attributes:r}=i;[this.selectedElement,...this.selectedSiblingElements].forEach(l=>{r.style!==void 0&&(l.setAttribute("style",Cn(An(l),r.style)),l.setAttribute("data-replit-dirty","true")),r.textContent!==void 0&&(l.textContent=r.textContent,l.setAttribute("data-replit-dirty","true")),r.className!==void 0&&(l.className=r.className,l.setAttribute("data-replit-dirty","true")),r.src!==void 0&&(l.setAttribute("src",r.src),l.setAttribute("data-replit-dirty","true"))}),this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel),this.selectedSiblingElements.length>0&&(this.clearHighlighters(this.selectedSiblingHighlighters),this.selectedSiblingHighlighters=[],this.selectedSiblingHighlighters=this.highlightElements(this.selectedSiblingElements));break}case"CLEAR_ELEMENT_DIRTY":{let r=document.querySelectorAll('[data-replit-dirty="true"]');for(let o of r)o.removeAttribute("data-replit-dirty"),o.removeAttribute("data-original-text"),o.removeAttribute("data-original-style"),o.removeAttribute("data-original-src");break}case"RESTORE_DIRTY_ELEMENTS":{this.restoreElements();break}case"APPLY_THEME_PREVIEW":{this.handleApplyThemePreview(i);break}case"CLEAR_THEME_PREVIEW":{this.handleClearThemePreview();break}case"SCREENSHOT_PAGE":{this.handleScreenshotPage(i.requestId,i.capture);break}case"RELAY_TO_IFRAME":{this.handleRelayToIframe(i.event);break}case"REQUEST_CONTENT_HEIGHT":{this.handleContentHeightRequest(i.requestId);break}}};handleRelayToIframe(t){switch(t.kind){case"cancel-interaction":{this.cancelInteraction();break}case"set-canvas-gesture-relay":{this.isCanvasGestureRelayEnabled=t.enabled,this.dragStartPointer=null,this.dragRelayPointerId=null,this.scrollGestureState="idle",this.scrollGestureTimer&&(clearTimeout(this.scrollGestureTimer),this.scrollGestureTimer=null);break}case"set-canvas-relay-context-menu":{this.isContextMenuRelayEnabled=t.enabled;break}}}cancelInteraction(){document.getSelection()?.removeAllRanges(),document.activeElement instanceof HTMLElement&&document.activeElement.blur()}handleApplyThemePreview(t){if(t.type!=="APPLY_THEME_PREVIEW")return;let e=document.getElementById(y.THEME_PREVIEW_STYLE_ID);e||(e=document.createElement("style"),e.id=y.THEME_PREVIEW_STYLE_ID,document.head.appendChild(e)),e.textContent=t.themeContent}handleClearThemePreview(){let t=document.getElementById(y.THEME_PREVIEW_STYLE_ID);t&&t.remove()}async handleScreenshotPage(t,e="page"){try{let i=e==="viewport"?await Ue():await ee();this.postMessageToParent({type:"SCREENSHOT_PAGE_RESULT",timestamp:Date.now(),requestId:t,screenshotBlob:i})}catch(i){console.error("[replit-cartographer] Error capturing page screenshot:",i),this.postMessageToParent({type:"SCREENSHOT_PAGE_RESULT",timestamp:Date.now(),requestId:t,error:i instanceof Error?i.message:"Unknown screenshot error"})}}measureContentHeight(){return Nn()}handleContentHeightRequest(t){try{let e=this.measureContentHeight();this.postMessageToParent({type:"CONTENT_HEIGHT_RESULT",timestamp:Date.now(),requestId:t,contentHeight:e})}catch(e){this.postMessageToParent({type:"CONTENT_HEIGHT_RESULT",timestamp:Date.now(),requestId:t,error:e instanceof Error?e.message:"Unknown content height error"})}}handleVisualEditorToggle(t){if(t.type!=="TOGGLE_REPLIT_VISUAL_EDITOR")return;let e=!!t.enabled,i=this.hoverMessages;this.enableEditing=!!t.enableEditing,this.hoverMessages=!!t.hoverMessages,e?(this.hoverMessages||window.dispatchEvent(new CustomEvent("replit-init-tailwind")),this.postMessageToParent({type:"REPLIT_VISUAL_EDITOR_ENABLED",timestamp:Date.now(),hoverMessages:this.hoverMessages||void 0})):this.postMessageToParent({type:"REPLIT_VISUAL_EDITOR_DISABLED",timestamp:Date.now()}),this.isActive!==e?(this.isActive=e,this.toggleEventListeners(e)):this.isActive&&e&&i!==this.hoverMessages&&(this.toggleEventListeners(!1),this.toggleEventListeners(!0))}observeSelectedElement(){if(this.selectedElement){if(!this.isPureTextElement(this.selectedElement)){this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null);return}this.mutationObserver&&this.mutationObserver.disconnect(),this.mutationObserver=new MutationObserver(t=>{if(t.some(i=>i.type==="characterData")&&this.selectedElement){this.selectedElement.setAttribute("data-replit-dirty","true");let i=J(this.selectedElement,this.nodeMap);this.postMessageToParent({type:"ELEMENT_TEXT_CHANGED",payload:i,timestamp:Date.now()}),this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel)}}),this.mutationObserver.observe(this.selectedElement,{characterData:!0,childList:!1,attributes:!1,subtree:!0})}}observeLightDarkModeSwitch(){let t=new MutationObserver(i=>{i.forEach(r=>{r.type==="attributes"&&r.attributeName==="class"&&(r.target.classList.contains("dark")?this.postMessageToParent({type:"DARK_MODE_USED",timestamp:Date.now()}):this.postMessageToParent({type:"LIGHT_MODE_USED",timestamp:Date.now()}))})}),e=document.documentElement;t.observe(e,{attributes:!0,attributeFilter:["class"],childList:!1,subtree:!1})}recalculateSelectedElement=()=>{if(this.isActive){if(this.hoverMessages){if(this.lastHighlightedElement&&this.lastHighlightedElement!==this.selectedElement){let t=this.lastHighlightedElement===document.body||this.lastHighlightedElement===document.documentElement?document.body:this.lastHighlightedElement,e=t.getBoundingClientRect();this.postMessageToParent({type:"ELEMENT_HOVERED",timestamp:Date.now(),elementBounds:{x:e.x,y:e.y,width:e.width,height:e.height},elementName:x(t)})}return}this.selectedElement&&this.updateHighlighterPosition(this.selectedElement,this.selectedHighlighter,this.selectedLabel),this.lastHighlightedElement&&this.updateHighlighterPosition(this.lastHighlightedElement,this.hoverHighlighter,this.hoverLabel),this.selectedSiblingElements.length>0&&this.updateSiblingHighlighterPositions()}};updateSiblingHighlighterPositions(){for(let t=0;t<this.selectedSiblingHighlighters.length;t++){let e=this.selectedSiblingHighlighters[t],i=this.visibleSelectedSiblingElements[t];if(!e||!i)continue;let r=i.getBoundingClientRect(),o=window.innerHeight,l=Math.max(0,r.top),s=Math.min(o,r.bottom),c=Math.max(0,s-l);Object.assign(e.style,{opacity:c>0?"1":"0",top:`${l}px`,left:`${r.left}px`,width:`${r.width}px`,height:`${c}px`})}}handleKeyDown=t=>{if(this.isActive&&(t.key==="Escape"||t.key==="Esc")){if(this.hoverMessages){if(this.selectedElement){if(this.clearSelection(),this.lastHighlightedElement=null,!document.getElementById("replit-beacon-crosshair")){let e=document.createElement("style");e.id="replit-beacon-crosshair",e.textContent="* { cursor: crosshair !important; }",document.head.appendChild(e)}this.postMessageToParent({type:"ELEMENT_UNSELECTED",timestamp:Date.now()})}else this.handleVisualEditorToggle({type:"TOGGLE_REPLIT_VISUAL_EDITOR",enabled:!1,timestamp:Date.now()});return}this.handleVisualEditorToggle({type:"TOGGLE_REPLIT_VISUAL_EDITOR",enabled:!1,timestamp:Date.now()})}};toggleEventListeners(t){if(t){if(this.hoverMessages){let e=document.createElement("style");e.id="replit-beacon-crosshair",e.textContent="* { cursor: crosshair !important; }",document.head.appendChild(e)}else this.initializeHighlighter();this.enableDisabledElements(),document.addEventListener("mousemove",this.handleMouseMove),document.addEventListener("mouseleave",this.handleMouseLeave),document.addEventListener("click",this.handleClick,!0),document.addEventListener("keydown",this.handleKeyDown),this.throttledRecalculate&&(window.addEventListener("resize",this.throttledRecalculate),window.addEventListener("scroll",this.throttledRecalculate,!0))}else document.getElementById("replit-beacon-crosshair")?.remove(),this.restoreDisabledElements(),this.restoreElements(),document.removeEventListener("mousemove",this.handleMouseMove),document.removeEventListener("click",this.handleClick,!0),document.removeEventListener("mouseleave",this.handleMouseLeave),document.removeEventListener("keydown",this.handleKeyDown),this.throttledRecalculate&&(window.removeEventListener("resize",this.throttledRecalculate),window.removeEventListener("scroll",this.throttledRecalculate,!0)),this.mutationObserver&&(this.mutationObserver.disconnect(),this.mutationObserver=null),this.selectedElement&&(this.selectedElement.removeAttribute("contenteditable"),this.selectedElement.removeAttribute("data-original-text"),document.querySelectorAll('[contenteditable="plaintext-only"]').forEach(e=>{e.removeAttribute("contenteditable")})),this.clearSelectedSiblingHighlighters(),this.clearHoverSiblingHighlighters(),this.hoverHighlighter?.remove(),this.hoverLabel?.remove(),this.selectedHighlighter?.remove(),this.selectedLabel?.remove(),this.shadowHost?.remove(),this.hoverHighlighter=null,this.hoverLabel=null,this.selectedHighlighter=null,this.selectedLabel=null,this.shadowHost=null,this.shadowRoot=null,this.selectedElement=null}clearHighlighters(t){return t.forEach(e=>{e.remove()}),[]}clearHoverSiblingHighlighters(){this.hoverSiblingHighlighters=this.clearHighlighters(this.hoverSiblingHighlighters)}clearSelectedSiblingHighlighters(){this.selectedSiblingElements.forEach(t=>{t.removeAttribute("contenteditable")}),this.selectedSiblingElements=[],this.visibleSelectedSiblingElements=[],this.selectedSiblingHighlighters=this.clearHighlighters(this.selectedSiblingHighlighters)}highlightElements(t){if(!this.shadowRoot||t.length===0)return[];let e=[];return t.forEach(i=>{let r=document.createElement("div");r.className="beacon-highlighter beacon-sibling-highlighter",this.shadowRoot?.appendChild(r),e.push(r);let o=i.getBoundingClientRect(),l=window.innerHeight,s=Math.max(0,o.top),c=Math.min(l,o.bottom),h=Math.max(0,c-s);Object.assign(r.style,{opacity:h>0?"1":"0",top:`${s}px`,left:`${o.left}px`,width:`${o.width}px`,height:`${h}px`})}),e}highlightHoverSiblings(t){this.clearHoverSiblingHighlighters();let e=D(t,y.MAX_SIBLING_HIGHLIGHTERS,!0);this.hoverSiblingHighlighters=this.highlightElements(e)}highlightSelectedSiblings(t){this.clearSelectedSiblingHighlighters();let e=D(t),i=e.filter(r=>te(r));this.selectedSiblingElements=e,this.visibleSelectedSiblingElements=i,this.selectedSiblingHighlighters=this.highlightElements(i)}enableDisabledElements(){document.querySelectorAll("button[disabled], input[disabled]").forEach(t=>{t.removeAttribute("disabled"),t.setAttribute("data-replit-disabled","")})}restoreDisabledElements(){document.querySelectorAll("[data-replit-disabled]").forEach(t=>{t.removeAttribute("data-replit-disabled"),t.setAttribute("disabled","")})}};function ne(n){return n.includes("standalone")?"standalone":"installed"}function ie({currentVersion:n,existingVersion:t,existingCoexistenceStandaloneVersion:e}){let i=ne(n);if(!t)return{options:{source:i,acceptsRawMessages:!0},globalVersion:n,coexistenceStandaloneVersion:null};let r=ne(t);return i==="standalone"&&r==="installed"?e?{options:null,globalVersion:null,coexistenceStandaloneVersion:null}:{options:{source:"standalone",acceptsRawMessages:!1,installedVersion:t},globalVersion:null,coexistenceStandaloneVersion:n}:{options:null,globalVersion:null,coexistenceStandaloneVersion:null}}if(typeof window<"u")try{let n=ie({currentVersion:B,existingVersion:window.REPLIT_BEACON_VERSION,existingCoexistenceStandaloneVersion:window.REPLIT_BEACON_COEXISTENCE_STANDALONE_VERSION});n.options&&new N(n.options),n.globalVersion&&(window.REPLIT_BEACON_VERSION=n.globalVersion),n.coexistenceStandaloneVersion&&(window.REPLIT_BEACON_COEXISTENCE_STANDALONE_VERSION=n.coexistenceStandaloneVersion)}catch(n){console.error("[replit-beacon] Failed to initialize:",n)}})();
</script>
    <script>(function() {
  var initialized = false;

  function loadTailwind() {
    if (initialized) { return; }
    initialized = true;

        var script = document.createElement('script');
        script.src = "https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4.1.14";

        if (window.REPLIT_APP_TAILWIND_CONFIG) {
          script.setAttribute('data-config', JSON.stringify(window.REPLIT_APP_TAILWIND_CONFIG));
        }

        document.head.appendChild(script);
  }

  // Listen for the beacon requesting tailwind initialization.
  window.addEventListener('replit-init-tailwind', function() {
    if (window.REPLIT_APP_TAILWIND_CONFIG) {
      loadTailwind();
    } else {
      // Config not ready yet — wait for the config-ready event, but proceed
      // without a config after 1 second.  The config is optional (projects
      // without a tailwind config file will never fire the ready event).
      var configTimeout = setTimeout(function() { loadTailwind(); }, 1000);
      window.addEventListener('replit-tailwind-config-ready', function() {
        clearTimeout(configTimeout);
        loadTailwind();
      }, { once: true });
    }
  });
})();</script>
    <script>window.REPLIT_APP_THEME_TOKENS = {"color":[{"suffix":"background","expr":"hsl(var(--background))"},{"suffix":"foreground","expr":"hsl(var(--foreground))"},{"suffix":"border","expr":"hsl(var(--border))"},{"suffix":"input","expr":"hsl(var(--input))"},{"suffix":"ring","expr":"hsl(var(--ring))"},{"suffix":"card","expr":"hsl(var(--card))"},{"suffix":"card-foreground","expr":"hsl(var(--card-foreground))"},{"suffix":"card-border","expr":"hsl(var(--card-border))"},{"suffix":"popover","expr":"hsl(var(--popover))"},{"suffix":"popover-foreground","expr":"hsl(var(--popover-foreground))"},{"suffix":"popover-border","expr":"hsl(var(--popover-border))"},{"suffix":"primary","expr":"hsl(var(--primary))"},{"suffix":"primary-foreground","expr":"hsl(var(--primary-foreground))"},{"suffix":"primary-border","expr":"var(--primary-border)"},{"suffix":"secondary","expr":"hsl(var(--secondary))"},{"suffix":"secondary-foreground","expr":"hsl(var(--secondary-foreground))"},{"suffix":"secondary-border","expr":"var(--secondary-border)"},{"suffix":"muted","expr":"hsl(var(--muted))"},{"suffix":"muted-foreground","expr":"hsl(var(--muted-foreground))"},{"suffix":"muted-border","expr":"var(--muted-border)"},{"suffix":"accent","expr":"hsl(var(--accent))"},{"suffix":"accent-foreground","expr":"hsl(var(--accent-foreground))"},{"suffix":"accent-border","expr":"var(--accent-border)"},{"suffix":"destructive","expr":"hsl(var(--destructive))"},{"suffix":"destructive-foreground","expr":"hsl(var(--destructive-foreground))"},{"suffix":"destructive-border","expr":"var(--destructive-border)"}],"font":[{"suffix":"sans","expr":"'Plus Jakarta Sans', sans-serif"},{"suffix":"display","expr":"'Space Grotesk', sans-serif"}],"radius":[{"suffix":"sm","expr":"calc(var(--radius) - 4px)"},{"suffix":"md","expr":"calc(var(--radius) - 2px)"},{"suffix":"lg","expr":"var(--radius)"},{"suffix":"xl","expr":"calc(var(--radius) + 4px)"}]};</script>
    <script type="text/javascript" src="./Team Kalam_files/banner-script.js.download" id="replit-dev-banner"></script><style>
    #replit-dev-banner {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      z-index: 9999;
      display: flex;
      align-items: center;
      padding: 8px 16px;
      background-color: #004182;
      color: white;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;
      font-size: 14px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
      transition: opacity 0.2s ease-in-out;
    }
    
    .banner-text {
      flex-grow: 1;
    }
    
    .banner-link {
      color: white;
      font-weight: 500;
      text-decoration: underline;
    }
    
    .banner-link:hover {
      text-decoration: none;
    }
    
    .banner-close {
      flex-shrink: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      width: 28px;
      height: 28px;
      border: none;
      background: transparent;
      cursor: pointer;
      padding: 0;
      color: rgba(255, 255, 255, 0.7);
      margin-left: 12px;
      transition: transform 0.1s ease-in-out, color 0.1s ease-in-out;
    }
    
    .banner-close:hover {
      transform: scale(1.05);
      color: white;
    }
    
    @media (max-width: 600px) {
      #replit-dev-banner {
        padding: 8px;
        font-size: 12px;
      }
      
      .banner-close {
        width: 24px;
        height: 24px;
        margin-left: 8px;
      }
    }
  </style>
  <style type="text/css" data-vite-dev-id="/home/runner/workspace/artifacts/team-kalam/src/index.css">
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Plus+Jakarta+Sans:wght@400;500;600;700&display=swap');
@layer properties;
@layer theme, base, components, utilities;
/*! tailwindcss v4.3.0 | MIT License | https://tailwindcss.com */
@layer theme {
  :root, :host {
    --font-mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono",
      "Courier New", monospace;
    --color-red-50: oklch(97.1% 0.013 17.38);
    --color-red-300: oklch(80.8% 0.114 19.571);
    --color-red-400: oklch(70.4% 0.191 22.216);
    --color-red-500: oklch(63.7% 0.237 25.331);
    --color-red-600: oklch(57.7% 0.245 27.325);
    --color-orange-400: oklch(75% 0.183 55.934);
    --color-orange-500: oklch(70.5% 0.213 47.604);
    --color-amber-400: oklch(82.8% 0.189 84.429);
    --color-yellow-400: oklch(85.2% 0.199 91.936);
    --color-yellow-500: oklch(79.5% 0.184 86.047);
    --color-emerald-500: oklch(69.6% 0.17 162.48);
    --color-teal-400: oklch(77.7% 0.152 181.912);
    --color-cyan-400: oklch(78.9% 0.154 211.53);
    --color-blue-400: oklch(70.7% 0.165 254.624);
    --color-blue-500: oklch(62.3% 0.214 259.815);
    --color-purple-500: oklch(62.7% 0.265 303.9);
    --color-pink-400: oklch(71.8% 0.202 349.761);
    --color-gray-50: oklch(98.5% 0.002 247.839);
    --color-gray-600: oklch(44.6% 0.03 256.802);
    --color-gray-900: oklch(21% 0.034 264.665);
    --color-black: #000;
    --color-white: #fff;
    --spacing: 0.25rem;
    --container-sm: 24rem;
    --container-md: 28rem;
    --container-lg: 32rem;
    --container-2xl: 42rem;
    --container-3xl: 48rem;
    --container-4xl: 56rem;
    --container-5xl: 64rem;
    --container-6xl: 72rem;
    --container-7xl: 80rem;
    --text-xs: 0.75rem;
    --text-xs--line-height: calc(1 / 0.75);
    --text-sm: 0.875rem;
    --text-sm--line-height: calc(1.25 / 0.875);
    --text-base: 1rem;
    --text-base--line-height: calc(1.5 / 1);
    --text-lg: 1.125rem;
    --text-lg--line-height: calc(1.75 / 1.125);
    --text-xl: 1.25rem;
    --text-xl--line-height: calc(1.75 / 1.25);
    --text-2xl: 1.5rem;
    --text-2xl--line-height: calc(2 / 1.5);
    --text-3xl: 1.875rem;
    --text-3xl--line-height: calc(2.25 / 1.875);
    --text-4xl: 2.25rem;
    --text-4xl--line-height: calc(2.5 / 2.25);
    --text-5xl: 3rem;
    --text-5xl--line-height: 1;
    --text-6xl: 3.75rem;
    --text-6xl--line-height: 1;
    --text-8xl: 6rem;
    --text-8xl--line-height: 1;
    --text-9xl: 8rem;
    --text-9xl--line-height: 1;
    --font-weight-normal: 400;
    --font-weight-medium: 500;
    --font-weight-semibold: 600;
    --font-weight-bold: 700;
    --tracking-tighter: -0.05em;
    --tracking-tight: -0.025em;
    --tracking-wide: 0.025em;
    --tracking-wider: 0.05em;
    --tracking-widest: 0.1em;
    --leading-tight: 1.25;
    --leading-snug: 1.375;
    --leading-normal: 1.5;
    --leading-relaxed: 1.625;
    --radius-2xl: 1rem;
    --radius-3xl: 1.5rem;
    --ease-out: cubic-bezier(0, 0, 0.2, 1);
    --ease-in-out: cubic-bezier(0.4, 0, 0.2, 1);
    --animate-spin: spin 1s linear infinite;
    --animate-pulse: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
    --blur-md: 12px;
    --aspect-video: 16 / 9;
    --default-transition-duration: 150ms;
    --default-transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
    --default-font-family: 'Plus Jakarta Sans', sans-serif;
    --default-mono-font-family: var(--font-mono);
    --color-border: hsl(var(--border));
    --color-card: hsl(var(--card));
    --color-primary: hsl(var(--primary));
    --font-display: 'Space Grotesk', sans-serif;
  }
}
@layer base {
  *, ::after, ::before, ::backdrop, ::file-selector-button {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    border: 0 solid;
  }
  html, :host {
    line-height: 1.5;
    -webkit-text-size-adjust: 100%;
    tab-size: 4;
    font-family: var(--default-font-family, ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji");
    font-feature-settings: var(--default-font-feature-settings, normal);
    font-variation-settings: var(--default-font-variation-settings, normal);
    -webkit-tap-highlight-color: transparent;
  }
  hr {
    height: 0;
    color: inherit;
    border-top-width: 1px;
  }
  abbr:where([title]) {
    -webkit-text-decoration: underline dotted;
    text-decoration: underline dotted;
  }
  h1, h2, h3, h4, h5, h6 {
    font-size: inherit;
    font-weight: inherit;
  }
  a {
    color: inherit;
    -webkit-text-decoration: inherit;
    text-decoration: inherit;
  }
  b, strong {
    font-weight: bolder;
  }
  code, kbd, samp, pre {
    font-family: var(--default-mono-font-family, ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace);
    font-feature-settings: var(--default-mono-font-feature-settings, normal);
    font-variation-settings: var(--default-mono-font-variation-settings, normal);
    font-size: 1em;
  }
  small {
    font-size: 80%;
  }
  sub, sup {
    font-size: 75%;
    line-height: 0;
    position: relative;
    vertical-align: baseline;
  }
  sub {
    bottom: -0.25em;
  }
  sup {
    top: -0.5em;
  }
  table {
    text-indent: 0;
    border-color: inherit;
    border-collapse: collapse;
  }
  :-moz-focusring {
    outline: auto;
  }
  progress {
    vertical-align: baseline;
  }
  summary {
    display: list-item;
  }
  ol, ul, menu {
    list-style: none;
  }
  img, svg, video, canvas, audio, iframe, embed, object {
    display: block;
    vertical-align: middle;
  }
  img, video {
    max-width: 100%;
    height: auto;
  }
  button, input, select, optgroup, textarea, ::file-selector-button {
    font: inherit;
    font-feature-settings: inherit;
    font-variation-settings: inherit;
    letter-spacing: inherit;
    color: inherit;
    border-radius: 0;
    background-color: transparent;
    opacity: 1;
  }
  :where(select:is([multiple], [size])) optgroup {
    font-weight: bolder;
  }
  :where(select:is([multiple], [size])) optgroup option {
    padding-inline-start: 20px;
  }
  ::file-selector-button {
    margin-inline-end: 4px;
  }
  ::placeholder {
    opacity: 1;
  }
  @supports (not (-webkit-appearance: -apple-pay-button))  or (contain-intrinsic-size: 1px) {
    ::placeholder {
      color: currentcolor;
      @supports (color: color-mix(in lab, red, red)) {
        color: color-mix(in oklab, currentcolor 50%, transparent);
      }
    }
  }
  textarea {
    resize: vertical;
  }
  ::-webkit-search-decoration {
    -webkit-appearance: none;
  }
  ::-webkit-date-and-time-value {
    min-height: 1lh;
    text-align: inherit;
  }
  ::-webkit-datetime-edit {
    display: inline-flex;
  }
  ::-webkit-datetime-edit-fields-wrapper {
    padding: 0;
  }
  ::-webkit-datetime-edit, ::-webkit-datetime-edit-year-field, ::-webkit-datetime-edit-month-field, ::-webkit-datetime-edit-day-field, ::-webkit-datetime-edit-hour-field, ::-webkit-datetime-edit-minute-field, ::-webkit-datetime-edit-second-field, ::-webkit-datetime-edit-millisecond-field, ::-webkit-datetime-edit-meridiem-field {
    padding-block: 0;
  }
  ::-webkit-calendar-picker-indicator {
    line-height: 1;
  }
  :-moz-ui-invalid {
    box-shadow: none;
  }
  button, input:where([type="button"], [type="reset"], [type="submit"]), ::file-selector-button {
    appearance: button;
  }
  ::-webkit-inner-spin-button, ::-webkit-outer-spin-button {
    height: auto;
  }
  [hidden]:where(:not([hidden="until-found"])) {
    display: none !important;
  }
}
@layer utilities {
  .\@container\/field-group {
    container-type: inline-size;
    container-name: field-group;
  }
  .pointer-events-auto {
    pointer-events: auto;
  }
  .pointer-events-none {
    pointer-events: none;
  }
  .invisible {
    visibility: hidden;
  }
  .sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip-path: inset(50%);
    white-space: nowrap;
    border-width: 0;
  }
  .absolute {
    position: absolute;
  }
  .fixed {
    position: fixed;
  }
  .relative {
    position: relative;
  }
  .static {
    position: static;
  }
  .inset-0 {
    inset: calc(var(--spacing) * 0);
  }
  .inset-x-0 {
    inset-inline: calc(var(--spacing) * 0);
  }
  .inset-y-0 {
    inset-block: calc(var(--spacing) * 0);
  }
  .-top-12 {
    top: calc(var(--spacing) * -12);
  }
  .-top-16 {
    top: calc(var(--spacing) * -16);
  }
  .top-0 {
    top: calc(var(--spacing) * 0);
  }
  .top-1\.5 {
    top: calc(var(--spacing) * 1.5);
  }
  .top-1\/2 {
    top: calc(1 / 2 * 100%);
  }
  .top-1\/4 {
    top: calc(1 / 4 * 100%);
  }
  .top-2 {
    top: calc(var(--spacing) * 2);
  }
  .top-3\.5 {
    top: calc(var(--spacing) * 3.5);
  }
  .top-4 {
    top: calc(var(--spacing) * 4);
  }
  .top-\[1px\] {
    top: 1px;
  }
  .top-\[50\%\] {
    top: 50%;
  }
  .top-\[60\%\] {
    top: 60%;
  }
  .top-full {
    top: 100%;
  }
  .-right-12 {
    right: calc(var(--spacing) * -12);
  }
  .-right-16 {
    right: calc(var(--spacing) * -16);
  }
  .right-0 {
    right: calc(var(--spacing) * 0);
  }
  .right-1 {
    right: calc(var(--spacing) * 1);
  }
  .right-1\/4 {
    right: calc(1 / 4 * 100%);
  }
  .right-2 {
    right: calc(var(--spacing) * 2);
  }
  .right-3 {
    right: calc(var(--spacing) * 3);
  }
  .right-4 {
    right: calc(var(--spacing) * 4);
  }
  .-bottom-12 {
    bottom: calc(var(--spacing) * -12);
  }
  .bottom-0 {
    bottom: calc(var(--spacing) * 0);
  }
  .bottom-1\/4 {
    bottom: calc(1 / 4 * 100%);
  }
  .bottom-8 {
    bottom: calc(var(--spacing) * 8);
  }
  .-left-12 {
    left: calc(var(--spacing) * -12);
  }
  .left-0 {
    left: calc(var(--spacing) * 0);
  }
  .left-1\/2 {
    left: calc(1 / 2 * 100%);
  }
  .left-1\/4 {
    left: calc(1 / 4 * 100%);
  }
  .left-2 {
    left: calc(var(--spacing) * 2);
  }
  .left-\[28px\] {
    left: 28px;
  }
  .left-\[50\%\] {
    left: 50%;
  }
  .z-0 {
    z-index: 0;
  }
  .z-10 {
    z-index: 10;
  }
  .z-20 {
    z-index: 20;
  }
  .z-50 {
    z-index: 50;
  }
  .z-\[1\] {
    z-index: 1;
  }
  .z-\[100\] {
    z-index: 100;
  }
  .order-first {
    order: -9999;
  }
  .order-last {
    order: 9999;
  }
  .container {
    width: 100%;
    @media (width >= 40rem) {
      max-width: 40rem;
    }
    @media (width >= 48rem) {
      max-width: 48rem;
    }
    @media (width >= 64rem) {
      max-width: 64rem;
    }
    @media (width >= 80rem) {
      max-width: 80rem;
    }
    @media (width >= 96rem) {
      max-width: 96rem;
    }
  }
  .\!m-0 {
    margin: calc(var(--spacing) * 0) !important;
  }
  .-mx-1 {
    margin-inline: calc(var(--spacing) * -1);
  }
  .mx-2 {
    margin-inline: calc(var(--spacing) * 2);
  }
  .mx-3\.5 {
    margin-inline: calc(var(--spacing) * 3.5);
  }
  .mx-4 {
    margin-inline: calc(var(--spacing) * 4);
  }
  .mx-auto {
    margin-inline: auto;
  }
  .-my-2 {
    margin-block: calc(var(--spacing) * -2);
  }
  .my-0 {
    margin-block: calc(var(--spacing) * 0);
  }
  .my-0\.5 {
    margin-block: calc(var(--spacing) * 0.5);
  }
  .my-1 {
    margin-block: calc(var(--spacing) * 1);
  }
  .-mt-4 {
    margin-top: calc(var(--spacing) * -4);
  }
  .mt-1\.5 {
    margin-top: calc(var(--spacing) * 1.5);
  }
  .mt-2 {
    margin-top: calc(var(--spacing) * 2);
  }
  .mt-4 {
    margin-top: calc(var(--spacing) * 4);
  }
  .mt-24 {
    margin-top: calc(var(--spacing) * 24);
  }
  .mt-auto {
    margin-top: auto;
  }
  .mr-2 {
    margin-right: calc(var(--spacing) * 2);
  }
  .mb-1 {
    margin-bottom: calc(var(--spacing) * 1);
  }
  .mb-2 {
    margin-bottom: calc(var(--spacing) * 2);
  }
  .mb-3 {
    margin-bottom: calc(var(--spacing) * 3);
  }
  .mb-4 {
    margin-bottom: calc(var(--spacing) * 4);
  }
  .mb-6 {
    margin-bottom: calc(var(--spacing) * 6);
  }
  .mb-8 {
    margin-bottom: calc(var(--spacing) * 8);
  }
  .mb-10 {
    margin-bottom: calc(var(--spacing) * 10);
  }
  .mb-12 {
    margin-bottom: calc(var(--spacing) * 12);
  }
  .mb-16 {
    margin-bottom: calc(var(--spacing) * 16);
  }
  .mb-20 {
    margin-bottom: calc(var(--spacing) * 20);
  }
  .mb-24 {
    margin-bottom: calc(var(--spacing) * 24);
  }
  .-ml-4 {
    margin-left: calc(var(--spacing) * -4);
  }
  .ml-1 {
    margin-left: calc(var(--spacing) * 1);
  }
  .ml-4 {
    margin-left: calc(var(--spacing) * 4);
  }
  .ml-auto {
    margin-left: auto;
  }
  .line-clamp-2 {
    overflow: hidden;
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 2;
  }
  .block {
    display: block;
  }
  .flex {
    display: flex;
  }
  .grid {
    display: grid;
  }
  .hidden {
    display: none;
  }
  .inline-block {
    display: inline-block;
  }
  .inline-flex {
    display: inline-flex;
  }
  .table {
    display: table;
  }
  .aspect-square {
    aspect-ratio: 1 / 1;
  }
  .aspect-video {
    aspect-ratio: var(--aspect-video);
  }
  .size-4 {
    width: calc(var(--spacing) * 4);
    height: calc(var(--spacing) * 4);
  }
  .size-6 {
    width: calc(var(--spacing) * 6);
    height: calc(var(--spacing) * 6);
  }
  .size-8 {
    width: calc(var(--spacing) * 8);
    height: calc(var(--spacing) * 8);
  }
  .size-10 {
    width: calc(var(--spacing) * 10);
    height: calc(var(--spacing) * 10);
  }
  .size-\[--cell-size\] {
    width: --cell-size;
    height: --cell-size;
  }
  .h-0 {
    height: calc(var(--spacing) * 0);
  }
  .h-1\.5 {
    height: calc(var(--spacing) * 1.5);
  }
  .h-2 {
    height: calc(var(--spacing) * 2);
  }
  .h-2\.5 {
    height: calc(var(--spacing) * 2.5);
  }
  .h-3 {
    height: calc(var(--spacing) * 3);
  }
  .h-3\.5 {
    height: calc(var(--spacing) * 3.5);
  }
  .h-4 {
    height: calc(var(--spacing) * 4);
  }
  .h-5 {
    height: calc(var(--spacing) * 5);
  }
  .h-6 {
    height: calc(var(--spacing) * 6);
  }
  .h-7 {
    height: calc(var(--spacing) * 7);
  }
  .h-8 {
    height: calc(var(--spacing) * 8);
  }
  .h-9 {
    height: calc(var(--spacing) * 9);
  }
  .h-10 {
    height: calc(var(--spacing) * 10);
  }
  .h-12 {
    height: calc(var(--spacing) * 12);
  }
  .h-14 {
    height: calc(var(--spacing) * 14);
  }
  .h-16 {
    height: calc(var(--spacing) * 16);
  }
  .h-20 {
    height: calc(var(--spacing) * 20);
  }
  .h-24 {
    height: calc(var(--spacing) * 24);
  }
  .h-28 {
    height: calc(var(--spacing) * 28);
  }
  .h-48 {
    height: calc(var(--spacing) * 48);
  }
  .h-\[--cell-size\] {
    height: --cell-size;
  }
  .h-\[1px\] {
    height: 1px;
  }
  .h-\[2px\] {
    height: 2px;
  }
  .h-\[300px\] {
    height: 300px;
  }
  .h-\[400px\] {
    height: 400px;
  }
  .h-\[500px\] {
    height: 500px;
  }
  .h-\[600px\] {
    height: 600px;
  }
  .h-\[var\(--radix-navigation-menu-viewport-height\)\] {
    height: var(--radix-navigation-menu-viewport-height);
  }
  .h-\[var\(--radix-select-trigger-height\)\] {
    height: var(--radix-select-trigger-height);
  }
  .h-auto {
    height: auto;
  }
  .h-full {
    height: 100%;
  }
  .h-px {
    height: 1px;
  }
  .h-svh {
    height: 100svh;
  }
  .max-h-\[--radix-context-menu-content-available-height\] {
    max-height: --radix-context-menu-content-available-height;
  }
  .max-h-\[--radix-select-content-available-height\] {
    max-height: --radix-select-content-available-height;
  }
  .max-h-\[300px\] {
    max-height: 300px;
  }
  .max-h-\[var\(--radix-dropdown-menu-content-available-height\)\] {
    max-height: var(--radix-dropdown-menu-content-available-height);
  }
  .max-h-screen {
    max-height: 100vh;
  }
  .min-h-0 {
    min-height: calc(var(--spacing) * 0);
  }
  .min-h-8 {
    min-height: calc(var(--spacing) * 8);
  }
  .min-h-9 {
    min-height: calc(var(--spacing) * 9);
  }
  .min-h-10 {
    min-height: calc(var(--spacing) * 10);
  }
  .min-h-\[60px\] {
    min-height: 60px;
  }
  .min-h-screen {
    min-height: 100vh;
  }
  .min-h-svh {
    min-height: 100svh;
  }
  .w-0 {
    width: calc(var(--spacing) * 0);
  }
  .w-1 {
    width: calc(var(--spacing) * 1);
  }
  .w-2 {
    width: calc(var(--spacing) * 2);
  }
  .w-2\.5 {
    width: calc(var(--spacing) * 2.5);
  }
  .w-3 {
    width: calc(var(--spacing) * 3);
  }
  .w-3\.5 {
    width: calc(var(--spacing) * 3.5);
  }
  .w-3\/4 {
    width: calc(3 / 4 * 100%);
  }
  .w-4 {
    width: calc(var(--spacing) * 4);
  }
  .w-5 {
    width: calc(var(--spacing) * 5);
  }
  .w-6 {
    width: calc(var(--spacing) * 6);
  }
  .w-7 {
    width: calc(var(--spacing) * 7);
  }
  .w-8 {
    width: calc(var(--spacing) * 8);
  }
  .w-9 {
    width: calc(var(--spacing) * 9);
  }
  .w-10 {
    width: calc(var(--spacing) * 10);
  }
  .w-12 {
    width: calc(var(--spacing) * 12);
  }
  .w-14 {
    width: calc(var(--spacing) * 14);
  }
  .w-16 {
    width: calc(var(--spacing) * 16);
  }
  .w-24 {
    width: calc(var(--spacing) * 24);
  }
  .w-28 {
    width: calc(var(--spacing) * 28);
  }
  .w-48 {
    width: calc(var(--spacing) * 48);
  }
  .w-64 {
    width: calc(var(--spacing) * 64);
  }
  .w-72 {
    width: calc(var(--spacing) * 72);
  }
  .w-\[--cell-size\] {
    width: --cell-size;
  }
  .w-\[1px\] {
    width: 1px;
  }
  .w-\[100px\] {
    width: 100px;
  }
  .w-\[300px\] {
    width: 300px;
  }
  .w-\[400px\] {
    width: 400px;
  }
  .w-\[500px\] {
    width: 500px;
  }
  .w-\[600px\] {
    width: 600px;
  }
  .w-\[800px\] {
    width: 800px;
  }
  .w-\[var\(--sidebar-width\)\] {
    width: var(--sidebar-width);
  }
  .w-auto {
    width: auto;
  }
  .w-fit {
    width: fit-content;
  }
  .w-full {
    width: 100%;
  }
  .w-max {
    width: max-content;
  }
  .w-px {
    width: 1px;
  }
  .max-w-2xl {
    max-width: var(--container-2xl);
  }
  .max-w-3xl {
    max-width: var(--container-3xl);
  }
  .max-w-4xl {
    max-width: var(--container-4xl);
  }
  .max-w-5xl {
    max-width: var(--container-5xl);
  }
  .max-w-6xl {
    max-width: var(--container-6xl);
  }
  .max-w-7xl {
    max-width: var(--container-7xl);
  }
  .max-w-\[80px\] {
    max-width: 80px;
  }
  .max-w-\[var\(--skeleton-width\)\] {
    max-width: var(--skeleton-width);
  }
  .max-w-lg {
    max-width: var(--container-lg);
  }
  .max-w-max {
    max-width: max-content;
  }
  .max-w-md {
    max-width: var(--container-md);
  }
  .max-w-sm {
    max-width: var(--container-sm);
  }
  .min-w-0 {
    min-width: calc(var(--spacing) * 0);
  }
  .min-w-5 {
    min-width: calc(var(--spacing) * 5);
  }
  .min-w-8 {
    min-width: calc(var(--spacing) * 8);
  }
  .min-w-9 {
    min-width: calc(var(--spacing) * 9);
  }
  .min-w-10 {
    min-width: calc(var(--spacing) * 10);
  }
  .min-w-\[--cell-size\] {
    min-width: --cell-size;
  }
  .min-w-\[8rem\] {
    min-width: 8rem;
  }
  .min-w-\[12rem\] {
    min-width: 12rem;
  }
  .min-w-\[var\(--radix-select-trigger-width\)\] {
    min-width: var(--radix-select-trigger-width);
  }
  .flex-1 {
    flex: 1;
  }
  .shrink-0 {
    flex-shrink: 0;
  }
  .grow {
    flex-grow: 1;
  }
  .grow-0 {
    flex-grow: 0;
  }
  .basis-full {
    flex-basis: 100%;
  }
  .caption-bottom {
    caption-side: bottom;
  }
  .border-collapse {
    border-collapse: collapse;
  }
  .origin-\[--radix-context-menu-content-transform-origin\] {
    transform-origin: --radix-context-menu-content-transform-origin;
  }
  .origin-\[--radix-dropdown-menu-content-transform-origin\] {
    transform-origin: --radix-dropdown-menu-content-transform-origin;
  }
  .origin-\[--radix-hover-card-content-transform-origin\] {
    transform-origin: --radix-hover-card-content-transform-origin;
  }
  .origin-\[--radix-menubar-content-transform-origin\] {
    transform-origin: --radix-menubar-content-transform-origin;
  }
  .origin-\[--radix-popover-content-transform-origin\] {
    transform-origin: --radix-popover-content-transform-origin;
  }
  .origin-\[--radix-select-content-transform-origin\] {
    transform-origin: --radix-select-content-transform-origin;
  }
  .origin-\[--radix-tooltip-content-transform-origin\] {
    transform-origin: --radix-tooltip-content-transform-origin;
  }
  .-translate-x-1\/2 {
    --tw-translate-x: calc(calc(1 / 2 * 100%) * -1);
    translate: var(--tw-translate-x) var(--tw-translate-y);
  }
  .-translate-x-px {
    --tw-translate-x: -1px;
    translate: var(--tw-translate-x) var(--tw-translate-y);
  }
  .translate-x-\[-50\%\] {
    --tw-translate-x: -50%;
    translate: var(--tw-translate-x) var(--tw-translate-y);
  }
  .translate-x-px {
    --tw-translate-x: 1px;
    translate: var(--tw-translate-x) var(--tw-translate-y);
  }
  .-translate-y-1\/2 {
    --tw-translate-y: calc(calc(1 / 2 * 100%) * -1);
    translate: var(--tw-translate-x) var(--tw-translate-y);
  }
  .translate-y-\[-50\%\] {
    --tw-translate-y: -50%;
    translate: var(--tw-translate-x) var(--tw-translate-y);
  }
  .translate-y-full {
    --tw-translate-y: 100%;
    translate: var(--tw-translate-x) var(--tw-translate-y);
  }
  .rotate-45 {
    rotate: 45deg;
  }
  .rotate-90 {
    rotate: 90deg;
  }
  .transform {
    transform: var(--tw-rotate-x,) var(--tw-rotate-y,) var(--tw-rotate-z,) var(--tw-skew-x,) var(--tw-skew-y,);
  }
  .animate-caret-blink {
    animation: caret-blink 1.25s ease-out infinite;
  }
  .animate-in {
    animation: enter var(--tw-animation-duration,var(--tw-duration,.15s))var(--tw-ease,ease)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
  }
  .animate-pulse {
    animation: var(--animate-pulse);
  }
  .animate-spin {
    animation: var(--animate-spin);
  }
  .cursor-default {
    cursor: default;
  }
  .cursor-pointer {
    cursor: pointer;
  }
  .cursor-text {
    cursor: text;
  }
  .touch-none {
    touch-action: none;
  }
  .resize-none {
    resize: none;
  }
  .list-disc {
    list-style-type: disc;
  }
  .list-none {
    list-style-type: none;
  }
  .grid-cols-1 {
    grid-template-columns: repeat(1, minmax(0, 1fr));
  }
  .grid-cols-2 {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
  .grid-cols-3 {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }
  .flex-col {
    flex-direction: column;
  }
  .flex-col-reverse {
    flex-direction: column-reverse;
  }
  .flex-row {
    flex-direction: row;
  }
  .flex-wrap {
    flex-wrap: wrap;
  }
  .place-content-center {
    place-content: center;
  }
  .items-center {
    align-items: center;
  }
  .items-end {
    align-items: flex-end;
  }
  .items-start {
    align-items: flex-start;
  }
  .items-stretch {
    align-items: stretch;
  }
  .justify-between {
    justify-content: space-between;
  }
  .justify-center {
    justify-content: center;
  }
  .justify-start {
    justify-content: flex-start;
  }
  .gap-1 {
    gap: calc(var(--spacing) * 1);
  }
  .gap-1\.5 {
    gap: calc(var(--spacing) * 1.5);
  }
  .gap-2 {
    gap: calc(var(--spacing) * 2);
  }
  .gap-2\.5 {
    gap: calc(var(--spacing) * 2.5);
  }
  .gap-3 {
    gap: calc(var(--spacing) * 3);
  }
  .gap-4 {
    gap: calc(var(--spacing) * 4);
  }
  .gap-6 {
    gap: calc(var(--spacing) * 6);
  }
  .gap-7 {
    gap: calc(var(--spacing) * 7);
  }
  .gap-8 {
    gap: calc(var(--spacing) * 8);
  }
  .gap-10 {
    gap: calc(var(--spacing) * 10);
  }
  .gap-12 {
    gap: calc(var(--spacing) * 12);
  }
  .gap-16 {
    gap: calc(var(--spacing) * 16);
  }
  .space-y-1\.5 {
    :where(& > :not(:last-child)) {
      --tw-space-y-reverse: 0;
      margin-block-start: calc(calc(var(--spacing) * 1.5) * var(--tw-space-y-reverse));
      margin-block-end: calc(calc(var(--spacing) * 1.5) * calc(1 - var(--tw-space-y-reverse)));
    }
  }
  .space-y-2 {
    :where(& > :not(:last-child)) {
      --tw-space-y-reverse: 0;
      margin-block-start: calc(calc(var(--spacing) * 2) * var(--tw-space-y-reverse));
      margin-block-end: calc(calc(var(--spacing) * 2) * calc(1 - var(--tw-space-y-reverse)));
    }
  }
  .space-y-3 {
    :where(& > :not(:last-child)) {
      --tw-space-y-reverse: 0;
      margin-block-start: calc(calc(var(--spacing) * 3) * var(--tw-space-y-reverse));
      margin-block-end: calc(calc(var(--spacing) * 3) * calc(1 - var(--tw-space-y-reverse)));
    }
  }
  .space-y-4 {
    :where(& > :not(:last-child)) {
      --tw-space-y-reverse: 0;
      margin-block-start: calc(calc(var(--spacing) * 4) * var(--tw-space-y-reverse));
      margin-block-end: calc(calc(var(--spacing) * 4) * calc(1 - var(--tw-space-y-reverse)));
    }
  }
  .space-y-6 {
    :where(& > :not(:last-child)) {
      --tw-space-y-reverse: 0;
      margin-block-start: calc(calc(var(--spacing) * 6) * var(--tw-space-y-reverse));
      margin-block-end: calc(calc(var(--spacing) * 6) * calc(1 - var(--tw-space-y-reverse)));
    }
  }
  .space-y-12 {
    :where(& > :not(:last-child)) {
      --tw-space-y-reverse: 0;
      margin-block-start: calc(calc(var(--spacing) * 12) * var(--tw-space-y-reverse));
      margin-block-end: calc(calc(var(--spacing) * 12) * calc(1 - var(--tw-space-y-reverse)));
    }
  }
  .space-x-1 {
    :where(& > :not(:last-child)) {
      --tw-space-x-reverse: 0;
      margin-inline-start: calc(calc(var(--spacing) * 1) * var(--tw-space-x-reverse));
      margin-inline-end: calc(calc(var(--spacing) * 1) * calc(1 - var(--tw-space-x-reverse)));
    }
  }
  .space-x-4 {
    :where(& > :not(:last-child)) {
      --tw-space-x-reverse: 0;
      margin-inline-start: calc(calc(var(--spacing) * 4) * var(--tw-space-x-reverse));
      margin-inline-end: calc(calc(var(--spacing) * 4) * calc(1 - var(--tw-space-x-reverse)));
    }
  }
  .self-stretch {
    align-self: stretch;
  }
  .overflow-auto {
    overflow: auto;
  }
  .overflow-hidden {
    overflow: hidden;
  }
  .overflow-x-hidden {
    overflow-x: hidden;
  }
  .overflow-y-auto {
    overflow-y: auto;
  }
  .rounded-2xl {
    border-radius: var(--radius-2xl);
  }
  .rounded-3xl {
    border-radius: var(--radius-3xl);
  }
  .rounded-\[2px\] {
    border-radius: 2px;
  }
  .rounded-\[22px\] {
    border-radius: 22px;
  }
  .rounded-\[calc\(var\(--radius\)-5px\)\] {
    border-radius: calc(var(--radius) - 5px);
  }
  .rounded-\[inherit\] {
    border-radius: inherit;
  }
  .rounded-full {
    border-radius: calc(infinity * 1px);
  }
  .rounded-lg {
    border-radius: var(--radius);
  }
  .rounded-md {
    border-radius: calc(var(--radius) - 2px);
  }
  .rounded-none {
    border-radius: 0;
  }
  .rounded-sm {
    border-radius: calc(var(--radius) - 4px);
  }
  .rounded-xl {
    border-radius: calc(var(--radius) + 4px);
  }
  .rounded-t-\[10px\] {
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
  }
  .rounded-l-md {
    border-top-left-radius: calc(var(--radius) - 2px);
    border-bottom-left-radius: calc(var(--radius) - 2px);
  }
  .rounded-tl-sm {
    border-top-left-radius: calc(var(--radius) - 4px);
  }
  .rounded-r-md {
    border-top-right-radius: calc(var(--radius) - 2px);
    border-bottom-right-radius: calc(var(--radius) - 2px);
  }
  .border {
    border-style: var(--tw-border-style);
    border-width: 1px;
  }
  .border-0 {
    border-style: var(--tw-border-style);
    border-width: 0px;
  }
  .border-2 {
    border-style: var(--tw-border-style);
    border-width: 2px;
  }
  .border-4 {
    border-style: var(--tw-border-style);
    border-width: 4px;
  }
  .border-\[1\.5px\] {
    border-style: var(--tw-border-style);
    border-width: 1.5px;
  }
  .border-y {
    border-block-style: var(--tw-border-style);
    border-block-width: 1px;
  }
  .border-t {
    border-top-style: var(--tw-border-style);
    border-top-width: 1px;
  }
  .border-r {
    border-right-style: var(--tw-border-style);
    border-right-width: 1px;
  }
  .border-b {
    border-bottom-style: var(--tw-border-style);
    border-bottom-width: 1px;
  }
  .border-l {
    border-left-style: var(--tw-border-style);
    border-left-width: 1px;
  }
  .border-dashed {
    --tw-border-style: dashed;
    border-style: dashed;
  }
  .\[border-color\:var\(--badge-outline\)\] {
    border-color: var(--badge-outline);
  }
  .\[border-color\:var\(--button-outline\)\] {
    border-color: var(--button-outline);
  }
  .border-\[--color-border\] {
    border-color: --color-border;
  }
  .border-background {
    border-color: hsl(var(--background));
  }
  .border-border {
    border-color: hsl(var(--border));
  }
  .border-border\/50 {
    border-color: hsl(var(--border));
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, hsl(var(--border)) 50%, transparent);
    }
  }
  .border-destructive {
    border-color: hsl(var(--destructive));
  }
  .border-destructive-border {
    border-color: var(--destructive-border);
  }
  .border-destructive\/50 {
    border-color: hsl(var(--destructive));
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, hsl(var(--destructive)) 50%, transparent);
    }
  }
  .border-input {
    border-color: hsl(var(--input));
  }
  .border-primary {
    border-color: hsl(var(--primary));
  }
  .border-primary-border {
    border-color: var(--primary-border);
  }
  .border-primary\/20 {
    border-color: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, hsl(var(--primary)) 20%, transparent);
    }
  }
  .border-primary\/30 {
    border-color: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, hsl(var(--primary)) 30%, transparent);
    }
  }
  .border-primary\/40 {
    border-color: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, hsl(var(--primary)) 40%, transparent);
    }
  }
  .border-primary\/50 {
    border-color: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, hsl(var(--primary)) 50%, transparent);
    }
  }
  .border-red-500\/20 {
    border-color: color-mix(in srgb, oklch(63.7% 0.237 25.331) 20%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, var(--color-red-500) 20%, transparent);
    }
  }
  .border-red-500\/30 {
    border-color: color-mix(in srgb, oklch(63.7% 0.237 25.331) 30%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, var(--color-red-500) 30%, transparent);
    }
  }
  .border-secondary-border {
    border-color: var(--secondary-border);
  }
  .border-transparent {
    border-color: transparent;
  }
  .border-yellow-500\/30 {
    border-color: color-mix(in srgb, oklch(79.5% 0.184 86.047) 30%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      border-color: color-mix(in oklab, var(--color-yellow-500) 30%, transparent);
    }
  }
  .border-t-transparent {
    border-top-color: transparent;
  }
  .border-l-transparent {
    border-left-color: transparent;
  }
  .bg-\[--color-bg\] {
    background-color: --color-bg;
  }
  .bg-accent {
    background-color: hsl(var(--accent));
  }
  .bg-background {
    background-color: hsl(var(--background));
  }
  .bg-background\/50 {
    background-color: hsl(var(--background));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--background)) 50%, transparent);
    }
  }
  .bg-background\/80 {
    background-color: hsl(var(--background));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--background)) 80%, transparent);
    }
  }
  .bg-black\/80 {
    background-color: color-mix(in srgb, #000 80%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, var(--color-black) 80%, transparent);
    }
  }
  .bg-blue-500\/20 {
    background-color: color-mix(in srgb, oklch(62.3% 0.214 259.815) 20%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, var(--color-blue-500) 20%, transparent);
    }
  }
  .bg-border {
    background-color: hsl(var(--border));
  }
  .bg-card {
    background-color: hsl(var(--card));
  }
  .bg-card\/30 {
    background-color: hsl(var(--card));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--card)) 30%, transparent);
    }
  }
  .bg-destructive {
    background-color: hsl(var(--destructive));
  }
  .bg-destructive\/10 {
    background-color: hsl(var(--destructive));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--destructive)) 10%, transparent);
    }
  }
  .bg-foreground {
    background-color: hsl(var(--foreground));
  }
  .bg-gray-50 {
    background-color: var(--color-gray-50);
  }
  .bg-input {
    background-color: hsl(var(--input));
  }
  .bg-muted {
    background-color: hsl(var(--muted));
  }
  .bg-muted\/50 {
    background-color: hsl(var(--muted));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--muted)) 50%, transparent);
    }
  }
  .bg-popover {
    background-color: hsl(var(--popover));
  }
  .bg-primary {
    background-color: hsl(var(--primary));
  }
  .bg-primary\/10 {
    background-color: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--primary)) 10%, transparent);
    }
  }
  .bg-primary\/20 {
    background-color: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--primary)) 20%, transparent);
    }
  }
  .bg-primary\/30 {
    background-color: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--primary)) 30%, transparent);
    }
  }
  .bg-red-500\/10 {
    background-color: color-mix(in srgb, oklch(63.7% 0.237 25.331) 10%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, var(--color-red-500) 10%, transparent);
    }
  }
  .bg-secondary {
    background-color: hsl(var(--secondary));
  }
  .bg-secondary\/30 {
    background-color: hsl(var(--secondary));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--secondary)) 30%, transparent);
    }
  }
  .bg-secondary\/50 {
    background-color: hsl(var(--secondary));
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, hsl(var(--secondary)) 50%, transparent);
    }
  }
  .bg-transparent {
    background-color: transparent;
  }
  .bg-white\/20 {
    background-color: color-mix(in srgb, #fff 20%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, var(--color-white) 20%, transparent);
    }
  }
  .bg-yellow-500\/10 {
    background-color: color-mix(in srgb, oklch(79.5% 0.184 86.047) 10%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      background-color: color-mix(in oklab, var(--color-yellow-500) 10%, transparent);
    }
  }
  .bg-gradient-to-b {
    --tw-gradient-position: to bottom in oklab;
    background-image: linear-gradient(var(--tw-gradient-stops));
  }
  .bg-gradient-to-br {
    --tw-gradient-position: to bottom right in oklab;
    background-image: linear-gradient(var(--tw-gradient-stops));
  }
  .bg-gradient-to-r {
    --tw-gradient-position: to right in oklab;
    background-image: linear-gradient(var(--tw-gradient-stops));
  }
  .from-blue-500 {
    --tw-gradient-from: var(--color-blue-500);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-emerald-500 {
    --tw-gradient-from: var(--color-emerald-500);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-orange-500 {
    --tw-gradient-from: var(--color-orange-500);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-primary {
    --tw-gradient-from: hsl(var(--primary));
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-primary\/5 {
    --tw-gradient-from: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-from: color-mix(in oklab, hsl(var(--primary)) 5%, transparent);
    }
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-primary\/50 {
    --tw-gradient-from: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-from: color-mix(in oklab, hsl(var(--primary)) 50%, transparent);
    }
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-purple-500 {
    --tw-gradient-from: var(--color-purple-500);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-red-400 {
    --tw-gradient-from: var(--color-red-400);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-red-500\/5 {
    --tw-gradient-from: color-mix(in srgb, oklch(63.7% 0.237 25.331) 5%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-from: color-mix(in oklab, var(--color-red-500) 5%, transparent);
    }
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-red-500\/10 {
    --tw-gradient-from: color-mix(in srgb, oklch(63.7% 0.237 25.331) 10%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-from: color-mix(in oklab, var(--color-red-500) 10%, transparent);
    }
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-secondary {
    --tw-gradient-from: hsl(var(--secondary));
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-transparent {
    --tw-gradient-from: transparent;
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-white {
    --tw-gradient-from: var(--color-white);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .from-yellow-500 {
    --tw-gradient-from: var(--color-yellow-500);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .via-background {
    --tw-gradient-via: hsl(var(--background));
    --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-via-stops);
  }
  .via-blue-400 {
    --tw-gradient-via: var(--color-blue-400);
    --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-via-stops);
  }
  .via-blue-500\/50 {
    --tw-gradient-via: color-mix(in srgb, oklch(62.3% 0.214 259.815) 50%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-via: color-mix(in oklab, var(--color-blue-500) 50%, transparent);
    }
    --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-via-stops);
  }
  .via-orange-400 {
    --tw-gradient-via: var(--color-orange-400);
    --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-via-stops);
  }
  .via-primary {
    --tw-gradient-via: hsl(var(--primary));
    --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-via-stops);
  }
  .via-primary\/30 {
    --tw-gradient-via: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-via: color-mix(in oklab, hsl(var(--primary)) 30%, transparent);
    }
    --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-via-stops);
  }
  .via-primary\/50 {
    --tw-gradient-via: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-via: color-mix(in oklab, hsl(var(--primary)) 50%, transparent);
    }
    --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-via-stops);
  }
  .via-red-500\/40 {
    --tw-gradient-via: color-mix(in srgb, oklch(63.7% 0.237 25.331) 40%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-via: color-mix(in oklab, var(--color-red-500) 40%, transparent);
    }
    --tw-gradient-via-stops: var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-via) var(--tw-gradient-via-position), var(--tw-gradient-to) var(--tw-gradient-to-position);
    --tw-gradient-stops: var(--tw-gradient-via-stops);
  }
  .to-amber-400 {
    --tw-gradient-to: var(--color-amber-400);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-background {
    --tw-gradient-to: hsl(var(--background));
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-blue-400 {
    --tw-gradient-to: var(--color-blue-400);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-cyan-400 {
    --tw-gradient-to: var(--color-cyan-400);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-pink-400 {
    --tw-gradient-to: var(--color-pink-400);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-primary {
    --tw-gradient-to: hsl(var(--primary));
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-primary\/10 {
    --tw-gradient-to: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-to: color-mix(in oklab, hsl(var(--primary)) 10%, transparent);
    }
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-purple-500 {
    --tw-gradient-to: var(--color-purple-500);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-purple-500\/50 {
    --tw-gradient-to: color-mix(in srgb, oklch(62.7% 0.265 303.9) 50%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-to: color-mix(in oklab, var(--color-purple-500) 50%, transparent);
    }
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-red-400 {
    --tw-gradient-to: var(--color-red-400);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-teal-400 {
    --tw-gradient-to: var(--color-teal-400);
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-transparent {
    --tw-gradient-to: transparent;
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .to-white\/50 {
    --tw-gradient-to: color-mix(in srgb, #fff 50%, transparent);
    @supports (color: color-mix(in lab, red, red)) {
      --tw-gradient-to: color-mix(in oklab, var(--color-white) 50%, transparent);
    }
    --tw-gradient-stops: var(--tw-gradient-via-stops, var(--tw-gradient-position), var(--tw-gradient-from) var(--tw-gradient-from-position), var(--tw-gradient-to) var(--tw-gradient-to-position));
  }
  .bg-clip-text {
    background-clip: text;
  }
  .fill-current {
    fill: currentcolor;
  }
  .fill-primary {
    fill: hsl(var(--primary));
  }
  .p-0 {
    padding: calc(var(--spacing) * 0);
  }
  .p-1 {
    padding: calc(var(--spacing) * 1);
  }
  .p-2 {
    padding: calc(var(--spacing) * 2);
  }
  .p-3 {
    padding: calc(var(--spacing) * 3);
  }
  .p-4 {
    padding: calc(var(--spacing) * 4);
  }
  .p-6 {
    padding: calc(var(--spacing) * 6);
  }
  .p-8 {
    padding: calc(var(--spacing) * 8);
  }
  .p-10 {
    padding: calc(var(--spacing) * 10);
  }
  .p-\[1px\] {
    padding: 1px;
  }
  .px-1 {
    padding-inline: calc(var(--spacing) * 1);
  }
  .px-1\.5 {
    padding-inline: calc(var(--spacing) * 1.5);
  }
  .px-2 {
    padding-inline: calc(var(--spacing) * 2);
  }
  .px-2\.5 {
    padding-inline: calc(var(--spacing) * 2.5);
  }
  .px-3 {
    padding-inline: calc(var(--spacing) * 3);
  }
  .px-4 {
    padding-inline: calc(var(--spacing) * 4);
  }
  .px-6 {
    padding-inline: calc(var(--spacing) * 6);
  }
  .px-8 {
    padding-inline: calc(var(--spacing) * 8);
  }
  .px-\[--cell-size\] {
    padding-inline: --cell-size;
  }
  .py-0\.5 {
    padding-block: calc(var(--spacing) * 0.5);
  }
  .py-1 {
    padding-block: calc(var(--spacing) * 1);
  }
  .py-1\.5 {
    padding-block: calc(var(--spacing) * 1.5);
  }
  .py-2 {
    padding-block: calc(var(--spacing) * 2);
  }
  .py-3 {
    padding-block: calc(var(--spacing) * 3);
  }
  .py-4 {
    padding-block: calc(var(--spacing) * 4);
  }
  .py-6 {
    padding-block: calc(var(--spacing) * 6);
  }
  .py-32 {
    padding-block: calc(var(--spacing) * 32);
  }
  .pt-0 {
    padding-top: calc(var(--spacing) * 0);
  }
  .pt-3 {
    padding-top: calc(var(--spacing) * 3);
  }
  .pt-4 {
    padding-top: calc(var(--spacing) * 4);
  }
  .pt-6 {
    padding-top: calc(var(--spacing) * 6);
  }
  .pt-8 {
    padding-top: calc(var(--spacing) * 8);
  }
  .pt-20 {
    padding-top: calc(var(--spacing) * 20);
  }
  .pr-1 {
    padding-right: calc(var(--spacing) * 1);
  }
  .pr-2 {
    padding-right: calc(var(--spacing) * 2);
  }
  .pr-2\.5 {
    padding-right: calc(var(--spacing) * 2.5);
  }
  .pr-3 {
    padding-right: calc(var(--spacing) * 3);
  }
  .pr-8 {
    padding-right: calc(var(--spacing) * 8);
  }
  .pb-2 {
    padding-bottom: calc(var(--spacing) * 2);
  }
  .pb-3 {
    padding-bottom: calc(var(--spacing) * 3);
  }
  .pb-4 {
    padding-bottom: calc(var(--spacing) * 4);
  }
  .pb-10 {
    padding-bottom: calc(var(--spacing) * 10);
  }
  .pl-2 {
    padding-left: calc(var(--spacing) * 2);
  }
  .pl-2\.5 {
    padding-left: calc(var(--spacing) * 2.5);
  }
  .pl-3 {
    padding-left: calc(var(--spacing) * 3);
  }
  .pl-4 {
    padding-left: calc(var(--spacing) * 4);
  }
  .pl-8 {
    padding-left: calc(var(--spacing) * 8);
  }
  .text-center {
    text-align: center;
  }
  .text-left {
    text-align: left;
  }
  .align-middle {
    vertical-align: middle;
  }
  .font-display {
    font-family: 'Space Grotesk', sans-serif;
  }
  .font-mono {
    font-family: var(--font-mono);
  }
  .font-sans {
    font-family: 'Plus Jakarta Sans', sans-serif;
  }
  .text-2xl {
    font-size: var(--text-2xl);
    line-height: var(--tw-leading, var(--text-2xl--line-height));
  }
  .text-3xl {
    font-size: var(--text-3xl);
    line-height: var(--tw-leading, var(--text-3xl--line-height));
  }
  .text-4xl {
    font-size: var(--text-4xl);
    line-height: var(--tw-leading, var(--text-4xl--line-height));
  }
  .text-6xl {
    font-size: var(--text-6xl);
    line-height: var(--tw-leading, var(--text-6xl--line-height));
  }
  .text-base {
    font-size: var(--text-base);
    line-height: var(--tw-leading, var(--text-base--line-height));
  }
  .text-lg {
    font-size: var(--text-lg);
    line-height: var(--tw-leading, var(--text-lg--line-height));
  }
  .text-sm {
    font-size: var(--text-sm);
    line-height: var(--tw-leading, var(--text-sm--line-height));
  }
  .text-sm\/relaxed {
    font-size: var(--text-sm);
    line-height: var(--leading-relaxed);
  }
  .text-xl {
    font-size: var(--text-xl);
    line-height: var(--tw-leading, var(--text-xl--line-height));
  }
  .text-xs {
    font-size: var(--text-xs);
    line-height: var(--tw-leading, var(--text-xs--line-height));
  }
  .text-\[0\.8rem\] {
    font-size: 0.8rem;
  }
  .leading-none {
    --tw-leading: 1;
    line-height: 1;
  }
  .leading-normal {
    --tw-leading: var(--leading-normal);
    line-height: var(--leading-normal);
  }
  .leading-relaxed {
    --tw-leading: var(--leading-relaxed);
    line-height: var(--leading-relaxed);
  }
  .leading-snug {
    --tw-leading: var(--leading-snug);
    line-height: var(--leading-snug);
  }
  .leading-tight {
    --tw-leading: var(--leading-tight);
    line-height: var(--leading-tight);
  }
  .font-bold {
    --tw-font-weight: var(--font-weight-bold);
    font-weight: var(--font-weight-bold);
  }
  .font-medium {
    --tw-font-weight: var(--font-weight-medium);
    font-weight: var(--font-weight-medium);
  }
  .font-normal {
    --tw-font-weight: var(--font-weight-normal);
    font-weight: var(--font-weight-normal);
  }
  .font-semibold {
    --tw-font-weight: var(--font-weight-semibold);
    font-weight: var(--font-weight-semibold);
  }
  .tracking-tight {
    --tw-tracking: var(--tracking-tight);
    letter-spacing: var(--tracking-tight);
  }
  .tracking-tighter {
    --tw-tracking: var(--tracking-tighter);
    letter-spacing: var(--tracking-tighter);
  }
  .tracking-wide {
    --tw-tracking: var(--tracking-wide);
    letter-spacing: var(--tracking-wide);
  }
  .tracking-wider {
    --tw-tracking: var(--tracking-wider);
    letter-spacing: var(--tracking-wider);
  }
  .tracking-widest {
    --tw-tracking: var(--tracking-widest);
    letter-spacing: var(--tracking-widest);
  }
  .text-balance {
    text-wrap: balance;
  }
  .break-words {
    overflow-wrap: break-word;
  }
  .whitespace-nowrap {
    white-space: nowrap;
  }
  .text-accent-foreground {
    color: hsl(var(--accent-foreground));
  }
  .text-card-foreground {
    color: hsl(var(--card-foreground));
  }
  .text-current {
    color: currentcolor;
  }
  .text-destructive {
    color: hsl(var(--destructive));
  }
  .text-destructive-foreground {
    color: hsl(var(--destructive-foreground));
  }
  .text-foreground {
    color: hsl(var(--foreground));
  }
  .text-foreground\/50 {
    color: hsl(var(--foreground));
    @supports (color: color-mix(in lab, red, red)) {
      color: color-mix(in oklab, hsl(var(--foreground)) 50%, transparent);
    }
  }
  .text-foreground\/80 {
    color: hsl(var(--foreground));
    @supports (color: color-mix(in lab, red, red)) {
      color: color-mix(in oklab, hsl(var(--foreground)) 80%, transparent);
    }
  }
  .text-foreground\/90 {
    color: hsl(var(--foreground));
    @supports (color: color-mix(in lab, red, red)) {
      color: color-mix(in oklab, hsl(var(--foreground)) 90%, transparent);
    }
  }
  .text-gray-600 {
    color: var(--color-gray-600);
  }
  .text-gray-900 {
    color: var(--color-gray-900);
  }
  .text-muted-foreground {
    color: hsl(var(--muted-foreground));
  }
  .text-popover-foreground {
    color: hsl(var(--popover-foreground));
  }
  .text-primary {
    color: hsl(var(--primary));
  }
  .text-primary-foreground {
    color: hsl(var(--primary-foreground));
  }
  .text-primary-foreground\/90 {
    color: hsl(var(--primary-foreground));
    @supports (color: color-mix(in lab, red, red)) {
      color: color-mix(in oklab, hsl(var(--primary-foreground)) 90%, transparent);
    }
  }
  .text-red-400 {
    color: var(--color-red-400);
  }
  .text-red-500 {
    color: var(--color-red-500);
  }
  .text-secondary-foreground {
    color: hsl(var(--secondary-foreground));
  }
  .text-transparent {
    color: transparent;
  }
  .text-yellow-400 {
    color: var(--color-yellow-400);
  }
  .uppercase {
    text-transform: uppercase;
  }
  .tabular-nums {
    --tw-numeric-spacing: tabular-nums;
    font-variant-numeric: var(--tw-ordinal,) var(--tw-slashed-zero,) var(--tw-numeric-figure,) var(--tw-numeric-spacing,) var(--tw-numeric-fraction,);
  }
  .underline-offset-4 {
    text-underline-offset: 4px;
  }
  .opacity-0 {
    opacity: 0%;
  }
  .opacity-20 {
    opacity: 20%;
  }
  .opacity-50 {
    opacity: 50%;
  }
  .opacity-60 {
    opacity: 60%;
  }
  .opacity-70 {
    opacity: 70%;
  }
  .opacity-90 {
    opacity: 90%;
  }
  .shadow {
    --tw-shadow: 0 1px 3px 0 var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 1px 2px -1px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-\[0_0_0_1px_hsl\(var\(--sidebar-border\)\)\] {
    --tw-shadow: 0 0 0 1px var(--tw-shadow-color, hsl(var(--sidebar-border)));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-\[0_0_10px_var\(--color-primary\)\] {
    --tw-shadow: 0 0 10px var(--tw-shadow-color, var(--color-primary));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-\[0_0_15px_rgba\(0\,255\,255\,0\.4\)\] {
    --tw-shadow: 0 0 15px var(--tw-shadow-color, rgba(0,255,255,0.4));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-\[0_0_15px_rgba\(0\,255\,255\,0\.15\)\] {
    --tw-shadow: 0 0 15px var(--tw-shadow-color, rgba(0,255,255,0.15));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-\[0_0_20px_rgba\(0\,255\,255\,0\.1\)\] {
    --tw-shadow: 0 0 20px var(--tw-shadow-color, rgba(0,255,255,0.1));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-\[0_0_30px_rgba\(0\,255\,255\,0\.3\)\] {
    --tw-shadow: 0 0 30px var(--tw-shadow-color, rgba(0,255,255,0.3));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-lg {
    --tw-shadow: 0 10px 15px -3px var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 4px 6px -4px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-md {
    --tw-shadow: 0 4px 6px -1px var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 2px 4px -2px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-none {
    --tw-shadow: 0 0 #0000;
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-sm {
    --tw-shadow: 0 1px 3px 0 var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 1px 2px -1px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-xl {
    --tw-shadow: 0 20px 25px -5px var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 8px 10px -6px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-xs {
    --tw-shadow: 0 1px 2px 0 var(--tw-shadow-color, rgb(0 0 0 / 0.05));
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .ring-0 {
    --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(0px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .ring-1 {
    --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
    box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
  }
  .shadow-primary\/5 {
    --tw-shadow-color: hsl(var(--primary));
    @supports (color: color-mix(in lab, red, red)) {
      --tw-shadow-color: color-mix(in oklab, color-mix(in oklab, hsl(var(--primary)) 5%, transparent) var(--tw-shadow-alpha), transparent);
    }
  }
  .ring-ring {
    --tw-ring-color: hsl(var(--ring));
  }
  .ring-offset-background {
    --tw-ring-offset-color: hsl(var(--background));
  }
  .outline-hidden {
    --tw-outline-style: none;
    outline-style: none;
    @media (forced-colors: active) {
      outline: 2px solid transparent;
      outline-offset: 2px;
    }
  }
  .outline {
    outline-style: var(--tw-outline-style);
    outline-width: 1px;
  }
  .outline-2 {
    outline-style: var(--tw-outline-style);
    outline-width: 2px;
  }
  .outline-offset-2 {
    outline-offset: 2px;
  }
  .outline-transparent {
    outline-color: transparent;
  }
  .blur-\[60px\] {
    --tw-blur: blur(60px);
    filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  }
  .blur-\[80px\] {
    --tw-blur: blur(80px);
    filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  }
  .blur-\[100px\] {
    --tw-blur: blur(100px);
    filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  }
  .blur-\[120px\] {
    --tw-blur: blur(120px);
    filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  }
  .drop-shadow-\[0_0_20px_rgba\(0\,255\,255\,0\.4\)\] {
    --tw-drop-shadow-size: drop-shadow(0 0 20px var(--tw-drop-shadow-color, rgba(0,255,255,0.4)));
    --tw-drop-shadow: var(--tw-drop-shadow-size);
    filter: var(--tw-blur,) var(--tw-brightness,) var(--tw-contrast,) var(--tw-grayscale,) var(--tw-hue-rotate,) var(--tw-invert,) var(--tw-saturate,) var(--tw-sepia,) var(--tw-drop-shadow,);
  }
  .backdrop-blur-md {
    --tw-backdrop-blur: blur(var(--blur-md));
    -webkit-backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,);
    backdrop-filter: var(--tw-backdrop-blur,) var(--tw-backdrop-brightness,) var(--tw-backdrop-contrast,) var(--tw-backdrop-grayscale,) var(--tw-backdrop-hue-rotate,) var(--tw-backdrop-invert,) var(--tw-backdrop-opacity,) var(--tw-backdrop-saturate,) var(--tw-backdrop-sepia,);
  }
  .transition {
    transition-property: color, background-color, border-color, outline-color, text-decoration-color, fill, stroke, --tw-gradient-from, --tw-gradient-via, --tw-gradient-to, opacity, box-shadow, transform, translate, scale, rotate, filter, -webkit-backdrop-filter, backdrop-filter, display, content-visibility, overlay, pointer-events;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-\[color\,box-shadow\] {
    transition-property: color,box-shadow;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-\[left\,right\,width\] {
    transition-property: left,right,width;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-\[margin\,opacity\] {
    transition-property: margin,opacity;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-\[width\,height\,padding\] {
    transition-property: width,height,padding;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-\[width\] {
    transition-property: width;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-all {
    transition-property: all;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-colors {
    transition-property: color, background-color, border-color, outline-color, text-decoration-color, fill, stroke, --tw-gradient-from, --tw-gradient-via, --tw-gradient-to;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-opacity {
    transition-property: opacity;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .transition-transform {
    transition-property: transform, translate, scale, rotate;
    transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
    transition-duration: var(--tw-duration, var(--default-transition-duration));
  }
  .duration-100 {
    --tw-duration: 100ms;
    transition-duration: 100ms;
  }
  .duration-200 {
    --tw-duration: 200ms;
    transition-duration: 200ms;
  }
  .duration-300 {
    --tw-duration: 300ms;
    transition-duration: 300ms;
  }
  .duration-500 {
    --tw-duration: 500ms;
    transition-duration: 500ms;
  }
  .duration-1000 {
    --tw-duration: 1000ms;
    transition-duration: 1000ms;
  }
  .ease-in-out {
    --tw-ease: var(--ease-in-out);
    transition-timing-function: var(--ease-in-out);
  }
  .ease-linear {
    --tw-ease: linear;
    transition-timing-function: linear;
  }
  .ease-out {
    --tw-ease: var(--ease-out);
    transition-timing-function: var(--ease-out);
  }
  .fade-in-0 {
    --tw-enter-opacity: calc(0/100);
    --tw-enter-opacity: 0;
  }
  .outline-none {
    --tw-outline-style: none;
    outline-style: none;
  }
  .select-none {
    -webkit-user-select: none;
    user-select: none;
  }
  .zoom-in-95 {
    --tw-enter-scale: calc(95*1%);
    --tw-enter-scale: .95;
  }
  .\[--cell-size\:2rem\] {
    --cell-size: 2rem;
  }
  .group-focus-within\/menu-item\:opacity-100 {
    &:is(:where(.group\/menu-item):focus-within *) {
      opacity: 100%;
    }
  }
  .group-hover\:translate-x-1 {
    &:is(:where(.group):hover *) {
      @media (hover: hover) {
        --tw-translate-x: calc(var(--spacing) * 1);
        translate: var(--tw-translate-x) var(--tw-translate-y);
      }
    }
  }
  .group-hover\:translate-y-0 {
    &:is(:where(.group):hover *) {
      @media (hover: hover) {
        --tw-translate-y: calc(var(--spacing) * 0);
        translate: var(--tw-translate-x) var(--tw-translate-y);
      }
    }
  }
  .group-hover\:scale-110 {
    &:is(:where(.group):hover *) {
      @media (hover: hover) {
        --tw-scale-x: 110%;
        --tw-scale-y: 110%;
        --tw-scale-z: 110%;
        scale: var(--tw-scale-x) var(--tw-scale-y);
      }
    }
  }
  .group-hover\:bg-primary\/10 {
    &:is(:where(.group):hover *) {
      @media (hover: hover) {
        background-color: hsl(var(--primary));
        @supports (color: color-mix(in lab, red, red)) {
          background-color: color-mix(in oklab, hsl(var(--primary)) 10%, transparent);
        }
      }
    }
  }
  .group-hover\:bg-primary\/20 {
    &:is(:where(.group):hover *) {
      @media (hover: hover) {
        background-color: hsl(var(--primary));
        @supports (color: color-mix(in lab, red, red)) {
          background-color: color-mix(in oklab, hsl(var(--primary)) 20%, transparent);
        }
      }
    }
  }
  .group-hover\:text-primary {
    &:is(:where(.group):hover *) {
      @media (hover: hover) {
        color: hsl(var(--primary));
      }
    }
  }
  .group-hover\:opacity-40 {
    &:is(:where(.group):hover *) {
      @media (hover: hover) {
        opacity: 40%;
      }
    }
  }
  .group-hover\:opacity-100 {
    &:is(:where(.group):hover *) {
      @media (hover: hover) {
        opacity: 100%;
      }
    }
  }
  .group-hover\/menu-item\:opacity-100 {
    &:is(:where(.group\/menu-item):hover *) {
      @media (hover: hover) {
        opacity: 100%;
      }
    }
  }
  .group-has-data-\[sidebar\=menu-action\]\/menu-item\:pr-8 {
    &:is(:where(.group\/menu-item):has(*[data-sidebar="menu-action"]) *) {
      padding-right: calc(var(--spacing) * 8);
    }
  }
  .group-has-\[\[data-orientation\=horizontal\]\]\/field\:text-balance {
    &:is(:where(.group\/field):has(*:is([data-orientation=horizontal])) *) {
      text-wrap: balance;
    }
  }
  .group-has-\[\[data-slot\=item-description\]\]\/item\:translate-y-0\.5 {
    &:is(:where(.group\/item):has(*:is([data-slot=item-description])) *) {
      --tw-translate-y: calc(var(--spacing) * 0.5);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .group-has-\[\[data-slot\=item-description\]\]\/item\:self-start {
    &:is(:where(.group\/item):has(*:is([data-slot=item-description])) *) {
      align-self: flex-start;
    }
  }
  .group-has-\[\>input\]\/input-group\:pt-2\.5 {
    &:is(:where(.group\/input-group):has(>input) *) {
      padding-top: calc(var(--spacing) * 2.5);
    }
  }
  .group-has-\[\>input\]\/input-group\:pb-2\.5 {
    &:is(:where(.group\/input-group):has(>input) *) {
      padding-bottom: calc(var(--spacing) * 2.5);
    }
  }
  .group-data-\[collapsible\=icon\]\:-mt-8 {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      margin-top: calc(var(--spacing) * -8);
    }
  }
  .group-data-\[collapsible\=icon\]\:hidden {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      display: none;
    }
  }
  .group-data-\[collapsible\=icon\]\:h-8\! {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      height: calc(var(--spacing) * 8) !important;
    }
  }
  .group-data-\[collapsible\=icon\]\:w-8\! {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      width: calc(var(--spacing) * 8) !important;
    }
  }
  .group-data-\[collapsible\=icon\]\:w-\[calc\(var\(--sidebar-width-icon\)\+var\(--spacing-4\)\)\] {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      width: calc(var(--sidebar-width-icon) + var(--spacing-4));
    }
  }
  .group-data-\[collapsible\=icon\]\:w-\[calc\(var\(--sidebar-width-icon\)\+var\(--spacing-4\)\+2px\)\] {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      width: calc(var(--sidebar-width-icon) + var(--spacing-4) + 2px);
    }
  }
  .group-data-\[collapsible\=icon\]\:w-\[var\(--sidebar-width-icon\)\] {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      width: var(--sidebar-width-icon);
    }
  }
  .group-data-\[collapsible\=icon\]\:overflow-hidden {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      overflow: hidden;
    }
  }
  .group-data-\[collapsible\=icon\]\:p-0\! {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      padding: calc(var(--spacing) * 0) !important;
    }
  }
  .group-data-\[collapsible\=icon\]\:p-2\! {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      padding: calc(var(--spacing) * 2) !important;
    }
  }
  .group-data-\[collapsible\=icon\]\:opacity-0 {
    &:is(:where(.group)[data-collapsible="icon"] *) {
      opacity: 0%;
    }
  }
  .group-data-\[collapsible\=offcanvas\]\:right-\[calc\(var\(--sidebar-width\)\*-1\)\] {
    &:is(:where(.group)[data-collapsible="offcanvas"] *) {
      right: calc(var(--sidebar-width) * -1);
    }
  }
  .group-data-\[collapsible\=offcanvas\]\:left-\[calc\(var\(--sidebar-width\)\*-1\)\] {
    &:is(:where(.group)[data-collapsible="offcanvas"] *) {
      left: calc(var(--sidebar-width) * -1);
    }
  }
  .group-data-\[collapsible\=offcanvas\]\:w-0 {
    &:is(:where(.group)[data-collapsible="offcanvas"] *) {
      width: calc(var(--spacing) * 0);
    }
  }
  .group-data-\[collapsible\=offcanvas\]\:translate-x-0 {
    &:is(:where(.group)[data-collapsible="offcanvas"] *) {
      --tw-translate-x: calc(var(--spacing) * 0);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .group-data-\[disabled\=true\]\/field\:opacity-50 {
    &:is(:where(.group\/field)[data-disabled="true"] *) {
      opacity: 50%;
    }
  }
  .group-data-\[disabled\=true\]\/input-group\:opacity-50 {
    &:is(:where(.group\/input-group)[data-disabled="true"] *) {
      opacity: 50%;
    }
  }
  .group-data-\[focused\=true\]\/day\:relative {
    &:is(:where(.group\/day)[data-focused="true"] *) {
      position: relative;
    }
  }
  .group-data-\[focused\=true\]\/day\:z-10 {
    &:is(:where(.group\/day)[data-focused="true"] *) {
      z-index: 10;
    }
  }
  .group-data-\[focused\=true\]\/day\:border-ring {
    &:is(:where(.group\/day)[data-focused="true"] *) {
      border-color: hsl(var(--ring));
    }
  }
  .group-data-\[focused\=true\]\/day\:ring-\[3px\] {
    &:is(:where(.group\/day)[data-focused="true"] *) {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(3px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .group-data-\[focused\=true\]\/day\:ring-ring\/50 {
    &:is(:where(.group\/day)[data-focused="true"] *) {
      --tw-ring-color: hsl(var(--ring));
      @supports (color: color-mix(in lab, red, red)) {
        --tw-ring-color: color-mix(in oklab, hsl(var(--ring)) 50%, transparent);
      }
    }
  }
  .group-data-\[side\=left\]\:-right-4 {
    &:is(:where(.group)[data-side="left"] *) {
      right: calc(var(--spacing) * -4);
    }
  }
  .group-data-\[side\=left\]\:border-r {
    &:is(:where(.group)[data-side="left"] *) {
      border-right-style: var(--tw-border-style);
      border-right-width: 1px;
    }
  }
  .group-data-\[side\=right\]\:left-0 {
    &:is(:where(.group)[data-side="right"] *) {
      left: calc(var(--spacing) * 0);
    }
  }
  .group-data-\[side\=right\]\:rotate-180 {
    &:is(:where(.group)[data-side="right"] *) {
      rotate: 180deg;
    }
  }
  .group-data-\[side\=right\]\:border-l {
    &:is(:where(.group)[data-side="right"] *) {
      border-left-style: var(--tw-border-style);
      border-left-width: 1px;
    }
  }
  .group-data-\[state\=open\]\:rotate-180 {
    &:is(:where(.group)[data-state="open"] *) {
      rotate: 180deg;
    }
  }
  .group-data-\[variant\=floating\]\:rounded-lg {
    &:is(:where(.group)[data-variant="floating"] *) {
      border-radius: var(--radius);
    }
  }
  .group-data-\[variant\=floating\]\:border {
    &:is(:where(.group)[data-variant="floating"] *) {
      border-style: var(--tw-border-style);
      border-width: 1px;
    }
  }
  .group-data-\[variant\=floating\]\:shadow-sm {
    &:is(:where(.group)[data-variant="floating"] *) {
      --tw-shadow: 0 1px 3px 0 var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 1px 2px -1px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .group-data-\[variant\=outline\]\/field-group\:-mb-2 {
    &:is(:where(.group\/field-group)[data-variant="outline"] *) {
      margin-bottom: calc(var(--spacing) * -2);
    }
  }
  .group-\[\.destructive\]\:border-muted\/40 {
    &:is(:where(.group):is(.destructive) *) {
      border-color: hsl(var(--muted));
      @supports (color: color-mix(in lab, red, red)) {
        border-color: color-mix(in oklab, hsl(var(--muted)) 40%, transparent);
      }
    }
  }
  .group-\[\.destructive\]\:text-red-300 {
    &:is(:where(.group):is(.destructive) *) {
      color: var(--color-red-300);
    }
  }
  .group-\[\.toast\]\:bg-muted {
    &:is(:where(.group):is(.toast) *) {
      background-color: hsl(var(--muted));
    }
  }
  .group-\[\.toast\]\:bg-primary {
    &:is(:where(.group):is(.toast) *) {
      background-color: hsl(var(--primary));
    }
  }
  .group-\[\.toast\]\:text-muted-foreground {
    &:is(:where(.group):is(.toast) *) {
      color: hsl(var(--muted-foreground));
    }
  }
  .group-\[\.toast\]\:text-primary-foreground {
    &:is(:where(.group):is(.toast) *) {
      color: hsl(var(--primary-foreground));
    }
  }
  .group-\[\.toaster\]\:border-border {
    &:is(:where(.group):is(.toaster) *) {
      border-color: hsl(var(--border));
    }
  }
  .group-\[\.toaster\]\:bg-background {
    &:is(:where(.group):is(.toaster) *) {
      background-color: hsl(var(--background));
    }
  }
  .group-\[\.toaster\]\:text-foreground {
    &:is(:where(.group):is(.toaster) *) {
      color: hsl(var(--foreground));
    }
  }
  .group-\[\.toaster\]\:shadow-lg {
    &:is(:where(.group):is(.toaster) *) {
      --tw-shadow: 0 10px 15px -3px var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 4px 6px -4px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .peer-disabled\:cursor-not-allowed {
    &:is(:where(.peer):disabled ~ *) {
      cursor: not-allowed;
    }
  }
  .peer-disabled\:opacity-70 {
    &:is(:where(.peer):disabled ~ *) {
      opacity: 70%;
    }
  }
  .peer-data-\[size\=default\]\/menu-button\:top-1\.5 {
    &:is(:where(.peer\/menu-button)[data-size="default"] ~ *) {
      top: calc(var(--spacing) * 1.5);
    }
  }
  .peer-data-\[size\=lg\]\/menu-button\:top-2\.5 {
    &:is(:where(.peer\/menu-button)[data-size="lg"] ~ *) {
      top: calc(var(--spacing) * 2.5);
    }
  }
  .peer-data-\[size\=sm\]\/menu-button\:top-1 {
    &:is(:where(.peer\/menu-button)[data-size="sm"] ~ *) {
      top: calc(var(--spacing) * 1);
    }
  }
  .selection\:bg-primary\/30 {
    & *::selection {
      background-color: hsl(var(--primary));
      @supports (color: color-mix(in lab, red, red)) {
        background-color: color-mix(in oklab, hsl(var(--primary)) 30%, transparent);
      }
    }
    &::selection {
      background-color: hsl(var(--primary));
      @supports (color: color-mix(in lab, red, red)) {
        background-color: color-mix(in oklab, hsl(var(--primary)) 30%, transparent);
      }
    }
  }
  .file\:border-0 {
    &::file-selector-button {
      border-style: var(--tw-border-style);
      border-width: 0px;
    }
  }
  .file\:bg-transparent {
    &::file-selector-button {
      background-color: transparent;
    }
  }
  .file\:text-sm {
    &::file-selector-button {
      font-size: var(--text-sm);
      line-height: var(--tw-leading, var(--text-sm--line-height));
    }
  }
  .file\:font-medium {
    &::file-selector-button {
      --tw-font-weight: var(--font-weight-medium);
      font-weight: var(--font-weight-medium);
    }
  }
  .file\:text-foreground {
    &::file-selector-button {
      color: hsl(var(--foreground));
    }
  }
  .placeholder\:text-muted-foreground {
    &::placeholder {
      color: hsl(var(--muted-foreground));
    }
  }
  .after\:absolute {
    &::after {
      content: var(--tw-content);
      position: absolute;
    }
  }
  .after\:-inset-2 {
    &::after {
      content: var(--tw-content);
      inset: calc(var(--spacing) * -2);
    }
  }
  .after\:inset-y-0 {
    &::after {
      content: var(--tw-content);
      inset-block: calc(var(--spacing) * 0);
    }
  }
  .after\:left-1\/2 {
    &::after {
      content: var(--tw-content);
      left: calc(1 / 2 * 100%);
    }
  }
  .after\:w-1 {
    &::after {
      content: var(--tw-content);
      width: calc(var(--spacing) * 1);
    }
  }
  .after\:w-\[2px\] {
    &::after {
      content: var(--tw-content);
      width: 2px;
    }
  }
  .after\:-translate-x-1\/2 {
    &::after {
      content: var(--tw-content);
      --tw-translate-x: calc(calc(1 / 2 * 100%) * -1);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .group-data-\[collapsible\=offcanvas\]\:after\:left-full {
    &:is(:where(.group)[data-collapsible="offcanvas"] *) {
      &::after {
        content: var(--tw-content);
        left: 100%;
      }
    }
  }
  .first\:rounded-l-md {
    &:first-child {
      border-top-left-radius: calc(var(--radius) - 2px);
      border-bottom-left-radius: calc(var(--radius) - 2px);
    }
  }
  .first\:border-l {
    &:first-child {
      border-left-style: var(--tw-border-style);
      border-left-width: 1px;
    }
  }
  .last\:mt-0 {
    &:last-child {
      margin-top: calc(var(--spacing) * 0);
    }
  }
  .last\:rounded-r-md {
    &:last-child {
      border-top-right-radius: calc(var(--radius) - 2px);
      border-bottom-right-radius: calc(var(--radius) - 2px);
    }
  }
  .hover\:-translate-y-1 {
    &:hover {
      @media (hover: hover) {
        --tw-translate-y: calc(var(--spacing) * -1);
        translate: var(--tw-translate-x) var(--tw-translate-y);
      }
    }
  }
  .hover\:-translate-y-2 {
    &:hover {
      @media (hover: hover) {
        --tw-translate-y: calc(var(--spacing) * -2);
        translate: var(--tw-translate-x) var(--tw-translate-y);
      }
    }
  }
  .hover\:border-primary {
    &:hover {
      @media (hover: hover) {
        border-color: hsl(var(--primary));
      }
    }
  }
  .hover\:border-primary\/50 {
    &:hover {
      @media (hover: hover) {
        border-color: hsl(var(--primary));
        @supports (color: color-mix(in lab, red, red)) {
          border-color: color-mix(in oklab, hsl(var(--primary)) 50%, transparent);
        }
      }
    }
  }
  .hover\:border-red-500\/40 {
    &:hover {
      @media (hover: hover) {
        border-color: color-mix(in srgb, oklch(63.7% 0.237 25.331) 40%, transparent);
        @supports (color: color-mix(in lab, red, red)) {
          border-color: color-mix(in oklab, var(--color-red-500) 40%, transparent);
        }
      }
    }
  }
  .hover\:border-transparent {
    &:hover {
      @media (hover: hover) {
        border-color: transparent;
      }
    }
  }
  .hover\:bg-accent {
    &:hover {
      @media (hover: hover) {
        background-color: hsl(var(--accent));
      }
    }
  }
  .hover\:bg-card\/80 {
    &:hover {
      @media (hover: hover) {
        background-color: hsl(var(--card));
        @supports (color: color-mix(in lab, red, red)) {
          background-color: color-mix(in oklab, hsl(var(--card)) 80%, transparent);
        }
      }
    }
  }
  .hover\:bg-muted {
    &:hover {
      @media (hover: hover) {
        background-color: hsl(var(--muted));
      }
    }
  }
  .hover\:bg-muted\/50 {
    &:hover {
      @media (hover: hover) {
        background-color: hsl(var(--muted));
        @supports (color: color-mix(in lab, red, red)) {
          background-color: color-mix(in oklab, hsl(var(--muted)) 50%, transparent);
        }
      }
    }
  }
  .hover\:bg-primary\/10 {
    &:hover {
      @media (hover: hover) {
        background-color: hsl(var(--primary));
        @supports (color: color-mix(in lab, red, red)) {
          background-color: color-mix(in oklab, hsl(var(--primary)) 10%, transparent);
        }
      }
    }
  }
  .hover\:bg-secondary {
    &:hover {
      @media (hover: hover) {
        background-color: hsl(var(--secondary));
      }
    }
  }
  .hover\:text-accent-foreground {
    &:hover {
      @media (hover: hover) {
        color: hsl(var(--accent-foreground));
      }
    }
  }
  .hover\:text-foreground {
    &:hover {
      @media (hover: hover) {
        color: hsl(var(--foreground));
      }
    }
  }
  .hover\:text-muted-foreground {
    &:hover {
      @media (hover: hover) {
        color: hsl(var(--muted-foreground));
      }
    }
  }
  .hover\:text-primary {
    &:hover {
      @media (hover: hover) {
        color: hsl(var(--primary));
      }
    }
  }
  .hover\:underline {
    &:hover {
      @media (hover: hover) {
        text-decoration-line: underline;
      }
    }
  }
  .hover\:opacity-100 {
    &:hover {
      @media (hover: hover) {
        opacity: 100%;
      }
    }
  }
  .hover\:shadow-\[0_0_0_1px_hsl\(var\(--sidebar-accent\)\)\] {
    &:hover {
      @media (hover: hover) {
        --tw-shadow: 0 0 0 1px var(--tw-shadow-color, hsl(var(--sidebar-accent)));
        box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
      }
    }
  }
  .hover\:shadow-\[0_0_20px_rgba\(0\,255\,255\,0\.15\)\] {
    &:hover {
      @media (hover: hover) {
        --tw-shadow: 0 0 20px var(--tw-shadow-color, rgba(0,255,255,0.15));
        box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
      }
    }
  }
  .hover\:shadow-\[0_0_25px_rgba\(0\,255\,255\,0\.3\)\] {
    &:hover {
      @media (hover: hover) {
        --tw-shadow: 0 0 25px var(--tw-shadow-color, rgba(0,255,255,0.3));
        box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
      }
    }
  }
  .hover\:shadow-\[0_0_50px_rgba\(0\,255\,255\,0\.5\)\] {
    &:hover {
      @media (hover: hover) {
        --tw-shadow: 0 0 50px var(--tw-shadow-color, rgba(0,255,255,0.5));
        box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
      }
    }
  }
  .hover\:shadow-\[0_10px_30px_-10px_rgba\(0\,255\,255\,0\.1\)\] {
    &:hover {
      @media (hover: hover) {
        --tw-shadow: 0 10px 30px -10px var(--tw-shadow-color, rgba(0,255,255,0.1));
        box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
      }
    }
  }
  .hover\:shadow-\[0_10px_30px_-10px_rgba\(239\,68\,68\,0\.2\)\] {
    &:hover {
      @media (hover: hover) {
        --tw-shadow: 0 10px 30px -10px var(--tw-shadow-color, rgba(239,68,68,0.2));
        box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
      }
    }
  }
  .hover\:shadow-\[0_15px_40px_-10px_rgba\(0\,255\,255\,0\.2\)\] {
    &:hover {
      @media (hover: hover) {
        --tw-shadow: 0 15px 40px -10px var(--tw-shadow-color, rgba(0,255,255,0.2));
        box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
      }
    }
  }
  .group-\[\.destructive\]\:hover\:border-destructive\/30 {
    &:is(:where(.group):is(.destructive) *) {
      &:hover {
        @media (hover: hover) {
          border-color: hsl(var(--destructive));
          @supports (color: color-mix(in lab, red, red)) {
            border-color: color-mix(in oklab, hsl(var(--destructive)) 30%, transparent);
          }
        }
      }
    }
  }
  .group-\[\.destructive\]\:hover\:bg-destructive {
    &:is(:where(.group):is(.destructive) *) {
      &:hover {
        @media (hover: hover) {
          background-color: hsl(var(--destructive));
        }
      }
    }
  }
  .group-\[\.destructive\]\:hover\:text-destructive-foreground {
    &:is(:where(.group):is(.destructive) *) {
      &:hover {
        @media (hover: hover) {
          color: hsl(var(--destructive-foreground));
        }
      }
    }
  }
  .group-\[\.destructive\]\:hover\:text-red-50 {
    &:is(:where(.group):is(.destructive) *) {
      &:hover {
        @media (hover: hover) {
          color: var(--color-red-50);
        }
      }
    }
  }
  .focus\:bg-accent {
    &:focus {
      background-color: hsl(var(--accent));
    }
  }
  .focus\:text-accent-foreground {
    &:focus {
      color: hsl(var(--accent-foreground));
    }
  }
  .focus\:opacity-100 {
    &:focus {
      opacity: 100%;
    }
  }
  .focus\:ring-1 {
    &:focus {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .focus\:ring-2 {
    &:focus {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(2px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .focus\:ring-ring {
    &:focus {
      --tw-ring-color: hsl(var(--ring));
    }
  }
  .focus\:ring-offset-2 {
    &:focus {
      --tw-ring-offset-width: 2px;
      --tw-ring-offset-shadow: var(--tw-ring-inset,) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);
    }
  }
  .focus\:outline-none {
    &:focus {
      --tw-outline-style: none;
      outline-style: none;
    }
  }
  .group-\[\.destructive\]\:focus\:ring-destructive {
    &:is(:where(.group):is(.destructive) *) {
      &:focus {
        --tw-ring-color: hsl(var(--destructive));
      }
    }
  }
  .group-\[\.destructive\]\:focus\:ring-red-400 {
    &:is(:where(.group):is(.destructive) *) {
      &:focus {
        --tw-ring-color: var(--color-red-400);
      }
    }
  }
  .group-\[\.destructive\]\:focus\:ring-offset-red-600 {
    &:is(:where(.group):is(.destructive) *) {
      &:focus {
        --tw-ring-offset-color: var(--color-red-600);
      }
    }
  }
  .focus-visible\:border-ring {
    &:focus-visible {
      border-color: hsl(var(--ring));
    }
  }
  .focus-visible\:ring-0 {
    &:focus-visible {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(0px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .focus-visible\:ring-1 {
    &:focus-visible {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .focus-visible\:ring-2 {
    &:focus-visible {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(2px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .focus-visible\:ring-\[3px\] {
    &:focus-visible {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(3px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .focus-visible\:ring-ring {
    &:focus-visible {
      --tw-ring-color: hsl(var(--ring));
    }
  }
  .focus-visible\:ring-ring\/50 {
    &:focus-visible {
      --tw-ring-color: hsl(var(--ring));
      @supports (color: color-mix(in lab, red, red)) {
        --tw-ring-color: color-mix(in oklab, hsl(var(--ring)) 50%, transparent);
      }
    }
  }
  .focus-visible\:ring-offset-1 {
    &:focus-visible {
      --tw-ring-offset-width: 1px;
      --tw-ring-offset-shadow: var(--tw-ring-inset,) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);
    }
  }
  .focus-visible\:ring-offset-2 {
    &:focus-visible {
      --tw-ring-offset-width: 2px;
      --tw-ring-offset-shadow: var(--tw-ring-inset,) 0 0 0 var(--tw-ring-offset-width) var(--tw-ring-offset-color);
    }
  }
  .focus-visible\:ring-offset-background {
    &:focus-visible {
      --tw-ring-offset-color: hsl(var(--background));
    }
  }
  .focus-visible\:outline-none {
    &:focus-visible {
      --tw-outline-style: none;
      outline-style: none;
    }
  }
  .active\:shadow-none {
    &:active {
      --tw-shadow: 0 0 #0000;
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .disabled\:pointer-events-none {
    &:disabled {
      pointer-events: none;
    }
  }
  .disabled\:cursor-not-allowed {
    &:disabled {
      cursor: not-allowed;
    }
  }
  .disabled\:opacity-50 {
    &:disabled {
      opacity: 50%;
    }
  }
  .in-data-\[side\=left\]\:cursor-w-resize {
    :where(*[data-side="left"]) & {
      cursor: w-resize;
    }
  }
  .in-data-\[side\=right\]\:cursor-e-resize {
    :where(*[data-side="right"]) & {
      cursor: e-resize;
    }
  }
  .has-focus\:border-ring {
    &:has(*:focus) {
      border-color: hsl(var(--ring));
    }
  }
  .has-focus\:ring-\[3px\] {
    &:has(*:focus) {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(3px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .has-focus\:ring-ring\/50 {
    &:has(*:focus) {
      --tw-ring-color: hsl(var(--ring));
      @supports (color: color-mix(in lab, red, red)) {
        --tw-ring-color: color-mix(in oklab, hsl(var(--ring)) 50%, transparent);
      }
    }
  }
  .has-data-\[state\=checked\]\:border-primary {
    &:has(*[data-state="checked"]) {
      border-color: hsl(var(--primary));
    }
  }
  .has-data-\[state\=checked\]\:bg-primary\/5 {
    &:has(*[data-state="checked"]) {
      background-color: hsl(var(--primary));
      @supports (color: color-mix(in lab, red, red)) {
        background-color: color-mix(in oklab, hsl(var(--primary)) 5%, transparent);
      }
    }
  }
  .has-\[\:disabled\]\:opacity-50 {
    &:has(*:is(:disabled)) {
      opacity: 50%;
    }
  }
  .has-\[\[data-slot\=input-group-control\]\:focus-visible\]\:ring-1 {
    &:has(*:is([data-slot=input-group-control]:focus-visible)) {
      --tw-ring-shadow: var(--tw-ring-inset,) 0 0 0 calc(1px + var(--tw-ring-offset-width)) var(--tw-ring-color, currentcolor);
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .has-\[\[data-slot\=input-group-control\]\:focus-visible\]\:ring-ring {
    &:has(*:is([data-slot=input-group-control]:focus-visible)) {
      --tw-ring-color: hsl(var(--ring));
    }
  }
  .has-\[\[data-slot\]\[aria-invalid\=true\]\]\:border-destructive {
    &:has(*:is([data-slot][aria-invalid=true])) {
      border-color: hsl(var(--destructive));
    }
  }
  .has-\[\[data-slot\]\[aria-invalid\=true\]\]\:ring-destructive\/20 {
    &:has(*:is([data-slot][aria-invalid=true])) {
      --tw-ring-color: hsl(var(--destructive));
      @supports (color: color-mix(in lab, red, red)) {
        --tw-ring-color: color-mix(in oklab, hsl(var(--destructive)) 20%, transparent);
      }
    }
  }
  .has-\[\>\[data-align\=block-end\]\]\:h-auto {
    &:has(>[data-align=block-end]) {
      height: auto;
    }
  }
  .has-\[\>\[data-align\=block-end\]\]\:flex-col {
    &:has(>[data-align=block-end]) {
      flex-direction: column;
    }
  }
  .has-\[\>\[data-align\=block-start\]\]\:h-auto {
    &:has(>[data-align=block-start]) {
      height: auto;
    }
  }
  .has-\[\>\[data-align\=block-start\]\]\:flex-col {
    &:has(>[data-align=block-start]) {
      flex-direction: column;
    }
  }
  .has-\[\>\[data-slot\=button-group\]\]\:gap-2 {
    &:has(>[data-slot=button-group]) {
      gap: calc(var(--spacing) * 2);
    }
  }
  .has-\[\>\[data-slot\=checkbox-group\]\]\:gap-3 {
    &:has(>[data-slot=checkbox-group]) {
      gap: calc(var(--spacing) * 3);
    }
  }
  .has-\[\>\[data-slot\=field-content\]\]\:items-start {
    &:has(>[data-slot=field-content]) {
      align-items: flex-start;
    }
  }
  .has-\[\>\[data-slot\=field\]\]\:w-full {
    &:has(>[data-slot=field]) {
      width: 100%;
    }
  }
  .has-\[\>\[data-slot\=field\]\]\:flex-col {
    &:has(>[data-slot=field]) {
      flex-direction: column;
    }
  }
  .has-\[\>\[data-slot\=field\]\]\:rounded-md {
    &:has(>[data-slot=field]) {
      border-radius: calc(var(--radius) - 2px);
    }
  }
  .has-\[\>\[data-slot\=field\]\]\:border {
    &:has(>[data-slot=field]) {
      border-style: var(--tw-border-style);
      border-width: 1px;
    }
  }
  .has-\[\>\[data-slot\=radio-group\]\]\:gap-3 {
    &:has(>[data-slot=radio-group]) {
      gap: calc(var(--spacing) * 3);
    }
  }
  .has-\[\>button\]\:mr-\[-0\.4rem\] {
    &:has(>button) {
      margin-right: -0.4rem;
    }
  }
  .has-\[\>button\]\:ml-\[-0\.45rem\] {
    &:has(>button) {
      margin-left: -0.45rem;
    }
  }
  .has-\[\>kbd\]\:mr-\[-0\.35rem\] {
    &:has(>kbd) {
      margin-right: -0.35rem;
    }
  }
  .has-\[\>kbd\]\:ml-\[-0\.35rem\] {
    &:has(>kbd) {
      margin-left: -0.35rem;
    }
  }
  .has-\[\>svg\]\:p-0 {
    &:has(>svg) {
      padding: calc(var(--spacing) * 0);
    }
  }
  .has-\[\>svg\]\:px-2 {
    &:has(>svg) {
      padding-inline: calc(var(--spacing) * 2);
    }
  }
  .has-\[\>svg\]\:px-2\.5 {
    &:has(>svg) {
      padding-inline: calc(var(--spacing) * 2.5);
    }
  }
  .has-\[\>textarea\]\:h-auto {
    &:has(>textarea) {
      height: auto;
    }
  }
  .aria-disabled\:pointer-events-none {
    &[aria-disabled="true"] {
      pointer-events: none;
    }
  }
  .aria-disabled\:opacity-50 {
    &[aria-disabled="true"] {
      opacity: 50%;
    }
  }
  .aria-selected\:text-muted-foreground {
    &[aria-selected="true"] {
      color: hsl(var(--muted-foreground));
    }
  }
  .data-\[active\=true\]\:font-medium {
    &[data-active="true"] {
      --tw-font-weight: var(--font-weight-medium);
      font-weight: var(--font-weight-medium);
    }
  }
  .data-\[disabled\]\:pointer-events-none {
    &[data-disabled] {
      pointer-events: none;
    }
  }
  .data-\[disabled\]\:opacity-50 {
    &[data-disabled] {
      opacity: 50%;
    }
  }
  .data-\[disabled\=true\]\:pointer-events-none {
    &[data-disabled="true"] {
      pointer-events: none;
    }
  }
  .data-\[disabled\=true\]\:opacity-50 {
    &[data-disabled="true"] {
      opacity: 50%;
    }
  }
  .data-\[invalid\=true\]\:text-destructive {
    &[data-invalid="true"] {
      color: hsl(var(--destructive));
    }
  }
  .data-\[motion\=from-end\]\:slide-in-from-right-52 {
    &[data-motion="from-end"] {
      --tw-enter-translate-x: calc(52*var(--spacing));
    }
  }
  .data-\[motion\=from-start\]\:slide-in-from-left-52 {
    &[data-motion="from-start"] {
      --tw-enter-translate-x: calc(52*var(--spacing)*-1);
    }
  }
  .data-\[motion\=to-end\]\:slide-out-to-right-52 {
    &[data-motion="to-end"] {
      --tw-exit-translate-x: calc(52*var(--spacing));
    }
  }
  .data-\[motion\=to-start\]\:slide-out-to-left-52 {
    &[data-motion="to-start"] {
      --tw-exit-translate-x: calc(52*var(--spacing)*-1);
    }
  }
  .data-\[motion\^\=from-\]\:animate-in {
    &[data-motion^="from-"] {
      animation: enter var(--tw-animation-duration,var(--tw-duration,.15s))var(--tw-ease,ease)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[motion\^\=from-\]\:fade-in {
    &[data-motion^="from-"] {
      --tw-enter-opacity: 0;
    }
  }
  .data-\[motion\^\=to-\]\:animate-out {
    &[data-motion^="to-"] {
      animation: exit var(--tw-animation-duration,var(--tw-duration,.15s))var(--tw-ease,ease)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[motion\^\=to-\]\:fade-out {
    &[data-motion^="to-"] {
      --tw-exit-opacity: 0;
    }
  }
  .data-\[orientation\=vertical\]\:h-auto {
    &[data-orientation="vertical"] {
      height: auto;
    }
  }
  .data-\[panel-group-direction\=vertical\]\:h-px {
    &[data-panel-group-direction="vertical"] {
      height: 1px;
    }
  }
  .data-\[panel-group-direction\=vertical\]\:w-full {
    &[data-panel-group-direction="vertical"] {
      width: 100%;
    }
  }
  .data-\[panel-group-direction\=vertical\]\:flex-col {
    &[data-panel-group-direction="vertical"] {
      flex-direction: column;
    }
  }
  .data-\[panel-group-direction\=vertical\]\:after\:left-0 {
    &[data-panel-group-direction="vertical"] {
      &::after {
        content: var(--tw-content);
        left: calc(var(--spacing) * 0);
      }
    }
  }
  .data-\[panel-group-direction\=vertical\]\:after\:h-1 {
    &[data-panel-group-direction="vertical"] {
      &::after {
        content: var(--tw-content);
        height: calc(var(--spacing) * 1);
      }
    }
  }
  .data-\[panel-group-direction\=vertical\]\:after\:w-full {
    &[data-panel-group-direction="vertical"] {
      &::after {
        content: var(--tw-content);
        width: 100%;
      }
    }
  }
  .data-\[panel-group-direction\=vertical\]\:after\:translate-x-0 {
    &[data-panel-group-direction="vertical"] {
      &::after {
        content: var(--tw-content);
        --tw-translate-x: calc(var(--spacing) * 0);
        translate: var(--tw-translate-x) var(--tw-translate-y);
      }
    }
  }
  .data-\[panel-group-direction\=vertical\]\:after\:-translate-y-1\/2 {
    &[data-panel-group-direction="vertical"] {
      &::after {
        content: var(--tw-content);
        --tw-translate-y: calc(calc(1 / 2 * 100%) * -1);
        translate: var(--tw-translate-x) var(--tw-translate-y);
      }
    }
  }
  .data-\[placeholder\]\:text-muted-foreground {
    &[data-placeholder] {
      color: hsl(var(--muted-foreground));
    }
  }
  .data-\[range-end\=true\]\:rounded-md {
    &[data-range-end="true"] {
      border-radius: calc(var(--radius) - 2px);
    }
  }
  .data-\[range-end\=true\]\:bg-primary {
    &[data-range-end="true"] {
      background-color: hsl(var(--primary));
    }
  }
  .data-\[range-end\=true\]\:text-primary-foreground {
    &[data-range-end="true"] {
      color: hsl(var(--primary-foreground));
    }
  }
  .data-\[range-middle\=true\]\:rounded-none {
    &[data-range-middle="true"] {
      border-radius: 0;
    }
  }
  .data-\[range-middle\=true\]\:bg-accent {
    &[data-range-middle="true"] {
      background-color: hsl(var(--accent));
    }
  }
  .data-\[range-middle\=true\]\:text-accent-foreground {
    &[data-range-middle="true"] {
      color: hsl(var(--accent-foreground));
    }
  }
  .data-\[range-start\=true\]\:rounded-md {
    &[data-range-start="true"] {
      border-radius: calc(var(--radius) - 2px);
    }
  }
  .data-\[range-start\=true\]\:bg-primary {
    &[data-range-start="true"] {
      background-color: hsl(var(--primary));
    }
  }
  .data-\[range-start\=true\]\:text-primary-foreground {
    &[data-range-start="true"] {
      color: hsl(var(--primary-foreground));
    }
  }
  .data-\[selected-single\=true\]\:bg-primary {
    &[data-selected-single="true"] {
      background-color: hsl(var(--primary));
    }
  }
  .data-\[selected-single\=true\]\:text-primary-foreground {
    &[data-selected-single="true"] {
      color: hsl(var(--primary-foreground));
    }
  }
  .data-\[selected\=true\]\:rounded-none {
    &[data-selected="true"] {
      border-radius: 0;
    }
  }
  .data-\[selected\=true\]\:bg-accent {
    &[data-selected="true"] {
      background-color: hsl(var(--accent));
    }
  }
  .data-\[selected\=true\]\:text-accent-foreground {
    &[data-selected="true"] {
      color: hsl(var(--accent-foreground));
    }
  }
  .data-\[side\=bottom\]\:translate-y-1 {
    &[data-side="bottom"] {
      --tw-translate-y: calc(var(--spacing) * 1);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[side\=bottom\]\:slide-in-from-top-2 {
    &[data-side="bottom"] {
      --tw-enter-translate-y: calc(2*var(--spacing)*-1);
    }
  }
  .data-\[side\=left\]\:-translate-x-1 {
    &[data-side="left"] {
      --tw-translate-x: calc(var(--spacing) * -1);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[side\=left\]\:slide-in-from-right-2 {
    &[data-side="left"] {
      --tw-enter-translate-x: calc(2*var(--spacing));
    }
  }
  .data-\[side\=right\]\:translate-x-1 {
    &[data-side="right"] {
      --tw-translate-x: calc(var(--spacing) * 1);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[side\=right\]\:slide-in-from-left-2 {
    &[data-side="right"] {
      --tw-enter-translate-x: calc(2*var(--spacing)*-1);
    }
  }
  .data-\[side\=top\]\:-translate-y-1 {
    &[data-side="top"] {
      --tw-translate-y: calc(var(--spacing) * -1);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[side\=top\]\:slide-in-from-bottom-2 {
    &[data-side="top"] {
      --tw-enter-translate-y: calc(2*var(--spacing));
    }
  }
  .data-\[slot\=checkbox-group\]\:gap-3 {
    &[data-slot="checkbox-group"] {
      gap: calc(var(--spacing) * 3);
    }
  }
  .data-\[state\=active\]\:bg-background {
    &[data-state="active"] {
      background-color: hsl(var(--background));
    }
  }
  .data-\[state\=active\]\:text-foreground {
    &[data-state="active"] {
      color: hsl(var(--foreground));
    }
  }
  .data-\[state\=active\]\:shadow {
    &[data-state="active"] {
      --tw-shadow: 0 1px 3px 0 var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 1px 2px -1px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
      box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
    }
  }
  .data-\[state\=checked\]\:translate-x-4 {
    &[data-state="checked"] {
      --tw-translate-x: calc(var(--spacing) * 4);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[state\=checked\]\:bg-primary {
    &[data-state="checked"] {
      background-color: hsl(var(--primary));
    }
  }
  .data-\[state\=checked\]\:text-primary-foreground {
    &[data-state="checked"] {
      color: hsl(var(--primary-foreground));
    }
  }
  .data-\[state\=closed\]\:animate-accordion-up {
    &[data-state="closed"] {
      animation: accordion-up var(--tw-animation-duration,var(--tw-duration,.2s))var(--tw-ease,ease-out)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[state\=closed\]\:animate-out {
    &[data-state="closed"] {
      animation: exit var(--tw-animation-duration,var(--tw-duration,.15s))var(--tw-ease,ease)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[state\=closed\]\:duration-300 {
    &[data-state="closed"] {
      --tw-duration: 300ms;
      transition-duration: 300ms;
    }
  }
  .data-\[state\=closed\]\:fade-out-0 {
    &[data-state="closed"] {
      --tw-exit-opacity: calc(0/100);
      --tw-exit-opacity: 0;
    }
  }
  .data-\[state\=closed\]\:fade-out-80 {
    &[data-state="closed"] {
      --tw-exit-opacity: calc(80/100);
      --tw-exit-opacity: .8;
    }
  }
  .data-\[state\=closed\]\:zoom-out-95 {
    &[data-state="closed"] {
      --tw-exit-scale: calc(95*1%);
      --tw-exit-scale: .95;
    }
  }
  .data-\[state\=closed\]\:slide-out-to-bottom {
    &[data-state="closed"] {
      --tw-exit-translate-y: 100%;
    }
  }
  .data-\[state\=closed\]\:slide-out-to-left {
    &[data-state="closed"] {
      --tw-exit-translate-x: -100%;
    }
  }
  .data-\[state\=closed\]\:slide-out-to-left-1\/2 {
    &[data-state="closed"] {
      --tw-exit-translate-x: calc(1 / 2*-100%);
    }
  }
  .data-\[state\=closed\]\:slide-out-to-right {
    &[data-state="closed"] {
      --tw-exit-translate-x: 100%;
    }
  }
  .data-\[state\=closed\]\:slide-out-to-right-full {
    &[data-state="closed"] {
      --tw-exit-translate-x: calc(1*100%);
    }
  }
  .data-\[state\=closed\]\:slide-out-to-top {
    &[data-state="closed"] {
      --tw-exit-translate-y: -100%;
    }
  }
  .data-\[state\=closed\]\:slide-out-to-top-\[48\%\] {
    &[data-state="closed"] {
      --tw-exit-translate-y: calc(48%*-1);
    }
  }
  .data-\[state\=hidden\]\:animate-out {
    &[data-state="hidden"] {
      animation: exit var(--tw-animation-duration,var(--tw-duration,.15s))var(--tw-ease,ease)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[state\=hidden\]\:fade-out {
    &[data-state="hidden"] {
      --tw-exit-opacity: 0;
    }
  }
  .data-\[state\=on\]\:bg-accent {
    &[data-state="on"] {
      background-color: hsl(var(--accent));
    }
  }
  .data-\[state\=on\]\:text-accent-foreground {
    &[data-state="on"] {
      color: hsl(var(--accent-foreground));
    }
  }
  .data-\[state\=open\]\:animate-accordion-down {
    &[data-state="open"] {
      animation: accordion-down var(--tw-animation-duration,var(--tw-duration,.2s))var(--tw-ease,ease-out)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[state\=open\]\:animate-in {
    &[data-state="open"] {
      animation: enter var(--tw-animation-duration,var(--tw-duration,.15s))var(--tw-ease,ease)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[state\=open\]\:bg-accent {
    &[data-state="open"] {
      background-color: hsl(var(--accent));
    }
  }
  .data-\[state\=open\]\:bg-accent\/50 {
    &[data-state="open"] {
      background-color: hsl(var(--accent));
      @supports (color: color-mix(in lab, red, red)) {
        background-color: color-mix(in oklab, hsl(var(--accent)) 50%, transparent);
      }
    }
  }
  .data-\[state\=open\]\:bg-secondary {
    &[data-state="open"] {
      background-color: hsl(var(--secondary));
    }
  }
  .data-\[state\=open\]\:text-accent-foreground {
    &[data-state="open"] {
      color: hsl(var(--accent-foreground));
    }
  }
  .data-\[state\=open\]\:text-muted-foreground {
    &[data-state="open"] {
      color: hsl(var(--muted-foreground));
    }
  }
  .data-\[state\=open\]\:opacity-100 {
    &[data-state="open"] {
      opacity: 100%;
    }
  }
  .data-\[state\=open\]\:duration-500 {
    &[data-state="open"] {
      --tw-duration: 500ms;
      transition-duration: 500ms;
    }
  }
  .data-\[state\=open\]\:fade-in-0 {
    &[data-state="open"] {
      --tw-enter-opacity: calc(0/100);
      --tw-enter-opacity: 0;
    }
  }
  .data-\[state\=open\]\:zoom-in-90 {
    &[data-state="open"] {
      --tw-enter-scale: calc(90*1%);
      --tw-enter-scale: .9;
    }
  }
  .data-\[state\=open\]\:zoom-in-95 {
    &[data-state="open"] {
      --tw-enter-scale: calc(95*1%);
      --tw-enter-scale: .95;
    }
  }
  .data-\[state\=open\]\:slide-in-from-bottom {
    &[data-state="open"] {
      --tw-enter-translate-y: 100%;
    }
  }
  .data-\[state\=open\]\:slide-in-from-left {
    &[data-state="open"] {
      --tw-enter-translate-x: -100%;
    }
  }
  .data-\[state\=open\]\:slide-in-from-left-1\/2 {
    &[data-state="open"] {
      --tw-enter-translate-x: calc(1 / 2*-100%);
    }
  }
  .data-\[state\=open\]\:slide-in-from-right {
    &[data-state="open"] {
      --tw-enter-translate-x: 100%;
    }
  }
  .data-\[state\=open\]\:slide-in-from-top {
    &[data-state="open"] {
      --tw-enter-translate-y: -100%;
    }
  }
  .data-\[state\=open\]\:slide-in-from-top-\[48\%\] {
    &[data-state="open"] {
      --tw-enter-translate-y: calc(48%*-1);
    }
  }
  .data-\[state\=open\]\:slide-in-from-top-full {
    &[data-state="open"] {
      --tw-enter-translate-y: calc(1*-100%);
    }
  }
  .data-\[state\=open\]\:hover\:bg-accent {
    &[data-state="open"] {
      &:hover {
        @media (hover: hover) {
          background-color: hsl(var(--accent));
        }
      }
    }
  }
  .data-\[state\=open\]\:focus\:bg-accent {
    &[data-state="open"] {
      &:focus {
        background-color: hsl(var(--accent));
      }
    }
  }
  .data-\[state\=selected\]\:bg-muted {
    &[data-state="selected"] {
      background-color: hsl(var(--muted));
    }
  }
  .data-\[state\=unchecked\]\:translate-x-0 {
    &[data-state="unchecked"] {
      --tw-translate-x: calc(var(--spacing) * 0);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[state\=unchecked\]\:bg-input {
    &[data-state="unchecked"] {
      background-color: hsl(var(--input));
    }
  }
  .data-\[state\=visible\]\:animate-in {
    &[data-state="visible"] {
      animation: enter var(--tw-animation-duration,var(--tw-duration,.15s))var(--tw-ease,ease)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[state\=visible\]\:fade-in {
    &[data-state="visible"] {
      --tw-enter-opacity: 0;
    }
  }
  .data-\[swipe\=cancel\]\:translate-x-0 {
    &[data-swipe="cancel"] {
      --tw-translate-x: calc(var(--spacing) * 0);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[swipe\=end\]\:translate-x-\[var\(--radix-toast-swipe-end-x\)\] {
    &[data-swipe="end"] {
      --tw-translate-x: var(--radix-toast-swipe-end-x);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[swipe\=end\]\:animate-out {
    &[data-swipe="end"] {
      animation: exit var(--tw-animation-duration,var(--tw-duration,.15s))var(--tw-ease,ease)var(--tw-animation-delay,0s)var(--tw-animation-iteration-count,1)var(--tw-animation-direction,normal)var(--tw-animation-fill-mode,none);
    }
  }
  .data-\[swipe\=move\]\:translate-x-\[var\(--radix-toast-swipe-move-x\)\] {
    &[data-swipe="move"] {
      --tw-translate-x: var(--radix-toast-swipe-move-x);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .data-\[swipe\=move\]\:transition-none {
    &[data-swipe="move"] {
      transition-property: none;
    }
  }
  .data-\[variant\=label\]\:text-sm {
    &[data-variant="label"] {
      font-size: var(--text-sm);
      line-height: var(--tw-leading, var(--text-sm--line-height));
    }
  }
  .data-\[variant\=legend\]\:text-base {
    &[data-variant="legend"] {
      font-size: var(--text-base);
      line-height: var(--tw-leading, var(--text-base--line-height));
    }
  }
  .nth-last-2\:-mt-1 {
    &:nth-last-child(2) {
      margin-top: calc(var(--spacing) * -1);
    }
  }
  .sm\:top-auto {
    @media (width >= 40rem) {
      top: auto;
    }
  }
  .sm\:right-0 {
    @media (width >= 40rem) {
      right: calc(var(--spacing) * 0);
    }
  }
  .sm\:bottom-0 {
    @media (width >= 40rem) {
      bottom: calc(var(--spacing) * 0);
    }
  }
  .sm\:mt-0 {
    @media (width >= 40rem) {
      margin-top: calc(var(--spacing) * 0);
    }
  }
  .sm\:block {
    @media (width >= 40rem) {
      display: block;
    }
  }
  .sm\:flex {
    @media (width >= 40rem) {
      display: flex;
    }
  }
  .sm\:w-auto {
    @media (width >= 40rem) {
      width: auto;
    }
  }
  .sm\:max-w-sm {
    @media (width >= 40rem) {
      max-width: var(--container-sm);
    }
  }
  .sm\:grid-cols-2 {
    @media (width >= 40rem) {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }
  .sm\:flex-col {
    @media (width >= 40rem) {
      flex-direction: column;
    }
  }
  .sm\:flex-row {
    @media (width >= 40rem) {
      flex-direction: row;
    }
  }
  .sm\:justify-end {
    @media (width >= 40rem) {
      justify-content: flex-end;
    }
  }
  .sm\:gap-2\.5 {
    @media (width >= 40rem) {
      gap: calc(var(--spacing) * 2.5);
    }
  }
  .sm\:space-x-2 {
    @media (width >= 40rem) {
      :where(& > :not(:last-child)) {
        --tw-space-x-reverse: 0;
        margin-inline-start: calc(calc(var(--spacing) * 2) * var(--tw-space-x-reverse));
        margin-inline-end: calc(calc(var(--spacing) * 2) * calc(1 - var(--tw-space-x-reverse)));
      }
    }
  }
  .sm\:rounded-lg {
    @media (width >= 40rem) {
      border-radius: var(--radius);
    }
  }
  .sm\:text-left {
    @media (width >= 40rem) {
      text-align: left;
    }
  }
  .data-\[state\=open\]\:sm\:slide-in-from-bottom-full {
    &[data-state="open"] {
      @media (width >= 40rem) {
        --tw-enter-translate-y: calc(1*100%);
      }
    }
  }
  .md\:absolute {
    @media (width >= 48rem) {
      position: absolute;
    }
  }
  .md\:left-1\/2 {
    @media (width >= 48rem) {
      left: calc(1 / 2 * 100%);
    }
  }
  .md\:ml-auto {
    @media (width >= 48rem) {
      margin-left: auto;
    }
  }
  .md\:block {
    @media (width >= 48rem) {
      display: block;
    }
  }
  .md\:flex {
    @media (width >= 48rem) {
      display: flex;
    }
  }
  .md\:hidden {
    @media (width >= 48rem) {
      display: none;
    }
  }
  .md\:w-\[400px\] {
    @media (width >= 48rem) {
      width: 400px;
    }
  }
  .md\:w-\[600px\] {
    @media (width >= 48rem) {
      width: 600px;
    }
  }
  .md\:w-\[var\(--radix-navigation-menu-viewport-width\)\] {
    @media (width >= 48rem) {
      width: var(--radix-navigation-menu-viewport-width);
    }
  }
  .md\:w-auto {
    @media (width >= 48rem) {
      width: auto;
    }
  }
  .md\:max-w-\[420px\] {
    @media (width >= 48rem) {
      max-width: 420px;
    }
  }
  .md\:-translate-x-1\/2 {
    @media (width >= 48rem) {
      --tw-translate-x: calc(calc(1 / 2 * 100%) * -1);
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .md\:grid-cols-2 {
    @media (width >= 48rem) {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }
  .md\:grid-cols-3 {
    @media (width >= 48rem) {
      grid-template-columns: repeat(3, minmax(0, 1fr));
    }
  }
  .md\:flex-row {
    @media (width >= 48rem) {
      flex-direction: row;
    }
  }
  .md\:flex-row-reverse {
    @media (width >= 48rem) {
      flex-direction: row-reverse;
    }
  }
  .md\:items-center {
    @media (width >= 48rem) {
      align-items: center;
    }
  }
  .md\:items-end {
    @media (width >= 48rem) {
      align-items: flex-end;
    }
  }
  .md\:gap-12 {
    @media (width >= 48rem) {
      gap: calc(var(--spacing) * 12);
    }
  }
  .md\:gap-16 {
    @media (width >= 48rem) {
      gap: calc(var(--spacing) * 16);
    }
  }
  .md\:space-y-24 {
    @media (width >= 48rem) {
      :where(& > :not(:last-child)) {
        --tw-space-y-reverse: 0;
        margin-block-start: calc(calc(var(--spacing) * 24) * var(--tw-space-y-reverse));
        margin-block-end: calc(calc(var(--spacing) * 24) * calc(1 - var(--tw-space-y-reverse)));
      }
    }
  }
  .md\:p-12 {
    @media (width >= 48rem) {
      padding: calc(var(--spacing) * 12);
    }
  }
  .md\:px-0 {
    @media (width >= 48rem) {
      padding-inline: calc(var(--spacing) * 0);
    }
  }
  .md\:text-right {
    @media (width >= 48rem) {
      text-align: right;
    }
  }
  .md\:text-2xl {
    @media (width >= 48rem) {
      font-size: var(--text-2xl);
      line-height: var(--tw-leading, var(--text-2xl--line-height));
    }
  }
  .md\:text-3xl {
    @media (width >= 48rem) {
      font-size: var(--text-3xl);
      line-height: var(--tw-leading, var(--text-3xl--line-height));
    }
  }
  .md\:text-4xl {
    @media (width >= 48rem) {
      font-size: var(--text-4xl);
      line-height: var(--tw-leading, var(--text-4xl--line-height));
    }
  }
  .md\:text-5xl {
    @media (width >= 48rem) {
      font-size: var(--text-5xl);
      line-height: var(--tw-leading, var(--text-5xl--line-height));
    }
  }
  .md\:text-6xl {
    @media (width >= 48rem) {
      font-size: var(--text-6xl);
      line-height: var(--tw-leading, var(--text-6xl--line-height));
    }
  }
  .md\:text-8xl {
    @media (width >= 48rem) {
      font-size: var(--text-8xl);
      line-height: var(--tw-leading, var(--text-8xl--line-height));
    }
  }
  .md\:text-base {
    @media (width >= 48rem) {
      font-size: var(--text-base);
      line-height: var(--tw-leading, var(--text-base--line-height));
    }
  }
  .md\:text-sm {
    @media (width >= 48rem) {
      font-size: var(--text-sm);
      line-height: var(--tw-leading, var(--text-sm--line-height));
    }
  }
  .md\:text-xl {
    @media (width >= 48rem) {
      font-size: var(--text-xl);
      line-height: var(--tw-leading, var(--text-xl--line-height));
    }
  }
  .md\:opacity-0 {
    @media (width >= 48rem) {
      opacity: 0%;
    }
  }
  .md\:peer-data-\[variant\=inset\]\:m-2 {
    @media (width >= 48rem) {
      &:is(:where(.peer)[data-variant="inset"] ~ *) {
        margin: calc(var(--spacing) * 2);
      }
    }
  }
  .md\:peer-data-\[variant\=inset\]\:ml-0 {
    @media (width >= 48rem) {
      &:is(:where(.peer)[data-variant="inset"] ~ *) {
        margin-left: calc(var(--spacing) * 0);
      }
    }
  }
  .md\:peer-data-\[variant\=inset\]\:rounded-xl {
    @media (width >= 48rem) {
      &:is(:where(.peer)[data-variant="inset"] ~ *) {
        border-radius: calc(var(--radius) + 4px);
      }
    }
  }
  .md\:peer-data-\[variant\=inset\]\:shadow-sm {
    @media (width >= 48rem) {
      &:is(:where(.peer)[data-variant="inset"] ~ *) {
        --tw-shadow: 0 1px 3px 0 var(--tw-shadow-color, rgb(0 0 0 / 0.1)), 0 1px 2px -1px var(--tw-shadow-color, rgb(0 0 0 / 0.1));
        box-shadow: var(--tw-inset-shadow), var(--tw-inset-ring-shadow), var(--tw-ring-offset-shadow), var(--tw-ring-shadow), var(--tw-shadow);
      }
    }
  }
  .md\:peer-data-\[variant\=inset\]\:peer-data-\[state\=collapsed\]\:ml-2 {
    @media (width >= 48rem) {
      &:is(:where(.peer)[data-variant="inset"] ~ *) {
        &:is(:where(.peer)[data-state="collapsed"] ~ *) {
          margin-left: calc(var(--spacing) * 2);
        }
      }
    }
  }
  .md\:after\:hidden {
    @media (width >= 48rem) {
      &::after {
        content: var(--tw-content);
        display: none;
      }
    }
  }
  .lg\:grid-cols-2 {
    @media (width >= 64rem) {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }
  .lg\:grid-cols-4 {
    @media (width >= 64rem) {
      grid-template-columns: repeat(4, minmax(0, 1fr));
    }
  }
  .lg\:text-9xl {
    @media (width >= 64rem) {
      font-size: var(--text-9xl);
      line-height: var(--tw-leading, var(--text-9xl--line-height));
    }
  }
  .\@md\/field-group\:flex-row {
    @container field-group (width >= 28rem) {
      flex-direction: row;
    }
  }
  .\@md\/field-group\:items-center {
    @container field-group (width >= 28rem) {
      align-items: center;
    }
  }
  .\@md\/field-group\:has-\[\>\[data-slot\=field-content\]\]\:items-start {
    @container field-group (width >= 28rem) {
      &:has(>[data-slot=field-content]) {
        align-items: flex-start;
      }
    }
  }
  .dark\:border-destructive {
    &:is(.dark *) {
      border-color: hsl(var(--destructive));
    }
  }
  .dark\:bg-input\/30 {
    &:is(.dark *) {
      background-color: hsl(var(--input));
      @supports (color: color-mix(in lab, red, red)) {
        background-color: color-mix(in oklab, hsl(var(--input)) 30%, transparent);
      }
    }
  }
  .dark\:bg-transparent {
    &:is(.dark *) {
      background-color: transparent;
    }
  }
  .dark\:has-data-\[state\=checked\]\:bg-primary\/10 {
    &:is(.dark *) {
      &:has(*[data-state="checked"]) {
        background-color: hsl(var(--primary));
        @supports (color: color-mix(in lab, red, red)) {
          background-color: color-mix(in oklab, hsl(var(--primary)) 10%, transparent);
        }
      }
    }
  }
  .dark\:has-\[\[data-slot\]\[aria-invalid\=true\]\]\:ring-destructive\/40 {
    &:is(.dark *) {
      &:has(*:is([data-slot][aria-invalid=true])) {
        --tw-ring-color: hsl(var(--destructive));
        @supports (color: color-mix(in lab, red, red)) {
          --tw-ring-color: color-mix(in oklab, hsl(var(--destructive)) 40%, transparent);
        }
      }
    }
  }
  .\[\&_\.recharts-cartesian-axis-tick_text\]\:fill-muted-foreground {
    & .recharts-cartesian-axis-tick text {
      fill: hsl(var(--muted-foreground));
    }
  }
  .\[\&_\.recharts-cartesian-grid_line\[stroke\=\'\#ccc\'\]\]\:stroke-border\/50 {
    & .recharts-cartesian-grid line[stroke='#ccc'] {
      stroke: hsl(var(--border));
      @supports (color: color-mix(in lab, red, red)) {
        stroke: color-mix(in oklab, hsl(var(--border)) 50%, transparent);
      }
    }
  }
  .\[\&_\.recharts-curve\.recharts-tooltip-cursor\]\:stroke-border {
    & .recharts-curve.recharts-tooltip-cursor {
      stroke: hsl(var(--border));
    }
  }
  .\[\&_\.recharts-dot\[stroke\=\'\#fff\'\]\]\:stroke-transparent {
    & .recharts-dot[stroke='#fff'] {
      stroke: transparent;
    }
  }
  .\[\&_\.recharts-layer\]\:outline-none {
    & .recharts-layer {
      --tw-outline-style: none;
      outline-style: none;
    }
  }
  .\[\&_\.recharts-polar-grid_\[stroke\=\'\#ccc\'\]\]\:stroke-border {
    & .recharts-polar-grid [stroke='#ccc'] {
      stroke: hsl(var(--border));
    }
  }
  .\[\&_\.recharts-radial-bar-background-sector\]\:fill-muted {
    & .recharts-radial-bar-background-sector {
      fill: hsl(var(--muted));
    }
  }
  .\[\&_\.recharts-rectangle\.recharts-tooltip-cursor\]\:fill-muted {
    & .recharts-rectangle.recharts-tooltip-cursor {
      fill: hsl(var(--muted));
    }
  }
  .\[\&_\.recharts-reference-line_\[stroke\=\'\#ccc\'\]\]\:stroke-border {
    & .recharts-reference-line [stroke='#ccc'] {
      stroke: hsl(var(--border));
    }
  }
  .\[\&_\.recharts-sector\]\:outline-none {
    & .recharts-sector {
      --tw-outline-style: none;
      outline-style: none;
    }
  }
  .\[\&_\.recharts-sector\[stroke\=\'\#fff\'\]\]\:stroke-transparent {
    & .recharts-sector[stroke='#fff'] {
      stroke: transparent;
    }
  }
  .\[\&_\.recharts-surface\]\:outline-none {
    & .recharts-surface {
      --tw-outline-style: none;
      outline-style: none;
    }
  }
  .\[\&_\[cmdk-group-heading\]\]\:px-2 {
    & [cmdk-group-heading] {
      padding-inline: calc(var(--spacing) * 2);
    }
  }
  .\[\&_\[cmdk-group-heading\]\]\:py-1\.5 {
    & [cmdk-group-heading] {
      padding-block: calc(var(--spacing) * 1.5);
    }
  }
  .\[\&_\[cmdk-group-heading\]\]\:text-xs {
    & [cmdk-group-heading] {
      font-size: var(--text-xs);
      line-height: var(--tw-leading, var(--text-xs--line-height));
    }
  }
  .\[\&_\[cmdk-group-heading\]\]\:font-medium {
    & [cmdk-group-heading] {
      --tw-font-weight: var(--font-weight-medium);
      font-weight: var(--font-weight-medium);
    }
  }
  .\[\&_\[cmdk-group-heading\]\]\:text-muted-foreground {
    & [cmdk-group-heading] {
      color: hsl(var(--muted-foreground));
    }
  }
  .\[\&_\[cmdk-group\]\]\:px-2 {
    & [cmdk-group] {
      padding-inline: calc(var(--spacing) * 2);
    }
  }
  .\[\&_\[cmdk-group\]\:not\(\[hidden\]\)_\~\[cmdk-group\]\]\:pt-0 {
    & [cmdk-group]:not([hidden]) ~[cmdk-group] {
      padding-top: calc(var(--spacing) * 0);
    }
  }
  .\[\&_\[cmdk-input-wrapper\]_svg\]\:h-5 {
    & [cmdk-input-wrapper] svg {
      height: calc(var(--spacing) * 5);
    }
  }
  .\[\&_\[cmdk-input-wrapper\]_svg\]\:w-5 {
    & [cmdk-input-wrapper] svg {
      width: calc(var(--spacing) * 5);
    }
  }
  .\[\&_\[cmdk-input\]\]\:h-12 {
    & [cmdk-input] {
      height: calc(var(--spacing) * 12);
    }
  }
  .\[\&_\[cmdk-item\]\]\:px-2 {
    & [cmdk-item] {
      padding-inline: calc(var(--spacing) * 2);
    }
  }
  .\[\&_\[cmdk-item\]\]\:py-3 {
    & [cmdk-item] {
      padding-block: calc(var(--spacing) * 3);
    }
  }
  .\[\&_\[cmdk-item\]_svg\]\:h-5 {
    & [cmdk-item] svg {
      height: calc(var(--spacing) * 5);
    }
  }
  .\[\&_\[cmdk-item\]_svg\]\:w-5 {
    & [cmdk-item] svg {
      width: calc(var(--spacing) * 5);
    }
  }
  .\[\&_img\]\:size-full {
    & img {
      width: 100%;
      height: 100%;
    }
  }
  .\[\&_img\]\:object-cover {
    & img {
      object-fit: cover;
    }
  }
  .\[\&_p\]\:leading-relaxed {
    & p {
      --tw-leading: var(--leading-relaxed);
      line-height: var(--leading-relaxed);
    }
  }
  .\[\&_svg\]\:pointer-events-none {
    & svg {
      pointer-events: none;
    }
  }
  .\[\&_svg\]\:size-4 {
    & svg {
      width: calc(var(--spacing) * 4);
      height: calc(var(--spacing) * 4);
    }
  }
  .\[\&_svg\]\:shrink-0 {
    & svg {
      flex-shrink: 0;
    }
  }
  .\[\&_svg\:not\(\[class\*\=\'size-\'\]\)\]\:size-3 {
    & svg:not([class*='size-']) {
      width: calc(var(--spacing) * 3);
      height: calc(var(--spacing) * 3);
    }
  }
  .\[\&_svg\:not\(\[class\*\=\'size-\'\]\)\]\:size-4 {
    & svg:not([class*='size-']) {
      width: calc(var(--spacing) * 4);
      height: calc(var(--spacing) * 4);
    }
  }
  .\[\&_svg\:not\(\[class\*\=\'size-\'\]\)\]\:size-6 {
    & svg:not([class*='size-']) {
      width: calc(var(--spacing) * 6);
      height: calc(var(--spacing) * 6);
    }
  }
  .\[\&_tr\]\:border-b {
    & tr {
      border-bottom-style: var(--tw-border-style);
      border-bottom-width: 1px;
    }
  }
  .\[\&_tr\:last-child\]\:border-0 {
    & tr:last-child {
      border-style: var(--tw-border-style);
      border-width: 0px;
    }
  }
  .\[\&\+\[data-slot\=item-content\]\]\:flex-none {
    &+[data-slot=item-content] {
      flex: none;
    }
  }
  .\[\&\:first-child\[data-selected\=true\]_button\]\:rounded-l-md {
    &:first-child[data-selected=true] button {
      border-top-left-radius: calc(var(--radius) - 2px);
      border-bottom-left-radius: calc(var(--radius) - 2px);
    }
  }
  .\[\&\:has\(\[role\=checkbox\]\)\]\:pr-0 {
    &:has([role=checkbox]) {
      padding-right: calc(var(--spacing) * 0);
    }
  }
  .\[\.border-b\]\:pb-3 {
    &:is(.border-b) {
      padding-bottom: calc(var(--spacing) * 3);
    }
  }
  .\[\.border-t\]\:pt-3 {
    &:is(.border-t) {
      padding-top: calc(var(--spacing) * 3);
    }
  }
  .rtl\:\*\*\:\[\.rdp-button\\_next\>svg\]\:rotate-180 {
    &:where(:dir(rtl), [dir="rtl"], [dir="rtl"] *) {
      :is(& *) {
        &:is(.rdp-button_next>svg) {
          rotate: 180deg;
        }
      }
    }
  }
  .rtl\:\*\*\:\[\.rdp-button\\_previous\>svg\]\:rotate-180 {
    &:where(:dir(rtl), [dir="rtl"], [dir="rtl"] *) {
      :is(& *) {
        &:is(.rdp-button_previous>svg) {
          rotate: 180deg;
        }
      }
    }
  }
  .\[a\]\:transition-colors {
    &:is(a) {
      transition-property: color, background-color, border-color, outline-color, text-decoration-color, fill, stroke, --tw-gradient-from, --tw-gradient-via, --tw-gradient-to;
      transition-timing-function: var(--tw-ease, var(--default-transition-timing-function));
      transition-duration: var(--tw-duration, var(--default-transition-duration));
    }
  }
  .\[a\]\:hover\:bg-accent\/50 {
    &:is(a) {
      &:hover {
        @media (hover: hover) {
          background-color: hsl(var(--accent));
          @supports (color: color-mix(in lab, red, red)) {
            background-color: color-mix(in oklab, hsl(var(--accent)) 50%, transparent);
          }
        }
      }
    }
  }
  .\[\&\:last-child\[data-selected\=true\]_button\]\:rounded-r-md {
    &:last-child[data-selected=true] button {
      border-top-right-radius: calc(var(--radius) - 2px);
      border-bottom-right-radius: calc(var(--radius) - 2px);
    }
  }
  .\[\&\>\*\]\:w-full {
    &>* {
      width: 100%;
    }
  }
  .\[\&\>\*\]\:focus-visible\:relative {
    &>* {
      &:focus-visible {
        position: relative;
      }
    }
  }
  .\[\&\>\*\]\:focus-visible\:z-10 {
    &>* {
      &:focus-visible {
        z-index: 10;
      }
    }
  }
  .\@md\/field-group\:\[\&\>\*\]\:w-auto {
    @container field-group (width >= 28rem) {
      &>* {
        width: auto;
      }
    }
  }
  .\[\&\>\*\:not\(\:first-child\)\]\:rounded-t-none {
    &>*:not(:first-child) {
      border-top-left-radius: 0;
      border-top-right-radius: 0;
    }
  }
  .\[\&\>\*\:not\(\:first-child\)\]\:rounded-l-none {
    &>*:not(:first-child) {
      border-top-left-radius: 0;
      border-bottom-left-radius: 0;
    }
  }
  .\[\&\>\*\:not\(\:first-child\)\]\:border-t-0 {
    &>*:not(:first-child) {
      border-top-style: var(--tw-border-style);
      border-top-width: 0px;
    }
  }
  .\[\&\>\*\:not\(\:first-child\)\]\:border-l-0 {
    &>*:not(:first-child) {
      border-left-style: var(--tw-border-style);
      border-left-width: 0px;
    }
  }
  .\[\&\>\*\:not\(\:last-child\)\]\:rounded-r-none {
    &>*:not(:last-child) {
      border-top-right-radius: 0;
      border-bottom-right-radius: 0;
    }
  }
  .\[\&\>\*\:not\(\:last-child\)\]\:rounded-b-none {
    &>*:not(:last-child) {
      border-bottom-right-radius: 0;
      border-bottom-left-radius: 0;
    }
  }
  .\[\&\>\.sr-only\]\:w-auto {
    &>.sr-only {
      width: auto;
    }
  }
  .\[\&\>\[data-slot\=field-group\]\]\:gap-4 {
    &>[data-slot=field-group] {
      gap: calc(var(--spacing) * 4);
    }
  }
  .\[\&\>\[data-slot\=field-label\]\]\:flex-auto {
    &>[data-slot=field-label] {
      flex: auto;
    }
  }
  .\@md\/field-group\:\[\&\>\[data-slot\=field-label\]\]\:flex-auto {
    @container field-group (width >= 28rem) {
      &>[data-slot=field-label] {
        flex: auto;
      }
    }
  }
  .\[\&\>\[data-slot\=field\]\]\:p-4 {
    &>[data-slot=field] {
      padding: calc(var(--spacing) * 4);
    }
  }
  .has-\[select\[aria-hidden\=true\]\:last-child\]\:\[\&\>\[data-slot\=select-trigger\]\:last-of-type\]\:rounded-r-md {
    &:has(*:is(select[aria-hidden=true]:last-child)) {
      &>[data-slot=select-trigger]:last-of-type {
        border-top-right-radius: calc(var(--radius) - 2px);
        border-bottom-right-radius: calc(var(--radius) - 2px);
      }
    }
  }
  .\[\&\>\[data-slot\=select-trigger\]\:not\(\[class\*\=\'w-\'\]\)\]\:w-fit {
    &>[data-slot=select-trigger]:not([class*='w-']) {
      width: fit-content;
    }
  }
  .\[\&\>\[role\=checkbox\]\]\:translate-y-\[2px\] {
    &>[role=checkbox] {
      --tw-translate-y: 2px;
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .has-\[\>\[data-slot\=field-content\]\]\:\[\&\>\[role\=checkbox\]\,\[role\=radio\]\]\:mt-px {
    &:has(>[data-slot=field-content]) {
      &>[role=checkbox],[role=radio] {
        margin-top: 1px;
      }
    }
  }
  .\@md\/field-group\:has-\[\>\[data-slot\=field-content\]\]\:\[\&\>\[role\=checkbox\]\,\[role\=radio\]\]\:mt-px {
    @container field-group (width >= 28rem) {
      &:has(>[data-slot=field-content]) {
        &>[role=checkbox],[role=radio] {
          margin-top: 1px;
        }
      }
    }
  }
  .\[\&\>a\]\:underline {
    &>a {
      text-decoration-line: underline;
    }
  }
  .\[\&\>a\]\:underline-offset-4 {
    &>a {
      text-underline-offset: 4px;
    }
  }
  .\[\&\>a\:hover\]\:text-primary {
    &>a:hover {
      color: hsl(var(--primary));
    }
  }
  .\[\&\>button\]\:hidden {
    &>button {
      display: none;
    }
  }
  .\[\&\>input\]\:flex-1 {
    &>input {
      flex: 1;
    }
  }
  .has-\[\>\[data-align\=block-end\]\]\:\[\&\>input\]\:pt-3 {
    &:has(>[data-align=block-end]) {
      &>input {
        padding-top: calc(var(--spacing) * 3);
      }
    }
  }
  .has-\[\>\[data-align\=block-start\]\]\:\[\&\>input\]\:pb-3 {
    &:has(>[data-align=block-start]) {
      &>input {
        padding-bottom: calc(var(--spacing) * 3);
      }
    }
  }
  .has-\[\>\[data-align\=inline-end\]\]\:\[\&\>input\]\:pr-2 {
    &:has(>[data-align=inline-end]) {
      &>input {
        padding-right: calc(var(--spacing) * 2);
      }
    }
  }
  .has-\[\>\[data-align\=inline-start\]\]\:\[\&\>input\]\:pl-2 {
    &:has(>[data-align=inline-start]) {
      &>input {
        padding-left: calc(var(--spacing) * 2);
      }
    }
  }
  .\[\&\>kbd\]\:rounded-\[calc\(var\(--radius\)-5px\)\] {
    &>kbd {
      border-radius: calc(var(--radius) - 5px);
    }
  }
  .\[\&\>span\]\:line-clamp-1 {
    &>span {
      overflow: hidden;
      display: -webkit-box;
      -webkit-box-orient: vertical;
      -webkit-line-clamp: 1;
    }
  }
  .\[\&\>span\]\:text-xs {
    &>span {
      font-size: var(--text-xs);
      line-height: var(--tw-leading, var(--text-xs--line-height));
    }
  }
  .\[\&\>span\]\:opacity-70 {
    &>span {
      opacity: 70%;
    }
  }
  .\[\&\>span\:last-child\]\:truncate {
    &>span:last-child {
      overflow: hidden;
      text-overflow: ellipsis;
      white-space: nowrap;
    }
  }
  .\[\&\>svg\]\:absolute {
    &>svg {
      position: absolute;
    }
  }
  .\[\&\>svg\]\:top-4 {
    &>svg {
      top: calc(var(--spacing) * 4);
    }
  }
  .\[\&\>svg\]\:left-4 {
    &>svg {
      left: calc(var(--spacing) * 4);
    }
  }
  .\[\&\>svg\]\:size-3\.5 {
    &>svg {
      width: calc(var(--spacing) * 3.5);
      height: calc(var(--spacing) * 3.5);
    }
  }
  .\[\&\>svg\]\:size-4 {
    &>svg {
      width: calc(var(--spacing) * 4);
      height: calc(var(--spacing) * 4);
    }
  }
  .\[\&\>svg\]\:h-2\.5 {
    &>svg {
      height: calc(var(--spacing) * 2.5);
    }
  }
  .\[\&\>svg\]\:h-3 {
    &>svg {
      height: calc(var(--spacing) * 3);
    }
  }
  .\[\&\>svg\]\:h-3\.5 {
    &>svg {
      height: calc(var(--spacing) * 3.5);
    }
  }
  .\[\&\>svg\]\:h-4 {
    &>svg {
      height: calc(var(--spacing) * 4);
    }
  }
  .\[\&\>svg\]\:w-2\.5 {
    &>svg {
      width: calc(var(--spacing) * 2.5);
    }
  }
  .\[\&\>svg\]\:w-3 {
    &>svg {
      width: calc(var(--spacing) * 3);
    }
  }
  .\[\&\>svg\]\:w-3\.5 {
    &>svg {
      width: calc(var(--spacing) * 3.5);
    }
  }
  .\[\&\>svg\]\:w-4 {
    &>svg {
      width: calc(var(--spacing) * 4);
    }
  }
  .\[\&\>svg\]\:shrink-0 {
    &>svg {
      flex-shrink: 0;
    }
  }
  .\[\&\>svg\]\:text-destructive {
    &>svg {
      color: hsl(var(--destructive));
    }
  }
  .\[\&\>svg\]\:text-foreground {
    &>svg {
      color: hsl(var(--foreground));
    }
  }
  .\[\&\>svg\]\:text-muted-foreground {
    &>svg {
      color: hsl(var(--muted-foreground));
    }
  }
  .\[\&\>svg\+div\]\:translate-y-\[-3px\] {
    &>svg+div {
      --tw-translate-y: -3px;
      translate: var(--tw-translate-x) var(--tw-translate-y);
    }
  }
  .\[\&\>svg\:not\(\[class\*\=\'size-\'\]\)\]\:size-3\.5 {
    &>svg:not([class*='size-']) {
      width: calc(var(--spacing) * 3.5);
      height: calc(var(--spacing) * 3.5);
    }
  }
  .\[\&\>svg\:not\(\[class\*\=\'size-\'\]\)\]\:size-4 {
    &>svg:not([class*='size-']) {
      width: calc(var(--spacing) * 4);
      height: calc(var(--spacing) * 4);
    }
  }
  .\[\&\>svg\~\*\]\:pl-7 {
    &>svg~* {
      padding-left: calc(var(--spacing) * 7);
    }
  }
  .\[\&\>tr\]\:last\:border-b-0 {
    &>tr {
      &:last-child {
        border-bottom-style: var(--tw-border-style);
        border-bottom-width: 0px;
      }
    }
  }
  .\[\&\[data-panel-group-direction\=vertical\]\>div\]\:rotate-90 {
    &[data-panel-group-direction=vertical]>div {
      rotate: 90deg;
    }
  }
  .\[\&\[data-state\=open\]\>svg\]\:rotate-180 {
    &[data-state=open]>svg {
      rotate: 180deg;
    }
  }
  .\[\[data-side\=left\]\[data-collapsible\=offcanvas\]_\&\]\:-right-2 {
    [data-side=left][data-collapsible=offcanvas] & {
      right: calc(var(--spacing) * -2);
    }
  }
  .\[\[data-side\=left\]\[data-state\=collapsed\]_\&\]\:cursor-e-resize {
    [data-side=left][data-state=collapsed] & {
      cursor: e-resize;
    }
  }
  .\[\[data-side\=right\]\[data-collapsible\=offcanvas\]_\&\]\:-left-2 {
    [data-side=right][data-collapsible=offcanvas] & {
      left: calc(var(--spacing) * -2);
    }
  }
  .\[\[data-side\=right\]\[data-state\=collapsed\]_\&\]\:cursor-w-resize {
    [data-side=right][data-state=collapsed] & {
      cursor: w-resize;
    }
  }
  .\[\[data-slot\=card-content\]_\&\]\:bg-transparent {
    [data-slot=card-content] & {
      background-color: transparent;
    }
  }
  .\[\[data-slot\=popover-content\]_\&\]\:bg-transparent {
    [data-slot=popover-content] & {
      background-color: transparent;
    }
  }
  .\[\[data-slot\=tooltip-content\]_\&\]\:bg-background\/20 {
    [data-slot=tooltip-content] & {
      background-color: hsl(var(--background));
      @supports (color: color-mix(in lab, red, red)) {
        background-color: color-mix(in oklab, hsl(var(--background)) 20%, transparent);
      }
    }
  }
  .\[\[data-slot\=tooltip-content\]_\&\]\:text-background {
    [data-slot=tooltip-content] & {
      color: hsl(var(--background));
    }
  }
  .dark\:\[\[data-slot\=tooltip-content\]_\&\]\:bg-background\/10 {
    &:is(.dark *) {
      [data-slot=tooltip-content] & {
        background-color: hsl(var(--background));
        @supports (color: color-mix(in lab, red, red)) {
          background-color: color-mix(in oklab, hsl(var(--background)) 10%, transparent);
        }
      }
    }
  }
  .\[\[data-variant\=legend\]\+\&\]\:-mt-1\.5 {
    [data-variant=legend]+& {
      margin-top: calc(var(--spacing) * -1.5);
    }
  }
}
@property --tw-animation-delay {
  syntax: "*";
  inherits: false;
  initial-value: 0s;
}
@property --tw-animation-direction {
  syntax: "*";
  inherits: false;
  initial-value: normal;
}
@property --tw-animation-duration {
  syntax: "*";
  inherits: false;
}
@property --tw-animation-fill-mode {
  syntax: "*";
  inherits: false;
  initial-value: none;
}
@property --tw-animation-iteration-count {
  syntax: "*";
  inherits: false;
  initial-value: 1;
}
@property --tw-enter-blur {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-enter-opacity {
  syntax: "*";
  inherits: false;
  initial-value: 1;
}
@property --tw-enter-rotate {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-enter-scale {
  syntax: "*";
  inherits: false;
  initial-value: 1;
}
@property --tw-enter-translate-x {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-enter-translate-y {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-exit-blur {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-exit-opacity {
  syntax: "*";
  inherits: false;
  initial-value: 1;
}
@property --tw-exit-rotate {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-exit-scale {
  syntax: "*";
  inherits: false;
  initial-value: 1;
}
@property --tw-exit-translate-x {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-exit-translate-y {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
:root {
  --background: 230 40% 6%;
  --foreground: 210 40% 98%;
  --border: 230 30% 15%;
  --input: 230 30% 15%;
  --ring: 185 100% 50%;
  --card: 230 35% 9%;
  --card-foreground: 210 40% 98%;
  --card-border: 230 30% 15%;
  --popover: 230 35% 9%;
  --popover-foreground: 210 40% 98%;
  --popover-border: 230 30% 15%;
  --primary: 185 100% 50%;
  --primary-foreground: 230 40% 6%;
  --secondary: 230 30% 15%;
  --secondary-foreground: 210 40% 98%;
  --muted: 230 30% 15%;
  --muted-foreground: 215 20% 65%;
  --accent: 185 100% 50%;
  --accent-foreground: 230 40% 6%;
  --destructive: 0 84% 60%;
  --destructive-foreground: 210 40% 98%;
  --radius: 0.5rem;
}
.dark {
  --background: 230 40% 6%;
  --foreground: 210 40% 98%;
  --border: 230 30% 15%;
  --input: 230 30% 15%;
  --ring: 185 100% 50%;
  --card: 230 35% 9%;
  --card-foreground: 210 40% 98%;
  --card-border: 230 30% 15%;
  --popover: 230 35% 9%;
  --popover-foreground: 210 40% 98%;
  --popover-border: 230 30% 15%;
  --primary: 185 100% 50%;
  --primary-foreground: 230 40% 6%;
  --secondary: 230 30% 15%;
  --secondary-foreground: 210 40% 98%;
  --muted: 230 30% 15%;
  --muted-foreground: 215 20% 65%;
  --accent: 185 100% 50%;
  --accent-foreground: 230 40% 6%;
  --destructive: 0 84% 60%;
  --destructive-foreground: 210 40% 98%;
}
@layer base {
  * {
    border-color: hsl(var(--border));
  }
  body {
    background-color: hsl(var(--background));
    font-family: 'Plus Jakarta Sans', sans-serif;
    color: hsl(var(--foreground));
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
  h1, h2, h3, h4, h5, h6 {
    font-family: var(--font-display);
  }
}
html {
  scroll-behavior: smooth;
}
.card-3d {
  transform-style: preserve-3d;
  will-change: transform;
}
.perspective-1000 {
  perspective: 1000px;
}
.perspective-1200 {
  perspective: 1200px;
}
* {
  -webkit-font-smoothing: antialiased;
}
@property --tw-translate-x {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-translate-y {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-translate-z {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-rotate-x {
  syntax: "*";
  inherits: false;
}
@property --tw-rotate-y {
  syntax: "*";
  inherits: false;
}
@property --tw-rotate-z {
  syntax: "*";
  inherits: false;
}
@property --tw-skew-x {
  syntax: "*";
  inherits: false;
}
@property --tw-skew-y {
  syntax: "*";
  inherits: false;
}
@property --tw-space-y-reverse {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-space-x-reverse {
  syntax: "*";
  inherits: false;
  initial-value: 0;
}
@property --tw-border-style {
  syntax: "*";
  inherits: false;
  initial-value: solid;
}
@property --tw-gradient-position {
  syntax: "*";
  inherits: false;
}
@property --tw-gradient-from {
  syntax: "<color>";
  inherits: false;
  initial-value: #0000;
}
@property --tw-gradient-via {
  syntax: "<color>";
  inherits: false;
  initial-value: #0000;
}
@property --tw-gradient-to {
  syntax: "<color>";
  inherits: false;
  initial-value: #0000;
}
@property --tw-gradient-stops {
  syntax: "*";
  inherits: false;
}
@property --tw-gradient-via-stops {
  syntax: "*";
  inherits: false;
}
@property --tw-gradient-from-position {
  syntax: "<length-percentage>";
  inherits: false;
  initial-value: 0%;
}
@property --tw-gradient-via-position {
  syntax: "<length-percentage>";
  inherits: false;
  initial-value: 50%;
}
@property --tw-gradient-to-position {
  syntax: "<length-percentage>";
  inherits: false;
  initial-value: 100%;
}
@property --tw-leading {
  syntax: "*";
  inherits: false;
}
@property --tw-font-weight {
  syntax: "*";
  inherits: false;
}
@property --tw-tracking {
  syntax: "*";
  inherits: false;
}
@property --tw-ordinal {
  syntax: "*";
  inherits: false;
}
@property --tw-slashed-zero {
  syntax: "*";
  inherits: false;
}
@property --tw-numeric-figure {
  syntax: "*";
  inherits: false;
}
@property --tw-numeric-spacing {
  syntax: "*";
  inherits: false;
}
@property --tw-numeric-fraction {
  syntax: "*";
  inherits: false;
}
@property --tw-shadow {
  syntax: "*";
  inherits: false;
  initial-value: 0 0 #0000;
}
@property --tw-shadow-color {
  syntax: "*";
  inherits: false;
}
@property --tw-shadow-alpha {
  syntax: "<percentage>";
  inherits: false;
  initial-value: 100%;
}
@property --tw-inset-shadow {
  syntax: "*";
  inherits: false;
  initial-value: 0 0 #0000;
}
@property --tw-inset-shadow-color {
  syntax: "*";
  inherits: false;
}
@property --tw-inset-shadow-alpha {
  syntax: "<percentage>";
  inherits: false;
  initial-value: 100%;
}
@property --tw-ring-color {
  syntax: "*";
  inherits: false;
}
@property --tw-ring-shadow {
  syntax: "*";
  inherits: false;
  initial-value: 0 0 #0000;
}
@property --tw-inset-ring-color {
  syntax: "*";
  inherits: false;
}
@property --tw-inset-ring-shadow {
  syntax: "*";
  inherits: false;
  initial-value: 0 0 #0000;
}
@property --tw-ring-inset {
  syntax: "*";
  inherits: false;
}
@property --tw-ring-offset-width {
  syntax: "<length>";
  inherits: false;
  initial-value: 0px;
}
@property --tw-ring-offset-color {
  syntax: "*";
  inherits: false;
  initial-value: #fff;
}
@property --tw-ring-offset-shadow {
  syntax: "*";
  inherits: false;
  initial-value: 0 0 #0000;
}
@property --tw-outline-style {
  syntax: "*";
  inherits: false;
  initial-value: solid;
}
@property --tw-blur {
  syntax: "*";
  inherits: false;
}
@property --tw-brightness {
  syntax: "*";
  inherits: false;
}
@property --tw-contrast {
  syntax: "*";
  inherits: false;
}
@property --tw-grayscale {
  syntax: "*";
  inherits: false;
}
@property --tw-hue-rotate {
  syntax: "*";
  inherits: false;
}
@property --tw-invert {
  syntax: "*";
  inherits: false;
}
@property --tw-opacity {
  syntax: "*";
  inherits: false;
}
@property --tw-saturate {
  syntax: "*";
  inherits: false;
}
@property --tw-sepia {
  syntax: "*";
  inherits: false;
}
@property --tw-drop-shadow {
  syntax: "*";
  inherits: false;
}
@property --tw-drop-shadow-color {
  syntax: "*";
  inherits: false;
}
@property --tw-drop-shadow-alpha {
  syntax: "<percentage>";
  inherits: false;
  initial-value: 100%;
}
@property --tw-drop-shadow-size {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-blur {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-brightness {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-contrast {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-grayscale {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-hue-rotate {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-invert {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-opacity {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-saturate {
  syntax: "*";
  inherits: false;
}
@property --tw-backdrop-sepia {
  syntax: "*";
  inherits: false;
}
@property --tw-duration {
  syntax: "*";
  inherits: false;
}
@property --tw-ease {
  syntax: "*";
  inherits: false;
}
@property --tw-scale-x {
  syntax: "*";
  inherits: false;
  initial-value: 1;
}
@property --tw-scale-y {
  syntax: "*";
  inherits: false;
  initial-value: 1;
}
@property --tw-scale-z {
  syntax: "*";
  inherits: false;
  initial-value: 1;
}
@property --tw-content {
  syntax: "*";
  initial-value: "";
  inherits: false;
}
@keyframes spin {
  to {
    transform: rotate(360deg);
  }
}
@keyframes pulse {
  50% {
    opacity: 0.5;
  }
}
@keyframes enter {
  from {
    opacity: var(--tw-enter-opacity,1);
    transform: translate3d(var(--tw-enter-translate-x,0),var(--tw-enter-translate-y,0),0)scale3d(var(--tw-enter-scale,1),var(--tw-enter-scale,1),var(--tw-enter-scale,1))rotate(var(--tw-enter-rotate,0));
    filter: blur(var(--tw-enter-blur,0));
  }
}
@keyframes exit {
  to {
    opacity: var(--tw-exit-opacity,1);
    transform: translate3d(var(--tw-exit-translate-x,0),var(--tw-exit-translate-y,0),0)scale3d(var(--tw-exit-scale,1),var(--tw-exit-scale,1),var(--tw-exit-scale,1))rotate(var(--tw-exit-rotate,0));
    filter: blur(var(--tw-exit-blur,0));
  }
}
@keyframes accordion-down {
  from {
    height: 0;
  }
  to {
    height: var(--radix-accordion-content-height,var(--bits-accordion-content-height,var(--reka-accordion-content-height,var(--kb-accordion-content-height,var(--ngp-accordion-content-height,auto)))));
  }
}
@keyframes accordion-up {
  from {
    height: var(--radix-accordion-content-height,var(--bits-accordion-content-height,var(--reka-accordion-content-height,var(--kb-accordion-content-height,var(--ngp-accordion-content-height,auto)))));
  }
  to {
    height: 0;
  }
}
@keyframes caret-blink {
  0%,70%,100% {
    opacity: 1;
  }
  20%,50% {
    opacity: 0;
  }
}
@layer properties {
  @supports ((-webkit-hyphens: none) and (not (margin-trim: inline))) or ((-moz-orient: inline) and (not (color:rgb(from red r g b)))) {
    *, ::before, ::after, ::backdrop {
      --tw-translate-x: 0;
      --tw-translate-y: 0;
      --tw-translate-z: 0;
      --tw-rotate-x: initial;
      --tw-rotate-y: initial;
      --tw-rotate-z: initial;
      --tw-skew-x: initial;
      --tw-skew-y: initial;
      --tw-space-y-reverse: 0;
      --tw-space-x-reverse: 0;
      --tw-border-style: solid;
      --tw-gradient-position: initial;
      --tw-gradient-from: #0000;
      --tw-gradient-via: #0000;
      --tw-gradient-to: #0000;
      --tw-gradient-stops: initial;
      --tw-gradient-via-stops: initial;
      --tw-gradient-from-position: 0%;
      --tw-gradient-via-position: 50%;
      --tw-gradient-to-position: 100%;
      --tw-leading: initial;
      --tw-font-weight: initial;
      --tw-tracking: initial;
      --tw-ordinal: initial;
      --tw-slashed-zero: initial;
      --tw-numeric-figure: initial;
      --tw-numeric-spacing: initial;
      --tw-numeric-fraction: initial;
      --tw-shadow: 0 0 #0000;
      --tw-shadow-color: initial;
      --tw-shadow-alpha: 100%;
      --tw-inset-shadow: 0 0 #0000;
      --tw-inset-shadow-color: initial;
      --tw-inset-shadow-alpha: 100%;
      --tw-ring-color: initial;
      --tw-ring-shadow: 0 0 #0000;
      --tw-inset-ring-color: initial;
      --tw-inset-ring-shadow: 0 0 #0000;
      --tw-ring-inset: initial;
      --tw-ring-offset-width: 0px;
      --tw-ring-offset-color: #fff;
      --tw-ring-offset-shadow: 0 0 #0000;
      --tw-outline-style: solid;
      --tw-blur: initial;
      --tw-brightness: initial;
      --tw-contrast: initial;
      --tw-grayscale: initial;
      --tw-hue-rotate: initial;
      --tw-invert: initial;
      --tw-opacity: initial;
      --tw-saturate: initial;
      --tw-sepia: initial;
      --tw-drop-shadow: initial;
      --tw-drop-shadow-color: initial;
      --tw-drop-shadow-alpha: 100%;
      --tw-drop-shadow-size: initial;
      --tw-backdrop-blur: initial;
      --tw-backdrop-brightness: initial;
      --tw-backdrop-contrast: initial;
      --tw-backdrop-grayscale: initial;
      --tw-backdrop-hue-rotate: initial;
      --tw-backdrop-invert: initial;
      --tw-backdrop-opacity: initial;
      --tw-backdrop-saturate: initial;
      --tw-backdrop-sepia: initial;
      --tw-duration: initial;
      --tw-ease: initial;
      --tw-scale-x: 1;
      --tw-scale-y: 1;
      --tw-scale-z: 1;
      --tw-content: "";
      --tw-animation-delay: 0s;
      --tw-animation-direction: normal;
      --tw-animation-duration: initial;
      --tw-animation-fill-mode: none;
      --tw-animation-iteration-count: 1;
      --tw-enter-blur: 0;
      --tw-enter-opacity: 1;
      --tw-enter-rotate: 0;
      --tw-enter-scale: 1;
      --tw-enter-translate-x: 0;
      --tw-enter-translate-y: 0;
      --tw-exit-blur: 0;
      --tw-exit-opacity: 1;
      --tw-exit-rotate: 0;
      --tw-exit-scale: 1;
      --tw-exit-translate-x: 0;
      --tw-exit-translate-y: 0;
    }
  }
}
</style></head>
  <body style="padding-top: 45px;">
    <div id="root"><div data-replit-metadata="artifacts/team-kalam/src/App.tsx:13:4" data-component-name="div" class="min-h-screen bg-background text-foreground selection:bg-primary/30 font-sans"><nav data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:28:4" data-component-name="motion.nav" class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 bg-background/80 backdrop-blur-md border-b border-border shadow-sm shadow-primary/5" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:38:6" data-component-name="div" class="container mx-auto px-6 h-20 flex items-center justify-between" style="perspective: 1000px;"><a data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:39:8" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#" class="flex items-center gap-3 group card-3d" data-testid="nav-logo" style="transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:46:10" data-component-name="div" class="w-10 h-10 rounded-lg bg-primary/10 border border-primary/30 flex items-center justify-center group-hover:bg-primary/20 transition-colors"><span data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:47:12" data-component-name="span" class="text-primary font-bold text-lg leading-none tracking-tighter">T<br data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:48:15" data-component-name="br">K</span></div><span data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:51:10" data-component-name="span" class="font-display font-bold text-xl tracking-tight hidden sm:block">TEAM <span data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:52:17" data-component-name="span" class="text-primary">KALAM</span></span></a><div data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:57:8" data-component-name="div" class="hidden md:flex items-center gap-8"><a data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:59:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#" data-testid="nav-link-home" class="text-sm font-medium text-muted-foreground hover:text-primary transition-colors card-3d">Home</a><a data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:59:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#about" data-testid="nav-link-about" class="text-sm font-medium text-muted-foreground hover:text-primary transition-colors card-3d">About</a><a data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:59:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#project" data-testid="nav-link-project" class="text-sm font-medium text-muted-foreground hover:text-primary transition-colors card-3d">Project</a><a data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:59:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#violation" data-testid="nav-link-enforcement" class="text-sm font-medium text-muted-foreground hover:text-primary transition-colors card-3d">Enforcement</a><a data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:59:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#how-it-works" data-testid="nav-link-how-it-works" class="text-sm font-medium text-muted-foreground hover:text-primary transition-colors card-3d">How It Works</a><a data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:59:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#tech" data-testid="nav-link-tech" class="text-sm font-medium text-muted-foreground hover:text-primary transition-colors card-3d">Tech</a><a data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:59:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#team" data-testid="nav-link-team" class="text-sm font-medium text-muted-foreground hover:text-primary transition-colors card-3d">Team</a></div><button data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:73:8" data-component-name="button" class="md:hidden p-2 text-foreground" data-testid="mobile-menu-toggle"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-menu" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Navbar.tsx:78:38" data-component-name="Menu"><path d="M4 5h16"></path><path d="M4 12h16"></path><path d="M4 19h16"></path></svg></button></div></nav><main data-replit-metadata="artifacts/team-kalam/src/App.tsx:15:6" data-component-name="main"><section data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:35:4" data-component-name="section" class="relative min-h-screen flex items-center justify-center pt-20 overflow-hidden"><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:36:6" data-component-name="div" class="absolute inset-0 z-0 pointer-events-none opacity-20" style="background-image: radial-gradient(circle at center, var(--color-primary) 1px, transparent 1px); background-size: 40px 40px;"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:44:6" data-component-name="motion.div" class="absolute top-1/4 right-1/4 w-[600px] h-[600px] bg-primary/20 rounded-full blur-[120px] pointer-events-none" style="transform: scale(1.04861);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:49:6" data-component-name="motion.div" class="absolute bottom-1/4 left-1/4 w-[500px] h-[500px] bg-blue-500/20 rounded-full blur-[100px] pointer-events-none" style="transform: scale(1.25354);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:55:6" data-component-name="div" class="container relative z-10 mx-auto px-6 flex flex-col items-center text-center" style="perspective: 1200px;"><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:56:8" data-component-name="motion.div" class="flex flex-col items-center w-full" style="transform-style: preserve-3d; opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:63:10" data-component-name="motion.div" class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-secondary border border-primary/30 mb-8 shadow-[0_0_20px_rgba(0,255,255,0.1)]" style="opacity: 1; transform: none;"><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:69:12" data-component-name="span" class="w-2 h-2 rounded-full bg-primary animate-pulse shadow-[0_0_10px_var(--color-primary)]"></span><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:70:12" data-component-name="span" class="text-sm font-medium tracking-wide text-primary-foreground/90">Smart Cities Domain — Robotics Competition</span></div><h1 data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:73:10" data-component-name="motion.h1" class="text-6xl md:text-8xl lg:text-9xl font-display font-bold tracking-tighter mb-4" style="opacity: 1; transform: none;">TEAM <span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:80:12" data-component-name="span" class="text-transparent bg-clip-text bg-gradient-to-r from-primary via-blue-400 to-purple-500 animate-gradient-x drop-shadow-[0_0_20px_rgba(0,255,255,0.4)] pb-2 inline-block">KALAM</span></h1><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:85:10" data-component-name="motion.div" style="opacity: 1; transform: none;"><h2 data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:90:12" data-component-name="h2" class="text-2xl md:text-4xl font-bold text-foreground/90 mb-6 font-display">Adaptive Traffic Management</h2><p data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:93:12" data-component-name="p" class="text-lg md:text-2xl text-muted-foreground max-w-3xl mx-auto mb-10 leading-relaxed">Engineering tomorrow's cities. One signal at a time.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:98:10" data-component-name="motion.div" class="flex flex-col sm:flex-row gap-4 w-full sm:w-auto mb-16" style="opacity: 1; transform: none;"><a data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:104:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#project" data-testid="hero-project-link" class="card-3d group relative inline-flex items-center justify-center gap-2 px-8 py-4 bg-primary text-primary-foreground font-bold rounded-lg overflow-hidden shadow-[0_0_30px_rgba(0,255,255,0.3)] hover:shadow-[0_0_50px_rgba(0,255,255,0.5)]" style="transform: none;"><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:111:14" data-component-name="span" class="absolute inset-0 w-full h-full bg-white/20 translate-y-full group-hover:translate-y-0 transition-transform duration-300 ease-out"></span><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:112:14" data-component-name="span" class="relative flex items-center gap-2">Explore Project <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-arrow-right w-5 h-5 group-hover:translate-x-1 transition-transform" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:113:32" data-component-name="ArrowRight"><path d="M5 12h14"></path><path d="m12 5 7 7-7 7"></path></svg></span></a><a data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:116:12" data-component-name="motion.a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#team" data-testid="hero-team-link" class="card-3d group inline-flex items-center justify-center gap-2 px-8 py-4 bg-transparent border-2 border-primary/50 text-foreground font-bold rounded-lg hover:border-primary hover:bg-primary/10">Meet the Team</a></div><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:127:10" data-component-name="motion.div" class="grid grid-cols-3 gap-4 md:gap-12 w-full max-w-4xl border-t border-border pt-8" style="opacity: 1;"><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:133:12" data-component-name="motion.div" class="flex flex-col items-center card-3d"><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:138:14" data-component-name="span" class="text-4xl md:text-5xl font-bold font-display text-primary mb-2"><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:30:9" data-component-name="span">5</span></span><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:141:14" data-component-name="span" class="text-sm md:text-base text-muted-foreground uppercase tracking-wider font-medium">Members</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:143:12" data-component-name="motion.div" class="flex flex-col items-center border-l border-r border-border px-4 md:px-0 card-3d"><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:148:14" data-component-name="span" class="text-4xl md:text-5xl font-bold font-display text-primary mb-2"><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:30:9" data-component-name="span">1</span></span><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:151:14" data-component-name="span" class="text-sm md:text-base text-muted-foreground uppercase tracking-wider font-medium text-center">Flagship Project</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:153:12" data-component-name="motion.div" class="flex flex-col items-center card-3d"><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:158:14" data-component-name="span" class="text-4xl md:text-5xl font-bold font-display text-primary mb-2"><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:30:9" data-component-name="span">2026</span></span><span data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:161:14" data-component-name="span" class="text-sm md:text-base text-muted-foreground uppercase tracking-wider font-medium text-center">Active Year</span></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:165:10" data-component-name="motion.div" class="absolute bottom-8 left-1/2 -translate-x-1/2 text-muted-foreground hover:text-primary transition-colors cursor-pointer" style="transform: translateY(7.21112px);"><a data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:170:12" data-component-name="a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#about"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-chevron-down w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:170:29" data-component-name="ChevronDown"><path d="m6 9 6 6 6-6"></path></svg></a></div></div></div><svg data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:175:6" data-component-name="svg" class="absolute w-0 h-0"><defs data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:176:8" data-component-name="defs"><lineargradient data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:177:10" data-component-name="linearGradient" id="circuit-grad" x1="0%" y1="0%" x2="100%" y2="100%"><stop data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:178:12" data-component-name="stop" offset="0%" stop-color="var(--color-primary)" stop-opacity="0.2"></stop><stop data-replit-metadata="artifacts/team-kalam/src/components/Hero.tsx:179:12" data-component-name="stop" offset="100%" stop-color="transparent" stop-opacity="0"></stop></lineargradient></defs></svg></section><section data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:6:4" data-component-name="motion.section" id="about" class="py-32 relative bg-background" style="perspective: 1000px; opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:15:6" data-component-name="div" class="container mx-auto px-6"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:17:8" data-component-name="div" class="flex flex-col items-center mb-16"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:18:10" data-component-name="motion.div" class="inline-block px-4 py-1.5 rounded-full bg-primary/10 border border-primary/20 text-primary text-sm font-semibold tracking-wider uppercase mb-6">About Us</div></div><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:25:8" data-component-name="div" class="grid lg:grid-cols-2 gap-16 items-center mb-24 max-w-7xl mx-auto"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:27:10" data-component-name="div" class="space-y-6 text-lg md:text-xl text-muted-foreground leading-relaxed"><h2 data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:28:12" data-component-name="h2" class="text-4xl md:text-5xl font-display font-bold text-foreground mb-8">Pioneering <span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:29:25" data-component-name="span" class="text-primary">Smart Cities</span></h2><p data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:31:12" data-component-name="p">We are a passionate collective of student engineers, designers, and researchers united by a single goal: making urban spaces more livable, efficient, and sustainable.</p><p data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:34:12" data-component-name="p">Urban congestion isn't just a daily annoyance—it's an economic and environmental crisis. Traditional static traffic lights are blind to the reality of the roads they govern. We decided to change that.</p><p data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:37:12" data-component-name="p">Team Kalam approaches problems from the intersection of hardware and software, bringing intelligence to infrastructure that has remained unchanged for decades.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:43:10" data-component-name="div" class="grid grid-cols-2 gap-4"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:50:14" data-component-name="motion.div" class="bg-card border border-border p-8 rounded-2xl flex flex-col justify-center items-center text-center shadow-lg hover:border-primary/50 transition-colors group card-3d"><span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:56:16" data-component-name="span" class="text-4xl md:text-5xl font-display font-bold text-foreground group-hover:text-primary transition-colors mb-2">5</span><span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:57:16" data-component-name="span" class="text-sm text-muted-foreground font-medium uppercase tracking-wider">Core Members</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:50:14" data-component-name="motion.div" class="bg-card border border-border p-8 rounded-2xl flex flex-col justify-center items-center text-center shadow-lg hover:border-primary/50 transition-colors group card-3d"><span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:56:16" data-component-name="span" class="text-4xl md:text-5xl font-display font-bold text-foreground group-hover:text-primary transition-colors mb-2">1</span><span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:57:16" data-component-name="span" class="text-sm text-muted-foreground font-medium uppercase tracking-wider">Raspberry Pi at its Core</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:50:14" data-component-name="motion.div" class="bg-card border border-border p-8 rounded-2xl flex flex-col justify-center items-center text-center shadow-lg hover:border-primary/50 transition-colors group card-3d"><span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:56:16" data-component-name="span" class="text-4xl md:text-5xl font-display font-bold text-foreground group-hover:text-primary transition-colors mb-2">2026</span><span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:57:16" data-component-name="span" class="text-sm text-muted-foreground font-medium uppercase tracking-wider">Active Year</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:50:14" data-component-name="motion.div" class="bg-card border border-border p-8 rounded-2xl flex flex-col justify-center items-center text-center shadow-lg hover:border-primary/50 transition-colors group card-3d" style="transform: none;"><span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:56:16" data-component-name="span" class="text-4xl md:text-5xl font-display font-bold text-foreground group-hover:text-primary transition-colors mb-2">Smart</span><span data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:57:16" data-component-name="span" class="text-sm text-muted-foreground font-medium uppercase tracking-wider">Cities Domain</span></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:64:8" data-component-name="div" class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:70:12" data-component-name="motion.div" class="bg-secondary/50 border border-border p-8 rounded-2xl transition-transform duration-300 card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:78:14" data-component-name="div" class="w-14 h-14 bg-primary/10 rounded-xl flex items-center justify-center text-primary mb-6"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-lightbulb w-7 h-7" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:79:16" data-component-name="pillar.icon"><path d="M15 14c.2-1 .7-1.7 1.5-2.5 1-.9 1.5-2.2 1.5-3.5A6 6 0 0 0 6 8c0 1 .2 2.2 1.5 3.5.7.7 1.3 1.5 1.5 2.5"></path><path d="M9 18h6"></path><path d="M10 22h4"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:81:14" data-component-name="h3" class="text-2xl font-display font-bold mb-3">Innovation</h3><p data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:82:14" data-component-name="p" class="text-muted-foreground">Pushing boundaries with cutting-edge edge computing.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:70:12" data-component-name="motion.div" class="bg-secondary/50 border border-border p-8 rounded-2xl transition-transform duration-300 card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:78:14" data-component-name="div" class="w-14 h-14 bg-primary/10 rounded-xl flex items-center justify-center text-primary mb-6"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-users w-7 h-7" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:79:16" data-component-name="pillar.icon"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2"></path><path d="M16 3.128a4 4 0 0 1 0 7.744"></path><path d="M22 21v-2a4 4 0 0 0-3-3.87"></path><circle cx="9" cy="7" r="4"></circle></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:81:14" data-component-name="h3" class="text-2xl font-display font-bold mb-3">Collaboration</h3><p data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:82:14" data-component-name="p" class="text-muted-foreground">Interdisciplinary teamwork driving holistic solutions.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:70:12" data-component-name="motion.div" class="bg-secondary/50 border border-border p-8 rounded-2xl transition-transform duration-300 card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:78:14" data-component-name="div" class="w-14 h-14 bg-primary/10 rounded-xl flex items-center justify-center text-primary mb-6"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-target w-7 h-7" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:79:16" data-component-name="pillar.icon"><circle cx="12" cy="12" r="10"></circle><circle cx="12" cy="12" r="6"></circle><circle cx="12" cy="12" r="2"></circle></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:81:14" data-component-name="h3" class="text-2xl font-display font-bold mb-3">Impact</h3><p data-replit-metadata="artifacts/team-kalam/src/components/About.tsx:82:14" data-component-name="p" class="text-muted-foreground">Measurable improvements in daily urban mobility.</p></div></div></div></section><section data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:39:4" data-component-name="section" id="project" class="py-32 bg-card/30 relative border-y border-border overflow-hidden"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:41:6" data-component-name="div" class="absolute top-0 left-0 w-full h-[1px] bg-gradient-to-r from-transparent via-primary/50 to-transparent"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:43:6" data-component-name="div" class="container mx-auto px-6"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:45:8" data-component-name="div" class="flex flex-col items-center text-center mb-16"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:46:10" data-component-name="motion.div" class="inline-block px-4 py-1.5 rounded-full bg-primary/10 border border-primary/20 text-primary text-sm font-semibold tracking-wider uppercase mb-6" style="opacity: 1; transform: none;">Our Project</div><h2 data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:54:10" data-component-name="motion.h2" class="text-4xl md:text-6xl font-display font-bold mb-6" style="opacity: 1; transform: none;">Adaptive Traffic Management</h2><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:63:10" data-component-name="motion.p" class="text-xl text-muted-foreground max-w-3xl mx-auto" style="opacity: 1; transform: none;">Our flagship solution replaces rigid timers with responsive intelligence.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:75:8" data-component-name="motion.div" class="max-w-5xl mx-auto mb-24 relative rounded-3xl overflow-hidden card-3d" style="perspective: 1000px; opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:83:10" data-component-name="div" class="absolute inset-0 bg-gradient-to-r from-secondary to-background border border-border rounded-3xl"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:84:10" data-component-name="div" class="absolute top-0 right-0 w-[300px] h-[300px] bg-destructive/10 rounded-full blur-[80px]"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:85:10" data-component-name="div" class="absolute bottom-0 left-0 w-[300px] h-[300px] bg-primary/10 rounded-full blur-[80px]"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:87:10" data-component-name="div" class="relative z-10 p-8 md:p-12 flex flex-col md:flex-row gap-8 items-center"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:88:12" data-component-name="div" class="flex-1 space-y-4"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:89:14" data-component-name="div" class="text-sm font-bold text-destructive uppercase tracking-wider">The Problem</div><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:90:14" data-component-name="p" class="text-lg md:text-xl text-foreground/80 leading-relaxed font-medium">Traditional traffic lights use fixed timers regardless of actual traffic density. The result: gridlock, wasted fuel, increased emissions.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:94:12" data-component-name="div" class="hidden md:block w-px h-24 bg-border"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:95:12" data-component-name="div" class="flex-1 space-y-4"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:96:14" data-component-name="div" class="text-sm font-bold text-primary uppercase tracking-wider">Our Solution</div><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:97:14" data-component-name="p" class="text-lg md:text-xl text-foreground leading-relaxed font-bold">Real-time density sensing + adaptive timing = <span data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:98:62" data-component-name="span" class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-blue-400">up to 40% congestion reduction.</span></p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:105:8" data-component-name="div" class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto" style="perspective: 1200px;"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:107:12" data-component-name="motion.div" class="p-10 rounded-3xl bg-background border border-border hover:border-primary/50 transition-all duration-300 group relative overflow-hidden card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:116:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-primary/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:117:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-camera w-8 h-8 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:118:16" data-component-name="feature.icon"><path d="M13.997 4a2 2 0 0 1 1.76 1.05l.486.9A2 2 0 0 0 18.003 7H20a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h1.997a2 2 0 0 0 1.759-1.048l.489-.904A2 2 0 0 1 10.004 4z"></path><circle cx="12" cy="13" r="3"></circle></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:120:14" data-component-name="h3" class="text-2xl font-display font-bold mb-4">Density Monitoring</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:121:14" data-component-name="p" class="text-lg text-muted-foreground leading-relaxed">Real-time intersection analysis using advanced computer vision to calculate precise vehicle density across all lanes.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:107:12" data-component-name="motion.div" class="p-10 rounded-3xl bg-background border border-border hover:border-primary/50 transition-all duration-300 group relative overflow-hidden card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:116:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-primary/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:117:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-activity w-8 h-8 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:118:16" data-component-name="feature.icon"><path d="M22 12h-2.48a2 2 0 0 0-1.93 1.46l-2.35 8.36a.25.25 0 0 1-.48 0L9.24 2.18a.25.25 0 0 0-.48 0l-2.35 8.36A2 2 0 0 1 4.49 12H2"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:120:14" data-component-name="h3" class="text-2xl font-display font-bold mb-4">Dynamic Timing</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:121:14" data-component-name="p" class="text-lg text-muted-foreground leading-relaxed">Algorithms that adjust signal phases on the fly, prioritizing heavily congested routes to ensure smooth flow.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:107:12" data-component-name="motion.div" class="p-10 rounded-3xl bg-background border border-border hover:border-primary/50 transition-all duration-300 group relative overflow-hidden card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:116:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-primary/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:117:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-server w-8 h-8 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:118:16" data-component-name="feature.icon"><rect width="20" height="8" x="2" y="2" rx="2" ry="2"></rect><rect width="20" height="8" x="2" y="14" rx="2" ry="2"></rect><line x1="6" x2="6.01" y1="6" y2="6"></line><line x1="6" x2="6.01" y1="18" y2="18"></line></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:120:14" data-component-name="h3" class="text-2xl font-display font-bold mb-4">Edge Computing</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:121:14" data-component-name="p" class="text-lg text-muted-foreground leading-relaxed">Powered by localized Raspberry Pi units, ensuring ultra-low latency processing without relying on cloud infrastructure.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:107:12" data-component-name="motion.div" class="p-10 rounded-3xl bg-background border border-border hover:border-primary/50 transition-all duration-300 group relative overflow-hidden card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:116:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-primary/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:117:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-code-xml w-8 h-8 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:118:16" data-component-name="feature.icon"><path d="m18 16 4-4-4-4"></path><path d="m6 8-4 4 4 4"></path><path d="m14.5 4-5 16"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:120:14" data-component-name="h3" class="text-2xl font-display font-bold mb-4">Custom Stack</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:121:14" data-component-name="p" class="text-lg text-muted-foreground leading-relaxed">Proprietary software architecture built from the ground up for maximum reliability in critical traffic scenarios.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:107:12" data-component-name="motion.div" class="p-10 rounded-3xl bg-background border border-border hover:border-primary/50 transition-all duration-300 group relative overflow-hidden card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:116:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-primary/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:117:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-scan-line w-8 h-8 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:118:16" data-component-name="feature.icon"><path d="M3 7V5a2 2 0 0 1 2-2h2"></path><path d="M17 3h2a2 2 0 0 1 2 2v2"></path><path d="M21 17v2a2 2 0 0 1-2 2h-2"></path><path d="M7 21H5a2 2 0 0 1-2-2v-2"></path><path d="M7 12h10"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:120:14" data-component-name="h3" class="text-2xl font-display font-bold mb-4">Violation Detection</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:121:14" data-component-name="p" class="text-lg text-muted-foreground leading-relaxed">Computer vision tracks vehicle trajectories to detect illegal lane changes, red-light jumping, and signal non-compliance in real-time.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:107:12" data-component-name="motion.div" class="p-10 rounded-3xl bg-background border border-border hover:border-primary/50 transition-all duration-300 group relative overflow-hidden card-3d" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:116:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-primary/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:117:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-8 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-shield-alert w-8 h-8 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:118:16" data-component-name="feature.icon"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z"></path><path d="M12 8v4"></path><path d="M12 16h.01"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:120:14" data-component-name="h3" class="text-2xl font-display font-bold mb-4">Auto e-Challan</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Project.tsx:121:14" data-component-name="p" class="text-lg text-muted-foreground leading-relaxed">When a violation is confirmed, the system captures the offender's plate and automatically generates a digital challan — zero human intervention.</p></div></div></div></section><section data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:51:4" data-component-name="section" id="violation" class="py-32 relative bg-card/30 border-y border-border overflow-hidden"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:53:6" data-component-name="div" class="absolute top-0 left-0 w-full h-[1px] bg-gradient-to-r from-transparent via-red-500/40 to-transparent"></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:54:6" data-component-name="motion.div" class="absolute top-1/2 right-0 -translate-y-1/2 w-[500px] h-[500px] bg-red-500/10 rounded-full blur-[120px] pointer-events-none" style="transform: scale(1.01602);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:59:6" data-component-name="motion.div" class="absolute top-1/4 left-0 w-[400px] h-[400px] bg-primary/10 rounded-full blur-[100px] pointer-events-none" style="transform: scale(1.18493);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:65:6" data-component-name="div" class="container mx-auto px-6"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:68:8" data-component-name="div" class="flex flex-col items-center text-center mb-20"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:69:10" data-component-name="motion.div" class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-red-500/10 border border-red-500/30 text-red-400 text-sm font-semibold tracking-wider uppercase mb-6" style="opacity: 1; transform: none;"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-shield-alert w-4 h-4" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:75:12" data-component-name="ShieldAlert"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z"></path><path d="M12 8v4"></path><path d="M12 16h.01"></path></svg>Enforcement Module</div><h2 data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:78:10" data-component-name="motion.h2" class="text-4xl md:text-6xl font-display font-bold mb-6" style="opacity: 1; transform: none;">Traffic Violation <span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:86:12" data-component-name="span" class="text-transparent bg-clip-text bg-gradient-to-r from-red-400 via-orange-400 to-primary">Detection</span></h2><p data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:90:10" data-component-name="motion.p" class="text-xl text-muted-foreground max-w-3xl mx-auto" style="opacity: 1; transform: none;">Beyond managing flow — our system actively watches for violations, identifies offenders using computer vision, and automatically issues challans without human intervention.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:102:8" data-component-name="div" class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto mb-24" style="perspective: 1000px;"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:104:12" data-component-name="motion.div" data-testid="violation-capability-0" class="card-3d p-8 rounded-3xl bg-background border border-border hover:border-red-500/40 hover:-translate-y-2 hover:shadow-[0_10px_30px_-10px_rgba(239,68,68,0.2)] transition-all duration-300 group relative overflow-hidden" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:114:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-red-500/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:115:14" data-component-name="div" class="w-14 h-14 rounded-2xl bg-red-500/10 border border-red-500/20 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-camera w-7 h-7 text-red-400" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:116:16" data-component-name="cap.icon"><path d="M13.997 4a2 2 0 0 1 1.76 1.05l.486.9A2 2 0 0 0 18.003 7H20a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h1.997a2 2 0 0 0 1.759-1.048l.489-.904A2 2 0 0 1 10.004 4z"></path><circle cx="12" cy="13" r="3"></circle></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:118:14" data-component-name="h3" class="text-xl font-display font-bold mb-3">Live Camera Feed</h3><p data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:119:14" data-component-name="p" class="text-muted-foreground leading-relaxed">Continuous video stream from Raspberry Pi-mounted cameras monitors every lane and vehicle movement at the intersection.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:104:12" data-component-name="motion.div" data-testid="violation-capability-1" class="card-3d p-8 rounded-3xl bg-background border border-border hover:border-red-500/40 hover:-translate-y-2 hover:shadow-[0_10px_30px_-10px_rgba(239,68,68,0.2)] transition-all duration-300 group relative overflow-hidden" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:114:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-red-500/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:115:14" data-component-name="div" class="w-14 h-14 rounded-2xl bg-red-500/10 border border-red-500/20 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-scan-line w-7 h-7 text-red-400" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:116:16" data-component-name="cap.icon"><path d="M3 7V5a2 2 0 0 1 2-2h2"></path><path d="M17 3h2a2 2 0 0 1 2 2v2"></path><path d="M21 17v2a2 2 0 0 1-2 2h-2"></path><path d="M7 21H5a2 2 0 0 1-2-2v-2"></path><path d="M7 12h10"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:118:14" data-component-name="h3" class="text-xl font-display font-bold mb-3">Lane Violation Detection</h3><p data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:119:14" data-component-name="p" class="text-muted-foreground leading-relaxed">Computer vision algorithms track vehicle trajectories frame-by-frame. Illegal lane changes and line crossings are flagged instantly.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:104:12" data-component-name="motion.div" data-testid="violation-capability-2" class="card-3d p-8 rounded-3xl bg-background border border-border hover:border-red-500/40 hover:-translate-y-2 hover:shadow-[0_10px_30px_-10px_rgba(239,68,68,0.2)] transition-all duration-300 group relative overflow-hidden" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:114:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-red-500/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:115:14" data-component-name="div" class="w-14 h-14 rounded-2xl bg-red-500/10 border border-red-500/20 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-triangle-alert w-7 h-7 text-red-400" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:116:16" data-component-name="cap.icon"><path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3"></path><path d="M12 9v4"></path><path d="M12 17h.01"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:118:14" data-component-name="h3" class="text-xl font-display font-bold mb-3">Traffic Rule Enforcement</h3><p data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:119:14" data-component-name="p" class="text-muted-foreground leading-relaxed">Red-light jumping, wrong-way entry, and signal non-compliance are detected in real-time with high accuracy using OpenCV.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:104:12" data-component-name="motion.div" data-testid="violation-capability-3" class="card-3d p-8 rounded-3xl bg-background border border-border hover:border-red-500/40 hover:-translate-y-2 hover:shadow-[0_10px_30px_-10px_rgba(239,68,68,0.2)] transition-all duration-300 group relative overflow-hidden" style="opacity: 1; transform: none;"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:114:14" data-component-name="div" class="absolute inset-0 bg-gradient-to-br from-red-500/5 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300"></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:115:14" data-component-name="div" class="w-14 h-14 rounded-2xl bg-red-500/10 border border-red-500/20 flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-text w-7 h-7 text-red-400" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:116:16" data-component-name="cap.icon"><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7Z"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M10 9H8"></path><path d="M16 13H8"></path><path d="M16 17H8"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:118:14" data-component-name="h3" class="text-xl font-display font-bold mb-3">Automatic Challan Generation</h3><p data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:119:14" data-component-name="p" class="text-muted-foreground leading-relaxed">Once a violation is confirmed, the system captures the vehicle, extracts the license plate, and auto-generates an e-challan record.</p></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:125:8" data-component-name="motion.div" class="max-w-5xl mx-auto mb-24" style="opacity: 0; transform: translateY(30px);"><h3 data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:132:10" data-component-name="h3" class="text-2xl md:text-3xl font-display font-bold text-center mb-12">Automated Challan Pipeline</h3><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:135:10" data-component-name="div" class="flex flex-col md:flex-row items-center justify-between gap-4 relative" style="perspective: 1000px;"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:137:12" data-component-name="div" class="hidden md:block absolute top-1/2 left-0 right-0 h-px bg-gradient-to-r from-transparent via-primary/30 to-transparent -translate-y-1/2 z-0"></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:139:14" data-component-name="motion.div" class="relative z-10 flex flex-col items-center gap-3 flex-1 card-3d" data-testid="flow-step-0" style="opacity: 0; transform: translateX(-20px) rotateY(-20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:148:16" data-component-name="div" class="w-14 h-14 rounded-full bg-background border-2 border-primary/40 flex items-center justify-center shadow-[0_0_15px_rgba(0,255,255,0.15)] hover:shadow-[0_0_25px_rgba(0,255,255,0.3)] hover:border-primary transition-all duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-camera w-6 h-6 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:149:18" data-component-name="step.icon"><path d="M13.997 4a2 2 0 0 1 1.76 1.05l.486.9A2 2 0 0 0 18.003 7H20a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h1.997a2 2 0 0 0 1.759-1.048l.489-.904A2 2 0 0 1 10.004 4z"></path><circle cx="12" cy="13" r="3"></circle></svg></div><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:151:16" data-component-name="span" class="text-xs font-semibold text-center text-muted-foreground uppercase tracking-wide leading-tight max-w-[80px]">Camera Captures Frame</span><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:155:18" data-component-name="div" class="md:hidden w-px h-6 bg-primary/30"></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:139:14" data-component-name="motion.div" class="relative z-10 flex flex-col items-center gap-3 flex-1 card-3d" data-testid="flow-step-1" style="opacity: 0; transform: translateX(-20px) rotateY(-20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:148:16" data-component-name="div" class="w-14 h-14 rounded-full bg-background border-2 border-primary/40 flex items-center justify-center shadow-[0_0_15px_rgba(0,255,255,0.15)] hover:shadow-[0_0_25px_rgba(0,255,255,0.3)] hover:border-primary transition-all duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-scan-line w-6 h-6 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:149:18" data-component-name="step.icon"><path d="M3 7V5a2 2 0 0 1 2-2h2"></path><path d="M17 3h2a2 2 0 0 1 2 2v2"></path><path d="M21 17v2a2 2 0 0 1-2 2h-2"></path><path d="M7 21H5a2 2 0 0 1-2-2v-2"></path><path d="M7 12h10"></path></svg></div><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:151:16" data-component-name="span" class="text-xs font-semibold text-center text-muted-foreground uppercase tracking-wide leading-tight max-w-[80px]">CV Detects Violation</span><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:155:18" data-component-name="div" class="md:hidden w-px h-6 bg-primary/30"></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:139:14" data-component-name="motion.div" class="relative z-10 flex flex-col items-center gap-3 flex-1 card-3d" data-testid="flow-step-2" style="opacity: 0; transform: translateX(-20px) rotateY(-20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:148:16" data-component-name="div" class="w-14 h-14 rounded-full bg-background border-2 border-primary/40 flex items-center justify-center shadow-[0_0_15px_rgba(0,255,255,0.15)] hover:shadow-[0_0_25px_rgba(0,255,255,0.3)] hover:border-primary transition-all duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-shield-alert w-6 h-6 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:149:18" data-component-name="step.icon"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z"></path><path d="M12 8v4"></path><path d="M12 16h.01"></path></svg></div><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:151:16" data-component-name="span" class="text-xs font-semibold text-center text-muted-foreground uppercase tracking-wide leading-tight max-w-[80px]">Plate Recognized</span><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:155:18" data-component-name="div" class="md:hidden w-px h-6 bg-primary/30"></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:139:14" data-component-name="motion.div" class="relative z-10 flex flex-col items-center gap-3 flex-1 card-3d" data-testid="flow-step-3" style="opacity: 0; transform: translateX(-20px) rotateY(-20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:148:16" data-component-name="div" class="w-14 h-14 rounded-full bg-background border-2 border-primary/40 flex items-center justify-center shadow-[0_0_15px_rgba(0,255,255,0.15)] hover:shadow-[0_0_25px_rgba(0,255,255,0.3)] hover:border-primary transition-all duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-file-text w-6 h-6 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:149:18" data-component-name="step.icon"><path d="M15 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7Z"></path><path d="M14 2v4a2 2 0 0 0 2 2h4"></path><path d="M10 9H8"></path><path d="M16 13H8"></path><path d="M16 17H8"></path></svg></div><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:151:16" data-component-name="span" class="text-xs font-semibold text-center text-muted-foreground uppercase tracking-wide leading-tight max-w-[80px]">e-Challan Issued</span><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:155:18" data-component-name="div" class="md:hidden w-px h-6 bg-primary/30"></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:139:14" data-component-name="motion.div" class="relative z-10 flex flex-col items-center gap-3 flex-1 card-3d" data-testid="flow-step-4" style="opacity: 0; transform: translateX(-20px) rotateY(-20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:148:16" data-component-name="div" class="w-14 h-14 rounded-full bg-background border-2 border-primary/40 flex items-center justify-center shadow-[0_0_15px_rgba(0,255,255,0.15)] hover:shadow-[0_0_25px_rgba(0,255,255,0.3)] hover:border-primary transition-all duration-300"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-circle-check w-6 h-6 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:149:18" data-component-name="step.icon"><circle cx="12" cy="12" r="10"></circle><path d="m9 12 2 2 4-4"></path></svg></div><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:151:16" data-component-name="span" class="text-xs font-semibold text-center text-muted-foreground uppercase tracking-wide leading-tight max-w-[80px]">Record Logged</span></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:163:8" data-component-name="div" class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-10 items-start"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:165:10" data-component-name="motion.div" class="bg-background border border-border rounded-3xl p-8" style="perspective: 800px; opacity: 0; transform: translateX(-30px);"><h4 data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:173:12" data-component-name="h4" class="text-lg font-display font-bold mb-6 flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-triangle-alert w-5 h-5 text-red-400" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:174:14" data-component-name="AlertTriangle"><path d="m21.73 18-8-14a2 2 0 0 0-3.48 0l-8 14A2 2 0 0 0 4 21h16a2 2 0 0 0 1.73-3"></path><path d="M12 9v4"></path><path d="M12 17h.01"></path></svg>Violations Detected</h4><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:177:12" data-component-name="div" class="space-y-3"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:179:16" data-component-name="motion.div" class="card-3d flex items-center justify-between px-4 py-3 rounded-xl border text-sm font-medium text-red-400 border-red-500/30 bg-red-500/10" style="opacity: 0; transform: translateX(-15px) rotateX(10deg);"><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:187:18" data-component-name="span">Red Light Jump</span><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:188:18" data-component-name="span" class="text-xs uppercase tracking-wider opacity-70">high</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:179:16" data-component-name="motion.div" class="card-3d flex items-center justify-between px-4 py-3 rounded-xl border text-sm font-medium text-red-400 border-red-500/30 bg-red-500/10" style="opacity: 0; transform: translateX(-15px) rotateX(10deg);"><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:187:18" data-component-name="span">Illegal Lane Change</span><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:188:18" data-component-name="span" class="text-xs uppercase tracking-wider opacity-70">high</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:179:16" data-component-name="motion.div" class="card-3d flex items-center justify-between px-4 py-3 rounded-xl border text-sm font-medium text-red-400 border-red-500/30 bg-red-500/10" style="opacity: 0; transform: translateX(-15px) rotateX(10deg);"><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:187:18" data-component-name="span">Wrong Way Entry</span><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:188:18" data-component-name="span" class="text-xs uppercase tracking-wider opacity-70">high</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:179:16" data-component-name="motion.div" class="card-3d flex items-center justify-between px-4 py-3 rounded-xl border text-sm font-medium text-yellow-400 border-yellow-500/30 bg-yellow-500/10" style="opacity: 0; transform: translateX(-15px) rotateX(10deg);"><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:187:18" data-component-name="span">Stop Line Breach</span><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:188:18" data-component-name="span" class="text-xs uppercase tracking-wider opacity-70">medium</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:179:16" data-component-name="motion.div" class="card-3d flex items-center justify-between px-4 py-3 rounded-xl border text-sm font-medium text-yellow-400 border-yellow-500/30 bg-yellow-500/10" style="opacity: 0; transform: translateX(-15px) rotateX(10deg);"><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:187:18" data-component-name="span">Signal Non-Compliance</span><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:188:18" data-component-name="span" class="text-xs uppercase tracking-wider opacity-70">medium</span></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:179:16" data-component-name="motion.div" class="card-3d flex items-center justify-between px-4 py-3 rounded-xl border text-sm font-medium text-yellow-400 border-yellow-500/30 bg-yellow-500/10" style="opacity: 0; transform: translateX(-15px) rotateX(10deg);"><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:187:18" data-component-name="span">Lane Encroachment</span><span data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:188:18" data-component-name="span" class="text-xs uppercase tracking-wider opacity-70">medium</span></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:195:10" data-component-name="motion.div" class="space-y-6" style="opacity: 0; transform: translateX(30px);"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:202:12" data-component-name="div" class="bg-background border border-border rounded-3xl p-8"><h4 data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:203:14" data-component-name="h4" class="text-lg font-display font-bold mb-6 flex items-center gap-2"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-circle-check w-5 h-5 text-primary" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:204:16" data-component-name="CheckCircle2"><circle cx="12" cy="12" r="10"></circle><path d="m9 12 2 2 4-4"></path></svg>System Capabilities</h4><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:207:14" data-component-name="div" class="grid grid-cols-2 gap-4"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:214:18" data-component-name="div" class="p-4 bg-card rounded-2xl border border-border text-center"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:215:20" data-component-name="div" class="text-xl font-display font-bold text-primary mb-1">Real-time</div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:216:20" data-component-name="div" class="text-xs text-muted-foreground uppercase tracking-wide">Detection Speed</div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:214:18" data-component-name="div" class="p-4 bg-card rounded-2xl border border-border text-center"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:215:20" data-component-name="div" class="text-xl font-display font-bold text-primary mb-1">CV + GPIO</div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:216:20" data-component-name="div" class="text-xs text-muted-foreground uppercase tracking-wide">Tech Used</div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:214:18" data-component-name="div" class="p-4 bg-card rounded-2xl border border-border text-center"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:215:20" data-component-name="div" class="text-xl font-display font-bold text-primary mb-1">Zero</div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:216:20" data-component-name="div" class="text-xs text-muted-foreground uppercase tracking-wide">Human Intervention</div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:214:18" data-component-name="div" class="p-4 bg-card rounded-2xl border border-border text-center"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:215:20" data-component-name="div" class="text-xl font-display font-bold text-primary mb-1">e-Challan</div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:216:20" data-component-name="div" class="text-xs text-muted-foreground uppercase tracking-wide">Penalty Format</div></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:222:12" data-component-name="motion.div" class="relative rounded-3xl overflow-hidden p-8 bg-gradient-to-br from-red-500/10 via-background to-primary/10 border border-red-500/20" style="opacity: 0; transform: translateY(10px);"><div data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:229:14" data-component-name="div" class="text-sm font-bold text-red-400 uppercase tracking-wider mb-3">Why It Matters</div><p data-replit-metadata="artifacts/team-kalam/src/components/ViolationDetection.tsx:230:14" data-component-name="p" class="text-foreground/80 leading-relaxed">Manual enforcement is inconsistent and resource-heavy. Our system operates 24/7, applies rules uniformly, and creates a verifiable digital record — making streets safer and enforcement fair.</p></div></div></div></div></section><section data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:34:4" data-component-name="section" id="how-it-works" class="py-32 relative bg-background overflow-hidden"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:35:6" data-component-name="div" class="container mx-auto px-6"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:37:8" data-component-name="div" class="flex flex-col items-center text-center mb-20"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:38:10" data-component-name="motion.div" class="inline-block px-4 py-1.5 rounded-full bg-primary/10 border border-primary/20 text-primary text-sm font-semibold tracking-wider uppercase mb-6" style="opacity: 0; transform: translateY(20px);">System Flow</div><h2 data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:46:10" data-component-name="motion.h2" class="text-4xl md:text-5xl font-display font-bold" style="opacity: 0; transform: translateY(20px);">How It Works</h2></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:57:8" data-component-name="div" class="max-w-4xl mx-auto relative"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:59:10" data-component-name="div" class="absolute left-[28px] md:left-1/2 top-0 bottom-0 w-px bg-gradient-to-b from-primary/50 via-blue-500/50 to-purple-500/50 md:-translate-x-1/2 hidden sm:block"></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:61:10" data-component-name="div" class="space-y-12 md:space-y-24 relative z-10" style="perspective: 800px; transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:65:16" data-component-name="motion.div" class="flex flex-col md:flex-row items-start md:items-center gap-6 md:gap-16 card-3d md:flex-row-reverse" style="opacity: 0; transform: translateX(-60px) translateZ(-50px) rotateY(-20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:76:18" data-component-name="div" class="hidden md:block flex-1"></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:79:18" data-component-name="motion.div" class="relative shrink-0 w-14 h-14 rounded-full bg-background border-2 border-primary shadow-[0_0_15px_rgba(0,255,255,0.4)] flex items-center justify-center text-xl font-bold text-primary font-display z-10 md:absolute md:left-1/2 md:-translate-x-1/2" style="transform: scale(0.5) rotate(180deg);">1</div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:89:18" data-component-name="div" class="flex-1 w-full"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:90:20" data-component-name="div" class="bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_10px_30px_-10px_rgba(0,255,255,0.1)] hover:-translate-y-1 transition-all duration-300 group md:text-right"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:93:22" data-component-name="div" class="w-12 h-12 bg-primary/10 rounded-xl flex items-center justify-center text-primary mb-6 group-hover:scale-110 transition-transform md:ml-auto"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-scan-search w-6 h-6" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:94:24" data-component-name="step.icon"><path d="M3 7V5a2 2 0 0 1 2-2h2"></path><path d="M17 3h2a2 2 0 0 1 2 2v2"></path><path d="M21 17v2a2 2 0 0 1-2 2h-2"></path><path d="M7 21H5a2 2 0 0 1-2-2v-2"></path><circle cx="12" cy="12" r="3"></circle><path d="m16 16-1.9-1.9"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:96:22" data-component-name="h3" class="text-2xl font-display font-bold mb-3">Detect</h3><p data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:97:22" data-component-name="p" class="text-muted-foreground text-lg leading-relaxed">Raspberry Pi-mounted sensors scan intersection density in real-time across all lanes.</p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:65:16" data-component-name="motion.div" class="flex flex-col md:flex-row items-start md:items-center gap-6 md:gap-16 card-3d " style="opacity: 0; transform: translateX(60px) translateZ(-50px) rotateY(20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:76:18" data-component-name="div" class="hidden md:block flex-1"></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:79:18" data-component-name="motion.div" class="relative shrink-0 w-14 h-14 rounded-full bg-background border-2 border-primary shadow-[0_0_15px_rgba(0,255,255,0.4)] flex items-center justify-center text-xl font-bold text-primary font-display z-10 md:absolute md:left-1/2 md:-translate-x-1/2" style="transform: scale(0.5) rotate(180deg);">2</div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:89:18" data-component-name="div" class="flex-1 w-full"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:90:20" data-component-name="div" class="bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_10px_30px_-10px_rgba(0,255,255,0.1)] hover:-translate-y-1 transition-all duration-300 group text-left"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:93:22" data-component-name="div" class="w-12 h-12 bg-primary/10 rounded-xl flex items-center justify-center text-primary mb-6 group-hover:scale-110 transition-transform "><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-cpu w-6 h-6" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:94:24" data-component-name="step.icon"><path d="M12 20v2"></path><path d="M12 2v2"></path><path d="M17 20v2"></path><path d="M17 2v2"></path><path d="M2 12h2"></path><path d="M2 17h2"></path><path d="M2 7h2"></path><path d="M20 12h2"></path><path d="M20 17h2"></path><path d="M20 7h2"></path><path d="M7 20v2"></path><path d="M7 2v2"></path><rect x="4" y="4" width="16" height="16" rx="2"></rect><rect x="8" y="8" width="8" height="8" rx="1"></rect></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:96:22" data-component-name="h3" class="text-2xl font-display font-bold mb-3">Analyze</h3><p data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:97:22" data-component-name="p" class="text-muted-foreground text-lg leading-relaxed">Custom Python algorithms process the density data, computing optimal signal phase durations.</p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:65:16" data-component-name="motion.div" class="flex flex-col md:flex-row items-start md:items-center gap-6 md:gap-16 card-3d md:flex-row-reverse" style="opacity: 0; transform: translateX(-60px) translateZ(-50px) rotateY(-20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:76:18" data-component-name="div" class="hidden md:block flex-1"></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:79:18" data-component-name="motion.div" class="relative shrink-0 w-14 h-14 rounded-full bg-background border-2 border-primary shadow-[0_0_15px_rgba(0,255,255,0.4)] flex items-center justify-center text-xl font-bold text-primary font-display z-10 md:absolute md:left-1/2 md:-translate-x-1/2" style="transform: scale(0.5) rotate(180deg);">3</div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:89:18" data-component-name="div" class="flex-1 w-full"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:90:20" data-component-name="div" class="bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_10px_30px_-10px_rgba(0,255,255,0.1)] hover:-translate-y-1 transition-all duration-300 group md:text-right"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:93:22" data-component-name="div" class="w-12 h-12 bg-primary/10 rounded-xl flex items-center justify-center text-primary mb-6 group-hover:scale-110 transition-transform md:ml-auto"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-brain-circuit w-6 h-6" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:94:24" data-component-name="step.icon"><path d="M12 5a3 3 0 1 0-5.997.125 4 4 0 0 0-2.526 5.77 4 4 0 0 0 .556 6.588A4 4 0 1 0 12 18Z"></path><path d="M9 13a4.5 4.5 0 0 0 3-4"></path><path d="M6.003 5.125A3 3 0 0 0 6.401 6.5"></path><path d="M3.477 10.896a4 4 0 0 1 .585-.396"></path><path d="M6 18a4 4 0 0 1-1.967-.516"></path><path d="M12 13h4"></path><path d="M12 18h6a2 2 0 0 1 2 2v1"></path><path d="M12 8h8"></path><path d="M16 8V5a2 2 0 0 1 2-2"></path><circle cx="16" cy="13" r=".5"></circle><circle cx="18" cy="3" r=".5"></circle><circle cx="20" cy="21" r=".5"></circle><circle cx="20" cy="8" r=".5"></circle></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:96:22" data-component-name="h3" class="text-2xl font-display font-bold mb-3">Decide</h3><p data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:97:22" data-component-name="p" class="text-muted-foreground text-lg leading-relaxed">The decision engine calculates the most efficient green-light priority and timing windows.</p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:65:16" data-component-name="motion.div" class="flex flex-col md:flex-row items-start md:items-center gap-6 md:gap-16 card-3d " style="opacity: 0; transform: translateX(60px) translateZ(-50px) rotateY(20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:76:18" data-component-name="div" class="hidden md:block flex-1"></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:79:18" data-component-name="motion.div" class="relative shrink-0 w-14 h-14 rounded-full bg-background border-2 border-primary shadow-[0_0_15px_rgba(0,255,255,0.4)] flex items-center justify-center text-xl font-bold text-primary font-display z-10 md:absolute md:left-1/2 md:-translate-x-1/2" style="transform: scale(0.5) rotate(180deg);">4</div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:89:18" data-component-name="div" class="flex-1 w-full"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:90:20" data-component-name="div" class="bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_10px_30px_-10px_rgba(0,255,255,0.1)] hover:-translate-y-1 transition-all duration-300 group text-left"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:93:22" data-component-name="div" class="w-12 h-12 bg-primary/10 rounded-xl flex items-center justify-center text-primary mb-6 group-hover:scale-110 transition-transform "><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-zap w-6 h-6" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:94:24" data-component-name="step.icon"><path d="M4 14a1 1 0 0 1-.78-1.63l9.9-10.2a.5.5 0 0 1 .86.46l-1.92 6.02A1 1 0 0 0 13 10h7a1 1 0 0 1 .78 1.63l-9.9 10.2a.5.5 0 0 1-.86-.46l1.92-6.02A1 1 0 0 0 11 14z"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:96:22" data-component-name="h3" class="text-2xl font-display font-bold mb-3">Actuate</h3><p data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:97:22" data-component-name="p" class="text-muted-foreground text-lg leading-relaxed">Signal outputs are updated in milliseconds via GPIO pins connected to traffic light hardware.</p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:65:16" data-component-name="motion.div" class="flex flex-col md:flex-row items-start md:items-center gap-6 md:gap-16 card-3d md:flex-row-reverse" style="opacity: 0; transform: translateX(-60px) translateZ(-50px) rotateY(-20deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:76:18" data-component-name="div" class="hidden md:block flex-1"></div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:79:18" data-component-name="motion.div" class="relative shrink-0 w-14 h-14 rounded-full bg-background border-2 border-primary shadow-[0_0_15px_rgba(0,255,255,0.4)] flex items-center justify-center text-xl font-bold text-primary font-display z-10 md:absolute md:left-1/2 md:-translate-x-1/2" style="transform: scale(0.5) rotate(180deg);">5</div><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:89:18" data-component-name="div" class="flex-1 w-full"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:90:20" data-component-name="div" class="bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_10px_30px_-10px_rgba(0,255,255,0.1)] hover:-translate-y-1 transition-all duration-300 group md:text-right"><div data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:93:22" data-component-name="div" class="w-12 h-12 bg-primary/10 rounded-xl flex items-center justify-center text-primary mb-6 group-hover:scale-110 transition-transform md:ml-auto"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-repeat w-6 h-6" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:94:24" data-component-name="step.icon"><path d="m17 2 4 4-4 4"></path><path d="M3 11v-1a4 4 0 0 1 4-4h14"></path><path d="m7 22-4-4 4-4"></path><path d="M21 13v1a4 4 0 0 1-4 4H3"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:96:22" data-component-name="h3" class="text-2xl font-display font-bold mb-3">Adapt</h3><p data-replit-metadata="artifacts/team-kalam/src/components/HowItWorks.tsx:97:22" data-component-name="p" class="text-muted-foreground text-lg leading-relaxed">The system continuously loops, learning the ebb and flow of traffic patterns over time.</p></div></div></div></div></div></div></section><section data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:17:4" data-component-name="section" id="tech" class="py-32 bg-secondary/30 relative border-t border-border"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:18:6" data-component-name="div" class="container mx-auto px-6"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:20:8" data-component-name="div" class="flex flex-col items-center text-center mb-20"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:21:10" data-component-name="motion.div" class="inline-block px-4 py-1.5 rounded-full bg-primary/10 border border-primary/20 text-primary text-sm font-semibold tracking-wider uppercase mb-6" style="opacity: 0; transform: translateY(20px);">Technology</div><h2 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:29:10" data-component-name="motion.h2" class="text-4xl md:text-5xl font-display font-bold mb-6" style="opacity: 0; transform: translateY(20px);">Built With Purpose</h2><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:38:10" data-component-name="motion.p" class="text-xl text-muted-foreground max-w-2xl mx-auto" style="opacity: 0; transform: translateY(20px);">Every component chosen for reliability, performance, and real-world deployability.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:49:8" data-component-name="div" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 max-w-6xl mx-auto" style="perspective: 1000px;"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:51:12" data-component-name="motion.div" class="card-3d bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_0_20px_rgba(0,255,255,0.15)] transition-all duration-300 group flex flex-col items-center text-center" style="opacity: 0; transform: translateY(40px) scale(0.9) rotateX(25deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:60:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-6 group-hover:bg-primary/10 group-hover:text-primary transition-colors text-foreground"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-cpu w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:61:16" data-component-name="tech.icon"><path d="M12 20v2"></path><path d="M12 2v2"></path><path d="M17 20v2"></path><path d="M17 2v2"></path><path d="M2 12h2"></path><path d="M2 17h2"></path><path d="M2 7h2"></path><path d="M20 12h2"></path><path d="M20 17h2"></path><path d="M20 7h2"></path><path d="M7 20v2"></path><path d="M7 2v2"></path><rect x="4" y="4" width="16" height="16" rx="2"></rect><rect x="8" y="8" width="8" height="8" rx="1"></rect></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:63:14" data-component-name="h3" class="text-xl font-bold font-display mb-2">Raspberry Pi</h3><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:64:14" data-component-name="p" class="text-sm text-muted-foreground font-medium">Edge Computing Hardware</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:51:12" data-component-name="motion.div" class="card-3d bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_0_20px_rgba(0,255,255,0.15)] transition-all duration-300 group flex flex-col items-center text-center" style="opacity: 0; transform: translateY(40px) scale(0.9) rotateX(25deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:60:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-6 group-hover:bg-primary/10 group-hover:text-primary transition-colors text-foreground"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-code-xml w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:61:16" data-component-name="tech.icon"><path d="m18 16 4-4-4-4"></path><path d="m6 8-4 4 4 4"></path><path d="m14.5 4-5 16"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:63:14" data-component-name="h3" class="text-xl font-bold font-display mb-2">Python</h3><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:64:14" data-component-name="p" class="text-sm text-muted-foreground font-medium">Core Logic &amp; Algorithms</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:51:12" data-component-name="motion.div" class="card-3d bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_0_20px_rgba(0,255,255,0.15)] transition-all duration-300 group flex flex-col items-center text-center" style="opacity: 0; transform: translateY(40px) scale(0.9) rotateX(25deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:60:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-6 group-hover:bg-primary/10 group-hover:text-primary transition-colors text-foreground"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-layers w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:61:16" data-component-name="tech.icon"><path d="M12.83 2.18a2 2 0 0 0-1.66 0L2.6 6.08a1 1 0 0 0 0 1.83l8.58 3.91a2 2 0 0 0 1.66 0l8.58-3.9a1 1 0 0 0 0-1.83z"></path><path d="M2 12a1 1 0 0 0 .58.91l8.6 3.91a2 2 0 0 0 1.65 0l8.58-3.9A1 1 0 0 0 22 12"></path><path d="M2 17a1 1 0 0 0 .58.91l8.6 3.91a2 2 0 0 0 1.65 0l8.58-3.9A1 1 0 0 0 22 17"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:63:14" data-component-name="h3" class="text-xl font-bold font-display mb-2">GPIO</h3><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:64:14" data-component-name="p" class="text-sm text-muted-foreground font-medium">Hardware Interface Layer</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:51:12" data-component-name="motion.div" class="card-3d bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_0_20px_rgba(0,255,255,0.15)] transition-all duration-300 group flex flex-col items-center text-center" style="opacity: 0; transform: translateY(40px) scale(0.9) rotateX(25deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:60:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-6 group-hover:bg-primary/10 group-hover:text-primary transition-colors text-foreground"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-camera w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:61:16" data-component-name="tech.icon"><path d="M13.997 4a2 2 0 0 1 1.76 1.05l.486.9A2 2 0 0 0 18.003 7H20a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h1.997a2 2 0 0 0 1.759-1.048l.489-.904A2 2 0 0 1 10.004 4z"></path><circle cx="12" cy="13" r="3"></circle></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:63:14" data-component-name="h3" class="text-xl font-bold font-display mb-2">OpenCV</h3><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:64:14" data-component-name="p" class="text-sm text-muted-foreground font-medium">Computer Vision Processing</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:51:12" data-component-name="motion.div" class="card-3d bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_0_20px_rgba(0,255,255,0.15)] transition-all duration-300 group flex flex-col items-center text-center" style="opacity: 0; transform: translateY(40px) scale(0.9) rotateX(25deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:60:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-6 group-hover:bg-primary/10 group-hover:text-primary transition-colors text-foreground"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-chart-no-axes-column w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:61:16" data-component-name="tech.icon"><path d="M5 21v-6"></path><path d="M12 21V3"></path><path d="M19 21V9"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:63:14" data-component-name="h3" class="text-xl font-bold font-display mb-2">NumPy</h3><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:64:14" data-component-name="p" class="text-sm text-muted-foreground font-medium">Numerical Data Processing</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:51:12" data-component-name="motion.div" class="card-3d bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_0_20px_rgba(0,255,255,0.15)] transition-all duration-300 group flex flex-col items-center text-center" style="opacity: 0; transform: translateY(40px) scale(0.9) rotateX(25deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:60:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-6 group-hover:bg-primary/10 group-hover:text-primary transition-colors text-foreground"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-terminal w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:61:16" data-component-name="tech.icon"><path d="M12 19h8"></path><path d="m4 17 6-6-6-6"></path></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:63:14" data-component-name="h3" class="text-xl font-bold font-display mb-2">Linux</h3><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:64:14" data-component-name="p" class="text-sm text-muted-foreground font-medium">Operating System</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:51:12" data-component-name="motion.div" class="card-3d bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_0_20px_rgba(0,255,255,0.15)] transition-all duration-300 group flex flex-col items-center text-center" style="opacity: 0; transform: translateY(40px) scale(0.9) rotateX(25deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:60:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-6 group-hover:bg-primary/10 group-hover:text-primary transition-colors text-foreground"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-circuit-board w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:61:16" data-component-name="tech.icon"><rect width="18" height="18" x="3" y="3" rx="2"></rect><path d="M11 9h4a2 2 0 0 0 2-2V3"></path><circle cx="9" cy="9" r="2"></circle><path d="M7 21v-4a2 2 0 0 1 2-2h4"></path><circle cx="15" cy="15" r="2"></circle></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:63:14" data-component-name="h3" class="text-xl font-bold font-display mb-2">Custom PCB</h3><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:64:14" data-component-name="p" class="text-sm text-muted-foreground font-medium">Signal Control Circuit</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:51:12" data-component-name="motion.div" class="card-3d bg-card border border-border p-8 rounded-3xl hover:border-primary/50 hover:shadow-[0_0_20px_rgba(0,255,255,0.15)] transition-all duration-300 group flex flex-col items-center text-center" style="opacity: 0; transform: translateY(40px) scale(0.9) rotateX(25deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:60:14" data-component-name="div" class="w-16 h-16 rounded-2xl bg-secondary flex items-center justify-center mb-6 group-hover:bg-primary/10 group-hover:text-primary transition-colors text-foreground"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-clock w-8 h-8" aria-hidden="true" data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:61:16" data-component-name="tech.icon"><path d="M12 6v6l4 2"></path><circle cx="12" cy="12" r="10"></circle></svg></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:63:14" data-component-name="h3" class="text-xl font-bold font-display mb-2">Real-time OS</h3><p data-replit-metadata="artifacts/team-kalam/src/components/TechStack.tsx:64:14" data-component-name="p" class="text-sm text-muted-foreground font-medium">Low-latency Scheduling</p></div></div></div></section><section data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:126:4" data-component-name="section" id="team" class="py-32 relative bg-background border-t border-border"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:127:6" data-component-name="div" class="container mx-auto px-6"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:128:8" data-component-name="div" class="flex flex-col items-center text-center mb-20"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:129:10" data-component-name="motion.div" class="inline-block px-4 py-1.5 rounded-full bg-primary/10 border border-primary/20 text-primary text-sm font-semibold tracking-wider uppercase mb-6" style="opacity: 0; transform: translateY(20px);">The People Behind It</div><h2 data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:137:10" data-component-name="motion.h2" class="text-4xl md:text-6xl font-display font-bold mb-6" style="opacity: 0; transform: translateY(20px);">Meet Team Kalam</h2><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:146:10" data-component-name="motion.p" class="text-xl text-muted-foreground max-w-2xl mx-auto" style="opacity: 0; transform: translateY(20px);">Five students. One shared mission. A city's worth of ambition.</p></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:157:8" data-component-name="div" class="flex flex-wrap justify-center gap-8 max-w-7xl mx-auto" style="perspective: 1200px;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:65:4" data-component-name="motion.div" class="group p-1 rounded-3xl bg-gradient-to-br border border-border hover:border-transparent transition-colors duration-300 hover:shadow-[0_15px_40px_-10px_rgba(0,255,255,0.2)] w-full md:w-[600px] card-3d" style="background-image: linear-gradient(to bottom right, var(--color-border), var(--color-card)); transform-style: preserve-3d; opacity: 0; transform: scale(0.9);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:83:6" data-component-name="div" class="h-full bg-card rounded-[22px] p-8 relative overflow-hidden flex flex-col items-center text-center hover:bg-card/80 transition-colors" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:84:8" data-component-name="div" class="absolute -right-16 -top-16 w-48 h-48 bg-gradient-to-br from-blue-500 to-cyan-400 blur-[60px] opacity-20 group-hover:opacity-40 transition-opacity duration-500" style="transform: translateZ(0px);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:86:8" data-component-name="div" class="relative z-10 flex flex-col items-center w-full" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:87:10" data-component-name="div" class="rounded-full bg-gradient-to-br from-blue-500 to-cyan-400 p-1 mb-6 shadow-xl" style="transform: translateZ(30px);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:91:12" data-component-name="div" class="bg-secondary flex items-center justify-center font-display font-bold border-4 border-background rounded-full w-28 h-28 text-4xl"><span data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:94:14" data-component-name="span" class="text-transparent bg-clip-text bg-gradient-to-br from-white to-white/50">A</span></div></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:100:10" data-component-name="h3" class="text-3xl font-display font-bold mb-2" style="transform: translateZ(20px);">Adit Kumar</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:106:10" data-component-name="p" class="text-primary font-bold text-sm tracking-widest uppercase mb-6" style="transform: translateZ(15px);">Team Lead</p><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:112:10" data-component-name="p" class="text-muted-foreground leading-relaxed text-lg" style="transform: translateZ(10px);">Leads the team's vision, coordinates deliverables, and keeps the mission on track.</p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:65:4" data-component-name="motion.div" class="group p-1 rounded-3xl bg-gradient-to-br border border-border hover:border-transparent transition-colors duration-300 hover:shadow-[0_15px_40px_-10px_rgba(0,255,255,0.2)] w-full md:w-[400px] card-3d" style="background-image: linear-gradient(to bottom right, var(--color-border), var(--color-card)); transform-style: preserve-3d; opacity: 0; transform: scale(0.9);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:83:6" data-component-name="div" class="h-full bg-card rounded-[22px] p-8 relative overflow-hidden flex flex-col items-center text-center hover:bg-card/80 transition-colors" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:84:8" data-component-name="div" class="absolute -right-16 -top-16 w-48 h-48 bg-gradient-to-br from-purple-500 to-pink-400 blur-[60px] opacity-20 group-hover:opacity-40 transition-opacity duration-500" style="transform: translateZ(0px);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:86:8" data-component-name="div" class="relative z-10 flex flex-col items-center w-full" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:87:10" data-component-name="div" class="rounded-full bg-gradient-to-br from-purple-500 to-pink-400 p-1 mb-6 shadow-xl" style="transform: translateZ(30px);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:91:12" data-component-name="div" class="bg-secondary flex items-center justify-center font-display font-bold border-4 border-background rounded-full w-24 h-24 text-3xl"><span data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:94:14" data-component-name="span" class="text-transparent bg-clip-text bg-gradient-to-br from-white to-white/50">K</span></div></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:100:10" data-component-name="h3" class="text-2xl font-display font-bold mb-2" style="transform: translateZ(20px);">Krishna</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:106:10" data-component-name="p" class="text-primary font-bold text-sm tracking-widest uppercase mb-6" style="transform: translateZ(15px);">Design (UI &amp; UX)</p><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:112:10" data-component-name="p" class="text-muted-foreground leading-relaxed text-base" style="transform: translateZ(10px);">Crafts the user interface and visual identity that brings our work to life.</p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:65:4" data-component-name="motion.div" class="group p-1 rounded-3xl bg-gradient-to-br border border-border hover:border-transparent transition-colors duration-300 hover:shadow-[0_15px_40px_-10px_rgba(0,255,255,0.2)] w-full md:w-[400px] card-3d" style="background-image: linear-gradient(to bottom right, var(--color-border), var(--color-card)); transform-style: preserve-3d; opacity: 0; transform: scale(0.9);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:83:6" data-component-name="div" class="h-full bg-card rounded-[22px] p-8 relative overflow-hidden flex flex-col items-center text-center hover:bg-card/80 transition-colors" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:84:8" data-component-name="div" class="absolute -right-16 -top-16 w-48 h-48 bg-gradient-to-br from-emerald-500 to-teal-400 blur-[60px] opacity-20 group-hover:opacity-40 transition-opacity duration-500" style="transform: translateZ(0px);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:86:8" data-component-name="div" class="relative z-10 flex flex-col items-center w-full" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:87:10" data-component-name="div" class="rounded-full bg-gradient-to-br from-emerald-500 to-teal-400 p-1 mb-6 shadow-xl" style="transform: translateZ(30px);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:91:12" data-component-name="div" class="bg-secondary flex items-center justify-center font-display font-bold border-4 border-background rounded-full w-24 h-24 text-3xl"><span data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:94:14" data-component-name="span" class="text-transparent bg-clip-text bg-gradient-to-br from-white to-white/50">G</span></div></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:100:10" data-component-name="h3" class="text-2xl font-display font-bold mb-2" style="transform: translateZ(20px);">Gagan</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:106:10" data-component-name="p" class="text-primary font-bold text-sm tracking-widest uppercase mb-6" style="transform: translateZ(15px);">Technical Lead</p><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:112:10" data-component-name="p" class="text-muted-foreground leading-relaxed text-base" style="transform: translateZ(10px);">Architects the core software systems and technical decision-making.</p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:65:4" data-component-name="motion.div" class="group p-1 rounded-3xl bg-gradient-to-br border border-border hover:border-transparent transition-colors duration-300 hover:shadow-[0_15px_40px_-10px_rgba(0,255,255,0.2)] w-full md:w-[400px] card-3d" style="background-image: linear-gradient(to bottom right, var(--color-border), var(--color-card)); transform-style: preserve-3d; opacity: 0; transform: scale(0.9);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:83:6" data-component-name="div" class="h-full bg-card rounded-[22px] p-8 relative overflow-hidden flex flex-col items-center text-center hover:bg-card/80 transition-colors" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:84:8" data-component-name="div" class="absolute -right-16 -top-16 w-48 h-48 bg-gradient-to-br from-orange-500 to-red-400 blur-[60px] opacity-20 group-hover:opacity-40 transition-opacity duration-500" style="transform: translateZ(0px);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:86:8" data-component-name="div" class="relative z-10 flex flex-col items-center w-full" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:87:10" data-component-name="div" class="rounded-full bg-gradient-to-br from-orange-500 to-red-400 p-1 mb-6 shadow-xl" style="transform: translateZ(30px);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:91:12" data-component-name="div" class="bg-secondary flex items-center justify-center font-display font-bold border-4 border-background rounded-full w-24 h-24 text-3xl"><span data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:94:14" data-component-name="span" class="text-transparent bg-clip-text bg-gradient-to-br from-white to-white/50">M</span></div></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:100:10" data-component-name="h3" class="text-2xl font-display font-bold mb-2" style="transform: translateZ(20px);">Muhammad</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:106:10" data-component-name="p" class="text-primary font-bold text-sm tracking-widest uppercase mb-6" style="transform: translateZ(15px);">Hardware Lead</p><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:112:10" data-component-name="p" class="text-muted-foreground leading-relaxed text-base" style="transform: translateZ(10px);">Designs, assembles, and calibrates all physical hardware components.</p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:65:4" data-component-name="motion.div" class="group p-1 rounded-3xl bg-gradient-to-br border border-border hover:border-transparent transition-colors duration-300 hover:shadow-[0_15px_40px_-10px_rgba(0,255,255,0.2)] w-full md:w-[400px] card-3d" style="background-image: linear-gradient(to bottom right, var(--color-border), var(--color-card)); transform-style: preserve-3d; opacity: 0; transform: scale(0.9);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:83:6" data-component-name="div" class="h-full bg-card rounded-[22px] p-8 relative overflow-hidden flex flex-col items-center text-center hover:bg-card/80 transition-colors" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:84:8" data-component-name="div" class="absolute -right-16 -top-16 w-48 h-48 bg-gradient-to-br from-yellow-500 to-amber-400 blur-[60px] opacity-20 group-hover:opacity-40 transition-opacity duration-500" style="transform: translateZ(0px);"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:86:8" data-component-name="div" class="relative z-10 flex flex-col items-center w-full" style="transform-style: preserve-3d;"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:87:10" data-component-name="div" class="rounded-full bg-gradient-to-br from-yellow-500 to-amber-400 p-1 mb-6 shadow-xl" style="transform: translateZ(30px);"><div data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:91:12" data-component-name="div" class="bg-secondary flex items-center justify-center font-display font-bold border-4 border-background rounded-full w-24 h-24 text-3xl"><span data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:94:14" data-component-name="span" class="text-transparent bg-clip-text bg-gradient-to-br from-white to-white/50">H</span></div></div><h3 data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:100:10" data-component-name="h3" class="text-2xl font-display font-bold mb-2" style="transform: translateZ(20px);">Harshit Dobriyal</h3><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:106:10" data-component-name="p" class="text-primary font-bold text-sm tracking-widest uppercase mb-6" style="transform: translateZ(15px);">Research &amp; Documentation Lead</p><p data-replit-metadata="artifacts/team-kalam/src/components/Team.tsx:112:10" data-component-name="p" class="text-muted-foreground leading-relaxed text-base" style="transform: translateZ(10px);">Documents findings, conducts research, and translates tech into clear communication.</p></div></div></div></div></div></section></main><footer data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:5:4" data-component-name="motion.footer" class="bg-secondary relative overflow-hidden pt-20 pb-10" style="perspective: 1000px; opacity: 0; transform: translateY(40px) rotateX(10deg);"><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:14:6" data-component-name="div" class="absolute top-0 left-0 w-full h-[2px] bg-gradient-to-r from-transparent via-primary to-transparent opacity-50"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:17:6" data-component-name="div" class="absolute bottom-0 left-1/2 -translate-x-1/2 w-[800px] h-[400px] bg-primary/10 rounded-full blur-[120px] pointer-events-none"></div><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:19:6" data-component-name="div" class="container mx-auto px-6 relative z-10"><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:20:8" data-component-name="div" class="grid grid-cols-1 md:grid-cols-3 gap-12 mb-16"><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:23:10" data-component-name="div" class="flex flex-col gap-4"><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:24:12" data-component-name="div" class="flex items-center gap-3"><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:25:14" data-component-name="div" class="w-10 h-10 rounded-lg bg-primary/10 border border-primary/30 flex items-center justify-center"><span data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:26:16" data-component-name="span" class="text-primary font-bold text-lg leading-none tracking-tighter">T<br data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:27:19" data-component-name="br">K</span></div><h2 data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:30:14" data-component-name="h2" class="font-display font-bold text-2xl tracking-tight">TEAM <span data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:30:82" data-component-name="span" class="text-primary">KALAM</span></h2></div><p data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:32:12" data-component-name="p" class="text-muted-foreground text-sm max-w-sm mt-2 leading-relaxed">Engineering tomorrow's cities. One signal at a time.</p><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:35:12" data-component-name="div" class="mt-4 inline-block px-3 py-1 rounded-md bg-background/50 border border-border text-xs text-primary font-medium w-fit">Smart Cities Domain — Robotics</div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:41:10" data-component-name="div" class="flex flex-col gap-4 md:items-center"><h3 data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:42:12" data-component-name="h3" class="font-bold text-foreground mb-2">Quick Links</h3><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:43:12" data-component-name="div" class="flex flex-col gap-3 text-sm text-muted-foreground"><a data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:44:14" data-component-name="a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#" class="hover:text-primary transition-colors">Home</a><a data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:45:14" data-component-name="a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#about" class="hover:text-primary transition-colors">About</a><a data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:46:14" data-component-name="a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#project" class="hover:text-primary transition-colors">Project</a><a data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:47:14" data-component-name="a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#how-it-works" class="hover:text-primary transition-colors">How It Works</a><a data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:48:14" data-component-name="a" href="https://213c586d-0bf0-47d2-b775-0214510082fe-00-1wod5juxee55j.sisko.replit.dev/#team" class="hover:text-primary transition-colors">Team</a></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:53:10" data-component-name="div" class="flex flex-col gap-4 md:items-end"><h3 data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:54:12" data-component-name="h3" class="font-bold text-foreground mb-2">Team Info</h3><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:55:12" data-component-name="div" class="flex flex-col gap-3 text-sm text-muted-foreground md:text-right"><p data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:56:14" data-component-name="p">5 Core Members</p><p data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:57:14" data-component-name="p">Active 2026</p><p data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:58:14" data-component-name="p">Domain: <span data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:58:25" data-component-name="span" class="text-primary font-medium">Smart Cities</span></p></div></div></div><div data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:64:8" data-component-name="div" class="border-t border-border pt-8 flex flex-col md:flex-row items-center justify-between gap-4 text-xs text-muted-foreground opacity-60"><p data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:65:10" data-component-name="p">© 2026 Team Kalam. All rights reserved.</p><p data-replit-metadata="artifacts/team-kalam/src/components/Footer.tsx:66:10" data-component-name="p">Built for the future.</p></div></div></footer></div></div>
    <script type="module" src="./Team Kalam_files/main.tsx"></script>
  <script src="./Team Kalam_files/replit-pill.global.js.download" data-repl-id="213c586d-0bf0-47d2-b775-0214510082fe"></script>

<div id="replit-dev-banner">
    <div class="banner-text">
      This is a temporary development preview, and these links are not for public use. <a href="https://docs.replit.com/category/replit-deployments?ref=replit-dev-banner" target="_blank" class="banner-link">Publish your app</a> for secure sharing or use an invite link.
    </div>
    <button class="banner-close" aria-label="Close banner">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="currentColor">
        <path d="M5.293 5.293a1 1 0 0 1 1.414 0L12 10.586l5.293-5.293a1 1 0 1 1 1.414 1.414L13.414 12l5.293 5.293a1 1 0 0 1-1.414 1.414L12 13.414l-5.293 5.293a1 1 0 0 1-1.414-1.414L10.586 12 5.293 6.707a1 1 0 0 1 0-1.414z"></path>
      </svg>
    </button>
  </div><div id="replit-pill-host"><template shadowrootmode="closed"><style>
        #replit-pill {
          position: fixed;
          bottom: 48px;
          right: 48px;
          border-radius: 120px;
          font-family: system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
          font-size: 12px;
          display: inline-flex;
          align-items: center;
          gap: 6px;
          padding: 6px 12px;
          z-index: 1000000;
          white-space: nowrap;
          cursor: pointer;
          overflow: hidden;
          background-color: rgba(0, 0, 0, 0.4);
          backdrop-filter: blur(6px);
          -webkit-backdrop-filter: blur(6px);
          color: #f0f2f6;
          box-shadow: 1px 1px 1px 0px rgba(0, 0, 0, 0.05), 1px 1px 1px 0px rgba(255, 255, 255, 0.1);
          transition:
            transform 0.2s ease,
            background-color 400ms cubic-bezier(0.2, 0.6, 0.2, 1),
            box-shadow 400ms cubic-bezier(0.2, 0.6, 0.2, 1);
        }
        #replit-pill[data-state="cta"] {
          background-color: rgba(38, 20, 12, 0.55);
          color: #faf6f1;
          box-shadow:
            0 8px 24px rgba(255, 90, 30, 0.28),
            1px 1px 1px 0px rgba(0, 0, 0, 0.05),
            inset 0 0 0 1px rgba(255, 140, 70, 0.18);
        }
        #replit-pill:hover {
          transform: scale(1.05);
        }
        #replit-pill .shimmer {
          position: absolute;
          inset: 0;
          transform: translateX(-100%);
          transition: transform 0.7s ease-in-out;
          background: linear-gradient(to right, transparent, rgba(255, 255, 255, 0.1), transparent);
          pointer-events: none;
        }
        #replit-pill:hover .shimmer {
          transform: translateX(100%);
        }
        #replit-pill .badge-content {
          display: inline-flex;
          align-items: center;
          gap: 6px;
          position: relative;
          flex: 0 0 auto;
        }
        #replit-pill .replit-logo {
          color: currentColor;
        }
        #replit-pill .flip {
          position: relative;
          display: inline-block;
          height: 20px;
          overflow: hidden;
          font-weight: 500;
          line-height: 20px;
          color: currentColor;
        }
        #replit-pill .flip.ready {
          transition: width 300ms cubic-bezier(0.2, 0.6, 0.2, 1);
        }
        #replit-pill .row {
          position: absolute;
          inset: 0 auto 0 0;
          display: flex;
          align-items: center;
          white-space: nowrap;
          will-change: transform, opacity;
          transform: translateY(-110%);
          opacity: 0;
          line-height: 1;
        }
        #replit-pill .row.in {
          animation: replit-pill-roll-in 380ms cubic-bezier(0.2, 0.6, 0.2, 1) forwards;
        }
        #replit-pill .row.out {
          animation: replit-pill-roll-out 380ms cubic-bezier(0.2, 0.6, 0.2, 1) forwards;
        }
        @keyframes replit-pill-roll-in {
          from { transform: translateY(110%); opacity: 0; }
          to   { transform: translateY(0);    opacity: 1; }
        }
        @keyframes replit-pill-roll-out {
          from { transform: translateY(0);     opacity: 1; }
          to   { transform: translateY(-110%); opacity: 0; }
        }
        #replit-pill .close-button {
          display: inline-flex;
          align-items: center;
          justify-content: center;
          padding: 2px;
          flex: 0 0 auto;
          border-radius: 64px;
          width: 12px;
          height: 12px;
          min-width: 0;
          cursor: pointer;
          border: none;
          box-sizing: border-box;
          background-color: transparent;
          transition: background-color 0.2s ease;
        }
        #replit-pill .close-button:hover {
          background-color: rgba(255, 255, 255, 0.1);
        }
        #replit-pill .close-button:focus-visible {
          outline: 1px solid #e6e9ef;
          outline-offset: 1px;
        }
        #replit-pill .close-icon {
          width: 8px;
          height: 8px;
          color: #e6e9ef;
        }
        #replit-pill[data-state="cta"] .close-icon {
          color: #faf6f1;
        }
        #replit-pill[data-state="cta"] .close-button:focus-visible {
          outline-color: #faf6f1;
        }
        @media (prefers-reduced-motion: reduce) {
          #replit-pill,
          #replit-pill .flip,
          #replit-pill .row,
          #replit-pill .shimmer {
            transition: none;
          }
          #replit-pill .row.in,
          #replit-pill .row.out {
            animation: none;
          }
        }
      </style><div id="replit-pill" data-state="brand"><div class="shimmer"></div><div class="badge-content"><svg width="10.67" height="16" viewBox="0 0 50 75" fill="none" class="replit-logo">
        <path d="M25 19.995C25 20.0375 25 20.0575 25 20.085C25.015 21.34 25.5475 22.6275 26.425 23.525C26.445 23.545 26.4475 23.5475 26.45 23.55C26.485 23.585 26.5025 23.6025 26.54 23.6375C27.4225 24.485 28.6775 25.005 29.9025 25.03C29.9525 25.03 29.9975 25.03 30.0825 25.03H42C44.8 25.03 46.2 25.03 47.27 25.575C48.21 26.055 48.975 26.82 49.455 27.76C50 28.83 50 30.23 50 33.03V42.03C50 44.83 50 46.23 49.455 47.3C48.975 48.24 48.21 49.005 47.27 49.485C46.2 50.03 44.8 50.03 42 50.03H29.9275C28.6425 50.0325 27.3225 50.58 26.4125 51.485C26.4075 51.49 26.4775 51.42 26.45 51.4475C26.445 51.4525 26.4425 51.4525 26.4225 51.475C25.545 52.3725 25.0125 53.6575 24.9975 54.9125C24.9975 54.94 24.9975 54.9625 24.9975 55.0025V67.0575C24.9975 69.8575 24.9975 71.2575 24.4525 72.3275C23.9725 73.2675 23.2075 74.0325 22.2675 74.5125C21.1975 75.0575 19.7975 75.0575 16.9975 75.0575H7.9975C5.1975 75.0575 3.7975 75.0575 2.7275 74.5125C1.7875 74.0325 1.0225 73.2675 0.542498 72.3275C-0.00250244 71.2575 -0.00250244 69.8575 -0.00250244 67.0575V58.0575C-0.00250244 55.2575 -0.00250244 53.8575 0.542498 52.7875C1.0225 51.8475 1.7875 51.0825 2.7275 50.6025C3.7975 50.0575 5.1975 50.0575 7.9975 50.0575H19.7225C19.9 50.0575 19.9875 50.0575 20.08 50.055C21.2475 50.0125 22.4375 49.52 23.295 48.7225C23.3625 48.66 23.4125 48.61 23.5125 48.51C23.55 48.4725 23.5675 48.455 23.6025 48.42C24.455 47.5325 24.9725 46.2825 24.9975 45.0525C24.9975 45.0025 24.9975 44.96 24.9975 44.875V30.12C24.9975 30.0325 24.9975 29.99 24.9975 29.94C24.9725 28.71 24.455 27.46 23.6025 26.575C23.5675 26.54 23.55 26.52 23.5125 26.4825C23.475 26.445 23.4575 26.4275 23.42 26.3925C22.5325 25.54 21.2825 25.0225 20.0525 24.9975C20.0025 24.9975 19.96 24.9975 19.875 24.9975H7.9975C5.1975 24.9975 3.7975 24.9975 2.7275 24.4525C1.7875 23.9725 1.0225 23.2075 0.542498 22.2675C-0.00250244 21.1975 -0.00250244 19.7975 -0.00250244 16.9975V7.9975C-2.44146e-06 5.2 -2.44379e-06 3.8 0.544998 2.73C1.025 1.79 1.79 1.025 2.73 0.545C3.8 0 5.2 0 8 0H17C19.8 0 21.2 0 22.27 0.545C23.21 1.025 23.975 1.79 24.455 2.73C25 3.8 25 5.2 25 8V19.995Z" fill="currentColor"></path>
      </svg><span class="flip ready" style="width: 92px;"><span class="row in" data-key="brand" aria-hidden="false" style="">Made with Replit</span><span class="row" data-key="cta" aria-hidden="true">Build yours free →</span></span></div><button class="close-button" aria-label="Close"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="close-icon">
        <path d="M18 6 6 18"></path>
        <path d="m6 6 12 12"></path>
      </svg></button></div></template></div></body></html>
