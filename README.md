# equation-ai-search
Equation Search Engine An Introduction to Ways to Find Artificial Intelligence AI Equations Formulas and Papers

## Introduction 

In this blog, we will give you a brief introduction to an Equation Search Engine DeepNLP Equation Search (http://www.deepnlp.org/search/equation), which is a comprehensive equation search engine to find equations meaning latex code and related papers and technical reports. It covers a wide range of domains, ranging from STEM (Science Technology Engineering and Math) subjects to more quantiative subjects (Finance, Economics) in more advanced level.


## Table of Content

### 1. Search Equations of Artificial Intelligence AI Related Subjects
### 2. Search Equations of Math and Physics Related Subjects
### 3. Search Equations of Finance and Economics Related Subjects

### 1. Search Equations of AI Related Subjects

AI and Machine Learning are fast growing subjects and there are many popular AI models emerging. For beginner or researchers in AI and ML related subjects, you can find the most
comprehensive AI and ML related models such as LLM/AI Agent/Computer Vision/Natural Language related equations in the Equation Search Engine (http://www.deepnlp.org/search/equation). And you can use the below models to search the equations.


AI related Equations

#### Stable Diffusion Models
#### Transfomer Model
#### Proximal Policy Optimization PPO
#### Direct Policy Optimization DPO


Some of the search results will direct you to the detail pages of each equation. You can find the content of the equation, meanings of each terms, related papers and discussions. For example, the equation for AI models optimization technique DPO (Direct Policy Optimization) can be found in http://www.deepnlp.org/equation/direct-policy-optimization-dpo. 
In this detail page, you can find the equation latex of DPO as 


\pi_{r} (y|x) = \frac{1}{Z(x)} \pi_{ref} (y|x) \exp(\frac{1}{\beta} r(x,y) ) ,r(x,y) = \beta \log \frac{\pi_{r} (y|x)}{\pi_{ref} (y|x)} + \beta \log Z(x) ,p^{*}(y_{1} &gt; y_{2} |x) = \frac{1}{1+\exp{(\beta \frac{\pi^{*} (y_{2}|x)}{\pi_{ref} (y_{2}|x)} - \beta \frac{\pi^{*} (y_{1}|x)}{\pi_{ref} (y_{1}|x)}&nbsp; )}} ,\mathcal{L}_{DPO}(\pi_{\theta};\pi_{ref}) = -\mathbb{E}_{(x, y_{w},y_{l}) \sim D } [\log \sigma (\beta \frac{\pi_{\theta} (y_{w}|x)}{\pi_{ref} (y_{w}|x)} - \beta \frac{\pi_{\theta} (y_{l}|x)}{\pi_{ref} (y_{l}|x)} )] ,\nabla \mathcal{L}_{DPO}(\pi_{\theta};\pi_{ref}) = - \beta \mathbb{E}_{(x, y_{w},y_{l}) \sim D } [ \sigma ( \hat{r}_{\theta} (x, y_{l}) - \hat{r}_{\theta} (x, y_{w})) [\nabla_{\theta} \log \pi (y_{w}|x) - \nabla_{\theta} \log \pi (y_{l}|x) ] ] ,\hat{r}_{\theta} (x, y) = \beta \log (\frac{\pi_{\theta} (y|x)}{\pi_{ref} (y|x)})

Then it explains the meaning of each term, such as the loss function L_DPO, the Gradient update of DPO Loss to parameter \theta,  true reward function and Function of updated language model. 


For academic papers, you can also search the equations and find related top AI and Machine Learning conferences, which now covers most of the top AI conferences.

AI Papers from Top Conferences and Journals include 

AI 

ICLR
ICML
NIPS
AAAI

NLP Natural Language Processing

ACL
EMNLP
NAACL

Computer Vision

CVPR
ICCV
ECCV

Data Mining

KDD
CIKM

### Related

http://www.deepnlp.org/search   <br>
http://www.deepnlp.org/search/equation <br>
http://www.deepnlp.org/search/agent <br>
http://www.deepnlp.org/search/robot <br>
http://www.deepnlp.org/search/store <br>
https://equation-ai-search.onrender.com <br>

