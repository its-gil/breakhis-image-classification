# Project - image classification - group 12

# TO-DO

maybe try different image sizes + callbacks + maybe checkpoints (christian)
try integrate reinhardt
different models 

### Preprocessing
1. Unifying (connect reinhard to the main code)
2. Increase contrast
3. Laplace - edge detection

-----
Scaling down the data => save locally (done for binary)  
Splitting the normalization and then join (done by image data generator)  

Batching (??)  

After preprocessing => checkpoint    

Imbalanced dataset => stratify!  


# Questions

### Drop magnification column from the original CSV?

### Q1: What about class computers for training?? Maybe better??
I believe all of our laptop have Intel Iris... So we are better off with Collab's Nvidia I suppose. Or maybe class computers??

### Q2: How to handle the HUGE amount of data?
about 4GB comprimated => about **30 GB** to handle for the whole process... no point in pushing that to the repository ofc.

### Q3: is it a good approach to scale down the data?
loss of information?

### Q4: idea - is it a good approach to uniformize the color of the samples?

# Team members

Christian Deluca, 20241264, 20241264@novaims.unl.pt  
Gabriele Francesco Zazzetta, 20241256, 20241256@novaims.unl.pt   
Michal Wojcik, 20241255, 20121255@novaims.unl.pt    
Simon Schumacher, 20241249, 20241249@novaims.unl.pt    
Virgil Baclanov, 20241247, www.itsgil.com    
