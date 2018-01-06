# Sublime HTML5 Boilerplate

A Sublime Text 2/3 snippet to generate a custom HTML5 Boilerplate template.

## Install

### Option 1: Manual

Copy the files to your Packages directory.

### Option 2: Package Control

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'HTML Boilerplate' then press enter to install.

## Usage

With a blank HTML file open, type

    html5

and press `TAB`.

That generates:

    <!doctype html>
    <html class="" lang="en">
      <head>
        <meta charset="utf-8">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <title>${1:Website}</title>
        <meta name="description" content="${2}">
        <meta name="format-detection" content="telephone=no">

        <base href="/">
        
        <link href="images/favicon-96x96.png" rel="icon" type="image/png">
        <link href="images/apple-touch-icon-180x180.png" rel="apple-touch-icon" >
        <link href='https://fonts.googleapis.com/css?family=Lato:400,900' rel='stylesheet' type='text/css'>
        <link href="css/style.css" rel="stylesheet">

        <!-- Facebook Open Graph -->
        <meta property="fb:app_id" content="123456789">
        <meta property="og:url" content="http://example.com/page.html">
        <meta property="og:type" content="website">
        <meta property="og:title" content="Content Title">
        <meta property="og:image" content="http://example.com/image.jpg">
        <meta property="og:description" content="Description Here">
        <meta property="og:site_name" content="Site Name">
        <meta property="og:locale" content="en_US">
        <meta property="article:author" content="">

        <!-- Twitter Card -->
        <meta name="twitter:card" content="summary">
        <meta name="twitter:site" content="@site_account">
        <meta name="twitter:creator" content="@individual_account">
        <meta name="twitter:url" content="http://example.com/page.html">
        <meta name="twitter:title" content="Content Title">
        <meta name="twitter:description" content="Content description less than 200 characters">
        <meta name="twitter:image" content="http://example.com/image.jpg">          
         
        <!--[if lt IE 9]>
          <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.6.2/html5shiv.js"></script>
          <script src="//cdnjs.cloudflare.com/ajax/libs/respond.js/1.1.0/respond.min.js"></script>
        <![endif]-->    

        <!-- Global Site Tag (gtag.js) - Google Analytics -->
        <script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
        <script>
          window.dataLayer = window.dataLayer || []; function gtag(){dataLayer.push(arguments);} gtag('js', new Date());
          gtag('config', 'GA_TRACKING_ID');
        </script>
      </head>
      <body>
        <!--[if lt IE 8]>
          <p class="browserupgrade">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
        <![endif]-->
        
        <div class="container">
          <div id="header" class="header">
          
          </div> <!-- /Header -->
          
          <div class="content">
              
          </div> <!-- /Content -->
          
          <div id="footer" class="footer">
            &copy; 2018
          </div> <!-- /Footer -->
        </div> <!-- /Container -->
        
        <script src="http://code.jquery.com/jquery-1.12.4.min.js"></script>
        <script>window.jQuery || document.write('<script src="js/vendor/jquery-1.12.4.min.js"><\/script>')</script>
        <script src="js/scripts.js"></script>
      </body>
    </html>

## License 

[MIT Licensed](http://sloria.mit-license.org/).
