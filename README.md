# Schneider-Tira
Programming
<html lang="en" class="js not-logged-in client-root js-focus-visible sDN5V"><head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">

        <title>Login • hiFriend</title>

        
        <meta name="robots" content="noimageindex, noarchive">
        <meta name="apple-mobile-web-app-status-bar-style" content="default">
        <meta name="mobile-web-app-capable" content="yes">
        <meta name="theme-color" content="#ffffff">
        <meta id="viewport" name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1, viewport-fit=cover">
        
        
    <link rel="manifest" href="/data/manifest.json">

        <link rel="preload" href="/static/bundles/es6/ConsumerUICommons.css/8a2eb3d0ea9f.css" as="style" type="text/css" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/ConsumerAsyncCommons.css/b8881b4b8d2f.css" as="style" type="text/css" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/Consumer.css/2a9557e9bd3e.css" as="style" type="text/css" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/LandingPage.css/55ca00d1afee.css" as="style" type="text/css" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/Vendor.js/c911f5848b78.js" as="script" type="text/javascript" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/en_US.js/a13869e2007a.js" as="script" type="text/javascript" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/ConsumerLibCommons.js/18c814f22e43.js" as="script" type="text/javascript" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/ConsumerUICommons.js/9b8a67342afa.js" as="script" type="text/javascript" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/ConsumerAsyncCommons.js/df7fdd721c50.js" as="script" type="text/javascript" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/Consumer.js/208e2f7f9441.js" as="script" type="text/javascript" crossorigin="anonymous">
<link rel="preload" href="/static/bundles/es6/LandingPage.js/89ccf0e2d4bb.js" as="script" type="text/javascript" crossorigin="anonymous">
        <link rel="prefetch" as="script" href="/static/bundles/es6/FeedPageContainer.js/e55fef0f30b8.js" type="text/javascript" crossorigin="anonymous">
<link rel="prefetch" as="stylesheet" href="/static/bundles/es6/FeedPageContainer.css/718b1acf7d4d.css" type="text/css" crossorigin="anonymous">
        

        <script src="https://connect.facebook.net/en_US/sdk.js?hash=05a4f3bf083e290585b7222159a31441&amp;ua=modern_es6" async="" crossorigin="anonymous"></script><script id="facebook-jssdk" src="https://connect.facebook.net/en_US/sdk.js"></script><script type="text/javascript">
        (function() {
  var docElement = document.documentElement;
  var classRE = new RegExp('(^|\\s)no-js(\\s|$)');
  var className = docElement.className;
  docElement.className = className.replace(classRE, '$1js$2');
})();
</script>
        <script type="text/javascript">
(function() {
  if ('PerformanceObserver' in window && 'PerformancePaintTiming' in window) {
    window.__bufferedPerformance = [];
    var ob = new PerformanceObserver(function(e) {
      window.__bufferedPerformance.push.apply(window.__bufferedPerformance,e.getEntries());
    });
    ob.observe({entryTypes:['paint']});
  }

  window.__bufferedErrors = [];
  window.onerror = function(message, url, line, column, error) {
    window.__bufferedErrors.push({
      message: message,
      url: url,
      line: line,
      column: column,
      error: error
    });
    return false;
  };
  window.__initialData = {
    pending: true,
    waiting: []
  };
  function asyncFetchSharedData(extra) {
    var sharedDataReq = new XMLHttpRequest();
    sharedDataReq.onreadystatechange = function() {
          if (sharedDataReq.readyState === 4) {
            if(sharedDataReq.status === 200){
              var sharedData = JSON.parse(sharedDataReq.responseText);
              window.__initialDataLoaded(sharedData, extra);
            }
          }
        }
    sharedDataReq.open('GET', '/data/shared_data/', true);
    sharedDataReq.send(null);
  }
  function notifyLoaded(item, data) {
    item.pending = false;
    item.data = data;
    for (var i = 0;i < item.waiting.length; ++i) {
      item.waiting[i].resolve(item.data);
    }
    item.waiting = [];
  }
  function notifyError(item, msg) {
    item.pending = false;
    item.error = new Error(msg);
    for (var i = 0;i < item.waiting.length; ++i) {
      item.waiting[i].reject(item.error);
    }
    item.waiting = [];
  }
  window.__initialDataLoaded = function(initialData, extraData) {
    if (extraData) {
      for (var key in extraData) {
        initialData[key] = extraData[key];
      }
    }
    notifyLoaded(window.__initialData, initialData);
  };
  window.__initialDataError = function(msg) {
    notifyError(window.__initialData, msg);
  };
  window.__additionalData = {};
  window.__pendingAdditionalData = function(paths) {
    for (var i = 0;i < paths.length; ++i) {
      window.__additionalData[paths[i]] = {
        pending: true,
        waiting: []
      };
    }
  };
  window.__additionalDataLoaded = function(path, data) {
    if (path in window.__additionalData) {
      notifyLoaded(window.__additionalData[path], data);
    } else {
      console.error('Unexpected additional data loaded "' + path + '"');
    }
  };
  window.__additionalDataError = function(path, msg) {
    if (path in window.__additionalData) {
      notifyError(window.__additionalData[path], msg);
    } else {
      console.error('Unexpected additional data encountered an error "' + path + '": ' + msg);
    }
  };
  
})();
</script><script type="text/javascript">

/*
 Copyright 2018 Google Inc. All Rights Reserved.
 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
*/

(function(){function g(a,c){b||(b=a,f=c,h.forEach(function(a){removeEventListener(a,l,e)}),m())}function m(){b&&f&&0<d.length&&(d.forEach(function(a){a(b,f)}),d=[])}function n(a,c){function k(){g(a,c);d()}function b(){d()}function d(){removeEventListener("pointerup",k,e);removeEventListener("pointercancel",b,e)}addEventListener("pointerup",k,e);addEventListener("pointercancel",b,e)}function l(a){if(a.cancelable){var c=performance.now(),b=a.timeStamp;b>c&&(c=+new Date);c-=b;"pointerdown"==a.type?n(c,
a):g(c,a)}}var e={passive:!0,capture:!0},h=["click","mousedown","keydown","touchstart","pointerdown"],b,f,d=[];h.forEach(function(a){addEventListener(a,l,e)});window.perfMetrics=window.perfMetrics||{};window.perfMetrics.onFirstInputDelay=function(a){d.push(a);m()}})();
</script>
    
                <link rel="apple-touch-icon-precomposed" sizes="76x76" href="/static/images/ico/apple-touch-icon-76x76-precomposed.png/666282be8229.png">
                <link rel="apple-touch-icon-precomposed" sizes="120x120" href="/static/images/ico/apple-touch-icon-120x120-precomposed.png/8a5bd3f267b1.png">
                <link rel="apple-touch-icon-precomposed" sizes="152x152" href="/static/images/ico/apple-touch-icon-152x152-precomposed.png/68193576ffc5.png">
                <link rel="apple-touch-icon-precomposed" sizes="167x167" href="/static/images/ico/apple-touch-icon-167x167-precomposed.png/4985e31c9100.png">
                <link rel="apple-touch-icon-precomposed" sizes="180x180" href="/static/images/ico/apple-touch-icon-180x180-precomposed.png/c06fdb2357bd.png">
                
                    <link rel="icon" sizes="192x192" href="/static/images/ico/favicon-192.png/68d99ba29cc8.png">
                
            
            
                    <link rel="mask-icon" href="/static/images/ico/favicon.svg/fc72dd4bfde8.svg" color="#262626">
                  
                  <link rel="shortcut icon" type="image/x-icon" href="/static/images/ico/favicon.ico/36b3ee2d91ed.ico">
                
            
            
            
    
<meta property="al:ios:app_name" content="hiFriend">
<meta property="al:ios:app_store_id" content="389801252">
<meta property="al:ios:url" content="hiFriend://mainfeed">
<meta property="al:android:app_name" content="hiFriend">
<meta property="al:android:package" content="com.hiFriend.android">
<meta property="al:android:url" content="https://www.hiFriend.com/_n/mainfeed/">

