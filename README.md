<h1 align="center">
Generative AI at AWS, First Edition</h1>
<p align="center">This is the code repository for <a href ="generative-ai-at-aws-first-edition"> Generative AI at AWS, First Edition</a>, published by Packt.
</p>

<h2 align="center">
Turn business strategy into production-ready AI applications and agents
</h2>
<p align="center">
Nestor Gandara, Eduardo Ordax, Srikanth Daggumalli, Ashutosh Dubey</p>

<p align="center">
   <a href="https://packt.link/I1tSU" alt="Discord" title="Learn more on the Discord server"><img width="32px" src="https://cliply.co/wp-content/uploads/2021/08/372108630_DISCORD_LOGO_400.gif"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
  <a href="https://packt.link/free-ebook/9781806104451"><img width="32px" alt="Free PDF" title="Free PDF" src="https://cdn-icons-png.flaticon.com/512/4726/4726010.png"/></a>
 &#8287;&#8287;&#8287;&#8287;&#8287;
  <a href="https://packt.link/gbp/9781806104451"><img width="32px" alt="Graphic Bundle" title="Graphic Bundle" src="https://cdn-icons-png.flaticon.com/512/2659/2659360.png"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
   <a href="https://www.amazon.com/Generative-AI-AWS-production-ready-applications/dp/1806104458/"><img width="32px" alt="Amazon" title="Get your copy" src="https://cdn-icons-png.flaticon.com/512/15466/15466027.png"/></a>
  &#8287;&#8287;&#8287;&#8287;&#8287;
</p>
<details open>
  <summary><h2>About the book</summary>
<a href="https://www.packtpub.com/product/unity-cookbook-fifth-edition/9781805123026">
<img src="https://content.packt.com/B34094/cover_image_small.jpg" alt="Unity Cookbook, Fifth Edition" height="256px" align="right">
</a>

Cut through the noise around generative AI and learn how to turn promising ideas into secure, scalable solutions on AWS. This book helps you connect business priorities with technical execution, so you can identify worthwhile use cases, select the right models and services, and move from pilot to production with confidence.
You explore the fundamentals of generative AI, understand how foundation models and agents work, and see where services such as Amazon Bedrock AgentCore and Amazon SageMaker AI fit into a modern AI stack. From there, the book guides you through preparing data, building an MVP, deploying production-ready applications, and designing for scalability, governance, and responsible AI.
Real-world industry examples and practical decision frameworks help you evaluate when to use generative AI, when traditional approaches are a better fit, and how to measure business value. You also examine advanced topics such as agentic AI, emerging patterns, and the future direction of enterprise AI.
By the end of this book, you will be able to plan, build, and govern generative AI solutions on AWS that deliver measurable value for your organization.

</details>
<details open>
  <summary><h2>Key Learnings</summary>
<ul>

<li>Understand how generative AI creates business value</li>

<li>Compare models, prompts, fine-tuning, and RAG</li>

<li>Navigate the AWS generative AI stack with confidence</li>

<li>Prepare data and select models for real use cases</li>

<li>Build MVPs and production-ready AI applications</li>

<li>Apply governance, ethics, and responsible AI controls</li>

<li>Evaluate agentic AI patterns and emerging trends</li>

<li>Measure impact across enterprise AI initiatives</li>

</ul>
</details>

<details open>
  <summary><h2>Get to know Authors</h2></summary>

_Nestor Gandara_ is a technology leader with over 20 years of IT experience specializing in Generative AI, cloud, and digital transformation. As Principal Partner SA and Generative AI Strategist at Amazon Web Services, he partners with C-suite executives to bridge the gap between technology and business value. Nestor is a program lead, mentor, and learning facilitator for MIT Professional Education and a faculty member at IENYC and ISDI. As the Founder of NextLevelguru and author of "The Art of Building Your Resilience and Adaptability," by combining executive leadership with talent mentoring, he holds a unique position at the intersection of Next-Gen Enterprise technology, education, and business strategy.

_Eduardo Ordax_ is a Principal GenAI Go-to-Market Lead at AWS with 15+ years of experience across technology, combining technical and business leadership with a strong passion for AI. Recognized as the #1 AI influential voice in Spain and among the #Top20 worldwide, I'm an international keynote speaker and postgraduate lecturer. I actively share insights on AI innovation, strategy, and real-world adoption with a community of 200,000+ professionals on LinkedIn, contributing to shaping the future of artificial intelligence.

_Srikanth Daggumalli_ is a Senior Analytics & AI Specialist Solutions Architect at Amazon Web Services, specializing in generative AI, machine learning, and cloud-native data architectures. With nearly two decades of experience, he has architected mission-critical data platforms across financial services, insurance, retail, automotive, ISV, and digital-native sectors, spanning global payments, anti-money laundering, credit-risk management, and enterprise analytics for Fortune 500 organizations. He is an IEEE Senior Member, IETE Fellow, and Technical Program Committee member and peer reviewer for IEEE conferences and Manning Publications. His articles on InfoQ and the AWS Big Data Blog have been syndicated across more than 15 international platforms.

