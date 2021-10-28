# 小西瓜

<!DOCTYPE HTML>
<html lang="zh-CN">


<head>
    <meta charset="utf-8">
    <meta name="keywords" content="HTML,CSS,JavaScript,JQuery,React,Vue.js,node.js,git,github,hexo">
    <meta name="description" content="专注于Web前端,分享生活,分享知识">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <meta name="renderer" content="webkit|ie-stand|ie-comp">
    <meta name="mobile-web-app-capable" content="yes">
    <meta name="format-detection" content="telephone=no">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    <!-- Global site tag (gtag.js) - Google Analytics -->


    <title>XiaoQi&#39;s Blog</title>
    <link rel="icon" type="image/png" href="/favicon.png">

    <link rel="stylesheet" type="text/css" href="/libs/awesome/css/all.css">
    <link rel="stylesheet" type="text/css" href="/libs/materialize/materialize.min.css">
    <link rel="stylesheet" type="text/css" href="/libs/aos/aos.css">
    <link rel="stylesheet" type="text/css" href="/libs/animate/animate.min.css">
    <link rel="stylesheet" type="text/css" href="/libs/lightGallery/css/lightgallery.min.css">
    <link rel="stylesheet" type="text/css" href="/css/matery.css">
    <link rel="stylesheet" type="text/css" href="/css/my.css">

    <script src="/libs/jquery/jquery.min.js"></script>
    
<meta name="generator" content="Hexo 4.2.1"><link rel="stylesheet" href="/css/prism-tomorrow.css" type="text/css"></head>


    <body>
        <header class="navbar-fixed">
    <nav id="headNav" class="bg-color nav-transparent">
        <div id="navContainer" class="nav-wrapper container">
            <div class="brand-logo">
                <a href="/" class="waves-effect waves-light">
                    
                    <img src="/medias/logo.png" class="logo-img" alt="LOGO">
                    
                    <span class="logo-span">XiaoQi's Blog</span>
                </a>
            </div>
            

<a href="#" data-target="mobile-nav" class="sidenav-trigger button-collapse"><i class="fas fa-bars"></i></a>
<ul class="right nav-menu">
  
  <li class="hide-on-med-and-down nav-item">
    
    <a href="/" class="waves-effect waves-light">
      
      <i class="fas fa-home" style="zoom: 0.6;"></i>
      
      <span>首页</span>
    </a>
    
  </li>
  
  <li class="hide-on-med-and-down nav-item">
    
    <a href="/tags" class="waves-effect waves-light">
      
      <i class="fas fa-tags" style="zoom: 0.6;"></i>
      
      <span>标签</span>
    </a>
    
  </li>
  
  <li class="hide-on-med-and-down nav-item">
    
    <a href="/categories" class="waves-effect waves-light">
      
      <i class="fas fa-bookmark" style="zoom: 0.6;"></i>
      
      <span>分类</span>
    </a>
    
  </li>
  
  <li class="hide-on-med-and-down nav-item">
    
    <a href="/archives" class="waves-effect waves-light">
      
      <i class="fas fa-archive" style="zoom: 0.6;"></i>
      
      <span>归档</span>
    </a>
    
  </li>
  
  <li class="hide-on-med-and-down nav-item">
    
    <a href="/about" class="waves-effect waves-light">
      
      <i class="fas fa-user-circle" style="zoom: 0.6;"></i>
      
      <span>关于</span>
    </a>
    
  </li>
  
  <li class="hide-on-med-and-down nav-item">
    
    <a href="/contact" class="waves-effect waves-light">
      
      <i class="fas fa-comments" style="zoom: 0.6;"></i>
      
      <span>留言板</span>
    </a>
    
  </li>
  
  <li class="hide-on-med-and-down nav-item">
    
    <a href="/friends" class="waves-effect waves-light">
      
      <i class="fas fa-address-book" style="zoom: 0.6;"></i>
      
      <span>友情链接</span>
    </a>
    
  </li>
  
  <li>
    <a href="#searchModal" class="modal-trigger waves-effect waves-light">
      <i id="searchIcon" class="fas fa-search" title="搜索" style="zoom: 0.85;"></i>
    </a>
  </li>
</ul>

