# NekosHaxs
Designed for the 3dshacks/Nintendo Homebrew community


cheers to : <a href="https://github.com/Chaaoos">/u/Chaaoos</a>  for catching my late night typos
* * *

### [](#header-3) Used Resources
* Materialize CSS framework <a href="http://materializecss.com">(Link)</a>
* Google Material Icon Pack <a href="https://material.io/icons/">(Link)</a>
* Google Roboto Fonts <a href="https://fonts.google.com/specimen/Roboto">(Link)</a>
* Kangax's HTML Minifier <a href="http://kangax.github.io/html-minifier/">(Link)</a>

* * *

## [](#header-2) Project Source Code

```html

 
 <!DOCTYPE html>
  <html>
    <head>

      <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
      <!--Import Google Icon Font-->
	  <noscript id="deferred-styles">
	  <!--Added CDN Support-->
      <link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
      <!--Import materialize.css-->
	  <!--Added CDN Support-->
      <link type="text/css" rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.98.0/css/materialize.min.css"  media="screen,projection"/>
	  </noscript>
	  <!--Google's Supposedly Async/defered CSS loading script-->
	  <script>
      var loadDeferredStyles = function() {
        var addStylesNode = document.getElementById("deferred-styles");
        var replacement = document.createElement("div");
        replacement.innerHTML = addStylesNode.textContent;
        document.body.appendChild(replacement)
        addStylesNode.parentElement.removeChild(addStylesNode);
      };
      var raf = requestAnimationFrame || mozRequestAnimationFrame ||
          webkitRequestAnimationFrame || msRequestAnimationFrame;
      if (raf) raf(function() { window.setTimeout(loadDeferredStyles, 0); });
      else window.addEventListener('load', loadDeferredStyles);
    </script>
	
      <!--Let browser know website is optimized for mobile-->
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

      <style>
      nav a.brand-logo {
      padding-left: 3%;
      font-weight: bold;
      font-family: "Century Gothic", sans-serif;
      }
      </style>
    </head>

    <body class="white">
      <!--Import jQuery before materialize.js-->
	  <!--Added CDN Support & Async JS -->
      <script async
  src="https://code.jquery.com/jquery-3.1.1.slim.min.js"
  integrity="sha256-/SIrNqv8h6QGKDuNoLGA4iret+kyesCkHGzVUUV0shc="
  crossorigin="anonymous"></script>
      <script async type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.98.0/js/materialize.min.js"></script>

      </br>
      <div class="container">
        <nav>
            <div class="nav-wrapper red">
                <a href="#" class="brand-logo">3DS Hacking Discord</a>
                <ul id="nav-mobile" class="right hide-on-med-and-down">

                    <li><a href="https://github.com/916253/Kurisu"><i class="material-icons left">assessment</i>KURISU REPO</a></li>
                    <li><a class="waves-effect waves-light btn blue-grey darken-3 z-depth-3" href="https://discord.gg/C29hYvh"><i class="material-icons right">input</i>Discord</a></li>
                </ul>
            </div>
        </nav>
        </div>

    <div class="container center ">
        </br>
        <img class="z-depth-2" width="80%" src="images/bowser.png">

  </div>
      </br>

       <div class="container z-depth-2">




                <div class="row">
                        <div class="col s2">
                        </div>
                       <div class="col s8">
                       <p class="flow-text">
                       <b>1) Expected behavior</b></br>
                        Keep your conduct and conversation civil. This means, including and limited to:
                        <blockquote>a) You may disagree with anyone or anything you like, but you should try to keep it to opinions, and not people. Avoid vitriol.</blockquote>
                        <blockquote>b) Constant antagonistic behavior is considered uncivil and appropriate action will be taken.
                        - This rule is intended purely for the purpose of attempting to prevent flame wars, and is not to be interpreted in a way that disrupts normal conversation.</blockquote>
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>2) Language</b></br>
                        English is the only language to be spoken on this server.
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>3) Getting help</b></br>
                        Support questions are to be asked in #help-and-questions exclusively.
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>4) Giving help</b></br>
                        When answering questions in #help-and-questions, remain helpful. 
                        Derailing support is impermissible. 
                        Remarks that are not helpful will be removed on sight.
                        Continued derailing will constitute further action.
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>5) Off topic</b></br>
                        Off-topic discussion is permitted only in #off-topic. 
                        This includes political and other strongly opinionated debates. 
                        The #voice channel is an exception, when it is active.
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>6) Long messages/pastebin</b></br>
                        Excessively long texts are to be placed on a "pastebin"-style website such as Hastebin.
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>7) Spam</b></br>
                        Repetitive posting is considered spamming and is unacceptable. 
                        <blockquote>a) Asking the same question repeatedly is permitted, but only if you have a reasonable cause to believe you were not purposefully ignored.</blockquote>
                        <blockquote>b) Sending a large number of messages in a short period of time ("flooding") is also considered spam. This includes image or link flooding.</blockquote>
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>8) Raiding</b></br>
                        Brigading, bombing, raiding, or otherwise making inaccessible, unusable, or undesirable another server or website is strictly prohibited.
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>9) User scripts</b></br>
                        User-side scripts / plugins are permitted, provided they do not cause annoyance to the community or have community-accessible triggers. </br>
                         <blockquote><b><i>- Note that this rule allows for individual triggers, running full on selfbots falls under 'fully automated clients' and must be used in accordance with rule 10.</i></b></blockquote
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>10) Bots</b></br>
                        Bots and other fully automated clients require explicit written permission from a Discord server owner.
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>11) Piracy</b></br>
                        Illegitimate copies and other copyright violations will not be tolerated. This includes: 
                        <blockquote>- Sharing full game data, such as .3DS/CCI or CIA files, Sharing 'ticket' files </br>
                        - Sharing titlekeys </br>
                        - linking to any site with the purpose of hosting or providing the former</br> 
                        (general encryption keys not associated with piracy are not affected by this). </br>
                        - Sharing software designed for copyright violations or sharing copyrighted material is not allowed. </br>
                        - Discussing the aforementioned software is allowed. </br>
                        - Naming software used to obtain copyrighted material illegitimately is strictly prohibited. </br>
                        </blockquote><blockquote>
                        <b>Attempting to bypass these rules via any method on this server is strictly prohibited.</b> </br>
                        <b>No piracy discussion in help channels at all. No exceptions.</b></blockquote>
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>12) Nsfw</b></br>
                        Not-safe-for-work content of any kind is strictly prohibited. This includes gore or other "shock" content.
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>13) Rule evasion</b></br>
                        Evading the rules, seeking loopholes, or attempting to stay "borderline" within the rules, is considered to be breaking the rules.
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>14) External servers</b></br></br>
                        <b>Links to other Discord servers are allowed, on the following conditions:</b></br>
                        <blockquote>
                        - You must receive written consent from a staff member. </br></br>
                        - The linked server must not directly violate any of this server's rules. </br></br>
                        - You may not spam advertisement to the server, post the link once and be done.
                        </blockquote>
                        </p>
                        </br>
                        <p class="flow-text">
                        <b>Staff Action:</b></br>
                        <blockquote>
                        Breaking these rules will result in appropriate measures taken by the staff. </br></br>
                        All decisions by the staff are final and are not up for debate. Staff instruction is to be followed. </br></br>
                        If you would like to appeal a staff decision, do so via PM and not in public.
                        </blockquote>
                        </p>
                        </br>
                        <p class="flow-text">
                        <b>Nickname and Avatar Policy:</b>
                        <blockquote>
                        - Nicknames are to be kept primarily alphanumeric, to keep them easy to tag and read. </br></br>
                        - In addition, excessively long usernames are unacceptable, as they break up the chat too much. </br></br>
                        - If your username is not, you may request a nickname from a staff member. Otherwise, we may forcibly set one on you. </br></br>
                        - Attempts to impersonate another user via nickname and/or avatar change are unacceptable. </br></br>
                        - Excessively crude or NSFW usernames or avatars are unacceptable.
                        </blockquote>
                        </p>
                        </p>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
                <div class="row">
                        <div class="col s2">
                        </div>
                        <div class="col s8">
                        <p class="flow-text">
                        <b>Miscellaneous:</b></br>
                        A shareable, permanent invite link to this server: <a href="https://discord.gg/C29hYvh">https://discord.gg/C29hYvh</a>
                        </p>
                        </br></br></br>
                        </div>
                        <div class="col s2">
                        </div>
                </div>
        </div>

    </body>

     <footer class="page-footer red">
          <div class="container">
            <div class="row">
              <div class="col l6 s12">
                <h5 class="white-text">Useful Links</h5>
                <p class="white-text"><a href="https://3ds.guide">A9LH Guide</a></p>


              </div>

            </div>
          </div>
          <div class="footer-copyright">
            <div class="container">
            <i class="material-icons tiny">copyright</i> 2017 Copyright - <a href="https://github.com/ihaveamac">Ihaveahax(Ihaveamac)</a> &amp; <a href="https://github.com/916253">Adrian(916253)</a>
            </br>Designed by Inori Shizuka 
            <a class="grey-text text-lighten-4 right" href="https://github.com/inorishizuka/NekosHaxs">Inori's Repo</a>
            </div>
</html>

```


```
Ending Notes: HTML could be cleaned up and minified. 
```
