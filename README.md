# Multimodal Autism Platform  

🚀 **Multimodal AI-based Detection and Tracking of Autistic Behavioral and Communication Patterns**  
Graduation Project – Systems & Biomedical Engineering, Cairo University  

---

## 📌 Overview  
Autism Spectrum Disorder (ASD) is a complex neurodevelopmental condition that affects communication, social interaction, and behavior. Traditional diagnosis relies on lengthy clinical assessments and specialist observation, making early intervention difficult.  

The **Multimodal Autism Platform** is an **AI-powered, web-based system** designed to support early, contactless, and objective autism screening. By integrating **computer vision, speech analysis, gaze estimation, and socio-emotional cues**, our system delivers clinician-friendly reports to assist in timely and accurate ASD assessment.  

---

## 🎯 Objectives  
- Enable **early autism detection** through multimodal AI analysis.  
- Provide **remote and accessible** screening tools for parents and clinicians.  
- Generate **interpretable reports** to support expert validation and intervention planning.  
- Combine multiple behavioral and developmental indicators into a **unified platform**.  

---

## 🧠 System Modules  
Our platform integrates several cutting-edge AI models into a modular pipeline:  

- **Stereotypical Behavior Recognition** → MViT-v2 + Detectron2 for action recognition.  
- **Graphomotor Skills Analysis** → CNNs, MobileNet, and Sketch-RNN on handwriting/drawing tasks.  
- **Audio-Visual Behavior Analysis** → PaliGemma with Whisper & CoNeTTE for multimodal classification.  
- **Early Risk Screening** → Ensemble ML applied to Q-CHAT-10 questionnaires.  
- **Gaze Estimation & Eye Contact** → Gaze-LLE with DINOv2 for joint attention and mutual gaze.  
- **Socio-Emotional Features** → MediaPipe & DeepFace for attention, emotions, blink rate, and head pose.  

---

## 🌍 Web Platform  
- **Bilingual Interface (English & Arabic)** for accessibility.  
- Built with **Next.js (frontend) + Django REST (backend)**.  
- Secure data handling with modular microservices for heavy AI models.  
- Generates **clinician-friendly PDF reports** with quantitative metrics, visualizations, and risk assessments.  
- Includes dashboards for both **parents and clinicians**.  

---

## ⚙️ Tech Stack  
- **Backend**: Python, PyTorch, Django REST Framework  
- **Frontend**: Next.js, Tailwind CSS  
- **Models**: MViT-v2, PaliGemma, Whisper, CoNeTTE, Gaze-LLE, DINOv2, MediaPipe, DeepFace  
- **Deployment**: Containerized microservices for scalable inference  

---

## 📊 Impact  
- Reduces reliance on lengthy clinical observation.  
- Expands accessibility to early autism screening, especially in under-resourced regions.  
- Provides **objective, multimodal insights** that support—but do not replace—expert evaluation.  

---

## 🏆 Achievements & Funding  
- 🥇 **Dell Technologies – Envision the Future Competition (2025)**  
   1st place out of 259 projects across 14 countries in the Middle East, Africa & Turkey  
   [🔗 See announcement](https://www.linkedin.com/posts/ziyad-el-fayoumy_delltechnologies-envisionthefuture-ai-activity-7368651017564962820--pH6)  

- 💰 **ITIDA Grant – ITAC Graduation Projects Support Program**  
   Officially funded and supported by the Information Technology Industry Development Agency (ITIDA)  
   [🔗 See announcement](https://www.linkedin.com/posts/ziyad-el-fayoumy_itida-itac-graduationabrprojects-activity-7330945809389191168-1Yo6)  

---

## 🚧 Project Status  
- ✅ Models trained and validated on multiple datasets.  
- ✅ Web platform prototype developed and tested.  
- 🔄 Ongoing collaboration with **Kasr Al-Ainy Hospital** for dataset expansion and clinical validation.  
- 🔮 Future enhancements: sensory processing analysis, language development modules, and clinician training tools.  

---

## 👥 Team <a name = "team"></a>

<table>
  <tr>
    <td align="center">
    <a href="https://github.com/AbdulrahmanGhitani" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/114954706?v=4" width="150px;" alt="Abdulrahman Ghitani"/>
    <br />
    <sub><b>Abdulrahman Ghitani</b></sub></a>
    </td>
    
  <td align="center">
    <a href="https://github.com/amg-eng" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/114669748?v=4" width="150px;" alt="Amgad Shaban"/>
    <br />
    <sub><b>Amgad Shaban</b></sub></a>
    </td>
    
  <td align="center">
    <a href="https://github.com/Mahmoudm007" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/120218155?v=4" width="150px;" alt="Mahmoud Abdelaty"/>
    <br />
    <sub><b>Mahmoud Abdelaty</b></sub></a>
    </td>
    
  <td align="center">
    <a href="https://github.com/omarnasser0" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/100535160?v=4" width="150px;" alt="Omar Shaban"/>
    <br />
    <sub><b>Omar Shaban</b></sub></a>
    </td>
    
  <td align="center">
    <a href="https://github.com/Ziyad-HF" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/99608059?v=4" width="150px;" alt="Ziyad El-Fayoumy"/>
    <br />
    <sub><b>Ziyad El-Fayoumy</b></sub></a>
    </td>
  </tr>
</table>

**Supervised by:** Prof. Muhammad Rushdi & Dr. Eman Marzban  


---

## 📌 Disclaimer  
This repository serves as a **public information hub** for our graduation project.  
Due to privacy, ethical, and clinical validation requirements, **datasets and implementation code are not publicly released** at this stage.  

---

## 📜 License  
TBD – Currently research-only.  
