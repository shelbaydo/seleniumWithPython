# seleniumWithPython
simple seleniumWithPythonDemo
1. pip install selenium  -- install python selenium client

2. pip install webdriver-manager -i https://pypi.tuna.tsinghua.edu.cn/simple   --这里使用国内镜像

3. import corresponding drvier : 
         from webdriver_manager.chrome import ChromeDriverManager
         driver = webdriver.Chrome(ChromeDriverManager().install())

4. import necessary package and classes  --- selenium.webdriver,etc 

5. create a webdriver instance -- given the location of webdriver file

6. call corresponding method to request a website and do other operations