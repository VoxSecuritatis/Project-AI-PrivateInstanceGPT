# Project:  Private Instance GPT
### Date:  2024-10-14

<h2>Description</h2>
This project aims to build a self-hosted AI environment capable of running large language models (LLMs) and generating AI-powered images without relying on cloud-based services. By leveraging Windows Subsystem for Linux (WSL) and Ubuntu 24.x, the system provides a flexible and efficient foundation for deploying various AI models locally. Ollama GPT serves as the core AI framework, enabling natural language processing and text-based AI interactions. A selection of specialized LLMs, including llama2, codegemma, llava, and Mistral 7b, will be installed to provide diverse capabilities such as general language understanding, coding assistance, and image analysis. Additionally, Stable Diffusion will be integrated to facilitate AI-generated art, allowing users to create high-quality images from text prompts. To streamline usability, Docker will be employed to containerize the applications, and Open Web UI will serve as an intuitive frontend, providing seamless interaction with AI models. With this setup, the project aims to deliver a powerful, privacy-focused, and locally controlled AI system that supports both text and image-based AI functionalities.
<br />

<h2>Tools and Utilities Used</h2>
<ul>
<li>Windows Subsystem for Linux (WSL)</li>
<li>Virtual machine of Ubuntu 24.x</li>
<li>Single Nvidia GTX 1080 GPU</li>
<li>Approximately 20 GB of storage space for all models and applications</li>
<li>Web server (Open Web UI)</li>
<li>Ollama GPT</li>
<li>llama2 (foundational model)</li>
<li>codegemma (for development / coding model)</li>
<li>llava (image analysis></li>
<li>Mistral 7B (founational model)</li></ul>

<h2>Environments Used</h2>
<ul><li>Windows 10</li></ul>

<h2>Install and integration</h2>
<ol>
  <li>Install Windows WSL (Windows Subsystem for Linux)</li>
  <li>Install Ubuntu 24.x</li>
  <li>Install Ollama GPT</li>
  <li>Added various LLM models:
    <ul>
      <li>llama2 (general LLM)</li>
      <li>codegemma (coding)</li>
      <li>llava (image analysis)</li>
      <li>mistral 7b (general LLM)</li>
    </ul>
  </li>
  <li>Install Docker (support for Open Web UI)</li>
  <li>Install Open Web UI as a frontend for the GPT (web UI)</li>
  <li>Install Stable Diffusion (for AI-generated art)</li>
  <li>Integration of GPT, LLMs, and Stable Diffusion</li>
</ol>





<h2>Project walk-through:</h2>
<p align="center">
My first prompt from my local GPT (non-GUI, text based): <br/>
<img src="https://imgur.com/UhhsI3Z.jpg" height="80%" width="80%" alt="My first prompt from my local GPT (non-GUI, text based)"/>
<br />
<br />
Monitoring the load on the GPU during a result:  <br/>
<img src="https://imgur.com/cYAKbWl.jpg" height="80%" width="80%" alt="Monitoring the load on the GPU during a result"/>
<br />
<br />
Open Web UI interface to llama2 LLM:  <br/>
<img src="https://imgur.com/JzgaGKb.jpg" height="80%" width="80%" alt="Open Web UI interface to llama2 LLM"/>
<br />
<br />
Test prompt to verify GUI of llama2 LLM is working:  <br/>
<img src="https://imgur.com/RpdPb9k.jpg" height="80%" width="80%" alt="Test prompt to verify GUI of llama2 LLM is working"/>
<br />
<br />
Addition of CodeGemma for development prompts (for me, Python):  <br/>
<img src="https://imgur.com/bjbzXhS.jpg" height="80%" width="80%" alt="Addition of CodeGemma for development prompts (for me, Python)"/>
<br />
<br />
Training the Model with new data, uploading documents to the LLM:  <br/>
<img src="https://imgur.com/1LD6guC.jpg" height="80%" width="80%" alt="Training the Model with new data, uploading documents to the LLM"/>
<br />
<br />
Validation of uploaded document is searchable in the LLM:  <br/>
<img src="https://imgur.com/ZKdjVvM.jpg" height="80%" width="80%" alt="Validation of uploaded document is searchable in the LLM"/>
<br />
<br />
Installation and verification of llava (image recognition) to LLM:  <br/>
<img src="https://imgur.com/jrUsW7j.jpg" height="80%" width="80%" alt="Installation and verification of llava (image recognition) to LLM"/>
<br />
<br />
Installation and verification of Minstral 7B to GPT:  <br/>
<img src="https://imgur.com/DkPlW1s.jpg" height="80%" width="80%" alt="Installation and verification of of Minstral 7B to GPT"/>
<br />
<br />
Installation and verification of Stable Diffision to GPT for image creation:  <br/>
<img src="https://imgur.com/PitAh4l.jpg" height="80%" width="80%" alt="Installation and verification of Stable Diffision to GPT for image creation"/>
<br />
<br />
Integration of Stable Diffision to LLM for image creation:  <br/>
<img src="https://imgur.com/HVoOrdD.jpg" height="80%" width="80%" alt="Integration of Stable Diffision to LLM for image creation"/>
