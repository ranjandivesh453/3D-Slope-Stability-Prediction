FOS Prediction GUI using Hybrid GBM–SMA Model

A graphical user interface (GUI)-based application developed for predicting the Factor of Safety (FOS) of slopes using a Hybrid Gradient Boosting Machine optimized with the Slime Mould Algorithm (GBM–SMA). The application provides a user-friendly platform for entering geotechnical parameters, generating FOS predictions, and exporting prediction results for engineering analysis and decision-making.

Overview

This project provides an interactive GUI for predicting slope stability conditions based on geotechnical and seismic input parameters. The developed hybrid GBM–SMA model was trained using deterministic three-dimensional slope stability analysis data and integrated into a lightweight desktop application using Python Tkinter.

The repository is structured to support:

Easy installation and execution
Cross-platform compatibility
Modular code organization
Future scalability and feature enhancement
Reproducible computational workflow
Features
Interactive graphical user interface for FOS prediction
Manual entry of geotechnical input parameters
Real-time prediction using trained GBM–SMA model
CSV export functionality for prediction results
Export and save functionality
Modular and maintainable architecture
User-friendly navigation and controls
Repository Structure
FOS-GBM-SMA-GUI/
│
├── model/                 # Trained GBM–SMA model (.pkl)
├── outputs/               # Exported prediction results
├── src/                   # GUI source code
├── assets/                # GUI screenshots and resources
├── requirements.txt       # Python dependencies
├── main.py                # Main GUI application
└── README.md              # Project documentation
Installation
Clone the Repository
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
Create Virtual Environment (Optional but Recommended)
python -m venv venv
Activate Environment
Windows
venv\Scripts\activate
macOS/Linux
source venv/bin/activate
Install Required Dependencies
pip install -r requirements.txt
Running the Application

Execute the following command:

python main.py

The graphical user interface will launch automatically.

Dependencies

Typical dependencies used in this project include:

Python 3.9+
Tkinter
NumPy
Pandas
Scikit-learn
Pickle

Install all required libraries using:

pip install -r requirements.txt
Example Workflow
Launch the GUI application.
Enter geotechnical parameters including cohesion (c), friction angle (ϕ), unit weight (γ), pore water pressure ratio (rᵤ), and seismic coefficient (kₑ).
Click the "Predict FOS" button.
View the predicted Factor of Safety (FOS).
Export the prediction results as a CSV file if required.
Screenshots

The developed GUI can support:

Three-dimensional slope stability assessment
Volcanic slope hazard analysis
Geotechnical risk evaluation
Rapid engineering decision support
Machine learning-assisted slope safety prediction
Research and educational applications in geotechnical engineering
Future Improvements
Dark mode support
Cloud deployment
Multi-threaded processing
Additional visualization modules
Export to PDF/Excel reports
Real-time monitoring dashboard
Contributing

Contributions are welcome.

Fork the repository
Create a new branch
Commit your changes
Push to the branch
Submit a pull request
License

This project for research purpose only.

Citation

If you use this repository in your research, please cite:

Kumar, S., Sunkpho, J., Kumar, D.R. and Wipulanusat, W., Slope stability analysis of Mount St. Helens slope using Scoops3D and machine learning.

For questions or collaborations:

Name: Divesh Ranjan Kumar
Email: ranjandivesh453@gmail.com
GitHub: https://github.com/your-username
