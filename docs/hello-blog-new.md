---

title: Demo POst datat
menu_order: 1
post_status: publish
post_excerpt: This is a post excerpt
featured_image: /wp-content/uploads/2024/09/pic1.jpg
taxonomy:
    category:
        - category-slug-1
        - category-slug-2
    post_tag:
        - tag-1
        - tag-2
custom_fields:
    field1: value 1
    field2: value 2

---

## My post content demo check this post data

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec a lacinia orci.
Nunc sodales massa enim, nec consectetur orci tempus ac.

### Section with image

![pic1](/wp-content/uploads/2024/09/pic1.jpg)

Nam rutrum ultricies sapien id rhoncus. In pellentesque efficitur suscipit.
Aliquam vel est consectetur lectus malesuada mollis sit amet non neque. 

### Section with link

This is a [relative link](../sub-dir1/post3.md) which links to another markdown post w.r.t the current file.
This is an [absolute link](/folder1/sub-dir1/post3.md) which links to another post w.r.t the root directory.

### Section with HTML

<section id="home">
    <h2>Welcome to Our Website!</h2>
    <img height="300px" width="300px" src="docs/_images/8dd203f717c974dd2f675ef202c5af05.jpg" />
    <p>This is a sample HTML page with JavaScript and CSS styling.</p>
    <button type="button" onclick="showMessage()">Show message</button>
</section>

<script>
    function showMessage() {
        alert('Thank you for contacting us!');
    }
</script>

<!-- Sample CSS Style -->
<style>
    h1 {
        color: red;
    }
</style>

### Section with Shortcodes
