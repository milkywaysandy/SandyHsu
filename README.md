<center> <h1>歡迎來到許珊綺個人網頁</h1> </center>
<center> <a href="resume_Shan-Chi_Sandy_Hsu.pdf" target="_top">Sandy Hsu's resume（English）</a> 
<a href="https://drive.google.com/file/d/1-FFpPwc2NVN0WzJ0cwsgUZHadlkwB1wS/view?usp=sharing" target="_top">許珊綺 履歷（中文版）</a><br/>
</center>
<center>  Email：organizingwithsandy@gmail.com</center>
<center>  <a href="https://www.linkedin.com/in/sandy-hsu-a2044549/" target="_top">LinkedIn</a></center>
<center>  <a href="https://github.com/milkywaysandy" target="_top">GitHub</a></center>

# Project 代表作
** 電商 AI 服裝推薦系統**  </center>
<br/>
<a href="https://github.com/milkywaysandy/Clothing-Retrieval" target="_top">Link to: Clothing Retrieval Project</a><br/>
<br/>
**Purpose:**<br/>
As a consumer, I found that it is very difficult to find exact clothing articles online due to the limitations of written descriptions and tags. Thus, I tried to use my knowledge of machine learning(CNN) to create an AI system， which aims to help on the shopping experience if adopted by an online merchant. The system works as follows: when a user input a clothing article image into this AI system, the system will retrieve 5 similar clothing images from the adopted merchant database.This clothing retrieval system contains two pre-trained models: a semantic segmentation model & ImageNet. The first model is to isolate the clothing items from the background, while the second model turns the clothing image into feature vectors. Finally, we use closest euclidean distance of the vectors to decide which items are to be presented to the user. Finally, using Flask, Docker to communicate via line bot to create an excellent user experience.<br/>
<br/>
**目的:**<br/>
對于喜歡網購衣服的我，常常因爲文字限制，很難精準的在電商所引裡找到我想要的衣服。所以，我們用卷積神經網路做成一個檢索系統: 當使用者輸入一張衣服照片，我們的系統會從電商商品資料庫檢索出5張類似圖檔。這個系統使用兩個模型，semantic segmentation model & ImageNet。第一個模型旨在去除背景留下衣服。第二個模型旨在轉換影像成爲特徵截取。然後，使用使用者照片跟電商商品資料庫裡最近的歐式距離，來決定最相似的推薦衣服。最後，以line做爲使用者介面。<br/>

<div class="embed-container">
  <iframe
      src="https://user-images.githubusercontent.com/63726744/131056824-9a27cd65-5d5f-436c-827f-77edbe6e3615.mp4{{ include.id }}"
      width="700"
      height="480"
      frameborder="0"
      allowfullscreen="">
  </iframe>
</div>
<br/>

********************************************************************************************************<br/>
** 健身手環專案 - 對手用戶使用分析**  </center><br/>
<a href="https://github.com/milkywaysandy/BellaBeat" target="_top">Link to: Data Analysis & Visualization Project</a><br/>
<br/>
**Purpose:**<br/>
This is a capstone project from Google Data Analytics Professional Certificate. As a data analyst working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the global smart device market.  By focus on BellaBeat Leaf and analyze smart device data to gain insight into how consumers are using their smart devices, these insights will help guide marketing strategy for the company. <br/>
<br/>
**目的:**<br/>
此為 Google 數據分析專業證書之總整專題。作為一名在 Bellabeat 營銷分析師團隊工作的數據分析師，Bellabeat 是一家為女性提供健康產品的高科技製造商。 Bellabeat 是一家成功的小公司，但他們有潛力成為全球智能設備市場中更大參與者。通過專注於 BellaBeat Leaf 並分析智能設備數據以深入了解消費者如何使用他們的智能設備，這些見解將有助於公司的營銷策略。<br/>

<img width="415" alt="number visual graph" src="https://user-images.githubusercontent.com/63726744/188815597-345e0578-bd64-46de-a62e-ed0c6a5c9d06.png">
<img width="406" alt="bar visual graph" src="https://user-images.githubusercontent.com/63726744/188815771-41074dc6-afbc-4ec3-b427-0ea2ffecc2fc.png">


