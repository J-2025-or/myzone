---
title: Beginner Python Application
layout: post
post-image: "https://raw.githubusercontent.com/thedevslot/WhatATheme/master/assets/images/SamplePost.png?token=AHMQUEPC4IFADOF5VG4QVN26Z64GG"
description: 빅데이터가 인공지능의 질을 높인다는 인식을 바탕으로, 첫 번째 프로젝트의 윤리적 AI 비전을 기술적으로 뒷받침하기 위한 Python 및 핵심 라이브러리 학습 기록입니다.
tags:
- Python
- Beginner
- BigData
- Pandas
- NumPy
---

**AI의 질을 높이는 빅데이터의 중요성을 인식하고, 첫 번째 프로젝트인 '기계-인간 감정 수용성'에서 제시한 윤리적 AI의 비전을 기술적으로 실현하기 위해 Python 학습을 시작했습니다.** 이 프로젝트는 제가 컴퓨터 공학도로서 Python의 기초를 습득하고, 대용량 데이터 처리에 필수적인 핵심 라이브러리(NumPy, Pandas)를 익혀 빅데이터 분석의 기초를 다진 과정을 기록한 포트폴리오입니다. 단편적인 지식 나열이 아닌, **데이터 처리의 논리적 흐름**을 파악하는 데 중점을 두었습니다.

---

# 🚀 빅데이터 분석을 위한 관문: Python 학습 로드맵

## 📚 1단계: 빅데이터 처리의 기반, 파이썬 기본 구조 이해

### **핵심 목표:** Python이 데이터를 어떻게 저장하고 처리하는지 이해하며, 궁극적으로 빅데이터를 효율적으로 다룰 수 있는 기초 데이터 유형과 제어 흐름을 마스터했습니다. 데이터 처리의 복잡성은 곧 기본적인 문법 구조에서 시작됨을 깨달았습니다.

#### **자료형 예시: 리스트(List)와 딕셔너리(Dictionary)의 활용**

##### 리스트는 순서가 있는 데이터의 묶음이며, **`append()`** 함수를 사용하여 데이터를 추가합니다. 딕셔너리는 **`Key: Value`** 쌍으로 데이터를 관리하며, 효율적인 데이터 접근에 사용됩니다. 이 두 자료형은 빅데이터를 전처리할 때 임시 데이터 저장 및 구조화에 필수적입니다.

###### **코드 스니펫 1: 리스트와 딕셔너리 기본 사용**
```python
# [1] 파이썬의 기본 자료형 학습
my_list = [10, 20, 30]
my_list.append(40) # 리스트에 원소 추가: O(1)의 시간 복잡도로 데이터 끝에 추가됩니다.
print(f"업데이트된 리스트: {my_list}") 

my_dict = {"name": "Alice", "age": 30}
print(f"이름 접근: {my_dict['name']}") # 키를 사용한 데이터 접근

