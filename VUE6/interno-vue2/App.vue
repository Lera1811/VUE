<div id="app" class="wrapper">
    <header-pages/>
    <main class="main">
    <home-page/>
    <!-- <home-page/> -->
    <!-- <blog-page/> -->
    <!-- <blog-details/> -->
    <our-project/>
    </main> 
    <footer-page/>
</div>
@@ -14,9 +15,10 @@
import FooterPage from './components/FooterPage.vue'
import HeaderPages from './components/HeaderPages.vue'
import OurProject from './pages/OurProject/OurProject.vue'
// import BlogDetails from './pages/BlogDetails/BlogDetails.vue'
// import BlogPage from './pages/Blog/BlogPage.vue'
import HomePage from './pages/HomePage/HomePage.vue'
// import HomePage from './pages/HomePage/HomePage.vue'
@@ -25,7 +27,8 @@ export default {
components: {
  HeaderPages,
  FooterPage,
  HomePage,
  OurProject,
  // HomePage,
  // BlogPage,
  // BlogDetails,
}