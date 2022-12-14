# Facebook Linear Regression

Built single and multiple (Additive and Interaction) Linear Regression Models on the Facebook dataset to derive inferences or conclusions with the hypothesis testing. When the sample size is small, used bootstrapping to approximate the sampling distribution needed to assess the uncertainty of our estimated coefficients and make inferences. The models are deployed using `ggplot` and `plotly`.

## The Facebook Dataset

This dataset is related to posts' critical information on user engagement during 2014 on a Facebook page of a famous cosmetics brand. The original dataset contains 500 observations relative to different classes of posts, and it can be found in [data.world](https://data.world/uci/facebook-metrics/workspace/project-summary?agentid=uci&datasetid=facebook-metrics). After some data cleaning, it ends up with 491 observations. The dataset was firstly analyzed by [Moro et al. (2016)](https://gw2jh3xr2c.search.serialssolutions.com/log?L=GW2JH3XR2C&D=ADALY&J=JOUROFBUSRE&P=Link&PT=EZProxy&A=Predicting+social+media+performance+metrics+and+evaluation+of+the+impact+on+brand+building%3A+A+data+mining+approach&H=d8c19bb47c&U=https%3A%2F%2Fezproxy.library.ubc.ca%2Flogin%3Furl%3Dhttps%3A%2F%2Fwww.sciencedirect.com%2Fscience%2Flink%3Fref_val_fmt%3Dinfo%3Aofi%2Ffmt%3Akev%3Amtx%3Ajournal%26svc_val_fmt%3Dinfo%3Aofi%2Ffmt%3Akev%3Amtx%3Asch_srv%26rfr_dat%3Dsaltver%3A1%26rfr_dat%3Dorigin%3ASERIALSSOL%26ctx_enc%3Dinfo%3Aofi%2Fenc%3AUTF-8%26ctx_ver%3DZ39.88-2004%26rft_id%3Dinfo%3Adoi%2F10.1016%2Fj.jbusres.2016.02.010) in their data mining work to predict the performance of different post metrics, which are also based on the type of post. The original dataset has 17 different continuous and discrete variables. However, in this project, we extracted five variables for `facebook_data`. Details are explained in the notebook or PDF file.


## Plots Examples

#### Comparison of single linear regression model with multiple linear regression using `ggplot`.
![image](https://user-images.githubusercontent.com/82040820/198413622-b7a79755-8012-40cb-a9fb-7cbed102c74e.png)

#### 3-dimensions a regression plan using `plotly`.
![image](https://user-images.githubusercontent.com/82040820/198413290-7429e4d1-9cb8-49e2-a946-75180a3cfa2a.png)
