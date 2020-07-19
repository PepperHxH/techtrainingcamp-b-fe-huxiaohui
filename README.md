# techtrainingcamp-b-fe

## 【玩转前端】大作业
1. 基础功能：实现搜索框、搜索结果页列表
2. 技术简介：
    - 框架：React
    - UI库：Antd

3. 实现功能：
    - 搜索框：支持用户手动输入词并基于ajax实现推荐词功能
    - 结果页：通过ajax获取搜索结果数据完成列表渲染

4. 分页：
由于搜索结果总条数过多，所以设置分页功能，每页最多展示10条数据，换页时再次调用接口获取当前页的数据

5. 缓存：
实现一次搜索后，若刷新页面会重新回到原始界面，需要用户重新手动输入词，这会很不方便
所以借助sessionStorage，每获取一次信息，就将结果缓存在浏览器中，这样即使刷新了页面信息也不会丢失