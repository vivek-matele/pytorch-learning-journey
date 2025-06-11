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