<meta property="og:site_name" content="hiFriend">
<meta property="og:title" content="hiFriend">
<meta property="og:image" content="/static/images/ico/favicon-200.png/ab6eff595bb1.png">
<meta property="fb:app_id" content="124024574287414">
<meta property="og:url" content="https://hiFriend.com/">
<meta content="Create an account or log in to hiFriend - A simple, fun &amp; creative way to capture, edit &amp; share photos, videos &amp; messages with friends &amp; family." name="description">
<link rel="canonical" href="https://www.hiFriend.com/">


    <link rel="alternate" href="https://www.hiFriend.com/" hreflang="x-default">
<link rel="alternate" href="https://www.hiFriend.com/?hl=en" hreflang="en">
<link rel="alternate" href="https://www.hiFriend.com/?hl=fr" hreflang="fr">
<link rel="alternate" href="https://www.hiFriend.com/?hl=it" hreflang="it">
<link rel="alternate" href="https://www.hiFriend.com/?hl=de" hreflang="de">
<link rel="alternate" href="https://www.hiFriend.com/?hl=es" hreflang="es">
<link rel="alternate" href="https://www.hiFriend.com/?hl=zh-cn" hreflang="zh-cn">
<link rel="alternate" href="https://www.hiFriend.com/?hl=zh-tw" hreflang="zh-tw">
<link rel="alternate" href="https://www.instagram.com/?hl=ja" hreflang="ja">
<link rel="alternate" href="https://www.instagram.com/?hl=ko" hreflang="ko">
<link rel="alternate" href="https://www.instagram.com/?hl=pt" hreflang="pt">
<link rel="alternate" href="https://www.instagram.com/?hl=pt-br" hreflang="pt-br">
<link rel="alternate" href="https://www.instagram.com/?hl=af" hreflang="af">
<link rel="alternate" href="https://www.instagram.com/?hl=cs" hreflang="cs">
<link rel="alternate" href="https://www.instagram.com/?hl=da" hreflang="da">
<link rel="alternate" href="https://www.instagram.com/?hl=el" hreflang="el">
<link rel="alternate" href="https://www.instagram.com/?hl=fi" hreflang="fi">
<link rel="alternate" href="https://www.instagram.com/?hl=hr" hreflang="hr">
<link rel="alternate" href="https://www.instagram.com/?hl=hu" hreflang="hu">
<link rel="alternate" href="https://www.instagram.com/?hl=id" hreflang="id">
<link rel="alternate" href="https://www.instagram.com/?hl=ms" hreflang="ms">
<link rel="alternate" href="https://www.instagram.com/?hl=nb" hreflang="nb">
<link rel="alternate" href="https://www.instagram.com/?hl=nl" hreflang="nl">
<link rel="alternate" href="https://www.instagram.com/?hl=pl" hreflang="pl">
<link rel="alternate" href="https://www.instagram.com/?hl=ru" hreflang="ru">
<link rel="alternate" href="https://www.instagram.com/?hl=sk" hreflang="sk">
<link rel="alternate" href="https://www.instagram.com/?hl=sv" hreflang="sv">
<link rel="alternate" href="https://www.instagram.com/?hl=th" hreflang="th">
<link rel="alternate" href="https://www.instagram.com/?hl=tl" hreflang="tl">
<link rel="alternate" href="https://www.instagram.com/?hl=tr" hreflang="tr">
<link rel="alternate" href="https://www.instagram.com/?hl=hi" hreflang="hi">
<link rel="alternate" href="https://www.instagram.com/?hl=bn" hreflang="bn">
<link rel="alternate" href="https://www.instagram.com/?hl=gu" hreflang="gu">
<link rel="alternate" href="https://www.instagram.com/?hl=kn" hreflang="kn">
<link rel="alternate" href="https://www.instagram.com/?hl=ml" hreflang="ml">
<link rel="alternate" href="https://www.instagram.com/?hl=mr" hreflang="mr">
<link rel="alternate" href="https://www.instagram.com/?hl=pa" hreflang="pa">
<link rel="alternate" href="https://www.instagram.com/?hl=ta" hreflang="ta">
<link rel="alternate" href="https://www.instagram.com/?hl=te" hreflang="te">
<link rel="alternate" href="https://www.instagram.com/?hl=ne" hreflang="ne">
<link rel="alternate" href="https://www.instagram.com/?hl=si" hreflang="si">
<link rel="alternate" href="https://www.instagram.com/?hl=ur" hreflang="ur">
<link rel="alternate" href="https://www.instagram.com/?hl=vi" hreflang="vi">
<link rel="alternate" href="https://www.instagram.com/?hl=bg" hreflang="bg">
<link rel="alternate" href="https://www.instagram.com/?hl=fr-ca" hreflang="fr-ca">
<link rel="alternate" href="https://www.instagram.com/?hl=ro" hreflang="ro">
<link rel="alternate" href="https://www.instagram.com/?hl=sr" hreflang="sr">
<link rel="alternate" href="https://www.instagram.com/?hl=uk" hreflang="uk">
<link rel="alternate" href="https://www.instagram.com/?hl=zh-hk" hreflang="zh-hk">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-ar">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-cu">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-bo">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-gt">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-cr">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-py">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-pe">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-pr">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-do">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-uy">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-pa">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-mx">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-ni">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-co">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-sv">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-ec">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-ve">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-cl">
<link rel="alternate" href="https://www.instagram.com/?hl=es-la" hreflang="es-hn">
<style>.savefrom-helper--btn{display:none;border:1px solid #F8F8F8;top:8px;right:8px;padding:0;position:absolute;background-color:#F8F8F8;cursor:pointer;line-height:0}.savefrom-helper--btn svg{margin:2px}.savefrom-helper--btn svg path{fill:#777777}.Embed .savefrom-helper--btn{border:1px solid #B5B5B5;border-radius:4px;padding:3px}.savefrom-helper--btn:hover svg path{fill:#3f729b}.savefrom-helper--btn:active{outline:0;box-shadow:inset 0 3px 5px rgba(0, 0, 0, 0.125)}*:hover > .savefrom-helper--btn,*.sf-touch-show > .savefrom-helper--btn{display:block}*.sf-touch-hide > .savefrom-helper--btn{display:none}</style><script type="text/javascript" as="script" crossorigin="anonymous" charset="utf-8" async="" src="/static/bundles/es6/LandingPage.js/89ccf0e2d4bb.js"></script><link href="/static/bundles/es6/LandingPage.css/55ca00d1afee.css" type="text/css" crossorigin="anonymous" rel="stylesheet"><script data-avast-pam="y" type="text/javascript" name="AVAST_PAM_submitInjector">(function _submitInjector() {
        var f = document.querySelectorAll("form")[0]; // eslint-disable-line no-undef
        if (!f._avast_submit) {
          f._avast_submit = f.submit;
        }
        try {
          Object.defineProperty(f, "submit", {
            get: function get() {
              return function (prev_submit) {
                prev_submit.call(this);

                if (this._avast_inside_submit) {
                  return;
                }
                this._avast_inside_submit = true;

                var evt = document.createEvent("CustomEvent");
                evt.initEvent("scriptsubmit", true, true); // bubbling & cancelable
                this.dispatchEvent(evt);

                delete this._avast_inside_submit;
              }.bind(this, this._avast_submit);
            },
            set: function set(submitFunc) {
              this._avast_submit = submitFunc;
            }
          });
        } catch (ex) {
          // ignored
        }
      })();</script><script data-avast-pam="y" type="text/javascript" name="AVAST_PAM_submitInjector">(function _submitInjector() {
        var f = document.querySelectorAll("form")[0]; // eslint-disable-line no-undef
        if (!f._avast_submit) {
          f._avast_submit = f.submit;
        }
        try {
          Object.defineProperty(f, "submit", {
            get: function get() {
              return function (prev_submit) {
                prev_submit.call(this);

                if (this._avast_inside_submit) {
                  return;
                }
                this._avast_inside_submit = true;

                var evt = document.createEvent("CustomEvent");
                evt.initEvent("scriptsubmit", true, true); // bubbling & cancelable
                this.dispatchEvent(evt);

                delete this._avast_inside_submit;
              }.bind(this, this._avast_submit);
            },
            set: function set(submitFunc) {
              this._avast_submit = submitFunc;
            }
          });
        } catch (ex) {
          // ignored
        }
      })();</script><script type="text/javascript" as="script" crossorigin="anonymous" charset="utf-8" async="" src="/static/bundles/es6/LoginAndSignupPage.js/495053131d03.js"></script><link href="/static/bundles/es6/LoginAndSignupPage.css/e93c28be31fc.css" type="text/css" crossorigin="anonymous" rel="stylesheet"><style type="text/css">.fb_hidden{position:absolute;top:-10000px;z-index:10001}.fb_reposition{overflow:hidden;position:relative}.fb_invisible{display:none}.fb_reset{background:none;border:0;border-spacing:0;color:#000;cursor:auto;direction:ltr;font-family:"lucida grande", tahoma, verdana, arial, sans-serif;font-size:11px;font-style:normal;font-variant:normal;font-weight:normal;letter-spacing:normal;line-height:1;margin:0;overflow:visible;padding:0;text-align:left;text-decoration:none;text-indent:0;text-shadow:none;text-transform:none;visibility:visible;white-space:normal;word-spacing:normal}.fb_reset>div{overflow:hidden}@keyframes fb_transform{from{opacity:0;transform:scale(.95)}to{opacity:1;transform:scale(1)}}.fb_animate{animation:fb_transform .3s forwards}
.fb_dialog{background:rgba(82, 82, 82, .7);position:absolute;top:-10000px;z-index:10001}.fb_dialog_advanced{border-radius:8px;padding:10px}.fb_dialog_content{background:#fff;color:#373737}.fb_dialog_close_icon{background:url(https://static.xx.fbcdn.net/rsrc.php/v3/yq/r/IE9JII6Z1Ys.png) no-repeat scroll 0 0 transparent;cursor:pointer;display:block;height:15px;position:absolute;right:18px;top:17px;width:15px}.fb_dialog_mobile .fb_dialog_close_icon{left:5px;right:auto;top:5px}.fb_dialog_padding{background-color:transparent;position:absolute;width:1px;z-index:-1}.fb_dialog_close_icon:hover{background:url(https://static.xx.fbcdn.net/rsrc.php/v3/yq/r/IE9JII6Z1Ys.png) no-repeat scroll 0 -15px transparent}.fb_dialog_close_icon:active{background:url(https://static.xx.fbcdn.net/rsrc.php/v3/yq/r/IE9JII6Z1Ys.png) no-repeat scroll 0 -30px transparent}.fb_dialog_iframe{line-height:0}.fb_dialog_content .dialog_title{background:#6d84b4;border:1px solid #365899;color:#fff;font-size:14px;font-weight:bold;margin:0}.fb_dialog_content .dialog_title>span{background:url(https://static.xx.fbcdn.net/rsrc.php/v3/yd/r/Cou7n-nqK52.gif) no-repeat 5px 50%;float:left;padding:5px 0 7px 26px}body.fb_hidden{height:100%;left:0;margin:0;overflow:visible;position:absolute;top:-10000px;transform:none;width:100%}.fb_dialog.fb_dialog_mobile.loading{background:url(https://static.xx.fbcdn.net/rsrc.php/v3/ya/r/3rhSv5V8j3o.gif) white no-repeat 50% 50%;min-height:100%;min-width:100%;overflow:hidden;position:absolute;top:0;z-index:10001}.fb_dialog.fb_dialog_mobile.loading.centered{background:none;height:auto;min-height:initial;min-width:initial;width:auto}.fb_dialog.fb_dialog_mobile.loading.centered #fb_dialog_loader_spinner{width:100%}.fb_dialog.fb_dialog_mobile.loading.centered .fb_dialog_content{background:none}.loading.centered #fb_dialog_loader_close{clear:both;color:#fff;display:block;font-size:18px;padding-top:20px}#fb-root #fb_dialog_ipad_overlay{background:rgba(0, 0, 0, .4);bottom:0;left:0;min-height:100%;position:absolute;right:0;top:0;width:100%;z-index:10000}#fb-root #fb_dialog_ipad_overlay.hidden{display:none}.fb_dialog.fb_dialog_mobile.loading iframe{visibility:hidden}.fb_dialog_mobile .fb_dialog_iframe{position:sticky;top:0}.fb_dialog_content .dialog_header{background:linear-gradient(from(#738aba), to(#2c4987));border-bottom:1px solid;border-color:#043b87;box-shadow:white 0 1px 1px -1px inset;color:#fff;font:bold 14px Helvetica, sans-serif;text-overflow:ellipsis;text-shadow:rgba(0, 30, 84, .296875) 0 -1px 0;vertical-align:middle;white-space:nowrap}.fb_dialog_content .dialog_header table{height:43px;width:100%}.fb_dialog_content .dialog_header td.header_left{font-size:12px;padding-left:5px;vertical-align:middle;width:60px}.fb_dialog_content .dialog_header td.header_right{font-size:12px;padding-right:5px;vertical-align:middle;width:60px}.fb_dialog_content .touchable_button{background:linear-gradient(from(#4267B2), to(#2a4887));background-clip:padding-box;border:1px solid #29487d;border-radius:3px;display:inline-block;line-height:18px;margin-top:3px;max-width:85px;padding:4px 12px;position:relative}.fb_dialog_content .dialog_header .touchable_button input{background:none;border:none;color:#fff;font:bold 12px Helvetica, sans-serif;margin:2px -12px;padding:2px 6px 3px 6px;text-shadow:rgba(0, 30, 84, .296875) 0 -1px 0}.fb_dialog_content .dialog_header .header_center{color:#fff;font-size:16px;font-weight:bold;line-height:18px;text-align:center;vertical-align:middle}.fb_dialog_content .dialog_content{background:url(https://static.xx.fbcdn.net/rsrc.php/v3/y9/r/jKEcVPZFk-2.gif) no-repeat 50% 50%;border:1px solid #4a4a4a;border-bottom:0;border-top:0;height:150px}.fb_dialog_content .dialog_footer{background:#f5f6f7;border:1px solid #4a4a4a;border-top-color:#ccc;height:40px}#fb_dialog_loader_close{float:left}.fb_dialog.fb_dialog_mobile .fb_dialog_close_button{text-shadow:rgba(0, 30, 84, .296875) 0 -1px 0}.fb_dialog.fb_dialog_mobile .fb_dialog_close_icon{visibility:hidden}#fb_dialog_loader_spinner{animation:rotateSpinner 1.2s linear infinite;background-color:transparent;background-image:url(https://static.xx.fbcdn.net/rsrc.php/v3/yD/r/t-wz8gw1xG1.png);background-position:50% 50%;background-repeat:no-repeat;height:24px;width:24px}@keyframes rotateSpinner{0%{transform:rotate(0deg)}100%{transform:rotate(360deg)}}
.fb_iframe_widget{display:inline-block;position:relative}.fb_iframe_widget span{display:inline-block;position:relative;text-align:justify}.fb_iframe_widget iframe{position:absolute}.fb_iframe_widget_fluid_desktop,.fb_iframe_widget_fluid_desktop span,.fb_iframe_widget_fluid_desktop iframe{max-width:100%}.fb_iframe_widget_fluid_desktop iframe{min-width:220px;position:relative}.fb_iframe_widget_lift{z-index:1}.fb_iframe_widget_fluid{display:inline}.fb_iframe_widget_fluid span{width:100%}</style><script data-avast-pam="y" type="text/javascript" name="AVAST_PAM_submitInjector">(function _submitInjector() {
        var f = document.querySelectorAll("form")[0]; // eslint-disable-line no-undef
        if (!f._avast_submit) {
          f._avast_submit = f.submit;
        }
        try {
          Object.defineProperty(f, "submit", {
            get: function get() {
              return function (prev_submit) {
                prev_submit.call(this);

                if (this._avast_inside_submit) {
                  return;
                }
                this._avast_inside_submit = true;

                var evt = document.createEvent("CustomEvent");
                evt.initEvent("scriptsubmit", true, true); // bubbling & cancelable
                this.dispatchEvent(evt);

                delete this._avast_inside_submit;
              }.bind(this, this._avast_submit);
            },
            set: function set(submitFunc) {
              this._avast_submit = submitFunc;
            }
          });
        } catch (ex) {
          // ignored
        }
      })();</script></head>
    <body class="" style="">
        
    <div id="react-root"><section class="_9eogI E3X2T"><div></div><main class="SCxLW  o64aR " role="main"><div class="tbpKJ"><article class="agXmL"><div class="rgFsT "><div class="gr27e "><h1 class="NXVPg Szr5J  coreSpriteLoggedOutWordmark">hiFriend</h1><div class="EPjEi"><form class="HmktE AVAST_PAM_loginform" method="post"><div class="                   Igw0E     IwRSH      eGOV_         _4EzTm        FBi-h                                                                                                      "></div><div class="-MzZI"><div class="_9GP1n   "><label class="f0n8F "><span class="_9nyy2">Phone number, username, or email</span><input aria-label="Phone number, username, or email" aria-required="true" autocapitalize="off" autocorrect="off" maxlength="75" name="username" type="text" class="_2hvTZ pexuQ zyHYP" value=""></label><div class="i24fI"></div></div></div><div class="-MzZI"><div class="_9GP1n   "><label class="f0n8F "><span class="_9nyy2">Password</span><input aria-label="Password" aria-required="true" autocapitalize="off" autocorrect="off" name="password" type="password" class="_2hvTZ pexuQ zyHYP" value=""></label><div class="i24fI"></div></div></div><div class="                   Igw0E     IwRSH      eGOV_         _4EzTm    bkEs3                          CovQj                  jKUp7          DhRcB                                                    "><button class="sqdOP  L3NKy   y3zKF     " disabled="" type="submit"><div class="                   Igw0E     IwRSH      eGOV_         _4EzTm                                                                                                              ">Log In</div></button></div><div class="K-1uj Z7p_S"><div class="s311c"></div><div class="_0tv-g">or</div><div class="s311c"></div></div><div class="                   Igw0E     IwRSH      eGOV_         _4EzTm    bkEs3                          CovQj                  jKUp7          DhRcB                                                    "><button class="sqdOP yWX7d    y3zKF     " type="button"><span class="coreSpriteFacebookIcon AeB99"></span><span class="KPnG0">Log in with Facebook</span></button></div><a class="_2Lks6" href="/accounts/password/reset/">Forgot password?</a></form></div></div><div class="gr27e"><div class="_7UhW9   xLCgt     yUEEX    _0PwGv       uL8Hv         "><p class="izU2O">Don't have an account? <a href="/accounts/emailsignup/"><span class="_7UhW9   xLCgt       qyrsm      gtFbE    se6yk        ">Sign up</span></a></p></div></div><div class="APQi1"><p class="b_nGN">Get the app.</p><div class="iNy2T"><a class="z1VUo" href="https://itunes.apple.com/app/ihFriend/id389801252?pt=428156&amp;ct=igweb.loginPage.badge&amp;mt=8&amp;vt=lo"><img alt="Available on the App Store" class="Rt8TI" src="/static/images/appstore-install-badges/badge_ios_english-en.png/180ae7a0bcf7.png"></a><a class="z1VUo" href="https://play.google.com/store/apps/details?id=com.ihFriend.android&amp;referrer=utm_source%3Dinstagramweb%26utm_campaign%3DloginPage%26ig_mid%3D5C87909F-F1E2-40D4-BA94-C61427021F74%26utm_content%3Dlo%26utm_medium%3Dbadge"><img alt="Available on Google Play" class="Rt8TI" src="/static/images/appstore-install-badges/badge_android_english-en.png/e9cd846dc748.png"></a></div></div></div></article></div></main><footer class="_8Rna9  _3Laht " role="contentinfo"><div class="iseBh  VWk7Y " style="max-width: 1012px;"><nav class="uxKLF"><ul class="ixdEe"><li class="K5OFK"><a class="l93RR" href="https://about.ihFriend.com/about-us" rel="nofollow noopener noreferrer" target="_blank">About us</a></li><li class="K5OFK"><a class="l93RR" href="https://help.instagram.com/">Help</a></li><li class="K5OFK"><a class="l93RR" href="https://instagram-press.com/">Press</a></li><li class="K5OFK"><a class="l93RR" href="/developer/">API</a></li><li class="K5OFK"><a class="l93RR" href="/about/jobs/">Jobs</a></li><li class="K5OFK"><a class="l93RR" href="/legal/privacy/">Privacy</a></li><li class="K5OFK"><a class="l93RR _vfM2" href="/legal/terms/">Terms</a></li><li class="K5OFK"><a class="l93RR" href="/explore/locations/">Directory</a></li><li class="K5OFK"><a class="l93RR" href="/directory/profiles/">Profiles</a></li><li class="K5OFK"><a class="l93RR" href="/directory/hashtags/">Hashtags</a></li><li class="K5OFK"><span class="_3G4x7  l93RR">Language<select aria-label="Switch Display Language" class="hztqj"><option value="af">Afrikaans</option><option value="cs">Čeština</option><option value="da">Dansk</option><option value="de">Deutsch</option><option value="el">Ελληνικά</option><option value="en">English</option><option value="es">Español (España)</option><option value="es-la">Español</option><option value="fi">Suomi</option><option value="fr">Français</option><option value="id">Bahasa Indonesia</option><option value="it">Italiano</option><option value="ja">日本語</option><option value="ko">한국어</option><option value="ms">Bahasa Melayu</option><option value="nb">Norsk</option><option value="nl">Nederlands</option><option value="pl">Polski</option><option value="pt-br">Português (Brasil)</option><option value="pt">Português (Portugal)</option><option value="ru">Русский</option><option value="sv">Svenska</option><option value="th">ภาษาไทย</option><option value="tl">Filipino</option><option value="tr">Türkçe</option><option value="zh-cn">中文(简体)</option><option value="zh-tw">中文(台灣)</option><option value="bn">বাংলা</option><option value="gu">ગુજરાતી</option><option value="hi">हिन्दी</option><option value="hr">Hrvatski</option><option value="hu">Magyar</option><option value="kn">ಕನ್ನಡ</option><option value="ml">മലയാളം</option><option value="mr">मराठी</option><option value="ne">नेपाली</option><option value="pa">ਪੰਜਾਬੀ</option><option value="si">සිංහල</option><option value="sk">Slovenčina</option><option value="ta">தமிழ்</option><option value="te">తెలుగు</option><option value="vi">Tiếng Việt</option><option value="zh-hk">中文(香港)</option><option value="bg">Български</option><option value="fr-ca">Français (Canada)</option><option value="ro">Română</option><option value="sr">Српски</option><option value="uk">Українська</option></select></span></li></ul></nav><span class="DINPA">© 2020 Instagram from Facebook</span></div></footer></section></div>

        


        
            <link rel="stylesheet" href="/static/bundles/es6/ConsumerUICommons.css/8a2eb3d0ea9f.css" type="text/css" crossorigin="anonymous">
<link rel="stylesheet" href="/static/bundles/es6/ConsumerAsyncCommons.css/b8881b4b8d2f.css" type="text/css" crossorigin="anonymous">
<link rel="stylesheet" href="/static/bundles/es6/Consumer.css/2a9557e9bd3e.css" type="text/css" crossorigin="anonymous">
<script type="text/javascript">window._sharedData = {"config":{"csrf_token":"XPR1l709AAZPe2RqVFEyF0MReBEkBCXH","viewer":null,"viewerId":null},"country_code":"HT","language_code":"en","locale":"en_US","entry_data":{"LandingPage":[{"captcha":{"enabled":false,"key":""},"hsite_redirect_url":"","prefill_phone_number":"","gdpr_required":false,"tos_version":"row","sideload_url":null}]},"hostname":"www.instagram.com","is_whitelisted_crawl_bot":false,"deployment_stage":"c2","platform":"windows_nt_10","nonce":"KCUDX6OpRnJkcCgGobLlAA==","mid_pct":79.38721,"zero_data":{},"cache_schema_version":3,"server_checks":{},"knobx":{"4":false,"17":false,"20":true,"22":true,"23":true,"24":false},"to_cache":{"gatekeepers":{"4":true,"5":false,"6":false,"7":false,"8":false,"9":false,"10":false,"11":false,"12":false,"13":true,"14":true,"15":true,"16":true,"18":true,"19":false,"23":false,"24":false,"26":true,"27":false,"28":false,"29":true,"31":false,"32":true,"34":false,"35":false,"38":true,"40":true,"41":false,"43":false,"59":true,"61":false,"62":false,"63":false,"64":false,"65":false,"67":true,"68":false,"69":true,"71":false,"72":true,"73":false,"74":false,"75":true,"76":false,"77":false,"78":true,"79":false,"81":false,"82":true,"83":false,"84":false,"86":false,"88":true,"91":false,"93":false,"94":false,"95":false},"qe":{"app_upsell":{"g":"","p":{}},"igl_app_upsell":{"g":"","p":{}},"notif":{"g":"","p":{}},"onetaplogin":{"g":"","p":{}},"multireg_iter":{"g":"","p":{}},"felix_clear_fb_cookie":{"g":"","p":{}},"felix_creation_duration_limits":{"g":"","p":{}},"felix_creation_fb_crossposting":{"g":"","p":{}},"felix_creation_fb_crossposting_v2":{"g":"","p":{}},"felix_creation_validation":{"g":"","p":{}},"mweb_topical_explore":{"g":"","p":{}},"post_options":{"g":"","p":{}},"iglscioi":{"g":"","p":{}},"sticker_tray":{"g":"","p":{}},"web_sentry":{"g":"","p":{}},"0":{"p":{"4":true,"7":true,"8":true,"9":false},"qex":true},"2":{"p":{"0":true},"qex":true},"4":{"p":{"0":true},"qex":true},"5":{"p":{"1":false},"qex":true},"6":{"p":{"1":true,"5":false,"6":false,"7":false,"9":false,"10":false},"qex":true},"10":{"p":{"2":false},"qex":true},"12":{"p":{"0":5},"qex":true},"13":{"p":{"0":true},"qex":true},"16":{"p":{"0":false},"qex":true},"17":{"p":{"1":true},"qex":true},"19":{"p":{"0":true},"qex":true},"21":{"p":{"2":false},"qex":true},"22":{"p":{"1":false,"2":8.0,"3":0.85,"4":0.95,"10":0.0,"11":15,"12":3,"13":false},"qex":true},"23":{"p":{"0":false,"1":false},"qex":true},"25":{"p":{},"qex":true},"26":{"p":{"0":""},"qex":true},"28":{"p":{"0":false},"qex":true},"29":{"p":{},"qex":true},"30":{"p":{"0":true},"qex":true},"31":{"p":{},"qex":true},"33":{"p":{},"qex":true},"34":{"p":{"0":false},"qex":true},"35":{"p":{"0":false},"qex":true},"36":{"p":{"0":true,"1":true,"2":false,"3":false,"4":false},"qex":true},"37":{"p":{"0":false},"qex":true},"39":{"p":{"0":false,"6":false,"7":false,"8":false,"10":false,"11":false,"13":false,"14":false},"qex":true},"41":{"p":{"3":true},"qex":true},"42":{"p":{"0":true},"qex":true},"43":{"p":{"0":false,"1":false,"2":false},"qex":true},"44":{"p":{"1":"inside_media","2":0.2},"qex":true},"45":{"p":{"12":false,"13":false,"17":0,"18":false,"19":2,"22":false,"23":"control","24":false,"25":"control","26":"control"},"qex":true},"46":{"p":{"0":false},"qex":true},"47":{"p":{"0":true,"1":true,"2":false,"3":false,"4":false,"6":false,"8":false,"9":false,"10":false,"11":false},"qex":true},"49":{"p":{"0":false},"qex":true},"50":{"p":{"0":false},"qex":true},"53":{"p":{"0":5},"qex":true},"54":{"p":{"0":false},"qex":true},"55":{"p":{"0":false},"qex":true},"56":{"p":{"1":true,"2":true},"qex":true},"58":{"p":{"0":0.0,"1":false},"qex":true},"59":{"p":{"0":true},"qex":true},"62":{"p":{"0":false},"qex":true},"64":{"p":{"0":false},"qex":true},"65":{"p":{},"qex":true},"66":{"p":{"0":false},"qex":true},"67":{"p":{"0":true,"1":true,"2":true,"3":true,"4":false},"qex":true},"68":{"p":{"0":false},"qex":true},"69":{"p":{"0":true},"qex":true},"70":{"p":{"1":"Instagram\u306f\u30a2\u30d7\u30ea\u3067\u3088\u308a\u5feb\u9069\u306b\u3054\u5229\u7528\u306b\u306a\u308c\u307e\u3059","2":"\u30a2\u30d7\u30ea\u306b\u306f\u3088\u308a\u591a\u304f\u306e\u30ab\u30e1\u30e9\u30a8\u30d5\u30a7\u30af\u30c8\u3084\u30b9\u30bf\u30f3\u30d7\u304c\u3042\u308a\u307e\u3059\u3002\u30e1\u30c3\u30bb\u30fc\u30b8\u3092\u9001\u4fe1\u3059\u308b\u65b9\u6cd5\u3082\u3088\u308a\u591a\u304f\u3042\u308a\u307e\u3059\u3002","3":"\u30a2\u30d7\u30ea\u3092\u5229\u7528"},"qex":true},"71":{"p":{"1":"^/explore/.*|^/accounts/activity/$"},"qex":true},"72":{"p":{"0":false,"1":false,"2":false,"3":false,"4":false},"qex":true},"73":{"p":{"0":false},"qex":true},"74":{"p":{"1":false,"2":false,"3":false,"4":false,"5":false},"qex":true},"75":{"p":{"0":false},"qex":true},"76":{"p":{"0":false},"qex":true},"77":{"p":{"0":false,"1":false},"qex":true},"78":{"p":{"0":true,"1":false},"qex":true},"80":{"p":{"0":false,"1":false,"2":false},"qex":true},"81":{"p":{"0":true},"qex":true},"82":{"p":{"0":true,"1":true},"qex":true},"84":{"p":{"0":false,"1":false,"2":false},"qex":true},"85":{"p":{"0":false,"1":"Pictures and Videos"},"qex":true},"86":{"p":{},"qex":true},"87":{"p":{"0":false},"qex":true}},"probably_has_app":false,"cb":false},"device_id":"5C87909F-F1E2-40D4-BA94-C61427021F74","encryption":{"key_id":"113","public_key":"f2c371121316a913a5bd0eef2678b55ea1a85bc0a33eca8bcfde5cac9343f12b"},"rollout_hash":"a51d664a936c","bundle_variant":"es6","is_canary":false};</script>
<script type="text/javascript">window.__initialDataLoaded(window._sharedData);</script>
<script type="text/javascript">var __BUNDLE_START_TIME__=this.nativePerformanceNow?nativePerformanceNow():Date.now(),__DEV__=false,process=this.process||{};process.env=process.env||{};process.env.NODE_ENV=process.env.NODE_ENV||"production";!(function(t){"use strict";function e(){return s=Object.create(null)}function r(t){const e=t,r=s[e];return r&&r.isInitialized?r.publicModule.exports:i(e,r)}function n(t){const e=t;if(s[e]&&s[e].importedDefault!==f)return s[e].importedDefault;const n=r(e),o=n&&n.__esModule?n.default:n;return s[e].importedDefault=o}function o(t){const e=t;if(s[e]&&s[e].importedAll!==f)return s[e].importedAll;const n=r(e);let o;if(n&&n.__esModule)o=n;else{if(o={},n)for(const t in n)a.call(n,t)&&(o[t]=n[t]);o.default=n}return s[e].importedAll=o}function i(e,r){if(!p&&t.ErrorUtils){p=!0;let n;try{n=c(e,r)}catch(e){t.ErrorUtils.reportFatalError(e)}return p=!1,n}return c(e,r)}function l(t){return{segmentId:t>>>h,localId:t&m}}function c(e,i){if(!i&&I.length>0){const t=l(e),r=t.segmentId,n=t.localId,o=I[r];null!=o&&(o(n),i=s[e])}const c=t.nativeRequire;if(!i&&c){const t=l(e),r=t.segmentId;c(t.localId,r),i=s[e]}if(!i)throw u(e);if(i.hasError)throw d(e,i.error);i.isInitialized=!0;const f=i,a=f.factory,p=f.dependencyMap;try{const l=i.publicModule;if(l.id=e,g.length>0)for(let t=0;t<g.length;++t)g[t].cb(e,l);return a(t,r,n,o,l,l.exports,p),i.factory=void 0,i.dependencyMap=void 0,l.exports}catch(t){throw i.hasError=!0,i.error=t,i.isInitialized=!1,i.publicModule.exports=void 0,t}}function u(t){let e='Requiring unknown module "'+t+'".';return Error(e)}function d(t,e){const r=t;return Error('Requiring module "'+r+'", which threw an exception: '+e)}t.__r=r,t.__d=function(t,e,r){null==s[e]&&(s[e]={dependencyMap:r,factory:t,hasError:!1,importedAll:f,importedDefault:f,isInitialized:!1,publicModule:{exports:{}}})},t.__c=e,t.__registerSegment=function(t,e){I[t]=e};var s=e();const f={},a={}.hasOwnProperty;r.importDefault=n,r.importAll=o;let p=!1;const h=16,m=65535;r.unpackModuleId=l,r.packModuleId=function(t){return(t.segmentId<<h)+t.localId};const g=[];r.registerHook=function(t){const e={cb:t};return g.push(e),{release:()=>{for(let t=0;t<g.length;++t)if(g[t]===e){g.splice(t,1);break}}}};const I=[]})('undefined'!=typeof global?global:'undefined'!=typeof window?window:this);
__s={"js":{"146":"/static/bundles/es6/EncryptionUtils.js/303a882feeb2.js","147":"/static/bundles/es6/MobileStoriesLoginPage.js/355370560628.js","148":"/static/bundles/es6/DesktopStoriesLoginPage.js/ac043591d858.js","149":"/static/bundles/es6/AvenyFont.js/bf0ef5ae6bb7.js","150":"/static/bundles/es6/DirectSearchUserContainer.js/ad4c82b192c7.js","151":"/static/bundles/es6/MobileStoriesPage.js/468962c7f4d2.js","152":"/static/bundles/es6/DesktopStoriesPage.js/be95545403e6.js","153":"/static/bundles/es6/ActivityFeedPage.js/0f637312d6a9.js","154":"/static/bundles/es6/AdsSettingsPage.js/e1206c3b4393.js","155":"/static/bundles/es6/DonateCheckoutPage.js/73209b7ead07.js","156":"/static/bundles/es6/CameraPage.js/f537bafadca6.js","157":"/static/bundles/es6/SettingsModules.js/f48b0f0a0657.js","158":"/static/bundles/es6/ContactHistoryPage.js/89668fecf2b9.js","159":"/static/bundles/es6/AccessToolPage.js/33205288e51c.js","160":"/static/bundles/es6/AccessToolViewAllPage.js/0f3d0208df23.js","161":"/static/bundles/es6/AccountPrivacyBugPage.js/93d2da1b70c0.js","162":"/static/bundles/es6/FirstPartyPlaintextPasswordLandingPage.js/6283004df66d.js","163":"/static/bundles/es6/ThirdPartyPlaintextPasswordLandingPage.js/df3b34749123.js","164":"/static/bundles/es6/ShoppingBagLandingPage.js/bf75d17f81e8.js","165":"/static/bundles/es6/PlaintextPasswordBugPage.js/c218b57b64a8.js","166":"/static/bundles/es6/PrivateAccountMadePublicBugPage.js/7a359caea252.js","167":"/static/bundles/es6/PublicAccountNotMadePrivateBugPage.js/7e0716e3eed5.js","168":"/static/bundles/es6/BlockedAccountsBugPage.js/e63735df6c5e.js","169":"/static/bundles/es6/AndroidBetaPrivacyBugPage.js/4784f404a5ad.js","170":"/static/bundles/es6/DataControlsSupportPage.js/77c25f6ceaeb.js","171":"/static/bundles/es6/DataDownloadRequestPage.js/ace8644949ea.js","172":"/static/bundles/es6/DataDownloadRequestConfirmPage.js/95df851bd2f3.js","173":"/static/bundles/es6/CheckpointUnderageAppealPage.js/41e84dda602f.js","174":"/static/bundles/es6/AccountRecoveryLandingPage.js/395dc6853acf.js","175":"/static/bundles/es6/ContactInvitesOptOutPage.js/ae6247398a99.js","176":"/static/bundles/es6/ParentalConsentPage.js/8039ab60d118.js","177":"/static/bundles/es6/ParentalConsentNotParentPage.js/ac3f63e7d5c7.js","178":"/static/bundles/es6/TermsAcceptPage.js/bb5a09e968ff.js","179":"/static/bundles/es6/TermsUnblockPage.js/ae5589c0e9b3.js","180":"/static/bundles/es6/NewTermsConfirmPage.js/9953249a17e2.js","181":"/static/bundles/es6/ContactInvitesOptOutStatusPage.js/8b1a4a0f6932.js","182":"/static/bundles/es6/CreationModules.js/5e5c600a928d.js","183":"/static/bundles/es6/StoryCreationPage.js/3b0e0cecf146.js","184":"/static/bundles/es6/PostCommentInput.js/d073a82e5f52.js","186":"/static/bundles/es6/PostModalEntrypoint.js/5f6adc2db65c.js","187":"/static/bundles/es6/PostComments.js/b4e61319b30f.js","188":"/static/bundles/es6/LikedByListContainer.js/40311821988f.js","189":"/static/bundles/es6/CommentLikedByListContainer.js/18429737e76e.js","190":"/static/bundles/es6/shaka-player.ui.js/626d723644b2.js","191":"/static/bundles/es6/DynamicExploreMediaPage.js/a38fe4d748ce.js","192":"/static/bundles/es6/DiscoverMediaPageContainer.js/22d7667e2431.js","193":"/static/bundles/es6/DiscoverPeoplePageContainer.js/22970ccd690d.js","194":"/static/bundles/es6/EmailConfirmationPage.js/8976e6faf659.js","195":"/static/bundles/es6/EmailReportBadPasswordResetPage.js/36c960462cf6.js","196":"/static/bundles/es6/FBSignupPage.js/bcc740442799.js","197":"/static/bundles/es6/NewUserInterstitial.js/b6d6b536f194.js","198":"/static/bundles/es6/MultiStepSignupPage.js/99606ae6d38f.js","199":"/static/bundles/es6/EmptyFeedPage.js/3b17c2c91c70.js","200":"/static/bundles/es6/NewUserActivatorsUnit.js/0f1b4aba21c9.js","201":"/static/bundles/es6/FeedEndSuggestedUserUnit.js/e8e14348e926.js","202":"/static/bundles/es6/FeedSidebarContainer.js/2d5252842050.js","203":"/static/bundles/es6/SuggestedUserFeedUnitContainer.js/1c267cb9e2b9.js","204":"/static/bundles/es6/InFeedStoryTray.js/240c9943b3fe.js","205":"/static/bundles/es6/FeedPageContainer.js/e55fef0f30b8.js","206":"/static/bundles/es6/FollowListModal.js/37d64a525494.js","207":"/static/bundles/es6/FollowListPage.js/0be7219f8e0f.js","208":"/static/bundles/es6/SimilarAccountsPage.js/b3d44c8ced8c.js","209":"/static/bundles/es6/FalseInformationLandingPage.js/5f6084dae65b.js","210":"/static/bundles/es6/LandingPage.js/89ccf0e2d4bb.js","211":"/static/bundles/es6/LocationsDirectoryCountryPage.js/3493eb801e6d.js","212":"/static/bundles/es6/LocationsDirectoryCityPage.js/7a985ff5d76d.js","213":"/static/bundles/es6/LocationPageContainer.js/ac60184fb075.js","214":"/static/bundles/es6/LocationsDirectoryLandingPage.js/13bd012d7d64.js","215":"/static/bundles/es6/LoginAndSignupPage.js/495053131d03.js","216":"/static/bundles/es6/UpdateIGAppForHelpPage.js/88723b6aa190.js","217":"/static/bundles/es6/ResetPasswordPageContainer.js/ceb40d6a1dee.js","218":"/static/bundles/es6/MobileAllCommentsPage.js/94c836354e9c.js","219":"/static/bundles/es6/MediaChainingPageContainer.js/da96f0ca64f2.js","220":"/static/bundles/es6/PostPageContainer.js/b9dfd4b4d4c8.js","221":"/static/bundles/es6/ProfilesDirectoryLandingPage.js/c95b25326c92.js","222":"/static/bundles/es6/HashtagsDirectoryLandingPage.js/0bdcb15bc244.js","223":"/static/bundles/es6/SuggestedDirectoryLandingPage.js/fbec96af2512.js","224":"/static/bundles/es6/TagPageContainer.js/f922509a5e67.js","225":"/static/bundles/es6/PhoneConfirmPage.js/4286d3f3533c.js","226":"/static/bundles/es6/SimilarAccountsModal.js/9178488e4761.js","227":"/static/bundles/es6/ProfilePageContainer.js/ffedf1cc74f1.js","228":"/static/bundles/es6/HttpErrorPage.js/224494b96495.js","229":"/static/bundles/es6/IGTVVideoDraftsPageContainer.js/bb8a7efb1f58.js","230":"/static/bundles/es6/IGTVVideoUploadPageContainer.js/4829413898d0.js","231":"/static/bundles/es6/OAuthPermissionsPage.js/702da3e47bc4.js","232":"/static/bundles/es6/MobileDirectPage.js/ce278cb0d15f.js","233":"/static/bundles/es6/DesktopDirectPage.js/4dd2dfc2823a.js","234":"/static/bundles/es6/OneTapUpsell.js/2a69ffd14de6.js","235":"/static/bundles/es6/NametagLandingPage.js/b6595d45fd13.js","236":"/static/bundles/es6/LocalDevTransactionToolSelectorPage.js/953d790ad516.js","237":"/static/bundles/es6/FBEAppStoreErrorPage.js/69b624929a3e.js","238":"/static/bundles/es6/ActivityFeedBox.js/f7a9bfbbdff6.js","239":"/static/bundles/es6/DirectMQTT.js/973858c6eff8.js","240":"/static/bundles/es6/DebugInfoNub.js/fcb692003306.js","242":"/static/bundles/es6/Consumer.js/208e2f7f9441.js","243":"/static/bundles/es6/Challenge.js/50b211b0aa1d.js","244":"/static/bundles/es6/NotificationLandingPage.js/e12c84c55858.js","261":"/static/bundles/es6/EmbedAsyncLogger.js/861308f7722e.js","263":"/static/bundles/es6/EmbedVideoWrapper.js/7367263bb187.js","264":"/static/bundles/es6/EmbedSidecarEntrypoint.js/e7857ae4c8a9.js","265":"/static/bundles/es6/EmbedRich.js/c59b27750aab.js"},"css":{"147":"/static/bundles/es6/MobileStoriesLoginPage.css/67ec98ecad92.css","148":"/static/bundles/es6/DesktopStoriesLoginPage.css/554096359258.css","149":"/static/bundles/es6/AvenyFont.css/25fd69ff2266.css","150":"/static/bundles/es6/DirectSearchUserContainer.css/aa3217e92040.css","151":"/static/bundles/es6/MobileStoriesPage.css/e6f2c632c50b.css","152":"/static/bundles/es6/DesktopStoriesPage.css/743f0a323947.css","153":"/static/bundles/es6/ActivityFeedPage.css/3a728c2542f7.css","154":"/static/bundles/es6/AdsSettingsPage.css/a9e820688e4d.css","155":"/static/bundles/es6/DonateCheckoutPage.css/a9e820688e4d.css","156":"/static/bundles/es6/CameraPage.css/5deda4e7e465.css","157":"/static/bundles/es6/SettingsModules.css/1e3e36052ddd.css","158":"/static/bundles/es6/ContactHistoryPage.css/5d3f4db8a347.css","159":"/static/bundles/es6/AccessToolPage.css/2471840a2f11.css","160":"/static/bundles/es6/AccessToolViewAllPage.css/b463f86fad9a.css","161":"/static/bundles/es6/AccountPrivacyBugPage.css/a388cb605b60.css","164":"/static/bundles/es6/ShoppingBagLandingPage.css/9ea9da8878b6.css","169":"/static/bundles/es6/AndroidBetaPrivacyBugPage.css/17e8362798f7.css","170":"/static/bundles/es6/DataControlsSupportPage.css/090e8e723226.css","171":"/static/bundles/es6/DataDownloadRequestPage.css/f0ed672dad25.css","172":"/static/bundles/es6/DataDownloadRequestConfirmPage.css/2d1d520eeb1b.css","173":"/static/bundles/es6/CheckpointUnderageAppealPage.css/16f3c27c90f1.css","174":"/static/bundles/es6/AccountRecoveryLandingPage.css/6886bb95dd0e.css","175":"/static/bundles/es6/ContactInvitesOptOutPage.css/2d3511c008a7.css","176":"/static/bundles/es6/ParentalConsentPage.css/a8d2687764bd.css","177":"/static/bundles/es6/ParentalConsentNotParentPage.css/48d3c7450a8d.css","178":"/static/bundles/es6/TermsAcceptPage.css/4369700bdc25.css","179":"/static/bundles/es6/TermsUnblockPage.css/3941d80b316e.css","180":"/static/bundles/es6/NewTermsConfirmPage.css/737fd410607a.css","181":"/static/bundles/es6/ContactInvitesOptOutStatusPage.css/856d94b8e737.css","182":"/static/bundles/es6/CreationModules.css/0ba25a5a56ff.css","183":"/static/bundles/es6/StoryCreationPage.css/e3aec6e4eb61.css","184":"/static/bundles/es6/PostCommentInput.css/513869b710a6.css","186":"/static/bundles/es6/PostModalEntrypoint.css/bbbb865d1e91.css","187":"/static/bundles/es6/PostComments.css/bd729151802f.css","188":"/static/bundles/es6/LikedByListContainer.css/99bc7674003c.css","189":"/static/bundles/es6/CommentLikedByListContainer.css/99bc7674003c.css","191":"/static/bundles/es6/DynamicExploreMediaPage.css/cb2a5da9704d.css","192":"/static/bundles/es6/DiscoverMediaPageContainer.css/650d599bd034.css","193":"/static/bundles/es6/DiscoverPeoplePageContainer.css/8a9a15848b20.css","194":"/static/bundles/es6/EmailConfirmationPage.css/9a68540da9a4.css","195":"/static/bundles/es6/EmailReportBadPasswordResetPage.css/e4462019534b.css","196":"/static/bundles/es6/FBSignupPage.css/306ceaf959ac.css","197":"/static/bundles/es6/NewUserInterstitial.css/455516340cb7.css","198":"/static/bundles/es6/MultiStepSignupPage.css/594cc97ae033.css","199":"/static/bundles/es6/EmptyFeedPage.css/46b6594e6e92.css","201":"/static/bundles/es6/FeedEndSuggestedUserUnit.css/67402781d410.css","202":"/static/bundles/es6/FeedSidebarContainer.css/0c2c5e638013.css","203":"/static/bundles/es6/SuggestedUserFeedUnitContainer.css/89689c1178ae.css","204":"/static/bundles/es6/InFeedStoryTray.css/56eec7040117.css","205":"/static/bundles/es6/FeedPageContainer.css/718b1acf7d4d.css","206":"/static/bundles/es6/FollowListModal.css/d1af8b189651.css","207":"/static/bundles/es6/FollowListPage.css/83958e11d46c.css","208":"/static/bundles/es6/SimilarAccountsPage.css/99bc7674003c.css","210":"/static/bundles/es6/LandingPage.css/55ca00d1afee.css","211":"/static/bundles/es6/LocationsDirectoryCountryPage.css/f011822b2d93.css","212":"/static/bundles/es6/LocationsDirectoryCityPage.css/f011822b2d93.css","213":"/static/bundles/es6/LocationPageContainer.css/2f76dbbc8b7c.css","214":"/static/bundles/es6/LocationsDirectoryLandingPage.css/a69bead6658f.css","215":"/static/bundles/es6/LoginAndSignupPage.css/e93c28be31fc.css","216":"/static/bundles/es6/UpdateIGAppForHelpPage.css/6fb2336f846b.css","217":"/static/bundles/es6/ResetPasswordPageContainer.css/9e2e7773d781.css","218":"/static/bundles/es6/MobileAllCommentsPage.css/1131070c05c9.css","219":"/static/bundles/es6/MediaChainingPageContainer.css/12c8442497a4.css","220":"/static/bundles/es6/PostPageContainer.css/0a955bc65530.css","221":"/static/bundles/es6/ProfilesDirectoryLandingPage.css/ec897738d3bc.css","222":"/static/bundles/es6/HashtagsDirectoryLandingPage.css/ec897738d3bc.css","223":"/static/bundles/es6/SuggestedDirectoryLandingPage.css/ec897738d3bc.css","224":"/static/bundles/es6/TagPageContainer.css/def69fc0503e.css","225":"/static/bundles/es6/PhoneConfirmPage.css/9646823c703f.css","227":"/static/bundles/es6/ProfilePageContainer.css/d4750492486d.css","228":"/static/bundles/es6/HttpErrorPage.css/97acfee23c4f.css","229":"/static/bundles/es6/IGTVVideoDraftsPageContainer.css/7fd813f8f8a3.css","230":"/static/bundles/es6/IGTVVideoUploadPageContainer.css/407d5a0b488a.css","231":"/static/bundles/es6/OAuthPermissionsPage.css/911f01846417.css","232":"/static/bundles/es6/MobileDirectPage.css/5fcf3ea1514a.css","233":"/static/bundles/es6/DesktopDirectPage.css/41dbb5f021e1.css","234":"/static/bundles/es6/OneTapUpsell.css/3d1082494e45.css","235":"/static/bundles/es6/NametagLandingPage.css/f5a715b37996.css","236":"/static/bundles/es6/LocalDevTransactionToolSelectorPage.css/3f8f9bb4c8a7.css","237":"/static/bundles/es6/FBEAppStoreErrorPage.css/37c4f5efdab6.css","238":"/static/bundles/es6/ActivityFeedBox.css/1ca7bf95a848.css","240":"/static/bundles/es6/DebugInfoNub.css/858400443420.css","242":"/static/bundles/es6/Consumer.css/2a9557e9bd3e.css","243":"/static/bundles/es6/Challenge.css/04f6e5c38e4c.css","263":"/static/bundles/es6/EmbedVideoWrapper.css/f9124eb1bf3f.css","264":"/static/bundles/es6/EmbedSidecarEntrypoint.css/25c8aa5f60d3.css","265":"/static/bundles/es6/EmbedRich.css/121fab5f0b7b.css"}}</script>
<script type="text/javascript" src="/static/bundles/es6/Vendor.js/c911f5848b78.js" crossorigin="anonymous"></script>
<script type="text/javascript" src="/static/bundles/es6/en_US.js/a13869e2007a.js" crossorigin="anonymous"></script>
<script type="text/javascript" src="/static/bundles/es6/ConsumerLibCommons.js/18c814f22e43.js" crossorigin="anonymous"></script>
<script type="text/javascript" src="/static/bundles/es6/ConsumerUICommons.js/9b8a67342afa.js" crossorigin="anonymous"></script>
<script type="text/javascript" src="/static/bundles/es6/ConsumerAsyncCommons.js/df7fdd721c50.js" crossorigin="anonymous"></script>
<script type="text/javascript" src="/static/bundles/es6/Consumer.js/208e2f7f9441.js" crossorigin="anonymous" charset="utf-8" async=""></script>
<script type="text/javascript" src="/static/bundles/es6/LandingPage.js/89ccf0e2d4bb.js" crossorigin="anonymous" charset="utf-8" async=""></script>

            
        

        <script type="text/javascript">
(function(){
  function normalizeError(err) {
    var errorInfo = err.error || {};
    var getConfigProp = function(propName, defaultValueIfNotTruthy) {
      var propValue = window._sharedData && window._sharedData[propName];
      return propValue ? propValue : defaultValueIfNotTruthy;
    };
    return {
      line: err.line || errorInfo.message || 0,
      column: err.column || 0,
      name: 'InitError',
      message: err.message || errorInfo.message || '',
      script: errorInfo.script || '',
      stack: errorInfo.stackTrace || errorInfo.stack || '',
      timestamp: Date.now(),
      ref: window.location.href,
      deployment_stage: getConfigProp('deployment_stage', ''),
      is_canary: getConfigProp('is_canary', false),
      rollout_hash: getConfigProp('rollout_hash', ''),
      is_prerelease: window.__PRERELEASE__ || false,
      bundle_variant: getConfigProp('bundle_variant', null),
      request_url: err.url || window.location.href,
      response_status_code: errorInfo.statusCode || 0
    }
  }
  window.addEventListener('load', function(){
    if (window.__bufferedErrors && window.__bufferedErrors.length) {
      if (window.caches && window.caches.keys && window.caches.delete) {
        window.caches.keys().then(function(keys) {
          keys.forEach(function(key) {
            window.caches.delete(key)
          })
        })
      }
      window.__bufferedErrors.map(function(error) {
        return normalizeError(error)
      }).forEach(function(normalizedError) {
        var request = new XMLHttpRequest();
        request.open('POST', '/client_error/', true);
        request.setRequestHeader('Content-Type', 'application/json; charset=utf-8');
        request.send(JSON.stringify(normalizedError));
      })
    }
  })
}());
</script>
    

<div class="Z2m7o"><div class="CgFia "></div></div><div id="fb-root" class=" fb_reset"><div style="position: absolute; top: -10000px; width: 0px; height: 0px;"><div></div></div></div></body></html>
