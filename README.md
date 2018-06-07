# Machine-learning-data-analysis
This respo is used for storing all projects in machine learning and data analysis.

### wrangle_act.ipynb / 评估并清洗推特账号WeRateDog的推文
首先通过调用request库来收集所需数据，总计约2355条推文数据（数据类型包括数值、文本、时间型数据），然后调用pandas、numpy和re库对推文数据进行评估、清洗及测试，最后使用matplotlib库对清洗以后的数据进行可视化。总共发现并修正8个质量问题及2个整洁度问题。

### P3_Data_visualization_Prosper_Loan.html / Prosper Loan探索性数据分析及可视化（R）
数据集总共包含114000条数据，83个变量，其中选取了18个变量进行分析。分析过程逐步深入，依次以单变量、双变量及多变量的方式探索能够带来较高利润的交易具备何种特征。最终发现交易利润的高低更多取决于交易规模（即贷款总额），而非贷款利率；职业较好的贷款者的贷款金额往往更高，且更倾向于将贷款用于“享受型”消费。

### [摩拜单车2016年8月上海地区业务增长情况及用户行为分析.twbx](https://public.tableau.com/profile/m0tao0#!/vizhome/20168v2/Story1)
项目分析了摩拜单车2016年8月在上海地区的业务增长情况。同时，分别从骑行距离和时间对比、每周用户活跃时间及每月用户使用服务的总天数三个角度分析了用户行为。最终在Tableau中以故事形式（包含四个故事点）呈现。
