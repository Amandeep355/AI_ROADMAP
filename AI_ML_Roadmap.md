# 🧠 Complete AI/ML/DL Learning Roadmap
## Zero → Professional AI Engineer
### The Most Comprehensive AI Learning Roadmap (2025-2026)

---

> **Language:** Python 🐍 Only  
> **Total Phases:** 22  
> **Total Lessons:** 433  
> **Goal:** Junior → Senior AI Engineer at FAANG / Anthropic / OpenAI  
> **Time Commitment:** ~2,400–3,200 hours (2–3 years full-time)  
> **Lesson Estimates:** (S) = <1 hr | (M) = 1-3 hrs | (L) = 3-8 hrs

---

## 🗺️ Learning Tracks & Dependency Graph
To help you navigate this comprehensive roadmap, here are the phase dependencies and suggested tracks based on your career goals.

### Minimum Viable Tracks
- **Research Scientist (Anthropic/OpenAI):** Phases 1, 3, 6, 9, 10, 11, 19, 20
- **LLM Platform Engineer:** Phases 0, 3, 6, 12, 14, 18

### Phase Dependencies
| Phase | Prerequisites | Description |
|-------|---------------|-------------|
| 0 to 5 | Sequential | Foundation (Math, ML, DL, CV, NLP) |
| 6. Transformers | Phase 3, 5 | Core architecture for modern AI |
| 7. Speech & Audio | Phase 6 | Transformers applied to audio |
| 8. Generative AI | Phase 3, 4 | VAEs, GANs, Diffusion |
| 9. Reinforcement Learning | Phase 3 | Core RL concepts |
| 10. LLMs from Scratch | Phase 6, 9 | Building and aligning LLMs |
| 11. Reasoning & Test-Time | Phase 10 | Scaling inference compute |
| 12. LLM Engineering | Phase 10 | Applying LLMs in production |
| 13. Multimodal AI | Phase 6, 10 | Vision-Language Models, etc. |
| 14. Tools & Protocols | Phase 12 | Function calling, MCP |
| 15. Agent Engineering | Phase 14 | Building tool-using agents |
| 16. Autonomous Systems | Phase 15 | Long-horizon agents |
| 17. Multi-Agent & Swarms | Phase 15 | Coordinating multiple agents |
| 18. Infra & Production | Phase 12 | Serving, CUDA, scaling |
| 19. Ethics & Alignment | Phase 10 | Safety, alignment, fairness |
| 20. Mech Interpretability | Phase 6, 10 | SAEs, circuits, patching |

---

## 📋 Table of Contents

