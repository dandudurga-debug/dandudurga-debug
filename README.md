- 👋 Hi, I’m @dandudurga-debug
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
dandudurga-debug/dandudurga-debug is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="index.css">
    <title>Portfolio Round Icon</title>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@200;300;400;500;600;700;800&family=Roboto:wght@100;300;400&display=swap');

:root {
    --primary-color: #f9532d;
    --primary-dark: #1F252E;
}

* {
    margin: 0;
    padding: 0;
    scroll-behavior: smooth;
}

body {
    font-family: 'Outfit', sans-serif;
    background-color: #1F252E;
    height: 100vh;
    color: #ffffff;
}
/* Genral */
.container {
    padding: 0 8.4rem;
}

.img-w {
    width: 100%;
    height: auto;
}
/* Nav */
header {
    background: var(--primary-dark);
    position: relative;
    box-shadow: 0 4px 17px rgb(255 255 255 / 10%);
    position: sticky;
    top: 0;
    z-index: 1;
}

.page-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 0;
}

.logo {
    font-size: 1.5rem;
    font-weight: 800;
    opacity: 0;
    animation: leftSideAni 1s ease forwards;
}

.logo a {
    color: #fff;
    text-decoration: none;
}

ul {
    display: flex;
    gap: .6rem;
    list-style-type: none;
    background-color: transparent;
    overflow: hidden;
}

li a {
    display: inline-block;
    padding: .3rem 1rem;
    color: #fff;
    text-decoration: none;
    font-size: 1.05rem;
    font-weight: 600;
    letter-spacing: .7px;
    border-radius: 36px;
    line-height: 2;
    transition: .3s;
    opacity: 0;
    animation: navani .3s ease forwards;
    animation-delay: calc(.15s * var(--navAni));
}

li a.active,
li a:hover {
    color: var(--primary-color);
}

#click {
    display: none;
}

.menu {
    display: none;
}

.mode i {
    font-size: 1.4rem;
    cursor: pointer;
    color: var(--primary-color);
    opacity: 0;
    animation: rightSideAni 1.5s ease forwards;
}

/* Nav End */

/* Section 1 */

.main {
    padding: 6rem 0;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(277px, 1fr));
    row-gap: 2rem;
    column-gap: 6rem;
    align-items: center;
}
.main h3 {
    color: #fff;
    font-size: 1.5rem;
    opacity: 0;
    animation: topSideAni 1s ease forwards;
}
.main h1 {
    color: #fff;
    font-size: 4rem;
    font-weight: 600;
    opacity: 0;
    animation: leftSideAni 1s ease forwards;
    animation-delay: 1s;
}
.main button {
    background-color: transparent;
    color: var(--primary-color);
    border: 2px solid var(--primary-color);
    padding: 0.8rem 1rem;
    font-size: 1.1rem;
    border-radius: 7px;
    margin-top: 2rem;
    cursor: pointer;
}
.images {
    margin-left: auto;
    width: 300px;
}
.images img {
    border-radius: 50%;
    box-shadow: 0 0 10px #D1D9E6;
}

/* Section 1 End */

/* Roundin sec */
  .main {
    position: relative;
  }
  .big-circle {
    height: 100%;
    width: 100%;
    position: relative;
    border: 3px solid #bbbbbb;
    border-radius: 50%;
    display: flex;
    display: -webkit-flex;
    align-items: center;
    -webkit-align-items: center;
    justify-content: center;
    -webkit-justify-content: center;
    animation: Rotate 20s linear infinite;
    -webkit-animation: Rotate 20s linear infinite;
  }
  .icon-block {
    width: 64px;
    height: 64px;
    position: absolute;
    border-radius: 50%;
    display: flex;
    display: -webkit-flex;
    align-items: center;
    -webkit-align-items: center;
    justify-content: center;
    -webkit-justify-content: center;
    background-color: #fff;
    box-shadow: 0 0 10px #fff;
  }
  .icon-block img {
    margin: 0px auto;
    width: 60%;
    animation: Rotate-reverse 20s linear infinite;
    -webkit-animation: Rotate-reverse 20s linear infinite;
  }
  .icon-block:first-child {
    top: 0;
    left: 50%;
    transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%, -50%);
  }
  .icon-block:nth-child(2) {
    top: 50%;
    right: 0;
    transform: translate(50%, -50%);
    -webkit-transform: translate(50%, -50%);
  }
  .icon-block:nth-child(3) {
    bottom: 0;
    left: 50%;
    transform: translate(-50%, 50%);
    -webkit-transform: translate(-50%, 50%);
  }
  .icon-block:nth-child(4) {
    top: 50%;
    left: 0;
    transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%, -50%);
  }
  .rounding-sec {
    position: relative;
    height: 400px;
    width: 400px;
  }
  .images {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%, -50%);
  }
  /* keyframe animation */

  @keyframes Rotate {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(360deg);
    }
  }

  @-webkit-keyframes Rotate {
    from {
      -webkit-transform: rotate(0deg);
    }
    to {
      -webkit-transform: rotate(360deg);
    }
  }

  @keyframes Rotate-reverse {
    from {
      transform: rotate(360deg);
    }
    to {
      transform: rotate(0deg);
    }
  }

  @-webkit-keyframes Rotate-reverse {
    from {
      -webkit-transform: rotate(360deg);
    }
    to {
      -webkit-transform: rotate(0deg);
    }
  }

/* Animation */
@keyframes leftSideAni {
    0% {
        transform: translateX(-100px);
        opacity: 0;
    }
    100% {
        transform: translateX(0);
        opacity: 1;
    }
}
@keyframes navani {
    0% {
        transform: translateY(100px);
        opacity: 0;
    }
    100% {
        transform: translateY(0);
        opacity: 1;
    }
}
@keyframes topSideAni {
    0% {
        transform: translateY(-100px);
        opacity: 0;
    }
    100% {
        transform: translateY(0);
        opacity: 1;
    }
}

