# TENEO-NODE

Running Teneo Node BETA, CLI Version. <br>
Teneo Is an Browser extension Node Based. <br>

<img src="https://cdn.prod.website-files.com/665c71122bb2018f6ed3f9c9/66eaaf8660d0ba047f3f2058_screenshot.png" loading="lazy" width="266" height="Auto" alt="" srcset="https://cdn.prod.website-files.com/665c71122bb2018f6ed3f9c9/66eaaf8660d0ba047f3f2058_screenshot-p-500.png 500w, https://cdn.prod.website-files.com/665c71122bb2018f6ed3f9c9/66eaaf8660d0ba047f3f2058_screenshot.png 626w" sizes="(max-width: 479px) 100vw, (max-width: 991px) 33vw, 266px" class="image-32"> <br>
Get paid in $TENEO Tokens for simply running a node that accesses public social media data. It’s easy, passive, and you earn from the value you contribute.



## 💡 How To SignUp (Register)

- **No Need Download the Extension you can register using script**
![alt text](image.png)


## 🚨 Attention Before Running Teneo Cli Version

I am not `responsible` for the possibility of an account being `banned`, due to running node in the CLI, because Officially `Teneo Node Beta` does not provide an option for the CLI version, only with the Chrome extension.
but `I think` there is no reason to ban the account, because this is not cheating, I didn't change anything in the script (Heartbeats 15 minutes, maximum teneo points 25, maximum points per day 2400)

## 📎 Teneo Node cli version Script features

- Register
- Login
- Running Node
- AutoLogin
- AutoReconnect

![alt text](image-2.png)

## 📌  ScreenShot Running With Javascript/NodeJs

![alt text](image-1.png)

## RUNNING (CLI Version)
- Clone Repository
```bash
git clone https://github.com/raymundedgar/teneo-bot.git
cd teneo-bot
```
- Install Dependency
```bash
npm install
```
- Run the script
```bash
node main.js
```

## RUNNING (Extension Version)
- Install [Teneo chrome extension](https://chromewebstore.google.com/detail/teneo-community-node/emcclcoaglgcpoognfiggmhnhgabppkm)
- Use my referral code to get 2,500 points: 6M9Bz
- Create a new browser tab and paste this
```bash
chrome-extension://emcclcoaglgcpoognfiggmhnhgabppkm/index.html
```
- Open developer console by clicking F12 or right click the page > Inspect element
- Under 'Console' tab, paste this code
```bash
(function checkAndClickButton() {
    const interval = 10000; // 10 seconds
    const buttonClass = "bg-blue-teneo";
    const targetText = "Connect Node";

    setInterval(() => {
        const button = document.querySelector(`.${buttonClass}`);
        if (button && button.textContent.trim() === targetText) {
            button.click();
            console.log(`Clicked the button with text "${targetText}"`);
        }
    }, interval);
})();
```
