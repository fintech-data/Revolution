# Revolution

## **#1 보건 의료 데이터**


<pre><code>- age: 나이
- sex: <str> 성별 
- bmi: <float> BMI지수
- children: <int> 자녀 수
- smoker: <str> 흡연여부
- region: <str> 사는 지역
- charges: <float> 보험료
- age <int> 나이
</code></pre>

#### **데이터 불러오기**
<pre><code>insurance = pd.read_csv('https://raw.githubusercontent.com/fintech-data/Revolution/main/data/insurance.csv')
</code></pre>

## **#2 계좌 정보 데이터**

<pre><code>- CLIENTNUM: <int> 고객번호
- Attrition_Flag: <str> 현재 상태
- Customer_Age: <int> 고객 연령
- Gender: <str> 결혼여부
- Dependent_count: <int> 부양가족수
- Education_Level: <str> 교육수준
- Marital_Status: <str> 결혼 상태
- Income_Category: <str> 연간 소득액 기준
- Card_Category: <str> 카드 등급
- Months_on_book: <int> 은행거래 기간 (월 단위)
- Total_Relationship_Count: <int> 총 보유계좌
- Months_Inactive_12_mon: <int> 거래내역 없는 거래월 수
- Contacts_Count_12_mon: <float> 거래기간 있는 거래월 수
- Credit_Limit: <int> 신용한도
- Total_Revolving_Bal: <int> 신용카드에서 결제해야 할 평균 금액
- Avg_Open_To_Buy: <float> 추가 결제를 위한 신용한도 승인액
- Total_Amt_Chng_Q4_Q1: <float> 1분기 대비 4분기 카드 거래금액 비율
- Total_Trans_Amt: <int> 12개월 동안의 총 거래금액
- Total_Trans_Ct: <int> 12개월 동안의 총 거래건수
- Total_Ct_Chng_Q4_Q1: <float>	1분기 대비 4분기 거래건수 비율
- Avg_Utilization_Ratio : <float> 
</code></pre>

#### **데이터 불러오기**
<pre><code>bank_customers = pd.read_csv('https://raw.githubusercontent.com/fintech-data/Revolution/main/data/Bank_customers_data.csv')
</code></pre>

## #3. 다이렉트 마케팅 데이터

<pre><code>- Age:<int> 나이
- Gender:<str> 성별
- OwnHome:<str> 주택보유여부(자가/임대)
- Married:<str> 결혼여부
- Location:<str> 집에서 마트까지 거리 (Far : 도보 30분 이상/close : 도보 30분 이내)
- Salary:<int> 연봉
- Children:<int> 자녀수
- History:<str> 회원가입연수 (5년 이상 : high, 2~5년 : Middle, 1년 이내 : Low)
- Mailing:<int> 쇼핑몰 뉴스레터 발송횟수
- **AmountSpent:<int> 연간 쇼핑몰 이용액**
</code></pre>

#### **데이터 불러오기**
<pre><code>direct_marketimg = pd.read_csv('https://raw.githubusercontent.com/fintech-data/Revolution/main/data/DirectMarketing.csv')
</code></pre>

## **#4 건강보험 및 신용 데이터**

<pre><code>- Agency:<str> 보험 판매점
- Agency Type:<str> 판매점 형태
- Distribution Channel:<str> 판매 채널
- Product Name Claim:<str>  판매 상품 종류
- Duration:<str> 보험기간
- Destination:<str>  여행국가
- Net Sales:<int> 순마진
- Commision (in value):<float> 수수료
- Gender:<str> 성별
- Age:<int> 나이
</code></pre>

#### **데이터 불러오기**
<pre><code>travel_insurance = pd.read_csv("https://raw.githubusercontent.com/fintech-data/Revolution/main/data/travel%20insurance.csv")
</code></pre>
