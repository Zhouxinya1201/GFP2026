# GFP_ProteinDesign_2026
2026蛋白设计赛 高亮度高热稳定绿色荧光蛋白全套可复现设计代码
## 项目简介
基于sfGFP骨架，整合mBaoJin、TGP增效突变，采用ESM3/ProteinMPNN/ThermoMPNN多模型四轮漏斗筛选，产出6条差异化参赛GFP序列，同步优化无细胞初始荧光、72℃热稳定性。
## 运行环境
Python 3.10
torch>=2.1
biopython, pandas, numpy, matplotlib, pymol, esm, proteinmpnn, thermompnn
一键安装：pip install -r requirements.txt
## 仓库目录
data/ 模板晶体、官方排除序列、突变数据集
scripts/ 结构预处理、序列生成、打分、合规校验脚本
intermediate_output 各轮筛选中间序列
final_submit 参赛CSV、完整设计PDF报告
## 复现步骤
1. 克隆本公开仓库
2. 安装全部依赖包
3. 依次运行01~04自动化脚本，复现6条参赛序列
## 输出文件
final_6seq_submit.csv 赛事标准6条氨基酸序列提交文件
## 完整复现步骤
1. 克隆本公开仓库至本地
2. 执行 pip install -r requirements.txt 安装全部依赖
3. 依次运行结构预处理、序列生成、打分筛选、合规校验脚本，复现6条参赛序列