@media screen and (max-width: 1024px) {
    .container {
        padding: 0 4.4rem;
    }
    .main h3 {
        color: #000;
        margin-top: 1rem;
    }
}
@media screen and (max-width: 990px) {
    .main {
        grid-template-columns: repeat(auto-fit, minmax(420px, 1fr));
    }
    .rounding-sec {
        margin: auto;
    }
}

@media screen and (max-width: 768px) {
    .container {
        padding: 0 1.6rem;
    }
}

@media screen and (max-width:600px) {
    body {
        height: auto;
    }
    header {
        height: auto;
        background-color: var(--primary-dark);
    }

    ul {
        background: var(--primary-dark);
        width: 100%;
        height: 100vh;
        position: absolute;
        display: flex;
        flex-direction: column;
        text-align: center;
        top: 3.4rem;
        left: -100%;
        z-index: 111111;
    }

    .menu {
        display: block;
        font-size: 1.5rem;
        font-weight: bold;
        color: var(--primary-color);
    }

    #click:checked~ul {
        left: 0%;
        transition: all 0.3s ease;
    }
    .main {
        grid-template-columns: repeat(auto-fit, minmax(266px, 1fr));
        margin-top: 2rem;
        overflow-x: hidden;
    }
    .icon-block {
        width: 50px;
        height: 50px;
    }
    .rounding-sec {
        height: 300px;
        width: 300px;
    }
    .images {
        width: 200px;
    }
}
    </style>
</head>

<body>
    <header class="container">
        <div class="page-header">
            <div class="logo">
                <a href="#">Logo.</a>
            </div>
            <input type="checkbox" id="click">

            <label for="click" class="mainicon">
                <div class="menu">
                    <i class='bx bx-menu'></i>
                </div>
            </label>
            <ul>
                <li><a href="#" class="active" style="--navAni:1">Home</a></li>
                <li><a href="#" style="--navAni:2">About</a></li>
                <li><a href="#" style="--navAni:3">Skills</a></li>
                <li><a href="#" style="--navAni:4">Portfolio</a></li>
                <li><a href="#" style="--navAni:5">Contact</a></li>
            </ul>
        </div>
    </header>


    <section class="container">
        <div class="main">
            <div class="rounding-sec">
                <div class="big-circle">
                    <div class="icon-block">
                        <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjIHDQ_CU0W38ktREqnPwdVlGCdA_e4xbaDK9NrjFOpD2AqdcajDV3c9_R3vp034nrC9eyvMThwY8ifNpmH3_8GMg_SzAsLKcWQeSskaVl8HjVtLWilhcBNwfep0yRxq-Z_klBXoYTVX0BaE39VwJ2a-drZup5i8owkdaZF0-KhCaodrtN2Rii9HPZrdlk/s1600/github.png"
                            alt="" />
                    </div>
                    <div class="icon-block">
                       <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhoPvxJtYJq2-7BDn6LGcQ6QsT3Bo0vxkKu8WAOZnqsHIiTtGJqsHHHWlqqYN4iQFlVaqTaq7AFkWbY5Wrqxvk9Se1Wc_rjA7UKZoXHoxqSWXyaTg9aL9RC37H78NTnT4TwePdwqEYwVw8VxtjPoy6eG-f7RTJhX0JCa0lPmpfaz69hJ1ZHI9seBrUuvf4/s64/instagram.png"
                            alt="" />
                    </div>
                    <div class="icon-block">
                        <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg-WWnXxgKNxwqarx8Vr_xpaCcwOQbv7bpFxWXy1o7DCq7jZNiT3CFdAo52AvJol-C-3InAzj6B4isdJVwVCAlUY9jxqgM43wDXrmfsqL4PGr-fsBG0YjcOzwAHFscoDXg3EGlhupxjKRwrMe7Y2bX9VzTc-RY95A03bV1avKnjwJZjh0HKbGZDEa73mPU/s1600/telegram.png"
                            alt="" />
                    </div>
                    <div class="icon-block">
                        <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiejpFbnjtnjhErKo-66_ATecAMmYtSrLzQYdIRMRAxLHtgMUZKnA6jGJQsTMnrniZmMhTZydWkR-l2cpZcGEBGlI4Ptl9ogR-NSPF2wNO5FQdMlL_xaGHQfPnSRIh0Lg4JX0PJLjg9p-tAL9Y8qFbbuGIW3YoolXiMja2qujyDjcFPYGzsPu-RyHle2Jc/s1600/youtube.png" alt="" />
                    </div>
                </div>
                <div class="images">
                    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhwX1hNs1uTxT4esqcM-g4cIPSSqGfCotsrSqPkI8aQMNoJMxECIOqHeVAPlGsSD6uEn7K5Fv_9m-vVdt4kaig7dInalmeBEnMUMbcFloJX3-y_lh6J8zz-PkIENB_1k8iAx5YEdP4FlBD0_U_JWbZC9TkP70Yd71hxULL5SbwvsZIen4_dtOOltgBpcGA/s1600/img_1.png" alt="" class="img-w">
                </div>
            </div>
            <div class="detail">
                <h3>Hi, I'm</h3>
                <h1><span style="color:#f9532d;">Durga</span> Venkateswarababu Dandu</h1>
                <p>I'm a professional Web Developer. Our Main Goal to help & Satisficed the Local & Global Clients by web development solutions</p>
            <button>Contact Us</button>
            </div>
        </div>
    </section>
</body>
</html>
