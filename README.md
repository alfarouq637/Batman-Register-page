# 🦇 Batman Registration Page

Welcome to the official **Batman Registration Page**! This is a simple, fun, and interactive HTML-based web form designed to recruit the next Dark Knight. The page features a unique dual-layout design, offering the registration form simultaneously in both English and Odia (ବ୍ୟାଟମ୍ୟାନ୍ ପଞ୍ଜିକରଣ ପୃଷ୍ଠା).

## 📝 Features

*   **Bilingual Interface:** Side-by-side registration tables catering to English and Odia speakers.
*   **Comprehensive Data Collection:** Captures essential vigilante information including Username, Password, Email, Phone, Address, Gender, Age, and a critical verification radio button: "Are you a Batman?"[cite: 1].
*   **Multimedia Integration:** Features embedded Batman imagery (GIFs and JPGs) and interactive audio playback controls[cite: 1].

## 🛠️ Tech Stack & Skills

[![My Skills](https://skillicons.dev/icons?i=js,html,css,wasm)](https://skillicons.dev)
[![My Skills](https://skillicons.dev/icons?i=java,kotlin,nodejs,figma&theme=light)](https://skillicons.dev)
[![My Skills](https://skillicons.dev/icons?i=aws,gcp,azure,react,vue,flutter&perline=3)](https://skillicons.dev)
<p align="center">
  <a href="https://skillicons.dev">
    <!-- Added HTML icon here as requested -->
    <img src="https://skillicons.dev/icons?i=git,kubernetes,docker,c,vim,html" />
  </a>
</p>

## 🎨 Visual Assets

![Webpage]([index.html](https://github.com/user-attachments/files/29661574/index.html)
)<!DOCTYPE html>

<html lang="en">

<head>
    
    <meta charset="UTF-8">
    <title> Batman Register page🦇 </title>
    <link rel="icon" type="image/gif" href="images/Batman.gif">

</head>

<body>

    <center>
    <h1 >Batman Register page🦇
        <br>
        ବ୍ୟାଟମ୍ୟାନ୍ ପଞ୍ଜିକରଣ ପୃଷ୍ଠା🦇
    </h1>
    <hr>
    <img src="images/Batman.gif" alt="شوف هي على حسب" width="200" height="200">
    <img src="images/Batmar.jpg" alt="شوف هي على حسب" width="200" height="200">
    <hr>
    </center>
    <center>
    <table border="1">
    <tr>
    <td>
        <table border="1">
        
        <tr>
            <td>ଉପଯୋଗକର୍ତ୍ତାନାମ:</td>
            <td><input type="Username" name="ଉପଯୋଗକର୍ତ୍ତାନାମ" placeholder="ତୁମର ଉପଯୋଗକର୍ତ୍ତାନାମ ପ୍ରବେଶ କରା"></td>
        </tr>
        <tr>
            <td>ପାସୱାର୍ଡ:</td>
            <td><input type="password" name="ପାସୱାର୍ଡ" placeholder="ତୁମର ପାସୱାର୍ଡ ପ୍ରବେଶ କରା"></td>
        </tr>
        <tr>
            <td>ଇମେଲ୍:</td>
            <td><input type="email" name="ଇମେଲ୍" placeholder="ତୁମର ଇମେଲ୍ ପ୍ରବେଶ କରା"></td>
        </tr>
        <tr>
            <td>ଫୋନ୍:</td>
            <td><input type="tel" name="ଫୋନ୍" placeholder="ତୁମର ଫୋନ୍ ନମ୍ବର ପ୍ରବେଶ କରା"></td>
        </tr>
        <tr>
            <td>ଠିକଣା:</td>
            <td><input type="text" name="ଠିକଣା" placeholder="ତୁମର ଠିକଣା ପ୍ରବେଶ କରା"></td>
        </tr>
        <tr>
            <td>ଲିଙ୍ଗ:</td>
            <td>
                <input type="radio" name="ଲିଙ୍ଗ" value="ପୁରୁଷ"> ପୁରୁଷ
                <input type="radio" name="ଲିଙ୍ଗ" value="ମହିଳା"> ମହିଳା
            </td>
        </tr>
        <tr>
            <td>ତୁମର ବୟସ:</td>
            <td><input type="number" name="ତୁମର ବୟସ" placeholder="ତୁମର ବୟସ ପ୍ରବେଶ କରା"></td>
        </tr>
        <tr>
            <td>ତୁମେ ବ୍ୟାଟମ୍ୟାନ୍ କି?</td>
            <td>
                <input type="radio" name="ବ୍ୟାଟମ୍ୟାନ୍" value="ହଁ"> ହଁ
                <input type="radio" name="ବ୍ୟାଟମ୍ୟାନ୍" value="ନାହିଁ"> ହଁ
            </td>
        </tr>
        <tr>
            <td><input type="submit" value="ପ୍ରବେଶ କରା"></td>
            <td><input type="reset" value="ପୁନଃସେଟ୍ କରା"></td>
        </tr>
        
    </tr>
    </table>
    </td>
    <td>
    <table border="1">
    <tr>
        
        <tr>
            <td>Username:</td>
            <td><input type="text" name="username" placeholder="Enter your username"></td>
        </tr>
        <tr>
            <td>Password:</td>
            <td><input type="password" name="password" placeholder="Enter your password"></td>
        </tr>
        <tr>
            <td>Email:</td>
            <td><input type="email" name="email" placeholder="Enter your email"></td>
        </tr>
        <tr>
            <td>Phone:</td>
            <td><input type="tel" name="phone" placeholder="Enter your phone number"></td>
        </tr>
        <tr>
            <td>Address:</td>
            <td><input type="text" name="address" placeholder="Enter your address"></td>
        </tr>
        <tr>
            <td>Gender:</td>
            <td>
                <input type="radio" name="gender" value="male"> Male
                <input type="radio" name="gender" value="female"> Female
            </td>
        </tr>
        <tr>
            <td>your age:</td>
            <td><input type="number" name="age" placeholder="Enter your age"></td>
        </tr>
        <tr>
            <td>are you a Batman?</td>
            <td>
                <input type="radio" name="batman" value="yes"> Yes
                <input type="radio" name="batman" value="no"> Yes
            </td>
        </tr>
        <tr>
            <td><input type="submit" value="submit"></td>
            <td><input type="reset" value="reset"></td>
        </tr>
        
    </table>
    </td>
    </table>
    </center>

    <hr>

    <center>
    <audio src="Voice/Int-3ayez-tbawaz-akhlaky.mp3" type="audio/mpeg"  controls>روح غير البراوسر يا بيه</audio>
    <audio src="Voice/du-bist-gut-genug.mp3" type="audio/mpeg"  controls>روح غير البراوسر يا بيه</audio>
    </center>

</html>

## 🧬 Our Community

Proudly backed by the **ANOMALY** Computers & Artificial Intelligence Community:

<p align="center">
  <img src="<img width="1433" height="1433" alt="Gemini_Generated_Image_aahbr9aahbr9aahb" src="https://github.com/user-attachments/assets/ccef185f-1dc2-4b3a-89d6-e998771ea77c" />
" alt="ANOMALY Community Icon" width="300">
</p>

---
*Developed by Eng. Alfarouq Ibrahim*
