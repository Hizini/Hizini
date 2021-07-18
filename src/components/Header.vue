<template>
     <div id ="page">
        <div class = "container">
            <header id="head" class="site-head">
                <div class="site-branding">
                    <h1 class="site-title">
                        <a href="index.html" rel="home">
                            <img class="main-logo" src="../../image/hizini.png">
                        </a>
                    </h1>
                </div>
                <div id="topArea" class="top-area">
                    <div id="login-area" class="site-login">
                        <a href="join.html">join </a>                      
                        <a href="login.html">login </a>                        
                        <a href="mypage.html">mypage</a> 
                    </div>
                    <div id="search-area" class="site-search">
                        <input type="text" placeholder="검색">
                        <button>Search</button>
                        <div id="post-area" class="site-post">
                            <a href="post.html">게시글등록</a>
                        </div>
                    </div>
                </div>   
                <nav id="site-navigation" class="main-navigation">
                    <div class="menu-area">
                        <ul class="menu-category">
                            <li class="menu-list">
                                <a href="menu1.html">게시판</a>
                            </li>
                            <li class="menu-list">
                                <a href="menu2.html">menu2</a>
                            </li>
                            <li class="menu-list">
                                <a href="menu3.html">menu3</a>
                            </li>
                            <li class="menu-list">
                                <a href="menu4.html">menu4</a>
                            </li>
                        </ul> 
                    </div>
                </nav>                    
            </header>
        </div>
    </div>    
</template>
<style scoped>
html {
	border:12px solid black;
}
.site-title {
	text-align: center;
}
.site-head {
	padding-top:2em;
	padding-bottom:1em;
	background-color: black;
}
.site-head a {
	color: #fff;
}
.main-navigation {
	background-color: black;
	font-size:14px;
	font-weight:700;
	letter-spacing:1px;
	padding:15px 0;
    padding-top: 8px;
	border-top:1px solid;
	border-bottom:1px solid;
	text-transform:uppercase;
	text-align: center;
}
.menu-area{
	clear: both;
	width: 100%;
	height: 50px;
	margin: 0px 0 0;
	background: #fff;
}
.menu-category{
	position: relative;
	width: 50%;
	height: 50px;
	text-align: center;
	margin: 0 auto;
}
.main-navigation a {
	color: black;
	text-align: center;
}
.main-navigation ul {
	list-style:none;
	margin:0 auto;
	padding:3px 0;
	text-align: center;
	line-height: 40px;
}
.main-navigation li {
	display:inline-block;
	margin:0 1em;
	position:relative;
}

.top-area{
    width: 100%;
    margin: 0px auto 0;
    padding: 0px 0;
    text-align: right;
}
.site-login{
    margin-right: 21px;
}
.site-post{
    border: 2px solid #fff;
    float: left;
    text-align: center;
    width: 100px;
    text-transform:uppercase;
    font-size: 13px;
    font-weight: bolder;
    letter-spacing:2px;
    margin-bottom: auto;
    margin-left: 5px;
    padding: 3px;
}
.site-search{
    padding: 5px;
}
.site-login a{
    text-decoration: none;
    color: #fff;
    text-transform:uppercase;
    letter-spacing:3px;
}
::placeholder{
    text-align: center;
}
button{
    border: 2px solid #fff;
    background-color: black;
    color: #fff;
    font-weight: 750;
}

</style>