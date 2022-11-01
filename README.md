# esg-scoring

The future of finance goes hand in hand with social responsibility, environmental stewardship and corporate ethics. In order to stay competitive, Financial Services Institutions (FSI) are increasingly disclosing more information about their environmental, social and governance (ESG) performance. By better understanding and quantifying the sustainability and societal impact of any investment in a company or business, FSIs can mitigate reputation risk and maintain the trust with both their clients and shareholders. At Databricks, we increasingly hear from our customers that ESG has become a C-suite priority. This is not solely driven by altruism but also by economics: Higher ESG ratings are generally positively correlated with valuation and profitability while negatively correlated with volatility. In this solution, we offer a novel approach to sustainable finance by combining NLP techniques and news analytics to extract key strategic ESG initiatives and learn companies' commitments to corporate responsibility.


By adapting this Solution Accelerator from Databricks, let me also share some important setup steps, that you can also run it in your environment. 


For running the notebooks, you have to Use this cluster, that's including ML. 
![image](https://user-images.githubusercontent.com/38947100/199015370-d5cab6dd-168f-4d0c-a009-18b4187c811e.png)


Make sure you run the esg_config file first:
![image](https://user-images.githubusercontent.com/38947100/199178108-9b283ae2-0864-4539-8b28-784e0aa087b7.png)



You will need also some additional Libraries installed. Go to Install New, Choose "Maven" and add "com.aamend.spark:spark-gdelt:3.0" 
![image](https://user-images.githubusercontent.com/38947100/199016141-1f186173-3b45-4d9f-a0a7-a7d4e02cadef.png)

The extracted PDFs are used from a public available source called https://www.responsibilityreports.com. 
The comparison between WHAT WAS SAID in a report and WHAT THE NEWS SAYS will be used by using https://www.gdeltproject.org/. 
In other terms, we do not want to solely base our assumptions on companies’ official disclosures but rather on how companies' reputations are perceived in the media, across all 3 environmental, social and governance variables.
