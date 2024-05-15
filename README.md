[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/X3WkcXtG)

# Homework3 - Train LoRA & generate images

### 本次作業獲得Irene的幫助 >< ～

### 在[LoRA-report.pdf](https://github.com/mvclab-ntust-course/course3-wsl5300/blob/main/LoRA%20-%20report.pdf) 完成LoRA訓練並得到[Haikyu7-20.safetensors](https://github.com/mvclab-ntust-course/course3-wsl5300/blob/main/Haikyu7-20.safetensors)

## 安裝stable diffusion webui.
### 我是參考影片安裝stable-diffusion-webui：
[在Mac上安裝Stable Diffusion WebUI繪圖軟體](https://www.youtube.com/watch?v=clrx1PQgcVs)

* 將 ˋHaikyu7-20.safetensorsˋ 放入 ˋ../stable-diffsion-webui/models/lora/ˋ 中。
* 在ˋstable-diffsion-webui/ˋterminal 執行 ˋ./webui.sh --autolaunchˋ
* 呈現![image](https://github.com/mvclab-ntust-course/course3-wsl5300/blob/main/images/CleanShot%202024-05-16%20at%2000.14.44%402x.png)
* 放入lora完成

## Generate images

### 產生效果圖：
* Sampling steps: 100
* CFG Scale: 18.5
* 結果為：![image](https://github.com/mvclab-ntust-course/course3-wsl5300/blob/main/output.png)



