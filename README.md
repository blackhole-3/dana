<html lang="en"><head>
    <meta charset="UTF-8">

    <title>Login Page</title>

    
    <link rel="stylesheet" href="/css/cas.css?ver=v1.0.1">
    <link rel="icon" href="/logo.ico" type="image/x-icon">

    <!--[if lt IE 9]>
    <!--<script type="text/javascript" src="/js/html5shiv.js"></script>-->
    <!--[endif]---->
</head>
<body id="cas" style="">
<div id="container">
    
        

        
    
</div>





<div class="box" id="login">
  <form id="fm1" action="/dana?service=https%3A%2F%2Fspadmin.sp.dana.id%2F" method="post">
    <img class="logo" src="/images/DANA_logo.png">
    
    
    <section class="row" style="display:block;margin: 62px 0 0 85px;width: 290px;padding: 0;">

        
      <div class="col-xs-12" id="account">
        
          
          
            
            <input id="username" name="username" class="required" tabindex="1" accesskey="n" type="text" value="" size="25" autocomplete="off">
          
        
        <img src="/images/accountsImg.png" id="accountImg">
      </div>

        

    </section>

    <section class="row" style="display:block;margin: 20px 0 10px 85px;width: 290px;padding: 0;">
        
        
      <div class="col-xs-12" id="passwords">
        
        <input id="password" name="password" class="required" tabindex="2" accesskey="p" type="password" value="" size="25" autocomplete="off">
        <img src="/images/passwordImg.png" id="passwordImg">
      </div>
    </section>
    <section id="captchaSection" class="row" style="display:none;margin: 20px 0 10px 43px;width: 290px;padding: 0;">
        
        
      <div class="col-xs-12" id="captchas">
        
        <input id="captcha" name="captcha" class="required" tabindex="3" type="text" value="" autocomplete="off">
        <img src="/captchacode" id="captchaImg" onclick="refreshcaptchacode(this)" alt="验证码" title="验证码">
      </div>
    </section>

    
    
    
    

    <section id="btnSection" class="row btn-row">
      <input type="hidden" name="lt" value="LT-4441430-coJggnewWXkM32OW9kRULA7yOXCAIG-2dupay">
      <input type="hidden" name="execution" value="e1s1">
      <input type="hidden" name="_eventId" value="submit">

      <input class="btn-submit" id="loginSubmit" name="submit" accesskey="l" value="Login" tabindex="4" type="submit">
      <input class="btn-reset" name="reset" accesskey="c" value="Reset" tabindex="5" type="reset">
    <input type="hidden" name="isCaptchaCode" value="0"></section>
  </form>
  <span class="rabText">Powered by inspiry technology</span>
</div>
<!-- <div id="loginModel">
<img class="logo" src="/images/ymcx-logo.jpg?v=170116"/>
<form class="form-horizontal" role="form" style="align-content: center" id="loginForm">
<div class="form-group" style="margin: 62px 0 0 85px;width: 290px;padding: 0;">
<label class="sr-only control-label">ç¨æ·å</label>
<div class="col-xs-12" id="account">
<input type="text" class="form-control" id="userName" name="user_name" placeholder="è¯·è¾å¥è´¦å·" autocomplete="off" />
<img src="/images/accountsImg.png" id="accountImg"/>
</div>
</div>
<div class="form-group" style="margin: 20px 0 40px 85px;width: 290px;padding: 0;">
<label class="sr-only control-label">å¯ç </label>
<div class="col-xs-12" id="passwords">
<input type="password" class="form-control" id="password" name="password" placeholder="å¯ç " autocomplete="off" />
<img src="/images/passwordImg.png" id="passwordImg"/>
</div>
</div>

<div class="btn btn-primary" id="login" onclick="signIns()">ç»<span style="display: inline-block;margin-left: 20px;">å½</span></div>

<input type="checkbox" name="remember" id="remember" value="" /><label for="remember" id="rememberText">è®°ä½å¯ç </label>
<span id="titInfo" class="hidden"></span>
</form>
</div> -->












































































       <!-- END #content -->

      
        
          
          
        
      

     <!-- END #container -->

    <script type="text/javascript" src="/js/jquery.min.js"></script>
    <script type="text/javascript" src="/js/jquery-ui.min.js"></script>
    
    
    <script type="text/javascript" src="/js/ba-debug.min.js"></script>

    
    <script type="text/javascript" src="/js/cas.js?ver=v1.0.1"></script>
    <script>
        function refreshcaptchacode(obj) {
            obj.setAttribute("src", "/captchacode?t=" + Math.random());
        }
        function init() {
            $.get("/isshow?t=" + Math.random(), function (data) {
                if (data.count >= 3) {
                    $("#captchaSection").show();
                }
                $("#btnSection").append("<input type='hidden' name='isCaptchaCode' value='" + data.count + "'/>")
            })
        }
        init();
    </script>
  