<div id="mobile-nav" class="side-nav sidenav">

    <div class="mobile-head bg-color">
        
        <img src="/medias/logo.png" class="logo-img circle responsive-img">
        
        <div class="logo-name">XiaoQi's Blog</div>
        <div class="logo-desc">
            
            专注于Web前端,分享生活,分享知识
            
        </div>
    </div>

    

    <ul class="menu-list mobile-menu-list">
        
        <li class="m-nav-item">
	  
		<a href="/" class="waves-effect waves-light">
			
			    <i class="fa-fw fas fa-home"></i>
			
			首页
		</a>
          
        </li>
        
        <li class="m-nav-item">
	  
		<a href="/tags" class="waves-effect waves-light">
			
			    <i class="fa-fw fas fa-tags"></i>
			
			标签
		</a>
          
        </li>
        
        <li class="m-nav-item">
	  
		<a href="/categories" class="waves-effect waves-light">
			
			    <i class="fa-fw fas fa-bookmark"></i>
			
			分类
		</a>
          
        </li>
        
        <li class="m-nav-item">
	  
		<a href="/archives" class="waves-effect waves-light">
			
			    <i class="fa-fw fas fa-archive"></i>
			
			归档
		</a>
          
        </li>
        
        <li class="m-nav-item">
	  
		<a href="/about" class="waves-effect waves-light">
			
			    <i class="fa-fw fas fa-user-circle"></i>
			
			关于
		</a>
          
        </li>
        
        <li class="m-nav-item">
	  
		<a href="/contact" class="waves-effect waves-light">
			
			    <i class="fa-fw fas fa-comments"></i>
			
			留言板
		</a>
          
        </li>
        
        <li class="m-nav-item">
	  
		<a href="/friends" class="waves-effect waves-light">
			
			    <i class="fa-fw fas fa-address-book"></i>
			
			友情链接
		</a>
          
        </li>
        
        
        <li><div class="divider"></div></li>
        <li>
            <a href="https://github.com/blinkfox/hexo-theme-matery" class="waves-effect waves-light" target="_blank">
                <i class="fab fa-github-square fa-fw"></i>Fork Me
            </a>
        </li>
        
    </ul>
</div>

        </div>

        
            <style>
    .nav-transparent .github-corner {
        display: none !important;
    }
    
    .github-corner {
        position: absolute;
        z-index: 10;
        top: 0;
        right: 0;
        border: 0;
        transform: scale(1.1);
    }
    
    .github-corner svg {
        color: #ff00cc;
        fill: #fff;
        height: 64px;
        width: 64px;
    }
    
    .github-corner:hover .octo-arm {
        animation: a 0.56s ease-in-out;
    }
    
    .github-corner .octo-arm {
        animation: none;
    }
    
    @keyframes a {
        0%,
        to {
            transform: rotate(0);
        }
        20%,
        60% {
            transform: rotate(-25deg);
        }
        40%,
        80% {
            transform: rotate(10deg);
        }
    }
</style>

<a href="https://github.com/blinkfox/hexo-theme-matery" class="github-corner tooltipped hide-on-med-and-down" target="_blank" data-tooltip="Fork Me" data-position="left" data-delay="50">
    <svg viewBox="0 0 250 250" aria-hidden="true">
        <path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path>
        <path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2"
              fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path>
        <path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z"
              fill="currentColor" class="octo-body"></path>
    </svg>
</a>
        
    </nav>

</header>

            
<style>
    .carousel-control {
        width: 45px;
        height: 45px;
        line-height: 55px;
        border-radius: 45px;
        background: transparent;
        cursor: pointer;
        z-index: 100;
    }
    
    #prev-cover {
        position: absolute;
        top: 48%;
        left: 8px;
    }
    
    #next-cover {
        position: absolute;
        top: 48%;
        right: 8px;
        ;
    }
    
    #prev-cover i {
        margin-right: 3px;
    }
    
    #next-cover i {
        margin-left: 3px;
    }
    
    .carousel-control:hover {
        background-color: rgba(0, 0, 0, .4);
    }
    
    .carousel-control i {
        color: #fff;
        font-size: 2.4rem;
    }
