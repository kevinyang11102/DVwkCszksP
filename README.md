# 【Java计算机毕业设计分享】在线考试系统

## 前言

本仓库为基于Java语言的在线考试系统毕业设计项目。通过这个项目，我希望能够分享我的开发经验，并为有需要的朋友提供实战项目的参考。本系统使用Spring Boot框架，前端技术包括JS、Vue和CSS3。数据库采用MySQL 5.7/8.0，开发工具为IDEA或Eclipse。

## 内容介绍

在线考试系统是一个面向教育行业的在线测试平台，教师可以通过该系统发布试题，学生可以在线参加考试。系统主要包括以下功能：试题管理、考试管理、学生考试、成绩查询等。通过这个项目，您可以学习到如何使用Java开发一个完整的Web应用程序，包括前端页面设计、后端逻辑处理以及数据库操作等。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为系统中试题管理部分的核心代码：

```java
@RestController
@RequestMapping("/question")
public class QuestionController {

    @Autowired
    private QuestionService questionService;

    @PostMapping("/add")
    public ResponseEntity<?> addQuestion(@RequestBody Question question) {
        questionService.addQuestion(question);
        return ResponseEntity.ok("试题添加成功！");
    }

    @GetMapping("/list")
    public ResponseEntity<List<Question>> getQuestionList() {
        List<Question> questionList = questionService.getQuestionList();
        return ResponseEntity.ok(questionList);
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/327471/20/4979/89870/689f03e9Ff2632b7e/75d3ace452b0b24e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/307367/5/26586/19322/689f03c2F76e45405/82b9b959c817e7da.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326915/30/4934/44436/689f03c3Faf62fd9a/d46e59e195a1ce63.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/314921/15/26478/26677/689f03c4Fe8041578/e57d9bbe016a32a7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/311765/20/26652/43316/689f03c4Ffc723e88/89482ee6fe04823f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/319730/8/25558/18080/689f03c5F587d76b8/77339632286dce45.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/302156/27/23597/43271/689f03c8F6aa8b580/cfbd1d76dbe0665b.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/303787/7/26937/32164/689f03d5Ff2d96e73/f6cae50464ccbb61.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/314550/38/26625/17920/689f03d6F331ddca7/9288f81a1929f35f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/307793/35/26739/48653/689f03d7F65f54c5f/86e958de74e382ab.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
