
# Week 9 Reflection
## Data Source
Junyu Luo, Zekun Li, Jinpeng Wang, and Chin-Yew Lin

ChartOCR: Data Extraction from Charts Images via a Deep Hybrid Framework

https://openaccess.thecvf.com/content/WACV2021/papers/Luo_ChartOCR_Data_Extraction_From_Charts_Images_via_a_Deep_Hybrid_WACV_2021_paper.pdf

## Reflection
For this week, I wanted to focus on visualization papers specific to my proposed final project idea -- gathering data programmatically from visualizations. I stumbled across this paper that proposes a mix of deep-learning and rule-based frameworks to identify arbitrary chart types while other algorithms are focused on specific types of graphs. In that fashion, such an algorithm can be generalized and applied to novel visualizations. 

The algorithm approaches data gathering in three main steps:
1. Information extraction (key points like intersections and corners) --> immediately attempting to predict chart type with softmax
2. Data range extraction via Microsoft OCR (extracting text like axes and legends)
3. Type-specific extraction (based on predicted type, try to find more information specific to bar, pie, and line charts)

Their algorithm was tested on nearly 400k charts from the ExcelChart400k collection, with different evaluation metrics to determine performance on bar, pie, and line charts. Compared to existing methods, ChartOCR's performance is quite stellar -- messing up on some edge cases but generally performing superior to existing work:

![image](https://github.com/akerekon/reflections-research/assets/89589162/47e5756f-d876-41e7-ae69-378d0a89630c)

It is also important to consider efficiency, and ChartOCR also computes answers quickly:

![image](https://github.com/akerekon/reflections-research/assets/89589162/c9fdf21d-9aef-40a2-9569-00256880bffd)

Going into these next few weeks, I want to continue to explore further work in this area so that my group and I can expand on these discoveries and develop a novel algorithm that combines these approaches with GPT models.
