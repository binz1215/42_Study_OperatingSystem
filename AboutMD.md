# 챕터 이름
## 마크다운? 어떻게 써야 할까?

줄바꿈을 할 떄는 띄어쓰기 2번 또는 `<br/>`로 띄워야 합니다.
그렇지 않으면 이런식으로 줄바꿈이 되지 않슴다.  
보이시나요? 위쪽 줄 뒤에 띄어쓰기를 두 번 했더니 줄 바꿈이 일어나고 있죠?  
vscode를 열어 마크다운로 쓰인 문서와, 미리보기를 함께 보시길 추천드립니다.



마크다운 형식에서는 아무리 줄을 많이 띄워도 한 줄만 띄워지는 걸로 보입니다.  
하지만
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
`<br/>`이렇게 태그를 이용한다면 여러줄 띄우기가 가능합니다!

> 정리

줄 바꿈을 하고 싶다면 -> `  `띄어쓰기 두번 후 줄 바꾸기  
줄 띄우기를 하고 싶다면 -> 두 줄 이상 바꾸기 or `<br/>`태그 사용하기

<details>
<summary> 토글 접기를 사용하고 싶다면 이렇게 </summary>
와! 정말 신기하다!

```c
main(void)
{
	int a = 3;
	int b = 6;
	if ("user do a + b")
	{
		printf("dude.. turn on your smartphone\n and just use your calculater.");
	}
	else
	{
		printf("of course I know that this code completely incorrect.\n but this is just example. Isn't it?")
	}
}
```

### 표생성
표생성은 조금 많이 어려울지도..  
\- 이거랑, \| 이 두가지를 사용해서 표를 만듭니당.

제목1 | 제목2 | 제목3
-- | -- | --
내용 어쩌구.. | 내용내용 | 내용...|
두번째 내용 | 가나다라 | 마바사

이 표 내용을 마크다운 형식으로 보면  

```
제목1 | 제목2 | 제목3
-- | -- | --
내용 어쩌구.. | 내용내용 | 내용...|
두번째 내용 | 가나다라 | 마바사
```

엉망진창으로 쓰여있지만 어떻게 사용하는 건지는 대충 이해하시리라 믿슴니다!
하지만 당연히 어려움. 당연함. 그렇다면 구글링 ㄱㄱ  
하지만 [여기][r여기]를 참고하면 조금 쉬울 지도?

[r여기]: https://docs.github.com/ko/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables

</details>

사실 노션이랑 많이 비슷해서 사용하기에 어렵지는 않을거라 생각합니다만 표생성, 줄바꾸기, 토글접기, 등등 몇가지가 조금 어려워서 간단하게 적어봤는데 더 어렵게 한 걸지도...  
