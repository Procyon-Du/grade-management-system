# 成绩管理系统

## 项目简介

成绩管理系统是一款专为教育机构设计的高效、智能的成绩管理解决方案。系统支持成绩录入与管理、成绩统计分析以及数据导出与报告等核心功能，帮助教师和教育管理者更便捷地处理学生成绩数据。

## 功能特点

1. **成绩录入与管理**
   - 支持批量导入Excel成绩单
   - 提供可视化编辑界面
   - 展示成绩录入界面和导入功能

2. **成绩统计分析**
   - 自动计算平均分、最高分、及格率
   - 生成成绩分布直方图
   - 显示统计图表和分析结果

3. **数据导出与报告**
   - 导出PDF成绩单
   - 生成班级成绩分析报告

## 技术栈

- **前端框架**：原生HTML、CSS、JavaScript
- **UI库**：Tailwind CSS v3
- **图表库**：Chart.js
- **Excel处理**：SheetJS (xlsx)
- **PDF生成**：jsPDF + html2canvas

## 安装与使用

### 本地部署

1. 克隆仓库到本地git clone https://github.com/Procyon-Du/grade-management-system.git
cd grade-management-system
2. 直接在浏览器中打开 `index.html` 文件即可使用

### 生产环境部署

1. 将项目文件上传至Web服务器
2. 确保服务器配置支持静态文件访问
3. 通过浏览器访问服务器域名或IP地址即可

## 目录结构
grade-management-system/
├── index.html                # 主页面
├── README.md                 # 项目说明文档
└── assets/                   # 资源文件夹
    ├── css/                  # CSS文件
    ├── js/                   # JavaScript文件
    └── images/               # 图片资源
## 贡献指南

1.  Fork 仓库
2.  创建你的特性分支 (`git checkout -b feature/your-feature`)
3.  提交你的更改 (`git commit -am 'Add some feature'`)
4.  将分支推送到远程仓库 (`git push origin feature/your-feature`)
5.  提交 Pull Request

## 许可证

本项目采用 MIT 许可证 - 详情见 [LICENSE](LICENSE) 文件

## 联系我们

如果你有任何问题或建议，请通过以下方式联系我们：
- 邮箱：contact@example.com
- 问题追踪：[GitHub Issues](https://github.com/Procyon-Du/grade-management-system/issues)
    