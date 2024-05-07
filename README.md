# Optimal-Warehouse-Expansion

# Introduction

This report aims to assist a small manufacturing company in **expanding its business capabilities** by suggesting a convenient location or space. The company has identified four alternative options: **A1 (Centre), A2 (Suburb), A3 (Shared), A4 (Extend)**. These alternatives are evaluated based on five different decision criteria: **C1 (Public Transport links), C2 (Parking), C3 (Warehouse), C4 (Security), and C5 (Cost)**. Selecting the best possible alternative requires a strategic methodology based on these business criteria. Making decisions using multiple criteria plays a crucial role in **improving business efficiency**. The biggest challenge in making the right business decisions is to enhance business performance while satisfying the maximum possible criteria.

In this report, I will present and justify the best possible alternative to acquire space using multi-criteria analysis methods such as **Analytic Hierarchy Process (AHP)** and **Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS)**. 

## AHP
AHP decomposes the whole business problem into a hierarchy and determines the weight coefficients by pairwise comparison. With this method, it becomes feasible to combine quantitative and qualitative factors in the decision-making process (Saaty, 1990). We must determine the relative importance of different options over others using the Saaty scale, which is a numerical value with a verbal judgment aligned with it (Saaty, 1990).

## TOPSIS

TOPSIS on the other hand is a useful technique where it ranks different available alternatives based on the Euclidean distance from the Positive Ideal Solution (PIS) or Negative Ideal Solution (NIS). The optimum solution or alternative is the one that has the shortest distance from the PIS and the longest distance from the NIS(Stević et al., 2015).

# Determination of comparison matrix using AHP 

Considering the given business scenario, I have assumed the criteria weights over another in the below manner: -


The weights are assumed in such a way that Warehouse space is of extreme importance and Public transport being the least one. After determining the relative importance of each decision criteria I assumed a number from the Saaty scale based on the judgement and developed a comparison matrix (Figure 2). 

# AHP Methodology

AHP calculations can be carried out using principal eigenvector or geometric mean for qualitative decision criteria.

In 1st step, the sum is calculated for each row of the comparison matrix determined above. Then the summed row is normalised. This method is repeated until the normalised value in consecutive calculations remains the same. 

# Multi-Criteria Decision Making Analysis

The above bar chart clearly shows the relative importance of each criterion over the other.

Similarly, from the 2nd step onwards each decision variable or alternative is evaluated among themselves based on the conditions or scenario given of each criterion until normalised values remain the same as previous calculation. This can be calculated using the principal eigenvector or geometric mean.

![Figure 5: Normalised Decision variable matrix w.r.t Public Transport](Fig/fig5)

![Figure 6: Normalised Decision variable matrix w.r.t Ease of Parking](link_to_image_6)

![Figure 7: Normalised Decision variable matrix w.r.t Warehouse space](link_to_image_7)

![Figure 8: Normalised Decision variable matrix w.r.t Security](link_to_image_8)

![Figure 9: Normalised Decision variable matrix w.r.t Cost](link_to_image_9)

In Figure 9, the cost is a quantitative criterion and a minimizing attribute because a company would always want a minimum purchase cost. So, in this case, I reciprocated the cost of the individual alternative and then normalised the value.

**Result** - In the last step, I combined all the decision variables matrix value w.r.t each criterion and generate a score by multiplying it with individual weights of the criteria determined earlier (as shown in figure-3). We can see that A2(suburb) has the maximum score compared to others and the company should opt for it. Figure-11 clearly shows the score difference through a bar chart.

**Figure 10: Final AHP weights, score**

**Figure 11: Bar chart of AHP result**

**TOPSIS Methodology**

In TOPSIS, I have used the same weights of decision criteria as determined in AHP (Figure-4).  In Step 1, the Saaty scale is used to determine a score for each qualitative attribute and then normalised the decision matrix using the vector normalisation method where Xij is the score of alternative i wrt criterion j.

![Figure 12: Qualitative to Quantitative score](link_to_image_12)

In Step 2, each cell value is divided with the corresponding Rij value to normalise(figure 13).

