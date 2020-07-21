<template>
    <aside class="profile-card">

    <header>
        <a href="https://me.nextblu.com/">
            <img src="https://www.nextblu.com/img/favicon.png" alt="App logo"/>
        </a>
        <h1>NextBlu</h1>
    </header>

    <!-- bit of a bio; who are you? -->
    <div class="profile-bio">
        <p>The lightning fast system to interact with NextBlu.</p>
        <br>
    </div>

    <!-- some social links to show off -->
    <ul class="profile-social-links">
        <li>
            <svg xmlns='http://www.w3.org/2000/svg' width='30' height='30' viewBox='0 0 512 512'><title>Login with GitHub</title><path d='M256,32C132.3,32,32,134.9,32,261.7c0,101.5,64.2,187.5,153.2,217.9a17.56,17.56,0,0,0,3.8.4c8.3,0,11.5-6.1,11.5-11.4,0-5.5-.2-19.9-.3-39.1a102.4,102.4,0,0,1-22.6,2.7c-43.1,0-52.9-33.5-52.9-33.5-10.2-26.5-24.9-33.6-24.9-33.6-19.5-13.7-.1-14.1,1.4-14.1h.1c22.5,2,34.3,23.8,34.3,23.8,11.2,19.6,26.2,25.1,39.6,25.1a63,63,0,0,0,25.6-6c2-14.8,7.8-24.9,14.2-30.7-49.7-5.8-102-25.5-102-113.5,0-25.1,8.7-45.6,23-61.6-2.3-5.8-10-29.2,2.2-60.8a18.64,18.64,0,0,1,5-.5c8.1,0,26.4,3.1,56.6,24.1a208.21,208.21,0,0,1,112.2,0c30.2-21,48.5-24.1,56.6-24.1a18.64,18.64,0,0,1,5,.5c12.2,31.6,4.5,55,2.2,60.8,14.3,16.1,23,36.6,23,61.6,0,88.2-52.4,107.6-102.3,113.3,8,7.1,15.2,21.1,15.2,42.5,0,30.7-.3,55.5-.3,63,0,5.4,3.1,11.5,11.4,11.5a19.35,19.35,0,0,0,4-.4C415.9,449.2,480,363.1,480,261.7,480,134.9,379.7,32,256,32Z'/></svg>
        </li>
        <li>
            <svg xmlns='http://www.w3.org/2000/svg' width='30' height='30' viewBox='0 0 512 512'><title>Login with oAuth</title><path d='M256,464C141.31,464,48,370.69,48,256S141.31,48,256,48s208,93.31,208,208S370.69,464,256,464Zm0-384C159,80,80,159,80,256S159,432,256,432s176-78.95,176-176S353.05,80,256,80Z'/><path d='M323.67,292c-17.4,0-34.21-7.72-47.34-21.73a83.76,83.76,0,0,1-22-51.32c-1.47-20.7,4.88-39.75,17.88-53.62S303.38,144,323.67,144c20.14,0,38.37,7.62,51.33,21.46s19.47,33,18,53.51h0a84,84,0,0,1-22,51.3C357.86,284.28,341.06,292,323.67,292Zm55.81-74h0Z'/><path d='M163.82,295.36c-29.76,0-55.93-27.51-58.33-61.33-1.23-17.32,4.15-33.33,15.17-45.08s26.22-18,43.15-18,32.12,6.44,43.07,18.14,16.5,27.82,15.25,45C219.69,267.86,193.53,295.36,163.82,295.36Z'/><path d='M420.37,355.28c-1.59-4.7-5.46-9.71-13.22-14.46-23.46-14.33-52.32-21.91-83.48-21.91-30.57,0-60.23,7.9-83.53,22.25-26.25,16.17-43.89,39.75-51,68.18-1.68,6.69-4.13,19.14-1.51,26.11a192.18,192.18,0,0,0,232.75-80.17Z'/><path d='M163.63,401.37c7.07-28.21,22.12-51.73,45.47-70.75a8,8,0,0,0-2.59-13.77c-12-3.83-25.7-5.88-42.69-5.88-23.82,0-49.11,6.45-68.14,18.17-5.4,3.33-10.7,4.61-14.78,5.75a192.84,192.84,0,0,0,77.78,86.64l1.79-.14A102.82,102.82,0,0,1,163.63,401.37Z'/></svg>
        </li>
        <li>
            <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 512 512"><title>Login with Google</title><path d="M473.16,221.48l-2.26-9.59H262.46v88.22H387c-12.93,61.4-72.93,93.72-121.94,93.72-35.66,0-73.25-15-98.13-39.11a140.08,140.08,0,0,1-41.8-98.88c0-37.16,16.7-74.33,41-98.78s61-38.13,97.49-38.13c41.79,0,71.74,22.19,82.94,32.31l62.69-62.36C390.86,72.72,340.34,32,261.6,32h0c-60.75,0-119,23.27-161.58,65.71C58,139.5,36.25,199.93,36.25,256S56.83,369.48,97.55,411.6C141.06,456.52,202.68,480,266.13,480c57.73,0,112.45-22.62,151.45-63.66,38.34-40.4,58.17-96.3,58.17-154.9C475.75,236.77,473.27,222.12,473.16,221.48Z"/></svg>
        </li>
    </ul>

    </aside>
