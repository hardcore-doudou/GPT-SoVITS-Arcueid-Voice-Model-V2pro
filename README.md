# GPT-SoVITS-Arcueid-Voice-Model-V2pro
# Arcueid Brunestud (Tsukihime) - GPT-SoVITS Voice Model

## 📝 项目介绍 / Introduction
这是一个基于 **GPT-SoVITS-v2Pro** 训练的《月姬》爱尔奎特·布伦史塔德（Arcueid Brunestud）AI 语音模型。

This is an AI voice model of Arcueid Brunestud from *Tsukihime*, trained using **GPT-SoVITS-v2Pro**.

## 📦 模型信息 / Model Info
- **底模版本 / Base Model**: GPT-SoVITS v2Pro
- **训练数据 / Dataset**: 约 30 分钟高质量干声 (From Tsukihime Remake)
- **训练轮数 / Epochs**: GPT 15 / SoVITS 8 (Recommended)

## 📂 文件说明 / Files
- `Arcueid_SoVITS.pth`: SoVITS 权重文件，负责音色还原。
- `Arcueid_GPT.ckpt`: GPT 权重文件，负责语气和韵律。

## 🚀 使用方法 / Usage
1. 下载本项目的所有模型文件。
2. 将 `.pth` 文件放入 GPT-SoVITS 的 `SoVITS_weights_v2Pro` 文件夹。
3. 将 `.ckpt` 文件放入 `GPT_weights_v2Pro` 文件夹。
4. 启动 WebUI，在推理页面加载对应模型即可。

## ⚠️ 免责声明 / Disclaimer
本模型仅供学习交流使用，严禁用于任何商业用途或非法传播。请尊重角色原配音演员及版权方利益。
This model is for educational and research purposes only. Commercial use is strictly prohibited.
