# RAG-Based Document Generation for Student Affairs

This project implements a Retrieval-Augmented Generation (RAG) system to automatically generate various academic-related documents based on user submissions. It streamlines the process of document generation, such as dispensations and assignment letters, ensuring efficiency and accuracy.

## Features
- Automated generation of dispensations and assignment letters based on submitted data.
- Integration with Streamlit for a user-friendly web interface.
- Organized folder structure for easy management of submissions and generated documents.

## Folder Structure

### 1. **Dispen**
- Contains the submitted documents for **dispensation requests**.

### 2. **STD**
- Contains the submitted documents for **faculty assignment letter requests**.

### 3. **surat_tugas**
- Contains the **generated faculty assignment letters** created by the RAG system based on submissions in the `STD` folder.

### 4. **surat_dispen**
- Contains the **generated dispensation letters** created by the RAG system based on submissions in the `Dispen` folder.

### 5. **input**
- A folder containing example submission files to demonstrate the process of document generation.

### 6. **app.py**
- The main application script for running the Streamlit interface. It allows users to:
  - Submit new requests for dispensations or assignment letters.
  - View and download generated documents.

## How to Run
1. **Install Dependencies**
   Ensure you have Python installed, and run the following command to install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Application**
   Start the Streamlit app with:
   ```bash
   streamlit run app.py
   ```

3. **Access the Interface**
   Open your browser and navigate to the URL displayed in the terminal (typically `http://localhost:8501`).

## Usage
- Place your submission documents in the appropriate folders (`Dispen` for dispensation requests and `STD` for assignment letter requests).
- Run the application and upload the documents through the Streamlit interface if needed.
- Generated documents will be saved automatically in the corresponding output folders (`surat_dispen` and `surat_tugas`).

## Example Workflow
1. Submit a document in the `Dispen` folder for a dispensation request.
2. The system processes the submission and generates a dispensation letter, saving it in the `surat_dispen` folder.
3. Similarly, submit a document in the `STD` folder for a faculty assignment letter request.
4. The system generates the assignment letter and saves it in the `surat_tugas` folder.

## Contributing
Feel free to contribute to this project by submitting issues or pull requests. Let’s improve and expand the functionality together!

## License
This project is licensed under the [MIT License](LICENSE).

---

Happy automating! :rocket:
