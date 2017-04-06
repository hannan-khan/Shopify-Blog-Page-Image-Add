# Shopify-Blog-Page-Image-Add
Shopify Blog Page Image Add


add this code in blog page for feature image in blog page

       {% if article.image %}
          <a class="article__featured-image" href="{{ article.url }}">
            {{ article | img_url: '1024x1024' | img_tag: article.title }}
          </a>
        {% endif %}
        
add this code in articale page for single blog page image    

       {% if article.image %}
          <a class="article__featured-image" href="{{ article.url }}">
            {{ article | img_url: '1024x1024' | img_tag: article.title }}
          </a>
        {% endif %}
