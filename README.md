1、react
2、事件、条件渲染、列表渲染   基础用法
3、refs及 React API详解
4、异步过程使用单例的 event 对象
5、模版语法及babel编译配置
6、react.js 组件化及生命周期
7、create-react-app cli 的使用
8、函数组件和class 组件
9、受控组件和非受控组件
10、immutable 、 immutable-js 、immer






1、 react 声明式设计 对应是命令式设计  
    声明式设计 只需要告诉机器我想要什么东西 具体由他自己实现   侧重结果
    命令式  一步一步告诉他怎么做       侧重过程
2、 高效  虚拟dom    vue 虚拟dom 参考react 
    找到需要更新的最小单元

### 与vue相比
## 相同：

     - 虚拟dom
     - 基于组件的开发模式
     - 专注于试图
#### 不同:

    - vue 数据流 mvvm
    - react   ui = render（date）
        - props 只读属性  父子流向
        - state 由setState 控制
    - vue 侧重于 编译时      react 侧重于 运行时
        - vue 中的 template + jsx    v-if v-for   vue 3.x  中按需编译 静态标记
        - 运行时 diff
    - react 侧重运行
        - jsx 编译成js 最终解释成 creatElement
        虚拟dom 解决 跨平台 可以做一些跨端的应用
    数据是否可变
        - React 数据不可变  immutable     不能使用---this.state.xx = xxx   修改数据。  需要用  this.setState()  修改数据
        - vue 数据可变  mutable  响应式：vue 2： object.defineproperty 以及 vue 3：proxy 
    语法不同
        - vue  SFC template js css
        - react  jsx
    





#### JSX

     
 