# Coding Skill & Application 程式能力 & 應用程式
- python
- SQL / BigQuery
- R
- Tableau
- MatLab
- Scikit-learn / Tensorflow / Pytorch
- Machine Learning & Deep Learning
- Git

# Work Experience 
- Data scientist/Research Associate - April 2023 ~ present
  - Built a clinical RAG prototype using Gemini embeddings, FAISS, and Streamlit to support Taiwan-FDA drug insert search for physicians and pharmacists; prototype is being evaluated for integration into the NTUH hospital system.
  - Engineered a custom layer from scratch in Python (bypassing LangChain) to benchmark diverse data chunking strategies, optimizing retrieval context across full-text, 150-word token windows, and section-based document parsing with 1800 drug inserts documents.
  - Prioritized clinical explainability and safety guardrails by implementing a top-k retrieval injecting the top 6 highest-scoring text chunks into the LLM context window and displaying the chunks side-by-side as reference based on feasibility feedback from physicians and pharmacists.
  - Built a structured RAG pipeline utilizing SQLite to query and retrieve localized internal QA datasets, passing the structured context to the local LLM to synthesize complex database lookups into coherence answers for medical personnel.
  - Built a localized, air-gapped LLM system using Python, Ollama, and Llama 3.1 8B to support secure EHR retrieval and clinical document analysis.
  - Developed NLP pipelines for ECHO and ECG reports using LLM prompting, JSON schema outputs, NLTK, n-gram analysis, and RegEx to extract structured clinical information.
  - Standardized 170,000 semi-structured ECG records from NTUH, resolving fragmented text fields for downstream database integration and analytics.
  - Built and evaluated 4 clinical classification ML models from scratch using scikit-learn to predict cardiotoxicity/heart failure in lung cancer patients; benchmarked 6 machine learning algorithms and selected Random Forest as the production model based on optimal precision-recall metrics.
  - Led and mentored a data science intern through the end-to-end prototyping lifecycle, delivering a successful stakeholder demo that is currently under technical evaluation for integration into the core NTUH system.
- Career Development - April 2022 ~ March 2023
  - SQL/R/BigQuery/Looker/Excel/Tableau skills: Complete the Google Data Analytics Certificate within the recommended time period. The certificate strengthens the skills of dataset manipulation during the initial stage of the project and increases programming language skills and toolset. 
  - Data visualization/Data Mining: Use R language to complete a self-selected project. Project included data processing, analysis, and visualization - BellaBeat opponent user usage analysis. 
  - Product data analysis: Self-motivated to complete the Hahow course and increased the capability of data analysis to industry standards.

- AI Engineer - Yang-Ming International Smart Healthcare Technologies INC 2021~2022
  - Machine Learning Development: Generated promising results and convinced the team to migrate from Microsoft Azure to in-house Scikit-Learning framework as a financial benefit of the APP
Data analysis & modeling
  - Model Training / Tuning / Optimization: Developed a machine learning model of Two-Class Averaged Perceptron to predict the patients with high blood pressure as an adverse event during hemodialysis
  - Real-Time Simulation: Simulated real-time data stream through the model package with the result of 0.88 as the area under curve, which is the same accuracy as that of the static data model prediction
  - Big Data Processing: Analyze 4,000 treatment sessions, 80,000 time points, 16 types of kidney dialysis machine values, predicted the characteristics of the data in a timely manner, standardize the use of Python, Excel & Google Cloud for the future data cleaning process, and complete the timely predictive test data cleaning independently.
  - Python Skill: Converted the feature engineering of 25 subroutines into python from AWK with pandas and NumPy packages for 84 designed features within two working weeks.
