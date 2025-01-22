<template>
    <div class="home">
        <div class="navbar">
            <div class="logo">
                <img class="img" src="../assets/images/logo.svg" alt="" srcset="">
            </div>
            <div class="navbar-links">
                <a class="link">Features</a>
                <a class="link">Team</a>
                <a class="link">Sign In</a>
            </div>
        </div>
        <div class="hero">
            <div class="hero-img">
                <img class="img" src="../assets/images/illustration-intro.png" alt="" srcset="">
            </div>
            <div class="hero-text">
                <p class="heading">All your files in one secure location, <br> accessible anywhere.</p>
                <p class="body">Fylo stores all your most important files in one secure location. <br>
                    Access them wherever you need, share and collaborate with <br> friends family, and co-workers.
                </p>
            </div>
            <button class="button">Get Started</button>
            <div class="curvy-bg">
                <img src="../assets/images/bg-curvy-desktop.svg">
            </div>
        </div>

    </div>
    <div class="home-2">
        <div class="services">
            <div class="service-row">
                <div class="service">
                    <div class="img">
                        <img src="../assets/images/icon-access-anywhere.svg" alt="">
                    </div>
                    <div class="title">
                        <p>Access your files, anywhere</p>
                    </div>
                    <div class="text">
                        <p>The ability to use a smartphone,
                            tablet, or computer to access your account means your
                            files follow you everywhere.
                        </p>
                    </div>
                </div>
                <div class="service">
                    <div class="img">
                        <img src="../assets/images/icon-security.svg" alt="">
                    </div>
                    <div class="title">
                        <p>Security you can trust</p>
                    </div>
                    <div class="text">
                        <p>2-factor authentication and user-controlled
                            encryption are just a couple of the security features
                            we allow to help secure your files.
                        </p>
                    </div>
                </div>
            </div>
            <div class="service-row">
                <div class="service">
                    <div class="img">
                        <img src="../assets/images/icon-collaboration.svg" alt="">
                    </div>
                    <div class="title">
                        <p>Real-time collaboration</p>
                    </div>
                    <div class="text">
                        <p>Securely share files and folders with friends,
                            family and colleagues for live collaboration. No email attachments required.
                        </p>
                    </div>
                </div>
                <div class="service">
                    <div class="img">
                        <img src="../assets/images/icon-any-file.svg" alt="">
                    </div>
                    <div class="title">
                        <p>Store any type of file</p>
                    </div>
                    <div class="text">
                        <p>Whether you're sharing holidays photos or work documents,
                            Fylo has you covered allowing for all file types to be securely stored and shared.
                        </p>
                    </div>
                </div>
            </div>
        </div>
        <div class="stay-productive">
            <div class="image">
                <img class="img" src="../assets/images/illustration-stay-productive.png" alt="" srcset="">
            </div>
            <div class="content">
                <div class="heading">
                    <p class="title">Stay productive, <br>wherever you are</p>
                </div>
                <div class="c-body">
                    <p class="text">
                        Never let location be an issue when accessing your files.
                        Fylo has you covered for all of your file storage needs.
                    </p>
                    <p class="text">
                        Securely share files and folders with friends, family and colleagues
                        for live collaboration. No email attachments required.
                    </p>
                </div>
                <div class="link-section">
                    <a class="link" href="">See how Flyo works</a>
                </div>
            </div>

        </div>
        <div class="feedback">
            <FeedbackCard
                content="Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine."
                img="../assets/images/profile-1.jpg" name="Satish Patel" occupation="Founder & CEO, Huddle" />
            <FeedbackCard
                content="Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine."
                img="../assets/images/profile-2.jpg" name="Bruce McKenzie" occupation="Founder & CEO, Huddle" />
            <FeedbackCard
                content="Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine."
                img="../assets/images/profile-3.jpg" name="Iva Boyd" occupation="Founder & CEO, Huddle" />
        </div>

    </div>
    <div class="home-3">
        <div class="early-access-card">
            <div class="card">
                <div class="heading">
                    <p class="title">Get early access today</p>
                </div>
                <div class="content">
                    <p class="text">It only takes a minute to sign up and our free starter tier is extremely generous. If
                        you have any questions, our support team would be happy to help you.</p>
                </div>
                <div class="email">
                    <input class="input" type="email" name="" id="">
                    <button class="button">Get Started For Free</button>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="logo">
                <img src="../assets/images/logo.svg" alt="" srcset="">
            </div>
            <div class="section">
                <div class="sec-1">
                    <p class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
                        incididunt ut labore et dolore magna aliqua</p>
                </div>
                <div class="sec-2">
                    <p>+1-543-123-4567</p>
                    <p>example@fylo.com</p>
                </div>
                <div class="sec-3">
                    <p>About Us</p>
                    <p>Jobs</p>
                    <p>Press</p>
                    <p>Blog</p>
                </div>
                <div class="sec-4">
                    <p>Contact Us</p>
                    <p>Privacy</p>
                    <p>Terms</p>
                </div>
                <div class="sec-5">
                    <a href="https://www.facebook.com" target="_blank" class="social-link">
                        <i class="fab fa-facebook-f"></i>
                    </a>
                    <a href="https://www.twitter.com" target="_blank" class="social-link">
                        <i class="fab fa-twitter"></i>
                    </a>
                    <a href="https://www.instagram.com" target="_blank" class="social-link">
                        <i class="fab fa-instagram"></i>
                    </a>
                </div>

            </div>
        </div>
    </div>