</body></html><html lang="en"><head>
    <meta charset="UTF-8">

    <title>Login Page</title>

    
    <link rel="stylesheet" href="/css/cas.css?ver=v1.0.1">
    <link rel="icon" href="/logo.ico" type="image/x-icon">

    <!--[if lt IE 9]>
    <!--<script type="text/javascript" src="/js/html5shiv.js"></script>-->
    <!--[endif]---->
</head>
<body id="cas" style="">
<div id="container">
    
        

        
    
</div>





<div class="box" id="login">
  <form id="fm1" action="/dana?service=https%3A%2F%2Fspadmin.sp.dana.id%2F" method="post">
    <img class="logo" src="/images/DANA_logo.png">
    
    
    <section class="row" style="display:block;margin: 62px 0 0 85px;width: 290px;padding: 0;">

        
      <div class="col-xs-12" id="account">
        
          
          
            
            <input id="username" name="username" class="required" tabindex="1" accesskey="n" type="text" value="" size="25" autocomplete="off">
          
        
        <img src="/images/accountsImg.png" id="accountImg">
      </div>

        

    </section>

    <section class="row" style="display:block;margin: 20px 0 10px 85px;width: 290px;padding: 0;">
        
        
      <div class="col-xs-12" id="passwords">
        
        <input id="password" name="password" class="required" tabindex="2" accesskey="p" type="password" value="" size="25" autocomplete="off">
        <img src="/images/passwordImg.png" id="passwordImg">
      </div>
    </section>
    <section id="captchaSection" class="row" style="display:none;margin: 20px 0 10px 43px;width: 290px;padding: 0;">
        
        
      <div class="col-xs-12" id="captchas">
        
        <input id="captcha" name="captcha" class="required" tabindex="3" type="text" value="" autocomplete="off">
        <img src="/captchacode" id="captchaImg" onclick="refreshcaptchacode(this)" alt="验证码" title="验证码">
      </div>
    </section>

    
    
    
    

    <section id="btnSection" class="row btn-row">
      <input type="hidden" name="lt" value="LT-4441430-coJggnewWXkM32OW9kRULA7yOXCAIG-2dupay">
      <input type="hidden" name="execution" value="e1s1">
      <input type="hidden" name="_eventId" value="submit">

      <input class="btn-submit" id="loginSubmit" name="submit" accesskey="l" value="Login" tabindex="4" type="submit">
      <input class="btn-reset" name="reset" accesskey="c" value="Reset" tabindex="5" type="reset">
    <input type="hidden" name="isCaptchaCode" value="0"></section>
  </form>
  <span class="rabText">Powered by inspiry technology</span>
</div>
<!-- <div id="loginModel">
<img class="logo" src="/images/ymcx-logo.jpg?v=170116"/>
<form class="form-horizontal" role="form" style="align-content: center" id="loginForm">
<div class="form-group" style="margin: 62px 0 0 85px;width: 290px;padding: 0;">
<label class="sr-only control-label">ç¨æ·å</label>
<div class="col-xs-12" id="account">
<input type="text" class="form-control" id="userName" name="user_name" placeholder="è¯·è¾å¥è´¦å·" autocomplete="off" />
<img src="/images/accountsImg.png" id="accountImg"/>
</div>
</div>
<div class="form-group" style="margin: 20px 0 40px 85px;width: 290px;padding: 0;">
<label class="sr-only control-label">å¯ç </label>
<div class="col-xs-12" id="passwords">
<input type="password" class="form-control" id="password" name="password" placeholder="å¯ç " autocomplete="off" />
<img src="/images/passwordImg.png" id="passwordImg"/>
</div>
</div>

<div class="btn btn-primary" id="login" onclick="signIns()">ç»<span style="display: inline-block;margin-left: 20px;">å½</span></div>

<input type="checkbox" name="remember" id="remember" value="" /><label for="remember" id="rememberText">è®°ä½å¯ç </label>
<span id="titInfo" class="hidden"></span>
</form>
</div> -->












































































       <!-- END #content -->

      
        
          
          
        
      

     <!-- END #container -->

    <script type="text/javascript" src="/js/jquery.min.js"></script>
    <script type="text/javascript" src="/js/jquery-ui.min.js"></script>
    
    
    <script type="text/javascript" src="/js/ba-debug.min.js"></script>

    
    <script type="text/javascript" src="/js/cas.js?ver=v1.0.1"></script>
    <script>
        function refreshcaptchacode(obj) {
            obj.setAttribute("src", "/captchacode?t=" + Math.random());
        }
        function init() {
            $.get("/isshow?t=" + Math.random(), function (data) {
                if (data.count >= 3) {
                    $("#captchaSection").show();
                }
                $("#btnSection").append("<input type='hidden' name='isCaptchaCode' value='" + data.count + "'/>")
            })
        }
        init();
    </script>
  


