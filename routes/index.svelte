<body>
    
<div id="title-id">     
  <div class="header-title">
    <h1 class="title">Discover</h1>
    <h4 class="subtitle">Welcome to Mobilekit</h4>
  </div>
</div>
<div class="imagesAll">
<div class="images-class">
    <img src="d1.jpg" class="image" alt="mobilekit1">
    <div class="text-class">
        <h4 class="images-text">Progressive web app ready</h4>
    </div>    
</div>
<div class="images-class">
    <img src="d2.jpg"  class="image" alt="mobilekit2">
    <div class="text-class">
        <h4 class="images-text">Reusable Components</h4>
    </div>
</div>
<div class="images-class">
    <img src="d3.jpg" alt="mobilekit3" class="image">
    <div class="text-class">
        <h4 class="images-text">Great for Phones and Tablets</h4>
    </div>
</div>
<div class="images-class">
    <img src="d5.jpg" alt="mobilekit4" class="image">
    <div class="text-class">
        <h4 class="images-text">Change the styles in SASS</h4>
    </div>
</div>
<div class="images-class">
    <img src="d6.jpg" alt="mobilekit5" class="image">
    <div class="text-class">
        <h4 class="images-text">Sketch Source file Included</h4>
    </div>
</div>
<div class="images-class">
    <img src="d7.jpg" alt="mobilekit6" class="image">
    <div class="text-class">
        <h4 class="images-text">RTL (Right to Left) Support</h4>
    </div>
</div>

</div>
<div>
    <div class="color-theme-section">
        <div class="color-theme">
            <div class="color-theme-body">
                <div>
                    <h6 class="discover">DISCOVER</h6>
                    <h5 class="dark-class">Dark Mode</h5>
                </div> 
                <div>
                    <input type="checkbox" class="checkbox" id="chk" />
                    <label class="label" for="chk">
                        <i class="fas fa-moon"></i>
                        <i class="fas fa-sun"></i>
                        <div class="ball"></div>
                    </label>
                </div>  
            </div>
        </div>
    </div>
</div>
<div class="color-theme-section">
    <div class="color-theme">
        <div>
        <img src="wide4.jpg" alt="wideImage" class="widey">
        </div>
        <div class="color-theme-body">
            <div>
                <h6 class="discover">DISCOVER</h6>
                <h5 class="dark-class">Components</h5>
                <p class="wide-text">Reusable components designed for the mobile interface and ready to use.</p>
                <a href="app-components.html" class="btn btn-primary">
                    <ion-icon name="cube-outline" role="img" class="md hydrated" aria-label="cube outline"></ion-icon>
                     Cube Preview
                </a>
        </div>
    </div>
</div>
<div class="color-theme-section">
    <div class="color-theme">
        <img src="wide2.jpg" alt="wideImage" class="widey">
        <div class="color-theme-body">
            <div>
                <h6 class="discover">DISCOVER</h6>
                <h5 class="dark-class">Pages</h5>
                <p class="wide-text">Mobilekit comes with basic pages you may need and use in your projects easily.</p>
                <a href="app-pages.html" class="btn btn-primary">
                    <ion-icon name="cube-outline" role="img" class="md hydrated" aria-label="cube outline"></ion-icon>
                     Cube Preview
                </a>
            </div>
        </div>
    </div>
</div>
<!--App Footer-->
<div class="app-footer">
    <img src="logo.png" alt="footerimage" class="logo-class">
    <div class="footer-title">
        Copyright © Mobilekit 2022. All Rights Reserved.
    </div>
    <div>Mobilekit is PWA ready Mobile UI Kit Template.</div>
    "Great way to start your mobile websites and pwa projects."
    <div class="social-links">
        <div class="socials">
            <i class="fa-brands fa-facebook-square"></i>
            <i class="fa-brands fa-twitter-square"></i>
            <i class="fa-brands fa-linkedin"></i>
            <i class="fa-brands fa-instagram-square"></i>
            <i class="fa-brands fa-whatsapp-square"></i>
            <i class="fa-solid fa-arrow-up"></i>
        </div>
    </div>
</div>
<hr>
<!--Bottom Menu-->
<div class="bottom-menu">
    <i class="fa-solid fa-house-chimney"></i>
    <i class="fa-solid fa-cube"></i>
    <i class="fa-brands fa-rocketchat"></i>
    <i class="fa-solid fa-layer-group"></i>
    <i class="fa-solid fa-bars"></i>

</div>
</body>

