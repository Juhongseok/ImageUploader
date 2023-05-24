# ImageUploader

## Infra Architecture
![Architecture5](https://github.com/Juhongseok/ImageUploader/assets/75611167/4e70942f-31a6-4c05-b8e1-6852a635c244)

## 작업일지

|날짜|작업내용|완료 여부|
|:---:|:---:|:---:|
|2023-05-24|VPC, Subnet, Internet Gateway 설정 & EC2, RDS 생성|완료|
|2023-05-25|Github Action 생성|미완|
|2023-05-26, 30~31|프로젝트 진행|미완|

---

### 추가 세부 내용
<details>
<summary>2023-05-24</summary>
<div markdown="1">

  **VPC**: 10.0.0.0/24<br>
  **Public Subnet**: 10.0.0.0/28<br>
  **Private Subnet**: 10.0.0.16/28<br>
  **Public Internet Gateway 생성**<br>
  **Public Routing Table**: <br>
    from 10.0.0.0/24 to local<br>
    from 0.0.0.0/0 to Public Internet Gateway<br>
  **Private Routing Table**: <br>
    from 10.0.0.0/24 to local<br>
  
</div>
</details>
  
