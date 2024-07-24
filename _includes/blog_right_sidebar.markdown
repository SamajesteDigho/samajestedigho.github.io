<div class="col-lg-4">
  <div class="sidebar-inner">
    <!-- Start Single Widget  -->
    <!-- <div class="axil-single-widget widget widget_categories mb--30">
      <ul>
        <li class="cat-item">
          <a href="#" class="inner">
            <div class="thumbnail">
              <img src="assets/images/post-images/category-image-01.jpg" alt="">
            </div>
            <div class="content">
              <h5 class="title">Tech</h5>
            </div>
          </a>
        </li>
        <li class="cat-item">
          <a href="#" class="inner">
            <div class="thumbnail">
              <img src="assets/images/post-images/category-image-02.jpg" alt="">
            </div>
            <div class="content">
              <h5 class="title">Style</h5>
            </div>
          </a>
        </li>
        <li class="cat-item">
          <a href="#" class="inner">
            <div class="thumbnail">
              <img src="assets/images/post-images/category-image-03.jpg" alt="">
            </div>
            <div class="content">
              <h5 class="title">Travel</h5>
            </div>
          </a>
        </li>
        <li class="cat-item">
          <a href="#" class="inner">
            <div class="thumbnail">
              <img src="assets/images/post-images/category-image-04.jpg" alt="">
            </div>
            <div class="content">
              <h5 class="title">Food</h5>
            </div>
          </a>
        </li>
      </ul>
    </div> -->
    <!-- End Single Widget  -->

    <!-- Start Single Widget  -->
    <div class="axil-single-widget widget widget_search mb--30">
      <h5 class="widget-title">Search</h5>
      <form action="#">
        <div class="axil-search form-group">
          <button type="submit" class="search-button"><i class="fal fa-search"></i></button>
          <input type="text" class="form-control" placeholder="Search">
        </div>
      </form>
    </div>
    <!-- End Single Widget  -->

    <!-- Start Single Widget  -->
    <div class="axil-single-widget widget widget_postlist mb--30">
      <h5 class="widget-title">Recent Blog Post</h5>
      <!-- Start Post List  -->
      <div class="post-medium-block">

        {% for blog in site.blogs %}
        <div class="content-block post-medium mb--20">
          <div class="post-content">
            <h6 class="title"><a href="{{ blog.url }}"> {{ blog.title}} </a></h6>
            <div class="post-meta">
              <ul class="post-meta-list">
                <li>{{ blog.date | date_to_string }}</li>
                <li>30 Views</li>
              </ul>
            </div>
          </div>
        </div>
        {% endfor %}

      </div>
    </div>
    <!-- End Single Widget  -->

    <!-- Start PROJECTS -->
    <div class="axil-single-widget widget widget_postlist mb--30">
      <h5 class="widget-title">Projects</h5>
      <!-- Start Post List  -->
      <div class="post-medium-block">

        <!-- Start Single Post  -->
        {% for project in site.projects %}
        <div class="content-block post-medium mb--20">
          <div class="post-thumbnail">
            <a href="{{ project.website }}">
              <img src="{{ project.image }}" alt="Post Images">
            </a>
          </div>
          <div class="post-content">
            <h6 class="title"><a href="{{ project.website }}">{{ project.title }}</a></h6>
            <div class="post-meta">
              <ul class="post-meta-list">
                <li>{{ project.date | date_to_string }}</li>
                <li>20 Views</li>
              </ul>
            </div>
          </div>
        </div>
        {% endfor %}
        <!-- End Single Post  -->
      </div>
      <!-- End Post List  -->

    </div>
    <!-- End Single Widget  -->

    <!-- Start SUBSCRIBE FORM  -->
    <div class="axil-single-widget widget widget_newsletter mb--30">
      <!-- Start Post List  -->
      <div class="newsletter-inner text-center">
        <h4 class="title mb--15">Never Miss A Post!</h4>
        <p class="b2 mb--30">
          Sign up for free and be the first to <br /> get notified about updates.
        </p>
        <form action="#">
          <div class="form-group">
            <input type="text" placeholder="Enter Your Email " required>
          </div>
          <div class="form-submit">
            <button class="cerchio axil-button button-rounded"><span>Subscribe</span></button>
          </div>
        </form>
      </div>
      <!-- End Post List  -->
    </div>
    <!-- End Single Widget  -->

    <!-- Start ADVERTISSEMENT  -->
    <div class="axil-single-widget widget widget_ads mb--30">
      <!-- Start Post List  -->
      <div class="thumbnail">
        <a href="#">
          <img src="https://picsum.photos/300/200" alt="Ads Images">
        </a>
      </div>
      <!-- End Post List  -->
    </div>
    <!-- End Single Widget  -->

    <!-- Start CONTACT WIDGETS  -->
    <div class="axil-single-widget widget widget_social mb--30">
      <h5 class="widget-title">Stay In Touch</h5>
      <!-- Start Post List  -->
      {% include social_links.html %}
      <!-- End Post List  -->
    </div>
    <!-- End Single Widget  -->

    <!-- Start ARCHIEVES  -->
    <!-- <div class="axil-single-widget widget widget_archive mb--30">
      <h5 class="widget-title">Archives</h5>
      <ul>
        <li><a href="#">January 2020</a></li>
        <li><a href="#">February 2020</a></li>
        <li><a href="#">March 2020</a></li>
        <li><a href="#">April 2020</a></li>
      </ul>
    </div> -->
    <!-- End Single Widget  -->

    <!-- Start Single Widget  -->
    <!-- <div class="axil-single-widget widget widget_dropdown mb--30">
      <h5 class="widget-title">Archives</h5>
      <form action="#">
        <select>
          <option>Select Month</option>
          <option>April 2020 (4)</option>
          <option>March 2020 (3)</option>
          <option>November 2018 (11)</option>
          <option>January 2013 (5)</option>
        </select>
      </form>
    </div> -->
    <!-- End Single Widget  -->
  </div>
</div>