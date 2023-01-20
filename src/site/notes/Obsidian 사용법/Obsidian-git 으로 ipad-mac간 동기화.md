---
{"dg-publish":true,"permalink":"/obsidian/obsidian-git-ipad-mac/","tags":["gardenEntry"]}
---

# Obsidian-git 으로 ipad-mac간 동기화 하기 
1. 준비물 
	1. H/W
		1. iPad
		2. Mac
		3. BT Keyboard
	2. S/W
		1. iSH on iPad
		2. Obsidian
		3. Obsidian-git plugin
2. 참고 가이드 문서
	1. [링크](https://gist.github.com/DannyQuah/f686c0e43b741468e12515cd79017489)
	2. ```mount -t ios null /mnt/dq/Obsidian```  를 
	3. ```mount -t ios-unsafe null /mnt/dq/Obsidian``` 으로 바꿔서 실행
3. 주의사항
	1. 폴더 이름 변경은 주의하자! ( 원인 파악중이지 만 한번 꼬임 발생 )
		1. 잘못하면 rebase해야한다. 