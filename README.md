## Table of Contents
- [Setting Up Docker Jupyter Notebook](#setup_docker_jupyter)
- [Syllabus](#syllabus)

## Setting Up Docker Jupyter Notebook

1. Create a folder in the root directory:
```
mkdir jupyter_vold
```
2. In the directory ```jupyter_docker_setup``` create a file named ```.env```.

3. Put the following content in the ```.env``` file:
```
JUPYTER_TOKEN=<your_secret_token>
HOST_VOLUME=<path_of_your_repository>/jupyter_vol
```

4. Create the jupyter notebook container using this command:
```
docker-compose -f jupyter_docker_setup/docker-compose.yaml up --build -d
```


## Syllabus

<details>
  <summary><strong>Module 1: Introduction to MLOps</strong></summary>

- **What is MLOps?**
- Importance of MLOps in the ML lifecycle
- Key principles and practices of MLOps Lifecycle:
  - Model Development to Deployment
- Comparison of MLOps with DevOps
- MLOps Workflow and Components:
  - (CI-CD)
  - (CM/CT)
  - (Experiment Tracking)
  - (Model Registries)
  - (Feature Stores)
  - (Different Model Deployment Strategies)
  - (Data Drift)
  - (Model Drift)
- MLOps in the Context of Large-Scale Machine Learning Workflows

</details>

<details>
  <summary><strong>Module 2: Linux & Git Fundamentals</strong></summary>

- **Introduction to Linux and Git**
- Setting Up WSL2/Linux VM/Linux OS
- Basic Linux commands: Navigation || File Management || Process Management
- Installing and Managing Software in Linux
- System Monitoring and Performance Tuning in Linux
- Shell Scripting Basics
- Git basics: Version Control || Branching || Merging
- Git workflow: Commit || Push || Pull || Forks || Pull Requests || Code reviews
- GitHub Actions

</details>

<details>
  <summary><strong>Module 3: Building Machine Learning Workflow and Project Setup</strong></summary>

- **GitHub and its role in machine learning projects:**
  - Setting up a project template with GitHub: Best practices for organizing and structuring code repositories
- **Modular Workflow Introduction and Implementation:**
  - Understanding the importance of modular workflows in machine learning
  - Implementing modular workflows using Python and other tools
  - Best practices for modular workflow design and implementation
- **Understanding the Training Pipeline and Its Components**
- **Creating Prediction Pipeline and End Point Creation:**
  - Techniques for creating prediction pipelines using scikit-learn and TensorFlow
  - Creating endpoints for prediction pipelines using FastAPI and other tools
- **Intro to CI/CD and CT:**
  - Techniques for implementing CI/CD using GitHub Actions (local setup)

</details>

<details>
  <summary><strong>Module 4: Machine Learning Fundamentals</strong></summary>

- Introduction to Machine Learning
- Types of Machine Learning: Supervised || Unsupervised || Reinforcement Learning
- Data Preprocessing || Processing || Transformation
- Machine Learning algorithms: Linear Regression || Decision Trees || Random Forest
- Model evaluation metrics: Accuracy || Precision || Recall || F1 Score
- Model selection and hyperparameter tuning
- Model deployment and monitoring with FastAPI/Flask

</details>

<details>
  <summary><strong>Module 5: Deep Learning Fundamentals</strong></summary>

- Introduction to Deep Learning
- Core Neural Network Architectures: CNNs || RNN || GANs
  - Neural Networks || Autoencoders || Generative Adversarial Networks
- Activation Functions and Layer Essentials
- Training Neural Networks: Backpropagation and Optimization
- Deep Learning Frameworks: TensorFlow || PyTorch || Keras
- Training Challenges and Solutions
- Hyperparameter Optimization and Fine-Tuning Models
- Deep Learning for Structured and Unstructured Data Types

</details>

<details>
  <summary><strong>Module 6: Fundamentals of Computer Vision</strong></summary>

- **Introduction to Computer Vision**
- **Key Computer Vision Tasks**: Filtering || Thresholding || Edge Detection
- **Feature Extraction**
- **Image Processing Techniques**:
  - Object detection and recognition
  - Deep Learning Applications in Computer Vision:
    - Batch || Real-time CV Applications
- **Computer Vision Toolbox**: OpenCV || TensorFlow || and More
- **Challenges in Computer Vision**
- **Lab**: Object Detection with YOLOv5/v8

</details>

<details>
  <summary><strong>Module 7: Fundamentals of Natural Language Processing</strong></summary>

- **Introduction to NLP**
- **Syntax || Semantics || Pragmatics**
- **Data Preparation and Word Embeddings**
- **Deep Learning in NLP**
- **NLP Toolbox**
- **Fundamentals of RNN || Transformers || LLM Architectures**
- **Future Directions in NLP**

</details>

<details>
  <summary><strong>Module 8: Docker and Containerization for ML Engineers</strong></summary>

- **Introduction to Docker**
- **Docker Basics**: Images || Containers || Volumes
- **Container Networking**
- **Redis Deployment and Integration**
- **Kafka Deployment and Integration**
- **Elasticsearch Deployment and Integration**
- **Docker for ML**: Building and running ML containers
- **Docker Best Practices**: Image optimization || Containerization
- **Explore Over 30 Hands-On Docker Lab Scenarios in the Poridhi Lab Environment**

</details>

<details>
  <summary><strong>Module 9: AWS Cloud Fundamentals for ML Workflow</strong></summary>

- **Introduction to AWS**
- **AWS Networking**
- **AWS Basics**: EC2 || S3 || Lambda
- **AWS for ML**: Deploying ML models to AWS
- **AWS Best Practices**: Cost optimization || Security
- **Explore Over 40 Hands-On AWS and ML Scenarios in the Poridhi Lab Environment**

</details>

<details>
  <summary><strong>Module 10: ML Workflows with AWS SageMaker</strong></summary>

- **Introduction to End-to-End MLOps Platforms**
- **Introduction to Amazon SageMaker**: ML Development and Deployment (Lab)
- **Explore Over 50 Hands-On AWS Lab Scenarios in the Poridhi Lab Environment**

</details>

<details>
  <summary><strong>Module 11: Kubernetes for Scaling ML Workloads</strong></summary>

- **Introduction to Kubernetes**
- **Kubernetes Architecture and Theory**
- **Kubernetes Basics**: Pods || Services || Deployments
- **Deploy k3s Cluster in AWS**
- **Working with Poridhi Kubernetes Cluster**
- **Understanding Kubernetes Networking for Debugging**
- **Kubernetes for ML**: Deploying ML models to Kubernetes
- **Kubernetes Best Practices**: Resource allocation || Scalability
- **Explore Over 100 Hands-On Kubernetes Lab Scenarios in the Poridhi Lab Environment**

</details>

<details>
  <summary><strong>Module 12: ML Workflows with KubeFlow</strong></summary>

- **Deploying KubeFlow on Poridhi Kubernetes Clusters/EKS**  
- **End-to-end ML Workflow with KubeFlow**  

</details>

<details>
  <summary><strong>Module 13: Introduction to Ray</strong></summary>

- **Challenges in Traditional Machine Learning Workflows**  
- **Benefits of Distributed Computing in Machine Learning**  
- **How Ray Addresses These Challenges**  
- **Ray Architecture**:  
  - Core Components of Ray:  
    - Ray Core  
    - Ray Tune  
    - Ray Serve  
    - Ray Train  
- **Ray's Distributed Scheduler**  
- **Actors and Tasks**  
- **Raylets || Object Store and Shared Memory**  
- **Execution and Resource Management**  
- **Overview of ML Workflow on Ray**  

</details>

<details>
  <summary><strong>Module 14: Deploying and Setting up Ray Clusters</strong></summary>

- **Deploying and Managing Clusters**  
- **Setting up Ray Clusters on Local Machine**  
- **Setting up Ray Clusters on Cloud (AWS)**  
- **Autoscaling**  

</details>

<details>
  <summary><strong>Module 15: Deploying Ray Clusters on KubeRay</strong></summary>

- **Setting up Ray Clusters on Kubernetes**:  
  - AWS EKS Cluster  
  - Poridhi Kubernetes Cluster  

</details>

<details>
  <summary><strong>Module 16: Setting up Monitoring and Observability for Ray Clusters</strong></summary>

- **Setting up Ray Dashboard**  
- **Setting up Prometheus for Ray Clusters**  
- **Setting up Grafana for Ray Clusters**  

</details>

<details>
  <summary><strong>Module 17: Building a Python App with Ray Core API</strong></summary>

- **Introduction to Ray Core API**:  
  - Overview of Ray Core API  
  - Use Cases for Ray Core API  
- **Implementing Ray Core Concepts**:  
  - **Tasks and Remote Functions**:  
    - Defining and Using Remote Functions  
    - Task Scheduling and Execution  
  - **Actors**:  
    - Creating and Managing Actors  
    - State Management with Actors  
  - **Object Store**:  
    - Sharing and Accessing Data  
    - Optimizing Object Storage Usage  
- **Building A Ray Application**: Deploying a Flask/Django App on Ray Cluster  

</details>

<details>
  <summary><strong>Module 18: Data Concepts and Data Processing with Ray Datasets</strong></summary>

- **Overview of Distributed Data Processing**  
- **Distributed Data Processing with Ray Datasets**:  
  - Data Ingestion and Loading  
  - Data Transformation and Manipulation  
  - Data Export and Storage  
  - Advanced Data Transformations  
- **Parallel Processing with Ray**  
- **Scaling Data Workloads**  
- **Optimizing Performance**:  
  - Data Persistence and Checkpointing  
  - Efficient Data Partitioning  
  - Minimizing Data Shuffling  
  - Leveraging Caching  
- **Integrating Ray Datasets with Other Libraries**  
- **Designing Efficient Data Pipelines**  
- **Fault Tolerance and Recovery**  

</details>

<details>
  <summary><strong>Module 19: Experiment Tracking and Model Metadata Management Tools</strong></summary>

- **Introduction to Experiment Tracking and Model Metadata Management**  
- **MLflow with Ray Clusters**: Experiment Tracking || Model Versioning || Model Serving  
- **Weights & Biases with Ray Clusters**: Experiment Tracking || Model Versioning || Model Serving  
- **Setting up TensorBoard for Ray Clusters**  
- **Best Practices for Experiment Tracking and Model Metadata Management**  

</details>

<details>
  <summary><strong>Module 20: Training Large Scale ML Models with Ray Train</strong></summary>

- **Understanding Ray Train Concepts**:  
  - Overview of Distributed Training  
  - Core Components of Ray Train  
  - Parallel and Distributed Training Strategies  

- **Data Preparation for Large Scale Training**:  
  - Loading and Preprocessing Data  
  - Efficient Data Partitioning  
  - Handling Large Datasets  

- **Model Training with Ray Train**:  
  - Defining and Configuring Models  
  - Using Ray Train API for Training  
  - Implementing Custom Training Loops  

- **Distributed Training Techniques**:  
  - Data Parallelism  
  - Model Parallelism  
  - Hybrid Parallelism  

- **Integrating with Popular ML Frameworks**:  
  - Using Ray Train with TensorFlow  
  - Using Ray Train with PyTorch  
  - Integrating with Other ML Libraries  

- **Model Evaluation and Validation**:  
  - Evaluating Model Performance  
  - Implementing Validation and Testing  
  - Cross-Validation Strategies  

- **Best Practices for Training Large Scale Models with Ray Train**:  
  - Designing Efficient Training Pipelines  
  - Managing Cluster Resources  
  - Ensuring Model Quality and Consistency  

</details>

<details>
  <summary><strong>Module 21: Data and Pipeline Versioning Tools</strong></summary>

- **Introduction to Data and Pipeline Versioning**  
- **DVC with Ray Clusters**:  
  - Data Versioning  
  - Data Management  
  - Data Collaboration  
- **Pachyderm**:  
  - Data Versioning  
  - Data Pipelines  
- **Best Practices for Data and Pipeline Versioning**  

</details>

<details>
  <summary><strong>Module 22: Hyperparameter Tuning/Optimization with Ray Tune</strong></summary>

- **Understanding Ray Tune Concepts**:  
  - Overview of Hyperparameter Tuning  
  - Core Components of Ray Tune  
  - Parallel and Distributed Search Strategies  

- **Defining Hyperparameter Search Space**:  
  - Specifying Hyperparameters  
  - Defining Search Space and Distributions  
  - Configuring Search Algorithms  

- **Search Algorithms and Schedulers**:  
  - Random Search  
  - Grid Search  
  - Bayesian Optimization  
  - Hyperband and ASHA  
  - Population Based Training (PBT)  

- **Running Hyperparameter Tuning Jobs**:  
  - Setting Up Training Functions  
  - Using Ray Tune API for Tuning  
  - Implementing Custom Schedulers  

- **Advanced Hyperparameter Tuning Techniques**:  
  - Multi-Objective Optimization  
  - Transfer Learning for Tuning  
  - Early Stopping Strategies  

- **Integrating Ray Tune with ML Frameworks**:  
  - Ray Tune with TensorFlow  
  - Ray Tune with PyTorch  
  - Integrating with Other ML Libraries  

- **Monitoring and Analyzing Tuning Jobs**:  
  - Using Ray Dashboard and Integrated Tools for Monitoring  
  - Logging and Visualization Tools  
  - Analyzing Hyperparameter Search Results  

- **Performance Optimization**:  
  - Profiling and Debugging Tuning Jobs  
  - Optimizing Resource Utilization  

</details>

<details>
  <summary><strong>Module 23: Training Reinforcement Learning Models with Ray RLlib</strong></summary>

- **Understanding Ray RLlib Concepts**:  
  - Overview of Reinforcement Learning  
  - Core Components of RLlib  
  - Policies and Algorithms  

- **Defining and Configuring RL Environments**:  
  - Supported Environments (e.g., OpenAI Gym)  
  - Custom Environments  
  - Environment Configuration  

- **Implementing RL Algorithms**:  
  - DQN, PPO, A3C, and More  
  - Customizing and Extending Algorithms  
  - Policy Training and Evaluation  

- **Advanced Features and Techniques**:  
  - Multi-Agent Training  
  - Model Parallelism  
  - Curriculum Learning  

- **Best Practices for RL Training with RLlib**:  
  - Designing Efficient RL Pipelines  
  - Managing Cluster Resources  
  - Ensuring Reproducibility  

</details>

<details>
  <summary><strong>Module 24: Deploying and Serving Models with Ray Serve</strong></summary>

- **Introduction to Model Deployment Patterns and Serving**  
- **Best Practices and Tools for Model Deployment and Serving**  
- **TensorFlow Serving**: Serving TensorFlow Models  
- **FastAPI in Depth**  
- **ONNX Runtime**: Serving ONNX Models  
- **Ray Serve**: Scalable Model Serving  

- **Understanding Ray Serve Concepts**:  
  - Core Components of Ray Serve  
  - Deployment Graphs and Pipelines  
  - Managing Endpoints  

- **Defining and Deploying Models**:  
  - Preparing Models for Deployment  
  - Using Ray Serve API for Deployment  
  - Handling Multiple Models and Versions  

- **Routing and Load Balancing**:  
  - Configuring Routing Policies  
  - Implementing Load Balancing Strategies  
  - Ensuring High Availability  

- **Scalable Model Serving**:  
  - Horizontal and Vertical Scaling  
  - Auto-scaling Based on Traffic  
  - Managing Resource Allocation  

- **Monitoring and Management**:  
  - Using Ray Dashboard for Monitoring  
  - Logging and Metrics Collection  
  - Managing Model Lifecycles  

- **Performance Optimization**:  
  - Profiling and Debugging Serving Pipelines  
  - Reducing Latency and Improving Throughput  
  - Optimizing Resource Utilization  

- **Fault Tolerance and Reliability**:  
  - Ensuring Fault Tolerance in Serving  
  - Handling Failures and Recovery  
  - Implementing Health Checks and Retries  

- **Common Pitfalls and How to Avoid Them**:  
  - Debugging Common Issues in Model Serving  
  - Handling Large Model Sizes  
  - Avoiding Bottlenecks in Serving Pipeline  

</details>

<details>
  <summary><strong>Module 25: Model Monitoring in Ray Clusters</strong></summary>

- **Introduction to Model Monitoring**  
- **Best Practices for Model Monitoring**:  
  - Why Monitoring Matters  
  - Observability in ML Models  
  - Monitoring Targets in ML  
  - Logging for ML Model Monitoring  
  - Tracing for ML Systems  
  - Monitoring Machine Learning Models in Production  
  - Model Monitoring and Logging  
- **Prometheus**: Metrics Collection and Alerting  
- **Grafana**: Dashboarding and Visualization  
- **Evidently AI**: Data and Model Drift Detection  

</details>

<details>
  <summary><strong>Module 26: Introduction to LLMs</strong></summary>

- **Introduction to LLMs**  
- **LLM Architectures**: Transformer, GPT, BERT, T5, LLama  
- **Transformer Architecture**:  
  - Key Components: Self-Attention || Multi-head Attention  
  - Transformer Encoder and Decoder  
- **Building an LLM from Scratch with Ray**:  
  - Fundamentals of Natural Language Processing (NLP)  
  - Data Collection and Preprocessing  
  - Model Architecture Design  
  - Training Strategies and Techniques  

</details>

<details>
  <summary><strong>Module 27: Building Scalable RAG Applications with Ray and LangChain</strong></summary>

- **LLMOps Libraries & Frameworks**: LangChain, LangServe  
- **Open-source LLMs and HuggingFace Ecosystem**  
- **Vector Databases**  
- **Fine-Tuning LLMs**  
- **LLM Applications**:  
  - Text Generation  
  - Question Answering  
  - Summarization  

</details>

<details>
  <summary><strong>Module 28: Introduction to Scalable Agentic Workflows</strong></summary>

- **Introduction to Agentic Workflows with LangChain and Autogen**  
- **Project**: Deploying an Agentic Workflow for a Repetitive Task  

</details>

<details>
  <summary><strong>Module 29: Feature Stores and Databases</strong></summary>

- **Introduction to Feature Stores**  
- **Feast**: Data Storage || Data Processing || Data Serving  
- **Tecton**: Feature Engineering || Feature Serving  
- **Best Practices for Feature Engineering and Management**  

**The following tasks may need to be moved up in the sequence of modules**:  
- Setting up Apache Kafka  
- Setting up Elasticsearch  
- Setting up MySQL || MongoDB  
- Setting up Redis  

</details>

<details>
  <summary><strong>Module 30: Orchestration and Workflow Pipelines</strong></summary>

- **Introduction to Orchestration and Workflow Pipelines**  
- **Building CI/CD Pipelines with GitHub Actions**  
- **Building Automated Training/Deployment Pipelines**  
- **Dagster with Ray**: Pipelines || Tasks || Dependencies  
- **Best Practices for Orchestrating ML Workflows with Ray and Dagster/Airflow**  

</details>