<div align="center">

  <img src="docs/assets/images/RepoMaster.png" alt="RepoMaster Logo" width="600"/>

<h1 align="center" style="color: #2196F3; font-size: 24px; font-weight: 600; margin: 20px 0; line-height: 1.4;">
  🌟 RepoMaster: <span style="color: #555; font-weight: 400; font-size: 18px;"><em>Make 100M+ GitHub Repositories Work for You</em></span>
</h1>

<p align="center" style="font-size: 16px; color: #666; margin: 10px 0; font-weight: 500;">
  🚀 <em>Turn GitHub Repositories into Your Personal AI Toolbox</em>
</p>

  <p style="margin: 20px 0;">
    <a href="https://arxiv.org/pdf/2505.21577"><img src="https://img.shields.io/badge/arXiv-2505.21577-B31B1B.svg?style=for-the-badge&logo=arxiv&logoColor=white" /></a>
    <a href="#"><img src="https://img.shields.io/badge/Python-3.11+-3776AB.svg?style=for-the-badge&logo=python&logoColor=white" /></a>
    <a href="#"><img src="https://img.shields.io/badge/License-MIT-00A98F.svg?style=for-the-badge&logo=opensourceinitiative&logoColor=white" /></a>
    <a href="#"><img src="https://img.shields.io/github/stars/QuantaAlpha/RepoMaster?style=for-the-badge&logo=github&color=FFD700" /></a>
  </p>

  <!-- <p style="margin: 15px 0;">
    <img src="https://img.shields.io/badge/🤖_AI_Agent-Framework-FF6B6B.svg?style=flat-square&logo=robot&logoColor=white" />
    <img src="https://img.shields.io/badge/⚡_Autonomous-Execution-4ECDC4.svg?style=flat-square&logo=autohotkey&logoColor=white" />
    <img src="https://img.shields.io/badge/🧠_Multi_Agent-System-45B7D1.svg?style=flat-square&logo=teamspeak&logoColor=white" />
    <img src="https://img.shields.io/badge/🔍_Code-Understanding-96CEB4.svg?style=flat-square&logo=searchcode&logoColor=white" />
  </p> -->

  <p style="font-size: 16px; color: #666; margin: 15px 0; font-weight: 500;">
    🌐 <a href="README.md" style="text-decoration: none; color: #0066cc;">English</a> | <a href="README_CN.md" style="text-decoration: none; color: #0066cc;">中文</a>
  </p>

</div>

---


