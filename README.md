Sympto_Scan aims to address the global healthcare challenge of medical misdiagnosis, which has severe consequences for patients. In India alone, there are approximately 52 lakhs cases of medical negligence reported annually, with a 110% increase in recent years according to the National Library of Medicine. These alarming statistics highlight the urgent need for an accurate and reliable medical diagnosis system to prevent such misdiagnosis and ensure patient safety.
The project focuses on developing an effective and accurate symptom-based disease diagnosis system utilizing tree data structure. Sympto_Scan will prompt users to input their symptoms using an initial question set and follow-up questions. Upon completion, it will provide the user with the most likely diagnosis or a list of potential conditions, along with relevant information about each. The goal is to create an intuitive and accurate platform for self-assessment of medical symptoms, aiding users in seeking appropriate medical advice and treatment.

Data Structures used: Trees

**Key Features**

**1)User-Friendly Interface:**
The system offers a simple and interactive console interface for users to input their details and symptoms, making the diagnosis process efficient. Users can seamlessly navigate through the system to obtain accurate diagnosis results.

**2)Patient Information Collection:**
The system collects essential patient details such as name, age, gender, weight, and blood group. This information is crucial for accurate disease diagnosis and medical record management.

**3)Hierarchical Tree Structure:**
The heart of the Disease Diagnosis System lies in its intricate tree structure. It is designed hierarchically, mimicking the decision-making process of healthcare professionals. Here's an overview of how the tree structure works:
 
 **a)Node Structure:** The tree consists of nodes representing medical conditions and decision points.
 
 **b)Root Node:** The root node represents the starting point of the decision-making process.
  
  ![Screenshot 2024-07-06 102133](https://github.com/nandinipathak2005/SYMPTO_SCAN/assets/166193813/7c33757f-9c7c-4bb6-9a5f-ac79528eb814)
 
 **c)Internal Nodes:** Internal nodes evaluate specific conditions or criteria based on patient information.
  
  All of the internal nodes are named as per the symptoms they are referring to.
 
  ![Screenshot 2024-07-06 102730](https://github.com/nandinipathak2005/SYMPTO_SCAN/assets/166193813/c8c5ef7e-77fb-4b9d-b1a1-1e174688ef57)

 **d)Leaf Nodes:** Leaf nodes represent disease diagnoses or outcomes based on the conditions evaluated.
 
**4)Decision Making:**

As patient information is entered, the system traverses the tree, making decisions at each node based on the input data.

**a)Probabilistic Diagnosis:**
    The algorithm calculates probabilities for various diagnoses based on the symptoms and decision path followed in the tree.

**b)Medical Card Generation:**
   
   Upon successful diagnosis, the system generates a medical card containing the diagnosis details and relevant medical information. This medical card serves as a concise summary for healthcare professionals 
   and patients.

**c)Customizable Rules:**
    Healthcare professionals can customize the decision tree rules based on specific medical conditions and diagnostic criteria. This flexibility allows for tailored diagnoses according to varying healthcare 
    scenarios.

**Installation:**

Before running the Disease Diagnosis System, ensure that you have the following prerequisites installed:

1.	Eclipse IDE: Download and install Eclipse IDE from the official website (https://www.eclipse.org/downloads/).

2.	Java Development Kit (JDK): Ensure that you have Java Development Kit (JDK) version 8 or higher installed on your system. Eclipse requires JDK to compile and run Java programs

**Forking the repository:**

1.   On GitHub.com, navigate to SYMPTO_SCAN repository.
https://github.com/nandinipathak2005/SYMPTO_SCAN

2.   In the top-right corner of the page, click Fork.

   ![Screenshot 2024-07-06 103025](https://github.com/nandinipathak2005/SYMPTO_SCAN/assets/166193813/2db9faf3-3c67-40af-8689-9c6b30df4a97)

3.   In the Fork dialog, define the options for your fork.

4.   Select the Fork repository button.

**Cloning your forked repository:**

1.   On GitHub.com, navigate to your fork of the SYMPTO_SCAN repository.

2.   Above the list of files, click  Code.

   ![Screenshot 2024-07-06 103112](https://github.com/nandinipathak2005/SYMPTO_SCAN/assets/166193813/00310f4e-a457-4b2a-8b48-a6bfcf9e0762)

4.   Copy the URL for the repository.

5.   To clone the repository using HTTPS, under "HTTPS", click .

6.   Depending on your system, you’ll use Terminal (with Mac) or Command line (with Windows git bash) to move it to your local directory. 

**For Mac:**

1.   Open Terminal

2.   type CD and specify where you want your cloned directory to be. Then, right-click on the folder in Finder. Select Copy [folder name] and copy the path onto your clipboard. 

3.   Paste the folder path into Terminal. 
     eg:cd directory_path

4. Finally, type Git Clone and paste the URL you copied in GitHub.
     It will look like this, with your GitHub username instead of YOUR-USERNAME:
     eg: git clone https://github.com/YOUR-USERNAME/ SYMPTO_SCAN.git

5. Click Enter.
   
**For Windows:**
1.   Open Git Bash.

2.   Change the current working directory to the location where you want the cloned directory.
          eg: cd directory path

3.   Type git clone, and then paste the URL you copied earlier. It will look like this, with your GitHub username instead of YOUR-USERNAME:
          eg: git clone https://github.com/YOUR-USERNAME/ SYMPTO_SCAN.git

4.   Press Enter. Your local clone will be created.

5.   Wait for Cloning to Finish: Git will download all the files from the repository to your local directory. Wait for the process to complete.
That's it! You have successfully cloned a repository from GitHub to your local machine using Git.

**Import it in Eclipse IDE or any other Java IDE.**

1.   Open your IDE (e.g., Eclipse).
2.   Choose File > Import > Existing Projects into Workspace.
3.	Select the cloned project directory and click Finish.
Run the Application

**Usage**

To use the Disease Diagnosis System, follow these steps:

**For command prompt:**
1.   Compile the program by running javac DiseaseDiagnosis.java
2.   Launch the program by running java DiseaseDiagnosis.
3.   Enter the patient's details as prompted by the user interface.
4.   Follow the on-screen instructions to complete the diagnosis process.
5.   View the diagnosis results and generate medical card for reference.

**For eclipse:**
1.   After importing the project or clone repository
2.   Open DiseaseDiagnosis.java in Eclipse.
3.   Right-click on the file and select Run As > Java Application.
4.   Enter the patient's details as prompted by the user interface.
5.   Follow the on-screen instructions to complete the diagnosis process.
6.   View the diagnosis results and generate medical card for reference.

