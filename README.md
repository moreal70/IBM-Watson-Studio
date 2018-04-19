
## IBM Watson Studio 사용자 가이드 ##

 * 본 문서는 Machine Learning & Advanced Analytics 플랫폼인 [IBM Watson Studio](https://console.bluemix.net/catalog/services/watson-studio)에 대한 사용자팁를 제공합니다.
 * 각각의 문서는 다양한 경로를 통해 확보된 소스 화일을 IBM Watson Studio 환경에서 수행가능 하도록 수정하였습니다.
 * Watson studio에서 수행하기 위해 필요한 팁과 수정 내용들을 가능하면 screen capture으로 설명하였습니다.
 * 잘못된 부분이나 보완이 필요한 사항은 메일 부탁드립니다. (parkhsu@kr.ibm.com)

![watson data platform](https://github.com/moreal70/IBM-Watson-Studio/raw/master/images/ibm-watson-data-platform.png)

:sunny:*`GITHUB integration process.ipynb`* : Studio에서 개발된 소스 코드를 Github에 업로드 하기 위한 설정 과정입니다.

:umbrella:*`MySQL access with Python.ipynb`* : mysql 을 생성하고 DB 에 접속하여 DDL,DML 등을 수행하는 Python 코드입니다.

:cloud:*`MySQL access with R.ipynb`* : mysql 을 생성하고 DB 에 접속하여 DDL,DML 등을 수행하는 R 코드입니다.

:snowflake:*`MySQL-connection info`* : [Compose for MySQL](https://console.bluemix.net/catalog/services/compose-for-mysql) IBM cloud PaaS 에서 생성하고 이 서비스를 Python 이나 R code 에서 접속하기 위한 connection 정보 흭득 방법입니다. 

:snowman:*`Titinic survival prediction`* : 가장 초보적인 Machine learning 학습을 위한 sample 소스입니다. Watson studio에서 사용하기 위해서 수정이 필요한 작업 내용을 추가하엿습니다. Input 소스 데이터를 IBM object storage에서 가져오는 절차입니다.

:zap:*`Quantum_emoticon.ipynb`* : IBM Q quantum program 으로 'Hello world'에 해당하는 기초 샘플 코드입니다.

:cyclone:*`WML using PMML.ipynb`* : [Watson Machine Learning](https://console.bluemix.net/catalog/services/machine-learning) 서비스를 활용하여 ML model 을 생성,저장,활용하는 과정을 Iris 데이터로 보여줍니다. 

:foggy:*`WML-from kaggle titanic.ipynb`* : ML 초보를 위한 대표 프로그램인 Titanic 생존자 분석 프로그램을 Kaggle에서 folk 하고 수행하는 일련을 절차를 설명했습니다.

:ocean:*`WML-with XGBoost for cancer detection.ipynb`* : [Watson Machine Learning](https://console.bluemix.net/catalog/services/machine-learning) 서비스를 활용하여 ML model 을 생성,저장,활용하는 과정을 cancer data로 보여줍니다

----------

:cat:*`images`* : notebook 이나 R studio 에서 사용하기 위한 image 화일들을 저장하기 위한 directory 입니다. 모든 화일은 URL 을 가지고 reference 되도록 코딩 되어 있습니다.

:dog:*`working`* : 작업용 temporary 폴더입니다.











