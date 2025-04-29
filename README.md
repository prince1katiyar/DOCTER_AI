<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>🏥 Medical Image Analysis Platform</title>
</head>
<body>

<h1>🏥 Medical Image Analysis Platform</h1>
<p><strong>An advanced AI-powered platform for medical image analysis, collaboration, and reporting.</strong></p>

<p>Built using <strong>Streamlit</strong>, <strong>OpenAI GPT-4 Vision</strong>, <strong>LangChain</strong>, <strong>FAISS</strong>, and modern medical imaging libraries.</p>

<hr>

<h2>📌 Project Overview</h2>
<p>The platform enables users to:</p>
<ul>
  <li>Upload and analyze medical images (JPG, PNG, DICOM, NIfTI).</li>
  <li>Visualize results with Explainable AI (heatmaps and overlays).</li>
  <li>Collaborate through multi-doctor case discussions and chats.</li>
  <li>Perform Q&A on stored reports via a retrieval-augmented chatbot.</li>
  <li>Generate professional PDF reports and medical statistics.</li>
  <li>Fetch related medical research articles automatically via PubMed.</li>
</ul>

<hr>

<h2>✨ Key Features</h2>
<ul>
  <li>🖼️ <strong>Medical Image Upload</strong> (DICOM, NIfTI, JPEG, PNG)</li>
  <li>🧠 <strong>AI-based Image Analysis</strong> using OpenAI GPT-4 Vision</li>
  <li>🔥 <strong>Explainable AI Visualizations</strong> (Heatmaps)</li>
  <li>💬 <strong>Multi-doctor Collaboration</strong> via Real-time Chat Rooms</li>
  <li>❓ <strong>Report Q&A Assistant</strong> (using RAG pipeline)</li>
  <li>📋 <strong>PDF Medical Report Generation</strong></li>
  <li>📚 <strong>PubMed Literature Integration</strong></li>
  <li>📈 <strong>Medical Statistics Dashboard</strong></li>
</ul>

<hr>

<h2>🛠 Tech Stack</h2>

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Technology</th>
      <th>Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Streamlit</strong></td>
      <td>Web App Interface</td>
    </tr>
    <tr>
      <td><strong>OpenAI GPT-4 Vision</strong></td>
      <td>Image Analysis and Medical Report Assistance</td>
    </tr>
    <tr>
      <td><strong>LangChain + FAISS</strong></td>
      <td>Context Storage and Retrieval for Q&A</td>
    </tr>
    <tr>
      <td><strong>BioPython (Entrez)</strong></td>
      <td>Medical Literature Search via PubMed</td>
    </tr>
    <tr>
      <td><strong>ReportLab</strong></td>
      <td>PDF Report Generation</td>
    </tr>
    <tr>
      <td><strong>Pillow, Pydicom, NiBabel</strong></td>
      <td>Medical Image Processing</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>🚀 Getting Started</h2>

<h3>1. Clone the Repository</h3>
<pre><code>git clone https://github.com/your-username/medical-image-analysis-platform.git
cd medical-image-analysis-platform
</code></pre>

<h3>2. Install Dependencies</h3>
<pre><code>pip install -r requirements.txt
</code></pre>

<p><strong>Main Packages:</strong> streamlit, openai, langchain, faiss-cpu, pydicom, nibabel, pillow, biopython, reportlab, scikit-learn</p>

<h3>3. Configure API Key</h3>
<ul>
  <li>🔑 OpenAI API Key (for GPT-4 Vision analysis)</li>
</ul>
<p>Provide it via the sidebar input when the app runs.</p>

<h3>4. Run the App</h3>
<pre><code>streamlit run app.py
</code></pre>

<hr>

<h2>📋 Core Modules</h2>

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Module</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Image Upload & Analysis</strong></td>
      <td>Upload images, run AI-powered diagnostics, and visualize results.</td>
    </tr>
    <tr>
      <td><strong>Collaboration (Chat System)</strong></td>
      <td>Discuss cases among multiple doctors and the AI Assistant.</td>
    </tr>
    <tr>
      <td><strong>Report Q&A Assistant</strong></td>
      <td>Ask questions about previous analyses and get expert answers.</td>
    </tr>
    <tr>
      <td><strong>Reports & Analytics</strong></td>
      <td>Download analysis reports and view platform usage statistics.</td>
    </tr>
  </tbody>
</table>

<hr>

<h2>🧠 How It Works</h2>
<ul>
  <li>Upload your medical image ➔ Analyze via GPT-4 Vision ➔ View findings and AI-generated reports.</li>
  <li>Start real-time chat rooms for multi-doctor collaboration.</li>
  <li>Ask clinical questions about stored reports via a smart QA system.</li>
  <li>Generate and download professional PDF reports and statistical summaries.</li>
</ul>

<hr>

<h2>🌐 Integrations</h2>
<ul>
  <li><strong>OpenAI GPT-4 Vision:</strong> Analyze medical images and assist with diagnosis/chatting.</li>
  <li><strong>PubMed via Entrez:</strong> Fetch relevant academic research articles automatically.</li>
  <li><strong>ReportLab:</strong> Generate high-quality PDF medical reports with key findings.</li>
</ul>

<hr>

<h2>📎 Project File Structure</h2>

<pre><code>
├── app.py                   # Main Streamlit application
├── utils_simple.py           # Utilities for image processing, reporting, literature search
├── chat_system.py            # Multi-user doctor and AI chat system
├── report_qa_chat.py         # Retrieval-Augmented Q&A system
├── qa_interface.py           # UI for Q&A module
├── analysis_store.json       # Stored analyses
├── chat_store.json           # Stored case discussions
├── qa_chat_store.json        # Stored Q&A sessions
└── README.html               # Project Documentation (This file)
</code></pre>

<hr>

<h1>🚀 Diagnose Smarter. Collaborate Faster. Discover More.</h1>

</body>
</html>
