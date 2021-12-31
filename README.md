# bookmarklet_test

- [Bookmarklet(ブックマークレット)の作り方 · Logical Dice 技術ブログ](https://blog2.logical-dice.com/posts/2020/07/15/howto-make-bookmarklet/)
- [uglify-js - npm](https://www.npmjs.com/package/uglify-js)


```
javascript:(()=>{const e=document.title,t=document.createElement("textarea");t.textContent=e,document.body.appendChild(t),t.select(),document.execCommand("copy"),document.body.removeChild(t),console.log(`Copyed this website title "${e}"`)})();
```

## サンプルスクリプト
```
javascript:(()=>{const e=document.title,s=document.createElement("script");s.src="https://cti1650.github.io/bookmarklet_test/src/sample.js",document.body.appendChild(s),document.body.removeChild(s),console.log(`Copyed this website title "${e}"`)})();
```