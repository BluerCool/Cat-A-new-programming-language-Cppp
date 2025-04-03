# Cat Programming Language / Cat 编程语言

**A Modern Evolution of C++**  
**C++的现代化演进**

---

## 🎯 Project Vision 项目愿景
Cat is designed to enhance C++ with three core improvements:  
Cat旨在通过三大核心改进提升C++：
- **Smart Memory Guardian** 智能内存卫士  
  Automatic memory management without garbage collection  
  无需垃圾回收的自动化内存管理
- **Error Handling Revolution** 错误处理革新  
  Simplified `try-catch` syntax with context-aware exceptions  
  支持上下文感知异常的简化`try-catch`语法
- **Next-Gen Standard Library** 新一代标准库  
---

## 👥 Contribution Guide 贡献指南

### 📝 PR Requirements PR要求
- **Mandatory 必需项**  
  ✅ Clear feature description 清晰功能描述  
  ✅ Unit tests covering edge cases 包含边界条件的单元测试  
  ![Test Coverage Badge](https://img.shields.io/badge/coverage-100%25-brightgreen)
  
- **Conditional 条件项**  
  📄 Update [SPEC.md] if modifying language syntax  
  修改语法时需更新[SPEC.md]规范文档

### ⏰ Review Cycle 审核周期
- **Regular Schedule**:  
  🗓️ **Weekends & Holidays** (UTC+8)
  常规审核：每周周末及节假日集中处理
  
- **Emergency Fixes**:  
  🔔 Add `[URGENT]` in PR title for expedited review  
  紧急修复：PR标题添加`[URGENT]`可加速审核

---

## 🚀 Getting Started 快速开始
```bash
# Clone with submodules 克隆含子模块
git clone --recursive https://github.com/your-repo/cat-lang

# Build with parallel compilation 并行编译
# Note: Adjust -jN based on your CPU cores
# 注意：根据CPU核心数调整-jN参数
mkdir build && cd build
cmake -DCMAKE_CXX_STANDARD=23 ..
make -j$(nproc)  # 使用所有CPU核心加速编译

# For first-time contributors: 
# 首次贡献者建议：
# make -j2  # 更稳定的调试编译

