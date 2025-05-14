# NJU 软件系统设计 2025 Spring 设计模式部分实验

![Java](https://img.shields.io/badge/language-Java-blue.svg)
![Maven](https://img.shields.io/badge/build-Maven-orange.svg)
![JUnit](https://img.shields.io/badge/testing-JUnit-green.svg)

本项目是南京大学软件学院2025年春季学期"软件系统设计"课程的设计模式实验部分，包含三个迭代开发的实验任务。

## 项目简介

本项目通过三个迭代实验，逐步实现为Java代码自动生成类图的系统 **JClassDiagram**，并在此基础上实现基于类图的程序分析器：

1. **迭代一**：基础类图分析与生成
2. **迭代二**：更多类图元素与基于类图的分析器
3. **迭代三**：多文件支持和命令行工具实现

## 快速开始

### 环境要求

- Java JDK 17
- Maven 3.6+
- (可选) Python 3.8+ (用于打包脚本)

### 安装与构建

```bash
git clone https://github.com/your-repo/nju-ssd-2025-design-pattern-lab.git
cd nju-ssd-2025s-design-patterns-lab
mvn install
```

### 运行测试

```bash
mvn test
```

## 项目结构

```
.
├── docs/                   # 实验文档模板
│   ├── iter1_template.md   # 迭代一文档模板
│   ├── iter2_template.md   # 迭代二文档模板
│   └── iter3_template.md   # 迭代三文档模板
├── src/
│   ├── main/java/          # 主代码目录
│   │   ├── diagram/        # 类图分析核心模块
│   │   └── command/        # 命令行接口
│   └── test/java/          # 单元测试(按实验迭代组织)
│       ├── lab1/           # 迭代一测试
│       ├── lab2/           # 迭代二测试
│       └── lab3/           # 迭代三测试
├── package.sh              # Linux打包脚本
├── package.py              # 跨平台打包脚本
└── pom.xml                 # Maven配置文件
```

## 实验提交

### 生成提交包

#### Linux/macOS系统

```bash
chmod +x package.sh
./package.sh
```

#### Windows/跨平台

```bash
python package.py
```

## 小组协作说明

本项目为4人小组作业，请注意：

1. 使用规范的版本控制流程
2. 在提供的模板中记录设计决策
3. 保持清晰的提交历史