<style>
    body {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
        color: #4F5050;
        background-color: #f9f9f9;
        font-family: "Inter",sans-serif;

    }
    #title-id {
        margin-bottom: env(safe-area-inset-bottom);
        margin-top: env(safe-area-inset-top);

    }
    .header-title {
        padding: 0 16px;
    }
    .title {
        margin: 4px 0 0 0;
        font-size: 34px;
        letter-spacing: -0.02em;
        line-height: 1.3em;
        font-weight: 700;
    }
    .subtitle {
        font-size: 17px;
        font-weight: 400;
        margin: 6px 0 0 0;
        color: #141515;
        line-height: 1.6em;

    }
    .imagesAll {
        display: flex;
        margin-left: 8px;
        margin-top: 28px;
        padding-left: 8px;
        overflow-x: scroll;

    }
    .imagesAll::-webkit-scrollbar {
        display: none;
    }
    .image{
        border-radius: 6px 6px 0 0;
        width: 313px;
        height: 238px;
    }
    .images-class {
        background: #ffffff;
        border-radius: 6px;
        border: 0;
        box-shadow: 0 3px 8px 0 rgb(0 0 0 / 10%), 0 1px 3px 0 rgb(0 0 0 / 8%);
        position: relative;
        margin-right: 16px;
        cursor: pointer;
        pointer-events: auto;
        gap: 5px;
        grid-template-columns: repeat(7, 1fr);
    }
    .images-class :hover {
        color: #1E74FD;
    }
    .images-class .text-class {
        padding-bottom: 5px;
        line-height: 1.4em;
    }
    .images-text {
        margin-top: 0px;
        color: #4F5050;
        letter-spacing: -0.02em;
        line-height: 1.3em;
        font-size: 15px;
        padding-left: 15px;
    }
    
    .color-theme-section {
        margin-bottom: 24px!important;
        margin-top: 24px!important;
        padding: 0 16px;  
    }
    .color-theme {
        background: #ffffff;
        border-radius: 6px;
        border: 0;
        line-height: 0!important;
        box-shadow: 0 3px 6px 0 rgb(0 0 0 / 10%), 0 1px 3px 0 rgb(0 0 0 / 8%);
    }
    .color-theme-body {
        justify-content: space-between;
        padding: 10px 16px;
        align-items: flex-end!important;
        display: flex;
        overflow: hidden;
    }
    .dark-class {
        font-weight: 700;
        color: #141515;
        font-size: 20px;
        display: flex;
    }
    .discover {
        color: black!important;
    }
    .color-theme .discover {
    color: #4F5050;
    font-weight: 500;
    letter-spacing: .01em;
    font-size: 11px;
    text-transform: uppercase;
    margin-bottom: 8px;
    margin-top: 10px;

    }
    @import url('https://fonts.googleapis.com/css?family=Muli&display=swap');
    .checkbox {
	opacity: 0;
	position: absolute;

    }
    .label {
    background-color: #1E74FD;
	border-radius: 50px;
	cursor: pointer;
	display: flex;
	align-items: center;
	justify-content: space-between;
	padding: 5px;
	position: relative;
	height: 30px;
	width: 56px;
	transform: scale(1.0);
    }
    .label .ball {
	background-color: #ffffff;
	border-radius: 50%;
	position: absolute;
	top: 2px;
	left: 2px;
	height: 35px;
	width: 35px;
	transform: translateX(0px);
	transition: transform 0.2s linear;
}
.checkbox:checked + .label .ball {
	transform: translateX(24px);
}
.fa-moon {
	color: #1E74FD;
}
    .fa-sun {
	color: #1E74FD;
}
.color-theme .widey {
    border-radius: 6px 6px 0 0;
}
.widey {
    width: 100%;
    height: 667px;
}
.wide-text {
    color: #4F5050;
    letter-spacing: .01em;
}
.btn-primary {
    background: #1E74FD !important;
    border-color: #1E74FD !important;
    color: #ffffff !important;
}
.btn {
    margin-top: 9px;
    margin-bottom: 17px;
    height: 40px;
    padding: 3px 14px;
    font-size: 17px;
    line-height: 1.2em;
    font-weight: 500;
    box-shadow: none !important;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    transition: none;
    text-decoration: none !important;
    border-radius: 6px;
    border-width: 2px;
}
.btn ion-icon {
    font-size: 32px;
    margin-right: 10px;
    margin-top: -2px;
    font-weight: 700;
}
.app-footer {
    border-top: 1px solid #E1E1E1;
    padding: 24px 16px;
    font-size: 12px;
    text-align: center;
    line-height: 1.2em;
    background: #fff;
}
.logo-class {
    margin-bottom: 16px;
    height: 16px;
}
.app-footer .footer-title {
    font-weight: 500;
    color: #141515;
    margin-bottom: 8px;
    font-size: 14px;
}
.social-links {
    margin: 16px 0 20px 0 !important;
    text-align: center;
}
.socials {
    font-size: xx-large;
    margin: 0 5px 0 5px;
}
.socials:hover {
    color: #4F5050;
}
.fa-facebook-square {
    color: blue;
    font-size: xx-large;
    margin: 0 5px 0 5px;
}
.fa-twitter-square {
    color: #049ff6;
    font-size: xx-large;
    margin: 0 5px 0 5px;
}
.fa-linkedin {
    color: #0075aa;
    font-size: xx-large;
    margin: 0 5px 0 5px;
}
.fa-instagram-square {
    color: #df237b;
    font-size: xx-large;
    margin: 0 5px 0 5px;
}
.fa-whatsapp-square {
    color: #0ad561;
    font-size: xx-large;
    margin: 0 5px 0 5px;
}
.fa-arrow-up {
    color: whitesmoke;
    background-color:  #5c636a;
    border-radius: 20px;
    border-top: 1px solid #E1E1E1;
    width: 28px;
}
.bottom-menu {
    min-height: 56px;
    position: fixed;
    z-index: 999;
    bottom: 0;
    left: 0;
    right: 0;
    background: #FFFFFF;
    align-items: center;
    justify-content: center;
    border-top: 1px solid #E1E1E1;
    padding-left: 4px;
    padding-right: 4px;
    padding-top: 13px;
    padding-bottom: env(safe-area-inset-bottom);
}
.fa-house-chimney {
    color: #1E74FD;
    font-size: xx-large;
    justify-content: space-between;
    margin-left: 130px;
}
.fa-cube {
    font-size: xx-large;
    color: #4F5050;;
    margin-left: 230px;
}
.fa-rocketchat {
    font-size: xx-large;
    color: #4F5050;;
    margin-left: 230px;
}
.fa-layer-group {
    font-size: xx-large;
    color: #4F5050;;
    margin-left: 230px;
}
.fa-bars {
    font-size: xx-large;
    color: #4F5050;;
    margin-left: 230px;
}
</style>
<svelte:head>
    <script src="https://kit.fontawesome.com/9af48a40fc.js" crossorigin="anonymous"></script>
</svelte:head>

<!-- <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"
    nomodule #src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js">
</script> -->
