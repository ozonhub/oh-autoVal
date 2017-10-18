# oh-autoVal

Oh-autoVal is a free Form validation API based on jQuery. It is developed by Amal K Jose as part of project work. The first version of Oh-autoVal v1.0.0 was released on 17th October, 2017. Now it is in a developing stage. And so, there may have more frequent updates.

Steps to implement API to your forms


1. Include following lines to your website.
&lt;-- Adding oh-autoVal css style --&gt;
&lt;link rel="stylesheet" type="text/css" href="https://rawgit.com/ozonhub/oh-autoVal/master/css/oh-autoval-style.css"&gt;
&lt;!-- Adding jQuery script. It must be before other script files --&gt;
&lt;script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"&gt;&lt;/script&gt;
&lt;!-- Adding oh-autoVal script file --&gt;
&lt;script src="https://rawgit.com/ozonhub/oh-autoVal/master/js/oh-autoval-script.js"&gt;&lt;/script&gt;

2. Add a Form with onsubmit="return" and class="oh-autoval-form".
Example:
&lt;form action="destignaion.php" class="oh-autoval-form" method="post" onsubmit="return"&gt;
      &lt;!--Form elements --&gt;
&lt;/form&gt;

3. Add all required elements with class="oh-autoval av-format" and av-message="Error message".
Example:
&lt;input type="text" name="email" class="oh-autoval av-email" av-message="Invalid email address"/&gt;

4. Add a submit button on your form.
Example:
&lt;input type="submit" name="submit" value="Submit"/&gt;

Visit http://www.oh-autoval.ml