- Data Engineering Immersive (Student) 2020~2021 
  -  Proposed and led a CNN based project on clothing retrieval system: when input a clothing image into the system, it retrieves 5 images with similar attributes from the adopted database
  -  Experienced in data processing and modeling with libraries including pandas, scikit-learn and other statistical/machine learning libraries in Python from Kaggle challenges
  -  Attended Taiwan AI Academy Technical Professional Program for application of Machine Learning (Regression, CNN, DNN, Classification)
  -  Self-taught python, mySQL, Web Scraping in a half year 
  -  Self-taught Machine Learning course by Andrew Ng, Stanford from coursera
  -  Ranked first in AIA Technical Professional Program project competition
  -  Won Best Poster for AIA Technical Professional Program project competition<br/>
- Social Media Strategist & Professional Organizer  2016~2021
  -  Needs Analysis: Researched market trends, collected competitor information, monitored and analyzed data from various social media platforms. Data mining and data analysis from Google Analytics and Facebook Insights, understanding audience preferences, customized posts & blog articles, resulted in a 300% increase in engagement rate during the first three months.
  -  Team Work: Planned and executed the promotional events and the clients’ large projects with an 8-person team. The in-person promotion events successfully exceeded audience capacity.
  -  <a href="https://www.facebook.com/OrganizingWithSandy" target="_top">@OrganizingWithSandy</a>
- Opioid Research Project Assistant/Program Assistant, CE&P - McMaster University 2008~2013
  -  Statistical Knowledge: Performed a full systematic review with meta-analysis for updating a Cancer Care Ontario guideline on Nasopharyngeal cancer.
Big Data Processing: Assisted in the opioid research project. Involved with 3000+ records data resulting in 4 medical peer-reviewed journals。 
  -  Created, designed, maintained over 23 online surveys with 50 plus questions and 100 plus international responses depending on the demand of the research projects Summarized survey results for other research coordinators as references. <br/>Software using: Access & Google Workspace.
  -  Increased responsibilities as program assistant, resulted in job description re-evaluation, and promoted by two salary grades<br/>
- York University Observatory Student Coordinator & Research Assistant 2000~2007 
  - Contributed data management skills by independently creating an Excel database to manipulate and maintain 400+ data sets
  - Promoted to Observatory Coordinator based on exceptional interpersonal skills with colleagues and outstanding communication skills with the public

# 工作經驗
- 台大藥學院 研究專員/資料科學 -	2023/04～目前
  - 使用 Gemini 嵌入模型（embeddings）、FAISS 與 Streamlit 打造臨床檢索增強生成（RAG）原型系統，支援醫師與藥師查詢台灣食藥署（TFDA）仿單。
  - 以 Python 從零開始自主開發客製化架構（不使用 LangChain框架），藉此基準測試（benchmark）多種資料切塊（chunking）策略，並針對 1,800 份藥品仿單進行全文、150 字詞視窗（token windows）及依章節解析之文件處理，進而優化檢索時的上下文內容。
  - 注重臨床可解釋性與安全防護機制，依據醫師與藥師的可行性回饋，實作 Top-k 檢索技術將得分最高的 6 個文本切塊（text chunks）注入大語言模型（LLM）的上下文視窗中，並提供並排對照畫面以供參考。
  - 運用 SQLite 建構結構化 RAG 管線以查詢並檢索在地化的院內內部問答（QA）資料集，並將結構化上下文傳遞給本地端 LLM，將複雜的資料庫查詢轉化為適合醫療人員閱讀的連貫解答。
  - 利用 Python、Ollama 與 Llama 3.1 8B 部署在地化且與外網隔離（air-gapped）的大語言模型系統，以支援具安全性隱私保障的電子病歷（EHR）檢索與臨床文件分析。
  - 運用 LLM 提示詞工程、JSON Schema 輸出格式、NLTK、n-gram 分析及正規表示式（RegEx）開發自然語言處理（NLP）管線，用以分析心臟超音波（ECHO）與心電圖（ECG）報告並萃取出結構化的臨床資訊。
  - 標準化台大醫院（NTUH）170,000 筆半結構化心電圖（ECG）紀錄，解決文字欄位破碎零散的問題，以利後續的資料庫整合與數據分析。
  - 使用 scikit-learn 從零開始建立並評估 4 種臨床機器學習分類模型，用以預測肺癌患者的心臟毒性與心臟衰竭風險；基準測試了 6 種機器學習演算法，並依據最佳的精準率-召回率（Precision-Recall）指標選擇「隨機森林」（Random Forest）作為最終的上線生產模型。
  - 帶領並指導資料科學實習生完成端到端（end-to-end）的原型開發生命週期，並成功向利害關係人進行成果展示（Demo）。
