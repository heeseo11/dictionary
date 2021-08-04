### 이것저것 이것저것

- 데이터 재구조화
  - pivot()
  - pd.pivot_table()
  - stack()
  - unstack()
  - melt()
  - wide_to_long()
  - pd.crosstab()


#### [colab 참고]

- colab 연결 끊김 방지
```php
  function ClickConnect(){
      console.log("코랩 연결 끊김 방지"); 
      document.querySelector("colab-toolbar-button#connect").click() 
  }
  setInterval(ClickConnect, 60 * 1000)
```

- colab gdrive 연결
```python
  from google.colab import drive
  drive.mount('/content/gdrive')
```