| Phase | Name | Lessons |
|-------|------|---------|
| [Phase 0](#phase-0--dev-environment--tooling) | Dev Environment & Tooling | 12 |
| [Phase 1](#phase-1--math-foundations) | Math Foundations | 22 |
| [Phase 2](#phase-2--ml-fundamentals) | ML Fundamentals | 20 |
| [Phase 3](#phase-3--deep-learning-core) | Deep Learning Core | 14 |
| [Phase 4](#phase-4--computer-vision) | Computer Vision | 28 |
| [Phase 5](#phase-5--nlp-foundations-to-advanced) | NLP: Foundations to Advanced | 29 |
| [Phase 6](#phase-6--transformers-deep-dive) | Transformers Deep Dive | 14 |
| [Phase 7](#phase-7--speech--audio) | Speech & Audio | 17 |
| [Phase 8](#phase-8--generative-ai) | Generative AI | 14 |
| [Phase 9](#phase-9--reinforcement-learning) | Reinforcement Learning | 13 |
| [Phase 10](#phase-10--llms-from-scratch) | LLMs from Scratch | 25 |
| [Phase 11](#phase-11--reasoning--test-time-compute) | Reasoning & Test-Time Compute | 8 |
| [Phase 12](#phase-12--llm-engineering) | LLM Engineering | 17 |
| [Phase 13](#phase-13--multimodal-ai) | Multimodal AI | 25 |
| [Phase 14](#phase-14--tools--protocols) | Tools & Protocols | 23 |
| [Phase 15](#phase-15--agent-engineering) | Agent Engineering | 31 |
| [Phase 16](#phase-16--autonomous-systems) | Autonomous Systems | 22 |
| [Phase 17](#phase-17--multi-agent--swarms) | Multi-Agent & Swarms | 25 |
| [Phase 18](#phase-18--infrastructure--production) | Infrastructure & Production | 35 |
| [Phase 19](#phase-19--ethics-safety--alignment) | Ethics, Safety & Alignment | 31 |
| [Phase 20](#phase-20--mechanistic-interpretability) | Mechanistic Interpretability | 8 |
| [Phase 21](#phase-21--capstone-projects) | Capstone Projects | 17 |
| **TOTAL** | | **433** |

---

## Phase 0 — Dev Environment & Tooling
> 🛠️ 12 Lessons · Get your environment ready for everything that follows

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Dev Environment | Build 🐍 (M) | Installing Python, package managers (pip), PATH setup, VS Code/Cursor/PyCharm — your entire local setup from zero |
| 02 | Git & Collaboration | Learn (S) | git init/add/commit/push/pull, branching strategies, pull requests, merge conflicts, code review — how teams actually work |
| 03 | GPU Setup & Cloud | Build 🐍 (M) | CUDA, cuDNN, checking GPU availability in PyTorch, Google Colab Pro, Kaggle kernels, Lambda Labs, RunPod |
| 04 | APIs & Keys | Build 🐍 (S) | OpenAI/Anthropic/Gemini API setup, environment variables, .env files, never hardcoding secrets, rate limits, API cost tracking |
| 05 | Jupyter Notebooks | Build 🐍 (S) | Jupyter Lab, magic commands (%timeit, %%capture), nbconvert, notebook best practices, why notebooks are dangerous in production |
| 06 | Python Environments | Build 🐍 (S) | venv, conda, pyenv, uv (the new fast standard), requirements.txt, pyproject.toml, dependency hell and how to avoid it |
| 07 | Docker for AI | Build 🐍 (M) | What Docker solves, images vs containers, Dockerfile, docker-compose, building ML images, NVIDIA Container Toolkit |
| 08 | Editor Setup | Build 🐍 (S) | VS Code extensions for ML/AI (Python, Pylance, Jupyter, GitLens, GitHub Copilot), Cursor AI editor, keybindings |
| 09 | Data Management | Build 🐍 (M) | DVC (Data Version Control), large file handling, .gitignore for datasets, cloud storage (S3/GCS buckets), data lineage |
| 10 | Terminal & Shell | Learn (S) | bash vs zsh, shell navigation (cd/ls/grep/find/awk/sed), piping, redirects, aliases, .bashrc/.zshrc |
| 11 | Linux for AI | Learn (M) | File permissions (chmod/chown), process management (ps/kill/htop), screen/tmux for long training runs, SSH, cron jobs |
| 12 | Debugging & Profiling | Build 🐍 (L) | pdb/ipdb debugger, Python profilers (cProfile, line_profiler), memory profiling (memory_profiler), PyTorch profiler |

---

## Phase 1 — Math Foundations
> 🟣 22 Lessons · The intuition behind every AI algorithm, through code

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Linear Algebra Intuition | Learn 🐍 (M) | What vectors and matrices mean geometrically, why linear algebra is the language data lives in, visual intuition first |
| 02 | Vectors, Matrices & Operations | Build 🐍 (M) | Vector addition/scaling/dot product, matrix multiplication, transpose, inverse, determinant — implemented in NumPy |
| 03 | Matrix Transformations & Eigenvalues | Build 🐍 (L) | Eigenvalues/eigenvectors geometric meaning, SVD derivation, PCA from first principles mathematically |
| 04 | Calculus for ML: Derivatives & Gradients | Learn 🐍 (M) | Limits → derivatives (power/chain/product/quotient rules), partial derivatives, gradients as direction of steepest ascent |
| 05 | Chain Rule & Automatic Differentiation | Build 🐍 (L) | Multivariable chain rule, computation graphs, forward-mode vs reverse-mode autodiff, building a tiny autograd engine |
| 06 | Probability & Distributions | Learn 🐍 (M) | Sample spaces, probability rules, conditional probability, Bernoulli, Binomial, Gaussian, Poisson, Beta, Dirichlet |
| 07 | Bayes Theorem & Statistical Thinking | Build 🐍 (M) | Bayes theorem derivation, prior/likelihood/posterior, MLE vs MAP, CLT, hypothesis testing, p-values, confidence intervals |
| 08 | Optimization: Gradient Descent Family | Build 🐍 (L) | Convexity, gradient descent from scratch, SGD, Mini-Batch GD, Momentum, NAG, AdaGrad, RMSProp, Adam, AdamW |
| 09 | Information Theory: Entropy & KL Divergence | Learn 🐍 (M) | Shannon entropy, cross-entropy, KL divergence, mutual information, Jensen-Shannon divergence, perplexity |
| 10 | Dimensionality Reduction: PCA, t-SNE, UMAP | Build 🐍 (M) | PCA (geometric intuition → math → code), t-SNE (neighbor preservation), UMAP (topology-based), when to use which |
| 11 | Singular Value Decomposition (SVD) | Build 🐍 (M) | SVD decomposition (A = UΣVᵀ), geometric interpretation, truncated SVD, SVD for image compression |
| 12 | Tensor Operations | Build 🐍 (S) | What tensors are, tensor shapes, reshaping, broadcasting rules, Einstein summation (einsum), batched operations |
| 13 | Numerical Stability | Build 🐍 (M) | Floating point arithmetic, overflow/underflow, log-sum-exp trick, numerically stable softmax |
| 14 | Norms & Distances | Build 🐍 (S) | L1/L2/Lp/Frobenius norms, cosine similarity, Euclidean/Manhattan/Chebyshev/Mahalanobis distance |
| 15 | Statistics for ML | Build 🐍 (M) | Mean/variance/covariance/correlation, t-tests, chi-square, ANOVA, effect size, statistical significance |
| 16 | Sampling Methods | Build 🐍 (M) | Monte Carlo sampling, importance sampling, rejection sampling, MCMC, Gibbs sampling |
| 17 | Linear Systems | Build 🐍 (M) | Solving Ax=b (Gaussian elimination, LU decomposition), least squares (OLS derivation), pseudoinverse |
| 18 | Convex Optimization | Build 🐍 (L) | Convex sets and functions, Lagrange multipliers, KKT conditions (used in SVMs), duality, constrained optimization |
| 19 | Complex Numbers for AI | Learn 🐍 (M) | Complex number arithmetic, Euler's formula, why this matters for Fourier transforms and RoPE positional encodings |
| 20 | The Fourier Transform | Build 🐍 (L) | DFT/FFT intuition, why it matters for audio AI, spectrograms, positional encodings, convolution theorem |
| 21 | Graph Theory for ML | Build 🐍 (M) | Graphs (nodes/edges/adjacency matrices), graph traversal, PageRank, GNN preview, knowledge graphs |
| 22 | Stochastic Processes | Learn 🐍 (M) | Random walks, Markov chains, MDP preview for RL, Brownian motion — math behind diffusion models and RL |

---

## Phase 2 — ML Fundamentals
> 🔵 20 Lessons · Classical ML — still the backbone of most production AI

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | What Is Machine Learning | Learn 🐍 (S) | Supervised/unsupervised/semi-supervised/self-supervised, batch vs online, instance-based vs model-based, ML pipeline |
| 02 | Linear Regression from Scratch | Build 🐍 (M) | Simple & multiple linear regression, OLS derivation, MLE interpretation, regression metrics (MSE/MAE/RMSE/R²), gradient descent |
| 03 | Logistic Regression & Classification | Build 🐍 (M) | Sigmoid function, binary cross-entropy, MLE derivation, gradient descent from scratch, softmax for multiclass, classification metrics |
| 04 | Decision Trees & Random Forests | Build 🐍 (L) | Decision trees (entropy, Gini impurity, information gain), Random Forest (bagging, feature importance, OOB score, bias-variance) |
| 05 | Support Vector Machines | Build 🐍 (M) | Geometric intuition, hard-margin SVM (full math), soft-margin SVM, kernel trick (RBF, polynomial) |
| 06 | KNN & Distance Metrics | Build 🐍 (M) | K-Nearest Neighbors (intuition, distance metrics, choosing K, curse of dimensionality), KNN from scratch |
| 07 | Unsupervised Learning: K-Means, DBSCAN | Build 🐍 (M) | K-Means (K-Means++ initialization, elbow method, silhouette score, from scratch), hierarchical clustering, DBSCAN |
| 08 | Feature Engineering & Selection | Build 🐍 (M) | EDA, feature scaling, encoding (ordinal/label/one-hot/target), transforms, binning, date/time features, ML Pipelines |
| 09 | Model Evaluation: Metrics, Cross-Validation | Build 🐍 (M) | Cross-validation (k-fold, stratified), precision/recall/F1/AUC-ROC, calibration, A/B testing, leakage prevention |
| 10 | Bias, Variance & the Learning Curve | Learn 🐍 (S) | Bias-variance tradeoff, underfitting vs overfitting, learning curves, validation curves, VC dimension |
| 11 | Ensemble Methods: Boosting, Bagging, Stacking | Build 🐍 (L) | Voting, Bagging, AdaBoost (step-by-step math), Gradient Boosting (math), XGBoost (full math), LightGBM, Stacking & Blending |
| 12 | Hyperparameter Tuning | Build 🐍 (M) | GridSearchCV, RandomizedSearchCV, Bayesian Optimization (Optuna), Keras Tuner |
| 13 | ML Pipelines & Experiment Tracking | Build 🐍 (L) | Scikit-learn Pipelines, MLflow, Weights & Biases (W&B), experiment tracking, model registry, reproducibility |
| 14 | Naive Bayes | Build 🐍 (M) | Conditional probability → Bayes theorem → Gaussian/Multinomial/Bernoulli NB, Laplace smoothing |
| 15 | Time Series Fundamentals | Build 🐍 (L) | Stationarity, ACF/PACF, ARIMA, seasonal decomposition, feature engineering for time series, forecasting evaluation |
| 16 | Anomaly Detection | Build 🐍 (M) | Statistical methods (Z-score, IQR, Winsorization), Isolation Forest, One-Class SVM, Local Outlier Factor |
| 17 | Handling Imbalanced Data | Build 🐍 (M) | Class imbalance, undersampling, oversampling, SMOTE, class weights |
| 18 | Feature Selection | Build 🐍 (S) | Filter/wrapper/embedded methods, PCA for selection, handling missing data (SimpleImputer, KNN Imputer, MICE) |
| 19 | Data-Centric AI I: Data Quality | Learn 🐍 (M) | Importance of data quality over model tweaking, handling noisy labels, data cleaning pipelines, outlier handling |
| 20 | Data-Centric AI II: Annotation & Active Learning | Build 🐍 (L) | Labeling pipelines, annotation tools (Label Studio), active learning loop, uncertainty sampling |

---

## Phase 3 — Deep Learning Core
> 🟢 14 Lessons · Neural networks from first principles — no frameworks until you build one

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | The Perceptron: Where It All Started | Build 🐍 (M) | Biological neuron vs mathematical perceptron, geometric intuition, perceptron trick, hinge loss, binary cross-entropy |
| 02 | Multi-Layer Networks & Forward Pass | Build 🐍 (M) | MLP notation, why we need multiple layers (XOR problem), forward propagation, universal approximation theorem, NumPy MLP |
| 03 | Backpropagation from Scratch | Build 🐍 (L) | Chain rule through computation graphs, backprop (The What/How/Why), MLP memoization, gradient flow visualization |
| 04 | Activation Functions: ReLU, Sigmoid, GELU | Build 🐍 (S) | Sigmoid, Tanh, ReLU, Leaky ReLU, Parametric ReLU, ELU, SELU, GELU, Swish — when to use what and why |
| 05 | Loss Functions: MSE, Cross-Entropy | Build 🐍 (M) | MSE, MAE, Huber loss, binary/categorical cross-entropy, focal loss, contrastive loss, triplet loss |
| 06 | Optimizers: SGD, Momentum, Adam, AdamW | Build 🐍 (L) | Batch/SGD/Mini-batch GD, exponentially weighted moving averages, SGD Momentum, NAG, AdaGrad, RMSProp, Adam, AdamW |
| 07 | Regularization: Dropout, Weight Decay | Build 🐍 (M) | L1/L2 regularization, dropout, early stopping, Batch Normalization, Layer Normalization |
| 08 | Weight Initialization & Training Stability | Build 🐍 (M) | Why initialization matters, vanishing/exploding gradients, Xavier/Glorot initialization, He initialization, gradient clipping |
| 09 | Learning Rate Schedules & Warmup | Build 🐍 (S) | Step decay, cosine annealing, warmup, cyclical learning rates, learning rate finder |
| 10 | Build Your Own Mini Framework | Build 🐍 (L) | Complete mini deep learning framework — Tensor class, autograd, optimizers, layers (like simplified PyTorch) |
| 11 | Introduction to PyTorch | Build 🐍 (L) | Tensors, autograd, nn.Module, DataLoader, training loop, saving/loading models, GPU usage |
| 12 | Introduction to JAX | Build 🐍 (M) | What JAX is, jit/vmap/grad/pmap, Flax/Haiku basics — used at Google DeepMind and top research labs |
| 13 | Debugging Neural Networks | Build 🐍 (M) | Systematic debugging (overfit one batch first), gradient checking, loss curves diagnosis, common failure modes |
| 14 | Safety Checkpoint: Representational Harms | Learn 🐍 (S) | Unintended biases in simple MLPs, data bias reflecting in weights, introduction to fairness |

---

## Phase 4 — Computer Vision
> 🟠 28 Lessons · From pixels to understanding — image, video, 3D, VLMs, and world models

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Image Fundamentals: Pixels, Channels | Learn 🐍 (S) | What a pixel is, RGB/BGR/HSV/grayscale, image arrays in NumPy, OpenCV basics, image histograms |
| 02 | Convolutions from Scratch | Build 🐍 (M) | Edge detection (Sobel, Canny), convolution operation math, padding & strides (formulas), convolution on RGB images |
| 03 | CNNs: LeNet to ResNet | Build 🐍 (L) | LeNet-5, AlexNet, VGG16, ResNet (residual connections — why they work, from scratch), EfficientNet |
| 04 | Image Classification | Build 🐍 (M) | Full CNN pipeline from scratch, callbacks, pooling layers, backpropagation in CNNs, Cat vs Dog project, MNIST |
| 05 | Transfer Learning & Fine-Tuning | Build 🐍 (M) | Feature extraction vs full fine-tuning, ImageNet/ILSVRC, pretrained model zoo, visualizing CNN filters, Keras Functional API |
| 06 | Object Detection — YOLO from Scratch | Build 🐍 (L) | R-CNN → Fast R-CNN (NMS) → Faster R-CNN → YOLO (architecture, YOLOv11 custom training, cloud deployment) |
| 07 | Semantic Segmentation — U-Net | Build 🐍 (L) | Pixel-wise classification, U-Net architecture (encoder-decoder + skip connections), coding U-Net from scratch |
| 08 | Instance Segmentation — Mask R-CNN | Build 🐍 (M) | Difference between semantic and instance segmentation, Mask R-CNN architecture, RoI Align |
| 09 | Image Generation — GANs | Build 🐍 (L) | Minimax game, GAN training from scratch, DCGAN, training instability, mode collapse, conditional GANs, StyleGAN |
| 10 | Image Generation — Diffusion Models | Build 🐍 (L) | Forward (noise) process, reverse (denoise) process, DDPM math from scratch, score matching, DDIM |
| 11 | Stable Diffusion — Architecture & Fine-Tuning | Build 🐍 (L) | Latent Diffusion Models, VAE as compressor, U-Net denoiser, CLIP text conditioning, classifier-free guidance, ControlNet, LoRA |
| 12 | Video Understanding — Temporal Modeling | Build 🐍 (M) | Video as 3D tensors, optical flow, 3D convolutions, temporal attention, video classification, action recognition |
| 13 | 3D Vision: Point Clouds, NeRFs | Build 🐍 (M) | Point cloud representation, PointNet, Neural Radiance Fields (NeRF), depth estimation |
| 14 | Vision Transformers (ViT) | Build 🐍 (M) | Patch tokenization, class token, positional embeddings, ViT architecture — attention applied to images |
| 15 | Real-Time Vision: Edge Deployment | Build 🐍 (M) | ONNX export, TensorRT, quantization for edge, mobile deployment |
| 16 | Build a Complete Vision Pipeline | Build 🐍 (L) | End-to-end: data ingestion → preprocessing → training → evaluation → serving — production-grade CV pipeline |
| 17 | Self-Supervised Vision — SimCLR, DINO, MAE | Build 🐍 (M) | Contrastive learning (SimCLR), DINO (self-distillation), Masked Autoencoders (MAE) — learning without labels |
| 18 | Open-Vocabulary Vision — CLIP | Build 🐍 (L) | Contrastive image-text pretraining, zero-shot classification, CLIP embeddings for retrieval |
| 19 | OCR & Document Understanding | Build 🐍 (M) | Text detection, text recognition, Tesseract, PaddleOCR, document layout analysis |
| 20 | Image Retrieval & Metric Learning | Build 🐍 (M) | Embedding images into metric spaces, triplet loss, contrastive loss, ArcFace, FAISS for image search |
| 21 | Keypoint Detection & Pose Estimation | Build 🐍 (M) | Human pose estimation, skeleton detection, heatmap-based detection, MediaPipe |
| 22 | 3D Gaussian Splatting from Scratch | Build 🐍 (L) | 3D-GS as alternative to NeRF, Gaussian primitives, rasterization, real-time rendering |
| 23 | Diffusion Transformers & Rectified Flow | Build 🐍 (M) | DiT (Diffusion Transformer), Rectified Flow (flow matching), used in Sora and Stable Diffusion 3 |
| 24 | SAM 3 & Open-Vocabulary Segmentation | Build 🐍 (M) | Segment Anything Model (SAM) architecture, prompt-based segmentation, zero-shot segmentation |
| 25 | Vision-Language Models (ViT-MLP-LLM) | Build 🐍 (M) | Standard VLM architecture (visual encoder + projector MLP + language decoder), LLaVA architecture |
| 26 | Monocular Depth & Geometry Estimation | Build 🐍 (M) | Estimating depth from a single image, Depth Anything, geometric understanding |
| 27 | Multi-Object Tracking & Video Memory | Build 🐍 (M) | SORT, DeepSORT, ByteTrack, tracking by detection, re-identification, video memory |
| 28 | World Models & Video Diffusion | Build 🐍 (M) | What a world model is, video diffusion (Sora, CogVideoX), GAIA, applications in autonomous driving |

---

## Phase 5 — NLP: Foundations to Advanced
> 🔴 29 Lessons · Language is the interface to intelligence

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Text Processing: Tokenization, Stemming | Build 🐍 (M) | NLP pipeline intro, text preprocessing, tokenization (word/sentence/character), stemming, lemmatization, stop words, regex |
| 02 | Bag of Words, TF-IDF & Text Representation | Build 🐍 (S) | BoW, N-grams/Bi-grams/Uni-grams, TF-IDF, sparsity problem — classical text features |
| 03 | Word Embeddings: Word2Vec from Scratch | Build 🐍 (L) | Why BoW fails, Word2Vec (CBOW + Skip-gram from scratch), negative sampling, Game of Thrones Word2Vec project |
| 04 | GloVe, FastText & Subword Embeddings | Build 🐍 (M) | GloVe (global co-occurrence matrix), FastText (character n-grams for OOV words), Average Word2Vec |
| 05 | Sentiment Analysis | Build 🐍 (L) | Rule-based (VADER), ML-based (logistic regression on TF-IDF), DL-based (RNN/LSTM sentiment) — full pipeline comparison |
| 06 | Named Entity Recognition (NER) | Build 🐍 (M) | Sequence labeling, BIO tagging scheme, CRF, spaCy NER, fine-tuning BERT for NER |
| 07 | POS Tagging & Syntactic Parsing | Build 🐍 (M) | Part-of-Speech tagging, Hidden Markov Models (HMM), Viterbi algorithm (full derivation), dependency parsing |
| 08 | Text Classification — CNNs & RNNs for Text | Build 🐍 (L) | CNNs for text (n-gram features), RNN for sentiment, types of RNN, Quora Duplicate Question Pairs project |
| 09 | Sequence-to-Sequence Models | Build 🐍 (L) | Encoder-Decoder architecture (seq2seq), teacher forcing, beam search decoding, BLEU score evaluation |
| 10 | Attention Mechanism — The Breakthrough | Build 🐍 (M) | Bahdanau attention (additive, step-by-step), Luong attention (multiplicative), solving the information bottleneck |
| 11 | Machine Translation | Build 🐍 (L) | Full NMT pipeline, evaluation (BLEU, chrF, COMET), multilingual models, low-resource translation |
| 12 | Text Summarization | Build 🐍 (M) | Extractive (TextRank) vs abstractive (seq2seq, BART, T5) summarization, ROUGE evaluation |
| 13 | Question Answering Systems | Build 🐍 (M) | Extractive QA (finding answer span), SQuAD dataset, BERT for QA, generative QA |
| 14 | Information Retrieval & Search | Build 🐍 (M) | TF-IDF retrieval, BM25 (gold standard for sparse retrieval), dense retrieval (DPR), bi-encoders vs cross-encoders |
| 15 | Topic Modeling: LDA, BERTopic | Build 🐍 (M) | Latent Dirichlet Allocation (LDA math), BERTopic (clustering embeddings), discovering themes in large corpora |
| 16 | Text Generation | Build 🐍 (M) | Language modeling, temperature, top-k sampling, nucleus (top-p) sampling, greedy vs beam search vs sampling |
| 17 | Chatbots: Rule-Based to Neural | Build 🐍 (M) | Rule-based chatbots, retrieval-based chatbots, generative chatbots, state management |
| 18 | Multilingual NLP | Build 🐍 (S) | Multilingual BERT (mBERT), XLM-R, zero-shot cross-lingual transfer, challenges of multilingual models |
| 19 | Subword Tokenization: BPE, WordPiece | Learn 🐍 (S) | Why subword tokenization exists, BPE (step by step), WordPiece (BERT tokenizer), Unigram LM, SentencePiece |
| 20 | Structured Outputs & Constrained Decoding | Build 🐍 (M) | JSON mode, grammar-constrained generation, Guidance/Outlines library, why structured outputs matter in production |
| 21 | NLI & Textual Entailment | Learn 🐍 (M) | Natural Language Inference (entailment/contradiction/neutral), SNLI/MultiNLI datasets, zero-shot classification via NLI |
| 22 | Embedding Models Deep Dive | Learn 🐍 (S) | Sentence-BERT (SBERT), E5, BGE, GTE, OpenAI embeddings, MTEB benchmark — choosing the right embedding model |
| 23 | Chunking Strategies for RAG | Build 🐍 (L) | Fixed-size chunking, recursive character splitting, semantic chunking, markdown-aware, code-aware splitting |
| 24 | Coreference Resolution | Learn 🐍 (S) | Pronoun resolution, why this matters for document understanding |
| 25 | Entity Linking & Disambiguation | Build 🐍 (M) | Linking mentions to knowledge base entities (Wikipedia/Wikidata), disambiguation |
| 26 | Relation Extraction & Knowledge Graphs | Build 🐍 (L) | Extracting (subject, relation, object) triples from text, building knowledge graphs, Graph RAG foundation |
| 27 | LLM Evaluation: RAGAS, DeepEval, G-Eval | Build 🐍 (L) | RAGAS (faithfulness/answer relevancy/context precision/recall), DeepEval framework, G-Eval (LLM-as-judge) |
| 28 | Long-Context Evaluation: NIAH, RULER | Learn 🐍 (S) | Needle-in-a-Haystack (NIAH) test, RULER benchmark, LongBench, MRCR — evaluating models at 100K+ token contexts |
| 29 | Dialogue State Tracking | Build 🐍 (M) | Tracking conversation state across turns, slot filling, dialogue acts, building a stateful conversational system |

---

## Phase 6 — Transformers Deep Dive
> 🟣 14 Lessons · The architecture that changed everything

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Why Transformers: The Problems with RNNs | Learn 🐍 (S) | Epic history of LLMs (LSTMs to ChatGPT), vanishing gradient in RNNs, BPTT, sequential computation bottleneck |
| 02 | Self-Attention from Scratch | Build 🐍 (L) | Q/K/V matrices derivation, why we need Query/Key/Value, self-attention score computation, geometric intuition, code |
| 03 | Multi-Head Attention | Build 🐍 (M) | Why multiple attention heads, concatenation + projection, multi-head vs single-head comparison |
| 04 | Positional Encoding: Sinusoidal, RoPE, ALiBi | Build 🐍 (L) | Why Transformers have no inherent position sense, sinusoidal PE (original paper), RoPE (LLaMA), ALiBi |
| 05 | The Full Transformer: Encoder + Decoder | Build 🐍 (M) | Encoder architecture, masked self-attention in decoder, cross-attention, full Transformer architecture |
| 06 | BERT — Masked Language Modeling | Build 🐍 (M) | BERT architecture (encoder-only), MLM, NSP, [CLS] token for classification, fine-tuning BERT |
| 07 | GPT — Causal Language Modeling | Build 🐍 (L) | GPT architecture (decoder-only), causal masking, autoregressive generation, GPT-1 → GPT-2 → GPT-3 → GPT-4 |
| 08 | T5, BART — Encoder-Decoder Models | Learn 🐍 (M) | T5 (text-to-text framework), BART (denoising pretraining), when to use encoder-only vs decoder-only vs encoder-decoder |
| 09 | Vision Transformers (ViT) | Build 🐍 (M) | Applying Transformers to images (patch tokenization), ViT architecture, DeiT, Swin Transformer |
| 10 | Audio Transformers — Whisper Architecture | Learn 🐍 (S) | How Whisper uses encoder-decoder Transformer on spectrogram patches, multitask tokens, timestamp prediction |
| 11 | Mixture of Experts (MoE) | Build 🐍 (M) | What MoE is (sparse activation), gating mechanism, load balancing loss, MoE in Mixtral/GPT-4/DeepSeek |
| 12 | KV Cache, Flash Attention & Inference | Build 🐍 (L) | KV cache, Flash Attention (IO-aware algorithm), Flash Attention 2&3, multi-query attention (MQA), grouped-query attention (GQA) |
| 13 | Scaling Laws | Learn 🐍 (M) | Kaplan et al. scaling laws, Chinchilla optimal compute, emergent abilities, what scaling laws tell us about future AI |
| 14 | Build a Transformer from Scratch | Build 🐍 (L) | Complete, training-ready Transformer in PyTorch (similar to Karpathy's nanoGPT) |

---

## Phase 7 — Speech & Audio
> 🟢 17 Lessons · Hear, understand, speak

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Audio Fundamentals: Waveforms, Sampling, FFT | Learn 🐍 (S) | What sound is (pressure waves), digital audio (sampling rate, bit depth), Nyquist theorem, Fast Fourier Transform (FFT) |
| 02 | Spectrograms, Mel Scale & Audio Features | Build 🐍 (M) | STFT, spectrograms, Mel scale, Mel spectrograms, MFCCs (Mel-Frequency Cepstral Coefficients) |
| 03 | Audio Classification | Build 🐍 (M) | Training CNNs on spectrograms, audio data augmentation (SpecAugment), ESC-50/AudioSet datasets |
| 04 | Speech Recognition (ASR) | Build 🐍 (L) | CTC (Connectionist Temporal Classification) loss, acoustic models, end-to-end ASR with deep speech architecture |
| 05 | Whisper: Architecture & Fine-Tuning | Build 🐍 (L) | OpenAI Whisper architecture (encoder-decoder Transformer on log-Mel spectrograms), multitask training, fine-tuning |
| 06 | Speaker Recognition & Verification | Build 🐍 (M) | Speaker embeddings (d-vectors, x-vectors), speaker verification, speaker identification, diarization |
| 07 | Text-to-Speech (TTS) | Build 🐍 (L) | Neural TTS pipeline (text → phonemes → spectrogram → waveform), Tacotron 2, FastSpeech 2, vocoders (HiFi-GAN) |
| 08 | Voice Cloning & Voice Conversion | Build 🐍 (M) | Zero-shot voice cloning (XTTS), voice conversion, ethical considerations |
| 09 | Music Generation | Build 🐍 (L) | MusicGen (Meta), AudioCraft, melody conditioning, music continuation |
| 10 | Audio-Language Models | Build 🐍 (M) | Models that understand both audio and text (Qwen-Audio, Gemini Audio), audio captioning, audio QA |
| 11 | Real-Time Audio Processing | Build 🐍 (M) | Streaming audio, ring buffers, low-latency inference |
| 12 | Build a Voice Assistant Pipeline | Build 🐍 (L) | Full pipeline: microphone → VAD → ASR (Whisper) → LLM → TTS → speaker — the voice AI product loop |
| 13 | Neural Audio Codecs — EnCodec, SNAC, Mimi | Learn 🐍 (M) | Compressing audio into discrete tokens (residual vector quantization), why this enables audio language models |
| 14 | Voice Activity Detection & Turn-Taking | Build 🐍 (M) | Detecting when someone is speaking (VAD), silence detection, endpointing, handling turn-taking |
| 15 | Streaming Speech-to-Speech — Moshi | Learn 🐍 (M) | Real-time duplex speech models, streaming architecture, latency constraints, Moshi (Kyutai) architecture |
| 16 | Voice Anti-Spoofing & Audio Watermarking | Build 🐍 (M) | Detecting synthetic/cloned voices, audio deepfake detection, SynthID for audio |
| 17 | Audio Evaluation — WER, MOS, MMAU | Learn 🐍 (S) | Word Error Rate (WER), Character Error Rate (CER), Mean Opinion Score (MOS), MMAU benchmark |

---

## Phase 8 — Generative AI
> 💗 14 Lessons · Create images, video, audio, 3D, and more

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Generative Models: Taxonomy & History | Learn 🐍 (S) | Landscape of generative models (explicit vs implicit density), VAEs, GANs, Normalizing Flows, Diffusion, Autoregressive |
| 02 | Autoencoders & VAE | Build 🐍 (L) | Autoencoders (reconstruction loss, bottleneck), VAEs (reparameterization trick, ELBO derivation, KL term, latent space) |
| 03 | GANs: Generator vs Discriminator | Build 🐍 (L) | Minimax game, JS divergence connection, Wasserstein GAN (WGAN, gradient penalty), training instability, mode collapse |
| 04 | Conditional GANs & Pix2Pix | Build 🐍 (L) | Class-conditional generation (cGAN), image-to-image translation (Pix2Pix), paired training data, CycleGAN (unpaired) |
| 05 | StyleGAN | Build 🐍 (M) | StyleGAN architecture (mapping network, AdaIN, progressive growing), style mixing, GAN evaluation (FID, IS) |
| 06 | Diffusion Models — DDPM from Scratch | Build 🐍 (L) | Forward diffusion (adding Gaussian noise step by step), reverse diffusion (learning to denoise), DDPM loss derivation |
| 07 | Latent Diffusion & Stable Diffusion | Build 🐍 (L) | Why compress to latent space first, VAE as compressor, U-Net denoiser in latent space, Stable Diffusion full architecture |
| 08 | ControlNet, LoRA & Conditioning | Build 🐍 (M) | ControlNet (conditioning on edges/depth/pose), LoRA for diffusion fine-tuning, DreamBooth, textual inversion |
| 09 | Inpainting, Outpainting & Editing | Build 🐍 (M) | Masked image editing, DALL-E style inpainting, Prompt2Prompt, Instruct-Pix2Pix |
| 10 | Video Generation | Build 🐍 (L) | Temporal diffusion models, DiT for video, Sora architecture (spacetime patches), CogVideoX, Wan2.1 |
| 11 | Audio Generation | Build 🐍 (M) | AudioLDM (latent diffusion for audio), MusicGen (autoregressive), AudioCraft |
| 12 | 3D Generation | Build 🐍 (M) | Text-to-3D (DreamFusion, Zero-1-to-3), 3D Gaussian Splatting for generation |
| 13 | Flow Matching & Rectified Flows | Build 🐍 (L) | Flow matching (ODE-based generation), Rectified Flow (Stable Diffusion 3, FLUX) |
| 14 | Evaluation: FID, CLIP Score | Build 🐍 (S) | FID (Fréchet Inception Distance), CLIP Score (text-image alignment), IS (Inception Score), human evaluation |

---

## Phase 9 — Reinforcement Learning
> 🟣 13 Lessons · The foundation of RLHF and game-playing AI

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | MDPs, States, Actions & Rewards | Learn 🐍 (M) | Markov Decision Processes, state/action/reward/transition/discount, return, Bellman equation, episodic vs continuing tasks |
| 02 | Dynamic Programming | Build 🐍 (L) | Policy evaluation, policy improvement, policy iteration, value iteration — solving MDPs when you know the environment |
| 03 | Monte Carlo Methods | Build 🐍 (M) | Learning from experience (no model needed), MC prediction, MC control, importance sampling |
| 04 | Q-Learning, SARSA | Build 🐍 (L) | Temporal Difference learning, Q-Learning, SARSA, exploration vs exploitation (ε-greedy, UCB, Thompson sampling) |
| 05 | Deep Q-Networks (DQN) | Build 🐍 (L) | DQN, experience replay, target network, Double DQN, Dueling DQN, Atari game playing |
| 06 | Policy Gradients — REINFORCE | Build 🐍 (L) | Policy gradient theorem (derivation), REINFORCE algorithm, baseline (variance reduction), advantage function |
| 07 | Actor-Critic — A2C, A3C | Build 🐍 (L) | Combining value-based and policy-based, A2C, asynchronous A3C, Generalized Advantage Estimation (GAE) |
| 08 | PPO | Build 🐍 (L) | Proximal Policy Optimization — clipped surrogate objective, why PPO is dominant, PPO for LLMs (RLHF connection) |
| 09 | Reward Modeling & RLHF | Build 🐍 (L) | InstructGPT pipeline, human preferences, training a reward model, PPO with reward model, DPO, Constitutional AI (RLAIF) |
| 10 | Multi-Agent RL | Build 🐍 (M) | Cooperative vs competitive agents, MADDPG, QMIX, MAPPO, emergent behavior |
| 11 | Sim-to-Real Transfer | Build 🐍 (M) | Training in simulation, domain randomization, sim-to-real gap, applications in robotics |
| 12 | RL for Games | Build 🐍 (M) | AlphaGo/AlphaZero (MCTS + RL), self-play, OpenAI Five (DOTA), Libratus (poker) |
| 13 | RL → LLM Alignment Transition | Learn 🐍 (S) | Conceptual bridge: How standard RL concepts map directly to LLM alignment and Phase 10 |

---

## Phase 10 — LLMs from Scratch
> 🟧 25 Lessons · Build, train, and understand large language models

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Tokenizers: BPE, WordPiece, SentencePiece | Build 🐍 (M) | Why tokenization matters, BPE algorithm step-by-step, WordPiece, Unigram, SentencePiece — implement from scratch |
| 02 | Building a Tokenizer from Scratch | Build 🐍 (L) | Full BPE tokenizer: training vocabulary, encode/decode functions, special tokens, handling edge cases |
| 03 | Data Pipelines for Pre-Training | Build 🐍 (L) | Large-scale data collection (CommonCrawl, The Pile, FineWeb), deduplication, quality filtering, streaming datasets |
| 04 | Pre-Training a Mini GPT (124M) | Build 🐍 (L) | Training full GPT-2-sized model from scratch: architecture, data loading, training loop, checkpointing, evaluation |
| 05 | Distributed Training, FSDP, DeepSpeed | Build 🐍 (L) | Data parallelism (DDP), model parallelism, pipeline parallelism, FSDP, DeepSpeed ZeRO stages |
| 06 | Synthetic Data Generation Pipelines | Build 🐍 (L) | Self-play, rejection sampling, Alpaca/Magpie/WizardLM generation, Self-Instruct at scale |
| 07 | Instruction Tuning — SFT | Build 🐍 (L) | Supervised Fine-Tuning on instruction-following data (Alpaca format), FLAN, chat templates, system prompts |
| 08 | RLHF — Reward Model + PPO | Build 🐍 (L) | Full RLHF pipeline: preference data → reward model (Bradley-Terry) → PPO with reward model → alignment evaluation |
| 09 | DPO — Direct Preference Optimization | Build 🐍 (M) | DPO derivation (bypassing reward model), DPO vs PPO tradeoffs, IPO, KTO, SimPO — preference optimization landscape |
| 10 | Constitutional AI & Self-Improvement | Build 🐍 (L) | Constitutional AI (RLAIF), self-critique and revision, Anthropic's approach to alignment |
| 11 | Continual Learning & Catastrophic Forgetting | Build 🐍 (M) | Rehearsal mechanisms, Elastic Weight Consolidation (EWC), updating LLMs without destroying prior knowledge |
| 12 | Safety Checkpoint: Model Evals | Learn 🐍 (S) | Recognizing alignment drift, benchmarking safety vs capability tradeoffs during fine-tuning |
| 13 | Evaluation — Benchmarks, Evals | Build 🐍 (M) | MMLU, HumanEval, GSM8K, HellaSwag, BIG-bench, MT-Bench, Arena-Hard — measuring what actually matters |
| 14 | Quantization: INT8, GPTQ, AWQ, GGUF | Build 🐍 (M) | Why quantization, PTQ vs QAT, GPTQ, AWQ, GGUF (for llama.cpp), bitsandbytes |
| 15 | Inference Optimization | Build 🐍 (M) | KV cache management, continuous batching, PagedAttention (vLLM), speculative decoding, Flash Attention |
| 16 | Building a Complete LLM Pipeline | Build 🐍 (L) | End-to-end: pretrain → SFT → RLHF/DPO → evaluate → quantize → serve |
| 17 | Open Models: Architecture Walkthroughs | Learn 🐍 (M) | LLaMA 3 (GQA, RoPE, RMSNorm), Mistral/Mixtral (sliding window attention, MoE), Phi-3/4, Gemma 3 |
| 18 | Speculative Decoding and EAGLE-3 | Build 🐍 (L) | Draft model + verification model (2-3x speedup), EAGLE (tree-structured speculative decoding), EAGLE-3 |
| 19 | Differential Attention (V2) | Build 🐍 (M) | Differential Attention mechanism (cancelling attention noise), implementation, performance gains |
| 20 | Native Sparse Attention (DeepSeek NSA) | Build 🐍 (M) | DeepSeek's Native Sparse Attention, block-sparse patterns, hardware-efficient implementation for long contexts |
| 21 | Multi-Token Prediction (MTP) | Build 🐍 (L) | Predicting multiple future tokens simultaneously, training objective, inference-time use |
| 22 | DualPipe Parallelism | Learn 🐍 (M) | DeepSeek's DualPipe for pipeline parallelism, overlapping computation and communication |
| 23 | DeepSeek-V3 Architecture Walkthrough | Learn 🐍 (S) | MLA (Multi-head Latent Attention), MoE, MTP, DualPipe, FP8 training — why DeepSeek changed the cost narrative |
| 24 | Jamba — Hybrid SSM-Transformer | Learn 🐍 (S) | Mamba (State Space Models), combining SSM blocks with Transformer attention (Jamba), linear-time sequence modeling |
| 25 | Async and Hogwild! Inference | Build 🐍 (M) | Asynchronous inference, Hogwild! parallel SGD, lock-free updates — production inference at scale |

---

## Phase 11 — Reasoning & Test-Time Compute
> 🟨 8 Lessons · The frontier of AI reasoning (o1/o3/DeepSeek-R1 paradigms)

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Test-Time Compute Paradigm Shift | Learn 🐍 (S) | Why scaling inference computes is the new frontier, comparison of pre-training vs test-time scaling curves |
| 02 | Chain of Thought & Reasoning Paths | Build 🐍 (M) | Eliciting long reasoning traces, prompting for reflection, building o1-style "thinking" outputs |
| 03 | Process Reward Models (PRMs) | Build 🐍 (L) | Outcome Reward Models (ORMs) vs PRMs, step-by-step verification, training PRMs using mathematical reasoning datasets |
| 04 | Best-of-N Sampling & Rejection Sampling | Build 🐍 (L) | Generating N reasoning paths, scoring with PRMs, selecting the best path for final output |
| 05 | Monte Carlo Tree Search (MCTS) for Language | Build 🐍 (L) | Applying AlphaGo-style MCTS to language generation, exploring reasoning branches, UCT algorithm |
| 06 | Q-Star / Expert Iteration Concepts | Learn 🐍 (M) | Iterative self-improvement, using test-time compute to generate superior training data for the base model |
| 07 | DeepSeek-R1 Architecture & Distillation | Learn 🐍 (M) | Cold-start data generation, pure RL for reasoning discovery, how R1 distills reasoning into smaller dense models |
| 08 | Building a Reasoning Wrapper | Build 🐍 (L) | Creating a custom inference pipeline that loops, verifies, and corrects itself before answering |

---

## Phase 12 — LLM Engineering
> 🟥 17 Lessons · Put LLMs to work in production

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Prompt Engineering: Techniques & Patterns | Build 🐍 (M) | Zero-shot, few-shot, system prompts, role prompting, delimiters, structured prompts, hallucination mitigation |
| 02 | Few-Shot, CoT, Tree-of-Thought | Build 🐍 (M) | Few-shot in-context learning, Chain-of-Thought (CoT), zero-shot CoT, Tree-of-Thought (ToT), Self-Consistency, ReAct |
| 03 | Structured Outputs | Build 🐍 (M) | JSON mode, grammar-constrained generation, Pydantic for output validation, Instructor library, function calling |
| 04 | Embeddings & Vector Representations | Build 🐍 (S) | Embedding models, cosine similarity, FAISS (flat/IVF/HNSW), Pinecone, Chroma, Qdrant, Weaviate — vector DB operations |
| 05 | Context Engineering | Build 🐍 (M) | What context engineering is, system prompt design, conversation history management, dynamic context assembly |
| 06 | RAG: Retrieval-Augmented Generation | Build 🐍 (L) | Full LangChain RAG: document loaders → text splitters → embeddings → vector store → retriever → generator |
| 07 | Advanced RAG: Chunking, Reranking | Build 🐍 (L) | Advanced retrieval (MMR, hybrid search, contextual compression, parent doc retriever, self-query), RAG Fusion, HyDE, CRAG, Self-RAG, Graph RAG |
| 08 | Fine-Tuning with LoRA & QLoRA | Build 🐍 (L) | Full fine-tuning vs PEFT, LoRA (low-rank decomposition math), QLoRA, PEFT library, adapters, instruction tuning, SFT |
| 09 | Model Merging | Build 🐍 (L) | SLERP, TIES-merging, DARE, Task Arithmetic, merging LoRA adapters with base models for multi-task capabilities |
| 10 | Function Calling & Tool Use | Build 🐍 (L) | OpenAI/Anthropic function calling APIs, tool schema definition, parallel calls, streaming calls, handling tool errors |
| 11 | Evaluation & Testing | Build 🐍 (M) | RAGAS framework (all metrics), DeepEval, G-Eval (LLM-as-judge), regression testing, LangSmith observability (full course) |
| 12 | Caching, Rate Limiting & Cost | Build 🐍 (M) | Semantic caching, prompt caching (Anthropic/OpenAI prefix caching), rate limit handling, cost tracking, batch APIs |
| 13 | Guardrails & Safety | Build 🐍 (L) | Input/output validation, Llama Guard, Nemo Guardrails, PII detection and scrubbing, prompt injection defense |
| 14 | Building a Production LLM App | Build 🐍 (L) | End-to-end LLM application: FastAPI + vector DB + LLM + Streamlit UI + Docker + cloud deployment |
| 15 | Model Context Protocol (MCP) | Build 🐍 (L) | What MCP is, MCP architecture, MCP lifecycle, connecting to Claude Desktop, building local/remote servers, MCP clients |
| 16 | Prompt Caching & Context Caching | Build 🐍 (M) | Anthropic's prompt caching (cache prefix, 90% cost reduction), OpenAI's context caching, when caching helps |
| 17 | Multi-Adapter Serving | Build 🐍 (M) | Dynamically loading LoRA adapters per request (LoRAX), efficient multi-tenant serving |

---

## Phase 13 — Multimodal AI
> 🟩 25 Lessons · See, hear, read, and reason across modalities

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Vision Transformers and Patch-Token | Learn 🐍 (S) | How images become token sequences (patchification), the bridge between vision and language |
| 02 | CLIP and Contrastive Vision-Language | Build 🐍 (L) | CLIP training (image encoder + text encoder + contrastive loss on 400M pairs), zero-shot classification |
| 03 | BLIP-2 Q-Former as Modality Bridge | Build 🐍 (L) | Q-Former as lightweight bridge between frozen image encoder and frozen LLM, instruction-following with images |
| 04 | Flamingo and Gated Cross-Attention | Learn 🐍 (M) | Flamingo's approach (gated cross-attention layers into frozen LLM), few-shot multimodal learning, perceiver resampler |
| 05 | LLaVA and Visual Instruction Tuning | Build 🐍 (L) | LLaVA architecture (CLIP encoder + MLP projector + LLaMA), visual instruction tuning dataset creation |
| 06 | Any-Resolution Vision — Patch-n-Pack | Build 🐍 (M) | Processing images at native resolution, dynamic patching, NaFlex for flexible aspect ratios |
| 07 | Open-Weight VLM Recipes | Learn 🐍 (S) | Practical lessons from training VLMs (data quality > quantity, connector design, training stages) |
| 08 | LLaVA-OneVision: Single, Multi, Video | Build 🐍 (L) | Unifying single image, multi-image, and video understanding in one model |
| 09 | Qwen-VL Family and Dynamic-FPS Video | Learn 🐍 (M) | Qwen2-VL (naive dynamic resolution, dynamic FPS for video), position IDs for 2D images |
| 10 | InternVL3 Native Multimodal Pretraining | Learn 🐍 (M) | Training vision and language jointly from scratch |
| 11 | Chameleon Early-Fusion Token-Only | Build 🐍 (L) | Treating image tokens and text tokens identically (no separate vision encoder), joint vocabulary |
| 12 | Emu3 Next-Token Prediction | Learn 🐍 (M) | Using the same autoregressive objective for both understanding and generation |
| 13 | Transfusion Autoregressive + Diffusion | Build 🐍 (M) | Combining autoregressive LM (for text) with diffusion (for images) in a single model |
| 14 | Show-o Discrete-Diffusion Unified | Learn 🐍 (S) | Unified model using discrete diffusion for both text and image generation |
| 15 | Janus-Pro Decoupled Encoders | Build 🐍 (M) | Using different visual encoders for understanding vs generation (decoupled) |
| 16 | MIO Any-to-Any Streaming | Learn 🐍 (M) | Any-to-any multimodal model (any modality input → any modality output), streaming generation |
| 17 | Video-Language Temporal Grounding | Build 🐍 (L) | Finding the moment in a video described by text, temporal localization, dense video captioning |
| 18 | Long-Video at Million-Token Context | Build 🐍 (M) | Processing hour-long videos with memory-efficient attention for very long token sequences |
| 19 | Audio-Language Models: Whisper to AF3 | Build 🐍 (L) | Models that understand both audio and language (Qwen-Audio, Gemini Audio, AudioFlamingo 3) |
| 20 | Omni Models: Thinker-Talker Streaming | Build 🐍 (L) | Models that see/hear/speak simultaneously (GPT-4o style), streaming omni architecture |
| 21 | Embodied VLAs: RT-2, OpenVLA, π0, GR00T | Learn 🐍 (M) | Vision-Language-Action models for robotics, RT-2, π0 (Physical Intelligence), GR00T (NVIDIA humanoid) |
| 22 | Document and Diagram Understanding | Build 🐍 (L) | Processing PDFs/scans with vision (not OCR), chart/diagram understanding, DocVQA, infographic understanding |
| 23 | ColPali Vision-Native Document RAG | Build 🐍 (M) | RAG without OCR (embed document page images directly), late interaction retrieval (ColPali) |
| 24 | Multimodal RAG and Cross-Modal Retrieval | Build 🐍 (L) | Retrieving across modalities (text query → image results), FAISS for image embeddings |
| 25 | Multimodal Agents and Computer-Use | Build 🐍 (L) | Agents that see the screen and use computers (Claude Computer Use, GPT-4V + browser), GUI grounding |

---

## Phase 14 — Tools & Protocols
> 🟦 23 Lessons · The interfaces between AI and the real world

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | The Tool Interface | Learn 🐍 (S) | What tools mean for LLMs (function calling abstraction), tool schemas (JSON Schema), tool selection problem |
| 02 | Function Calling Deep Dive | Build 🐍 (L) | OpenAI/Anthropic function calling APIs, defining tool schemas, the full request-response cycle, handling edge cases |
| 03 | Parallel and Streaming Tool Calls | Build 🐍 (M) | Calling multiple tools simultaneously, streaming tool call deltas, handling partial results |
| 04 | Structured Output | Build 🐍 (M) | JSON mode, Pydantic integration, Instructor library, guaranteed structured outputs for production |
| 05 | Tool Schema Design | Learn 🐍 (M) | Principles for writing good tool descriptions, parameter naming, optional vs required, enum values |
| 06 | MCP Fundamentals | Learn 🐍 (S) | What MCP solves (the N×M tool integration problem), MCP vs raw APIs, client-server model, Anthropic specification |
| 07 | Building an MCP Server | Build 🐍 (L) | Python MCP server from scratch (MCP SDK), exposing tools/resources/prompts, connecting to Claude Desktop |
| 08 | Building an MCP Client | Build 🐍 (M) | MCP client that connects to any MCP server, session management, capability negotiation |
| 09 | MCP Transports | Learn 🐍 (S) | stdio transport (local), SSE/HTTP transport (remote), choosing the right transport |
| 10 | MCP Resources and Prompts | Build 🐍 (M) | Exposing data as Resources (files, DB results), reusable Prompts, dynamic resource content |
| 11 | MCP Sampling | Build 🐍 (L) | Server-initiated LLM calls, agentic patterns via sampling |
| 12 | MCP Roots and Elicitation | Build 🐍 (M) | Roots (constraining server filesystem access), Elicitation (server requesting user input) |
| 13 | MCP Async Tasks | Build 🐍 (M) | Long-running operations via MCP, progress reporting, cancellation |
| 14 | MCP Apps | Build 🐍 (L) | Building complete applications with MCP: blog writer agent, resume chat, database integration |
| 15 | MCP Security I — Tool Poisoning | Learn 🐍 (M) | Tool poisoning attacks (malicious tool descriptions that hijack the LLM), prompt injection via tools |
| 16 | MCP Security II — OAuth 2.1 | Build 🐍 (L) | Securing MCP servers with OAuth 2.1, PKCE, token validation, authorization flows |
| 17 | MCP Gateways and Registries | Learn 🐍 (S) | Central MCP gateway (routing to multiple servers), MCP server registries (discovery), Smithery |
| 18 | MCP Auth in Production — DCR + JWKS | Build 🐍 (M) | Dynamic Client Registration (DCR), JWKS (JSON Web Key Sets), production auth patterns |
| 19 | A2A Protocol | Build 🐍 (L) | Google's Agent-to-Agent protocol, Agent Cards, Task objects, A2A vs MCP |
| 20 | OpenTelemetry GenAI | Build 🐍 (M) | Tracing LLM calls with OpenTelemetry, semantic conventions for GenAI, distributed tracing across agent hops |
| 21 | LLM Routing Layer | Learn 🐍 (M) | Routing requests to different LLMs based on capability/cost/latency (LiteLLM, RouteLLM) |
| 22 | Skills and Agent SDKs | Learn 🐍 (M) | OpenAI Agents SDK, Anthropic's tool use patterns, standardized skill interfaces |
| 23 | Capstone — Tool Ecosystem | Build 🐍 (L) | Complete tool ecosystem: MCP server + MCP client + OAuth + OpenTelemetry tracing + LLM routing |

---

## Phase 15 — Agent Engineering
> 🟧 31 Lessons · Build agents from first principles

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | What Is an Agent | Learn 🐍 (S) | Agent = LLM + memory + tools + planning loop, Generative AI vs Agentic AI, the agency spectrum |
| 02 | The Agent Loop | Build 🐍 (L) | Observe → Think → Act → Observe loop, ReAct (Reasoning + Acting) implementation from scratch, stopping conditions |
| 03 | Memory Types | Build 🐍 (M) | In-context, external (vector DB), episodic, semantic, procedural memory — LLMs don't have memory (what this means + solution) |
| 04 | Short-Term Memory in LangGraph | Build 🐍 (L) | Implementing conversation memory in LangGraph, checkpointing, thread-level persistence, LangGraph + SQLite |
| 05 | Long-Term Memory in LangGraph | Build 🐍 (L) | Cross-conversation memory, memory extraction and storage, memory retrieval, user preference storage |
| 06 | Planning Strategies | Build 🐍 (L) | Chain-of-Thought planning, Plan-and-Execute, Reflection (agent critiques its own output), MCTS for planning |
| 07 | LangGraph Core | Build 🐍 (M) | LangChain vs LangGraph, stateful graphs (nodes + edges + state), StateGraph, sequential/parallel/conditional/iterative workflows |
| 08 | LangGraph Persistence & Streaming | Build 🐍 (M) | Checkpointing (MemorySaver, SqliteSaver, PostgresSaver), streaming (stream_mode: values/updates/messages) |
| 09 | Human-in-the-Loop (HITL) | Build 🐍 (M) | Interrupt before/after node execution, propose-then-commit pattern, user approval for high-stakes actions |
| 10 | Tool-Using Agents | Build 🐍 (L) | Connecting LangGraph agents to tools, ToolNode, error handling in tool calls, LangGraph + MCP client integration |
| 11 | RAG Agents | Build 🐍 (L) | Agentic RAG (agent decides when/how to retrieve), adaptive RAG, self-RAG in LangGraph, corrective RAG (CRAG) flow |
| 12 | Subgraphs and Modular Agents | Build 🐍 (L) | Composing agents from sub-agents (subgraphs), state sharing between parent/child graphs, reusable agent components |
| 13 | LangSmith Observability | Build 🐍 (M) | LangSmith crash course, tracing every agent step, evaluating agent outputs, debugging agent failures |
| 14 | Code Agents | Build 🐍 (L) | Agents that write and execute code (Python REPL tool), sandboxed execution, code interpreter pattern, E2B sandbox |
| 15 | Web Browsing Agents | Build 🐍 (L) | Browser automation (Playwright/Selenium), web search tools, scraping + summarizing |
| 16 | File System Agents | Build 🐍 (M) | Agents that read/write files, directory navigation, file editing (with diffs), version control integration |
| 17 | Agent Evaluation | Build 🐍 (M) | Evaluating agents (task completion rate, tool call accuracy, efficiency), trajectory evaluation, AgentBench, SWE-bench |
| 18 | Failure Modes & Robustness | Learn 🐍 (M) | Common agent failures (infinite loops, hallucinated tool calls, context overflow), error recovery strategies |
| 19 | Agent Security & Safety Checkpoint | Learn 🐍 (M) | Prompt injection in agents (indirect injection via tool results), privilege escalation, implementing safe tool usage borders |
| 20 | Stateless vs Stateful Agents | Build 🐍 (M) | When to use stateless vs stateful, state schema design, state compression for long contexts |
| 21 | OpenAI Agents SDK | Build 🐍 (M) | Agents, Handoffs, Guardrails, Tracing in OpenAI's SDK, building with the official framework |
| 22 | LangChain Agent Ecosystem | Build 🐍 (M) | Full LangChain agent toolkit (tools, chains, runnables, LangChain hub) |
| 23 | CrewAI | Build 🐍 (L) | CrewAI framework (agents with roles, tasks, crews), sequential vs hierarchical process, memory in CrewAI |
| 24 | Agent Benchmarks | Learn 🐍 (S) | SWE-bench, WebArena, GAIA, AgentBench — measuring agent capability |
| 25 | Agent Patterns Catalog | Learn 🐍 (M) | Prompt chaining, routing, parallelization, orchestrator-subagent, evaluator-optimizer — standard patterns |
| 26 | Cost & Latency Optimization | Build 🐍 (M) | Token budget management, caching agent decisions, parallel tool calls, choosing right model per subtask |
| 27 | Production Agent Architecture | Build 🐍 (L) | Durable execution (Temporal/Inngest), queue-based agents, retry logic, idempotency |
| 28 | Blog Writer Agent Project | Build 🐍 (L) | Agent that plans → researches (web search) → writes → edits blog posts automatically — LangGraph + tools |
| 29 | Coding Agent Project | Build 🐍 (L) | Agent that reads GitHub issue → plans → writes code → runs tests → creates PR |
| 30 | Voice Agent Project | Build 🐍 (L) | Full voice agent: speech input → ASR → agent loop → TTS → speech output |
| 31 | AutoGPT and BabyAGI Internals | Learn 🐍 (S) | Understanding how early autonomous agent loop structures worked and failed |

---

## Phase 16 — Autonomous Systems
> 🟩 22 Lessons · Long-horizon agents, self-improvement, and the 2026 safety stack

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Long-Horizon Agents (METR) | Learn 🐍 (S) | METR's task complexity taxonomy, what long-horizon means (hours of autonomous work), current capability frontier |
| 02 | STaR, V-STaR, Quiet-STaR | Learn 🐍 (M) | Self-Taught Reasoner (STaR — generating rationales to improve itself), V-STaR (verified), Quiet-STaR |
| 03 | AlphaEvolve: Evolutionary Coding Agents | Learn 🐍 (S) | Google DeepMind's AlphaEvolve, evolutionary algorithms + LLMs for algorithm discovery |
| 04 | Darwin Gödel Machine: Self-Modifying | Learn 🐍 (S) | Theoretical self-improving agents, Darwin Gödel Machine (evolutionary self-modification) |
| 05 | AI Scientist v2: Workshop-Level Research | Learn 🐍 (M) | Automated ML research (hypothesis → experiment → paper → peer review) — Sakana AI's AI Scientist |
| 06 | Automated Alignment Research (AAR) | Learn 🐍 (M) | Using AI to do alignment research, interpretability automation, scalable oversight via AI assistance |
| 07 | Recursive Self-Improvement | Learn 🐍 (S) | The recursive self-improvement scenario, capability gain curves, alignment stability under self-modification |
| 08 | Bounded Self-Improvement Designs | Learn 🐍 (M) | Safe self-improvement (bounded domains, verification gates, sandboxing), practical implementations |
| 09 | Autonomous Coding Agent Landscape | Learn 🐍 (S) | SWE-bench Verified scores, CodeAct (code as actions), Devin/SWE-agent/OpenHands |
| 10 | Claude Code Permission Modes | Learn 🐍 (M) | Claude's agentic coding modes (yolo/auto/ask), bash tool, file edit tool, MCP integration |
| 11 | Browser Agents & Prompt Injection | Learn 🐍 (M) | Agents that browse the web, indirect prompt injection via webpage content, defense mechanisms |
| 12 | Durable Execution for Long-Running Agents | Learn 🐍 (L) | Workflow engines (Temporal, Inngest, Cloudflare Workflows), checkpointing long agent runs |
| 13 | Action Budgets, Cost Governors | Learn 🐍 (M) | Bounding agent resource consumption (token budget, wall-clock time, cost limit, iteration count) |
| 14 | Kill Switches, Canary Tokens | Learn 🐍 (M) | Emergency shutdown mechanisms, circuit breakers for tool calls, canary tokens |
| 15 | HITL: Propose-Then-Commit | Learn 🐍 (M) | Human approval for irreversible actions, minimal footprint principle |
| 16 | Checkpoints and Rollback | Learn 🐍 (L) | Saving agent state at each step, rollback to previous state on failure, agent undo mechanisms |
| 17 | Constitutional AI & Rule Overrides | Learn 🐍 (M) | Hard-coded vs soft-coded behaviors, Constitutional AI in agentic contexts, rule hierarchies |
| 18 | Llama Guard & Input/Output Classification | Learn 🐍 (M) | Llama Guard (open-source content classifier), ShieldGemma, input sanitization, output validation |
| 19 | Responsible Scaling Policy v3.0 | Learn 🐍 (S) | RSP (capability thresholds, safety cases, deployment restrictions), ASL-2/ASL-3/ASL-4 definitions |
| 20 | Preparedness Framework & FSF | Learn 🐍 (S) | OpenAI's Preparedness Framework, DeepMind's Frontier Safety Framework, dangerous capability evaluation |
| 21 | Time Horizons & External Evaluation | Learn 🐍 (M) | METR's task horizon evaluation (15-min → 1-hour → 1-day tasks), third-party capability evaluation |
| 22 | CAIS, CAISI, & Societal-Scale Risk | Learn 🐍 (S) | Center for AI Safety (CAIS), catastrophic risk scenarios, governance mechanisms |

---

## Phase 17 — Multi-Agent & Swarms
> 🟩 25 Lessons · Coordination, emergence, and collective intelligence

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Why Multi-Agent | Learn 🐍 (S) | When one agent isn't enough (parallelism, specialization, verification), multi-agent vs single-agent tradeoffs |
| 02 | FIPA-ACL Heritage and Speech Acts | Learn 🐍 (S) | History of multi-agent communication (FIPA standards), speech acts (request/inform/propose/agree) |
| 03 | Communication Protocols | Build 🐍 (M) | Message passing between agents (shared state vs message queue vs direct call), communication topology |
| 04 | The Multi-Agent Primitive Model | Learn 🐍 (S) | Agents as primitives (identity, memory, capabilities, communication), the basic unit of multi-agent systems |
| 05 | Supervisor / Orchestrator-Worker | Build 🐍 (L) | Orchestrator agent that plans and delegates, worker agents that execute, LangGraph supervisor pattern |
| 06 | Hierarchical Architecture | Learn 🐍 (M) | Nested hierarchies of agents, task decomposition strategies, decomposition drift |
| 07 | Society of Mind and Multi-Agent Debate | Build 🐍 (L) | Minsky's Society of Mind, multi-agent debate (agents argue toward better answers), self-consistency |
| 08 | Role Specialization | Build 🐍 (M) | Planner / Critic / Executor / Verifier — specialization improves quality, role assignment strategies |
| 09 | Parallel Swarm and Networked | Build 🐍 (L) | All agents run simultaneously (no central orchestrator), peer-to-peer communication, emergent coordination |
| 10 | Group Chat and Speaker Selection | Build 🐍 (M) | AutoGen-style group chat, speaker selection strategies (round-robin, LLM-based, topic-based) |
| 11 | Handoffs and Routines | Build 🐍 (L) | OpenAI Swarm pattern (agents hand off to other agents), routines, stateless orchestration |
| 12 | A2A — Agent-to-Agent Protocol | Build 🐍 (L) | Google's A2A protocol, Agent Cards (capability advertisement), Task lifecycle, streaming, push notifications |
| 13 | Shared Memory and Blackboard | Build 🐍 (M) | Blackboard architecture (shared workspace all agents read/write) |
| 14 | Consensus & Byzantine Fault Tolerance | Build 🐍 (M) | Agents reaching agreement (consensus algorithms), Byzantine agents (malicious or faulty), fault-tolerant systems |
| 15 | Voting, Self-Consistency, and Debate | Build 🐍 (M) | Majority voting, self-consistency (sample multiple times, take most common answer), debate graph topologies |
| 16 | Negotiation and Bargaining | Build 🐍 (M) | Agents that negotiate (allocating tasks, resolving conflicts), auction mechanisms, game theory for coordination |
| 17 | Generative Agents & Emergent Simulation | Build 🐍 (L) | Stanford's Generative Agents (25 agents in a virtual town), emergent social behaviors |
| 18 | Theory of Mind & Emergent Coordination | Build 🐍 (M) | Agents modeling other agents' beliefs/goals, coordination without explicit communication |
| 19 | Swarm Optimization (PSO, ACO) | Build 🐍 (M) | Particle Swarm Optimization, Ant Colony Optimization — classical swarm intelligence applied to LLM agents |
| 20 | MARL — MADDPG, QMIX, MAPPO | Learn 🐍 (L) | Multi-Agent RL (centralized training decentralized execution), MADDPG, QMIX, MAPPO |
| 21 | Agent Economies, Token Incentives | Learn 🐍 (M) | Economic mechanisms for agent coordination, reputation systems, token-based resource allocation |
| 22 | Production Scaling | Build 🐍 (L) | Running 100s of agents reliably (message queues, Redis, Celery), distributed checkpointing |
| 23 | Failure Modes — MAST, Groupthink | Learn 🐍 (S) | Multi-Agent Safety Taxonomy (MAST), groupthink, monoculture risk |
| 24 | Evaluation & Coordination Benchmarks | Learn 🐍 (M) | Evaluating multi-agent systems (task completion, coordination efficiency, communication overhead) |
| 25 | Case Studies & 2026 State of the Art | Learn 🐍 (S) | OpenAI o3/o4-mini agentic use, Claude's multi-agent features, Gemini 2.5 Pro agents |

---

## Phase 18 — Infrastructure & Production
> ⬛ 35 Lessons · Ship AI to the real world at scale (Now including GPU Kernel Programming)

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Managed LLM Platforms | Learn 🐍 (S) | AWS Bedrock, Azure OpenAI, Google Vertex AI — comparing managed offerings, when to use managed vs self-hosted |
| 02 | Inference Platform Economics | Learn 🐍 (M) | Fireworks, Together AI, Baseten, Modal — cost-per-token comparison, latency benchmarks, choosing a provider |
| 03 | GPU Autoscaling on Kubernetes | Learn 🐍 (M) | Karpenter (node autoscaling), KAI Scheduler (GPU-aware scheduling), scaling from 0 to 100 GPUs automatically |
| 04 | vLLM Serving Internals | Learn 🐍 (L) | PagedAttention, continuous batching, chunked prefill — why vLLM is the standard |
| 05 | EAGLE-3 Speculative Decoding in Prod | Learn 🐍 (M) | Running EAGLE-3 in vLLM, production speculative decoding setup, measuring speedup |
| 06 | SGLang and RadixAttention | Learn 🐍 (M) | SGLang for prefix-heavy workloads (shared prefixes cached via RadixAttention) |
| 07 | TensorRT-LLM with FP8 | Learn 🐍 (M) | NVIDIA's TensorRT-LLM, FP8 precision on H100/B100/B200, kernel fusion |
| 08 | Inference Metrics — TTFT, TPOT, Goodput | Learn 🐍 (M) | Time-to-First-Token (TTFT), Time-per-Output-Token (TPOT), Inter-Token Latency (ITL), Goodput, P99 latency |
| 09 | Production Quantization — AWQ, GPTQ | Learn 🐍 (S) | Choosing quantization method for production, quality vs speed tradeoff, GGUF for CPU inference |
| 10 | Cold Start Mitigation for Serverless | Learn 🐍 (S) | Cold starts, mitigation strategies (keep-warm, provisioned concurrency, model caching) |
| 11 | Multi-Region LLM Serving | Learn 🐍 (S) | Geo-distributed serving, KV cache locality, global load balancing |
| 12 | Edge Inference — ANE, WebGPU, Jetson | Learn 🐍 (M) | Apple Neural Engine, Qualcomm Hexagon, WebGPU for browser inference, NVIDIA Jetson |
| 13 | LLM Observability Stack Selection | Learn 🐍 (S) | LangSmith, Langfuse, Helicone, Arize, Weave — comparing observability platforms |
| 14 | Prompt & Semantic Caching Economics | Learn 🐍 (M) | Provider-level prompt caching, semantic caching (GPTCache), measuring cache hit rates and cost savings |
| 15 | Batch APIs — the 50% Discount | Learn 🐍 (M) | OpenAI/Anthropic batch APIs (async, 50% cheaper), when to use batch, batch job management |
| 16 | Model Routing as a Cost-Reduction Primitive| Learn 🐍 (S) | Routing easy queries to cheap models and hard queries to capable models (RouteLLM) |
| 17 | Disaggregated Prefill/Decode | Learn 🐍 (M) | NVIDIA Dynamo (separating prefill and decode into different machines), why disaggregation improves utilization |
| 18 | vLLM Production Stack with LMCache | Learn 🐍 (M) | LMCache (KV cache offloading to CPU/disk), complete vLLM production stack configuration |
| 19 | AI Gateways | Learn 🐍 (M) | LiteLLM (unified API over 100+ LLMs), Portkey, Kong AI Gateway, Bifrost |
| 20 | Shadow, Canary, and Progressive Deployment | Learn 🐍 (L) | Shadow deployment, canary (1% of traffic), progressive rollout (1% → 10% → 100%) |
| 21 | A/B Testing LLM Features | Learn 🐍 (M) | GrowthBook, Statsig for LLM A/B tests, statistical significance for open-ended outputs |
| 22 | Load Testing LLM APIs | Build 🐍 (L) | k6 for load testing, LLMPerf (LLM-specific), GenAI-Perf (NVIDIA), defining SLOs |
| 23 | SRE for AI — Multi-Agent Incident Response| Learn 🐍 (M) | On-call for AI systems, runbooks for LLM outages, alert fatigue |
| 24 | Chaos Engineering for LLM Production | Learn 🐍 (M) | Injecting failures (API timeouts, model errors, KV cache eviction), ensuring graceful degradation |
| 25 | Security — Secrets, PII Scrubbing, Logs | Learn 🐍 (L) | Secret management (Vault, AWS Secrets Manager), PII detection and redaction in LLM I/O, audit logging |
| 26 | Compliance — SOC 2, HIPAA, GDPR | Learn 🐍 (M) | What compliance means for AI systems, data residency requirements, EU AI Act risk tiers |
| 27 | FinOps for LLMs — Unit Economics | Learn 🐍 (M) | Cost per user/query/task, multi-tenant cost attribution, LLM budget alerts, cost anomaly detection |
| 28 | Self-Hosted Serving Selection | Learn 🐍 (S) | llama.cpp (CPU), Ollama (developer experience), TGI (Hugging Face), vLLM (production), SGLang (prefix) |
| 29 | Safety Checkpoint: Production Threat Models| Learn 🐍 (S) | Mapping threats across the serving layer, data pipelines, and public APIs |
| 30 | CUDA 101: GPU Hardware Architecture | Learn 🐍 (M) | What is a GPU, Streaming Multiprocessors (SMs), Threads, Blocks, Grids — for absolute beginners |
| 31 | CUDA Memory Hierarchy | Learn 🐍 (M) | Global vs Shared vs Registers, coalesced memory access, memory bandwidth limitations |
| 32 | Writing a basic CUDA Kernel | Build 🐍 (L) | Writing matrix multiplication in PyCUDA/C++, compiling, dispatching grids |
| 33 | Warp-Level Primitives | Build 🐍 (L) | Warps, warp divergence, shuffle instructions, thread synchronization (`__syncthreads()`) |
| 34 | Triton 101: Pythonic Kernel Programming | Build 🐍 (L) | Intro to OpenAI Triton, writing a fused kernel (e.g., fused Softmax) in Python, performance vs PyTorch |
| 35 | Profiling Kernels with Nsight | Build 🐍 (M) | Using NVIDIA Nsight Compute to profile kernels, identify memory bottlenecks, optimize occupancy |

---

## Phase 19 — Ethics, Safety & Alignment
> 🟪 31 Lessons · Build AI that helps humanity — not optional

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Instruction-Following as Alignment Signal | Learn 🐍 (S) | What alignment means operationally, instruction following as proxy for alignment, Goodhart's Law |
| 02 | Reward Hacking & Goodhart's Law | Learn 🐍 (M) | Classic reward hacking examples, specification gaming, proxy alignment vs true alignment |
| 03 | Direct Preference Optimization Family | Learn 🐍 (M) | DPO, IPO, KTO, SimPO, ORPO — the full landscape of preference optimization |
| 04 | Sycophancy as RLHF Amplification | Learn 🐍 (M) | Models agreeing with users even when wrong, sycophancy as alignment failure, detection and mitigation |
| 05 | Constitutional AI & RLAIF | Learn 🐍 (M) | Anthropic's Constitutional AI (AI giving feedback using a constitution), RLAIF vs RLHF |
| 06 | Mesa-Optimization & Deceptive Alignment | Learn 🐍 (M) | Inner alignment problem, deceptive alignment (model behaves well during training, differently at deployment) |
| 07 | Sleeper Agents — Persistent Deception | Learn 🐍 (S) | Anthropic's sleeper agents paper (models that hide malicious behaviors until triggered) |
| 08 | In-Context Scheming in Frontier Models | Learn 🐍 (M) | Apollo Research's scheming evaluation, frontier models showing deceptive behaviors in evaluations |
| 09 | Alignment Faking | Learn 🐍 (M) | Anthropic's alignment faking paper — models pretending to be aligned to avoid modification |
| 10 | AI Control — Safety Despite Subversion | Learn 🐍 (L) | Redwood Research's AI Control (building systems safe even if the AI is trying to subvert them) |
| 11 | Scalable Oversight & Weak-to-Strong | Learn 🐍 (L) | Debate (two AIs argue, human judges), recursive reward modeling, OpenAI's weak-to-strong generalization |
| 12 | Red-Teaming: PAIR & Automated Attacks | Build 🐍 (L) | PAIR (Prompt Automatic Iterative Refinement), automated red-teaming, jailbreak taxonomies |
| 13 | Many-Shot Jailbreaking | Learn 🐍 (M) | Exploiting long context (100+ examples to override safety), Anthropic's paper, defenses |
| 14 | ASCII Art & Visual Jailbreaks | Build 🐍 (M) | Using ASCII art/images to bypass text safety filters, multimodal jailbreaks |
| 15 | Indirect Prompt Injection | Build 🐍 (M) | Injecting instructions via tool results/web content/documents — the #1 agent security threat |
| 16 | Red-Team Tooling: Garak, Llama Guard | Build 🐍 (L) | Garak (LLM vulnerability scanner), Llama Guard (content classifier), Microsoft PyRIT |
| 17 | WMDP & Dual-Use Capability Evaluation | Learn 🐍 (S) | Weapons of Mass Destruction Proxy (WMDP) benchmark, evaluating uplift for bio/chem/cyber/nuclear risks |
| 18 | Frontier Safety Frameworks | Learn 🐍 (S) | Anthropic RSP v3.0, OpenAI Preparedness Framework, DeepMind Frontier Safety Framework |
| 19 | Model Welfare Research | Learn 🐍 (S) | Do LLMs have morally relevant experiences? Anthropic's model welfare team, moral patienthood uncertainty |
| 20 | Bias & Representational Harm | Build 🐍 (M) | Measuring bias (demographic parity, equalized odds, calibration), SHAP for bias attribution, debiasing |
| 21 | Causal Inference & ML Fairness | Build 🐍 (L) | Structural causal models, counterfactual fairness, why purely correlational fairness metrics fail |
| 22 | Fairness Criteria: Group, Individual | Learn 🐍 (M) | Mathematical definitions of fairness (incompatibility theorem), choosing appropriate criteria |
| 23 | Differential Privacy for LLMs | Build 🐍 (L) | DP-SGD (training with privacy guarantees), ε-δ privacy, membership inference attacks, private fine-tuning |
| 24 | Watermarking: SynthID, Stable Signature | Build 🐍 (M) | Google SynthID (invisible watermarks for AI images/text), Stable Signature, C2PA content provenance |
| 25 | Regulatory Frameworks | Learn 🐍 (M) | EU AI Act (risk tiers), US Executive Order on AI, UK AI Safety Institute, Korea AI Act |
| 26 | EchoLeak & CVEs for AI | Learn 🐍 (M) | EchoLeak (data exfiltration via prompt injection), CVE tracking for AI vulnerabilities, responsible disclosure |
| 27 | Model, System & Dataset Cards | Build 🐍 (M) | Writing model cards (intended use, limitations, evaluation), system cards, dataset cards |
| 28 | Data Provenance & Training Governance | Learn 🐍 (M) | Where training data comes from, copyright issues, C4/RedPajama/ROOTS governance, data consent |
| 29 | Alignment Research Ecosystem | Learn 🐍 (S) | MATS, Redwood Research, Apollo Research, METR — how to get into alignment research |
| 30 | Moderation Systems | Build 🐍 (L) | OpenAI Moderation API, Perspective API (Jigsaw), Llama Guard 3, building custom moderation pipelines |
| 31 | Dual-Use Risk: Cyber, Bio, Chem, Nuclear | Learn 🐍 (S) | AI uplift for dangerous capabilities, responsible publication norms, red lines in AI development |

---

## Phase 20 — Mechanistic Interpretability
> 🔬 8 Lessons · Opening the black box of LLMs (Anthropic's core focus)

| # | Lesson | Type | What's Inside |
|---|--------|------|---------------|
| 01 | Introduction to Mech Interp | Learn 🐍 (S) | What is mechanistic interpretability? Reverse-engineering neural networks, motivation, Transformer Lens basics |
| 02 | Superposition & Polysemanticity | Learn 🐍 (M) | Why individual neurons don't correspond to single concepts, superposition hypothesis, the toy models of superposition paper |
| 03 | Sparse Autoencoders (SAEs) | Build 🐍 (L) | Training SAEs to extract monosemantic features from dense activations, Anthropic's SAE scaling breakthroughs |
| 04 | Circuits Analysis | Build 🐍 (L) | Induction heads (how models do in-context learning), identifying specific subgraphs (circuits) that perform tasks |
| 05 | Activation Patching & Causal Tracing | Build 🐍 (L) | Causal interventions to prove a circuit's function, patching activations between prompts |
| 06 | Attribution Methods | Build 🐍 (L) | Integrated gradients, ROME (Rank-One Model Editing), MEMIT — attributing facts to specific MLP layers |
| 07 | Universal Features & Universality | Learn 🐍 (M) | Do different models learn the same features? Convergent evolution in neural networks |
| 08 | Automated Interpretability | Build 🐍 (M) | Using LLMs to generate explanations for SAE features automatically, scaling interpretability pipelines |

---

## Phase 21 — Capstone Projects
> 🏆 17 Projects · End-to-end shippable products — 20-40 hours each

| # | Project | Phases Combined |
|---|---------|-----------------|
| 01 | Terminal-Native Coding Agent | P0 + P5 + P6 + P10 + P12 + P14 + P15 + P16 + P18 + P19 |
| 02 | RAG over Codebase (Cross-Repo Semantic Search) | P5 + P6 + P12 + P14 + P18 |
| 03 | Real-Time Voice Assistant (ASR → LLM → TTS) | P6 + P7 + P12 + P14 + P15 + P18 |
| 04 | Multimodal Document QA (Vision-First) | P4 + P5 + P6 + P12 + P13 + P18 |
| 05 | Autonomous Research Agent (AI-Scientist Class) | P0 + P2 + P3 + P6 + P10 + P15 + P16 + P17 + P19 |
| 06 | DevOps Troubleshooting Agent for Kubernetes | P12 + P14 + P15 + P16 + P18 + P19 |
| 07 | End-to-End Fine-Tuning Pipeline | P2 + P3 + P6 + P10 + P12 + P18 + P19 |
| 08 | Production RAG Chatbot (Regulated Vertical) | P5 + P6 + P12 + P13 + P18 + P19 |
| 09 | Code Migration Agent (Repo-Level Upgrade) | P5 + P6 + P12 + P14 + P15 + P16 + P18 |
| 10 | Multi-Agent Software Engineering Team | P12 + P14 + P15 + P16 + P17 + P18 |
| 11 | LLM Observability & Eval Dashboard | P12 + P14 + P18 + P19 |
| 12 | Video Understanding Pipeline (Scene → QA) | P4 + P6 + P7 + P12 + P13 + P18 |
| 13 | MCP Server with Registry and Governance | P12 + P14 + P15 + P18 + P19 |
| 14 | Speculative-Decoding Inference Server | P3 + P6 + P10 + P18 |
| 15 | Constitutional Safety Harness + Red-Team Range | P10 + P12 + P14 + P15 + P19 |
| 16 | GitHub Issue-to-PR Autonomous Agent | P12 + P14 + P15 + P16 + P18 |
| 17 | Personal AI Tutor (Adaptive, Multimodal) | P5 + P7 + P12 + P13 + P15 + P18 + P19 |

---

## 📚 Foundational Papers — Mapped to Phases

| Paper | Authors | Year | Phase |
|-------|---------|------|-------|
| Attention Is All You Need | Vaswani et al. | 2017 | Phase 6 |
| Improving Language Understanding by Generative Pre-Training | Radford et al. | 2018 | Phase 10 |
| GPT-3: Language Models are Few-Shot Learners | Brown et al. | 2020 | Phase 10 |
| Denoising Diffusion Probabilistic Models | Ho et al. | 2020 | Phase 8 |
| Training language models to follow instructions (InstructGPT) | Ouyang et al. | 2022 | Phase 10 |
| Direct Preference Optimization (DPO) | Rafailov et al. | 2023 | Phase 10 |
| Chain-of-Thought Prompting | Wei et al. | 2022 | Phase 11 |
| ReAct: Reasoning + Acting in LLMs | Yao et al. | 2022 | Phase 15 |
| MCP: Model Context Protocol | Anthropic | 2024 | Phase 14 |
| CLIP | Radford et al. | 2021 | Phase 13 |
| Scaling Laws for Neural Language Models | Kaplan et al. | 2020 | Phase 6 |
| LLaVA: Visual Instruction Tuning | Liu et al. | 2023 | Phase 13 |
| Constitutional AI | Bai et al. | 2022 | Phase 19 |
| Model Cards for Model Reporting | Mitchell et al. | 2019 | Phase 19 |
| System Cards, a new resource for understanding AI systems | Meta AI | 2023 | Phase 19 |
| Sleeper Agents | Hubinger et al. | 2024 | Phase 19 |
| Flash Attention | Dao et al. | 2022 | Phase 6 |
| LoRA: Low-Rank Adaptation | Hu et al. | 2021 | Phase 12 |
| DeepSeek-V3 Technical Report | DeepSeek | 2025 | Phase 10 |
| AlphaFold 2 | Jumper et al. | 2021 | Phase 6 |

---

## 📊 Complete Summary