[![Quick Start](https://img.shields.io/badge/🚀_Quick-Start-4CAF50?style=for-the-badge)](#-quick-start)
[![Live Demo](https://img.shields.io/badge/🎬_Live-Demo-FF9800?style=for-the-badge)](#-quick-demo)
[![Documentation](https://img.shields.io/badge/📖_Complete-Guide-2196F3?style=for-the-badge)](user-guide.md)

</div>
</div>

---

## 🚀 Overview

<div align="center">
  <h3>🎯 Discover · Understand · Execute - Make Open Source Work for You</h3>
  
  <p style="font-size: 16px; color: #666; max-width: 800px; margin: 0 auto; line-height: 1.6;">
    RepoMaster transforms how you solve coding tasks by <strong>automatically finding the right GitHub tools</strong> and making them work together seamlessly. Just describe what you want, and watch as open source repositories become your intelligent assistants.
  </p>
  
  <p style="font-size: 16px; color: #2196F3; max-width: 800px; margin: 15px auto; line-height: 1.6; font-weight: 600;">
    💬 Describe Task → 🧠 AI Analysis → 🔍 Auto Discovery → ⚡ Smart Execution → ✅ Perfect Results
  </p>
</div>

<br/>


<img src="docs/assets/images/performance_01.jpg" alt="RepoMaster performance" style="background-color: #ffffff; display: block; margin: 0 auto;" />

---



## 🚀 Quick Start

### 🛠️ Installation

<details open>
<summary><strong>📦 Dependencies Installation</strong></summary>

```bash
# Clone the repository
git clone https://github.com/QuantaAlpha/RepoMaster.git

# Navigate to project directory
cd RepoMaster

# Install required dependencies
pip install -r requirements.txt
```

</details>

<details open>
<summary><strong>🔐 API Configuration</strong></summary>

Create your `configs/.env` file:

```bash
# Primary AI Provider Configuration
OPENAI_API_KEY=your_openai_api_key_here
OPENAI_MODEL=gpt-4-turbo-preview

# External Service APIs
Serper_API_KEY=your_serper_key          # Google search integration
JINA_API_KEY=your_jina_key              # Web content extraction

# Optional: Advanced Configuration
# CLAUDE_API_KEY=your_claude_key        # Anthropic Claude support
# DEEPSEEK_API_KEY=your_deepseek_key    # DeepSeek integration
```

</details>

### 🚀 Quick Run

<div align="center">

| Mode | Description | Command | Access |
|------|-------------|---------|--------|
| **🖥️ Frontend** | Interactive Web UI | `python launcher.py --mode frontend` | http://localhost:8501 |
| **⚡ Backend** | Unified API Mode | `python launcher.py --mode backend --backend-mode unified` | Terminal/API |

</div>

<details open>
<summary><strong>💡 Quick Launch Commands</strong></summary>

```bash
# Web Interface (Recommended for beginners)
bash run.sh frontend

# Backend Unified Mode (Recommended for advanced users)
bash run.sh backend unified

# Direct Python execution
python launcher.py --mode frontend
python launcher.py --mode backend --backend-mode unified
```

</details>

> 📘 **Need more configuration options?** Check our comprehensive [User Guide](user-guide.md) for advanced setup, troubleshooting, and optimization tips.


---

## 🎯 Quick Demo

<div align="center">
  <h3>💬 Natural Language → 🤖 Autonomous Execution → ✨ Real Results</h3>
  <p style="font-size: 16px; color: #666; margin: 20px 0; max-width: 700px;">
    Simply describe your task in natural language. RepoMaster's AI automatically analyzes your request, intelligently routes to optimal solution paths, and orchestrates the perfect GitHub tools to bring your ideas to life.
  </p>
</div>

| Task Description | RepoMaster Action | Result |
|------------------|-------------------|---------|
| *"Help me scrape product prices from this webpage"* | 🔍 Find scraping tools → 🔧 Auto-configure → ✅ Extract data | Structured CSV output |
| *"Transform photo into Van Gogh style"* | 🔍 Find style transfer repos → 🎨 Process images → ✅ Generate art | Artistic masterpiece |

<div align="center" style="background: linear-gradient(135deg, #FF6B6B 0%, #4ECDC4 100%); border-radius: 15px; padding: 20px; margin: 20px auto; max-width: 700px;">
  <p style="color: white; margin: 5px 0; font-size: 16px;">From <strong>"Writing Code from Scratch"</strong> → To <strong>"Making Open Source Work"</strong></p>
</div>

### 🎨 Neural Style Transfer Case Study

<div align="center">

<table style="border: none; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 15px; padding: 20px; margin: 20px 0;">
<tr>
<td align="center" width="33%" style="padding: 10px;">
  <h4 style="color: white; margin-bottom: 10px;">📷 Original Image</h4>
  <div style="background: white; border-radius: 10px; padding: 5px;">
    <img src="docs/assets/images/origin.jpg" width="180px" style="border-radius: 5px;" />
  </div>
</td>
<td align="center" width="33%" style="padding: 10px;">
  <h4 style="color: white; margin-bottom: 10px;">🎨 Style Reference</h4>
  <div style="background: white; border-radius: 10px; padding: 5px;">
    <img src="docs/assets/images/style.jpg" width="180px" style="border-radius: 5px;" />
  </div>
</td>
<td align="center" width="33%" style="padding: 10px;">
  <h4 style="color: white; margin-bottom: 10px;">✨ Final Result</h4>
  <div style="background: white; border-radius: 10px; padding: 5px;">
    <img src="docs/assets/images/transfer.jpg" width="180px" style="border-radius: 5px;" />
  </div>
</td>
</tr>
</table>

</div>

### 🎬 Complete Execution Demo | [📺 YouTube Demo](https://www.youtube.com/watch?v=Kva2wVhBkDU)

<div align="center">

https://github.com/user-attachments/assets/a21b2f2e-a31c-4afd-953d-d143beef781a

*Complete process of RepoMaster autonomously executing neural style transfer task*

</div>

**For advanced usage, configuration options, and troubleshooting, see our [User Guide](user-guide.md).**

---

## 🤝 Contributing

<div align="center">
  <h3>🌟 Join Our Mission to Revolutionize Code Intelligence</h3>
  <p style="color: #666; margin: 15px 0;">
    We believe in the power of community-driven innovation. Your contributions help make RepoMaster smarter, faster, and more capable.
  </p>
</div>

### 🚀 Ways to Contribute

<table align="center">
<tr>
<td align="center" width="25%">
  <h4>🐛 Bug Reports</h4>
  <p>Help us identify and fix issues</p>
  <a href="https://github.com/QuantaAlpha/RepoMaster/issues">Report Bugs</a>
</td>
<td align="center" width="25%">
  <h4>💡 Feature Requests</h4>
  <p>Suggest new capabilities</p>
  <a href="https://github.com/QuantaAlpha/RepoMaster/discussions">Share Ideas</a>
</td>
<td align="center" width="25%">
  <h4>📖 Documentation</h4>
  <p>Improve guides and examples</p>
  <a href="docs/">View Docs</a>
</td>
<td align="center" width="25%">
  <h4>💻 Code Contributions</h4>
  <p>Add features and improvements</p>
  <a href="#development-setup">Get Started</a>
</td>
</tr>
</table>

### 🛠️ Development Setup

<details open>
<summary><strong>Quick Developer Environment Setup</strong></summary>

```bash
# Fork and clone the repository
git clone https://github.com/your-username/RepoMaster.git
cd RepoMaster

# Install development dependencies
pip install -e ".[dev]"

# Set up pre-commit hooks for code quality
pre-commit install

# Run tests to ensure everything works
pytest tests/

# Start developing! 🚀
```

</details>

> 📋 **New to open source?** Check our [Contributing Guidelines](CONTRIBUTING.md) for detailed instructions and best practices.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Support

- 📧 **Email**: quantaalpha.ai@gmail.com
- 🐛 **Issues**: [GitHub Issues](https://github.com/QuantaAlpha/RepoMaster/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/QuantaAlpha/RepoMaster/discussions)
- 📖 **Documentation**: [Full Documentation](docs/)

---

## 🙏 Acknowledgments

Special thanks to:
- [AutoGen](https://github.com/microsoft/autogen) - Multi-agent framework
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Software engineering agents
- [SWE-Agent](https://github.com/princeton-nlp/SWE-agent) - GitHub issue resolution
- [MLE-Bench](https://github.com/openai/mle-bench) - ML engineering benchmarks

---

## 🌐 About QuantaAlpha

- QuantaAlpha was founded in **April 2025** by a team of professors, postdocs, PhDs, and master's students from **Tsinghua University, Peking University, CAS, CMU, HKUST**, and more.  

🌟 Our mission is to explore the **"quantum"** of intelligence and pioneer the **"alpha"** frontier of agent research — from **CodeAgents** to **self-evolving intelligence**, and further to **financial and cross-domain specialized agents**, we are committed to redefining the boundaries of AI. 

✨ In **2025**, we will continue to produce high-quality research in the following directions:  
- **CodeAgent**: End-to-end autonomous execution of real-world tasks  
- **DeepResearch**: Deep reasoning and retrieval-augmented intelligence  
- **Agentic Reasoning / Agentic RL**: Agent-based reasoning and reinforcement learning  
- **Self-evolution and collaborative learning**: Evolution and coordination of multi-agent systems  

📢 We welcome students and researchers interested in these directions to join us!  

🔗 Team Homepage: [QuantaAlpha](https://quantaalpha.github.io/)

---

## 📖 Citation

If you find RepoMaster useful in your research, please cite our work:

```bibtex
@article{wang2025repomaster,
  title={RepoMaster: Autonomous Exploration and Understanding of GitHub Repositories for Complex Task Solving},
  author={Huacan Wang and Ziyi Ni and Shuo Zhang and Lu, Shuo and Sen Hu and  Ziyang He and Chen Hu and Jiaye Lin and Yifu Guo and Ronghao Chen and Xin Li and Daxin Jiang and Yuntao Du and Pin Lyu},
  journal={arXiv preprint arXiv:2505.21577},
  year={2025},
  doi={10.48550/arXiv.2505.21577},
  url={https://arxiv.org/abs/2505.21577}
}
```

---

<div align="center">

**⭐ If RepoMaster helps you, please give us a star!**

Made with ❤️ by the QuantaAlpha Team

</div>
