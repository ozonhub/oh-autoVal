# oh-autoVal

Oh-autoVal is a free Form validation API based on jQuery. It is developed by Amal K Jose as part of project work. The first version of Oh-autoVal v1.0.0 was released on 17th October, 2017. Now it is in a developing stage. And so, there may have more frequent updates.

Steps to implement API to your forms


1. Include following lines to your website.
<!-- Adding oh-autoVal css style -->
<link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/ozonhub/oh-autoVal/ee4e79dc/css/oh-autoval-style.css">
<!-- Adding jQuery script. It must be before other script files -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<!-- Adding oh-autoVal script file -->
<script src="https://cdn.rawgit.com/ozonhub/oh-autoVal/ee4e79dc/js/oh-autoval-script.js"></script>

2. Add a Form with onsubmit="return" and class="oh-autoval-form".
Example:
<form action="destignaion.php" class="oh-autoval-form" method="post" onsubmit="return">
      <!--Form elements -->
</form>

3. Add all required elements with class="oh-autoval av-format" and av-message="Error message".
Example:
<input type="text" name="email" class="oh-autoval av-email" av-message="Invalid email address"/>

4. Add a submit button on your form.
Example:
<input type="submit" name="submit" value="Submit"/>

Visit http://www.oh-autoval.ml
