# Building Intelligent Multimodal Applications with Amazon Nova2 Omni

This repository contains hands-on workshops and examples demonstrating how to build intelligent multimodal applications using Amazon Nova2 Omni, AWS's advanced foundation model. The workshops cover text generation, image creation, video understanding, multimodal RAG, and intelligent agent systems.

## 🎯 What You'll Learn

- **Text & Image Generation**: Create compelling content and visuals with Nova's multimodal capabilities
- **Video Understanding**: Analyze and extract insights from video content
- **Multimodal RAG**: Build retrieval-augmented generation systems that work with text, images, and documents
- **Intelligent Agents**: Develop AI agents using the Strands framework for real-world applications
- **Image Editing**: Perform advanced image manipulation and enhancement
- **Audio Analysis**: Process and analyze audio recordings for insights

## 📚 Workshop Contents

### Core Workshops

1. **[Text & Image Generation](nova-text-image.ipynb)**
   - Text generation with word count control
   - Structured JSON output
   - Built-in reasoning capabilities
   - Professional image generation with text rendering

2. **[Video Understanding](nova-video-understanding.ipynb)**
   - Video content analysis
   - Scene detection and description
   - Multi-frame processing

3. **[Multimodal RAG](nova-multimodel-rag.ipynb)**
   - Document and image retrieval
   - Cross-modal search capabilities
   - Context-aware responses

4. **[Image Editing](nova-image-editing.ipynb)**
   - Advanced image manipulation
   - Style transfer and enhancement
   - Automated editing workflows

5. **[Meeting Workshop](nova-meeting-workshop.ipynb)**
   - Meeting transcription and analysis
   - Action item extraction
   - Summary generation

6. **[Smart Real Estate Assistant](nova-strands-agent.ipynb)**
   - Multi-agent system using Strands framework
   - Property analysis from images
   - Marketing content generation
   - Market valuation insights
   - Visual enhancement for listings

## 🚀 Getting Started

### Prerequisites

- AWS Account with Bedrock access
- Python 3.8+
- Jupyter Notebook or JupyterLab
- AWS CLI configured with appropriate permissions

### Installation

1. Clone this repository:
```bash
git clone https://github.com/your-username/sample-building-intelligent-multimodal-applications-with-Nova2.git
cd sample-building-intelligent-multimodal-applications-with-Nova2
```

2. Install dependencies:
```bash
# For basic workshops
pip install -r requirementsv2.txt

# For agent-based workshops
pip install strands-agents strands-agents-tools boto3 pillow
```

3. Configure AWS credentials:
```bash
aws configure
```

### Quick Start

1. Open any notebook in Jupyter:
```bash
jupyter notebook
```

2. Start with [nova-text-image.ipynb](nova-text-image.ipynb) for basic concepts
3. Progress to more advanced workshops like the real estate assistant

## 🏗️ Project Structure

```
├── img/                          # Sample images for workshops
├── media/                        # Sample videos for analysis
├── Boto3CliV1Artifacts/         # Boto3 dependencies v1
├── Boto3CliV2Artifacts/         # Boto3 dependencies v2
├── nova-text-image.ipynb        # Text and image generation
├── nova-video-understanding.ipynb # Video analysis
├── nova-multimodel-rag.ipynb    # Multimodal RAG
├── nova-image-editing.ipynb     # Image editing
├── nova-meeting-workshop.ipynb  # Meeting analysis
├── nova-strands-agent.ipynb     # Multi-agent real estate system
├── requirementsv1.txt           # Python dependencies v1
└── requirementsv2.txt           # Python dependencies v2
```

## 🔧 Configuration

The workshops use Amazon Nova 2 Omni model (`us.amazon.nova-2-omni-v1:0`) in the `us-west-2` region. Ensure you have:

- Bedrock model access enabled for Nova 2
- Appropriate IAM permissions for Bedrock operations
- Sufficient service quotas for your use case

## 💡 Key Features Demonstrated

- **Multimodal Understanding**: Process text, images, and video simultaneously
- **Structured Output**: Generate JSON, formatted text, and specific schemas
- **Agent Orchestration**: Coordinate multiple AI agents for complex workflows
- **Real-world Applications**: Practical examples in real estate, content creation, and analysis
- **Advanced Reasoning**: Built-in reasoning capabilities for complex problem-solving
- **Professional Quality**: Generate marketing-ready content and visuals

## 🎨 Sample Applications

### Real Estate Assistant
A complete multi-agent system that:
- Analyzes property images for features and condition
- Generates compelling marketing descriptions
- Provides market valuation insights
- Creates enhanced property visuals

### Content Creation Suite
- Professional image generation with text overlays
- Video content analysis and summarization
- Document processing with visual elements
- Meeting transcription and action item extraction

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

