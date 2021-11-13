-----

# 课程：数字媒体技术

> - 记录人：曾洁欣
> - 时间：2021-11-10
> - week11  

-----

## 本周任务

>1. Typora的介绍
>
>   > [typora官网](https://typora.io/)
>   >
>   > [typora进阶](https://www.bilibili.com/video/BV12T4y1g7se?from=search&seid=1073155979321395137&spm_id_from=333.337.0.0)
>
>   1.代码块
>
>   ```css
>   gitGraph:
>   options
>   {
>       "nodeSpacing": 150,
>       "nodeRadius": 10
>   }
>   end
>   commit
>   branch newbranch
>   checkout newbranch
>   commit
>   commit
>   checkout master
>   commit
>   commit
>   merge newbranch
>   body{
>       margin:0
>   }
>   ```
>
>   2. 流程图
>
>      > ```mermaid
>      > graph TB
>      > A[Apple]--->B{Boy}
>      > B.->C(Cat)
>      > C==喵==>D
>      > style A  fill:#2ff,fill-opacity:0.1,stroke:#faa,stroke-width:3px
>      > style D stroke:#000.stroke-width:8px
>      > ```
>
>      3. 甘特图
>
>         ```mermaid
>         gantt
>         dateFormat YYYY-MM-DD
>         TITLE 产品计划表
>         section 阶段一
>         产品原型图:2021-11-10,2021-11-20
>         section 阶段二
>         产品交互界面:2021-12-22,2022-01-10
>         section 阶段三
>         前端开发:2021-12-13,2022-01-10
>         ```
>
>         ```mermaid
>         gantt         
>         dateFormat  YYYY-MM-DD   
>         title 使用mermaid语言定制甘特图
>         section 任务1
>                已完成的任务:done,des1,2014-01-06,2014-01-08
>                正在进行的任务:active,des2,2014-01-09, 3d
>                待完成任务1:des3, after des2,5d
>                待完成任务2:des4, after des3, 5d
>         section 关键任务
>                已完成的关键任务: crit,done,2014-01-06,24h
>                已完成的关键任务2:crit,done,after des1, 2d
>                正在进行的关键任务:crit,active, 3d
>                待完成的关键任务:crit,5d
>                待完成任务:2d
>                待完成任务2:1d
>         section 文档编写
>                描述甘特图语法:active, a1,after des1, 3d
>                完成甘特图实例1:after a1,20h
>                完成甘特图实例2:doc1,after a1,48h
>         ```
>
>         
>
>         

#### 文章参考文献

> - [markdown流程图详解](https://blog.csdn.net/suoxd123/article/details/84992282)
> - [许智超gitee](https://gitee.com/xzhichao/digital-media-technology/blob/master/week05/week11.md#https://blog.csdn.net/suoxd123/article/details/84992282)

