# Predicting_Video_Memorability


**********************************************************************************************
FOLDER STRUCTURE:
For Dev-set, I followed same directory structure as provided in gdrive
For test-set, the ground-truth is moved in main directory instead of ground-truth folder.

**********************************************************************************************
Helpful commands for changing directory:
NEW_PATH =r'C:\Users\Gaurav\Desktop\ML PROJECT'
os.chdir(NEW_PATH)

**********************************************************************************************
EXPLORATION WHICH WAS NOT INCLUDED:
Visualatory explorations were already done for the project and seemed repetetive so I did not include them in the main notebook.
I also tried various other models like linear regression and decision trees, but they did not show any significant improvement.
I got better results using Ensemble techniques but including that would not have contributed to this research as many people have already done that. Instead,
I attempted to provide a model which can be used by others in their ensembling techniques.

**********************************************************************************************
WHY NOT USE GOOGLE COLAB:
Since I was not using GPU, and I have a 8-core laptop so I used n_jobs = -1 parameter to run algorithms faster in my laptop.
Also, google colab was getting time-out for long-running algoritms like cross valdiation and learning curves 