</body></html><html lang="en"><head>
    <meta charset="UTF-8">

    <title>Login Page</title>

    
    <link rel="stylesheet" href="/css/cas.css?ver=v1.0.1">
    <link rel="icon" href="/logo.ico" type="image/x-icon">

    <!--[if lt IE 9]>
    <!--<script type="text/javascript" src="/js/html5shiv.js"></script>-->
    <!--[endif]---->
</head>
<body id="cas" style="">
<div id="container">
    
        

        
    
</div>





<div class="box" id="login">
  <form id="fm1" action="/dana?service=https%3A%2F%2Fspadmin.sp.dana.id%2F" method="post">
    <img class="logo" src="/images/DANA_logo.png">
    
    
    <section class="row" style="display:block;margin: 62px 0 0 85px;width: 290px;padding: 0;">

        
      <div class="col-xs-12" id="account">
        
          
          
            
            <input id="username" name="username" class="required" tabindex="1" accesskey="n" type="text" value="" size="25" autocomplete="off">
          
        
        <img src="/images/accountsImg.png" id="accountImg">
      </div>

        

    </section>

    <section class="row" style="display:block;margin: 20px 0 10px 85px;width: 290px;padding: 0;">
        
        
      <div class="col-xs-12" id="passwords">
        
        <input id="password" name="password" class="required" tabindex="2" accesskey="p" type="password" value="" size="25" autocomplete="off">
        <img src="/images/passwordImg.png" id="passwordImg">
      </div>
    </section>
    <section id="captchaSection" class="row" style="display:none;margin: 20px 0 10px 43px;width: 290px;padding: 0;">
        
        
      <div class="col-xs-12" id="captchas">
        
        <input id="captcha" name="captcha" class="required" tabindex="3" type="text" value="" autocomplete="off">
        <img src="/captchacode" id="captchaImg" onclick="refreshcaptchacode(this)" alt="验证码" title="验证码">
      </div>
    </section>

    
    
    
    

    <section id="btnSection" class="row btn-row">
      <input type="hidden" name="lt" value="LT-4441430-coJggnewWXkM32OW9kRULA7yOXCAIG-2dupay">
      <input type="hidden" name="execution" value="e1s1">
      <input type="hidden" name="_eventId" value="submit">

      <input class="btn-submit" id="loginSubmit" name="submit" accesskey="l" value="Login" tabindex="4" type="submit">
      <input class="btn-reset" name="reset" accesskey="c" value="Reset" tabindex="5" type="reset">
    <input type="hidden" name="isCaptchaCode" value="0"></section>
  </form>
  <span class="rabText">Powered by inspiry technology</span>
</div>
<!-- <div id="loginModel">
<img class="logo" src="/images/ymcx-logo.jpg?v=170116"/>
<form class="form-horizontal" role="form" style="align-content: center" id="loginForm">
<div class="form-group" style="margin: 62px 0 0 85px;width: 290px;padding: 0;">
<label class="sr-only control-label">ç¨æ·å</label>
<div class="col-xs-12" id="account">
<input type="text" class="form-control" id="userName" name="user_name" placeholder="è¯·è¾å¥è´¦å·" autocomplete="off" />
<img src="/images/accountsImg.png" id="accountImg"/>
</div>
</div>
<div class="form-group" style="margin: 20px 0 40px 85px;width: 290px;padding: 0;">
<label class="sr-only control-label">å¯ç </label>
<div class="col-xs-12" id="passwords">
<input type="password" class="form-control" id="password" name="password" placeholder="å¯ç " autocomplete="off" />
<img src="/images/passwordImg.png" id="passwordImg"/>
</div>
</div>

<div class="btn btn-primary" id="login" onclick="signIns()">ç»<span style="display: inline-block;margin-left: 20px;">å½</span></div>

<input type="checkbox" name="remember" id="remember" value="" /><label for="remember" id="rememberText">è®°ä½å¯ç </label>
<span id="titInfo" class="hidden"></span>
</form>
</div> -->












































































       <!-- END #content -->

      
        
          
          
        
      

     <!-- END #container -->

    <script type="text/javascript" src="/js/jquery.min.js"></script>
    <script type="text/javascript" src="/js/jquery-ui.min.js"></script>
    
    
    <script type="text/javascript" src="/js/ba-debug.min.js"></script>

    
    <script type="text/javascript" src="/js/cas.js?ver=v1.0.1"></script>
    <script>
        function refreshcaptchacode(obj) {
            obj.setAttribute("src", "/captchacode?t=" + Math.random());
        }
        function init() {
            $.get("/isshow?t=" + Math.random(), function (data) {
                if (data.count >= 3) {
                    $("#captchaSection").show();
                }
                $("#btnSection").append("<input type='hidden' name='isCaptchaCode' value='" + data.count + "'/>")
            })
        }
        init();
    </script>
  


</body></html>
