# titles_created_ai
基于星火大模型制作的小红书爆款标题生成器  
## 依赖环境：  
  Python 3.10  
  Streamlit  
  SparkAI SDK  
## 使用指南：
  ### 1.获取星火大模型 API 凭证
  在使用本项目之前，您需要在星火大模型平台注册并获取以下 API 凭证：  
    SPARKAI_APP_ID  
    SPARKAI_API_SECRET  
    SPARKAI_API_KEY  
  ### 2. 运行应用
       streamlit run main.py
在项目目录终端下，运行以下命令启动 Streamlit 应用：  
  ### 3. 使用应用
  在星火API配置部分，输入您的’SPARKAI_APP_ID’、’SPARKAI_API_SECRET’ 和 ‘SPARKAI_API_KEY’。在生成文案 部分，输入您想要生成标题的主题，例如：“秋季穿搭”、“美食推荐等。点击 生成标题 按钮。稍等片刻，生成的五个小红书爆款标题将会显示在页面下方。
