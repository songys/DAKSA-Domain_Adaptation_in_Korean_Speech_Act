# DAKSA-Domain-Adaptation-in-Korean-Speech-Act
Cross-Domain Speech Act Adaptation and Analysis


# Annotation Guideline
The annotation guideline ([in Korean is here](https://docs.google.com/document/d/1UapqM8PZBNlVCyBwxUnLqsGmfb6KD9lHzEfjWDqhGHc/edit?usp=sharing)) was elaborately constructed by Youngsook Song and Won Ik Cho, with the great help of Eyoung Ko and Soyoung Jeon (from DeepNatural AI), and Jisu Shim, who helped with the annotation process.


# quick pics

## petition data   

| task_uid | task_name | text | result_0 | result_1 | result_2 | result_3 | result_4 | Major_voting_ko | Major_voting_en | Major_voting |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 65bc30aece41fa08a028f971 | peti-0001 | 스텔라 데이지호에 대한 제안입니다. | 서술 | 제안/요구 | 서술 | 서술 | 서술 | 서술 | statement | 6 |
| 65bc30aece41fa08a028f972 | peti-0002 | 비리제보처를 만들어주세요. | 서술 | 제안/요구 | 제안/요구 | 제안/요구 | 제안/요구 | 제안/요구 | suggestion/request | 7 |
| 65bc30aece41fa08a028f973 | peti-0003 | 공공기관 무조건적인 정규직전환을 반대합니다. | 서술 | 서술 | 제안/요구 | 제안/요구 | 제안/요구 | 제안/요구 | suggestion/request | 7 |
| 65bc30aece41fa08a028f974 | peti-0004 | 제2의 개성공단 | 서술 | 작업불가 | 제안/요구 | 서술 | 작업불가 | 서술 | statement | 6 |
| 65bc30aece41fa08a028f975 | peti-0005 | 보건복지부 부령 제339호중 “특수의료장비 운영에 관한 규칙” 중 불합리한 행정제도·법령·시책 등으로 인하여 권리·이익이 침해되어 시정요구시정을 요구합니다 | 제안/요구 | 제안/요구 | 제안/요구 | 제안/요구 | 제안/요구 | 제안/요구 | suggestion/request | 7 |

## messenger data

| file_id | speaker | result_0 | result_1 | result_2 | result_3 | result_4 | Major_voting_ko | Major_voting_en | Major_voting |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MDRW1900003747.1.1.1 | user_2 | 인사 | 인사 | 인사 | 인사 | 인사 | 인사 | greeting | 3 |
| MDRW1900003747.1.1.2 | user_1 | 인사 | 인사 | 인사 | 인사 | 인사 | 인사 | greeting | 3 |
| MDRW1900003747.1.1.3 | user_1 | 설명 의문 | 설명 의문 | 설명 의문 | 설명 의문 | 설명 의문 | 설명 의문 | wh-question | 8 |
| MDRW1900003747.1.1.4 | user_2 | 서술 | 서술 | 서술 | 서술 | 서술 | 서술 | statement | 6 |
| MDRW1900003747.1.1.5 | user_2 | 설명 의문 | 설명 의문 | 설명 의문 | 설명 의문 | 설명 의문 | 설명 의문 | wh-question | 8 |

Due to the license policy, the [NLTK dataset](https://kli.korean.go.kr/corpus/main/requestMain.do?lang=ko) is not allowed to be released. Therefore, we are releasing the ID. After downloading the data from the NLTK website, please email [me](klanguage1004@gmail.com), and I will send you the full annotation data.    


# data source
 petition data : https://github.com/lovit/petitions_archive
 messenger data : NIKL. Nikl corpora 2020 (v.1.0), 2020. URL https://corpus.korean.go.kr.


# Citation
If you find this dataset useful, please cite the following:
