# Liu Junyan / 刘俊岩

🌐 [English](#english) | [中文](#中文)

---

## English

Hangzhou Dianzi University · B.Eng. student in Intelligent Science and Technology · Class of 2027

Computer Vision / Deep Learning · Object Detection · Instance Segmentation · Model Quantization

📍 Hangzhou, China  ·  📧 1295402349@qq.com  ·  🔎 Open to remote internships and project-based opportunities

### About Me

I am an undergraduate student working on practical computer vision and deep learning systems. My experience covers data annotation and quality assurance, OCR, object detection, instance segmentation, model evaluation, Linux deployment, and post-training quantization. I enjoy building reproducible experiments and measuring real accuracy/latency trade-offs instead of relying on unsupported claims.

### Education

**Hangzhou Dianzi University** · Intelligent Science and Technology (B.Eng.) · 2023.09 – 2027.06

- GPA: 4.327 / 5.0 (Top 25%)
- National Encouragement Scholarship ×2; University Scholarships ×3
- Selected coursework: Deep Learning (5.0/5.0), Machine Vision (4.9/5.0), Machine Learning (4.3/5.0)

### Experience

#### Data Annotation Intern · AI R&D Department · Jiuzhou Culture Media Co., Ltd.
**2026.05 – 2026.08**

- Organized, annotated, and quality-checked multi-source short-drama data; delivered 60,000+ labeled samples.
- Built a YOLO + OCR subtitle detection and recognition pipeline with 99.99% validation-set character recognition accuracy.
- Trained OCR models for printed text and artistic fonts, improving extraction efficiency by approximately 4× versus manual processing.
- Set up Linux training environments, task scheduling, and inference deployment for a reusable annotation–training–evaluation workflow.

### Selected Projects

#### [nanoquant](https://github.com/stenpten/nanoquant) · Post-Training Quantization Toolkit for YOLO Detectors

- Implemented a PyTorch-based PTQ toolkit for weight quantization, activation calibration, layer sensitivity analysis, and goal-driven mixed-precision search.
- Compared calibration methods and measured accuracy/latency end to end across ONNX Runtime and TensorRT backends.
- Built reproducible experiments and 71 automated tests; released under the MIT License.

#### Urban Flooding Image Monitoring System Based on YOLOv11

- Delivered the pipeline from Labelme annotation and data cleaning to model training, evaluation, and a PyQt5 interface.
- Achieved 0.91 mAP@0.5 and 40 FPS inference, with approximately 6% higher accuracy than an R-CNN baseline.

#### Plant H₂O₂ Fluorescence Detection System

- Built datasets containing 500 fluorescence images, 500 leaf regions, and 800+ fluorescence-point instances.
- Compared six YOLO11/YOLO26 variants and optimized augmentation strategies.
- Achieved Box mAP50 0.971 and Mask mAP50 0.907; the project received a provincial third prize in the National College Students Life Science Competition.

### Technical Skills

- **Programming:** Python, C
- **ML/CV:** PyTorch, YOLO11/YOLO26, U-Net, OCR, object detection, instance segmentation
- **Optimization:** Post-training quantization, INT8, mixed precision, model sensitivity analysis, inference benchmarking
- **Engineering:** Linux, Git, Labelme/LabelImg, PyQt5, ONNX Runtime, TensorRT, model deployment
- **Languages:** Chinese (native), English (CET-4; technical reading)

### Additional Experience

- President of a 40-person student association team, leading campus support initiatives.
- International visiting student at Cyprus University of Technology; completed English-taught coursework and cross-cultural collaboration.

### Contact

- Email: 1295402349@qq.com
- GitHub: https://github.com/stenpten
- Open to: remote computer vision, Python/PyTorch, AI evaluation, data quality, OCR, model optimization, and inference-related internships or project work.

> Detection, quantization, and honest benchmarks. 📉⚡

---

## 中文

杭州电子科技大学 · 智能科学与技术（2027 届本科）

计算机视觉 / 算法方向 · 目标检测 · 实例分割 · 模型量化

📍 中国杭州  ·  📧 1295402349@qq.com  ·  🔎 正在寻找远程实习与项目制机会

### 关于我

我是一名专注于计算机视觉与深度学习应用的本科生，具备数据标注与质检、OCR、目标检测、实例分割、模型评估、Linux 部署和训练后量化经验。我重视可复现实验，以及真实的精度与延迟测量。

### 教育背景

**杭州电子科技大学** · 智能科学与技术（本科） · 2023.09 – 2027.06

- GPA 4.327/5（专业前 25%）
- 国家励志奖学金 ×2、校二等奖学金 ×2、校三等奖学金 ×1
- 核心课程：深度学习（5.0/5.0）、机器视觉（4.9/5.0）、机器学习（4.3/5.0）

### 实习经历

#### 九州文化传媒有限公司 · AI 产研部门 · 数据标注实习生
**2026.05 – 2026.08**

- 主导短剧多源数据整理、标注与质检，搭建标准化标注流程，累计交付数据 6 万+ 条。
- 基于 YOLO + OCR 构建字幕区域检测与自动提取识别流水线，验证集字符识别准确率达 99.99%。
- 训练覆盖印刷体、艺术字等复杂场景的 OCR 模型，相较纯人工提取效率提升约 4 倍。
- 基于 Linux 完成训练环境搭建、任务调度与推理部署，沉淀“标注—训练—评估”可复用流水线。

### 项目经历

#### [nanoquant](https://github.com/stenpten/nanoquant) · YOLO 目标检测模型训练后量化工具库 · 独立开发

- 从零实现 PyTorch PTQ 工具库，覆盖权重量化、激活校准、逐层敏感度分析和目标驱动的混合精度搜索。
- 基于 ONNX Runtime 和 TensorRT 对校准方法、模型精度与推理延迟进行端到端测量。
- 构建可复现实验流程和 71 项自动化测试，项目采用 MIT License 开源。

#### 基于 YOLOv11 的城市内涝图像监测系统 · 项目负责人

- 覆盖 Labelme 数据标注、数据清洗、模型训练、评估和 PyQt5 可视化界面交付全流程。
- mAP@0.5 达 0.91，推理速度 40 FPS，较 R-CNN 基线精度提升约 6%。

#### 植物 H₂O₂ 荧光智能探测系统 · YOLO 算法核心成员

- 构建包含 500 张荧光图像、500 个叶片区域和 800+ 个亮点实例的数据集。
- 对比 6 个 YOLO11/YOLO26 模型并优化数据增强策略。
- Box mAP50 达 0.971，Mask mAP50 达 0.907；获全国大学生生命科学竞赛省级三等奖。

### 技术栈

- **编程语言：** Python、C
- **机器学习 / 计算机视觉：** PyTorch、YOLO11/YOLO26、U-Net、OCR、目标检测、实例分割
- **模型优化：** 训练后量化、INT8、混合精度、模型敏感度分析、推理基准测试
- **工程能力：** Linux、Git、Labelme/LabelImg、PyQt5、ONNX Runtime、TensorRT、模型部署
- **语言能力：** 中文（母语）、英语（CET-4，可阅读英文技术文献）

### 校园经历

- 学生资助管理中心学生社团社长：带领 40 人团队，策划落地多项校园支持活动。
- 塞浦路斯理工大学国际访学：完成一个月英文课程学习与跨文化小组协作。

### 联系方式

- 邮箱：1295402349@qq.com
- GitHub：https://github.com/stenpten
- 求职方向：远程计算机视觉、Python/PyTorch、AI 评测、数据质量、OCR、模型优化和推理部署相关实习或项目机会。

> Detection, quantization, and honest benchmarks. 📉⚡