</style>



    <div class="carousel carousel-slider center index-cover" data-indicators="true" style="margin-top: -64px;">
        

                <div class="carousel-item red white-text bg-cover about-cover">
                    <div class="container">
                        <div class="row">
    <div class="col s10 offset-s1 m8 offset-m2 l8 offset-l2">
        <div class="brand">
            <div class="title center-align">
                
                    Serious life.
                        
            </div>

            <div class="description center-align">
                
                    <span id="subtitle"></span>
                    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.11"></script>
                    <script>
                        var typed = new Typed("#subtitle", {
                            strings: ['每一个不曾起舞的日子，都是对生命的辜负。', '不爱折腾的前端，跟咸鱼有什么区别。'],
                            startDelay: 300,
                            typeSpeed: 100,
                            loop: true,
                            backSpeed: 50,
                            showCursor: true
                        });
                    </script>
                    
            </div>
        </div>
    </div>
</div>


        <script>
            $('.bg-cover').css('background-image', 'url(/medias/banner/0.jpg)');
        </script>
        

                            <div class="cover-btns">
                                <a href="#indexCard" class="waves-effect waves-light btn">
                                    <i class="fa fa-angle-double-down"></i>
                                    开始阅读
                                </a>

                                
                                    <a href="https://github.com/manitoYang97" class="waves-effect waves-light btn" target="_blank">
                        <i class="fab fa-github-alt"></i>Github
                    </a>
                                    
                            </div>
                            <div class="cover-social-link">
                                
    <a href="https://github.com/manitoYang97" class="tooltipped" target="_blank" data-tooltip="访问我的GitHub" data-position="top" data-delay="50">
        <i class="fab fa-github"></i>
    </a>



    <a href="mailto:1678271576@qq.com" class="tooltipped" target="_blank" data-tooltip="邮件联系我" data-position="top" data-delay="50">
        <i class="fas fa-envelope-open"></i>
    </a>







    <a href="tencent://AddContact/?fromId=50&fromSubId=1&subcmd=all&uin=1678271576" class="tooltipped" target="_blank" data-tooltip="QQ联系我: 1678271576" data-position="top" data-delay="50">
        <i class="fab fa-qq"></i>
    </a>







    <a href="/atom.xml" class="tooltipped" target="_blank" data-tooltip="RSS 订阅" data-position="top" data-delay="50">
        <i class="fas fa-rss"></i>
    </a>


                            </div>
                    </div>
                </div>

                
    </div>

    <script>
        // TODO 此处的轮播尚需优化，PC/Mobile 在触摸切换时都感觉相当不灵活
        $(function() {
            let coverSlider = $('.carousel');

            //用户触摸轮播自动 restartPlay 是否生效
            let initUserPressedOrDraggedActive = false

            //用户触摸轮播自动 restartPlay
            function initUserPressedOrDragged(instance) {
                setInterval(() => {
                    if (instance.pressed || instance.dragged) {
                        // console.log('initUserPressedOrDragged: ',instance.pressed,instance.dragged)
                        restartPlay()
                    }
                }, 1000)
            }

            coverSlider.carousel({
                duration: Number('120'),
                fullWidth: true,
                indicators: 'true' === 'true',
                onCycleTo() {
                    if (!initUserPressedOrDraggedActive) {
                        // console.log('initUserPressedOrDraggedActive')
                        initUserPressedOrDragged(this)
                        initUserPressedOrDraggedActive = true
                    }
                },
            })

            let carouselIntervalId;
            
            // Loop to call the next cover article picture.
            let autoCarousel = function() {
                carouselIntervalId = setInterval(function() {
                    coverSlider.carousel('next');
                }, 5000);
            };
            autoCarousel();
            

            function restartPlay() {
                
                clearInterval(carouselIntervalId);
                autoCarousel();
                
            };

            
            // prev and next cover post.
            $('#prev-cover').click(function() {
                coverSlider.carousel('prev');
                restartPlay();
            });
            $('#next-cover').click(function() {
                coverSlider.carousel('next');
                restartPlay();
            });
            
        });
    </script>


<main class="content">

    
    <div id="indexCard" class="index-card">
        <div class="container ">
            <div class="card">
                <div class="card-content">
                    
                        <div class="dream">
    
    <div class="title center-align">
        <i class="far fa-lightbulb"></i>&nbsp;&nbsp;Serendipity
    </div>
    
    <div class="row">
        <div class="col l8 offset-l2 m10 offset-m1 s10 offset-s1 center-align text">
            努力的意义，就是，以后的日子里，放眼望去，全部都是自己喜欢的人和事。
        </div>
    </div>
