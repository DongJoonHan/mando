# mando

## Liazrd 설치
```
pip install lizard
```

## Lizard 실행해서 엑셀파일로 저장 (순환복잡도 10 이상)
```
lizard.exe -C 10 --csv > lizard_result.csv
```

## CLOC 다운로드
[https://github.com/AlDanial/cloc/releases/tag/v1.90](https://github.com/AlDanial/cloc/releases/tag/v1.92)

## CLOC 실행
```
cloc-1.90.exe --by-file --csv . > cloc_result.csv
```

## CPD 실행
100 Token 이상, C++ 을 대상으로 분석, 엑셀에서 확인하기 위해 csv로 출력해서 저장
```
cpd.bat --minimum-tokens 100 --files . --language cpp --format csv > cpd_result.csv
```


// 코드 수정 가정


## CPPChcek 실행
```
"c:\Program Files\Cppcheck\cppcheck.exe" --enable=all --inconclusive --xml --xml-version=2 src 2> cppcheck.xml
```
