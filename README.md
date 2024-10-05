# Test website
This is a test website for embodied agent interface website. This website removes unnessary script head.

Specifically, we take advice made by CHATGPT-4o:
original:
```html
<head>
    <title>Embodied Agent Interface: A Single Line to Evaluate LLMs for Embodied Decision Making</title>
    <!-- consider to add our icon here -->
    <!-- <link rel="icon" href="" type="image/icon type"> -->

    <meta name="viewport" content="width=device-width, initial-scale=1">

    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-datalabels@2.0.0"></script>
    <script
        src="https://cdn.jsdelivr.net/npm/chartjs-plugin-annotation@3.0.1/dist/chartjs-plugin-annotation.min.js"></script>

    <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">
    <link rel="stylesheet" href="website/css/bulma.min.css">
    <link rel="stylesheet" href="website/css/bulma-carousel.min.css">
    <link rel="stylesheet" href="website/css/bulma-slider.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
    <link rel="stylesheet" href="website/css/fontawesome.all.min.css">

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="./website/javascript/bulma-carousel.min.js"></script>
    <script src="./website/javascript/bulma-slider.min.js"></script>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>

    <link href="https://unpkg.com/tabulator-tables@5.5.2/dist/css/tabulator_bootstrap4.min.css" rel="stylesheet">
    <script type="text/javascript" src="https://unpkg.com/tabulator-tables@5.5.2/dist/js/tabulator.min.js"></script>
    <script defer src="website/javascript/fontawesome.all.min.js"></script>
    <!-- <script src="website/javascript/peity-vanilla.js"></script> -->


    <!-- below we load some js scripts -->
    <script src="website/javascript/benchmark_table.js" type="module"></script>
    <script src="website/javascript/success_rate_vs_k_vis.js" type="module"></script>
    <script src="website/javascript/feedback_success_rate_vis.js" type="module"></script>
    <script src="website/javascript/feedback_provider_efficacy.js" type="module"></script>

    <link rel="stylesheet" href="website/css/index.css">

    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-C7GJ4FYMY9"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() { dataLayer.push(arguments); }
        gtag('js', new Date());

        gtag('config', 'G-C7GJ4FYMY9');
    </script>

    <!-- MathJax script -->
    <script type="text/javascript" async
        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML">
    </script>
    <script type="text/javascript">
        MathJax.Hub.Config({
            tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}
        });
    </script>

    <noscript>
        <p><img alt="Clicky" width="1" height="1" src="//in.getclicky.com/101339888ns.gif" /></p>
    </noscript>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
        var toggles = document.querySelectorAll('.toggle-section');
        toggles.forEach(function(toggle) {
            toggle.addEventListener('click', function() {
            var content = document.getElementById(toggle.getAttribute('aria-controls'));
            var toggleIcon = toggle.children[1].children[0];
            content.classList.toggle('is-active');
            if (content.classList.contains('is-active')) {
                toggleIcon.style.transition = 'transform 0.3s ease';
                toggleIcon.style.transform = 'rotate(180deg)';
            } else {
                toggleIcon.style.transition = 'transform 0.3s ease';
                toggleIcon.style.transform = 'rotate(0deg)';
            }
            });
        });
        });
      </script>

    <style>
        .collapse-content {
          display: none;
          margin-top: 10px;
        }
        .collapse-content.is-active {
          display: block;
        }
        /* .toggle-section .icon.is-small {
          transition: transform 0.3s ease;
        } */
        /* .toggle-section .fa-angle-up {
          transform: rotate(180deg);
        } */
      </style>
</head>
```

modified:
```html
<head>
    <title>Embodied Agent Interface: A Single Line to Evaluate LLMs for Embodied Decision Making</title>
    <!-- consider to add our icon here -->
    <!-- <link rel="icon" href="" type="image/icon type"> -->

    <meta name="viewport" content="width=device-width, initial-scale=1">
    

    <script src="https://cdn.jsdelivr.net/npm/chart.js@4.4.0/dist/chart.umd.min.js" 
            integrity="sha384-kjsdflskdjflksdjflskdjflksdf" 
            crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-datalabels@2.0.0" 
            integrity="sha384-abcdefabcdefg" 
            crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/chartjs-plugin-annotation@3.0.1/dist/chartjs-plugin-annotation.min.js" 
            integrity="sha384-hijklmnoprstu" 
            crossorigin="anonymous"></script>

    <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet" 
          integrity="sha384-pqrstuvxyz" 
          crossorigin="anonymous">
    <link rel="stylesheet" href="website/css/bulma.min.css">
    <link rel="stylesheet" href="website/css/bulma-carousel.min.css">
    <link rel="stylesheet" href="website/css/bulma-slider.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
    <link rel="stylesheet" href="website/css/fontawesome.all.min.css">

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="./website/javascript/bulma-carousel.min.js"></script>
    <script src="./website/javascript/bulma-slider.min.js"></script>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>

    <link href="https://unpkg.com/tabulator-tables@5.5.2/dist/css/tabulator_bootstrap4.min.css" rel="stylesheet">
    <script type="text/javascript" src="https://unpkg.com/tabulator-tables@5.5.2/dist/js/tabulator.min.js"></script>
    <script defer src="website/javascript/fontawesome.all.min.js"></script>
    <!-- <script src="website/javascript/peity-vanilla.js"></script> -->


    <!-- below we load some js scripts -->
    <script src="website/javascript/benchmark_table.js" type="module"></script>
    <!-- <script src="website/javascript/success_rate_vs_k_vis.js" type="module"></script> -->
    <!-- <script src="website/javascript/feedback_success_rate_vis.js" type="module"></script> -->
    <!-- <script src="website/javascript/feedback_provider_efficacy.js" type="module"></script> -->

    <link rel="stylesheet" href="website/css/index.css">

    <!-- Google tag (gtag.js) -->
    <!-- Google Tag Manager with SRI -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-C7GJ4FYMY9" 
            integrity="sha384-ZYXWVUTSRQPONML" 
            crossorigin="anonymous"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() { dataLayer.push(arguments); }
        gtag('js', new Date());

        gtag('config', 'G-C7GJ4FYMY9');
    </script>

    <!-- MathJax script -->
    <script type="text/javascript" async
        src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML">
    </script>
    <script type="text/javascript">
        MathJax.Hub.Config({
            tex2jax: {inlineMath: [['$','$'], ['\\(','\\)']]}
        });
    </script>

    <noscript>
        <p><img alt="Clicky" width="1" height="1" src="//in.getclicky.com/101339888ns.gif" /></p>
    </noscript>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
        var toggles = document.querySelectorAll('.toggle-section');
        toggles.forEach(function(toggle) {
            toggle.addEventListener('click', function() {
            var content = document.getElementById(toggle.getAttribute('aria-controls'));
            var toggleIcon = toggle.children[1].children[0];
            content.classList.toggle('is-active');
            if (content.classList.contains('is-active')) {
                toggleIcon.style.transition = 'transform 0.3s ease';
                toggleIcon.style.transform = 'rotate(180deg)';
            } else {
                toggleIcon.style.transition = 'transform 0.3s ease';
                toggleIcon.style.transform = 'rotate(0deg)';
            }
            });
        });
        });
      </script>

    <style>
        .collapse-content {
          display: none;
          margin-top: 10px;
        }
        .collapse-content.is-active {
          display: block;
        }
        /* .toggle-section .icon.is-small {
          transition: transform 0.3s ease;
        } */
        /* .toggle-section .fa-angle-up {
          transform: rotate(180deg);
        } */
      </style>
</head>
```
