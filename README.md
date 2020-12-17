# Deep Video Analysiser

## milestone1
- [ ] 1. 对视频内容进行目标检测，人脸检测
- [ ] 2. 人脸聚类，人脸识别
- [ ] 3. general_pid(关联人脸与人体特征)
- [ ] 4. 统计结果：
  - [ ] 视频中出现多少物体，每个物体出现时长与对应时间段
  - [ ] 视频中人脸id出现时间段
- [ ] 5. 关联分析：
  - [ ] pid之间关系
  - [ ] pid与物体之间关系

## 模型：
1. 目标检测，FCOS， FCOS_RT_MS_DLA_34_4x_shtw：https://github.com/aim-uofa/AdelaiDet
2. 人脸检测，DSFD，light，  https://github.com/lijiannuist/lightDSFD
3. 人脸识别，CurricularFace， https://github.com/HuangYG123/CurricularFace


## 检索与匹配
1. https://github.com/milvus-io/milvus
2. https://github.com/facebookresearch/faiss
