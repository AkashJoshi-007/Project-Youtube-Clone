<!DOCTYPE html>
<html>
  <head>
    <title>Youtube Clone</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="Styles/general.css">
    <link rel="stylesheet" href="Styles/header.css">
    <link rel="stylesheet" href="Styles/vedio.css">
    <link rel="stylesheet" href="Styles/sidebar.css">
  </head>

  <body>
    <header class="header-el">
      <div class="left-section">
          <img class="hamburger-menu" src="icons/hamburger-menu.svg">

          <img class="youtube-logo" src="icons/youtube-logo.svg">
      </div>
      
      <div class="middle-section" >
        <input class="search-bar" type="text" placeholder="Search">

        <button class="search-btn-el">
          <img class="search-icon" src="icons/search.svg">
          <div class="tooltip">Search</div> 
        </button>

        <button class="voice-search-btn-el">
          <img class="voice-search-icon" src="icons/voice-search-icon.svg">
          <div class="tooltip">Search With Your Voice</div>
        </button>
      </div>

      <div class="right-section">
        
        <div class="upload-icon-el">
          <img class="upload-icon" src="icons/upload.svg">
          <div class="tooltip">Creat</div>   
        </div>
        
        <div class="youtube-apps-el">
          <img class="youtube-apps" src="icons/youtube-apps.svg">
          <div class="tooltip">Apps</div>
        </div>
        

        <div class="notifications-icon-el">
          <img class="notifications-icon" src="icons/notifications.svg">

          <div class="notifications-count">3</div>
          <div class="tooltip">Notifications</div>
        </div>

        <img class="profile" src="channel-pics/unnamed.jpg">
      </div>
      
    </header>

    <nav class="side-bar-el">
      <div class="side-bar-boxes">
        <img class="sidebar-img-el" src="icons/home.svg">
        <p class="side-bar-text-el">Home</p>
      </div>

      <div class="side-bar-boxes">
        <img class="sidebar-img-el" src="icons/explore.svg">
        <p class="side-bar-text-el">Explore</p>
      </div>

      <div class="side-bar-boxes">
        <img class="sidebar-img-el" src="icons/subscriptions.svg">
        <p class="side-bar-text-el">Subscriptions</p>
      </div>

      <div class="side-bar-boxes">
        <img class="sidebar-img-el" src="icons/originals.svg">
        <p class="side-bar-text-el">Originals</p>
      </div>

      <div class="side-bar-boxes">
        <img class="sidebar-img-el" src="icons/youtube-music.svg">
        <p class="side-bar-text-el">Youtube-Music</p>
      </div>

      <div class="side-bar-boxes">
        <img class="sidebar-img-el" src="icons/library.svg">
        <p class="side-bar-text-el">Library</p>
      </div>
    </nav>
    
    
    <main>
      <section class="final-grid">  
      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-1.webp">
          <div class="vedio-time">14.30</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-1.jpeg"> 
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
              Talking Tech and AI with Google CEO Sundar Pichai!
            </p>
      
            <p class="video-author">
              Marques Brownlee
            </p>
      
            <p class="video-stats">
              3.4M views &#183; 6 months ago
            </p> 
          </div> 
          
        </div>
      </div>

      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-2.webp">
          <div class="vedio-time">08:22</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-2.jpeg"> 
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
              Try Not To Laugh Challenge #9
            </p>
            <p class="video-author">
              Markiplier
            </p>
            <p class="video-stats">
              19M views &#183; 4 years ago
            </p>
          </div> 
          
        </div>
      </div>

      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-3.webp">
          <div class="vedio-time">09:13</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-3.jpeg">
             
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
              Crazy Tik Toks Taken Moments Before DISASTER
            </p>
            <p class="video-author">
              SSSniperWolf
            </p>
            <p class="video-stats">
              12M views &#183; 1 year ago
            </p> 
          </div> 
          
        </div>
      </div>

      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-4.webp">
          <div class="vedio-time">22:09</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-4.jpeg"> 
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
              The Simplest Math Problem No One Can Solve - Collatz Conjecture
            </p>
            <p class="video-author">
              Veritasium
            </p>
            <p class="video-stats">
              18M views &#183; 4 months ago
            </p>
          </div> 
          
        </div>
      </div>

      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-5.webp">
          <div class="vedio-time">11:17</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-5.jpeg"> 
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
              Kadane's Algorithm to Maximum Sum Subarray Problem
            </p>
            <p class="video-author">
              CS Dojo
            </p>
            <p class="video-stats">
              519K views &#183; 5 years ago
            </p> 
          </div> 
          
        </div>
      </div>

      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-6.webp">
          <div class="vedio-time">19:59</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-6.jpeg"> 
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
                Anything You Can Fit In The Circle I’ll Pay For
              </p>
              <p class="video-author">
                MrBeast
              </p>
              <p class="video-stats">
                141M views &#183; 1 year ago
              </p>
          </div> 
        
        </div>
      </div>

      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-5.webp">
          <div class="vedio-time">11:17</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-5.jpeg"> 
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
              Kadane's Algorithm to Maximum Sum Subarray Problem
            </p>
            <p class="video-author">
              CS Dojo
            </p>
            <p class="video-stats">
              519K views &#183; 5 years ago
            </p> 
          </div> 
          
        </div>
      </div>

      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-2.webp">
          <div class="vedio-time">08:22</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-2.jpeg"> 
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
              Try Not To Laugh Challenge #9
            </p>
            <p class="video-author">
              Markiplier
            </p>
            <p class="video-stats">
              19M views &#183; 4 years ago
            </p>
          </div> 
          
        </div>
      </div>

      <div class="vedio-preview">

        <div class="thumnail-el"> <!--Verical Element-1-->
          <img class="image-el" src="thumbnails/thumbnail-3.webp">
          <div class="vedio-time">09:13</div>
        </div>

        <div class="creater-info-grid"> <!--Verical Element-2-->

          <div class="creater-pic"> <!--Horizontal Element-1(Inside Verical Element-2)-->
            <img class="profile-pic" src="channel-pics/channel-3.jpeg">
             
          </div>  

          <div class="vedio-info"><!--Horizontal Element-2(Inside Verical Element-2)-->
            <p class="video-title">
              Crazy Tik Toks Taken Moments Before DISASTER
            </p>
            <p class="video-author">
              SSSniperWolf
            </p>
            <p class="video-stats">
              12M views &#183; 1 year ago
            </p> 
          </div> 
          
        </div>
      </div>

      

      </section>
    </main>
    
  </body>
</html>
