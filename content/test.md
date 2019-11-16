---
views:
    test-left:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta: 
                type: single
                route: block/test-left
    test-side:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta: 
                type: single
                route: block/test-side
---
This is a test page
=========================

<p class="comment" markdown="1">
Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/test.md`.
</p>

I have no idea what content I should place here... 

<i class="fa fa-hand-peace-o fa-lg"></i>
