## 仿小米页面文档
### html代码结构
1. “firstbox”的div是小米上到 头部，下到白色边缘的大盒子
    - 内部包含了顶部nav
    - 大轮播banner
2. secondbox的div是小米上到白色底边，下到“手机”版块的大盒子
    - 内部包含一张1226px的横幅广告
    - 手机版块
3. third的div是上到手机版块底部，下到家电版块底部的大盒子
    - 包含家电版块的==所有内容==

### css结构
1. 动态效果全部由css完成
2. 部分动效受限于css做不出来，需要借助js

### 小细节
1. topnav如果使用display：none和block做隐藏显示，transition不生效，需要用opacity：0和1代替display的隐藏显示效果