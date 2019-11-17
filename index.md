---
#
# Here you can change the text shown in the Home page before the Latest Posts section.
#
# Edit cayman-blog's home layout in _layouts instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

<style type="text/css">
    .desktop {
        display: block;
        padding: 0;
    }

    .mobile {
        display: none;
        padding: 0;
    }

    .row {
        display: -ms-flexbox;
        display: flex;
        -ms-flex-wrap: wrap;
        flex-wrap: wrap;
    }

    .col-img, .col-content {
        position: relative;
        width: 100%;
        min-height: 1px;
        padding-right: 15px;
        padding-left: 15px;
        box-sizing: border-box;
    }

    .col-img {
        -ms-flex: 0 0 66.666667%;
        flex: 0 0 66.666667%;
        max-width: 66.666667%;
    }

    .col-content {
        -ms-flex: 0 0 33.333333%;
        flex: 0 0 33.333333%;
        max-width: 33.333333%;
    }

    .page-header {
        color: #fff;
        text-align: center;
        background-color: #159957;
        background-image: linear-gradient(120deg, #155799, #159957); 
    }
    
    @media screen and (min-width: 64em) {
        
    }

    @media screen and (min-width: 42em) and (max-width: 64em) {
        
    }

    @media screen and (max-width: 42em) {
        .row {
            display: block;
            text-align: center;
        }

        .col-img {
            -ms-flex: none;
            flex: none;
            max-width: 60%;
            margin: 0 auto;
        }

        .col-content {
            -ms-flex: none;
            flex: none;
            max-width: 100%;
        }

        .desktop {
            display: none;
        }

        .mobile {
            display: block;
        }
    }

</style>

<script type="text/javascript">
    // function windowResize() {
    //     console.log(document.body.clientWidth);
    //     document.getElementById('id').style.top = 
    // }
    // window.addEventListener('load', windowResize, false);
    // window.addEventListener('resize', windowResize, false);
</script>

<dir class="desktop">
    <div class="row">
        <div class="col-content">
            <h2>简单易用</h2>
            <p>轻量使用, 随时随地记录生活中的灵感</p>
            <p>Markdown支持, 简洁的标记语法, 清爽的视觉体验 </p>
        </div>
        <div class="col-img"><img src="https://gitee.com/uploads/images/2018/0102/000654_034595ab_91466.jpeg"/></div>
    </div>
    <br /><br />
    <div class="row">
        <div class="col-img"><img src="https://gitee.com/uploads/images/2018/0101/233633_1c208a45_91466.png"/></div>
        <div class="col-content">
            <h2>Git强力支持</h2>
            <p>天生的私有云, 任何只要能公网访问的Git仓库皆能成为她的存储仓库</p>
            <p>库在人在, 库亡人亡, 只要Git仓库在任何笔记都不可能丢失</p>
        </div>
    </div>
    <br /><br />
    <div class="row">
        <div class="col-content">
            <h2>支持所有设备</h2>
            <p>你可以保存任何你想保存的东西, 她会为你自动同步</p>
            <p>无需再用麻烦的方法来回传文件了, 一切都是这么方便</p>
        </div>
        <div class="col-img"><img src="https://gitee.com/uploads/images/2018/0102/001234_ea0e14c7_91466.png"/></div>
    </div>
</dir>
<dir class="mobile">
    <div class="row">
        <div class="col-img"><img src="https://gitee.com/uploads/images/2018/0102/000654_034595ab_91466.jpeg"/></div>
        <div class="col-content">
            <h2>简单易用</h2>
            <p>轻量使用, 随时随地记录生活中的灵感</p>
            <p>Markdown支持, 简洁的标记语法, 清爽的视觉体验 </p>
        </div>
    </div>
    <br />
    <div class="row">
        <div class="col-img"><img src="https://gitee.com/uploads/images/2018/0101/233633_1c208a45_91466.png"/></div>
        <div class="col-content">
            <h2>Git强力支持</h2>
            <p>天生的私有云, 任何只要能公网访问的Git仓库皆能成为她的存储仓库</p>
            <p>库在人在, 库亡人亡, 只要Git仓库在任何笔记都不可能丢失</p>
        </div>
    </div>
    <br />
    <div class="row">
        <div class="col-img"><img src="https://gitee.com/uploads/images/2018/0102/001234_ea0e14c7_91466.png"/></div>
        <div class="col-content">
            <h2>支持所有设备</h2>
            <p>你可以保存任何你想保存的东西, 她会为你自动同步</p>
            <p>无需再用麻烦的方法来回传文件了, 一切都是这么方便</p>
        </div>
    </div>
</dir>