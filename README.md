# **AI EdTech UX Research Repository**

Welcome to the **AI EdTech UX Research Repository**, a centralized hub for user experience (UX) research, design, and analytics to optimize educational technology tools. This repository integrates AI-driven analytics, design best practices, and real-time insights to create innovative solutions for learners and educators.

## **Overview**
Our mission is to create **user-centric EdTech products** that deliver impactful learning experiences. This repository combines:
- **UX research**: User personas, journey maps, and heuristic evaluations.
- **Real-time analytics**: Maze data, heatmaps, and usability test results.
- **Design assets**: Wireframes, prototypes, and branding guidelines.
- **Kubernetes metrics**: Horizontal Pod Autoscaler (HPA) configurations and resource monitoring.

### **Key Tools and Technologies**
- **Maze**: Real-time UX analytics (heatmaps, path analysis, feedback).
- **Kubernetes Metrics Server**: Monitoring and scaling AI-driven services.
- **Figma/Sketch**: Wireframe and prototype design.
- **Jupyter Notebooks**: Data visualization and insights.

---

## **Repository Structure**

```plaintext
ai-edtech-ux-research/
├── docs/                         # Research and Documentation
│   ├── personas.md               # Detailed user personas
│   ├── journey-maps.md           # User journey maps and workflows
│   ├── research-summary.md       # Summary of Maze/Openfield findings
│   └── accessibility-checklist.md# Accessibility guidelines
├── designs/                      # Design Assets
│   ├── wireframes/               # Low-fidelity wireframes
│   ├── prototypes/               # High-fidelity prototypes
│   ├── branding-guidelines/      # Color, typography, and style guides
│   └── assets/                   # Logos, icons, illustrations
├── tests/                        # Maze Analytics and Test Data
│   ├── reports/                  # Exported Maze analytics reports
│   ├── heatmaps/                 # Heatmaps from Maze tests
│   ├── raw-data/                 # Raw interaction data for analysis
│   └── usability-tests/          # Usability test findings and scripts
├── scripts/                      # Automation and Data Visualization
│   ├── maze-api-fetch.py         # Script to fetch Maze data
│   └── data-visualization.ipynb  # Jupyter notebook for insights
├── metrics/                      # HPA and Kubernetes Metrics
│   ├── metrics-server-config/    # Configs for Kubernetes Metrics Server
│   └── hpa-configs/              # Horizontal Pod Autoscaler configurations
├── components/                   # Modular UI/UX components
│   ├── input-fields/             # Accessible forms and inputs
│   ├── navigation/               # Nav bar, breadcrumbs, etc.
│   └── modals/                   # Reusable modal components
├── workflows/                    # User and development workflows
│   ├── ideation-workshop.md      # Notes from workshops or sessions
│   ├── design-review.md          # Design review process
│   └── ux-testing-schedule.md    # Schedule for testing and iterations
└── LICENSE                       # Licensing information
```

---

## **How to Use This Repository**

### **1. Explore User Research**
- Navigate to the `docs/` folder for user personas, journey maps, and research summaries.
- Refer to the `accessibility-checklist.md` for compliance guidelines.

### **2. Leverage Design Assets**
- Access wireframes and prototypes in the `designs/` directory.
- Review the branding guidelines for consistent design practices.

### **3. Analyze Real-Time Data**
- Explore Maze reports and heatmaps in the `tests/` directory.
- Use the `scripts/maze-api-fetch.py` to automate Maze data retrieval.

### **4. Monitor and Scale Services**
- Use configurations in the `metrics/` folder to set up Kubernetes Metrics Server and HPA for dynamic scaling.

### **5. Collaborate on Workflows**
- Follow the `workflows/` folder for ideation workshops, UX testing schedules, and design reviews.

---

## **Getting Started**

### **Prerequisites**
- **Python 3.8+**: For Maze API scripts and data processing.
- **Jupyter Notebook**: For visualizing analytics.
- **Kubernetes Cluster**: To deploy metrics and HPA configurations.
- **Figma/Sketch**: To access and edit design assets.

### **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-org>/ai-edtech-ux-research.git
   cd ai-edtech-ux-research
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure Maze API in `maze-api-fetch.py`:
   - Add your Maze API key:
     ```python
     API_KEY = 'your-maze-api-key'
     ```

4. Deploy Kubernetes Metrics Server:
   ```bash
   kubectl apply -f metrics/metrics-server-config/
   ```

5. Run the data visualization script:
   ```bash
   jupyter notebook scripts/data-visualization.ipynb
   ```

---

## **Contributing**

We welcome contributions! Please follow the guidelines below:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature-name"`).
4. Push the branch (`git push origin feature-name`).
5. Submit a pull request.

---

## **License**
This repository is licensed under the [MIT License](LICENSE). Feel free to use and adapt our resources with attribution.

---

## **Contact**
For questions or support, contact:
- **Syed Hussain Ather**  
  AI Team Lead  
  [GitHub](https://github.com/HussainAther) | [Email](mailto:shussainather@gmail.com)  

Let’s create impactful, user-centered EdTech solutions together!
