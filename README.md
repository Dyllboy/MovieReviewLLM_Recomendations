# MovieReviewLLM_Recomendations
A project utilizing Langchain and HuggingFaceHub GoogleFlan-T5-XXL to read movie review pdfs, then summarize and make recommendations based off of them. 

The reviews utilized in the project are provided for context of how the project works and where it is pulling context from.

# HOW TO RUN
If you want to run this project you will need your own HuggingFaceAPI Key. This can be added to the colab environment secrets tab.

The reviews can be uploaded into the files section of colab.
Remove or comment out the mounting code: 'drive.mount('/content/gdrive', force_remount=True)' then change the root_dir path to /content/folder_name_where_you_uploaded_reviews