- AI 職業發展進修	-	2022/04～2023/03
  - SQL/BigQuery/Looker/Excel/Tableau 技能：在短於建議學習時程完成 Google Data Analytic Certificate, 強化對專案初期截取資料之技能、增加可使用語言及工具集。
  - 資料挖掘：使用R語言從資料處理、分析、可視化完成自選健身手環專案 - BellaBeat 對手用戶使用分析。
  - 產品數據分析: 自學完成好學校課程， 增加對數據分析之理解能力和對資料敏感性。
- AI 工程師 	-	陽明智慧樂齡國際生醫科技股份有限公司 2021~2022
  - 使用機器學習模型預測血液透析療程中高血壓之不良事件，及時預測模型結果高達AUC 0.88。
  - 規範使用Excel為未來數據清洗流程、獨力完成及時預測測試數據清洗。
  - 優化數據清理策略，作為臨床驗證試驗中ELT數據管線系統的一部分。
  - 於兩個工作週內，將25個特徵工程的子程序轉換為python語言，此為機器學習模型運算中所用之84個設計特徵。
  - 使用scikit-learn框架優化機器學習預測模型
  - 設計包括特徵工程的和機器學習模型的代碼包，為來將使用於APP開發。
- 社群經營 & 整理師 - 效率媽咪生活.com 2016~2021
  - 需求分析：研究市場趨勢、收集競爭對手數據、監控分析來自各社交媒體平台的數據，例Google Analytics 和 Facebook Insights 的數據挖掘和數據分析、了解受眾偏好、客制貼文和部落格文使前三個月的互動率提高300%。
  - 團隊合作：與8人團隊一起策劃促銷活動和客戶的大型工作、完售2日80人見面會/工坊門票。
- 癌症研究行政人員 - McMaster University 2008~2016
  - 統計學知識：獨立完成系統化文獻回顧跟統合分析，用於更新安大略省癌症鼻咽癌治療指南
  - 大數據處理：清洗3000多筆Opioid藥物文獻數據，刊登於四本醫學同行評審期刊，包括JAMA。
  - 創建、設計、維護 23份、各50+題、來自100+國際受試者回饋的線上問卷。<br/>使用Access, Google Workspace
  - 就職第一年內晉升專案助理、職責增加，並晉升了兩個薪級<br/>
- 約克大學天文台研究助理 - York University 2000~2007
  - 建立、操縱 400+筆變星軌道、火星大氣研究資料庫。使用Excel
  - 因良好的人際溝通技巧而晉升天文台統籌

# Education 學歷
- Master of Science in Data Science University of Colorado Boulder, USA.  <br/>
美國 科羅拉多大學波爾得分校 資料科學 碩士
- Google Data Analytics Professional Certificate. <br/>
谷歌專業證書 數據分析師
- Taiwan AI Academy Technical Professional Program, Taiwan. <br/>
台灣人工智慧學校 技術領袖班
- Completed courses of MSc in Health Research Method McMaster University, Canada. <br/>
加拿大 麥克馬斯特大學 臨床研究 碩士肄業
- Bachelor Degree, Specialized Honours in Sociology & Astronomy. York University, Canada.  <br/>
加拿大 約克大學 社會學 & 天文系 學士畢業 

<img img align="left" src="https://user-images.githubusercontent.com/63726744/131054316-d8c43f1c-dc69-4d8e-b5e6-cfb803d81a62.jpg" width="100" height="130">
<br/> 
In my 
spare time, I love to cook, makes food photographs, and play with my two lovely girls.<br/>
休閒時，我喜歡做菜、食物攝影、和慢跑。
