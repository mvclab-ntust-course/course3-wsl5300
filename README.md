[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/X3WkcXtG)

# Homework3 - Train LoRA & generate images

#### 本次作業獲得Irene大大的幫助!</br>

## (1/2)Train LoRA
* 我選擇的資料集總覽：
  <div align=center><img src="https://github.com/mvclab-ntust-course/course3-wsl5300/blob/main/images/CleanShot%202024-05-16%20at%2000.41.48%402x.png" width=600></div>
  </br>
##### 在[LoRA-report](https://docs.google.com/document/d/1JNP28hvgi8iLeNHfedGLjFqZSJkl3RY3_JSAMlUnYhU/edit?usp=share_link) 提及完成LoRA訓練的過程並得到[Haikyu7-20.safetensors](https://github.com/mvclab-ntust-course/course3-wsl5300/blob/main/Haikyu7-20.safetensors)，因此不過多贅述</br></br>

## (2/2)generate images

* __install__ __stable__ __diffusion__ __webui.__
  * 我是參考影片安裝stable-diffusion-webui：
[在Mac上安裝Stable Diffusion WebUI繪圖軟體](https://www.youtube.com/watch?v=clrx1PQgcVs)

  * 將 `Haikyu7-20.safetensors` 放入 `../stable-diffsion-webui/models/lora/` 中。
  * 在`stable-diffsion-webui/` terminal 執行 `./webui.sh --autolaunch`
  * 呈現如下圖</br>
  <img src="https://github.com/mvclab-ntust-course/course3-wsl5300/blob/main/images/CleanShot%202024-05-16%20at%2000.14.44%402x.png" width=600>
  </br>
  放入自己訓練的lora!</br></br>

* __generate__ __image__
  * config：
    * Sampling steps: `100`
    * CFG Scale: `18.5`
    * prompt: `haiku, walking, happy`
    * 以下為產生的圖片：
<div align=center>
  <img src="https://github.com/mvclab-ntust-course/course3-wsl5300/blob/main/output.png" width=300>
</div>


