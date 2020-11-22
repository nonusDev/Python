# Dictionary

> 연관배열 구조를 이용하여 키(key)에 결과 값(value)을 저장하는 해쉬 테이블로 구현된 자료구조



### 정렬

```python
import operator
# 0은 key 값을 뜻함
sorted(dict.items(), key=operator.itemgetter(0))
# 1은 value 값을 뜻함
sorted(dict.items(), key=operator.itemgetter(1))
# reverse를 이용하여 내림차순으로 정렬
sorted(dict.items(), key=operator.itemgetter(1), reverse=True)
# 두 개의 인자 입력 시 첫 번째 인자를 기준으로 정렬 한 후, 같은 값이 있다면 두 번째 인자를 기준으로 정렬
sorted(dict.items(), key=operator.itemgetter(1, 0))
```

