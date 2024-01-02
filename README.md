# সহজ বাংলায় গিট্ এবং গিটহাব


### রিপোজিটরি ক্রিয়েট:
![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/creatNewRepository.png)

![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/creatNewRepositoryPage.png)

### রিপোজিটরি ডিলিট:
![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/forDeleteRepo1.png)

![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/forDeleteRepo2.png)

![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/forDeleteRepo3.png)

![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/forDeleteRepo4.png)



### রিপোজিটরি  ক্লোন করা:
![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/forProjectClone.png)

গিট্ ইনস্টল করার পর, সংক্ষেপে নিজের করা প্রজেক্ট গিটহাবে উপলোড করার পদ্ধতি, গিটহাবে shohojBanglayGit_GitHub নামে একটি রিপোজিটরি ক্রিয়েট করেছি যা উপরে রিপোজিটরি ক্রিয়েট ছবিতেও দেখানো আছে।একটি রিপোজিটরি ক্রিয়েট করার পর HTTPS লিংক কপি করে git clone এর পরে ব্যবহার করি, যা রিপোজিটরি ক্লোন করা অংশে দেখানো আছে।  <br>
ভার্সন চেক করতে,
 ###  কমান্ড লাইন:
  ```bash
   git --version
   ```

গ্লোবাল কনফিগারেশন করতে,
 ###  কমান্ড লাইন:
  ```bash
   git config --global user.name "shahidulalam447"
   ```
  ```bash
   git config --global user.email “shahidulalam447@gmail.com”
   ```

যদি চাই একািধক প্রেজক্টের জন্য একািধক নাম ও ইমেইল  থাকেব তাহেল,
 ###  কমান্ড লাইন:
  ```bash
   git config user.name "shahidulalam447"
   ```
  ```bash
   git config user.email “shahidulalam447@gmail.com”
   ```
রিপোজিটরি ক্লোন করা,
###  কমান্ড লাইন:
  ```bash
   git clone https://github.com/shahidulalam447/shohojBanglayGit_GitHub.git
   ```

cd  shohojBanglayGit_GitHub লিখে/সরাসরি shohojBanglayGit_GitHub ফোল্ডারে ঢুকে কমান্ড লাইনে আবার নিচের কমান্ড লিখি|এর পূর্বে আমার করা প্রজেক্ট গুলো কপি করে shohojBanglayGit_GitHub ফোল্ডারে রাখি। 
 ###  কমান্ড লাইন:
  ```bash
   git status
   ```

 ###  কমান্ড লাইন:
  ```bash
   git add .
   ```

 ###  কমান্ড লাইন:
  ```bash
   git commit -m "Your Message"
   ```

###  কমান্ড লাইন:
  ```bash
   git push origin master
   ```
এবার গিটহাব রিফ্রেশ দিয়ে চেক করলে দেখবো আমার প্রজেক্ট গিটহাবে এসেগেছে। যা হচ্ছে সংক্ষেপে নিজের করা প্রজেক্ট গিটহাবে উপলোড করার পদ্ধতি। আরো বিস্তারিত বিষয় গুলো নিম্নে দেওয়া হলো। 


<br>
প্রজেক্টে গিট্ ইনিশিয়ালাইজ করতে,
###  কমান্ড লাইন:
  ```bash
   git init
   ```


###  গিটহাব শর্টকার্ট কী(Key):
আমরা যদি গিটহাবে শর্টকার্ট key ব্যবহার করতে চাই রিপোসিটোরি থেকে, তবে প্রথমে  shift + ? বাটন চাপি, তারপর সব প্রয়জনীয় শর্টকার্ট key দেখতে পারবো এবং প্রয়জন অনুযায়ী তা ব্যবহার করবো। যেমন g + p দিলে Pull request পেইজে নিয়ে যাবে। আবার g + c দিলে Code পেইজে যাবে। 
git.io এই ওয়েবসাইট থেকে গিটহাবের লিংক শর্ট করা যাবে।
আমার গিটহাবের প্রজেক্টের কোনো নির্দিষ্ট কোডের অংশ যদি লিংক এর মাধম্যে কারো সাথে শেয়ারে করতে চাই, যেন সে লিংকে ক্লিক করে সরাসরি ঐ নির্ধারিত অংশ দেখতে পায়। এর জন্য প্রথমে প্রজেক্টে ঢুকে কোডে গিয়ে যেখান থেকে শেয়ার করতে চাই সেই নাম্বার এর উপর ক্লিক করি, তারপর shift বাটন চেপে যতটুকু শেয়ার করতে চাই বাম পাশে এর নম্বরের উপর ক্লিক করি। তারপর url এ দেখতে পাবো একটা লিংক যা কারো সাথে শেয়ার করলে তা থেকে ঐ ব্যাক্তি সরাসরি ঐ জায়গায় যেতে পারবে। 
কোনো একটা ফাইলে যদি Blame এ ক্লিক করি তাহলে এর সকল History দেখতে পারবো। যেমন কোনো কোড ডিলেট করে থাকলে তা লাল করে দেখাবে। 










### প্রজেক্ট লাইভ করা: 
![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/forGitHubLive1.png)

![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/forGitHubLive2.png)

![image](https://github.com/shahidulalam447/shohojBanglayGit_GitHub/blob/master/img_shohojBanglayGit_GitHub/forLive.png)



 ###  কমান্ড লাইন:
  ```bash
   git status
   ```
