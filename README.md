# Genshin Impact Check-In Helper

[Daily Check-In](https://webstatic-sea.mihoyo.com/ys/event/signin-sea/index.html?act_id=e202102251931481&lang=en-us)

[Original Repository (defunct)](https://github.com/y1ndan/genshin-impact-helper)

[TakaGG fork](https://github.com/takagg/genshin-impact-helper)

[Napkatti fork](https://github.com/napkatti/genshin-impact-helper/)

## Usage

1. Fork this repository to your own account.
2. Go to the Daily Check-In event website https://webstatic-sea.mihoyo.com/ys/event/signin-sea/index.html?act_id=e202102251931481&lang=en-us
3. Log in with your MiHoYo/Genshin Impact account.
4. Open the developer tools on your web browser (F12 on firefox/chrome)
5. Click on the "Console" tab
6. Type in `document.cookie` in the console
7. Copy the text output from the console
8. Go back to your GitHub repository page, Click "Settings" on the top right
9. Click "Secrets" on the bottom left
10. Click "New Repository Secret" on the top right
11. In the "Name" box type in `OS_COOKIE`
12. In the "Value" box paste the text you copied earlier
    - Remove any quotation marks "" at the front or end of the text 
    - Go back to the MiHoYo event website. You may close the tab but do not click the "Log Out" button because it may cause your cookie to expire.
    - **IF YOU WANT TO CHECK-IN MULTIPLE GENSHIN ACCOUNTS:**
    1. Paste your first cookie into the Value box on GitHub, but do not click "Add Secret" yet.
    2. Open a new private browsing / Incognito window
    3. Go to the MiHoYo event website on your new browser instance, and log in with your second account
    4. Copy the `document.cookie` as before
    5. Go back to the GitHub page, and type a hash `#` at the end of your first cookie
    6. Paste your second cookie immediately after the `#` and remove the quotation marks "" if needed
13. Click "Add Secret"
14. Click the "Actions" tab in the top middle of the page
15. Click "I understand my workflows"
16. Click "Genshin Impact Helper Global"
17. Click "Enable workflows"
18. Click "Run workflows"
19. You should see a yellow circle next to the job. Wait for it to become a green check mark.
