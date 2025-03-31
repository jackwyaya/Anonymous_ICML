# **Experimental Evidence Supporting "Different Neurons Prefer Different Motor Parameters"**

To validate the claim that **"different neurons prefer different motor parameters"**, we conducted an experimental analysis by fitting **neuronal firing rates** with three motor parameters: **speed**, **direction**, and **velocity**. Using **linear regression**, we evaluated the **encoding performance** of each parameter for individual neurons (channels in this experiments). 

Our results provide clear experimental evidence demonstrating that **different neurons exhibit distinct preferences** for specific motor parameters, thereby supporting the motivation behind the proposed method.

---

## ✅ **Experimental Design and Results**

The following figures illustrate the experimental findings:  
![image](https://github.com/user-attachments/assets/37161db4-d012-4ae9-a04b-45c87820459b)  
![image](https://github.com/user-attachments/assets/64044c90-7eff-4dae-a98e-e6dd764ed543)  
![image](https://github.com/user-attachments/assets/9e640a69-54ec-4686-b3b7-866581c110bf)  

---

### **1️⃣ Figure 1: Neuronal Encoding with Different Movement Parameters**

In **Figure 1**, we fitted individual neuronal firing rates using **speed**, **direction**, and **velocity** via linear regression. The results reveal **substantial variability** in the encoding performance across neurons:
- Some neurons exhibit a **stronger correlation with speed**, indicating a higher sensitivity to speed.
- Other neurons show a **greater encoding performance for velocity**, suggesting they are more responsive to the combined effects of speed and direction.
- **Fewer neurons demonstrate a preference for direction**, as indicated by the generally lower encoding performance for this parameter.

---

### **2️⃣ Figure 2: Encoding Performance Distribution**

In **Figure 2**, we evaluated the encoding performance of the three movement parameters across all neurons. The **\( R^2 \)** values, which measure the proportion of variance explained by each parameter, were used to quantify encoding quality:
- **Speed** exhibits higher \( R^2 \) values in a subset of neurons, suggesting that these neurons are more sensitive to speed.
- **Velocity** shows relatively stronger encoding performance in certain neurons, indicating that some neurons prefer the combined influence of speed and direction.
- **Direction**, on the other hand, generally results in lower \( R^2 \) values, suggesting that directional information maybe **less effectively captured** by linear models.

---

### **3️⃣ Figure 3: Preferred Motor Parameters of Individual Neurons**

In **Figure 3**, we identified the **preferred movement parameter** for each neuron by selecting the parameter with the highest \( R^2 \) value. This allowed us to determine which motor feature each neuron encodes most effectively:
- **Many neurons predominantly prefer speed**, indicating that movement magnitude is a key feature for these neurons.
- **A subset of neurons favor velocity**, suggesting they are sensitive to the combined effects of speed and direction.
- **Fewer neurons prefer direction**, highlighting that this parameter is less frequently the most effective feature for individual neurons.

By mapping the **preferred movement parameter** of each neuron, we provide direct experimental evidence that neurons **"Different Neurons Prefer Different Motor Parameters"**

---

## ✅ **Conclusion: Experimental Evidence for Neuronal Preferences**

The experimental results provide evidence supporting the claim that **different neurons prefer different motor parameters**:
- **Encoding performance** varies significantly across neurons when fitted with speed, direction, and velocity.
- Individual neurons exhibit **distinct preferences** for specific motor parameters, as demonstrated by the distribution of their preferred parameters.
- These findings confirm that **neurons specialize in representing different movement features**, validating the motivation behind the proposed approach.

By directly quantifying and visualizing the **neuronal preferences** for specific motion parameters, we substantiate the claim with robust experimental evidence.
