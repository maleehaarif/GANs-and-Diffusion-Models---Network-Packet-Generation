# GANs-and-Diffusion-Models---Network-Packet-Generation
**Download the Dataset**
First access the dataset from the link - https://www.unb.ca/cic/datasets/ids-2017.html


Click on PCAPs and download each file and store it in a directory called gan_dataset


**Clone the Repository**
git clone https://github.com/maleehaarif/GANs-and-Diffusion-Models---Network-Packet-Generation.git


**Set Up the Environment**
Ensure you have Python installed (preferably Python 3.7 or later). You can set up a virtual environment for the project:


**Install Required Dependencies**
Install all necessary Python libraries by running:


pip install -r requirements.txt


**Prepare the Dataset**


•	Input Structure: The program expects a directory containing multiple CSV files of network traffic data, which is present in the directory we created called gan_dataset


•	Directory Setup: Ensure your dataset is placed in a directory named gan_dataset within the project root, or update the data_dir parameter in the script if your dataset is stored elsewhere.


**Preprocessing**
The script automatically handles the preprocessing of the data:


•	Data Consolidation: All CSV files within the directory are consolidated into a single dataset.


•	Feature Selection: Benign labels are removed, and the 'Label' column is dropped.


**Run the Program**


The program can be executed using the main script:


python main.py
