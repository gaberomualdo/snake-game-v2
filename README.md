# [Snake Game](https://xtrp.github.io/snakegame/)

A super simple snake game in the browser.

## The Pastable DataURL Version

I've written a very small data URL version of snake below. **Just copy &amp; paste the below text into your browser to get snake!**

```
data:text/html,%3Cdiv%20id%3Dg%3E%3C%2Fdiv%3E%3Cstyle%3E%2A%7Bmargin%3A0%3Bpadding%3A0%7D%23g%7Bbackground%3A%23000%3Bwidth%3A100vh%3Bheight%3A100vh%7D%23g%20div%7Bwidth%3A5vh%3Bheight%3A5vh%3Bposition%3Aabsolute%3Bbox-sizing%3Aborder-box%3Bborder%3A%202px%20solid%20%23000%3Bbackground%3A%230f0%7D%23g%20div%5Bn%5D%7Bbackground%3A%23f00%7D%3C%2Fstyle%3E%3Cscript%3Epx%3Dpy%3D9%3Bz%3Dax%3Day%3Dxv%3Dyv%3D0%3Bt%3D%5B%5D%3Bd%3Ddocument%3Bg%3Dd.getElementById%28%22g%22%29%3Bd.onkeydown%3D%28e%29%3D%3E%7Bk%3De.keyCode%3Bif%28k%3D%3D37%26%26xv%21%3D1%29%7Bxv%3D-1%3Byv%3D0%7Dif%28k%3D%3D39%26%26xv%21%3D-1%29%7Bxv%3D1%3Byv%3D0%7Dif%28k%3D%3D38%26%26yv%21%3D1%29%7Byv%3D-1%3Bxv%3D0%7Dif%28k%3D%3D40%26%26yv%21%3D-1%29%7Byv%3D1%3Bxv%3D0%7D%7D%3Bb%3DsetInterval%28%28%29%3D%3E%7Bt.push%28%7Bx%3Apx%2Cy%3Apy%7D%29%3Bpx%2B%3Dxv%3Bpy%2B%3Dyv%3Bif%28px%3D%3D-1%29%7Bpx%3D19%7Dif%28px%3D%3D20%29%7Bpx%3D0%7Dif%28py%3D%3D-1%29%7Bpy%3D19%7Dif%28py%3D%3D20%29%7Bpy%3D0%7Dif%28z%29%7Balert%28%22gameover%22%29%3BclearInterval%28b%29%3B%7Dc%3D%28l%2Ct%2Cn%29%3D%3E%60%3Cdiv%20%24%7Bn%7D%20style%3D%27left%3A%24%7Bl%2A5%7Dvh%3Btop%3A%24%7Bt%2A5%7Dvh%3B%27%3E%3C%2Fdiv%3E%60%3Bg.innerHTML%3Dc%28ax%2Cay%2C%27n%27%29%3Bm%3D%28q%2Cw%2Ce%2Cr%29%3D%3Eq%3D%3De%26%26w%3D%3Dr%3Bt.forEach%28i%3D%3E%7Bg.innerHTML%2B%3Dc%28i.x%2Ci.y%29%3Bif%28m%28i.x%2Ci.y%2Cpx%2Cpy%29%26%26xv%2Byv%21%3D0%29%20z%3D1%3B%7D%29%3Bif%28m%28ax%2Cay%2Cpx%2Cpy%29%29%7Br%3D%28%29%3D%3EMath.floor%28Math.random%28%29%2A20%29%3Bax%3Dr%28%29%3Bay%3Dr%28%29%3B%7Delse%7Bt.shift%28%29%3B%7D%7D%2C100%29%3B%3C%2Fscript%3E
```

## The QR Code Version

Using the data URL version, I've created a QR Code version. **This version does not work on mobile.** Simply scan the QR code on your laptop or desktop device, and play the game in your browser!

![Snake QR Code](snakeinaqrcode.png)