</div>
                    

                    

                    

                    
                    <div id="recommend-sections" class="recommend">
                        



                    </div>
                    
                </div>
            </div>
        </div>
    </div>
    

    

    <!-- 所有文章卡片 -->
    <article id="articles" class="container articles">
        <div class="row article-row">
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2021/05/01/%E6%90%AD%E5%BB%BA%E5%8D%9A%E5%AE%A2/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/21.jpg" class="responsive-img" alt="搭建博客">
                            
                            <span class="card-title">搭建博客</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                搭建博客前言​        收到很多留言和联系我怎么搭建一个博客，但是由于工作比较忙，所有就没有给大家都回复到，还有很多同学想让我给搭建博客，但是我觉得授人以鱼不如授人以渔，所以整理出来一些我搭建过程中的主要步骤。在之后如果有时间或者有人
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2021-05-01
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/blog/" class="post-category">
                                    blog
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/blog/">
                            <span class="chip bg-color">blog</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2021/05/01/%E5%AE%9E%E4%B9%A0%E6%84%9F%E6%82%9F%E4%B8%80/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/5.jpg" class="responsive-img" alt="关于实习">
                            
                            <span class="card-title">关于实习</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                这是我第一次正式的实习工作，有时候觉得还挺幸运的，能找到一个自己理想中的工作，我还记得我刚开始接触前端的时候，除了每天在网上在资料学习，还有就是在网上搜索前端程序员的一天工作都是在干什么，有一个印象很深的回答：一天 一支烟 一个BUG 完。
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2021-05-01
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/%E6%84%9F%E6%82%9F/" class="post-category">
                                    感悟
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/%E6%84%9F%E6%82%9F/">
                            <span class="chip bg-color">感悟</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/09/28/Vuex/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/10.jpg" class="responsive-img" alt="Vuex">
                            
                            <span class="card-title">Vuex</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                Vuex是一个全局数据管理的一种机制，可以方便的实现数据的共享
使用Vuex管理数据的好处A.能够在vuex中集中管理共享的数据，便于开发和后期进行维护B.能够高效的实现组件之间的数据共享，提高开发效率C.存储在vuex中的数据是响应式的，
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-09-28
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/web%E5%89%8D%E7%AB%AF/" class="post-category">
                                    web前端
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/vue/">
                            <span class="chip bg-color">vue</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/09/23/%E5%85%B3%E4%BA%8EES6/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/19.jpg" class="responsive-img" alt="关于ES6">
                            
                            <span class="card-title">关于ES6</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                let命令ES6 新增了let命令，用来声明变量。它的用法类似于var，但是所声明的变量，只在let命令所在的代码块内有效。
for循环的计数器，就很合适使用let命令。
let在for循环还有一个特别之处，就是设置循环变量的那部分是一个父
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-09-23
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/web%E5%89%8D%E7%AB%AF/" class="post-category">
                                    web前端
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/ES6/">
                            <span class="chip bg-color">ES6</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/09/23/%E6%89%BE%E5%88%B0%E6%95%B0%E7%BB%84%E4%B8%AD%E7%AC%A6%E5%90%88%E6%9D%A1%E4%BB%B6%E7%9A%84%E6%95%B0/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/6.jpg" class="responsive-img" alt="超级简历一面">
                            
                            <span class="card-title">超级简历一面</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                找到数组中符合条件的数findfind方法，用于找出第一个符合条件的数组成员。它的参数是一个回调函数，所有数组成员依次执行该回调函数，直到找出第一个返回值为true的成员，然后返回该成员。如果没有符合条件的成员，则返回undefined。

                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-09-23
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/%E5%89%8D%E7%AB%AF%E9%9D%A2%E8%AF%95/" class="post-category">
                                    前端面试
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/%E9%9D%A2%E8%AF%95%E9%A2%98/">
                            <span class="chip bg-color">面试题</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/08/19/this%E5%85%A8%E9%9D%A2%E8%A7%A3%E6%9E%90/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/21.jpg" class="responsive-img" alt="this全面解析">
                            
                            <span class="card-title">this全面解析</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                
