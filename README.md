![TikTok Banner](Images/tiktok_banner.png)

*Can a machine tell the difference between a claim and an opinion at scale?*

## Overview

TikTok's moderation team was drowning in user reports. Every report needed to be reviewed — but not all reports are equal. A user claiming a video contains misinformation is fundamentally different from a user sharing an opinion. Treating them the same wastes moderation resources and slows down the decisions that actually matter.

The goal was to build a machine learning model that could automatically classify user reports as claims or opinions — accurately, at scale, and with high enough recall that genuine claims weren't slipping through undetected.

I worked through the full analytics lifecycle: initial EDA to understand the data, hypothesis testing to validate assumptions, logistic regression to explore feature  relationships, and finally Random Forest and XGBoost models for the classification task itself. Random Forest emerged as the clear winner.

**The result:** 99.21% recall for identifying claims — a highly reliable classification model that reduces manual moderation workload and supports faster, more consistent content decisions at scale.

**Tools:** Python · Random Forest · XGBoost · Scikit-Learn · Tableau · Jupyter Notebook

---

<br>

## Deliverables

**1. Project Workflow**  
[View →](Resources/01_Project_Workflow.md) Structured workflow and key milestones from project kickoff through to final model delivery.

**2. Project Proposal**  
[View →](Resources/02_C1_TikTok_Project_Proposal.pdf) Formal proposal outlining objectives, scope, and approach before analysis began.

**3. Initial EDA**  
[Jupyter Notebook →](Resources/03_C2_Initial_EDA_Jupyter_Notebook.ipynb) First pass at the data — structure, distributions, and early signals that shaped the analytical direction. Accompanied by an [Executive Summary →](https://www.canva.com/design/DAGMDAe1zbM/kuAsDPI0ZO81mV-sPrDGag/view?utm_content=DAGMDAe1zbM&utm_campaign=designshare&utm_medium=link&utm_source=editor)

**4. Full EDA**  
[Jupyter Notebook →](Resources/05_C3_Full_EDA_Jupyter_Notebook.ipynb) Deep exploration of engagement patterns, user behaviour, and key relationships in the data. Accompanied by an [Executive Summary →](https://www.canva.com/design/DAGPAdlUrF0/k7B0179ZnC65CUd3cXjUvw/view?utm_content=DAGPAdlUrF0&utm_campaign=designshare&utm_medium=link&utm_source=editor) and [Tableau Dashboard →](Resources/06_C3_Tableau_Summary_Dashboard.md)

**5. Tableau Summary Dashboard**  
[View →](Resources/06_C3_Tableau_Summary_Dashboard.md) Visual summary of key EDA insights built for stakeholder communication.

**6. Hypothesis Testing**  
[Jupyter Notebook →](Resources/08_C4_Hypothesis_Test_Jupyter_Notebook.ipynb) Two-sample hypothesis test validating assumptions and confirming feature selection decisions before modelling. Accompanied by an [Executive Summary →](https://www.canva.com/design/DAGSZopRy2I/5JjMtMJ5uvX7Xgo5F0RYKw/view?utm_content=DAGSZopRy2I&utm_campaign=designshare&utm_medium=link&utm_source=editor)

**7. Logistic Regression Model**  
[Jupyter Notebook →](Resources/10_C5_Logistic_Regression_Model_Jupyter_Notebook.ipynb) Explored the relationship between video characteristics and user verification status — providing feature insights that informed the final classification model. Accompanied by an [Executive Summary →](https://www.canva.com/design/DAGW4WemkVM/-hJ_t55riU_MqIDAsCJ1DA/view?utm_content=DAGW4WemkVM&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hd43129146c)

**8. Pre-Processed Dataset**  
[Jupyter Notebook →](Resources/12_C6_Pre-Processed_Dataset_Jupyter_Notebook.ipynb) Dataset preparation for machine learning — data quality issues resolved and features engineered for optimal model performance.

**9. Model Development**  
[Jupyter Notebook →](Resources/13_C6_Model_Development_Jupyter_Notebook.ipynb) Built and evaluated Random Forest and XGBoost models for claims classification. Random Forest selected as the final model based on recall performance.

**10. Final Executive Report**  
[View →](https://www.canva.com/design/DAGcjLKpYUE/uwZpIoxtSQCnMpQSjMSyhw/view?utm_content=DAGcjLKpYUE&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=he2b4c17bde) Complete summary of model development, performance results, and recommendations for deploying machine learning to enhance TikTok's content moderation at scale.

---

<br>

> *Note: Team member names used in this workplace scenario are fictional and are not representative of TikTok.*

---

<br>

*Built by [Dane Tipene](https://github.com/DataDaneHQ) · Analytics & Automation Engineer*

***License:*** *All rights reserved. No part of this repository may be reproduced, distributed, or transmitted in any form or by any means without the prior written permission of the owner.*