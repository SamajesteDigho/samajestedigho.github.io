---
layout: blogs
title: "Housekeeper Finder"
date: 2024-07-22 10:30:00 +0800
categories: jekyll update
category: mobile
image: "/assets/images/blog/housekeeper-logo.png"
alt: "housekeeperfinderlogo"
author: "SamajesteDigho"
author_image: "/assets/images/avatar.jpg"
fullname: "DIGHO D. T. Jordan"
accreditations: "Software Engineer"
---

<div class="row">
  <!-- ================================================== -->
  <!--              Start Principal Content Area          -->
  <!-- ================================================== -->
  <div class="col-lg-8">
    <!-- Start Banner Area -->
    <div class="banner banner-single-post post-formate post-layout axil-section-gapBottom">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <!-- Start Single Slide  -->
            <div class="content-block">
              <!-- Start Post Content  -->
              <div class="post-content">
                <div class="post-cat">
                  <div class="post-cat-list">
                    <a class="hover-flip-item-wrapper" href="#">
                      <span class="hover-flip-item">
                        <span data-text="BLOG POST">BLOG POST</span>
                      </span>
                    </a>
                  </div>
                </div>
                <h1 class="title">{{ page.title }}</h1>
                <!-- Post Meta  -->
                <div class="post-meta-wrapper">
                  <div class="post-meta">
                    <div class="post-author-avatar border-rounded">
                      <img src="{{ page.author_image }}" style="width: 100px; height: 100px;" alt="Author Images">
                    </div>
                    <div class="content">
                      <h6 class="post-author-name">
                        <a class="hover-flip-item-wrapper" href="#">
                          <span class="hover-flip-item">
                            <span data-text="{{ page.author }}">{{ page.author }}</span>
                          </span>
                        </a>
                      </h6>
                      <ul class="post-meta-list">
                        <li>{{ page.date | date_to_string }}</li>
                        <li>8 Views</li>
                      </ul>
                    </div>
                  </div>
                  <ul class="social-share-transparent justify-content-end">
                    <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                    <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                    <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                    <li><a href="#"><i class="fas fa-link"></i></a></li>
                  </ul>
                </div>
              </div>
              <!-- End Post Content  -->
            </div>
            <!-- End Single Slide  -->
          </div>
        </div>
      </div>
    </div>
    <!-- End Banner Area -->

    <div class="axil-post-details">
      <!-- <p class="has-small-font-size"> -->
      <p>
        The HouseKeeper Finder project is a project which is made to help those who are in
        need to get in touch with people who can help them to accomplish some home tasks like
        keeping the children, cleaning the house, ...
      </p>

      <figure class="wp-block-image">
        <img src="/assets/images/blog/housekeeper-banner.jpg" alt="Post Images">
        <figcaption>
          The caption of the image
        </figcaption>
      </figure>

      <p>
        This project was fully thought and realized by <b>DIGHO Jordan</b> who thought
        and realized the project in it integrality in a time frame of 3 weeks.
      </p>

      <blockquote>
        <p>
          “Mr XXX has a job that occupies him and his wife Mrs. XXX is also sometime between 2 planes for
          work purpose. They have 2 children who are scholars. There are actively looking for someone who
          can take them to school and bring them back, prepare food for them, clean thier cloths...”
        </p>
      </blockquote>

      <p>
        As mentionned earlier, this project have been thought and put in place for people
        who may because of one reason or the other, be in need of some assistance in thier
        home <i>(keep children, to clean the house, to do some shopping...)</i> to find close
        to their environment those who can be able t do this. The initial idea was to find people who
        can keep children in the abscence of thier parents, or to keep the house in general speeking.
        With this, I had the intention that the person in need can in this case hire the housekeeper
        to do the task on daily bases if the need is actually a permenent one. Progressively, I thought is
        will be better to enlarge it to express tasks like tasks which can be limited to just in a service
        of some minutes.
      </p>

      <h2>Accomplishements with the Project</h2>
      <figure class="wp-block-image">
        <img src="/assets/images/blog/housekeeper-architecture.png" alt="Post Images">
        <figcaption>
          Data flow architecture
        </figcaption>
      </figure>
      <p>
        It is important to know that the application we have put in place is a mobile (android) application
        and that we project to continue with the web application to make it more complete and accessible to all.<br />

      <ul>
        <li>
          <b>Frontend</b> :
          As the frontend is concerned, I used the flutter as framework which is based on the dart
          programming language. The app was tested on a <i>Google Pixel 7 pro</i> phone devices.
        </li>
        <li>
          <b>Backend</b> :
          <ul>
            <li>
              <b><i>Server</i></b>:
              For the server part, I choosed to use Laravel framework as developement tool. The choice was made
              based on my prior understanding of the framework and its large community in case any problem could
              as it was the case when trying to deploy the app on a web server with nginx.
            </li>
            <li>
              <b><i>Database</i></b>:
              The database I choosed to use in this case is MySQL due to the ease to table model of representing
              data and because it is also popuar and easily integrable on many servers.
            </li>
          </ul>
        </li>
      </ul>
      </p>

      <p>
        Some of the features we implemented are:
      <ul>
        <li>
          <b>Basic Token Authentication</b> :
          The API calls from the mobile app is base on Basic Token Authentication. Due to the fact
          that theenvironment where I am does not support Google services and Facebook, I could not
          be able to put in place a more secure authentication but it have been put into perspectif.
        </li>
        <li>
          <b>HouseKeeper Search</b> :
          With this functionality, the user can search a housekeeper based on certain criteria such as
          the name, the age range, the nationality, the religion and many more.
        </li>
      </ul>
      </p>

      <figure class="row">
        <div class="col-md-3"><img src="/assets/images/blog/housekeeper-home.png"></div>
        <div class="col-md-3"><img src="/assets/images/blog/housekeeper-search.png"></div>
        <div class="col-md-3"><img src="/assets/images/blog/housekeeper-tasks.png"></div>
        <div class="col-md-3"><img src="/assets/images/blog/housekeeper-profile.png"></div>
        <figcaption>
          Screenshots of principal pages of the mobile app
        </figcaption>
      </figure>


      <h2>Technical Challenge</h2>
      <p>
        At the very early stage of the frontend developement phase, I was confronted with a quite exasperating
        difficulty.
        Since I decided to use flutter for this purpose, I did not come to realize that the official links for the
        initialization
        of the project and the libraries required in developing and running the project were not accessible in my
        region. I am presently
        residing in China, and there are many sites and library repositories which are not accessible from here. It was
        quite difficult to
        find a solution through that since the websites I commonly us to search for some solutions like starkoveflow is
        also difficultly
        accessible here. After conducting a series of search as this was concerned, I found that it can be possible to
        go around this issue
        by search mirror sites which are accessible in China and can offer the basic libraries needed for the app to be
        initialized and run
        properly. Even though the is a series of libraries and soeme versions which are not accessible, but I came
        through the biggest part
        of the problem.
      </p>


      <h3>What I learned</h3>
      <p>
      <ul>
        Even though it connot be listed all here because there a certain things that I learned for sur
        but I am not imidiately conscious of them, here are the most evident ones :
        <li>
          <b>Application development flow and best practices.</b> Through out the learning process, I have come through
          things that really as an autoictact
          would have not be easy for me to come through and apprehend. I learned about best practices of programming and
          steps to go through when we was to
          build and app completely. This project was an exemple and I really happy of the outccomings of this project.
        </li>
        <li>
          <b>Configured a server and hosted my app.</b> This is one of the things I have never done before principally
          due to
          lack of ressources but also due to lack of the knowledge. With this project, I configure a web server and
          hosted my
          application and it is available online. It is just a great acheivement for me and I think I'm gone to do
          better as time moves on.
        </li>
        <li>
          <b>About my engineering habilities.</b> The most important thing I can say that I have learned is that the
          work of an engineer is not easy
          but due to this, it is passionating and if one puts in the required efforts, it will be an exciting journey.
          This project wasan example. It
          is not perfect nor too good, but I thing it is a good start.
        </li>
      </ul>
      </p>

      <h2>Conclusion</h2>
      It was a great journey through out this project, I learned, I failed, I continued to learn untill I got a result,
      even as minim as it is, I think
      it is the promese that I can do better with additional efforts. Focused on developping more and more, I thanks you
      for having taken time to go through
      this post.

      <div class="tagcloud">
        <a href="#">Design</a>
        <a href="#">Development</a>
        <a href="#">Mobile</a>
      </div>

      <div class="social-share-block">
        <div class="post-like">
          <!-- <a href="#"><i class="fal fa-thumbs-up"></i><span>2.2k Like</span></a> -->
        </div>
        <ul class="social-icon icon-rounded-transparent md-size">
          <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
          <li><a href="#"><i class="fab fa-instagram"></i></a></li>
          <li><a href="#"><i class="fab fa-twitter"></i></a></li>
          <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
        </ul>
      </div>


      <!-- Start Author  -->
      <div class="about-author">
        <div class="media">
          <div class="thumbnail">
            <a href="#">
              <img src="{{ page.author_image }}" style="width: 100px; height: 100px;" alt="Author Images">
            </a>
          </div>
          <div class="media-body">
            <div class="author-info">
              <h5 class="title">
                <a class="hover-flip-item-wrapper" href="#">
                  <span class="hover-flip-item">
                    <span data-text="{{ page.author }}">{{ page.fullname }}</span>
                  </span>
                </a>
              </h5>
              <span class="b3 subtitle">{{ page.accreditations }}</span>
            </div>
            <div class="content">
              <p class="b1 description">
                I am 25 years old an am a graduate student at the National Advanced School of Engineering - Yaounde.
                I actually continue my studies in China where I'm presently studying the Chinese language in order
                to pursue my Ph.D.
              </p>

              <ul class="social-share-transparent size-md">
                <li><a href="https://www.facebook.com/samajeste.dighojordan.7?mibextid=ZbWKwL"><i
                      class="fab fa-facebook-f"></i></a></li>
                <li><a href="https://github.com/samajestedigho"><i class="fab fa-github"></i></a></li>
                <li><a href="https://www.linkedin.com/in/samajesteDigho"><i class="fab fa-linkedin-in"></i></a></li>
              </ul>
            </div>
          </div>
        </div>
        <ul>
          <li>Project Repository: <a href="https://github.com/samajestedigho/housekeeper.git">Click here</a></li>
          <li>Deployed Project Page : <a href="http://housekeeper.samajestedigho.tech/">Click here</a></li>
          <li>Project Landing Page : <a href="http://housekeeper.samajestedigho.tech/">Click here</a></li>
        </ul>
      </div>
    </div>

  </div>

  <!-- ================================================== -->
  <!--              Start Sidebar Area                    -->
  <!-- ================================================== -->
  {% include blog_right_sidebar.markdown %}
  <!-- End Sidebar Area  -->

</div>