</template>

<script>
import FeedbackCard from './FeedbackCard.vue';

export default {
    name: 'HomePage',
    components: { FeedbackCard },
}
</script>

<style>
.home {
    color: white;
    padding: 5%;
}

.home-2 {
    color: white;
    padding: 5%;
    background-color: #181F2B;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 5%;
}

.navbar-links {
    display: flex;
    gap: 3rem;
}

.home .navbar-links .link {
    text-decoration: none;
    color: white;
    font-family: var(--font-heading);
    font-size: 12px;
    white-space: nowrap;
    transition: color 0.3s;
}

.home .navbar-links .link:hover {
    color: #00C1FF;
}

.hero {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-left: 22%;
    padding-right: 22%;
}

.hero-img {
    margin-top: 5%;
}

.hero-img img {
    width: 720px;
    height: 534px;
}

.hero-text {
    text-align: center;
}

.hero-text .heading {
    font-family: var(--font-heading);
    font-size: 40px;
    font-weight: 700;
}

.hero-text .body {
    font-family: var(--font-body);
    font-size: 20px;
    font-weight: 400;
}

.button {
    padding: 10px 60px;
    border-radius: 999px;
    background-color: #00C1FF;
    color: white;
    border: none;
    font-family: var(--font-heading);
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.curvy-bg {
    position: absolute;
    top: 100%;
    left: 50%;
    transform: translateX(-50%);
    z-index: -1;
    width: 100%;
}

.curvy-bg img {
    width: 100%;
    height: auto;
}

.services {
    background-color: #181F2B;
    padding-left: 22%;
    padding-right: 22%;
    display: flex;
    flex-direction: column;
    gap: 5rem;
}

.service-row {
    display: flex;
    justify-content: center;
    text-align: center;
    gap: 4rem;
}

.service .title {
    font-family: var(--font-heading);
    font-size: 18px;
    font-weight: 700;
}

.service .text {
    font-family: var(--font-body);
    font-size: 12px;
    font-weight: 400;
}

.stay-productive {
    margin-top: 5%;
    display: flex;
    gap: 2rem;
}

.stay-productive .content .heading .title {
    font-family: var(--font-heading);
    font-size: 40px;
    font-weight: 700;
}

.stay-productive .content .c-body .text {
    font-family: var(--font-body);
    font-size: 16px;
    font-weight: 400;
}

.stay-productive .content .c-body .link-section {
    background-color: aliceblue;
    color: #62E0D9;
}

.stay-productive .content .c-body .link-section .link {
    font-family: var(--font-body);
    font-size: 16px;
    font-weight: 400;
    color: #62E0D9;
}

.feedback {
    padding-top: 15%;
    padding-bottom: 15%;
    display: flex;
    gap: 2rem;
}

.home-3 {
    color: white;
    padding: 5%;
    background-color: #0B1524;
}

.early-access-card {
    margin-top: 5%;
}

.early-access-card .card {
    margin-top: -20%;
    background-color: #1B2330;
    padding: 5%;
    text-align: center;
}

.early-access-card .card .heading .title {
    font-family: var(--font-heading);
    font-size: 32px;
    font-weight: 700;
}

.early-access-card .card .content .text {
    font-family: var(--font-body);
    font-size: 14px;
    font-weight: 400;
}

.footer {
    margin-top: 10%;
    padding: 20px;
    /* background-color: #202A3C; */
    color: #fff;
    font-family: var(--font-body);
}

.footer .section {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    gap: 2rem;
}

.footer .section .sec-1 {
    width: 30%;
}

.sec-5 .social-link {
    margin: 0 10px;
    color: #fff;
    font-size: 20px;
    text-decoration: none;
}

.early-access-card .email {
    display: flex;
    justify-content: center;
    gap: 2rem;
}

.early-access-card .email .input {
    padding: 10px 100px;
    border-radius: 999px;
}

.early-access-card .button {
    padding: 10px 40px;
    border-radius: 999px;
    background-color: #00C1FF;
    color: white;
    border: none;
    font-family: var(--font-heading);
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

@media (max-width: 420px) {
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 5px 5%;
        gap: 3rem;
    }

    .navbar .logo .img {
        width: 80px
    }

    .navbar-links {
        display: flex;
        gap: 3rem;
    }

    .hero .hero-img .img {
        width: 304px;
        height: 225px;
    }

    .stay-productive .img {
        width: 300px;
    }

    .stay-productive {
        padding-left: 5%;
        padding-right: 5%;
        gap: 2rem;
        display: flex;
        flex-direction: column;
    }

    .hero {
        padding-left: 5%;
        padding-right: 5%;
    }

    .hero-text .heading {
        font-family: var(--font-heading);
        font-size: 24px;
        font-weight: 700;
    }

    .hero-text .body {
        font-family: var(--font-body);
        font-size: 14px;
        font-weight: 400;
    }

    .button {
        padding: 10px 60px;
        border-radius: 999px;
        background-color: #00C1FF;
        color: white;
        border: none;
        font-family: var(--font-heading);
        font-size: 16px;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }

    .curvy-bg {
        position: absolute;
        top: 100%;
        left: 50%;
        transform: translateX(-50%);
        z-index: -1;
        width: 100%;
    }

    .curvy-bg img {
        width: 100%;
        height: auto;
    }

    .services {
        background-color: #181F2B;
        padding-left: 22%;
        padding-right: 22%;
        display: flex;
        flex-direction: column;
        gap: 5rem;
    }

    .service-row {
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: center;
        gap: 4rem;
    }

    .service .title {
        font-family: var(--font-heading);
        font-size: 18px;
        font-weight: 700;
    }

    .service .text {
        font-family: var(--font-body);
        font-size: 12px;
        font-weight: 400;
    }

    .stay-productive {
        margin-top: 5%;
        display: flex;
        gap: 2rem;
    }

    .stay-productive .content .heading .title {
        font-family: var(--font-heading);
        font-size: 24px;
        font-weight: 700;
    }

    .stay-productive .content .c-body .text {
        font-family: var(--font-body);
        font-size: 14px;
        font-weight: 400;
    }

    .stay-productive .content .c-body .link-section {
        background-color: aliceblue;
        color: #62E0D9;
    }

    .stay-productive .content .c-body .link-section .link {
        font-family: var(--font-body);
        font-size: 16px;
        font-weight: 400;
        color: #62E0D9;
    }

    .feedback {
        padding-top: 15%;
        padding-bottom: 15%;
        padding-left: 5%;
        padding-right: 5%;
        display: flex;
        flex-direction: column;
        gap: 2rem;
    }

    .feedback-card {
        padding: 4%;
    }

    .home-3 {
        color: white;
        padding: 5%;
        background-color: #0B1524;
    }

    .early-access-card {
        margin-top: 5%;
    }

    .early-access-card .card {
        margin-top: -20%;
        background-color: #1B2330;
        padding: 5%;
        text-align: center;
    }

    .early-access-card .card .heading .title {
        font-family: var(--font-heading);
        font-size: 32px;
        font-weight: 700;
    }

    .early-access-card .card .content .text {
        font-family: var(--font-body);
        font-size: 14px;
        font-weight: 400;
    }

    .footer {
        margin-top: 10%;
        padding: 20px;
        /* background-color: #202A3C; */
        color: #fff;
        font-family: var(--font-body);
    }

    .footer .section {
        display: flex;
        flex-direction: row;
        justify-content: space-evenly;
        gap: 2rem;
    }

    .footer .section .sec-1 {
        width: 30%;
    }

    .sec-5 .social-link {
        margin: 0 10px;
        color: #fff;
        font-size: 20px;
        text-decoration: none;
    }

    .early-access-card .email {
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 2rem;
    }

    .early-access-card .email .input {
        padding: 10px 4px;
        border-radius: 999px;
    }

    .early-access-card .button {
        padding: 10px 4px;
        border-radius: 999px;
        background-color: #00C1FF;
        color: white;
        border: none;
        font-family: var(--font-heading);
        font-size: 16px;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }

    .early-access-card .title {
        font-size: 24px;
    }

    .early-access-card .text {
        font-size: 14px;
    }

    .footer .section {
        display: flex;
        flex-direction: column;
    }
}
</style>