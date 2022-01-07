# eclipse_eXbuilder_study_test
공부중
# 이현길

순서

설명

```jsx
	var dm1 = app.lookup("dm1");
	var grp6 = app.lookup("grp6");
	var ds1 = app.lookup("ds1");
	
	dm1.reset();
	grp6.redraw();
	ds1.clearData();
	
	sms1Search();
```

```jsx
//  (맵) 검색하는 곳 == 그룹의인풋==조회영역  초기화
	var dm1 = app.lookup("dm1");
	dm1.reset();
	
// 초기화된 값이 갱신되도록 컨트롤을 포함한 그룹을 redraw()
	var grp6 = app.lookup("grp6");
	grp6.redraw();
	
//	(셋)검색뜨는곳 ==그리드 초기화
	var ds1 = app.lookup("ds1");
	ds1.clearData();
	
	sms1Search();
```
