# Java_Learning
记录Java学习过程
计划周期约**4-6个月**（可根据每天学习时间灵活调整）。

---

### **阶段1：编程基础与Java入门（1-1.5个月）**
**目标**：掌握编程基础逻辑和Java核心语法。  
#### **1.1 计算机基础**
- **二进制/数据类型**：理解基本存储单位（bit/byte）。  
- **基础算法逻辑**：顺序、分支、循环（用流程图辅助理解）。  
- **环境搭建**：安装JDK、配置环境变量、使用IDE（IntelliJ IDEA或Eclipse）。  
**资源**：  
- 视频：[B站《计算机科学速成课》](https://www.bilibili.com/video/BV1EW411u7th)  
- 工具：[Oracle JDK下载](https://www.oracle.com/java/technologies/javase-downloads.html)  

#### **1.2 Java基础语法**
- **核心内容**：  
  - 变量与数据类型（`int`, `String`, `boolean`）  
  - 运算符（算术、逻辑、三元）  
  - 流程控制（`if-else`, `for`, `while`, `switch`）  
  - 数组与基础算法（冒泡排序、二分查找）  
**行动**：  
- 完成《Head First Java》前6章练习。  
- 每日在[LeetCode](https://leetcode.com/)或[牛客网](https://www.nowcoder.com/)刷5道简单题（如「斐波那契数列」）。  

#### **1.3 面向对象（OOP）基础**
- **四大特性**：封装、继承、多态、抽象。  
- **类与对象**：`class`定义、构造方法、`this`关键字。  
- **实战**：实现一个「学生管理系统」（控制台版）。  
**常见坑点**：  
- 混淆`==`和`equals()`的区别。  
- 不理解`static`关键字的作用。  

---

### **阶段2：Java进阶与工具链（1.5-2个月）**
**目标**：掌握Java核心API和开发工具。  
#### **2.1 Java核心API**
- **集合框架**：`ArrayList`、`HashMap`、迭代器（重点掌握底层原理）。  
- **异常处理**：`try-catch-finally`、自定义异常。  
- **IO流**：`FileInputStream`、`BufferedReader`（实现文件复制）。  
**面试高频考点**：  
- `HashMap`的扩容机制。  
- `ArrayList` vs `LinkedList`区别。  

#### **2.2 常用工具**
- **Maven**：依赖管理、`pom.xml`配置。  
- **Git**：`clone`/`commit`/`push`、解决冲突。  
- **JUnit**：单元测试编写。  
**行动**：  
- 在GitHub创建一个仓库，每天提交代码（哪怕只有一行注释）。  

#### **2.3 多线程与网络编程**
- **多线程基础**：`Thread`类、`Runnable`接口、`synchronized`。  
- **TCP/UDP**：用`Socket`实现简易聊天室。  
**注意**：先理解概念，不必深究底层（如JVM内存模型）。  

---

### **阶段3：数据库与框架（1.5-2个月）**
**目标**：掌握企业开发必备技术栈。  
#### **3.1 数据库**
- **SQL基础**：`SELECT`/`INSERT`/`UPDATE`/`DELETE`。  
- **MySQL**：安装、索引优化、事务ACID特性。  
- **JDBC**：`Connection`/`PreparedStatement`增删改查。  
**实战**：  
- 设计「图书管理系统」数据库表（至少3张表关联）。  

#### **3.2 JavaWeb基础**
- **Servlet**：`doGet`/`doPost`方法处理请求。  
- **JSP**（了解即可）：EL表达式、JSTL标签。  
- **HTTP协议**：GET/POST区别、状态码（404/500）。  

#### **3.3 Spring框架**
- **Spring Boot**：用`@RestController`开发RESTful API。  
- **MyBatis**：`mapper.xml`配置、动态SQL。  
**快速入门**：  
- 使用[Spring Initializr](https://start.spring.io/)生成一个带`Web`/`MyBatis`依赖的项目。  

---

### **阶段4：项目实战与求职（1-2个月）**
**目标**：积累项目经验，准备面试。  
#### **4.1 完整项目**
- **推荐项目**：  
  - 电商秒杀系统（Spring Boot + Redis）  
  - 博客平台（Spring Boot + Vue前后端分离）  
  - 在线考试系统（Spring Cloud微服务）  
**关键点**：  
- 至少包含「用户认证」和「数据库交互」模块。  
- 部署到云服务器（阿里云/腾讯云学生机约10元/月）。  

#### **4.2 面试准备**
- **八股文**：  
  - JVM内存结构  
  - HashMap vs ConcurrentHashMap  
  - Spring事务传播机制  
- **算法题**：LeetCode热题100（重点：链表、二叉树）。  
- **简历优化**：用STAR法则描述项目（如“使用Redis缓存QPS提升50%”）。  

#### **4.3 持续学习**
- **源码阅读**：从`ArrayList`开始看JDK源码。  
- **新技术**：了解Quarkus、GraalVM等新兴技术。  

---

### **学习资源推荐**
| 类型 | 资源 | 备注 |
|------|------|------|
| 书籍 | 《Java核心技术卷1》 | 重点读前8章 |
| 视频 | [尚硅谷Java零基础](https://www.bilibili.com/video/BV1PY411e7J6) | 适合纯小白 |
| 刷题 | 牛客网《Java专项练习》 | 高频面试题 |
| 社区 | [Stack Overflow](https://stackoverflow.com/) | 英文问答 |

---

### **关键建议**
1. **代码量优先**：前3个月至少写2万行代码（可通过重复练习积累）。  
2. **避坑指南**：  
   - 不要纠结于「GUI编程」（如Swing）。  
   - 先学Spring Boot而非SSM（减少配置负担）。  
3. **时间分配**：  
   ```mermaid
   pie
       title 每日学习时间分配（建议）
       "编码实践" : 50
       "理论学习" : 30
       "算法/面试题" : 20
   ```

坚持完成计划后，可达到**Java初级开发工程师**水平（薪资范围：6-12K/月，视地区而定）。如果需要某个阶段的详细资料包（如Spring Boot实战项目模板），可以告诉我！ 💻
