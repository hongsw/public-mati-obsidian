---
{"dg-publish":true,"permalink":"/garden/obs-tips/obsidian-git-ipad-mac/"}
---


	1. 준비물 
	2. H/W¨
		1. iPad
		2. Mac
		3. BT Keyboard
	3. S/W
		1. iSH on iPad
		2. Obsidian
		3. Obsidian-git plugin
2. 참고 가이드 문서
	1. [링크](https://gist.github.com/DannyQuah/f686c0e43b741468e12515cd79017489)
	2. ```mount -t ios null /mnt/dq/Obsidian```  를 
	3. ```mount -t ios-unsafe null /mnt/dq/Obsidian``` 으로 바꿔서 실행 <mark style="background: #FF5582A6;">ios-unsafe</mark>
3. 주의사항
	1. 폴더 이름 변경은 주의하자! ( 원인 파악중이지 만 한번 꼬임 발생 )
		1. 잘못하면 rebase해야한다. 