</template>

<script>
export default {
    name: "TimeToLogin"
}
</script>

<style>
    .profile-card {
        background: #FFB300;
        width: 60px;
        height: 40px;
        position: absolute;
        left: 50%;
        top: 55%;
        z-index: 2;
        overflow: hidden;
        opacity: 0;
        margin-top: 70px;
        -webkit-transform: translate(-50%, -50%);
        transform: translate(-50%, -50%);
        -webkit-border-radius: 50%;
        border-radius: 50%;
        -webkit-box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.16), 0px 3px 6px rgba(0, 0, 0, 0.23);
        box-shadow: 0px 3px 6px rgba(0 ,0, 0, 0.16), 0px 3px 6px rgba(0, 0, 0, 0.23);
        -webkit-animation: init 0.5s 0.2s cubic-bezier(0.55, 0.055, 0.675, 0.19) forwards, moveDown 1s 0.8s cubic-bezier(0.6, -0.28, 0.735, 0.045) forwards, moveUp 1s 1.8s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards, materia_landscape 0.5s 2.7s cubic-bezier(0.86, 0, 0.07, 1) forwards;
        animation: init 0.5s 0.2s cubic-bezier(0.55, 0.055, 0.675, 0.19) forwards, moveDown 1s 0.8s cubic-bezier(0.6, -0.28, 0.735, 0.045) forwards, moveUp 1s 1.8s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards, materia_landscape 0.5s 2.7s cubic-bezier(0.86, 0, 0.07, 1) forwards;
    }
    .profile-card header {
        width: 179px;
        height: 280px;
        padding: 40px 20px 30px 20px;
        display: inline-block;
        float: left;
        border-right: 2px dashed #EEEEEE;
        background: #FFFFFF;
        color: #000000;
        margin-top: 50px;
        opacity: 0;
        text-align: center;
        -webkit-animation: moveIn 1s 3.1s ease forwards;
        animation: moveIn 1s 3.1s ease forwards;
    }
    .profile-card header h1 {
        color: cornflowerblue;
    }
    .profile-card header a {
        display: inline-block;
        text-align: center;
        position: relative;
        margin: 25px 30px;
    }
    .profile-card header a:after {
        position: absolute;
        content: "";
        bottom: 3px;
        right: 3px;
        width: 20px;
        height: 20px;
        border: 4px solid #FFFFFF;
        -webkit-transform: scale(0);
        transform: scale(0);
        background: -webkit-linear-gradient(top, #2196F3 0%, #2196F3 50%, #FFC107 50%, #FFC107 100%);
        background: linear-gradient(#2196F3 0%, #2196F3 50%, #FFC107 50%, #FFC107 100%);
        -webkit-border-radius: 50%;
        border-radius: 50%;
        -webkit-box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.1);
        box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.1);
        -webkit-animation: scaleIn 0.3s 3.5s ease forwards;
        animation: scaleIn 0.3s 3.5s ease forwards;
    }
    .profile-card header a > img {
        width: 120px;
        max-width: 100%;
        -webkit-border-radius: 50%;
        border-radius: 50%;
        -webkit-transition: -webkit-box-shadow 0.3s ease;
        transition: box-shadow 0.3s ease;
        -webkit-box-shadow: 0px 0px 0px 8px rgba(0, 0, 0, 0.06);
        box-shadow: 0px 0px 0px 8px rgba(0, 0, 0, 0.06);
    }
    .profile-card header a:hover > img {
        -webkit-box-shadow: 0px 0px 0px 12px rgba(0, 0, 0, 0.1);
        box-shadow: 0px 0px 0px 12px rgba(0, 0, 0, 0.1);
    }
    .profile-card .profile-bio {
        width: 175px;
        height: 180px;
        display: inline-block;
        float: right;
        padding: 50px 20px 30px 20px;
        background: #FFFFFF;
        color: #333333;
        margin-top: 50px;
        text-align: center;
        opacity: 0;
        -webkit-animation: moveIn 1s 3.1s ease forwards;
        animation: moveIn 1s 3.1s ease forwards;
        margin-bottom: 30px;
    }
    .profile-social-links {
        width: 218px;
        display: inline-block;
        float: right;
        padding: 15px 20px;
        background: #FFFFFF;
        margin: 60px 0px 0px;
        text-align: center;
        opacity: 0;
        -webkit-box-sizing: border-box;
        box-sizing: border-box;
        -webkit-animation: moveIn 1s 3.1s ease forwards;
        animation: moveIn 1s 3.1s ease forwards;
    }
    .profile-social-links li {
        list-style: none;
        margin: -5px 0px 0px 0px;
        padding: 0px;
        float: left;
        width: 33.3%;
        text-align: center;
    }
    .profile-social-links li a {
        display: inline-block;
        width: 24px;
        height: 24px;
        padding: 6px;
        position: relative;
        overflow: hidden!important;
        -webkit-border-radius: 50%;
        border-radius: 50%;
    }
    .profile-social-links li a img {
        position: relative;
        z-index: 1;
    }
    .profile-social-links li a:before {
        display: block;
        content: "";
        background: rgba(0, 0, 0, 0.3);
        position: absolute;
        left: 0px;
        top: 0px;
        width: 36px;
        height: 36px;
        opacity: 1;
        -webkit-transition: transform 0.4s ease, opacity 1s ease-out;
        transition: transform 0.4s ease, opacity 1s ease-out;
        -webkit-transform: scale3d(0, 0, 1);
        transform: scale3d(0, 0, 1);
        -webkit-border-radius: 50%;
        border-radius: 50%;
    }
    .profile-social-links li a:hover:before {
        -webkit-animation: ripple 1s ease forwards;
        animation: ripple 1s ease forwards;
    }
    .profile-social-links li a img,
    .profile-social-links li a svg {
        width: 24px;
    }


    @media screen and (min-aspect-ratio: 4/3) {
        body {
            background-size: 100% auto;
        }
        body:before {
            width: 0px;
        }
        @-webkit-keyframes puff {
            0% {
                top: 100%;
                width: 0px;
                padding-bottom: 0px;
            }
            100% {
                top: 50%;
                width: 100%;
                padding-bottom: 100%;
            }
        }
        @keyframes puff {
            0% {
                top: 100%;
                width: 0px;
                padding-bottom: 0px;
            }
            100% {
                top: 50%;
                width: 100%;
                padding-bottom: 100%;
            }
        }
    }
    @media screen and (min-height: 480px) {
        .profile-card {
            -webkit-animation: init 0.5s 0.2s cubic-bezier(0.55, 0.055, 0.675, 0.19) forwards, moveDown 1s 0.8s cubic-bezier(0.6, -0.28, 0.735, 0.045) forwards, moveUp 1s 1.8s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards, materia_portrait 0.5s 2.7s cubic-bezier(0.86, 0, 0.07, 1) forwards;
            animation: init 0.5s 0.2s cubic-bezier(0.55, 0.055, 0.675, 0.19) forwards, moveDown 1s 0.8s cubic-bezier(0.6, -0.28, 0.735, 0.045) forwards, moveUp 1s 1.8s cubic-bezier(0.175, 0.885, 0.32, 1.275) forwards, materia_portrait 0.5s 2.7s cubic-bezier(0.86, 0, 0.07, 1) forwards;
        }
        .profile-card header {
            width: auto;
            height: auto;
            padding: 30px 20px;
            display: block;
            float: none;
            border-right: none;
        }
        .profile-card .profile-bio {
            width: auto;
            height: auto;
            padding: 15px 20px 30px 20px;
            display: block;
            float: none;
        }
        .profile-social-links {
            width: 100%;
            display: block;
            float: none;
        }
    }
    @media screen and (min-aspect-ratio: 4/3) {
        body {
            background-size: 100% auto;
        }
        body:before {
            width: 0px;
            -webkit-animation: puff_landscape 0.5s 1.8s cubic-bezier(0.55, 0.055, 0.675, 0.19) forwards, borderRadius 0.2s 2.3s linear forwards;
            animation: puff_landscape 0.5s 1.8s cubic-bezier(0.55, 0.055, 0.675, 0.19) forwards, borderRadius 0.2s 2.3s linear forwards;
        }
    }
    @-webkit-keyframes init {
        0% {
            width: 0px;
            height: 0px;
        }
        100% {
            width: 56px;
            height: 56px;
            margin-top: 0px;
            opacity: 1;
        }
    }
    @keyframes init {
        0% {
            width: 0px;
            height: 0px;
        }
        100% {
            width: 56px;
            height: 56px;
            margin-top: 0px;
            opacity: 1;
        }
    }
    @-webkit-keyframes puff_portrait {
        0% {
            top: 100%;
            height: 0px;
            padding: 0px;
        }
        100% {
            top: 50%;
            height: 100%;
            padding: 0px 100%;
        }
    }
    @keyframes puff_portrait {
        0% {
            top: 100%;
            height: 0px;
            padding: 0px;
        }
        100% {
            top: 50%;
            height: 100%;
            padding: 0px 100%;
        }
    }
    @-webkit-keyframes puff_landscape {
        0% {
            top: 100%;
            width: 0px;
            padding-bottom: 0px;
        }
        100% {
            top: 50%;
            width: 100%;
            padding-bottom: 100%;
        }
    }
    @keyframes puff_landscape {
        0% {
            top: 100%;
            width: 0px;
            padding-bottom: 0px;
        }
        100% {
            top: 50%;
            width: 100%;
            padding-bottom: 100%;
        }
    }
    @-webkit-keyframes borderRadius {
        0% {
            -webkit-border-radius: 50%;
        }
        100% {
            -webkit-border-radius: 0px;
        }
    }
    @keyframes borderRadius {
        0% {
            -webkit-border-radius: 50%;
        }
        100% {
            border-radius: 0px;
        }
    }
    @-webkit-keyframes moveDown {
        0% {
            top: 50%;
        }
        50% {
            top: 40%;
        }
        100% {
            top: 100%;
        }
    }
    @keyframes moveDown {
        0% {
            top: 50%;
        }
        50% {
            top: 40%;
        }
        100% {
            top: 100%;
        }
    }
    @-webkit-keyframes moveUp {
        0% {
            background: #FFB300;
            top: 100%;
        }
        50% {
            top: 40%;
        }
        100% {
            top: 50%;
            background: #E0E0E0;
        }
    }
    @keyframes moveUp {
        0% {
            background: #FFB300;
            top: 100%;
        }
        50% {
            top: 40%;
        }
        100% {
            top: 50%;
            background: #E0E0E0;
        }
    }
    @-webkit-keyframes materia_landscape {
        0% {
            background: #E0E0E0;
        }
        50% {
            -webkit-border-radius: 4px;
        }
        100% {
            width: 440px;
            height: 280px;
            background: #FFFFFF;
            -webkit-border-radius: 4px;
        }
    }
    @keyframes materia_landscape {
        0% {
            background: #E0E0E0;
        }
        50% {
            border-radius: 4px;
        }
        100% {
            width: 440px;
            height: 280px;
            background: #FFFFFF;
            border-radius: 4px;
        }
    }
    @-webkit-keyframes materia_portrait {
        0% {
            background: #E0E0E0;
        }
        50% {
            -webkit-border-radius: 4px;
        }
        100% {
            width: 280px;
            height: 440px;
            background: #FFFFFF;
            -webkit-border-radius: 4px;
        }
    }
    @keyframes materia_portrait {
        0% {
            background: #E0E0E0;
        }
        50% {
            border-radius: 4px;
        }
        100% {
            width: 280px;
            height: 440px;
            background: #FFFFFF;
            border-radius: 4px;
        }
    }
    @-webkit-keyframes moveIn {
        0% {
            margin-top: 50px;
            opacity: 0;
        }
        100% {
            opacity: 1;
            margin-top: -20px;
        }
    }
    @keyframes moveIn {
        0% {
            margin-top: 50px;
            opacity: 0;
        }
        100% {
            opacity: 1;
            margin-top: -20px;
        }
    }
    @-webkit-keyframes scaleIn {
        0% {
            -webkit-transform: scale(0);
        }
        100% {
            -webkit-transform: scale(1);
        }
    }
    @keyframes scaleIn {
        0% {
            transform: scale(0);
        }
        100% {
            transform: scale(1);
        }
    }
    @-webkit-keyframes ripple {
        0% {
            transform: scale3d(0, 0, 0);
        }
        50%, 100% {
            -webkit-transform: scale3d(1, 1, 1);
        }
        100% {
            opacity: 0;
        }
    }
    @keyframes ripple {
        0% {
            transform: scale3d(0, 0, 0);
        }
        50%, 100% {
            transform: scale3d(1, 1, 1);
        }
        100% {
            opacity: 0;
        }
    }

    .footer-message {
        position: fixed;
        bottom: 6px;
        left: 0;
        width: 100%;
        text-align: center;
        -webkit-animation: moveIn 1s 3.1s ease forwards;
        animation: moveIn 1s 3.1s ease forwards;
    }
</style>
