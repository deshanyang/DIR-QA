The datasets in this folder was refered as "New Landmark Pairs (NLP) " in the manuscript.

In the .mat file, there are four variables, which are

'landmark_EE' represents the original 300 landmarks from DIRLAB at EE phase
'landmark_dirlab_EI' represents the original 300 landmarks from DIRLAB at EI phase

'landmark_new_EI' represents our improved version of the 300 landmarks at EI phase. Please note that not all landmarks in this variable are different from its original 300 landmarks from DIRLAB. On average, around 200 landmarks per case were different. 

'landmark_changed_idx' should be interpreted with landmark_new_EI, it indicate that in landmark_new_EI, which one is changed from DIRLAB, which one is the same as DIRLAB.





The pdf compared image patches around selected 'landmark_dirlab_EI' and 'landmark_new_EI' in order to demonstrate the improved positional accuracy of 'landmark_new_EI' as compared to 'landmark_dirlab_EI'.

If you would like to use our improved version of 300 landmark pairs for you DIR evaluation, please use 'landmark_EE' and 'landmark_new_EI'.