# some_tools_for_everything
some tools for becoming a better developer(实际上是因为开直播不能总鸽大家所以特意开了个库放直播中写的小脚本,或者是自己觉得有意思的，平时实用性会比较高的脚本。)

### cheat_checkin_out
##### 这个脚本实现的时间大概是两个月以前了
```python
1. app: E-Mobile
2. params: USERNAME PASSWORD 分别写自己的用户名和密码
3. tips: 
    a. 可能不同的公司使用的host不同 BASE_URL = 'http://106.15.179.143:89/client.do' 中的host部分可能需要替换
    b. 打卡的原理就是在请求体中传入正确的经纬度参数
    float: latitude      # 经度
    float: longitude     # 纬度
4. 第一版比较粗糙没有判断周六日和节假日，没有换掉ip，配置文件写死等问题，第二版的时候我会修复这些问题
```

### auto_follow_in_github
##### 大概是一个月前开的坑吧 现在才填上 这个脚本主要实现 关注 拥有50stars以上的repo的大佬
##### 非要说意义在哪里的话 意义就是... 关注起来比较方便一点吧
```python
1. python follow_all_i_want.py
2. 输入你的github账号和密码以及你想要关注的前多少页的人。
```

### broke__jsl_clearance
#### 这个项目主要针对的是破解银保监，破解加速乐的反爬虫机制
#### 不足：
> 1. 正则表达式写的不够高级，现在看上去还比较弱智，目前只是解决了基础问题
> 2. 虽然用了面向对象的写法，但是没有分文件写，看上去还是比较混乱，暂时不想管了
> 3. 因为我没学过js，所以无法通过使用python来实现js脚本相同功能，这是一个短板吧


### jingdong_captcha_break
#### 这个项目也是之前做的 开源出来 破解了京东的滑块验证码
#### 这个东西的意义....
> 1. 你完全可以写一个爬虫，爬取折扣力度大的商品，然后再转手放到闲鱼上面卖，做中间商赚差价
> 2. 我快毕业啦！！！！！！


### bilibili_get_latiao
##### 新开的坑 应该也不难 实现一下之前答应各位的 一个在b站自动签到领辣条的程序
```python 
```


#### 仅供个人学习参考，欢迎发邮件或者加QQ与我交流，如果合适的工作机会，当然也欢迎提供给我