_Ashutosh Dubey_ is a technology leader and recognized expert in Generative and Agentic AI at Amazon Web Services. He empowers enterprise leaders to operationalize artificial intelligence at a global scale. A dedicated advocate for technical education and community engagement, he regularly shares industry insights through his public blogs. He is the coauthor of Generative AI for Software Developers and Interview Guide for Solution Architects, providing practical guidance for engineering and leadership teams navigating the complexities of modern software design.



</details>


  # 🤖 Note From the authors
  ##  Generative AI at AWS

A collection of advanced Generative AI applications and demonstrations built on AWS services, showcasing cutting-edge AI agent patterns and real-world implementations.

**Demo**
https://www.youtube.com/watch?v=IJmfIONe3Ws

## 🎯 **Projects**

### 🏨 **Hotel Reservations - AI Agentic Application**
**Location**: [`hotel-reservations/`](./hotel-reservations/)

A complete AI-powered hotel reservation system demonstrating advanced agentic AI patterns:

- **🤖 AI Agent**: Claude 3.7 Sonnet with AWS Bedrock + AgentCore + Strands
- **🛠️ 6 Specialized Tools**: Search, availability, booking, management, cancellation, web search
- **💻 Web Interface**: Streamlit chat app with admin panel
- **🗄️ Database**: PostgreSQL with sample hotels and reservations
- **📊 Real-world Demo**: Complete booking lifecycle management

**Key Features:**
- Natural language hotel search and booking
- Intelligent tool orchestration and decision making
- Real-time availability checking and reservation management
- Admin panel for hotel and booking management
- Comprehensive documentation and testing

**Quick Start:**
```bash
cd hotel-reservations/
pip install -r requirements.txt
python database/setup.py
python run_streamlit.py
```

**Live Demo**: http://localhost:8501

---

## 🚀 **Technologies Used**

### **AWS Services**
- **AWS Bedrock**: Foundation models (Claude 3.7 Sonnet)
- **AgentCore**: Enterprise AI agent framework
- **AWS CLI**: Authentication and configuration

### **AI Frameworks**
- **Strands**: Tool orchestration and conversation management
- **Anthropic Claude**: Advanced reasoning and natural language processing

### **Development Stack**
- **Python 3.8+**: Core development language
- **Streamlit**: Modern web interface framework
- **PostgreSQL**: Production-ready database
- **Rich**: Beautiful CLI interfaces and logging

## 🏗️ **Architecture Patterns**

### **Agentic AI Design**
- **Tool-based Architecture**: Modular, reusable AI tools
- **Context Management**: Conversation state and memory
- **Error Handling**: Graceful degradation and recovery
- **Natural Language Interface**: Chat-based user interaction

### **Enterprise Patterns**
- **Database Integration**: Real-time data operations
- **Web Interface**: Production-ready user experience
- **Admin Capabilities**: Management and monitoring tools
- **Testing Framework**: Comprehensive validation and testing

## 📚 **Learning Resources**

Each project includes comprehensive documentation:
- **Architecture Guides**: System design and component interaction
- **Implementation Guides**: Step-by-step setup and deployment
- **API Documentation**: Tool interfaces and data models
- **Testing Examples**: Validation and quality assurance

## 🎯 **Use Cases Demonstrated**

### **Business Applications**
- **Customer Service Automation**: AI-powered booking assistance
- **Process Automation**: Intelligent workflow orchestration
- **Data Integration**: Real-time database operations
- **User Experience**: Natural language interfaces

### **Technical Demonstrations**
- **Agentic AI Patterns**: Tool selection and orchestration
- **AWS Integration**: Enterprise cloud services
- **Modern Web Development**: Responsive user interfaces
- **Database Design**: Scalable data architecture

## 🚀 **Getting Started**

### **Prerequisites**
- Python 3.8+
- AWS Account with Bedrock access
- PostgreSQL (for hotel-reservations)
- AWS CLI configured

### **Quick Setup**
```bash
# Clone the repository
git clone https://github.com/daggumalli/Generative-AI-on-AWS.git
cd Generative-AI-on-AWS

# Choose a project
cd hotel-reservations/

# Follow project-specific setup instructions
```

## 🤝 **Contributing**

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Add comprehensive tests
4. Submit a pull request

## 📄 **License**

This project is licensed under the MIT License - see individual project LICENSE files for details.

## 🆘 **Support**

- **Issues**: Report bugs and request features
- **Discussions**: Ask questions and share ideas
- **Documentation**: Comprehensive guides and examples

---

**🎉 Explore the future of AI-powered applications with real-world implementations on AWS!**
