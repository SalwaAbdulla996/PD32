# PD32
Persona Detection using CNN,BERT and GPT Models
#This paper "Improving Persona Detection in Natural Language Processing using Pre-Training on CNN, BERT, and GPT Models " developed by Salwa Abdulla and Suadad Muammar  proposes a novel approach which aims to investigate whether pre-training on CNN, BERT, and GPT can improve the performance of persona detection on two datasets, Person Match on Persona Chat (PMPC) and ROCStories. 

#The PMPC dataset contains dialogues between two speakers, where each speaker assumes a given persona, and the task is to match each speaker with their corresponding persona. The ROCStories dataset comprises fictional stories that describe characters' traits and behaviors. Our approach employs a transformer-based architecture that utilizes external context from the stories to enhance the accuracy of persona detection.


#Our model combined  got the performance of :

		        F1     Bleu 					   F1     Bleu 

CNN 
	ROC-STORIES,PMPC: 0.0801 ,0.000431          ROC-STORIES,PMPC0= 0807,0.00111
GPT
	ROC-STORIES,PMPC: 0.1901 ,0.007131          ROC-STORIES,PMPC0= 1987,0.01111
BERT
	ROC-STORIES,PMPC: 0.1981 ,0.009131          ROC-STORIES,PMPC0= 1997,0.01911

#Download the code from the below link
https://drive.google.com/file/d/1v-1F9d78RhSXcmxm7dHv_KDCpfR_euQX/view?usp=share_link


## Testing the code
unzip the PD32 file and
just Run the interactive.py and watch the output (it may take more than 30 minutes depending on speed of your computer!)
