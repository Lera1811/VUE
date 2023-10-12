<h2 class="heading__title">Articles & News</h2>
<ul class="bread-crumbs">
    <li><a href="#">Home</a> </li>
    <li><a href="#">Blog</a> </li>
    <li><a href="#">{{ namePage }}</a> </li>
</ul>
</div>
</section>
@@ -15,7 +15,7 @@
export default {
name: 'HeadingPages',
props:['blogBg'],
props:['blogBg','namePage'],

data() {
return {