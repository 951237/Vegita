### ���� ���� ���� �ΰ����� ����Ʈ����
���� ������ �����ϴ� �ΰ����� ����Ʈ�����Դϴ�.

### �ý��� ������
![image](https://user-images.githubusercontent.com/16822641/44393019-8881e580-a56e-11e8-8c08-f72eb87f1016.png)

### Demo Web Site
![image](https://user-images.githubusercontent.com/16822641/44393034-933c7a80-a56e-11e8-9678-a3a088e7d23f.png)

### ���� ����
* [���û ���� ��� �� ������](https://data.kma.go.kr/climate/StatisticsDivision/selectStatisticsDivision.do?pgmNo=158) : ���û ������ ���� ä�� ���ݿ� ������ ��ġ�� ������ �м��ϱ� ���� �����Ͽ����ϴ�.
* [���� ���� ����](https://www.kamis.or.kr/customer/price/retail/period.do?action=monthly&yyyy=2018&period=10&countycode=&itemcategorycode=200&itemcode=211&kindcode=&productrankcode=&convert_kg_yn=N) : �������� ���� ���� ���� ������ �м��ϱ� ���� �����Ͽ����ϴ�.
* [�ð迭��ġ�Է� ��ġ���� �� ������](https://tykimos.github.io/2017/09/09/Time-series_Numerical_Input_Numerical_Prediction_Model_Recipe/) : �ð迭(Time-Series Analysis) ���� �� �н��ڷ�� �����Ͽ����ϴ�.

### ���� ���� ��ɾ�
```
# �� ��꿡�� �ҽ��ڵ带 �ٿ�ε� �޽��ϴ�.
git clone https://github.com/ndb796/Vegita.git

# ���� ������Ʈ ������ �̵��մϴ�.
cd Vegita

# �ö�ũ �� ���� ������ �̵��մϴ�.
cd "Flask Web Server"

# �� ������ �����մϴ�.
python server.py
```

### ���̽� ������ �н� �� ���� ��ɾ�
```
# ������Ʈ �������� ���̽� ������ �̵��մϴ�.
cd "Python Software"

# ����(Excel) ���Ϸ� �н��� �����մϴ�.
python offline.py

# (�ɼ�) �н��� �����͸� Ȯ���մϴ�.
python "predict test.py"
>> ��� �µ�: -2.7
>> ���� �µ�: -6.6
>> �ְ� �µ�: 2.0
>> ������:  0.1
[2000.2086]

# ���Ŀ� ������ �� ������ �� ������ model ������ �ٿ��ֱ� �ϸ� ����˴ϴ�.
```
