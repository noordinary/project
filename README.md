# project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <title>Document</title>
</head>
<style type="text/css" media="screen">
    @font-face{
        font-family:"opensans";
        src:url('opensans.ttf');
    }
    body{
        font-family:"opensans";
        margin:0px;
    }
    div{
        margin:0px auto;
        font-family:"微软雅黑";
    }
    header{
        width:1300px;
        height:85px;
        border:1px solid white;
        background:url('img/icrowdme-PSD---cssauthor_03.png')134px 21px no-repeat;
    }
    .home{
        margin-left:426px;
    }
    header span{
        line-height:85px;
        margin-right:29px;
        font-size:13px;
        color:#a2a2a2;
    }
    .LOGIN{
        width:100px;
        height:37px;
        background-color: #bcda5c;
        border-radius:50px;
        float:right;
        text-align:center;
        line-height:37px;
        margin-right:140px;
        margin-top:26px;
    }
    .LOGIN a{
        /* font-family:"微软雅黑"; */
        display:block;
        text-decoration:none;
        color:#f3f8e6;
    }
    .property{
        width:1300px;
        height:570px;
        border:1px solid white;
        background:url('img/Overlay.png') no-repeat;
        /* background-size:cover; */
        text-align:center;
    }
    .property:after{
        content:'';
        display:block;
        width:13px;
        height:20px;
        background:url('img/Shape-663-copy-3.png') no-repeat;
        float:right;
        margin-right:-58px;
        margin-top:73px;
    }
    .property:before{
        content:'';
        display:block;
        width:13px;
        height:20px;
        background:url('img/Shape-663-copy-4.png') no-repeat;
        float:right;
        margin-right:185px;
        margin-top:505px;
    }
    .Int{
        margin-top:170px;
        margin-left:205px;
        font-size:49px;
        color:#ffffff;
    }
    .of{
        font-size:35px;
        color:#ffffff;
    }
    .become{
        width:255px;
        height:73px;
        margin-top:59px;
        background-color:#99c50a;
        border-radius:10px;
    }
    .become a{
        text-decoration:none;
        color:white;
        line-height:73px;
        display:block;
        font-size:19px;
    }
    .our{
        /* width:980px; */
        width:1300px;
        height:742px;
        border:1px solid white;
        background:url('img/icrowdme-PSD---cssauthor_09.png')656px 99px no-repeat;
        text-align:center;
    }
    .work{
        /* font-family:"微软雅黑"; */
        margin-top:208px;
        font-size:31px;
        color:#515151;
    }
    .lorem{
        font-size:19px;
        color:#919191;
        /* font-family:"微软雅黑"; */
        margin-top:70px;
    }
    .ull{
        font-size:19px;
        color:#919191;
        /* font-family:"微软雅黑"; */
        margin-top:52px;
    }
    .simple{
        width:980px;
        height:81px;
        border-bottom:1px solid #e6e6e6;

        margin-top:145px;
    }
    li{
        list-style:none;
        float:left;
        line-height:81px;
        display:block;
        width:250px;
        height:81px;
        /* margin-top:-16px; */
        margin-left:-40px;
        font-size:33px;
    }
    li:after{
        line-height:43px;
        color:white;
        background-color:#5f5f5f;
        content:'1';
        display:block;
        width:43px;
        height:43px;
        /* border:1px solid #000; */
        border-radius:50%;
        margin-top:-65px;
    }
    .STC2{
        width:300px;
        margin-left:50px;
    }
    .STC3{
        width:310px;
        margin-left:50px;
    }
    .tran{
        margin-left:50px;
    }
    .coll{
        margin-left:50px;
    }
    .STC2:after{
        content:'2';
    }
    .STC3:after{
        content:'3';
    }
    li:hover{
        border-bottom:1px solid #add136;
    }
    li:hover:after{
        background-color:#add136;
    }
    .STC li a{
        color:#656565;
    }

    .brwse{
        width:1300px;
        height:309px;
        border:1px solid white;
        background:url('img/icrowdme-PSD---cssauthor_13.png')249px 87px no-repeat;
    }
    .browse{
        color:#add136;
        font-size:25px;
        margin-left:478px;
        margin-top:65px;
    }
    .ipsum{
        line-height:25px;
        font-size:17px;
        margin-left:468px;
        margin-top:40px;
        color:#9f9f9f;
    }
    .find{
        width:1300px;
        height:305px;
        border:1px solid white;
    }
    .member{
        width:648px;
        height:305px;
        background:#e2f8ff url('img/icrowdme-PSD---cssauthor_17.png')141px 84px no-repeat;
        float:left;
    }
    .submit:after,
    .member:after{
        /* font-family:"微软雅黑"; */
        font-size:15px;
        text-align:center;
        line-height:51px;
        color:white;
        background-color:#26a6d1;
        content:'Become A Member';
        display:block;
        width:187px;
        height:51px;
        border-radius:10px;
        margin-top:30px;
        margin-left:322px;
        cursor:pointer;
    }
    .submit{
        width:652px;
        height:305px;
        background:#f5f9eb url('img/icrowdme-PSD---cssauthor_20.png')141px 84px no-repeat;
        float:right;
    }
    .submit:after{
        content:'Submit Your Project';
        background-color:#add136;
    }
    .pro{
        font-size:23px;
        color:#515151;
        margin-top:47px;
        margin-left:332px;
    }
    .sign{
        text-height:15px;
        font-size:17px;
        color:#515151;
        margin-top:40px;
        margin-left:319px;
    }
    .featured{
        width:1300px;
        height:1423px;
        border:1px solid white;
    }
    .popular{
        width:980px;
        height:100px;
        /* border:1px solid #000; */
        margin-top:81px;
    }
    .popular:before{
        /* font-family:"微软雅黑"; */
        font-size:15px;
        text-align:center;
        line-height:51px;
        border:1px solid #000;
        content:'Become A Member';
        display:block;
        width:187px;
        height:51px;
        border-radius:10px;
        margin-top:26px;
        float:right;
        cursor:pointer;
    }
    .Featured_Projects{
        font-size:29px;
        color:#515151;
        margin-top:-7px;
        margin-left:10px;
    }
    .view{
        font-size:17px;
        color:#8f8f8f;
        margin-top:-10px;
    }
    .new{
        width:980px;
        height:520px;
        margin-top:56px;
        border:1px solid white;
    }
    .new1{
        width:300px;
        height:520px;
        border:1px solid white;
        margin-right:37px;
        background:#f9f9f9 url('img/Layer-16.png')no-repeat;
        float:left;
    }
    .new1:before{
        /* font-family:"微软雅黑"; */
        font-size:17px;
        text-align:center;
        line-height:35px;
        color:white;
        /* border:1px solid #000; */
        background-color:#26a6d1;
        content:'From GBP  3600';
        display:block;
        width:139px;
        height:35px;
        border-radius:10px;
        margin-top:173px;
        float:right;
        cursor:pointer;
    }
    .ontario{
        /* font-family:"微软雅黑"; */
        font-size:17px;
        color:#484848;
        margin-top:176px;
        margin-left:35px;
    }
    .sit{
        /* font-family:"微软雅黑"; */
        font-size:13px;
        color:#9b9b9b;
        margin-left:25px;
        line-height:20px;
    }
    .radius{
        width:253px;
        height:14px;
        background:#e3e3e3;
        border-radius:50px;
        margin-top:20px;
    }
    .radius:after{
        content:'';
        display:block;
        width:38px;
        height:14px;
        background:#add136;
        border-radius:50px;
    }
    .raius2:after{
        width:170px;
    }
    .funded{
        font-size:13px;
        color:#8d8d8d;
        margin-left:24px;
        margin-top:20px;
    }
    .see{
        width:252px;
        height:66px;
        border-top:1px solid #d6d6d6;
        line-height:66px;
    }
    .details{
        margin-left:80px;
        color:#e1e1e1;
    }
    .triangle{
        width:0px;
        height:0px;
        border:10px solid transparent;
        border-left-color:#bfdb63;
        float:right;
        margin-top:23px;
    }
    .new2{
        background:#f9f9f9 url('img/Layer-20.png')no-repeat;
    }
    .new3{
        background:#f9f9f9 url('img/Layer-161.png')no-repeat;
        margin-right:0;
    }
    .be{
        width:1300px;
        height:670px;
        border:1px solid white;
        background:url('img/bg.png') no-repeat;
        text-align:center;
    }
    .be:after{
        color:#494949;
        line-height:60px;
        text-indent:75px;
        content:'David Beckham';
        display:block;
        width:197px;
        height:60px;
        /* border:1px solid #000; */
        margin-top:321px;
        margin-left:225px;
        background:url('img/Layer-23.png')no-repeat;
    }
    .Exellent:after{
        color:#494949;
        line-height:60px;
        text-indent:75px;
        content:'David Beckham';
        display:block;
        width:197px;
        height:60px;
        /* border:1px solid #000; */
        margin-top:14px;
        margin-right:154px;
        background:url('img/Layer-24.png')no-repeat;
        float:right;
    }
    .part{
        font-size:39px;
        color:#9ec02d;
        margin-top:80px;
    }
    .one{
        font-size:19px;
        color:#949494;
        margin-top:42px;
        line-height:30px;
    }
    .best{
        width:400px;
        height:147px;
        background-color:white;
        border-radius:10px;
        float:left;
        margin-left:172px;
        margin-top:120px;
    }
    .Exellent{
        margin-left:155px;
    }
    .trigon{
        width:0px;
        height:0px;
        border:20px solid transparent;
        border-left-color:white;
        margin-top:-5px;
        margin-left:85px;
    }
    .one1{
        font-size:21px;
        color:#a5c545;
    }
    .one2{
        font-size:13px;
        color:#848484;
    }
    .zanzhu{
        width:1300px;
        height:131px;
        border-bottom:1px solid #ededed;
        background:url('img/icrowdme-03 .png')145px 59px no-repeat;
    }
    .bottom{
        width:1300px;
        height:64px;
        border:1px solid white;
        text-align:center;
    }
    .banquan{
        line-height:64px;
        font-size:13px;
        color:#848484;
    }
