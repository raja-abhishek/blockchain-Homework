# blockchain-Homework

### Background

This assignment requires building a blockchain-based ledger system with a user-friendly web interface using Streamlit. This ledger should allow to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

#### Streamlit

##### - What is Streamlit?

Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes a powerful data apps can be built and deployed.

##### - Installation 

command to install streamlit: pip install streamlit

##### - Features of Streamlit

- Streamlit runs the python script from top to bottom
- Each time the user interacts the script is a rerun from top to bottom
- Streamlit allows caching for costly operations like loading large datasets
- There are several widgets available in streamlit, like selectbox, checkbox, slider,etc.

#### Steps required to complete this assignment: 

1. Create a Record Data Class
2. Modify the Existing Block Data Class to Store Record Data
3. Add Relevant User Inputs to the Streamlit Interface
4. Test the PyChain Ledger by Storing Records

##### 1. Create a Record Data Class

This step requires defining a new Python data class named Record and giving this new class a formalized data structure that consists of the sender, receiver, and amount attributes.

##### 2. Modify the Existing Block Data Class to Store Record Data

Rename the data attribute in Block class to record, and then set it to use an instance of the new Record class that got created in the previous step. 

##### 3. Add Relevant User Inputs to the Streamlit Interface

Coded additional input areas for the user interface of Streamlit application. Created these input areas to capture the sender, receiver, and amount for each transaction and stored in the Block record. 

##### 4. Test the PyChain Ledger by Storing Records

Tested complete PyChain ledger and user interface by running Streamlit application and storing some mined blocks in PyChain ledger. Then tested the blockchain validation process by using PyChain ledger. To do so, following steps are required:

- In the terminal, navigate to the project folder where this assignment has been coded
- In the terminal, run the Streamlit application by using streamlit run pychain.py.
- Enter values for the sender, receiver, and amount, and then click the Add Block button. Do this several times to store several blocks in the ledger.
- Verify the block contents and hashes in the Streamlit dropdown menu. 
- Test the blockchain validation process by using the web interface. 

#### Streamlit Application Screenshots




#### Sources for Streamlit features

- https://www.analyticsvidhya.com/blog/2021/06/build-web-app-instantly-for-machine-learning-using-streamlit/
- https://docs.streamlit.io/