![Figure 13: Normalised value for each criterion](link_to_image_13)

In Step 3, Multiplied the weights with each normalised value of its corresponding cell (Figure 14).

![Figure 14: Weighted Normalised matrix](link_to_image_14)

In Step 4, I have determined the orientation of the criteria- C1, C2, C3, C4 as maximizing and C5 as minimizing. Then I have identified the Positive Ideal solution(PIS) and Negative Ideal Solution (NIS) for each criteria. PIS in GREEN and NIS in RED (Figure 15).

![Figure 15: PIS & NIS](link_to_image_15)

In Step 5, Calculated the distance between each alternative score and PIS (Vij-Vj*)  of a given criterion (Figure 16). 

![Figure 16: Euclidean distance from PIS](link_to_image_16)

Similarly, Calculated the distance between each alternative score and NIS (Vij-Vj-)  of a given criterion (Figure 17).

![Figure 17: Euclidean distance from NIS](link_to_image_17)

**Result** –  In figure 4, we can see that A2(Suburb)is the best solution as it tends closest to 1 whereas A1(centre) is the worst solution as it tends to be 0. 

**Figure 18: TOPSIS final bar chart**

**Response to Company**

**Technical Details of Result**

I reached the conclusion using the relative importance of the decision criteria as C3 > C2 > C4 > C5 > C1 based on the following assumption:

a)I have assumed C3-Warehouse space to be most important because the company is expanding its business and for them, the main priority is the availability of space where they can store their raw materials, park their forklifts, finish products, waste by-products etc. They need office space, canteens to accommodate more staff. Lengthy conveyor belts are needed to sort the finished products and pack the items in case of the retail or parcel industry.

b)I have considered C2-Parking as the 2nd most effective criteria as the company are expanding their Warehouse capacity they would need more parking space to park their number of Movable trucks such as Box trucks, heavy-duty trucks etc and also facilitate their ease of movements. As the number of staff is increasing, they will need a large area to accommodate a greater number of cars, bikes.

c)C4-Security comes 3rd in the list to minimize the number of thefts and burglary as there might be many valuable raw materials or finished products like mobile phones, car parts, expensive jewellery or apparel etc. They do also need to keep their employees/staff safe at work.

d)C5-Cost comes second last in the list. I think a purchase cost is a one-time investment that can be recovered within a period of time by providing the business with a proper environment to function and earn profits.  Any land or warehouse area purchased will be an asset to a company and will boost its market value in the coming days.

e)C1-Public Transport is the least important criterion. According to me, labour and staff can easily move to the warehouse from the company provided passenger vehicles instead of public transport and can be a benefit for employees/workers. The goods and raw material generally move in and out directly from the warehouse in company-owned vehicles or third part logistical support. 

Resting on the above assumption, I made a comparison matrix using the Saaty scale which further helped me in analysing the given data. MCDM methods like AHP and TOPSIS brought out the optimum solution as A2(Suburb) to acquire space.

**Proposed way forward plan**

A2(Suburb) is the most efficient location to acquire space. We now need to devise a brief implementation plan to carry out the decision. I have divided it into 4 phases:

1. Identifying step by step process to acquire the A2(Suburb). Starting from managing funds, acquiring resources etc. 
2. Communicating between stakeholders such as employees, shareholders, investors, board members etc. and gaining each other confidence.
3. Planned and optimized allocation of tasks to resources. Need to split the task into smaller ones as it will be easy to keep a track of it.
4. Preparing a proper Time framework and associating deadlines to each task and resolving any constraint on the way

One incorrect or mismanaged step during the whole process may lead to economic discomfort and functional imbalances for a company. So, proper implementation of the decision is equally important as identifying an optimum solution.

**Conclusion**

In today’s fast-paced business world there are a lot of factors influencing a decision. The biggest challenge is to handle these constraints on one hand and reaching to an optimum solution on the other hand. MCDM techniques such as AHP, TOPSIS helps to tackle these types of problems where many stakeholders come into the picture to play their part in the whole process. For the given business scenario, A2(Suburb) has risen as a prominent solution align with the assumptions taken.
