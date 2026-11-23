## Hi, I am an AI Engineer & Researcher

I hold a Bachelor’s in Computer Science and a Master’s in AI. My background bridges strong theoretical foundations with hands-on implementation, ranging from applied labs and end-to-end projects to analyzing and presenting academic research. 
Currently, I’m focused on building personal AI projects designed to solve practical, everyday problems.

### ASL Sign Transcription (In Progress)
The goal of this project is to build a real-time interface where a user can sign in front of a camera and have live closed-caption transcriptions appear below. 
The long-term vision is to integrate this into a video-calling app so Deaf and hearing people can communicate naturally on a call, even if the hearing person does not know sign language.
It extracts 3D body, hand, and facial keypoints using **MediaPipe Holistic** and processes landmark motion sequences in **PyTorch** using a **Temporal Convolutional Network (TCN)** trained with **Supervised Contrastive Learning (SupCon)**, exported to **ONNX Runtime** for low-latency CPU inference. *(Currently in development.)*

**Skills & Technologies:** Computer Vision, Deep Learning, PyTorch, MediaPipe, OpenCV, Temporal Convolutional Networks (TCN), Contrastive Metric Learning, ONNX Runtime, Real-Time Video Processing.

### FlowSR : Generative Super-Resolution for 2D Fluid Dynamics (In Progress)
The goal of this project is to use lightweight generative AI models to quickly and efficiently reconstruct high-resolution fluid flow fields from coarse, low-resolution simulations. It compares a deterministic U-Net baseline against a probabilistic Conditional VAE (cVAE) to accurately recover small-scale turbulent vortices and measure prediction confidence without the cost of supercomputer simulations.

**Skills & Technologies:** PyTorch, NumPy, SciPy, Matplotlib, HDF5 (`h5py`), Pytest, Deep Learning, Conditional Variational Autoencoders (cVAE), U-Net
  
### Agentic Job Search & Portfolio Synthesizer (In Progress)
An end-to-end agentic AI platform that indexes a user's CV and project experience to evaluate job offers from scraped URLs or raw descriptions. 
It identifies technical skill gaps using semantic retrieval, tracks all applications and market requirements in a relational database, and orchestrates a Drafter-Critic-Refiner agent loop to 
design practical projects that cover multiple missing skills at once.

**Skills & Technologies:** RAG, LangGraph, Multi-Agent Workflows, FastAPI, Pydantic, LLMOps, Scikit-Learn, SQLite, Trafilatura, PyPDF, PII Redaction, Streamlit.