this 关键字是 JavaScript 中最复杂的机制之一。它是一个很特别的关键字，被自动定义在 所有函数的作用域中。但是即使是非常有经验的 JavaScript 开发者也很难说清它到底指向 什么。
实际上，JavaScript 中 t
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-08-19
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/web%E5%89%8D%E7%AB%AF/" class="post-category">
                                    web前端
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84JavaScript/">
                            <span class="chip bg-color">你不知道的JavaScript</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/08/19/%E4%BD%9C%E7%94%A8%E5%9F%9F/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/11.jpg" class="responsive-img" alt="作用域">
                            
                            <span class="card-title">作用域</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                1.作用域

作用域是一套规则，用于确定在何处以及如何查找变量（标识符）。
如果查找的目的是对 变量进行赋值，那么就会使用 LHS 查询；如果目的是获取变量的值，就会使用 RHS 查询。
赋值操作符会导致 LHS 查询。＝操作符或调用函数时
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-08-19
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/web%E5%89%8D%E7%AB%AF/" class="post-category">
                                    web前端
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84JavaScript/">
                            <span class="chip bg-color">你不知道的JavaScript</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/08/06/Vue/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/22.jpg" class="responsive-img" alt="Vue">
                            
                            <span class="card-title">Vue</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                数据与方法当一个 Vue 实例被创建时，它将 数据 对象中的所有的 属性加入到 Vue 的响应式系统中。当这些 属性 的值发生改变时，视图将会产生“响应”，即匹配更新为新的值。值得注意的是只有当实例被创建时就已经存在于数据中的属性才是响应式
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-08-06
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-user fa-fw"></i>
                                XiaoQi
                                
                            </span>
                        </div>
                    </div>

                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/08/04/promise/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/19.jpg" class="responsive-img" alt="Promise">
                            
                            <span class="card-title">Promise</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                JavaScript 执行机制
javascript是一门单线程语言不能同时处理多个任务，把任务分成了同步和异步。
事件循环Event Loop事件循环是js实现异步的一种方法，也是js的执行机制。

同步和异步任务分别进入不同的执行”场所
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-08-04
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/web%E5%89%8D%E7%AB%AF/" class="post-category">
                                    web前端
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84JavaScript/">
                            <span class="chip bg-color">你不知道的JavaScript</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/08/03/%E7%B1%BB%E5%9E%8B%E5%92%8C%E8%AF%AD%E6%B3%95/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/4.jpg" class="responsive-img" alt="类型和语法">
                            
                            <span class="card-title">类型和语法</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                1.类型

JavaScript 有 七 种 内 置 类 型：null、undefined、boolean、number、string、object 和 symbol，可以使用 typeof 运算符来查看。
变量没有类型，但它们持有的值有类
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-08-03
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/web%E5%89%8D%E7%AB%AF/" class="post-category">
                                    web前端
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84JavaScript/">
                            <span class="chip bg-color">你不知道的JavaScript</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/08/01/%E4%BD%9C%E7%94%A8%E5%9F%9F%E9%97%AD%E5%8C%85/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/0.jpg" class="responsive-img" alt="闭包">
                            
                            <span class="card-title">闭包</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                作用域闭包

闭包就好像从 JavaScript 中分离出来的一个充满神秘色彩的未开化世界，只有最勇敢的人 才能够到达那里。但实际上它只是一个标准，显然就是关于如何在函数作为值按需传递的 词法环境中书写代码的。
当函数可以记住并访问所在的词
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-08-01
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/web%E5%89%8D%E7%AB%AF/" class="post-category">
                                    web前端
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84JavaScript/">
                            <span class="chip bg-color">你不知道的JavaScript</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
            <div class="article col s12 m6 l4" data-aos="zoom-in">
                <div class="card">
                    <a href="/2020/08/01/%E5%AF%B9%E8%B1%A1%E5%92%8C%E7%B1%BB/">
                        <div class="card-image">
                            
                            
                            <img src="/medias/featureimages/7.jpg" class="responsive-img" alt="对象和类">
                            
                            <span class="card-title">对象和类</span>
                        </div>
                    </a>

                    <div class="card-content article-content">
                        <div class="summary block-with-text">
                            
                                对象

JavaScript 中的对象有字面形式（比如 var a = { .. }）和构造形式（比如 var a = new Array(..)）。字面形式更常用，不过有时候构造形式可以提供更多选项。

