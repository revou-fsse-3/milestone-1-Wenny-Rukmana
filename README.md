<img align="center" src="images/logo-light.png"/><br/>

## Website and documentation of [MAGO](http://gelatospace.shop/)

Mago, a parent company that striving for positive change. It's complementary businesses deliver world-leading, sustainable solutions. This web created using HTML, CSS and a little pinch of JavaScript. Adapted responsive CSS to suitqable with various screen size. Plus a little touch from Adobe Illustrator and Photoshop for the images.

<img align="center" src="images/web-display.png" /><br/>

---
## Getting Started
- **[Web Development](#web-development)**
  - **[HTML](#html)**
  - **[CSS](#css)**
  - **[Javascript](#javascript)**
  - **[GitHub](#github)**
- **[Deployment](#deployment)**
  - **[NiagaHoster](#niagahoster)**
  - **[Netlify](#netlify)**
    - **[Register Netlify & Connect with Github](#register-netlify--connect-with-github)**
    - **[Auto Deployment with Netlify](#auto-deployment-with-netlify)**
    - **[Connect Custom Domain with Netlify](#connect-custom-domain-with-netlify)**
  - **[SSL / TSL Certificate](#ssl--tsl-certificate)**
    - **[Installing / TSL Certificate](#installing--tsl-certificate)**
  - **[More Simple Way to Custom the Domain Name](#more-simple-way-to-custom-the-domain-name)**
- **[Get in Touch](#get-in-touch)**
---

## Web Development
This responsive web was created using HTML, CSS and JavaScript with a little animation and transitions for effects. After that, the web was commit to github's repository which has been clone before hand.

- ### **HTML**
  as the files named itself and its extensions in this repository, the homepage `index.html` file was created using HTML which contain **non-semantic elements** such as `<div>`, `<span> ` etc and **semantic elements** `<header>`, `<footer>`, `<form>`, `<section>`, `<main>`, etc.

  - **Header**
  For the header itself contain `Top Navigation Manu` and `Main Navigation` which contain logo, navigation menu, search icon and hamburger menu (which is hidden by default on big screens). <br>
  - **Main**
  At the main section, there is a `div` that holds `h1`, `p` and the `button` which created using `a href` . There are 2 `buttons` on default, however, only the button with CTA only will be displayed on smaller screens.
  <img align="center" src="images/web-mainsc.jpg" width="650px" height="auto"/><br/>
  - **Body** 
    For the body content which located below the main section, there are 2 sections
    - The first sections `(second section)` contain header (`h2` & `h3`) and text `p`, with gallery images which built using `grid`. 
    <img align="center" src="images/web-displayed2.png" width="650px" height="auto"/><br/>
  
    - The second sections `(third section)` contain header (`h2` & `h3`) and text `p`, with 3 columns which displayed the company features.
    <img align="center" src="images/web-displayed3.png" width="650px" height="auto"/><br/>
  - **Footer**
    The footer part has 2 sections. The upper part contains 1 row with four columns which contain the company features, contacts, `links`, and subscription form`. The bottom parts contains `links`, `social icons` and copyright text.
    <img align="center" src="images/web-displayed4.png" width="650px" height="auto"/><br/>


- ### **CSS**
  All styling or transitions in this site was written using CSS in the file named `styles.css` for the styling, and `responsive.css` for responsive display for various size screen.
   <img align="center" src="images/web-displayed6.jpg" width="600px" height="auto"/><br/>

- ### **JavaScript**
  This site only contains simple JavaScript for the hamburger menu buttons on smaller screen size.
  <img align="center" src="images/web-displayed5.png" width="400px" height="auto"/><br/>

- ### **Github**
  Github repository was cloned before hand. All the files and folders was committed to this repository via source control in VSCode.<br/>
  <img align="center" src="images/github.png" width="300px" height="auto"/><br/>


  <br/>

## Deployment
- ### **NiagaHoster**
  At here we will purchase the custom domain name for this project.
  - Go to [Niagahoster](https://www.niagahoster.co.id/) and buy a domain name.
  
  - Go to `Domain` menu button and click `Cari & Cek Domain` on dropdown menu.<br/>
  <img align="center" src="images/buydomain1.png" width="650px" height="auto"/><br/><br/>

  - Search and Check the domain name. For example in this case `GelatoSpace`.<br/>
   <img align="center" src="images/search-domain.png" width="650px" height="auto"/><br/><br/>

  - It will give several domain name options that available to purchase. <br/>
   <img align="center" src="images/buydomain2.png" width="650px" height="auto"/><br/><br/>

  - Choose and checkout the domain name and pay using your favorite payment method.<br/>
  <img align="center" src="images/buydomain3.png" width="650px" height="auto"/><br/><br/>

  - After the payment completed, login to <br/>Niagahoster's member area and check the domain name.<br/>
  <img align="center" src="images/buydomain2.png" width="650px" height="auto"/><br/><br/>
  

- ### **Netlify**
  - #### **Register Netlify & Connect with Github**
    - Click the `Sign Up` button on [Netlify](https://www.netlify.com/) <br/>
       <img align="center" src="images/netlify1.png" width="650px" height="auto"/><br/><br/>

    - Choose the sign up method. In this case we use Github. Authorize Netlify and finish the registration process.<br/> 
       <img align="center" src="images/netlify2.png" width="300px" height="auto"/><br/>
       <img align="center" src="images/netlify3.png" width="300px" height="auto"/><br/>
       <img align="center" src="images/netlify4.png" width="300px" height="auto"/><br/><br/>

  - #### **Auto Deployment with Netlify**
    - Go to `Sites` menu on left side in Netlify Dashboard and click `Add new site`. Choose `Import and existing projects`.<br/>
      <img align="center" src="images/netlify8.png" width="300px" height="auto"/><br/>
      
    - Click `Deploy with Github`.<br/>
      <img align="center" src="images/netlify5.png" width="300px" height="auto"/><br/>

    - Choose the repository and deploy the projects by clicking the deploy button.
      <img align="center" src="images/netlify9.png" width="600px" height="auto"/><br/>
      <img align="center" src="images/netlify10.png" width="300px" height="auto"/><br/>

    - Site has been successfully deployed if the status changed to link as shown on below images.<br/>
    <img align="center" src="images/netlify11.png" width="300px" height="auto"/><br/>
    <img align="center" src="images/netlify12.png" width="300px" height="auto"/><br/>

  - #### **Connect Custom Domain with Netlify**
  - Go to `Setup your site` Section and click   `Setup a custom Domain`.<br/>
    <img align="center" src="images/cname4.png" width="650px" height="auto"/><br/>
  - Add custom domain name and click verify button.<br/>
    <img align="center" src="images/cname5.png" width="650px" height="auto"/><br/>
    
  - Netlify checking to DNS and will shown as below if not connected.<br/>
    <img align="center" src="images/cname6.png" width="650px" height="auto"/><br/>

  - If the domain has been connected to Cloudflare, it will shown as bellow image.<br/>
    <img align="center" src="images/cname3.png" width="650px" height="auto"/><br/>
  
- ### **SSL / TSL Certificate**
  - #### **Installing / TSL Certificate**
    - At `Setup your site` Section's and click `Secure your site to HTTPS`.
    <img align="center" src="images/SSL1.png" width="650px" height="auto"/><br/>
    - Click on `Verify DNS Configuration` button to verify.
    <img align="center" src="images/SSL2.png" width="650px" height="auto"/><br/>
    - If the SSL / TSL certificate successfull to installed, it will show as bellow image.<br/>
    <img align="center" src="images/SSL3.png" width="650px" height="auto"/><br/>

### **More Simple Way to Custom the Domain Name**
- At Niagahoster Memberpages, go to `DNS / Name Server` Section.
  <img align="center" src="images/dns1.png" width="650px" height="auto"/><br/>
- Click `Change Nameserver` button and change the nameserver at DNS Records section. 
- at `Change Nameserver` section, insert DNS provided by Netlify.<br/>
  <img align="center" src="images/dns3.png" width="300px" height="auto"/><br/>
- The web should be accessible now.




## Get in Touch

<a href="https://www.linkedin.com/in/wennyleo/" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="linkedin" height="30" width="40" /></a><a href="https://instagram.com/wnyleo" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="instagram" height="30" width="40" /></a><a href="https://www.facebook.com/wenny.leo" target="_blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="100011683902531e" height="30" width="40" /></a>
&nbsp;


