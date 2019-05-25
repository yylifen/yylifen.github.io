<style>html, body { height: 100%; width: 100%;margin: 0; background: #000; color: #fff}a {font-weight:700; color: #fff; border-bottom: 1px solid #da1b60!important;}a:hover { color: transparent; background: linear-gradient(to right,#ff8a00,#da1b60);-webkit-background-clip: text; border-bottom: 1px solid #fff!important;}</style>
<style>#bg { position: absolute; left: 0; top: 0;}</style>
<script src="https://cdnjs.cloudflare.com/ajax/libs/css-doodle/0.4.9/css-doodle.min.js"></script>
<div id="bg">
    <css-doodle>
    :doodle {
        @grid: 10 / 5vmin;
        perspective: 5vmin;
        transform: scale(.6) translateY(-50%);
    }
    :container {
        transform-origin: center;
        transform-style: preserve-3d;
    }
    @size: 10vmin;
    :after, :before {
        content: '*';
    font-size: 250%;
        @size: 50%;
        transform-style: preserve-3d;
        color: @p(#00b8a9, #f8f3d4, #f6416c, #ffde7d);
        animation: move @r(14s, 16s, 1.1) linear infinite;
        animation-delay: calc(@i() * -1s);
    } 
    @keyframes sway {
        0% { transform: rotateX(45deg) rotate(45deg) rotateZ(0); }
        100% { transform: rotateX(45deg) rotate(45deg) rotateZ(1turn); }
    }
    @keyframes move {
        0% { transform: scale(0) rotateZ(45deg) translateZ(0vmin); opacity: 0; }
        20%, 90% { opacity: 1; }
        50% { transform: scale(1) rotateZ(45deg) translateZ(-20vmin); }
        100% { transform: scale(@r(1, 2, .1)) rotateZ(45deg) translateZ(100vmin); opacity: 0; }
    }
    </css-doodle>
</div>



**yylifen's homepage is developing...**

### 可阅读的翻译书籍

+ 【2019-03-06】[图像优化自动化](https://yylifen.github.io/images.guide/)

+ 【2019-05-05】[前端开发者手册2019](https://yylifen.github.io/front-end-handbook-2019/)

+ 【2019-05-22】[色彩：从十六进制编码到眼球](https://yylifen.github.io/color-from-hexcodes-to-eyeballs/)

### 可阅读的翻译文章

+ 【2019-03-24】[如何说服你的团队采用CSS Grid](https://yylifen.github.io/sundries-trans/other/how-to-convince-your-team-to-adopt-grid/ch.html)


### 即将开源作品

+ 【2019-06-？】[MIX CLI](https://yylifen.github.io/mix-cli/)(开发中……)


### 过去现在未来

+ 【1993-06至2006-02】空白。

+ 【2006-02至2010-06】当不了作家，却放不下键盘，码代码的乐趣也是这个时候发现的吧？！

+ 【2010-09至2014-06】不喜欢应试教育却有想当个学生的学渣，去不了设计学院只能读个计算机专业。

+ 【2015-03至20??-??] [机缘巧合成了一名前端，但也不会戒了爪哇咖啡的...](./bio/about-me.md)

+ 【20??-??至20??-??] 退休了，就做个自由的[素人](https://zh.wiktionary.org/zh-hans/%E7%B4%A0%E4%BA%BA)，多出去走走，看看展...

+ 【20??-??至20??-??] 走不动了，就做个独立的闲人，读读诗词，写写字...

……

