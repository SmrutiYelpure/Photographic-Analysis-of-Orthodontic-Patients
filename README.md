# Photographic Analysis of Orthodontic patients

Traditionally, cephalometric analysis relies heavily on manual tracing of landmarks on X-ray films. This process is time-consuming, prone to human error, and raises concerns about patient exposure to radiation. There is a growing demand for precise dentofacial measurements that traditional methods can no longer fully meet. Our project introduces advanced software tailored for cephalometric measurements directly from patient profile photos, aiming to simplify diagnostics and reduce reliance on X-rays. This innovative approach leverages machine learning, particularly Convolutional Neural Networks (CNNs), to enhance accuracy, efficiency, and patient safety in orthodontic diagnostics.

## Installation Steps

1. **Install VS Code and Set Python Interpreter**
   - Install [VS Code](https://code.visualstudio.com/) from the official website.
   - Ensure the Python extension is installed.
   - Set up the Python interpreter environment properly.

2. **Install Flask**
   - Open a terminal in VS Code and execute the following command to install Flask:
     ```bash
     pip install flask
     ```

3. **Create and Activate a Virtual Environment**
   - Create a virtual environment named `myenv`:
     ```bash
     python -m venv myenv
     ```
   - Activate the virtual environment:
     - On Windows:
       ```bash
       .\myenv\Scripts\Activate
       ```
     - On macOS/Linux:
       ```bash
       source myenv/bin/activate
       ```

4. **Navigate to Your Project Directory**
   - Navigate to your project directory where you plan to develop your application.

5. **Install PyTorch and Related Libraries**
   - If your project requires PyTorch with CUDA 11.3 support, run the following command:
     ```bash
     pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu113
     ```

6. **View Installed Packages**
   - To verify the installation of Flask and PyTorch, list all installed packages:
     ```bash
     pip list
     ```

7. **Restart VS Code and Run Your Program**
   - Restart VS Code to ensure all changes take effect.
   - Run your main application file (e.g., `App.js` or equivalent).

8. **Access Your Application**
   - After running your application, you'll typically find a link like `http://127.0.0.1:5000/` printed in the terminal. Paste this URL into your web browser to access your application.



