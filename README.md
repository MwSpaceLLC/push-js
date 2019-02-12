# Fake Push js <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/JQuery-Logo.svg/2000px-JQuery-Logo.svg.png" width="100">

> Small file for fake Browsere Notification in HTML5.
```
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
  <button> Try Me </button>
  </body>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <script src="https://cdn.jsdelivr.net/gh/MwSpaceLLC/push-js@master/fake-push.min.js"></script>
  <script type="text/x-ecmascript">
    $('button').click(function(){
      $.push(
      'Notification',
      'I am so Happy!',
      'https://firebase.google.com/images/appmakers/jet_1x.png'
      );
    });
  </script>
</html>
```
🚀 Try yourself at https://jsfiddle.net/5kvt4uhe/10/