许多人都以为“JavaScript
                            
                        </div>
                        <div class="publish-info">
                            <span class="publish-date">
                                <i class="far fa-clock fa-fw icon-date"></i>2020-08-01
                            </span>
                            <span class="publish-author">
                                
                                <i class="fas fa-bookmark fa-fw icon-category"></i>
                                
                                <a href="/categories/web%E5%89%8D%E7%AB%AF/" class="post-category">
                                    web前端
                                </a>
                                
                                
                            </span>
                        </div>
                    </div>

                    
                    <div class="card-action article-tags">
                        
                        <a href="/tags/%E4%BD%A0%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%84JavaScript/">
                            <span class="chip bg-color">你不知道的JavaScript</span>
                        </a>
                        
                    </div>
                    
                </div>
            </div>
            
        </div>
    </article>

</main>


<div class="container paging">
    <div class="row">
        <div class="col s6 m4 l4">
            
            <a class="left btn-floating btn-large disabled">
                <i class="fas fa-angle-left"></i>
            </a>
            
        </div>
        <div class="page-info col m4 l4 hide-on-small-only">
            <div class="center-align b-text-gray">1 / 2</div>
        </div>
        <div class="col s6 m4 l4">
            
            <a href="/page/2/"
               class="right btn-floating btn-large waves-effect waves-light bg-color">
                <i class="fas fa-angle-right"></i>
            </a>
            
        </div>
    </div>
</div>




                <footer class="page-footer bg-color">
    
    <div class="container row center-align" style="margin-bottom: 15px !important;">
        <div class="col s12 m8 l8 copy-right">
            Copyright&nbsp;&copy;
            <span id="year">2020</span>
            <a href="https://www.iamys.club" target="_blank">XiaoQi</a>
            |&nbsp;Powered by&nbsp;<a href="https://hexo.io/" target="_blank">Hexo</a>
            |&nbsp;Theme&nbsp;<a href="https://github.com/blinkfox/hexo-theme-matery" target="_blank">Matery</a>
            <br>
            
            &nbsp;<i class="fas fa-chart-area"></i>&nbsp;站点总字数:&nbsp;<span
                class="white-color">61k</span>&nbsp;字
            
            
            
            
            
            
            <span id="busuanzi_container_site_pv">
                |&nbsp;<i class="far fa-eye"></i>&nbsp;总访问量:&nbsp;<span id="busuanzi_value_site_pv"
                    class="white-color"></span>&nbsp;次
            </span>
            
            
            <span id="busuanzi_container_site_uv">
                |&nbsp;<i class="fas fa-users"></i>&nbsp;总访问人数:&nbsp;<span id="busuanzi_value_site_uv"
                    class="white-color"></span>&nbsp;人
            </span>
            
            <br>
            
            <span id="sitetime">载入运行时间...</span>
            <script>
                function siteTime() {
                    var seconds = 1000;
                    var minutes = seconds * 60;
                    var hours = minutes * 60;
                    var days = hours * 24;
                    var years = days * 365;
                    var today = new Date();
                    var startYear = "2020";
                    var startMonth = "4";
                    var startDate = "6";
                    var startHour = "0";
                    var startMinute = "0";
                    var startSecond = "0";
                    var todayYear = today.getFullYear();
                    var todayMonth = today.getMonth() + 1;
                    var todayDate = today.getDate();
                    var todayHour = today.getHours();
                    var todayMinute = today.getMinutes();
                    var todaySecond = today.getSeconds();
                    var t1 = Date.UTC(startYear, startMonth, startDate, startHour, startMinute, startSecond);
                    var t2 = Date.UTC(todayYear, todayMonth, todayDate, todayHour, todayMinute, todaySecond);
                    var diff = t2 - t1;
                    var diffYears = Math.floor(diff / years);
                    var diffDays = Math.floor((diff / days) - diffYears * 365);
                    var diffHours = Math.floor((diff - (diffYears * 365 + diffDays) * days) / hours);
                    var diffMinutes = Math.floor((diff - (diffYears * 365 + diffDays) * days - diffHours * hours) /
                        minutes);
                    var diffSeconds = Math.floor((diff - (diffYears * 365 + diffDays) * days - diffHours * hours -
                        diffMinutes * minutes) / seconds);
                    if (startYear == todayYear) {
                        document.getElementById("year").innerHTML = todayYear;
                        document.getElementById("sitetime").innerHTML = "本站已安全运行 " + diffDays + " 天 " + diffHours +
                            " 小时 " + diffMinutes + " 分钟 " + diffSeconds + " 秒";
                    } else {
                        document.getElementById("year").innerHTML = startYear + " - " + todayYear;
                        document.getElementById("sitetime").innerHTML = "本站已安全运行 " + diffYears + " 年 " + diffDays +
                            " 天 " + diffHours + " 小时 " + diffMinutes + " 分钟 " + diffSeconds + " 秒";
                    }
                }
                setInterval(siteTime, 1000);
            </script>
            
            <br>
            
        </div>
        <div class="col s12 m4 l4 social-link social-statis">
    <a href="https://github.com/manitoYang97" class="tooltipped" target="_blank" data-tooltip="访问我的GitHub" data-position="top" data-delay="50">
        <i class="fab fa-github"></i>
    </a>



    <a href="mailto:1678271576@qq.com" class="tooltipped" target="_blank" data-tooltip="邮件联系我" data-position="top" data-delay="50">
        <i class="fas fa-envelope-open"></i>
    </a>







    <a href="tencent://AddContact/?fromId=50&fromSubId=1&subcmd=all&uin=1678271576" class="tooltipped" target="_blank" data-tooltip="QQ联系我: 1678271576" data-position="top" data-delay="50">
        <i class="fab fa-qq"></i>
    </a>







    <a href="/atom.xml" class="tooltipped" target="_blank" data-tooltip="RSS 订阅" data-position="top" data-delay="50">
        <i class="fas fa-rss"></i>
    </a>

