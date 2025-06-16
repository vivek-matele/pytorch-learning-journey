"# Daily Learning Log" 
# Daily Learning Log – PyTorch Journey

---

##  2025-06-8

**Topic:** Tensors in PyTorch  
**What I learned:**
- Created 1D and 2D tensors using `torch.tensor()`
- Explored tensor attributes: `shape`, `dtype`, `device`
- Performed basic operations: addition, multiplication, reshaping
- Understood difference between `.view()` and `.reshape()`

**Notebook:** `C:\Users\vivek matele\pytorch-learning-journey\tutorials\Day_1_tensors_in_pytorch.ipynb`  

**Next Goal:** Start with Autograd for automatic differentiation

---

##  2025-06-10

**Topic:** Autograd – Automatic Differentiation  
**What I learned:**
- Track all operations on this tensor so I can compute its gradients   later. `requires_grad=True`
- Used `backward()` to compute gradients
- Explored `.grad` attribute of tensors
- Learned how PyTorch builds dynamic computation graphs
- Understood when to use `with torch.no_grad()`

**Notebook:** `tutorials/Day_2_pytorch_autograd.ipynb`  
**Next Goal:** Learn about Pipeline building 

---

##  2025-06-11

**Topic:** Building training Pipeline for practice
**What I learned:**
- Today, I build normal baseline pipeline in pytorch
- I used object oriented concept to build pipeline
- how to convert numpy arrey in tensor form
- how to build neural network using pytorch
- forward_pass,calculate_loss,backpropogation,updation weights
- evaluation 

**Notebook:** `tutorials/Day_2_pytorch_training_pipeline.ipynb`  
**Next Goal:** Learn about Pipeline building 

---
##  2025-06-12

**Topic:** Building training Pipeline Using NN modules and optim module
**What I learned:**
- Today, I build normal baseline pipeline using NN module and optim module
- I used object oriented concept to build pipeline
- how to convert numpy arrey in tensor form
- how to build neural network using nn module
- forward_pass,calculate_loss,backpropogation,updation weights
- evaluation 

**Notebook:**`C:tutorials\Day_4_pytorch_training_pipeline_using_nn_module.ipynb`  
**Next Goal:** Learn about Data loading

---
##  2025-06-14

**Topic:** Building dataset class and dataloder in pytorch 
**What I learned:**
- Today, I build customdataset class and it inherit builtin Dataset class methods and attributes
- there is 3 method in this class 
- convert x_features and labels into tensor using torch.tensor
- in constructor we calculate length of x_features for creating batch_size
- and then create __getitem__ constructor to fetch data from the dataset
- also created objects of dataloader class 
- i practiced it and apply in small scale project

**Notebook:**`tutorials\Day_5_dataset_and_dataloader_demo.ipynb`  
**Next Goal:** Build ann NN using dataset and dataloader

---

##  2025-06-16

**Topic:** Building ANN model using Dataset  and DataLoader class 
**What I learned:**
- Today, I build ANN nn using customdataset and dataloader class
- project name is  fashion_mnist classification

**Notebook:**`tutorials\Day_6_ann_fashion_mnist_pytorch.ipynb`  
**Next Goal:** 

---
