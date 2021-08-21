# vulongtran.github.io
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/vulongtran/vulongtran.github.io">
    <img src="https://pages.vulongtran.com/images/dejavu-logo.png" alt="DejaVu">
  </a>

  <h3 align="center">DejaVu</h3>

  <p align="center">
This project is built to demonstrate how to create a generate time-based one time passwords in the browser.
    <br />
    <a href="https://github.com/vulongtran/totp"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://pages.vulongtran.com/totp">View TOTP Demo Website</a>
    ·
    <a href="https://github.com/vulongtran/totp/issues">Report Bug</a>
    ·
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
This project is built to demonstrate how to create a generate time-based one time passwords in the browser.
[[TOTP demo page]](https://pages.vulongtran.com/totp)

#### TOTP Token Generator
Generate time-based one time passwords in the browser.

This page lets you easily generate a time-based one time password (TOTP) entirely in the web browser. This is useful if you want to do some quick testing to see what OTP is generated from your TOTP secret key. 


<!-- GETTING STARTED -->
## Getting Started
To use my hosted demo website to quickly check your TOTP OTP output. 

# Using Secret Key only 
Place your key in the URL using one of the following approaches: 
* https://pages.vulongtran.com/totp/#/KEY or 
* https://pages.vulongtran.com/totp?key=KEY

# Using Digits and period
You can also provide the digits and token period using a query string in the URL itself. You will be able to do this by running something like this: 
* https://pages.vulongtran.com/totp/?period=60&digits=6&key=KEY


### Installation
You are welcome to clone the repo and run a copy of this on local machine or website. To get a local copy up and running follow these simple steps.

1. Clone the repo
   ```sh
   git clone https://github.com/vulongtran/totp.git
   ```
2. Change into TOTP directory
   ```sh
   ls
   cd totp
   ```

<!-- CONTACT -->
## Contact
* Vu Long Tran - [@vulongtran](https://twitter.com/vulongtran)
* Project Link: [https://github.com/vulongtran/totp](https://github.com/vulongtran/totp)

<!-- ACKNOWLEDGEMENTS & REFERENCES-->
## References
* [Github - OTP Auth](https://hectorm.github.io/otpauth)
* [Github - TOTP Generator](https://github.com/jaden/totp-generator)
* [Website hosting - Github Pages](https://pages.github.com/)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-url]: https://linkedin.com/in/vulongtran