</div>
    </div>
</footer>

<div class="progress-bar"></div>


                    <!-- 搜索遮罩框 -->
<div id="searchModal" class="modal">
    <div class="modal-content">
        <div class="search-header">
            <span class="title"><i class="fas fa-search"></i>&nbsp;&nbsp;搜索</span>
            <input type="search" id="searchInput" name="s" placeholder="请输入搜索的关键字"
                   class="search-input">
        </div>
        <div id="searchResult"></div>
    </div>
</div>

<script src="/js/search.js"></script>
<script type="text/javascript">
$(function () {
    searchFunc("/" + "search.xml", 'searchInput', 'searchResult');
});
</script>
                        <!-- 回到顶部按钮 -->
<div id="backTop" class="top-scroll">
    <a class="btn-floating btn-large waves-effect waves-light" href="#!">
        <i class="fas fa-arrow-up"></i>
    </a>
</div>


                            <script src="/libs/materialize/materialize.min.js"></script>
                            <script src="/libs/masonry/masonry.pkgd.min.js"></script>
                            <script src="/libs/aos/aos.js"></script>
                            <script src="/libs/scrollprogress/scrollProgress.min.js"></script>
                            <script src="/libs/lightGallery/js/lightgallery-all.min.js"></script>
                            <script src="/js/matery.js"></script>


                            <!-- Baidu Analytics -->

                                <!-- Baidu Push -->

<script>
    (function () {
        var bp = document.createElement('script');
        var curProtocol = window.location.protocol.split(':')[0];
        if (curProtocol === 'https') {
            bp.src = 'https://zz.bdstatic.com/linksubmit/push.js';
        } else {
            bp.src = 'http://push.zhanzhang.baidu.com/push.js';
        }
        var s = document.getElementsByTagName("script")[0];
        s.parentNode.insertBefore(bp, s);
    })();
</script>

                                    
                                        <script src="/libs/others/clicklove.js" async="async"></script>
                                        
                                            
                                                <script async src="/libs/others/busuanzi.pure.mini.js"></script>
                                                

                                                    

                                                            

                                                                    
                                                                        <script type="text/javascript" color="0,0,255" pointColor="0,0,255" opacity='0.7' zIndex="-1" count="99" src="/libs/background/canvas-nest.js"></script>
                                                                        

                                                                            
                                                                                
                                                                                    <script type="text/javascript" size="150" alpha='0.6' zIndex="-1" src="/libs/background/ribbon-refresh.min.js" async="async"></script>
                                                                                    

                                                                                        

                                                                                                
                                                                                                    <script src="/libs/instantpage/instantpage.js" type="module"></script>
                                                                                                    

    <script src="/live2dw/lib/L2Dwidget.min.js?094cbace49a39548bed64abff5988b05"></script><script>L2Dwidget.init({"log":false,"pluginJsPath":"lib/","pluginModelPath":"assets/","pluginRootPath":"live2dw/","tagMode":false});</script></body>

</html>
