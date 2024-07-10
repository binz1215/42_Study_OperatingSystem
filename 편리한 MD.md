# 마크다운 작성 시 편리함을 위해
1. vscode 사용을 권장드립니다.  
	우측 상단의 `측면 미리보기`를 활용하여 작성한다면 편리합니다!
2. extention 설치  
	추천 extention : markdown all in one, markdown shortcuts  
	단축키를 지정하여 `인라인 코드`, **굵은 글씨** 처리 등을 하면 좋습니다.
3. code snippet 활용  
	토글 및 글자 색 등은 마크다운 문법에 없어 html문법을 사용해야 합니다.  
	매번 태그를 입력하기는 번거로우니 code snippet을 활용하여 단축 명령어로 지정한다면 편합니다.  
<details>
<summary>  Code snippet example  </summary>

``` json

{
	"toggle": {
		"prefix": ["to", "de", "<det"],
		"body": [
			"<details>",
			"<summary>  $1  </summary>",
			"",
			"$2",
			"",
			"</details>"
		],
		"description": "Markdown toggle maker"
	},
	"color_start": {
		"prefix": ["col"],
		"body": [
			"<span style=\"color:yellow\">"
		],
		"description": "color span start part"
	},
	"color_end": {
		"prefix": ["/c"],
		"body": [
			"</span>"
		],
		"description": "color span end part"
	},
}
```

</details>

이상 어려운 부분이 있다면 1. 구글링 2. 동료학습 3. 혜빈 찬스를 적극 애용하시길 바랍니다.
