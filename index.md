---
layout: home
---

<script>
        $(document).ready(function(){
            $('#typewriteText').typewrite({
                actions: [
                    {type: 'Hello, I’m John Doe, Web-Developer based on San Fransisco.'}
                ]
            });
        });
    </script>


<div class="col-lg-8 offset-md-2">
  <div class="jumbotron" style="text-align: center;">
    <h1 class="display-4">Hello, welcome to devlopr starter !</h1>
    <h3> {{site.description}}</h3>
    <p class="lead" id="typewriteText"></p>
    <button class="btn btn-dark btn-lg"><a href="/get-started">Get Started </a></button>
  </div>
</div>