# S5-Assignment-Final

MNIST - Pytorch - Creation of model and getting accuracy of 99.4 in 5 steps by improving model in each step.

Step 1:
Targets:   

           To have a basic skeleton with a good model.
           Params should be less than 15k. 
           Aim to max pool having a look at the data 
           
Results:   
           
           Params - 13590 ,  
           Best Train acc: 99.40 
           Best Test acc : 98.77
           
Analysis:   
            
            Model is fine.  
            Results came well . 
            But there is slight over fitting . 
             And model has to be improved.
            
File Link:https://github.com/mmaruthi/S5-Assignment-Final/blob/master/Step1.ipynb


Step 2 :

Targets:   

        Params should be less than 15k. 
        Use Batch Normalization to improve the model 
        
Results:
        
        Params - 13730 ,    
        Best Train acc: 99.81
        Best Test acc : 99.31
        
Analysis:   

        Results  improved
        But there is over fitting . Has  to reduce it.
        And model has to be taken care to reduce parameters
        
File Link:https://github.com/mmaruthi/S5-Assignment-Final/blob/master/Step2.ipynb

Step 3 :

Targets:   

        Params should be less than 15k. 
        Use Drop out to reduce the overfitting 
        
Results:
   
        Params - 13730 ,     
        Best Train acc: 99.38
        Best Test acc : 99.43
        
Analysis:   

         Overfitting is lost now 
         Accuracy also improved drastically. 
         Tune the model to sustain the accuracy with reduced parameters
         
File Link:https://github.com/mmaruthi/S5-Assignment-Final/blob/master/Step3.ipynb


Step 4 :

Targets:  
         
         Params should be less than 10k.
         Accuracy should be greater than 99.2 
         Use Image augmentation techniques
         
 Results:
     
         Params - 5422 ,     
         Best Train acc: 98.51
         Best Test acc : 99.30
         
  Analysis:  
  
         Model is good and reached an accuracy of 99.30 
         Tried to push accuracy further , but capacity is not enoughTune the model by increasing the capacity to reach target accuracy
         
  File Link:https://github.com/mmaruthi/S5-Assignment-Final/blob/master/step4.ipynb
  
  
  Step 5 : 
  
  Targets:   
       
          Params should be less than 10k. 
          Accuracy should be  greater than or equal to 99.4
          Increase model capacity and use Learning rate with StepLR
          
  Results:
         
         Params - 7758    
         Best Train acc: 98.49
         Best Test acc : 99.40
         
  Analysis:  
         
           Model reached an accuracy of 99.40
           Will try pushing further by using other Image augmentation techniques and cyclic LR etc.
           
  File Link:https://github.com/mmaruthi/S5-Assignment-Final/blob/master/step5.ipynb


