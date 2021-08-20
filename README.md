# Revolution

## **#1 보건 의료 데이터**


<pre><code>- age: 나이
- sex: 성별
- bmi: BMI지수
- children: 자녀 수
- smoker: 흡연여부
- region: 사는 지역
- charges: 보험료
</code></pre>

#### **데이터 불러오기**
<pre><code>bank_customers = pd.read_csv('https://raw.githubusercontent.com/fintech-data/Revolution/main/data/Bank_customers_data.csv')
</code></pre>

## **#2 계좌 정보 데이터**

<pre><code>- CLIENTNUM: 고객번호
- Attrition_Flag: 현재 상태
- Customer_Age: 고객 연령
- Gender: 결혼여부
- Dependent_count: 부양가족수
- Education_Level: 교육수준
- Marital_Status: 결혼 상태
- Income_Category: 연간 소득액 기준
- Card_Category: 카드 등급
- Months_on_book: 은행거래 기간 (월 단위)
- Total_Relationship_Count: 총 보유계좌
- Months_Inactive_12_mon: 거래내역 없는 거래월 수
- Contacts_Count_12_mon: 거래기간 있는 거래월 수
- Credit_Limit: 신용한도
- Total_Revolving_Bal: 신용카드에서 결제해야 할 평균 금액
- Avg_Open_To_Buy: 추가 결제를 위한 신용한도 승인액
- Total_Amt_Chng_Q4_Q1: 1분기 대비 4분기 카드 거래금액 비율
- Total_Trans_Amt: 12개월 동안의 총 거래금액
- Total_Trans_Ct: 12개월 동안의 총 거래건수
- Total_Ct_Chng_Q4_Q1: 	1분기 대비 4분기 거래건수 비율
</code></pre>

#### **데이터 불러오기**
<pre><code>direct_marketimg = pd.read_csv('https://raw.githubusercontent.com/fintech-data/Revolution/main/data/DirectMarketing.csv')
</code></pre>

## #3. 다이렉트 마케팅 데이터

<pre><code>- Age: 나이
- Gender: 성별
- OwnHome: 주택보유여부(자가/임대)
- Married: 결혼여부
- Location: 집에서 마트까지 거리 (Far : 도보 30분 이상/close : 도보 30분 이내)
- Salary: 연봉
- Children: 자녀수
- History: 회원가입연수 (5년 이상 : high, 2~5년 : Middle, 1년 이내 : Low)
- Mailing: 쇼핑몰 뉴스레터 발송횟수
- **AmountSpent: 연간 쇼핑몰 이용액**
</code></pre>

#### **데이터 불러오기**
<pre><code>insurance = pd.read_csv('https://raw.githubusercontent.com/fintech-data/Revolution/main/data/insurance.csv')
</code></pre>

## **#4 건강보험 및 신용 데이터**

<pre><code>- Agency: 보험 판매점
- Agency Type: 판매점 형태
- Distribution Channel: 판매 채널
- Product Name Claim:  판매 상품 종류
- Duration: 보험기간
- Destination:  여행국가
- Net Sales	: 순마진
- Commision (in value): 수수료
- Gender: 성별
- Age: 나이
</code></pre>

#### **데이터 불러오기**
<pre><code>travel_insurance = pd.read_csv("https://raw.githubusercontent.com/fintech-data/Revolution/main/data/travel%20insurance.csv")
</code></pre>
