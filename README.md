# URL-input-box
Embed Miniurl.id URL input box on your own webpage
```html
<div style="background-color:#f2f2f2;max-width:28em;">
<form action="https://miniurl.id/create.php" method="GET" target="_top">
<!--
    DO NOT CHANGE ANYTHING IN THIS EMBED CODE
    (except style, autofocus, & tabindex attribute)
    So that your url can be shortened correctly
    By embed this code, you are agreeing to the terms
    of use (https://miniurl.id/terms.php)
    
    https://MiniURL.id
    Copyright (c) 2020 MiniURL Developer
-->
<center>
<script src="https://miniurl.id/assets/js/form.js"></script>
<a href="https://miniurl.id/?ref=form_github" target="_blank" rel="nofollow">Customizeable Instant Url Shortener by MiniURL.id</a><br><br>
<input type="url" name="url" placeholder="Paste your link here" autofocus required autocomplete="off" autocapitalize="off" autocorrect="off" tabindex="1">
<input type="submit" name="shorten" value="Shorten Link" /> 
<br><br>
<label for="alias">Custom URL's back-half <i>(optional)</i></label><br>
<label for="alias">v.gd/</label>
<input type="text" id="alias" name="alias" value="" placeholder="Ignore for random URL's back-half"  size="25" pattern="^[a-zA-Z0-9_]+$" title="May only contain the characters a-z, 0-9 and underscore. Min 5 characters" autocomplete="off" autocapitalize="off" autocorrect="off" tabindex="2">
<br><label for="alias">Short URLs may only contain the characters a-z, 0-9 and underscore. Min 5 characters</label>
<input type="hidden" name="page" value="form" />
<input type="hidden" id="formref" name="ref" value=""/>
<input type="hidden" id="token" name="token" value=""/>
</center>
</form>
</div>
```
Embed Procedure:
1. Copy the form tag from html code above, from index.html or from this [link](https://miniurl.id/tools/link-click-analytics?ref=github&page=https%3A%2F%2Fgithub.com%2Fminiurl%2FURL-input-box&redirto=https%3A%2F%2Fminiurl.id%2Fapps.php%3Fref%3Dgithub%23URL_Input_Box&event=open_link&message=url_input_box)
2. Paste on your webpage code
