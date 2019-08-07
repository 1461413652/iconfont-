# react-native-vector-icons的使用
react-native-vector-icons的使用
前面的安装配置过程，参考https://www.jianshu.com/p/332198bf46a7
由于文章中使用python2.7的fonttools一直不出效果。但每次添加字体图标都手动去对应其iconName和code又非常麻烦。索性就用node来处理。
拷贝到生成的icomoon文件夹下，执行命名node readIcomoon.js

拷贝失败请将iconmmon.ttf拷贝至readIcomoon.js同级执行
运行无效请清除缓存重试npm start -- --reset-cache
