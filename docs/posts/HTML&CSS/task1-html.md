# Lesson

+ [task1-零基础HTML编码](http://ife.baidu.com/course/detail/id/90)

# Requirements

+ 理解语义化，合理地使用HTML标签来构建页面
+ 尽可能多地尝试更多的HTML标签

# Task
+ [task1 previev](https://codepen.io/zhongshanxian/pen/gmbxbp)
+ [task1 source code](https://github.com/zhongshanxian/Baidu-IFE-2017/blob/master/codes/HTML%26CSS/task1-html.html)

### html
```html
<h1>古风</h1>
<!--导航链接-->
  <nav>
    <ul>
      <li><a href="#part1">古风兴起</a></li>
      <li><a href="#part2">古风图片</a></li>
      <li><a href="#part3">表格</a></li>
      <li><a href="#part4">注册</a></li>
    </ul>
  </nav>
<!--文章-->
  <article>
    <h3 id="part1">古风兴起</h3>
    <p>作者：xian  2017-02-25</p>
    <p>随着人们对古代越来越清醒的认识，古代的文学、思想、习俗等等已经不再是秘密；现代社会的利己、金钱观念等不良思想、<br>观念，也冲击着人们的心灵，使人们陷入迷惘与愁苦当中。因此，有一部分人就利用古代的思想文化、<br>诗词歌赋等等，提升自己的精神境界，在这个物欲横流的世界中保持自己的本真。<br>这里，我只想说一下古风的<strong>图片和服装</strong>。我在微博上关注了一位专画古风图片的大大：<a href="http://weibo.com/u/1789124483?topnav=1&wvr=6&topsug=1&is_hot=1" target="_blank">伊吹鸡腿子</a>，也关注了一个萌萌的妹子：<a href="http://weibo.com/u/2831094660?topnav=1&wvr=6&topsug=1" target="_blank">小豆蔻儿</a>，她是一个非常喜欢汉服的软妹。</p>
    <p>汉服的款式</p>
      <img src="http://ww4.sinaimg.cn/bmiddle/a163c684jw1e6b46lo3kwj20m8123gpc.jpg">
    <ul>
      <li>袄裙</li>
      <li>褙子</li>
      <li>道袍</li>
      <li>对襟半臂襦裙</li>
      <li>交领襦裙</li>
      <li>齐胸襦裙</li>
      <li>曲裾</li>
      <li>裋褐</li>
      <li>圆领袍</li>
      <li>坦领半臂襦裙</li>
      <li>直裾</li>
      <li>朱子深衣</li>
    </ul>
  </article>
  <section id="part2">
    <h3>古风图片</h3>
    <figure>
      <p>最适合做手机壁纸的图片</p>
      <img src="http://wx4.sinaimg.cn/mw1024/6aa3df83gy1fcgpc1mws2j20gj0rktee.jpg">
      <p>很真实的图片</p>
      <img src="http://wx1.sinaimg.cn/mw1024/6aa3df83gy1fbv250n5d9j20gj0rk123.jpg">
      <p>我保证这不是黄图</p>
      <img src="http://ww4.sinaimg.cn/mw1024/6aa3df83gw1fbg6zx9co8j20fr0q9acd.jpg">
      <p>每一张图片都美到窒息</p>
      <img src="http://ww2.sinaimg.cn/mw1024/6aa3df83gw1fazf8gi60jj20gj0rkthp.jpg">
      <p>这张是上上张图片的正脸</p>
      <img src="http://ww1.sinaimg.cn/mw1024/6aa3df83gw1faxizn239jj20gj0rk0xo.jpg">
    </figure>
  </section>
  <section id="part3">
    <h3>表格</h3>
    <p>作者：xian 2017-02-25</p>
    <ol>
      <li>Au</li>
      <li>Ag</li>
      <li>Cu</li>
    </ol>
    <p>零食清单</p>
      <table border="1">
        <tr>
          <th>品种</th>
          <th>单价</th>
          <th>数量</th>
          <th>总价</th>
        </tr>
        <tr>
          <td>章鱼烧</td>
          <td>￥10</td>
          <td>1</td>
          <td>￥10</td>
        </tr>
        <tr>
          <td>烤玉米</td>
          <td>￥8</td>
          <td>2</td>
          <td>￥16</td>
        </tr>
        <tr>
          <td>鸡排</td>
          <td>￥10</td>
          <td>1</td>
          <td>￥10</td>
        </tr>
        <tr>
          <td>热珍珠奶茶</td>
          <td>￥15</td>
          <td>1</td>
          <td>￥15</td>
        </tr>   
        <tr>
          <td>合计</td>
          <td colspan="3">￥51</tr>
        </tr>
      </table>
  </section>
<!--侧边栏-->
  <aside id="part4">
    <h3>注册</h3>
    <p>新用户请注册，并按照提示完成填写资料</p>
    <form>
      <span>请输入邮箱地址：</span>
        <input type="email">
      <p>请按照邮箱格式填写：@***.com</p>
      <span>请输入密码：</span>
        <input type="password"> <span>
      请重复输入密码：</span>
        <input type="password">
      <p>密码请为6-16位英文数字</p>
      <p>性别：</p>
        <input type="radio" checked>男 
        <input type="radio">女 
      <p>城市：</p>
        <select>
          <option>北京</option>
          <option>广州</option>
          <option>东莞</option>
        </select>
      <p>爱好：</p>
        <input type="checkbox">运动 
        <input type="checkbox">艺术 
        <input type="checkbox">科学
      <p>个人描述：</p>
        <textarea placeholder="输入您的个人描述"></textarea>
        <input type="submit" value="确认提交">
    </form>
  </aside>
<!--页脚-->
  <footer>
    <p style="font-size:10px;">版权所有&copy;xian
      <script type="text/javascript">
        document.write(new Date().getFullYear());
      </script>
    </p>
  </footer>
```

# Notes
+ [RUNOOB.COM(HTML5)](http://www.runoob.com/html/html5-intro.html)
+ 页脚代码

```html
  <footer>
    <p style="font-size:10px;">版权所有&copy;xian
      <script type="text/javascript">
        document.write(new Date().getFullYear());
      </script>
    </p>
  </footer>
```