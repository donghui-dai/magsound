## Magnetic Interference Induced Inaudible Voice Attacks and Defenses on Smart Assistants

Recent works demonstrated that speech recognition systems or voice assistants can be manipulated by malicious voice commands, which are injected through various inaudible media, such as ultrasound, laser, and electromagnetic interference (EMI). In this work, we explore a new kind of inaudible voice attack through the magnetic interference induced by a wireless charger.  Essentially, we show that the microphone components of smart devices suffer from severe magnetic interference when they are enjoying wireless charging, due to the absence of effective protection against the EMI at low frequencies (100 kHz or below). By taking advantage of this vulnerability, we have developed an inaudible voice attack termed ParasiteAttack, designed to inject malicious voice commands into smart devices during wireless charging. This attack utilizes an accessory equipment known as a parasite label to replicate the victim's voiceprint first and then deliver inaudible voice commands. We conducted comprehensive experiments involving 17 victim devices (including iPhones, Huawei, Samsung, etc.) and 6 types of voice assistants (such as Siri, Google STT, Bixby, etc.). The evaluation results demonstrate the feasibility of the proposed attack under commercial wireless charging conditions. To address this emerging threat, we present a privacy-preserving on-device defense framework that leverages small language models (SLMs) to detect abnormal magnetic voice commands. The framework is evaluated across five representative SLMs (e.g., SpeechLLM, Aero-1-Audio, etc.), achieving an average detection accuracy of 96.9% and an equal error rate of 3.06%, while maintaining an average real-time inference latency below 500 ms on mobile devices. These results confirm that the proposed approach provides an effective and responsive on-device defense against magnetic voice command attacks.

<!-- ## Teaser Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/-JItdyhV1ik" title="IEEE S&amp;P 2023 Teaser Video &quot;Inducing Wireless Chargers to Voice Out for Inaudible Command Attacks&quot;" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->

## Full Demo Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/oU4hSGAzZCU" title="Full Demo Video for MagSound" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


<!-- ## Paper

  @inproceedings{dai2022inducing,  
    title={Inducing wireless chargers to voice out for inaudible command attacks},  
    author={Dai, Donghui and An, Zhenlin and Yang, Lei},  
    booktitle={2023 IEEE Symposium on Security and Privacy (SP)},  
    pages={503--520},  
    year={2022},  
    organization={IEEE Computer Society}  
  }   -->