</style>
<body>
    <header>
        <span class="home">HOME</span>
        <span>HOW IT WORKS</span>
        <span>DISCOVER A PROJECT</span>
        <span>BLOG</span>
        <span>FIND OUT MORE</span>
        <div class="LOGIN">
            <a href="#">LOGIN</a>
        </div>
    </header>
    <div class="property">
        <p class="Int">Intellectual Property has the Shelf Life<br>
        <span class="of">of a Banana.</span></p>
        <div class="become">
            <a href="#">Become a Member</a>
        </div>
    </div>
    <div class="our" mar-；>
        <p class="work">Our work is the presentation<br>
            of our capabilities.</p>

            <p class="lorem">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore<br> magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation</p>

            <p class="ull">Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in<br>
            voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        <div class="simple">
            <ul class="STC">
                <li class="STC1"><a href="#">Simple</a></li>
                <li class="STC2"><a href="#" class="tran">Transparent</a></li>
                <li class="STC3"><a href="#" class="coll">Collaborative</a></li>
            </ul>
        </div>
    </div>
    <div class="brwse">
        <p class="browse">Browse projects, like booking a hotel online !</p>
        <p class="ipsum">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor<br> incididunt ut labore et do lore magna aliqua. Ut enim ad minim veniam, quis nostrud<br> exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>
    <div class="find">
        <div class="member">
            <p class="pro">Find Properties</p>
            <p class="sign">Sign up to browse the portfolio.<br>
                Your journey to becoming a real<br>
                 estate baron starts here.
            </p>
        </div>
        <div class="submit">
            <p class="pro">Find Buyers</p>
            <p class="sign">Sign up to browse the portfolio.<br>
                Your journey to becoming a real<br>
                 estate baron starts here.
            </p>
        </div>
    </div>
    <div class="featured">
        <div class="popular">
            <p class="Featured_Projects">Featured Projects</p>
            <p class="view">Brief details of new and popular projects. To view full listings, you willberequired to<br>sign up and become a member.
            </p>
        </div>
        <div class="new">
            <div class="new1">
                <img src="img/NEW.png" alt="">
                <p class="ontario">Ontario Tower , LONDON</p>
                <p class="sit">Lorem ipsum dolor sit amet, consectetur<br>
                 adipisicing elit, sed do eiusmod tempor<br>
                incididunt ut labore et dolore magna<br>
                aliqua.
                </p>
                <div class="radius">

                </div>
                <p class="funded">10% Funded&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8 Days Left</p>
                <div class="see">
                    <span class="details">See Project Details</span>
                    <div class="triangle">

                    </div>
                </div>
            </div>
            <div class="new1 new2">
                <img src="img/NEW.png" alt="">
                <p class="ontario">Ontario Tower , LONDON</p>
                <p class="sit">Lorem ipsum dolor sit amet, consectetur<br>
                 adipisicing elit, sed do eiusmod tempor<br>
                incididunt ut labore et dolore magna<br>
                aliqua.
                </p>
                <div class="radius raius2">

                </div>
                <p class="funded">60% Funded&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8 Days Left</p>
                <div class="see">
                    <span class="details">See Project Details</span>
                    <div class="triangle">

                    </div>
                </div>
            </div>
            <div class="new1 new3">
                <img src="img/NEW.png" alt="">
                <p class="ontario">Ontario Tower , LONDON</p>
                <p class="sit">Lorem ipsum dolor sit amet, consectetur<br>
                 adipisicing elit, sed do eiusmod tempor<br>
                incididunt ut labore et dolore magna<br>
                aliqua.
                </p>
                <div class="radius">

                </div>
                <p class="funded">10% Funded&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8 Days Left</p>
                <div class="see">
                    <span class="details">See Project Details</span>
                    <div class="triangle">

                    </div>
                </div>
            </div>
        </div>
        <div class="be">
            <p class="part">Be Part of a Growing International Community</p>
            <p class="one">One of the challenges in networking is everybody thinks it's making cold calls to strangers. Actually, it's<br> the people who already have strong trust relationships with you</p>
            <div class="best">
                    <p class="one1">One of the Best </p>
                    <p class="one2">Lorem ipsum dolor sit amet, consectetur adipisicing<br> elit, sed do eiusmod taempor incididunt ut labore et<br> dolore magna aliqua.</p>
                <div class="trigon">

                </div>
            </div>
            <div class="best Exellent">
                <p class="one1">Exellent Service </p>
                    <p class="one2">Lorem ipsum dolor sit amet, consectetur adipisicing<br> elit, sed do eiusmod taempor incididunt ut labore et<br> dolore magna aliqua.</p>
                <div class="trigon">

                </div>
            </div>
        </div>
    </div>
    <div class="zanzhu">

    </div>
    <div class="bottom">
        <span class="banquan">Copyright © 2001 - 2014  Cssauthor.com</span>
    </div>
</body>
</html>
